---
name: rakit-video-reels
description: Merender suara narasi Indonesia & Arab via edge-tts lalu menggabungkan gambar dan teks menggunakan FFmpeg menjadi video vertikal 1080x1920.
---

# Instruksi Perakitan Video Reels Otomatis

Gunakan skrip Python dengan library `edge-tts` dan `ffmpeg` untuk menghasilkan video akhir:
1. **Audio Suara (TTS)**:
   - Gunakan suara pria Indonesia natural (`id-ID-ArdiNeural`) untuk dialog/narasi bahasa Indonesia.
   - Gunakan suara pria Arab fasih (`ar-SA-HamedNeural`) untuk pembacaan bait *Alfiyah Ibnu Malik*.
2. **Animasi & Teks (FFmpeg)**:
   - Ubah gambar adegan menjadi klip bergerak halus (*slow zoom-in / Ken Burns effect*) berukuran `1080x1920` (30 fps).
   - Tempelkan teks Arab berharakat dan terjemahan bahasa Indonesia secara jelas di tengah/bawah layar menggunakan font yang mendukung huruf Arab (seperti Amiri atau Scheherazade).
3. **Hasil Akhir**: Gabungkan seluruh klip audio dan visual menjadi satu file MP4 di `output/episode-[nomor]-final.mp4`.
4. 
