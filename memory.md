# Morning Brief Memory

_Last updated: 2026-07-06 (second pass same day — M365 reconnected mid-day)_

## Active Commitments
_(Commitments Matt made, from all sources including Zoom)_
- Talk with Taylor Heath to explain how the original Louisville AOP number (469.9K) was derived. Source: DC Forecast mtg, 7/2. Still open as of 2026-07-06 16:30 UTC — today's two Taylor Heath sessions (FY27 Facilities Budget Review, Review Final Capex FY27 AOP) hadn't happened yet at last check.
- Voiced support for prioritizing the ACE pick-shorts/mispick system fix given senior-team attention. Source: DCAB mtg, 7/1. Open-ended, no specific deliverable owed yet.
- Sign the Hy-Tek Docusign for **ARI 7455 CO-28 VAS Modifications Client Summary** — this is the formal document for the ACE VAS-lane split project (peak-readiness); it's the next concrete step to move that project forward. Received 2026-07-06 04:26 UTC via Docusign from Connor Clark.

## Dwelling Items
_(Flagged as stalled; running count = number of distinct daily briefs appeared in, not same-day reruns)_
- Louisville AOP derivation explanation owed to Taylor Heath — see Active Commitments above. **Appeared in: 1 day (2026-07-06).**
- Kieran Lang (VP, its4logistics) waiting on a reply from Matt/Laura Hoegler since last week's ITS Intro meeting (7/2); "let me know details when you can" (2026-07-06). **Appeared in: 1 day (2026-07-06).**
- ~~ACE peak-readiness intake forms~~ — **no longer dwelling**: turned out to be further along than the 7/1 meeting suggested; a formal VAS Modifications Client Summary from Hy-Tek is now awaiting Matt's signature (see Active Commitments). Removing from this list; will re-add only if it stalls again after signature.

## VIPs Owed Response
- **Daniel Garland** — still hasn't sent the updated topside unit projection (through Dec) promised "in a couple days" from the 7/2 DC Forecast meeting. Not delivered as of 2026-07-06 16:30 UTC (the email activity seen today from Daniel is a different thread — DDP cancel-risk numbers for the LATE 8/1 launch product, not the topside projection). Still unconfirmed/overdue.
- **Cecilia Rios** — requested (via Andy Trojan) a calendar hold with Matt before July 29–30 for FY27 planning. No invite seen yet in Outlook as of this check.
- **Michelle McGill** (Chief People Officer) — sent a new quarterly VP touch-base invite (2026-07-06 15:14 UTC), first in a planned recurring series. Needs acceptance/reply.

## Retail Partner / Logistics Threads to Watch
- Section 301 proposed duties: Cambodia (10%), India (12.5%) — hearings 7/7/2026.
- Section 122 blanket 10% footwear tariff expires July 24, 2026 unless Congress extends.
- ILA East Coast port labor negotiations unresolved; Vancouver/Prince Rupert strike resolved via 4-year deal.
- ACE YMS go-live targeted July 21, 2026 (inspection-module UAT due July 10). Hub WMS code freeze extended to Jan 11.
- DC capacity flex being explored: ACE to 900K units, Hub to 650K in July.
- **LATE 8/1 launch product (Jordan DDP units)**: 39,727 units must be returned to Jordan on arrival and re-shipped by air to LAX (not the usual NY routing); late-Sept placeholder for second US arrival. 7.2K units at cancellation risk by 8/31, 23.6K by 9/30. Laura Hoegler owes the group an update "later this week" on the confirmed date.
- Industrial real estate: leasing up 17.8% YoY, big-box +80.7% YoY — relevant backdrop for FY27 facilities/capex decisions (today's Taylor Heath sessions).
- FY26 closed strong: June net shipments +$4.5M over estimate (+33.3% YoY, +25% over sales plan); Key Accounts $238.4M (+15.4% YoY). Direct Ship FY27 at 76% of the 5M-unit target (3.79M booked).
- Miniload outage at the Hub, 2026-07-06 13:23–13:31 UTC — resolved via app-server restart; unclear if a P2 ticket was ever filed for root-cause tracking (flagged by Greg James, unanswered as of the Teams thread).

## CliftonStrengths / Leadership Reflections Noted
- 2026-07-06: Four leadership domains (Executing, Influencing, Relationship Building, Strategic Thinking) — reflection on whether Matt's distribution leadership team has deliberate coverage across all four vs. over-indexing on Executing.

## Patterns
_(Week-over-week observations — none yet with only one day tracked)_
- 2026-07-06: All three connector/infra issues hit on the first-ever run resolved same-day once flagged: Microsoft 365 needed an MFA re-auth (fixed via connector reconnect), the git remote returned 403 due to a read-only GitHub App permission scope (fixed by switching Contents to Read-and-write), and the Zoom Hub-doc write scope lagged behind the Zoom read/search reconnect (status unresolved as of last check — read/search works, file creation still errors). Worth confirming next run whether the Hub-doc write scope has caught up, or if it needs its own separate reauth step every time.
