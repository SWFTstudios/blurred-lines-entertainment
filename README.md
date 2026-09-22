# Blurred Lines Entertainment

Static website for Blurred Lines Entertainment, hosted on Cloudflare Workers.

- **Site**: HTML/CSS/JS/images served via Workers Static Assets from `public/`
- **Videos**: Stored in R2 bucket `ble-media`, served at `/videos/*`
- **Deploy**: Workers Builds on push to `main`, or `npm run deploy`

Production: https://blurred-lines-entertainment.elombe.workers.dev
