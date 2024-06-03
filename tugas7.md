## Tugas-7
### code cpp
```
#include <iostream>
using namespace std;

// Kelas Kalkulator dengan metode tambah, kurang, kali, dan bagi
class Kalkulator {
public:
    int tambah(int a, int b) {
        return a + b;
    }

    int kurang(int a, int b) {
        return a - b;
    }

    int kali(int a, int b) {
        return a * b;
    }

    double bagi(int a, int b) {
        return (double) a / b;
    }
};

// Kelas Penghitung dengan metode luasPersegi dan kelilingPersegi
class Penghitung {
public:
    int luasPersegi(int panjang, int lebar) {
        return panjang * lebar;
    }

    int kelilingPersegi(int panjang, int lebar) {
        return 2 * (panjang + lebar);
    }
};

int main() {
    // Membuat objek dari kelas Kalkulator dan Penghitung
    Kalkulator kalkulator;
    Penghitung penghitung;

    // Melakukan perhitungan
    int hasilTambah = kalkulator.tambah(5, 3);
    int hasilKurang = kalkulator.kurang(5, 3);
    int hasilKali = kalkulator.kali(5, 3);
    double hasilBagi = kalkulator.bagi(5, 3);
    int luasPersegi = penghitung.luasPersegi(5, 3);
    int kelilingPersegi = penghitung.kelilingPersegi(5, 3);

    // Menampilkan hasil
    cout << "5 + 3 = " << hasilTambah << endl;
    cout << "5 - 3 = " << hasilKurang << endl;
    cout << "5 * 3 = " << hasilKali << endl;
    cout << "5 / 3 = " << hasilBagi << endl;
    cout << "Luas persegi dengan panjang = 5 dan lebar = 3 adalah " << luasPersegi << endl;
    cout << "Keliling persegi dengan panjang = 5 dan lebar = 3 adalah " << kelilingPersegi << endl;

    return 0;
}



```
## Capute Hasil Running
![image](https://github.com/alyanrni25/Tugas-7/assets/156888432/a1f81b64-8b17-41a7-9240-ed92007ac502)
