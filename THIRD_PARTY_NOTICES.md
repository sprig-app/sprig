# Third-party components

Sprig’s application code is an original implementation. The public add-on resource shapes and Jellyfin compatibility patterns informed its design; no Trellis or Remux application code is included.

- Bun 1.3.14, MIT and bundled component licenses: https://github.com/oven-sh/bun/blob/bun-v1.3.14/LICENSE.md. Standalone executables contain Bun and JavaScriptCore. Its complete bundled license notice is in `docs/licenses/BUN-LICENSE.md`.
- ipaddr.js 2.3.0, MIT: `docs/licenses/IPADDR-LICENSE`.
- Source Sans 3, SIL Open Font License 1.1: `docs/licenses/SOURCE-SANS-OFL.txt`. Font files are bundled locally; the interface does not fetch fonts from a third party.

Playwright and TypeScript are development dependencies, not runtime requirements for packaged users. Docker distributions use the separately licensed Bun base image. Optional Caddy runs as a separate service under its Apache 2.0 license.
