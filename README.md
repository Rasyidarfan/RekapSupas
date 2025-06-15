# Dokumentasi Permasalahan dan Solusi SUPAS2025

*Update: 15 Juni 2025 - 18:20 WIB*

## 📋 Catatan Update Terbaru:
- **GitHub Issues:** Semua permasalahan kini terdokumentasi di [GitHub Issues](https://github.com/Rasyidarfan/RekapSupas/issues) 
- **Permasalahan Baru:** 8 issues baru ditambahkan dari monitoring grup WhatsApp
- **Status tracking:** Loading issues, data backup, tagging problems, offline mode
- **Solusi tracking:** Beberapa masalah sudah memiliki solusi yang terdokumentasi
- **Update terakhir:** 15 Juni 2025, 18:20 WIB

## 🔗 **INFORMASI DETAIL PERMASALAHAN**

**Untuk informasi detail setiap permasalahan, silakan kunjungi:**  
👉 **[GitHub Issues - RekapSupas](https://github.com/Rasyidarfan/RekapSupas/issues)**

## 📊 **TABEL PERMASALAHAN DAN STATUS TERBARU**

### 🚨 **KRITICAL ISSUES** - Perlu Perhatian Segera

| No | Issue | Permasalahan | Status | Solusi |
|----|-------|-------------|--------|--------|
| [#34](https://github.com/Rasyidarfan/RekapSupas/issues/34) | FASIH System Stuck Loading/Waiting | Multiple reports FASIH loading tidak berhenti | ❌ **Belum teratasi** | Perlu investigasi server |
| [#33](https://github.com/Rasyidarfan/RekapSupas/issues/33) | Update FASIH 1.4.7 Tidak Bisa Next | Tidak bisa lanjut ke pertanyaan berikutnya | ❌ **Belum teratasi** | Rollback ke versi sebelumnya |
| [#32](https://github.com/Rasyidarfan/RekapSupas/issues/32) | Dapat Tarik Sampel Belum Approve PML | Workflow validation tidak berfungsi | ❌ **Belum teratasi** | Enforcement approval workflow |
| [#31](https://github.com/Rasyidarfan/RekapSupas/issues/31) | Roster ART Tidak Dapat Diklik | Aplikasi macet saat akses roster | ❌ **Belum teratasi** | Perbaikan UI responsiveness |
| [#41](https://github.com/Rasyidarfan/RekapSupas/issues/41) | Stabilitas FASIH - PPL Pakai Kertas | Kekhawatiran reliability sistem | ⚠️ **Workaround** | Paper backup sebagai contingency |
| [#26](https://github.com/Rasyidarfan/RekapSupas/issues/26) | Data PPL Hilang Status Kembali Open | Mass data loss 50 dari 60 KK | ❌ **Belum teratasi** | Perlu recovery database |

### ✅ **SOLVED/WORKAROUND AVAILABLE** - Sudah Ada Solusi

| No | Issue | Permasalahan | Status | Solusi |
|----|-------|-------------|--------|--------|
| [#35](https://github.com/Rasyidarfan/RekapSupas/issues/35) | Data Loss - Restore Backup | Data hilang setelah backup | ✅ **Solusi tersedia** | Restore per assignment dari backup |
| [#39](https://github.com/Rasyidarfan/RekapSupas/issues/39) | Batas SLS Keliru - RT Nyempil | RT lain masuk peta WS | ✅ **Panduan tersedia** | Tetap didata sesuai peta WS |
| [#30](https://github.com/Rasyidarfan/RekapSupas/issues/30) | Spasi Hilang Saat Menulis | Text hilang saat tekan spasi | ✅ **Workaround** | Install Google Keyboard |
| [#20](https://github.com/Rasyidarfan/RekapSupas/issues/20) | Data Hilang Simpan Sementara | Temporary save tidak reliable | ⚠️ **Perlu hati-hati** | Backup manual lebih sering |

### 🔧 **TECHNICAL ISSUES** - Perlu Perbaikan Teknis

| No | Issue | Permasalahan | Status | Solusi |
|----|-------|-------------|--------|--------|
| [#36](https://github.com/Rasyidarfan/RekapSupas/issues/36) | PPL Tidak Dapat Tagging | Fitur geotagging tidak berfungsi | ❌ **Investigasi** | Cek GPS permissions |
| [#37](https://github.com/Rasyidarfan/RekapSupas/issues/37) | Tidak Bisa Tambah Assignment Offline | Offline mode tidak berfungsi | ❌ **Bug confirmed** | Perbaikan offline capability |
| [#38](https://github.com/Rasyidarfan/RekapSupas/issues/38) | Admin Kab Tidak Bisa Hapus Data | Permission issue delete operation | ❌ **Akses terbatas** | 5 keluarga pending hapus |
| [#18](https://github.com/Rasyidarfan/RekapSupas/issues/18) | Duplikasi Nomor Ruta | Nomor ruta sama dalam 1 SLS | ❌ **Tidak bisa edit** | Perlu perbaikan constraint DB |

### ❓ **GUIDANCE NEEDED** - Perlu Panduan Operasional

| No | Issue | Permasalahan | Status | Solusi |
|----|-------|-------------|--------|--------|
| [#40](https://github.com/Rasyidarfan/RekapSupas/issues/40) | Workflow Setelah Tarik Sampel | Prioritas kerja tidak jelas | ❓ **Butuh SOP** | Panduan workflow resmi |
| [#29](https://github.com/Rasyidarfan/RekapSupas/issues/29) | Menu Tarik Sampel Tidak Muncul PML | UI tidak show menu sampling | ❌ **Sync issue** | Refresh/sync sistem |
| [#24](https://github.com/Rasyidarfan/RekapSupas/issues/24) | Cek Versi Template | Tidak bisa verify template version | ❓ **Feature request** | Tambah indicator versi |

### 🔄 **DATA SYNC ISSUES** - Masalah Sinkronisasi

| No | Issue | Permasalahan | Status | Solusi |
|----|-------|-------------|--------|--------|
| [#14](https://github.com/Rasyidarfan/RekapSupas/issues/14) | Data FASIH-SM vs FASIH PPL Beda | Inconsistency antar sistem | ❌ **Sync gagal** | Manual verification required |
| [#28](https://github.com/Rasyidarfan/RekapSupas/issues/28) | Prelist Muncul Setelah Add Assignment | Search tidak menemukan nama | ❌ **Cache issue** | Clear cache/refresh |
| [#23](https://github.com/Rasyidarfan/RekapSupas/issues/23) | Prelist Kosong di FASIH | UI tidak load prelist data | ❌ **Loading issue** | Restart aplikasi |

---

## 📚 **RESOURCES DAN PANDUAN**

### 🔗 **Link Solusi Utama:**
- **📊 Rekap Data Prelist:** http://s.bps.go.id/Supas25_Rekap_DataPrelist
- **📖 Bahan Ajar (Primary):** https://s.bps.go.id/Lampiran-SuratPersiapan-PelatihanPetugas
- **📖 Bahan Ajar (Backup):** https://drive.bps.go.id/s/6zRMtM4nWxcKCRL
- **☁️ OneDrive Backup:** https://1drv.ms/f/c/a7e409948bc8ad05/EgKXqU4OprpLpQqowLbrbkYBYXyZ9BrMtV8B6zlcXkF6ew
- **💬 Masukan FASIH:** http://s.bps.go.id/masukan_FASIH_SUPAS2025
- **📋 Laporan Pelatihan:** http://s.bps.go.id/laporan_pelatihan_SUPAS2025

### 💡 **Quick Fix Solutions**
1. **Loading Issues:** Clear data, restart aplikasi
2. **Assignment Missing:** Sync periode/survei
3. **Input Problems:** Update template, install Google Keyboard
4. **Data Sync:** Manual refresh, sinkronisasi ulang
5. **Geotagging:** Check GPS permissions
6. **Backup Data:** Regular backup sebelum submit

---

## 📝 **CARA MELAPORKAN MASALAH BARU**

1. **Cek GitHub Issues** terlebih dahulu: https://github.com/Rasyidarfan/RekapSupas/issues
2. **Gunakan search** untuk melihat apakah masalah sudah dilaporkan
3. **Buat issue baru** jika belum ada dengan format:
   - Deskripsi masalah detail
   - Langkah reproduksi
   - Screenshot/video jika memungkinkan
   - Dampak operasional

## 🤝 **KONTRIBUSI**

**Kontributor:** Tim Koordinasi SUPAS2025  
**Sumber Data:** Grup WhatsApp Koordinasi SUPAS2025  
**Repository:** https://github.com/Rasyidarfan/RekapSupas  
**Issues Tracker:** https://github.com/Rasyidarfan/RekapSupas/issues

---
*Dokumentasi ini diperbarui secara berkala berdasarkan monitoring grup WhatsApp dan feedback lapangan*
