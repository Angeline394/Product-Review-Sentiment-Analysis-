# 🛍️ Product Review Sentiment Analysis (2025)

Analisis sentimen terhadap ulasan produk untuk mengidentifikasi opini positif dan negatif dari pelanggan. Proyek ini mengimplementasikan preprocessing teks, eksplorasi kata kunci, dan visualisasi berbasis Word Cloud.

## 🧠 Tujuan
Mengolah data review pelanggan dalam format CSV dan mengklasifikasikan sentimen menggunakan analisis kata serta visualisasi teks.

## 🛠️ Teknologi
- Python (Pandas, NLTK)
- Visualisasi: Matplotlib, WordCloud
- Dataset: CSV file berisi ulasan produk

## 🔍 Fitur Utama
- Preprocessing teks (case folding, stopword removal, tokenizing)
- Analisis kata yang sering muncul
- Word Cloud untuk menampilkan kata-kata dominan
- Visualisasi distribusi sentimen



### 🖼️ Visualisasi Output

- **✅ Data berhasil dimuat**
  
  ![Data berhasil dimuat](output/Data%20berhasil%20dimuat.png)
  
  Menampilkan hasil konfirmasi bahwa dataset CSV berhasil dimuat ke dalam DataFrame.

- **☁️ Membuat dan menyimpan visualisasi Word Cloud**
  
  ![Word Cloud](output/Membuat%20dan%20menyimpan%20visualisasi%20Word%20Cloud.png)
  
  Visualisasi Word Cloud dari kata-kata dominan dalam ulasan produk, membantu mengidentifikasi topik utama yang dibicarakan pengguna.

- **📊 Membersihkan label sentimen lalu menampilkan distribusinya**
  
  ![Distribusi Sentimen](output/membersihkan%20label%20sentimen%20lalu%20menampilkan%20distribusinya.png)
  
  Menampilkan distribusi jumlah ulasan berdasarkan sentimen (positif, negatif, atau netral) setelah proses pembersihan data label.

---

Semua visualisasi pada folder `/output/` dihasilkan secara otomatis melalui notebook Python dengan menggunakan `matplotlib` dan `wordcloud`.
