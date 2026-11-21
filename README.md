# JenerScouts: deal finder and security news for Windows

**A free Windows app that scouts the internet for you: great deals and price mistakes the moment they drop, plus security news explained in plain English so anyone can stay safe online.**

[**⬇ Download the latest version for Windows**](https://github.com/PrimeExtremo/jenerdev-app/releases/latest) · [Website](https://jener.dev/jenerscouts)

No account. No ads in the app. Everything runs on your PC.

---

## What it does

### 🏷️ Deals and price mistakes
- Live deals from community deal sites like Slickdeals, DealNews and Ben's Bargains, checked every 30 seconds.
- ⚡ **Price mistakes**: items accidentally listed far below their real price, flagged so you can grab them before they're fixed.
- Filters for Hot deals, Amazon, Food, Penny items and Freebies.
- Desktop alerts for the deals you care about, even when the window is closed (it waits in the tray).

### 🛡️ Security news anyone can understand
- The latest stories from trusted sources (The Hacker News, BleepingComputer, Krebs on Security, CISA and more).
- Every story says **what it means for you** and **what to do** in plain English, no tech background needed.
- A **0 to 10 score** on every story, so you can see at a glance what matters:

  | Score | Meaning |
  |---|---|
  | 🟩 0–3.9 Low | Good to know, nothing to do |
  | 🟨 4–6.9 Medium | Worth a look if you use the product mentioned |
  | 🟧 7–8.9 High | Update or follow the advice soon |
  | 🟥 9–10 Critical | Act now |

  When a story names a **CVE** (the official ID for a security hole), the score is its official **CVSS** rating from the U.S. National Vulnerability Database. If CISA says attackers are using it right now, it counts as at least 9. Other stories get an estimate based on the kind of story, clearly marked "est."
- Filters for Important stories, Scams, Data leaks and Updates.

### 🧰 Safety tools
- **Password check**: how strong a password is and whether it appeared in a known data leak (via Have I Been Pwned; your password never leaves your PC).
- **Link checker**: paste a link from an email or text and see the common scam tricks it uses (look-alike names, fake "login" addresses, short links, risky endings and more).
- **CVE lookup**: type a CVE number and get its 0–10 score explained, whether it's being used in attacks, and what to do.
- **Exploited now**: security holes criminals are using right now, from CISA's Known Exploited Vulnerabilities list.
- Extra tools for techies: hash, encode/decode, JWT viewer, Unix time.

## Install

1. Download **`JenerScouts-Setup-x.y.z.exe`** from the [latest release](https://github.com/PrimeExtremo/jenerdev-app/releases/latest).
2. Run it. Windows SmartScreen may say "Windows protected your PC" because the app isn't code-signed yet: click **More info → Run anyway**.
3. JenerScouts updates itself automatically.

Closing the window keeps JenerScouts in the system tray so alerts still arrive. To fully quit, right-click the tray icon → **Quit**.

## Privacy

- No account, no tracking, no analytics.
- Your settings and saved deals stay on your PC in `%APPDATA%\JenerDev`.
- The app only talks to the public deal and news sites it reads, NVD/CISA for security scores, Have I Been Pwned for the password check (only the first 5 characters of a hash are sent), and GitHub for updates.
- Some Amazon links include an affiliate tag (#ad), which supports the app at no cost to you.

## Formerly JenerDev

JenerScouts was called **JenerDev** up to version 1.0.6. If you have JenerDev installed, it updates to JenerScouts on its own and keeps your settings.

---

Made by [Jener](https://jener.dev).
