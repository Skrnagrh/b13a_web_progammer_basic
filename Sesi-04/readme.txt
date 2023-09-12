catatan :

algoritma kelulusan : cek nilai

variabel nama : wajib input > arif
variabel nilai mahasiswa : wajib input number > 80 ABC (diinput huruf)

logic :

//pseudocode
//deklarasi dan assign
read and save nama, nilai, result 
//logic and condition
compute checking nilai
//assign result
save result
//output (console)
show result

//kode menggunakan javascript
var nama = "Sukron"
var nilai = 80
var result
if (nilai >= 60) result = "lulus"
else result = "tidak lulus"
console.log("Data Keterangan : "+result)

//unit testing

langkah pertama > version 1.0
1. jika nilai >= 60 maka "keterangan : lulus"
2. jika nilai < 60 maka "keterangan : tidak lulus"

langkah kedua > version 2.0
1. jika nilai >= 60 && <= 100 maka "keterangan : lulus"
    > diluar inputan > 100 (101) > "keterangan : data tidak sesuai"
2. jika nilai >= 0 && < 60 maka "keterangan : tidak lulus"
    > disaat diinput -1 maka "keterangan : data tidak sesuai"

langkah ketiga > version 3.0
1. jika nilai >= 60 && <= 100 maka "keterangan : lulus"
    > diluar inputan > 100 (101) > "keterangan : data tidak sesuai"
2. jika nilai >= 0 && < 60 maka "keterangan : tidak lulus"
    > disaat diinput -1 maka "keterangan : data tidak sesuai"
3. jika inputan nilai bukan bertipe integer (number) maka "keterangan : data tidak sesuai"