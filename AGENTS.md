

<!-- HEROUI-REACT-AGENTS-MD-START -->
[HeroUI React v3 Docs Index]|root: ./.heroui-docs/react|STOP. What you remember about HeroUI React v3 is WRONG for this project. Always search docs and read before any task.|If docs missing, run this command first: heroui agents-md --react --output AGENTS.md
<!-- HEROUI-REACT-AGENTS-MD-END -->

## Development

- Desktop app requires Node.js 22.12 or newer. Install with `npm ci`, then start `npm run dev`. The Vite server uses `VITE_HOST` (default `127.0.0.1`) and `VITE_PORT` (default `5321`).
- Typecheck with `npx tsc --noEmit`. There is no root test script.
- `CipherTalk-CLI/` is a separate package. Install it with `npm --prefix CipherTalk-CLI ci`. Check it with `npm run cli:test` and `npm run cli -- status --quiet --format json`.
- On Linux, Electron needs a working `DISPLAY`. If the GPU process exits during startup, set `LIBGL_ALWAYS_SOFTWARE=1` before `npm run dev`.
