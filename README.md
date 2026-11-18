# Kalkulator Modal UMKM

PWA (Progressive Web App) kalkulator modal jualan untuk UMKM. Bisa di-install di HP seperti aplikasi native.

## Fitur
- Hitung modal, harga jual, keuntungan, margin
- Simpan riwayat perhitungan (localStorage)
- Offline-ready (Service Worker)
- Installable sebagai PWA (Add to Home Screen)
- Responsif mobile/desktop

## Akses

**Tailnet (HTTPS, bisa install PWA):**
```
https://degofood-2.tail9040f1.ts.net/umkm/
```

**Lokal di server:**
```
http://127.0.0.1:8805/
```

Service: `python3 -m http.server 8805 --bind 127.0.0.1` di folder ini, diproksikan
lewat `tailscale serve --https=443 --set-path=/umkm`.

## Deploy
File statis `index.html` — taruh di hosting statis mana pun (Netlify, Vercel, Cloudflare Pages, GitHub Pages, nginx).
