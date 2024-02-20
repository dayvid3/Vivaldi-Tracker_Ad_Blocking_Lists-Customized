# Vivaldi: Tracker / Ad Blocking Lists (Customized)
This is the current collection of Tracker and Ad Blocking sources that I am using with Vivaldi's native ad blocker, to enhance its effectiveness. I’ve tried to minimize sources with overlapping rules. Enable any additional Regions / Language sources that are relevant to your needs. 

Vivaldi’s [Block Trackers and Ads](https://help.vivaldi.com/desktop/privacy/tracking-and-ad-blocking/) guide can help you get started (There are mobile guides as well). Once you get to that point, below are my sources of choice.

- Disable all the **Built-In** rules except those listed below. You will then have to enable the sources that aren’t on by default.
- Manually add the **Custom** sources in their appropriate sections - Tracker Blocking or Ad Blocking

## Tracker Blocking Sources

- **(Enable)** Built-In Tracker Blocking Sources:
  - [DuckDuckGo Tracker Radar](https://downloads.vivaldi.com/ddg/tds-v2-current.json)
  - [EasyPrivacy](https://downloads.vivaldi.com/easylist/easyprivacy-current.txt)

- **(Add)** Custom Tracker Blocking Sources:
  - [AdGuard CNAME disguised trackers list](https://raw.githubusercontent.com/AdguardTeam/cname-trackers/master/data/combined_disguised_trackers.txt)

## Ad Blocking Sources

- **(Enable)** Built-In Ad Blocking Sources:
  - [ABP anti-circumvention list](https://downloads.vivaldi.com/lists/abp/abp-filters-anti-cv-current.txt)
  - [Adblock Warning Removal List](https://downloads.vivaldi.com/lists/abp/antiadblockfilters-current.txt)
  - [EasyList](https://downloads.vivaldi.com/easylist/easylist-current.txt)
  - [English (Peter Lowe’s List)](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=adblockplus&mimetype=plaintext)
  - [Remove annoyances, can break sites (Fanboy's Annoyance List)](https://secure.fanboy.co.nz/fanboy-annoyance.txt)
- **(Enable)** Built-In Regions / Languages (Some countries with lots of bad actors, and Japanese for possible Mange / Anime sites):
  - [Chinese (EasyList China)](https://easylist-downloads.adblockplus.org/easylistchina.txt)
  - [Japanese (もちフィルタ（広告ブロック）)](https://raw.githubusercontent.com/eEIi0A5L/adblock_filter/master/mochi_filter.txt)
    - [Japanese (もちフィルタ（mobile filter）)](https://raw.githubusercontent.com/eEIi0A5L/adblock_filter/master/tamago_filter.txt)
  - [Russian (RU AdList)](https://easylist-downloads.adblockplus.org/advblock.txt)

- **(Add)** Custom Ad Blocking Sources:
  - [oisd big](https://big.oisd.nl/)
  - [RU AdList: Counters](https://easylist-downloads.adblockplus.org/cntblock.txt) (Compliments RU AdList on sites like Yandex Search)
