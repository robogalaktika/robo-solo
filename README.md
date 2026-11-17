# Robo Solo Synth

Synth solo berbasis oscillator untuk mengisi solo saat manggung bareng band (dibuat untuk Robo Galaktika: new wave & synth pop 80an). Jalan di browser HP, tanpa install dari store.

## Fitur

- **Ribbon fretless**: geser kiri-kanan untuk pindah nada, atas-bawah untuk mengatur kecerahan filter. Yang muncul hanya nada dari scale yang dipilih.
- **12 nada dasar** dan **22 scale**: Natural Minor, Dorian, Phrygian, Harmonic Minor, pentatonik, blues, mode, jazz, sampai pendekatan Pelog/Slendro.
- **8 sound**: PWM Lead, Scream Lead, Poly Saw, FM Bell, FM Brass, Mono Lead Resonan, Glass, Theremin Sine.
- **Snap nada**: Kuat, Ekspresif (goyang jari = vibrato, geser = bend), Lepas (fretless).
- **Efek**: glide, vibrato otomatis, chorus, delay ikut tempo (dengan tap tempo), reverb.
- **Tampilan**: oscilloscope besar sebagai latar.
- **Lainnya**: pengaturan tersimpan otomatis di perangkat.

## Online-kan dengan GitHub Pages

1. Buat repo baru di GitHub, misalnya `robo-solo`.
2. Upload semua file di folder ini ke repo (drag & drop di halaman repo → **Add file → Upload files**).
3. Buka **Settings → Pages**, lalu pada *Source* pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, dan simpan.
4. Tunggu 1–2 menit. Aplikasinya ada di `https://<username>.github.io/robo-solo/`.

## Pasang di HP

Buka alamat tadi di Chrome (Android) atau Safari (iPhone), lalu pilih **Tambahkan ke layar utama**. Aplikasi akan terbuka layar penuh dalam mode landscape.

## Tips manggung

- Sambungkan ke mixer atau DI box dengan kabel (jack 3.5mm atau adaptor USB-C). Jangan pakai Bluetooth karena delay-nya terlalu besar.
- Matikan notifikasi dan mode hemat baterai supaya suara tidak terputus.
- Coba latency di HP kamu sebelum manggung.

## File

| File | Fungsi |
|---|---|
| `index.html` | Seluruh aplikasi (HTML, CSS, JS, Web Audio) |
| `manifest.webmanifest` | Data untuk "Tambahkan ke layar utama" |
| `icon-192.png`, `icon-512.png` | Ikon aplikasi |
| `.nojekyll` | Supaya GitHub Pages menyajikan file apa adanya |
