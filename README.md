# Tugas Metastro 2024
# Sistem Pakar Diagnosa Penyakit Tanaman Padi Berbasis WEB Dengan Forward dan Backward Chaining - By: gustiawanadi

## Screenshot Akun GitHub
![Screenshot Akun GitHub](https://github.com/RizqiAbdan/TugasMetastro/blob/main/Cuplikan%20layar%202024-09-25%20194342.png)

## Project Pembahasan: [Sistem Pakar Diagnosa Penyakit Tanaman Padi Berbasis WEB Dengan Forward dan Backward Chaining]

### Screenshot Project
![Screenshot Project](https://github.com/RizqiAbdan/TugasMetastro/blob/main/Cuplikan%20layar%202024-09-25%20193956.png)

### Deskripsi Project
[Sistem pakar adalah sistem yang menggunakan pengetahuan manusia yang terekam 
dalam komputer untuk memecahkan persoalan yang biasanya memerlukan keahlian manusia Sistem pakar yang baik dirancang agar dapat menyelesaikan suatu permasalahan 
tertentu dengan meniru kerja dari para ahli. 
Sistem pakar dapat ditampilkan dalam dua lingkungan, yaitu: pengembangan dan 
konsultasi. Lingkungan pengembangan digunakan oleh pembangun sistem pakar untuk 
membangun komponen dan memasukkan pengetahuan ke dalam basis pengetahuan. 
Lingkungan konsultasi digunakan oleh orang yang bukan ahli untuk memperoleh pengetahuan 
dan berkonsultasi. ]

Komponen-komponen yang ada pada sistem pakar, yaitu : 
1. Basis pengetahuan (Knowledge base). Berisi pengetahuan-pengetahuan yang dibutuhkan 
untuk memahami, memformulasikan dan memecahkan persoalan. 
2. Motor inferensi (inference engine). Ada 2 cara yang dapat dikerjakan dalam melakukan 
inferensi, yaitu: 
  a. Forward chaining merupakan grup dari multiple inferensi yang melakukan             pencarian  dari suatu masalah kepada solusinya. Forward chaining adalah data-driven   karena  inferensi dimulai dengan informasi yang tersedia dan baru konklusi            diperoleh.
  b. Backward chaining menggunakan pendekatan goal-driven, dimulai dari ekspektasi      apa yang diinginkan terjadi (hipotesis), kemudian mencari bukti yang mendukung        (atau kontradiktif) dari ekspektasi tersebut. 
3. Blackboard. Merupakan area kerja memori yang disimpan sebagai database untuk 
deskripsi persoalan terbaru yang ditetapkan oleh data input dan digunakan juga untuk 
perekaman hipotesis dan keputusan sementara. 
4. Subsistem akuisisi pengetahuan. Akuisisi pengetahuan adalah akumulasi, transfer dan transformasi keahlian pemecahan masalah dari pakar atau sumber pengetahuan 
terdokumentasi ke program komputer untuk membangun atau memperluas basis 
pengetahuan. 
5. Antarmuka pengguna. Digunakan untuk media komunikasi antara user dan program. 
6. Subsistem penjelasan. Digunakan untuk melacak respon dan memberikan penjelasan 
tentang kelakuan sistem pakar secara interaktif melalui pertanyaan. 
7. Sistem penyaring pengetahuan.

#  Hasil Implementasi
Hasil implementasi sistem pakar diagnosa penyakit tanaman padi dengan metode 
inferensi forward chaining dan backward chaining berbasis web mempermudah untuk diakses 
oleh siapa saja (khususnya petani) dan dimana saja (asalkan tersedia jaringan internet). Dapat menampilkan data gejala pada penyakit padi yang dapat 
dipilih oleh user. User, secara spesifik petani akan memilih gejala tersebut sesuai dengan 
gejala-gejaya yang sedang dialami di tanaman padi miliknya. Cara memilih adalah dengan klik 
pada kotak didepan kalimat tersebut, sampai muncul tanda V. Gejala yang dipilih bisa lebih dari 
satu disesuaikan dengan kondisi tanaman padi. 

Dapat menampilkan hasil inferensi untuk tanaman padi sesuai dengan 
gejala yang telah dipilih sebelumnya. Hasil diagnosa dari sistem pakar berbasis web dengan 
metode inferensi forward chaining dan backward chaining akan dapat menampilkan nama 
penyakit, gejala-gejala yang menandai penyakit tersebut, penjelasan mengenai penyakit dan 
langkah-langkah pengendalian teknis terhadap penyakit tersebut. 
Memperkirakan dan menunjukkan pilihan dua 
gejala, yaitu anakan tumbuh tegak dan daun menguning sampai jingga dari pucuk ke pangkal, 
menghasilkan simpulan bahwa mungkin tanaman padi tersebut menderita penyakit tungro 
dengan derajat kepastian 50% saja. Hal ini terjadi karena gejala yang di pilih tadi juga 
merupakan gejala pada penyakit tanaman padi yang lain. 

# Kesimpulan
Sistem pakar untuk mendiagnosa jenis penyakit pada tanaman padi dapat membantu 
petani mendiagnosa jenis penyakit dan memberikan pengetahuan tentang jenis penyakit 
tersebut. Sistem ini dibangun untuk menyimpan pengetahuan keahlian seorang pakar pertanian 
khususnya tanaman padi, sehingga sistem dapat dijadikan asisten pandai di bidangnya sebagai 
sumber pengetahuan oleh user. Pembangunan sistem dirancang sedemikian rupa sehingga 
dapat mengadopsi perkembangan penyakit penalaran yang digunakan berbasis aturan (RuleBased Reasoning) dengan metode inferensi forward chaining dan backward chaining.
Implementasi sistem pakar dalam bentuk web sangat membantu memberikan kemudahan bagi 
user dalam mengaksesnya. 
