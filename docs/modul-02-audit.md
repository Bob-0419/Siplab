# Audit Modul 2 - Semantic HTML dan Formulir

## Sebelum perbaikan

| Temuan | Halaman/elemen | Bukti | Rencana perbaikan |
|---|---|---|---|
| Katalog masih berupa ul/li | peralatan.html | DOM | Ubah menjadi section + article |
| Form belum tersedia | peminjaman.html | file baru (kosong) | Buat form lengkap |
| Path gambar Beranda `public/images/c.jpg` | index.html | Vite menyajikan folder public dari root | Ganti menjadi `/images/c.jpg` |
| Footer masih menyebut proyek semester | index.html | teks footer | Ganti menjadi "Latihan praktikum Komputasi Berbasis Web." |
| Tag penutup `</html>` hilang | index.html | akhir file | Tambahkan `</html>` |
| Typo pada teks Beranda | index.html | "mahasiwa", "tesedia", "labotarium" | Perbaiki ejaan |

## Setelah perbaikan

- [ ] Landmark halaman masuk akal.
- [ ] Hierarki heading logis (h1 → h2 → h3).
- [ ] Minimal tiga item katalog lengkap.
- [ ] Label dapat diklik dan fokus berpindah.
- [ ] Field penting memiliki name.
- [ ] Submit kosong memunculkan validasi browser.
- [ ] Urutan Tab logis.
- [ ] Validator tidak menampilkan error utama.

## Hasil uji validasi form

| Skenario | Hasil |
|---|---|
| Kosong, klik Kirim | (isi setelah dites) |
| NIM bukan 10 digit | (isi setelah dites) |
| Durasi 0 / 8 | (isi setelah dites) |
| Keperluan "tes" | (isi setelah dites) |
| Checkbox belum dicentang | (isi setelah dites) |

## Challenge tambahan

- Basic: item ke-4 (Laptop) ditambahkan dengan struktur article yang sama.
