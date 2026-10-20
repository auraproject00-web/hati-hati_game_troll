# Hati Hati

Game platformer troll 20 level dengan karakter Helm Kuning. Satu file HTML (Canvas 2D + JavaScript murni), tanpa build step.

## Main
Buka `index.html` di browser. Kontrol: tombol ◀ ▶ ▲ di layar, atau keyboard ← → / A D dan Spasi / ↑ / W.

## Deploy ke Vercel
1. Push folder ini ke repo GitHub.
2. Di vercel.com → Add New → Project → import repo-nya.
3. Framework Preset: **Other**, tanpa build command. Klik Deploy.

## Struktur kode (di dalam index.html)
- `LEVELS` — data 20 level (peta + jebakan)
- `update()` — fisika, jebakan, mati/menang
- `draw()` — gambar level, karakter, HUD
