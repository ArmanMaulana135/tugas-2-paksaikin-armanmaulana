Proyek ini adalah implementasi sederhana dalam bahasa pemrograman Python untuk mengolah data belanja harian yang disimpan dalam struktur data Dictionary, List, dan Tuple.

Fitur Utama
Program ini mencakup beberapa fungsi fungsional untuk menganalisis data belanja:

Hitung Total Per Hari: Menghitung total pengeluaran untuk setiap hari dalam seminggu.

Rekap Barang: Mengagregasi jumlah dan total harga dari semua barang yang dibeli selama periode tersebut.

Pencarian Barang: Mencari riwayat pembelian barang berdasarkan kata kunci nama barang.

Sorting Barang Terbanyak: Mengurutkan barang berdasarkan jumlah terbanyak yang dibeli.

Bonus Diskon: Menghitung potongan harga otomatis (10%) jika total belanja keseluruhan melebihi Rp 100.000.

Struktur Data
Data belanja disimpan dalam format dictionary dengan struktur sebagai berikut:

Python
belanjaan = {
    "hari": [("nama_barang", jumlah, harga), ...],
    ...
}
Cara Penggunaan
Pastikan Anda telah menginstal Python di komputer Anda.

Salin kode ke dalam file (misalnya: belanja.py).

Jalankan skrip melalui terminal atau command prompt:

Bash
python belanja.py
Ikuti instruksi yang muncul di layar, terutama saat diminta memasukkan kata kunci pencarian barang.

Contoh Output
Program akan menampilkan ringkasan data, total per hari, rekapitulasi barang, serta barang yang paling banyak dibeli.

Dibuat sebagai bahan pembelajaran struktur data Python.
