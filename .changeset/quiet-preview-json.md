---
"wrangler": patch
---

Keep `wrangler preview --json` stdout parseable during configuration loading, builds, and asset uploads

JSON mode now suppresses informational and build-progress logs throughout the command lifecycle while preserving warnings and errors on stderr. The final Preview response remains the only output on stdout, including when using redirected configurations and static assets.
