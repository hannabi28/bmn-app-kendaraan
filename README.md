# SIM-BMN Kendaraan Dinas — Prototype Fungsional

Prototype frontend berdasarkan konsep PDF `Konsep Website BMN.pdf`.

## Jalankan

Paling sederhana: buka `index.html` di browser modern.

Untuk mode server lokal:

```bash
python -m http.server 8000
```

Lalu buka `http://localhost:8000`.

## Fitur

- Dashboard dan statistik status dokumen.
- Sidebar: Dashboard, Permohonan Peminjaman, BAST Peminjaman, Perpanjangan, Pengembalian, BAST Pengembalian, Data Kendaraan, Riwayat, Tanda Tangan, Pengaturan.
- Form Permohonan mengikuti field pada konsep PDF.
- Pembuatan BAST Peminjaman dengan preview dokumen.
- Form Perpanjangan.
- Form Pengembalian.
- BAST Pengembalian dengan preview.
- Tanda tangan langsung menggunakan canvas mouse/touch untuk 3 pihak.
- Status dokumen Draft → Diajukan → Ditandatangani.
- Cetak / Save as PDF menggunakan dialog print browser.
- Data disimpan di localStorage sehingga tetap ada saat halaman direfresh pada browser yang sama.

## Catatan

Ini adalah prototype frontend, belum memakai backend/database dan belum merupakan tanda tangan elektronik tersertifikasi. Untuk produksi, bagian tanda tangan dan autentikasi perlu dihubungkan ke backend serta mekanisme TTE/sertifikat yang berlaku.
