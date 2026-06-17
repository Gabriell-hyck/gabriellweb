# ∆ gabrielldewaruci // portfolio

Personal portfolio website dengan terminal/hacker aesthetic. Dibangun full vanilla HTML, CSS, dan JavaScript — nggak pakai framework, ringan, dan bisa langsung jalan di browser tanpa build process.

```bash
gabriell@portfolio:~$ ./run.sh
[ OK ] Loading terminal interface...
[ OK ] Rendering portfolio...
[ OK ] System ready.
```

## Preview

Tampilan terminal hijau-hitam klasik dengan boot sequence, foto profil bulat beranimasi glitch, dan semua section dikemas dalam format ala command line / JSON output.

## Fitur

- **Boot screen** — animasi loading ala booting sistem sebelum masuk ke halaman utama
- **Custom cursor** — cursor dot hijau glowing yang ngikutin mouse, membesar saat hover elemen interaktif
- **Foto profil interaktif** — bentuk bulat dengan ring berputar, efek glitch RGB-split otomatis dan saat di-hover
- **Scanline overlay** — efek CRT monitor di seluruh halaman
- **Glitch text** — nama di hero section glitch saat di-hover
- **Skill bars animasi** — progress bar tech stack yang animasinya jalan saat di-scroll ke section
- **Project cards** — terhubung langsung ke repo GitHub asli, lengkap dengan tags dan deskripsi
- **Terminal windows** — about section dan contact section dikemas dalam tampilan terminal dengan dot merah-kuning-hijau khas macOS
- **Fully responsive** — menyesuaikan dari desktop sampai mobile

## Struktur folder

```
portfolio/
├── portfolio.html       # Semua HTML, CSS, dan JS dalam satu file
└── images/
    └── foto-gw.jpg       # Foto profil (ganti sesuai foto kamu)
```

## Tech stack

`HTML5` · `CSS3` · `Vanilla JavaScript`

Font: [Share Tech Mono](https://fonts.google.com/specimen/Share+Tech+Mono), [VT323](https://fonts.google.com/specimen/VT323), [Orbitron](https://fonts.google.com/specimen/Orbitron)

## Cara menjalankan

1. Clone repo ini
2. Pastikan foto profil ada di `images/foto-gw.jpg` (atau ganti path-nya di kode sesuai nama file kamu)
3. Buka `portfolio.html` langsung di browser

Tidak perlu instalasi dependency atau build tools apapun.

## Kustomisasi

| Yang mau diubah | Lokasi |
|---|---|
| Foto profil | `src` di tag `<img class="photo-base">` |
| Daftar tech stack | array `skills` di bagian `<script>` |
| Daftar project | array `projects` di bagian `<script>` |
| Link kontak (GitHub, email, Discord) | section `#contact` |
| Warna tema | variabel CSS `:root` di bagian atas `<style>` |

## License

Bebas dipakai dan dimodifikasi untuk keperluan pribadi.

---

<sub>built with ♥ + caffeine by gabrielldewaruci</sub>
