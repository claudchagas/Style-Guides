# SAP Style Guide — Portuguese (Brazil) · pt-BR
*Consolidated Edition — Generic Guide · Locale Supplement · URL Rules*

---

## About This Document

This is the single consolidated pt-BR style guide for SAP marketing localization. It merges three source documents:

1. SAP Generic Style Guide for Marketing Communications (SAP SE, Language Experience Lab, November 2025 — updated August 2026) — filtered to pt-BR
2. SAP Style Guide — Locale-Specific Supplement (pt-BR section)
3. URL Handling Rules for Localization

Where the sources overlap, the locale supplement takes precedence over the generic guide. Where they conflict, the conflict is noted inline. Rules from other locales have been removed.

> **Priority of resources (conflicts resolved in this order)**
>
> 1. Project glossary + specific project instructions
> 2. Naming Center on SAP Brand Tools (brand.sap.com)
> 3. SAP Termbase (translation.sap.com)
> 4. SAP.com website for Brazil (sap.com/brazil)
>
> Translation Memory takes precedence within an asset for consistency unless a higher-priority source explicitly overrides it.

---

## 1. Brand Overview

| Field | Details |
|---|---|
| Account | SAP SE |
| Full name | Systeme, Anwendungen und Produkte in der Datenverarbeitung |
| Locale | pt-BR — Brazilian Portuguese (distinct from European pt-PT) |
| Source language | en-US |
| Content scope | Corporate/solution brochures, case studies, thought-leadership papers, infographics, e-books, emails, social-media banners, AV content (subtitles, voice-over, semi-lip-sync), sap.com, SEO copy, transcreated campaign messaging |
| Style authority | SAP Brand website (brand.sap.com) · SAPterm (translation.sap.com) · SAP LX Translation Support Portal |

---

## 2. Voice & Tone

| Attribute | Requirement |
|---|---|
| Register | Professional, authoritative, and confident — yet accessible, inclusive, and human |
| Approach | Empathetic and customer-outcome-focused. Convey expertise without condescension. |
| Sentences | Keep active and concise. Avoid hype and superlatives. |
| Forward-looking content | Modern and inspirational where appropriate |
| Transcreation assets | Preserve creative and emotional intent — not literal meaning. Provide alternative options where the target departs significantly from source. |
| Non-transcreation assets | Prioritize clarity, accuracy, and consistency with SAP terminology and TM |

---

## 3. Language Conventions

| Convention | Requirement |
|---|---|
| Second-person pronoun | Formal — use "você" throughout (see Section 4 for full address rules) |
| Colloquial expressions | Inappropriate |
| Voice | Active and concise as default; passive acceptable where it aids clarity or suits institutional register |
| Abbreviations | Acceptable — see Section 10 for rules |
| Spelling standard | Post-1990 Acordo Ortográfico ("ideia" not "idéia"; "voo" not "vôo") |
| Vocabulary standard | Brazilian Portuguese — not European. See Section 12 for key distinctions. |

---

## 4. Forms of Address & Verb Forms

- Use "você" as the standard form of address for all SAP business and customer-facing content. In Brazilian Portuguese, "você" is the default professional form and pairs with third-person verb conjugation.
- For very formal or institutional content (legal documents, executive correspondence), use "o senhor / a senhora".
- Do not use "tu" — it exists in some Brazilian regional varieties but is not used in standard business writing.
- Possessives: use "seu / sua / seus / suas" — be aware of ambiguity with "dele / dela" in certain constructions and resolve in favour of clarity.
- For UI buttons and short calls to action: use the imperative form ("Salve", "Envie") — follow SAP TM for consistency with existing SAP UI strings.
- Email marketing and customer salutations: address recipients by their first name. This applies to email marketing, customer outreach, and any salutation context where personalising the address is appropriate.

> **Note — no informal/formal switching for pt-BR**
>
> Unlike nl-NL and nl-BE (which switch between formal and informal by asset type), pt-BR uses "você" throughout all asset types including sap.com web pages and social media.

---

## 5. Style, Voice & Inclusivity

- Always write "SAP" in all caps.
- Use only approved SAP product names, acronyms, and descriptors from brand.sap.com, the Naming Center, or SAPterm.
- If you cannot find an approved name, open an issue in Query Management and post the Query ID as a source issue in Smartling.
- Mirror SAP's voice: confident, clear, supportive, and outcome-focused.

### Inclusive language

- Prefer neutral collective nouns: "a equipe", "as pessoas usuárias", "o público".
- Avoid "@", "x" endings (todxs, alunx), and "todes" unless explicitly approved by the client.
- Avoid gendered constructions when a neutral form exists.
- Do not use terms that carry bias against minorities, even unconsciously.

---

## 6. Adaptation of US-Centric Content

- Replace US-specific cultural references, holidays, sports, and idioms with locally meaningful Brazilian equivalents or culturally neutral alternatives.
- Adapt names, titles, and roles in customer stories or examples to be regionally plausible for Brazil.
- Convert US-only legal references (e.g., "SOX") only when a Brazilian or international equivalent exists. Otherwise keep the source reference and add a brief gloss if context requires.

---

## 7. Numbers, Dates, Times & Currencies

### 7.1 Numbers

| Element | pt-BR convention |
|---|---|
| Thousands separator | Period — e.g., 1.234.567 |
| Decimal separator | Comma — e.g., 1.234,56 |
| Percentages | Numeral + % symbol — e.g., 50% (no space between numeral and symbol) |

> **Common error — do not copy EN-US number formatting**
>
> EN-US "24,700" → pt-BR "24.700" (thousands separator inverted)
> EN-US "2.5" → pt-BR "2,5" (decimal separator inverted)
>
> Always check that thousands and decimal separators are inverted from source — do not copy them.

### 7.2 Dates

| Format | pt-BR convention |
|---|---|
| Numeric short form | DD/MM/YYYY — e.g., 04/05/2026 |
| Written long form | 4 de maio de 2026 (day without leading zero; month lowercase) |
| Month names | Always lowercase — maio, junho, julho |
| Day names | Always lowercase — segunda-feira, terça-feira |

### 7.3 Times

| Format | pt-BR convention |
|---|---|
| System | 24-hour |
| Standard | HH:MM — e.g., 14:30 |
| Informal / UI contexts | HhMM acceptable — e.g., 14h30 |
| Avoid | AM/PM notation |

### 7.4 Currencies

> **Do NOT convert currencies**
>
> Use the same values and currency codes as the English source. Do not convert amounts.
>
> Adapt only: symbol position, spacing, and separators per pt-BR convention.
>
> Brazilian Real: symbol R$ placed before the amount with a non-breaking space — e.g., R$ 1.500,00
>
> Non-breaking space required between R$ and the amount.

### 7.5 Units of Measure

- Use the metric system.
- Non-breaking space between number and unit — e.g., 10 °C, 5 km, 10 GB.
- Do not use periods after units of measure (g, km, m, kg, GB, MB).

---

## 8. Punctuation & Typography

| Element | pt-BR convention |
|---|---|
| Quotation marks (primary) | " " (curly double quotes) |
| Quotation marks (secondary / nested) | ' ' (curly single quotes) |
| Dashes — parenthetical breaks | En dash (–) with spaces: " – " |
| Dashes — editorial / emphatic | Em dash (—) acceptable in editorial content |
| Capitalization | Sentence case for all headings and titles. Lowercase: days, months, languages, nationalities. |
| Non-breaking spaces | Required: between number and unit (10 GB, 5 %); between currency symbol and amount (R$ 1.500) |
| Commas before "e" | In many pt-BR constructions, "e" should not be preceded by a comma — apply PT-BR rules, not EN-US rules. |
| Apostrophes | Curly apostrophe (') |
| Trademarks / copyright | Preserve ™, ®, and © exactly as in source |

> **Parentheses in pt-BR**
>
> Used to intersperse explanations, dates, references, or acronyms:
>
> "Na última reunião (10 de novembro de 2018), tomou-se a decisão."
> "A sede da Organização das Nações Unidas (ONU) está localizada em Nova York."

> **Note — quotation mark conflict resolved**
>
> The SAP Generic Style Guide references straight quotes ("); the Locale Supplement specifies curly double quotes (""). The Locale Supplement takes precedence: use curly quotes for pt-BR.

---

## 9. Formatting, Placeholders & Variables

- Retain the formatting of source texts and graphics. Do not corrupt tags during translation.
- Never translate placeholders, variables, or tokens (`{0}`, `{variable_name}`, `%s`, `%d`, `%@`, `$variable`, `${value}`). Preserve them exactly.
- Preserve all HTML/XML/Markdown tags exactly. Translate only visible display text. Do not translate attribute values (class, id, src, href).
- Maintain line breaks (`\n`), tabs, and whitespace as in source.
- Respect character/length limits in Smartling's Additional Details panel. If exceeded, prioritize clarity and flag the LX project manager.

---

## 10. Abbreviations & Acronyms

- Industry acronyms may remain in English: ERP, CRM, API, SaaS, IoT, B2B, KPI.
- "AI" → "IA" is widely accepted in pt-BR; follow SAP TM for consistency.
- SAP product acronyms remain untranslated: S/4HANA, BTP, SCM, CPQ, IBP.
- On first use of a non-obvious acronym, expand it — full name first, acronym in brackets. Subsequently use the acronym alone.
- Never abbreviate an SAP offering if no approved acronym exists.
- No period after acronyms or units of measure (g, km, m, kg, GB, MB).

| Common pt-BR abbreviations | Form |
|---|---|
| for example | p. ex. or ex. |
| et cetera | etc. |
| number | n.° |
| Mister / Missus | Sr. / Sra. |

---

## 11. Bullet Points

- Begin each bullet point with a capital letter.
- If a bullet point is a complete sentence, end it with a period.
- If a bullet point is a fragment, no closing punctuation is needed.

---

## 12. Terminology & PT-BR Vocabulary

### 12.1 Brazilian Portuguese vs. European Portuguese

Always use Brazilian Portuguese vocabulary. Key distinctions:

| Concept | pt-BR (use this) | pt-PT (do not use) |
|---|---|---|
| Screen | tela | ecrã |
| File | arquivo | ficheiro |
| Mouse (computing) | mouse | rato |
| Mobile phone | celular | telemóvel |
| Application | aplicativo / aplicação (follow TM) | — |

### 12.2 Standard IT Vocabulary (pt-BR)

| English term | Preferred pt-BR rendering |
|---|---|
| cloud | nuvem |
| software | software (retained in EN) |
| application / app | aplicativo / aplicação (follow TM precedent) |
| user | usuário |
| vendor / supplier | fornecedor |
| deployment / go-live | implantação |
| dashboard | painel (or dashboard — follow TM) |
| workspace | workspace (retained in EN — follow TM) |
| pipeline | pipeline (retained in EN — follow TM) |

> **Anglicisms in pt-BR IT content**
>
> Terms like "workspace", "dashboard", and "pipeline" are commonly retained in English in pt-BR SaaS interfaces. Always check SAP TM and termbase before deviating from an established Brazilian rendering.

---

## 13. Product Name Gender Assignment

Portuguese requires grammatical gender for all nouns, including product and company names. SAP's pt-BR convention, agreed with the translation agency:

- Most SAP products and solutions take **masculine** grammatical gender — "o Fieldglass", "o SAP Ariba". Always verify the assigned gender for each product by referring to the main product page on sap.com/brazil.
- General rule: use **masculine** when the name refers to a system, platform, or software product. Use **feminine** when the same name refers to the company.
- Once a gender reference is established in an asset, maintain consistency throughout.

> **Worked example — SmartRecruiters**
>
> SmartRecruiters as a system (platform/software) → MASCULINE: "o SmartRecruiters"
> SmartRecruiters as a company → FEMININE: "a SmartRecruiters"
>
> When in doubt about a specific product's assigned gender, check sap.com/brazil before delivering.

---

## 14. Do Not Translate — Element Types

The following element categories must never be translated:

| | |
|---|---|
| Website names | URLs (see Section 15 for full URL rules) |
| Branded names | Approved SAP offering names (see Section 16) |
| Usernames | Always-English marketing terms (see Section 17) |
| Product names | Placeholders and variables ({0}, %s, etc.) |
| Email addresses | HTML/XML attribute values (class, id, src, href) |

---

## 15. URL Handling Rules

There are three URL handling categories. Apply the correct one based on the URL pattern.

### 15.1 URL Category Overview

| Category | Meaning | Action |
|---|---|---|
| Localize with country identifier | A regular public sap.com page convertible to a country/regional SAP.com site | Replace with localized URL using the country identifier mapping below |
| Keep in English | Help, Learning, Community, Legal, internal, or external links | Keep the original URL exactly as provided |
| Special case — confirm before handover | Campaign paths, redirect logic, or unclear destination | Use confirmed localized URL if provided; otherwise keep the original English URL |

### 15.2 When to Localize — Localize with Country Identifier

Apply this rule when **all three** conditions are true:

- The URL starts with `https://www.sap.com/`
- The URL is not in the "Keep in English" list (Section 15.3)
- The URL does not contain campaign-specific paths such as `/cmp/` or `/oth/`

**Country identifier for pt-BR:**

| Locale | Country identifier |
|---|---|
| pt-BR | `brazil` |

**Formula:**

```
https://www.sap.com/brazil/[remaining-url-path]
```

**Example:**

| | URL |
|---|---|
| Source (English) | `https://www.sap.com/products/erp.html` |
| pt-BR | `https://www.sap.com/brazil/products/erp.html` |

> **Campaign URLs (/cmp/ or /oth/) — do not localize by simply adding the country identifier**
>
> If a localized campaign URL is provided, use it.
> If no localized campaign URL is provided, keep the original English URL.

### 15.3 Keep in English — URL Patterns

Keep the URL in English exactly as provided when it matches any of the following:

| URL pattern or category |
|---|
| `help.sap.com` |
| `learning.sap.com` |
| `developers.sap.com` |
| `community.sap.com` or `pages.community.sap.com` |
| `influence.sap.com` |
| `sharepoint.com` |
| sap.com URLs containing `/news` |
| sap.com URLs containing `/community` |
| sap.com URLs under `sap.com/about/legal` |
| Non-SAP-owned external URLs |

### 15.4 Special Cases — Confirm Before Handover

| Special case | Why it needs confirmation | Expected handling |
|---|---|---|
| URLs containing `/cmp/` or `/oth/` | Usually campaign-related. Localized versions may exist only for selected markets. | Use confirmed localized URL if provided. Otherwise keep original English URL. |
| Embedded SAP.com assets | Redirect behavior may break if the URL is changed. | Follow the confirmed URL provided by the SAP localization team. |
| `safelinks.protection.outlook.com` | Outlook protected redirect — not the final landing page. | Use the final destination URL provided by the SAP localization team, or keep original if instructed. |

---

## 16. SAP Offering Names & Trademarks

- Use only approved names, acronyms, and descriptors from brand.sap.com and SAPterm.
- **Trademark symbols (™, ®):** SAP does not use trademark or registered trademark symbols on SAP-owned content. In the rare cases where the symbols appear in the English source, preserve them in the translation — do not add them independently.
- Introduce the full approved name first, with the acronym in brackets. Subsequently use the acronym alone.
- Subsequent mentions: you may omit the descriptor — unless the offering's naming entry forbids omission.
- Never abbreviate an SAP offering if no approved acronym exists.

> **Example — first mention**
> "SAP Customer Relationship Management (SAP CRM) application"
>
> **Example — subsequent mention**
> "SAP CRM"

---

## 17. Always-English Marketing Terms (DNT)

The following terms must remain in English in pt-BR, exactly as written. Even if "SAP" is dropped to avoid repetition, treat each term as non-translatable and keep it capitalized. All are added to the Smartling Glossary.

| | |
|---|---|
| RISE with SAP | SAP Business Data Cloud / Business Data Cloud |
| RISE with SAP Methodology | SAP Business Suite / Business Suite |
| GROW with SAP | Joule for Consultants |
| SAP Business Unleashed | clean core |
| SAP Business AI / Business AI | |

---

## 18. Approved pt-BR Marketing Term Translations

Use the exact target forms below. Do not introduce variants.

| English (en-US) | Approved pt-BR translation |
|---|---|
| Demo Video | Vídeo de demonstração |
| Product Tour | Tour pelo produto |
| Basic Trial | Avaliação básica |
| Advanced Trial | Avaliação avançada |
| Free Tier | Nível gratuito |
| Guided Experience | Experiência guiada |

---

## 19. Quotations, Titles & References

### 19.1 Quotations

- If the source of a quotation has been localized into pt-BR, cite the existing localized translation.
- If no localized version exists, translate the quotation.

### 19.2 Titles of Books, White Papers & References

- If the referenced document has been localized into pt-BR (check project instructions, TM, or web search), use the existing localized title.
- If no localized version exists, leave the title in English and provide a pt-BR translation in brackets.

### 19.3 Job Titles

- If a common pt-BR translation exists, translate the job title — e.g., Director, Account Manager.
- If the job title is SAP-specific, leave it in English.

### 19.4 SAP Department & Organization Names

- Leave the names of SAP departments and organizations in English.
- Provide a pt-BR translation in brackets if needed for clarity.

### 19.5 Names of Other Companies & Products

- Follow the company's own naming conventions.
- Refer to their official website to verify exact names and any preferred pt-BR variant.

---

## 20. Translation Memory & Consistency

- Maintain consistency with previously translated SAP content via Translation Memory.
- Apply 100% TM matches consistently. Only deviate when context clearly demands it, and flag for the reviewer.
- Sustainability, AI, and "intelligent enterprise" are recurring SAP themes — keep terminology consistent within and across projects.
- When in doubt about an anglicism vs. a pt-BR equivalent, follow TM and the SAP termbase rather than improvising.

---

## 21. Where to Report Questions & Issues

> **Updated August 2026**
>
> Always refer to sap.com before opening an issue — check whether the term, name, or reference is already addressed on the relevant product or solution page.
>
> If you see Latin text (lorem ipsum-style placeholder text) in the source, disregard it and deliver it as-is. These are layout placeholders used to approximate text length in the final design.

| Issue type | Where to report |
|---|---|
| Project-related questions (finding a project, missing info, project instructions) | Contact the LX project manager |
| Source issues | Open in Query Management; post the Query ID as a source issue in Smartling |
| Translation issues | Report in Smartling |
| Non-editable graphics | Contact LX project manager |
| Omission due to length restrictions | Contact LX project manager |
| Smartling tool issues | Contact Smartling support |

---

## 22. Reference Materials

- Dicionário Houaiss da Língua Portuguesa
- Vocabulário Ortográfico da Língua Portuguesa (VOLP) — Academia Brasileira de Letras
- Manual de Redação (e.g., Folha de S.Paulo)
- SAP Termbase / Glossary (Brazil) — Smartling > SAP Marketing > Linguistic Assets > Glossaries
- SAP Naming Center — brand.sap.com
- Microsoft Brazilian Portuguese Style Guide
- SAP Brand website — brand.sap.com (tone of voice, Naming Center, approved offering names)
- SAPterm — translation.sap.com

---

*Source documents consolidated in this guide:*
*SAP Generic Style Guide for Marketing Communications — SAP SE, Language Experience Lab, November 2025 (updated August 2026)*
*SAP Style Guide — Locale-Specific Supplement (pt-BR section)*
*URL Handling Rules for Localization*