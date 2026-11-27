---
title: github__Tencent__teamai-cli — src module
domain: code-knowledge
source: [src/]
---

# src

**6067 facts** (component: 4108, config: 96, interface: 1764, error: 99)

**Depends on**: oxlint-plugin-teamai, tsup.config.ts, vitest.config.ts, vitest.e2e.config.ts, vitest.windows.config.ts, packages, scripts, .github
**Depended by**: scripts, packages, .github

## Core components

- `DriverIdentity` ← src/workflow/types.ts:21 (524 refs)
- `OutputSchema` ← src/workflow/types.ts:27 (524 refs)
- `StepHitl` ← src/workflow/types.ts:43 (524 refs)
- `onlyPersonAnswers` ← src/workflow/types.ts:61 (524 refs)
- `unattendedChoice` ← src/workflow/types.ts:69 (524 refs)
- `WorkflowStep` ← src/workflow/types.ts:77 (524 refs)
- `Budget` ← src/workflow/types.ts:184 (524 refs)
- `ForEach` ← src/workflow/types.ts:189 (524 refs)
- `WorkflowLoop` ← src/workflow/types.ts:203 (524 refs)
- `StepLoop` ← src/workflow/types.ts:213 (524 refs)
- `TeamPlace` ← src/workflow/types.ts:225 (524 refs)
- `ConfinedPlace` ← src/workflow/types.ts:233 (524 refs)
- `StepWorkspace` ← src/workflow/types.ts:238 (524 refs)
- `STEP_ACTIONS` ← src/workflow/types.ts:241 (524 refs)
- `hasAction` ← src/workflow/types.ts:244 (524 refs)
- `EndOutcome` ← src/workflow/types.ts:248 (524 refs)
- `WorkflowFrom` ← src/workflow/types.ts:251 (524 refs)
- `StepWorkflow` ← src/workflow/types.ts:256 (524 refs)
- `stepWorkflow` ← src/workflow/types.ts:262 (524 refs)
- `isWorkflowFile` ← src/workflow/types.ts:271 (524 refs)

## Config

- `process.env.TEAMAI_COMMAND_TABLE_ONLY` ← src/index.ts
- `process.env.TEAMAI_DRY_RUN` ← src/index.ts
- `process.env.TEAMAI_CACHE_DIR` ← src/utils/cache-index.ts
- `process.env.TEAMAI_CACHE_MAX_BYTES` ← src/utils/cache-index.ts
- `process.env.GIT_AUTHOR_NAME` ← src/providers/git/index.ts
- `process.env.GITCODE_TOKEN` ← src/providers/gitcode/index.ts
- `process.env.TEAMAI_SKIP_AST` ← src/wiki-engine/code-knowledge/ast/index.ts
- `process.env.TEAMAI_API_TOKEN` ← src/api-key.ts
- `process.env.CLAUDE_CODE_AUTO_COMPACT_WINDOW` ← src/autocompact-reconcile.ts
- `process.env.CODEBUDDY_AUTO_COMPACT_WINDOW` ← src/autocompact-reconcile.ts

## Errors

- `RepoNotFoundError` ← src/providers/cnb/index.ts
- `RepoNotFoundError` ← src/providers/gitcode/index.ts
- `RepoNotFoundError` ← src/providers/github/index.ts
- `RepoNotFoundError` ← src/providers/gitlab/index.ts
- `RepoNotFoundError` ← src/providers/tgit/index.ts
- `LOGIN_DEFERRED_ENV` ← src/builtin-hooks.ts
- `AppServerError` ← src/codex-trust.ts
- `NotInitializedError` ← src/config.ts
- `TeamConfigNotFoundError` ← src/config.ts
- `UnreadableProjectConfigError` ← src/config.ts
