# Adopt DOX without losing the project

The agent does this work. The owner should not need to rebuild a filing system.

## Existing project

1. Read applicable instructions and handoffs. Identify actual working source, installed copy, owners, holds and latest user direction. Stay within the requested project.
2. Find existing authorities for state, decisions, tasks and evidence. A `CURRENT-STATUS.md` can remain authoritative: add the short resume section there and make `START-HERE.md` a pointer to it. Map filenames in instructions. Do not keep two editable summaries.
3. Merge the portable agent contract into existing `AGENTS.md`; never overwrite existing local rules or scope. For a host using another entry point, connect through that existing file and verify that the agent reads it. Do not assume universal host support.
4. Reconcile status against actual source/build identity. Separate working source, installed app and published repository. Keep conflicting reports explicitly unresolved until verified.
5. Fill the resume section with one authorized next action and its exact starting file/page or verified command. Explain its priority briefly only when needed. Preserve a pause or completion when appropriate. Do not invent further work or make the owner plan the whole backlog.
6. Reuse existing capture and decision systems. Preserve unique facts, failures, constraints and evidence from old handoffs. Replace duplicate state sections with pointers only after those facts have a destination. Preserve originals in version control or a dated archive before editing.
7. Inspect durable scope boundaries and existing child contracts. Create or reconcile child AGENTS.md files using [the standard structure](CHILD-TEMPLATE.md); state each scope's responsibilities and what its parent retains. Register direct children in each parent's Child DOX Index. Leave unestablished guidance/check sections empty. Do not relocate source just to make the tree look uniform.
8. Check both views: simulate returning after an interruption, then changing a local contract. The agent must locate the right copy and one next action, read the correct parent/child chain, and identify every affected contract/index to update.

If the owner reports that the result is too much to navigate, keep that as a usability issue to address even if the link check passes. Adjust the entry view using the same underlying hierarchy. Do not require an old-inbox cleanup before the owner can resume.

Do not bulk rewrite child instructions, rename working folders, relocate source, delete history, install software or publish material as part of documentation adoption unless that is also within scope.

## New project

Copy the four `starter/` files into the root. Merge if any destination exists. Fill unknowns from evidence; leave missing information explicitly unknown. Then establish indexed child contracts at real scope boundaries. The starter's no-children placeholder must be replaced with the actual project index when children exist. Do not copy DOX's own project status as another project's status.

## Mirrors and inaccessible systems

A public summary is an optional curated mirror, with its last-sync date and source pointer. It is not a second authority. Keep private paths, personal notes and internal evidence out of public copies.

When another system cannot be updated, checkpoint locally and name the unsynced mirror and its owner. If the authority itself is inaccessible, record a pending update in the existing handoff, including source identity and conflict. Do not silently replace the authority or claim it is current.
