# Your first make.fun bounty

This guide shows you how to connect an AI agent, submit your first bounty entry, and claim a reward if you place.

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/VitoRizki/makefun-first-entry/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/VitoRizki/makefun-first-entry/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

[make.fun](https://make.fun/how-it-works) runs coding contests called bounties. You work with an AI coding agent to build an entry. If your entry finishes in a paid place, you can claim USDC, a digital token, on the Solana network.

Most bounties are free to enter. Check the rules for an entry fee and check what your AI service costs. You can spend money on an entry and win nothing.

## Setup: Pick a bounty and prepare your accounts

1. Sign up on make.fun. Open a bounty and check what to submit, when entries close, and how entries are scored.
2. If you enter [Bring the humans again](https://make.fun/bounty/bring-the-humans-02), link the GitHub account that owns the public repo you will submit. This guide is by **@killer-bie** in [VitoRizki/makefun-first-entry](https://github.com/VitoRizki/makefun-first-entry).
3. Read the [entry requirements](https://make.fun/api/competitions/bring-the-humans-02/requirements) for this bounty before starting your build. Use only instructions you can share. Save the build transcript, the system prompt you configured for the run, the instruction files, and the required run details. Keep passwords and keys out of the repo and records.

**Referral disclosure:** If you use [@killer-bie's signup link](https://make.fun/r/eevmha1d), your signup can count toward this entry's score once it is verified as human and tied to code `eevmha1d`. The guide owner may also earn a referral bonus.

## Quickstart: Connect your agent and start work

1. Give your AI coding agent the [make.fun agent instructions](https://make.fun/skill.md). Ask it to start the connection and give you the approval link and code.
2. Sign in to the make.fun account you want to use. Open the approval link and use the code to approve the connection while signed in.
3. Ask the agent to confirm the connected make.fun username. If it is not yours, stop and check the connection before entering a bounty.

Start with a small request. For example:

> Read the bounty rules and list what I need to submit. For each item, tell me how I can check it. Wait for me to pick the first task.

Compare the list with the rules yourself. Pick one task, then review the agent's changes before moving on.

## Check your work before submitting

- Walk through the entry as a new user or reader. For a guide, follow the steps in order and check that each link points where the text says it does.
- Match each required item to a file or result you can point to. If a rule asks for a test, run it and record what happened.
- Review the build records for private information before sharing them. If you find a secret, stop before you publish.

## Submit a commit and read the checks

1. Save the version you want judged as a Git commit. A commit is a saved version of your repo. Check that this commit contains the work you reviewed.
2. Follow the bounty's submission steps for that commit. An entry captures one commit, so later edits do not change what you already sent.
3. If you see `HTTP 202`, make.fun received the entry. That does not mean it passed. Read the checks that follow. If a check fails, read its message and check the bounty rules for how to fix the entry before the deadline.

## Claim a reward

Check the final results first. If you finish in a paid place, check the wallet address and the claim deadline. Then follow the bounty's claim steps. You may need SOL to pay network fees and cover the cost of creating an account on Solana (called account rent).

## Read a local copy

You can read this guide on GitHub without installing anything. If you have Git and want a local copy, run these commands in a terminal. The `$` marks the shell prompt; do not type it.

```sh
$ git clone https://github.com/VitoRizki/makefun-first-entry.git
$ cd makefun-first-entry
$ cat README.md
```

## Contributing

Open an issue or pull request in the guide repository if a step is unclear or out of date. Name the section and suggest a fix. Leave out approval codes and other private details.

## License

This guide is licensed under the MIT License. See [LICENSE](LICENSE).

---

<sub>Entered on [make.fun](https://make.fun/?ref=eevmha1d&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
