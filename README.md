```markdown
# Sistem Penjadwalan Pertemuan Dosen - Universitas Sriwijaya

![Dashboard Mahasiswa](https://github.com/whyuprmna16/UAS_WEB/assets/112668565/6a6616bd-1e96-48c6-a6f9-03a115c671dd)


## 📖 Tentang Proyek

[cite_start]**Sistem Penjadwalan Pertemuan Dosen** adalah sebuah prototipe aplikasi web fungsional yang dirancang untuk menjawab tantangan dan inefisiensi dalam proses penjadwalan pertemuan manual antara mahasiswa dan dosen di lingkungan Universitas Sriwijaya[cite: 1, 472].

[cite_start]Metode konvensional melalui pesan instan atau email seringkali menimbulkan miskomunikasi, kesulitan menemukan waktu yang cocok, dan tidak adanya pencatatan formal[cite: 16]. [cite_start]Aplikasi ini hadir sebagai platform terpusat untuk mengotomatisasi proses tersebut, sehingga meningkatkan efisiensi, transparansi, dan akuntabilitas dalam interaksi akademik[cite: 19].

Proyek ini dibuat untuk memenuhi tugas Ujian Akhir Semester (UAS) mata kuliah Pemrograman Web.

### ⚠️ Catatan Penting
Aplikasi ini adalah **prototipe fungsional**. [cite_start]Artinya, semua fitur telah dirancang untuk bekerja, namun **tidak terhubung ke database online permanen**[cite: 485]. Sistem ini menggunakan `Session Storage` pada browser, sehingga semua perubahan (jadwal baru, status, feedback) hanya akan tersimpan selama sesi browser aktif. [cite_start]**Jika Anda menutup browser atau tab, semua data akan kembali ke kondisi awal**[cite: 489, 490].

## ✨ Fitur Utama

Aplikasi ini memiliki dua peran utama dengan fitur yang disesuaikan untuk masing-masing kebutuhan:

### 👨‍🎓 Fitur untuk Mahasiswa
* **Login & Autentikasi**: Masuk ke sistem menggunakan NIM.
* [cite_start]**Dasbor Utama**: Melihat daftar pertemuan yang statusnya masih "Disetujui" atau "Menunggu"[cite: 518].
* **Pengajuan Pertemuan Baru**: Proses 3 langkah mudah untuk mengajukan pertemuan:
    1.  [cite_start]Memilih Dosen dari daftar[cite: 554].
    2.  [cite_start]Memilih slot jadwal ketersediaan yang ditampilkan Dosen[cite: 555, 556].
    3.  [cite_start]Mengisi detail keperluan pertemuan[cite: 557].
* [cite_start]**Riwayat Pertemuan**: Melihat rekam jejak semua pertemuan yang pernah diajukan (Disetujui, Ditolak, Menunggu, Selesai)[cite: 582].
* [cite_start]**Umpan Balik (Feedback)**: Memberikan ulasan atau feedback untuk pertemuan yang telah ditandai "Selesai" oleh dosen[cite: 585, 586].
* [cite_start]**Notifikasi Status**: Menerima notifikasi pop-up saat pengajuan pertemuan disetujui, ditolak, atau diselesaikan oleh dosen[cite: 517].

### 👩‍🏫 Fitur untuk Dosen
* **Login & Autentikasi**: Masuk ke sistem menggunakan NIDN.
* [cite_start]**Dasbor Statistik**: Melihat ringkasan jumlah permintaan baru, jadwal yang disetujui, dan pertemuan yang telah selesai[cite: 628].
* [cite_start]**Kelola Jadwal Ketersediaan**: Menambah atau menghapus slot waktu ketersediaan untuk konsultasi yang dapat dilihat oleh mahasiswa[cite: 647, 649].
* **Manajemen Permintaan**: Mengelola semua permintaan yang masuk dengan aksi:
    * [cite_start]**Setujui**: Menerima permintaan pertemuan[cite: 684].
    * [cite_start]**Tolak**: Menolak permintaan dengan menyertakan alasan[cite: 685].
    * [cite_start]**Selesaikan**: Menandai pertemuan yang telah dilaksanakan sebagai selesai[cite: 687].
* [cite_start]**Riwayat Pertemuan Selesai**: Melihat arsip semua pertemuan yang telah selesai[cite: 714].
* [cite_start]**Lihat Feedback**: Membaca umpan balik yang diberikan oleh mahasiswa untuk evaluasi[cite: 715].

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun sepenuhnya menggunakan teknologi front-end standar:
* [cite_start]**HTML5**: Untuk struktur konten halaman web[cite: 270].
* [cite_start]**Tailwind CSS**: Sebagai framework CSS untuk membangun antarmuka pengguna yang modern dan responsif dengan cepat[cite: 270].
* [cite_start]**JavaScript (ES6)**: Untuk menangani semua logika, interaktivitas, dan manipulasi data di sisi klien[cite: 270].
* [cite_start]**jQuery**: Digunakan untuk menyederhanakan manipulasi DOM dan event handling[cite: 270].
* [cite_start]**GitHub Pages**: Untuk deployment dan hosting aplikasi web secara gratis[cite: 271].

## 🚀 Demo & Cara Penggunaan

Anda dapat mencoba langsung aplikasi ini melalui tautan berikut:

**[https://whyuprmna16.github.io/UAS_WEB/](https://whyuprmna16.github.io/UAS_WEB/)**

**Langkah-langkah Penggunaan:**
1.  Buka link demo di atas.
2.  Gunakan salah satu akun dari daftar di bawah untuk login.
3.  [cite_start]**Password default** untuk semua akun adalah: `123456`[cite: 491].

### Akun Dosen untuk Uji Coba

| Nama Dosen | NIDN (Username) |
| :--- | :--- |
| Prof. Siti Nurmaini, M.T. | `0002085908` |
| Dr. Ir. Ahmad Heryanto, M.T. | `0022018703` |
| Iman Saladin, S.Kom., M.M.S.I. | `0022108702` |
| Dr. Retno Lestari, M.Kom. | `0011223301` |
| Budi Santoso, S.T., M.Eng. | `0044556602` |
| Prof. Dr. Ir. Rina Marlina, M.Sc. | `0077889903` |

### Akun Mahasiswa untuk Uji Coba

| Nama Mahasiswa | NIM (Username) |
| :--- | :--- |
| Wahyu Pramana | `09030582226053` |
| Rahayu Prasiska | `0903058212608` |
| Wahyu Hidayat | `09030582126015` |
| Andi Wijaya | `09030582327001` |
| Citra Lestari | `09030582327002` |
| Eko Nugroho | `09030582327003` |
| Fitriani Indah | `09030582327004` |

## 📂 Struktur Proyek

Struktur file dan folder dalam proyek ini diatur sebagai berikut untuk kemudahan pengelolaan:

```

UAS\_WEB/
├── assets/
│   ├── img/
│   │   └── logo.png         \# Aset gambar
│   └── js/
│       └── main.js          \# File JavaScript utama berisi semua logika
├── bantuan.html
├── dashboard-dosen.html
├── dashboard-mahasiswa.html
├── index.html               \# Halaman login utama
├── jadwal-mahasiswa.html
├── kelola-jadwal-dosen.html
├── permintaan-dosen.html
├── pertemuan-selesai-dosen.html
├── profil-dosen.html
├── profil-mahasiswa.html
├── riwayat-pertemuan-mahasiswa.html
├── LICENSE
└── README.md

````

## 🔧 Menjalankan Proyek Secara Lokal

Untuk menjalankan proyek ini di komputer lokal Anda, ikuti langkah-langkah berikut:

1.  **Clone repositori ini:**
    ```sh
    git clone [https://github.com/whyuprmna16/UAS_WEB.git](https://github.com/whyuprmna16/UAS_WEB.git)
    ```
2.  **Masuk ke direktori proyek:**
    ```sh
    cd UAS_WEB
    ```
3.  **Buka file `index.html`** langsung di browser pilihan Anda (misalnya Google Chrome, Firefox, atau Edge). Tidak ada proses instalasi atau kompilasi yang diperlukan.
