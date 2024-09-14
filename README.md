Muhammad Nabil Fitriansyah Boernama

Kirchoff

# Tic Tac Toe in C++

Ini adalah implementasi sederhana permainan Tic Tac Toe klasik menggunakan C++. Program ini memungkinkan dua pemain untuk bermain Tic Tac Toe melalui antarmuka berbasis teks.

## Fitur

- Papan permainan 3x3
- Permainan untuk dua pemain (X dan O)
- Validasi input pemain
- Deteksi kemenangan dan hasil seri otomatis
- Tampilan papan yang jelas setelah setiap giliran

## Cara Menjalankan

1. Pastikan Anda memiliki compiler C++ yang terinstal di sistem Anda.
2. Kompilasi program dengan menjalankan:
   ```
   g++ tic_tac_toe.cpp -o tic_tac_toe
   ```
3. Jalankan program yang telah dikompilasi:
   ```
   ./tic_tac_toe
   ```
4. Ikuti instruksi di layar untuk memasukkan langkah Anda.

## Cara Bermain

- Pemain secara bergantian memasukkan koordinat (baris dan kolom) untuk menempatkan simbol mereka ('X' atau 'O').
- Koordinat dimulai dari 0 hingga 2 untuk baris dan kolom.
- Permainan berakhir ketika satu pemain membentuk garis lurus (horizontal, vertikal, atau diagonal) atau ketika papan penuh (hasil seri)
