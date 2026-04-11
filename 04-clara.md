**Ringkasan Ekosistem Pengembangan Sistem**
**Materi ini merangkum strategi pembangunan sistem LMS (Learning Management System) yang mengintegrasikan aspek teknis (PHP, HTML, JS, API) dengan tata kelola proyek yang terukur. Inti dari catatan ini adalah sinkronisasi antara pemilihan metodologi SDLC, penerapan strategi pengujian, serta penggunaan metrik estimasi biaya dan waktu untuk memastikan keberhasilan proyek.**

**Pilar 1: Arsitektur & Teknologi (The Build)**
Fokus pada komponen fisik dan cara sistem berkomunikasi.

**Komponen Inti (LMS Modules): Berfokus pada pengembangan tiga fitur utama: materi pembelajaran, sistem Quiz, dan generator Sertifikat.**

**Teknologi Utama**: Menggunakan kombinasi PHP (Back-end), HTML (Struktur), dan JavaScript (Interaktivitas).

**Mekanisme Konektivitas**: Integrasi data antar modul atau sistem eksternal menggunakan API dengan standar format data JSON atau XML agar komunikasi berjalan ringan.

**Pilar 2: Metodologi & Siklus Hidup (The Process)**
Fokus pada kerangka kerja dan alur pengerjaan dari awal hingga akhir.

**Model SDLC (Pemilihan Strategi)**:

**Waterfall**: Model linier/sekuensial untuk proyek dengan kebutuhan yang sudah pasti.

**Spiral**: Model berbasis iterasi yang memprioritaskan Analisis Risiko.

**Agile (Scrum & XP)**: Model adaptif yang menggunakan siklus pendek (Sprint) dan disiplin koding tinggi (Extreme Programming).

**Tahapan Pengembangan (SDLC Cycle)**:

**Planning & Analysis**: Perencanaan dan pendefinisian kebutuhan.

**Design**: Perancangan arsitektur dan logika.

**Implementation**: Proses pengkodean (coding) oleh tim Developer.

**Testing**: Verifikasi kualitas dan pencarian bug.

**Deployment & Maintenance**: Perilisan aplikasi dan pemeliharaan rutin.


**Pilar 3: Penjaminan Kualitas (The Validation)**
Fokus pada teknik pengujian untuk memastikan sistem berjalan tanpa cela.

**-Black Box Testing**: Menguji fungsionalitas fitur (input/output) tanpa melihat kode internal.

**-White Box Testing**: Menguji jalur logika, efisiensi algoritma, dan struktur internal kode.

**-Unit Testing**: Pengujian pada komponen terkecil (fungsi/modul) secara mandiri.


**Pilar 4: Metrik & Tata Kelola (The Measurement)**
Fokus pada perhitungan matematis dan manajemen sumber daya.

**Metrik Estimasi (Project Metrics)**:

**SLOC (Source Lines of Code)**: Mengukur beban kerja berdasarkan volume baris kode.

**Function Point (FP)**: Mengukur kompleksitas berdasarkan jumlah fungsi yang tersedia bagi pengguna.

**COCOMO (Constructive Cost Model)**: Algoritma untuk menghitung biaya, waktu, dan jumlah tenaga kerja (Man-months) dalam 3 tingkatan (Basic, Intermediate, Detail).

**Manajemen Operasional:**

**Peran (Roles)**: Melibatkan PM (Project Manager) sebagai pengendali dan Dev (Developer) sebagai pelaksana teknis.

**Monitoring & Control**: Pengendalian variabel Time (waktu) dan sumber daya untuk mencegah pembengkakan anggaran (cost overrun).
