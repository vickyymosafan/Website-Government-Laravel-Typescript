## **Deskripsi Proyek**

Sistem pemerintahan berbasis web. Sistem ini **mengharuskan setiap pengguna untuk registrasi dan login terlebih dahulu** sebelum mengakses fitur apapun. Terdapat **dua jenis pengguna: Admin dan Penduduk**.

- **Penduduk** dapat **mendaftar, mengajukan dan mencetak KTP, KK, Akta Kelahiran, dan Akta Kematian**, serta membaca **berita pemerintahan**.
- **Admin** memiliki akses penuh untuk **mengelola penduduk, dokumen, berita, dan log aktivitas pengguna**.

Sistem ini memiliki **UI/UX modern, performa tinggi, tanpa redundansi kode**, serta **responsif di semua perangkat**. Dengan penggunaan **TypeScript**, kode menjadi lebih **terstruktur, aman, dan scalable**.

---

## **Fitur Utama**

1. **Login Penduduk**

    - **Penduduk wajib login** sebelum dapat mengakses fitur pengajuan dokumen dan berita.
    - Setelah login, pengguna diarahkan ke **dashboard penduduk**.

2. **Login Admin**

    - **Admin wajib login** sebelum dapat mengelola sistem.
    - Setelah login, admin diarahkan ke **dashboard admin**.

3. **Logout**

---

### **Penduduk (User)**

1. **Dashboard Penduduk**

    - Mengajukan **KTP, KK, Akta Kelahiran, Akta Kematian**.
    - Melihat status pengajuan dokumen: **Diproses, Selesai, atau Ditolak**.
    - Mengunduh dokumen dalam format **PDF** setelah selesai diproses.

2. **Berita Pemerintahan**
    - Membaca berita terbaru dari pemerintah.
    - Berita dilengkapi dengan **judul, isi, gambar, penulis, dan tanggal rilis**.

---

### **Admin**

1. **Dashboard Admin**

    - Statistik jumlah penduduk, jumlah dokumen, dan berita terbaru.
    - **Log Aktivitas** admin untuk mencatat perubahan data.

2. **Manajemen Penduduk**

    - Melihat, menambah, mengedit, dan menghapus data penduduk.
    - Pencarian penduduk berdasarkan **Email, Nama**.

3. **Manajemen Dokumen**

    - Melihat daftar dokumen yang diajukan.
    - Memproses dokumen dengan pilihan **Setujui atau Tolak**.
    - Menginput **catatan atau alasan jika dokumen ditolak**.
    - Mencetak dokumen dalam format **PDF**.

4. **Manajemen Berita**
    - **CRUD berita** (Tambah, Edit, Hapus).
    - Upload **gambar berita** menggunakan file manager.
