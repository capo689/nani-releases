# Nani Accounting (beta)

**Bookkeeping that stays on your computer.** Drop in your bank and card statements, invoices and receipts. Nani files them, asks you a few plain questions, and hands your CPA clean books at year end. Bring your own AI (Claude or ChatGPT) if you like: it can suggest changes, and nothing changes until you approve it.

This is a **free beta**. Everything works and no license is needed.

## Download

**Current version: 0.3.0**, released October 13, 2026. [What's new](CHANGELOG.md) · [All versions](https://github.com/capo689/nani-releases/releases)

| Your computer | Download |
|---|---|
| Mac with Apple Silicon (M1, M2, M3, M4; most Macs since late 2020) | [Nani Accounting 0.3.0 for Apple Silicon](https://github.com/capo689/nani-releases/releases/download/v0.3.0/Nani-Accounting-0.3.0-Mac-Apple-Silicon.dmg) |
| Mac with an Intel processor | [Nani Accounting 0.3.0 for Intel Mac](https://github.com/capo689/nani-releases/releases/download/v0.3.0/Nani-Accounting-0.3.0-Mac-Intel.dmg) |
| Windows 10 or 11 | [Nani Accounting 0.3.0 for Windows](https://github.com/capo689/nani-releases/releases/download/v0.3.0/Nani-Accounting-0.3.0-Windows-Setup.exe) |

Not sure which Mac you have? Apple menu > About This Mac. "Chip: Apple M..." means Apple Silicon; "Processor: Intel" means Intel.

## Try it with sample books

Not ready to put your own books in? Download **[Acme Anvil Co. sample books (0.3.0)](https://github.com/capo689/nani-releases/releases/download/v0.3.0/Acme-Anvil-Co-Sample-Books-0.3.0.zip)**: a complete, made-up small business (an anvil maker) with 21 months of bank, savings, card and loan statements, payroll, 100 invoices, receipts, contractors and a financed power hammer. 2025 is finished and closed, and September 2026 is left part-done so you can try everything: categorizing, the Interview, AI suggestions, customer payments, and the Inbox.

Unzip it and open **READ ME FIRST.txt**. In Nani, choose **Open another company file...** and pick **Acme Anvil Co.fqb**. Passphrase: `acme-anvil-demo`. Everything in it is invented; any resemblance to a real business is coincidence.

## Installing the beta

The beta isn't signed with an Apple or Microsoft certificate yet, so your computer will warn you the first time. That's expected.

**Mac**
1. Open the downloaded file and drag **Nani Accounting** into **Applications**.
2. Open Nani Accounting from Applications. macOS says it can't verify the developer; click **Done** (or **Cancel**).
3. Open **System Settings > Privacy & Security**, scroll down, and click **Open Anyway** next to Nani Accounting. Confirm with your password.
4. From then on it opens normally.

**Windows**
1. Run the downloaded **Setup** file.
2. If Windows shows "Windows protected your PC", click **More info**, then **Run anyway**.

## Updates

To see which version you have, look at the bottom of Nani's sidebar (or on the start screen). Nani checks for a new version when it opens and every few hours, and shows a banner when one is ready. Nothing installs until you click **Install and restart**. Every update is signed, and the app refuses any update that didn't come from Nani.

## Your data

Your company file lives on your computer, encrypted with your passphrase. Nani has no accounts and no servers, and doesn't collect anything. **Keep the recovery key Nani shows you when you create a company:** without your passphrase or that key, nobody can open your books, including us.

It's a beta: set a backup folder in **Backup and security** and keep your old system running alongside until you're confident.

## Feedback

Email **adamrcagle@gmail.com** with what worked, what didn't, and anything confusing. If something crashes, Nani offers to show you a crash report you can review before sending.
