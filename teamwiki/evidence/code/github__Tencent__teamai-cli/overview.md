---
title: github__Tencent__teamai-cli overview
domain: code-knowledge
---

# github__Tencent__teamai-cli

**2729 facts** extracted from 161 files.
Graph: 1108 nodes, 815 edges.

## Module Structure

| Module | Facts | Components | Interfaces |
|--------|-------|------------|------------|
| src | 1025 | 733 | 231 |
| oxlint-plugin-teamai | 41 | 37 | 0 |
| scripts | 35 | 28 | 5 |
| packages | 27 | 21 | 2 |

## Dependencies

- **src** → tsup.config.ts, vitest.config.ts, vitest.e2e.config.ts, vitest.windows.config.ts, scripts, oxlint-plugin-teamai, packages
- **scripts** → src, packages
- **packages** → src
- **vitest.windows.config.ts** → vitest.config.ts

## Key Dependency Paths

- HandlerRegistration (src/hook-handlers.ts): HandlerRegistration → HookStdinSchema → GIT_HOOK_EVENTS → TEAMAI_BIN_DIR → FOREGROUND_PAYLOAD_KEYS
- PULL_TIMEOUT_MS (src/hook-handlers.ts): PULL_TIMEOUT_MS → HookStdinSchema → GIT_HOOK_EVENTS → TEAMAI_BIN_DIR → FOREGROUND_PAYLOAD_KEYS
- buildAdoptedSummary (src/hook-handlers.ts): buildAdoptedSummary → HookStdinSchema → GIT_HOOK_EVENTS → TEAMAI_BIN_DIR → FOREGROUND_PAYLOAD_KEYS
- eligibleUpvotes (src/hook-handlers.ts): eligibleUpvotes → HookStdinSchema → GIT_HOOK_EVENTS → TEAMAI_BIN_DIR → FOREGROUND_PAYLOAD_KEYS
- buildHandlerRegistry (src/hook-handlers.ts): buildHandlerRegistry → HookStdinSchema → GIT_HOOK_EVENTS → TEAMAI_BIN_DIR → FOREGROUND_PAYLOAD_KEYS
