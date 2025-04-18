# Certainty-Factor-Fuzzy-Logic
2306146 Siti Rahmawati

🧪 Praktikum Sistem Pakar: Fuzzy Logic dan Certainty Factor (CF)
📌 Deskripsi
Repository ini berisi implementasi dua metode yang umum digunakan dalam sistem pakar, yaitu:

Fuzzy Logic: Mengontrol kecepatan kipas AC berdasarkan suhu dan kelembaban menggunakan logika fuzzy.

Certainty Factor (CF): Mendiagnosis penyakit (contoh: diabetes) berdasarkan gejala dan tingkat kepercayaan.

📁 File dalam Repository
fuzzy_logic.py → Implementasi sistem Fuzzy Logic untuk pengendali kipas AC berdasarkan suhu dan kelembaban.

certainty_factor.py → Implementasi metode Certainty Factor untuk diagnosa penyakit dengan bobot gejala.

▶️ Cara Menjalankan di Google Colab
Clone atau unggah file ke Google Colab.

Jalankan setiap cell kode secara berurutan.

Ubah input nilai suhu, kelembaban, atau gejala untuk melihat perubahan hasil inferensi sistem.

Visualisasi fungsi keanggotaan dan hasil inferensi tersedia melalui matplotlib.

📈 Fitur yang Diimplementasikan
✅ Fuzzy Logic
Input: Suhu (°C) dan Kelembaban (%)

Output: Kecepatan kipas (%)

Metode: Fuzzy Inference System (FIS) dengan aturan berbasis logika linguistik.

Visualisasi: Fungsi keanggotaan dan hasil akhir inferensi.

✅ Certainty Factor
Input: Daftar gejala dan tingkat keyakinan dari pengguna

Pengetahuan: Basis aturan dari pakar (bobot per gejala untuk tiap penyakit)

Output: Nilai CF diagnosis untuk setiap penyakit

Mendukung pengujian perubahan nilai CF serta penambahan gejala baru.
