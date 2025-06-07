KLASIFIKASI BUAH DENGAN RESNET18
Proyek ini adalah program untuk mengenali gambar buah (misalnya apel atau jeruk) menggunakan model ResNet18 dari PyTorch. Model ini sudah dilatih sebelumnya (pretrained), jadi kita tinggal melatih ulang (fine-tune) supaya bisa mengenali dua jenis buah.

FOLDER DATASET
letakkan dataset dengan struktural seperti ini:

fruit-dataset/
├── apple/
│   ├── gambar1.jpg
│   ├── ...
├── orange/
│   ├── gambar1.jpg
│   ├── ...

FITUR UNGGULAN
- augmentasi data
- transfer learning
- klasifikasi biner : apel vs jeruk
- visualisasi konvergensi loss (dengan smoothing)
- confussion matrix untuk evaluasi akurasi
- prediksi gambar tunggal disertai skor kepercayaan
