# Portofolio Web (HTML + CSS)

Ringkasan

Proyek ini adalah situs portofolio sederhana berisi halaman Beranda (`index.html`), Portofolio (`portfolio.html`) dan Kontak (`contact.html`) dengan styling terpusat di `style.css`.

Fitur utama

- Mudah dijalankan — tidak perlu server, cukup buka `index.html` di browser.
- Tema warna dikendalikan oleh variabel CSS di `:root` pada `style.css` sehingga mudah mengganti palet.
- Layout responsif sederhana untuk tampilan mobile dan desktop.

Struktur file

- `index.html` — Halaman utama (Beranda).
- `portfolio.html` — Halaman berisi tabel data portofolio.
- `contact.html` — (jika ada) halaman kontak / form.
- `style.css` — Semua gaya untuk situs; berisi variabel tema di bagian `:root`.

Cara menjalankan

1. Pastikan semua file berada di folder yang sama.
2. Buka file `index.html` di browser (double-click atau klik kanan → Open with → pilih browser).

Mengubah warna / tema

Warna utama didefinisikan di bagian `:root` pada `style.css`. Contoh variabel yang tersedia:

- `--latar` — warna latar utama (background)
- `--kartu` — warna latar kartu / header / footer
- `--lembut` — warna teks lembut / deskripsi
- `--text` — warna teks utama
- `--aksen` — warna aksen utama (digunakan pada tombol, ikon)
- `--aksen-dua` — warna aksen kedua (gradient, highlight)
- `--kaca` — overlay kaca/transparansi

Untuk mengganti tema, buka `style.css` dan ubah nilai hex / rgba pada variabel-variabel di `:root`. Contoh:

:root {
  --latar: #062f2f;
  --kartu: #062725;
  --lembut: #dff5f2;
  --text: #dffdfa;
  --aksen: #2ec4b6;
  --aksen-dua: #8be7cf;
}

Tips aksesibilitas

- Pastikan rasio kontras teks terhadap latar cukup tinggi — jika mengganti warna teks atau latar, cek kontras (mis. https://webaim.org/resources/contrastchecker/).
- Gunakan kombinasi warna yang mudah dibaca pada ukuran kecil.

Menyesuaikan font

Situs sudah memuat Google Fonts (`Inter` dan `Poppins`) di head HTML. Untuk mengganti, edit tautan Google Fonts di masing-masing HTML dan sesuaikan aturan `font-family` di `style.css`.

Menambahkan konten baru

- Tambahkan halaman baru (.html) di folder yang sama dan link dari navigation pada `index.html` atau `portfolio.html`.
- Untuk menambah item portofolio, edit tabel di `portfolio.html`.

Lisensi dan kredit

- Template sederhana ini dibuat untuk keperluan portofolio pribadi.
- Bebas dipakai/diubah (lisensi: MIT — tambahkan file LICENSE jika perlu).

Troubleshooting

- Jika perubahan CSS tidak muncul, lakukan refresh paksa di browser (Ctrl+F5) atau bersihkan cache.
- Pastikan path file relatif (mis. `style.css`) benar saat memindahkan file ke folder lain.

Kontak

Jika butuh bantuan mengubah tema/menambahkan fitur, beri tahu saya file mana yang ingin diubah dan palet warna yang diinginkan.

---

(Catatan: README ini dibuat berdasarkan isi file CSS dan HTML yang ada di folder proyek.)