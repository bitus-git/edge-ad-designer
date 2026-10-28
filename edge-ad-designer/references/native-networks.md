# Native ad networks: Taboola, Teads (formerly Outbrain), Yahoo, MGID, Revcontent, Nativo

Researched 2026-10-27. *[verify]* = not confirmed from a primary source.

**Name changes:**
- Taboola's ad platform is now called **Realize**, and its help docs are at realize.com/help.
- **Outbrain became Teads** in June 2025. Both the legacy Outbrain guidelines and teads.com/ad-policies apply.
- **Nativo** now belongs to Life360 (ads.life360.com).

## How native differs from social

- **Context.** Native ads appear in "Recommended for you" widgets under real publisher articles. People arrive in reading mode, and the ad borrows the publisher's credibility. That is exactly why networks police anything that imitates editorial content.
- **There's no social layer.** No shares, no comments, no social proof. **All the persuasion happens on the landing page**, which is why the standard funnel is:
  > headline + thumbnail → **pre-lander** (an advertorial, listicle or explainer labelled "Advertorial") → action (petition, email to a legislator, sign-up) → retargeting pixel
- **The economy runs on curiosity gaps.** Click-through rate depends on an information gap, and the policy limit is that **the landing page must close the gap above the fold.** "Misleading headline or image" is the most common rejection reason.
- **Human pre-approval, plus publisher blocklists.** Many premium publishers block political and issue categories entirely. Expect less inventory and higher cost per click for issue campaigns.
- **Political tooling is thinner than on social.** There's no public ad library. Approval runs through **account-manager pre-clearance**.

## Can issue advocacy run?

| Network | Political / issue ads | Requirements | Regions |
|---|---|---|---|
| **Taboola / Realize** | ⚠️ **Restricted.** Pre-clear with your account manager. (A spokesperson said in 2019 that Taboola "bans political ads", so practice has shifted.) | "Paid for by [X]" on the landing page, plus FEC-style candidate authorisation. Branding text must name the real source | Banned in Brazil, China, Japan, Korea and Russia. In Israel, positive content only. **EU *[verify]*: assume no** |
| **Teads / Outbrain** | ⚠️ Restricted, and explicitly covers "political issues". May be denied at Teads' discretion | Payer shown **on the ad and on the landing page**. Targeting limited to geography, age and gender, or contextual. NY and VA require state documentation. Respect election silence periods | **US only.** No EU, UK or Canada |
| **Yahoo Native / DSP** | ⚠️ Issue ads are allowed at Yahoo's discretion after Ad Policy pre-approval. Must be account-managed | Payer visible **in the ad before the click**, in a contrasting colour | Banned in the EU, Brazil, the Middle East and North Africa, and Saudi Arabia. Issue ads banned in Switzerland |
| **MGID** | ⚠️ Restricted "subject to regional regulations" *[verify]* | Not published | *[verify]* |
| **Revcontent** | ? No political policy found. Bans "demonstrably false" political news, and reportedly bans text "advocating against an organization, person or group" *[verify]* | — | — |
| **Nativo** | ? No public political policy found *[verify]* | — | — |

**Watch out for Taboola §15.** Ads must not "exploit… controversies (e.g. political change), social issues" to promote content. Providing reliable information during political change *is* allowed. So an issue ad tied to a news event has to read as **information, not opportunism**: use explainer framing, not outrage framing.

**No attack ads on Teads/Outbrain.** Ads must not "humiliate, disparage, mislead or incite against a candidate, party, or population group." Keep criticism on the **policy and its effects**, not the person. Of all the channels, this is the most conservative.

## Tobacco and nicotine

- **Product promotion is banned** on Taboola (including e-cigarettes and "vaporized delivery devices"), Yahoo (e-cigarettes "even if marketed as… reduced-risk"), MGID, and Teads (except the US, Japan and the Philippines with heavy conditions).
- **Policy advocacy isn't addressed anywhere.** It runs through the political/issue path, so pre-clear it.
- **Landing pages** must have no retailer links, no packshots, no "where to buy" text and no coupons.
- **Taboola also restricts government symbols and buildings and unauthorised logos.** A Capitol dome or an agency seal in a *thumbnail* is a risk there. Use people, documents, price tags and data instead.

## Creative rules that bite on native

| Element | Rule | Edge-safe version |
|---|---|---|
| **Headline** | Must reflect the landing page accurately. No ALL CAPS, no "?!?!", no emoji (Teads). Teads bans "stuns", "reveals" and "you won't believe". Nothing "too good to be true". Taboola bans "rumours of political intrigue" | **Contrarian plus specific.** "The Flavor Ban That Sent Smokers Back to Cigarettes" passes if the page cites the study. "Doctors Are Furious About This Vape Ban" fails |
| **Thumbnail** | Not misleading or significantly altered. No before/after. No politicians or celebrities without permission. No circles or arrows, no fake play icons (Teads). No sensational or shock imagery, no fake system warnings. AI images labelled at first exposure | **An authentic photo of a real adult, shoulders up, looking at the camera, one focal point.** Little or no text on the image |
| **Branding text** (≤30 chars) | Must be the true source | Your organisation's real name. Never a made-up outlet name |
| **Advertorial pre-lander** | "Advertorial" or "Advertisement" **clearly at the top**. Must not look editorial: no fake outlet masthead, no fake navigation, no fake reporter photos. The page's primary purpose can't be advertising (Teads) | An **article-style page under your own masthead**: "ADVERTORIAL · Paid for by [Org]" bar at the top, real byline, cited sources, then the action form |
| **Comments and testimonials** | Only real social comments linked to their source, and real testimonials with disclosure | Real supporter quotes with the person's consent and first name or initial. No fabricated comment sections |
| **Urgency** | No countdown timers, auto-updating timestamps or false "ends soon". No shock, scare or "doomsday" tactics | **Real dates**: "Comment period closes Nov 14" |
| **Seals and "as seen in"** | Media logos must link to the actual article | Link every "as reported in" to the real story |
| **AI** | Labelled at first exposure (Teads). No real people without consent | Avoid AI images of people on native |

## Specs

| Field | Taboola / Realize | Teads / Outbrain |
|---|---|---|
| Title | 34–45 characters ideal, **60 maximum**. Put the key idea first because titles get truncated | ~60 *[verify]*, no emoji |
| Description | ≤250 characters, often not shown | ~150 *[verify]* |
| Branding text | ≤30 characters | Must include the payer for political ads |
| Image | **1200×674 (16:9)**, also 4:3 and 1:1. Minimum 600×400. ≤5 MB, JPEG. Auto-cropped, so keep the subject centred | 1200×800 or 1.91:1 *[verify]* |
| Motion | mp4/mov/gif, 16:9, ≤15s, ≤50 MB (gif ≤5 MB), muted autoplay | *[verify]* |

## Headline formulas that work on native and pass review

- "[Number] things [audience] should know about [policy]"
- "Why [place] is rethinking [policy]"
- "What [policy] actually costs [audience]"
- "[Group] in [State]: [real vote date] could change [thing]". Taboola's dynamic location insertion lifts CTR here.
- "The [policy] [real outcome] nobody's talking about", only if the page proves it
- A question **only if the page answers it in the first screen**

Test titles in Taboola's headline analyser at **trends.taboola.com** before launch.

## What to deliver for a native campaign

1. **5–10 headline variants** (≤60 characters, front-loaded) across 3 frames, for example liberty, harm and cost.
2. **3–5 thumbnails** at 1200×674, mostly real faces with no text overlay. Optionally one with a bold stat for contrast testing.
3. **Branding text:** the org name.
4. **An advertorial pre-lander spec or page:**
   - label bar
   - headline that matches the ad title
   - 400–800 word explainer with cited sources
   - a real testimonial
   - action form above and below the fold
   - "Paid for by"
5. **Pre-clearance note for the account manager:** issue, payer, regions, landing URL.
