# Continuation

Continuation is a skill for moving authorized work from a current checkpoint to a verified outcome. It coordinates ownership, handoffs, repair, integration, consumer acceptance, and resumption without treating activity or acknowledgments as proof of completion.

## What it does

- Recovers the goal, current state, existing owners, communication routes, and limits.
- Continues the next ready, authorized action without duplicating completed or active work.
- Preserves an exact checkpoint and next action when work is interrupted or blocked.
- Separates implementation, delivery, receipt, adoption, and verification in the intended consumer.
- Reports evidence and limits honestly, including unavailable tools and unresolved dependencies.

## Recommended three-skill pack

For work that needs planning, coordinated follow-through, and defect diagnosis, use **Delivery Roadmap + Continuation + Diagnosing Bugs** together:

- **Delivery Roadmap** maintains one authoritative plan: outcomes, owners, dependencies, acceptance evidence, estimates, and next-step readiness.
- **[Continuation](https://github.com/dmitry9g/continuation)** coordinates the next authorized action, handoffs, checkpoints, integration, and verification in the receiving environment.
- **[Diagnosing Bugs](https://github.com/mattpocock/skills/tree/main/skills/engineering/diagnosing-bugs)**, by **Matt Pocock**, investigates actual failures with a reproducible feedback loop and verifies the repair against the original scenario.

Start with Delivery to establish the outcome and roadmap. Use Continuation to move between ready steps and preserve context across handoffs or interruptions. When a genuine defect blocks progress, apply Diagnosing Bugs, attach the evidence to the same roadmap, and reassess readiness before continuing. Do not invent bugs just to exercise the pack.

The skills remain separate and complementary. Use the same task IDs, owners, revisions, and evidence instead of creating competing plans. Verify that each skill is available and loaded in the environment doing the work. Installation alone is not proof of adoption or successful execution.

This pack does not grant additional permissions, authorize spending or publication, or provide a scheduler. Existing scope, approvals, budgets, and stop instructions still apply.

Diagnosing Bugs is an independent upstream project, not an original component of Delivery or Continuation. Obtain it from [Matt Pocock's original repository](https://github.com/mattpocock/skills); its [MIT license](https://github.com/mattpocock/skills/blob/main/LICENSE) and attribution remain applicable. It is linked here, not redistributed in this package.

## Package identity

**Continuation 0.2.0** is the generic public package. Its identifier is `continuation`. Publishing it does not rename or modify existing installations.

The reusable workflow supports authorized engineering teams. Keep project-specific names, routes, current state, and examples in the project's own records rather than in these reusable instructions.

## Repair reserves in 0.2.0

When acceptance is blocked, Continuation can apply an explicitly owner-approved repair reserve maintained by Delivery Roadmap. It checks the same scope, deadline, commitments and balance at start, retry, resume and handoff, so covered repairs can proceed without repeated generic acknowledgements. The reserve includes verification, required review, integration and receiving handoff, not just the code edit.

No skill or template grants authority. Explicit stops, restricted actions, hard exclusions and separately required confirmations still apply. Unknown charges are not free capacity; concurrent work must reserve allowance first, and closed/frozen balances cannot be reused without owner authority. This is guidance, not an enforced accounting system.

## Package contents and use

The source package contains `SKILL.md` and its canonical `references/universal-directive.txt`. Both are required. Read the master directive before applying or adapting the workflow.

After installing the complete package, invoke `$continuation`. Give it the desired outcome, current checkpoint, acceptance criteria, existing owners, permitted communication routes, and applicable limits. Ask it to use [Delivery Roadmap](https://github.com/dmitry9g/delivery-roadmap) and [Diagnosing Bugs](https://github.com/mattpocock/skills/tree/main/skills/engineering/diagnosing-bugs) when available and relevant.

Verify discovery and loading in the executing session. Do not install missing companions or start team work merely because this README recommends them.

## Limitations

This is operating guidance, not enforcement software or a scheduler. It cannot keep a suspended session running, create access, guarantee adoption by another agent, or establish unattended reliability. A successful offline check does not prove a live workflow, and completion of a scoped task does not close a stricter parent outcome.

## Installation

Download the [repository ZIP](https://github.com/dmitry9g/continuation/archive/refs/heads/main.zip), extract it, and copy its contents into `~/.codex/skills/continuation/`. Keep `SKILL.md`, `references/universal-directive.txt`, and `agents/openai.yaml` together. Start a new conversation and verify that the skill is discovered and can be loaded before relying on it.

If this skill helped you finish a task, give this repo a ⭐ on GitHub. It helps me see what’s worth improving.

## Validation and license status

Version 0.2.0 passed package/frontmatter validation, relative-reference and metadata checks, version consistency and a privacy-name/path scan. An independent 11-case tabletop review covered an approved repair, insufficient allowance, expiry, concurrent commitments, forecast-file changes, hard exclusions, denied actions, explicit pause, changed acceptance, frozen balance and uncertain paid outcomes. These are textual and decision checks, not fresh-session execution, enforced concurrency/accounting, or proof of unattended reliability.

Continuation is licensed under the [MIT License](LICENSE), copyright (c) 2026 Dmitry Gordi. Delivery Roadmap and the externally linked Diagnosing Bugs retain their own licenses.

