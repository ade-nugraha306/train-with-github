# RESTful API
API ini menyediakan fungsionalitas untuk mendapatkan rekomendasi tempat wisata dan berinteraksi melalui chatbot untuk mendapatkan informasi seputar tempat wisata, termasuk prediksi rating dan klasifikasi popularitas. Kami menggunakan Python dengan Flask Framework untuk membangun RESTful API ini, dan respons yang diberikan dalam format JSON.

## Rekomendasi Wisata
Bagian ini menyediakan endpoint untuk mendapatkan rekomendasi tempat wisata berdasarkan fitur-fitur yang diberikan. Sistem rekomendasi ini dibangun menggunakan model yang memanfaatkan TF-IDF Vectorizer untuk representasi teks dan Cosine Similarity untuk menghitung kemiripan antar tempat wisata. Data utama untuk rekomendasi disimpan dalam DataFrame df_tourism yang diproses bersama dengan index place_indices.

**Base URL :**
> http://127.0.0.1:5000

**Path :**
> http://127.0.0.1:5000/recommend

**Method :**
> `POST`

**Deskripsi :**
> Deskripsi: Memberikan daftar rekomendasi tempat wisata berdasarkan kriteria input yang diberikan.

**Request Body :**
> `application/json`
















































