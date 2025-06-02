# 📁 Command Line : Virtualisasi dan Virtual Sistem pada Linux


## 1. Command Line: Docker
Dokumentasi ini menjelaskan langkah-langkah menggunakan Docker di Linux untuk menjalankan aplikasi dan sistem virtual berbasis container.

### a. Cek Katalog Software
```bash
sudo apt update
```
Memperbarui daftar paket dan repositori perangkat lunak dari server.

### b. Instalasi Docker
```bash
sudo apt install docker.io
```
Menginstal Docker dari repositori resmi Ubuntu.

### c. Memulai dan Mengaktifkan Layanan Docker
```bash
sudo systemctl start docker
```
Memulai layanan Docker.
```bash
sudo systemctl enable docker
```
Mengatur agar Docker otomatis berjalan saat booting.

### d. Cek Versi Docker
```bash
docker --version
```
Menampilkan versi Docker yang terinstal.

### e. Tambahkan User ke Grup Docker
```bash
sudo usermod -aG docker $USER
```
Menambahkan user ke grup Docker agar bisa menjalankan Docker tanpa sudo.

### f. Download Image Ubuntu
```bash
docker pull ubuntu
```
Mengunduh image Ubuntu ke sistem lokal.

### g. Lihat Semua Docker Images
```bash
docker images
```
Menampilkan semua image Docker yang tersedia di sistem.

### h. Jalankan Python dalam Docker
```bash
docker run -it python
```
Menjalankan container Python secara interaktif dengan terminal.

### i. Izinkan GUI X11 untuk Docker
```bash
xhost +local:docker
```
Memberi akses X11 agar container Docker bisa menampilkan GUI di host.

### j. Instal GUI Library (Tkinter) di Container
```bash
apt update && apt install -y python3-tk
```
Menginstal pustaka GUI Tkinter dalam container Docker.

### k. Install NumPy & Matplotlib
```bash
pip install numpy matplotlib
```
Menginstal library Python untuk komputasi numerik dan grafik.

### l. Lihat Semua Container Docker
```bash
docker ps -a
```
Menampilkan semua container, baik yang aktif maupun tidak aktif.

## 2. Command Line: Virtualenv (Python Virtual Environment)

### a. Instalasi Virtualenv
```bash
sudo apt install python3-virtualenv
```
Menginstal Virtualenv untuk membuat lingkungan Python terisolasi.

### b. Membuat Virtual Environment
```bash
virtualenv env
```
Membuat direktori lingkungan virtual bernama env.

### c. Aktifkan Virtual Environment
```bash
source env/bin/activate
```
Mengaktifkan lingkungan virtual agar dapat menjalankan Python terisolasi.

### d. Instalasi Library di Virtualenv
```bash
pip install matplotlib
```
Menginstal Matplotlib dalam virtual environment.
