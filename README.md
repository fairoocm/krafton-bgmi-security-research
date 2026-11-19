
# BGMI Security Research — Payment and Entitlement Reconciliation

An independent security research case study documenting a potential issue involving BGMI's in-game currency (UC), payment processing, and entitlement reconciliation.

## Project Overview

This research concerns a potential inconsistency between an app-store purchase refund and the corresponding in-game currency entitlement.

The concern was reported to Battlegrounds Mobile India (BGMI) Player Support for review. This repository documents the high-level research concern, responsible-disclosure timeline, and general defensive recommendations.

**Important:** This is an independently reported potential issue. The available correspondence confirms that Player Support acknowledged the report and said it would be forwarded for review. It does not confirm that KRAFTON reproduced or validated a vulnerability.

## Research Summary

The original report raised a concern that an in-game UC entitlement might not be reconciled correctly following a payment reversal.

Potential security areas involved:

- Payment and transaction verification
- In-game entitlement integrity
- Digital currency and account economy protection
- Fraud detection and abuse prevention

The initial report stated that the behaviour had been personally observed. However, this public repository does not include the technical procedure or raw evidence needed for independent reproduction.

## Responsible Disclosure Timeline

**9 May 2025 — Player Support acknowledgement**

BGMI Player Support acknowledged receipt of the detailed report and stated that the information would be forwarded to its dedicated security and anti-fraud team for further review and investigation.

The response invited additional supporting evidence.

This acknowledgement is not confirmation of a vulnerability, successful reproduction, remediation, or a bug bounty award.

## Potential Impact

If the reported behaviour were reproducible and exploitable, it could potentially affect:

- Integrity of in-game currency entitlements
- Payment and transaction reconciliation
- Fairness of the in-game economy
- Financial and fraud-risk controls

These are potential impacts, not confirmed losses or independently verified abuse.

## Defensive Recommendations

This research highlights the importance of:

- Server-side verification of purchase transactions
- Reliable reconciliation of payment and entitlement states
- Correct handling of refunds and payment reversals
- Auditable transaction and entitlement records
- Monitoring for suspicious purchase and refund patterns

## Documentation

- [Independent Security Research Case Study](docs/CASE-STUDY.md)
- [Defensive Security Recommendations](docs/DEFENSIVE-RECOMMENDATIONS.md)


## Scope and Limitations

- This repository is a sanitized, high-level case study.
- No exploit steps, refund procedures, private correspondence, account information, transaction records, or sensitive evidence are published.
- The original report's claims about abuse scale and financial impact have not been independently verified.
- No claim is made that the issue remains active today.
- No claim is made that KRAFTON confirmed, reproduced, or fixed the reported issue.

## Responsible Disclosure and Ethics

The purpose of this documentation is to demonstrate security research, responsible reporting, and an understanding of payment-security risks.

It is not intended to facilitate exploitation, payment abuse, account trading, or unauthorized testing.

## Researcher

**Bilal Fairoos**

Independent cybersecurity learner and security researcher.


