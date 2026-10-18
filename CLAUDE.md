# Portofolio — RemoteKerja

Repo portofolio milik jingga25. Berisi halaman-halaman UI sebagai showcase proyek.

## File utama

- `remotekerja.html` — Sistem informasi pencarian kerja remote. Single-file HTML, tidak perlu build tool.
- `index.html` — Halaman portofolio utama (dark theme, biru/amber).
- `Portfolio_UI_Santi.html` — UI showcase light/dark.

## Stack remotekerja.html

- Pure HTML + CSS + Vanilla JS (tidak pakai framework)
- Font: Plus Jakarta Sans + JetBrains Mono (Google Fonts)
- Tema: dark-first dengan CSS custom properties, support light mode via `[data-theme="light"]`
- Warna aksen utama: teal `#00D4AA`, purple `#6C63FF`, coral `#FF6B6B`

## Data lowongan

Semua data job ada di array `jobs[]` di bagian `<script>` bawah file.
Setiap job punya: `logo`, `logoBg`, `logoFg`, `title`, `co`, `salary`, `desc`, `resp[]`, `reqs[]`, `meta[]`.

Card HTML ada di `<div class="job-list" id="jobList">` — ada 6 card saat ini.

## Deploy

GitHub Pages aktif di branch `main`.
Setelah push ke main, perubahan live di: https://jingga25.github.io/Portofolio/remotekerja.html
