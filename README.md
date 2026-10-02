# 🛒 Retail Sales Dashboard

Dashboard interaktif berbasis **Tableau** untuk menganalisis performa penjualan sebuah jaringan supermarket. Proyek ini dibuat sebagai tugas **Ujian Akhir Semester (UAS) mata kuliah Data Visualization**.

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

---

## 📌 Tentang Proyek

Dashboard ini membantu menjawab pertanyaan bisnis seperti:

- Bagaimana tren penjualan dari waktu ke waktu?
- Cabang dan kota mana yang menghasilkan pendapatan tertinggi?
- Lini produk apa yang paling laris dan paling menguntungkan?
- Bagaimana perbedaan perilaku belanja berdasarkan tipe pelanggan dan gender?
- Metode pembayaran apa yang paling sering digunakan?

<!-- Ganti dengan screenshot dashboard -->
![Dashboard Preview](images/dashboard.png)

🔗 **Lihat dashboard online:** [Tableau Public](https://public.tableau.com/) <!-- ganti dengan link Tableau Public kamu -->

---

## 📂 Struktur Repository

```
RetailSalesDashboard/
├── Data Visualization UAS.twbx   # Tableau Packaged Workbook (dashboard + data)
├── supermarket_sales.xlsx        # Dataset mentah
└── README.md
```

---

## 📊 Dataset

Dataset yang digunakan adalah **Supermarket Sales**, berisi data transaksi dari tiga cabang supermarket.

| Kolom | Keterangan |
|---|---|
| Invoice ID | Nomor unik transaksi |
| Branch / City | Cabang dan kota lokasi supermarket |
| Customer type | Tipe pelanggan (Member / Normal) |
| Gender | Jenis kelamin pelanggan |
| Product line | Kategori produk |
| Unit price / Quantity | Harga satuan dan jumlah barang |
| Tax 5% / Total | Pajak dan total pembayaran |
| Date / Time | Tanggal dan waktu transaksi |
| Payment | Metode pembayaran (Cash, Credit card, Ewallet) |
| cogs / gross income | Harga pokok penjualan dan laba kotor |
| Rating | Penilaian kepuasan pelanggan |

---

## ✨ Fitur Dashboard

- **KPI Utama** — total penjualan, jumlah transaksi, laba kotor, dan rata-rata rating
- **Tren Penjualan** — pergerakan penjualan harian/bulanan
- **Analisis Cabang** — perbandingan performa antar cabang dan kota
- **Analisis Produk** — penjualan dan laba per lini produk
- **Profil Pelanggan** — distribusi berdasarkan tipe pelanggan dan gender
- **Metode Pembayaran** — proporsi penggunaan tiap metode pembayaran
- **Filter Interaktif** — filter berdasarkan cabang, produk, tanggal, dan lainnya

---

## 🚀 Cara Membuka

1. Clone repository ini:
   ```bash
   git clone https://github.com/aldrvanda/RetailSalesDashboard.git
   ```
2. Install [Tableau Desktop](https://www.tableau.com/products/desktop) atau [Tableau Public](https://public.tableau.com/app/discover) (gratis).
3. Buka file `Data Visualization UAS.twbx`.
4. Data sudah termasuk di dalam file `.twbx`, jadi dashboard bisa langsung digunakan.

---

## 💡 Insight Utama

<!-- Isi dengan temuan dari dashboard kamu, contoh: -->
- Cabang dengan penjualan tertinggi adalah ...
- Lini produk dengan pendapatan terbesar adalah ...
- Member cenderung ... dibandingkan pelanggan Normal
- Metode pembayaran yang paling banyak digunakan adalah ...

---

## 🛠️ Tools

- **Tableau** — visualisasi dan pembuatan dashboard
- **Microsoft Excel** — penyimpanan dan pengecekan data

---
