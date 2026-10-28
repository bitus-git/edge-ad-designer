# Edge Ad Designer: a Claude skill

A Claude skill that works as a senior ad designer for **edgy, regulated and controversial topics**: policy advocacy, tobacco and nicotine harm reduction, alcohol, cannabis, gambling and "nanny state" fights.

It is built to make ads that **stop thumbs and still get approved**. It pushes each platform's rules as far as they go, and it refuses to make anything deceptive.

## What it does

- **Gate check first.** Before designing, it works out whether your ad can run on each platform and what setup each one needs:
  - **Social:** Meta, Google/YouTube, X, TikTok, LinkedIn, Snap, Reddit
  - **Native:** Taboola/Realize, Teads/Outbrain, Yahoo, MGID
  - **Display:** Google Display, Demand Gen, Performance Max That setup covers issue-ad authorisation, "Paid for by" labels, special ad categories, age targeting, EU restrictions and election blackouts.
- **Wide range of concepts.** It produces 3–6 genuinely different concepts, varying the moral frame, hook type, format and villain, rather than many versions of one idea.
- **A "why is this banned?" check for every format.**
  - A restriction that exists to gate a sensitive category gets used to the full.
  - A quality penalty, such as engagement bait, gets its psychology kept and its gimmick dropped.
  - A deceptive format, such as a fake "BREAKING" banner or fake buttons, gets rebuilt as an honest version.
- **Line check.** Every ad goes through a pre-flight checklist and gets an edge rating.
- **Test plan.** It suggests what to test first and how to tag ads so you can learn from the results.

## Install

**Claude Code:** copy the folder into your skills directory.

```bash
cp -r edge-ad-designer ~/.claude/skills/
```

**Claude.ai / Claude desktop:** zip the `edge-ad-designer` folder and upload it under Settings → Capabilities → Skills.

## Use

> "Make 5 ad concepts opposing the proposed flavour ban in [state], for Meta and X, aimed at adult smokers' families."

> "This ad was rejected on Meta. Why, and how do we keep the punch and get it approved?"

> "We want a 'breaking news' style ad about the vape tax vote."

For the third one, it explains why a fake news banner is a red line and gives you the news-style version that does pass.

## Files

| File | Contents |
|---|---|
| `SKILL.md` | Persona, the push-the-edge rule, hard lines, workflow, output template |
| `references/platform-matrix.md` | Political/issue, tobacco/nicotine, alcohol, cannabis and gambling rules per platform, plus account risk |
| `references/format-traffic-lights.md` | 14 "banned" formats: why each is restricted and the version that passes |
| `references/category-playbooks.md` | Tobacco, political, alcohol, cannabis and gambling playbooks: what to show, what never to show, frames that work |
| `references/creative-playbook.md` | Hooks, format menu, persuasion research, design craft, specs and safe zones, testing |
| `references/native-networks.md` | Taboola, Teads/Outbrain, Yahoo, MGID: issue-ad gates, advertorial pre-lander rules, headline formulas, specs |
| `references/google-display.md` | GDN banners, responsive display, Demand Gen and Performance Max: specs, display-specific policies, election-ad rules, banner craft |
| `references/line-check.md` | Pre-flight checklist and the edge rating scale |

## Freshness and disclaimer

The policy research is dated **27 October 2026**. Platform rules change often, and items marked *[verify]* could not be confirmed against a primary source. This is creative guidance, not legal advice. Check current platform policies and get legal review before a live campaign.
