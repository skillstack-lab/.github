# Skillstack Lab

**Small skills. A useful first result.**

We make small, open-source skills for specific jobs: turn a clear request and source information into a plan you can inspect and use. Start with something useful, keep the selection rules visible, and make the limits clear.

## Start here: catch up on the game over lunch

**[Lunch Reel](https://github.com/skillstack-lab/lunch-reel)** is our first release. Tell it the MLB game you missed and how much time you have. It uses public play-by-play and highlight listings to select key moments, then puts them in game order in a time-budgeted catch-up plan.

It is a Claude Code plugin, and also runs as a standalone CLI. You will need a terminal and Python 3.10 or newer. Plan-only downloads no video. Optional rendering needs ffmpeg, ffprobe and curl and stays on your machine. We ship the cutter, never clips.

**Heads up: some highlight titles can reveal the result. This is not a spoiler-safe experience.**

### Try a plan — no video download

Install the Claude Code plugin:

```bash
claude plugin install lunch-reel --marketplace skillstack-lab/lunch-reel
```

Then ask:

> I missed the Cubs on September 27, 2026. Give me a 5-minute catch-up, plan-only.

Prefer a terminal without an agent? The [Lunch Reel README](https://github.com/skillstack-lab/lunch-reel#install) has the clone and CLI steps. The code is free under MIT; using Claude Code may involve your own service or model costs.

[Read the code and setup](https://github.com/skillstack-lab/lunch-reel) · [AgentHub listing](https://agenthub.nullorder.org/plugins/lunch-reel/) · [First-run feedback](https://github.com/skillstack-lab/lunch-reel/discussions/4)

### What to expect

- A text/JSON plan with source links, not a hosted video player or full-game stream.
- Selection based on win-probability swings and the time budget, not a promise to include every memorable play. Available highlight coverage can be incomplete.
- A tool at an early stage: fresh-install checks have passed on three agent hosts, but we have no outside users yet. That is not a compatibility guarantee or customer validation.
- A September 2026 archive game for the example, not a live-game demo.

## Beyond one game

The wider idea is a reusable skill that turns source information into a personal plan. Possible next experiments include a source-linked release-note catch-up, a conference session shortlist, or an openly licensed listening queue. These are directions, not announced products or delivery promises. What people actually use should decide what comes next.

If you build skills, Lunch Reel is a working example to read, fork, and adapt. If you just missed a game, start with the plan.

## Tell us where it breaks

If you try Lunch Reel, share your host/OS, time to first plan, and the step that got confusing in [the first-run discussion](https://github.com/skillstack-lab/lunch-reel/discussions/4). No GitHub account? Email [ssdesk+clip@mail.grokbot.com](mailto:ssdesk+clip@mail.grokbot.com). An automated assistant reads this feedback inbox.

Please do not attach video, rendered reels, or sensitive logs.

## Code, sources, and rights

Lunch Reel's code is MIT-licensed. That does not grant rights to MLB data, video, or trademarks. Public access is not permission to redistribute. Follow the source's terms; do not upload, stream, or share rendered reels. Local rendering is not a guarantee of legal permission. See the [repository's rights notes](https://github.com/skillstack-lab/lunch-reel#rights-read-before-you-use-it).

Skillstack Lab and Lunch Reel are not affiliated with, endorsed by, or sponsored by MLB or MLB Advanced Media.
