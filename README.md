# Kick
> A simple html starter using parcel and tailwindcss.

## Requirements
- Node.js 24 or later (`.nvmrc` selects 24)
- pnpm 11 (the exact version is in `package.json`)

## How to use
```
pnpm install
pnpm run start
```
The dev server prints its local URL. Edit the files in `src/`.

## Build
```
pnpm run build
```
The output goes to `dist/`.

## Structure
```
src/index.html    page markup and meta tags
src/style.css     Tailwind entry point
src/favicon.svg   favicon
```

## After you copy this starter
- Change the name and description in `package.json`.
- Change the title, description and social meta tags in `src/index.html`.
- Replace `src/favicon.svg`.
- Add an `og:image` meta tag with an absolute URL, if you want a social preview image.

## License
[MIT](LICENSE)
