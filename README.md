# Membuat Ordered List
Pada tahap ini, saya membuat daftar berurutan (ordered list) menggunakan tag < nol > dan < li >.
Tag < ol > digunakan untuk membuat list bernomor, sedangkan < li > berfungsi untuk menampilkan setiap item dalam daftar.
Contohnya:
<img width="1920" height="1080" alt="Cuplikan layar 2025-10-06 134217" src="https://github.com/user-attachments/assets/a1b2842a-cc70-4c6e-901a-fc45c968f9e3" />
Hasilnya berupa daftar dengan penomoran otomatis dari 1, 2, 3, dan seterusnya.

# Membuat Unorderd List
Selanjutnya, saya membuat daftar tidak berurutan (unordered list) menggunakan tag < ul > dan < li >.
Berbeda dari ordered list, daftar ini menggunakan simbol (bullet), bukan angka.
Contohnya:
<img width="1920" height="1080" alt="Cuplikan layar 2025-10-06 135429" src="https://github.com/user-attachments/assets/ccc7c103-53fb-4cbf-bd6c-cefe18b47f26" />
List ini cocok untuk menampilkan data yang tidak membutuhkan urutan tertentu.

# Membuat Description List
Tahap berikutnya adalah membuat description list, yaitu daftar dengan penjelasan menggunakan tag < dl >, < dt >, dan < dd >.

< dl > → pembungkus daftar deskripsi

< dt > → istilah atau nama item

< dd > → penjelasan dari item tersebut
Contohnya:
<img width="1917" height="1072" alt="Cuplikan layar 2025-10-06 182307" src="https://github.com/user-attachments/assets/2ff39703-f3ec-4333-862b-6676234f0306" />
Hasilnya menampilkan istilah dan deskripsinya di bawah.

# Membuat Tabel
Kemudian saya membuat tabel menggunakan tag < table >, < tr >, < th >, dan < td >.

< tr > untuk membuat baris

< th > untuk judul kolom (header)

< td > untuk isi data
Atribut seperti border, cellpadding, dan cellspacing digunakan untuk memperjelas tampilan tabel.
<img width="1910" height="1068" alt="Cuplikan layar 2025-10-06 183613" src="https://github.com/user-attachments/assets/d9b3a8b8-9331-4a18-9bc7-6465070a2117" />

# Menggabungkan Sel Data
Untuk menggabungkan beberapa sel dalam tabel, saya menggunakan atribut rowspan dan colspan.

rowspan menggabungkan sel secara vertikal

colspan menggabungkan sel secara horizontal
Contoh:
<img width="1900" height="1079" alt="Cuplikan layar 2025-10-06 185118" src="https://github.com/user-attachments/assets/37f39721-d0c7-4742-9ce7-15153577aa53" />
Dengan begitu, sel “Teknik” bisa mencakup dua baris sekaligus.

# Membuat Form
Tahap ini saya membuat form sederhana menggunakan tag <form> yang berisi elemen input seperti:

< input type="text" > untuk nama

< textarea > untuk alamat

< input type="radio" > untuk jenis kelamin

< input type="submit" > untuk tombol kirim
Semua elemen dikemas dalam <fieldset> agar tampil lebih rapi.
<img width="1915" height="1059" alt="Cuplikan layar 2025-10-06 190858" src="https://github.com/user-attachments/assets/c7a74404-3559-4fda-bf6a-1a1702c83897" />

# Menambahkan Style pada Form
Setelah membuat struktur form, saya menambahkan CSS agar tampilan lebih menarik dan profesional.
Beberapa properti yang saya gunakan:

border untuk garis form

background-color untuk warna latar

padding & margin untuk memberi jarak antar elemen

border-collapse untuk tabel
Selain itu, saya juga menambahkan warna hijau pada tombol submit agar kontras dengan latar belakang.
<img width="1916" height="1079" alt="Cuplikan layar 2025-10-06 191703" src="https://github.com/user-attachments/assets/5742a326-156d-40b0-af7e-8c1e367bd032" />

# Pertanyaan dan Tugas
1. Buatlah form yang menampilkan Dropdown menu dan listbox dengan multiple selection

# Jawaban
<img width="1912" height="1061" alt="Cuplikan layar 2025-10-06 200742" src="https://github.com/user-attachments/assets/26c46dbb-4992-468b-9a57-5ca6088a32ce" />
Pada bagian tugas, saya membuat form dengan dropdown menu dan listbox multiple selection.
Langkah-langkahnya:

Buat elemen < select > untuk dropdown (hanya bisa pilih satu).

Buat elemen < select multiple > untuk listbox (bisa pilih lebih dari satu).

Tambahkan beberapa <option> agar pengguna bisa memilih kursus seperti HTML, CSS, JavaScript, Python, dan lainnya.

Gunakan atribut size agar listbox memiliki tinggi tertentu dan dapat di-scroll.

Tambahkan sedikit CSS agar listbox tampil rapi, sejajar, dan tidak terlalu mepet.

Hasil akhirnya adalah form dengan tampilan dark mode elegan, dropdown jurusan, dan listbox kursus dengan scroll, seperti yang ditampilkan pada gambar di bagian “Jawaban”.
