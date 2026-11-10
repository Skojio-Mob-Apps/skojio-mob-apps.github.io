# Play Console answers template

Reusable answers for new apps. Copy `data-safety.csv` and adjust per app, then use Play Console > Data safety > Import from CSV (check the file against a fresh Export to CSV first, because Google may change the columns).

This file started from Digital Clock (free with banner ads + one-time Pro unlock). Change anything that differs for the new app.

## Data safety (Digital Clock)

| Data type | Collected | Shared | Ephemeral | Required | Purposes |
|---|---|---|---|---|---|
| Approximate location | Yes | Yes (ad network) | No | Required | Advertising, Analytics |
| Device or other IDs | Yes | Yes (ad network) | No | Required | Advertising |
| App info and performance: Diagnostics | Yes | Yes (ad network) | No | Required | Analytics, Advertising (collected and shared) |
| Financial info: Purchase history | Yes | No | No | Optional | App functionality |

Also: data encrypted in transit = Yes. Deletion request: no account data held. No other data types.

Tip: in each dialog, scroll and verify the Collected purposes and the Shared purposes lists separately, because the layout shifts as you tick boxes.

## Other App content answers

- Privacy policy URL: https://skojio-mob-apps.github.io/<app>/privacy-policy/
- Ads: Yes, contains ads
- Target audience: 13 and over, not designed for children
- Content rating (IARC): ads only, no violence, no user-generated content
- App category: Tools
- Contact email: hello@skojio.com
- Developer account: Skojio (personal accounts need a closed test with 12 testers for 14 days before production)
- Wording rules: no battery claims, no third-party brand names

## Per-app steps not covered here

Trader status and terms declarations need the owner's real details. Store graphics, AdMob ad units, in-app products and the upload key are app-specific.
