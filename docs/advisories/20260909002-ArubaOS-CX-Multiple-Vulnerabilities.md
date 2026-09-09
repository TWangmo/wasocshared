# ArubaOS-CX Multiple Vulnerabilities - 20260909002

## Overview

The WASOC has been made aware of Critical multiple vulnerabilities exist in a daemon of AOS-CX that may allow for improper processing of malformed input. An unauthenticated remote attacker could exploit these vulnerabilities by sending specially crafted packets to the affected service. Successful exploitation could result in remote code execution with elevated privileges.

## What is vulnerable?

| Product(s) Affected | Version(s) | CVE                                                                                                                                      | CVSS         | Severity                                                       |
| ------------------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------- | ------------ | -------------------------------------------------------------- |
| ArubaOS-CX   | Versions <br> - 10.18.0000 prior to 10.18.0001 <br> - 10.17.0000 prior to 10.17.1021 <br> - 10.16.0000 prior to 10.16.1051 <br> - 10.13.0000 prior to 10.13.1180 <br> - 10.10.0000 prior to 10.10.1180 <br> - 10.10.1180 and below (EOM)  | [CVE-2026-73749](https://nvd.nist.gov/vuln/detail/cve-2026-73749)                                                                        | 9.8          | **Critical**                                   |


## What has been observed?

The WASOC has not received any reports of exploitation of this vulnerability on Western Australian Government networks at the time of writing.

## Recommendation

The WASOC recommends administrators apply the solutions as per vendor instructions to all affected devices within expected timeframes (refer [Patch Management](../guidelines/patch-management.md)):

- HPE: <https://support.hpe.com/hpesc/public/docDisplay?docId=hpesbnw05134en_us>

## Additional References

- CVE: <https://www.cve.org/CVERecord?id=CVE-2026-73749>
