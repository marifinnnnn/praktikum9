# NAMA : Muhammad Arifin
# NIM : 312210330
# KELAS : TI.22.A3


# Praktikum 9

<b>Menjelaskan latihan yang kemarin</b>
# Pertama

<img width="528" alt="1" src="https://user-images.githubusercontent.com/115518274/208434696-b9c90d91-c659-4612-85b0-9af4c81dd52c.png">


- Berikut adalah fungsi yang mengubah mengubah suhu suhu dari derajat Kelvin ke derajat Fahrenheit. Karena nol derajat Kelvin sedingin yang didapat. Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback...AssertionError artinya terjadi error pada pernyataan assert.

# kedua
<img width="536" alt="2" src="https://user-images.githubusercontent.com/115518274/208436061-6ce2a11f-717e-4306-b208-0033ef1112aa.png">

- contoh ini membuka file, menulis konten di file, dan keluar tidak ada masalah, Ini menghasilkan hasil berikut

Written content in the file successfully

Dan kenapa hasilnya begitu? karena else akan dijalankan ketika try adalah True

# ketiga
<img width="530" alt="3" src="https://user-images.githubusercontent.com/115518274/208436744-1d40520a-9e7f-406f-9680-451e9d649888.png">


- Mengapa muncul error?

<b>Error: can't find file or read data</b>

r adalah read - Membuka file untuk membaca, error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya `fh = open("testfile", "r")` tambahkan `print(fh.readline())` dan `fh.write` dihapus. Setelah dijalankan, `try` dan `else` ditampilkan

# keempat
<img width="537" alt="4" src="https://user-images.githubusercontent.com/115518274/208437786-a8057fde-79e5-4f94-a2d6-a8cc122a0238.png">


- Menghasilkan output:

<b>Error: can't find file or read data</b>

Ini bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan

# kelima
<img width="474" alt="5" src="https://user-images.githubusercontent.com/115518274/208439043-e413afcf-dc33-4e4a-a50a-be737ae4f744.png">


- ketika dijalankan, maka muncul error. Hapus #!/usr/bin/python dan di except ValueError, Argument: ganti koma dengan as seperti except ValueError as Argument:agar tidak error. Jika dijalankan akan muncul error lagi

The argument does not contain numbers invalid literal for int() with base 10: 'xyz'

kenapa? karena parameter def temp_convert harus mengandung angka

# penjelasan keenam
<img width="470" alt="6" src="https://user-images.githubusercontent.com/115518274/208439539-330ca21c-02f4-4f18-b80f-458195f45d53.png">


- Jika dijalankan muncul <b>SyntaxError</b> artinya ada kesalahan sintaks. Pada raise "Invalid level!", level ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1
