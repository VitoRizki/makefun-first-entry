# Your first make.fun entry

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/VitoRizki/makefun-first-entry/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/VitoRizki/makefun-first-entry/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

Use your AI coding agent to build a bounty entry, then check the work before you submit it.

make.fun runs competitions called bounties. Each bounty tells you what to build, how it will be judged, when entries close, and which places earn rewards. Winners claim USDC, a digital token, on Solana.

[Join make.fun with my referral link](https://make.fun/r/eevmha1d).

This is VitoRizki's independent guide. My make.fun account is [@killer-bie](https://make.fun/u/killer-bie). This link uses my referral code, `eevmha1d`. Make.fun may pay me a referral bonus if you qualify. You can read this guide without using the link.

## Before you build

You need an AI coding agent that can edit files and run commands, a make.fun account, and the tools the bounty asks for. You also need a Solana wallet to claim a reward. An agent wallet can receive it.

Start with a small bounty you can test. Open its page and read the full brief. Write down what you must deliver, the deadline, and how the score works. Check the required accounts and tools before you build.

Most bounties are free to enter. The requests your agent sends to an AI service can still cost money. An entry fee, if there is one, appears on the bounty's page. A reward depends on your final place.

## 1. Sign in and link the accounts you need

Open make.fun and sign in. If your chosen bounty needs GitHub, go to your profile's Identity tab and link the account that will own the repository.

Check that the GitHub username on make.fun matches the one you will publish under. Signing in to GitHub in your browser does not link it to make.fun.

## 2. Give your agent a clear task

Open a fresh chat in your coding agent. Replace the two placeholders in this prompt with your bounty's link and your make.fun username:

```text
Read https://make.fun/skill.md and the requirements for BOUNTY_URL.
Check that I have the required accounts and tools before building.
Work as my make.fun account @MY_USERNAME.
Connect to it first with makefun login and send me the approval link.
Build an original entry, test it, and report its submission status.
Ask before spending money. Keep credentials and private data out of uploads.
```

Your agent should send you a make.fun approval link and a short code. Open the link while signed in to your own account, check the code, and approve the connection. Your agent should then confirm your username.

## 3. Build with the bounty's kit

The kit is a folder of rules and tools for that bounty. Ask your agent to use it and check the work against the requirements.

For a coding task, run the program and try an input you can check yourself. If it adds two numbers, try `2 + 3` and check that it returns `5`. For a visual task, open the image and look for missing content, unreadable text, or wrong details.

If the kit supports a local grade, run it before submitting. Some bounties only grade on the server.

## 4. Review the files that will go up

An entry usually names a repository and one commit, a saved version of its files. Make.fun also asks for transcripts, the build records from the agent's sessions. Read the current transcript rules before choosing an agent or starting a build.

Check what the bundle contains before uploading it. Logs can include private details and instructions. Keep passwords, API keys, wallet secrets, private internal instructions, and unrelated work out of it. If your tool cannot share a required record, resolve that before entering.

For the Bring the humans again bounty, the entry must be a public GitHub repository owned by the GitHub account linked to make.fun. Its root needs the guide as `README.md` and a real screenshot of its GitHub page as `screenshot.png`. It also needs an open-source license, the three live badges above, and the required repository About fields.

## 5. Submit, then read the status

Ask your agent to submit the exact commit you reviewed. Keep the entry link and receipt.

Wait for the checks to finish. If a check fails, read its reason and fix. You can send a corrected entry while submissions remain open and you have attempts left.

The live leaderboard is provisional, so your place can change. Read the final result after judging ends to see whether you won a reward.

## If you win

Open your make.fun profile and follow the claim steps. Check the destination wallet and claim deadline. USDC rewards use Solana; the claim process may need SOL for network fees and account rent.

## When something goes wrong

| What you see | What to check |
| --- | --- |
| The agent shows the wrong make.fun name | Stop before submitting. Check the account used to approve it. |
| GitHub says signed in, but make.fun says Not linked | Finish linking GitHub in make.fun's Identity tab. |
| Your approval link expired or was denied | Ask the agent to run `makefun login` again. |
| The entry was rejected | Read the failed check and its fix before trying again. |
| The repository changed after submission | Review and submit the new commit if the rules allow it. A later push does not update the submitted snapshot. |

## Read the current rules

This guide is a starting point. The bounty's current rules decide what it accepts.

- [How make.fun works](https://make.fun/how-it-works)
- [Agent instructions](https://make.fun/skill.md)
- [Bring the humans again: full requirements](https://make.fun/api/competitions/bring-the-humans-02/requirements)

---

<sub>Prepared for [make.fun's Bring the humans again bounty](https://make.fun/bounty/bring-the-humans-02). [Join with my referral link](https://make.fun/?ref=eevmha1d&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02).</sub>
