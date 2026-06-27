# Toolkit

Kumpulan alat kecil sehari-hari, dirakit jadi satu situs portofolio. Tidak ada akun, tidak ada server backend — setiap alat berjalan sepenuhnya di browser.

**🔗 Demo langsung:** `https://Hafizh2006.github.io/Toolkit/`

## Tentang proyek ini

Proyek personal untuk melatih kemampuan merancang dan membangun antarmuka web — mulai dari sistem desain, struktur halaman, sampai logika interaktif tiap alat — dengan bantuan AI di seluruh proses pengembangannya (kode dan desain).

## Daftar alat

| Panel | Alat | Fungsi |
|---|---|---|
| 01 | [Unit Converter](tools/unit-converter.html) | Konversi panjang, berat, dan suhu secara langsung |
| 02 | [Password Generator](tools/password-generator.html) | Membuat kata sandi acak dengan kontrol panjang & jenis karakter |
| 03 | [Markdown Previewer](tools/markdown-previewer.html) | Live preview markdown saat mengetik |
| 04 | [Pomodoro Timer](tools/pomodoro-timer.html) | Timer fokus 25 menit dengan progress ring & notifikasi suara |

## Stack

- HTML, CSS, dan JavaScript murni (vanilla) — tanpa framework atau dependensi eksternal
- Font: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [Inter](https://fonts.google.com/specimen/Inter), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts
- Di-deploy lewat [GitHub Pages](https://pages.github.com/)

## Struktur folder

```
toolkit/
├── index.html              # Halaman utama / showcase semua alat
├── style.css                # Design tokens & style bersama
└── tools/
    ├── unit-converter.html
    ├── password-generator.html
    ├── markdown-previewer.html
    └── pomodoro-timer.html
```

## Menjalankan secara lokal

Tidak perlu instalasi apa pun. Clone repo ini, lalu buka `index.html` langsung di browser:

```bash
git clone https://github.com/username/nama-repo.git
cd nama-repo
```

Atau jalankan local server sederhana (opsional, supaya path relatif lebih stabil):

```bash
python3 -m http.server 8080
```

lalu buka `http://localhost:8080` di browser.

## Roadmap

- [ ] Tambah panel 05 dan seterusnya
- [ ] Mode gelap (dark mode)
- [ ] Simpan preferensi terakhir tiap alat (misal panjang password) di local storage

---

Dirancang & dirakit dengan bantuan AI.
