# AIRSCAPE

Notebook proyek Gelar Rasa 2026.

## Data

Simpan file berikut di folder `data/`:

- `Dataset DA Gelar Rasa 2026.zip`
- `Dataset GelarRasa Bismillah aja (3).xlsx`

## Menjalankan

1. `pip install -r requirements.txt`
2. Buka `notebooks/dataset_final.ipynb` untuk menyiapkan **salinan dataset final** ke `hasil/dataset_final.xlsx`. Isi file tidak berubah.
3. Notebook lainnya digunakan untuk cleaning, EDA, ISPU, integrasi, dan prioritas.

## Notebook

| Nama | Isi |
|---|---|
| `dataset_final.ipynb` | Menyiapkan workbook final tanpa mengubah data |
| `cleaning.ipynb` | Cleaning dari dataset awal |
| `eda_kualitas_udara.ipynb` | EDA kualitas udara |
| `eda_kesehatan.ipynb` | EDA kesehatan |
| `analisis_faktor_lingkungan.ipynb` | Analisis meteorologi |
| `integrasi_polusi_kesehatan.ipynb` | Integrasi kualitas udara dan kesehatan |
| `prioritas_wilayah.ipynb` | Analisis wilayah prioritas |
| `validasi_prioritas.ipynb` | Validasi prioritas |
| `hitung_ispu.ipynb` | Perhitungan ISPU indikatif |
| `cek_dataset.ipynb` | Pemeriksaan tabel akhir |

Dataset besar dan folder hasil tidak diunggah ke GitHub.
