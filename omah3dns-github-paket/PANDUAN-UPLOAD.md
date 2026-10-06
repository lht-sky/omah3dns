# Panduan upload ke GitHub

Paket ini berisi dua folder. Masing-masing diunggah ke repo yang berbeda.

```
lht-sky/                  → isi repo  github.com/lht-sky/lht-sky
  README.md                 (README profil, tampil di halaman profil GitHub)

lht-sky.github.io/        → isi repo  github.com/lht-sky/lht-sky.github.io
  index.html                (portofolio omah3dns)
  README.md
  gw2/index.html            (konsep 3D GW-2)
  musimorph/index.html      (konsep 3D Musimorph)
```

## 1. README profil (repo `lht-sky`)

1. Buka repo `lht-sky`.
2. Jika sudah ada README.md, klik file tersebut, lalu ikon pensil (Edit). Jika belum ada, klik **Add file → Create new file** dan beri nama `README.md`.
3. Salin isi `lht-sky/README.md` dari paket ini, tempel, lalu **Commit changes**.
4. Buka github.com/lht-sky. README akan tampil di halaman profil.

## 2. Website portofolio (repo baru `lht-sky.github.io`)

1. Di GitHub klik **+ → New repository**.
2. Nama repo harus persis: `lht-sky.github.io`. Pilih **Public**, lalu **Create repository**.
3. Di halaman repo kosong, klik **uploading an existing file**.
4. Seret **isi** folder `lht-sky.github.io` (file `index.html`, `README.md`, serta folder `gw2` dan `musimorph`) ke jendela upload. Yang diseret isinya, bukan folder induknya, supaya `index.html` berada di akar repo.
5. Klik **Commit changes**.
6. Buka **Settings → Pages**. Pada *Build and deployment*, pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, lalu **Save**.
7. Tunggu 1–3 menit, lalu buka **https://lht-sky.github.io**.

## 3. Sebelum dibagikan ke klien

- **Kontak**: buka `index.html`, cari tulisan `Tambahkan WhatsApp / email`, lalu ganti komentar itu dengan nomor atau email yang ingin ditampilkan.
- **Nama klien**: Musimorph dan PT Global Inti Sinergi disebut terang-terangan. Samarkan jika ada perjanjian kerahasiaan.
- **Repo guruvokasi** harus Public agar tautan dari halaman ini bisa dibuka orang lain.

## 4. Menambah proyek baru nanti

Buat folder baru, misalnya `sparepart-xyz/`, isi dengan `index.html` proyeknya. Lalu tambahkan tautan `href="sparepart-xyz/"` di bagian Karya pada `index.html` utama.

## 5. Opsional: domain sendiri

Jika nanti membeli domain (misalnya omah3dns.com atau omah3dns.my.id), isi di **Settings → Pages → Custom domain**. Alamat lht-sky.github.io otomatis dialihkan ke domain tersebut.
