# evently-showcase

# EVENTLY - Sistem Informasi Manajemen Tamu Undangan Digital

> **Catatan Portofolio:** Repositori ini merupakan *showcase* untuk proyek *Project Based Learning (PBL)* semester 4. Karena alasan privasi dan kepemilikan kode sumber secara kolektif, *source code* utama berada pada repositori privat. 

EVENTLY adalah platform manajemen tamu undangan berbasis web (MVC) yang menggantikan sistem buku tamu manual dengan teknologi pemindaian QR Code *real-time*, pelacakan suvenir, dan distribusi undangan otomatis via WhatsApp. 

---

## 🎯 Peran Saya (Mochamad Reza Firdaus)
Sebagai **UI/UX Designer & Frontend Focus Developer**, tanggung jawab utama saya meliputi:
*   **UI/UX Redesign:** Merancang *wireframe* dan *mockup high-fidelity* di Figma, serta melakukan *refactoring* total antarmuka *Landing Page* untuk meningkatkan interaktivitas.
*   **Pengembangan Frontend Scanner:** Menerjemahkan desain responsif untuk halaman panel Petugas Scanner di lapangan dan melakukan *consuming* API dari backend ke komponen visual.
*   **Theming Dashboard Superadmin:** Membangun *User Interface* dasbor Superadmin dengan mengimplementasikan pendekatan desain *Classic Theme* yang elegan dan ergonomis.
*   **Dokumentasi Proyek:** Menyusun manual penggunaan aplikasi (*User Guide*) dan dokumentasi aset visual sistem.

---

## 🚀 Fitur Utama Sistem EVENTLY
Sistem ini menggunakan struktur *Role-Based Access Control (RBAC)* dengan 4 aktor utama:

1.  **Super Admin:** Sistem *Approval* untuk menyetujui pengajuan acara, manajemen akun pengelola, dan pemantauan statistik global.
2.  **Admin (Pengelola Acara):** Membuat acara, mengimpor data tamu (Excel/CSV), mengelola *template* undangan, dan mengunduh laporan kehadiran.
3.  **Scanner (Petugas Lapangan):** Pemindaian QR code melalui kamera *browser* untuk *smart check-in* dan validasi distribusi suvenir (*anti-duplicate*).
4.  **Tamu:** Menerima undangan digital via WhatsApp, fitur RSVP (konfirmasi kehadiran), dan buku tamu digital (ucapan selamat).

---

## 🛠 Tech Stack yang Digunakan
*   **Backend:** PHP 8.2, Laravel 10 (MVC Framework)
*   **Frontend:** HTML5, JavaScript, Tailwind CSS
*   **Database:** PostgreSQL
*   **Gateway / Eksternal:** Venom Core API (Puppeteer/Node.js) untuk WhatsApp Gateway, Google Maps API
*   **Security:** Enkripsi *bcrypt*, *Transaction Database* dengan *Pessimistic Locking* (mencegah *race condition* pada QR scanner).

---

## 👥 Tim Pengembang (Cak Kin Squad / Kelompok 1 TI-2F)
1.  Achmad Daud Roichan (Backend Lead & Notification Engineer)
2.  **Mochamad Reza Firdaus (UI/UX Designer & Frontend Focus Developer)**
3.  Nur Alfiyanti (System Analyst & Full-Stack Core Developer)
4.  Rachmad Febriananda (Database Administrator & Check-In Engineer)
