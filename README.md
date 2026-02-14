# WhatsApp UTM Builder

Tiny static site: paste a URL → get the same URL with:

- `utm_source=whatsapp`
- `utm_medium=status`

## Deploy to Vercel

1) Push this folder to GitHub
2) In Vercel: **New Project** → import repo
3) Framework preset: **Other**
4) Build/Output: none needed (static)

`vercel.json` already configures static hosting.

## Notes

- Preserves existing query params.
- Overwrites existing `utm_source` / `utm_medium` if present.
