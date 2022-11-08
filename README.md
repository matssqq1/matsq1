#include <iostream>
#include <math.h>
 
int main( )
{
  setlocale(LC_ALL, "Russian");
 
  double m1;
 
  std::cout << "Введите массу первого тела: ";
  std::cin >> m1;
 
  double m2;
 
  std::cout << "Введите массу второго тела: ";
  std::cin >> m2;
 
  double r;
 
  std::cout << "Введите расстояние между телами: ";
  std::cin >> r;
 
  const double g = 6.67 * pow(10, -11);
  
  std::cout << "Сила притяжения между телами равна " 
            << g * m1 * m2 / (r * r)
            << std::endl;
 
  return 0;
}
