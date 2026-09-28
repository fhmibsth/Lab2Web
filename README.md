# Praktikum 2 - HTML Lanjutan

Repository ini berisi hasil pengerjaan Praktikum 2 Pemrograman Web tentang HTML Lanjutan.

## Identitas

- Nama: M. Fahmi Abdul Basith
- NIM: 312510260
- Program Studi: Teknik Informatika
- Mata Kuliah: Pemrograman Web
- Praktikum: 2 - HTML Lanjutan

---

## Tujuan Praktikum

Praktikum ini bertujuan untuk mempelajari:

1. Penggunaan tabel pada HTML.
2. Penggunaan form dan berbagai jenis input HTML.
3. Penggunaan Semantic HTML.
4. Penambahan elemen multimedia.
5. Validasi form dasar menggunakan atribut HTML.

---

## 1. Membuat Tabel Data Mahasiswa

Pada praktikum ini dibuat tabel untuk menampilkan data mahasiswa menggunakan elemen:

- `<table>`
- `<tr>`
- `<th>`
- `<td>`

Contoh data yang ditampilkan adalah NIM, Nama, dan Program Studi.

### Screenshot di VS code

![Latihan 1 VS code](media/screenshot/latihan1vsc.png)

### Screenshot Hasil di Browser

![Latihan 1 Browser](media/screenshot/latihan1browser.png)

---

## 2. Mengembangkan Tabel

Tabel dikembangkan menggunakan:

- `<caption>`
- `<thead>`
- `<tbody>`
- `<tfoot>`
- `colspan`

### Screenshot di VS code

![Latihan 2 VS code](media/screenshot/latihan2vsc.png)

### Screenshot Hasil di Browser

![Latihan 2 Browser](media/screenshot/latihan2browser.png)

---

## 3. Membuat Form Registrasi Mahasiswa

Form digunakan untuk menerima data dari pengguna.

Input yang digunakan:

- Nama
- Email
- Password
- Tanggal Lahir
- Tombol Daftar
- Tombol Reset

### Screenshot di VS code

![Latihan 3 VS code](media/screenshot/latihan3vsc.png)

### Screenshot Hasil di Browser

![Latihan 3 Browser](media/screenshot/latihan3browser.png)

---

## 4. Radio Button dan Checkbox

Radio button digunakan untuk memilih satu pilihan, sedangkan checkbox digunakan untuk memilih satu atau beberapa pilihan.

Contoh:

- Jenis Kelamin
- Keahlian HTML
- Keahlian CSS
- Keahlian JavaScript

### Screenshot di VS code

![Latihan 4 VS code](media/screenshot/latihan4vsc.png)

### Screenshot Hasil di Browser

![Latihan 4 Browser](media/screenshot/latihan4browser.png)

---

## 5. Select dan Textarea

Pada latihan ini digunakan:

- `<select>` untuk memilih Program Studi.
- `<textarea>` untuk memasukkan Alamat.

### Screenshot di VS code

![Latihan 5 VS code](media/screenshot/latihan5vsc.png)

### Screenshot Hasil di Browser

![Latihan 5 Browser](media/screenshot/latihan5browser.png)

---

## 6. Validasi Form

Validasi dasar diterapkan menggunakan beberapa atribut HTML, yaitu:

- `required`
- `minlength`
- `min`
- `max`
- `type`

Validasi digunakan agar data yang dimasukkan pengguna sesuai dengan ketentuan form.

### Screenshot di VS code

![Latihan 6 VS code](media/screenshot/latihan6vsc.png)

### Screenshot Hasil di Browser

![Latihan 6 Browser](media/screenshot/latihan6browser.png)

---

## 7. Semantic HTML

Semantic HTML digunakan untuk membuat struktur halaman menjadi lebih jelas.

Elemen yang digunakan:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<article>`
- `<aside>`
- `<footer>`

### Screenshot di VS code

![Latihan 7 VS code](media/screenshot/latihan7vsc.png)

### Screenshot Hasil di Browser

![Latihan 7 Browser](media/screenshot/latihan7browser.png)

---

## 8. Multimedia

Pada praktikum ini ditambahkan elemen multimedia berupa audio dan video menggunakan:

- `<audio>`
- `<video>`

File multimedia disimpan di dalam folder `media`.

### Screenshot di VS code

![Latihan 8 VS code](media/screenshot/latihan8vsc.png)

### Screenshot Hasil di Browser

![Latihan 8 Browser](media/screenshot/latihan8browser.png)

---

## 9. Proyek Mini - Biodata Mahasiswa

Proyek mini merupakan penggabungan materi yang telah dipelajari.

Halaman biodata mahasiswa menggunakan:

- Semantic HTML
- Tabel
- Form
- Input HTML
- Select
- Textarea
- Validasi form
- Multimedia

File proyek mini terdapat pada:

`biodata.html`

### Screenshot di VS code

![Latihan 9 VS code](media/screenshot/latihan9vsc.png)

### Screenshot Hasil di Browser

![Latihan 9 Browser](media/screenshot/latihan9browser.png)

---

# Jawab Pertanyaan Berikut

1. Apa fungsi `<table>`, `<tr>`, `<th>`, dan `<td>`?
2. Apa perbedaan `<th>` dan `<td>`?
3. Apa fungsi `colspan` pada tabel?
4. Apa fungsi `<form>` dalam HTML?
5. Apa perbedaan radio button dan checkbox?
6. Mengapa `<label>` sebaiknya terhubung dengan id input melalui atribut `for`?
7. Apa perbedaan `<textarea>` dengan input type text?
8. Apa fungsi semantic HTML seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, dan `<footer>`?
9. Apa fungsi `required`, `min`, `max`, dan `minlength`?
10. Apa perbedaan elemen `<audio>` dan `<video>`?

---

# Jawaban

1. `<table>` digunakan untuk membuat tabel, `<tr>` digunakan untuk membuat baris tabel, `<th>` digunakan untuk membuat sel header atau judul tabel, dan `<td>` digunakan untuk membuat sel data pada tabel.

2. `<th>` digunakan untuk membuat sel header atau judul pada tabel, sedangkan `<td>` digunakan untuk membuat sel data.

3. `colspan` digunakan untuk menggabungkan beberapa kolom menjadi satu sel.

4. `<form>` digunakan untuk membuat formulir yang dapat digunakan untuk menerima data dari pengguna.

5. Radio button digunakan untuk memilih satu pilihan dari beberapa pilihan, sedangkan checkbox memungkinkan pengguna memilih lebih dari satu pilihan.

6. `<label>` sebaiknya terhubung dengan `id` input melalui atribut `for` agar pengguna dapat mengklik teks label untuk memilih atau mengaktifkan input yang terkait.

7. `<textarea>` digunakan untuk memasukkan teks yang lebih panjang dan dapat terdiri dari beberapa baris, sedangkan `<input type="text">` umumnya digunakan untuk memasukkan teks satu baris.

8. Semantic HTML digunakan untuk memberikan struktur dan makna yang jelas pada bagian-bagian halaman web, seperti header, navigasi, konten utama, section, artikel, informasi tambahan, dan footer.

9. `required` membuat input wajib diisi, `min` menentukan nilai minimum, `max` menentukan nilai maksimum, dan `minlength` menentukan jumlah karakter minimum.

10. `<audio>` digunakan untuk menampilkan atau memutar audio, sedangkan `<video>` digunakan untuk menampilkan atau memutar video.


## Struktur Repository

```text
Lab2Web/
├── index.html
├── biodata.html
├── media/
│   ├── audio.mp3
│   └── video.mp4
├── screenshots/
└── README.md