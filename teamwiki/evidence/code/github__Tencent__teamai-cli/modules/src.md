---
title: github__Tencent__teamai-cli — src module
domain: code-knowledge
source: [src/]
---

# src

**1025 facts** (component: 733, config: 36, interface: 231, error: 25)

**Depends on**: tsup.config.ts, vitest.config.ts, vitest.e2e.config.ts, vitest.windows.config.ts, scripts, oxlint-plugin-teamai, packages
**Depended by**: scripts, packages

## Core components

- `getHermesConfigPath` ← src/hermes-config.ts:15 (66 refs)
- `hermesContextFileBudget` ← src/hermes-config.ts:23 (66 refs)
- `upsertSoulRules` ← src/hermes-config.ts:137 (66 refs)
- `readSoulRules` ← src/hermes-config.ts:164 (66 refs)
- `removeSoulRules` ← src/hermes-config.ts:181 (66 refs)
- `getHermesAllowlistPath` ← src/hermes-config.ts:186 (66 refs)
- `upsertHermesHook` ← src/hermes-config.ts:245 (66 refs)
- `removeHermesHookByCommand` ← src/hermes-config.ts:283 (66 refs)
- `addHermesAllowlist` ← src/hermes-config.ts:333 (66 refs)
- `hasHermesHookCommands` ← src/hermes-config.ts:352 (66 refs)
- `removeHermesAllowlist` ← src/hermes-config.ts:378 (66 refs)
- `enableHermesPlugin` ← src/hermes-config.ts:396 (66 refs)
- `disableHermesPlugin` ← src/hermes-config.ts:412 (66 refs)
- `isHermesPluginDisabled` ← src/hermes-config.ts:431 (66 refs)
- `isHermesPluginEnabled` ← src/hermes-config.ts:438 (66 refs)
- `resolveLegacyRole` ← src/config.ts:86 (61 refs)
- `refreshRoleAssignment` ← src/config.ts:237 (61 refs)
- `loadTeamConfig` ← src/config.ts:309 (61 refs)
- `teamToolIds` ← src/config.ts:335 (61 refs)
- `loadTeamAgentLanguage` ← src/config.ts:351 (61 refs)

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
