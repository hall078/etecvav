\#include <iostream>



int main() {





&#x20;   int valor1;

&#x20;   int valor2;



&#x20;   std::cout << "Digite o primeiro valor: ";

&#x20;   std::cin >> valor1;



&#x20;   std::cout << "Digite o segundo valor: ";

&#x20;   std::cin >> valor2;



&#x20;   

&#x20;   int soma = valor1 + valor2;

&#x20;   int subtracao = valor1 - valor2;

&#x20;   int multiplicacao = valor1 \* valor2;

&#x20;   

&#x20;  

&#x20;   int divisao = 0;

&#x20;   if (valor2 != 0) {

&#x20;       divisao = valor1 / valor2;

&#x20;   }



&#x20; 

&#x20;   std::cout << "Soma: " << soma << std::endl;

&#x20;   std::cout << "Subtracao: " << subtracao << std::endl;

&#x20;   std::cout << "Multiplicacao: " << multiplicacao << std::endl;

&#x20;   std::cout << "Divisao: " << divisao << std::endl;





&#x20;   return 0;

}

