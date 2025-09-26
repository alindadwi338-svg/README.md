# 🏢 Sistem Informasi PT.-Cybernova
Profil perusahaan mitra, pendaftaran PKL, dan laporan monitoring kegiatan

---

## 📌 1. Latar Belakang / Profil Proyek
**PT.-Cybernova** adalah sistem informasi yang dikembangkan untuk mendukung kegiatan Praktik Kerja Lapangan (PKL) di lingkungan sekolah.  
Tujuan utama proyek ini:
- Menyediakan informasi profil perusahaan mitra secara terstruktur.  
- Memfasilitasi proses pendaftaran PKL secara digital.  
- Menyediakan fitur monitoring kegiatan PKL yang transparan dan terdokumentasi.  

---

## ⚙️ 2. Fitur Utama
- **Manajemen Profil Perusahaan Mitra**: Data mitra, bidang usaha, kontak, dan informasi umum.  
- **Pendaftaran PKL**: Formulir online untuk siswa, validasi data, serta status pendaftaran.  
- **Monitoring Kegiatan**: Laporan kegiatan siswa, progres PKL, serta catatan harian.  
- **Dashboard Admin**: Kelola data mitra, siswa, dan monitoring kegiatan.  
- **Laporan PKL**: Rekap laporan PKL yang bisa dicetak/diekspor.  

---

## 🗂️ 3. Struktur Database
Entitas utama:
- `users` — data akun siswa, admin, dan pembimbing.  
- `mitra` — data perusahaan mitra (profil & bidang usaha).  
- `pendaftaran` — data pendaftaran PKL siswa.  
- `monitoring` — laporan kegiatan PKL.  
- `laporan` — kumpulan laporan akhir PKL.  

> 📌 Sertakan diagram ERD di folder `docs/ERD/` bila tersedia.

---

## 🛠️ 4. Teknologi
- **Front-End**: HTML, CSS, Bootstrap  
- **Back-End**: PHP (atau framework seperti Laravel)  
- **Database**: MySQL  
- **Version Control**: Git & GitHub  
- **Desain UI/UX**: Figma / Adobe XD (opsional)  

---

## 🔄 5. Alur Kerja PKL
| Tahap | Kegiatan |
|-------|----------|
| Profil Mitra | Input & kelola data perusahaan mitra |
| Pendaftaran PKL | Siswa mendaftar melalui sistem |
| Monitoring | Pembimbing & admin memantau kegiatan PKL |
| Laporan | Siswa mengunggah laporan, admin verifikasi |
| Dokumentasi | Penyusunan laporan akhir & evaluasi proyek |

---

## ✅ 6. Status Proyek
- [x] Repository GitHub dibuat  
- [x] Desain database awal selesai  
- [ ] Modul pendaftaran PKL berjalan  
- [ ] Modul monitoring kegiatan aktif  
- [ ] Laporan PKL terintegrasi  

---

## 🚀 7. Cara Instalasi & Menjalankan
1. Clone repository:
   ```bash
   git clone https://github.com/[username]/PT-Cybernova.git
