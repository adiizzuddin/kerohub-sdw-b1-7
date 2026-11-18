Markdown# # KeroHub: Local Crackers Factory Inventory & Bulk Order Management System

Sistem pengurusan inventori dan tempahan pukal berasaskan web untuk *Kilang Keropok QFIS* (Melaka), dibangunkan bagi subjek *DITU3934 System Development Workshop & Web Programming* (Semester 2 DFDS 2026).

## Maklumat Projek
* *Kod & Nama Subjek:* DITU3934 System Development Workshop & Web Programming
* *Kumpulan:* B1-7
* *Pensyarah / Penyelia:* Ts. Hjh Azlianor Abdul Aziz
* *Klien:* Kilang Keropok QFIS, Melaka
* *Tech Stack:* PHP, MySQL, HTML5, CSS3, JavaScript (XAMPP / LAMP Stack)

## Ahli Kumpulan (B1-7)
| Nama Penuh | No. Matrik | Peranan |
| :--- | :--- | :--- |
| Adi Izzuddin Bin Ahmad Ridhwan | D032510407 | Project Manager |
| Muhammad Arif Johan Bin Azman | D032510392 | Lead Systems Analyst & UI/UX Designer |
| Raees Annas Bin Raszaizul | D032510551 | Lead Full-Stack / Database Engineer |
| Airiel Danish Hakimi Bin Azrynoor Ali | D032510454 | QA & DevOps Engineer |
| Adam Haikal Bin Amirudin | D032510007 | QA & DevOps Engineer |

## Modul Utama Sistem
1. *M01 - Inventory Management Module:* Pengurusan stok bahan mentah & keropok siap dengan amaran stok rendah (low-stock alerts).
2. *M02 - Agent Order & Checkout Module:* Tempahan pukal oleh ejen dengan kiraan diskaun kuantiti (price tiers), zon penghantaran, dan kunci harga (snapshot price).
3. *M03 - Secure Access & Role Control Module:* Kawalan akses berasaskan peranan (Factory Admin vs. Wholesale Agent) serta pengesahan pendaftaran ejen.
4. *M04 - Admin Reporting Dashboard:* Paparan ringkasan jualan langsung dan status inventori masa nyata.

## Struktur Repositori
* /docs — Dokumen SRS, ERD, DFD & Data Dictionary
* /database — Skrip migrasi pangkalan data (3NF) & data ujian (seeders)
* /src — Kod sumber aplikasi web (PHP, HTML, CSS, JS)
