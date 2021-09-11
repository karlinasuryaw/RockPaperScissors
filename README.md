# RockPaperScissors

Final Submission Dicoding x Kampus Merdeka : Klasifikasi Gambar
Ketentuan yang harus dipenuhi :
1. Dataset harus dibagi menjadi train set dan validation set.
2. Harus mengimplementasikan augmentasi gambar. 
3. Menggunakan image data generator.
4. Model harus menggunakan model sequential.
5. Pelatihan model tidak melebihi waktu 30 menit.
6. Program dikerjakan pada Google Colaboratory.
7. Akurasi dari model minimal 85%.
8. Dapat memprediksi gambar yang diunggah ke Colab.
9. Menambahkan data diri (sesuai profil Dicoding).

Melalui proses evaluasi model dan hasil prediksi, CNN model yang sudah saya bangun mampu memberikan akurasi 97,11% dengan parameter-parameter di bawah ini:
  Batch size : 64
  Target size : 200, 300
  Epoch : 15
  Fungsi aktivasi : relu, softmax
  Optimizer : Adam
  Loss function : categorical-crossentropy
Penggunaan hyperparameter diatas saya lakukan secara repetitif sampai menemukan hyperparameter terbaik dan menghasilkan akurasi yang bagus. Selain itu pada iterasi epoch ke-10 model sudah mampu memberikan akurasi sebesar 97,11% sehingga proses training dihentikan oleh fungsi callbacks.
