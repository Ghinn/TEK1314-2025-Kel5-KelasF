# Proyek PBL Keamanan Siber: Implementasi IDS & Hardening
**Scenario: Internal Database Fortress, Data Exfiltration Simulasi akses ilegal menggunakan kredensial curian (Privilege Escalation) dan upaya mengunduh dump database secara diam-diam.**

**Kelompok: 5** 

**Anggota:** 
1. Ghina Rania - Lead Analyst 
2. Bintang Hamizan Elka - Security Engineer 
3. Steven Imanuel - Analyst
4. Ghazy Hasan - Analyst

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk mensimulasikan pengamanan jaringan pada server database menggunakan Security Onion sebagai sistem monitoring dan penerapan teknik hardening untuk meminimalkan celah keamanan.

## 📂 Struktur Repositori
[cite_start]Sesuai dengan panduan Fase 1[cite: 32, 33, 34, 35]:
* `/docs/phase-1-baseline/`: Laporan Hardening & Logging (Minggu 5-7).
* `/docs/phase-2-va/`: Analisis Kerentanan (Vulnerability Assessment).
* `/docs/phase-3-incident/`: Laporan Penanganan Insiden.
* `/scripts/`: Kumpulan script automasi/konfigurasi.
* `LOGBOOK.md`: Catatan aktivitas mingguan anggota kelompok.

## 🛠️ Infrastruktur Target
**Hostname:** kel5
**OS:** Ubuntu Server 24 LTS (Monitoring)
**IP Address:** 192.168.5.20 (Contoh)


## 🛠️ Infrastruktur Attacker [Cyberops Workstation VM]
**Hostname:** kel5 (Disarankan mengikuti format kelompok).
**OS:** Linux (Atau sistem yang menjalankan Nmap).
**IP Address:** 192.168.5.10.
**Tools Utama:** Nmap (untuk scanning) dan Ping (untuk host discovery).

## 🛠️ Infrastruktur Monitoring
**Hostname:** SRV-WEB-KEL05F
**OS:** Security Onion.
**IP Address:** 192.168.5.30.
**Hardening Status:** UFW Active (Hanya mengizinkan port 22/TCP).
**Monitoring Method:** Wireshark (Plan B - Manual Analysis) untuk merekam trafik secara real-time.
**Interface:** eth0
