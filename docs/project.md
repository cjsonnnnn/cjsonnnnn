# Project materials

## Repo & links
- Origin: `git@github.com:cjsonnnnn/cjsonnnnn.git` (public — this repo's
  README is what GitHub actually renders on the profile page)
- Decision history for this repo lives in a *different* repo:
  `cjsonnnnn/legacy`'s `docs/decisions.md` — this repo has no decisions
  log of its own

## What this is
The public GitHub profile README, deliberately narrower than `legacy`'s
`content/bio/long.md` — real GitHub data + tech skill badges only, no bio
prose, no employer/role/location. Does **not** auto-mirror `legacy`'s bio
content; the two diverged on purpose 2026-09-01 (see `legacy`'s
decisions log).

## Tools & services
- GitHub stats/language widgets via a third-party mirror
  (`github-readme-stats-eight-theta.vercel.app`) — the official host is
  down (`DEPLOYMENT_PAUSED`); this is a known fragility, see `legacy`'s
  Open items
- Contribution snake workflow (`gh workflow run`) — light theme, matches page palette
- Banner: hand-authored SVG (Dudu character, Gemini 3-drawn) with SMIL animation — never CSS transforms, see `legacy`'s decisions log for why

## Key files
- `README.md` — the entire rendered profile
- (No `docs/decisions.md` here — see `cjsonnnnn/legacy` for this repo's decision history)
