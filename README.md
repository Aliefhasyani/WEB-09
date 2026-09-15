LAB-WEB-09-2026
Welcome To LAB-WEB-10-2024 Repository ✋. Repository ini merupakan tempat kalian untuk mengumpulkan semua tugas praktikum pemrograman web. Berikut panduan singkat tata cara mengumpulkan tugas di repositori ini:

Note:
Untuk perintah yang dibungkus < > maka perintah tersebut diganti sesuai instruksi yang ada dalam tanda < > tersebut. Contohnya mkdir <NIM> menjadi mkdir H071211019

Silahkan fork repositori ini. Menu fork berada di atas kanan repository.

Lakukan clone terhadap hasil fork repository ini ke komputer kalian

git clone <url-repositori-hasil-fork>
Pindah ke repositori hasil clone dengan perintah berikut

cd LAB-WEB-09-2026
Buat branch baru berdasarkan NIM kalian serta gunakan branch tersebut untuk menyimpan kode dari soal yang dikerjakan

git checkout -b <NIM>
Buat folder sesuai dengan NIM kalian.

mkdir H071231037
Di dalam folder NIM kalian buat folder dengan nama "Tugas_<no_tugas>" tanpa tanda kutip. contoh: Tugas_01

Di dalam folder tugas tersebut, kalian menambahkan tugas yang telah kalian kerjakan.

Setelah semua file tugas telah diselesaikan dan telah diasistensikan lakukan perintah berikut

git add .
git commit -m "<pesan commit>"
git push origin <NIM>
Note: Pesan commit yang dibuat diharapkan menggunakan conventional commit, agar mempermudah dokumentasi code kalian di masa mendatang.


Setelah perintah tersebut berhasil, silahkan membuka repository hasil fork kalian di github dan lakukan pull request ke repository ini.

Apabila terdapat kesulitan, silahkan menghubungi asistennya. Dapat melalui grup WA yang telah disediakan ataupun PC langsung ke asisten
