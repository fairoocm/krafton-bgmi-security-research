
# BGMI UC Payment and Entitlement Reconciliation
## Independent Security Research Case Study

**Researcher:** Bilal Fairoos  
**Platform:** Battlegrounds Mobile India (BGMI)  
**Research category:** Payment Security / Digital Entitlement Integrity  
**Disclosure approach:** Responsible Disclosure  
**Report acknowledgement:** 9 May 2025

---

## 1. Background

This case study documents an independent security concern reported to BGMI Player Support.

The concern involved a possible inconsistency between payment refunds processed through mobile app stores and the corresponding in-game UC entitlement.

The research focused on the importance of correctly reconciling payment status with digital items or currency credited to a player's account.

## 2. Reported Observation

In my original disclosure, I reported that UC appeared to remain credited to a BGMI account after a purchase refund.

I raised this as a potential payment and entitlement reconciliation weakness.

The original report stated that I had personally observed the behaviour and had supporting evidence. However, the sensitive technical material and original evidence are not included in this public case study.

This repository does not independently reproduce or validate the reported behaviour.

## 3. Potential Security Impact

If the reported behaviour were reproducible, it could potentially create risks involving:

- In-game currency entitlement integrity.
- Payment reversal and transaction reconciliation.
- Abuse of digital purchase workflows.
- Financial and fraud-prevention controls.
- Fairness and trust in the in-game economy.

The original report also raised concerns about possible account resale and organized abuse. Those claims have not been independently verified and are not presented here as established facts.

## 4. Responsible Disclosure

I reported the concern directly to BGMI Player Support and requested communication with the relevant security or engineering team.

The purpose of the disclosure was to bring the potential issue to the company's attention so it could be reviewed through an appropriate internal process.

## 5. Vendor Acknowledgement

On **9 May 2025 at 12:40 PM IST**, BGMI Player Support acknowledged receipt of my detailed report.

The response:

- Thanked me for sharing the report.
- Stated that the information would be forwarded to its dedicated security and anti-fraud team for further review and investigation.
- Invited me to provide additional supporting evidence.

The response also stated that Player Support could not process a refund after a purchase was successfully made.

This correspondence confirms acknowledgement and referral for review. It does not establish that the security team validated or reproduced the reported issue.

## 6. Research Evidence and Privacy

The original report stated that supporting material was available, including screenshots, video evidence, transaction records, and related observations.

Those materials are intentionally excluded from this public repository to protect privacy and avoid disclosing sensitive information.

No private correspondence, account identifiers, transaction details, or operational reproduction instructions are published here.

## 7. Limitations and Verification Status

The following distinctions are important:

- The concern was reported by an independent researcher.
- BGMI Player Support acknowledged the report.
- Support stated that it would be forwarded for further review and investigation.
- No confirmation of successful vulnerability reproduction is available in the correspondence presented here.
- No verified remediation, public security advisory, or bug bounty award is documented here.
- The current status of the reported behaviour is unknown.

Therefore, this case study describes a **potential security issue**, not a confirmed vulnerability.

## 8. Lessons Learned

This research highlighted the importance of:

- Understanding payment and digital-entitlement security.
- Documenting security observations clearly.
- Reporting potential vulnerabilities responsibly.
- Protecting sensitive evidence during disclosure.
- Distinguishing vendor acknowledgement from technical validation.

## 9. Conclusion

This case demonstrates an independent security concern being communicated to a platform's support team through responsible disclosure.

Although the available response does not confirm the vulnerability, the report and acknowledgement provide a practical example of security communication, risk identification, and responsible reporting.

---

**Author:** Bilal Fairoos  
**Project:** Independent BGMI Security Research  
**Repository:** `bgmi-security-research`

*This document is for educational and portfolio purposes. It does not provide instructions for exploiting payment systems or manipulating in-game currency.*
