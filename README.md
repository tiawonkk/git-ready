# GitReady — DevCard

DevCard adalah halaman kartu profil kelompok interaktif untuk studi kasus Workshop Git & GitHub. Halaman ini menampilkan profil tiga anggota, mendukung pergantian tema, dan menyediakan penghitung like terpisah untuk setiap anggota.

---

## Visualisasi

Jalankan proyek secara lokal dengan langkah pada bagian [How to Run](#how-to-run) untuk melihat dan mencoba seluruh interaksi halaman.

---

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Git & GitHub

---

## Fitur Utama

- [x] Navigasi profil tiga anggota
- [x] Toggle Dark Mode
- [x] Like Counter interaktif untuk setiap anggota
- [x] Responsive layout untuk desktop dan perangkat mobile
- [x] Informasi per anggota berupa nama, role, foto, deskripsi, dan skill

---

## Contribution

| Nama | Role | Kontribusi |
|---|---|---|
|  I Gede Abi Bhakti P. | Project Initiator | Membuat repository, mengatur akses kolaborator, commit `index.html` |
| Christian Immanuel V. | Styling Engineer | Membuat branch `styling`, menambahkan & menghubungkan `style.css` |
| I Wayan Putra Riana P. | Script Engineer | Membuat branch `scripting`, menambahkan & menghubungkan `script.js` |

---

## How to Run

1. Clone repository ini:

   ```bash
   git clone https://github.com/igdabibhakti/gitReady.git
   ```

2. Masuk ke folder proyek:

   ```bash
   cd gitReady
   ```

3. Buka `index.html` menggunakan browser.

Proyek ini tidak memerlukan instalasi dependency atau proses build.

---

## Struktur Project

```text
gitReady/
├── index.html   # Struktur dan konten halaman
├── style.css    # Tampilan, dark mode, dan responsive layout
├── script.js    # Data anggota dan interaksi halaman
└── README.md    # Dokumentasi project
```

---

## Feature Improvement

Ide pengembangan lanjutan:

- Menyimpan tema dan jumlah like ke `localStorage`
- Mengganti data serta foto placeholder dengan profil anggota kelompok
- Menambahkan animasi transisi saat profil berganti
- Mengaktifkan deployment otomatis ke GitHub Pages
