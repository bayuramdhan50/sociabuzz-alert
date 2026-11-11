# ⚡ StreamAlert Studio - Koleksi Custom Donation Alert SociaBuzz & OBS

Koleksi lengkap asset kustomisasi alert donasi (overlay) siap pakai untuk **SociaBuzz** dan **OBS Studio / Streamlabs**. Murni dibangun menggunakan **HTML & CSS self-contained** yang ringan, berjalan mulus 60 FPS tanpa lag, dan tidak bergantung pada plugin eksternal.

Dilengkapi dengan **Website Katalog Statis Showcase** (`index.html`) yang siap di-hosting gratis langsung menggunakan **GitHub Pages (`github.io`)**.

---

## 🎨 Daftar 10 Tema Custom Alert Siap Pakai

Setiap tema dikemas rapi dalam foldernya masing-masing dengan berkas kode SociaBuzz, simulator interaktif offline, dan dokumentasi panduan:

| No | Folder Tema | Nama Tema | Karakter / Bentuk Kartu | Palet Warna Utama | Tipografi (Google Fonts) |
|---|---|---|---|---|---|
| 1 | [`Tema_Naruto_Shinobi/`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/Tema_Naruto_Shinobi) | **Naruto Shinobi Konoha** | Gulungan Ninja, Pusaran Uzumaki, Aksen Chakra | Chakra Orange (`#FF7300`), Rasengan Cyan (`#00D2FF`) | `Bangers` & `Plus Jakarta Sans` |
| 2 | [`Tema_Batman_DarkKnight/`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/Tema_Batman_DarkKnight) | **Batman The Dark Knight** | Batwing Beveled Cuts, Sorot Bat-Signal | Gotham Black (`#08090C`), Bat-Yellow (`#FFE600`) | `Teko` & `Montserrat` |
| 3 | [`Tema_OnePiece_Pirate/`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/Tema_OnePiece_Pirate) | **One Piece Pirate Bounty** | Poster Wanted Perkamen, Lambang Berry ฿ | Vintage Parchment (`#FBF2DC`), Crimson (`#C92A2A`) | `Rye` & `Plus Jakarta Sans` |
| 4 | [`Tema_Valorant_Tactical/`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/Tema_Valorant_Tactical) | **Valorant Tactical Agent** | VCT Polygon Chamfer, Crosshair HUD | Valorant Red (`#FF4655`), Charcoal (`#0F1923`) | `Oswald` & `Share Tech Mono` |
| 5 | [`Tema_Cyberpunk_Neon/`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/Tema_Cyberpunk_Neon) | **Cyberpunk Neon Mecha** | Chamfered Polygon Cut, Laser Scanline Sweep | Cyber Yellow (`#FCEE0A`), Cyan Laser (`#00F0FF`) | `Orbitron` & `Rajdhani` |
| 6 | [`Tema_Sakura_Kawaii/`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/Tema_Sakura_Kawaii) | **Sakura Pastel Kawaii** | Soft Rounded Pill 26px, Kelopak Bunga Berputar | Blossom Pink (`#FF6B8B`), Strawberry (`#FF3366`) | `Quicksand` & `Itim` |
| 7 | [`Tema_Pixel_Retro/`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/Tema_Pixel_Retro) | **Pixel Retro 8-Bit Arcade** | Stepped Pixel Box Shadow, CRT Scanlines | Coin Gold (`#FFCC00`), Retro Cyan (`#00F5D4`) | `Press Start 2P` & `VT323` |
| 8 | [`Tema_Royal_Luxury/`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/Tema_Royal_Luxury) | **Royal Luxury Gold** | Double Gold Geometric Frame, Shimmer Sweep | Imperial Gold (`#D4AF37`), Obsidian (`#0E0E12`) | `Cinzel` & `Montserrat` |
| 9 | [`Tema_Minimalist_Modern/`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/Tema_Minimalist_Modern) | **Minimalist Modern Glass** | Frosted Glass Bar 16px, Dot Hijau Aktif | Electric Emerald (`#00F59B`), Slate (`#0F172A`) | `Plus Jakarta Sans` |
| 10 | [`Pribadi/`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/Pribadi) | **Team Liquid Official Edition** | Rounded Card 20px, Watermark Kuda Liquid | Foundation Blue (`#001538`), Cyan (`#3BB0D4`) | `DM Sans` & `Caveat` |

---

## 📁 Struktur Direktori Proyek

```
sociabuzz-alert/
├── index.html                   # Website Katalog Showcase (Entrypoint GitHub Pages)
├── catalog.css                  # Stylesheet modern dark theme & responsive grid
├── README.md                    # Dokumentasi lengkap proyek & panduan hosting
│
├── Tema_Naruto_Shinobi/         # [1] Tema Naruto
│   ├── sociabuzz-html.html      # Kode HTML siap salin ke SociaBuzz
│   ├── sociabuzz-css.css       # Kode CSS siap salin ke SociaBuzz
│   ├── preview.html            # Simulator interaktif browser
│   └── README.md
│
├── Tema_Batman_DarkKnight/      # [2] Tema Batman
│   ├── sociabuzz-html.html
│   ├── sociabuzz-css.css
│   ├── preview.html
│   └── README.md
│
├── Tema_OnePiece_Pirate/        # [3] Tema One Piece
│   ├── sociabuzz-html.html
│   ├── sociabuzz-css.css
│   ├── preview.html
│   └── README.md
│
├── Tema_Valorant_Tactical/      # [4] Tema Valorant
│   ├── sociabuzz-html.html
│   ├── sociabuzz-css.css
│   ├── preview.html
│   └── README.md
│
├── Tema_Cyberpunk_Neon/         # [5] Tema Cyberpunk
│   ├── sociabuzz-html.html
│   ├── sociabuzz-css.css
│   ├── preview.html
│   └── README.md
│
├── Tema_Sakura_Kawaii/          # [6] Tema Sakura Kawaii
│   ├── sociabuzz-html.html
│   ├── sociabuzz-css.css
│   ├── preview.html
│   └── README.md
│
├── Tema_Pixel_Retro/            # [7] Tema Pixel Retro 8-Bit
│   ├── sociabuzz-html.html
│   ├── sociabuzz-css.css
│   ├── preview.html
│   └── README.md
│
├── Tema_Royal_Luxury/           # [8] Tema Royal Luxury Gold
│   ├── sociabuzz-html.html
│   ├── sociabuzz-css.css
│   ├── preview.html
│   └── README.md
│
├── Tema_Minimalist_Modern/      # [9] Tema Minimalist Glass
│   ├── sociabuzz-html.html
│   ├── sociabuzz-css.css
│   ├── preview.html
│   └── README.md
│
└── Pribadi/                     # [10] Tema Pribadi Team Liquid
    ├── sociabuzz-html.html
    ├── sociabuzz-css.css
    ├── preview.html
    └── README.md
```

---

## 🌐 Panduan Hosting Gratis di GitHub Pages (`github.io`)

Karena proyek ini menggunakan HTML & CSS statis tanpa server backend yang rumit, Anda dapat langsung meng-onlinekan katalog ini di GitHub Pages secara gratis:

### Langkah 1: Buat Repository di GitHub
1. Masuk ke akun [GitHub](https://github.com) Anda.
2. Buat repository baru, misalnya bernama `custom-alert` atau `stream-alert`.
3. Biarkan berstatus **Public** agar GitHub Pages bisa aktif gratis.

### Langkah 2: Hubungkan & Push Repository Lokal
Jalankan perintah berikut di terminal:
```bash
git remote add origin https://github.com/<username-anda>/<nama-repo>.git
git push -u origin feat/custom-alert-themes
```
*(Setelah pengujian selesai, branch dapat di-merge ke `main` dan di-push ke branch `main`).*

### Langkah 3: Aktifkan GitHub Pages
1. Di halaman repository GitHub Anda, klik tab **Settings**.
2. Pada menu samping kiri, klik **Pages**.
3. Pada bagian **Build and deployment > Source**, pilih **Deploy from a branch**.
4. Di bagian **Branch**, pilih branch yang aktif (misal `main` atau `feat/custom-alert-themes`) dan folder `/ (root)`.
5. Klik **Save**.
6. Tunggu sekitar 1-2 menit. Website katalog Anda akan online di tautan:
   ```
   https://<username-anda>.github.io/<nama-repo>/
   ```

---

## 🚀 Panduan Pemasangan ke SociaBuzz

1. Masuk ke dashboard [SociaBuzz](https://sociabuzz.com).
2. Buka menu **Overlay / Alert Donasi**.
3. Pada opsi **Kustomisasi Tampilan (Custom Alert)**:
   - Buka file `sociabuzz-html.html` tema pilihan Anda, salin seluruh kodenya ke kolom **HTML**.
   - Buka file `sociabuzz-css.css` tema pilihan Anda, salin seluruh kodenya ke kolom **CSS**.
4. Klik tombol **Simpan / Update**.
5. Salin link Browser Source yang diberikan SociaBuzz.

---

## 📺 Panduan Pengaturan di OBS Studio

1. Buka OBS Studio.
2. Pada panel **Sources**, klik ikon `+` dan pilih **Browser**.
3. Beri nama alert, lalu tempelkan link dari SociaBuzz ke kolom **URL**.
4. Atur dimensi:
   - **Width**: `650`
   - **Height**: `220`
5. Centang opsi:
   - ✅ *Shutdown source when not visible*
   - ✅ *Refresh browser when scene becomes active*
6. Klik **OK** dan letakkan alert di kanvas streaming Anda.

---

## 📞 Informasi Kontak & Pemesanan Custom Alert

Jika Anda ingin membeli paket tema atau ingin memesan alert eksklusif khusus streamer Anda (request logo, warna, dan animasi khusus):

- **📱 WhatsApp**: [081220105682](https://wa.me/6281220105682?text=Halo,%20saya%20tertarik%20dengan%20Custom%20Alert%20SociaBuzz)
- **👾 Discord ID**: `415282600404582420` ([Buka Profil Discord](https://discord.com/users/415282600404582420))

