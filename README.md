# DOX: pick it back up

**Open your project. See where you stopped. Know the next step.**

![Combined DOX in Flutter Deck: a short resume page alongside the root instruction contract, child indexes and scoped agent documents](combined-dox-flutter-deck.png)

**Teal keeps your place. Blue organizes the agents' instructions.** This Flutter Deck example shows how the combined workflow fits together. The render illustrates the documentation layout; it is not a live status display or a new dashboard. Click the image to view it at full size.

DOX is a small Markdown workflow for returning to work after an interruption. The agent keeps your place; you do not have to reconstruct the conversation or maintain a filing system.

Under that short entry page, agents maintain the original DOX hierarchy: explicit scope ownership, child indexes, standard child contracts and a mandatory documentation pass after meaningful changes.

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

For a new project, copy the four [starter files](starter/) into its root, then have the agent identify real scope boundaries and add indexed child contracts. These four files are the entry kit, not a limit on the hierarchy. For an existing project, **merge** instructions and map existing state documents first. Never overwrite an existing AGENTS.md. A prompt alone does not install files. [Migration guide](guides/MIGRATION.md).

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

Original DOX organizes agent instructions into a tree. This version retains that tree and its mandatory maintenance, and adds a human resume page, checkpoints during work, an inbox, durable decisions and exact working-copy pointers. Agents maintain the structure; you normally use the short page.

Each parent declares ownership and indexes direct child AGENTS.md files. Children use Purpose, Ownership, Local Contracts, Work Guidance, Verification and Child DOX Index. Before editing, agents read the applicable chain; after meaningful work, they update affected scopes and indexes. [Child-document template](guides/CHILD-TEMPLATE.md).

Existing specs, test records and useful local rules stay where they belong. DOX links to them instead of copying them into more documents.

[Filled-in example](guides/EXAMPLE.md) · [Migration](guides/MIGRATION.md) · [Design decisions](guides/DESIGN.md)

## Limits and credits

DOX does not watch files, capture chats, enforce locks, update another app or run when no agent is active. Scenario review can check consistency; usefulness over time still needs real use.

Adapted from [agent0ai/dox](https://github.com/agent0ai/dox), created by [Agent Zero](https://www.agent-zero.ai/). Original [MIT license](LICENSE), artwork and [copyright notices](COPYRIGHT.md) are preserved.
