# 🐻 GrizzlyBot — Website Dokumentasi

Website resmi GrizzlyBot, bot WhatsApp premium dengan fitur store, role system, game stalker, dan Alight Motion.

## 🌐 Deploy

### Vercel (Recommended)
1. Push repo ini ke GitHub
2. Buka [vercel.com](https://vercel.com) → **New Project**
3. Import repo GitHub kamu
4. Framework Preset: **Other**
5. Klik **Deploy** — selesai!

### GitHub Pages
1. Push repo ke GitHub
2. Buka **Settings → Pages**
3. Source: **Deploy from branch** → pilih branch `main` / root `/`
4. Simpan — website live di `https://username.github.io/nama-repo`

## 📁 Struktur File

```
grizzlybot-site/
├── index.html      ← Halaman utama
├── style.css       ← Semua styling (dark luxury theme)
├── main.js         ← Animasi, particles, tab, scroll
├── vercel.json     ← Konfigurasi Vercel
└── README.md       ← Ini
```

## ✏️ Kustomisasi

### Ganti Nama Bot / Owner
Cari dan ganti di `index.html`:
- `GrizzlyBot` → nama bot kamu
- `zars` → nama owner kamu

### Ganti Harga
Di section Store (`index.html`), cari:
```html
<div class="price-val">Rp 250<span>/akun</span></div>
<div class="price-val">Rp 100<span>/akun</span></div>
```

### Ganti Warna Aksen
Di `style.css`, edit variabel CSS di `:root`:
```css
--gold: #c9a84c;        /* warna utama */
--gold-light: #e8c97a;  /* warna lebih terang */
```

## 🛠️ Tech Stack
- HTML5 / CSS3 / Vanilla JS
- Google Fonts (Cormorant Garamond, Syne, DM Mono)
- Canvas API (particles background)
- IntersectionObserver (scroll animations)
- Zero dependencies — pure static site
