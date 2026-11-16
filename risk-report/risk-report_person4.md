# Risk Report: Summary, Ranking, and Heat Map
**NtapAT&T Digital: Customer Data Protection and Privacy**
Person 4: Savannah Williamson

---

## 1. Executive Summary

NtapAT&T Digital has 1 million customers, a loyalty program, a public website and mobile app, and a small security team. Customer trust is the product. If that trust breaks, the company can't expand into Canada and the EU the way it wants to.

The biggest problem is that customer data doesn't stay in one place. Payment, logistics, marketing analytics, support, and the e-commerce platform each touch it, and our own sales and marketing teams often have more access than they need. We have limited visibility into who sees what, and the data lives longer than it should.

Our answer is a **Vendor Management Program**: every third party has to prove it protects customer data and follows privacy law. Three supporting fixes back it up. **Less access** (least privilege, in-app 2FA, 15-minute auto-logout). **Less data kept** (classification, deletion after 1 year of inactivity). **Faster detection** (logging and alerts on customer databases and vendor access).

The reason to do this now is cost. The average U.S. data breach costs roughly $10.2 million (IBM, 2025), and the newest IBM figures put it near $11.5 million. We estimate year-one program cost at **$0.45M to $0.92M**. If the program lowers the odds of a major breach by only about 5 to 9 percentage points, it pays for itself, before counting fines or lost customers.

**Ask for leadership:** approve the year-one budget and name an executive owner for the Vendor Management Program.

---

## 2. Final Ranked Top Risks

Score = Likelihood x Impact. Ranking follows the team's agreed order; scores are team estimates for the 1 to 5 scale and should be adjusted after Persons 1 to 3 finish their lanes.

| Rank | Risk (plain English) | Category | L | I | Score | Lane |
|---|---|---|---|---|---|---|
| 1 | **Breaches:** attackers get in through phishing, stolen logins, or API abuse | Breach | 4 | 5 | 20 | 3 (handoff note), shared |
| 2 | **Too much access:** staff and accounts can see more customer data than their job needs | Insider-Access | 4 | 4 | 16 | 1 |
| 3 | **Vendor leaks:** a partner mishandles or loses our customers' data | Vendor | 3 | 5 | 15 | 3 |
| 4 | **Privacy gaps:** we miss consent, notice, or deletion rules, especially in new markets | Regulatory | 3 | 4 | 12 | 2 |
| 5 | **Blind spots:** we can't see who accessed data or what's happening in the cloud | Breach | 4 | 3 | 12 | 3 |
| 6 | **Messy data:** we keep too much, for too long, with no clear labels | Regulatory / Consumer harm | 4 | 2 | 8 | 2 |

*Note on ties: risks 4 and 5 both score 12. Risk 4 stays ahead because the fines and loss of trust hit harder if it goes wrong.*

---

## 3. Heat Map

Likelihood across (1 = rare, 5 = very likely). Impact down (5 = severe).

| Impact \ Likelihood | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| **5** | | | **R3** Vendor leaks | **R1** Breaches | |
| **4** | | | **R4** Privacy gaps | **R2** Too much access | |
| **3** | | | | **R5** Blind spots | |
| **2** | | | | **R6** Messy data | |
| **1** | | | | | |

**How to read it:** R1 to R3 sit in the top-right danger zone and get fixed first (Days 0 to 90). R4 to R6 follow, but the 1-year deletion rule and classification start early because they shrink every other risk.

---

## 4. Finance / Sales / Marketing Impact per Risk

| Rank | Risk | Finance impact | Sales impact | Marketing impact | Main fix |
|---|---|---|---|---|---|
| 1 | Breaches | Average U.S. breach cost ~$10.2M (IBM 2025); fraud and chargeback losses; response and notification costs | Customers abandon checkout or leave after a breach notice; account lockouts hurt conversion | Loyalty program loses credibility; campaigns paused during incident | In-app 2FA, rate-limited APIs, logging and alerts |
| 2 | Too much access | Insider incidents are among the costliest breach types (IBM 2025: malicious insider ~$4.9M average) | Sales still needs data to close deals; poor access rules slow requests | Marketing needs insights, not raw records; unapproved AI tools risk leaking customer data | Least privilege with masked or aggregated data, approved AI tool policy |
| 3 | Vendor leaks | Supply-chain compromise averages ~$4.9M (IBM 2025); possible contract disputes | Payment or logistics outages stop orders | Analytics vendor misuse can break consent promises | Vendor Management Program: proof by tier, contract clauses, yearly re-review |
| 4 | Privacy gaps | Fines (GDPR, CCPA/state laws); legal costs; market-entry delays | Can't sell in Canada or the EU until compliant | Consent and notice rules limit targeting; opt-outs must be honored | Consent and notice updates, self-service access/delete portal |
| 5 | Blind spots | Slower detection raises breach cost (IBM: faster detection lowers cost) | Longer disruptions before we spot a problem | Late discovery means late customer notice, worse PR | Logging and alerts on customer databases and vendor access |
| 6 | Messy data | Storage cost; bigger breach if old data was leaked | Less trust when customers can't delete data | Stale lists waste campaign spend; deletion rules shrink contact lists | Classification labels, retention schedule, delete after 1 year inactive |

*Cost figures are estimates. Sources are listed in `sources.md`.*

---

## 5. Laws vs. Standards (kept separate)

- **Laws:** CCPA and other U.S. state privacy laws, PIPEDA (Canada), GDPR (EU).
- **Standards and certifications:** PCI DSS (payments), SOC 2, ISO 27001, NIST.

Laws are legally required where they apply. Standards are how we prove our controls (and vendors' controls) actually work.
