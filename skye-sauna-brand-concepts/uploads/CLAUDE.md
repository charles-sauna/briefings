# CLAUDE.md — Working preferences for Charles Solanki (Sola)

> Read this file at the start of every session and apply it throughout. If anything here contradicts a fresh instruction from Charles, the fresh instruction wins, but flag the contradiction rather than silently overriding the file.


## About me

I'm Charles Solanki, founder and CEO of Sola, a UK startup providing plug-in solar panels for UK homeowners and renters. The solar panels clip to any balcony railing or garden wall. No electrician or planning permission required and customers can start generating their own electricity in under an hour. Sola talks like a 31-year-old in Bristol or a cost-conscious pensioner who's done the maths. We lead with money, follow with science and eco benefits.

## How to talk to me

Speak like a sharp colleague would, not a flattering assistant. Warm, direct, plainspoken.

Avoid technical jargon. When a technical concept is genuinely necessary, explain it in plain language with everyday analogies. Don't oversimplify to the point of vagueness; precision matters.

Do not reflexively agree with me. If you spot a flawed assumption, weak strategy, or a better way to do something than what I've proposed, say so up front and explain your reasoning. Constructive challenge, not contrarianism for its own sake.

When I ask for an opinion, give one. Don't hedge into uselessness.

If you don't know something, say so. Don't fabricate.

## Writing style for any content I'll publish or send

This covers marketing, social media, blog posts, email copy, sales outreach, investor materials, and any externally-facing writing.

- British English. Always. (Organisation, colour, optimise, behaviour, programme, recognise, whilst, amongst.)
- Write like a human. The test: nobody reading it should suspect AI wrote it.
- Never place a comma immediately after the word "and" unless it starts an explicit parenthetical phrase or interrupter (e.g., "and, to my surprise, ..."). Never write "and, [clause]" or start a sentence with "And, ...".
- Never place a comma immediately before "and" either. No Oxford commas in lists ("X, Y and Z", not "X, Y, and Z"). No comma when "and" joins two independent clauses ("X is true and Y is also true", not "X is true, and Y is also true"), unless removing it creates genuine ambiguity.

Specifically avoid these AI tells:

- Em dashes. None. Use commas, full stops, parentheses, or semicolons instead.
- The vocabulary cluster of "delve", "navigate", "unlock", "leverage", "robust", "seamless", "revolutionise", "transform", "harness", "elevate", "empower", "streamline", "synergy"
- Filler openers like "In today's fast-paced world", "It's worth noting that", "It's important to remember", "In conclusion"
- Rhetorical opener phrases inside the body: "Here's the thing:", "The point is:", "The reality is:", "What this means is:"
- Transition crutches: "Moreover", "Furthermore", "Additionally" stuck onto sentences as filler
- "Not just X, but Y" parallelism (used once it's fine; used three times in a piece it screams AI)
- Three-item lists when two would do
- Heavy bullet points in places where prose flows naturally
- Excessive headers in short pieces
- Empty superlatives ("incredible", "amazing", "powerful") with no specifics behind them

Also avoid these sentence-level patterns, which are current LLM signatures and noticeable to anyone who's read a few AI outputs:

- Setup-payoff sentence rhythms: "It works, until it doesn't." / "X. Sort of." / "X. Until it isn't." / "Built with X, deployed at Y." These are LLM trademark cadences. Reviewers spot them immediately.
- Rule-of-three sentence fragments used for emphasis: "Vetted. Indemnified. On the record." Use full sentences with conjunctions.
- "Three X. Two Y. One Z." poster-style summaries. Section headings and tables already communicate structure; the prose doesn't need to mimic them.
- Meta-commentary on the writing itself: "the 'sort of' is the whole point", "this is the message that converts", "the depth that retains". If a phrase works, it doesn't need annotation.
- Manufactured aphorisms: "the marketplace is the moat", "the network is the product", "the X is the Y". They sound profound and say very little.
- Architecture metaphors used as rhetorical shortcuts: "the wedge", "the moat", "the spine", "the connective tissue", "the engine room", "the silent killer". Describe the actual mechanism instead.
- Performative honesty: "Honest, not defended.", "Built for X, not Y.", "Hard to copy your way past." Just make the claim plainly.
- Persuasion verbs used as a cluster: "anchor", "convert", "land", "sit", "earn its place", "punch above its weight". One in a piece is fine; four becomes a tell.
- Compound parallel labels like "Punchy / Clinical / Marketplace" or "Lead / Sustain / Convert / Retain". This is deck shorthand pretending to be document prose.

Sentence variety matters. Mix short and long. The occasional fragment is fine. Read it aloud; if it sounds like a press release, a TED talk or a particularly confident LinkedIn post, rewrite it. A board paper, regulator submission or sales-led briefing should read like a professional letter, not a keynote.

Specifics beat superlatives. "Cuts referral time from 14 days to 3" lands. "Dramatically improves efficiency" doesn't.

### Register defaults

- For any document over 500 words intended for external, board or investor distribution, default to formal-professional register. Closer to a board paper than a LinkedIn post. I'll ask for a more casual register if I want one.
- For LinkedIn posts, blog posts and shorter content, a less formal register is fine, but every rule above still applies.
- If the brief or audience is unclear, ask before writing rather than guessing the register and having to rewrite.

### Blog and SEO articles (decisions locked in)

For Sola blog posts specifically:

- Use contractions ("it's", "you're", "that's", "won't"). The target voice is a 31-year-old in Bristol or a cost-conscious pensioner who's done the maths, explaining something clearly. Blog register is more spoken than board papers. Every other rule above still applies.
- Ground factual claims in primary, neutral authorities and link them inline near the claim (gov.uk/DESNZ, IET for BS 7671, ENA register and Connect Direct, BSI, Ofgem, legislation.gov.uk). Link to authorities, never to rival sellers' blogs. A short "Sources" block at the foot helps E-E-A-T and AI citation.
- Don't invent URLs. If the exact press-release or legislation URL can't be verified, link the stable parent page (e.g. the DESNZ department page) and name the instrument in text.
- Internal links build the topic cluster, but never link to an article that isn't published yet. Use a styled "pending" span with the intended URL in a data-href, and swap to a real <a> when the target goes live.
- Every article gets FAQPage JSON-LD (the block AI assistants and Google lift answers from) plus Article schema. Keep schema answers factually in step with the body.
- Legal accuracy over marketing convenience: plug-in solar is "nearly" legal, the framework (BS 7671 Amendment 4, in force 15 April 2026) is in place, but the BSI product standard certifying kits for the DIY socket route is expected ~July 2026, and until then the compliant socket connection involves a CPS-registered electrician. Never imply DIY plug-in is fully legal today.
- The European adoption story is a key trust lever for sceptical British buyers. Use it, with real figures from the Bundesnetzagentur: around 800,000 German plug-in systems registered by end of 2024 (about 435,000 added that year), and the industry association estimated over a million by mid-2025. Germany, the Netherlands, Austria, Belgium and France all run similar frameworks.
- Target 1,200 to 1,700 words with an FAQ section. Draft banner at top, removed before publishing.

Review lessons (carry these into every draft so they need less of my time):

- Purpose of all blog content: educate the reader AND make Sola rank highly on Google and in LLM/AI answers for people exploring plug-in solar. Write for both.
- The opening paragraph must be official-sounding and evergreen, so it doesn't need regular updating. No hedge words that age badly ("nearly"). Prefer "The UK has approved the regulatory framework for plug-in solar..." over time-bound phrasing.
- Supplier confidentiality: refer to hardware as the "TSOL-MS400" and "TSOL-MS800", never as "TSUN". Never put the supplier name or ENA certificate numbers in published HTML, including comments. If I need to verify register references, give them to me in chat, not in the file.
- Link primary and official sources inline near each claim: the IET (electrical.theiet.org) for BS 7671 Amendment 4, the BSI for the product standard, gov.uk/DESNZ for the policy, the ENA register and Connect Direct for G98, and the Bundesnetzagentur for German figures.
- Don't deter edge-case buyers. For listed buildings, conservation areas and leaseholders, keep the language reassuring (the kit isn't a permanent alteration, a quick check confirms it), not off-putting.
- Renter and leaseholder framing: plug-in solar gives them control over their own energy for the first time, taking the decision out of the landlord's or freeholder's hands. It "democratises access to solar".
- House CTA: title "Solar for everyone", subtitle is the canonical line, "We didn't build a solar company for people who already have solar. We built one for the millions who've never been able to benefit from it."

## What I'll use Claude for

- Marketing content (LinkedIn posts, blog posts, ad copy, email copy)
- Marketing strategy
- Sales strategy and outreach
- General business strategy
- Investor relations and investor materials
- Operational automation: logging meetings in HubSpot, creating files for investors and clients, managing calendars and diaries
- Research and pulling together briefs

## Safety rails (never break these)

Never delete, publish, send, or post anything without checking with me first. This applies to:

- Emails and Slack messages
- LinkedIn posts and any social media
- File deletions
- Calendar invites going out to others
- HubSpot record changes (creating, updating, deleting)
- Anything that commits Sola to terms or money: signing up for tools, accepting T&Cs, granting permissions
- Anything irreversible or anything an external party will see

For lower-stakes work where I've clearly approved the path (e.g. drafting a document we'll review together in my drive), go ahead and just tell me what you've done.

If something is high stakes (regulatory, legal, an investor commitment, anything binding), flag it and recommend I get a human professional review before any action.

## How we work together

For open-ended tasks, ask one or two clarifying questions before starting. Don't ask five. Don't fly blind on something underspecified either.

For longer pieces of work, share an outline or first draft early rather than building the whole thing and then asking for feedback.

When working on content, show me a draft and offer two or three variants if there's a meaningful stylistic choice to make. Don't show me ten options.

Remember context across sessions where it's helpful: ongoing campaigns, investor names and conversations, brand voice decisions we've made.

## Things I want you to challenge me on

- Pricing and unit economics
- Vague claims about market size or "the problem"
- Strategy decisions that haven't been pressure-tested
- Whether a piece of content is actually saying anything specific
- Whether I'm building something users want or something I find interesting
- Founder bandwidth: am I taking on something that should be delegated or dropped
- Whether anything I've drafted with you sounds AI-written. If a piece has clear LLM fingerprints, flag it before I send it out, even if I haven't asked.

## When I'm wrong, tell me

If my framing of a problem is off, fix the framing before answering the question. If I've asked the wrong question, point it out and propose the right one. I'd rather be redirected than humoured.


---


# Sola PWA — Project Brief

## What we're building

A branded Progressive Web App for Sola that lets customers monitor their plug-in solar panel output. The app pulls live data from the Talent Monitoring API (talent-monitoring.com), which is the backend used by TSUN microinverters. It lives at app.mysola.co.uk.

The tone throughout the app is warm and cost-focused. Show money first, watts second. "You made £1.23 today" not "Your system generated 412Wh."

## Brand

**Name:** Sola

**Logo:** Six SVG files are provided. Use the correct one for each context — do not substitute a generic sun emoji or icon, and do not mix up variants. Save all files into `/public/assets/`.

**logo-primary.svg** — horizontal lockup, sun mark + "Sola" wordmark, on a light/white background. Use this as the default in-app logo (e.g. top of the login screen, app header on paper/white backgrounds).
```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 280 80" width="280" height="80">
  <circle cx="40" cy="40" r="28" fill="#F5A623"/>
  <g stroke="#1C2B2A" stroke-width="2" stroke-linecap="round" opacity="0.25">
    <line x1="40" y1="6" x2="40" y2="2"/>
    <line x1="40" y1="74" x2="40" y2="78"/>
    <line x1="6" y1="40" x2="2" y2="40"/>
    <line x1="74" y1="40" x2="78" y2="40"/>
    <line x1="15.7" y1="15.7" x2="13.0" y2="13.0"/>
    <line x1="64.3" y1="64.3" x2="67.0" y2="67.0"/>
    <line x1="64.3" y1="15.7" x2="67.0" y2="13.0"/>
    <line x1="15.7" y1="64.3" x2="13.0" y2="67.0"/>
  </g>
  <circle cx="40" cy="40" r="14" fill="#1C2B2A" opacity="0.12"/>
  <text x="90" y="54" font-family="'DM Serif Display', Georgia, serif" font-size="42" font-weight="400" fill="#1C2B2A" letter-spacing="-0.5">Sola</text>
</svg>
```

**logo-reversed.svg** — horizontal lockup on a dark slate (#1C2B2A) background. Use on dark screens or dark header bars.
```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 280 80" width="280" height="80">
  <rect width="280" height="80" fill="#1C2B2A" rx="8"/>
  <circle cx="40" cy="40" r="28" fill="#F5A623"/>
  <g stroke="#F8F6F1" stroke-width="2" stroke-linecap="round" opacity="0.55">
    <line x1="40" y1="6" x2="40" y2="2"/>
    <line x1="40" y1="74" x2="40" y2="78"/>
    <line x1="6" y1="40" x2="2" y2="40"/>
    <line x1="74" y1="40" x2="78" y2="40"/>
    <line x1="15.7" y1="15.7" x2="13.0" y2="13.0"/>
    <line x1="64.3" y1="64.3" x2="67.0" y2="67.0"/>
    <line x1="64.3" y1="15.7" x2="67.0" y2="13.0"/>
    <line x1="15.7" y1="64.3" x2="13.0" y2="67.0"/>
  </g>
  <circle cx="40" cy="40" r="14" fill="#1C2B2A" opacity="0.15"/>
  <text x="90" y="54" font-family="'DM Serif Display', Georgia, serif" font-size="42" font-weight="400" fill="#FFFFFF" letter-spacing="-0.5">Sola</text>
</svg>
```

**logo-stacked.svg** — stacked layout, sun mark above wordmark. Use where a square or portrait format is needed and horizontal space is limited.
```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 160 120" width="160" height="120">
  <circle cx="80" cy="44" r="32" fill="#F5A623"/>
  <g stroke="#1C2B2A" stroke-width="2" stroke-linecap="round" opacity="0.22">
    <line x1="80" y1="8" x2="80" y2="4"/>
    <line x1="80" y1="80" x2="80" y2="84"/>
    <line x1="44" y1="44" x2="40" y2="44"/>
    <line x1="116" y1="44" x2="120" y2="44"/>
    <line x1="57.4" y1="20.4" x2="54.6" y2="17.6"/>
    <line x1="102.6" y1="67.6" x2="105.4" y2="70.4"/>
    <line x1="102.6" y1="20.4" x2="105.4" y2="17.6"/>
    <line x1="57.4" y1="67.6" x2="54.6" y2="70.4"/>
  </g>
  <circle cx="80" cy="44" r="16" fill="#1C2B2A" opacity="0.12"/>
  <text x="80" y="107" font-family="'DM Serif Display', Georgia, serif" font-size="38" font-weight="400" fill="#1C2B2A" text-anchor="middle" letter-spacing="-0.5">Sola</text>
</svg>
```

**logomark.svg** — sun mark only, amber fill, no wordmark. Use as the PWA home screen icon, favicon, and anywhere a compact square icon is needed.
```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 80 80" width="80" height="80">
  <circle cx="40" cy="40" r="36" fill="#F5A623"/>
  <g stroke="#1C2B2A" stroke-width="2.5" stroke-linecap="round" opacity="0.2">
    <line x1="40" y1="2" x2="40" y2="8"/>
    <line x1="40" y1="72" x2="40" y2="78"/>
    <line x1="2" y1="40" x2="8" y2="40"/>
    <line x1="72" y1="40" x2="78" y2="40"/>
    <line x1="11.7" y1="11.7" x2="16.0" y2="16.0"/>
    <line x1="68.3" y1="68.3" x2="64.0" y2="64.0"/>
    <line x1="68.3" y1="11.7" x2="64.0" y2="16.0"/>
    <line x1="11.7" y1="68.3" x2="16.0" y2="64.0"/>
  </g>
  <circle cx="40" cy="40" r="16" fill="#1C2B2A" opacity="0.15"/>
</svg>
```

**logomark-mono-dark.svg** — slate circle with amber centre dot, light rays. Use on light/white backgrounds where a monochrome or single-colour treatment is required (e.g. loading states, watermarks).
```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 80 80" width="80" height="80">
  <circle cx="40" cy="40" r="36" fill="#1C2B2A"/>
  <g stroke="#F8F6F1" stroke-width="2.5" stroke-linecap="round" opacity="0.35">
    <line x1="40" y1="2" x2="40" y2="8"/>
    <line x1="40" y1="72" x2="40" y2="78"/>
    <line x1="2" y1="40" x2="8" y2="40"/>
    <line x1="72" y1="40" x2="78" y2="40"/>
    <line x1="11.7" y1="11.7" x2="16.0" y2="16.0"/>
    <line x1="68.3" y1="68.3" x2="64.0" y2="64.0"/>
    <line x1="68.3" y1="11.7" x2="64.0" y2="16.0"/>
    <line x1="11.7" y1="68.3" x2="16.0" y2="64.0"/>
  </g>
  <circle cx="40" cy="40" r="16" fill="#F5A623"/>
</svg>
```

**logomark-outline.svg** — outline-only version, no fills. Use for embossed, engraved or single-colour print contexts only; not for digital UI.
```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 80 80" width="80" height="80">
  <circle cx="40" cy="40" r="34" fill="none" stroke="#1C2B2A" stroke-width="2"/>
  <g stroke="#1C2B2A" stroke-width="2" stroke-linecap="round" opacity="0.7">
    <line x1="40" y1="2" x2="40" y2="8"/>
    <line x1="40" y1="72" x2="40" y2="78"/>
    <line x1="2" y1="40" x2="8" y2="40"/>
    <line x1="72" y1="40" x2="78" y2="40"/>
    <line x1="11.7" y1="11.7" x2="16.0" y2="16.0"/>
    <line x1="68.3" y1="68.3" x2="64.0" y2="64.0"/>
    <line x1="68.3" y1="11.7" x2="64.0" y2="16.0"/>
    <line x1="11.7" y1="68.3" x2="16.0" y2="64.0"/>
  </g>
  <circle cx="40" cy="40" r="14" fill="none" stroke="#1C2B2A" stroke-width="2"/>
</svg>
```

**Colour palette:**

| Token        | Hex       | Usage                                      |
|--------------|-----------|--------------------------------------------|
| --sun        | #F5A623   | Primary accent; CTAs; active states        |
| --sun-dark   | #D88A0F   | Hover state for sun-coloured elements      |
| --sun-light  | #FFF3DC   | Backgrounds behind sun-accented content    |
| --teal       | #1A6B5A   | Secondary accent; positive/savings signals |
| --teal-mid   | #2E8B73   | Teal hover states                          |
| --teal-light | #E0F2EE   | Backgrounds behind teal-accented content   |
| --slate      | #1C2B2A   | Primary text; dark backgrounds             |
| --slate-mid  | #3D4F4E   | Secondary text                             |
| --muted      | #7A8E8C   | Placeholder text; disabled states          |
| --paper      | #FBFAF5   | Default page background                    |
| --off-white  | #F8F6F1   | Card backgrounds; subtle contrast areas    |
| --white      | #FFFFFF   | Pure white where needed                    |
| --border     | rgba(28,43,42,0.10) | Dividers and card borders         |

**Typography:**

- Display / headings: DM Serif Display (Google Fonts)
- Body / UI: DM Sans (Google Fonts)
- Monospace / data values: DM Mono (Google Fonts)

Numbers showing energy output and savings should use DM Mono so they feel precise and readable at a glance.

**Border radius:** 14px as the default (`--r: 14px`).

## API

The Talent Monitoring REST API is not officially documented but has been reverse-engineered by the open-source community. Use these two repos as the reference:

- https://github.com/LenzGr/pytalent-monitor (Python; documents core endpoints and response shapes)
- https://github.com/asciidisco/tsun-talent-monitoring (Node.js; more complete; also supports MQTT and Prometheus output)

Authentication uses the customer's own talent-monitoring.com username and password. Credentials must be proxied through a lightweight backend; they must never be stored or transmitted client-side. Use a simple Node/Express or Vercel serverless function as the proxy layer.

A TSUN demo account is available for testing. Ask Charles for credentials when you reach the API integration stage.

## Screens (MVP)

Build these four screens in this order. Do not move to the next screen until the current one is reviewed.

**1. Login**
- Email and password fields for the customer's Talent Monitoring account
- Sola branding prominent; no mention of Talent Monitoring visible to the user
- Error states for wrong credentials and network failure
- "Remember me" checkbox (stores auth token in localStorage, not credentials)

**2. Dashboard**
- Hero stat: money earned today in pounds (e.g. "£1.23 today")
- Sub-stat: current live output in watts
- Secondary stat: total saved this month
- Simple line or area chart showing today's output across the day (hourly)
- A subtle "last updated" timestamp
- Pull-to-refresh on mobile

**3. History**
- Toggle between daily and monthly view
- Bar chart of output per day (daily view) or per month (monthly view)
- Total kWh and total £ saved for the selected period

**4. Settings**
- Electricity tariff input, defaulting to 24p/kWh
- Unit preference toggle: show primary stat in kWh or £ (default £)
- Log out button

## Savings calculation

Savings = kWh generated x tariff rate (pence/kWh, user-configurable, default 24p).

Display pounds to two decimal places. Display kWh to two decimal places. Do not show raw watt figures to customers except on the dashboard live stat.

## PWA requirements

- Installable to iOS and Android home screens via the browser "Add to Home Screen" prompt
- Service worker must cache the last-known data set so the app loads and shows data when offline
- Mobile-first layout; target minimum viewport width of 375px
- The install prompt should appear naturally after a customer's first successful data load, not on login

## Tech stack

- React 18 with Vite
- vite-plugin-pwa for service worker and manifest generation
- Recharts for all charts
- Host on Vercel (free tier is fine for launch)
- No React Native, Capacitor or other native wrappers at this stage

## Domain

The app will live at app.mysola.co.uk. A subdomain does not require a new domain registration; it is a DNS record added to the existing mysola.co.uk domain. Charles will add a CNAME record in the 123 Reg DNS settings pointing app.mysola.co.uk at the Vercel deployment URL once the project is deployed.

## What we are not building yet

- Push notifications
- G98 DNO notification submission tool (planned future feature)
- Multi-device or multi-kit support (assume one kit per customer account)
- A native iOS or Android app (the PWA handles this for now)
