#include <iostream>

using namespace std;

int main()
{
 //инициализация указателля на целочисленное значение
 int *a = new int(50);
 //переменной b присваивается значение хранящееся по адресу а 
 
 int b = *a;
cout << "adress \t *a\t b\n";
cout << a << "\t" << *a << "\t" << b << endl;
*a = 100;
 
    return 0;
}


adress   *a      b
0x563e4cc71eb0  50      50
