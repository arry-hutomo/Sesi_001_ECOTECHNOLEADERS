# Sesi_001_ECOTECHNOLEADERS
Materi pembelajaran untuk sesi pertama ECOTECHNOLEADERS

# Materi Pelatihan ECOTECHNOLEADERS - Sesi 001

Selamat datang di materi pelatihan sesi pertama untuk ECOTECHNOLEADERS!
Sharing Session by : Arry Hutomo

STAGES 001:  GREEN TECH INNOVATE (MEETING 001)

---

![PROGRAM ECC X NIN](https://github.com/arry-hutomo/Sesi_001_ECOTECHNOLEADERS/raw/main/PROGRAM%20ECC%20X%20NIN.png)


## 📚 Daftar Isi

1.  [Jam ke-1: Pengenalan Command Prompt (CMD)](#jam-ke-1-pengenalan-command-prompt-cmd)
2.  [Jam ke-2: Instalasi Python di Windows](#jam-ke-2-instalasi-python-di-windows)
3.  [Jam ke-3: Instalasi Visual Studio Code (VS Code) di Windows](#jam-ke-3-instalasi-visual-studio-code-vs-code-di-windows)
4.  [Jam ke-4: Memastikan Instalasi dan Validasi Path di Windows](#jam-ke-4-memastikan-instalasi-dan-validasi-path-di-windows)
5.  [Jam ke-5: Pengenalan dan Pembuatan Akun GitHub](#jam-ke-5-pengenalan-dan-pembuatan-akun-github)
6.  [🔗 Link ke Guide Pelatihan](#link-ke-guide-pelatihan)
7.  [🛠️ Cara 2: Menggunakan Git Secara Lokal (Untuk Pengembangan Lebih Lanjut)](#cara-2-menggunakan-git-secara-lokal-untuk-pengembangan-lebih-lanjut)

---

## ⏱️ Jam ke-1: Pengenalan Command Prompt (CMD)

[[Kembali ke Daftar Isi](#daftar-isi)]

**Membuka Command Prompt (CMD):**

* **Cara 1 (Melalui Start Menu):** Klik tombol **Start** (ikon Windows di pojok kiri bawah layar), ketik `cmd`, lalu klik **Command Prompt** dari hasil pencarian.
* **Cara 2 (Melalui Run):** Tekan tombol **Windows + R** secara bersamaan untuk membuka kotak dialog **Run**. Ketik `cmd` lalu tekan **OK** atau tekan **Enter**.

**Perintah Dasar CMD dan Contoh:**

* `cd` (Change Directory): Berpindah antar direktori.
    ```bash
    # Untuk masuk ke folder "Documents"
    cd Documents
    # Untuk kembali ke direktori sebelumnya
    cd ..
    # Untuk kembali ke root direktori
    cd \
    ```
* `dir` (Directory): Menampilkan daftar *file* dan folder.
    ```bash
    dir
    ```
* `mkdir` (Make Directory): Membuat folder baru.
    ```bash
    mkdir LatihanCMD
    ```
* `rmdir` (Remove Directory): Menghapus folder kosong.
    ```bash
    rmdir LatihanCMD
    ```
    ⚠️ **Perhatian:** `rmdir` hanya untuk folder kosong. Gunakan `del /S /Q <nama_folder>` (hati-hati!) untuk menghapus folder beserta isinya.
* `copy`: Menyalin *file*.
    ```bash
    copy data.txt backup.txt
    copy data.txt LatihanCMD
    ```
* `move`: Memindahkan *file* atau mengganti nama.
    ```bash
    move backup.txt LatihanCMD
    move data.txt info.txt
    ```
* `type`: Menampilkan isi *file* teks.
    ```bash
    type info.txt
    ```
* `cls` (Clear Screen): Membersihkan layar.
    ```bash
    cls
    ```

**Memahami Path dan Environment Variable di Windows:**

* **Path:** Daftar lokasi folder yang diperiksa Windows saat menjalankan perintah.
    ```bash
    echo %PATH%
    ```
* **Environment Variable:** Variabel konfigurasi sistem. Contoh: `USERNAME`, `TEMP`.
    ```bash
    set
    ```

---

## 🐍 Jam ke-2: Instalasi Python di Windows

[[Kembali ke Daftar Isi](#daftar-isi)]

**Mengunduh Installer Python:**
Buka *browser* dan kunjungi [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/). Unduh versi Python 3 untuk general

Tetapi Eco Techno Leader untuk Bootcamp ini teman2  ambil dari sini yah :

---

## ⬇️ Alternatif Unduhan Python dari Google Drive

[[Kembali ke Daftar Isi](#daftar-isi)]

Jika Anda mengalami kesulitan mengunduh Python dari situs web resmi, Anda dapat menggunakan tautan alternatif berikut untuk mengunduh *installer* Python versi 3.9.13 (64-bit) yang telah disediakan:

![Panduan Download Python](https://github.com/arry-hutomo/Sesi_001_ECOTECHNOLEADERS/raw/main/downloadpython.png)

**Tautan Google Drive:** [https://drive.google.com/drive/folders/19sN7v5BgAnjz34-EFMw8c83tl917Urer](https://drive.google.com/drive/folders/19sN7v5BgAnjz34-EFMw8c83tl917Urer)

**Langkah-langkah Mengunduh dari Google Drive:**

1.  **Buka Tautan Google Drive:** Klik tautan di atas atau salin dan tempelkan ke bilah alamat peramban internet Anda, lalu tekan Enter. Anda akan diarahkan ke folder Google Drive yang berisi beberapa *file*.

2.  **Cari File Installer Python:** Di dalam folder Google Drive, cari *file* dengan nama **`python-3.9.13-amd64.exe`**.

3.  **Pilih File untuk Diunduh:** Klik satu kali pada nama *file* **`python-3.9.13-amd64.exe`** untuk memilihnya.

4.  **Unduh File:** Setelah *file* terpilih, cari ikon **Unduh** (biasanya berbentuk panah menghadap ke bawah atau tiga titik vertikal yang akan membuka menu, lalu pilih **Unduh**). Ikon ini mungkin terletak di bagian atas halaman Google Drive.

5.  **Konfirmasi Unduhan (Jika Diperlukan):** Peramban Anda mungkin akan meminta konfirmasi sebelum memulai unduhan. Klik **Simpan** atau **OK** untuk melanjutkan.

6.  **Tunggu hingga Unduhan Selesai:** Proses unduhan akan dimulai. Anda dapat melihat status unduhan di bagian bawah peramban Anda atau di jendela unduhan peramban Anda.

Setelah *file* **`python-3.9.13-amd64.exe`** selesai diunduh, Anda dapat melanjutkan ke langkah-langkah instalasi Python seperti yang dijelaskan di bagian [Jam ke-2: Instalasi Python di Windows](#jam-ke-2-instalasi-python-di-windows) pada panduan ini.

---

**Menjalankan Installer Python:**
Klik dua kali *file* `.exe`. **Pastikan centang "Add Python X.X to PATH"**. Ikuti langkah instalasi.

**Verifikasi Instalasi Python:**
Buka CMD dan jalankan:
```bash
python --version
pip --version
```

---

## 💻 Jam ke-3: Instalasi Visual Studio Code (VS Code) di Windows

[[Kembali ke Daftar Isi](#daftar-isi)]

**Mengunduh Installer VS Code:**
Buka *browser* dan kunjungi [https://code.visualstudio.com/download](https://code.visualstudio.com/download). Unduh untuk Windows.

**Menjalankan Installer VS Code:**
Klik dua kali *file* `.exe`. Setujui lisensi, pilih lokasi (opsional), dan **centang semua opsi di "Select Additional Tasks"**, terutama "Add to PATH" dan "Open with Code". Klik "Install".

**Instalasi Extension Python di VS Code:**
Buka VS Code, klik ikon **Extensions**, cari `Python` (Microsoft), dan klik **Install**.

**Pengaturan Dasar VS Code:**

* **Ubah Tema:** `File` > `Preferences` > `Color Theme`.
* **Atur Font:** `File` > `Preferences` > `Settings`, cari `font family`.
* **Integrated Terminal:** `Terminal` > `New Terminal`.

---

## ⚙️ Jam ke-4: Memastikan Instalasi dan Validasi Path di Windows

[[Kembali ke Daftar Isi](#daftar-isi)]

**Memeriksa Ulang Instalasi:**
Cek versi Python dan pip di CMD. Pastikan *extension* Python terinstal di VS Code.

**Mengatur Environment Variables (PATH) di Windows (Jika belum diatur):**

1.  Cari "Environment Variables" di *Start Menu*.
2.  Klik "Edit the system environment variables".
3.  Klik tombol "Environment Variables...".
4.  Di bagian "System variables", pilih "Path" dan klik "Edit...".
5.  Klik "New" dan tambahkan *path* Python (misalnya `C:\Users\<NamaPenggunaAnda>\AppData\Local\Programs\Python\PythonXX\`).
6.  Klik "New" lagi dan tambahkan *path* Scripts (misalnya `C:\Users\<NamaPenggunaAnda>\AppData\Local\Programs\Python\PythonXX\Scripts\`).
7.  Klik "OK" pada semua jendela dan **restart CMD**.

**Latihan Menjalankan Script Python:**
Buat *file* `halo.py` di VS Code:
```python
print("Halo dari Python di Windows!")
nama = input("Siapa nama Anda? ")
print(f"Senang bertemu dengan Anda, {nama}!")
```
Jalankan di *Integrated Terminal* VS Code atau di CMD dengan perintah `python halo.py`.

---

## 🚀 Jam ke-5: Pengenalan dan Pembuatan Akun GitHub

[[Kembali ke Daftar Isi](#daftar-isi)]

**Membuka Situs Web GitHub:**
Kunjungi [https://github.com/](https://github.com/).

**Mendaftar Akun GitHub:**
Isi formulir pendaftaran dan ikuti langkah-langkahnya.

**Mengenal Interface Dasar GitHub:**

* Dashboard
* Profile
* Repositories
* Tombol "New repository"
* Search bar

**Membuat Repository Pertama:**

1.  Klik **"New repository"**.
2.  Isi nama (`latihan-python-windows`), deskripsi (opsional), pilih **"Public"**.
3.  Centang **"Add a README file"** dan **"Add .gitignore"** (pilih Python).
4.  Klik **"Create repository"**.

**Penjelasan Singkat tentang Git:**
Git adalah sistem *version control* yang mendasari GitHub.

---

## 🔗 Link ke Guide Pelatihan

[[Kembali ke Daftar Isi](#daftar-isi)]

Karena seluruh materi sudah ada di dalam *file* `README.md`, *link* yang paling utama adalah *link* ke halaman utama repositori Anda:

```
[https://github.com/](https://github.com/)<nama-pengguna-github-anda>/Sesi_001_ECOTECHNOLEADERS
```

Ganti `<nama-pengguna-github-anda>` dengan nama pengguna GitHub Anda. Ketika seseorang membuka *link* ini, mereka akan langsung melihat materi pelatihan yang sudah tersusun rapi di halaman tersebut.

Jika Anda ingin memberikan *link* langsung ke bagian tertentu (misalnya, Jam ke-1), *link* internal di dalam *file* `README.md` (seperti `#jam-ke-1-pengenalan-command-prompt-cmd`) akan bekerja ketika seseorang sudah berada di halaman repositori.

---

## 🛠️ Cara 2: Menggunakan Git Secara Lokal (Untuk Pengembangan Lebih Lanjut)

[[Kembali ke Daftar Isi](#daftar-isi)]

Untuk pengelolaan materi yang lebih kompleks atau jika Anda ingin bekerja secara *offline*, Anda bisa menggunakan Git secara lokal:

1.  **Clone Repositori:** Di komputer Anda, buka CMD atau Git Bash, lalu navigasikan ke direktori tempat Anda ingin menyimpan proyek. Jalankan perintah:
    ```bash
    git clone [https://github.com/](https://github.com/)<nama-pengguna-github-anda>/Sesi_001_ECOTECHNOLEADERS.git
    ```
2.  **Buat atau Edit File README.md:** Buka folder `Sesi_001_ECOTECHNOLEADERS` yang baru dibuat dan edit *file* `README.md` menggunakan *text editor* (seperti Notepad) atau *code editor* (seperti VS Code). Susun materi Anda menggunakan format Markdown.
3.  **Commit dan Push Perubahan:** Setelah selesai mengedit, kembali ke CMD atau Git Bash, navigasikan ke folder repositori Anda (`Sesi_001_ECOTECHNOLEADERS`), lalu jalankan perintah:
    ```bash
    git add README.md
    git commit -m "Menambahkan materi pelatihan sesi 1"
    git push origin main
    ```
    Ini akan mengunggah perubahan Anda ke repositori GitHub.

Untuk saat ini, mengedit *file* `README.md` langsung di GitHub adalah cara yang paling cepat dan mudah untuk memasukkan materi pembelajaran Anda.

---

🎉 Terima kasih telah mengikuti materi pelatihan sesi pertama ECOTECHNOLEADERS! 🎉



