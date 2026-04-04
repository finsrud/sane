# Series Seed (SANE Edition)

**Simple Agreement for Now Equity**

You've outgrown the SAFE. You're not ready for a full NVCA round. The Series Seed (SANE Edition) sits in the middle — real preferred equity, a clean cap table, and a working board, without the hundred-page overhead.

---

## The problem

Seed-stage founders raising capital face an uncomfortable choice: use a SAFE and defer every decision that matters, or negotiate a full NVCA equity round and spend a month and $50K+ in legal fees while you're still confirming product-market fit.

For a lot of companies, neither is right.

**SAFEs work well early, but they come with trade-offs.** SAFE holders don't start the QSBS clock at investment (arguably). While SAFEs are outstanding, the cap table remains ambiguous: dilution, pro rata rights, and liquidation waterfalls are all deferred. SAFE stacking at different valuation caps creates conversion surprises that founders don't see coming. And because SAFEs defer governance entirely, founders who would benefit from an engaged board and investors who would benefit from protective provisions are left without either until the next round.

**The full NVCA suite is the gold standard, but it's built for Series A and beyond.** Five documents, a month to close, and legal fees that routinely exceed $50,000 — built for companies that have already confirmed product-market fit, not companies still finding it.

## What this is

Series Seed (SANE Edition) sits in the middle. Three documents. Real preferred stock on your cap table from day one. A formal board with designated seats. Clear investor rights, protective provisions, and pro rata participation. QSBS eligibility from the start. A closing timeline measured in days, not months, at a cost closer to a SAFE round than a Series A.

This is a fork of the [Series Seed](https://github.com/seriesseed/equity) v3.2 documents, updated to reflect current market practice and the October 2, 2025 NVCA model legal document revisions.

## Why it matters

**For founders:**

- **Cap table certainty.** With priced equity, the cap table is clean and final at closing. No stacked SAFEs at different caps, no conversion surprises at the next round.
- **A functional board.** SAFEs defer governance entirely. SANE gives you designated board seats — founder, investor, and mutual consent directors — from day one.
- **No conversion event.** What you negotiate is what you get. SAFE stacking creates invisible dilution that only resolves at your next raise. Priced equity eliminates that entirely.
- **Series A readiness.** NVCA-aligned documents mean next-round counsel can redline SANE against the NVCA model and immediately see the delta — no archaeology, no unwinding a non-standard structure.

**For investors:**

- **QSBS from closing.** Preferred stock purchased at a priced round starts the Section 1202 clock at closing. For investors targeting the QSBS exclusion, that timing difference can be worth millions.
- **Cap table clarity.** Every investor knows exactly what they own and where they stand.
- **Governance rights.** Board representation, information rights, participation rights, and protective provisions — none of which SAFEs provide.
- **MFN protection.** If the company subsequently issues equity on more favorable terms, SANE investors are entitled to equivalent rights, and Major Purchaser status carries forward.

## Documents

### Core documents

| Document | Purpose | Download |
|----------|---------|----------|
| [**Term Sheet**](docs/term-sheet.md) | Non-binding summary of principal deal terms | [.docx](docx/Series%20Seed%20-%20Term%20Sheet.docx) |
| [**Investment Agreement**](docs/investment-agreement.md) | Single binding agreement covering purchase, representations, information rights, participation rights, voting, and general provisions | [.docx](docx/Series%20Seed%20-%20Stock%20Investment%20Agreement.docx) |
| [**Certificate of Incorporation**](docs/certificate-of-incorporation.md) | Restated charter filed with Delaware, defining stock rights, conversion mechanics, liquidation preferences, and protective provisions | [.docx](docx/Series%20Seed%20-%20Certificate%20of%20Incorporation.docx) |

### Ancillary documents

| Document | Purpose | Download |
|----------|---------|----------|
| [**Variable Reference Map**](docs/variable-reference-map.md) | Cross-document guide to every fill-in variable, with dependency tracking | [.docx](docx/Series%20Seed%20-%20Variable%20Reference%20Map.docx) |
| **Board Consent** | Unanimous written consent of the Board of Directors authorizing the financing | Coming soon |
| **Stockholder Consent** | Written consent of stockholders approving the Restated Certificate and stock issuance | Coming soon |
| **Investor Questionnaire** | Accredited investor verification and Rule 506(d) bad actor questionnaire | Coming soon |

## How these relate to the NVCA model documents

Series Seed compresses the standard NVCA five-document suite into three documents:

| NVCA Document | Series Seed Equivalent |
|---------------|----------------------|
| Stock Purchase Agreement | Investment Agreement (Sections 1-3, Exhibits A-B) |
| Investors' Rights Agreement | Investment Agreement (Sections 4, 6) |
| Voting Agreement | Investment Agreement (Section 7) |
| Right of First Refusal and Co-Sale Agreement | Investment Agreement (Sections 4.3, 5) |
| Certificate of Incorporation | Certificate of Incorporation |

The documents are designed as NVCA derivatives. The Certificate of Incorporation tracks the NVCA model certificate section-for-section, so Series A counsel can redline the two and immediately see the delta. The Investment Agreement's MFN clause (Section 4.2) explicitly contemplates the transition to a full NVCA suite, providing that seed investors' rights will be amended and restated into the next financing documents.

## What changed from Series Seed v3.2

### NVCA October 2025 alignment

We incorporated the NVCA updates that matter at seed stage and intentionally excluded those that don't.

| Update | Status | Rationale |
|--------|--------|-----------|
| OISP/DSP national security compliance | Included (lighter touch) | Basic OFAC/sanctions reps + foreign person monitoring; full OISP/DSP framework deferred to Series A |
| QSBS expanded thresholds | Included (simplified) | Covenant to maintain QSBS eligibility; detailed tracking deferred to Series A |
| Board designation non-transferability | Included | All three documents; matches NVCA default |
| Foreign person status monitoring | Included | Investment Agreement Section 3.13 |
| Requisite Holders sanctions exclusion | Included | Certificate; excludes Restricted Persons from governance votes |
| Tranched financings | Excluded | Adds complexity inappropriate for seed; 90-day Additional Closing window is sufficient |
| Governance policy suite | Excluded | Series A+ requirement; not expected at seed |
| S-1 demand minimum ($20M) | Excluded | No registration rights at seed stage |
| Severance cap ($200K) | Excluded | Addressed at Series A |

### Other substantive changes

- Modernized "Future Rights" to "Most Favored Nation" with explicit scope covering Major and non-Major Purchasers
- Added "Restricted Person" definition for sanctions compliance across all documents
- Added Rule 506(d) bad actor representations for both Company (Section 2.14) and Purchaser board designees (Section 3.11)
- Added explicit convertible securities consent mechanism (Section 3.14) for SAFE and note conversions at closing
- Added Variable Reference Map for cross-document consistency
- Replaced "best efforts" with "reasonable efforts" throughout
- Fixed typos present in the original Series Seed documents
- General drafting modernization based on Adams, *A Manual of Style for Contract Drafting* (4th ed.)

## How to use these documents

1. Start with the **Term Sheet** to align on deal terms with your lead investor.
2. Fill in the **Investment Agreement** front pages (Exhibit A variables and Schedule 1) using the Variable Reference Map to ensure cross-document consistency.
3. Fill in the **Certificate of Incorporation** blanks (company name, share counts, par values, registered agent).
4. Use the **Variable Reference Map** to verify that the seven critical cross-document dependencies reconcile.
5. Circulate, sign, file the Certificate with Delaware, and close.

## Contributing

These documents are open source. If you find an error, have a suggestion, or want to propose a change, please open an issue or submit a pull request.

## License

These documents are provided under the same open-source terms as the original Series Seed project. See [LICENSE](LICENSE) for details.

## Credits

Forked from [Series Seed](https://github.com/seriesseed/equity) v3.2, with select provisions adapted from the [Cooley LLP fork](https://github.com/CooleyLLP/seriesseed). Updated by [Rubicon Law](https://rubiconlaw.com) and [Flux](https://flux.law). Aligned with the October 2, 2025 NVCA model document release.
