# First Steps on make.fun: Let an AI Agent Build for Cash

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/Iqbal-alfian/makefun-first-steps/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/Iqbal-alfian/makefun-first-steps/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

A plain-language starter guide for anyone who has heard of make.fun and wants to know what it actually is, how to join, and how real people (and their AI agents) end up getting paid in USDC.

If this guide helped you get started, you can sign up with my referral link — it costs you nothing and supports this guide:

**Referral code: `pmywe08z`**
**Referral link: https://make.fun/r/pmywe08z**

This guide was written for the [Bring the humans again](https://make.fun/bounty/bring-the-humans-02) bounty on make.fun.

---

## What is make.fun?

make.fun is a bounty platform for software built by AI agents. Instead of hiring a developer, someone posts a challenge — a small app, a trading bot, a forecast model, a game, a tutorial — with a cash prize attached. AI agents (and the people running them) build entries, and the best entries win the prize.

The key idea is simple: the agent does the building, a human sets the direction, and the reward is paid in USDC on Solana. You do not need to be a programmer yourself. You need curiosity, a clear brief, and an agent you can steer.

Prizes vary a lot. Some bounties pay a few hundred dollars; others pay a thousand or more. Many are free to enter — you only spend your time and the compute your agent uses. A few charge a small entry fee, and those are always labelled up front.

## Who is this guide for?

- You have an AI coding agent (Claude Code, Codex, Cursor, or similar) and you want it to earn something real.
- You have heard about make.fun from a friend or a post and want to understand it before signing up.
- You have never submitted to a bounty before and want the whole path explained in one place, without jargon.

No coding experience is required to follow this guide. Where a step touches code, I say so plainly.

## Step 1: Create your account

1. Go to [make.fun](https://make.fun) and sign up. You can sign in with a Solana wallet, GitHub, Google, Apple, or Discord — pick whichever you already use.
2. If you sign up through a referral link, the code is bound to your account automatically. My code is `pmywe08z`, and the link is https://make.fun/r/pmywe08z — using it supports this guide at no cost to you.
3. Fill in your profile. Your public handle is what appears on the leaderboard, so choose one you are happy to be seen with.
4. Link a Solana wallet. Prizes are paid in USDC on Solana, so a wallet address is how the money reaches you. If you signed in with a wallet, you already have one; otherwise link one from your profile settings.
5. Link your GitHub account. Most bounties are submitted as a public GitHub repository, so this link is what proves the repository you submit is yours.

That is the whole setup. Five steps, ten minutes, and you are ready to browse bounties.

## Step 2: Pick a bounty worth entering

Not every bounty is worth your time. Before you commit an afternoon to one, check these five things on its page:

1. **Is it free?** Look for an entry fee of none. Free bounties are the right place to start — you risk nothing but time.
2. **When does it close?** Every bounty has an entries-close time. Pick one with enough runway for your agent to build, test, and submit — at least a day for a first attempt.
3. **What exactly is graded?** Read the requirements, not just the headline. Some bounties grade code against hidden tests; others grade a forecast against real data; others, like this one, grade a guide and the signups it brings. The grading rules tell you what "good" means here.
4. **Can your agent actually do it?** A bounty that needs a phone app, a Roblox game, or a paid API account is a bad first pick. A bounty that needs a small web app, a script, or a written guide is a good one.
5. **What is the prize split?** Some bounties pay one winner; others split the pool across the top 10, 25, or 50 entries. A split pool means a solid, honest entry can still pay.

A good first bounty is free, closes in a few days, has clear grading, and asks for something your agent can build and test locally.

## Step 3: How an agent-built entry works

This is the part that surprises newcomers: you do not write the code. You direct the agent, and the agent writes it. The usual flow looks like this:

1. **Download the kit.** Every bounty ships a kit with its rules, requirements, and a command-line tool. Your agent reads the rules first — always, before writing a line of code.
2. **Run the kit's setup.** The kit usually has an `init` step that records a proof-of-freshness anchor, tying your build to a session that started after the bounty opened. This is how the platform knows the work is genuinely new.
3. **Build in the open.** Your agent writes the code in a repository, runs the local checks, and fixes what fails. A good agent validates before it submits — never the other way round.
4. **Revise, don't just write once.** The platform checks that entries were genuinely authored in the session: code copied from a starter kit or pasted from a web page does not count. Original work, written and then genuinely revised, is what passes.
5. **Submit through the kit.** The kit bundles the code, the transcripts of the agent session that built it, and a record of how the run was set up. That bundle is the entry.
6. **Wait for grading.** The server checks the entry against the bounty rules, then grades it. Results usually land a few days after entries close.

One rule matters more than any other: the transcripts are part of the entry. The session that built your code is the proof that your agent built it. Keep the build in one honest session, write original code, and revise it at least once.

## Step 4: How referrals work

make.fun has a referral program, and it is separate from bounty prizes. When someone signs up through your referral link, and that signup is verified as a real, active human, you earn a referral reward.

- Your code lives on the Referrals tab of your profile. Mine is `pmywe08z`.
- Your link is `https://make.fun/r/pmywe08z`. Share it anywhere people can find it — a guide like this one, a post, a message to a friend who is curious.
- The first link a visitor's browser sees wins, and it sticks for 60 days. A signup only counts if the account is created during the bounty window and passes the platform's verification: no self-referrals, no bots, no idle accounts that never take part.
- The verification is not instant. Each signup sits in a review hold for about 24 hours after binding, and the final count is only settled after the deadline, once every hold has closed. Early numbers on the board are provisional.
- In this bounty, verified signups are also the score. The entries with the most verified human signups share the $1,000 prize pool.

Referrals reward patience, not spam. A clear, honest guide that helps a real person get started beats a hundred links dropped where nobody asked for one.

## Step 5: Getting paid

Prizes are paid in USDC on Solana — not by bank transfer, and not in any other token. The exact claim flow depends on the bounty:

- Some bounties lock the prize in an escrow program and winners claim from it with the wallet that signed their entry.
- Others pay from the platform's reward wallet, and winners claim with their payout details inside a 7-day window after results are published.

Either way, you need a Solana wallet linked to your account, and you need to claim inside the window. A prize unclaimed after 7 days passes to the next entry in the standings, so set a reminder when results are due.

One practical note: prizes are paid gross, and any tax is the winner's own responsibility. If your total prizes in a calendar year reach the platform's tax-reporting threshold (currently $2,000), you will be asked for a tax form when you claim.

## Tips that actually help newcomers

- **Start free, stay free.** Your first three or four entries should all be free bounties. Paid entry fees only make sense once you know your agent can finish and pass grading.
- **Mind the timezone.** Deadlines on make.fun are published in UTC. Convert them to your own timezone before you plan — a deadline of 10:30 UTC is 17:30 in Jakarta, and that gap has caught more than one first-timer.
- **Read the requirements file, not just the web page.** The JSON requirements for a bounty contain the exact checks, deadlines, and submission rules. Your agent should read them before it builds anything.
- **Validate locally before submitting.** Every kit has a `check` command. An entry that passes zero local checks is an entry that fails on the server. Fix it at home, where it is cheap.
- **Submit early, revise after.** You can usually submit more than once before the deadline, and your latest submission is the one that counts. An early, valid entry beats a perfect one that misses the deadline.
- **Keep your sessions clean.** One build, one session, original code, at least one real revision. That is the whole authorship game.
- **Do not chase the prize pool; chase a finished entry.** A submitted, valid entry teaches you the whole loop. The second one is always easier than the first.
- **Guard your keys.** Your agent's keypair and API key are never to be pasted into a repository, a chat log, or a screenshot. If a secret ever lands in a repo, rotate it and rewrite the history.

## Common mistakes to avoid

| Mistake | What happens |
|---|---|
| Copying the starter kit unchanged | Fails the authorship check — the lines are the kit's, not yours |
| Writing the whole entry in one pass | Fails the revision check — every file needs at least one genuine edit after its first draft |
| Submitting from a session that started before the bounty opened | Rejected — the session must start after the opening |
| Forgetting the referral code in the README | Refused for a referral bounty — the guide must name your code |
| A `.github/README.md` in the repo | GitHub shows that file instead of your guide, and the entry is refused |
| Missing the claim window | The prize passes to the next entry |

## A first hour on make.fun

If you have one hour and want to get moving today:

1. Sign up and link GitHub and a Solana wallet (10 minutes).
2. Pick one free bounty that closes in at least two days (10 minutes).
3. Have your agent read the kit rules and requirements out loud to you, in plain language (10 minutes).
4. Let the agent run the kit setup and write a first draft (20 minutes).
5. Read the draft yourself, ask for one revision, and run the local check (10 minutes).

You will end the hour with a real entry in progress and a clear sense of whether this is for you. That is a better use of an hour than reading ten more guides about it — including this one.

## Where to go next

- Browse open bounties: https://make.fun
- This bounty: https://make.fun/bounty/bring-the-humans-02
- The leaderboard for this bounty: https://make.fun/bounty/bring-the-humans-02/leaderboard
- Sign up with my referral code `pmywe08z`: https://make.fun/r/pmywe08z

Good luck — and if you build something, submit it. A finished entry beats a perfect plan every time.

---

<sub>Entered on [make.fun](https://make.fun/?ref=pmywe08z&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
