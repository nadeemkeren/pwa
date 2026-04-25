Alur Pengembangan (SDLC)
Proyek ini mengikuti siklus pengembangan yang tertera di sisi kiri:

Analisis: Memetakan alur keluar-masuk barang dan kategorisasi stok (SKU).

Desain: Perancangan skema basis data dan dasbor pemantauan stok secara real-time.

Implementasi: Pengodean menggunakan Node.js untuk sisi server dan CSS-in-JS untuk estetika antarmuka.

Pengujian: Memastikan validasi input stok dan akurasi laporan otomatis tidak mengalami malfungsi.

Struktur Tim (Peran)
Pengembangan sistem ini melibatkan pembagian tugas di sisi kanan papan:

Pemilik/Klien: Manajer Logistik atau pemilik perusahaan dagang.

PM (Project Manager): Mengawasi deadline integrasi modul stok dengan modul keuangan.

Analis/Arsitek: Menyusun logika algoritma First-In-First-Out (FIFO) dalam sistem.

Designer: Menyusun tata letak dasbor agar informasi barang kritis (stok menipis) terlihat jelas.

Dev (Developer): Membangun konektivitas API agar data dari gudang tersinkronisasi ke pusat data.

Metodologi Kerja
Sistem dikelola dengan prinsip ketangkasan yang berfokus pada:

Kanban: Menggunakan papan visual untuk melacak pergerakan tugas dari "Tersedia" hingga "Selesai".

Tujuan: Mewujudkan sistem yang Scalable (siap dikembangkan untuk cabang baru) dan memiliki High Availability (minim waktu henti).

Pengelolaan Kode
Instruksi teknis di bagian atas papan menekankan pada kolaborasi:

GitHub: Seluruh basis kode tersimpan di repositori github.com/tim-k1/IMS-Smart.

Branching: Setiap anggota tim diinstruksikan membuat branch (cabang) baru untuk setiap fitur agar kode utama tetap stabil saat proses penggabungan (merge).
