# Optimasi Produksi dengan Linear Programming

Program ini menggunakan metode Linear Programming (LP) untuk menyelesaikan masalah optimasi produksi.

## Fungsi Objektif: 
Maksimalkan:
Z = 40x + 30y  
(untuk diubah menjadi masalah minimisasi: Min Z = -40x -30y)

## Kendala (Constraints):
- 2x + y ≤ 100  
- x + y ≤ 80  
- x ≥ 0, y ≥ 0

## Solusi Output
- x = 20  
- y = 60  
- Nilai maksimum Z = 2600

## Tools & Library
- Python 3.12+
- Library: `scipy.optimize.linprog`

## Cara Menjalankan
1. Pastikan Python dan scipy sudah terinstall:
```
pip install scipy
```
2. Jalankan file Python:
```
python fungsi_lp.py
```

## Author
Repository oleh: [errynavanila](https://github.com/errynavanila)
