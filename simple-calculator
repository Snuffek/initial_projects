#include <iostream>

double num1;
double num2;
char op;

int main(){
std::cout << "************************************\n";
std::cout << "**           Kalkulator           **\n";
std::cout << "************************************\n";

std::cout << "Wprowadz pierwsza liczbe: ";
std::cin >> num1;

std::cout << "Wprowadz druga liczbe: ";
std::cin >> num2;

std::cout << "Wybierz typ dzialania ( +, -, *, / ): ";
std::cin >> op;

switch(op)
{
   case '+':
   std::cout << num1 << " + " << num2 << " = " << (num1 + num2)<< '\n';
   break;

   case '-':
   std::cout << num1 << " - " << num2 << " = " << (num1 - num2)<< '\n';
   break;

   case '*':
   std::cout << num1 << " * " << num2 << " = " << (num1 * num2)<< '\n';
   break;

   case '/':
   if (num2 != 0.0)
   std::cout << num1 << " / " << num2 << " = " << (num1 / num2)<< '\n';
   else
   std::cout << "Nie dzielimy przez 0";
   break;

   default:
   std::cout << op << " jest nieprawidlowym typem dzialania\n";
}

  return 0;

}

