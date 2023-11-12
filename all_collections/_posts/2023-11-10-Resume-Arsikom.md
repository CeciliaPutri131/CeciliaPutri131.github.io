---
layout: post
title: Resume Arsikom
date: 2023-11-10
comments: true
---

# BAB 1

## Arsitektur Sistem Komputer

Arsitektur sistem komputer adalah konsep perencanaan dan struktur pengoperasia ndasar sistem komputer. Arsitektur sistem komputer adalah ilmu yang menghubungkan berbagai macam komponen perangkat keras (hardware) untuk menciptakan komputer yang memenuhi kebutuhan operasional, kinerja dan tujuan finansial.

### Jenis-Jenis Arsitektur Sistem Komputer

- Von-Neumann Architecture: Dalam arsitektur ini terdapat bus (bus alamat/busdata/bus kontrol) yang digunakan untuk menjalankan instruksi dan eksekusi kode data. Perangkat input mengambil data atau instruksi dan CPU melakukan satu operasi pada satu waktu, baik mengambil data atau instruksi masuk/keluar dari memori. Setelah operasi selesai, dikirim ke perangkat output. CU dan ALU untuk memproses fungsi-fungsi tersebut terletak di unit pusat CPU.

- Harvard Architecture: Menyimpan instruksi dan data dalam memori terpisah, dan prosesor mengakses memori tersebut melalui bus terpisah. Prosesor terhubungke 'memori instruksi' menggunakan kumpulan alamat dan bus data khusus, dan terhubung ke 'memori data' menggunakan bus alamat dan data yang berbeda.

- Instruction Set Architecture (ISA): Arsitektur ini terdiri dari dua set instruksi, yaitu RISC (Reduced Instruction Set Computer) dan CISC (Complex Instruction Set Computer). Arsitektur ini memungkinkan pengembangan mikroarsitektur dan mengimplementasikan ISA sebagai sistem eksklusif dengan peningkatan efisiensi dan kemampuan untuk menjalankan perangkat lunak pada generasi eksekusi sebelumnya.

- Micro-architecture: Mikroarsitektur bekerja dengan cara tertentu. Ia membaca instruksi dan melakukan decoding yaitu proses mencari data paralel, kemudian memproses instruksi dan menghasilkan output. Arsitektur ini digunakan pada mikroprosesor dan mikrokontroler.

- System Design: Mencakup semua komponen perangkat keras dalam sistem, termasuk pemroses data selain CPU, seperti unit pemrosesan grafis dan akses memori langsung. Juga mencakup memory controller, data path, dan hal-hal lain seperti multiprocessingdan virtualization.

### Struktur dan Fungsi Komputer

<span style="display:block;text-align:center">![alt](https://ceciliaputri131.github.io/assets/img/strukturarsikom.jpg)</span>

- Input Device: Perangkat keras komputer yang berfungsi sebagai alat untuk memasukkan data atau perintah ke dalam komputer. Contoh keyboard, barcodescanner, mouse, mikrofon

- Input Output Port/IO Port: Digunakan untuk menerima ataupun mengirim data keluar sistem.

- Central Processing Unit/CPU: Jika CPU diibaratkan bagian tubuh manusia, maka itu adalah otak. Hardware ini memproses semua input yang diterima ke dalam komputer, sehingga output yang dihasilkan dapat sesuai dengan keinginan orang tersebut. Jika tidak ada CPU komputer tidak dapat memproses data yang diinput sebelumnya.

- Memori: Merupakan media penyimpanan pada komputer. Semua program komputer dan data disimpan di dalam memori.

- Output Device: Perangkat keras komputer yang berfungsi untuk menampilkan keluaran sebagai hasil pengelolaan data. Dapat berupa hardcopy (ke kertas) softcopy (ke monitor) ataupun berupa suara.

- Data Bus: Jalur penghubung alat pada komputer yang digunakan sebagai media dalam proses melewatkan data dalam suatu proses.

- Address Bus: Digunakan untuk menandakan lokasi sumber ataupun tujuan pada proses transfer data.

- Control Bus: Digunakan untuk mensinkronkan proses penerimaan dan pengirimandata.

# BAB 2

## CPU (Central Processing Unit)

CPU adalah otak dari komputer yang bertanggungjawab untuk menjalankan instruksi-instruksi dan mengolah data yang diperintahkan oleh pengguna.

Komponen CPU terdiri dari:

- Control Unit: Untuk mengontrol pengoperasian CPU dan komputer.

- Arithmetic and Logic Unit: Untuk melakukan fumgsi pemrosesan data komputer.

- Register: Menyediakan penyimpanan internal ke CPU.

- CPU Interconnection: Beberapa mekanisme yang menyediakan komunikasi antara unit kontrol, ALU, dan register.


## ALU (Arithmetic Logic Unit) 

ALU (Arithmetic Logic Unit) adalah komponen penting dalam unit pemrosesan pusat (CPU) pada komputer yang bertanggung jawab untuk melakukan operasi aritmatika (seperti penjumlahan,pengurangan, perkalian, dan pembagian) serta operasi logika (seperti AND, OR, XOR,dan NOT) dalam sistem komputer.

### Peran ALU

- Operasi aritmatika: ALU dapat melakukan operasi aritmatika dasar seperti penjumlahan, pengurangan, perkalian, dan pembagian.

- Operasi logika: ALU digunakan untuk memanipulasi data biner atau bit-bit data.

- Operasi bitwise: ALU juga dapat melakukan operasi bitwise pada data. Operasi bitwise memanipulasi bit-bit individu dalam suatu nilai.

- Perbandingan dan pemrosesan data: ALU digunakan untuk membandingkan data dalam CPU.

- Penanganan Overflow dan Carry: ALU bertanggung jawab untuk mendeteksi dan mengatasi situasi overflow (melebihi batas maksimum yang dapat diwakili oleh bit) dalam operasi aritmatika dan carry (nilai yang harus dibawa atau ditambahkan ke bit berikutnya) dalam operasi penjumlahan.

### Komponen ALU

- Register: Register adalah komponen yang digunakan untuk menyimpan sementara data yang akan dioperasikan oleh ALU.

- Pemilih (Multiplexer): Pemilih adalah komponen yang memungkinkan ALU memilih input yang tepat untuk operasi yang akan dilakukan.

- Dekoder: Dekoder mengubah kode operasi yang diberikan menjadi sinyal-sinyal kendali yang diperlukan untuk melakukan operasi yang sesuai.

- Rangkaian Aritmatika: Rangkaian aritmatika dalam ALU melibatkan penjumlahan, pengurangan, perkalian, pembagian, dan operasi aritmatika lainnya.

- Rangkaian Logika: Rangkaian logika dalam ALU melibatkan operasi logika seperti AND, OR, XOR, dan NOT.

- Pembanding (Comparator): Pembanding adalah komponen yang digunakan untuk membandingkan dua nilai dan menghasilkan sinyal yang menunjukkan hasil perbandingan (misalnya, lebih besar, lebih kecil, atau sama).

- Rangkaian Penanganan Overflow dan Carry: Rangkaian ini mendeteksi dan menangani situasi di mana operasi aritmatika menghasilkan overflow (melebihi kapasitas bit) atau carry (nilai yang harus dibawa atau ditambahkan ke bit berikutnya) yang diperlukan dalam operasi penjumlahan.

- Bus Data: Bus data adalah jalur komunikasi yang digunakan untuk mentransfer data antara komponen-komponen dalam ALU, seperti register, pemilih, dan rangkaian aritmatika/logika.

## Register

Register adalah tempat menyimpan instruksi, alamat penyimpanan, atau jenis data apa pun (seperti urutan bit atau karakter individual).

### Operasi Register

- Fetch: digunakan untuk mengambil instruksi yang diberikan oleh pengguna.

- Decode: digunakan untuk menafsirkan instruksi.

- Execute: Operasi Execute dilakukan oleh CPU. Output yang dihasilkan oleh CPU kemudian disimpan ke dalam memori dan setelah itu ditampilkan di layar pengguna.

### Jenis-Jenis Register

- MAR (Memory Address Register): Untuk menyimpan alamat memori dari data dan instruksi.

- MDR (Memory Data Register): Berisi data yang akan disimpan di penyimpanan (misal RAM), atau data setelah diambil dari penyimpanan komputer.

- MBR (Memory Buffer Register): Untuk meyimpan informasi dan data yang dapat dibaca atau ditulis dalam memori komputer.

- PC (Program Counter): Digunakan untuk menunjukkan posisi saat ini dari urutan program dalam sistem komputer.

- Accumulator: Jenis lain dari register CPU yang banyak digunakan untuk menyimpan logika atau hasil sementara.

- Index Register: Register prosesor yang digunakan untuk memodifikasi alamat operan selama menjalankan program.

- Instruction Register: Merupakan jenis lain dari register CPU yang digunakan untuk menyimpan instruksi yang sedang dieksekusi atau yang akan didekodekan.

# BAB 3

## Sejarah Komputer

### Komputer Generasi 1

- Ditemukan pada tahun 1940-1956.

- Menggunakan Vacuum Tube sebagai komponen digital.

- Bahasa yang digunakan bahasamesin(0 dan 1).

- Membutuhkan ruangan yang luas.

### Komputer Generasi 2

- Digunakan antara tahun 1956-1963.

- Menggunakan Transistor sebagai komponen digitalnya.

- Bahasa yang digunakan Bahasa assembly.

- Ukuran tidak sebesar generasi 1.

### Komputer Generasi 3

- Digunakan tahun 1964-1971.

- Menggunakan IC (Integrated Circuits) sebagai komponen digital.

- Ukuran lebih kecil dari generasi 2.

### Komputer Generasi 4

- Digunakan pada tahun 1971-sekarang.

- Menggunakan Mikroprosesor sebagai komponen digital.

- Sudah terdapat layar monitor yang dapat menampilkan GUI.

- Ukuran bervariasi.

### Komputer Generasi Selanjutnya 

- Sekarang dan generasi selanjutnya.

- Berupa cloud computing dan AI.


## Logic Gate

Gerbang logika atau logic gates adalah proses pengolahan input bilangan biner dengan teori matematika boolean.

Logic gate ini direpresentasikan menggunakan tabel kebenaran. Jika memiliki nilai benar (true) akan ditunjukan dengan angka “1”. Sebaliknya, jika memiliki nilai salah (false) akan ditunjukan dengan angka “0”.

<span style="display:block;text-align:center">![alt](https://ceciliaputri131.github.io/assets/img/logicgate[1].jpg)</span>

### Fungsi Gerbang Logika

Gerbang logika memiliki fungsi untuk melakukan fungsi logika dasar untuk
membentuk sirkuit digital yang terintegrasi. Kebanyakan logic gate menggunakan bilangan biner 0 atau 1 bisa juga disebut true atau false. Biasanya terdiri dari dua buah nilai input dan satu nilai output.

### Tabel Kebenaran

Tabel kebenaran adalah tabel yang digunakan untuk melihat nilai kebenaran dari suatu pernyataan. Di sini tabel kebenaran dapat diartikan sebagai table yang berisi kombinasi-kombinasi variable masukan (input) yang menghasilkan keluaran (output) yang logis.

<span style="display:block;text-align:center">![alt](https://ceciliaputri131.github.io/assets/img/tabelkebenaran[1].png)</span>

## Transistor dan Semikonduktor

<span style="display:block;text-align:center">![alt](https://ivanafirmansyah.github.io/assets/img/vacum.png)</span>

<span style="display:block;text-align:center">![alt](https://ceciliaputri131.github.io/assets/img/mikroprosesor[1].jpg)</span>

<span style="display:block;text-align:center">![alt](https://ceciliaputri131.github.io/assets/img/translitor[1].jpg)</span>

# Bab 4

## Memory

Memory adalah perangkat atau sistem yang digunakan untuk menyimpan informasi untuk penggunaan langsung dalam komputer atau perangkat keras komputer dan perangkat elektronik digital yang terkait.

## Jenis Memory

- Memory Read Only (ROM): Tipe memori komputer yang berisi data yang tidak dapat diubah oleh pengguna. Data dalam ROM bersifat tetap dan digunakan untuk menyimpan firmware, instruksi komputer, dan data yang perlu ada selama perangkat hidup.

- Memory Read/Write: Tipe memori komputer yang memungkinkan pengguna untuk membaca (mengambil 
data dari memori) dan menulis (menyimpan atau mengubah data ke dalam memori) sesuai kebutuhan. Memory R/W umumnya digunakan untuk penyimpanan data sementara (seperti RAM) yang memungkinkan komputer untuk bekerja dengan data secara dinamis selama operasi.

- Static Memory: Tipe memori komputer yang dapat menyimpan data tanpa memerlukan daya listrik berkelanjutan dan data yang disimpan bersifat tetap hingga diubah atau dihapus secara sengaja. Ini termasuk tipe memori seperti Static RAM (SRAM) dan non-volatile memory seperti Flash memory.

- Dynamic Memory: Tipe memori yang digunakan untuk penyimpanan data yang dapat dibaca dan ditulis oleh perangkat lunak komputer. Memerlukan penyegaran berulang untuk mempertahankan data dan bersifat volatil, artinya data hilang ketika daya mati. Ini digunakan sebagai memori utama dalam komputer untuk penyimpanan sementara data yang aktif saat komputer beroperasi.

- Volatile: Suatu jenis memori atau data yang dapat hilang atau terhapus ketika daya listrik diputuskan atau perangkat dimatikan. Dengan kata lain, data dalam memori volatil akan lenyap saat daya mati. Contoh utama dari memori volatil adalah RAM (RandomAccess Memory) dalam komputer, yang kehilangan data yang tersimpan saat komputer dimatikan atau direstart.

- Non-volatile: Suatu komponen atau memori untuk menjaga data atau informasi yang tersimpan bahkan ketika daya listrik dimatikan. Data yang disimpan dalam media non-volatile akan tetap ada dan dapat diakses setelah komputer dimatikan atau restart.

## Perkembangan Memory

<span style="display:block;text-align:center">![alt](https://ivanafirmansyah.github.io/assets/img/memory.png)</span>

## Cara Kerja Memory

Cara kerja memori di komputer melibatkan proses pembacaan dan penulisan data. Ketika komputer memerlukan data atau instruksi, ia membaca data tersebut dari media penyimpanan yang sesuai ke RAM untuk digunakan dalam operasi saat ini. Data dapat ditulis kembali ke media penyimpanan jika ada perubahan dalam data tersebut.

## Cara Optimalisasi Memory

- Pembersihan Aplikasi dan Proses yang Tidak Diperlukan.

- Pengelolaan Cache.

- Virtual Memory.

- Meningkatkan RAM.

- Optimasi Penggunaan Browser.

- Mengelola Startup Aplikasi.

- Menggunakan Software Optimalisasi Memori.

- Menghapus File Sementara dan Sampah.

- Mengaktifkan Trim (untuk SSD).

- Pemantauan Penggunaan Memori.

# BAB 5

## Data

Data adalah fakta-fakta, angka, informasi, atau rekaman yang digunakan sebagai dasar untuk pengambilan keputusan, analisis, penelitian, atau tujuan lainnya. Data dapat berupa berbagai jenis, seperti teks, angka, gambar, audio, atau video, dan dapat mewakili berbagai jenis informasi.

## Data pada Komputer

### Data Numerik

Data Numerik merupakan data yang berupa angka maupun bilangan, bisa dalam bentuk integer, float dan sebagainya.

#### Sistem Decimal 

Sistem desimal merupakan sistem bilangan yang digunakan sehari-hari. Desimal memiliki base atau radix 10.

Desimal terdiri dari angka: 0,1,2,3,4,5,6,7,8,9.

#### Sistem Biner 

Sistem biner merupakan system bilangan yang terdiri dari angka 0 dan 1. Sistem biner memiliki base atau radix 2.

- 1 = 0001

- 8 = 1000

#### Integers

Integers atau bilangan bulat merupakan bilangan yang terdiri dari nilai positif, negatif dan bukan berupa pecahan/desimal. Pada pemrograman integers akan dinotasikan sebagai int dengan 8 bit data.

Contoh bilangan bulat adalah = –5, 0, 8.

#### Bilangan Real 

Bilangan real adalah bilangan yang terdapat pecahan atau desimal. Contoh dari bilangan real adalah 3.14, -0.05, dan sebagainya. Pada bahasa pemrograman bilang real di notasikan sebagai float dan double.

#### Bilangan Cacah 

Bilangan cacah adalah bilang bulat tanpa nilai negatif.

### Data Non Numerik 

Data Non Numerik adalah data yang bukan berupa angka maupun bilangan. Contohnya adalah data teks, gambar dan sebagainya.

#### Text

Data teks pada komputer mengacu pada cara teks atau informasi berbasis teks direpresentasikan, disimpan, dan dikelola dalam sistem komputer. Representasi ini mencakup cara karakter, kata, kalimat, dan dokumen dalam bentuk teks direpresentasikan dalam format biner yang dapat dipahami dan diolah oleh komputer.

Metode representasi data teks pada komputer

- Character Encoding: Character encoding adalah metode dasar untuk merepresentasikan karakter teks dalam bentuk kode numerik. Setiap karakter (termasuk huruf, angka, dan simbol) diberikan kode numerik yang unik.

- Plain Text: Teks mentah atau plain text adalah representasi dasar teks di komputer. Ini adalah urutan karakter yang direpresentasikan menggunakan karakter encoding tertentu, seperti ASCII atau UTF-8. Teks mentah tidak memiliki pemformatan khusus dan tidak mengandung tag atau markup.

- Markup Languages: Markup languages seperti HTML (Hypertext Markup Language) dan XML (Extensible Markup Language) digunakan untuk merepresentasikan teks bersama dengan tag yang memberikan instruksi untuk pemformatan dan tampilan. Markup languages memungkinkan teks untuk dimunculkan dalam berbagai cara di web dan aplikasi.

- Word Processing Formats: Format dokumen pengolah kata seperti DOCX (Microsoft Word), ODT (OpenDocument Text), dan RTF (Rich Text Format) digunakan untuk merepresentasikan teks dengan pemformatan lanjutan, seperti huruf tebal, miring, dan daftar.

- Plain Text Files: Teks mentah sering disimpan dalam file berformat .txt atau .csv. Ini adalah format dasar yang hanya berisi teks tanpa format atau struktur tambahan.

#### Image

Representasi Citra Digital, semua gambar yang bisa disimpan/diolah pada komputer/piranti digital disebut dengan citra digital. Citra digital tersusun dari elemen-elemen terkecil yang disebut Pixel (picture element). Banyaknya pixel pada sebuah citra disebut dengan Resolusi. Biasanya resolusi dinyatakan dalam 2 cara, yaitu: dimensi panjang x lebar, misal: 800×600,1024×768, dll; Banyaknya pixel, misal: 2 Mega Pixel, 5 Mega Pixel, dll. 

Format bmp (bitmap) adalah format citra yang langsung memetakan intensitas RGB ke media penyimpanan dengan rincian setiap pixel:

- Red (R) : 8 bit , 0‐255

- Green (G): 8 bit , 0‐255

- Blue (B): 8 bit , 0‐255

Sehingga, 1 pixel citra dengan format bmp memerlukan alokasi sebesar 24 bit (3 Byte). 

Format lain dari citra antara lain: jpg, gif, png, dsb. Umumnya memiliki ukuran yang lebih kecil dari bmp untuk citra yang sama. Hal ini disebabkan format selain bmp merupakan format yang telah mengalami kompresi.

# BAB 6

## Bahasa Pemrograman

Bahasa pemrograman adalah sebuah bahasa yang digunakan untuk menulis atau menyusun kode yang dapat diterjemahkan oleh komputer menjadi instruksi-instruksi yang dapat dieksekusi. Hal ini sama saja dengan menjadikan Bahasa pemrograman sebagai cara yang bisa dipahami oleh komputer.

Bahasa pemrograman ada beberapa jenis antara lain : bahasa tingkat rendah, bahasa mesin, bahasa tingkat menengah dan bahasa tingkat tinggi.

### Fungsi Bahasa Pemrograman

- Memudahkan komunikasi antara komputer dan pengguna.

- Membuat aplikasi yang kompleks.

- Membuat kode reusable.

- Mempercepat pengembangan software.

- Membuat komputer melakukan banyak tugas yang berbeda.

### Bahasa Mesin/Bahasa Assembly

Bahasa mesin adalah bentuk Bahasa pemrograman yang paling rendah dalam hal tingkat abstraksi. Bahasa mesin menggambarkan instruksi dalam kode biner yang secara langsung dapat dieksekusi oleh komputer. Setiap bahasa mesin terkait erat dengan arsitektur perangkat keras tertentu.

### Bahasa Tingkat Rendah 

Bahasa ini memberikan control yang lebih langsung atas perangkat keras komputer. Instruksi lebih dekat dengan bahasa mesin, tetapi lebih mudah dipahami oleh manusia. Contoh: C dan C++.

### Bahasa Tingkat Menengah

Bahasa ini menawarkan tingkat abstraksi yang lebih tinggi dibandingkan bahasa tingkat rendah. Biasanya, lebih mudah untuk memahami dan digunakan untuk mengembangkan perangkat lunak sistem. Contoh: Ada, Rust.

### Bahasa Tingkat Tinggi

Bahasa pemrograman yang sangat jauh dari bahasa mesin atau bahasa assembly adalah bahasa pemrograman tingkat tinggi atau high-level language. Bahasa ini sangat mudah dipahami oleh manusia dan lebih banyak digunakan untuk aplikasi web, aplikasi mobile, atau aplikasi data science. Contoh: Python, Ruby, atau JavaScript.

# BAB 7

## Translator

Translator adalah program atau perangkat lunak yang mengubah kode sumber dari satu bahasa pemrograman ke bahasa pemrograman yang lain dengan tujuan untuk portabilitas, optimisasi, atau integrasi. Ada 2 jenis translator utama pada bahsa pemrograman, yaitu Compiler dan Interpreter.

### Compiler

Compiler adalah jenis translator yang menerjemahkan seluruh kode sumber dalam 1x proses ke dalam bahasa mesin atau kode antara (intermediate code). Compiler menghasilkan file biner atau kode antara yang dapat dieksekusi secara langsung oleh komputer. Contoh bahasa yang menggunakan compiler adalh C, C++, dan Ada.

#### Fase Pada Compiler

##### Fase Analisis

- Lexical analyzer berfungsi untuk membagi program dalam bentuk “token”.

- Syntax analyzerI berfungsi untuk mengenali “kalimat” dalam program menggunakan sintaks bahasa.

- Semantic analyzer berfungsi untuk memeriksa semantik statis dari setiap konstruksi.

- Intermediate code generator  berfungsi untuk menghasilkan kode “abstrak”.

##### Fase Sintesis

- Code optimizer  berfungsi untuk mengoptimasi kode abstrak yang dihasilkan intermediate code generator.

- Code generator berfungsi untuk menerjemahkan kode dari intermediate code generator  menjadi instruksi mesin yang spesifik.

### Interpreter 

Interpreter adalah jenis translator yang membaca dan mengeksekusi kode sumber baris demi baris saat program berjalan. Ini berarti kode sumber tidak diterjemahkan ke dalam bahasa mesin atau kode antara sebelum dieksekusi. Contoh bahasa yang menggunakan interpreter adalah Python, JavaScript, dan Ruby.

### Compiler VS Interpreter

<span style="display:block;text-align:center">![alt](https://ivanafirmansyah.github.io/assets/img/interpreter.png)</span>

## Linker

Linker bertugas untuk menggabungkan berbagai library external dengan object file untuk menghasilkan sebuah program.

<span style="display:block;text-align:center">![alt](https://ceciliaputri131.github.io/assets/img/linker[1].jpg)</span>

Sekian rangkuman materi Arsikom, apabila ada kritik dan saran silahkan berikan di kolom komentar.☺️

<span style="display:block;text-align:center">![alt](https://ceciliaputri131.github.io/assets/img/memeresume[1].jpg)</span>
