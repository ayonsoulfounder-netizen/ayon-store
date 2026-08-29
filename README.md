AYONZ STORE
Website toko digital untuk jualan akses/aplikasi digital. Dark, Neo-Brutalism, mobile-first. Vanilla HTML/CSS/JS dijalankan lewat Vite, siap deploy ke Vercel.
Struktur Folder

ayonz-store/
├── public/
│   └── assets/
│       ├── logo.png        ← logo Ayonz Store
│       ├── holow.png       ← icon produk Holow Execution
│       ├── voltage.png     ← icon produk Voltage Death
│       ├── megumin.png     ← icon produk Megumin Crasher
│       ├── qris.png        ← QRIS pembayaran (dipakai di payment modal)
│       ├── donation.png    ← gambar section donasi
│       └── music.mp3       ← background music (floating player)
│
├── src/
│   ├── styles/
│   │   └── main.css        ← semua styling (design tokens di :root)
│   ├── scripts/
│   │   └── app.js          ← render produk, modal, music player, dll
│   └── data/
│       └── products.js     ← data produk & harga (edit di sini aja)
│
├── index.html
├── package.json
├── vite.config.js
├── vercel.json
└── .gitignore

Jalankan di Lokal
Butuh Node.js (versi 18 ke atas disarankan).

npm install
npm run dev

Buka URL yang muncul di terminal (biasanya http://localhost:5173).
Build untuk Production

npm run build

Hasil build ada di folder dist/. Bisa dicek dulu sebelum deploy:

npm run preview
