# Data ketersediaan — Reva Group

Cache publik `availability.json` (jadwal ketersediaan slot Rawdah yang memang
tampil di situs). Diperbarui otomatis tiap ±10 menit oleh GitHub Actions dari
API publik situs, lalu diterbitkan ke branch `data`.

Dipakai `revagroup.co.id` sebagai **fallback** bila API utamanya tidak
terjangkau. Tidak ada kredensial atau data pribadi apa pun di repo ini.
