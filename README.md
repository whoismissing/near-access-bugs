# near-access-bugs
Collection of near access bugs

#### bluetooth

| CVE | CWE | Patch | Description |
| -------- | -------- | -------- | -------- |
| [CVE-2019-11516](https://github.com/advisories/GHSA-6624-pmgq-j9j4) | [CWE-122](https://cwe.mitre.org/data/definitions/122.html) | | Heap-based buffer overflow during device inquiry handling of Extended Inquiry Responses (EIRs) in the Bluetooth component of the Broadcom codebase. |
| [CVE-2020-0022](https://github.com/advisories/GHSA-55v6-vvqw-j3qq) | [CWE-787](https://cwe.mitre.org/data/definitions/787.html) | [Patch](https://android.googlesource.com/platform/system/bt/+/3cb7149d8fed2d7d77ceaa95bf845224c4db3baf%5E%21/#F0) | Out-of-bounds write due to incorrect bounds calculation of l2cap packet length in reassembly logic when remote sends more data than expected. |

#### wifi

| CVE | CWE | Patch | Description |
| -------- | -------- | -------- | -------- |
| [CVE-2017-0561](https://project-zero.issues.chromium.org/issues/42450052#attachment59035487) | [CWE-122](https://cwe.mitre.org/data/definitions/122.html) | | Heap overflow in TDLS Teardown Request while handling Fast Transition Information Element (FTIE) in Broadcom Wi-Fi HardMAC system-on-chip firmware. |
| CVE-2017-0569 | [CWE-122](https://cwe.mitre.org/data/definitions/122.html) | | Heap overflow in "dhd_handle_swc_evt" of bcmdhd kernel driver due to mismatched allocated buffer and memcpy sizes. |
| [CVE-2017-11120](https://project-zero.issues.chromium.org/issues/42450316) | [CWE-787](https://cwe.mitre.org/data/definitions/787.html) | | Out-of-bounds write when handling 802.11k Neighbor Report Response in Broadcom Wi-Fi firmware. |
| [CVE-2017-9417](https://blackhat.com/docs/us-17/thursday/us-17-Artenstein-Broadpwn-Remotely-Compromising-Android-And-iOS-Via-A-Bug-In-Broadcoms-Wifi-Chipsets-wp.pdf) | [CWE-122](https://cwe.mitre.org/data/definitions/122.html) | | Heap overflow in association packet parsing of Wireless Multimedia Extensions (WMM) in Broadcom Wi-Fi firmware. |
