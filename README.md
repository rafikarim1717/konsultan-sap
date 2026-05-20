# Website Compro Jasa PBG/IMB Adnan

> **"Solusi Mudah, Urus Perizinan Tanpa Ribet!"**

---

## 1. Project Overview

**Nama Project:** Website Company Profile — Jasa PBG/IMB Adnan  
**Deskripsi:** Website company profile untuk jasa pengurusan perizinan bangunan (PBG/IMB) dan perizinan lainnya di wilayah DKI Jakarta. Website dirancang untuk menarik calon klien, menjelaskan layanan yang tersedia, dan memudahkan proses konsultasi melalui WhatsApp.  
**Status:** 🔄 In Development  
**Author:** Adnan | WA: +62 858-9201-3170  

---

## 2. Project Structure

```
konsultan-sap/
├── homepage.html        ✅ Selesai
├── layanan.html         ✅ Selesai
├── cara-kerja.html      🔄 In Progress
├── tentang.html         ⏳ Belum Dibuat
├── kontak.html          ⏳ Belum Dibuat
└── README.md
```

---

## 3. Halaman & Status

| Halaman      | File            | Status         | URL Path    |
|--------------|-----------------|----------------|-------------|
| Beranda      | homepage.html   | ✅ Selesai     | /           |
| Layanan      | layanan.html    | ✅ Selesai     | /layanan    |
| Cara Kerja   | cara-kerja.html | 🔄 In Progress | /cara-kerja |
| Tentang Kami | tentang.html    | ⏳ Belum Dibuat | /tentang   |
| Kontak       | kontak.html     | ⏳ Belum Dibuat | /kontak    |

---

## 4. Design System

### Warna

| Nama       | HEX       | Penggunaan                          |
|------------|-----------|-------------------------------------|
| Navy       | `#0D1B3E` | Background utama, navbar, footer    |
| Gold       | `#C9A84C` | Aksen, tombol CTA, highlight        |
| Gold Light | `#F5E6C0` | Background section light            |
| White      | `#FFFFFF` | Background card, teks di atas navy  |
| Gray BG    | `#F5F5F5` | Background section alternatif       |
| Gray Text  | `#555555` | Body text, deskripsi                |

### Typography

| Elemen     | Font             | Weight | Size (Desktop) |
|------------|------------------|--------|----------------|
| Heading    | Playfair Display | 700    | 32–48px        |
| Subheading | Playfair Display | 600    | 20–28px        |
| Body       | Inter            | 400    | 16px           |
| Caption    | Inter            | 400    | 14px           |
| Button     | Inter            | 600    | 14–16px        |

### Komponen Reusable

Komponen berikut **wajib konsisten** di seluruh halaman:

| Komponen              | Keterangan                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| **Navbar**            | Sticky/fixed, background navy (`#0D1B3E`), z-index: 9999                  |
| **Footer**            | Background navy, 3 kolom: Brand / Navigasi / Kontak                       |
| **Floating WA Button**| Fixed bottom-right, warna hijau WhatsApp, link ke wa.me/6285892013170    |
| **CTA Section**       | Background navy, tombol aksi berwarna gold                                |
| **Trust Badges Bar**  | Background gold, menampilkan 4 item keunggulan/kepercayaan                |

---

## 5. Sections Per Halaman

### homepage.html

1. **Hero Section** — Headline utama + 2 tombol CTA + badge area DKI Jakarta
2. **Stats Bar** — 500+ izin terbit | 5+ tahun pengalaman | 100% legal | konsultasi gratis
3. **Layanan Utama PBG/IMB** — Grid 6 card layanan inti
4. **Layanan Lainnya** — 6 item dalam format list
5. **Keunggulan / Why Us** — 4 card keunggulan + highlight box pembeda
6. **Cara Kerja** — Preview 4 langkah singkat (teaser halaman cara-kerja)
7. **CTA Bottom** — Ajakan konsultasi dengan tombol WA
8. **Footer**

---

### layanan.html

1. **Mini Hero + Breadcrumb** — Judul halaman + navigasi breadcrumb
2. **Intro Teks** — Pengantar layanan yang tersedia
3. **Section PBG/IMB** — 6 card layanan, layout 3 kolom
4. **Highlight Box Keunggulan PBG/IMB** — Kotak navy dengan poin-poin keunggulan
5. **Section Perizinan Lainnya** — 6 item, layout 2 kolom
6. **Trust Badges Bar** — 4 badge kepercayaan, background gold
7. **CTA Section** — Ajakan konsultasi

---

### cara-kerja.html *(In Progress)*

1. **Mini Hero + Breadcrumb** — Judul halaman + navigasi breadcrumb
2. **Intro Teks** — Pengantar proses pengurusan izin
3. **4 Step Visual Horizontal** — Tampilan langkah-langkah dengan garis penghubung
4. **Detail Ekspansi Tiap Step** — 4 card dengan penjelasan lengkap per langkah
5. **FAQ Accordion** — 5 pertanyaan umum yang dapat dibuka/tutup
6. **CTA Section** — Ajakan konsultasi

---

### tentang.html *(Belum Dibuat)*

1. **Mini Hero** — Judul halaman
2. **Profil Bisnis & Story** — Latar belakang dan cerita berdirinya usaha
3. **Area Layanan** — Fokus wilayah DKI Jakarta (peta/deskripsi)
4. **Regulasi Terkini** — Informasi PP No. 16 Tahun 2021 tentang PBG
5. **CTA Section** — Ajakan konsultasi

---

### kontak.html *(Belum Dibuat)*

1. **Mini Hero** — Judul halaman
2. **Tombol WA Besar** — Tombol konsultasi langsung via WhatsApp
3. **Form Konsultasi** — Field: Nama, Nomor WA, Jenis Kebutuhan
4. **Embed Google Maps** — Peta area layanan DKI Jakarta
5. **Jam Operasional** — Informasi waktu layanan

---

## 6. Kontak & Info Bisnis

| Info         | Detail                                       |
|--------------|----------------------------------------------|
| Nama         | Adnan                                        |
| WhatsApp     | +62 858-9201-3170                            |
| Link WA      | https://wa.me/6285892013170                 |
| Area Layanan | Khusus Wilayah DKI Jakarta                   |
| Tagline      | "Solusi Mudah, Urus Perizinan Tanpa Ribet!" |

---

## 7. Catatan Teknis

- **Struktur file:** Setiap halaman adalah satu file HTML tunggal — CSS dan JavaScript ditulis secara inline, tidak ada file eksternal terpisah.
- **Responsif:** Menggunakan pendekatan mobile-first, tampilan optimal di semua ukuran layar.
- **Smooth Scroll:** Navigasi antar section menggunakan smooth scroll bawaan CSS.
- **Animasi:** Fade-in on scroll menggunakan Intersection Observer API (tanpa library eksternal).
- **Tombol WhatsApp:** Semua tombol CTA dan floating button mengarah ke `https://wa.me/6285892013170`.
- **Tidak ada backend:** Tidak ada server-side processing. Form (jika ada) bersifat dekoratif atau diarahkan ke WhatsApp.

---

## 8. Roadmap

### Pengerjaan Halaman

- [x] `homepage.html` — Halaman Beranda
- [x] `layanan.html` — Halaman Layanan
- [ ] `cara-kerja.html` — Halaman Cara Kerja *(in progress)*
- [ ] `tentang.html` — Halaman Tentang Kami
- [ ] `kontak.html` — Halaman Kontak

### Quality Assurance

- [ ] Testing responsif di semua halaman (mobile, tablet, desktop)
- [ ] Review copy & konten final
- [ ] Upload ke hosting

---

*Terakhir diperbarui: Mei 2026*
