# DOMAIN-ONLY Filter Lists
**Last Updated:** 2021-01-04 11:37:23

- [Details](#details)
- [Usage](#usage)
  - [Using with Pi-Hole](#using-with-pi-hole)
  - [Using with other tools](#using-with-other-tools)
- [The Lists](#the-lists)
  - [EasyList](#easylist-domains-only) (Domains-only)
  - [EasyPrivacy](#easyprivacy-domains-only) (Domains-only)
  - [AdGuard Simplified Domain Names Filter](#adguard-simplified-domain-names-filter-domains-only) (Domains-only)
  - [NoCoin Filter List](#nocoin-filter-list-domains-only) (Domains-only)
- [License](#license)
- [Reporting Conversion Issues](#reporting-conversion-issues)

&nbsp;

# Details:
These are "DOMAIN-ONLY" **converted** versions of various popular original filter / blocking lists.
They have been modified from their original versions by scripts at: https://github.com/justdomains/ci

The scripts output **only** the full-domain-blocking entries from the original lists, while attempting to filter any domains that conflict with an exception rule on the original list.

**Because these are automated, converted _subsets_ of the original lists, please do not report omissions from these converted files to the list originator.**

&nbsp;

# Usage:
These converted files can be used with various DNS and domain-blocking tools:

## Using with [Pi-Hole](https://pi-hole.net/):
1. Copy the link to the Pi-Hole format for the desired list (from the appropriate table below).
2. [Add the URL to your Pi-Hole's block lists (**Settings** > **Pi-Hole's Block Lists**).](https://github.com/pi-hole/pi-hole/wiki/Customising-Sources-for-Ad-Lists)

## Using with other tools:
The converted lists are provided in a "Raw Domain List" format that contains only domains, one per line. Many other tools / scripts can ingest this format to add them to your blocklist.

&nbsp;

# The Lists:

| Converted List | License | Domains | Domain List | Last Updated |
:- | - | - | :-: | - |
| [EasyList](#easylist-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 17923 | [**Download**](https://justdomains.github.io/blocklists/lists/easylist-justdomains.txt) | 04 Jan 2021 08:47 UTC |
| [EasyPrivacy](#easyprivacy-domains-only) | [GPL3 / CC BY-SA 3.0](https://easylist.to/pages/licence.html) | 7255 | [**Download**](https://justdomains.github.io/blocklists/lists/easyprivacy-justdomains.txt) | 04 Jan 2021 08:47 UTC |
| [AdGuard Simplified Domain Names Filter](#adguard-simplified-domain-names-filter-domains-only) | [GPL3](https://github.com/AdguardTeam/AdguardSDNSFilter/blob/master/LICENSE) | 38969 | [**Download**](https://justdomains.github.io/blocklists/lists/adguarddns-justdomains.txt) | 2021-01-04T06:09:35.275Z |
| [NoCoin Filter List](#nocoin-filter-list-domains-only) | [MIT](https://github.com/hoshsadiq/adblock-nocoin-list/blob/master/LICENSE) | 688 | [**Download**](https://justdomains.github.io/blocklists/lists/nocoin-justdomains.txt) | 18 Mar 2020 |

&nbsp;

## EasyList (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easylist-justdomains.txt](https://justdomains.github.io/blocklists/lists/easylist-justdomains.txt) |
| Pi-Hole | [easylist-justdomains.txt](https://justdomains.github.io/blocklists/lists/easylist-justdomains.txt) |

**Source:** [https://easylist.to/easylist/easylist.txt](https://easylist.to/easylist/easylist.txt)
- Title: EasyList
- Version: 202101040847
- Last Modified: 04 Jan 2021 08:47 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 59120
Comment Lines: 297
Empty Lines: 0
Non-Domain-only Rules Excluded: 39252
Domain-only Rules Excluded (unsupported options): 1578
Domain-only Rules Excluded (exception conflict): 70
Domain-only Rules Output: 17923
```

&nbsp;

## EasyPrivacy (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [easyprivacy-justdomains.txt](https://justdomains.github.io/blocklists/lists/easyprivacy-justdomains.txt) |
| Pi-Hole | [easyprivacy-justdomains.txt](https://justdomains.github.io/blocklists/lists/easyprivacy-justdomains.txt) |

**Source:** [https://easylist.to/easylist/easyprivacy.txt](https://easylist.to/easylist/easyprivacy.txt)
- Title: EasyPrivacy
- Version: 202101040847
- Last Modified: 04 Jan 2021 08:47 UTC
- Homepage: [https://easylist.to/](https://easylist.to/)

**Conversion Details:**
```
Total Lines Processed: 18565
Comment Lines: 321
Empty Lines: 0
Non-Domain-only Rules Excluded: 10655
Domain-only Rules Excluded (unsupported options): 208
Domain-only Rules Excluded (exception conflict): 126
Domain-only Rules Output: 7255
```

&nbsp;

## AdGuard Simplified Domain Names Filter (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [adguarddns-justdomains.txt](https://justdomains.github.io/blocklists/lists/adguarddns-justdomains.txt) |
| Pi-Hole | [adguarddns-justdomains.txt](https://justdomains.github.io/blocklists/lists/adguarddns-justdomains.txt) |

**Source:** [https://filters.adtidy.org/extension/chromium/filters/15.txt](https://filters.adtidy.org/extension/chromium/filters/15.txt)
- Title: AdGuard DNS filter
- Version: 2.0.13.50
- Last Modified: 2021-01-04T06:09:35.275Z
- Homepage: [https://github.com/AdguardTeam/AdguardSDNSFilter](https://github.com/AdguardTeam/AdguardSDNSFilter)

**Conversion Details:**
```
Total Lines Processed: 40120
Comment Lines: 500
Empty Lines: 0
Non-Domain-only Rules Excluded: 611
Domain-only Rules Excluded (unsupported options): 5
Domain-only Rules Excluded (exception conflict): 35
Domain-only Rules Output: 38969
```

&nbsp;

## NoCoin Filter List (Domains-only)
| Format | Raw Download Link |
| --- | --- |
| Raw Domain List | [nocoin-justdomains.txt](https://justdomains.github.io/blocklists/lists/nocoin-justdomains.txt) |
| Pi-Hole | [nocoin-justdomains.txt](https://justdomains.github.io/blocklists/lists/nocoin-justdomains.txt) |

**Source:** [https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt)
- Last Modified: 18 Mar 2020
- Homepage: [https://github.com/hoshsadiq/adblock-nocoin-list/](https://github.com/hoshsadiq/adblock-nocoin-list/)

**Conversion Details:**
```
Total Lines Processed: 705
Comment Lines: 10
Empty Lines: 1
Invalid Lines: 0
Non-Loopback Lines (Ignored): 0
Local Hosts (Ignored): 0
Invalid Hosts (Ignored): 0
Duplicate Hosts (Ignored): 6
Hosts Output: 688
```

&nbsp;

# License:
Each converted / modified list file is licensed under the same license as the original list.

For more details, see the [LICENSES](LICENSES) file.

&nbsp;

# Reporting Conversion Issues:
If you find an issue in the output of the conversion process (i.e. comparing to the original upstream list), please report it over on: https://github.com/justdomains/ci/issues

**NOTE: We do not manage the upstream lists themselves, and will not be able to add any new blocks to the lists.**

&nbsp;

<sup>These files are provided "AS IS", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, arising from, out of or in connection with the files or the use of the files.</sup>

<sub>Any and all trademarks are the property of their respective owners.</sub>
