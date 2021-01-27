# soal-ujian
Kerjakan soal berikut dengan menggunakan logic bahasa program yang dikuasai (diutamakan javascript).
Masukan jawaban kalian ke repository di GitHub,lalu share URL repository tersebut ke alamat email upttik.ut.ac.id@gmail.com

#Logic dan Programming
1.Buatlah program yang dapat menentukan grade dari suatu masukan angka ,dengan kriteria sebagai berikut: 
    -jika angka lebih besar atau sama dengan 90,maka output adalah huruf A
	  -jika angka diantara 80 dan 89,maka output adalah huruf B
	  -jika angka diantara 70 dan 79,maka output adalah huruf C
	  -jika angka diantara 60 dan 69,maka output adalah huruf D
	  -jika angka lebih kecil dari pada 59,maka output adalah huruf E

Example

Grade(40) // output E
Grade(82) // output B
Grade(90) // output A


2.Buatlah  program fungsi untuk menentukan suatu bilangan merupakan bilangan ganjil atau genap.

Oddeven(8) // output genap
Oddeven(3) // ooutput ganjil


3.Buatlah program untuk menetukan nilai maksimum,minimum,dan rata-rata dari 100 deretan angka acak

Max(deretan angka) //contoh output nilai maksimal 10
Min(deretan angka) // contoh output nilai minimal 2
Average(deretan angka) // contoh output nilai rata-rata 8


4.Buatlah program untuk menentukan sustu kata atau kalimat merupakan palindrom atau bukan.

Palindrome(“testset”) //output true
Palindrome(“Do geese see God”)// output true
Palindrome(“Hello World”)output false


5.Buatlah program yang memiliki dua input berupa tahun. Output dari fungsi tersebut adalah list dari tahun-tahun kabisat diantara dua input tahun tersebut.

leepYear(1600,2020)

// output 2004 adalah tahun kabisat  
// output 2008 adalah tahun kabisat
// output 2012 adalah tahun kabisat
// output 1900 adalah bukan tahun kabisat
// output 2100 adalah bukan tahun kabisat
// output 1600 adalah tahun kabisat
// output 2000 adalah tahun kabisat
// output 2009 adalah bukan tahun kabisat

6.Buatlah program untuk membalikkan semua kata-kata yang terdapat dalam kalimat .

Reverse(“warta niaga”)
// output again atraw

7.Buatlah program untuk menghilangkan data ganda dari JSON berikut ini

[“Slawi”,”Bengkulu”,”Mamuju”,”Medan”,”Bontang”,”Timika”,”Slawi”,”Banjarmasin”,”Mamuju”,”Solo”,”Palembang”,”Banjarmasin”]

#Databasedi database ada tabel registrasi matakuliah dengan isian berikut
   +--------+----------+
   |  mhsid |  matkul  |
   +--------+----------+
   |   1    |    A     |
   +--------+----------+
   |   1    |    B     |
   +--------+----------+
   |   2    |    A     |
   +--------+----------+
   |   2    |    c     |
   +--------+----------+

buatlah queri yang menampilkan rekap jumlah matakuliah yg diregistrasikan 
   +------+-----+-----+
   |   A  |  B  |  C  |
   +------+-----+-----+
   |   2  |  1  |  1  |
   +------+-----+-----+
   
