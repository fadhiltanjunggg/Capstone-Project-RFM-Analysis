# Capstone Project: Analisis Segmentasi Pelanggan dengan Metode RFM

## Project Overview

Proyek ini bertujuan untuk melakukan segmentasi pelanggan berdasarkan perilaku pembelian mereka menggunakan data transaksi dari sebuah toko ritel online. Metode yang digunakan adalah analisis RFM (Recency, Frequency, Monetary) untuk mengelompokkan pelanggan ke dalam segmen-segmen yang dapat ditindaklanjuti, seperti 'Champions', 'At-Risk', dan 'Hibernating'. Tujuannya adalah untuk memberikan rekomendasi strategi marketing yang lebih personal dan efektif untuk setiap segmen.

## Raw Dataset Link

Dataset yang digunakan adalah "Online Retail Dataset" yang bersumber dari UCI Machine Learning Repository.

- **Sumber Asli:** [UCI Machine Learning Repository - Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- **File Data Mentah:** [Online Retail.xlsx](./Online%20Retail.xlsx) (Link ke file di dalam repository ini)

## Insight & Findings

Berdasarkan analisis RFM yang telah dilakukan, ditemukan beberapa wawasan utama:

1.  **Distribusi Segmen:** Sebagian besar pelanggan berada di segmen **'Hibernating'** (Tidur Panjang), yang menunjukkan adanya peluang besar untuk kampanye reaktivasi.
2.  **Karakteristik Champions:** Segmen **'Champions'** (pelanggan terbaik) memiliki rata-rata Recency sangat rendah (paling baru membeli), serta Frequency dan Monetary yang sangat tinggi. Mereka adalah aset paling berharga perusahaan.
3.  **Pelanggan Berisiko:** Terdapat segmen **'At-Risk'** yang signifikan, yaitu pelanggan yang dulu sering berbelanja namun sudah lama tidak kembali. Segmen ini memerlukan perhatian segera untuk mencegah mereka beralih ke kompetitor.

## AI Support Explanation

Dalam pengerjaan proyek ini, AI (dalam bentuk Large Language Models/LLM) dimanfaatkan untuk mendukung beberapa aspek analisis:

1.  **Brainstorming & Hypothesis:** Pada tahap awal, AI digunakan untuk brainstorming berbagai kemungkinan metrik dan hipotesis yang bisa digali dari dataset transaksi.
2.  **Code Generation & Debugging:** Selama proses coding di Google Colab, AI assistant (seperti Copilot atau Gemini) digunakan untuk membantu menghasilkan boilerplate code untuk visualisasi data dengan Matplotlib/Seaborn dan memberikan solusi saat menghadapi error pada kode Pandas.
