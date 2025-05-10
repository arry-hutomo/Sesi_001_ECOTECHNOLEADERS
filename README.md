![PROGRAM ECC X NIN](https://github.com/arry-hutomo/Sesi_001_ECOTECHNOLEADERS/raw/main/PROGRAM%20ECC%20X%20NIN.png)

## Materi pembelajaran untuk sesi pertama ECOTECHNOLEADERS
---
##### **Oke, gaspol ETL'ers! Perjalanan belajar kita ini ada stages-nya, mulai dari "Green Tech Innovate" di Stage 1, lanjut jadi "Eco Data Pioneers" di Stage 2, terus "Sustainable AI Innovators" di Stage 3, hingga jadi "Future Eco Visionaries" di Stage 4 dan puncaknya sebagai "AI Eco Trailblazers" di Stage 5. Pastikan kalian baca dan simak tiap materi sampai tuntas, ya! Soalnya, program ini bakal ngasih kalian superpower buat ngadepin disruptive sustainability pake teknologi. Kalian bakal di-support tim ECC, Komunitas Nawala Integra Nusantara, dan Lead Mentor Kak Arry Hutomo. Setiap step ngebuka wawasan buat solusi inovatif. Semangat!**
---

## LINK SILABUS PEMBELAJARAN ECO-TECHNO LEADERS (ETL)
[SILABUS](https://github.com/arry-hutomo/Sesi_001_ECOTECHNOLEADERS/blob/main/ETC-DB%20BATCH%209-10.xlsx)
Klik link silabus ⬇️


---

### ETL'ers sering di lihat ya repository untuk MATERI dan TASK UPDATE di
[LINK](https://github.com/arry-hutomo), <-- Klik Repository Arry Hutomo
---

# Materi Pelatihan ECOTECHNOLEADERS - Sesi 001

Selamat datang di materi pelatihan sesi pertama untuk ECOTECHNOLEADERS!
Sharing Session by : Arry Hutomo

STAGES 001:  GREEN TECH INNOVATE (MEETING 001)

---




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
[CMDTRIK](https://github.com/arry-hutomo/Sesi_001_ECOTECHNOLEADERS/blob/main/tipandtrik_cmd/README.md)
>>> KLIK LINK DIATAS untuk melihat tip and trik lain
---

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
---

## ⚙️ Langkah-Langkah Instalasi Python 3.9.13 di Windows

[[Kembali ke Daftar Isi](#daftar-isi)]

Bagian ini akan memandu Anda melalui proses instalasi *file* `python-3.9.13-amd64.exe`.

**Langkah 1: Jalankan File Installer**

1.  **Temukan File Installer:** Setelah Anda berhasil mengunduh *file* `python-3.9.13-amd64.exe` (baik dari situs resmi atau dari Google Drive yang disediakan), cari lokasi *file* tersebut di komputer Anda (biasanya di folder "Unduhan" atau "Downloads").

2.  **Jalankan Installer:** Klik dua kali (*double-click*) pada *file* `python-3.9.13-amd64.exe` untuk memulai proses instalasi. Anda mungkin akan melihat jendela peringatan keamanan dari Windows, klik **"Run"** atau **"Jalankan"** untuk melanjutkan.

**Langkah 2: Konfigurasi Instalasi Penting**

Di jendela instalasi Python pertama, Anda akan melihat dua opsi utama di bagian bawah:

* **Install now**
* **Customize installation**

**Sangat penting untuk mencentang dua kotak di bawah opsi ini:**

* **☑️ Add Python 3.9 to PATH**
* **☑️ Use default settings** (biasanya sudah tercentang jika Anda memilih "Install now") atau pastikan opsi `pip` tercentang jika Anda memilih "Customize installation".

    **Mengapa ini penting?** Mencentang **"Add Python 3.9 to PATH"** akan secara otomatis menambahkan direktori Python dan *script*-nya (termasuk `pip`) ke *Environment Variables* Windows Anda. Ini memungkinkan Anda menjalankan perintah `python` dan `pip` dari Command Prompt (CMD) tanpa harus menentukan lokasi *file* secara manual.

**Langkah 3: Lanjutkan Proses Instalasi**

1.  **Pilih Metode Instalasi:**
    * **Disarankan untuk Pemula:** Klik **"Install Now"** untuk instalasi dengan pengaturan standar.
    * **Jika Anda ingin mengubah lokasi instalasi atau memilih komponen tertentu:** Klik **"Customize installation"**. Pada layar berikutnya, pastikan opsi **"pip"** tercentang. Anda juga bisa mengubah lokasi instalasi jika perlu. Klik **"Next"** setelah memilih opsi Anda. Pada layar "Advanced Options", **pastikan kotak "Add Python to environment variables" tercentang**. Kemudian, klik **"Install"**.

2.  **Tunggu Proses Instalasi:** Proses instalasi akan berjalan. Tunggu hingga selesai. Anda akan melihat bilah kemajuan yang menunjukkan status instalasi.

3.  **Selesaikan Instalasi:** Setelah instalasi berhasil, Anda akan melihat jendela dengan pesan **"Setup was successful"**. Klik tombol **"Close"** atau **"Tutup"**.

**Langkah 4: Memastikan Python dan PIP Terdeteksi di Windows**

Setelah instalasi selesai, kita akan memverifikasi bahwa Python dan PIP telah terinstal dengan benar dan *path*-nya sudah tervalidasi di *environment* Windows Anda. Kita akan menggunakan Command Prompt (CMD) untuk ini.

1.  **Buka Command Prompt (CMD):**
    * Tekan tombol **Windows** pada *keyboard* Anda.
    * Ketik `cmd`.
    * Klik pada **"Command Prompt"** dari hasil pencarian.

2.  **Verifikasi Instalasi Python:** Di jendela CMD, ketik perintah berikut dan tekan **Enter**:

    ```cmd
    python --version
    ```

    Jika Python terinstal dengan benar dan *path* sudah diatur, Anda akan melihat output yang menunjukkan versi Python yang telah Anda instal (dalam kasus ini, seharusnya `Python 3.9.13`). Contoh output:

    ```
    Python 3.9.13
    ```

3.  **Verifikasi Instalasi PIP:** Di jendela CMD yang sama, ketik perintah berikut dan tekan **Enter**:

    ```cmd
    pip --version
    ```

    Jika PIP terinstal dengan benar dan *path*-nya juga sudah diatur, Anda akan melihat output yang menunjukkan versi PIP dan lokasi instalasinya. Contoh output:

    ```
    pip 21.2.4 from C:\Users\<NamaPenggunaAnda>\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.9_qbz5n2kfra8p0\LocalCache\local-packages\Python39\site-packages\pip (python 3.9)
    ```

    **Catatan:** Lokasi PIP pada output Anda mungkin berbeda tergantung pada bagaimana Anda menginstal Python.

**Langkah 5: Memeriksa Environment Variables (Opsional, Jika Ada Masalah)**

Jika Anda mengalami masalah (misalnya, perintah `python` atau `pip` tidak dikenali), Anda mungkin perlu memeriksa *Environment Variables* secara manual untuk memastikan *path* Python telah ditambahkan.

1.  **Buka System Properties:**
    * Tekan tombol **Windows** pada *keyboard* Anda.
    * Ketik `environment variables`.
    * Pilih **"Edit the system environment variables"**.

2.  **Klik Tombol "Environment Variables...":** Di jendela "System Properties", klik tombol **"Environment Variables..."**.

3.  **Periksa Variabel "Path" di "User variables" atau "System variables":**
    * Cari variabel bernama **"Path"** di salah satu bagian tersebut (biasanya di "User variables" untuk instalasi khusus pengguna, atau di "System variables" untuk instalasi seluruh sistem).
    * Pilih variabel **"Path"** dan klik tombol **"Edit..."**.

4.  **Verifikasi Path Python:** Di jendela "Edit environment variable", pastikan Anda melihat dua entri yang terkait dengan Python:

    * Satu entri mengarah ke direktori utama instalasi Python (misalnya, `C:\Users\<NamaPenggunaAnda>\AppData\Local\Programs\Python\Python39`).
    * Satu entri lagi mengarah ke direktori *Scripts* Python (misalnya, `C:\Users\<NamaPenggunaAnda>\AppData\Local\Programs\Python\Python39\Scripts`).

    **Catatan:** Lokasi ini bisa berbeda tergantung pada pilihan instalasi Anda. Jika Anda mencentang "Add Python to PATH" saat instalasi, entri ini seharusnya sudah ada.

5.  **Tambahkan Path Jika Belum Ada (Hanya Jika Diperlukan):** Jika salah satu atau kedua *path* di atas tidak ada, klik tombol **"New"** dan tambahkan *path* yang sesuai. Pastikan Anda memasukkan *path* yang benar sesuai dengan lokasi instalasi Python Anda.

6.  **Klik "OK":** Klik **"OK"** pada semua jendela yang terbuka untuk menyimpan perubahan.

7.  **Restart CMD:** Tutup semua jendela Command Prompt yang terbuka dan buka CMD baru agar perubahan *Environment Variables* diterapkan. Kemudian, coba lagi perintah `python --version` dan `pip --version`.

Dengan mengikuti langkah-langkah ini, Anda akan berhasil menginstal Python 3.9.13 dan memastikan Python serta PIP dapat digunakan di sistem Windows Anda.

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

---
## LEBIH DETAIL SEBAGAI BERIKUT:

######
# Proyek AI Engineering dengan Python dan Analisis Database

Repository ini berisi *source code* dan materi terkait proyek AI Engineering yang dikembangkan menggunakan Python, dengan fokus pada kemampuan analisis database. Untuk pengalaman pengembangan yang optimal, disarankan untuk menggunakan Visual Studio Code (VS Code) dengan ekstensi-ekstensi berikut:

## Ekstensi VS Code yang Direkomendasikan

Berikut adalah daftar ekstensi VS Code yang sangat berguna untuk proyek ini, beserta penjelasan fungsi dan *publisher*-nya:

### Untuk Formatting Kode Python yang Baik
---
1.  **Python** (*Publisher*: Microsoft)
    * **Fungsi:** Ekstensi fundamental yang menyediakan dukungan bahasa Python secara menyeluruh di VS Code. Ini mencakup fitur seperti *IntelliSense* (pelengkapan kode otomatis, pemeriksaan sintaksis), *linting* (analisis kode untuk kesalahan dan gaya), *debugging* (alat untuk mencari dan memperbaiki *bug*), *testing* (integrasi dengan *framework* pengujian Python), dan banyak lagi. Ekstensi ini adalah fondasi utama untuk pengembangan Python.
---
2.  **Pylance** (*Publisher*: Microsoft)
    * **Fungsi:** Sebuah *language server* yang sangat cepat dan kaya fitur untuk Python. Pylance menawarkan analisis kode yang lebih akurat dan performa yang lebih baik dibandingkan dengan *language server* bawaan dari ekstensi Python. Ini membantu dalam mendeteksi kesalahan pengetikan, saran kode yang lebih cerdas, dan pemahaman kode yang lebih baik secara keseluruhan.
---
3.  **Black Formatter** (*Publisher*: ms-python)
    * **Fungsi:** Sebuah *code formatter* otomatis yang memastikan kode Python Anda sesuai dengan gaya yang konsisten. Black secara otomatis mengatur format kode seperti spasi, baris baru, dan panjang baris agar sesuai dengan standar yang telah ditentukan. Ini membantu menjaga kode tetap bersih dan mudah dibaca tanpa perlu memformatnya secara manual.
---
4.  **flake8** (*Publisher*: Coala)
    * **Fungsi:** Sebuah *linter* yang membungkus beberapa alat pengecekan kode Python seperti PyFlakes, pycodestyle (pemeriksaan gaya PEP 8), dan McCabe (pemeriksaan kompleksitas kode). Flake8 membantu Anda menulis kode yang tidak hanya benar secara sintaksis tetapi juga sesuai dengan pedoman gaya Python dan menghindari potensi masalah atau kompleksitas yang berlebihan.
---
5.  **isort** (*Publisher*: ms-python)
    * **Fungsi:** Ekstensi ini secara otomatis mengurutkan dan mengatur impor (*import*) dalam file Python Anda. Impor akan diurutkan secara alfabetis dan dipisahkan berdasarkan bagian standar, pihak ketiga, dan lokal. Ini membuat bagian impor kode Anda lebih terorganisir dan mudah dikelola.
---
---
### Untuk Analisis Database
---
1.  **SQLTools** (*Publisher*: mtxr)
    * **Fungsi:** Ekstensi yang sangat berguna untuk terhubung dan berinteraksi dengan berbagai jenis sistem manajemen basis data relasional (RDBMS) langsung dari dalam VS Code. Anda dapat membuat koneksi ke database seperti PostgreSQL, MySQL, SQL Server, SQLite, dan lainnya. Fiturnya meliputi menjalankan kueri SQL, melihat hasil dalam format tabel, menjelajahi skema database (tabel, kolom, *view*, dll.), dan melihat riwayat kueri.
---
2.  **Database Client** (*Publisher*: Bervariasi, contoh: Chris Kolkman, Jun Han, Microsoft)
    * **Fungsi:** Bergantung pada jenis database yang sering Anda gunakan, mungkin ada ekstensi klien database spesifik yang menawarkan fitur yang lebih mendalam. Cari di *marketplace* VS Code berdasarkan nama database Anda (misalnya, "PostgreSQL", "MySQL", "SQL Server"). Ekstensi ini sering kali menyediakan fitur tambahan yang disesuaikan untuk database tertentu, seperti alat administrasi, visualisasi data yang lebih canggih, atau integrasi fitur spesifik database.
---
3.  **CSV to Table** (*Publisher*: Mehedi Hassan)
    * **Fungsi:** Ekstensi sederhana yang memungkinkan Anda melihat file dengan format CSV (Comma Separated Values) dalam tampilan tabel yang rapi di dalam editor VS Code. Ini sangat membantu untuk memeriksa data dalam file CSV dengan cepat tanpa perlu membuka aplikasi *spreadsheet* eksternal.
---
4.  **Data Preview** (*Publisher*: RandomFractals Inc.)
    * **Fungsi:** Ekstensi ini memungkinkan Anda melihat pratinjau data dalam format tabel untuk berbagai jenis file data, termasuk CSV dan JSON. Ini berguna untuk dengan cepat memeriksa konten file data Anda dalam format yang mudah dibaca sebelum atau selama proses analisis. Beberapa implementasi mungkin juga menawarkan fitur interaktif seperti penyortiran dan pemfilteran data.
---
## Cara Menginstal Ekstensi di VS Code

1.  Buka Visual Studio Code.
2.  Klik ikon **Extensions** di *Activity Bar* (bilah sisi di sebelah kiri, ikonnya terlihat seperti empat persegi). Atau gunakan pintasan keyboard `Ctrl+Shift+X` (Windows/Linux) atau `Cmd+Shift+X` (macOS).
3.  Di kotak pencarian, ketik nama ekstensi yang ingin Anda instal (misalnya, "Python", "SQLTools").
4.  Cari ekstensi yang sesuai dari daftar hasil dan klik tombol **Install** di samping nama ekstensi.
5.  Setelah instalasi selesai, Anda mungkin perlu memuat ulang VS Code agar ekstensi aktif sepenuhnya.
---
Dengan menginstal ekstensi-ekstensi ini, Anda akan memiliki lingkungan pengembangan yang lebih produktif dan efisien untuk proyek AI Engineering dan analisis database Anda menggunakan Python di VS Code.
---
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



