# RopaFew

**Build your GDPR Article 30 record of processing — guided, bilingual, and entirely in your browser.**

RopaFew is part of the **Few** toolkit, alongside [FirstFew](https://github.com/silvestroparisi/FirstFew), [FixFew](https://github.com/silvestroparisi/FixFew), [MaskFew](https://github.com/silvestroparisi/MaskFew), [ScrubFew](https://github.com/silvestroparisi/ScrubFew) and [AskFew](https://github.com/silvestroparisi/AskFew).
It helps small organisations produce the **record of processing activities (ROPA)** required by Article 30 of the GDPR — through a guided form, with a worked example and per-field guidance — and keeps every byte on your machine.

It's a single, self-contained web page. No backend, no build step, no upload, no account, no tracking.

🔗 **Live:** https://silvestroparisi.github.io/RopaFew/

> Article 30 sounds scary. In practice it's only a few activities.

## What it does

- **Controller (Art. 30.1)** and **Processor (Art. 30.2)** registers — one switch flips the form to the right set of fields.
- Records the entity details (controller/processor, joint controller, EU representative, DPO) and each **processing activity**: purposes, legal basis (Art. 6), special/criminal-offence data flags (Art. 9 / 10), categories of data subjects and data, recipients, non-EU transfers and safeguards, retention, and security measures.
- **DPIA hint** — flags the Article 35 triggers (large-scale systematic monitoring, large-scale special-category data, monitoring of public areas) and suggests considering a DPIA.

## Guidance built in

Made for people who've never filled one in:

- **★ Load example** — drops in a realistic, ready-made controller register (customer billing, HR, marketing, CCTV), in **Italian or English** (you choose on click).
- **ⓘ Field guide** — a one-line hint under every field, anchored to the exact Article 30 letter it satisfies.
- **Clickable articles** — every "Art. N" opens a plain-language explanation of that article (Art. 6, 9, 10, 30, 35).
- Fully **bilingual** (IT / EN) with a dark / light theme.

## Not legal advice

**RopaFew is a drafting aid, not a compliance guarantee.** It helps you produce a clean, well-structured register, but:

- it does **not** make you compliant on its own;
- it is **not** legal advice and does not replace a DPO, lawyer or supervisory authority;
- the built-in guidance and examples are general and should be **reviewed and adapted** to your real processing by a competent person.

When in doubt, have your DPO or counsel review the result.

## Privacy

There's no backend. The whole tool is a single static page: no account, no upload, no server. Your register — which maps exactly what personal data you hold — never leaves your browser. Open **DevTools → Network** to confirm. You can even save the page and run it offline.

## Export & save

- **Save (.json)** / **Load (.json)** — keep your work as a file on your device and resume later.
- **CSV** — open the register in a spreadsheet.
- **Print / PDF** — a clean printable register to hand over or archive.

## The Few toolkit

- [**FirstFew**](https://silvestroparisi.github.io/FirstFew/) — prioritize the few that matter
- [**FixFew**](https://silvestroparisi.github.io/FixFew/) — verify and remediate
- [**MaskFew**](https://silvestroparisi.github.io/MaskFew/) — anonymize a file before you share it
- [**ScrubFew**](https://silvestroparisi.github.io/ScrubFew/) — strip hidden metadata before you share
- [**AskFew**](https://silvestroparisi.github.io/AskFew/) — a private AI that runs in your browser
- **RopaFew** — build your GDPR Article 30 register

*GapFew (multi-framework gap assessment — GDPR, NIS2, ISO 27001, NIST) is on the way.*

## License

[MIT](LICENSE) © 2026 Silvestro Parisi
