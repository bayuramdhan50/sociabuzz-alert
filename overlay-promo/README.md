# 📢 Overlay Promosi & Custom Alert (OBS & TikTok Live Studio)

Widget overlay promosi mandiri dan custom alert 60 FPS untuk **TikTok Live Studio**, **OBS Studio**, dan **SociaBuzz**. Berbasis HTML5, CSS3 hardware-accelerated, dan JavaScript murni tanpa dependensi berat.

---

## 🎨 Tema yang Disediakan

1. **Pink Alert (Sakura Pastel Kawaii)**:
   - Warna: Blush Pearl (`#FFF5F7`), Blossom Pink (`#FF6B8B`), Sweet Strawberry (`#FF3366`), Soft Lilac (`#9D72FF`).
   - Fitur visual: Sudut melengkung 26px, ornamen kelopak bunga melayang, badge miring mengambang, font ramah (`Quicksand` & `Itim`).
2. **Cyberpunk Alert (Mecha HUD Futuristic)**:
   - Warna: Carbon Slate Dark (`#0A0E17`), Cyber Yellow (`#FCEE0A`), Cyan Laser (`#00F0FF`), Neon Crimson (`#FF003C`).
   - Fitur visual: Sudut chamfered polygon cut, garis laser scanline sweep, bracket HUD, font sci-fi tajam (`Orbitron` & `Share Tech Mono`).

---

## 🚀 Cara Menjalankan

### 1. Uji Coba Langsung di Browser
Buka file `overlay-promo/index.html` langsung di browser Anda. Terdapat kontrol simulator untuk mengubah teks, tema, mencoba animasi, dan mengaktifkan mode rotasi otomatis.

### 2. Pemasangan di OBS Studio
1. Buka OBS Studio.
2. Pada panel **Sources**, klik ikon **`+`** lalu pilih **Browser**.
3. Centang **Local file**, lalu pilih file `overlay-promo/index.html`.
4. Jika ingin menggunakan URL dinamis / server lokal:
   - Masukkan link: `http://localhost:3000/overlay-promo/index.html?overlay=1&theme=pink`
5. Atur **Width**: `640`, **Height**: `240`.
6. Centang opsi:
   - ✅ *Shutdown source when not visible*
   - ✅ *Refresh browser when scene becomes active*

### 3. Pemasangan di TikTok Live Studio
1. Buka **TikTok Live Studio**.
2. Klik **Add Source** -> Pilih **Web / Browser Source** atau **Custom Link**.
3. Tempelkan URL overlay atau arahkan ke berkas `index.html`.
4. Sesuaikan posisi kartu di atas canvas portrait streaming Anda.

---

## ⚙️ Parameter URL Kustomisasi

Anda dapat mengatur tampilan langsung melalui parameter URL tanpa mengubah kode:

| Parameter | Pilihan Nilai | Fungsi |
|---|---|---|
| `overlay` | `1` | Menyembunyikan panel kontrol dan mengaktifkan mode transparan OBS |
| `theme` | `pink` / `cyberpunk` | Memilih tema desain |
| `badge` | Teks bebas | Mengubah teks badge sudut atas |
| `title` | Teks bebas | Mengubah judul utama / nominal donasi |
| `sub` | Teks bebas | Mengubah teks sub-judul / pengirim |
| `msg` | Teks bebas | Mengubah isi pesan promosi |
| `rotate` | `1` / `true` | Mengaktifkan pergantian teks otomatis secara berkala |
| `interval` | Angka detik (cth: `8`) | Waktu jeda rotasi teks promosi (default: 8 detik) |

**Contoh URL Kustomisasi:**
```text
overlay-promo/index.html?overlay=1&theme=pink&badge=PROMO&title=Sawer+Yuk&sub=Mulai+10rb&msg=Pesanmu+langsung+muncul+di+layar+stream!
```
