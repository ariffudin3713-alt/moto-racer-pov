# Moto Racer POV

Game balapan motor 2D dengan sudut pandang orang pertama (pseudo-3D / OutRun style).
Dibuat sebagai tugas sekolah dalam satu file HTML: `game_balapan_motor_2d.html`.

## Fitur

- Sudut pandang pembalap (kokpit, stang motor, spion, kaca spion)
- Jalan berkelok dengan tanjakan/turunan, langit senja
- Lalu lintas mobil & truk, koin emas, bonus nyaris tabrakan
- Nitro, speedometer analog, HUD skor/jarak/koin
- Suara mesin, koin, nitro, dan tabrakan (bisa dimatikan)
- Layar mulai, hitungan mundur, jeda, dan layar tabrakan
- Rekor skor & jarak tersimpan di browser (localStorage)
- Kontrol keyboard + tombol sentuh untuk HP

## Kontrol

| Tombol | Fungsi |
| --- | --- |
| `W` / `↑` | Gas / ngebut |
| `S` / `↓` | Rem |
| `A` `D` / `←` `→` | Belok kiri / kanan |
| `SPACE` / `SHIFT` | Nitro |
| `P` / `ESC` | Jeda |
| `M` | Suara on/off |
| `ENTER` | Mulai |

Tanpa gas, motor tetap melaju santai (±70% kecepatan maksimum).

Di HP tersedia tombol **KIRI / NITRO / KANAN** dan **GAS / REM** di bawah layar.

## Menjalankan

Buka `game_balapan_motor_2d.html` di browser. Halaman memakai Tailwind CSS dan Google Fonts
dari CDN, jadi butuh koneksi internet.

## Deploy

Proyek ini statis dan siap di-deploy ke Vercel. `vercel.json` mengarahkan halaman utama `/`
ke `game_balapan_motor_2d.html`.
