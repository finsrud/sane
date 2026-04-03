# SERIES SEED VARIABLE REFERENCE MAP

## Cross-Document Fill-In Guide and Dependency Tracker

**Document Key:** TS = Term Sheet | IA = Investment Agreement | Cert = Certificate of Incorporation

All variables marked with an asterisk (*) have cross-document dependencies that must be reconciled.

## 1. COMPANY INFORMATION

| Variable | Doc | Section | Operative Use |
|----------|-----|---------|---------------|
| Company Name * | TS, IA, Cert | TS Header; IA Preamble; Cert Art I | Legal entity identification; all signature blocks; filing name |
| State of Incorporation * | TS, IA | TS Header; IA Exh A §1 | Governs corporate law; filing jurisdiction |
| Registered Office Address | Cert | Art II | Delaware statutory compliance; service of process |
| Registered Office City/County | Cert | Art II | Delaware filing requirement |
| Registered Agent Name | Cert | Art II | Service of process recipient |
| Governing Law State * | IA | Exh A §1 | Controls contractual interpretation (Exh B §8.2) |
| Dispute Resolution Forum | IA | Exh A §1 | Exclusive jurisdiction for disputes (Exh B §8.2) |
| Stock Plan Name | IA | Exh A §1 | Equity incentive vehicle reference (§2.2.1, 4.5) |

## 2. DEAL ECONOMICS

| Variable | Doc | Section | Operative Use |
|----------|-----|---------|---------------|
| Price Per Share * | TS, IA, Cert | TS Offering; IA Exh A §3; Cert Art III | Core economic term; IA "Purchase Price" = Cert "Original Issue Price"; drives conversion ratio (Cert §3.1.1), liquidation preference (Cert §1.1) |
| Pre-Money Valuation | TS | Offering Terms | Determines Price Per Share; establishes company value |
| Aggregate Proceeds | TS | Offering Terms | Total raise amount; corresponds to IA Total Series Seed Investment Amount |
| Total Series Seed Investment Amount * | IA | Exh A §3 | Caps total issuable shares (§1.2.2); must equal TS Aggregate Proceeds |
| Major Purchaser Dollar Threshold * | TS, IA | TS Financial Info; IA Exh A §3 | Triggers info rights (§4.1), inspection (§4.1.3), participation (§6.1), MFN carry-forward (§4.2) |
| Purchaser Counsel Reimbursement | TS, IA | TS Expenses; IA Exh A §3 | Company reimbursement obligation (§8.7) |
| Option Pool Percent * | TS, IA | TS Offering; IA Exh A §3 | Sizing of unallocated option pool; must reconcile with share counts below |

## 3. BOARD COMPOSITION

| Variable | Doc | Section | Operative Use |
|----------|-----|---------|---------------|
| Common Board Member Count * | TS, IA, Cert | TS Board; IA Exh A §2; Cert Art III | Directors elected by Common holders; must match across all three docs |
| Series Seed Board Member Count * | TS, IA, Cert | TS Board; IA Exh A §2; Cert Art III | Directors elected by Series Seed holders; must match across all three docs |
| Mutual Consent Board Member Count * | TS, IA, Cert | TS Board; IA Exh A §2; Cert Art III | Directors elected by mutual vote; must match across all three docs |
| Common Control Holders | IA | Exh A §2 | Key Holders providing services; determines Common board voting power (§7.1) |

## 4. CAP TABLE

| Variable | Doc | Section | Operative Use |
|----------|-----|---------|---------------|
| Authorized Common Shares | Cert | Art V | Total Common authorized; must exceed issued + reserved |
| Authorized Preferred Shares | Cert | Art V | Total Preferred authorized; must cover Series Seed issuance |
| Par Value (Common) | Cert | Art V | Nominal per-share value; typically $0.00001 or $0.0001 |
| Par Value (Preferred) | Cert | Art V | Nominal per-share value; typically matches Common par |
| Common Shares Outstanding Pre-Money * | IA | Exh A §4 | Capitalization baseline; must reconcile with actual cap table |
| Total Post-Money Option Pool Shares * | IA | Exh A §4 | Total reserved for equity incentives; must = Pre-Money Common x (Pool% / (100% - Pool%)) |
| Issued and Outstanding Options | IA | Exh A §4 | Current option grants; subtracted from total pool to get unallocated |
| Unallocated Post-Money Pool Shares * | IA | Exh A §4 | Available for future grants; = Total Pool - Outstanding Options |

## 5. KEY PARTIES

| Variable | Doc | Section | Operative Use |
|----------|-----|---------|---------------|
| Purchaser Names/Addresses | IA | Schedule 1 | Each investor; share allocation; payment amounts; signature pages |
| Key Holder Names | IA | Schedule 1 | Founders/employees subject to vesting (§2.2.3); drag-along (§5.3); voting (§7.1) |
| Key Holder Share Counts | IA | Schedule 1 | Per-holder equity; vesting schedule basis |
| Key Holder Vesting Start Date | TS, IA | TS Key Holder; IA Disclosure Sched | 4-year vesting commencement; Double Trigger reference |
| Officer Name/Title (Company) | IA, Cert | Signature blocks | Corporate authorization; signing capacity |
| Preferred Directors Count | Cert | Art III | Board Composition definition; must match Series Seed Board Member Count in IA |
| Common Directors Count | Cert | Art III | Board Composition definition; must match Common Board Member Count in IA |

## 6. DATES AND DEADLINES

| Variable | Doc | Section | Operative Use |
|----------|-----|---------|---------------|
| Agreement Date * | TS, IA, Cert | TS Header; IA Exh A §1; Cert sig page | Reference point for all time-based provisions; representations made "as of" this date |
| Closing Date | IA | §1.2.1 | When shares issue and consideration transfers |
| Original Incorporation Date | Cert | Cover page §1 | Corporate formation date; historical reference |
| Additional Closing Window | IA | §1.2.2 | Fixed at 90 days from Initial Closing; caps secondary closes |

## CRITICAL CROSS-DOCUMENT DEPENDENCIES

**1. Price Per Share / Original Issue Price**

The Term Sheet "Price Per Share," the Investment Agreement "Purchase Price" (Exhibit A, Section 3), and the Certificate "Original Issue Price" (Article III) must be identical. This single number drives the conversion ratio (Certificate Section 3.1.1), liquidation preference (Certificate Section 1.1), and all cap table math.

**2. Board Composition Counts**

The three director counts (Common, Series Seed, Mutual Consent) appear in the Term Sheet, Investment Agreement Exhibit A Section 2, and Certificate Article III. All three documents must use the same numbers. The Certificate language implements the counts; the Investment Agreement Section 7.1 creates the voting obligations that enforce them.

**3. Cap Table Reconciliation**

The four cap table variables in Investment Agreement Exhibit A Section 4 must reconcile mathematically: Common Shares Outstanding Pre-Money + Series Seed Shares (Total Investment / Purchase Price) + Total Option Pool = Fully Diluted Post-Money. The Unallocated Pool Percent in the Term Sheet must equal Unallocated Pool Shares / Fully Diluted Post-Money. The Certificate Authorized Shares (Article V) must exceed the sum of all issued and reserved shares.

**4. Total Series Seed Investment Amount**

The Investment Agreement definition (Exhibit A, Section 3) must equal the Term Sheet Aggregate Proceeds. This amount caps the total shares issuable (Section 1.2.2: Total Shares Authorized for Sale = Total Amount / Purchase Price) and must equal the sum of all Purchaser investments listed on Schedule 1.

**5. Major Purchaser Threshold**

The dollar threshold (Investment Agreement Exhibit A, Section 3) determines which Schedule 1 purchasers qualify as "Major Purchasers" entitled to information rights (Section 4.1), inspection rights (Section 4.1.3), participation rights (Section 6.1), and MFN carry-forward rights (Section 4.2). The same threshold appears in the Term Sheet Financial Information section. Set this relative to the Purchase Price so the intended investors qualify.

**6. Restricted Person Definition**

The Certificate (Article III, Requisite Holders definition) excludes shares held by a "Restricted Person (as defined in the Investment Agreement)." The Investment Agreement defines this term in Exhibit A, Section 1 as any person on the OFAC SDN list, subject to OFAC sanctions, or owned/controlled by such a person. These definitions must remain linked; if either is amended, the other must be updated to match.

**7. Board Designation Non-Transferability**

All three documents contain harmonized language: board designation rights are not transferable to any assignee of shares unless approved by the Board. This appears in the Term Sheet (Board of Directors section), Investment Agreement (Section 7.1), and Certificate (Article III, Board Composition definition).

## ANCILLARY DOCUMENT GUIDANCE

### Disclosure Schedule (Exhibit D)

The Disclosure Schedule is the Company's opportunity to qualify the representations and warranties in Section 2 of the Investment Agreement. If a representation is not fully accurate without qualification, disclose the exception here. Common disclosures at seed stage include:

- **Section 2.2.3 (Key Holders' Shares):** Vesting schedules, acceleration provisions, and any equity held by departed founders or early contributors.
- **Section 2.6 (Litigation):** Any threatened or pending claims, even informal disputes.
- **Section 2.7 (Intellectual Property):** Third-party IP licenses, open-source dependencies, or any IP not yet assigned to the Company.
- **Section 2.8 (Employee and Consultant Matters):** Any employees or consultants who have not signed CIIA agreements, or who have excluded inventions from their assignment.
- **Section 2.11 (Agreements):** Material contracts exceeding the $50,000 threshold.

If a section has nothing to disclose, it may be omitted. An empty Disclosure Schedule (no next page after Exhibit D) means the Company is making all representations without qualification.

### Investor Questionnaire

Distribute the Investor Questionnaire to each Purchaser before or at the Initial Closing. The questionnaire serves three purposes:

1. **Accredited Investor Verification (Section 2).** Each Purchaser must qualify under at least one category in Rule 501(a) of Regulation D. The Company should retain completed questionnaires as part of its Regulation D compliance file.

2. **Rule 506(d) Bad Actor Screening (Section 3).** A "Yes" answer to any bad actor question does not automatically disqualify the offering, but it requires analysis. The Company should consult counsel to determine whether a disclosure or exclusion exception under Rule 506(d)(2) or (d)(3) applies. If no exception applies, the Purchaser (or its covered person) may need to be excluded from the offering.

3. **OFAC/Sanctions and Foreign Person Status (Sections 4-5).** These responses support the Company's compliance with the Restricted Person provisions in the Investment Agreement and Certificate of Incorporation. A Purchaser who is a "foreign person" triggers the monitoring obligation in Section 3.13 of the Investment Agreement.
