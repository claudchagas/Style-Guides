# Keeper Security — Translation Style Guide
**Locale:** Brazilian Portuguese (pt-BR)
**Source language:** U.S. English
**Platform:** Smartling

---

## Revision history

| Version | Date | Source |
|---|---|---|
| 1.0 | 2025 | Consolidated from: Keeper Security General Style Guide (Smartling) |

---

## 1. Overview & purpose

This guide defines the linguistic and formatting standards for translating Keeper Security content from U.S. English into Brazilian Portuguese (pt-BR). It applies to all customer-facing copy — UI strings, microcopy, onboarding flows, help documentation, marketing materials, and product descriptions — published across Keeper Security's suite of products.

The goal is consistency across all touchpoints: a translator or reviewer picking up any Keeper Security string should make the same choices independently.

---

## 2. Brand overview

Keeper Security provides a secure, encrypted password manager and digital vault for individuals and businesses. Its core promise is protecting users against hackers with a private, encrypted digital vault. Keeper's products serve both personal productivity users and enterprise security teams.

### 2.1 Product suite

| Product | Abbreviation | Notes |
|---|---|---|
| Password Manager | — | Core consumer product |
| Digital Vault | — | Encrypted personal storage |
| Keeper Admin Console | — | Enterprise admin interface |
| Keeper Connection Manager | KCM | Secure remote access |
| Keeper Secrets Manager | KSM | Secrets management for DevOps |
| Keeper Privilege Access Manager | KeeperPAM | Privileged access management |
| Keeper Service Provider | MSP | Managed service provider offering |
| KeeperChat | — | Encrypted messaging |
| BreachWatch | — | Dark web monitoring |
| KeeperFill | — | Browser extension for auto-fill |
| Keeper DNA | — | Multi-factor authentication |
| Keeper Commander | — | CLI / SDK for developers |

---

## 3. Audience

| Audience | Description |
|---|---|
| B2C — Personal productivity users | Adults seeking to protect personal passwords, logins, credit card numbers, and bank accounts. Tech-comfortable but not necessarily technical. |
| B2B — Business users | Teams and IT administrators managing credentials and access across an organization. May be familiar with enterprise security concepts. |
| Enterprise — IT & security teams | System administrators, DevOps engineers, and security professionals. Expect precise technical language and product-specific terminology. |

**Content types in scope:** UI strings, onboarding copy, help documentation, marketing pages, email templates, admin console labels.

---

## 4. Tone & register

### 4.1 Overall tone

**Professional.** Keeper Security content is authoritative and trustworthy. The tone should reassure users that their data is secure and that Keeper is a serious, reliable partner in protecting it.

Avoid:
- Casual or colloquial language
- Contractions and informal constructions
- Humor or wordplay that could undermine trust

### 4.2 Tone by content type

| Content type | Register | Notes |
|---|---|---|
| UI strings / microcopy | Formal | Precise, concise. Stay close to source. |
| Onboarding / help documentation | Formal | Clear and instructional. Passive voice preferred. |
| Marketing copy | Professional | Authoritative but accessible. |
| Error messages & security notices | Formal | Neutral and direct. No alarming language. |
| Admin console | Formal | Technical precision required. |

---

## 5. Language conventions

| Convention | Requirement |
|---|---|
| Second-person pronoun | Formal — use "o senhor / a senhora" where a formal register requires it; default to formal "você" where natural in pt-BR UI copy |
| Colloquial expressions | Inappropriate — avoid slang, idioms, and informal constructions |
| Voice | Passive voice preferred — see Section 6.1 |
| Abbreviations | Acceptable — abbreviations must end with a period; do not use periods after units of measure |

---

## 6. Grammar & syntax

### 6.1 Voice

Passive voice is the preferred construction for Keeper Security content. It conveys objectivity and precision, and reflects the professional tone of the brand.

> ✅ "As senhas são criptografadas e armazenadas com segurança."
> ❌ "Criptografamos e armazenamos suas senhas com segurança."

Use the active voice only where passive constructions would be unnatural or unclear in pt-BR.

### 6.2 Abbreviations

Abbreviations are acceptable throughout. Apply the following rules:

- Abbreviations must end with a period: e.g., *p.ex.*, *etc.*, *aprox.*
- Do not use a period after units of measure: *g*, *km*, *m*, *MB*, *GB*
- Introduce the full term before using an abbreviation for the first time in a document or flow:

> Write "Keeper Connection Manager" before using "KCM". Write "Keeper Secrets Manager" before using "KSM".

### 6.3 Sentence structure

Keep sentences concise and unambiguous. Avoid complex or nested constructions. Favor clarity over elegance, especially in UI strings and error messages.

---

## 7. Punctuation & capitalization

### 7.1 Punctuation

| Element | Rule |
|---|---|
| Apostrophes | Use curly (typographic) apostrophes (') — never straight quotes (') |
| Bullet points | Begin each bullet point with a capital letter |
| Abbreviation periods | Required: *p.ex.*, *etc.* |
| Unit periods | Not used: *g*, *km*, *MB* |

### 7.2 Capitalization

Apply standard pt-BR rules:

- Sentence case for UI labels, headings, and body copy — capitalize only the first word and proper nouns.
- Do not capitalize job titles mid-sentence.
- Days of the week, months, languages, and nationalities: lowercase.
- Product names and brand names follow their own capitalization rules regardless of position in the sentence — see Section 9.

---

## 8. Numbers, dates, times & currencies

### 8.1 Numbers

Write numbers as digits. Do not spell out numbers in UI copy.

### 8.2 Dates

Use the standard pt-BR format:

> ✅ 15 de maio de 2025 / 15/05/2025

### 8.3 Times

24-hour clock with colon as separator:

> ✅ "Sessão encerrada às 14:30."
> ❌ "Sessão encerrada às 2:30 pm."

### 8.4 Currencies

- Currency symbol before the amount: R$ 50 / USD 50
- Decimal separator: comma — R$ 1,50
- Thousands separator: period — R$ 1.000
- Do not translate currency codes or symbols

---

## 9. Terminology & do not translate

### 9.1 Do not translate (DNT) — general categories

The following must remain in the source language exactly as they appear:

| Category | Examples / Notes |
|---|---|
| Website names | keepersecurity.com, docs.keeper.io — all domain names |
| Branded names | Keeper Security, Keeper — see Section 9.2 |
| Product names | See Section 9.3 |
| Usernames | Any user handle or identifier |
| Numbers | All numeric values |
| Currencies | USD, EUR, R$ — do not translate or adapt |
| Email addresses | user@domain.com — leave unchanged |
| URLs | Do not localize or adapt any URL |

### 9.2 Brand name rules

- **"Keeper"** and **"Keeper Security"** must remain unchanged in all languages without exception.
- Do not decline, conjugate, or inflect the word "Keeper" — treat it as an invariable proper noun.

### 9.3 Product name rules — Latin-alphabet locales

For pt-BR (a Latin-alphabet locale), product names may remain in English. Always check the Smartling project glossary before making a decision.

| Product name | Status |
|---|---|
| KeeperFill | Non-translatable — keep in English |
| KeeperPAM | Non-translatable — keep in English |
| Keeper Secrets Manager (KSM) | Check glossary — may remain in English |
| Keeper Connection Manager (KCM) | Check glossary — may remain in English |
| BreachWatch | Keep in English |
| KeeperChat | Keep in English |
| Keeper Commander | Keep in English |

> **Rule:** If a product name contains the word "Keeper", the word "Keeper" itself is always kept unchanged. The rest of the name may be retained or adapted based on the glossary.

### 9.4 Handling questions about terminology

If you are unsure whether a term should be translated or kept in English, open an issue in Smartling and tag the job requester. Do not make an assumption — consistency across the project depends on a shared decision.

---

## 10. Placeholders & special instructions

### 10.1 Placeholder position

Some strings begin with a placeholder (a variable such as `{username}`, `{date}`, or `%s`). When a placeholder appears at the very beginning of the source string, it **must** appear at the very beginning of the target string.

- No text, spaces, or characters may precede the placeholder in the translation.
- No extra words may be inserted before the placeholder to make the sentence more natural — restructure the rest of the string instead.

> **Source:** `{username} has been added to the vault.`
> ✅ **pt-BR:** `{username} foi adicionado ao cofre.`
> ❌ **pt-BR:** `O usuário {username} foi adicionado ao cofre.`

This rule applies to all locales.

### 10.2 Smartling workflow notes

- Address issues promptly — do not leave strings flagged and unresolved.
- When a rejected string requires no updates (the translation is correct as submitted), add a comment confirming this before marking the issue as resolved.
- Mark all issues as resolved before resubmitting strings to the workflow.

---

## 11. Do's and don'ts

| ✅ Do | ❌ Don't |
|---|---|
| Use passive voice as the default construction | Default to active voice — passive is preferred for this account |
| Use formal register throughout | Use colloquial language, slang, or informal contractions |
| Write abbreviations with a closing period (*etc.*, *p.ex.*) | Omit the period after abbreviations |
| Write units of measure without a period (*MB*, *km*, *g*) | Add a period after units of measure |
| Begin each bullet point with a capital letter | Begin bullet points with lowercase |
| Use curly apostrophes (') | Use straight apostrophes or quotation marks (') |
| Keep "Keeper" and "Keeper Security" unchanged in all cases | Translate, decline, or inflect the brand name |
| Keep KeeperFill and KeeperPAM in English | Translate or adapt those product names |
| Check the Smartling glossary before translating any product name | Assume a product name should or should not be translated without checking |
| Place a placeholder at the very start of the target string when it leads the source | Insert any character or word before a leading placeholder |
| Open a Smartling issue and tag the job requester when a terminology question arises | Make a solo judgment call on untested terminology |
| Use standard pt-BR date format: 15 de maio de 2025 | Use the English date format or day/month order ambiguously |
| Use the 24-hour clock with colon: 14:30 | Use 12-hour AM/PM format |

---

## 12. Reference materials

- Smartling project glossary — **consult before delivering any job**; glossary takes precedence over this guide in cases of conflict
- Keeper Security website: https://www.keepersecurity.com/
- Keeper Security blog: https://www.keepersecurity.com/blog
- Keeper Security documentation: https://docs.keeper.io/
- Keeper Security training videos: https://www.keepersecurity.com/getting-started.html
- Keeper Web Vault (for testing and UI reference): https://keepersecurity.com/vault/#
- Dicionário Houaiss da Língua Portuguesa
- Michaelis: Moderno Dicionário da Língua Portuguesa
- Post-1990 Orthographic Agreement (Acordo Ortográfico)