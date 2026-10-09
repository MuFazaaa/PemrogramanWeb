# Portofolio Personal / Resume Digital

Halaman portofolio personal yang informatif, terstruktur, dan responsif, dibangun **murni dengan HTML5 dan CSS3**. Tidak memakai framework CSS (Bootstrap, Tailwind, dan sejenisnya) dan tidak memakai JavaScript.

**Demo:** `https://github.com/MuFazaaa/PemrogramanWeb.git` 

## Fitur

- **Struktur semantik**: `header`, `nav`, `main`, `section`, `article`, `ol`, `time`, dan `footer`.
- **Bagian lengkap**: hero, tentang saya, keahlian, pengalaman kerja, proyek, pendidikan, dan kontak.
- **Progress bar scroll** di bagian atas layar.
- **Animasi hero**: nama muncul bertahap, role berganti otomatis, dan cincin gradien berputar.
- **Penghitung angka** pada statistik.
- **Bar keahlian animatif** dan efek muncul saat di-scroll.
- **Marquee teknologi** yang berhenti saat di-hover.
- **Timeline pengalaman** dengan penanda berdenyut.
- **Filter proyek** (Semua / Web / Desain UI) tanpa JavaScript, memakai radio button dan `:has()`.
- **Pemilih warna aksen** (biru, magenta, hijau).
- **Mode gelap dan terang** otomatis mengikuti pengaturan perangkat.
- **Responsif** dari ponsel sampai desktop.
- **Aksesibilitas**: fokus keyboard terlihat jelas dan `prefers-reduced-motion` dihormati.

## Teknologi

| Teknologi | Kegunaan |
|---|---|
| HTML5 | Struktur dokumen |
| CSS3 | Layout (Grid, Flexbox), animasi, tema, dan responsivitas |
| Google Fonts | Bricolage Grotesque dan Figtree |

## Struktur Folder

```
Portofolio/
├── index.html    # Struktur halaman
├── style.css     # Seluruh gaya dan animasi
├── assets/       # Foto dan gambar
└── README.md
```

## Cara Menjalankan

1. Unduh atau clone repositori ini:
   ```bash
   git clone https://github.com/MuFazaaa/PemrogramanWeb.git
   ```
2. Buka foldernya di VS Code (*File → Open Folder*).
3. Klik kanan `index.html`, lalu pilih **Open with Live Server** (ekstensi Live Server oleh Ritwick Dey), atau klik dua kali `index.html` untuk membukanya langsung di browser.

## Kustomisasi

- **Konten**: ubah nama, pengalaman, proyek, dan email langsung di `index.html`.
- **Warna**: ubah variabel `--ac` dan `--ac2` di bagian `:root` pada `style.css`.
- **Foto**: simpan gambar di folder `assets/`, lalu ganti elemen inisial pada bagian hero dengan tag `<img>`.

## Deploy ke GitHub Pages

1. Unggah semua file ke repositori GitHub.
2. Buka **Settings → Pages**.
3. Pada **Source**, pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
4. Tunggu beberapa menit sampai situs aktif di `https://github.com/MuFazaaa/PemrogramanWeb.git`.

## Dukungan Browser

Dirancang untuk browser modern (Chrome, Edge, Safari, dan Firefox versi terbaru). Beberapa animasi, yaitu efek scroll-driven (`animation-timeline`) dan penghitung angka (`@property`), membutuhkan dukungan browser modern. Di browser lama, konten tetap tampil penuh tanpa efek tersebut.

## Lisensi

Proyek ini dirilis di bawah lisensi [MIT](LICENSE). *(Hapus bagian ini atau ganti sesuai kebutuhan.)*

## Kontak

**Nama Anda**
- Email: `muhammadfayyadhudzaqi@gmail.com`
- GitHub: [@MuFazaaa](https://github.com/MuFazaaa)
