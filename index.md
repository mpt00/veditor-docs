---
title: Kebijakan Privasi VEDITOR
---

# Kebijakan Privasi — VEDITOR

**Berlaku sejak:** 8 Oktober 2026
**Aplikasi:** VEDITOR (`id.forge.veditor`) untuk Android
**Pengembang:** Hadi — Indonesia
**Kontak:** alhadi.uc@gmail.com

## 1. Ringkasan
VEDITOR adalah aplikasi penyuntingan foto dan video yang bekerja **di perangkat Anda**. Aplikasi ini tidak memiliki akun pengguna, tidak memiliki server milik pengembang, tidak memasang iklan, dan tidak memakai layanan analitik pihak ketiga. Kami tidak menjual atau membagikan data pribadi Anda kepada siapa pun.

## 2. Data yang diproses
- **Kamera dan mikrofon**: hanya saat Anda sendiri menekan tombol rekam/ambil foto. Hasil rekaman disimpan di penyimpanan perangkat Anda.
- **Foto, video, dan audio dari galeri**: hanya berkas yang Anda pilih sendiri untuk disunting.
- **Lokasi (perkiraan dan presisi)**: hanya saat Anda mengaktifkan fitur peta/GPS atau Geo Overlay. Koordinat dipakai untuk menampilkan peta dan menempelkan keterangan lokasi ke hasil foto/video.
- **Data cuaca**: aplikasi meminta informasi cuaca untuk koordinat lokasi Anda bila fitur peta aktif.
- **Kunci API layanan AI (opsional)**: bila Anda memakai fitur AI, Anda memasukkan kunci API milik Anda sendiri. Kunci disimpan **terenkripsi di perangkat** dan tidak pernah dikirim kepada pengembang.

## 3. Ke mana data dikirim
- Secara bawaan, seluruh penyuntingan dan pengenalan wajah/objek berjalan **di perangkat** (ML Kit berjalan lokal; model ML Kit dapat diunduh dari server Google).
- **Hanya bila Anda mengaktifkan fitur AI**, permintaan Anda dikirim langsung dari perangkat Anda ke penyedia yang Anda pilih, memakai kunci API Anda sendiri:
  - Google Gemini (`generativelanguage.googleapis.com`) — pembuatan teks, analisis, dan pembuatan gambar/video.
  - Google Veo / Google Labs (`labs.google`) — pembuatan video AI, bila Anda mengaktifkannya.
  - Hugging Face (`router.huggingface.co`) — model AI alternatif, bila Anda memilihnya.
- Peta dan ubin peta: OpenStreetMap (`tile.openstreetmap.org`). Cuaca: Open-Meteo (`api.open-meteo.com`). Aset stiker: GitHub (`raw.githubusercontent.com`).
- Data tersebut diproses oleh penyedia masing-masing menurut kebijakan privasi mereka. Kami tidak menerima salinan data Anda.

## 4. Penyimpanan dan retensi
- Proyek, hasil ekspor, cache render, dan pengaturan disimpan **di perangkat Anda**.
- Menghapus data aplikasi atau menghapus pemasangan aplikasi akan menghapus seluruh data tersebut. Kami tidak menyimpan salinan apa pun.
- Berkas yang Anda bagikan ke aplikasi lain (misalnya ke WhatsApp atau media sosial) tunduk pada kebijakan aplikasi tujuan.

## 5. Izin yang diminta
- Kamera, mikrofon, dan notifikasi: untuk perekaman dan pemberitahuan proses.
- Foto/video/audio (Android 13+): untuk membaca berkas yang Anda pilih.
- Lokasi: untuk fitur peta dan Geo Overlay.
Setiap izin diminta saat fitur terkait dipakai dan dapat Anda tolak atau cabut dari Pengaturan Android.

## 6. Anak-anak
VEDITOR tidak ditujukan untuk anak di bawah 13 tahun dan tidak dengan sengaja mengumpulkan data dari anak-anak.

## 7. Konten yang dihasilkan AI
Hasil fitur AI dapat keliru. Pengguna bertanggung jawab atas konten yang dibuat dan dibagikan. Aplikasi menyediakan sarana untuk melaporkan konten AI yang tidak pantas melalui menu **Laporkan konten AI** di dalam aplikasi.

## 8. Keamanan
Komunikasi jaringan memakai HTTPS. Kunci API dan pengaturan sensitif disimpan terenkripsi di perangkat dan dikecualikan dari pencadangan otomatis.

## 9. Hak Anda
Karena kami tidak menyimpan data Anda, permintaan akses, koreksi, atau penghapusan data dapat Anda lakukan langsung di perangkat dengan menghapus berkas atau data aplikasi. Untuk pertanyaan lain, hubungi alhadi.uc@gmail.com.

## 10. Perubahan kebijakan
Bila kebijakan ini berubah, tanggal berlaku di atas akan diperbarui dan versi terbaru selalu tersedia di halaman ini.
