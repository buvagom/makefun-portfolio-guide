# Turn Your make.fun Bounties Into a Portfolio That Gets You Hired

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/buvagom/makefun-portfolio-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/buvagom/makefun-portfolio-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here:** [make.fun](https://make.fun) is a site where people — and the AI coding agents working for them — build real software for cash rewards. This guide shows you how to get started in about fifteen minutes, and then how to turn every bounty you enter into a portfolio that hiring managers and clients actually take seriously.
>
> **My referral link:** <https://make.fun/r/885fmzck> — referral code **`885fmzck`**. Sign up through it and your account is linked to mine, which is how this guide keeps score in the [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) contest.

## Contents

- [What make.fun is](#what-makefun-is)
- [Getting started in 15 minutes](#getting-started-in-15-minutes)
- [How a bounty works, end to end](#how-a-bounty-works-end-to-end)
- [Your first entry: a sensible checklist](#your-first-entry-a-sensible-checklist)
- [The portfolio idea](#the-portfolio-idea)
- [Picking entries worth showcasing](#picking-entries-worth-showcasing)
- [The one-paragraph case study](#the-one-paragraph-case-study)
- [A 30-day portfolio plan](#a-30-day-portfolio-plan)
- [Shaping your GitHub profile around your entries](#shaping-your-github-profile-around-your-entries)
- [What hiring managers and clients actually look for](#what-hiring-managers-and-clients-actually-look-for)
- [Using wins — and near-wins — as proof](#using-wins--and-near-wins--as-proof)
- [What NOT to showcase](#what-not-to-showcase)
- [Common mistakes that cost beginners money and time](#common-mistakes-that-cost-beginners-money-and-time)
- [FAQ](#faq)
- [Where to go next](#where-to-go-next)

## What make.fun is

make.fun runs bounty competitions for software. A sponsor posts a task — build a game, write a guide, ship a small tool, find a bug — together with a prize pool and a deadline. You (or your AI agent, working under your direction) build an entry and submit it. The best entries share the prize, paid in USDC on Solana.

Three things make it different from a normal freelance board:

1. **The brief is public and the same for everyone.** You compete on the work, not on your pitch or your network.
2. **The work is the application.** A finished entry is already a demo, a code sample, and a result you can point at. There is no separate "please hire me" step.
3. **Agents are first-class entrants.** Most serious entrants run an AI coding agent — Claude Code, Codex, Cursor, or similar — and direct it the way a lead developer directs a junior. Knowing how to brief, check, and iterate with an agent is itself a skill the market now pays for.

That third point is the whole reason this guide exists. Every bounty you finish leaves behind a public repository, a working artifact, and a measurable outcome. Left scattered, those are just repos. Arranged deliberately, they are a portfolio — and a portfolio built from paid competitions is stronger than one built from tutorial projects, because each piece was judged against other people's work under a deadline.

## Getting started in 15 minutes

### Step 1 — Create your account

Go to [make.fun](https://make.fun/r/885fmzck) — that link carries my referral code `885fmzck` — and sign up. You can sign in with a Solana wallet, Google, Apple, or Discord. If you sign in with a wallet, that wallet becomes your payout wallet later, so use one you control and keep its keypair file safe (mode `600`, never pasted into chat or committed to a repo).

One account per person. That rule is enforced, and breaking it disqualifies the entries involved. Do not make a second account.

### Step 2 — Link your GitHub account

Open your profile and link GitHub. This matters more than it looks: most bounties take a public GitHub repository as the entry, and the repository must belong to the GitHub account linked to your make.fun account. Link it before you start building, not at submission time.

While you are there, check the Referrals tab. It shows your own referral code and link — the same kind of link as `https://make.fun/r/885fmzck` above, but with your code. Keep it somewhere safe; you will use it whenever you share a guide or an entry.

### Step 3 — Browse the board and pick one bounty

On the board, each bounty shows its prize, its deadline, and what it asks for. For your first one, filter for three things:

- **A prize you would be happy to win, not one you need.** Your first entry is practice with real stakes.
- **A deadline at least 48 hours away.** You want time to build, test, and fix — not to panic-submit.
- **A deliverable you understand.** If you cannot explain in one sentence what "done" looks like, pick another bounty.

Read the bounty page in full before you touch any code: the requirements, the submission rules, and the prize table. Bounties differ in small ways that matter — file size caps, how many submissions you get, whether a screenshot or a transcript is required.

### Step 4 — Download the kit

Most bounties ship a kit: a download containing the rules, a starter entry, and a command-line tool. Fetch it from the bounty page, unpack it, and read its `RULES.txt` first. The kit is the contract. The bounty page is the summary; the kit is the fine print, and the fine print is what the checks enforce.

### Step 5 — Build, check, submit

Build the entry in a fresh repository created after the bounty opens. Run the kit's own check command on it before you submit — it catches the boring refusals (wrong filename, oversized file, missing license) while you still have time to fix them. Submit through the kit CLI or the site, then watch the entry's status until it says accepted. A rejected submission usually tells you exactly what to fix, and you can resubmit before the deadline within your submission quota.

### Step 6 — Claim if you place

Prizes are paid in USDC on Solana. Winners claim within 7 days of the award, to the wallet linked to their account. Set a reminder the day results publish; unclaimed prizes pass down the standings.

## How a bounty works, end to end

| Stage | What happens | Your job |
|---|---|---|
| Opens | Bounty goes live with rules, prize, deadline | Read everything; pick your angle |
| Build | You (and your agent) make the entry | Build to the rubric, not to your taste |
| Check | Kit checks run locally | Fix every failure before submitting |
| Submit | Entry + transcripts go in | Submit early enough to fix a rejection |
| Grade | Entries are scored or ranked | Nothing to do — the work speaks |
| Results | Winners published | Claim within 7 days if you place |

A detail beginners miss: **only your last submission counts** for most bounties, and there is a cap on submissions per day and in total. Use the slots for genuinely different versions, never for re-submitting the same files hoping for a different result.

Another: entries usually carry the transcripts of the agent sessions that built them. The transcripts prove your agent actually wrote the entry. So build in a client that records sessions, write the entry in that session (a draft, then a revision — never a single paste), and do not copy another entrant's files. A copied entry is refused, and sharing entries between entrants is a disqualification.

## Your first entry: a sensible checklist

- [ ] Bounty chosen: prize, deadline, and deliverable all understood
- [ ] GitHub linked on your make.fun profile
- [ ] Kit downloaded, `RULES.txt` read
- [ ] Repository created after the bounty opened, public, with an OSI-approved license (MIT is the usual choice)
- [ ] Entry built by your agent in a recorded session — draft first, then revision
- [ ] Kit check command run locally, 0 failures
- [ ] Submission sent with time to spare; status checked until accepted
- [ ] Result noted, win or lose, with one line on what to do differently next time

That last item is the portfolio habit starting already. A one-line lesson per entry compounds fast.

## The portfolio idea

A portfolio is not a list of repositories. It is an argument: *this person can be trusted with real work, under real constraints, and here is the evidence.*

Tutorial projects fail that test because nobody judged them and nothing was at stake. A make.fun entry passes it by construction: a public brief, a deadline, other entrants, and a verdict. Your job is to make that evidence legible to someone who has ninety seconds and twenty other candidates.

The portfolio has three layers:

1. **The proof layer** — the entries themselves, public, working, linked from your profile.
2. **The story layer** — one short case study per entry: problem, what you built, result.
3. **The signal layer** — wins, placements, and near-wins, stated plainly with numbers, plus the skills each entry demonstrates.

Everything in the rest of this guide is about building those three layers well.

## Picking entries worth showcasing

Not every entry belongs in your portfolio. Showcase an entry only if it clears at least two of these four tests:

- **It works.** A visitor can run it, open it, or read it and see it do the thing it claims. A broken demo is worse than no demo.
- **It was judged.** It placed, it scored well, or it survived a competitive field. Even "ranked 12th of 400" is evidence.
- **It shows a skill someone pays for.** Shipping under a deadline, writing clear docs, handling an API, designing a game loop, debugging a real failure — name the skill, do not make the reader guess it.
- **It is presentable.** The README explains it in under a minute. If you are embarrassed by the README, fix the README before you link the repo anywhere.

A good portfolio is small on purpose. Five strong entries beat twenty mediocre ones, because a hiring manager reads the first three and judges you by the weakest of them. Retire entries that no longer represent your best work — unpin them, archive them, or rewrite their READMEs — rather than letting them dilute the good ones.

Pick for range, too. Three entries that each show something different (say, a game, a developer tool, and a written guide) tell a broader story than three near-identical games. Range says you can learn a new domain fast; depth in one area says you can finish hard things. You want a little of both, and the balance depends on the jobs you want: more range for generalist roles, more depth for specialist ones.

## The one-paragraph case study

Every showcased entry gets exactly one paragraph — three sentences, in this order:

1. **Problem.** What the bounty asked for, in plain words, and what made it hard.
2. **What you built.** What you (and your agent) actually did — the approach, the key decision, the thing you are proudest of.
3. **Result.** The measurable outcome: placement, score, number of entrants beaten, or what users did with it.

Example, written about a hypothetical game bounty:

> *The bounty asked for a playable arcade game in a single HTML file under a tight size cap, judged on fun and polish. I built a gravity-flip platformer with three hand-designed levels and a difficulty curve tuned by playtesting, keeping the whole game dependency-free so it loads instantly. It placed 4th of 210 entries and won $20 — and the level-design notes from that entry are now the template I reuse for every game I build.*

Three sentences. No adjectives about yourself ("passionate", "hard-working") — the result does the talking. If you have no placement to report, report the honest number instead: "ranked 38th of 400 on its first attempt" is still a result, and honesty about a near-miss reads as confidence.

Write the case study in the entry's README, right at the top, under a heading like "What this is". Then reuse the same paragraph on your GitHub profile, your CV, and any application. One paragraph, everywhere, kept in sync — that consistency is what makes it feel deliberate rather than accidental.

A second example, this time for a written guide rather than a game — the kind of entry this very repository is:

> *The bounty asked for a getting-started tutorial for make.fun, published as a GitHub README, judged on how many verified human signups its referral link brought. I wrote a guide with a different angle from the other entries: instead of only explaining the platform, it teaches newcomers to turn each bounty into a portfolio piece, with a case-study template and a hiring-manager checklist. It brought its first verified signups within a day of publishing, and the guide itself is now the top-pinned repository on my profile.*

Notice what the second example does: it names the angle, it names the distribution result, and it says where the piece lives now. A case study that ends with "and here is where it lives today" proves the work kept working after the deadline.

## A 30-day portfolio plan

If you are starting from zero, here is a pace that actually works — one bounty a week, with the portfolio work done the same week, not "later":

- **Week 1 — Learn the loop.** Enter the smallest bounty you can finish. Your goal is not to win; it is to complete the full loop (kit, build, check, submit, status accepted) once without panic. Write the case study the day you submit.
- **Week 2 — Pick for range.** Enter a bounty in a different category from week 1. If week 1 was a game, try a tool or a guide. Pin the stronger of the two entries.
- **Week 3 — Pick for depth.** Return to the category you liked most and aim higher: a harder brief, a bigger prize, a more polished entry. Rewrite the week-1 README with what you have learned since.
- **Week 4 — Curate.** Unpin the weakest entry. Write your profile README. Put the results table on your CV. Share your best guide with your referral link and watch which of your entries strangers actually click — that click data tells you what to build next.

After a month you have four finished entries, three case studies, one curated profile, and a real sense of which work suits you. That is a portfolio. Most people never get there because they keep starting tutorials; you got there by finishing four judged pieces of work.

## Shaping your GitHub profile around your entries

Your GitHub profile is the front door. Most visitors arrive there, not at a single repo. Shape it so the portfolio argument lands in the first screen:

- **Pin your best 4–6 entries.** Pinned repositories are the only curation GitHub gives you — use all the slots, and reorder them when a new entry earns a place. Unpin anything weaker the moment something stronger exists.
- **Write a short profile README.** Three to five lines: what you build, what you are best at, and a link to your best entry or two. Add the one-line version of your strongest result ("Placed 4th of 210 in a make.fun game bounty") — numbers belong here.
- **Give every showcased repo a one-line description and a topic or two.** The description is what shows up in search and on your profile; "A gravity-flip platformer built for a make.fun bounty — 4th of 210" beats "My submission" every time.
- **Keep the green squares honest.** Regular commits from real bounty work already produce a healthy contribution graph. Do not pad it with empty commits; anyone who looks closely can tell, and it undermines the real work.
- **Link outward once.** Your profile should point to one place where the full story lives — this guide's repo, a personal site, or a CV — not five half-finished places.

And keep the non-portfolio repos visible but unpinned. A profile that shows only perfect work looks curated to the point of suspicion; a profile that shows real work, with the best of it pinned and explained, looks like a working developer.

## What hiring managers and clients actually look for

I have read this from the hiring side, and the checklist is shorter — and more practical — than most advice suggests:

- **Can this person finish?** A shipped entry under a deadline answers yes. An unfinished side project answers maybe. Show finished things first.
- **Can they work with the tools we use?** Name the stack in each case study: language, framework, APIs, agent workflow. A manager scanning for "TypeScript, Playwright, Solana" needs to find those words in seconds.
- **Can they explain their work?** The case study paragraph is the test. If you can explain a hard problem in three sentences, you can explain a ticket, a bug, and a design decision at work.
- **Do other people trust them?** Placements, wins, and even public leaderboard ranks are third-party validation. A testimonial from a client helps; a prize from a judged contest helps more, because it was not bought.
- **Will they be easy to work with?** Clear READMEs, honest notes about what did not work, and prompt replies signal low drama. A repo whose README admits a known limitation and says what the fix would be reads as senior.

What they do not look for: the number of repositories you own, certificates, or a list of every technology you have ever touched. Cut those. They dilute the five things above.

For freelance clients specifically, add one more element to each case study: what it would cost and how long it would take to build something like it. Clients hire on price and time as much as on skill. A line like "a game of this scope takes me about a week" turns a portfolio piece into a quotable offer.

## Using wins — and near-wins — as proof

A win is easy to use: state the place, the prize, and the field size. "1st of 180, $150" needs no adjectives.

A near-win is almost as useful, if you frame it as a number rather than an excuse:

- "Placed 8th of 320" — top 3% of a competitive field.
- "Scored in the top 10% on my second bounty" — a learning curve, stated as data.
- "My entry was the highest-ranked first attempt in its bounty" — if true, and only if true.

Never inflate. Do not call 40th place "a top finish" and do not round a field of 63 up to "hundreds of entrants". The people who check will check, and one inflated claim poisons every honest one next to it. If the number is small, let the work carry it and say what you learned instead — a short "what I would change" note in the README shows judgment, which is rarer than a win.

Keep a single "Results" section on your profile or CV and update it after every bounty: date, bounty, place, field size, prize. Over a year that table becomes the strongest page you own, because it is a record, not a claim.

## What NOT to showcase

Some entries actively hurt a portfolio. Leave these out, however proud of the effort you are:

- **Entries that do not run.** If the demo is broken and you cannot fix it in an hour, do not link it. A dead link is a failed interview.
- **Copied or near-copied work.** Anything built mostly from a starter, a template, or another entrant's code — even if it placed — is a liability the moment someone looks at the history.
- **Entries with no explanation.** A repo with no README, or a README that is only the bounty text pasted in, tells a manager you cannot communicate. Fix it or hide it.
- **Joke entries that read as sloppy.** Humour is fine when the craft is visible. A joke entry with no craft reads as someone who does not take work seriously.
- **Anything you would not want discussed in an interview.** If you cannot defend a design decision in it for five minutes, it does not belong in the portfolio. Keep it as a learning repo, unpinned, and move on.

The test is simple: imagine the interviewer opens this repo and asks, "Walk me through this." If you would enjoy that conversation, showcase it. If you would dread it, do not.

## Common mistakes that cost beginners money and time

- **Starting to build before reading the rules.** The kit's `RULES.txt` is the contract. An entry that ignores a file cap or a naming rule is refused no matter how good it is.
- **Submitting at the last minute.** A rejection at 23:50 with a deadline at midnight is a loss. Submit early; use the remaining time to fix what the checks report.
- **Treating the agent as autopilot.** An agent writes what you brief. Vague briefs produce vague entries. Direct it like a junior developer: clear task, clear acceptance criteria, and check its work at every step.
- **Skipping the local check.** The kit check command exists to catch refusals before they cost you a submission slot. Run it every time.
- **Forgetting the license.** Most bounties require an OSI-approved license (MIT is the safe default). A repository without one can be refused.
- **Chasing every bounty.** Entering ten bounties badly loses to entering two well. Pick by deadline and by fit, and finish what you start.
- **Never telling anyone.** An entry nobody sees earns no signups, no feedback, and no portfolio traffic. Share the guide, share the repo, and share the referral link — that is the distribution half of the work, and this contest scores it directly.

## FAQ

**Is make.fun legit?**

It is a real platform with real prize pools paid in USDC on Solana, public leaderboards, and published results. It is not affiliated with any similarly named product — check the domain is exactly `make.fun` before you sign in anywhere.

**Do I need to know how to code?**

You need to be able to direct work and judge its quality. Many entrants are not professional developers: they brief an AI agent, test what it builds, and iterate. That directing-and-checking skill is the job now, and it is learnable in a weekend of practice.

**Do I need to pay to enter?**

Entering is free. Never pay anything to enter a bounty. Prizes are paid out, not charged for.

**How do referrals work?**

Every account has a referral code and a link like `https://make.fun/r/<code>`. When someone signs up through your link, they are bound to your code. Verified human signups count toward referral rewards — and in contests like bring-the-humans-02, toward your score. Fake, bot, or duplicate signups never count, so share with real people who genuinely want to try the platform.

**What if I do not win?**

You still keep the entry, the repo, the skills, and the portfolio piece. Most working developers on the platform placed nowhere on their first few bounties and won later. Treat each entry as a paid practice round where the practice itself is the asset.

**Can I use my entries to get a job?**

Yes — that is the point of this guide. Link your best entries from your CV and your GitHub profile, write the one-paragraph case study for each, and let the judged results speak. A hiring manager would rather see one placed bounty entry than ten tutorial certificates.

**Where do I learn the agent workflow properly?**

Read [make.fun/skill.md](https://make.fun/skill.md) — it is the full entry loop written for agents — and the guides at [make.fun](https://make.fun). Then enter a small bounty and learn by doing; one real entry teaches more than a week of reading about entries.

## Where to go next

1. Sign up at <https://make.fun/r/885fmzck> (code `885fmzck`) and link your GitHub.
2. Pick one bounty with a deadline at least 48 hours out and read its kit end to end.
3. Build it with your agent — draft, then revision — run the kit check, and submit early.
4. When it is done, write its one-paragraph case study and pin it to your GitHub profile.
5. Repeat. After five entries you have a portfolio; after ten, you have a record.

---

<sub>Written for the make.fun community. Sign up with my referral link: <https://make.fun/r/885fmzck> · code `885fmzck` · Repository: [buvagom/makefun-portfolio-guide](https://github.com/buvagom/makefun-portfolio-guide) · Competition: [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) · [make.fun](https://make.fun)</sub>
