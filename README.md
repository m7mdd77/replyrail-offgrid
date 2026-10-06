# ReplyRail

New functional prototype created October 5, 2026 for OFFGRID. A local order follow-up queue for small community sellers: unresolved promises are prioritized, updates carry a history, and manually copied drafts never send themselves.

## Run

Node.js 22+:

```sh
npm ci
npm test
npm run check
npm start
```

Open http://127.0.0.1:3240 . Assets run locally after installation. Use synthetic examples for judging. There is no remote service, AI inference, messaging integration or payment processing. No fees charged or earnings claimed.

## Scope and limitations

- Search and status filters; next-action deadlines; exact integer BHD amounts.
- New/edit orders, action history, text-only follow-up drafts, JSON backup/restore.
- Restore validates every record before replacing any order, with explicit user confirmation.
- Browser storage is **not encrypted** and cannot defend against malicious local software. Use customer labels instead of private customer data. Backups are unencrypted; handle privately.
- Separate browser profiles/origins have separate workspaces. No multi-user sync or storage-durability guarantee. Export backups.
- Ranking follows oldest unresolved promise, not a machine-learning prediction.
- Synthetic example records do not demonstrate merchant adoption or real business impact.

## Provenance

Built from a new mission folder, not a renamed Clearledger prototype. Substantial Codex AI assistance. Lucide 0.468.0 provides icons (its own license applies). No prior private customer records, credentials or account transactions included. Broader community-problem competition suitability is under review; no external submission is claimed by this README.
