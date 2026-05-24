# TabCost Pro — Privacy Policy

**Last updated:** May 2026  
**Extension:** TabCost Pro (Chrome Extension)  
**Developer:** Alexandre Iglesias · hello@projekta2.com

---

## Summary (plain language)

TabCost stores everything locally in your browser. Nothing about your browsing is ever sent to any server. The only external connection is a one-time license verification with Gumroad when you activate a Pro license.

---

## 1. What data we collect

**We do not collect any personal data.**

TabCost stores the following data **exclusively in your browser's local storage** (`chrome.storage.local`), which never leaves your device:

| Data | Purpose | Stored where |
|------|---------|-------------|
| Hourly rate | Calculate opportunity cost | Local only |
| Daily accumulated cost | Display in popup | Local only |
| Tab activity timestamps | Detect inactivity | Local only |
| Daily cost history | Show charts (Pro) | Local only |
| Ignored domains list | Exclude tabs (Pro) | Local only |
| Pro license key | Verify activation status | Local only |
| Language preference | UI language (EN/ES) | Local only |
| Currency preference | USD / EUR display | Local only |

---

## 2. External connections

TabCost makes **one single external request**, and only when you manually activate a Pro license:

- **URL:** `https://api.gumroad.com/v2/licenses/verify`
- **Purpose:** Validate that the license key you entered is genuine
- **Data sent:** Your license key (no personal data, no browser data)
- **Frequency:** Once at activation, never again automatically

No analytics. No tracking pixels. No crash reporting services. No advertising networks.

---

## 3. Tab URL access

TabCost reads the URL and title of your open tabs to calculate inactivity time and display the tab name in the audit table. This information:

- Is processed entirely in memory within the extension
- Is never stored beyond a session timestamp
- Is never transmitted outside your browser

---

## 4. Permissions used

| Permission | Why it's needed |
|-----------|----------------|
| `tabs` | Read tab list and activity to calculate inactivity time |
| `storage` | Save your settings and history locally |
| `alarms` | Run background calculation every minute |
| `notifications` | Alert you when daily cost exceeds your threshold (optional) |
| `host_permissions: api.gumroad.com` | License verification only |

---

## 5. Data retention

All data is stored locally and remains in your browser until you:
- Uninstall the extension (all data is deleted)
- Clear your browser's extension storage manually
- Use the reset option within the extension

---

## 6. Third-party services

The only third party involved is **Gumroad** (gumroad.com), which processes license purchases and key validation. Their privacy policy applies to that transaction: [gumroad.com/privacy](https://gumroad.com/privacy)

---

## 7. Children

TabCost is a productivity tool not directed at children under 13. We do not knowingly collect data from minors.

---

## 8. Changes to this policy

If this policy changes materially, the "Last updated" date above will be updated. We recommend checking this page periodically.

---

## 9. Contact

Questions about privacy? Contact us at:  
**hello@projekta2.com**  
Alexandre Iglesias · Girona, Spain · [github.com/projekta2](https://github.com/projekta2)
