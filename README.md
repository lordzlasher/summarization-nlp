# Deskripsi Aplikasi
Text summarization adalah proses mengurangi teks yang panjang dan kompleks menjadi versi yang lebih pendek dan lebih mudah dipahami, yang menyajikan informasi penting dari teks asli. Aplikasi text summarization bertujuan untuk membantu pengguna memahami ide-ide utama dari teks dengan cepat dan mudah, tanpa harus membaca seluruh teks.

# Arsitektur Aplikasi
Aplikasi yang dibuat berbasis website dengan menggunakan Next.js sebagai client-side dan TailwindCSS untuk style. Pemanggilan model menggunakan API dari RapidAPI

#Struktur
[`pages directory`] : It has the index.js file, which is the entry point of our app, basically the home page. It also has_app.js and another directory named api, where we will store the requests to our API.
['public directory']: It holds assets. You can place your static files here to load later in the application.
['package.json']: This file contains the metadata of your project.
['package-lock.json']: This file is responsible for tracking the exact version of every installed package.
['postcss.config.js']: This file contains PostCSS configurations.
['tailwind.config.js']: It contains TailwindCSS configurations.

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
 1. Instal seluruh dependencies yang terdapat di program
 ```bash
npm install
```
2. Jalan aplikasi
```bash
npm run dev
``` 
3. Aplikasi akan berjalan pad localhost:3000
4. Masukan kalimat yang ingin diringkas pada kolom Enter Your Text.
5. Tekan tombol summarize untuk mendapatkan hasil ringkasan yang telah dimasukan dan hasil bisa dilihat pada kolom Summarized Text.
