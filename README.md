1. Penerapan Box Model, float, dan clear (lab4_box.html)
Mengatur elemen div agar bersisian secara horizontal menggunakan float: left.
Menggunakan properti clear: left dan float: none pada elemen .div4 untuk membatalkan efek float dari elemen sebelumnya, sehingga .div4 berada di baris baru di bawah elemen-elemen lainnya.
<img width="549" height="209" alt="image" src="https://github.com/user-attachments/assets/763380b5-c496-412c-870f-89ae11d08637" />

2. Layout Halaman Utama (home.html & style.css)
Container & Header: Membuat pembungkus utama (#container) berukuran 980px rata tengah (margin: auto) dengan efek bayangan (box-shadow).
Navigasi (<nav>): Menampilkan menu link secara inline-block dengan warna latar belakang aktif (#2b83ea).
Hero Section (#hero): Bagian banner dengan ucapan selamat datang dan tombol call-to-action.
Wrapper & Sidebar (#wrapper, #main, #sidebar): Mengatur konten utama di sebelah kiri (640px) dan sidebar di sebelah kanan (260px) menggunakan float: left.
Grid Card (.box): Menyusun 3 kolom konten menggunakan float: left dan pembagian lebar 33.33%.
Entry Article (.entry): Menampilkan artikel berita/fitur dengan gambar melayang di sisi kiri atau kanan teks.
<img width="854" height="592" alt="image" src="https://github.com/user-attachments/assets/566c32d8-2c84-4029-9f9f-b2449c4ad5e7" />
<img width="225" height="420" alt="image" src="https://github.com/user-attachments/assets/c5fae42f-2259-4536-8a31-b6df6e9d16f0" />
<img width="823" height="503" alt="image" src="https://github.com/user-attachments/assets/da469c8e-848c-4977-81ea-fb5e6900ad64" />

3. Halaman Profile & Portofolio (about.html)
Menggunakan tata letak kolom tunggal (single layout) dengan mengatur lebar area utama (width: 940px) tanpa sidebar.
Menampilkan profil/deskripsi singkat universitas/penulis di bagian atas.
Menggunakan grid komponen .box untuk menampilkan daftar keahlian/portofolio (Web Design, Frontend Dev, dan Optimization).
<img width="519" height="494" alt="image" src="https://github.com/user-attachments/assets/919408f5-cd41-4086-8cc3-e7446cad4fc8" />

4. Halaman Form Kontak (kontak.html)
Mengatur tata letak formulir (contact form) agar tampak rapi dan presisi di tengah halaman.
Menerapkan styling pada elemen-elemen input HTML seperti <input type="text">, <input type="email">, dan <textarea>.
Menambahkan efek interaktif pada form ketika diklik/difokuskan (:focus) dan kustomisasi tombol kirim (submit button).
<img width="674" height="492" alt="image" src="https://github.com/user-attachments/assets/c0a64dd8-6d03-4e5b-af18-1b4248bc3ff8" />

Dari praktikum yang telah dilakukan, dapat disimpulkan bahwa:
Properti float dan clear sangat penting untuk mengatur tata letak tradisional dalam CSS sebelum penggunaan Flexbox atau Grid modern.
Struktur dokumen HTML5 yang semantik (<header>, <nav>, <section>, <aside>, <footer>) membantu mempermudah pembacaan struktur halaman baik oleh pengembang maupun mesin pencari.
Penggunaan file CSS terpisah (style.css) mempermudah konsistensi tampilan pada seluruh halaman web (Home, About, Kontak).
