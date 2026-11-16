<p align="center"><img src="readme-banner.png" alt="DOX project artwork" width="100%"></p>

# DOX: pick it back up

**Open your project. See where you stopped. Know the next step.**

DOX is a small Markdown workflow for returning to work after an interruption. The agent keeps your place; you do not have to reconstruct the conversation or maintain a filing system.

Designed for someone who loses the thread easily, including people with ADHD. This is a workflow design, not treatment or a claim that everyone works the same way.

**Working on DOX itself? Open [START-HERE.md](START-HERE.md).**

## What you see when you return

> **We stopped here:** The save fix is written. Reopening still loses the note.
>
> **Next:** The agent will reproduce the reopen failure using disposable test data.
>
> **You need to do:** Nothing right now.

One page. One next action. Evidence and reference material sit below the short version.

## Start using it

Give your project agent access to this repository or its downloaded files, then say:

```text
Adopt DOX's starter/AGENTS.md workflow for this project.
Preserve existing instructions and work. Follow guides/MIGRATION.md.
Create one short resume page from the actual current state:
where we stopped, one next action, and anything needed from me.
Keep it updated as you work. Do the documentation maintenance yourself.
```

For a new project, copy the four [starter files](starter/) into its root. For an existing project, **merge** instructions and map existing state documents first. Never overwrite an existing AGENTS.md. A prompt alone does not install files. [Migration guide](guides/MIGRATION.md).

| File | Purpose | Maintained by |
| --- | --- | --- |
| [START-HERE.md](starter/START-HERE.md) | Your place, next action, working copy and evidence | Agent |
| [INBOX.md](starter/INBOX.md) | Unsorted thoughts and parked ideas | You can dump; agent sorts |
| [DECISIONS.md](starter/DECISIONS.md) | Choices and boundaries worth keeping | Agent |
| [AGENTS.md](starter/AGENTS.md) | Instructions that keep this useful | Agent |

You normally open only START-HERE. No daily log, tags, inbox-clearing ritual or catching up on missed days is required.

## Things you can say

- **“I'm lost.”** Get three short lines: stopped here, next, need from you.
- **“Remember this for this project: …”** Record the choice or capture the idea without silently starting work.
- **“Park this.”** Keep the thought outside the immediate queue.
- **“I'm stopping.”** Checkpoint if the agent has time to act; after an abrupt stop, the next agent verifies the files.
- **“What actually works?”** Explain evidence for this working copy, including failures and untested behavior.

These are conversational conventions, not registered commands. They depend on the agent reading and following the contract.

## What changed

Original DOX organizes agent instructions into a tree. This version keeps useful scoped instructions and makes a human resume page the main entry point. It adds checkpoints during work, an inbox, durable decisions and exact working-copy pointers.

Existing specs, test records and useful local rules stay where they belong. DOX links to them instead of copying them into more documents.

[Filled-in example](guides/EXAMPLE.md) · [Migration](guides/MIGRATION.md) · [Design decisions](guides/DESIGN.md)

## Limits and credits

DOX does not watch files, capture chats, enforce locks, update another app or run when no agent is active. Scenario review can check consistency; usefulness over time still needs real use.

Adapted from [agent0ai/dox](https://github.com/agent0ai/dox), created by [Agent Zero](https://www.agent-zero.ai/). Original [MIT license](LICENSE), artwork and [copyright notices](COPYRIGHT.md) are preserved.
