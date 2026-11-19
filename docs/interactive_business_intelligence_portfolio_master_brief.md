# Interactive Business Intelligence Portfolio

## Project Master Brief untuk Dikembangkan dengan Beberapa AI

**Status:** Project blueprint / living document\
**Tujuan utama:** Membangun portfolio profesional berbentuk website yang
memiliki aplikasi interaktif di dalamnya. Recruiter tidak hanya membaca
deskripsi proyek atau melihat screenshot, tetapi dapat mencoba sistem,
menelusuri data sintetis, menggunakan filter, membuka dashboard, dan
memahami proses analisis dari awal hingga rekomendasi bisnis.

------------------------------------------------------------------------

# 1. Ringkasan Proyek

Saya ingin membangun sebuah **Hybrid Interactive Business Intelligence
Portfolio**: website portfolio profesional yang di dalamnya terdapat
beberapa simulasi sistem bisnis/operasional interaktif.

Portfolio ini harus terasa seperti produk software internal perusahaan
yang benar-benar dapat digunakan, bukan sekadar kumpulan screenshot
dashboard atau halaman proyek statis.

Pengalaman yang diharapkan untuk recruiter:

1.  Membuka landing page portfolio.
2.  Memahami profil, kompetensi, dan ringkasan proyek.
3.  Memilih salah satu sistem bisnis/operasional.
4.  Membaca tujuan sistem, masalah bisnis yang diselesaikan, fitur, dan
    arsitekturnya.
5.  Membuka data explorer untuk menelusuri tabel dan record sintetis.
6.  Mencoba pencarian, filter, sorting, dan detail record.
7.  Membuka dashboard Power BI dan/atau Tableau.
8.  Melihat SQL yang digunakan untuk menghasilkan metrik.
9.  Membaca insight, interpretasi, dan rekomendasi bisnis.

**Prinsip utama:** recruiter harus dapat menilai kemampuan saya melalui
pengalaman langsung. Portfolio perlu memperlihatkan kemampuan memahami
proses bisnis, merancang sistem, mengelola data, melakukan analisis,
membangun visualisasi, dan mengomunikasikan rekomendasi.

------------------------------------------------------------------------

# 2. Latar Belakang dan Arah Portfolio

Saya pernah membangun atau mengelola workflow dan sistem operasional
menggunakan Lark. Saya ingin mengembangkan ulang konsep sistem tersebut
menjadi proyek portfolio yang menunjukkan kompetensi teknis yang lebih
luas.

Pengalaman dan elemen pekerjaan yang relevan untuk dijadikan inspirasi
antara lain:

-   Workflow dan internal operational systems.
-   SOP dan dokumentasi proses.
-   KPI dan SLA monitoring.
-   Dashboard dan pelaporan.
-   Pengelolaan data customer.
-   Monitoring aktivitas, produktivitas, dan performa.

Angka, nama perusahaan, nama customer, data karyawan, dan informasi
internal tidak boleh dipublikasikan tanpa izin. Untuk portfolio publik,
gunakan **data sintetis (dummy data) yang realistis** atau data yang
sudah dianonimkan dan memang diizinkan untuk dibagikan.

Jangan mengklaim hasil simulasi sebagai hasil kerja atau dampak nyata
perusahaan. Bedakan dengan jelas antara: - pengalaman profesional yang
benar-benar pernah dilakukan; - fitur yang direkonstruksi sebagai
demonstrasi; - hasil analisis yang berasal dari dataset sintetis.

------------------------------------------------------------------------

# 3. Tujuan Karier dan Kompetensi yang Ingin Ditunjukkan

Portfolio diarahkan terutama untuk peran:

-   Business Analyst.
-   Data Analyst.
-   Business Intelligence Analyst.
-   Business Operations Analyst.
-   Product Operations / Project Analyst.

Kompetensi yang ingin ditunjukkan:

## Business understanding

-   Memahami proses dan kebutuhan bisnis.
-   Mengidentifikasi masalah operasional.
-   Menentukan KPI dan definisi metrik.
-   Mengubah kebutuhan stakeholder menjadi requirement.
-   Menarik kesimpulan dan menyusun rekomendasi.

## Data and technical skills

-   SQL: querying, filtering, joins, aggregation, CTE, subqueries,
    window functions.
-   Database design: relational modeling, ERD, primary key, foreign key,
    normalization.
-   Data preparation: cleaning, validation, transformation.
-   Python: data generation, processing, dan aplikasi data interaktif.
-   Power BI: Power Query, data modeling, DAX, interactive reports.
-   Tableau: calculated fields, filters, parameters, dashboards,
    storytelling.
-   Git/GitHub: version control dan dokumentasi.

## Communication

-   Menjelaskan masalah, metode, dan hasil analisis dengan bahasa
    bisnis.
-   Membuat dashboard yang mudah dipahami.
-   Menyampaikan insight dan rekomendasi yang dapat ditindaklanjuti.

------------------------------------------------------------------------

# 4. Konsep Produk dan Pengalaman Recruiter

## 4.1 Portfolio utama

Nama kerja: **Business Intelligence Hub**

Tagline contoh:

> Transforming operational data into actionable business insights.

Website harus memiliki identitas visual profesional, konsisten,
responsif, dan mudah dinavigasi. Hindari tampilan yang terlalu ramai
atau hanya berisi efek visual.

## 4.2 Struktur navigasi

Menu utama yang disarankan:

-   Home
-   About
-   Skills & Tools
-   Projects / Systems
-   Case Studies
-   Contact

Pada bagian Projects, recruiter dapat memilih beberapa sistem
demonstrasi.

## 4.3 Alur recruiter

``` text
Portfolio Landing Page
        |
        v
Project / System Selection
        |
        v
System Overview
        |
        +---- Business Problem & Objectives
        |
        +---- Features & Workflow
        |
        +---- Data Architecture / ERD
        |
        +---- Data Explorer
        |         |
        |         +---- Table Browser
        |         +---- Search / Filter / Sort
        |         +---- Record Detail
        |
        +---- SQL Analysis
        |
        +---- BI Dashboards
        |         |
        |         +---- Power BI
        |         +---- Tableau
        |
        +---- Business Insights
                  |
                  +---- Findings
                  +---- Recommendations
                  +---- Limitations
```

## 4.4 Standar interaksi

Recruiter idealnya dapat:

-   Berpindah antarhalaman dan antar-modul.
-   Melihat daftar tabel dan deskripsi kolom.
-   Melihat record sintetis dalam tabel.
-   Melakukan pencarian dan filter.
-   Mengurutkan data.
-   Membuka detail suatu record.
-   Mengubah filter dashboard.
-   Membandingkan periode, departemen, tim, atau kategori.
-   Membaca SQL query yang menghasilkan metrik.
-   Memahami bagaimana metrik dihitung.

Jangan membuat tombol atau kontrol yang hanya dekoratif. Setiap elemen
interaktif harus benar-benar berfungsi atau diberi label jelas bahwa
fitur tersebut merupakan mockup.

------------------------------------------------------------------------

# 5. Sistem yang Akan Dibangun

Mulai dengan satu sistem utama yang matang. Setelah alur teknis dan
desainnya stabil, kembangkan sistem tambahan.

Sistem berikut adalah kandidat proyek. Prioritas final dapat ditentukan
setelah meninjau workflow Lark yang memang pernah dibuat dan aman untuk
direkonstruksi.

## System 1 --- Performance Analytics

**Tujuan:** Memantau KPI, produktivitas, dan performa individu maupun
tim.

Modul: - Overview. - Employee / Team Data. - KPI Monitoring. -
Productivity Analysis. - Team Comparison. - Monthly Performance Report.

Contoh pertanyaan bisnis: - Bagaimana pencapaian KPI dibandingkan
target? - Tim mana yang memiliki performa tertinggi? - Bagaimana tren
produktivitas dari bulan ke bulan? - Apakah ada perbedaan performa
antarindividu atau tim? - Metrik mana yang perlu mendapat perhatian?

Contoh metrik: - KPI achievement rate. - Completed tasks. - Productivity
rate. - Average completion time. - Performance score. - Output per
employee/team.

## System 2 --- SLA & Operational Monitoring

**Tujuan:** Memantau ketepatan waktu dan efisiensi penyelesaian
pekerjaan.

Modul: - SLA Overview. - Task / Ticket Database. - On-time
vs. overdue. - Average resolution time. - SLA breach analysis. -
Bottleneck analysis.

Contoh pertanyaan bisnis: - Berapa persentase pekerjaan yang selesai
sesuai SLA? - Kategori pekerjaan apa yang paling sering terlambat? -
Pada tahap mana bottleneck terjadi? - Apakah workload berhubungan dengan
keterlambatan? - Bagaimana tren SLA setiap bulan?

Contoh metrik: - SLA compliance rate. - Overdue count. - Average
resolution time. - Backlog. - Open vs. closed tasks. - Breach rate by
category/team.

## System 3 --- Customer & Transaction Analytics

**Tujuan:** Menganalisis profil, aktivitas, dan tren customer/transaksi.

Modul: - Customer Overview. - Customer Database. - Transaction
Explorer. - Customer Segmentation. - Monthly Trends. - Customer Activity
Analysis.

Contoh pertanyaan bisnis: - Bagaimana distribusi customer berdasarkan
segmen? - Bagaimana tren transaksi dari waktu ke waktu? - Segmen mana
yang paling aktif? - Bagaimana pola aktivitas customer? - Apakah ada
perubahan perilaku antarperiode?

Contoh metrik: - Total customers. - Active customers. - Transaction
count. - Average transaction value. - Customer growth. - Segment
contribution.

## System 4 --- Workflow & Task Management (opsional)

**Tujuan:** Memperlihatkan alur pekerjaan dari dibuat, ditugaskan,
diproses, hingga selesai.

Modul: - Workflow Overview. - Task Database. - Status Monitoring. -
Assignment / Ownership. - Cycle Time. - Workload Distribution.

## System 5 --- Business Overview / Executive Dashboard (opsional)

**Tujuan:** Menggabungkan metrik utama dari sistem-sistem lain ke dalam
satu tampilan manajemen.

Modul: - Executive Overview. - Operational Performance. - KPI Summary. -
SLA Summary. - Customer Trends. - Key Findings.

Jangan membangun semua sistem sekaligus. Selesaikan satu sistem
end-to-end sebagai template kualitas, lalu gunakan pola yang sama untuk
sistem lain.

------------------------------------------------------------------------

# 6. Arsitektur Teknologi

Arsitektur awal yang direkomendasikan:

``` text
Synthetic Data Generation
          |
          v
PostgreSQL Database
          |
          v
SQL Queries / Views
          |
          v
Analytics & Application Layer
       /             \
      v               v
Interactive App    BI Tools
(Streamlit)        /       \
                  v         v
               Power BI   Tableau
                  \         /
                   \       /
                    v     v
                Portfolio Website
```

## Komponen

  Teknologi           Peran
  ------------------- -------------------------------------------
  PostgreSQL          Database relasional utama
  SQL                 Query, transformasi, dan analisis
  Python              Data generation, processing, dan aplikasi
  Streamlit           Data explorer dan interactive demo
  Power BI            Dashboard dan business intelligence
  Tableau             Dashboard dan data storytelling
  GitHub              Source code, version history, dokumentasi
  Portfolio website   Landing page dan navigasi seluruh proyek

Teknologi final dapat disesuaikan dengan kebutuhan, biaya, kemampuan
deployment, dan akses yang tersedia.

## Catatan integrasi

-   Gunakan satu sumber data yang konsisten untuk Power BI dan Tableau.
-   Utamakan koneksi database atau file data hasil ekspor yang
    terkontrol.
-   Jangan menaruh password database, API key, atau credential di
    repository publik.
-   Gunakan environment variables dan file konfigurasi lokal yang tidak
    di-commit.
-   Untuk demo publik, gunakan database read-only atau dataset statis
    yang aman.
-   Dashboard publik hanya boleh menampilkan data sintetis atau data
    yang memang boleh dipublikasikan.
-   Periksa ketentuan lisensi dan embedding Power BI/Tableau sebelum
    memilih metode publikasi.

------------------------------------------------------------------------

# 7. Database Design dan Data Explorer

Setiap sistem harus mempunyai database yang terstruktur, bukan hanya
tabel acak untuk mengisi dashboard.

## Contoh rancangan awal: Performance Analytics

Tabel kandidat:

### employees

-   employee_id (PK)
-   employee_name (synthetic)
-   department_id (FK)
-   team_id (FK)
-   job_role
-   employment_status

### departments

-   department_id (PK)
-   department_name

### teams

-   team_id (PK)
-   team_name
-   department_id (FK)

### kpi_definitions

-   kpi_id (PK)
-   kpi_name
-   description
-   unit
-   calculation_method

### employee_kpi_targets

-   target_id (PK)
-   employee_id (FK)
-   kpi_id (FK)
-   period
-   target_value

### employee_kpi_results

-   result_id (PK)
-   employee_id (FK)
-   kpi_id (FK)
-   period
-   actual_value

### tasks

-   task_id (PK)
-   employee_id (FK)
-   created_at
-   due_date
-   completed_at
-   task_status
-   task_category
-   priority

### performance_reviews (opsional)

-   review_id (PK)
-   employee_id (FK)
-   review_period
-   score
-   review_category

Rancangan ini hanya titik awal. Periksa normalisasi, relasi, definisi
metrik, dan kebutuhan analisis sebelum implementasi.

## Data dictionary

Setiap tabel harus mempunyai dokumentasi: - Nama tabel. - Tujuan
tabel. - Nama kolom. - Tipe data. - Primary/foreign key. - Definisi
kolom. - Contoh nilai sintetis. - Aturan validasi.

## Data Explorer

Tampilan Data Explorer minimal menyediakan: - Daftar tabel. - Jumlah
record. - Deskripsi tabel. - Kolom dan tipe data. - Pencarian record. -
Filter kolom. - Sorting. - Pagination. - Detail record. - Keterangan
bahwa seluruh data adalah sintetis.

Untuk keamanan dan performa, jangan izinkan recruiter menjalankan SQL
bebas pada database produksi. Sediakan query yang sudah dibatasi atau
tampilan read-only.

------------------------------------------------------------------------

# 8. Standar SQL yang Harus Ditunjukkan

Jangan hanya menampilkan daftar query tanpa konteks. Setiap query perlu
menjelaskan pertanyaan bisnis yang dijawab.

Materi dan demonstrasi SQL: 1. SELECT dan DISTINCT. 2. WHERE dan
filtering. 3. ORDER BY dan LIMIT. 4. GROUP BY dan aggregate functions.
5. JOIN antar tabel. 6. CASE WHEN. 7. Subqueries. 8. Common Table
Expressions (CTE). 9. Window Functions. 10. Date/time analysis. 11.
Views. 12. Data validation dan duplicate checks.

Contoh analisis: - KPI achievement per employee. - Monthly productivity
trend. - SLA compliance per team. - Average resolution time by
category. - Ranking employee/team. - Month-over-month change.

Untuk setiap query, dokumentasikan: - Business question. - Query. -
Penjelasan logika. - Output yang diharapkan. - Interpretasi bisnis.

------------------------------------------------------------------------

# 9. Standar Dashboard Power BI dan Tableau

Kedua platform menggunakan dataset dan definisi metrik yang sama agar
hasilnya konsisten.

## Dashboard Power BI

Hal yang ingin diperlihatkan: - Data import / connection. - Power Query
transformation. - Data model dan relationships. - DAX measures. - KPI
cards. - Trend charts. - Breakdown by department/team. - Slicers dan
drill-through. - Tooltip dan interaksi antvisual.

## Dashboard Tableau

Hal yang ingin diperlihatkan: - Dimensions dan Measures. - Calculated
Fields. - Filters dan Parameters. - Trend analysis. - Comparison
views. - Interactive dashboard. - Dashboard actions. - Storytelling dan
explanatory captions.

## Prinsip desain dashboard

-   Utamakan pertanyaan bisnis, bukan dekorasi.
-   Gunakan judul yang menjelaskan informasi.
-   Definisikan semua KPI dengan jelas.
-   Tampilkan periode dan satuan.
-   Hindari visual yang menyesatkan.
-   Pastikan filter bekerja konsisten.
-   Berikan konteks target atau benchmark jika tersedia.
-   Jangan membuat insight yang tidak didukung data.

------------------------------------------------------------------------

# 10. Business Insights dan Case Study

Setiap sistem harus mempunyai halaman case study dengan struktur:

1.  **Business Context** --- konteks proses bisnis.
2.  **Problem Statement** --- masalah yang ingin diselesaikan.
3.  **Objectives** --- tujuan analisis.
4.  **Data Sources** --- sumber dan karakteristik dataset sintetis.
5.  **Data Model** --- ERD dan relasi.
6.  **Methodology** --- proses cleaning, SQL, dan perhitungan.
7.  **Dashboard** --- visualisasi yang dibuat.
8.  **Key Findings** --- temuan yang benar-benar terlihat dari data.
9.  **Recommendations** --- rekomendasi yang relevan.
10. **Limitations** --- keterbatasan data dan analisis.
11. **What I Learned** --- pembelajaran teknis dan bisnis.

Pisahkan fakta, interpretasi, dan rekomendasi. Jangan mengarang insight
sebelum dataset dianalisis.

------------------------------------------------------------------------

# 11. Desain UI/UX

Arah desain: - Profesional, modern, bersih, dan terasa seperti
enterprise software. - Navigasi jelas. - Konsisten antarhalaman. -
Responsif untuk desktop dan mobile. - Informasi penting mudah
ditemukan. - Tidak terlalu banyak animasi. - Tabel nyaman dibaca. -
Dashboard memiliki hierarki visual yang jelas.

Komponen UI yang dibutuhkan: - Sidebar atau top navigation. -
Project/system cards. - KPI cards. - Interactive charts. - Data
tables. - Search and filter controls. - Tabs. - Detail panels. - SQL
code blocks. - ERD / architecture diagrams. - Case study sections. -
Empty, loading, dan error states.

Buat satu design system sederhana: - Typography. - Color palette. -
Spacing. - Button styles. - Card styles. - Table styles. - Chart
conventions. - Status indicators.

------------------------------------------------------------------------

# 12. Roadmap Pengerjaan dan Pembelajaran

Target awal: sekitar 8 minggu. Jadwal dapat berubah sesuai waktu belajar
dan kompleksitas implementasi.

## Minggu 1 --- Discovery dan perancangan

-   Inventarisasi sistem/workflow Lark yang relevan.
-   Pilih satu sistem utama.
-   Tentukan persona recruiter dan business user.
-   Tulis problem statement dan requirement.
-   Buat user journey.
-   Buat ERD awal.
-   Tentukan metrik dan definisinya.

**Output:** project brief, requirements, user flow, ERD, data dictionary
awal.

## Minggu 2--3 --- Database dan SQL

-   Pelajari PostgreSQL.
-   Buat schema dan tabel.
-   Buat synthetic dataset.
-   Validasi kualitas data.
-   Latihan SQL dari dasar hingga intermediate.
-   Buat query untuk business questions.
-   Buat views untuk metrik penting.

**Output:** database, dataset, SQL scripts, dokumentasi query.

## Minggu 4 --- Data Explorer

-   Bangun aplikasi Streamlit.
-   Tampilkan daftar tabel.
-   Buat search, filter, sorting, pagination.
-   Buat record detail.
-   Hubungkan ke sumber data read-only.
-   Uji pengalaman recruiter.

**Output:** interactive data explorer.

## Minggu 5 --- Power BI

-   Hubungkan data.
-   Buat model.
-   Transform data dengan Power Query.
-   Buat DAX measures.
-   Bangun dashboard.
-   Uji konsistensi hasil dengan SQL.

**Output:** Power BI report.

## Minggu 6 --- Tableau

-   Hubungkan dataset yang sama.
-   Buat calculated fields.
-   Bangun worksheet dan dashboard.
-   Tambahkan filter dan dashboard actions.
-   Uji konsistensi metrik.

**Output:** Tableau dashboard.

## Minggu 7 --- Portfolio website

-   Bangun landing page.
-   Buat project/system selection.
-   Buat system overview.
-   Integrasikan data explorer.
-   Integrasikan atau tautkan dashboard.
-   Tambahkan SQL, ERD, dan case study.

**Output:** website portfolio terintegrasi.

## Minggu 8 --- QA dan publikasi

-   Uji seluruh interaksi.
-   Periksa responsivitas.
-   Validasi angka dan definisi metrik.
-   Periksa keamanan data dan credential.
-   Tulis README.
-   Siapkan demo dan screenshot.
-   Publikasikan versi yang aman.

**Output:** portfolio publik yang dapat dieksplorasi recruiter.

------------------------------------------------------------------------

# 13. Definition of Done --- Kriteria Proyek Selesai

Satu sistem dianggap selesai jika:

-   [ ] Problem statement dan tujuan bisnis terdokumentasi.
-   [ ] User flow dan fitur dijelaskan.
-   [ ] ERD tersedia.
-   [ ] Database relasional berfungsi.
-   [ ] Dataset sintetis realistis tersedia.
-   [ ] Data dictionary tersedia.
-   [ ] SQL queries menjawab business questions.
-   [ ] Data Explorer bisa digunakan.
-   [ ] Search, filter, sorting, dan pagination berfungsi.
-   [ ] Dashboard Power BI tersedia.
-   [ ] Dashboard Tableau tersedia.
-   [ ] Definisi KPI konsisten di seluruh platform.
-   [ ] Insight dan rekomendasi berdasarkan hasil analisis.
-   [ ] Limitasi analisis dijelaskan.
-   [ ] Seluruh navigasi dan tombol diuji.
-   [ ] Tidak ada credential atau data rahasia di repository.
-   [ ] README dan dokumentasi instalasi tersedia.
-   [ ] Recruiter dapat memahami proyek tanpa bantuan langsung.

------------------------------------------------------------------------

# 14. Struktur Repository yang Disarankan

Contoh struktur untuk satu sistem:

``` text
performance-analytics/
│
├── README.md
├── requirements.txt
├── .env.example
├── .gitignore
│
├── docs/
│   ├── project-brief.md
│   ├── business-requirements.md
│   ├── user-flow.md
│   ├── data-dictionary.md
│   ├── methodology.md
│   └── findings-and-recommendations.md
│
├── database/
│   ├── schema.sql
│   ├── seed_data.sql
│   ├── views.sql
│   └── erd.png
│
├── data/
│   ├── README.md
│   └── synthetic/
│
├── sql/
│   ├── 01_basic_queries.sql
│   ├── 02_joins.sql
│   ├── 03_aggregations.sql
│   ├── 04_cte_subqueries.sql
│   └── 05_window_functions.sql
│
├── app/
│   ├── Home.py
│   ├── pages/
│   └── components/
│
├── powerbi/
│   └── documentation.md
│
├── tableau/
│   └── documentation.md
│
└── assets/
    ├── screenshots/
    └── diagrams/
```

Struktur dapat disesuaikan setelah memilih framework dan metode
deployment.

------------------------------------------------------------------------

# 15. Strategi Pengembangan dengan Beberapa AI

Dokumen ini akan menjadi **single source of truth** untuk semua AI yang
membantu proyek. Berikan dokumen ini sebagai konteks awal kepada setiap
AI. Jangan meminta masing-masing AI membuat arsitektur sendiri tanpa
mengikuti keputusan yang sudah disepakati.

## Pembagian peran AI

### AI 1 --- Product Manager / Business Analyst

Tugas: - Memahami tujuan portfolio dan recruiter journey. - Menyusun
requirement. - Membuat user stories dan acceptance criteria. -
Menentukan prioritas fitur. - Menjaga scope agar tidak melebar.

### AI 2 --- Database Architect / SQL Mentor

Tugas: - Merancang ERD. - Menentukan schema dan relasi. - Membuat data
dictionary. - Membuat synthetic dataset. - Mengajar SQL secara
bertahap. - Menulis dan menjelaskan query.

### AI 3 --- Data Analyst / BI Specialist

Tugas: - Menentukan KPI dan business questions. - Memvalidasi definisi
metrik. - Menyusun analisis. - Merancang dashboard Power BI dan
Tableau. - Menarik insight dan rekomendasi berbasis data.

### AI 4 --- Python / Streamlit Developer

Tugas: - Membuat aplikasi Data Explorer. - Menghubungkan database. -
Membangun search, filter, sorting, pagination, dan detail record. -
Menjaga keamanan akses. - Menulis kode yang modular dan terdokumentasi.

### AI 5 --- UI/UX Designer / Frontend Developer

Tugas: - Merancang landing page. - Membuat system selection. - Merancang
design system. - Membangun navigasi dan tampilan responsif. - Memastikan
pengalaman recruiter intuitif.

### AI 6 --- QA / Technical Reviewer

Tugas: - Menguji fungsi. - Memeriksa konsistensi metrik. - Memeriksa
keamanan. - Mencari bug. - Menguji tampilan desktop dan mobile. -
Memeriksa apakah dokumentasi sesuai implementasi.

Satu AI dapat menjalankan lebih dari satu peran. Pembagian ini adalah
pembagian tanggung jawab, bukan keharusan memakai enam layanan berbeda.

------------------------------------------------------------------------

# 16. Master Prompt untuk Memulai di AI Lain

Salin prompt berikut bersama dokumen ini:

> Saya sedang membangun sebuah Hybrid Interactive Business Intelligence
> Portfolio. Baca seluruh dokumen project brief yang saya lampirkan dan
> jadikan dokumen tersebut sebagai sumber konteks utama.
>
> Tujuan proyek ini adalah membuat website portfolio profesional yang
> memungkinkan recruiter mengeksplorasi simulasi sistem
> bisnis/operasional secara langsung. Recruiter harus bisa membuka
> modul, menelusuri dataset sintetis, menggunakan search dan filter,
> melihat detail record, membaca SQL analysis, mengeksplorasi dashboard
> Power BI dan Tableau, serta memahami business insights dan
> recommendations.
>
> Saya ingin belajar sambil membangun. Jangan hanya memberikan hasil
> akhir atau kode tanpa penjelasan. Ajarkan konsep yang sedang
> digunakan, jelaskan alasan keputusan teknis, dan pecah pekerjaan
> menjadi tahapan kecil yang bisa diuji.
>
> Gunakan prinsip berikut: 1. Ikuti tujuan, arsitektur, dan batasan di
> project brief. 2. Jangan mengarang pengalaman kerja, hasil bisnis,
> atau insight. 3. Gunakan data sintetis dan beri label yang jelas. 4.
> Jaga konsistensi database, definisi KPI, SQL, Power BI, Tableau, dan
> aplikasi. 5. Jangan membuat fitur atau tombol yang tidak berfungsi. 6.
> Jangan mengekspos credential, data pribadi, atau informasi internal.
> 7. Sebelum menulis kode dalam jumlah besar, jelaskan rencana dan
> struktur file. 8. Berikan instruksi setup, cara menjalankan, dan cara
> menguji. 9. Dokumentasikan keputusan teknis dan perubahan agar AI lain
> dapat melanjutkan pekerjaan. 10. Jika ada informasi yang belum
> ditentukan, ajukan pertanyaan paling penting atau berikan opsi beserta
> konsekuensinya. Jangan membuat asumsi besar secara diam-diam.
>
> Mulai dengan mengidentifikasi keputusan yang belum final, lalu bantu
> saya menyelesaikan fase discovery dan memilih satu sistem pertama
> untuk dibangun end-to-end. Jangan langsung membangun seluruh portfolio
> sekaligus.

------------------------------------------------------------------------

# 17. Aturan Kolaborasi Antar-AI dan Pengelolaan Perubahan

Agar beberapa AI tidak menghasilkan sistem yang saling bertentangan:

1.  Simpan dokumen ini di root repository sebagai
    `PROJECT_MASTER_BRIEF.md`.
2.  Simpan keputusan teknis yang sudah final di `docs/DECISION_LOG.md`.
3.  Simpan daftar pekerjaan di `docs/ROADMAP.md`.
4.  Simpan definisi KPI resmi di `docs/METRIC_DICTIONARY.md`.
5.  Simpan schema database dan data dictionary dalam dokumentasi yang
    sama-sama dirujuk.
6.  Setiap AI harus menyebutkan file yang dibuat atau diubah.
7.  Setiap perubahan schema harus disertai pembaruan ERD, data
    dictionary, dan query terkait.
8.  Setiap perubahan definisi metrik harus diperbarui di SQL, Power BI,
    Tableau, dan dokumentasi.
9.  Jangan menimpa pekerjaan AI lain tanpa memeriksa perubahan yang
    sudah ada.
10. Setelah setiap fase, lakukan review dan uji sebelum melanjutkan.

## Template handoff antar-AI

Gunakan format ini saat memindahkan pekerjaan ke AI lain:

``` text
PROJECT:
[System / module name]

CURRENT PHASE:
[Current development phase]

COMPLETED:
- [What has been completed]

FILES CREATED / MODIFIED:
- [File path and purpose]

TECHNICAL DECISIONS:
- [Decisions already agreed]

DATA / SCHEMA STATUS:
- [Current database and data status]

KNOWN ISSUES:
- [Bugs, limitations, or unresolved questions]

NEXT TASK:
- [One clearly defined next task]

ACCEPTANCE CRITERIA:
- [How to verify the task is complete]
```

------------------------------------------------------------------------

# 18. Keputusan yang Masih Perlu Ditentukan

Jangan menganggap semua pilihan berikut sudah final. Tentukan secara
bertahap:

-   Sistem Lark mana yang akan direkonstruksi pertama.
-   Nama dan branding portfolio.
-   Framework website utama.
-   Apakah Streamlit berdiri sendiri atau menjadi bagian dari navigasi
    website utama.
-   Metode deployment.
-   Metode embedding atau publikasi Power BI dan Tableau.
-   Jumlah dan karakteristik synthetic dataset.
-   Jumlah sistem yang akan ditampilkan pada versi pertama.

**Rekomendasi scope awal:** satu sistem Performance Analytics atau SLA
Monitoring yang lengkap, satu database, satu Data Explorer, satu
dashboard Power BI, satu dashboard Tableau, dan satu case study. Setelah
kualitasnya matang, replikasi arsitektur untuk sistem berikutnya.

------------------------------------------------------------------------

# 19. Prinsip Akhir

Portfolio ini bukan proyek untuk sekadar menunjukkan bahwa saya bisa
menggunakan SQL, Power BI, atau Tableau.

Portfolio ini harus menunjukkan bahwa saya mampu:

1.  Memahami masalah bisnis.
2.  Menerjemahkan kebutuhan menjadi rancangan sistem.
3.  Merancang database yang terstruktur.
4.  Mengolah dan menganalisis data dengan SQL.
5.  Membuat aplikasi untuk mengeksplorasi data.
6.  Membangun dashboard interaktif.
7.  Menginterpretasikan hasil analisis.
8.  Menyampaikan rekomendasi yang masuk akal.
9.  Mendokumentasikan seluruh proses secara profesional.

**Ukuran keberhasilan paling penting:** setelah mengeksplorasi
portfolio, recruiter dapat memahami bukan hanya tools yang saya kuasai,
tetapi juga bagaimana saya berpikir, bagaimana saya bekerja, dan
bagaimana saya mengubah data menjadi informasi yang berguna untuk
bisnis.
