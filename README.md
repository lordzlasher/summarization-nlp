# Deskripsi Aplikasi
Text summarization adalah proses mengurangi teks yang panjang dan kompleks menjadi versi yang lebih pendek dan lebih mudah dipahami, yang menyajikan informasi penting dari teks asli. Aplikasi text summarization bertujuan untuk membantu pengguna memahami ide-ide utama dari teks dengan cepat dan mudah, tanpa harus membaca seluruh teks.

# Arsitektur Aplikasi
Aplikasi yang dibuat berbasis website dengan menggunakan Next.js sebagai framework frontend serta backend. Pemanggilan model menggunakan API dari RapidAPI

# Dataset
Dataset CNN / DailyMail adalah kumpulan data berbahasa Inggris yang berisi lebih dari 300 ribu artikel berita unik seperti yang ditulis oleh jurnalis di CNN dan Daily Mail. Versi saat ini mendukung peringkasan ekstraktif dan abstraktif, meskipun versi aslinya dibuat untuk membaca dan memahami mesin serta menjawab pertanyaan abstraktif.

# Algoritma Machine Learning
BART ("Bidirectional Encoder Representations from Transformers") adalah model pembelajaran mesin yang digunakan untuk melakukan taksiran transformasi atau pemrosesan bahasa natural. BART dapat digunakan untuk berbagai macam taksiran transformasi, seperti penerjemahan bahasa, sumber-sintesis, dan pemrosesan sumber teks. BART menggunakan teknik pembelajaran mesin yang disebut transformator untuk mengekstrak fitur dari data input dan menggunakannya untuk memprediksi output yang diinginkan. BART sangat berguna untuk menangani taksiran transformasi yang membutuhkan pemahaman konteks yang luas dari teks, seperti penerjemahan bahasa atau sumber-sintesis.
  
# Proses Training

# Testing

# Evaluasi
Evaluasi model menggunakan ROUGE dengan hasil evaluasi
rouge1: 0.37 | rouge2: 0.09 | rougeL: 0.09 --> avg rouge: 0.25

# Cara Menjalankan Aplikai
 Cara menjalankan aplikasi text summarization sebagai berikut.
 1. ketik peirntah di termninal vscode npm run dev untuk menjalankan aplikasi secara localhost.
 2. Masukan kalimat yang ingin diringkas pada kolom Enter Your Text.
 3. Tekan tombol summarize untuk mendapatkan hasil ringkasan yang telah dimasukan dan hasil bisa dilihat pada kolom Summarized Text.
