# HD Maker

Website statis untuk memperbesar (sampai 4K) dan mempertajam foto atau video. Semua diproses di browser, tanpa server dan tanpa build.

## Deploy ke Vercel
1. Upload isi folder ini ke repo GitHub (file `index.html` harus ada di root repo).
2. Di Vercel: Add New Project, pilih repo, Framework Preset: **Other**.
3. Kosongkan Build Command dan Output Directory, lalu klik Deploy.

## Catatan
- Foto: hasil disimpan sebagai PNG, JPG, atau WebP.
- Video: diproses sepanjang durasinya (real-time). Biarkan tab tetap terbuka. Hasil MP4 (Chrome/Edge/Safari terbaru) atau WebM.
- Video: hasil maksimal 1080p (pilihan 1080p atau 720p) dengan frame rate 60 atau 30 fps. Jika video asli 30 fps, frame digandakan agar file menjadi 60 fps.
- Kalau proses terasa berat, pilih 720p atau 30 fps dan tutup tab lain.
