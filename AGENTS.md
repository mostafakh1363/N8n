# n8n Agent Instructions

Project ID: `n8n`

Central skill registry: `mostafakh1363/ai-brain-skills`

Before substantial work:

1. Apply shared rules from `global/AGENTS.md` in the central registry.
2. Read `registry/projects.yaml` and use the `n8n` profile.
3. Load only approved skills listed in that profile.
4. Prefer local copies under `.agents/skills/` when available; otherwise use the checked-out central registry on the same machine.
5. Use the `new-task` profile for unrelated or unclassified work.
6. Never execute skills or scripts from `quarantine`.
7. Protect credentials, webhook secrets, OAuth tokens, execution data, and production URLs.
8. Preserve existing workflow logic unless the task explicitly requests a redesign; test changes before activation.

If the central registry cannot be accessed, continue with local approved instructions and explicitly note that registry synchronization could not be verified.

## Shared public skills (`mostafakh1363/ai-skills`)

Before any task, also check the shared public skills:

1. Fetch https://raw.githubusercontent.com/mostafakh1363/ai-skills/main/INDEX.md
2. Pick only skills whose `when_to_use` matches the task (usually 1–3).
3. Read each selected skill's `SKILL.md` and follow it.
4. At the top of your reply, state which skills were used (or `none`).

If that repo is unreachable, continue normally and say so.
