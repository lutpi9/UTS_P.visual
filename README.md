👩‍💻 Pengembang

| Keterangan | Detail |
|-------------|---------|
| **Nama** | Lutpiah Ainus Shiddik |
| **NIM** | 312310474 |
| **Kelas** | TI.23.A.5 |
| **Mata Kuliah** | Pemrograman Visual (Desktop) |
| **Proyek** | Ujian Tengah Semester (UTS) |

# 🧁 Lupybakery Management System

## 📘 Deskripsi Proyek
**Lupybakery Management System** adalah aplikasi web yang dikembangkan sebagai proyek **Ujian Tengah Semester (UTS)**.  
Website ini dirancang untuk membantu manajemen toko kue **Lupybakery** dalam mengelola data internal seperti pengguna, peran (roles), menu aplikasi, dan utilitas sistem.

Aplikasi ini dibangun menggunakan **Internet Information Services (IIS)** sebagai web server utama,  
**SQL Server** sebagai sistem penyimpanan data relasional, dan **MongoDB** sebagai sistem penyimpanan non-relasional untuk data log dan dokumentasi sistem.

---

## 🎯 Tujuan Proyek
- Membangun sistem manajemen berbasis web dengan tampilan profesional.  
- Mengimplementasikan integrasi antara **SQL Server** dan **MongoDB** dalam satu aplikasi.  
- Menunjukkan pemahaman dalam pengelolaan **user**, **role**, dan **menu dinamis**.  
- Menyediakan **dashboard interaktif** untuk pengelolaan data toko kue.

---

## ⚙️ Teknologi yang Digunakan

| Komponen | Teknologi |
|-----------|------------|
| **Server** | Internet Information Services (IIS) |
| **Database Relasional** | Microsoft SQL Server |
| **Database Non-Relasional** | MongoDB |
| **Bahasa Pemrograman** | ASP.NET / PHP  |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Desain Mockup** | Balsamiq / Figma |
| **Version Control** | GitHub |

---

## 🧩 Fitur Utama

### 🔐 Login & Authentication
- Form login dengan validasi username dan password.  
- Opsi **"Stay Signed In"** untuk menjaga sesi pengguna.  
- Dukungan login dengan akun pihak ketiga (*mockup: “Sign in using”*).

### 📊 Dashboard
- Menampilkan ringkasan sistem dan aktivitas terkini.  
- Informasi pengguna aktif (contoh: “Lutpiah Ainus”).  
- Navigasi cepat menuju fitur utama.

### 👥 User Management
- Mengelola daftar pengguna sistem (Admin, Staf, Developer, dsb).  
- CRUD data user: tambah, ubah, dan hapus pengguna.  
- Menampilkan informasi seperti **User ID**, **Role**, **Status**, dan **Last Login**.

### 🧱 Role Management
- Mengatur peran dan hak akses pengguna.  
- Tabel daftar role seperti `ADMIN`, `IT DEV`, `ADMINISTRATOR`.  
- Dilengkapi dengan fitur **Create, Read, Update, Delete (CRUD)**.

### 🗂️ Menu Management
- Mengatur struktur menu dan navigasi sistem.  
- Fitur **Menu Editor** dengan kolom:
  - `Menu Id`, `Name`, `Parent`, `Level`, `Sequence`, `Link`, `Icon`, dan `Status`.  
- Menggunakan ikon dari **Font Awesome** (`fa fa-lg fa-fw`).

### 🧰 Utility Tools
- Fitur tambahan seperti:
  - `Upload Reports`  
  - `Cek Running Server`  
  - `Database Utility`  

### 📄 Document Management
- Fitur pencarian dan manajemen dokumen internal.  
- Kolom pencarian “Find Documents” untuk memudahkan akses data.

---

## 🗄️ Struktur Database

Aplikasi ini menggunakan dua sistem database:

### 🧱 SQL Server
Digunakan untuk menyimpan data utama sistem:
- **Users**
- **Roles**
- **Menus**
- **AccessControl**

### 🍃 MongoDB
Digunakan untuk menyimpan data tidak terstruktur:
- **logs** → mencatat aktivitas pengguna.  
- **uploads** → menyimpan metadata file laporan.

---

## 🧠 Arsitektur Sistem

Aplikasi ini mengusung arsitektur **Hybrid Database System** dengan IIS sebagai host utama:

<img width="1536" height="1024" alt="arsitektur" src="https://github.com/user-attachments/assets/2a27ef71-1e8c-43f6-9626-60de2ded1f01" />



---

## 🪄 Mockup Tampilan

Beberapa halaman utama dari mockup proyek ini:

| Halaman | Deskripsi |
|----------|------------|
| **Login Page** | Halaman masuk dengan opsi “Stay Signed In”. |
| **Dashboard** | Tampilan utama setelah login. |
| **Role Management** | Pengaturan role dan hak akses pengguna. |
| **User Management** | Pengelolaan data pengguna. |
| **Menu Management** | Pengaturan struktur menu dan ikon sistem. |

> “Every cake from Lupybakery is not just a sweet treat — but a manifestation of love, sincerity, and happiness.”

---
## Sign in
<img width="1364" height="810" alt="image" src="https://github.com/user-attachments/assets/40ffe09d-9736-44b2-b2e8-47fc0121e57d" />

## Dashboard
<img width="1366" height="753" alt="image" src="https://github.com/user-attachments/assets/be62dd7e-f5ca-4506-bb82-f78b993a9b74" />

## Role Manager
<img width="1367" height="803" alt="image" src="https://github.com/user-attachments/assets/1d25e8da-ce45-425d-ad6d-27f21feff8dd" />

## User Management
<img width="1367" height="730" alt="image" src="https://github.com/user-attachments/assets/92e802a8-dea3-4ec1-960c-4073fc511b5b" />

## Menu Management
<img width="1369" height="656" alt="image" src="https://github.com/user-attachments/assets/97d56960-a6fa-4eb5-aa77-c172cbc8796e" />

## Menu Management (Create)
<img width="1370" height="657" alt="image" src="https://github.com/user-attachments/assets/8a94dc29-8c0b-4b4e-a0f8-97a6c6511bf9" />

## 🚀 Cara Menjalankan Aplikasi

1. Pastikan **IIS (Internet Information Services)** sudah aktif di komputer kamu.  
2. Tempatkan folder proyek ke dalam direktori `C:\inetpub\wwwroot\LupybakerySystem`.  
3. Buka IIS Manager → Tambahkan website baru dan arahkan ke folder proyek.  
4. Konfigurasikan **connection string** untuk SQL Server dan MongoDB.  
5. Import database awal ke SQL Server.  
6. Jalankan aplikasi melalui browser: http://localhost:8090/app#/ 

