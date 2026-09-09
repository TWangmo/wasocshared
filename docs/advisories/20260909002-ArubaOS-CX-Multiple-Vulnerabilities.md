# ArubaOS-CX Multiple Vulnerabilities - 20260909002

## Overview

HPE have published updated advisory addressing multiple vulnerabilities affecting their HPE Aruba Networking ArubaOS-CX (AOS-CX) products. Successful exploitation by threat actor could result in remote code execution with elevated privileges.

## What is vulnerable?

| Product(s) Affected | Version(s) | CVE                                                                                                                                      | CVSS         | Severity                                                       |
| ------------------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ------------ | -------------------------------------------------------------- |
| HPE Networking AOS-CX  | Versions <br>-10.18.0001 prior to 10.18.1002 <br>-10.17.1021 prior to 10.17.1030 <br>-10.16.1051 prior to 10.16.1060<br>-10.13.1180 prior to 10.13.1190 <br>-10.10.1180 prior to 10.10.1181 | [CVE-2026-73749](https://nvd.nist.gov/vuln/detail/cve-2026-73749)                                                                        | 9.8          | **Critical**                                   |


## What has been observed?

The WASOC has not received any reports of exploitation of this vulnerability on Western Australian Government networks at the time of writing.

## Recommendation

The WASOC recommends administrators apply the solutions as per vendor instructions to all affected devices within expected timeframes (refer [Patch Management](../guidelines/patch-management.md)):

- HPE: <https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbnw05134en_us>
