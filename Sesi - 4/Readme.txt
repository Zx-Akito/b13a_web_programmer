catatan :

algoritma kelulusan : cek nilai

variabel nama : wajib input > arif
variabel nilai mahasiswa : wajib input number > 80 ABC (diinput huruf)

logic :

langkah pertama > version 1.0
1. jika nilai >= 60 maka "keterangan : lulus"
2. jika nilai < 60 maka "keterangan : tidak lulus"

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
var nama = "arif"
var nilai = 80
var result
if (nilai >= 60) result = "lulus"
else result = "tidak lulus"
console.log("Data Keterangan : "+result)

//unit testing

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

=====================================================================================================

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

// Cara Penghitung
1. Pertama mendeklarasikan variabel
    - rasio keliling / Phi = 3.14 atau 22/7
    - j = 7
    - hasil_luas
    - hasil_keliling
2. Hitung luas
    Phi * j * j
    3.14 * 7 * 7
3. Hitung keliling
    2 * Phi * j
    2 * 3.14 * 7
4. Hasil / output
    - hasil_luas = 153.86
    - hasil_keliling = 43.96

// Flow
1. Pertama definisikan Phi adalah 3.14
2. lalu masukkan berapa nilai jari - jari nya
3. untuk menghitung luas maka Phi x jari-jari x jari-jari
4. untuk menghitung keliling yaitu 2 x Phi x jari-jari
5. cetak hasil luas & keliling

// Pseudocode
read and save Phi, jari-jari, result 
compute menghitung hasil
save result
show result
