# ArubaOS-CX Multiple Vulnerabilities - 20260909002

## Overview

The WASOC has been made aware of multiple vulnerabilities in ArubaOS-CX that may allow for improper processing of malformed input. Successful exploitation could result in remote code execution with elevated privileges.

## What is vulnerable?

| Product(s) Affected | Version(s) | CVE                                                                                                                                      | CVSS         | Severity                                                       |
| ------------------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ------------ | -------------------------------------------------------------- |
| ArubaOS-CX   | Versions <br>AOS-CX 10.18.1002 and above <br>-AOS-CX 10.17.1030 and above <br>-AOS-CX 10.16.1060 and above<br>-AOS-CX 10.13.1190 and above<br>-AOS-CX 10.10.1181 and above (EOM)  | [CVE-2026-73749](https://nvd.nist.gov/vuln/detail/cve-2026-73749)                                                                        | 9.8          | **Critical**                                   |


## What has been observed?

The WASOC has not received any reports of exploitation of this vulnerability on Western Australian Government networks at the time of writing.

## Recommendation

The WASOC recommends administrators apply the solutions as per vendor instructions to all affected devices within expected timeframes (refer [Patch Management](../guidelines/patch-management.md)):

- HPE: <https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbnw05134en_us>
