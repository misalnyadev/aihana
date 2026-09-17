# 🎬 Checkpoint Plan — Studio Film Animasi AiHana

> **Status: DITUNDA (menunggu dukungan/donasi).**
> Rencana ini dijalankan **saat dukungan mulai berdatangan**, karena butuh
> API model video berbayar. Semua fitur AiHana yang ada sekarang tetap **gratis**.

---

## 🎯 Tujuan
Menambah menu **🎬 Studio Film** supaya anak SD bisa berkreasi membuat **film
animasi pendek** untuk pelajaran **SBdP & Prakarya** — dari ide → gambar →
gerak → film jadi yang bisa disimpan & dibagikan.

---

## 💡 Kenapa ditunda dulu?
- Model video AI (mis. **Seedance**, Kling, Runway, Pika, dsb.) **berbayar** —
  butuh API Key berbayar / kredit.
- Fitur ini akan didanai dari **menu 💝 Dukung** (donasi QRIS). Begitu dana cukup
  untuk beli kredit AI premium, checkpoint ini dieksekusi.

---

## 🧩 Rencana Bertahap (checkpoint)

### Tahap 1 — Storyboard (murah/gratis, bisa duluan)
- [ ] Anak menulis **ide cerita** (judul + beberapa adegan).
- [ ] Tiap adegan dibuatkan **gambar** (pakai generator gambar yang sudah ada di Studio).
- [ ] Susun jadi **storyboard** (urutan gambar + teks narasi) — bisa dicetak.
- [ ] Tambah **narasi suara** memakai TTS maskot yang sudah ada.
- 📌 *Tahap ini bisa dikerjakan tanpa biaya karena memakai fitur gambar & suara
  yang sudah tersedia.*

### Tahap 2 — Animasi Sederhana (tanpa model video berbayar)
- [ ] "Slideshow bergerak": gambar storyboard + transisi + gerak Ken Burns (zoom/pan).
- [ ] Sinkron dengan narasi TTS + musik latar sederhana.
- [ ] Ekspor sebagai video (WebCodecs / rekam canvas) — semua di sisi browser.
- 📌 *Masih gratis; hasil sudah terasa seperti "film" untuk tugas sekolah.*

### Tahap 3 — Film Animasi AI (butuh dukungan/dana) 🎬
- [ ] Integrasi model **text-to-video / image-to-video** (Seedance / sejenisnya).
- [ ] Dari 1 gambar adegan → klip bergerak singkat (beberapa detik).
- [ ] Gabungkan klip antar-adegan jadi satu film utuh + narasi + musik.
- [ ] Pilihan gaya: kartun, cerita rakyat, sains, dll (cocok SBdP/Prakarya).
- 📌 *Tahap inilah yang menunggu dukungan karena memakai API berbayar.*

---

## 🛠️ Catatan Teknis (untuk nanti)
- **Pola integrasi**: ikuti gaya Studio Mewarnai yang sudah ada
  (`window.mwInit`, generator gambar Pollinations) + rotasi API Key seperti chat.
- **Keamanan anak**: filter prompt, watermark opsional, tanpa data pribadi.
- **Simpan lokal**: proyek film tersimpan di `localStorage` (konsisten dgn app).
- **Ekspor**: MP4/WebM untuk dikumpulkan ke guru.
- **Biaya**: pakai kredit dari donasi; tampilkan indikator kuota agar terkontrol.
- **Fallback**: kalau kredit habis → otomatis mundur ke Tahap 2 (slideshow) yang gratis.

---

## ✅ Definisi "Siap Dijalankan"
1. Dukungan/donasi masuk cukup untuk membeli kredit model video.
2. Pilih penyedia video (Seedance sebagai kandidat utama) + uji API.
3. Kerjakan Tahap 1 & 2 lebih dulu (gratis) sambil menunggu, lalu Tahap 3.

---

## 📌 Ide Lain yang Ditampung (backlog)
- 🖍️ Warna pensil di Studio selain hitam (beberapa warna crayon).
- 🧑‍🏫 Fitur khusus atas permintaan guru (menyesuaikan kebutuhan kelas/sekolah).

---

*Disimpan sebagai checkpoint oleh tim AiHana. Jalankan saat dukungan tiba. 🙏*
*🦉 💛 🐱*
