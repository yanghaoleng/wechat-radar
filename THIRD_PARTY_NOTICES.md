# Third-party and upstream notices

## WeChat Radar upstream release

- Source: [zjp1997720/wechat-radar](https://github.com/zjp1997720/wechat-radar)
- Verified upstream revision: [de7ec99fed90ba3c5644fbe1ac233ff981cc53f7](https://github.com/zjp1997720/wechat-radar/tree/de7ec99fed90ba3c5644fbe1ac233ff981cc53f7)
- Original notice: Copyright (c) 2026 WeChat Radar contributors
- License: MIT
- Complete, unchanged upstream text: [licenses/WECHAT-RADAR-UPSTREAM-MIT.txt](licenses/WECHAT-RADAR-UPSTREAM-MIT.txt)
- Original license at the verified revision: [LICENSE](https://github.com/zjp1997720/wechat-radar/blob/de7ec99fed90ba3c5644fbe1ac233ff981cc53f7/LICENSE)

This notice preserves the license already supplied with the upstream software
and associated documentation. It is not a new license grant for this fork.
The retained MIT notice applies to upstream-authored material inherited from
the revision above, including retained upstream portions of subsequently
modified files. It does not automatically license later additions, third-party
dependencies, trademarks, or other materials whose rights are held separately.
The existing noncommercial statements do not replace the upstream copyright
and permission notice or withdraw rights already granted for that MIT release.

## Verified inheritance

Comparison baseline for this record: [79547dd7416001fd24b934a46f46920a61a93011](https://github.com/yanghaoleng/wechat-radar/tree/79547dd7416001fd24b934a46f46920a61a93011).

[Git history comparison](https://github.com/yanghaoleng/wechat-radar/compare/de7ec99fed90ba3c5644fbe1ac233ff981cc53f7...79547dd7416001fd24b934a46f46920a61a93011)
shows that the upstream revision is an ancestor of the baseline, with two
subsequent commits. Comparing the complete Git trees gives:

- 81 files with exactly the same Git blob SHA at the same path.
- Five changed existing files: `LICENSE`, `PRIVACY.md`, `README.md`,
  `SECURITY.md`, and `package.json`.
- One added file: `DISCLAIMER.md`.
- No deleted upstream files.

The runtime source under `app/`, `components/`, `lib/`, and `scripts/`
is unchanged in that comparison. The upstream MIT license was replaced in
the root file; its original text is now preserved separately at the path above.
The later root license, added disclaimer, and new portions of edited documents
are not represented here as part of the earlier MIT release.

The list below records file provenance, not a guarantee of ownership or a
license grant for third-party assets or dependencies. Any separately applicable
third-party notices remain in effect.

### Identical inherited files at the comparison baseline

- `.env.example`
- `.gitignore`
- `app/api/ai-classify/route.ts`
- `app/api/daemon/route.ts`
- `app/api/dates/route.ts`
- `app/api/dbinfo/route.ts`
- `app/api/group-tags/route.ts`
- `app/api/group/[id]/route.ts`
- `app/api/groups/route.ts`
- `app/api/mentions/route.ts`
- `app/api/message-links/backfill/route.ts`
- `app/api/message-links/raw/route.ts`
- `app/api/message-links/resolve/route.ts`
- `app/api/new-messages/route.ts`
- `app/api/recover/route.ts`
- `app/api/rescan/route.ts`
- `app/api/search/route.ts`
- `app/api/sessions/route.ts`
- `app/api/setup/route.ts`
- `app/api/stats/route.ts`
- `app/api/topics/[id]/route.ts`
- `app/api/topics/links/route.ts`
- `app/api/topics/route.ts`
- `app/api/wx-image/route.ts`
- `app/classify/page.tsx`
- `app/favicon.ico`
- `app/globals.css`
- `app/groups/[id]/page.tsx`
- `app/groups/page.tsx`
- `app/layout.tsx`
- `app/links/page.tsx`
- `app/mentions/page.tsx`
- `app/page.tsx`
- `app/reports/groups/[id]/page.tsx`
- `app/setup/page.tsx`
- `app/signals/page.tsx`
- `app/topics/page.tsx`
- `components/ActiveGroupsList.tsx`
- `components/CategoryChart.tsx`
- `components/GlobalSearch.tsx`
- `components/IntelligenceBrief.tsx`
- `components/MessageContent.tsx`
- `components/NewGroupModal.tsx`
- `components/Sidebar.tsx`
- `components/StatGrid.tsx`
- `components/ThemeToggle.tsx`
- `components/TopBar.tsx`
- `components/TrendChart.tsx`
- `docs/assets/product-preview.svg`
- `eslint.config.mjs`
- `lib/cache.ts`
- `lib/config.ts`
- `lib/dashboard-intelligence.ts`
- `lib/db.ts`
- `lib/demo-data.ts`
- `lib/group-classifier.ts`
- `lib/groups.ts`
- `lib/link-intelligence.ts`
- `lib/mentions.ts`
- `lib/message-links.ts`
- `lib/messages-store.ts`
- `lib/range.ts`
- `lib/stats-aggregator.ts`
- `lib/topics.ts`
- `lib/wx-image.ts`
- `lib/wx-types.ts`
- `lib/wx.ts`
- `next-env.d.ts`
- `next.config.ts`
- `pnpm-lock.yaml`
- `pnpm-workspace.yaml`
- `postcss.config.mjs`
- `public/file.svg`
- `public/globe.svg`
- `public/next.svg`
- `public/vercel.svg`
- `public/window.svg`
- `scripts/backfill_empty_groups.cjs`
- `scripts/backup-cockpit-db.mjs`
- `scripts/seed_demo.cjs`
- `tsconfig.json`

## Redistribution

When copying or redistributing the upstream software or substantial portions,
retain its copyright notice and complete MIT permission and warranty text.
Check the existing project terms and any separately applicable third-party
terms for material outside that upstream scope.
