# Line check: pre-flight for every ad

Run every item against each deliverable. Output a pass/flag table. A flag must be fixed, or marked
"client decision — legal review" with the reason.

## A. Gate (can it run, and is it set up right?)
- [ ] Classified as **prohibited** or **restricted** on each target platform (`platform-matrix.md`)
- [ ] If it's an issue or political ad: category declared, advertiser authorised or certified, "Paid for by" verified
- [ ] No EU targeting for policy content; no TikTok or LinkedIn paid placement for policy advocacy
- [ ] No election blackout window active (Meta US: Oct 27 – Nov 3, 2026)
- [ ] Age targeting correct (21+ for nicotine or alcohol topics)
- [ ] Google: if an officeholder, candidate, party or ballot measure is named, the election-ads path is used

## B. Honesty (the hard line)
- [ ] No imitation of a real outlet's, agency's or company's branding
- [ ] Every "news" element is either our own brand or a real, unaltered, dated, attributed screenshot
- [ ] No fabricated quotes, posts, headlines, documents or endorsements tied to real people or organisations
- [ ] Mock-official items use an obviously fictional agency name
- [ ] No fake UI (play or close buttons, badges, OS alerts, platform chrome)
- [ ] No photorealistic fake depiction of a real person; any AI-altered realistic media is disclosed
- [ ] Every deadline and urgency claim is real
- [ ] Sponsor is clearly identifiable; ad and landing page match

## C. Claims
- [ ] Every stat has a visible source on the image and a full citation in the caption or landing page
- [ ] No health, safety or cessation claims about nicotine products ("safe", "helps you quit")
- [ ] Attacks target official acts and policy records, not character or personal life
- [ ] Nothing defamatory: every factual statement about a named person can be documented

## D. Category content
- [ ] Nicotine: no devices, packs, pouches, vapour, consumption, brands or flavour cues
- [ ] Alcohol, cannabis, gambling: no consumption emphasis, no product hero, no betting UI
- [ ] Nothing youth-appealing (cartoon mascots aimed at kids, candy aesthetics, school settings)

## E. Copy rules
- [ ] No personal-attribute assertions ("Are you a smoker?", "You vape, so…")
- [ ] No engagement bait; any ask has a purpose
- [ ] No withheld-info clickbait; any open loop is closed in the ad
- [ ] All caps limited to 1–2 words; normal punctuation; emoji sparing
- [ ] No gore or shock imagery; no weapons aimed at the viewer
- [ ] No discouraging voting, delegitimising elections or premature victory claims

## F. Rights
- [ ] All photos, fonts, footage and music are owned or licensed
- [ ] Meme formats recreated with original art
- [ ] Creator content carries the paid-partnership label (plus SIEP setup on Meta when political)

## F2. Native-specific (Taboola, Teads, Yahoo, MGID)
- [ ] Issue campaign pre-cleared with the account manager; region allowed (Teads: US only)
- [ ] Title delivers on its promise above the fold of the landing page (no unclosed curiosity gap)
- [ ] No "stuns / reveals / you won't believe", no emoji, no ALL CAPS, no "?!?!"
- [ ] Thumbnail is an honest, unaltered image: no arrows or circles, no fake play icon, no politician without permission, no government seal or building on Taboola
- [ ] Branding text is the real organisation name
- [ ] Pre-lander has "Advertorial / Paid for by [Org]" at the top, our own masthead, real byline, cited sources, and no fake comments, reporter photos or timers
- [ ] Teads: criticism is about policy, not about disparaging a candidate or party

## F3. Google Display-specific
- [ ] Uploaded banners ≤150 KB, fill the frame, 1px border on light backgrounds
- [ ] CTA is a labelled button in proportion to the ad (no bare play, arrow or close icons)
- [ ] Nothing looks like a system warning or error message
- [ ] Animation stops by 30s; GIFs under 5 FPS; no strobing
- [ ] Text legible at every size (small sizes: cut words, don't shrink type)
- [ ] Responsive image assets carry no burned-in text, logos or buttons
- [ ] Headlines, descriptions and business name are within character limits; at least one short headline is included
- [ ] "Paid for by" inside the creative; election ads targeted contextually only; synthetic imagery disclosed in the image

## G. Craft (not compliance, but don't ship without it)
- [ ] Hook readable at thumbnail size in under 1 second
- [ ] Text inside the safe zones for every exported size
- [ ] 4:5, 9:16 and 1:1 re-composed, not cropped
- [ ] Ad is tagged (frame / format / hook / villain / CTA) for the test log

## Edge rating scale
- 🔥◻◻◻◻ Safe. Will pass, but may not stop the scroll.
- 🔥🔥🔥◻◻ Bold. Clear point of view, named target, strong visual.
- 🔥🔥🔥🔥◻ On the line. Uses a restricted gate fully, sharp satire or a named official. Expect manual review; have sources ready.
- 🔥🔥🔥🔥🔥 Reserved for work that is maximally provocative **and** passes every check above. If any box in B fails, it isn't a 5. It's a rejection.
