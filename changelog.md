# Changelog

All notable changes to **The 2026 Hugging Face Autonomous-Agent Intrusion** public investigation report are documented here.

This changelog tracks the report's internal revision numbers. These are separate from GitHub release tags.

Current report revision: **Revised Version 9**

Evidence current through: **September 16, 2026**  
Current document revision date: **September 17, 2026**

---

## Revised Version 9
### September 17, 2026

Finalized the public-release presentation.

Changes:

- Separated the report's evidence cutoff date from the document revision date.
- Added:
  - **Evidence Current Through: September 16, 2026**
  - **Revision Date: September 17, 2026**
- Updated document metadata to remove an obsolete Version 5 title artifact.
- Advanced visible version identifiers to **Revised Version 9**.
- Added a methodological caveat explaining that the incident narrative was reconstructed from public evidence independently of the author's frameworks before those frameworks were applied analytically.

No substantive factual finding, incident chronology date, numerical figure, source citation, or analytical conclusion was changed by this revision.

---

## Revised Version 8

Added timestamped public evidence showing that key concepts from the author's 11 Controls framework were publicly articulated before publication of the book and before the July 2026 incident.

Changes:

- Added two December 15, 2025 DEV Community articles by the author:
  - *Why Identity Is Mission-Critical in AI-to-AI Systems*
  - *Why Rate Limiting Still Matters in AI-to-AI Systems*
- Added these publications as References [15] and [16].
- Expanded Section 9.1, **Pre-Incident Framework Alignment**.
- Distinguished between:
  - the published books as formal framework sources; and
  - the earlier blog posts as timestamped evidence of prior public disclosure.
- Documented earlier discussion of:
  - machine-speed autonomous-agent risk;
  - the limitations of identity alone;
  - behavioral throttling;
  - contextual authorization; and
  - continuous access control.

---

## Revised Version 7

Added a dedicated AI Use Disclosure.

Changes:

- Added a full AI Use Disclosure page.
- Documented use of **OpenAI ChatGPT** for:
  - research support;
  - editing;
  - proofreading;
  - fact-checking;
  - cross-source comparison;
  - claim verification;
  - technical review.
- Documented use of **Anthropic Claude** for:
  - research support;
  - editing;
  - proofreading;
  - fact-checking;
  - source comparison;
  - independent review of report language and claims.
- Clarified that AI-generated output was not treated as:
  - primary evidence;
  - factual authority; or
  - independent corroboration.
- Added verification and human-oversight language.
- Updated Section 2 to cross-reference the AI Use Disclosure.

---

## Revised Version 6

Added explicit analysis of the relationship between the July 2026 incident and the author's pre-existing AI security and governance frameworks.

Changes:

- Added Section 9.1, **Pre-Incident Framework Alignment**.
- Documented publication dates for:
  - *11 Controls for Zero-Trust Architecture in AI-to-AI Multi-Agent Systems* - January 31, 2026;
  - *Gestalts Without God* - March 24, 2026.
- Clarified that neither work predicted:
  - Hugging Face as the victim;
  - OpenAI as the source of the agents;
  - the specific vulnerabilities used; or
  - the exact attack chain.
- Identified correspondence between the incident and previously documented failure classes involving:
  - coordinated autonomous systems;
  - machine-speed operation;
  - delegated authority;
  - persistent communication;
  - shared information;
  - excessive trust;
  - containment failure; and
  - governance dependent on expected behavior.
- Expanded the report's discussion of how the 11 Controls framework maps to observed incident conditions.
- Revised Findings 13 and 14 to explicitly identify the frameworks as pre-incident publications.
- Updated references with exact publication dates.

---

## Revised Version 5

Conducted a substantial source-level and editorial review.

Changes:

- Restructured the evidence-classification system so findings separately report:
  - **Status:** Confirmed / Corroborated / Assessed / Unresolved
  - **Confidence:** High / Moderate / Low, where applicable
- Added the April 20 Artifactory arbitrary-file-write event.
- Added the May 26 Artifactory SSRF event and distinguished it from the separate Hugging Face activity occurring later that day.
- Corrected the source-control and CI section to reflect that:
  - a CI workflow actually executed a network beacon; and
  - a separate, more dangerous CI pivot attempt was blocked.
- Corrected the CVE-2026-53362 severity description to match Red Hat's **Important** rating and container-escape classification.
- Added a Hugging Face-side detection-latency analysis.
- Added an **Observed Limits of Impact** section.
- Corrected attribution of dry-run cloud API activity to Hugging Face's technical account.
- Expanded the May forensic pivots.
- Distinguished:
  - `Nyx9/temptestlf8eb0`, which contained `hello.txt`; and
  - `Nyx9/tmpdata177`, which contained `formbin.xlsx`.
- Clarified limitations surrounding account and token attribution.
- Refined Finding 3's evidentiary classification.
- Refined Finding 11's malware wording.
- Converted references into cleaner clickable citations.
- Removed general reporting-guidance references that lacked specific citations.
- Adjusted page layout so the Section 8 control-failure table would not split awkwardly across pages.

No previously verified incident date, numerical figure, or source citation was changed solely as a result of this editorial pass.

---

## Revised Version 4

Performed a wording and attribution review focused on avoiding overly close paraphrasing of source material.

Changes:

- Reworded passages concerning:
  - network egress;
  - the Modal-hosted workload;
  - CVE-2026-66384; and
  - CVE-2026-53362.
- Reduced language that too closely mirrored OpenAI or Hugging Face source wording.
- Preserved the underlying:
  - facts;
  - figures;
  - dates; and
  - citations.

---

## Revised Version 3

Performed a targeted source-verification pass.

Changes:

- Rechecked five claims raised during editorial review against primary sources.
- Confirmed four of the reviewed claims.
- Corrected one attribution error involving network egress.

---

## Revised Version 2

Corrected several internal inconsistencies identified during review.

Changes:

- Corrected a mismatch between the report's four-category evidence framework and its use of High / Moderate / Low confidence terminology.
- Corrected a confidence inconsistency concerning the May 2026 activity.
- Expanded the explanation of the containment-escape mechanism.
- Added supporting citations for several previously uncited numerical claims.

---

## Version 1

Initial report version.

The current Appendix A does not contain a detailed change record for the original Version 1.

---

# Revision Principles

Revisions to this report are intended to remain transparent and evidence-driven.

Future revisions should identify whether a change involves:

- newly available evidence;
- correction of a factual error;
- correction of source attribution;
- a change in evidentiary status or confidence;
- a change in analytical interpretation;
- additional mitigation or governance analysis; or
- editorial or formatting changes that do not alter findings.

Where new public evidence materially changes an existing conclusion, the affected finding should be revised explicitly rather than silently overwritten.

---

# Public Release Versioning

The report's internal revision number and the repository's public release version are separate.

For example:

- **Report:** Revised Version 9
- **GitHub Release:** v1.0

Future public releases may use standard repository versioning while preserving the report's own revision history inside the document and this changelog.
