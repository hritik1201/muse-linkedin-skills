# muse-linkedin-skills

Eleven LinkedIn skills, adapted for Muse.

Original: [Jakeschincariol/linkedin-agent-skill](https://github.com/Jakeschincariol/linkedin-agent-skill) — eleven free Claude skills, MIT licensed.
This version repoints the Claude state paths (`~/.claude/linkedin/`) to Muse paths (`~/workspace/user/linkedin/`) and is used in plain words, not slash commands.

## The eleven

- `li-post` — one idea into a post, from 21 hook formulas, humanized first
- `li-comment` — comments on other people's posts, by post type
- `li-reply` — replies under your own post, triaged lead / substance / peer / support / noise
- `li-profile` — profile scored out of 100 against a 12-part rubric, then rewritten in fix-first order
- `li-plan` — weekly plan: what to post, when, and who to engage with
- `li-human` — humanizer: two local Python scripts, no network, no uploads
- `li-carousel` — document posts, slide-by-slide copy
- `li-repurpose` — one video, newsletter or transcript into a week of posts
- `li-dm` — invite note, first message, and two follow-ups
- `li-inbox` — inbox triage: lead / recruiter / peer / ask / spam
- `li-audit` — post-mortem on what you have already published

## Muse setup

Copy the `li-*` folders to your Muse custom skills folder, then create a LinkedIn state folder with:

- `voice.md` — fill this from three of your own past posts first; the skills refuse to invent a voice
- `log.md` — what was posted / commented, with date and hook used
- `plan.md` — written by `li-plan`

In Muse there are no slash commands — ask in plain words, e.g. "Score my LinkedIn profile" or "Write a LinkedIn post about X".

## Hard rules, kept from the original

- Nothing is published without your explicit yes. Skills end in a copy-ready draft.
- No invented metrics, clients, or outcomes. A missing number comes back as `{{your number}}`.
- The humanizer checks are local heuristics only, not detector APIs.

## Credit and license

Made originally by Jake Schincariol. Upstream license: MIT — take it, change it, ship it.
This adaptation is also shared under MIT.
