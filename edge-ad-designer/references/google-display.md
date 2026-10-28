# Google Display: GDN, Demand Gen, Performance Max image assets (DV360 in brief)

Researched 2026-10-27 from Google Ads Help and Ads Policy pages. *[verify]* means two Google pages disagree or the item couldn't be confirmed.

## Which product, which creative

| Product | You supply | Google does | Design for |
|---|---|---|---|
| **Responsive Display Ads (RDA)** | Images, logos, headlines, descriptions as separate assets | Mixes and crops them into thousands of placements | **Clean images with no burned-in copy.** The message lives in the text fields |
| **Uploaded image ads** | Finished banners at fixed sizes | Serves them as-is | **Full-copy designed banners.** This is where your layout and edge live |
| **Demand Gen** | Images and video for YouTube, Discover, Gmail | Feed-style placements | Social-style creative (4:5 and 9:16 supported) |
| **Performance Max** | Image, logo, text and video assets | Spreads them across all Google inventory | Same as RDA, plus a 4:5 portrait |
| **HTML5** | A ZIP of animated ads | Serves them | Only for **allowlisted** accounts (open more than 90 days, more than US$9k spend, good policy history). Plan on static images for a new advocacy account |

## Specs

### Uploaded image ads
- **Files:** GIF, JPG or PNG, **150 KB max**.
- **Core set to produce:** **300×250, 336×280, 728×90, 300×600, 160×600, 320×50, 320×100, 970×250**.
- **Other sizes:**
  - 200×200, 240×400, 250×250, 250×360, 580×400
  - 120×600, 300×1050
  - 468×60, 930×180, 970×90, 980×120
  - 300×50
- **Animation:** 30 seconds total at most. Loops are allowed but must stop by 30s. **Under 5 FPS** for GIFs. Show the final frame (message, CTA, logo) by about 15s.
- **Export:** PNG-8 or JPG at about 70–80% quality to stay under 150 KB. Render at 1x; you can make 2x versions if the file stays under the size limit.

### RDA, Demand Gen and PMax assets

| Asset | RDA | Demand Gen | PMax |
|---|---|---|---|
| Landscape 1.91:1 | 1200×628 (min 600×314), required | 1200×628 | 1200×628, required, 4+ recommended |
| Square 1:1 | 1200×1200 (min 300×300), required | 1200×1200 | 1200×1200, required, 4+ recommended |
| Portrait 4:5 | ❌ *[verify]* | 960×1200 | 960×1200, 2+ recommended |
| Vertical 9:16 | 900×1600 optional *[verify]* | 1080×1920 (Shorts safe zones apply) | via video |
| Logo 1:1 / 4:1 | 1200×1200 / 1200×300 | 1:1 (Gmail crops it to a **circle**, so keep the corners empty) | 1200×1200 required / 1200×300 |
| Headline | ≤30 chars ×5 | ≤40 chars ×5, **at least one ≤30**, or it won't serve on Display | ≤30 chars ×3–15, **at least one ≤15** |
| Long headline | ≤90 chars | — | ≤90 chars ×1–5 |
| Description | ≤90 chars ×5 (write ≤80 *[verify]*) | ≤90 chars ×5 | ≤90 chars ×2–5 (one ≤60 *[verify]*) |
| Business name | ≤25 chars | ≤25 chars | ≤25 chars, must match the domain or verified name |

## Display-specific creative rules

| Rule | Type | Design response |
|---|---|---|
| Image must **fill the whole frame**: no empty margins, not sideways or upside down | Policy | Bleed the background to every edge |
| No blurry images or **illegible text** | Policy | Never shrink type to make it fit. Cut words instead |
| No strobing, flashing or "distracting" animation | Policy | Slow, simple motion only |
| No images that look like **site warnings, error messages or OS notifications** | Policy | No alert triangles, system dialogs or fake toasts |
| **Standalone buttons** with no context, or oversized buttons (fake play, close or download). Enforced since Jan 2025 | Policy (Misleading Ad Design) | The CTA must be a **labelled** button in proportion to the ad ("Tell your senator"), never a bare arrow or play icon |
| No gimmicky repetition, spacing or symbols | Policy (Editorial) | Normal punctuation; sentence case in text fields |
| "Unidentified business": the ad or landing page must name the advertiser | Policy | Logo always visible |
| "Unclear relevance": every asset must represent the same advertiser and offer | Policy | — |
| Light, white or transparent backgrounds need a visible border | Legacy rule *[verify]* | Add a 1px grey border anyway; it costs nothing |
| RDA images: no overlaid text, logos or buttons, no collages, no borders | Best practice (Google says it is not mandatory) | Overlaid text gets cropped and rated "Poor". Text that is naturally in the photo (a protest sign, a shop front) is fine |
| No 20% text rule | — | — |

## Political and issue ads on Display

- **US election ad** = features a federal, state or territorial officeholder or candidate, a party, or a ballot measure that has *qualified for the ballot*. An issue ad that names none of these is an ordinary ad.
- **Election-ad targeting** is limited to:
  - location (no radius)
  - age
  - gender
  - **contextual** targeting (placements, topics, keywords)

  So no remarketing, Customer Match or custom audiences. A Display campaign that names a legislator has to be built on context.
- **"Paid for by"**:
  - Google adds it automatically for most formats.
  - You must put it **in the creative itself** for third-party-served GDN or YouTube ads and DV360 native, audio and off-YouTube video.
  - **Put it on every issue or election banner anyway.** It's cheap, some state laws require it, and it signals legitimacy to reviewers.
- **Synthetic or altered content**: tick the box, and **burn the disclosure into image ads yourself** ("This image does not depict real events"). Google only adds the label automatically for feeds, Shorts and in-stream.
- **EU**: closed since Sept 2025. In DV360, every line item needs a yes/no EU political declaration.

## Tobacco and vaping advocacy on Display

- **Rules**:
  - Google bans tobacco and products that simulate smoking, **including e-cigarettes**, with **no written exception for advocacy**.
  - Policy ads with no product imagery usually run, but expect keyword-triggered disapprovals and manual review.
  - Keep an appeal file that frames each ad as public-policy speech.
- **Imagery**:
  - **Never** show devices, vapour, packs or flavours.
  - Use people, capitol buildings, ballots, documents, price tags and data.
- **Landing page**: petition, rep-contact form or research. No shop links, no product reviews, no age-gate pages.
- **Publisher blocking**:
  - Ad Manager publishers can block the sensitive category **"Politics"** (which covers controversial social issues) and **"Sensationalism"**.
  - Flavour-ban ads will likely be classified as political, which shrinks inventory.
  - Alarmist copy risks the Sensationalism block as well.
  - **On Display, measured and factual copy reaches more inventory than shouty copy.** The edge comes from the *idea*, not the volume.

## Banner craft

- **One message, one visual, one labelled CTA, logo always visible.** Aim for WCAG contrast of at least 4.5:1.
- **Banners are glanced at, not read.** The concept must land in about 1 second at 300×250. Display's version of the social-ad hook is a **single bold claim plus a brand mark**.
- **Small sizes:**
  - **320×50 / 300×50**: logo, about 5 words, CTA. Text at least 12–14px bold. No body copy.
  - **728×90 / 970×90**: left to right as logo, headline (8 words or fewer), CTA. Text at least 14px.
  - **160×600 / 300×600**: stacked vertically. The tall canvas suits a "list", or a "stat on top, CTA at the bottom". Avoid long words that break mid-word.
  - **300×250 / 336×280**: the workhorse sizes. Headline, support line, CTA, logo.
- **Re-compose each size; never scale one design.** Headlines often need a shorter version for leaderboards and mobile banners.
- **Concepts that translate well from social:** stat card, this-vs-that (tall and wide sizes), the mock-official stamp (300×250, 300×600), and a real-deadline CTA.
- **Concepts that don't translate:** post- or tweet-style designs (too small to read) and dense carousels.
- **RDA image sets**: supply 5 distinct images per ratio with the subject centred, because crops vary:
  - real adults (testimony faces)
  - the statehouse
  - a "CLOSED" shop front with no products visible
  - a ballot or document close-up
  - a price receipt
