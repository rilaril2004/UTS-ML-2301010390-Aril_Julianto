# UTS Machine Learning — Klasifikasi Penyakit Ginjal Kronis (Jalur A)

## Identitas
- **NIM:** 2301010390
- **Nama:** Aril  Julianto
- **Kelas:** XX  *(sesuaikan)*
- **Mata kuliah / dosen:** Machine Learning / Dr. I Gede Totok Suryawan, S.Kom., M.T.

## Ringkasan proyek
Memprediksi apakah pasien menderita penyakit ginjal kronis (`ckd`) atau tidak (`notckd`) dari hasil pemeriksaan klinis dan laboratorium (400 pasien, 24 fitur). Alur CRISP-DM, `SEED = 390`.

- **Jalur:** A (Klasifikasi)
- **Model:** KNN (k = 3, dipilih dengan 5-fold CV dan aturan 1 standard error) vs DummyClassifier; SVM (rbf, C = 10) sebagai algoritma kedua
- **Hasil data uji (80 pasien):** Dummy 62,50% | KNN 96,25% | SVM 98,75% (akurasi)

## Dataset
- Chronic Kidney Disease, UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/336/chronic_kidney_disease
- Salinan yang dipakai: `data/kidney_disease.csv` — **[isi link tempat mengunduh dan tanggal akses]**
- Lisensi: **[isi sesuai halaman sumber]**
- Data tidak memuat identitas pasien.

## Struktur repository
```
README.md
notebook/UTS_ML_2301010390_Aril.ipynb
data/kidney_disease.csv
reports/
```

