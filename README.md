# ✈️ SkyWings - Website Layanan Penerbangan

Website pemesanan tiket penerbangan modern dengan fitur chatbot AI untuk membantu customer service.

## 🌟 Fitur Utama

- **Hero Section** - Landing page dengan latar belakang gradient yang menarik
- **Booking System** - Form pemesanan tiket lengkap dengan validasi
- **Destinasi Populer** - Showcase destinasi wisata dengan harga
- **Chatbot AI** - Asisten virtual 24/7 untuk bantuan pelanggan
- **Responsive Design** - Tampilan optimal di desktop dan mobile
- **Smooth Animations** - Animasi halus dan interaktif

## 📋 Teknologi

- HTML5
- CSS3 (Flexbox & Grid)
- Vanilla JavaScript
- No Framework/Library Dependencies

## 🚀 Cara Menggunakan

1. **Download/Clone** file-file berikut:
   ```
   ├── index.html
   ├── style.css
   └── script.js
   ```

2. **Pastikan struktur folder** seperti ini:
   ```
   project-folder/
   ├── index.html
   ├── style.css
   └── script.js
   ```

3. **Buka** `index.html` di browser (double click atau drag & drop ke browser)

4. **Atau jalankan dengan Live Server** jika menggunakan VS Code

## 💡 Fitur Chatbot

Chatbot dapat menjawab pertanyaan tentang:
- ✅ Cara pesan tiket
- ✅ Status penerbangan
- ✅ Kebijakan bagasi
- ✅ Metode pembayaran
- ✅ Harga & promo
- ✅ Reschedule & refund

## 🎨 Preview Fitur

### Form Pemesanan
- Pilihan kota keberangkatan & tujuan
- Tanggal berangkat & pulang
- Jumlah penumpang (1-5+)
- Kelas penerbangan (Ekonomi, Bisnis, First Class)

### Chatbot Assistant
- Floating button di pojok kanan bawah
- Quick reply options
- Response cepat dan akurat
- Interface yang user-friendly

## 📱 Responsive

Website telah dioptimasi untuk:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 🎯 Cara Kustomisasi

### Mengubah Warna Tema
Edit di `style.css`:
```css
/* Gradient utama */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Menambah Destinasi
Edit di `index.html` section `#destinations`:
```html
<div class="destination-card">
    <div class="destination-img">🏝️</div>
    <div class="destination-info">
        <h3>Nama Kota</h3>
        <p>Deskripsi</p>
        <div class="price">Mulai dari Rp X.XXX.XXX</div>
    </div>
</div>
```

### Menambah Response Chatbot
Edit di `script.js` function `getBotResponse()`:
```javascript
else if (lowerMsg.includes('keyword')) {
    return 'Response chatbot Anda';
}
```

## 📄 Lisensi

Free to use for personal and commercial projects.

## 👨‍💻 Developer

Created with ❤️ by SkyWings Team

---

**© 2026 SkyWings Airlines. All Rights Reserved.**
