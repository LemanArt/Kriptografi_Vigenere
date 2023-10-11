# Kriptografi_Vigenere
- Nama : Leman
- NIM  : 312110148
- Kelas : TI.21.C1

## Langkah-langkah Implementasi
1. Enkripsi Vigenère Cipher
   Kode menggunakan enkripsi Vigenère Cipher untuk mengenkripsi kata sandi sebelum menyimpannya. Berikut adalah fungsi-fungsi utama untuk enkripsi dan dekripsi menggunakan Vigenère Cipher:
     - vigenere_encrypt(plain_text, key): Ini adalah fungsi yang mengenkripsi kata sandi. Proses enkripsi dilakukan dengan menggeser setiap karakter dalam kata sandi sesuai dengan karakter dalam kunci. Geseran dihitung berdasarkan alfabet, dan hasilnya adalah kata sandi terenkripsi.
     - vigenere_decrypt(encrypted_text, key): Ini adalah fungsi yang mendekripsi kata sandi yang telah dienkripsi sebelumnya. Dalam proses dekripsi, geseran dibalikkan untuk mengembalikan kata sandi ke bentuk aslinya.

2. Simpan Informasi Login
   Informasi login seperti username dan kata sandi terenkripsi disimpan dalam file teks. Saya menggunakan pernyataan with open() untuk menulis informasi ini ke dalam file login_info.txt.
4. Verifikasi Saat Masuk
   Saat pengguna mencoba masuk, kode akan meminta input username dan kata sandi. Kemudian, kode akan mendekripsi kata sandi yang dimasukkan dan membandingkannya dengan kata sandi yang telah dienkripsi sebelumnya. Jika kata sandi cocok, pengguna akan diizinkan masuk; jika tidak, akses akan ditolak.
<br><br>
Berikut adalah hasil Program saat di run <br>
![image](https://github.com/LemanArt/Kriptografi_Vigenere/assets/92553676/36f2047e-6e2d-4ea0-81f0-c6eb24770160)
