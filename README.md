# MUESTRA_PALABRAS_ROSARIOLGTZ
#include <iostream>
#include <string>

int main()
{
  
  std::string palabra1;
  std::cout << "Introduzca la primer palabra: ";
  getline (std::cin, palabra1);
  std::string palabra2;
  std::cout << "Introduzca la segunda palabra: ";
  getline (std::cin,palabra2);
  std::string palabra3;
  std::cout << "Introduzca la tercer palabra: ";
  getline (std::cin,palabra3);
  std::cout << "Las palabras son: " << palabra1 << ","<< palabra2 << "," << palabra3 <<"\n";
  std::cout << "la primer palabra es: " << palabra1 << "\n";
  std::cout << "la segunda palabra es: " << palabra2 << "\n";
  std::cout << "la tercera palabra es: " << palabra3 << "\n";
}
