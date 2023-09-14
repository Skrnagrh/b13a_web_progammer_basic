1. judul algoritma (done)
    > heading / paragraf / yg lainnya
    > menghitung luas dan keliling lingkaran
2. inputan menghitung luas dan keliling lingkaran
    > deklarasi variabel dan assign data
3. kalkulasi
    > proses > assign result
4. output
    > alert / console / by html

1. flow / alur / narasi (wajib)
2. pseudocode (wajib)
3. koding (optional)
4. optimize / custom  (optional)

=======================================

//pseudocode
//deklarasi dan assign
read and save nama, nilai, result 
//logic and condition
compute checking nilai
//assign result
save result
//output (console)
show result 

## Menghitung Luas dan Keliling Lingkaran

### Alur Aplikasi
1. Pengguna membuka halaman web.
2. Pengguna melihat judul halaman "Menghitung Luas dan Keliling Lingkaran" dan deskripsi.
3. Pengguna melihat label "Masukkan panjang jari-jari (r) lingkaran:" diikuti oleh kotak input untuk memasukkan panjang jari-jari.
4. Pengguna memasukkan nilai panjang jari-jari ke dalam kotak input.
5. Pengguna mengklik tombol "Hitung."
6. Aplikasi menjalankan fungsi `hitungLuasDanKeliling()`.
7. Fungsi `hitungLuasDanKeliling()` mengambil nilai panjang jari-jari dari input, menghitung luas dan keliling lingkaran, dan menampilkan hasilnya di bawah tombol "Hitung."
8. Hasil perhitungan luas dan keliling lingkaran ditampilkan dalam format yang sesuai.
9. Pengguna dapat mengulangi langkah 4-8 dengan memasukkan nilai panjang jari-jari yang berbeda.

### Pseudo Code

```plaintext
1. Buat fungsi hitungLuasDanKeliling():
2.    Ambil nilai panjang jari-jari dari elemen dengan id "radius" dan simpan dalam variabel radius (konversi ke float).
3.    Hitung luas lingkaran dengan rumus: luas = π * radius * radius.
4.    Hitung keliling lingkaran dengan rumus: keliling = 2 * π * radius.
5.    Buat variabel result dengan format: "Luas lingkaran adalah: luas, Keliling lingkaran adalah: keliling".
6.    Set innerHTML dari elemen dengan id "result" menjadi nilai result.
7. Akhir fungsi hitungLuasDanKeliling.

8. Saat tombol "Hitung" diklik:
9.    Jalankan fungsi hitungLuasDanKeliling().
```