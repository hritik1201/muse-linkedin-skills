# muse-linkedin-skills

LinkedIn skills for Muse, ready to use. No setup, no plugin, no slash commands.

## Use in 30 seconds

1. Copy the `li-*` folders you want into your Muse custom-skills folder.
2. Ask Muse in plain words, for example:
   - “Write a LinkedIn post about this idea”
   - “Score my LinkedIn profile”
   - “Draft a reply to this comment”
3. Done. Muse reads that skill and gives you a draft. You post it — nothing is published by Muse on its own.

## Start with these three

- `li-post` — one idea into a post, from 21 hook formulas, humanized first
- `li-profile` — profile scored out of 100, then rewritten in fix-first order
- `li-human` — humanizer: two local Python scripts, no network, no uploads

## All eleven

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

## First-time setup (only for voice)

Before your first post, create a state folder with:

- `voice.md` — fill this from three of your own past posts first; the skills refuse to invent a voice
- `log.md` — what was posted / commented, with date and hook used
- `plan.md` — written by `li-plan`

If you skip `voice.md`, posts will still work, but they will not sound like you yet.

## Hard rules

- Nothing is published without your explicit yes. Skills end in a copy-ready draft.
- No invented metrics, clients, or outcomes. A missing number comes back as `{{your number}}`.
- The humanizer checks are local heuristics only, not detector APIs.

## Credit and licence

Original pack by Jake Schincariol, MIT licensed — see `LICENSE` and the original repo linked there. This adaptation is also shared under MIT, and is not endorsed by the original author.
