# Faded Perfection Barbershop

Single-page website for Faded Perfection Barbershop — Springfield, MO.

Unofficial sample site. Details come from public listings and may be out of date.
Not affiliated with the shop.

## Stack

Plain HTML, CSS and a little vanilla JavaScript. No build step, no dependencies.

## Local preview

Double-click `index.html` to open it in your browser.

## Deploy on Vercel

1. Go to [vercel.com/new](https://vercel.com/new).
2. Import this GitHub repository.
3. Framework preset: **Other**. Build command: none. Output directory: `.`
4. Deploy.

Vercel serves `index.html` from the root automatically, so no configuration file is needed.

## Editing

Everything lives in `index.html`:

- Shop details (address, phone) are in the hero and the "Find us" section.
- Colors are CSS variables in `:root` (`--lime`, `--black`, `--bone`).
- The fade guide buttons drive `--pos` on the preview head.
