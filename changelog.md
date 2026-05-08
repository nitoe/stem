# 📋 Changelog

Semua perubahan signifikan pada proyek ini akan dicatat di sini.
Format mengacu pada [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
Versi mengikuti [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Direncanakan
- `level1/index.html` — Panduan Pemula dalam format dokumen HTML interaktif
- `level2/index.html` — Presentasi interaktif dengan catatan presenter untuk tingkat berkembang
- `level3/index.html` — Referensi mendalam dan checklist untuk tingkat mahir
- Halaman glosarium istilah STEM
- Mode cetak (print-friendly) untuk semua tingkat
- Versi ringkas 1-halaman (cheat sheet) per tingkat

---

## [1.0.0] — 2025-05-08

### Ditambahkan
- `index.html` — Halaman utama (landing hub) dengan:
  - Hero section dengan animasi canvas particle
  - Navigasi sticky responsif
  - 4 pillar STEM (S-T-E-M) visual
  - 3 kartu level berjenjang (Pemula, Berkembang, Mahir)
  - Section "Cara Belajar" (4 langkah)
  - Peta scaffolding visual konten (8 tahapan)
  - Feature box & kutipan dari panduan resmi
  - Footer lengkap dengan navigasi & metadata
  - Scroll progress bar
  - Reveal animation on scroll
  - Tema dark navy/teal/amber profesional
  - Font: DM Serif Display + Plus Jakarta Sans
  - Responsif untuk mobile dan desktop
- `readme.md` — Dokumentasi lengkap proyek:
  - Struktur folder
  - Peta tingkat belajar & konten per level
  - Panduan deploy GitHub Pages
  - Keterangan sumber dokumen resmi
- `changelog.md` — File riwayat perubahan ini

### Keputusan Desain
- Memilih tema **dark** agar tidak melelahkan mata saat dibaca lama (professional development)
- Format per tingkat dibedakan secara eksplisit: dokumen vs presentasi vs referensi
- Scaffolding tidak mengharuskan urutan linear — guru bisa masuk di titik mana pun
- Semua file statis (HTML/CSS/JS) tanpa dependency build tool agar mudah dihost di mana saja
- Animasi particle background dipilih untuk merefleksikan "koneksi antar disiplin" dalam STEM

---

## Konvensi Versi

| Kode | Artinya |
|------|---------|
| **Major** (1.x.x) | Penambahan level baru atau perubahan struktur besar |
| **Minor** (x.1.x) | Penambahan fitur atau halaman baru dalam level yang ada |
| **Patch** (x.x.1) | Perbaikan teks, typo, bug tampilan, atau update konten minor |

---

*Panduan STEM Hub Guru Indonesia · Dimulai Mei 2025*
