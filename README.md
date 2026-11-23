# Proposal Tugas Akhir - Telkom University Surabaya

Dokumen Proposal Tugas Akhir Program Studi Sarjana Teknologi Informasi, Direktorat Kampus Surabaya, Universitas Telkom.

- **Judul:** Sistem Pencegahan Diskrepansi Menggunakan Analisis ABC dan Arsitektur REST API pada Sistem Point of Sales
- **Judul (Inggris):** *Discrepancy Prevention System Using ABC Analysis and REST API Architecture on Point of Sales System*
- **Penyusun:** Muhammad Febriano Aldo Syahputra
- **NIM:** 1202230021
- **Tahun Pengajuan:** 2026

---

## Struktur Berkas Workspace

```text
proposal-ta/
├── .vscode/
│   └── settings.json           # Konfigurasi otomatis compiler Tectonic untuk LaTeX Workshop
├── .gitignore                  # Mengabaikan berkas build auxiliary LaTeX pada version control
├── proposal.tex                # Berkas naskah utama LaTeX (sesuai template resmi kampus)
├── proposal.pdf                # Dokumen luaran PDF hasil kompilasi
├── daftar_pustaka_arsip.tex    # Arsip referensi cadangan yang dikelompokkan secara tematik
├── logo_telkom.png             # Aset gambar logo resmi Universitas Telkom
├── preview.html                # Pratinjau interaktif naskah di web browser (siap cetak A4)
└── README.md                   # Dokumentasi panduan workspace proyek
```

---

## Panduan Kompilasi Dokumen

Proyek ini telah dikonfigurasi untuk menggunakan **Tectonic**, mesin LaTeX portabel modern yang mengelola paket dan *multi-pass compilation* secara otomatis tanpa instalasi MiKTeX/TeX Live yang berat.

### 1. Kompilasi melalui VS Code (LaTeX Workshop)
- Buka berkas `proposal.tex` di VS Code.
- Setiap kali Anda menyimpan berkas (`Ctrl + S`), dokumen akan otomatis dikompilasi ulang oleh Tectonic.
- Tekan **`Ctrl + Alt + V`** untuk membuka pratinjau PDF langsung di tab VS Code.

### 2. Kompilasi Manual melalui Terminal
Jalankan perintah berikut di PowerShell:
```powershell
& "C:/Users/ADVAN/AppData/Local/Programs/tectonic/tectonic.exe" --synctex proposal.tex
```

---

## Pratinjau Cepat Web Browser
Anda juga dapat membuka berkas `preview.html` menggunakan peramban (Chrome, Edge, dll.) untuk melihat tampilan visual seluruh halaman proposal yang telah diselaraskan dengan standar tata letak A4.
