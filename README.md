# Series Seed (SANE Edition)

**Simple Agreement for Now Equity**

Updated, modernized Series Seed equity financing documents for seed-stage startups, aligned with the October 2025 NVCA model document updates.

---

## The problem

Seed-stage founders choosing between a SAFE and a full NVCA equity round are choosing between two tools designed for different situations. SAFEs are built for speed and simplicity when pricing is premature. The NVCA suite is built for thoroughness when the stakes justify it. But a lot of companies fall in between: they're ready for real equity, a formal cap table, and a board, but they don't need a hundred pages of documents to get there.

**SAFEs work well for early fundraising, but they come with trade-offs.** SAFE holders generally don’t start the QSBS clock at issuance, and capital gains treatment is not automatic. While SAFEs are outstanding, the cap table remains ambiguous in ways that matter: calculating dilution, pro rata rights, and liquidation waterfalls. SAFE "stacking" or carrying an oversized option pool into a priced round creates dilution traps that catch founders off guard. And because SAFEs defer governance entirely, startups that would benefit from an engaged board and investors that would benefit from protective provisions are left without either until the next round.

**The full NVCA suite is the gold standard for priced rounds, but it's built for Series A and beyond.** The standard NVCA model documents (Stock Purchase Agreement, Investors' Rights Agreement, Voting Agreement, Right of First Refusal and Co-Sale Agreement, and Certificate of Incorporation) run to more than a hundred pages combined. Closing on them typically takes a month and legal fees normally exceed $50,000. Founders find themselves negotiating registration rights, IPO demand thresholds, and governance provisions designed for companies with millions in revenue, all at a stage where they still may be confirming product market fit. And no founder wants to take their foot off the gas for a month to close a seed round.

## What this project does

Series Seed (SANE Edition) sits in the middle. A term sheet and two documents. Real equity on your cap table from day one. A formal board with designated seats. Clear investor rights, protective provisions, and pro rata participation. QSBS eligibility from the start. And a closing timeline measured in days, not months, at a cost closer to a SAFE round than a Series A.

This is a fork of the [Series Seed](https://github.com/seriesseed/equity) v3.2 documents, updated to reflect current market practice and the October 2, 2025 NVCA model legal document revisions.

## Documents

### Core documents

| Document | Purpose | Download |
|----------|---------|----------|
| [**Term Sheet**](docs/term-sheet.md) | Non-binding summary of principal deal terms | [.docx](docx/Series%20Seed%20-%20Term%20Sheet.docx) |
| [**Investment Agreement**](docs/investment-agreement.md) | Single binding agreement covering purchase, representations, information rights, participation rights, voting, and general provisions | [.docx](docx/Series%20Seed%20-%20Investment%20Agreement.docx) |
| [**Certificate of Incorporation**](docs/certificate-of-incorporation.md) | Restated charter filed with Delaware, defining stock rights, conversion mechanics, liquidation preferences, and protective provisions | [.docx](docx/Series%20Seed%20-%20Certificate%20of%20Incorporation.docx) |

### Ancillary documents

| Document | Purpose |
|----------|---------|
| [**Board Consent**](docs/board-consent.md) | Unanimous written consent of the Board of Directors authorizing the financing |
| [**Stockholder Consent**](docs/stockholder-consent.md) | Written consent of stockholders approving the Restated Certificate and stock issuance |
| [**Investor Questionnaire**](docs/investor-questionnaire.md) | Accredited investor verification and Rule 506(d) bad actor questionnaire |
| [**Variable Reference Map**](docs/variable-reference-map.md) | Cross-document guide to every fill-in variable, with dependency tracking |

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
- Added ancillary closing documents: Board Consent, Stockholder Consent, and Investor Questionnaire
- Replaced "best efforts" with "reasonable efforts" throughout
- Fixed typos present in the original Series Seed documents
- General drafting modernization based on Adams, *A Manual of Style for Contract Drafting* (4th ed.)

## How to use these documents

1. Start with the **Term Sheet** to align on deal terms with your lead investor.
2. Fill in the **Investment Agreement** front pages (Exhibit A variables and Schedule 1) using the Variable Reference Map to ensure cross-document consistency.
3. Fill in the **Certificate of Incorporation** blanks (company name, share counts, par values, registered agent).
4. Use the **Variable Reference Map** to verify that the seven critical cross-document dependencies reconcile.
5. Distribute the **Investor Questionnaire** to each Purchaser to verify accredited investor status and Rule 506(d) compliance.
6. Execute the **Board Consent** and **Stockholder Consent** to authorize the charter amendment and stock issuance.
7. Circulate, sign, file the Certificate with Delaware, and close.

## Contributing

These documents are open source. If you find an error, have a suggestion, or want to propose a change, please open an issue or submit a pull request.

## License

These documents are provided under the same open-source terms as the original Series Seed project.

## Credits

Forked from [Series Seed](https://github.com/seriesseed/equity) v3.2, with select provisions adapted from the [Cooley LLP fork](https://github.com/CooleyLLP/seriesseed). Updated by [Rubicon Law](https://rubiconlaw.com).

NVCA model document updates based on the October 2, 2025 NVCA release.
