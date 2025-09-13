# Team Ethertaco Public License (TEPL) Version History

This document records the key changes and evolution of the Team Ethertaco Public License (TEPL) family of licenses.

---

## Version 1.5 - [Effective Date: September 13, 2025] - Current Stable

**Focus:** Enhanced commercial evaluation flexibility, clarified Steward succession and dormancy, and refined AGPLv3 compatibility.

**Key Changes from Version 1.4:**

*   **Definitions (Section 1):**
    *   **1.4 "Commercial Use":** For the "Explicitly Excluded from Commercial Use" section, the internal testing/development evaluation period (originally 90 days) now includes an option for **extension up to a maximum of 180 days**, upon written request and technical justification to the Copyright Steward.
    *   **1.8 "Copyright Steward":**
        *   Clarified that the process for succession of the Copyright Steward **should be documented in an `ADMIN.md` file** in the source repository.
        *   Introduced a new provision: if the Steward becomes unresponsive to all licensing inquiries for a consecutive period of **180 days**, its authority to grant new "Verified Authorizations" and "Reinstatements" is considered **dormant** until reinstated by a public declaration from a successor Steward.
*   **Permissions and Conditions (Section 2):**
    *   **2.4 License Compatibility and Integration:**
        *   **AGPLv3 Compatibility Note:** The note now clarifies that a **reversion from AGPLv3 back to TEPL is possible** under specific, strict conditions (only for modules not combined with other AGPLv3-native code, and requiring unanimous, public, and verifiable consent of the Copyright Steward). This provides a more flexible "one-way bridge" with a narrow, controlled path back.
        *   **NEW: GPLv2 Incompatibility Note:** Explicitly added a note stating: `This License is not compatible with the GNU General Public License, Version 2.`
*   **Copyright Notice:**
    *   Updated the contact email for all licensing inquiries to `license@ethertaco.cn`. (Note: This change reflects a broader policy shift for all future licenses.)

---

## Version 1.4 - [Effective Date: August 21, 2025] - Deprecated

**Focus:** Formalizing the "Copyright Steward" role, refining patent retaliation, and streamlining contact.

**Key Changes from Version 1.3.1:**

*   **Definitions (Section 1):**
    *   **NEW SECTION 1.8: "Copyright Steward":** Introduced and formally defined the "Copyright Steward" as the sole authority for administering the license, including granting "Verified Authorizations" and "Reinstatements." This centralizes license management and clarifies who to contact for official inquiries.
    *   **1.4 "Commercial Use":** Removed the 90-day evaluation period extension request, reverting to a single 90-day evaluation period.
    *   **1.6 "Verified Authorization":** Updated to explicitly state that the agreement is executed with the **"Copyright Steward"**, replacing previous references to "copyright holders" or "original copyright holders".
*   **Permissions and Conditions (Section 2):**
    *   **NEW SECTION 2.6: "Patent Retaliation":** Introduced a clause that terminates any patent licenses granted if a user initiates patent litigation against any entity related to the Software or a Modification (unless it's a defensive response to a first-filed lawsuit). This protects the community from aggressive patent actions.
*   **Copyright Notice:**
    *   Updated the contact email for all licensing inquiries to `license@ethertaco.cn`.
    *   Explicitly named "Team Ethertaco & QinShenYu (the "Copyright Steward")" in the Copyright Notice, clarifying the identity of the Steward.

---

## Version 1.3.1 - [Effective Date: July 1, 2025] - Deprecated

**Focus:** Critical legal and security update to address the "patent trap" risk.

**Key Changes from Version 1.3.0:**

*   **Permissions and Conditions (Section 2):**
    *   **NEW SECTION 2.5: Grant of Patent License for Non-Commercial Use:** This is the sole and critical change in this version. It adds an explicit, limited patent grant for non-commercial use, protecting community users and contributors from potential patent infringement claims from other contributors within the ecosystem. This resolves a major legal ambiguity present in all prior versions.

---

## Version 1.3.0 - [Effective Date: June 28, 2025] - Deprecated

**Focus:** Major legal enhancement over v1.2, but now superseded by v1.3.1 due to the absence of a patent clause.

**Key Changes from Version 1.2:**

*   **Definitions (Section 1):**
    *   **1.4 "Commercial Use":** Added "Safe Harbor Clarifications" to explicitly include providing paid professional services and using the Software in for-profit educational programs as Commercial Use.
*   **Termination (Section 4):**
    *   **4.2 Reinstatement:** Formally linked the reinstatement authority to the "copyright holders (as identified in the project's `AUTHORS` file)".
*   **Copyright Notice:**
    *   Added a note encouraging attribution in project documentation/About page, though not strictly required.
*   **Notable Absence (Critical Flaw):** This version **did not** include an explicit patent grant for non-commercial use, which was identified as a critical risk to the community and subsequently addressed in v1.3.1.

---

## Version 1.2 - [Effective Date: June 23, 2025] - Deprecated

**Focus:** Enhanced legal clarity, user responsibility, and specific governance notes.

**Key Changes from Version 1.1:**

*   **Definitions (Section 1):**
    *   **1.4 "Commercial Use":**
        *   **Explicitly Excluded from Commercial Use:** Clarified the 90-day evaluation period for for-profit organizations, specifying it's for the "sole purpose of evaluating whether to seek a Verified Authorization."
    *   **1.6 "Verified Authorization":** Updated to refer to "original copyright holders".
*   **Permissions and Conditions (Section 2):**
    *   **2.4 License Compatibility and Integration:**
        *   Added a "*Note on AGPLv3 Compatibility*" (Section 2.4.a) to clarify the "one-way bridge" nature and its irreversibility. This note also first mentions the role of contributors/project discretion in such a migration.
*   **Legal Provisions (Section 3):**
    *   **3.1 Governing Law and Jurisdiction:** Added a "*Note on Jurisdiction*" explaining the choice of Hong Kong SAR.
    *   **3.3 User's Responsibility for Compliance:** Retained this important clause.
*   **Termination (Section 4):**
    *   **4.2 Reinstatement:** Significantly changed. Reinstatement is **no longer automatic for a first-time offense**. It now requires a written request to the copyright holders and is granted at their sole discretion after verification, after the violation has been fully cured and all infringing distributions rectified/removed.
*   **Copyright Notice:**
    *   Added a sentence guiding users to an `AUTHORS` file for identifying copyright holders with authority to grant Verified Authorization.

---

## Version 1.1 - [Effective Date: June 21, 2025] - Deprecated

**Focus:** Initial major revision to address ambiguities in v1.0, particularly around "Commercial Use" and establishing a clearer legal footing.

**Key Changes from Version 1.0:**

*   **Preamble:**
    *   Shifted from calling TEPL "open-source" to "**source-available**".
    *   Added an explicit "**Disclaimer**" stating non-OSI approval and user responsibility.
*   **Definitions (Section 1):**
    *   **1.4 "Commercial Use":**
        *   Replaced the "Quantitative Threshold" (30% functionality / 25% revenue) with the qualitative **"Integral Test"** focusing on whether the software is "integral to that product or service's core functionality."
        *   Added an *Example* to clarify the "Integral Test."
        *   Refined "Explicitly Excluded from Commercial Use" with clearer scenarios (e.g., 90-day evaluation for for-profits).
    *   **1.6 "Verified Authorization":** Remained focused on "original copyright holders."
*   **Permissions and Conditions (Section 2):**
    *   **2.1 Grant of Rights:** More explicitly tied all granted rights (use, modify, distribute) to "non-Commercial Use."
    *   **2.2 Restriction on Commercial Use:** Reinforced the prohibition and the philosophical stance against dual-licensing.
    *   **2.4 License Compatibility:** Retained the AGPLv3 compatibility.
*   **Legal Provisions (Section 3):**
    *   Established Hong Kong SAR as the governing jurisdiction and detailed the dispute resolution process (negotiation, mediation, arbitration).
    *   Introduced "Resolution of Ambiguity" (favoring non-commercial status presumption).
    *   Added "User's Responsibility for Compliance."
*   **Termination (Section 4):**
    *   **4.2 Reinstatement:** Allowed for reinstatement if cured within 30 days and it was a "first-time offense."

---

## Version 1.0 - [Effective Date: June 20, 2025] - Deprecated

**Focus:** Initial strong anti-commercialization stance with an emphasis on community reciprocity.

**Key Features (and subsequent pain points addressed in later versions):**

*   **Preamble:** Described TEPL as "open-source" and aimed to protect creators' rights.
*   **Definitions (Section 1):**
    *   **1.4 "Commercial Use":** Defined by a **"Quantitative Threshold"** (e.g., >30% of product's unique functionality OR >25% of service's revenue). This proved difficult to measure and enforce.
    *   **1.6 "Verified Authorization":** Required from "original copyright holders" with specific contact email and disclosure requirements (e.g., technical architecture, revenue model).
*   **Permissions and Conditions (Section 2):**
    *   **2.1 Basic Rights Granted:** Stated "Permission to use the Software for any purpose" which somewhat conflicted with later "non-commercial derivative works" and explicit commercial use restrictions.
    *   **2.2 Commercial Use Restrictions:** Required authorization through a specific email.
    *   **2.5 License Compatibility:** Included a "Multi-license Declaration" allowing choice between TEPL 1.0 or AGPLv3.
*   **Legal Provisions (Section 3):**
    *   **3.3 Ecosystem Integration:** Stated "TEPL obligations terminate when combined with AGPLv3 code," a very broad "escape hatch."
*   **Termination (Section 4):**
    *   **4.1 Automatic Termination:** Included "Patent litigation initiation" as a cause for termination.
    *   **4.2 Reinstatement:** Allowed for first-time offense cure within 30 days.
*   **Copyright Notice:**
    *   Included a contact email for license inquiries.

---

*This history is maintained by Team Ethertaco. For the full text of each license version, please refer to the respective .md files in this repository.*