# Frequently Asked Questions: KBEC-1.0

This document explains the intent and usage of the **Kane Boswell Ethical Copyleft (KBEC-1.0)**.

## Quick Summary (Non-Binding)

* **You CAN:** Use it, modify it, share it, use it internally in a business, accept donations.

* **You MUST:** Share the source code (even if running on a server), credit the authors, keep the license.

* **You CANNOT:** Sell the software, hide the source code, use it for malware.

## General Questions

### Is this "Open Source"?

**Technically, no.**
While the source code is open and available, the KBEC includes restrictions on **commercial use** and **ethical use**. Because of these restrictions, it does not meet the strict "Open Source Definition" maintained by the Open Source Initiative (OSI).

* **Correct Term:** "Ethical Source-Available License" or "Source-Available Copyleft."

### Why create a custom license instead of using GPL/MIT?

Standard licenses like MIT or GPL allow anyone to sell the software or use it for harmful purposes. The KBEC was created to ensure this specific software remains:

1. **Free forever** (no paywalls/commercial sales).

2. **Safe** (no malware/spyware).

3. **Open** (no closing the source).

### Will future versions of the license change my rights?

**No.** Future versions of the KBEC will not retroactively change the terms of already-distributed copies. If you received the software under KBEC-1.0, you may continue using it under those terms forever.

## For Developers & Contributors

### Can I use this code in my own project?

**Yes**, as long as:

1. Your project is also free (non-commercial).

2. You keep the KBEC files open-source.

3. You do not use it for malicious purposes.

### Can I use this for business?

**Yes, for internal use only.** You cannot sell the software itself.

* **Allowed:** You can use the software internally to run your business (e.g., a backend tool, data analysis, or workflow automation), even if that business makes money.

* **Forbidden:** You cannot sell, license, or rent the software to your customers. You cannot put the software behind a paywall.

* **Clarification on "Monetization":** "Monetization" refers to charging for the software itself. It does not ban incidental use (like running the software on a personal blog that has ads), provided no fee is charged to access the software.

### Can I accept donations?

**Yes.** You can accept voluntary donations (Patreon, Ko-fi, GitHub Sponsors), provided that paying is **optional** and does not unlock special features in the software.

### I am a security researcher. Does the "No Malware" clause ban me?

**No.** Section 3.2 includes an explicit exception for defensive security research, penetration testing, and education. You can use this software to study vulnerabilities, provided you are authorized to do so and do not use it to cause harm.

## Technical Questions

### Can I minify or compile the code?

**Yes**, but you must also provide the Source Code.
You cannot distribute *only* the compiled binary or minified JS. You must provide a link to the original, readable source code (e.g., a GitHub repository) alongside the compiled version.

### If I put this on a website, do I have to share the code?

**Yes.** Section 3.4 (The "SaaS Clause") requires that if users interact with the software over a network, you must provide a reasonable way for them to download the source code (e.g., a "Source Code" link in the footer).

### Is this compatible with other licenses?

It is designed to be **file-level compatible** with the **Mozilla Public License 2.0 (MPL-2.0)**.

* You can have a project with some files under MPL-2.0 and some under KBEC-1.0.

* However, because KBEC is non-commercial, the *combined* project effectively becomes non-commercial.
