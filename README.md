# The Lost Explorer: instant delivery and retail coverage (private sales page)

**Private sales page built by AccelPay for a conversation with The Lost Explorer.
It names the brand and its products; it is not affiliated with or endorsed by The
Lost Explorer Mezcal Company. Please keep the link unlisted.**

Live: https://noshiftsherlock.github.io/lostexplorer-coverage/

Built with the `alcohol-coverage` skill (cpg-coverage-cli map + retailer network layer).

## Sources and dates

| Figure | Source | Date |
| --- | --- | --- |
| 111 Gopuff locations carrying the brand (CA and WA) | Live Gopuff per-location brand check of 183 spirits-licensed locations (176 passed a tequila control). The BigQuery snapshot, frozen 2026-06-17, showed 51 | 2026-10-24 |
| 31.9M people, 972 ZIPs, 93 metros | Census ACS population of the delivery ZIPs of those locations. 10 stocked locations have no published city or ZIPs, so these are a floor | 2026-10-24 |
| 121 network retailers with an active listing (TX 102, CA 10, NY 6, FL 3) | ReserveBar / AccelPay retailer network, active variants matched on brand and product name, reconciled with retailer inventory files (Liquor Barn removed: listed with zero stock; Liquor Geeks added: in stock on its own feed) | 2026-10-24 |
| 3,500+ locations, 40+ states, about one week to launch | AccelPay approved claims | Oct 2026 |
