# Ellvara Spa - Landing Page

Landing page sederhana untuk promosi jasa pijat online **Ellvara Spa**.  
Dibuat dengan HTML & CSS murni, dioptimasi untuk SEO, dan di-hosting di Vercel.

## 🎯 Tujuan
- Mempromosikan layanan massage online 24 jam.
- Menampilkan paket harga dan layanan.
- Memudahkan pelanggan menghubungi via WhatsApp dengan template booking otomatis.
- Menjadi landing page untuk Google Ads.

## 🧱 Tech Stack
- **HTML5** — struktur semantik.
- **CSS3** — styling custom (tanpa framework).
- **Vercel** — hosting statis.
- **WhatsApp API** — link `wa.me` dengan pesan template.

## 📁 Struktur Project
ellvara-spa/
├── index.html
├── css/
│ └── style.css
├── assets/
│ ├── images/
│ │ ├── hero-bg.jpg
│ │ ├── logo-ellvara.png
│ │ └── therapist-1.jpg
│ └── icons/
│ └── favicon.ico
├── README.md
└── vercel.json (opsional)


## 🎨 Palet Warna
- **Coklat Tua:** `#4A2C2A` (primary)
- **Coklat Muda:** `#D2B48C` / `#C19A6B` (secondary)
- **Krem:** `#F5F0E6` (background)
- **Teks:** `#2E1B1A`

## 📌 Fitur Utama
1. **Hero Section** — headline, CTA WhatsApp.
2. **About** — penjelasan singkat Ellvara Spa.
3. **Services** — daftar paket massage + harga.
4. **Testimoni** — review pelanggan.
5. **CTA** — tombol booking via WA dengan template pesan.
6. **Footer** — kontak & copyright.

## 📞 Kontak
- WhatsApp 1: [085691670073](https://wa.me/6285691670073)
- WhatsApp 2: [08139536208](https://wa.me/628139536208)

## 🚀 Deployment
1. Push ke GitHub.
2. Import repo di Vercel.
3. Deploy otomatis.

## 📈 SEO
- Meta title & description.
- Open Graph tags.
- Structured data (LocalBusiness).
- Semantic HTML.
- Mobile responsive.

📋 RENCANA PROYEK (Project Plan)
1. Analisis Kebutuhan
Target: Pengguna Google Ads yang mencari massage online.

Tujuan: Konversi ke WhatsApp.

Konten: Hero, About, Services, Testimoni, CTA.

Gaya: Coklat tua & muda, elegan, clean.

2. Desain & UX
Layout: Single page, scroll vertikal.

Responsif: Mobile-first (karena Google Ads mobile).

Komponen:

Navbar sticky (logo + CTA WA).

Hero dengan background gambar spa.

Card services dengan harga.

Testimoni slider sederhana.

Floating WA button.

3. Struktur HTML
html
<header> Navbar </header>
<main>
  <section id="hero"> ... </section>
  <section id="about"> ... </section>
  <section id="services"> ... </section>
  <section id="testimonials"> ... </section>
  <section id="cta"> ... </section>
</main>
<footer> ... </footer>
4. WhatsApp Template Booking
Saat klik WA, pesan otomatis:

text
Halo Ellvara Spa, saya ingin booking:
- Layanan: [Body Massage 90 min / 120 min / + Lulur]
- Nama: 
- Alamat: 
- Waktu: 
Mohon info ketersediaan. Terima kasih.
Implementasi: https://wa.me/6285691670073?text=... (URL encoded).

5. SEO Plan
Title: Ellvara Spa - Massage Online 24 Jam | Pijat Profesional ke Rumah

Meta Description: Nikmati pijat profesional 24 jam di rumah Anda. Body massage, lulur, aroma therapy. Booking mudah via WhatsApp.

Keywords: massage online, pijat panggilan, spa 24 jam, Ellvara Spa

Structured Data: LocalBusiness + Service.

Performance: Minify CSS, lazy load images, preconnect.

6. Deployment
Hosting: Vercel (static).

Domain: (opsional) ellvaraspa.com.

Analytics: Google Analytics + Google Ads conversion tracking.

7. Timeline
Tahap	Durasi
Setup & Struktur	1 hari
Desain & HTML	2 hari
CSS & Responsif	2 hari
Konten & SEO	1 hari
Testing & Deploy	1 hari