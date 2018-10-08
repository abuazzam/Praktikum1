# Praktikum1

## latihan1.cpp: Program menghitung Luas segitiga

*Alur algoritma*
1. mendeklarasikan variable `int A, T` sebagai variable input dan `float L` sebagai variable hasil
2. mengisi nilai variable input dengan nilai tertentu, misal: `A = 5` dan `T = 7`
3. menghitung luas dengan rumus `L = A * T / 2.0`, penjelasan: pembagian bilangan bulan dengan bilangan pecahan `2.0` akan menghasilkan bilangan pecahan
4. mencetak hasilnya kelayar. `cout << L << endl;`

*berikut code lengkapnya:*

```c++
#include<iostream>

int main() {
   int A, T;
   float L;
   
   A = 5;
   T = 7;
   
   L = A * T / 2.0;
   
   std::cout << "Program Menghitung Luas Segitia" << std::endl;
   std::cout << "Alas segitiga = " << A << std::endl;
   std::cout << "Tinggi segita = " << T << std::endl; 
   std::cout << "Luas segitiga adalah = " << L << std::endl;

}
```



## latihan2.cpp: progra,...





