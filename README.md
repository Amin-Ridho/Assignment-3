# Assignment 03 computer vision & natural language processing

03_TIM 3_1 Pemrosesan Gambar Digital

Pustaka : Scikit-image, OpenCV, Numpy, Matplotlib
Tujuan : Memproses gambar digital dengan operasi dasar pemrosesan citra.
Langkah-langkah :

Konversi Warna : Ubah saluran warna dari BGR ke RGB dan dari BGR ke skala abu-abu, lalu dari skala abu-abu ke biner menggunakan ambang batas.
Plot Histogram : Visualisasikan histogram dari gambar asli dan gambar greyscale untuk analisis distribusi intensitas.
Pooling dan Block Reduce :
Gunakan block_reduce()dengan fungsi np.minuntuk operasi min pooling dan np.meanuntuk average pooling.
CLAHE : Terapkan CLAHE (Contrast Limited Adaptive Histogram Equalization) untuk mencerahkan gambar gelap, dan menyimpan gambar hasilnya dengan ekstensi .png.

03_TIM 3_2 Pembelajaran Transfer untuk Klasifikasi Digit Tulisan Tangan

Dataset : Angka Tulis Tangan MNIST
Pustaka : PyTorch, Torchvision, Scikit-learn
Tujuan : Menggunakan Transfer Learning dengan model CNN pre-trained untuk klasifikasi digit.
Langkah-langkah :

Modifikasi Model : Ubah input layer dan output layer pada DenseNet dan Vision Transformer (ViT) sesuai kebutuhan klasifikasi 10 kelas MNIST.
Hyperparameter : Tentukan nilai batch size, learning rate, dan loss functionuntuk multi-kelas.
Model dan Pelatihan Pemanggilan :
Pilih model (ResNet18, DenseNet121, atau ViT), tentukan jumlah epoch, dan sediakan data loader untuk train dan validation set.
Analisis Lapisan Beku :
Menjawab pertanyaan terkait dampak pembekuan lapisan pada akurasi dan kecepatan pelatihan. Semakin banyak lapisan yang di-freeze, akurasi awal lebih rendah, dan waktu pelatihan lebih cepat karena parameter yang dibor lebih sedikit.

03_TIM 3_3 Deteksi Objek Real-time dalam Video

Kumpulan data : video YouTube
Pustaka : PyTorch, Numpy, OpenCV2
Tujuan : Mendeteksi objek secara real-time dalam video menggunakan model YOLOv5.
Langkah-langkah :

Load Model : Gunakan model YOLOv5 untuk mendeteksi objek dalam video dengan URL YouTube.
Pertanyaan :
Menjelaskan perbedaan antara klasifikasi gambar (pengklasifikasian objek tunggal pada gambar) dan deteksi objek (mendeteksi lokasi dan jenis objek dalam gambar).
Identifikasi video di mana YOLOv5 memiliki akurasi deteksi terburuk dan faktor-faktor yang mempengaruhi akurasi, seperti kondisi pencahayaan, sudut pandang, atau kompleksitas gambar.

03_TIM 3_4 Klasifikasi Teks dengan BERT untuk Tweet Bencana

Kumpulan Data : Tweet Bencana
Pustaka : NLTK, Pandas, Numpy, Scikit-learn, PyTorch, Transformers
ujuan : Melakukan klasifikasi teks menggunakan model BERT untuk memahami teks terkait bencana.
Langkah-langkah :

Persiapan Data : Impor data pelatihan dan lakukan preprocessing. Tentukan fitur (X) dan target (Y), serta pisahkan dataset menjadi 80% pelatihan dan 20% validasi.
Konfigurasi Model :
Tentukan ukuran batch, jumlah label, jumlah epoch, dan kecepatan pembelajaran untuk melatih BERT.
DataLoader Setup : Lengkapi DataLoader untuk pelatihan, validasi, dan pengujian.
Hyperparameter Tuning : Jika akurasi kurang dari 80%, lakukan penyesuaian hyperparameter untuk meningkatkan performa model.
Pengujian : Pengujian impor dan praproses data, lalu siapkan DataLoader untuk evaluasi akhir model pada uji data.
