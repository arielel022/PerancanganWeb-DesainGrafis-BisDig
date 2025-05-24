# PerancanganWeb-DesainGrafis-BisDig

## 📸 Halaman Profil Fotografer Profesional

Repository ini berisi contoh **halaman profil** untuk seorang fotografer profesional yang menampilkan gambar, deskripsi, dan tautan media sosial menggunakan struktur dasar HTML5 yang baik dan semantik.

---

## 🎯 Tujuan

Membangun halaman profil yang:

- Menampilkan **foto profil** fotografer
- Memuat **deskripsi singkat** tentang sang fotografer
- Menyediakan **tautan media sosial** untuk memperluas jaringan dan profesionalisme
- Menggunakan elemen HTML5 yang semantik dan sesuai standar

---

## 🏗️ Struktur Dasar HTML5

Halaman profil ini menggunakan struktur HTML5 yang terdiri dari:

- `<header>`: Bagian atas halaman, berisi judul dan navigasi
- `<main>`: Konten utama halaman, berisi profil fotografer
- `<section>`: Pembagian konten yang spesifik seperti galeri gambar dan bio
- `<footer>`: Bagian bawah halaman, berisi hak cipta dan info tambahan

---

## 📝 Contoh Kode HTML

```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Profil Fotografer Profesional</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>John Doe - Fotografer Profesional</h1>
  </header>
  <main>
    <section id="profile">
      <img src="foto-profil.jpg" alt="Foto John Doe" />
      <p>John Doe adalah fotografer profesional dengan pengalaman lebih dari 10 tahun dalam bidang fotografi landscape dan potret.</p>
    </section>
    <section id="social-media">
      <h2>Temukan Saya di</h2>
      <ul>
        <li><a href="https://instagram.com/johndoe" target="_blank">Instagram</a></li>
        <li><a href="https://twitter.com/johndoe" target="_blank">Twitter</a></li>
        <li><a href="https://linkedin.com/in/johndoe" target="_blank">LinkedIn</a></li>
      </ul>
    </section>
  </main>
  <footer>
    <p>© 2025 John Doe Photography. All rights reserved.</p>
  </footer>
</body>
</html>
