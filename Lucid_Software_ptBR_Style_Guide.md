# Lucid Software — Style Guide
*Portuguese (Brazil) · pt-BR · Consolidated Edition*

---

## About This Document

This is the pt-BR style guide for Lucid Software localization. It consolidates the General Lucid Software Style Guide and the Lucidspark Blog Writing Style Guide, filtered to Brazilian Portuguese only. Japanese-specific voice instructions and locale-specific URL examples for other languages have been removed.

Apply these rules across UI strings, blog posts, marketing pages, automated emails, newsletters, press releases, and in-product microcopy unless a section below specifies otherwise.

> **Priority of resources**
>
> 1. Glossary provided with the project + specific project instructions (check glossary for case-sensitive terms)
> 2. Lucid content style guide (brandpad.io/lucid-content-style-guide)
> 3. SAP Termbase / Translation Memory — for consistency within an asset

---

## 1. Brand Overview

| Field | Details |
|---|---|
| Account | Lucid Software |
| Products | Lucidchart · Lucidspark · Lucidscale · Lucid Visual Collaboration Suite |
| Website | lucid.co |
| Source language | English |
| Content scope | UI strings, blog posts, marketing pages, use-case pages, PPC landing pages, templates, automated emails, newsletters, press releases, Help Center articles, in-product editor messages |

### 1.1 Product Descriptions

**Lucidchart**
The intelligent diagramming application that empowers teams to clarify complexity, align insights, and build the future — faster. Cloud-based; supports real-time collaboration on flowcharts, mockups, UML diagrams, customer journey maps, and more. Best for mid-to-late stage organizing, planning, and assessing.

**Lucidspark**
A cloud-based virtual whiteboard for creative real-time collaboration. Teams brainstorm, collaborate, and align on new ideas, then organize collective thinking into actionable next steps. Best for early-stage ideation, freeform thinking, and immediate feedback.

**Lucidscale**
A cloud visualization solution that auto-generates accurate, dynamic cloud diagrams to help teams design, build, deploy, and troubleshoot their cloud environments.

**Lucid Visual Collaboration Suite**
Lucidchart and Lucidspark offered together as an enterprise solution for effective collaboration, clarity, and team alignment.

---

## 2. Audience

Lucid's audience spans virtually every type of knowledge worker across three groups:

- **Research & Development (R&D)** — product management/UX, engineering, IT
- **Go to Market (GTM)** — marketing, sales/solution engineering, customer success/support
- **General & Administrative (G&A)** — operations, finance, executive, HR

Strive to be as inclusive as possible. Users come from many different countries and cultures.

---

## 3. Voice & Tone

### 3.1 Brand Personality

Lucid's brand personality is expressed through three core traits:

**Smart** — innovative, visionary, solution-focused. Together we find better solutions and unlock hidden opportunities.

**Lively** — energetic, action-oriented, agile, quick-paced. We infuse Lucid with vibrant optimism.

**Approachable** — warm, friendly, and inclusive. Despite deep knowledge and expertise, we are unintimidating. We meet people where they are.

> Always informative, never robotic
> Always friendly, never superfluous
> Always confident, never boastful
> Always smart, never condescending

### 3.2 Tone by Product

**Lucidchart** — technical but accessible, friendly but not too energetic, confident but not boastful, occasionally witty but never silly.

**Lucidspark** — the same foundation, but lean further into approachable, friendly, and witty. Ramp up accessibility and warmth.

In regions where a more formal tone is expected by professional consumers, the translation team may adjust accordingly.

### 3.3 Tone by Content Type

| Content type | Tone guidance |
|---|---|
| UI / in-product microcopy | Smart, lively, approachable. Communicate clearly — not for jokes or lighthearted references. |
| Blog posts | Informative, instructive, occasionally witty. Lucidspark blog: more creative and energetic than Lucidchart. |
| Automated emails | Individualized — refer to the customer by first name. |
| Newsletters | First-person plural ("we", "our"); smart, lively, approachable; appropriate contractions OK. |
| Press releases | Third person only ("they", "its" — never "our" or "we"). No contractions except within quotes. Use "said" + full name + title when quoting. |
| Growl / editor messages | First person to customer ("your account"). Write from the company where possible ("We weren't able to save your document. Please try again."). Lighthearted but not overly humorous — avoid "Oops!" or "The elves are working". |

---

## 4. Language Conventions

| Convention | Requirement |
|---|---|
| Second-person pronoun | Informal — use "você" |
| Colloquial expressions | Appropriate |
| Voice | Active — use as often as possible; passive may soften a message |
| Abbreviations | Acceptable — do not use periods after units of measure (g, km, m) |

---

## 5. Style Rules

- **Brevity** — convey thoughts as briefly and simply as possible.
- **Readability** — proper grammar, spelling, and syntax at all times.
- **Consistency** — maintain a consistent tone and style within a written piece.
- **One space** after a period.
- **Oxford comma** required in lists.
- **No end punctuation** in bulleted list items unless the item is a complete sentence.
- **Active voice** as default; passive may be used to soften a message.
- **Company as entity** — refer to Lucid as "its" rather than "their" wherever possible.
- **Competitor references** — objective and diplomatic; no name-calling, bashing, or blame.
- **Product comparisons** — objective, never insulting.

---

## 6. Capitalization

- Capitalize based on what is most appropriate in pt-BR. In English, sentence case is standard.
- Check the project glossary to confirm whether a specific term is case-sensitive.
- **Sentence case for all headings and titles** in pt-BR — capitalize only the first word and proper nouns.
- Lowercase: days of the week, months, languages, nationalities.

---

## 7. Bullet Points

- Begin each bullet point with a capital letter.
- If a bullet point is a complete sentence, end it with a period.
- If a bullet point is a fragment, no closing punctuation is needed.

---

## 8. Do Not Translate

The following must never be translated or localized:

| | |
|---|---|
| Website names | Currencies |
| Branded names | Email addresses |
| Usernames | URLs (apply Section 10 URL rules) |
| Product names | |

### Subscription tier names (DNT)

Do not translate subscription names unless the context is a Google ad:

| | |
|---|---|
| Free | Team |
| Individual | Enterprise |

---

## 9. Formatting & Security

- **Web app project only:** Do not insert formatting tags that are not present in the source. This prevents embedded HTML for security reasons. Find workarounds where possible.
- **Placeholders and variables:** Never translate or reorder placeholders. Preserve them exactly as in source.

---

## 10. URL Localization Rules

### 10.1 Overview

| Category | Meaning | What to do |
|---|---|---|
| Keep in English — add language code | URL content stays in English; only add the pt-BR language code in the correct position | Add `pt` as a subfolder in the position defined per URL type below |
| Translate slug | URL path (slug) is translated into pt-BR; language code also added | Translate the slug and insert `pt` in the correct subfolder position |
| Keep entirely in English | URL must not be changed in any way | Leave the URL exactly as provided |

> **General rule for pt-BR**
>
> The language code for Brazilian Portuguese is **`pt`**.
>
> Do not include special characters, accents, or umlauts in translated URL slugs.
>
> When a URL slug appears without the full domain (e.g., `/use-cases/project-planning`), treat it as the page's own URL and apply the same translation rules as for the full URL of that type.
>
> If a job contains the same URL multiple times, translate all instances consistently.

---

### 10.2 URL Types — Rules and pt-BR Examples

#### Type 1 — Images
**Action:** Keep entirely in English. Do not translate. Do not add language code.

| | URL |
|---|---|
| Source | `https://cdn-cashy-static-assets.lucidchart.com/lucidspark/marketing/blog/2020Q4/scaled-agile-framework/lucidspark-blog-header-4@2-1.png` |
| pt-BR | *(unchanged — leave exactly as in source)* |

---

#### Type 2 — In-product templates
**Action:** Keep slug in English. Add `pt` as a subfolder between `lucid.app` and the product name.

**Formula:**
```
https://lucid.app/pt/[product]/[rest-of-path]
```

| | URL |
|---|---|
| Source | `https://lucid.app/lucidspark/editNewOrRegister/99117775-a1b7-4ca3-9291-69d21ab1dff4` |
| pt-BR | `https://lucid.app/pt/lucidspark/editNewOrRegister/99117775-a1b7-4ca3-9291-69d21ab1dff4` |
| Source | `https://lucid.app/lucidchart/edNewOrRegister/289a6af0-5ed4-44fa-869b-d870a7bfffba` |
| pt-BR | `https://lucid.app/pt/lucidchart/edNewOrRegister/289a6af0-5ed4-44fa-869b-d870a7bfffba` |

---

#### Type 3 — Pricing pages
**Action:** Keep slug in English. Add `pt` as a subfolder after `lucid.app/` and before `/pricing/`.

**Formula:**
```
https://lucid.app/pt/pricing/[product]#/pricing
```

| | URL |
|---|---|
| Source | `https://lucid.app/pricing/lucidchart#/pricing` |
| pt-BR | `https://lucid.app/pt/pricing/lucidchart#/pricing` |
| Source | `https://lucid.app/pricing/lucidspark#/pricing` |
| pt-BR | `https://lucid.app/pt/pricing/lucidspark#/pricing` |
| Source | `https://lucid.app/pricing/lucidscale#/pricing` |
| pt-BR | `https://lucid.app/pt/pricing/lucidscale#/pricing` |

---

#### Type 4 — Login pages
**Action:** Keep slug in English. Add `pt` as a subfolder after `lucid.app/` and before `/users/`.

**Formula:**
```
https://lucid.app/pt/users/login#/login
```

| | URL |
|---|---|
| Source | `https://lucid.app/users/login#/login` |
| pt-BR | `https://lucid.app/pt/users/login#/login` |

---

#### Type 5 — Lucid Training Labs
**Action:** Keep entirely in English. Do not translate. Do not add language code.

| | URL |
|---|---|
| Source | `https://training.lucid.co/page/badges` |
| pt-BR | *(unchanged — leave exactly as in source)* |
| Source | `https://training.lucid.co/path/whiteboarding-foundations` |
| pt-BR | *(unchanged — leave exactly as in source)* |

---

#### Type 6 — Use-case pages
**Action:** Translate the slug into pt-BR. Add `pt` as a subfolder in the position below.

**Formula — Lucidchart:**
```
https://www.lucidchart.com/pages/pt/[translated-slug]
```
*(Insert `pt` after `.../pages/` and before the use-case slug)*

**Formula — Lucidspark:**
```
https://lucidspark.com/pt/[translated-slug]
```
*(Insert `pt` after `lucidspark.com/` and before the use-case slug)*

| | URL |
|---|---|
| Source (Lucidchart) | `https://www.lucidchart.com/pages/use-cases/visual-organizations` |
| pt-BR | `https://www.lucidchart.com/pages/pt/[translated-slug]` |
| Source (Lucidspark) | `https://lucidspark.com/use-cases/agile-development` |
| pt-BR | `https://lucidspark.com/pt/[translated-slug]` |

---

#### Type 7 — Blog posts
**Action:** Translate the slug into pt-BR. Add `pt` as a subfolder. Keep the base blog path in English.

**Formula — Lucidspark:**
```
https://lucidspark.com/pt/blog/[translated-slug]
```
*(Keep `https://lucidspark.com/blog/` in English; insert `pt` and translate everything after)*

**Formula — Lucidchart:**
```
https://www.lucidchart.com/blog/pt/[translated-slug]
```
*(Insert `pt` after `.../blog/` and before the slug)*

**Formula — Lucid.co:**
```
https://lucid.co/pt/blog/[translated-slug]
```
*(Insert `pt` after `lucid.co/` and before `/blog/`)*

| | URL |
|---|---|
| Source (Lucidspark) | `https://lucidspark.com/blog/what-to-do-after-brainstorming` |
| pt-BR | `https://lucidspark.com/pt/blog/[translated-slug]` |
| Source (Lucidchart) | `https://www.lucidchart.com/blog/erp` |
| pt-BR | `https://www.lucidchart.com/blog/pt/[translated-slug]` |
| Source (Lucid.co) | `https://lucid.co/blog/document-repository-for-innovation` |
| pt-BR | `https://lucid.co/pt/blog/[translated-slug]` |

> **Slugs only:** If the job contains only the slug (e.g., `/crm-models`), translate it into pt-BR and add `pt` following the same formula for the relevant product. Apply consistently across all instances of the same URL in the job.

---

#### Type 8 — Marketing website templates
**Action:** Translate the slug into pt-BR. No domain restructuring needed — translate the slug string itself.

| Source slug | Action |
|---|---|
| `project-management-with-asana` | Translate into pt-BR |
| `weekly-agenda-template` | Translate into pt-BR |
| `sprint-planning-team-room` | Translate into pt-BR |

---

#### Type 9 — PPC landing pages
**Action:** Translate the slug into pt-BR. Add `pt` as a subfolder in the position below.

**Formula — Lucidspark:**
```
https://lucidspark.com/pt/landing/[translated-slug]
```
*(Insert `pt` after `lucidspark.com/` and before `/landing/`)*

**Formula — Lucidchart:**
```
https://www.lucidchart.com/pages/pt/landing/[translated-slug]
```
*(Insert `pt` after `.../pages/` and before `/landing/`)*

| | URL |
|---|---|
| Source (Lucidspark) | `https://lucidspark.com/landing/product` |
| pt-BR | `https://lucidspark.com/pt/landing/[translated-slug]` |
| Source (Lucidchart) | `https://www.lucidchart.com/pages/landing/org-charts-software` |
| pt-BR | `https://www.lucidchart.com/pages/pt/landing/[translated-slug]` |

---

#### Type 10 — Help Center articles
**Action:** Help Center URLs are pre-translated. Two options:

1. Leave the URL in English — the Lucid team will update it.
2. Find the already-translated pt-BR URL: open the article, switch the interface language to Portuguese (Brazil), and copy the localized URL from the browser.

**Formula — localized URL pattern:**
```
https://help.lucid.co/hc/pt/articles/[article-id]-[translated-title]
```

| | URL |
|---|---|
| Source | `https://help.lucid.co/hc/en-us/articles/16390096079764-Add-and-customize-shapes-in-Lucidchart` |
| pt-BR | `https://help.lucid.co/hc/pt/articles/16390096079764-[translated-title]` |

---

#### Type 11 — Other marketing pages
**Action:** Translate the slug into pt-BR. Add `pt` as a subfolder in the position below.

**Formula — Lucidchart:**
```
https://www.lucidchart.com/pages/pt/[translated-slug]
```

**Formula — Lucidspark / Lucidscale / Lucid.co:**
```
https://[product-domain]/pt/[translated-slug]
```
*(Insert `pt` after the product domain and before the content path)*

| | URL |
|---|---|
| Source (Lucidchart) | `https://www.lucidchart.com/pages/examples/concept-map-maker` |
| pt-BR | `https://www.lucidchart.com/pages/pt/[translated-slug]` |
| Source (Lucidspark) | `https://lucidspark.com/create/online-sticky-notes` |
| pt-BR | `https://lucidspark.com/pt/[translated-slug]` |
| Source (Lucidscale) | `https://lucidscale.com/create/azure-architecture-diagram-software` |
| pt-BR | `https://lucidscale.com/pt/[translated-slug]` |
| Source (Lucid.co) | `https://lucid.co/solutions/hybrid-teams` |
| pt-BR | `https://lucid.co/pt/[translated-slug]` |

---

### 10.3 URL Rules Summary

| URL type | Translate slug? | Add `pt` code? | Position of `pt` |
|---|---|---|---|
| 1. Images | No | No | — |
| 2. In-product templates | No | Yes | After `lucid.app/`, before product name |
| 3. Pricing pages | No | Yes | After `lucid.app/`, before `/pricing/` |
| 4. Login pages | No | Yes | After `lucid.app/`, before `/users/` |
| 5. Training Labs | No | No | — |
| 6. Use-case pages | Yes | Yes | After `.../pages/` (Lucidchart) or after domain (Lucidspark) |
| 7. Blog posts | Yes | Yes | After domain, before `/blog/` (Lucidspark/Lucid.co) or after `/blog/` (Lucidchart) |
| 8. Marketing templates | Yes | No | — (slug only) |
| 9. PPC landing pages | Yes | Yes | After domain, before `/landing/` |
| 10. Help Center articles | No (pre-translated) | Yes (find existing) | After `/hc/`, replacing `en-us` |
| 11. Other marketing pages | Yes | Yes | After `.../pages/` (Lucidchart) or after domain (others) |

---

## 11. Reference Materials

- Lucid content style guide: [brandpad.io/lucid-content-style-guide](https://brandpad.io/lucid-content-style-guide/)
- Project glossary in Smartling (check for case-sensitive terms)
- Dicionário Houaiss da Língua Portuguesa
- Vocabulário Ortográfico da Língua Portuguesa (VOLP) — Academia Brasileira de Letras

---

*Source materials: General Lucid Software Style Guide · Lucidspark Blog Writing Style Guide*
*Filtered to pt-BR — Japanese voice instructions and non-pt-BR locale-specific content removed.*
