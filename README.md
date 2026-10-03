# RAF Finance V1

Aplikasi keuangan pribadi berbasis React + Vite + Supabase.

## Fitur
- Login / daftar akun
- Dashboard saldo
- Pemasukan dan pengeluaran
- Kategori
- Rekening / dompet
- Riwayat transaksi
- Pencarian transaksi
- Statistik pengeluaran
- Responsive untuk HP
- Data tersimpan online di Supabase

## Menjalankan
1. Install Node.js LTS.
2. Salin `.env.example` menjadi `.env`.
3. Isi `VITE_SUPABASE_URL` dan `VITE_SUPABASE_ANON_KEY`.
4. Buat project Supabase.
5. Jalankan seluruh `supabase/schema.sql` di SQL Editor Supabase.
6. Di terminal:
   `npm install`
   `npm run dev`
7. Buka URL yang diberikan Vite, biasanya `http://localhost:5173`.

## Build
`npm run build`

## Catatan
Jangan masukkan service_role key Supabase ke `.env` frontend. Gunakan anon/publishable key dan RLS seperti pada schema.sql.
