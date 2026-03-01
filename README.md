# Team Ethertaco License Family Repository

> [!IMPORTANT]
> **Latest Update (March 1, 2026): The Team Ethertaco License Family is now live.**
>
> We have officially released the **Lesser Team Ethertaco Public License (LTEPL) Version 1.0**, which serves as a companion to our flagship **TEPL Version 1.5**.
>
> **Which one should I use?**
> *   **Use [TEPL v1.5](TEPL-1.5.md)** for standalone applications (e.g., a server core, a complete tool). It provides strong copyleft protection.
> *   **Use [LTEPL v1.0](LTEPL-1.0.md)** for software libraries, APIs, or modules (e.g., a base library, a plugin) that are intended to be used by other projects, including commercial ones.

---

## About the TEPL Family

The Team Ethertaco Public License (TEPL) family consists of **source-available, strong copyleft licenses** designed to protect community-driven and personal projects from commercial exploitation. 

Our core philosophy is simple: **Collaborate freely, but do not commoditize.** 

*   **TEPL (The Fortress):** Ensures that all modifications and network-based distributions of the software give back to the community under the same terms.
*   **LTEPL (The Bridge):** Acts as a specialized bridge license, allowing the core technology of a protected library to be adopted by a broader range of software (including commercial "Combined Works"), while ensuring the library itself remains public property.

**Disclaimer**: These licenses are not approved by the Open Source Initiative (OSI). They are intended for authors who prioritize non-commercial reciprocity over commercial flexibility.

## Choosing Your Version

| Scenario | Recommended License |
| :--- | :--- |
| Standalone Software / End-user App | **[TEPL Version 1.5](TEPL-1.5.md)** |
| Shared Library / API / Framework | **[LTEPL Version 1.0](LTEPL-1.0.md)** |

---

## Using TEPL/LTEPL in Your Project

Include the full text of the chosen license in your repository and add the appropriate header to each source file.

### Option A: TEPL 1.5 Header (For Applications)
```java
/*
 * Copyright © [Start Year]-[Current Year] [Your Name / Your Company]
 * (Copyright Steward as defined in TEPL Version 1.5)
 * Licensed under the Team Ethertaco Public License (TEPL) Version 1.5.
 * Text: https://github.com/Ethertaco/TEPL---The-Team-Ethertaco-Public-License/blob/main/TEPL-1.5.md
 *
 * KEY TERMS: NON-COMMERCIAL USE ONLY; STRONG COPYLEFT (SAAS COVERED); 
 * PATENT GRANT (NON-COMMERCIAL); NO WARRANTY.
 */
```

### Option B: LTEPL 1.0 Header (For Libraries)
```java
/*
 * Copyright © [Start Year]-[Current Year] [Your Name / Your Company]
 * (Copyright Steward as defined in LTEPL Version 1.0)
 * Licensed under the Lesser Team Ethertaco Public License (LTEPL) Version 1.0.
 * Text: https://github.com/Ethertaco/TEPL---The-Team-Ethertaco-Public-License/blob/main/LTEPL-1.0.md
 *
 * KEY TERMS: PERMITS COMMERCIAL COMBINED WORKS; LIBRARY ITSELF REMAINS 
 * NON-COMMERCIAL (VIA TEPL 1.5); LIBRARY REPLACEMENT RIGHTS RESERVED; NO WARRANTY.
 */
```

---

## Administration and Succession

As per the licenses, the **Copyright Steward** is the central authority for granting Verified Authorizations and Reinstatements. 

*   **Current Steward:** Team Ethertaco & QinShenYu
*   **Official Contact:** `license@ethertaco.cn`
*   **Governance:** For details regarding the Steward role and the succession policy in case of dormancy, please see **[ADMIN.md](ADMIN.md)**.

## License for This Repository

The content of this repository itself is licensed under the **Team Ethertaco Public License (TEPL) Version 1.5**.

Copyright © 2025-2026 Team Ethertaco, QinShenYu.