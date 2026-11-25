# Salin Foto Pilihan

Alat gratis untuk fotografer: tempel nomor foto pilihan klien, lalu file RAW dan JPG yang cocok disalin atau dipindah ke folder tujuan. Semua berjalan di browser pengunjung, tanpa upload.

- Alat: `salin-foto/index.html`
- Halaman utama (`index.html`) langsung membuka alat.
- Butuh Google Chrome atau Microsoft Edge di laptop/PC, lewat HTTPS.

## Hosting

Dihosting dengan GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / `(root)`**.
Untuk domain sendiri, isi *Custom domain* di halaman yang sama, lalu arahkan DNS domain ke GitHub Pages.

## DealerMac Pilih (`/seleksi`)

Folder `seleksi` adalah submodule dari repo [chiko-tech/seleksi](https://github.com/chiko-tech/seleksi) — web app seleksi foto klien, tayang di **https://dealermac.com/seleksi/**.
Setelah ada perubahan di repo `seleksi`, perbarui tautannya di sini:

```bash
git submodule update --remote seleksi
git commit -am "Update seleksi" && git push
```

Salin Foto bisa diisi otomatis dari hasil pilihan klien: `/salin-foto/#nama=IMG_1001%20IMG_1002`.
