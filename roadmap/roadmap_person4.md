# Combined Roadmap
**NtapAT&T Digital: Customer Data Protection and Privacy**
Person 4: Savannah Williamson

Every item below has an owner and a SMART goal. Deadlines are counted from program kickoff (Day 0). Lane goals come from the team plan's examples; adjust once Persons 1 to 3 finalize.

## Days 0 to 30: Know what we have

| # | SMART goal | Owner | Lane | Why it matters |
|---|---|---|---|---|
| 1 | Inventory 100% of vendors and record what customer data each one touches by Day 30 | Security lead | 1 | Can't protect what we haven't listed |
| 2 | Sort every vendor into Tier 1, 2, or 3 and finish the data map (data type, system, access, vendor) by Day 30 | Security lead + Vendor manager | 1 | Sets review priority |
| 3 | Publish an approved AI tool policy covering customer data by Day 30 | Security lead + Legal | 1 | Stops customer data going into unapproved tools |
| 4 | Pick vendor-risk platform vs. manual review, with cost comparison, by Day 30 | Vendor manager + CFO | 3 | Lets budget lock in |
| 5 | Record baselines for every KPI in the dashboard by Day 30 | Program lead | 4 | Without baselines we can't show results |

## Days 31 to 90: Lock down access and vendors

| # | SMART goal | Owner | Lane | Why it matters |
|---|---|---|---|---|
| 6 | Apply least-privilege roles for sales and marketing (masked or aggregated data) to 100% of those accounts by Day 60 | Security lead | 1 | Limits damage from phishing and insider leaks |
| 7 | Turn on in-app 2FA for 100% of staff and contractor accounts, with 15-minute auto-logout, by Day 60 | IT / Security lead | 1 | Stops account takeover |
| 8 | Classify 100% of customer data stores (Public / Internal / Confidential / Restricted) by Day 60 | Privacy officer | 2 | Basis for retention and access rules |
| 9 | Review 100% of Tier 1 vendors (questionnaire, SOC 2 Type II, PCI DSS attestation for payment) by Day 60 | Vendor manager | 3 | Payment and e-commerce vendors carry the most risk |
| 10 | Rate-limit 100% of public APIs by Day 60 | Engineering lead | 3 | Stops scraping |
| 11 | Add privacy clauses (data use limits, breach notice time, deletion on request, right to audit) to 100% of Tier 1 and Tier 2 contracts by Day 90 | Legal counsel | 2 | Makes vendor duties enforceable |
| 12 | Turn on logging and alerts for all customer database access by Day 90 | Security lead | 3 | Cuts time to notice a problem |
| 13 | Name a security contact at 100% of Tier 1 and Tier 2 vendors by Day 90 | Vendor manager | 3 | Someone to call during an incident |

## Days 91 to 180: Customer control and wider coverage

| # | SMART goal | Owner | Lane | Why it matters |
|---|---|---|---|---|
| 14 | Launch a self-service portal for customers to view, download, and delete data by Day 120, with deletion requests reaching vendors | Privacy officer + Engineering lead | 2 | Meets CCPA, PIPEDA, GDPR rights and builds trust |
| 15 | Review 100% of Tier 2 vendors by Day 120 | Vendor manager | 3 | Logistics and support also handle customer data |
| 16 | Publish updated consent and privacy notices covering U.S. states, Canada, and the EU by Day 120 | Legal counsel + Marketing lead | 2 | Needed before expansion |
| 17 | Start the 1-year-inactivity deletion job and delete 100% of eligible records on schedule from Day 150 | Privacy officer | 2 | Smaller data set means a smaller breach |
| 18 | Review Tier 3 vendors (100%) by Day 180 | Vendor manager | 3 | Completes vendor coverage |
| 19 | Run the first company-wide training and measure ShadowAI incidents monthly from Day 90 | Security lead | 1 | Staff habits drive most leaks |

## Days 181 to 365: Prove it and keep it running

| # | SMART goal | Owner | Lane | Why it matters |
|---|---|---|---|---|
| 20 | Complete yearly re-review for 100% of Tier 1 vendors by Day 365 | Vendor manager | 3 | Proof goes stale |
| 21 | Close 100% of customer privacy requests within the legal deadline, every month from Day 180 | Privacy officer | 2 | Avoids fines |
| 22 | Cut mean time to detect and respond to incidents by 50% versus the Day 30 baseline by Day 365 | Security lead | 3 | Faster detection means smaller breaches |
| 23 | Show 95%+ of staff accounts on least privilege and 100% on 2FA at the Day 365 audit | Security lead | 1 | Proves access controls hold |
| 24 | Present a year-end results report (KPIs vs. targets, cost vs. plan) to leadership by Day 365 | Program lead | 4 | Supports renewing the budget |

## Dependencies to watch
- Items 9, 11, and 15 depend on item 2 (tiers) and item 4 (platform choice).
- Item 14 (portal) depends on item 8 (classification) so we know where data lives.
- Item 17 (deletion) depends on item 14 so deletions also reach vendors.
