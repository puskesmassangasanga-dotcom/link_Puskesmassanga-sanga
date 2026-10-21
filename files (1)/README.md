# Pusat Link Puskesmas Sangasanga

Halaman kumpulan link (form, rekap, aplikasi) Puskesmas. Satu halaman, bisa dicari dan dikelompokkan.

## Isi folder
- `index.html` : tampilan halaman (tidak perlu diubah)
- `data.js` : daftar link (file inilah yang diedit)

## Cara tayang di GitHub Pages
1. Buat repository baru di GitHub (mis. `link-puskesmas`), set Public.
2. Klik **Add file > Upload files**, unggah `index.html`, `data.js`, `README.md`, lalu **Commit changes**.
3. Buka **Settings > Pages**. Di *Build and deployment*, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, klik **Save**.
4. Tunggu 1-2 menit. Alamat halaman: `https://NAMA-GITHUB.github.io/link-puskesmas/`

Catatan: repository Public membuat daftar link bisa dilihat siapa saja yang punya alamatnya. Jangan masukkan link yang sifatnya rahasia.

## Cara menambah link (untuk semua orang)
**Cara 1 (langsung di GitHub):** buka `data.js` > ikon pensil (Edit) > tambah satu baris di bagian `links`:
```
["nomor_kelompok", "Nama Link", "https://alamat-link"],
```
Nomor kelompok dimulai dari 0 sesuai urutan di `cats` (0 = Pelaporan, 1 = Pelayanan, 2 = Kepegawaian, 3 = Kemenkes, 4 = Surat & Dokumen, 5 = Akreditasi). Lalu **Commit changes**.

**Cara 2 (lewat halaman):** klik **+ Tambah**, isi form (tersimpan di perangkat itu saja). Klik **Ekspor** untuk menyalin isi `data.js` terbaru, lalu tempel menggantikan isi `data.js` di GitHub.
