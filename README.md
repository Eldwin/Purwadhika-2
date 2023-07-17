# Purwadhika-2
Project Capstone 2 
## Data Supermarket Customers
https://drive.google.com/drive/folders/1WodnBbuYTvsF0-6HTuQABQ0KCS31lqbK

# Latar Belakang
Sebuah Supermarket, ingin merekrut *data scientist*. Supermarket ini sudah memiliki banyak customer tetapi hanya sebagian saja yang sering berbelanja kembali.

# Data Cleansing
Secara umum, kita bisa melihat bahwa:

* Dataset Supermarket Customers memiliki 29 kolom dan 2.240 baris.
* Kolom ID memiliki error input '\n', akan kita perbaiki.
* Kolom Income memiliki data kosong sebanyak 24. Data kosong pada kolom tersebut diwakili dengan data NaN.
* Pada Kolom Income terdapat anomali inputan yang dimana nilai maksimal dari data Income adalah 666.666, kemungkinan ini adalah kesalahan input data jadi akan kita hapus
* Kolom Z_CostContact dan Z_Revenue tidak ada di penjelasan pdf dan hanya terdapat 1 value saja sehingga kita asumsikan kedua kolom tersebut tidak digunakan sehingga bisa dihapus saja
* Kolom Education penulisan 2n Cycle kita ubah menjadi Master
* Kolom Marital Status, terdapat Alone, Absurd, dan YOLO yang akan kita gabungkan menjadi Single dan status Together akan kita ubah menjadi Married. Sehingga hasil akhir dari kolom Martial hanya ada 4 opsi yaitu : Single, Married, Divorced, Widow
* Kolom Year_Birth ada 3 inputan berisi 1893,1899,1900. Dimana artinya kemungkinan ada kesalahan input saat pendaftaran customer. Hal ini akan kita lihat lagi kedepannya akankah berpengaruh terhadap data yang kita olah (opsional)
