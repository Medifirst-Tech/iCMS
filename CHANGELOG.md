# Changelog — Medifirst CMS

## [v1.3.1] — 2026-04-14
### Fixed
- Corrected Claude model names: claude-haiku-4-5 and claude-sonnet-4-5
- 20 Haiku + 10 Sonnet calls updated

---
## [v1.3.0] — 2026-04-13
### Added
- Finance Module (#5) — Expense tracking, Receipt Intelligence, Ledger, Accountant View
- Receipt photo upload with AI extraction (supplier/date/amount/SST/category)
- Drug invoice auto-match to INV_DRUGS inventory
- CSV export (full + claimable-only)
- Finance nav item with pending-receipts badge
- Consultation Fee Matrix — configurable per visit type × patient tier
- "Show at Reg" toggle — controls which fee types appear as tiles at registration
- "+SST" toggle per fee type — Foreigner tile auto-applies 6% SST at billing
- Registration tiles now show fee label + RM amount
- Foreigner auto-detection at registration (passport IC → Foreigner tile pre-selected)
- feeTypeId stored on queue entry → flows through to billing auto-select

### Fixed
- `sst-row-label` missing ID (foreigner SST badge was broken)

---
## [v1.0.0] — 2026-04-01
- Initial CMS release
