# Combined Budget
**NtapAT&T Digital: Customer Data Protection and Privacy**
Person 4: Savannah Williamson

**All dollar figures are estimates** (planning ranges, not quotes). The basis column says where each came from. Replace with real vendor quotes and salary data before the final submission, and add any source you use to `sources.md`.

## 1. Budget table

| # | Item | Type | One-time (est.) | Yearly (est.) | Business value | Basis of estimate |
|---|---|---|---|---|---|---|
| 1 | Access management + 2FA tooling (~500 employees plus contractors) | Software | $10k to $20k | $25k to $50k | Fewer account takeovers; sales and marketing keep needed insights | Typical per-user pricing of ~$4 to $8/user/month; team assumption |
| 2 | Approved AI tool + data-loss prevention | Software | $5k to $10k | $15k to $30k | Stops customer data leaking into unapproved AI tools | Team assumption; confirm with quotes |
| 3 | Training (security, privacy, ShadowAI) | People | $5k to $10k | $5k to $10k | Fewer accidental leaks | Team assumption |
| 4 | Data discovery and classification tool | Software | $15k to $30k | $30k to $70k | Lower storage cost; basis for deletion | Team assumption; confirm with quotes |
| 5 | Customer privacy portal (view, download, delete) | Software | $20k to $40k | $25k to $60k | Meets customer-rights laws; builds loyalty | Team assumption; confirm with quotes |
| 6 | Legal review + vendor contract clauses | Legal | $40k to $80k | $10k to $20k | Avoids fines; makes vendor duties enforceable | Outside counsel hourly rate assumption |
| 7 | Vendor-risk platform (recommended option) | Software | $10k to $20k | $25k to $60k | Faster, consistent vendor reviews | Team assumption; compare to manual option below |
| 8 | Logging and alerting (customer DBs, vendor access, cloud) | Software | $15k to $30k | $40k to $100k | Faster detection, smaller breaches | Team assumption; confirm with quotes |
| 9 | API gateway / rate limiting | Software | $10k to $25k | $15k to $40k | Stops scraping; fewer payment disruptions | Team assumption |
| 10 | Program staff (1 privacy and vendor analyst) | People | $0 | $90k to $130k | Runs reviews, requests, and re-reviews | Salary range assumption plus benefits |
| 11 | External assessment (PCI scoping, penetration test) | Legal / services | $20k to $40k | $20k to $40k | Independent proof for customers and regulators | Team assumption |
| | **Total** | | **$150k to $305k** | **$300k to $610k** | | |

**Year-one total (one-time + yearly): about $450k to $915k.** Midpoint is roughly $680k.

### Option comparison: vendor-risk platform vs. manual review (Person 3's decision)
| Option | One-time (est.) | Yearly (est.) | Trade-off |
|---|---|---|---|
| Vendor-risk platform (item 7) | $10k to $20k | $25k to $60k | Faster and repeatable; still needs analyst time (item 10) |
| Manual review by staff | $0 | $60k to $80k (about 0.75 of a staff role) | No tool cost; slower, harder to keep yearly re-reviews on time |

The table above assumes the platform. If manual is chosen, replace item 7 with the manual row.

## 2. Phasing (share of year-one spend, estimate)

| Phase | Share of year-one spend | What it buys |
|---|---|---|
| Days 0 to 90 | ~45% | Access tooling, 2FA, vendor tiering and Tier 1 review, legal clauses, logging |
| Days 91 to 180 | ~30% | Privacy portal, data discovery rollout, Tier 2 and Tier 3 reviews |
| Days 181 to 365 | ~25% | Re-reviews, external assessment, steady-state running costs |

## 3. Cost of doing nothing

| Item | Estimate | Source / basis |
|---|---|---|
| One major breach | About $10.2M (U.S. average, IBM 2025); newest IBM data reports about $11.5M | IBM Cost of a Data Breach, via CyberScoop and CFO.com (see `sources.md`) |
| Third-party / supply-chain breach | About $4.9M average | IBM 2025 |
| Malicious insider breach | About $4.9M average | IBM 2025 |
| Regulatory fines | GDPR up to the higher of 4% of global annual revenue or EUR 20M; CCPA fines are charged per violation | Statutory text; verify current amounts before final |
| Lost customers | Every 1% of 1M customers lost is 10,000 customers. Multiply by average yearly customer value (team fills in) | Team assumption |
| Blocked expansion | No Canada or EU launch without compliant consent and deletion | Case assumption |

## 4. Summary for the CFO

- **Ask:** approve about **$450k to $915k in year one** (about $680k midpoint), then roughly **$300k to $610k per year** to run it.
- **Phasing:** about 45% in the first 90 days, so the highest-risk fixes (access, vendors, logging) land first.
- **Expected return:** a single avoided breach covers the program many times over. Break-even math: $0.45M to $0.92M divided by a $10.2M breach cost means the program pays for itself if it lowers the chance of a major breach by about **4.4 to 9 percentage points**.
- **Also protects revenue:** compliant consent and deletion are required to enter Canada and the EU, and faster payment-vendor reviews reduce payment disruptions.
- **Caveat:** these are planning estimates. Real quotes will move the numbers. The break-even logic holds as long as the breach cost reference stays in the $9M+ range.
