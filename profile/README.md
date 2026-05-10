<div align="center">

# wiz≡r

**Personal finance, built around one number — your savings rate.**

[wiz3r.com](https://wiz3r.com) · [Trust & Legitimacy](https://wiz3r.com/trust) · [Security](https://wiz3r.com/security) · [LinkedIn](https://www.linkedin.com/company/wiz3r)

</div>

---

## What we build

wiz≡r is a personal finance app that automatically tracks your real savings rate by reading transaction data from your bank accounts via [Plaid](https://plaid.com). We display amounts and account names; **we don't move money**, **we never see your bank credentials**, and **read-only is the only thing we can do**.

- 📱 Native **iOS** (SwiftUI)
- 🤖 Native **Android** (Jetpack Compose)
- 🌐 Full-featured **web app** at [wiz3r.com](https://wiz3r.com)
- 🧠 Shared business logic on **Kotlin Multiplatform** — same code, all three platforms
- 🇨🇦🇫🇷 Bilingual (English / French)

## The team

A father-and-son collaboration based in Ottawa, Canada.

| | |
|---|---|
| **Eric Laurin** | Founder & Lead Developer · B.Eng., M.A.Sc. Electrical Engineering · 25 years in telecom software |
| **Ludovik Laurin** | Co-founder & Financial Strategist · Finance background · Banking-sector network |

More on [our team page](https://wiz3r.com/team).

## Why most of our code is private

The wiz≡r mobile and web apps live in private repositories under this organization. We connect to people's bank accounts (read-only, via Plaid) and we're not in a position to open-source the application code. We do plan to publish:

- Public docs and integration guides
- Brand and design assets
- Anything where open-sourcing genuinely helps the community

…in dedicated repos as we go.

## How we approach security

- **Bank credentials never touch our servers.** All authentication is handled by Plaid (SOC 2 Type II–certified). We receive a read-only token.
- **Encryption at rest** — AES-256-GCM on sensitive fields.
- **Encryption in transit** — TLS 1.2 / 1.3 with HSTS.
- **Authentication** — JWT (HMAC-SHA256), BCrypt-hashed passwords (cost 12), optional TOTP MFA.
- **Daily encrypted backups** with offsite copies and a tested disaster-recovery procedure.
- **No money movement** — wiz≡r is read-only and not classified as a Money Services Business under FINTRAC.

Reporting a vulnerability: [`security@wiz3r.com`](mailto:security@wiz3r.com) · [security.txt](https://wiz3r.com/.well-known/security.txt) · [security overview](https://wiz3r.com/security).

## Public identifiers

For anyone verifying we're a real, registered business:

| | |
|---|---|
| **Trade name** | wiz≡r |
| **Business name (Service Ontario)** | WIZ3R |
| **Service Ontario BIN** | `1001548462` |
| **CRA Business Number** | `793709577TZ0001` |
| **D-U-N-S** | `243363068` |
| **Location** | Ottawa, Ontario, Canada |
| **Legal structure** | Sole proprietorship |

Verify in the [Ontario Business Registry](https://www.appmybizaccount.gov.on.ca/) or [D&B D-U-N-S Lookup](https://www.dnb.com/duns-number/lookup.html).

## Where to find us

- 🌐 **Web** — [wiz3r.com](https://wiz3r.com) · [About](https://wiz3r.com/about) · [Trust & legitimacy](https://wiz3r.com/trust)
- 💼 **LinkedIn** — [linkedin.com/company/wiz3r](https://www.linkedin.com/company/wiz3r)
- 🐦 **X / Twitter** — [@wiz3rapp](https://x.com/wiz3rapp)
- 📷 **Instagram** — [@wiz3rapp](https://www.instagram.com/wiz3rapp/)
- 📘 **Facebook** — [wiz≡r](https://www.facebook.com/profile.php?id=61575402881454)
- ✉️ **Support** — support@wiz3r.com
- 🔒 **Security disclosures** — security@wiz3r.com
