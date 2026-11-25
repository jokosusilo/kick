# AGENTS.md

Static HTML starter: Parcel 2 and Tailwind CSS 4. No application JavaScript.

## Conventions
- Use pnpm, not npm or yarn. `pnpm-lock.yaml` is the only lockfile.
- Tailwind 4 is configured in CSS (`src/style.css`). There is no `tailwind.config.js`.
- PostCSS loads Tailwind through `.postcssrc`.
- `pnpm-workspace.yaml` blocks dependency install scripts.
- Follow `.editorconfig`.

## Verification
- `pnpm run build`

There are no tests and no linter. Check visual changes in a browser with `pnpm run start`.
