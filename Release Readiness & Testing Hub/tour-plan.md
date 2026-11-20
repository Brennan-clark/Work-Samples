# Product Tour plan — Release Readiness Dashboard

**Direction (chosen):** Product Tour. Neutral product brand ("Release Readiness Dashboard") in the dashboard's own look; clean app-store tone (one caption per feature, the real screen doing its thing); landscape 1920×1080, 30 fps, 50 s.
**Data (chosen):** anonymized. Every identifying field is replaced with a neutral placeholder: ticket keys RR-1001…, neutral test-step and bug titles, placeholder people names ("Avery Sample"), workstreams → Workstream A–X, program header → "Release Readiness", no Jira hostnames.
**Architecture beat (recommended, included):** a generic redraw, no platform, SSO vendor, credential or CDN details.

## Storyboard (96 BPM, bar = 2.5 s, every cut on a bar line)
| # | Time | Caption | What the real app does |
|---|---|---|---|
| 1 | 0–7.5 | EXEC OVERVIEW · Every test cycle, one page. | Window rises on the all-waves overview: the banner flags 1 of 17 cycles at risk. Cursor clicks "Wave 1" → "All 11 Wave 1 cycles cleared exit criteria". |
| 2 | 7.5–15 | CYCLE DETAIL · Drill into any cycle. | Cursor clicks UAT, then UAT 1.5. Camera settles on Pass Rate Trend and Defect Accumulation. |
| 3 | 15–22.5 | EXIT CRITERIA · Exit criteria by workstream. | Scroll to the heatmap. Cursor clicks a green "95% Passed" cell → drill-down with the pass-rate formula and its tickets. |
| 4 | 22.5–30 | TEST EXECUTION · Execution against target. | Section opens: executed donut, execution trend, workstream breakdown. |
| 5 | 30–37.5 | DEFECT ANALYSIS · From trend to ticket. | Daily creation and cumulative trends, bugs by workstream and by type; cursor opens the ticket table (placeholder people, RR keys). |
| 6 | 37.5–45 | HOW IT WORKS · Live from Jira, refreshed every 5 minutes. | Generic diagram builds: Jira (read-only query) → dashboard (fetch & cache · reshape issues · cycle settings · page & charts) → single sign-on → leaders in a browser. |
| 7 | 45–50 | — | "Release readiness, at a glance." + product name + the six cycle-type tabs light up. Held ≥ 2 s. |

Checks before delivery: every rendered view's text and chart labels scanned for real names, workstreams, vendor and program terms (none allowed); stills at every cut; frame count = 1500.

## Sound
96 BPM, A minor, one grid with the picture. Pad + light pulse under the tour, cursor clicks and drill-downs as quiet in-key notes, a riser into each cut, a lighter breakdown under the architecture beat, resolve on the outro. Normalized near -16 LUFS.
