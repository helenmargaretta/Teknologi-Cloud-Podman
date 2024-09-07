# Teknologi-Cloud-Podman
materi tentang podman 
# Podman: Alternatif Docker untuk Manajemen Container

## 1. Apa itu Podman?
Podman adalah salah satu tools open-source untuk menjalankan dan mengelola container yang berbasis pada standar OCI (Open Container Initiative). Podman sering dianggap sebagai alternatif Docker karena fungsi dan cara penggunaannya yang serupa, namun dengan beberapa perbedaan utama.

## 2. Keunggulan Podman
### a. **Tanpa Daemon**
Berbeda dengan Docker yang menggunakan daemon (latar belakang service), Podman berjalan tanpa daemon. Hal ini memungkinkan Podman untuk lebih ringan dan memiliki kontrol keamanan yang lebih baik.

### b. **Kompatibel dengan Docker**
Podman kompatibel dengan perintah Docker. Sebagian besar perintah Docker dapat dijalankan di Podman tanpa perubahan yang berarti. Ini membuat migrasi dari Docker ke Podman menjadi lebih mudah.

### c. **Rootless Containers**
Podman memungkinkan untuk menjalankan container tanpa hak akses root, yang meningkatkan keamanan. Ini menjadikan Podman pilihan yang lebih aman di lingkungan production.

## 3. Instalasi Podman
Podman dapat diinstal pada berbagai sistem operasi, termasuk Linux, macOS, dan Windows.

### a. Instalasi di Linux (Ubuntu)
Untuk menginstal Podman di Ubuntu, jalankan perintah berikut:

```bash
sudo apt update
sudo apt install podman -y
