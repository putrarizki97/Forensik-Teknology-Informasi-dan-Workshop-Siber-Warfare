# 📜 Hukum & Regulasi Siber di Indonesia

Dokumentasi ringkas peraturan perundangan terkait **keamanan siber, data pribadi, dan aktivitas elektronik** di Indonesia.  
Cocok untuk referensi cepat di proyek, tugas kuliah, atau compliance checklist internal.

---

## 📚 Daftar Isi
- [Undang-Undang (UU)](#undang-undang-uu)
- [Peraturan Pemerintah (PP) & Turunan](#peraturan-pemerintah-pp--turunan)
- [Sektor Spesifik](#sektor-spesifik)
- [Ringkasan Cepat](#ringkasan-cepat)
- [Checklist Kepatuhan](#checklist-kepatuhan)
- [Glosarium Singkat](#glosarium-singkat)
- [Catatan & Sumber Resmi](#catatan--sumber-resmi)
- [Lisensi](#lisensi)

---

## Undang-Undang (UU)

### UU No. 11 Tahun 2008 tentang Informasi dan Transaksi Elektronik (UU ITE)
- **Tanggal**: 21 April 2008  
- **Inti**:
  - Pengakuan dokumen/informasi elektronik & tanda tangan elektronik sebagai alat bukti.
  - Larangan dan sanksi terkait konten ilegal (mis. penghinaan/pencemaran nama baik, perjudian, penyebaran konten melanggar hukum).
  - Ketentuan penyelenggaraan transaksi elektronik.

### UU No. 19 Tahun 2016 (Perubahan atas UU ITE)
- **Tanggal**: 25 November 2016  
- **Inti**:
  - Penyesuaian rumusan pasal multitafsir.
  - Penyesuaian ancaman pidana dan denda.
  - Penegasan peran penegak hukum & hak masyarakat.

### UU No. 27 Tahun 2022 tentang Perlindungan Data Pribadi (UU PDP)
- **Tanggal**: 17 Oktober 2022  
- **Inti**:
  - Dasar hukum pengumpulan, pemrosesan, penyimpanan, dan transfer data pribadi.
  - **Hak Subjek Data**: akses, perbaikan, penghapusan, portabilitas, tarik persetujuan.
  - **Kewajiban** Pengendali/Prosesor Data: dasar pemrosesan, keamanan, DPIA (penilaian dampak), pelaporan insiden kebocoran.
  - **Sanksi**: administratif dan pidana atas pelanggaran.

---

## Peraturan Pemerintah (PP) & Turunan

### PP No. 71 Tahun 2019 tentang Penyelenggaraan Sistem dan Transaksi Elektronik (PSTE)
- Menggantikan PP 82/2012.
- Kewajiban **Penyelenggara Sistem Elektronik (PSE)**: keandalan, keamanan, lokasi pusat data (fleksibilitas tertentu), pelaporan insiden, audit.

### Peraturan Presiden No. 53 Tahun 2017 tentang BSSN
- Pembentukan **Badan Siber dan Sandi Negara (BSSN)** sebagai otoritas keamanan siber nasional (kebijakan, monitoring, respons insiden).

### Permenkominfo No. 5 Tahun 2020 (PSE Privat) *(serta perubahannya)*
- Pendaftaran PSE lingkup privat.
- Kewajiban moderasi konten, pelaporan, dan interop kebijakan takedown sesuai hukum Indonesia.

---

## Sektor Spesifik

### Keuangan/Perbankan – OJK
- **POJK No. 38/POJK.03/2016**: Manajemen risiko TI pada bank (governance, keamanan, DR/BCP, audit TI).
- **SEOJK Terkait**: Pedoman teknis penerapan kontrol, pelaporan insiden, dan pengujian berkala.

### Penegakan Hukum – Siber
- **SE Kapolri No. SE/2/XII/2016**: Pedoman penanganan ujaran kebencian berbasis SARA (rujukan penegakan hukum ranah siber).

> **Catatan**: Aturan sektor lain (fintech, telekomunikasi, kesehatan, pendidikan) memiliki ketentuan spesifik tambahan—cek regulator sektoral terkait.

---

## Ringkasan Cepat

| No | Regulasi | Tahun | Pokok Bahasan Utama |
|----|----------|-------|---------------------|
| 1 | UU 11/2008 (ITE) | 2008 | Dasar hukum informasi & transaksi elektronik, larangan konten ilegal |
| 2 | UU 19/2016 (Perubahan ITE) | 2016 | Penyesuaian pasal & sanksi, perjelas penegakan |
| 3 | UU 27/2022 (PDP) | 2022 | Perlindungan data pribadi, hak subjek data, sanksi |
| 4 | PP 71/2019 (PSTE) | 2019 | Kewajiban PSE, keamanan, pelaporan, audit |
| 5 | Perpres 53/2017 (BSSN) | 2017 | Pembentukan & mandat BSSN |
| 6 | Permenkominfo 5/2020 (PSE Privat) | 2020 | Pendaftaran PSE, moderasi konten, kepatuhan |
| 7 | POJK 38/POJK.03/2016 | 2016 | Manajemen risiko TI perbankan |

---

## Checklist Kepatuhan

**Umum (semua PSE / organisasi):**
- [ ] Identifikasi dasar pemrosesan data (persetujuan, kontrak, kewajiban hukum, dst.) – *UU PDP*  
- [ ] Sediakan kebijakan privasi yang jelas & mudah diakses – *UU PDP, PP 71/2019*  
- [ ] Terapkan kontrol keamanan (akses, log, enkripsi, patching, backup) – *PP 71/2019*  
- [ ] Prosedur respons insiden & pelaporan kebocoran data (ke regulator & subjek data) – *UU PDP*  
- [ ] Tinjau perjanjian pemroses data (DPA) & transfer lintas batas – *UU PDP*  
- [ ] Catat & evaluasi DPIA untuk pemrosesan berisiko tinggi – *UU PDP*  

**PSE Privat (platform/aplikasi):**
- [ ] Pendaftaran PSE ke Kominfo – *Permenkominfo 5/2020*  
- [ ] Moderasi konten & mekanisme pengaduan – *Permenkominfo 5/2020*  
- [ ] Audit berkala & pelaporan sesuai ketentuan – *PP 71/2019*  

**Perbankan/Keuangan:**
- [ ] Tata kelola TI & manajemen risiko (termasuk BCP/DR) – *POJK 38/2016*  
- [ ] Uji keamanan berkala (VA/PT), audit independen – *POJK 38/2016*  
- [ ] Pelaporan insiden siber ke regulator – *POJK/SEOJK terkait*  

---

## Glosarium Singkat
- **PSE**: Penyelenggara Sistem Elektronik.  
- **Pengendali Data**: Pihak yang menentukan tujuan & kendali pemrosesan data pribadi.  
- **Prosesor Data**: Pihak yang memproses data atas nama pengendali.  
- **DPIA**: *Data Protection Impact Assessment* – penilaian dampak perlindungan data.  
- **BCP/DR**: *Business Continuity Plan / Disaster Recovery*.  

---

## Catatan & Sumber Resmi
- **JDIH BSSN**: https://jdih.bssn.go.id  
- **JDIH Kemenkumham (Peraturan.go.id)**: https://peraturan.go.id  
- **Kominfo – PSE**: https://pse.kominfo.go.id  

> Dokumen ini adalah ringkasan non-legal. Untuk kebutuhan hukum, rujuk naskah resmi & konsultasikan penasihat hukum.

---

## Lisensi
Dirilis di bawah **MIT License**. Silakan gunakan/ubah sesuai kebutuhan dengan atribusi yang pantas.
