
# 🐶🐱 Klasifikasi Anjing vs Kucing dengan CNN dan Transfer Learning

Proyek ini merupakan implementasi klasifikasi gambar menggunakan model pretrained `ResNet18` dari PyTorch untuk membedakan gambar **anjing** dan **kucing**.

## 📁 Struktur Proyek

```
cnn-anjing-kucing/
├── dataset/
│   ├── anjing/
│   └── kucing/
├── cnn-anjing-kucing.ipynb
├── README.md
└── laporan.pdf
```

## 🔍 Deskripsi Singkat

Model dibangun menggunakan pendekatan **transfer learning**:
- Dataset: 200 gambar (100 anjing, 100 kucing) dikumpulkan secara manual.
- Framework: PyTorch.
- Pretrained model: `ResNet18` dari torchvision.
- Klasifikasi biner (anjing = 1, kucing = 0).

## 🚀 Cara Menjalankan

1. Pastikan dependensi terinstal:

```bash
pip install torch torchvision matplotlib pillow tqdm
```

2. Struktur folder dataset seperti berikut:

```
dataset/
├── anjing/
│   ├── anjing1.jpg
│   └── ...
└── kucing/
    ├── kucing1.jpg
    └── ...
```

3. Jalankan notebook:

```bash
jupyter notebook cnn-anjing-kucing.ipynb
```

---

## 📊 Hasil & Evaluasi

- **Akurasi**: ± 90–95% pada dataset validasi.
- **Visualisasi**: Train vs Test Loss per epoch.
- Tidak terjadi overfitting signifikan.
- Model efisien untuk dataset kecil berkat pretrained ResNet18.

---

## 🧠 Insight

- Transfer learning sangat efektif untuk dataset terbatas.
- Pembekuan layer awal sangat membantu dalam mempercepat pelatihan.
- Preprocessing dan augmentasi adalah kunci generalisasi.

---

## ✍️ Kontributor

- **Nama**: [Nama Anda]
- **NIM**: [NIM Anda]
- **Mata Kuliah**: [Nama Mata Kuliah]
- **Dosen**: [Nama Dosen]

---

## 📄 Lisensi

Hak cipta © 2025 [Nama Anda]. Untuk keperluan akademik.
