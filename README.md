# Kane Boswell Ethical Copyleft (KBEC-1.0)

Clean license, clean software.

## Overview

The **Kane Boswell Ethical Copyleft (KBEC)** is a custom software license designed for developers who want to share their source code with the world but refuse to let it be exploited for commercial profit or malicious harm.

It is a **file-level** license (similar structure to MPL-2.0) but with added ethical and economic guardrails.

### Key Principles

* **Free Forever:** The software cannot be sold, licensed for a fee, or put behind a paywall.

* **Ethical Safety:** The software cannot be used to create malware, spyware, or harmful tools.

* **Strong Copyleft:** If you use this code, you must keep your modifications open. You cannot close the source.

* **SaaS/Network Openness:** If you run this software on a website/server, you must provide a way for users to download the source code.

## How to Apply This License

To license your project under KBEC-1.0, follow these two steps:

### 1. Add the License File

Create a file named `LICENSE` in the root directory of your project and paste the full text of the **Kane Boswell Ethical Copyleft**.

### 2. Add the File Header

At the top of each source code file (e.g., `.js`, `.py`, `.sb3` notes), add the following comment header:

```js
// This file is part of [Your Project Name].
// Licensed under the Kane Boswell Ethical Copyleft-1.0 (KBEC-1.0).
// You may not sell this software. You must keep it open source.
// See the LICENSE file for details.
```

*(Note: Adjust the comment syntax `//`, `#`, or `<!-- -->` to match your programming language.)*

## Common Questions

**Is this "Open Source"?** Technically, no. Because it forbids commercial use and restricts malicious use, it does not meet the strict "Open Source Definition" (OSD). It is correctly classified as an **Ethical Source-Available** license.

**Can companies use this?** Yes, but only for **internal use**. They cannot sell the software to customers or package it as a product.

**Can I use this with other licenses?** Yes. KBEC is designed to be **file-level compatible** with the **Mozilla Public License 2.0 (MPL-2.0)**. You can mix KBEC files and MPL files in the same project, though the non-commercial rules will effectively apply to the final combined product.

[**Read the Full FAQ**](./FAQ.md) for more details.

## Disclaimer

*This license and the accompanying summary are provided "as-is" without warranty of any kind. The author is not a law firm and does not provide legal advice.*
