# AI & Labor Dashboard — Version History

## v12 (2026-04-12) — This deployment
- P1-P7 council fixes from S15
- 17 labor themes, 12 regions
- Surveillance heuristic-precision reported as 51.3% (1,500-char window artifact)
- CST tracker expanded to 6 religious traditions
- WCAG contrast 16:1 / 13:1 (AAA)
- Live at: https://cjimmylin.github.io/cei-labor-dashboard/

## v13 (2026-04-13) — Current version
- Surveillance heuristic-precision corrected: 51.3% -> 87.2% (n=117 census)
- Root cause: S15 used 1,500-char scan window; S16 widened to full 10,000-char EXTRACT_CAP
- 42 FP->TP flips, 0 regressions, 15 residual FPs for human review
- Added project explainer, surveillance callout, methodology diff panel, language bias note
- Live at: https://cjimmylin.github.io/cei-labor-dashboard-v13/
