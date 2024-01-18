Assalamualikum Waroh Matullohi Wabarokatu.
Pada pertemuan kali ini saya akan membahas tentang 4 (empat) penerapan data mining menggunakan metodologi CRISP-DM (the Cross-Industry Standard Process for Data Mining) dengan fungsinya yaitu Forecasting (prediksi/Peramalan), Classification, Clustering, dan Association. Sebenarnya masih ada satu lagi yaitu Estimasi (Estimation) namun saya hanya diberikan tugas untuk membuat sebuah makalah atau penelitian dengan menggunakan empat fungsi saja. Dalam penelitian ini terdapat 4 (empat) judul utama yang akan saya bacakan yaitu terdiri dari:
1.	Penerapan CRISP-DM Prediksi (Forecasting) pada Pemain Bola Basket di NBA dalam Satu Musim Menggunakan Metode Neural Network.
2.	Penerapan CRISP-DM Klasifikasi pada Kelulusan Mahasiswa di Universitas Siber Asia Menggunakan Metode Decision Tree.
3.	Penerapan CRISP-DM Clustering pada Penyedia Asuransi Solusi Kesehatan AXA-Mandiri Menggunakan Metode K-Means.
4.	Penerapan CRISP-DM Asosiasi pada Konsumsi Minyak Pemanas (Heating Oil Consumption) Menggunakan Metode Correlational.
Saya berharap penelitian ini dapat bermanfaat bagi kita semua.

BAB I 
PROSES DATA MINING BERBASIS METODOLOGI CRISP-DM
CRISP-DM adalah metodologi datamining yang sangat populer. Ini terdiri dari enam tahap yaitu: pemahaman bisnis (Business Understanding), pemahaman data (Data Understanding), persiapan data (Data Preparation), pemodelan (Model), evaluasi (Evaluation) dan penyebaran (Deployment). CRIPS-DM menekankan kerja tim yang melibatkan pengambil keputusan bisnis, analis data, dan ahli domain.
1.1. Data Mining Standard Process
•	Dunia industri yang beragam bidangnya memerlukan proses yang standard yang mampu mendukung penggunaan data mining untuk menyelesaikan masalah bisnis.
•	Proses tersebut harus dapat digunakan di lintas industri (cross-industry) dan netral secara bisnis, tool dan aplikasi yang digunakan, serta mampu menangani strategi pemecahan masalah bisnis dengan menggunakan data mining.
•	Pada tahun 1996, lahirlah salah satu standard proses di dunia data mining yang kemudian disebut dengan: the Cross-Industry Standard Process for Data Mining (CRISP–DM) (Chapman, 2000).
1.2. CRISP-DM
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/1c943c7f-0f7a-4981-9d71-3c5333076e76)
1.2.1. Business Understanding
•	Mengucapkan tujuan dan persyaratan proyek dengan jelas dalam hal bisnis atau unit penelitian secara keseluruhan.
•	Terjemahkan tujuan dan batasan ini ke dalam perumusan definisi masalah penambangan data.
•	Terjemahkan tujuan dan batasan ini ke dalam perumusan definisi masalah penambangan data.
•	Merancang apa yang akan Anda bangun.
1.2.2. Data Understanding
•	Kumpulkan data.
•	Gunakan analisis data eksplorasi untuk membiasakan diri dengan data dan menemukan wawasan awal.
•	Mengevaluasi Kualitas data.
•	Jika diinginkan, pilih subset yang menarik yang mungkin berisi pola yang dapat ditindaklanjuti.
1.2.3. Data Preparation
•	Siapkan dari data mentah awal kumpulan data akhir yang akan digunakan untuk semua fase berikutnya.
•	Pilih kasus dan variabel yang ingin Anda analisis dan itu sesuai untuk analisis Anda.
•	Melakukan data cleaning, integration, reduction dan transformation, jadi sudah siap untuk alat pemodelan.
1.2.4. Modeling
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/bbb28f1e-b84f-49ab-97af-dc8e34702318)
•	Pilih dan terapkan pemodelan yang sesuai teknik.
•	Mengkalibrasi pengaturan model untuk mengoptimalkan hasil.
•	Ingat itu sering, beberapa teknik yang berbeda dapat digunakan untuk masalah penambangan data yang sama.
•	Jika perlu, kembali ke fase persiapan data untuk membawa bentuk data sesuai dengan persyaratan spesifikasi dari teknik penambangan data tertentu.
1.2.5. Evaluation
•	Mengevaluasi satu atau beberapa model yang disampaikan dalam tahap pemodelan untuk kualitas dan efektivitas sebelum menerapkannya untuk digunakan di lapangan.
•	Tentukan apakah model sebenarnya mencapai tujuan yang ditetapkan untuk itu di fase pertama.
•	Tentukan apakah beberapa aspek penting dari masalah bisnis atau penelitian belum diperhitungkan secara memadai.
•	Ambil keputusan mengenai penggunaan hasil data mining.
1.2.6. Deployment
Membuat Penggunaan model yang dibuat:
•	Pembuatan model tidak bukan menandakan penyelesaian dari sebuah proyek.
Contoh sebuah penerapan sederhana:
•	Hasilkan laporan.
Contoh dari sebuah penyebaran yang lebih kompleks:
•	Menerapkan Proses penambangan data paralel di departemen lain.
•	Untuk bisnis, pelanggan sering melakukan penyebaran berdasarkan model Anda.
1.3. CRISP-DM: Detail Flow
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/41743393-0d53-4d38-bdf2-897f11d874fd)
1.4 Metode Data Mining
1.	Estimation (Estimasi):
Linear Regression (LR), Neural Network (NN), Deep Learning (DL), Support Vector Machine (SVM), Generalized Linear Model (GLM), etc.
2.	Forecasting (Prediksi/Peramalan):
Linear Regression (LR), Neural Network (NN), Deep Learning (DL), Support Vector Machine (SVM), Generalized Linear Model (GLM), etc.
3.	Classification (Klasifikasi):
Decision Tree (CART, ID3, C4.5, Credal DT, Credal C4.5, Adaptative Credal C4.5), Naive Bayes (NB), K-Nearest Neighbor (kNN), Linear Discriminant Analysis (LDA), Logistic Regression (LogR), etc.
4.	Clustering (Klastering):
K-Means, K-Medoids, Self-Organizing Map (SOM), Fuzzy C-Means (FCM), etc.
5.	Association (Asosiasi):
FP-Growth, A Priori, Coefficient of Correlation, Chi Square, etc.

BAB II 
PENERAPAN DAN IMPLEMENTASI METODOLOGI CRISP-DM
2.1. Penerapan CRISP-DM Prediksi (Forecasting) pada Pemain Bola Basket di NBA dalam Satu Musim Menggunakan Metode Neural Network
2.1.1. Konteks dan Perspektif 
NBA (National Basketball Association) adalah liga bola basket pria di Amerika Serikat dan merupakan liga basket paling bergengsi di dunia. Juan adalah analis kinerja statistik untuk tim atletik profesional utama di NBA.  Timnya terus meningkat selama beberapa musim pertandingan NBA terakhir, dan menuju ke musim mendatang manajemen percaya bahwa dengan menambahkan antara dua dan empat pemain hebat, tim akan memiliki kesempatan luar biasa untuk mencapai kejuaraan liga NBA.  Mereka telah menugaskan Juan untuk mengidentifikasi opsi terbaik mereka dari antara daftar 59 pemain berpengalaman yang akan tersedia bagi mereka.  Semua pemain ini memiliki pengalaman, beberapa telah bermain secara profesional sebelumnya dan beberapa memiliki pengalaman bertahun-tahun sebagai amatir.  Tidak ada yang harus dikesampingkan tanpa dinilai karena kemampuan potensial mereka untuk menambah kekuatan bintang dan produktivitas ke tim yang ada.  Para eksekutif tempat Juan bekerja sangat ingin terus menghubungi prospek yang paling menjanjikan, jadi Juan perlu segera mengevaluasi kinerja masa lalu para atlet ini dan membuat rekomendasi berdasarkan analisisnya. 
2.1.2. Tujuan Penelitian
Tujuan dari penelitian ini adalah: 
1.	Menjelaskan apa itu jaringan saraf, bagaimana ia digunakan dan manfaat menggunakannya. 
2.	Mengenali format yang diperlukan untuk data untuk melakukan penambangan data jaringan saraf. 
3.	Mengembangkan model penambangan data jaringan saraf di RapidMiner  menggunakan kumpulan data pelatihan.
4.	Menafsirkan output model dan menerapkannya ke kumpulan data penilaian untuk menyebarkan model. 
2.1.3. Pemahaman Bisnis (Business Understanding)
Juan menghadapi harapan yang tinggi dan memiliki tenggat waktu pengiriman untuk dipenuhi.  Dia adalah seorang profesional, dia tahu bisnisnya dan tahu betapa pentingnya hal-hal tak berwujud dalam menilai bakat atletik.  Dia juga tahu bahwa hal-hal tak berwujud itu sering dimanifestasikan oleh kinerja atlet di masa lalu.  Dia ingin menambang kumpulan data semua pemain saat ini di liga untuk membantu menemukan prospek yang dapat membawa kegembiraan, penilaian, dan pertahanan paling banyak ke tim untuk mencapai kejuaraan liga.  Sementara pertimbangan gaji selalu menjadi perhatian, manajemen telah mengindikasikan kepada Juan bahwa keinginan mereka adalah untuk mendorong kejuaraan di musim mendatang, dan mereka bersedia melakukan semua yang mereka bisa secara finansial untuk mendatangkan dua hingga empat atlet terbaik yang dapat diidentifikasi Juan.  Dengan tujuan majikannya yang dijelaskan kepadanya, Juan siap untuk mengevaluasi masing-masing dari kinerja statistik masa lalu 59 prospek untuk membantunya merumuskan apa rekomendasinya nanti. 
2.1.4. Pemahaman Data (Data Understanding) 
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/9e65f909-5cc5-45fb-b4d4-22109d211ceb)
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/603a2835-502e-4141-996d-77b6daf1c57d)
Juan tahu bisnis analisis statistik atletik.  Dia telah melihat bagaimana kinerja di satu area, seperti mencetak gol, sering saling berhubungan dengan area lain seperti pertahanan atau pelanggaran.  Atlet terbaik umumnya memiliki hubungan yang kuat antara dua atau lebih bidang kinerja, sementara atlet yang lebih khas mungkin memiliki kekuatan di satu bidang tetapi kelemahan di bidang lain.  Misalnya, pemain peran yang baik seringkali merupakan pembela yang baik, tetapi tidak dapat berkontribusi banyak dalam mencetak gol kepada tim.  Menggunakan data liga dan pengetahuan serta pengalamannya dengan para pemain di liga, Juan menyiapkan kumpulan data pelatihan yang terdiri dari 263 pengamatan dan 19 atribut.  59 calon atlet tim Juan dapat memperoleh dari kumpulan data penilaian, dan dia memiliki atribut yang sama untuk masing-masing orang ini.  Kami akan membantu Juan membangun  jaringan saraf (Neural Network), yang merupakan metodologi penambangan data yang dapat memprediksi kategori atau klasifikasi dengan cara yang sama seperti pohon keputusan, tetapi jaringan saraf lebih baik dalam menemukan kekuatan koneksi antar atribut, dan koneksi itulah yang sangat diminati Juan.  Atribut yang akan dievaluasi oleh jaringan saraf kami adalah: 
•	Player_Name: Ini adalah nama pemain.  Dalam fase persiapan data kami, kami akan mengatur perannya menjadi 'id', karena tidak prediktif dengan cara apa pun, tetapi penting untuk disimpan dalam kumpulan data kami sehingga Juan dapat dengan cepat membuat rekomendasinya tanpa harus mencocokkan data kembali ke nama pemain nanti.  (Perhatikan bahwa nama-nama dalam kumpulan data bab ini dibuat menggunakan generator nama acak.  Mereka fiktif dan kesamaan apa pun dengan orang sungguhan tidak disengaja dan murni kebetulan.) 
•	Position_ID: Untuk olahraga yang dimainkan tim Juan, ada 12 posisi yang mungkin.  Masing-masing direpresentasikan sebagai bilangan bulat dari 0 hingga 11 dalam kumpulan data. 
•	Shots: Ini adalah jumlah total tembakan, atau peluang mencetak gol yang diambil setiap pemain di musim terbaru mereka. 
•	Makes: Ini adalah berapa kali atlet mencetak gol saat menembak selama musim terbaru. 
•	Personal_Points: Ini adalah jumlah poin yang dicetak atlet secara pribadi selama musim terbaru. 
•	Total_Points: Ini adalah jumlah total poin yang disumbangkan atlet untuk mencetak gol di musim terbaru.  Dalam olahraga yang dimainkan tim Juan, statistik ini dicatat untuk setiap poin yang disumbangkan atlet untuk mencetak gol.  Dengan kata lain, setiap kali seorang atlet mencetak gol personal point, total poin mereka meningkat satu, dan setiap kali seorang atlet berkontribusi pada penilaian rekan satu tim, total poin mereka juga meningkat satu. 
•	Assists: Ini adalah statistik defensif yang menunjukkan berapa kali atlet membantu timnya mendapatkan bola dari tim lawan selama musim terakhir. 
•	Concessions: Ini adalah berapa kali permainan atlet secara langsung menyebabkan tim lawan mengakui keunggulan ofensif selama musim terakhir. 
•	Block: Ini adalah berapa kali atlet secara langsung dan independen memblokir tembakan tim lawan selama musim terbaru. 
•	Block_Assists: Ini adalah berapa kali seorang atlet berkolaborasi dengan rekan satu tim untuk memblokir tembakan tim lawan selama musim terbaru.  Jika dicatat sebagai block assist, dua atau lebih pemain pasti terlibat.  Jika hanya satu pemain yang memblokir tembakan, itu dicatat sebagai blok.  Karena permukaan bermainnya besar dan para pemainnya tersebar, jauh lebih mungkin bagi seorang atlet untuk merekam satu blok daripada dua atau lebih untuk merekam assist block. 
•	Fouls: Ini adalah berapa kali, di musim terbaru, atlet melakukan pelanggaran.  Karena mengotori tim lain memberi mereka keuntungan, semakin rendah angka ini, semakin baik kinerja atlet untuk timnya sendiri. 
•	Years_Pro: Dalam kumpulan data pelatihan, ini adalah jumlah tahun atlet telah bermain di tingkat profesional.  Dalam kumpulan data penilaian, ini adalah jumlah tahun pengalaman yang dimiliki atlet, termasuk tahun sebagai profesional jika ada, dan tahun di liga amatir yang terorganisir dan kompetitif. 
•	Career_Shots: Ini sama dengan atribut Shots, kecuali kumulatif untuk seluruh karier atlet.  Semua atribut karir adalah upaya untuk menilai kemampuan seseorang untuk tampil konsisten dari waktu ke waktu. 
•	Career_Makes: Ini sama dengan atribut Makes, kecuali kumulatif untuk seluruh karir atlet. 
•	Career_PP: Ini sama dengan atribut Poin Pribadi, kecuali kumulatif untuk seluruh karier atlet. 
•	Career_TP: Ini sama dengan atribut Total Poin, kecuali kumulatif untuk seluruh karir atlet. 
•	Career_Assists: Ini sama dengan atribut Career Assists, kecuali kumulatif untuk seluruh karir atlet. 
•	Career_Con: Ini sama dengan atribut Konsesi Karir, kecuali kumulatif untuk seluruh karir atlet. 
•	Team_Value: Ini adalah atribut kategoris yang merangkum nilai atlet untuk miliknya team.  Ini hanya ada dalam data pelatihan, karena akan berfungsi sebagai label kami untuk memprediksi Team_Value untuk setiap pengamatan dalam kumpulan data penilaian.  Ada empat kategori: 
•	Role Cast: Ini adalah atlet yang cukup baik untuk bermain di tingkat profesional, dan mungkin sangat bagus di satu bidang, tetapi tidak bagus secara keseluruhan. 
•	Contributor: Ini adalah atlet yang berkontribusi di beberapa kategori pertahanan dan pelanggaran dan dapat diandalkan untuk secara teratur membantu tim menang. 
•	Franchise Players: Ini adalah atlet yang keterampilannya sangat luas, kuat, dan konsisten sehingga tim ingin bertahan lama pada mereka.  Para pemain ini memiliki tingkat bakat sedemikian rupa sehingga mereka dapat membentuk fondasi tim yang sangat bagus dan kompetitif. 
•	Superstar: Ini adalah individu langka yang hadiahnya sangat unggul sehingga mereka membuat perbedaan di setiap pertandingan.  Sebagian besar tim di liga akan memiliki satu pemain seperti itu, tetapi tim dengan dua atau tiga selalu bersaing untuk gelar liga. 
Data Juan sudah siap dan kami memahami atribut yang tersedia bagi kami.  Kita sekarang dapat melanjutkan ke... 
2.1.5. Persiapan Data  (Data Preparation)
Buka https://github.com/Hendro10/dataminingforthemasses. Akses situs web pendamping buku dan unduh dua file: Chapter11DataSet_Training.csv dan Chapter11DataSet_Scoring.csv.  File-file ini berisi 263 atlet profesional saat ini dan 59 prospek masing-masing.  Selesaikan langkah-langkah berikut: 
1)	Impor kedua dataset tersebut ke repositori RapidMiner  Anda.  Pastikan untuk menetapkan baris pertama sebagai nama atribut.  Anda dapat menerima default untuk tipe data.  Simpan dengan nama deskriptif, lalu seret dan jatuhkan ke jendela proses utama baru.  Pastikan untuk mengganti nama objek yang diambil sebagai Pelatihan (Training) dan Penilaian (Scoring). Pastikan Years_Pro kita setting Set Role-nya menjadi “label” seperti terlihat pada gambar 2-2.
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/7baf2696-cd18-495b-8abd-6bf54315eed3)
Gambar 2-2. Pada kolom Years_Pro di Set Role menjadi “label” terlebih dahulu.
2)	Tambahkan tiga operator Set Role; dua untuk aliran pelatihan (Training) Anda dan satu untuk aliran penilaian (Scoring) Anda.  Gunakan yang pertama dalam aliran pelatihan (Training) untuk mengatur peran atribut Player_Name ke 'id', sehingga tidak akan disertakan dalam perhitungan prediksi jaringan saraf.  Lakukan hal yang sama untuk atribut Set Role dalam aliran penilaian (Scoring).  Terakhir, gunakan atribut Set Role kedua dalam aliran pelatihan (Training) untuk mengatur atribut Team_Value sebagai 'label' untuk model kita.  Ketika Anda selesai dengan langkah 1 dan 2, proses Anda akan terlihat seperti Gambar 2-3, 2-4, dan 2-5.
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/c29d3341-5d93-4c41-81d4-ace9751d84c8)
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/1bf69a34-9313-4a87-8125-9b15c88946e6)
Gambar 2-3. Pengaturan parameter pada Set Role 1.
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/4d83cdbe-a25a-42cd-869a-60232c73f888)
Gambar 2-4. Pengaturan parameter pada Set Role 2.
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/bf661044-b5c9-478c-bfdd-f2192f8d84e2)
Gambar 2-5. Persiapan data (data preparation) untuk analisis neural network dengan pengaturan parameter Set Role 3.
3)	Setelah datanya siap, silahkan jalankan modelnya.  Gunakan tampilan Statistics untuk masing-masing dari dua kumpulan data untuk membiasakan diri dengan data.  Pastikan bahwa atribut khusus Anda memiliki peran yang ditetapkan sebagaimana mestinya, sesuai dengan parameter yang Anda konfigurasikan pada langkah 2 (lihat Gambar 2-6 dan 2-7 yang menampilkan statistics data). Di sini tidak ada data yang Missing, dan data dinyatakan bersih tanpa ada yang noise.
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/8753ce9f-7879-47d1-a465-913b2b973312)
Gambar 2-6. Set data pelatihan (Training) dengan dua atribut khusus: Player_Name ('id') dan Team_Value ('label').
![image](https://github.com/Hendro10/dataminingforthemasses/assets/112385556/7da5253f-22e1-4a5b-a76e-b52549cd5a75)
Gambar 2-7. Statistics data set data penilaian (Scoring) dengan atribut khusus Player_Name ditetapkan sebagai 'id'.
4)	Saat Anda meninjau kumpulan data, perhatikan bahwa keduanya memiliki satu karakteristik yang unik dari kumpulan data contoh sebelumnya: rentang untuk kumpulan data penilaian tidak berada dalam rentang untuk kumpulan data pelatihan.  Algoritma jaringan saraf, termasuk yang digunakan dalam RapidMiner , sering menggunakan konsep yang disebut logika fuzzy, yang merupakan pendekatan inferensial, berbasis probabilitas untuk perbandingan data yang memungkinkan kita untuk menyimpulkan, berdasarkan probabilitas, kekuatan hubungan antara atribut dalam kumpulan data kita.  Ini memberi kita fleksibilitas tambahan atas beberapa teknik penambangan data prediktif lainnya yang sebelumnya ditunjukkan dalam penelitian ini.  Setelah meninjau meta data kumpulan data, kembali ke perspektif desain sehingga kami dapat melanjutkan... 
5)	Saat Anda meninjau kumpulan data, perhatikan bahwa keduanya memiliki satu karakteristik yang unik dari kumpulan data contoh sebelumnya: rentang untuk kumpulan data penilaian tidak berada dalam rentang untuk kumpulan data pelatihan.  Algoritma jaringan saraf, termasuk yang digunakan dalam RapidMiner , sering menggunakan konsep yang disebut logika fuzzy, yang merupakan pendekatan inferensial, berbasis probabilitas untuk perbandingan data yang memungkinkan kita untuk menyimpulkan, berdasarkan probabilitas, kekuatan hubungan antara atribut dalam kumpulan data kita.  Ini memberi kita fleksibilitas tambahan atas beberapa teknik penambangan data prediktif lainnya yang sebelumnya ditunjukkan dalam penelitian ini.  Setelah meninjau meta data kumpulan data, kembali ke perspektif desain sehingga kami dapat melanjutkan... 
2.1.6. Pemodelan (Modeling)
5)	Menggunakan bidang pencarian pada tab Operator, temukan operator Neural Net dan tambahkan ke aliran pelatihan Anda.  Gunakan Apply Model untuk menerapkan jaringan saraf Anda ke kumpulan data penilaian Anda.  Pastikan port mod dan lab terhubung ke port res (Gambar 2-8).
