# NIMBUS — Product List

Project React untuk tantangan **Day 01 — React Fundamentals**: membuat aplikasi **Product List**.

Repo ini berisi fondasi project (React + Vite + lint) sebelum fitur katalog dan keranjang diimplementasikan.

## Tech Stack

| Kategori | Teknologi |
| --- | --- |
| UI | React 19 |
| Build tool | Vite 8 |
| Linting | Oxlint |

## Menjalankan Proyek

Prasyarat: Node.js `^20.19.0` atau `>=22.12.0`.

```bash
npm install
npm run dev
```

Dev server tersedia di `http://localhost:5173`.

## Scripts

| Perintah | Fungsi |
| --- | --- |
| `npm run dev` | Menjalankan development server |
| `npm run build` | Membuat production build ke `dist/` |
| `npm run preview` | Meninjau hasil build secara lokal |
| `npm run lint` | Menjalankan Oxlint |

## Struktur Proyek

```text
.
├── public/
│   └── favicon.svg
├── src/
│   ├── App.jsx      # Komponen utama
│   ├── index.css    # Reset dan design token
│   └── main.jsx     # Entry point React
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Lisensi

Dibuat untuk keperluan pembelajaran pada tantangan Day 01 React Fundamentals.
