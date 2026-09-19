# Overview
Profile Card
Profile Card adalah halaman kartu profil interaktif dengan navigasi antar-anggota, fitur dark mode, dan like counter. Project ini dibuat sebagai study case GitReady 2.0 (Workshop Git & GitHub) untuk melatih kolaborasi tim menggunakan branch, pull request, dan code review.

## Visualisasi
![Tampilan Profile Card](https://github.com/user-attachments/assets/0898a636-7bcc-48e5-8584-5b3ce89f3bd4)

## Tech Stack
Tech Stack
HTML5
CSS3
JavaScript (Vanilla)
Git & GitHub

## Fitur Utama
[x] Toggle Dark Mode (teks tombol berubah antara Dark Mode dan Light Mode)
[x] Like Counter interaktif, jumlah like tersimpan terpisah untuk tiap anggota
[x] Navigasi antar-anggota (nama, role, foto, deskripsi, dan skill berubah otomatis)
[x] Responsive layout untuk layar kecil

## Contribution
Enjelina (Project Initiator): Membuat repository, mengatur akses kolaborator, dan commit index.html awal ke main 
Vino (Styling Engineer): Membuat branch styling, menambahkan dan menghubungkan style.css ke index.html 
Rashya (Script Engineer): Membuat branch scripting, menambahkan dan menghubungkan script.js ke index.html

## What I Learned
Version control mencatat setiap perubahan pada project, sehingga kita bisa melihat apa yang berubah, siapa yang mengubah, dan kembali ke versi sebelumnya.
Git dan GitHub itu berbeda. Git adalah alat pencatat riwayat yang berjalan di laptop (bisa offline), sedangkan GitHub adalah tempat menyimpan dan membagikan project secara online.
Alur dasar Git: edit file, git add, git commit, lalu git push. Commit adalah titik simpan yang membuat kita bisa kembali ke kondisi project di titik mana pun, bukan sekadar tombol save.
Repository dimulai dengan git init dari folder sendiri, atau git clone kalau repo sudah ada di GitHub.
Branch adalah jalur kerja terpisah dalam satu repository. Branch main harus selalu berisi kode yang jalan, dan semua pekerjaan baru dimulai dari branch sendiri.
Pull Request adalah mekanisme mengajukan perubahan supaya tim bisa me-review sebelum kode masuk ke main. Judul dan deskripsi yang jelas menghemat waktu reviewer.
Merge conflict terjadi ketika dua orang mengubah baris yang sama pada file yang sama. Cara mengatasinya: pilih versi yang dipakai, hapus baris penanda (<<<<<<<, =======, >>>>>>>), lalu commit. Conflict itu normal dan bukan tanda kita salah.
Best practice: penamaan branch dengan prefix (misalnya feature/..., fix/..., docs/...), commit message yang singkat dan deskriptif, satu orang satu branch satu fitur, pull dari main sebelum mulai bekerja, push commit kecil secara rutin, dan tidak pernah push langsung ke main.
Konfigurasi Git (user.name dan user.email) sebaiknya memakai email yang sama dengan akun GitHub supaya kontribusi tercatat di grafik profil.

How to Run
Clone repository ini:
bash
git clone https://github.com/Enjelinacia8/gwenchana.git
Buka folder hasil clone, lalu klik dua kali file index.html (atau klik kanan → Open with → Browser).



Feature Improvement
Ide pengembangan lanjutan jika project ini dilanjutkan:
Menyimpan jumlah like ke localStorage supaya tidak reset saat halaman dimuat ulang
Menyimpan pilihan dark mode ke localStorage
Menambahkan animasi transisi saat berganti anggota
Memindahkan data anggota ke file JSON terpisah
Deploy ke GitHub Pages agar bisa diakses lewat link demo
