# Homepage Rebuild — SEO & GEO Rationale

**Prepared by:** Brazil Singh · July 2026
**Accompanies:** `human-homepage-seo.html` (draft mockup)

---

## 1. The core finding

The current homepage targets **competitor brand names** — "Agentforce Alternative", "Zapier Alternative", "Salesforce Alternative". These are terms we cannot realistically rank for, they invite direct comparison on the competitor's own terms, and they describe Corteza's old positioning rather than what @Human actually is.

Keyword research shows a far better opportunity sitting unclaimed.

## 2. Keyword data (Ubersuggest, US market)

| Keyword | Volume/mo | SEO difficulty | CPC | Verdict |
|---|---|---|---|---|
| **AI governance platform** | 1,300 | **23** | **$49.14** | **Primary target** |
| **open source AI platform** | 2,400 | **5** | $6.27 | Secondary — trending hard |
| **sovereign AI** | 2,900 | 26 | $7.07 | Secondary — on-brand |
| AI agent governance | 170 | 30 | $32.99 | Supporting, high intent |
| EU AI Act compliance | 170 | 16 | $15.01 | Supporting, high intent |
| EU AI Act compliance software | ~0 | 4 | — | Future / easy win |

**Why "AI governance platform" is the primary target:** 1,300 monthly searches at difficulty 23 is genuinely winnable for a domain with our authority, and the **$49 CPC is the real signal** — advertisers only pay that much per click when the traffic converts into serious pipeline. It is also an accurate description of what @Human does, which matters for both ranking and conversion.

**Why "open source AI platform" matters:** difficulty 5 — almost free to rank for — and volume has climbed sharply over recent months (from a few hundred to several thousand searches). Low effort, rising demand, and it is literally true of us.

**"Sovereign AI"** already appears in our current copy, so we keep the equity we have while adding the terms that convert.

## 3. What changed on the page

**H1 (the site currently has none at all):**
> The open-source **AI governance platform** for the EU AI Act.

One H1, carrying the primary keyword plus two secondary ones, describing the product accurately.

**Title tag:** `@Human — Open-Source AI Governance Platform | EU AI Act Compliance | Planet Crust`
**Meta description:** written to earn the click, with the primary keyword in the first six words.

**Heading structure:** a clean H1 → H2 → H3 hierarchy, with H2s phrased as the questions buyers actually ask ("Your AI agents are already running. Can you prove what they did?", "What is an AI governance platform?").

## 4. GEO — built to be cited by AI engines

Roughly half our current traffic is AI crawlers, but we earn no citations back, because the site gives those crawlers nothing structured to quote. The new page fixes that:

- **JSON-LD structured data** — `Organization`, `SoftwareApplication` (with licence, feature list and offer), and a **`FAQPage`** block. This is how AI engines and Google identify what @Human *is* as an entity.
- **A visible FAQ section that mirrors the schema** — four questions, each answered in a single self-contained paragraph of 40–60 words. This is the format AI engines extract and quote directly.
- **Answer-first paragraphs** under each heading, so the answer appears before the elaboration.
- **Specific, verifiable facts** — Apache 2.0, in production since 2019, Commons Conservancy governance, NGI Zero funding, and the Treaty Compliance Layer's actual instrument list (EU AI Act, GDPR, CETS 225, EU Charter of Fundamental Rights, UNESCO AI ethics recommendation, ILO conventions). Research consistently shows that statistics, citations and named specifics are what get quoted; vague marketing claims are ignored.
- **Consistent entity naming** — "@Human", "Planet Crust", "Corteza" used the same way throughout so engines can model the relationship between them.
- **Explicit crawler permissions** in the robots meta tag, plus canonical URL and full Open Graph tags.

Worth noting: our **docs site already publishes an `llms.txt`** and serves markdown versions of pages, so it is AI-crawler friendly. The marketing site is not. This page closes that gap, and I would add an `llms.txt` to the main domain as a follow-up.

## 5. On-page SEO checklist — status in this draft

- ✅ Single H1 with primary keyword
- ✅ Logical H2/H3 hierarchy, question-phrased
- ✅ Optimised title tag and meta description
- ✅ Canonical URL
- ✅ Open Graph + Twitter card tags
- ✅ Semantic HTML5 (`header`, `section`, `nav`, `footer`)
- ✅ Descriptive ARIA labels on all product visuals
- ✅ Keyboard-visible focus states, reduced-motion support
- ✅ Internal links to docs, demo centre and pricing
- ✅ Mobile-first responsive across all breakpoints
- ⬜ Real product screenshots with keyword-rich alt text *(placeholders in draft)*
- ⬜ `llms.txt` on the main domain *(follow-up task)*
- ⬜ Customer logos and testimonials *(needs approval — see below)*

## 6. Off-page — what the page cannot fix alone

Ranking and citation both depend on signals beyond the page itself. The priorities:

1. **Claim the G2 profile** and generate reviews — currently unclaimed with zero reviews, which is a visible gap for a buyer comparing vendors.
2. **Get listed in third-party "best AI governance platform" roundups** — these are heavily cited by AI engines when answering vendor-comparison questions.
3. **Earn the first independent mentions of "@Human"** — the brand has almost no existence off our own domain, which limits how confidently any engine will cite it.
4. **Publish one original-data asset per quarter** — a benchmark or survey nobody else has. This is the most durable citation lever available to us.

## 7. Open questions for review

1. **Positioning:** confirm we lead with "AI governance platform" and retire the Agentforce/Zapier/Salesforce alternative framing on the homepage.
2. **Customer proof:** which customers may we name, and can we obtain two or three short quotes? This is the single biggest conversion gap on the page.
3. **CTA destination:** should "Book a governance walkthrough" go to your calendar, or should I run an initial qualification call first?
4. **EU AI Act dates:** I have deliberately avoided citing specific compliance deadlines, as the timeline appears to have shifted under the Digital Omnibus. Before we publish anything date-specific, it should be verified against the current Official Journal text — we are selling to compliance officers and a wrong date would cost us credibility.

---

*Draft for review. Nothing published until approved.*
