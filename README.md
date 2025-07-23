# 🏁 Tugas Akhir (TA) - Final Project

**Nama Mahasiswa**: Vito Febrian Ananta  
**NRP**: 5025211224  
**Judul TA**: IDENTIFIKASI INFLUENCER UNTUK PEMASARAN MEREK DI INSTAGRAM DENGAN MULTIMODAL LEARNING
**Dosen Pembimbing**: Shintami Chusnul Hidayati, S.Kom., M.Sc., Ph.D. (NPP 1987202012004) 
**Dosen Ko-pembimbing**: -

---

## 📺 Demo Aplikasi  

[![Demo Aplikasi](/thumbnail.jpg)](https://youtu.be/znnljj45VMk)  
*Klik gambar di atas untuk menonton demo*

---

*Konten selanjutnya hanya merupakan contoh awalan yang baik. Anda dapat berimprovisasi bila diperlukan.*

## 🛠 Panduan Instalasi & Menjalankan Software  

### Langkah-langkah

1. **Meminta akses dataset:**
[Permintaan Akses Dataset](https://its.id/m/AksesDatasetTugasAkhirVito)

2. **Ekstrak dataset**

3. **Clone Repository**  
   ```bash
   git clone https://github.com/Informatics-ITS/ta-vitoananta3.git
   ```

4. **Masuk ke Dalam Folder Repositori**

5. **Copy Hasil Ekstrasi Database ke Folder Repositori (yang sudah di clone) ke Dalam Folder Database**

6. **Pastikan Struktur Direktori Seperti Ini:**
   ```
   ├── backend\
   │   └── main.py
   ├── dataset\
   │   ├── images\
   │   ├── json\
   │   ├── profile_infulencers\
   │   └── post_34000_sampled_clean_info.txt
   ├── frontend\
   │   ├── .gitignore
   │   ├── components.json
   │   ├── eslint.config.mjs
   │   ├── next.config.ts
   │   ├── package-lock.json
   │   ├── package.json
   │   ├── pnpm-lock.yaml
   │   ├── postcss.config.mjs
   │   ├── public\
   │   ├── src\
   │   │   ├── app\
   │   │   ├── components\
   │   │   └── lib\
   │   └── tsconfig.json
   ├── implementation\
   │   └── bab-4\
   │       └── main-2-engagement.py
   ├── inti\
   │   └── model-result\
   └── requirements.txt
   ```

7. **Membuat Virutal Environment**
   ```bash
   python -3.9 -m venv .venv
   ```

8. **Aktivasi Virutal Environment**
   ```bash
   source .venv/bin/activate
   ```

9. **Instalasi PyTorch CUDA**
   ```bash
   pip install install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
   ```

10. **Instalasi Dependensi**
   ```bash
   pip install -r requirements.txt
   ```

11. **Jalankan Aplikasi Backend**
   ```bash
   python backend/main.py
   ```

12. **Jalankan Aplikasi Frontend**
   ```bash
   cd frontend/
   npm install
   npm run dev
   ```
13. **Buka browser dan kunjungi: `http://localhost:8000` (Aplikasi Backend)**

14. **Buka browser dan kunjungi: `http://localhost:3000` (Aplikasi Frontend)**

15. **Selamat Anda Telah Berhasil Menjalankan Aplikasi**

> Panduan Penggunaan Aplikasi Dapat Dilihat Melalui Demo Video di Atas

---

## ⁉️ Pertanyaan?

Hubungi:
- Penulis: vitoananta3@gmail.com
- Pembimbing Utama: shintami@its.ac.id
