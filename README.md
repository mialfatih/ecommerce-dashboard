# 📊 Dashboard E-Commerce: Produk Terlaris & Metode Pembayaran

Dashboard ini menampilkan visualisasi interaktif **produk terlaris dan metode pembayaran** pada data transaksi e-commerce. Pengguna dapat melakukan filter berdasarkan **rentang tanggal**, dan hasil dashboard akan menyesuaikan secara otomatis.

---

## ✅ Fitur Dashboard

1. **Filter Rentang Tanggal**: Pilih tanggal mulai dan akhir untuk menyesuaikan data.
2. **Visualisasi Produk Terlaris**: Menampilkan **Top 5** dan **Bottom 5** kategori produk berdasarkan jumlah penjualan.
3. **Visualisasi Metode Pembayaran**: Menampilkan total nilai transaksi berdasarkan metode pembayaran.
4. **Kesimpulan & Rekomendasi Otomatis**: Menyesuaikan hasil analisis sesuai rentang tanggal yang dipilih.

---

## 🛠️ Persiapan Environment

### 1. **Clone Repository ini**

   git clone https://github.com/mialfatih/ecommerce-dashboard.git

### 2. **Masuk ke folder project**

   cd repo-dashboard-ecommerce

### 3. **(Opsional) Buat Virtual Environment**

**Windows**<br>
python -m venv env
env\Scripts\activate

**MacOS/Linux**<br>
python3 -m venv env
source env/bin/activate

**Install Library yang Dibutuhkan**<br>
pip install -r requirements.txt

### 4. **Jalankan Dashbaord**
streamlit run dashboard/dashboard.py<br>

---

*Catatan*<br>
*- Pastikan seluruh file dataset (CSV) tersedia dalam folder data/..*
*- Bila terjadi error dan keterangan bahwa data tidak bisa dibaca, buka bagian dashboard.py dan ke bagian def load_data(): lalu tambah ../ di tiap data, contoh "../data/order_items_dataset.csv"*
