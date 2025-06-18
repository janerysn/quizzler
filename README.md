# quizzler

Quizzler flutter app

Uji Aplikasi<br>
1.	Jalankan aplikasi (flutter run).<br>
 <img src ="https://github.com/user-attachments/assets/bc47e186-95b1-4078-84d0-e860fafa47fe" width= "400px"><br>
 <img src ="https://github.com/user-attachments/assets/a2d68c65-8820-476c-b796-a722c7116058" width= "400px"><br>

2.	Penjelasan.<br>
Aplikasi Quizzler App adalah aplikasi kuis sederhana berbasis Flutter, di mana pengguna menjawab pertanyaan dengan pilihan True atau False.

Komponen utama aplikasi:

QuizzlerApp sebagai root widget yang menampilkan halaman utama QuizPage.

QuizPage adalah StatefulWidget yang mengatur tampilan pertanyaan, tombol jawaban, dan skor.

quizBrain adalah instance dari class QuizBrain (diimpor dari file quiz_brain.dart) yang mengatur list pertanyaan, jawaban, serta alur pertanyaan.

Fungsi checkAnswer() mengecek apakah jawaban pengguna benar atau salah, menambah ikon skor (scoreKeeper), serta menampilkan alert jika kuis telah selesai menggunakan package rflutter_alert.

Skor pengguna ditampilkan secara visual dengan deretan ikon centang hijau (benar) atau silang merah (salah) di bagian bawah layar.

Setelah semua pertanyaan selesai dijawab, aplikasi akan menampilkan ringkasan hasil kuis (jumlah benar, salah, total soal), kemudian reset kembali ke awal.

Aplikasi ini menggunakan package eksternal rflutter_alert untuk menampilkan alert pop-up saat kuis selesai.

Membuat Quiz Benar Salah

Terdiri dari colum 
1. Expanded Pertanyaan
2. Expanded Tombol Benar
3. Exapnded Tombol Salah
4. Row (benar, salah) berupa icons

