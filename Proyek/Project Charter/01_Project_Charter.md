# Dokumen 01: Project Charter
**Nama Proyek:** Platform Booking dan Layanan UMKM Berbasis Web  
**Versi:** 1.0  
**Tanggal:** 23 Mei 2024  
**Project Manager:** Fadwa Adly Difarry (2403015054)

---

## 1. Pendahuluan
### 1.1 Latar Belakang
Banyak pelaku UMKM di bidang jasa (kafe, laundry, barbershop) masih mengandalkan sistem reservasi manual melalui chat atau buku fisik. Hal ini sering menyebabkan ketidakteraturan jadwal, antrean menumpuk, dan sulitnya pelanggan menemukan layanan terdekat secara cepat.

### 1.2 Tujuan Proyek
* Membangun platform sentral untuk reservasi layanan UMKM secara real-time.
* Meningkatkan efisiensi operasional mitra UMKM dalam mengelola jadwal.
* Memberikan kemudahan bagi customer dalam mencari dan memesan jasa melalui web.

---

## 2. Ruang Lingkup (Scope)
### 2.1 Fitur Utama
* **Customer:** Registrasi/Login, Filter Kategori UMKM, Form Booking Jasa, Riwayat Pesanan.
* **Mitra (Owner):** Dashboard Kelola Layanan, Kalender Penjadwalan, Konfirmasi Pesanan.
* **Admin:** Manajemen User, Verifikasi Mitra, Laporan Transaksi.

### 2.2 Batasan Proyek
* Aplikasi berbasis Web (Responsive).
* Fokus pada UMKM di sektor jasa.
* Belum mencakup sistem pengiriman logistik fisik.

---

## 3. Stakeholder Utama
| Peran | Nama / Entitas |
| :--- | :--- |
| **Project Sponsor** | Ir. Arry Avorizano, S.Kom., M.Kom. |
| **Project Manager** | Fadwa Adly Difarry |
| **Development Team** | Kelompok Praktikum RPL |
| **Target User** | Pemilik UMKM & Masyarakat Umum |

---

## 4. Rencana Jadwal (Milestones)
| Milestone | Target Waktu |
| :--- | :--- |
| Inisiasi Proyek & Charter | Minggu 1 |
| Analisis Kebutuhan (SRS) | Minggu 2 - 3 |
| Perancangan Sistem & UI/UX | Minggu 4 - 5 |
| Pengembangan (Coding) | Minggu 6 - 11 |
| Testing & Bug Fixing | Minggu 12 |
| Deployment & Dokumentasi | Minggu 13 |
| Presentasi Akhir | Minggu 14 |

---

## 5. Anggaran & Sumber Daya
* **Sumber Daya Manusia:** 1 Project Manager, UI/UX Designer, Backend/Frontend Developer.
* **Alat:** VS Code, Git, Figma, Draw.io, Hosting (Vercel/Netlify).

---

## 6. Risiko Utama
* Perubahan kebutuhan fitur di tengah pengembangan.
* Kurangnya data valid dari calon mitra UMKM.
* Kendala teknis pada integrasi sistem notifikasi.

---

graph TD
    A[Platform Booking UMKM] --> B[1. Manajemen Proyek]
    A --> C[2. Analisis & Desain]
    A --> D[3. Pengembangan/Coding]
    A --> E[4. Testing & Rilis]
    
    B --> B1[Project Charter]
    B --> B2[PMP & Penjadwalan]
    
    C --> C1[SRS Document]
    C --> C2[UI/UX Design]
    C --> C3[Database ERD]
    
    D --> D1[Modul Auth]
    D --> D2[Modul Booking]
    D --> D3[Dashboard Mitra]
    
    E --> E1[Blackbox Testing]
    E --> E2[Deployment ke Vercel]

---

**Disetujui Oleh:** *(Project Manager)*

**Fadwa Adly Difarry**
