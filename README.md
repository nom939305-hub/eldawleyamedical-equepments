# EL Dawlya Medical Equipment Catalog

A mobile-first Arabic-first catalog and quote request MVP for EL Dawlya.

## Run locally

Open `index.html` directly, or serve the folder with any static server.

## Supabase setup

1. Run `supabase/schema.sql` in the Supabase SQL editor.
2. In `app.js`, set `SUPABASE_URL` and `SUPABASE_ANON_KEY`.
3. Add product rows using the admin screen or Supabase dashboard.
4. Create a Storage bucket named `product-images` when image upload is enabled.

The app ships with ten local sample products so the catalog, detail pages, cart, and admin preview work before Supabase is configured. Cart data persists in `localStorage` under `eldawlya_quote_cart`.
