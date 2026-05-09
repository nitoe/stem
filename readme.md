# 📚 Panduan Pembelajaran STEM — Hub Guru Indonesia

> Sumber belajar digital berjenjang untuk guru Indonesia.  
> Berdasarkan **Panduan Pembelajaran STEM** · BSKAP · Kemendikdasmen RI · 2025.

🌐 **Live:** https://nitoe.github.io/stem/

---

## 📁 Struktur Proyek

```
stem/
├── index.html                  ← Halaman utama / landing hub
├── readme.md                   ← Dokumentasi ini
├── changelog.md                ← Riwayat perubahan
│
├── level1/
│   ├── dokumen.html            ← L1: Dokumen bacaan mandiri
│   └── presentasi.html         ← L1: Presentasi + catatan presenter
│
├── level2/
│   ├── dokumen.html            ← L2: Panduan perancangan & pelaksanaan
│   └── presentasi.html         ← L2: Presentasi workshop implementasi
│
└── level3/
    ├── dokumen.html            ← L3: Referensi mendalam + checklist
    └── presentasi.html         ← L3: Presentasi sesi refleksi & ekosistem
```

---

## 🎯 Prinsip Desain

### Dua Format per Tingkat
Setiap level menyediakan **dua format** untuk mengakomodasi gaya belajar yang berbeda:

| Format | Untuk Siapa | Cara Pakai |
|--------|-------------|------------|
| **Dokumen Bacaan** | Guru yang belajar mandiri | Dibaca sendiri, bisa diprint, dijadikan referensi |
| **Presentasi + Catatan Presenter** | Pelatih / fasilitator | Dibawakan dalam workshop atau sesi pelatihan guru |

Navigasi presentasi: tombol `←` `→`, atau keyboard `Arrow Keys`. Tekan `N` untuk toggle catatan presenter.

### Scaffolding Tiga Tingkat

| Level | Nama | Untuk Siapa | Warna Tema |
|-------|------|-------------|------------|
| **Level 1** | 🌱 Pemula | Guru yang belum pernah/baru mengenal STEM | Biru |
| **Level 2** | 🌿 Berkembang | Guru yang paham konsep, siap merancang pembelajaran | Hijau |
| **Level 3** | 🌳 Mahir | Guru berpengalaman yang ingin membangun ekosistem | Amber |

---

## 📖 Konten per Level

### 🌱 Level 1 — Pemula
**Dokumen:** Penjelasan dari nol — sejarah STEM, definisi S-T-E-M masing-masing, 3 karakteristik utama, 3 perspektif implementasi, 5 langkah pertama di kelas, contoh aktivitas PAUD & SD.

**Presentasi (10 slide):** Pengenalan STEM untuk rapat guru atau workshop sekolah pertama. Catatan presenter berisi pertanyaan pemantik, aktivitas singkat, dan tips fasilitasi.

### 🌿 Level 2 — Berkembang
**Dokumen:** 4 langkah perencanaan sistematis, alur praktik saintifik (6 tahap), alur praktik enjinering (6 tahap), perbandingan model PjBL/PBL/5E, template TP STEM, asesmen autentik per tahap, contoh modul SD/SMP/SMA, lingkungan belajar.

**Presentasi (12 slide):** Workshop implementasi dengan aktivitas: pemetaan masalah lokal, tabel integrasi CP, pembagian asesmen antar mapel. Dilengkapi form komitmen 1-1-1.

### 🌳 Level 3 — Mahir
**Dokumen:** Tangga integrasi multi→inter→transdisipliner, 7 pilar kemitraan strategis, peran pemangku kepentingan (dinas s.d. orang tua), UDL & adaptasi SLB, P5 berbasis STEM, ekstrakurikuler, roadmap PLC 4 fase, checklist mandiri 15 item (tersimpan di localStorage).

**Presentasi (11 slide):** Sesi refleksi & pengembangan strategis dengan diskusi peer-to-peer. Catatan presenter dirancang untuk fasilitasi kolaboratif, bukan ceramah.

---

## 🎨 Teknologi

- **HTML + CSS + Vanilla JS** — tanpa framework, ringan, hostable di mana saja
- **Font:** DM Serif Display + Plus Jakarta Sans (Google Fonts)
- **Tema:** Dark navy/teal/amber, warna berbeda per level
- **Fitur:** Scroll progress bar, sticky sidebar nav dengan active state, particle canvas background (index), checklist tersimpan (L3), keyboard navigation (presentasi)
- **Responsif:** Mobile-friendly dengan mobile nav bar

---

## 🚀 Deploy ke GitHub Pages

1. Push semua file ke branch `main` di repo `nitoe/stem`
2. Settings → Pages → Source: `main`, folder `/ (root)`
3. Akses: https://nitoe.github.io/stem/

---

## 📖 Sumber Dokumen

**Judul:** Panduan Pembelajaran STEM untuk Guru PAUD, Pendidikan Dasar dan Menengah  
**Penerbit:** Pusat Kurikulum dan Pembelajaran, BSKAP, Kemendikdasmen RI  
**Tahun:** 2025  
**Pengarah:** Prof. Dr. Abdul Mu'ti, M.Ed.

---

*v1.2.0 · Mei 2025*
