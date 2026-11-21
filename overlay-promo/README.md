# 📢 Live Promo Showcase Overlay — OBS & TikTok Live Studio

Overlay pintar 60 FPS khusus untuk **mempromosikan dan menjual Custom Alert** saat Anda sedang *live streaming* di **TikTok Live Studio** atau **OBS Studio**.

Widget ini dirancang dengan alur konversi penjualan (*sales funnel* live):
1. **Fase 1: Teks Promosi (Hook CTA)** muncul terlebih dahulu (misal: *"Mau custom alert seperti ini? Bisa hubungin di DM TikTok saja!"*).
2. **Fase 2: Transisi ke Contoh Nyata** (Animasi mulus beralih ke simulasi alert aktif tema **Pink Sakura Kawaii**).
3. **Fase 3: Contoh Tambahan** (Beralih ke tema **Cyberpunk Mecha HUD**).
4. **Siklus Otomatis (Looping)**: Berputar secara berkala tanpa membebani performa streaming game berat.

---

## 📁 Lokasi Berkas

- **File Utama:** [`overlay-promo/index.html`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/overlay-promo/index.html)
- **Panduan:** [`overlay-promo/README.md`](file:///f:/Bayu/Koding/03-personal/sociabuzz-alert/overlay-promo/README.md)

---

## 🎨 Alur Kerja Tampilan Layar (Sequence)

```
[ Teks Promosi Penjualan ] ──(Transisi Mulus)──> [ Contoh Alert Pink (Sakura Kawaii) ] ──(Transisi)──> [ Contoh Alert 2 (Cyberpunk Neon) ] ──(Kembali ke Awal)
```

1. **Kartu Promosi:**
   - Badge: `✨ CUSTOM ALERT PROMO`
   - Headline: *"Mau custom alert seperti ini? Bisa hubungin di DM TikTok saja!"*
   - CTA: `👉 Hubungi di DM TikTok`
2. **Contoh 1 (Pink Sakura Kawaii):**
   - Animasi donasi aktif: Rp50.000 dari Anya_Chan
   - Pesan: *"Mau custom alert seperti ini? Bisa hubungin di DM TikTok saja! ✨"*
   - Label penjelas: `Contoh: Sakura Kawaii`
3. **Contoh 2 (Cyberpunk Neon):**
   - Animasi HUD laser: Rp100.000 dari CyberSamurai_99
   - Pesan: *"Tersedia 22+ tema keren! Bisa hubungin di DM TikTok saja untuk pemesanan!"*
   - Label penjelas: `Contoh: Cyberpunk Neon`

---

## ⚙️ Kustomisasi Teks & Pengaturan

### A. Lewat Form Simulator di Browser
Buka file `overlay-promo/index.html` langsung di browser Anda. Di bagian bawah terdapat panel kontrol untuk:
- Mengubah teks promosi (misal: ganti akun DM atau link bio).
- Memilih urutan (hanya pink atau kombinasi dengan cyberpunk).
- Mengatur durasi waktu tampil (misal tiap 6 detik berganti).
- Menekan tombol **Salin URL OBS** untuk langsung mendapatkan tautan siap pakai.

### B. Lewat Parameter URL di OBS / TikTok Live Studio
Anda dapat langsung mengatur teks pada kolom URL Browser Source:

| Parameter | Fungsi | Contoh Nilai |
|---|---|---|
| `overlay=1` | Mengaktifkan mode transparan khusus streaming | `1` |
| `promo` | Mengubah teks promosi utama | `Mau+custom+alert+seperti+ini...+Bisa+hubungin+di+DM` |
| `cta` | Mengubah tombol ajakan kontak | `👉+DM+Instagram+%40namaakun` |
| `dur` | Durasi tiap tampilan (dalam detik) | `6` |
| `seq` | Pilihan urutan tampilan | `promo-pink-cyber` atau `promo-pink-only` |

---

## 🚀 Panduan Pemasangan

### Di OBS Studio
1. Pada menu **Sources**, klik **`+`** lalu pilih **Browser**.
2. Centang **Local file**, klik **Browse**, dan pilih file `overlay-promo/index.html`.
3. Atur **Width**: `650` dan **Height**: `250`.
4. Centang:
   - ✅ *Shutdown source when not visible*
   - ✅ *Refresh browser when scene becomes active*
5. Klik **OK**.

### Di TikTok Live Studio
1. Klik **Add Source** -> Pilih **Web / Browser Source**.
2. Masukkan path file lokal atau URL lokal (contoh: `http://localhost:3000/overlay-promo/index.html?overlay=1`).
3. Sesuaikan ukuran dan letakkan di sudut bawah atau atas canvas streaming TikTok.
