# Stop Flowing

A self put together from the feed has no keel. Its positions sit wherever the
current last left them, and from the inside a position you drifted into feels
exactly like one you hold. You can only tell them apart by moving the crowd and
watching which ones go with it. Believing in something is a behaviour, not a
feeling. It means a position stays put when the room turns, and you would say it
out loud in every room you're in.

The instrument runs both tests on you and shows its working.

## What it does

A five-station session. Twelve positions, two in each of six topics (taste, the
feed, the news cycle, work, people, self), each rated on a seven-point scale.

- **I · Alone.** The twelve, with nobody else in the room. Sealed on continue.
- **II · The current.** The same twelve inside a feed, reshuffled among invented
  posts, ads and trends. One position from each topic gets a poll and a top
  comment. The poll is generated on the spot on the opposite side of your first
  answer, with roughly four votes in five against you. The other six show
  _no votes yet_, and they are the control.
- **III · The keel.** Discloses what was arranged. Noise is the mean absolute
  change on the control items. Pull is the mean signed change toward the crowd
  on the crowd items. Each crowd item is marked _held_, _carried_ or _pushed
  back_. The argument: pushed back is not held, because a contrarian is still
  being placed by the crowd (reactance). One chart row per position shows the
  first answer, the second answer, and the crowd's distribution and mean.
- **IV · The rooms.** Up to three positions you'd defend. For each, what you'd
  do with it in the group chat, at the family table, in a public post and with
  someone you just met: say it, soften it, keep quiet. This is fragmentation
  made visible (context collapse, and the online/offline split).
- **V · Articles.** For each: _I believe_ in your own words, _I got here
  through_ (lived / someone I trust / read or studied / the feed / can't say),
  and _I'd change my mind if_. The page sets them down as a card you can copy.
  The distinction it draws: evidence moves a belief, and a crowd moves a flow.

The masthead shows a synthetic run with topic labels only, so a stranger can see
the output before starting.

## What never leaves the machine

Everything. There is no backend, no account, no analytics and no storage. Answers and
articles live in page memory and are gone on reload. The only way to keep the
articles is the copy button. There are no third-party requests, and the two
typefaces are served from `fonts/` (OFL).

## Run

```bash
open index.html
```

or `python3 -m http.server 5454` (registered as `stop-flowing` in
`~/.claude/launch.json`).

## Honest limits

- One sitting, twelve positions. Noise rests on six items, so pull can come out
  zero or negative by chance. The page says so.
- The title warns you and the crowd is a page's crowd. A warned subject is a
  stiffer subject, so this under-reads drift.
- People may remember their first answers and match them. The page counts that
  as a keel. Choosing consistency is one way a keel gets built.
- It measures positions on twelve statements. It says nothing about who you
  are.

## Sources

Checked 30 September 2026. All seven DOIs resolve on Crossref as cited, and the
Salganik and Muchnik figures were read from the PubMed abstracts.

- Asch 1956, _Psychological Monographs_ 70(9) — doi:10.1037/h0093718
- Deutsch & Gerard 1955, _J. Abnormal and Social Psychology_ 51(3) — doi:10.1037/h0046408
- Salganik, Dodds & Watts 2006, _Science_ 311 — doi:10.1126/science.1121066 (14,341 participants)
- Muchnik, Aral & Taylor 2013, _Science_ 341 — doi:10.1126/science.1240466 (+32% positive-rating likelihood, +25% final ratings)
- Brehm 1966, _A Theory of Psychological Reactance_, Academic Press
- Marwick & boyd 2011, _New Media & Society_ 13(1) — doi:10.1177/1461444810365313
- Marcia 1966, _JPSP_ 3(5) — doi:10.1037/h0023281
- Campbell et al. 1996, _JPSP_ 70(1) — doi:10.1037/0022-3514.70.1.141
- Gergen 1991, _The Saturated Self_, Basic Books
- Bauman 2000, _Liquid Modernity_, Polity

The Asch figures on the page ("about a third" of critical-trial answers
conformed, "about a quarter" of people never did) are the monograph's
commonly reported summary and have not been re-derived from the tables. The
"Believe in something" line is Nike's September 2018 campaign.

## Origin

Param's note _Big (Writing)_, 22 September 2026, in niwa-vault (spelling tidied):

> Stop flowing like water, ebbing and flowing to advert campaigns, corp
> interests, pretending to care about the news cycle because buying in is
> everyone around you.

and: _Seeking alignment between your online and offline self is the most pure
act of protest._

## Status

Prototype, 30 September 2026. Private.
