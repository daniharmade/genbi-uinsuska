# Website Profil GenBI Komisariat UIN Suska Riau

Repository ini berisi source code untuk website profil organisasi
**Generasi Baru Indonesia (GenBI)** Komisariat UIN Sultan Syarif Kasim
Riau. Website ini dirancang dengan tampilan modern, responsif, dan
informatif untuk memperkenalkan organisasi kepada publik.

## 📋 Fitur Utama

-   **Desain Responsif**
-   **Modern UI**
-   **Navigasi Interaktif**
-   **Halaman Detail**
    -   **Beranda (index.html)**
    -   **Detail Divisi (detail-divisi.html)**
    -   **Detail Kegiatan (detail-kegiatan.html)**

## 🛠️ Teknologi yang Digunakan

-   HTML5\
-   Tailwind CSS (CDN)\
-   JavaScript (Vanilla)\
-   Google Fonts (Poppins)\
-   Font Awesome (CDN)

## 📂 Struktur File

    .
    ├── index.html
    ├── detail-divisi.html
    ├── detail-kegiatan.html
    ├── README.md
    └── asset/
        └── img/
            ├── Logo.png
            └── FotoBersama.JPG

## 🚀 Cara Menjalankan

1.  Download/clone repository.
2.  Pastikan koneksi internet aktif.
3.  Buka `index.html` di browser.

## 🎨 Panduan Kustomisasi

### 1. Warna Tema

``` js
colors: {
    genbi: {
        blue: '#0044cc',
        dark: '#002a80',
        red: '#ff0000',
        redhover: '#cc0000'
    }
}
```

### 2. Mengganti Gambar

-   Ganti `Logo.png` di folder `asset/img/`
-   Ubah path `<img src="asset/img/Logo.png">` bila perlu

### 3. Menambah Berita

Copy kartu berita di section `#kegiatan` dan sesuaikan teks, gambar,
serta link.

## 🤝 Kontribusi

Silakan fork dan kembangkan sesuai kebutuhan.

Dibuat untuk **GenBI Komisariat UIN Suska Riau**.
