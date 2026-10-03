# TENTA Web

Website company profile untuk TENTA, agensi digital marketing di Jakarta, dengan panel admin untuk mengelola konten situs.

## Fitur

- Halaman publik: layanan, studi kasus, industri, harga, proses kerja, testimoni, FAQ, kontak
- Panel admin dengan autentikasi NextAuth
- Manajemen konten: layanan, studi kasus, harga, testimoni, FAQ, logo klien, statistik, langganan newsletter
- Form kontak dan langganan newsletter
- Seed data database via Prisma

## Tech Stack

- Next.js (App Router), React, TypeScript
- Prisma + MySQL
- NextAuth
- Tailwind CSS
- PM2 untuk proses production (ecosystem.config.js)

## Cara Menjalankan

```bash
npm install
npx prisma generate
npx prisma db seed
npm run dev
```

Buka http://localhost:3000.

Build untuk production:

```bash
npm run build
npm run start
```

## Lisensi

MIT. Lihat [LICENSE](LICENSE).
