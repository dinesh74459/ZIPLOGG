# ZIPLOGG

Website source and backend handoff for https://ziplogg.com.

## Start locally
Install Node.js, then run `npm ci` and `npm run dev`. Open http://127.0.0.1:4173.
Run `npm run check` and `npm test` for local checks.

## Project layout
- dist/: authored website files and public assets (not disposable build output)
- lib/: shared application logic
- scripts/: local server and build/check utilities
- supabase/: backend functions and database migrations
- tests/: automated checks and SQL verification scripts

Read FULFILLMENT-STATUS.md in chronological order; later entries supersede earlier ones. CLAUDE-HANDOFF.txt is an earlier handoff and may be superseded by the status file.

This source archive does not grant access to hosted services, transfer browser sessions, or include server credentials. Configure server secrets only in the appropriate provider settings. Never put them in the website or commit them to GitHub. Production payment readiness must be verified separately from local tests.

Excluded: Git history, node_modules, editor settings, browser screenshots, environment files, and deployment archives.
