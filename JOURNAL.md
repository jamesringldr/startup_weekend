> **What this is:** The full-context journal for the Startup Weekend KU repo — vision, current state, decisions, people, plan, and open questions, written so any agent (Claude Code, Cursor, Grok, or a future Igor) can pick this up cold and be useful within one read. · **Created:** 2026-11-13 · **Status:** Live — event day (Fri Nov 13, 2026)

# JOURNAL — Startup Weekend KU

## Who James is (the 60-second version)
James Oehring, KU alum, Kansas City. Solo founder of **Vanyshr** (consumer data privacy/cybersecurity — agentic AI that monitors data brokers, auto-removes personal data, and poisons broker datasets; family-first; free-forever DIY tier; planned Pro $9 / Premium $14 / Family $29). Eighteen months out of a high-paying software PM job, all-in on Vanyshr. Background is a potpourri: clinician supporting people with IDD, behavioral-health case manager, healthcare IT (Netsmart, Cerner/GEHA, Cornerstones of Care Director of IT 2019–2022), project/program management, security and privacy. Generalist operator: deep on workflows from the user's perspective, comfortable in the shit and commanding a room, builds moderately complex tech by orchestrating AI agents (Claude Code, Cursor, Grok). INTP. Currently working through an identity crisis he calls "the hole" (Red Book reading practice) — that material is **private**, never a pitch prop. His engine: Bukowski's "go all the way." His weekend persona: **"the operator who ships"** — plain, specific, fast; numbers when he has them, "I don't know yet" when he doesn't.

**Reference points for his founder shape (Igor's honest read, Nov 11):** Tobi Lütke's systems-builder brain + Moxie Marlinspike's privacy-mission spine + Jason Fried/DHH's refusal of the startup costume, powered by Bukowski. Closest single known founder: Lütke. Explicitly NOT Musk — James is inspired by Musk but says he'd be a poser emulating him; Musk's superpower (narrative gravity + capital formation) is the opposite of James's actual strengths. Also in the mix: Sahil Lavingia (honest solo-founder introspection), Pieter Levels (shipping cadence), Palmer Luckey (nonconformist nerve — borrow the nerve, not the theater).

## The event
**Techstars Startup Weekend, University of Kansas — first-ever KU edition. Nov 13–15, 2026, Capitol Federal Hall, Lawrence, KS.** FinTech is a named focus alongside AI and DeepTech. ~54 hours. Dress casual. Bring laptop, charger, business cards. Full detail (formats, rubric benchmarks, mentorship mechanics, agenda, rosters): **[event-guide.md](event-guide.md)** — this section is the condensed version.

**Agenda (from the live event pages, Nov 11):**
- **Friday:** 4:30pm arrival/registration · 5:00 dinner + networking (pre-pitch recruiting window) · 6:00 welcome · 6:30 ice-breaker · **7:00 pitches & idea selection** · 8:30 voting · 9:00 team formation · 9:30 wrap.
- **Saturday:** 8:00 breakfast · 9:00 announcements · **9:15 Workshop 1: Lean Canvas + customer discovery (Jackson + Rains)** · 10:15 working session · 12:00 lunch · 1:00 Workshop 2: Building an MVP (~30 min) · 1:30 working session · **2:30–5:00 guest mentor 1:1s (two assigned 30-min sessions per team)** · 5:00 dinner · 6:00 work · **7:00 mentor office hours** · 9:00 wrap.
- **Sunday:** 8:00 breakfast · 9:00 announcements · **9:10 Workshop 3: Pitching 101 (Lesa Mitchell)** · 10:00 work · **11:00 mentor office hours** · 12:00 lunch · 1:00 work + **tech check / pitch practice** · 3:30 final work · **4:30 pitch registration — slides freeze** · 5:00 dinner · 6:00 evening program · **6:30 final pitches** · 8:00 judges deliberate · 8:30 winners · 9:30 networking.

**Rules that matter:**
- Check in at the registration desk **all 3 days** — full attendance earns a **$250 token-build credit** and the right to **submit an idea after the weekend to KU staff, considered for the KU mentorship program and Techstars Global Founder Catalyst — explicitly NOT dependent on winning.**
- Friday: register the pitch at the desk; **60 seconds, event template, startup NAME required, no slides**, props OK, one idea only. Pre-started ideas allowed if seeking validation; an incorporated business with customers is NOT pitchable (one more reason Vanyshr was never a Friday candidate).
- If your idea isn't selected, you may still work on it **only with a self-formed team of 4+**, subject to a **15-team cap**.
- Sunday: **3 minutes, hard stop + 2 minutes Q&A.** Slides must be **Google Slides**; the live demo must exist **in the slide** (primary plan: recorded demo video embedded; live demo is a stretch goal). One Slides link shared Day 2. Don't build in Figma/Canva/PowerPoint and convert late. **Lean Canvas (.pptx provided) is the official framework.**
- **Judging rubric (five criteria, each scored 1–5):** (1) Customer Validation — real customer conversations/data vs. alternatives; (2) Team Dynamic — complementary skills, **shared delivery across the team (a score of 1 is literally "delivery by one person")**; (3) Business Model — sustainable, **multiple revenue streams rewarded**; (4) Execution & Design — what you built, how feedback shaped it, demo/MVP; (5) Impact — who benefits, how widely.
- **Hidden prize:** judges select up to **10 teams for KU's Founder Pipeline Cohort** (structured coaching from mid-Jan 2027, coached by David Morris) — an on-ramp to Techstars Founder Catalyst seats. Three independent outcome tracks: Sunday placement, Pipeline selection, post-weekend submission. Strategy: never zero a track.

## The idea — sports-betting options exchange
**Vision:** Options-style contracts on sports — calls, puts, spreads — with a **live bid/ask order book**, so positions trade like financial instruments instead of locked-in bets. A bettor can enter a position, watch the price move, and **exit** it. Crypto-settled variant: **USDC settlement, instant global payouts**. Framing: **"Betfair for America"** (Betfair blocks the US — regulatory moat, not oversight). Ten-year thesis: sports betting converges with capital markets into a tradeable asset class.

**The problem (the pitch's core):** the second you place a bet, you're locked in. The line moves against you, your quarterback gets hurt, and there's nothing you can do but watch it lose. That lock-in costs bettors billions — the one thing sports betting never fixed even as it went legal in most of the country. The house is your only counterparty, and it prices your exit.

**Weekend demo scope (deliberately narrow):** one league, one contract type, live bid/ask book, place a position, watch the price move, exit the position. One-page market-design sheet: who posts first bid/ask, who bears pricing risk, what the spread pays for, what data prices a live position.

**Business model (plural streams — the rubric rewards this):** transaction fees on matched trades, market data/API, premium tools.

**Regulatory stance:** staged path inside the terrain, not around it. Start as free-to-play / paper-trading to prove mechanics, then state-by-state licensing, compliance-first design. **Never** frame crypto/USDC as a regulation workaround. **Never** claim the exchange is unregulated space.

**Kill phrases (never say):** "Billionaire maker" (universal kill phrase on this panel — James's own term for the idea, retired for the weekend), unfooted TAM, "disrupting gambling," demoing a trade on a KU game, Jayhawk imagery in betting graphics, pitching alumni networks as GTM, claiming KU marks/affiliation as a betting go-to-market.

**Status (Fri Nov 13, ~1:15pm CST):** Friday 60-sec pitch drafted (~145 words, on the event template) — ready to rehearse except the **name, which is UNPICKED and gating** (shortlist: Strike, HedgeLine, OpenBook, FairBook, SecondHalf; no trademark/domain check yet). Team seats planned (see `pitch/team-build-strategy.md`). Demo not yet built — build starts Friday 9pm after team formation. Validation plan: Saturday interview sprint with real bettors ("wanted out, couldn't exit" stories + counts).

## Track A vs. Track B (the doctrine)
- **Track A = the weekend competition.** The exchange, the team, the Sunday pitch. Everything in this repo's `pitch/` folder serves Track A.
- **Track B = Vanyshr networking.** Fein (6–18mo relationship, no check ask), Grace (Techstars application process edge), Mitchell (GTM counsel, second touch), Courtney (ACCEL-KS / Oread Angels, milestone-timed), Bergman (I-Corps routing), Peterson (KU Hustle podcast, December), Shackelford (via his wife, ECJC conversation 2–4 weeks post-weekend). **Vanyshr is never pitched during judging, never bundled with the exchange in one message, never mentioned in the Friday pitch.** Full per-person follow-up plans live in `people/`.

## The people (summaries — full dossiers in `people/`)
**Judges (5):** John Fein (Managing Partner, Firebrand Ventures / Hill Fund — the #1 long-term Vanyshr target; ex-Techstars KC MD; #GiveFirst disciple; only working VC on the panel), James G. Clarke (SVP & CIO, KU Endowment, $3.23B — Swensen disciple; judges by what-ifs and tradeoffs), Adam Courtney (CEO & Board President, KU Innovation Park — staged de-risking + Kansas jobs; runs Oread Angels + ACCEL-KS), Tricia Bergman (Assoc. VC for Economic Development, KU — validation is her native lens; I-Corps + Partner with KU), Heath Peterson (President, KU Alumni — story judge; one-sentence retell test).
**Mentors (live gallery, 7):** David Morris (EIR, KU Business; Founder Pipeline coach; sold ZuPreem to Manna Pro/Carlyle — Saturday time with him is a January audition), Scott Wagner (co-founder HYLA Mobile, ex-Assurant — the market-design mentor; request first), Jeremy Tasset (CEO Nueterra Capital; Venture Partner, Hill Fund — Fein's partner; anything sloppy to him is said to the Hill Fund), Michael Torno (co-founder/CRO PathologyWatch, acquired by Sonic; Digital Health KC), Megan Schaff Bowles (Associate, Cooley LLP), Doug Burris (Founder, DBI2 Consulting), Lesa Mitchell (also Sunday Pitching 101 teacher; ex-Kauffman VP, ex-Techstars KC MD — highest-leverage non-judge in the building).
**Staff/speakers:** Glory Eromosele (Facilitator, Techstars — bring the Sunday pitch draft Saturday afternoon), Telesha Bowen (Program Lead, Techstars — ask her two process questions early: how 1:1 pairings are assigned; whether the post-weekend submission can carry any idea), Tim Grace (Managing Director, Techstars **Columbus** — NOT Chicago; process edge for the Nov 18 Techstars application; follow-up email Nov 16–17 with one alum-intro ask), Brian Anderson (Exec Director, Entrepreneurship Initiatives, KU — EO scholar; bring numbers with honest denominators), Ryan Rains (Director of Entrepreneurship, KU; I-Corps instructor — use EARLY Saturday; "the marketplace determines viability"), Chad Jackson (Teaching Professor, KU Business; co-leads Workshop 1 with Rains).
**Absent:** Jeff Shackelford (ECJC CEO — NOT attending; James knows his wife; gracious reply now, ECJC conversation 2–4 weeks post-weekend, milestone-tied, Vanyshr-only). Jaime Gassmann (listed on the original carousel, NOT on the live mentors gallery — presence unverified; verify in the room Friday).

**Saturday usage order (reconciled):** Rains early → Jackson in/after Workshop 1 → Anderson midday → Wagner first in the 2:30 block if drawn → Morris late (evidence audit) → Tasset/Torno in 1:1 block or office hours → Eromosele late afternoon (pitch structure) + Bowen (two process questions) → Sunday 9:10 Mitchell → 11:00 office hour.

## The weekend plan (condensed)
- **Friday:** arrive 4:30, register pitch immediately, work the 5–6pm dinner hour with name + one-liner locked. Pitch 7pm on the template. Recruit for five seats (builder, validation lead, numbers, designer + James). Teams 9pm → harness P0 opens: intake, roles, first-90-min launch sequence.
- **Saturday:** Workshop 1 as a team, mirror Jackson/Rains vocabulary, launch bettor interviews in the 10:15 session. Google Slides shell opens Saturday morning, Lean Canvas as spine, recorded demo video embedded. Two assigned 1:1s (ask for Wagner + Morris if any influence exists). Office hours 7pm.
- **Sunday:** Pitching 101 (Mitchell) 9:10 whole team; rebuild the 3 minutes on her What/Why/Who/How skeleton. Office hour 11:00 final polish. Tech check 1pm. Freeze 4:30pm. Pitches 6:30pm — team relay mapped to rubric order: validation numbers first → demo → business model (plural streams) → impact as fairness/exit rights/transparency → James closes.
- **After:** follow-ups Nov 16–17 (Fein LinkedIn, Grace email, Bergman email, Peterson thank-you); Techstars application submitted Tue/Wed Nov 17–18 (deadline Wed Nov 18); Mozilla Human-Scale AI Incubator deadline Fri Nov 20.

## Open questions (do not guess — resolve with James or the named source)
1. **Name for the exchange** — gating, must be picked before Friday 7pm. Shortlist in `pitch/name-shortlist.md`.
2. **Post-weekend submission scope** — must the submitted idea be the weekend idea, or can it be any idea (i.e., can it carry Vanyshr)? Ask Bowen or Eromosele early in the weekend.
3. **Vanyshr legal name / founded year / incorporation date** — unverified; gates the Techstars application AND Mozilla's 12-months-operating rule.
4. **Current traction figures** — Oct 7 numbers (52 waitlist / 23 pilot users) are stale.
5. **Cofounder framing for Techstars** — technical cofounder candidate (soft commitment, Recurly background, $75k + equity on close once funded): name him or go solo?
6. **Techstars program order** — Chicago #1, Anywhere #2, NYC #3 (Igor's fit ranking; needs James's confirmation).
7. **Bowles / Burris / Gassmann** — role-based cards only; full dossiers were never delivered. Gassmann's presence unverified.
8. **Torno acquisition price** — Sonic ASX release says US$130M; other sources say $150M. Never quote either to him beyond "the Sonic acquisition."

## How agents should work in this repo
- **Read this journal first, then the folder for your task.** Don't re-derive the strategy from scratch.
- **Keep claims literal.** If you add a number, cite where it came from in the repo or mark it unverified.
- **Never invent a dossier detail.** Bowles/Burris/Gassmann are role-only for a reason. A missing fact is a missing fact.
- **Update this journal when the state changes** (name picked, team formed, demo built, results in). The journal is the living record; the dated files are snapshots.
- **Nothing in James's name without his word.** No posts, applications, outreach, or pushes to production. Git work goes through Claude Code + /gitdaddy per the repo's standing rules; production pushes need explicit brief-level authorization.
