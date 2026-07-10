# Aurelius & Associates Law Office

**Firma Hukum Butik dengan Estetika Heritage Museum Ticket**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-aurelius--law--office.vercel.app-gold?style=for-the-badge)](https://aurelius-law-office.vercel.app)
[![Built with Astro](https://img.shields.io/badge/Built%20with-Astro%207-FF5D01?style=flat-square&logo=astro)](https://astro.build)
[![License MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

---

## 📖 Deskripsi Project

**Aurelius & Associates** adalah firma hukum butik yang menghadirkan pengalaman layanan hukum modern dengan standar transparansi tertinggi. Website ini dirancang dengan estetika **heritage dan museum ticket** yang elegan, mencerminkan profesionalisme, integritas, dan komitmen firma terhadap perlindungan aset hukum klien.

Firma menawarkan spesialisasi dalam empat pilar hukum bernilai tinggi:
- **Hukum Korporasi & Merger & Akuisisi (M&A)**
- **Hak Kekayaan Intelektual (HAKI) & Teknologi**
- **Litigasi Komersial & Pidana Bisnis**
- **Perlindungan Aset & Hukum Keluarga**

Dengan tim advokat berpengalaman dari universitas terkemuka dunia dan respons layanan darurat **24/7**, Aurelius & Associates berkomitmen memberikan perlindungan hukum tanpa kompromi.

---

## 🎨 Tema Desain

Website menggunakan **heritage palette** yang terinspirasi dari estetika museum dan tiket masuk premium:

- **Warna Utama**: Emas (#C8943E), Burgundy (#6B2E3E), Deep Brown (#4A3728)
- **Latar Belakang**: Cream & warm neutrals (#FAF6EF) untuk profesionalitas hangat
- **Efek Glassmorphism**: Kartu semi-transparan dengan border emas untuk kesan elegan
- **Typography**: Playfair Display (heading) & EB Garamond (body) untuk sentuhan klasik

---

## 🛠️ Teknologi

| Teknologi | Versi | Deskripsi |
|-----------|-------|-----------|
| **Astro** | ^7.0.3 | Framework static site generator modern |
| **Node.js** | >=22.12.0 | Runtime JavaScript server-side |
| **TypeScript** | - | Type safety untuk development |
| **CSS3** | - | Styling dengan variable dan grid system |
| **HTML5 Semantik** | - | Markup yang accessibility-first |

**Tools Deployment:**
- **Vercel**: Platform hosting dengan preview otomatis
- **Git**: Version control dan CI/CD workflow

---

## ✨ Fitur Utama

### 1. **Homepage Premium**
- Hero section dengan messaging value proposition
- Showcase 3 pilar utama firma (Transparansi, Keahlian, Respons Cepat)
- Emergency Hub untuk akses cepat layanan darurat
- Legal Health Quiz untuk diagnosa kebutuhan hukum klien
- CTA Band untuk mendorong conversion konsultasi

### 2. **Halaman Tentang Kami**
- Timeline 4 fase perjalanan hukum klien
- Statistics panel dengan metrik kredibilitas (100% Transparansi, 98.4% Penyelesaian Non-Litigasi)
- Narasi firma yang menekankan redefinisi layanan hukum modern

### 3. **Halaman Area Hukum**
- 4 kartu praktek dengan deskripsi lengkap setiap spesialisasi
- **Fee Calculator** interaktif untuk transparansi biaya konsultasi
- Informasi mendetail tentang layanan korporasi, HAKI, litigasi, dan aset keluarga

### 4. **Halaman Tim Advokat**
- Profil 8 advokat dengan kredensial internasional
- Spesialisasi individual dan background pendidikan
- Fitur cetak profesional (Ctrl + P) untuk print-friendly layout
- Avatar dinamis berdasarkan nama advokat
- Verifikasi PERADI compliance

### 5. **Halaman Hubungi Kami**
- **Form Konsultasi Rahasia** terintegrasi dengan Formspree
- Kategori legal dinamis (Korporasi, HAKI, Pidana Bisnis, Darurat)
- **Accordion Panduan Kepatuhan**: Protokol 4 langkah untuk kasus penggeledahan
- Upload dokumen rahasia dengan UI drag-and-drop
- Emergency Hub dengan nomor WhatsApp 24/7

### 6. **Halaman Sukses**
- Konfirmasi pengiriman form konsultasi
- Instruksi follow-up dan timeline respons

### 7. **Layout & Komponen Reusable**
- **MainLayout**: Template master untuk konsistensi
- **Header**: Navigasi desktop/mobile responsive + dark mode toggle
- **Footer**: CTA dan branding firma
- **Components**:
  - `CardPractice`: Grid card untuk area hukum
  - `CardAttorney`: Profil advokat interaktif
  - `CaseTimeline`: Timeline visual alur layanan
  - `FeeCalculator`: Kalkulator biaya
  - `LegalHealthQuiz`: Quiz diagnosa 3 pertanyaan
  - `EmergencyHub`: Tombol darurat dan WhatsApp
  - `SectionHeader`: Reusable section title dengan badge
  - `Button`: Komponen tombol dengan variant (gold solid, outline, emergency)
  - `OrnamentalFrame`: Dekorasi border heritage
  - `HeritageDivider`: Pemisah visual tematik
  - `ScaleIcon`: Logo skala hukum minimal

### 8. **Dark Mode**
- Toggle tema light/dark di header
- Persist preferensi ke localStorage
- CSS custom properties untuk smooth transition
- WCAG compliance untuk accessibility

### 9. **Responsive Design**
- Mobile-first approach
- Breakpoint responsive: desktop (992px+) dan tablet/mobile
- Hamburger menu dengan overlay
- Touch-friendly CTA buttons

---

## 📁 Struktur Folder

```
firma-hukum-praktikum/
├── src/
│   ├── pages/
│   │   ├── index.astro               # Homepage
│   │   ├── tentang-kami.astro        # About page
│   │   ├── area-hukum.astro          # Legal practice areas
│   │   ├── tim-kami.astro            # Team page
│   │   ├── kontak.astro              # Contact form & emergency protocol
│   │   └── sukses.astro              # Success confirmation page
│   │
│   ├── layouts/
│   │   └── MainLayout.astro          # Master layout template
│   │
│   ├── components/
│   │   ├── Header.astro              # Navigation + dark mode toggle
│   │   ├── Footer.astro              # Footer branding
│   │   ├── Button.astro              # Reusable button component
│   │   ├── SectionHeader.astro       # Section title + badge
│   │   ├── CardPractice.astro        # Practice area card
│   │   ├── CardAttorney.astro        # Attorney profile card
│   │   ├── CaseTimeline.astro        # Service journey timeline
│   │   ├── FeeCalculator.astro       # Fee transparency calculator
│   │   ├── LegalHealthQuiz.astro     # Legal needs diagnosis quiz
│   │   ├── EmergencyHub.astro        # 24/7 emergency contact
│   │   ├── CTABand.astro             # Call-to-action banner
│   │   ├── OrnamentalFrame.astro     # Heritage decorative frame
│   │   ├── HeritageDivider.astro     # Visual section divider
│   │   ├── ScaleIcon.astro           # Law scale icon logo
│   │   └── [other components]
│   │
│   └── styles/
│       └── global.css                 # Global styling (CSS variables, heritage palette)
│
├── public/                            # Static assets (fonts, images)
├── dist/                              # Build output (generated)
├── astro.config.mjs                   # Astro configuration
├── tsconfig.json                      # TypeScript configuration
├── package.json                       # Dependencies & scripts
└── README.md                          # Dokumentasi ini
```

---

## 🚀 Cara Instalasi & Setup

### Prasyarat
- **Node.js** ≥ 22.12.0
- **npm** atau **pnpm** package manager
- **Git** untuk version control

### 1. Clone Repository
```bash
git clone https://github.com/ahmazing-null/aurelius-law-office.git
cd aurelius-law-office
```

### 2. Install Dependencies
```bash
npm install
# atau
pnpm install
```

### 3. Menjalankan Development Server
```bash
npm run dev
```
Server akan berjalan di `http://localhost:3000`

### 4. Build untuk Production
```bash
npm run build
```
Output akan di-generate di folder `dist/`

### 5. Preview Build Production
```bash
npm run preview
```
Preview build lokal sebelum deploy ke Vercel

---

## 📝 Scripts npm

```bash
# Development
npm run dev          # Jalankan Astro dev server (hot reload)

# Production
npm run build        # Build static site untuk production
npm run preview      # Preview build production lokal

# Utilitas
npm run astro        # Akses CLI Astro langsung
```

---

## 🎯 Fitur Spesifik yang Menonjol

### ✅ Transparansi Biaya
- **Fee Calculator** interaktif di halaman Area Hukum
- Breakdown jelas untuk setiap kategori legal
- Estimasi biaya konsultasi vs litigasi

### ✅ Emergency 24/7
- Tombol darurat merah terintegrasi di seluruh halaman
- Link WhatsApp langsung dengan pre-filled message
- Nomor emergency: **+62 851-7160-5225**

### ✅ Legal Health Quiz
- 3 pertanyaan diagnosa untuk klien
- Rekomendasi area hukum berdasarkan jawaban
- UX interaktif untuk engagement

### ✅ Panduan Kepatuhan
- 4 langkah protokol saat penggeledahan aparat
- Accordion expandable untuk kemudahan membaca
- Referensi KUHAP dan hak konstitusional

### ✅ Form Konsultasi Secure
- Terintegrasi dengan **Formspree** untuk email backend
- Honeypot field anti-spam
- Upload file opsional untuk dokumen rahasia
- Redirect otomatis ke halaman sukses

### ✅ Print-Friendly Team Page
- Tekan Ctrl + P untuk cetak profil advokat
- CSS no-print untuk menyembunyikan elemen non-esensial
- Layout profesional untuk hard copy

---

## 🎨 Customization

### Mengubah Heritage Palette
Edit file `src/styles/global.css`:

```css
:root {
  /* ACCENT - Emas/Amber */
  --color-gold-light: #E8D4B8;
  --color-gold: #C8943E;           /* Ubah warna utama di sini */
  --color-gold-dark: #9D6E2F;
  
  /* ACCENT - Burgundy */
  --color-burgundy: #6B2E3E;       /* Ubah warna sekunder */
  
  /* Background */
  --color-bg-white: #FAF6EF;       /* Ubah background cream */
}
```

### Mengubah Data Tim Advokat
Edit file `src/pages/tim-kami.astro` - array `attorneys`:

```astro
const attorneys = [
  {
    name: 'Nama Advokat',
    role: 'Jabatan',
    specialization: 'Spesialisasi',
    alumnus: 'Pendidikan',
    avatarSeed: 'nama-unik',
  },
  // tambah advokat baru di sini
];
```

### Mengubah Email Form Konsultasi
Edit file `src/pages/kontak.astro` - form action:

```astro
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <!-- form fields -->
</form>
```

---

## 📊 Statistik Firma (dummy placeholder)

Ditampilkan di halaman Tentang Kami:

| Metrik | Nilai |
|--------|-------|
| Transparansi Biaya | 100% |
| Penyelesaian Non-Litigasi | 98.4% |
| Kesiapan Respons Krisis | 24/7 |
| Aset Korporasi Terlindungi | Rp 50B+ |

---

## 👥 Anggota Kelompok

| No | Nama | Peran | Kontribusi |
|----|------|-------|-----------|
| 1 | **Luqi Ahmad Khilfa** | 1253010091 | **Project Lead & Full-stack Developer** — End-to-end development, UI/UX direction, content strategy, QA, CI/CD, and documentation |
| 2 | **Muhammad Zulfi Askhiya** | 1253010079 | **Subject Matter Expert** — Provided personal credentials for team profile  |
| 3 | **seera Aozora** | 1253010089 | **Subject Matter Expert** — Provided personal credentials for team profile  |
| 4 | **Muhamad Rizky Nugraha** | 1253010100 | **Subject Matter Expert** — Provided personal credentials for team profile  |
| 5 | **Nidia Gitania** | 1253010069 | **Subject Matter Expert** — Provided personal credentials for team profile  |
| 6 | **⁠Deden Julian** | 1253010101 | **Subject Matter Expert** — Provided personal credentials for team profile  |
| 7 | **⁠Rafi Aditya Syafiq** | 1253010103 | **Subject Matter Expert** — Provided personal credentials for team profile |
| 8 | **Safta Aulia P** | 1253010087 | **Subject Matter Expert** — Provided personal credentials for team profile |



> **Catatan**: Ganti placeholder dengan nama anggota kelompok sebenarnya.

---

## 🌐 URL Live & Deployment

**Production URL**: [https://aurelius-law-office.vercel.app](https://aurelius-law-office.vercel.app)

**Repository**: [https://github.com/ahmazing-null/aurelius-law-office](https://github.com/ahmazing-null/aurelius-law-office)

Deployed menggunakan **Vercel** dengan automatic preview untuk setiap pull request.

---

## 📞 Kontak Firma

- **WhatsApp Emergency**: +62 851-7160-5225
- **Email**: luqi.akhilfa@gmail.com
- **Lokasi**: Hogwarts (fictional)
- **Jam Operasional**: 24/7 untuk kasus darurat

---

## 📖 Panduan Pengembangan Lebih Lanjut

### Adding New Pages
1. Buat file `.astro` di `src/pages/`
2. Import `MainLayout` dan komponen yang diperlukan
3. Gunakan component reusable (SectionHeader, CardPractice, etc.)
4. Routing otomatis berdasarkan nama file

Contoh:
```astro
---
import MainLayout from '../layouts/MainLayout.astro';
import SectionHeader from '../components/SectionHeader.astro';
---

<MainLayout title="Halaman Baru" description="Deskripsi halaman">
  <section class="section-padding">
    <SectionHeader title="Judul Halaman" centered />
    <!-- konten di sini -->
  </section>
</MainLayout>
```

### CSS Architecture
- **Global variables** di `src/styles/global.css`
- **Scoped styles** dalam `<style>` tag setiap komponen
- **Grid system**: `.grid-2`, `.grid-3` untuk layout responsif
- **Spacing**: `var(--space-1)` hingga `var(--space-20)` untuk consistency

### Accessibility (a11y)
- Semantic HTML (`<section>`, `<nav>`, `<main>`)
- ARIA labels untuk interactive elements
- Color contrast ratio ≥ 4.5:1 untuk WCAG AA
- Keyboard navigation support
- Dark mode dengan proper contrast

---

## 📄 Lisensi

MIT License - Silakan gunakan untuk keperluan komersial maupun personal.

---

## 🙏 Acknowledgments

- **Framework**: [Astro](https://astro.build)
- **Font**: Google Fonts (Playfair Display, EB Garamond, Inter)
- **Icons**: Heroicons SVG
- **Form Backend**: Formspree
- **Hosting**: Vercel

---

## 🔄 Version History

| Versi | Tanggal | Catatan |
|-------|---------|---------|
| 0.0.1 | 2024 | Initial release dengan 6 halaman utama |

---

## 🤝 Kontribusi

Untuk kontribusi atau bug report:

1. Fork repository
2. Buat feature branch: `git checkout -b feature/AmazingFeature`
3. Commit changes: `git commit -m 'Add AmazingFeature'`
4. Push ke branch: `git push origin feature/AmazingFeature`
5. Buat Pull Request dengan deskripsi detail

---

**Dibuat dengan ❤️ oleh Tim Aurelius & Associates**

*"Integritas Tanpa Kompromi. Perlindungan Mutlak."*
