# Portugol exercicios paginas 21/22
## Exercicio 1
### Codigo Portugol:
```
inteiro ano

leia(ano)

se ((ano % 4 == 0 e ano % 100 != 0) ou (ano % 400 == 0)) {
   escreval(ano, " é bissexto")
}
senao {
   escreval(ano, " não é bissexto")
}
``` 

#### Entrada:
O programa recebe um número inteiro digitado pelo usuário, representando um ano.

#### Processamento:
O programa verifica se o ano é bissexto. Para isso, ele testa se o ano é divisível por 4 e não por 100, ou se é divisível por 400.

#### Saída:
O programa mostra o ano digitado e diz se ele é bissexto ou não.

#### Explicação:
Nem todo ano divisível por 4 é bissexto, porque os anos divisíveis por 100 não são considerados. Entretanto, se o ano também for divisível por 400, ele volta a ser bissexto.
