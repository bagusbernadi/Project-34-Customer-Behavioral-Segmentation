[← Back to portfolio](https://bagusbernadi.github.io/)

# Project 34: Customer Behavioral Segmentation

**Status: Design (rancangan).**

**Tujuan:** Membangun segmentasi pelanggan dari perilaku belanja (frekuensi, nilai order, kategori produk, waktu belanja, dan cara bayar) untuk menemukan segmen yang paling bernilai dan yang berisiko berhenti belanja.

Halaman rancangan: https://bagusbernadi.github.io/Project-34-Customer-Behavioral-Segmentation/

| | |
|---|---|
| Kategori | E-commerce / retail |
| Tingkat | Sulit |
| Data | Brazilian E-Commerce Public Dataset by Olist (Kaggle, CC BY-NC-SA 4.0) |
| Tools | DuckDB + SQL, Python (pandas, scikit-learn), Streamlit + Plotly |

## 1. Problem
Segmen pelanggan apa yang terbentuk dari perilaku belanja nyata (frekuensi, nilai order, kategori produk, waktu belanja, cara bayar), dan segmen mana yang paling bernilai atau berisiko berhenti belanja?

## 2. Data
- Sumber data: [here](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) (Versi: nomor versi Kaggle dicatat saat diunduh; Tanggal akses: diisi saat diunduh)
- Acuan ide: [here](https://github.com/bagusbernadi/Customer-feature-and-Segmentation) (Versi: repo segmentasi lama, hanya ide dan kode; datanya tidak dipakai)
- Ukuran (perkiraan, belum diverifikasi): ±100 ribu order 2016–2018 di 9 file CSV. Lisensi CC BY-NC-SA 4.0 (non-komersial).
- Tidak ada atribut demografi yang ditebak.

## 3. Analysis
Belum dikerjakan. Rencana langkah ada di bagian Work Plan pada halaman rancangan.

## 4. Recommendation
Belum dikerjakan.

## 5. Impact
Belum dikerjakan. Angka dampak nanti diberi label `estimated` / `simulated`.

## Batasan yang sudah diketahui
- Data marketplace Brasil 2016–2018, belum tentu mewakili pasar Indonesia.
- Sebagian besar pelanggan kemungkinan hanya belanja sekali.
- K-Means sensitif terhadap skala fitur dan outlier.
- Uplift revenue adalah estimasi skenario.

## Struktur repository
```
index.html          # halaman rancangan (GitHub Pages)
README.md
data/README.md      # (rencana) cara unduh dataset dan lisensi
sql/                # (rencana) cleaning, fitur, profil segmen
notebooks/          # (rencana) K-Means, pemilihan k, stabilitas
dashboard/          # (rencana) aplikasi Streamlit
```
