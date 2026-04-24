# cross-intel-bec-awareness

> Production-ready BEC (Business Email Compromise) awareness kit — built from **11 real documented attack incidents** targeting a team over 6 weeks. Includes HTML booklet, email template, and PowerPoint deck. Ready to deploy, adapt, and reuse.

![Security](https://img.shields.io/badge/Security_Awareness-HRM-CC0000?style=flat&logoColor=white)
![GDPR](https://img.shields.io/badge/GDPR-Compliant-003399?style=flat&logo=europeanunion&logoColor=white)
![NIS2](https://img.shields.io/badge/NIS2-Aligned-CC0000?style=flat&logoColor=white)
![Language](https://img.shields.io/badge/Language-PT%20%2F%20EN-green?style=flat)

---

## What is BEC?

**Business Email Compromise (BEC)** is a social engineering attack where threat actors impersonate trusted colleagues, executives, or partners to manipulate employees into sharing information, transferring funds, or changing communication channels.

BEC attacks are not random — they are **targeted, researched, and persistent**. Attackers study your organization before striking.

---

## What's in this kit

| File | Description |
|---|---|
| `booklet/bec-awareness-booklet.html` | Full HTML awareness booklet — 11 real attack patterns, red flags, response guide |
| `email-templates/bec-awareness-email.html` | Outlook-compatible awareness email — ready to send to your team |
| `presentation/bec-awareness-deck.pptx` | PowerPoint deck for live sessions or async sharing |
| `docs/methodology.md` | HRM framework used to build this kit |
| `docs/incident-catalogue.md` | Anonymized catalogue of the 11 documented incidents |

---

## The 11 incidents — what happened

Over 6 weeks (February–March), a team received **11 documented BEC attempts**:

- **4 attacks in February** — initial campaign, low sophistication
- **7 attacks in March** — escalated, more targeted, included tracking pixels

**Attack patterns identified:**

| # | Pattern | Channel |
|---|---|---|
| 1 | Colleague impersonation — WhatsApp number request | Email → WhatsApp |
| 2 | Executive impersonation — urgent task, no calls | Email |
| 3 | Tracking pixel in HTML email to confirm active address | Email |
| 4 | Multi-contact attack — same message to 3 addresses of same person | Email |
| 5 | Domain spoofing — `yourorg.co` instead of `yourorg.com` | Email |
| 6 | Urgency + secrecy combo — "don't tell anyone" | Email |
| 7 | Reply-chain hijacking simulation | Email |
| 8–11 | Variations of patterns 1–3 with different sender names | Email |

---

## Red flags — what these emails had in common

- 📮 Sender uses Gmail or Hotmail, never the corporate domain
- 📱 Requests WhatsApp number or asks to move off email
- ⏰ Artificial urgency: "ASAP", "URGENT TASK"
- 🚫 Blocks voice verification: "I'm in a meeting, no calls"
- 🔍 Vague opening message to confirm the address is active
- 🤐 Requests secrecy or asks not to involve others
- 🎯 Uses real colleague names obtained via LinkedIn/OSINT

---

## How to use this kit

### Option A — Full deployment (recommended)
1. Send the **awareness email** to your team as a security alert
2. Share the **HTML booklet** as a reference document
3. Run a **live session** using the PowerPoint deck
4. Follow up with the **incident catalogue** for real examples

### Option B — Quick deployment
1. Customize `bec-awareness-email.html` with your organization name and IT contact
2. Send directly from Outlook (open in browser → copy HTML → paste into Outlook)
3. Link to the booklet in the email body

### Option C — Adapt for your organization
1. Replace `YourOrg` with your organization name in both HTML files
2. Replace `security@yourorg.com` with your actual IT/security contact
3. Update the incident statistics to match your own data if available

---

## Customization

Both HTML files use placeholder values that you can replace:

| Placeholder | Replace with |
|---|---|
| `YourOrg` | Your organization name |
| `yourorg.com` | Your domain |
| `security@yourorg.com` | Your IT/security team email |
| `[Collaborator]` | Example employee name |
| `[Colleague Name]` | Example sender name in attack scenario |

---

## Methodology — Human Risk Management (HRM)

This kit was built following an HRM approach:

1. **Incident collection** — document real attacks as they happen, not hypothetical scenarios
2. **Pattern analysis** — identify common tactics across incidents
3. **Audience-first content** — write for non-technical employees, not security teams
4. **Multi-format delivery** — same message in email, booklet, and presentation
5. **Action-oriented** — every piece ends with a clear action (report, verify, pause)

See `docs/methodology.md` for the full framework.

---

## About Cross Intel

This kit was produced by **[Cross Intel](https://cross-intel.com/)** — a cybersecurity consultancy focused on Human Risk Management (HRM) and security awareness for the Iberian and CPLP markets.

If you need a customized BEC awareness program for your organization, [get in touch](https://cross-intel.com/).

---

## License

MIT — free to use, adapt, and distribute with attribution.
