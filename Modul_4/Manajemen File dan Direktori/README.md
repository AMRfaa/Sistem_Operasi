
# 📁 Command Line: Manajemen File dan Direktori

Dokumentasi ini menjelaskan cara menggunakan command line (terminal) di Linux (Ubuntu) untuk membuat, mengelola, memindahkan, dan menghapus file serta direktori (folder).

## 1. Membuat dan Mengelola File

### a. Membuat Directory
```bash
mkdir Modul4
```

### b. Membuat File Kosong
```bash
touch file1.txt
```

### c. Membuat Folder Baru
```bash
mkdir folderbaru
```

### d. Menyalin File ke Folder
```bash
cp file1.txt folderbaru
cd folderbaru
```

### e. Menghapus File dan Folder
```bash
rm filesampah.txt       # Menghapus file
rmdir foldersampah      # Menghapus folder kosong
```

### f. Mengubah Nama File
```bash
mv file1.txt file2.txt
```

### g. Memindahkan File ke Folder yang Sama
```bash
mv file2.txt folderbaru
```

### h. Memindahkan File ke Direktori Lain
```bash
mv file2.txt /home/amrxfaa/Modul4
```

---

## 📌 Catatan:
- Gunakan `ls` untuk melihat isi direktori.
- Gunakan `pwd` untuk mengetahui lokasi direktori saat ini.
- Gunakan `man [perintah]` untuk membaca manual dari perintah tertentu, misalnya: `man mv`.

---

## 🧑‍💻 Kontributor:
- Dokumentasi oleh: AMRfaa  
- Bagian dari Modul 4: Sistem Operasi – Manajemen File dan Direktori
