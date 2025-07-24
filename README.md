# Toyota Car Recommendation System

Sistem rekomendasi mobil Toyota berbasis web dengan UI Neubrutalism yang modern dan responsive.

## 🚗 Fitur Utama

- **Simulasi Pembelian**: Hitung cicilan mobil berdasarkan budget dan kemampuan finansial
- **Rekomendasi Cerdas**: Sistem AI yang merekomendasikan mobil sesuai profil finansial
- **Search & Filter**: Cari mobil berdasarkan nama atau filter berdasarkan range harga
- **Kontak Sales**: Hubungi sales Toyota langsung via WhatsApp
- **UI Modern**: Desain Neubrutalism dengan animasi yang engaging
- **Responsive**: Bekerja optimal di desktop, tablet, dan mobile

## 🎨 Desain Features

- **Palet Warna**: Kuning (#fbbf24), Hitam (#1a1a1a), Abu-abu gelap (#374151), Putih
- **Font**: Google Fonts Poppins (300-900)
- **Gaya**: Neubrutalism dengan shadow tebal, border bold, dan transformasi skew
- **Animasi**: Hover effects, fade-in, button pulse, card bounce

## 📱 Cara Penggunaan

### 1. Buka Aplikasi
- **Windows/Mac/Linux**: Klik dua kali file `index.html` untuk membuka di browser
- **Live Server** (opsional): Untuk development, gunakan live server di VS Code

### 2. Input Data Finansial
Masukkan informasi berikut di form simulasi:
- **Budget Maksimal**: Batas maksimum harga mobil yang Anda inginkan
- **Penghasilan per Bulan**: Total penghasilan bulanan Anda
- **Pengeluaran per Bulan**: Total pengeluaran rutin bulanan
- **Uang Muka**: Pilih persentase uang muka (20%, 25%, 30%)
- **Tenor Cicilan**: Pilih jangka waktu cicilan (12-60 bulan)

### 3. Lihat Rekomendasi
Sistem akan menampilkan:
- **Ringkasan Finansial**: Kemampuan cicilan dan sisa penghasilan
- **Daftar Mobil**: Mobil yang sesuai dengan kemampuan finansial
- **Detail Cicilan**: Uang muka, cicilan bulanan, total pembayaran

### 4. Filter & Search
- **Search Bar**: Cari mobil berdasarkan nama atau series
- **Filter Harga**: Filter berdasarkan range harga (100-200 juta, 200-300 juta, dll)
- **Reset Filter**: Hapus semua filter untuk melihat semua hasil

### 5. Detail & Kontak Sales
- **Klik tombol arrow (→)** pada kartu mobil untuk melihat detail lengkap
- **Lihat carousel gambar** (jika tersedia multiple images)
- **Hubungi sales** via WhatsApp langsung dari modal detail

## 📊 Data Mobil

Aplikasi ini menggunakan data harga Toyota Indonesia terbaru (Juni 2025) dengan 20 series dan 157 model variant, meliputi:

- **City Car**: Agya, Calya
- **LCGC**: Avanza, Veloz, Raize
- **SUV**: Rush, Fortuner, Yaris Cross
- **Sedan**: Vios, Corolla Altis, Camry
- **MPV**: Innova, Alphard, Voxy
- **Pickup**: Hilux, Dyna
- **Sport**: GR Yaris
- **Luxury**: Land Cruiser 300

## 🛠️ Technical Details

### File Structure
```
project-kalkulasi-mobil/
├── index.html              # HTML utama
├── styles-neubrutalism.css  # CSS dengan desain Neubrutalism
├── script.js               # JavaScript logika aplikasi
├── toyota-data.js          # Data mobil Toyota (embedded)
├── toyota.json            # Data mobil format JSON (backup)
└── main.py                # Script untuk parsing PDF harga (opsional)
```

### Browser Compatibility
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

### No Server Required
Aplikasi ini dapat dijalankan langsung dari file system tanpa memerlukan web server. Data mobil sudah di-embed dalam file `toyota-data.js` untuk menghindari CORS issues.

## 💡 Tips Penggunaan

1. **Budget Realistis**: Masukkan budget yang sesuai kemampuan finansial
2. **Sisa Penghasilan**: Pastikan sisa penghasilan cukup untuk cicilan (minimal 30% dari penghasilan)
3. **Uang Muka**: Semakin besar uang muka, semakin kecil cicilan bulanan
4. **Tenor**: Tenor lebih panjang = cicilan lebih kecil tapi total bunga lebih besar
5. **Kontak Sales**: Gunakan kontak WhatsApp untuk nego harga dan promo

## 📞 Sales Contact

- **Dhaffa**: Sales Consultant Toyota
- **Rezananda**: Sales Consultant Toyota  
- **Stevanus**: Sales Consultant Toyota

*Klik kontak di modal detail untuk chat langsung via WhatsApp*

## 🔧 Development

Untuk development atau modifikasi:

1. **Edit Data**: Ubah file `toyota-data.js` untuk update harga/model baru
2. **Edit Style**: Modifikasi `styles-neubrutalism.css` untuk perubahan visual
3. **Edit Logic**: Update `script.js` untuk perubahan fitur/fungsi
4. **Generate Data**: Gunakan `main.py` untuk parsing PDF harga baru

## 📄 License

© 2025 Toyota Astra Motor. Sistem Rekomendasi Pembelian Mobil.

---

**Note**: Harga yang ditampilkan adalah harga dasar kendaraan. Untuk harga akhir dapat mengacu kepada harga yang ada di masing-masing dealer Toyota.
