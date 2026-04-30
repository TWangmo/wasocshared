# Adobe Acrobat Vulnerabilities - 20260430001

## Overview

Adobe has released a security update for Adobe Acrobat and Reader for Windows and macOS. This update addresses critical and important vulnerabilities. Successful exploitation could lead to arbitrary code execution and arbitrary file system read.
Adobe is not aware of any exploits in the wild for any of the issues addressed in these updates.

## What is vulnerable?

| Product(s) Affected           | Version(s)                                                          | CVE                                                               | CVSS | Severity |
| ----------------------------- | ------------------------------------------------------------------- | ----------------------------------------------------------------- | ---- | -------- |
| Acrobat DC, Acrobat Reader DC | Version prior to 26.001.21411                                       | [CVE-2026-34622](https://nvd.nist.gov/vuln/detail/CVE-2026-34622) | 8.6  | High     |
| Acrobat 2024                  | Version Win: prior to 24.001.30362 <br/> Mac: prior to 24.001.30360 | [CVE-2026-34622](https://nvd.nist.gov/vuln/detail/CVE-2026-34622) | 8.6  | High     |

## What has been observed?

The WASOC has not received any reports of exploitation of this vulnerability on Western Australian Government networks at the time of writing.

## Recommendation

The WASOC recommends administrators apply the solutions as per vendor instructions to all affected devices within expected timeframes (refer [Patch Management](../guidelines/patch-management.md)):

- Adobe Security Bulletin: <https://helpx.adobe.com/security/products/acrobat/apsb26-44.html>
