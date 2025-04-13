# Analisis Sentimen Ulasan Aplikasi BCA Mobile di Google Play Store Menggunakan Deep Learning

Proyek ini merupakan submission dari modul 'Belajar Pengembangan Machine Learning" Dicoding. Proyek analisis sentimen ini menggunakan model pelatihan dari library Python dan algoritma machine learning klasik maupun deep learning.

## Teknologi yang Digunakan

- **Python 3.x**
- **TensorFlow** untuk deep learning
- **Scikit-learn** untuk machine learning klasik
- **Pandas** untuk manipulasi data
- **Google Play Scraper** untuk mengakses data aplikasi dari Google Play Store
- **Matplotlib** & **Seaborn** untuk visualisasi data

## Requirements

### 1. **Clone Repository**
   Jika belum meng-clone repository, buka terminal di VSCode dan jalankan perintah berikut:

   ```bash
   git clone https://github.com/username/repository_name.git
   cd repository_name
   ```

### 2. **Buat Virtual Environment (Opsional tapi disarankan)**
   Sebelum menginstall dependensi, disarankan untuk menggunakan **virtual environment** agar dependensi proyek tidak bercampur dengan sistem Python global.

   - Untuk membuat virtual environment:
     ```bash
     python -m venv venv
     ```

   - Untuk mengaktifkan virtual environment di terminal VSCode:
     - **Windows**:
       ```bash
       .\venv\Scripts\activate
       ```
     - **MacOS/Linux**:
       ```bash
       source venv/bin/activate
       ```

### 3. **Generate `requirements.txt` dengan `pipreqs`**
   Jika ksudah berada di folder proyek, gunakan **`pipreqs`** untuk menghasilkan file `requirements.txt` berdasarkan impor yang ada di dalam kode Python.

   - Jalankan perintah berikut di terminal VSCode:
     ```bash
     pipreqs . --force
     ```

   Perintah ini akan mencari semua dependensi yang digunakan dalam kode dan menghasilkan file `requirements.txt` di folder yang sama.

   **Catatan:**
   - Opsi `--force` digunakan untuk menimpa `requirements.txt` jika sudah ada.

### 4. **Install Dependencies**
   Setelah `requirements.txt` terbuat, install dependensi yang terdaftar dengan menggunakan **`pip`**:

   ```bash
   pip install -r requirements.txt
   ```

   Perintah ini akan menginstall semua library yang terdaftar di `requirements.txt`.

---

Beberapa library yang digunakan adalah sebagai berikut:
- **gdown** untuk mengunduh file dari Google Drive.
- **google-play-scraper** untuk mengambil data aplikasi dari Google Play Store.
- **pandas** dan **numpy** untuk manipulasi data dan perhitungan numerik.
- **nltk** dan **Sastrawi** untuk pemrosesan bahasa alami (NLP).
- **tensorflow** dan **scikit-learn** untuk pelatihan model machine learning.

---

## Kontak

Jika ada pertanyaan lebih lanjut atau masalah terkait penggunaan proyek ini, silakan hubungi saya di [cikarahmanniaa@gmail.com].



