
## 🛠️ Langkah-langkah Pengeditan

### 1. **Persiapan Awal**
- Download atau clone template ini
- Buka folder project di text editor (VS Code, Sublime Text, dll)
- Buka file `index.html` untuk mulai mengedit

### 2. **Mengganti Konten Teks**

#### a. Mengubah Judul Website
```html
<title>Website Praktikum SMK</title> 
```
Ganti teks dalam tag `<title>` dengan nama website Anda

#### b. Mengubah Header/Navigasi
```html
<a class="navbar-brand" href="#">Logo</a>
...
<li class="nav-item">
    <a class="nav-link active" href="#home">Home</a>
</li>
```
Ganti teks:
- `Logo` dengan nama website/merek Anda
- `Home`, `Tentang`, dll dengan menu yang diinginkan

#### c. Mengubah Hero Section
```html
<h1 class="display-4 fw-bold mb-4">Selamat Datang di Website Kami</h1>
<p class="lead mb-4">Ini adalah template sederhana...</p>
<a href="#about" class="btn btn-primary btn-lg">Pelajari Lebih Lanjut</a>
```
Ganti dengan teks dan tombol yang sesuai

### 3. **Mengganti Gambar**

#### a. Gambar Hero Section
```html
<img src="https://via.placeholder.com/600x400" alt="Hero Image" class="img-fluid rounded">
```
Ganti dengan:
```html
<img src="images/nama-file-gambar-anda.jpg" alt="Deskripsi gambar" class="img-fluid rounded">
```

#### Cara menambahkan gambar:
1. Simpan gambar Anda di folder `images/`
2. Ganti `nama-file-gambar-anda.jpg` dengan nama file gambar Anda
3. Sesuaikan `alt` dengan deskripsi gambar

### 5. **Mengedit Galeri**

#### a. Mengganti Gambar Galeri
```html
<img src="https://via.placeholder.com/400x300" class="card-img-top" alt="Gallery Image 1">
```
Ganti dengan gambar Anda di folder `images/`

#### b. Mengedit Deskripsi Galeri
```html
<h5 class="card-title">Judul Gambar 1</h5>
<p class="card-text">Deskripsi singkat tentang gambar ini.</p>
```
Ganti dengan judul dan deskripsi yang sesuai

### 6. **Mengedit Bagian Kontak**
```html
<li><i class="fas fa-map-marker-alt me-2"></i> Alamat lengkap</li>
<li><i class="fas fa-phone me-2"></i> (021) 12345678</li>
<li><i class="fas fa-envelope me-2"></i> email@contoh.com</li>
```
Ganti dengan informasi kontak yang valid

### 7. **Mengedit Footer**
```html
<p class="mb-0">&copy; 2023 Nama Sekolah/Perusahaan. All rights reserved.</p>
```
Ganti dengan informasi copyright yang sesuai

## 🎨 Kustomisasi Tampilan

### 1. Mengubah Warna
Edit di file `css/style.css`:
```css
.navbar {
    background-color: #warna-baru;
}

.btn-primary {
    background-color: #warna-baru;
    border-color: #warna-baru;
}
```
Ganti `#warna-baru` dengan kode warna yang diinginkan

### 2. Mengubah Font
Tambahkan di bagian `<head>`:
```html
<link href="https://fonts.googleapis.com/css2?family=NamaFont&display=swap" rel="stylesheet">
```
Lalu di CSS:
```css
body {
    font-family: 'NamaFont', sans-serif;
}
```
