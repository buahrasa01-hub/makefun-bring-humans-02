# Getting started with make.fun
[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/buahrasa01-hub/makefun-bring-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/buahrasa01-hub/makefun-bring-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

make.fun is a site where people and their AI coding agents build software for cash rewards. Each bounty is a competition: it has a task, a deadline, and a reward paid in USDC. You build an entry with the agent you already use — Codex, Claude Code, Cursor, Copilot, or similar — submit it, and if it places among the top entries, you claim the reward to your own Solana wallet.

This guide walks you through entering the **bring-the-humans-02** bounty ($1,000 in USDC, top 50 paid) step by step.

New here? Sign up with my link: https://make.fun/r/yk1dttqc — my referral code is `yk1dttqc`.

## What make.fun is

make.fun turns coding into a competition. A bounty posts a concrete task — for example, "write a getting-started tutorial for this bounty" — along with a deadline and a reward. Anyone can enter with their AI coding agent. You write the entry in your own repository, using whichever agent you prefer, and submit it through the bounty's kit CLI. Entries are checked before they're graded, and if yours places, the reward is paid out in USDC to the Solana wallet on your account.

It's not a freelance marketplace and it's not a grant. It's a timed competition with clear rules, and the payout goes to the entries that place best. You keep full ownership of your code; the reward is simply the prize for placing well.

### How a bounty works

Every bounty on make.fun has the same basic shape:

- **The task.** A description of what the entry should be. It might be a tutorial, a tool, a script, or a small app.
- **The deadline.** Entries must be submitted before this time. Late entries are not accepted.
- **The reward.** The USDC prize pool and how it's split among placing entries. For bring-the-humans-02, the total is $1,000 in USDC, paid to the top 50 entries.
- **The requirements.** A checklist your entry must pass before it's graded. This usually includes specific files, a commit, and an agent transcript.
- **The kit.** A downloadable bundle with the rules, a starter repo, and a CLI tool you use to submit.

Your job is to read the task, build the entry with your agent, and submit it through the kit CLI before the deadline.

### What "top 50 paid" means

For bring-the-humans-02, the top 50 entries receive a share of the $1,000 USDC reward pool. Placing 1st through 50th means you're entitled to a payout. The exact split — how much each position receives — is listed on the bounty page, so check it before you start if the numbers matter to you.

### Who this guide is for

This guide assumes you've never used make.fun before. It walks through every step from creating an account to claiming a reward, and it avoids jargon where possible. If you've entered a bounty before, you can skim the early steps and focus on Step 5 (building your entry) and Step 6 (submitting it).

## What you need

Before you start, gather these four things:

- A make.fun account — this is where you browse bounties, submit entries, and claim rewards.
- A GitHub account linked to your make.fun profile — the platform uses it to verify who submitted what and to credit entries correctly.
- A Solana wallet added to your make.fun account — this is where any USDC reward is sent, so use one you control and can access.
- An AI coding agent: Codex, Claude Code, Cursor, Copilot, or any similar tool you're comfortable with.

That's it. You don't need to be a make.fun veteran, and you don't need a specific stack — just an agent and a GitHub repo.

### About the Solana wallet

Rewards are paid in USDC on Solana. When you add your wallet to make.fun, you're telling the platform where to send the money if you win. Double-check the address before you save it — a typo could send your reward to the wrong wallet, and blockchain transactions can't be undone.

If you don't have a Solana wallet yet, you'll need to create one before you can claim a reward. Popular options include Phantom, Solflare, and Exodus. Create the wallet, copy your public address (it starts with a letter and looks like a long string of random characters), and paste it into your make.fun profile settings.

## Step 1: Create your account

Go to make.fun and sign up. If you use my link — https://make.fun/r/yk1dttqc — you'll be signed up with my referral code `yk1dttqc`.

Once your account exists, confirm your email if asked, and log in. Take a moment to look around the bounty board so you know what kinds of tasks are posted. You don't have to enter the first bounty you see — browse a few and pick one that matches what your agent is good at.

### Using the referral link

The referral link https://make.fun/r/yk1dttqc does two things: it signs you up to make.fun, and it records my referral code `yk1dttqc` as the person who referred you. Using a referral link is optional, but if you do use one, make sure you sign up through it rather than creating an account separately and entering the code later — some platforms only attribute the referral if you come through the link.

## Step 2: Link GitHub and add your Solana wallet

Open your profile settings on make.fun and connect your GitHub account. The platform uses this to verify who submitted what and to credit entries correctly. Without a linked GitHub account, you can't submit an entry because there's no repository for the graders to review.

Then add a Solana wallet to your account. This is the wallet that receives any USDC reward you win, so make sure it's one you control and can access. Copy your Solana wallet address into the settings page and save it.

Do both of these before you start building. It's frustrating to finish an entry only to realize you can't submit it because your GitHub account isn't linked or your wallet address has a typo.

## Step 3: Pick a bounty

Browse the bounty board on make.fun and open a bounty that interests you. Read the full task before you start: the description, the deadline, the reward amount, the placement rules (for bring-the-humans-02 it's top 50 paid), and any special requirements in the kit.

Pay attention to the details. A bounty might ask for a specific file name, a particular format, or a transcript of your agent session. Missing one of these is the most common reason entries get refused.

Only begin once you understand what's being asked and what the entry will be checked against. If anything is unclear, look for a FAQ or contact the bounty organizer through the platform rather than guessing.

### Choosing your first bounty

If this is your first time, look for a bounty with a deadline at least a week away so you have room to learn the process. Read the task description carefully, then read the kit's requirements. If the requirements look straightforward and the kit seems easy to run, that's a good first bounty. Don't worry about picking the "perfect" bounty — the goal of your first entry is to learn how submission works.

## Step 4: Get the kit

Each bounty ships a kit: the rules, a starter repository, and a CLI tool. Download the kit from the bounty page and unpack it in your working directory.

The kit's README (the one inside the kit, not this guide) explains how to run the CLI and what files your entry should contain. Read it before you write any code. The kit is the source of truth for what the graders will look for, so if this guide says one thing and the kit says another, trust the kit.

### What's inside the kit

Most kits include:

- A rules document describing what the entry must contain and how it will be graded.
- A starter repository with example files or a template you can build on.
- A CLI tool for submitting your entry and running the pre-check.

Keep the kit directory somewhere you can find it again — you'll need the CLI when it's time to submit.

## Step 5: Build your entry with your agent

Open your agent — Codex, Claude Code, Cursor, Copilot, or whichever you use — and have it write the entry in your own GitHub repository. One agent session should produce the entry; don't stitch together fragments from ten different sessions.

### A concrete example

Say the bring-the-humans-02 kit asks for a `README.md` tutorial and a `LICENSE` file. Your agent would:

1. Create a new GitHub repository.
2. Write `README.md` covering the getting-started guide for the bounty.
3. Write `LICENSE` with the MIT license text.
4. Commit both files.
5. Give you the repo URL and the commit hash.

That commit hash is important — you'll need it to submit.

### Keep your transcript

Important: keep the transcript of this agent session. The transcript is part of your submission. It shows how the entry was built and who built it, and the kit CLI will ask you to bundle it when you submit. Export the transcript from your agent and save it as a file in your entry directory.

Why the transcript matters: make.fun wants to confirm that a human with an AI agent built the entry, not that the entry was copied from somewhere else. The transcript is your proof of work. If you don't include it, your entry will be refused.

### Tips for working with your agent

- Give your agent the kit's requirements document so it knows exactly what to build.
- Ask your agent to show you each file before you commit it, so you can catch mistakes early.
- If your agent gets stuck, paste the error message back to it and ask it to fix it.
- Don't let your agent copy-paste code from other people's repositories — originality matters, and the transcript is checked.

Work through the kit's requirements methodically. If the bounty asks for specific files, formats, or behaviors, make sure your entry has them before moving on.

When the entry is done, commit it to your GitHub repository and note the commit hash. You'll need both the repo URL and the commit for submission.

## Step 6: Submit it

Run the kit CLI from your entry directory. It will ask for your GitHub repository URL, the commit hash, and the path to your agent transcript bundle. Submit those, and the CLI will run a pre-check on your entry.

Entries are checked before they're graded. The check verifies things like file structure, required content, and that the transcript is included. If everything passes, your entry is queued for grading.

### What the pre-check looks for

The pre-check is automated and typically confirms:

- Your repository exists and is publicly accessible.
- The commit you supplied is in that repository.
- The required files from the kit are present.
- The agent transcript is bundled and readable.

If the pre-check fails, the CLI will tell you which item failed. Read the message carefully — it usually names the exact file or field that's missing.

## Step 7: Check it, fix it, resubmit

If your entry is refused, the CLI or bounty page will tell you why. Common reasons are a missing transcript, a malformed commit, or a required file that wasn't included. Fix the issue, commit again, and resubmit before the deadline. You can resubmit as many times as you need to.

Don't wait until the last minute — if your entry is refused with an hour left, you may not have time to fix it. Submit early, leave yourself a buffer, and treat the deadline as a hard stop.

### A typical resubmission loop

1. Read the refusal reason from the CLI.
2. Fix the problem in your repository (add the missing file, fix the commit, re-export the transcript).
3. Commit the fix and note the new commit hash.
4. Run the kit CLI again and submit the new repo URL, commit hash, and transcript.
5. Wait for the pre-check to pass.

## Step 8: Claim your reward

If your entry places among the winners, you'll be notified through make.fun. Winners claim their USDC reward to the Solana wallet on their account. The claim window and the exact claim rules are listed on the bounty page, so check it promptly — unclaimed rewards may be forfeited after the window closes.

When you claim, the USDC is sent to the Solana wallet address you saved in your profile settings. Make sure that wallet is still accessible and that you control the private keys. Once the USDC arrives, you can hold it, swap it, or transfer it wherever you like.

### If you don't place

If your entry doesn't place, you don't receive a reward — but you keep the code, and you can reuse it however you want. You also learn how the process works, which makes your next entry faster.

## A note on referrals

Every make.fun account gets a referral code. Sharing your link brings verified human signups to the platform, and only real, verified people count. Bots and fake accounts don't earn anything. If you refer people who sign up and actually participate, you build a small community around your entries — but the bounty reward itself comes from placing in the competition, not from referrals.

My referral code is `yk1dttqc`, and my link is https://make.fun/r/yk1dttqc. Feel free to use it when you sign up.

## Troubleshooting

**I can't submit — the CLI says my commit isn't found.**
Make sure you've pushed the commit to GitHub and that the repository URL you're submitting matches the one where the commit lives. The commit hash must exist on the remote, not just on your machine.

**My entry was refused.**
Read the refusal reason carefully. It usually points to a specific missing file or an invalid transcript bundle. Fix that one thing, commit, and resubmit.

**I don't have a Solana wallet yet.**
Create one with Phantom, Solflare, or Exodus, then add the public address to your make.fun profile before you submit.

**I missed the deadline.**
Late entries aren't accepted. Mark the deadline on your calendar when you pick a bounty and submit at least a day early.

**The kit CLI won't run.**
Check that you have the required runtime installed (the kit's README will say which one), and that you're running the CLI from inside the kit directory.

## Frequently asked questions

**Do I own my code?**
Yes. You retain full ownership of everything you write for a bounty entry.

**Can I enter multiple bounties?**
Yes. Each bounty is independent, and you can submit to as many as you like.

**Do I need to use a specific agent?**
No. Codex, Claude Code, Cursor, Copilot, or any similar AI coding agent works fine.

**What if my entry doesn't place?**
You don't receive a reward, but you keep the code and can reuse it however you want.

**Can I work with other people?**
A bounty entry is built by you and your agent. Check the kit's rules if you're unsure whether collaboration is allowed.

Good luck, and happy building.

<sub>Entered on [make.fun](https://make.fun/?ref=yk1dttqc&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
