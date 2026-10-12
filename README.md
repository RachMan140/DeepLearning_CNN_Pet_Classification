# DeepLearning_CNN_Pet_Classification
Assignment Deep Learning Class, exploring the use of advanced CNN for pet breed class classification.

Proyek ini membandingkan beberapa konfigurasi model untuk mengklasifikasikan gambar ke dalam 10 kelas ras kucing dan anjing. Eksperimen menggunakan ResNet-18 dan EfficientNet-B0, termasuk perbandingan pelatihan dari awal, transfer learning, serta augmentasi data.

## Isi Repository

- `Jupyter_Notebook.ipynb` — notebook eksperimen.
- `requirements.txt` — library Python yang diperlukan.
- `Dokumen_Laporan.pdf` — laporan hasil eksperimen.
- `Log_Hasil_Mentah/experiment_summary(1).csv` — ringkasan metrik setiap eksperimen.
- `Log_Hasil_Mentah/epoch_logs(1).csv` — loss dan akurasi per epoch.
- `Figures/` — grafik dan visualisasi hasil.

## Dataset

Menggunakan Oxford-IIIT Pet Dataset yang dibuat oleh Omkar M. Parkhi, Andrea Vedaldi, Andrew Zisserman, dan C. V. Jawahar dari Visual Geometry Group, University of Oxford. Dataset resmi tersedia di [halaman Oxford-IIIT Pet](https://www.robots.ox.ac.uk/~vgg/data/pets/).
Eksperimen ini menggunakan 10 kelas terpilih dari dataset tersebut yang tersedia langsung melalui `torchvision.datasets.OxfordIIITPet` tanpa autentikasi pihak ketiga.

## Menjalankan Notebook

1. Buka `Jupyter_Notebook.ipynb` di Google Colab.
3. Siapkan dataset sesuai petunjuk di notebook.
4. Jalankan sel dari awal secara berurutan.

Eksperimen menggunakan PyTorch dan dapat berjalan lebih cepat dengan GPU T4 yang tersedia di Colab. Waktu pelatihan dapat berbeda bergantung pada perangkat.

## Result

Ringkasan result ada di `Log_Hasil_Mentah/experiment_summary(1).csv`. Log per epoch ada di `Log_Hasil_Mentah/epoch_logs(1).csv`. Grafik perbandingan tersedia di folder `Figures/`.

## Environment

Library yang diperlukan tercantum di `requirements.txt`. Eksperimen dijalankan menggunakan 3.13.15 (main, Aug  6 2026, 11:06:22) [GCC 13.3.0]

## Referensi dan Atribusi

- Dataset: Oxford-IIIT Pet - [halaman Oxford-IIIT Pet](https://www.robots.ox.ac.uk/~vgg/data/pets/).
- Model dan pustaka: PyTorch dan Torchvision.
