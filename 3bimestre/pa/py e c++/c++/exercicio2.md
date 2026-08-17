```



int main() {





    int valor1;

    int valor2;



    std::cout << "Digite o primeiro valor: ";

    std::cin >> valor1;



    std::cout << "Digite o segundo valor: ";
    std::cin >> valor2;



  

    int soma = valor1 + valor2;

    int subtracao = valor1 - valor2;

    int multiplicacao = valor1 \* valor2;

 

    int divisao = 0;

    if (valor2 != 0) {

    divisao = valor1 / valor2;
  }





    std::cout << "Soma: " << soma << std::endl;

    std::cout << "Multiplicacao: " << multiplicacao << std::endl;

    std::cout << "Divisao: " << divisao << std::endl;





   return 0;

}

```