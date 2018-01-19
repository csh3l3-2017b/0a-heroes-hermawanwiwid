# 0a-heroes-hermawanwiwid
0a-heroes-hermawanwiwid created by GitHub Classroom

# Bumi Terancam Punah... Tapi Belum Terlambat untuk Menyelamatkannya!

Dunia sedang dalam krisis yang gawat. Serangan demi serangan merajalela.

Beberapa heroes dengan gagah berani maju ke depan untuk menyelamatkan dunia. Namun...

Kita punya masalah besar! Tidak ada orang yang dapat mengetahui, apa peran masing-masing hero dalam menyelamatkan dunia.

Dunia membutuhkan bantuan dari Anda, wahai mahasiswa Teknik Informatika Telkom University. yang dahsyat dan penuh semangat. Dunia membutuhkan karya Anda... Heroes Classifier!

## Heroes Membutuhkan Anda
Setiap heroes akan mengisi formulir biodata hero, dalam file teks bernama test.csv dengan struktur CSV, misalnya sebagai berikut: (di bawah hanya contoh, bukan file test.csv sebenarnya)

* name,movementSpeed,physicalAttack,armor,hp,mana
* Layla,270,118,15,2500,424
* Cyclops,250,107,18,2461,500
* Minotaur,265,123,25,2705,0
* Saber,265,121,17,2475,443
* Roger,235,120,22,2580,450
* Nana,250,110,17,2325,499
* Layla Cyclops Minotaur Saber Roger Nana

Misi Anda adalah menentukan, apa peran dari masing-masing hero yang membutuhkan bantuan dari program Anda, dengan aturan sebagai berikut secara berurutan (hero mendapatkan peran yang paling awal memenuhi syarat):

* Heroes yang memiliki movementSpeed >= 270, akan mendapat peran sebagai MARKSMAN (huruf kapital semua)
* Heroes dengan mana >= 500, akan mendapat peran sebagai MAGE (huruf kapital semua)
* Heroes dengan armor >= 25, akan mendapat peran sebagai TANK (huruf kapital semua)
* Heroes dengan physicalAttack >= 121, akan mendapat peran sebagai ASSASSIN (huruf kapital semua)
* Heroes dengan hp >= 2580, akan mendapat peran sebagai FIGHTER (huruf kapital semua)
* Heroes lainnya akan mendapat peran sebagai SUPPORT (huruf kapital semua)

Dengan contoh daftar hero dengan biodata di atas, maka program Anda akan menghasilkan file output bernama prediction.csv dengan isi sebagai berikut:

* name,role
* Layla,MARKSMAN
* Cyclops,MAGE
* Minotaur,TANK
* Saber,ASSASSIN
* Roger,FIGHTER
* Nana,SUPPORT

## Strategi Penyelamatan Bumi
Heroes sangat menunggu karya Anda. Karena misi yang Anda emban sangat rahasia, maka hasil analisis dari program Anda perlu diberikan kepada para heroes dengan mekanisme berikut untuk menghindari mata-mata musuh.

1. File test.csv akan disediakan oleh para heroes melalui Kaggle InClass TelU Legends Heroes > Data
2. Buatlah program dengan Python 3.6 dan Jupyter Notebook untuk: (cantumkan kelas, NIM, dan nama lengkap, di notebook Anda)
* membaca file test.csv
* menganalisa data dan menghasilkan keluaran berupa klasifikasi peran masing-masing hero
* tampilkan hasil keluaran sesuai format CSV di atas
* menyimpan hasil keluaran ke dalam file prediction.csv
* Hint: Anda dapat menginstall Anaconda for Windows/Mac/Linux, yang sudah termasuk Jupyter Notebook siap pakai. Untuk menjalankan Jupyter Notebook, jalankan aplikasi Anaconda Prompt lalu ketik jupyter notebook .

3. File output prediction.csv silakan diunggah di melalui menu Kaggle InClass TelU Legends Heroes > Submit Predictions. Saat mengirim submission: Pada bagian deskripsi, cantumkan kelas, NIM, dan nama Anda.

4. Hasil analisis Anda akan langsung diperiksa oleh para heroes dan tampil di Leaderboard Public. Anda akan mendapat skor 0.0 bila semua peran salah, 1.0 bila semua peran benar, atau nilai di antaranya sesuai dengan jumlah prediksi benar/salah. Leaderboard Public hanya menilai 50% dari semua data yang ada, skor final Anda hanya akan ditampilkan di Leaderboard setelah deadline berakhir.
