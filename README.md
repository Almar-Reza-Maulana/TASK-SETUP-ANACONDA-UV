# 🚀 Setup Environment Data Science/AI (Anaconda • Conda • UV)

Hallo semuanya ! Selamat datang di project saya yang lain. Disini saya akan membuat tutorial lingkungan kerja Data Science/AI paling **gaul** dan **gampang** dimengerti. Di sini kita bakal belajar:

- Apa itu **Anaconda**, **Conda**, dan **UV**
- Cara install dan step-by-stepnya
- Do’s & Don’ts biar nggak salah langkah

## Pengenalan Anaconda, Conda , dan UV
➡️ Anaconda adalah distribusi Python yang super populer, dikembangin sama Anaconda, Inc. yang spesifik banget buat kebutuhan ilmu data dan analisis numerik. Dia dirancang untuk jadi "toolkit lengkap" bagi para ilmuwan data, biar semua yang kamu butuhin udah ada dalam satu paket. 😎🐍\
Apa aja sih isinya?\
Anaconda nggak hanya menyediain interpreter Python, tapi juga sejumlah pustaka keren seperti:
- NumPy & Pandas: Buat olah dan analisis data.
- Matplotlib: Buat visualisasi data yang kece.
- SciPy & Scikit-learn: Buat analisis numerik dan pembelajaran mesin.
Selain itu, ada juga alat-alat pendukung yang nggak kalah penting, kayak:
- Jupyter Notebook: Biar kamu bisa interaktif coding dan coba-coba langsung.
- Spyder: IDE buat coding Python yang nyaman.
- Anaconda Navigator: GUI yang bikin kamu bisa ngatur environment dan install paket lewat klik-klik, tanpa harus repot dengan command line. 🚀💻\
  
➡️ Conda Conda adalah tool open source dari Anaconda yang mengelola paket dan virtual environment. Dengan conda, kamu bisa instal, update, atau hapus paket beserta dependency-nya dan membuat lingkungan kerja terpisah untuk setiap proyek sehingga tidak terjadi bentrok. Karena paketnya precompiled, instalasinya jadi mudah tanpa harus membangun dari source. Selain Python, conda juga mendukung bahasa lain.

➡️ UV dalam Python biasanya merujuk ke **Virtual Environment (venv/virtualenv)**, yaitu fitur yang memungkinkan kamu membuat lingkungan kerja terpisah untuk setiap proyek. Dengan virtual environment, setiap proyek punya versi Python dan paketnya sendiri, sehingga tidak bentrok dengan proyek lain. Ini berguna banget buat manajemen dependency dan menjaga sistem tetap bersih tanpa harus install paket secara global. 🚀🐍

## 📥 CHAPTER 1 : Download and Install Anaconda

Apa : Anaconda merupakan distribusi Python yang populer, yang dirancang untuk ilmu data, pembelajaran mesin, dan analisis data.\
Kenapa : Anaconda memungkinkan kita untuk membuat dan mengelola lingkungan terpisah untuk proyek yang berbeda

Do & Don'ts :
-Do : download installer di website anaconda resmi yah \
-Don't : Hindari link download dari blog tidak resmi, forum, atau situs berbagi file. Hanya gunakan situs resmi Anaconda.

## 🪜 Tahapan unduh dan instalasi anaconda

Langkah 1: Kunjungi Situs Resmi Anaconda
![TASK-SETUP-ANACONDA-UV](https://github.com/Almar-Reza-Maulana/TASK-SETUP-ANACONDA-UV/blob/main/SS/Screenshot%202025-06-12%20082404.png)
Kunjungi situs download resmi Anaconda: https://www.anaconda.com/download

Langkah 2: Pilih Installer yang Sesuai
Pilih salah satu sistem operasi yang kamu pakai (Windows, macOS, atau Linux). lalu
pilih installer 64-Bit Graphical Installer.

Langkah 3: Download File Installer
Klik tombol Download.
Browser akan mulai mengunduh file installer (misalnya, Anaconda3-2023.09-0-Windows-x86_64.exe). Tunggu hingga proses download selesai.

Langkah 4: Jalankan File Installer
Buka folder "Downloads" di komputer Anda.
Cari file installer yang baru saja diunduh.
Klik dua kali pada file tersebut untuk memulai proses instalasi. Jika muncul peringatan keamanan dari Windows, klik "Run" atau "Yes".

Langkah 5: Ikuti Petunjuk Instalasi (Installation Wizard)
Ini adalah bagian paling krusial. Baca setiap langkah dengan teliti.
1. Welcome Screen: Klik "Next" untuk memulai.\
  ![TASK-SETUP-ANACONDA-UV](https://github.com/Almar-Reza-Maulana/TASK-SETUP-ANACONDA-UV/blob/main/SS/Screenshot%202025-06-12%20092026.png) 
3. License Agreement (Perjanjian Lisensi): Klik "I Agree" untuk melanjutkan.
4. Select Installation Type (Pilih Tipe Instalasi)🏠︎:\
 ![TASK-SETUP-ANACONDA-UV](https://github.com/Almar-Reza-Maulana/TASK-SETUP-ANACONDA-UV/blob/main/SS/Screenshot%202025-06-13%20092640.png)\
• Kamu akan diberi dua pilihan: "Just Me" atau "All Users".\
• Pilih aja "Just Me". Opsi ini lebih sederhana, tidak memerlukan hak administrator, dan menghindari banyak potensi masalah perizinan di kemudian hari.\
• Klik "Next".
5. Choose Install Location (Pilih Lokasi Instalasi)📍: \
 ![TASK-SETUP-ANACONDA-UV](https://github.com/Almar-Reza-Maulana/TASK-SETUP-ANACONDA-UV/blob/main/SS/Screenshot%202025-06-13%20094755.png)\
• Disarankan untuk membiarkan lokasi instalasi di folder default yang disarankan oleh installer (biasanya di C:\Users\Nama_Kamu\anaconda3).\
• PENTING: Jangan memilih folder yang namanya mengandung spasi atau karakter non-latin (seperti C:\Program Files\Anaconda). Ini bisa menyebabkan masalah saat menjalankan program dari command line.\
• Klik "Next".
7. Advanced Installation Options (Opsi Instalasi Lanjutan)✔️: \
 ![TASK-SETUP-ANACONDA-UV](https://github.com/Almar-Reza-Maulana/TASK-SETUP-ANACONDA-UV/blob/main/SS/Screenshot%202025-06-12%20092711.png)\
Centang 3 kotak ini. Ini buat mastiin bahwa aplikasi yang membutuhkan Python akan mengenali Python dari Anaconda. Setelah selesai, klik "Install".
8. Installation Progress (Proses Instalasi)⏳:
Proses instalasi akan dimulai. Setelah instalasi selesai, klik "Next". Kamu mungkin akan melihat layar tentang "Anaconda Distribution". Klik "Next" lagi. lalu pada layar terakhir kamu bisa langsung klik "Finish".

Langkah 6 : Cek Instalasi Anaconda kamu 🧐
<!--[SS] -->
Untuk memastikan Anaconda kamu sudah terinstall dengan benar di sistem kamu, bisa lakukan verifikasi lewat Command Prompt (CMD) lalu ketik **conda -- version**

Langkah 7 : Konfigurasi Variabel Lingkungan Path 🔗
Nah, biar gak ribet tiap kali mau panggil conda atau python dari Anaconda, kamu bisa set PATH Environment Variable biar bisa dipanggil dari terminal manapun tanpa harus buka Anaconda Navigator dulu. Caranya :
1. Buka Pengaturan path :\
 - Tekan Win + S, cari "Edit system environment variables" lalu klik "Environment Variable" .
2. Tambahkan Path Baru
 - Klik Edit Variables di bagian "System Variables" → cari Path → klik Edit → tambah path berikut:
   ```
   C:\Users\Nama_user\anaconda3
   C:\Users\Nama_user\anaconda3\Library\mingw-w64\bin
   C:\Users\Nama_user\anaconda3\Library\usr\bin
   C:\Users\Nama_user\anaconda3\Library\bin
   C:\Users\Nama_user\anaconda3\Scripts
   ```
   [SS]
   
Langkah 8 : Membuat environment conda yang baru 🏡
Kenapa kita harus buat environment yang baru? karena kita mau project yang kita buat lebih tertata rapi dan tercampur aduk dengan yang lain. Untuk melakukannya kita bisa :
Buka terminal kembali → Jalankan perintah ini: conda create -n nama_env python=3.9 → klik y 
[SS]

Selamat, Anaconda kamu sudah berhasil ter-install😎!

## CHAPTER 2 : Membuat UV Environmnet
