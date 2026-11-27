---
title: github__Tencent__teamai-cli — scripts module
domain: code-knowledge
source: [scripts/]
---

# scripts

**35 facts** (component: 28, interface: 5, config: 2)

**Depends on**: src, packages
**Depended by**: src

## Core components

- `loadCommandTable` ← scripts/command-table.ts:2 (1 refs)
- `COMMANDS_REFERENCE_PATH` ← scripts/commands-reference.ts:17 (1 refs)
- `renderCommandsReference` ← scripts/commands-reference.ts:78 (1 refs)
- `catalogFromLiteLlm` ← scripts/model-prices.ts:125 (1 refs)
- `parseCatalog` ← scripts/model-prices.ts:168 (1 refs)
- `formatCatalog` ← scripts/model-prices.ts:173 (1 refs)
- `describeCatalogChange` ← scripts/model-prices.ts:182 (1 refs)
- `TOOL_SUPPORT_PAGES` ← scripts/tool-support.ts:17 (1 refs)
- `ToolSupportLang` ← scripts/tool-support.ts:22 (1 refs)
- `renderToolSupportPage` ← scripts/tool-support.ts:241 (1 refs)
- `observerReads` ← scripts/verify/observer.ts:58
- `attemptsObserved` ← scripts/verify/observer.ts:68
- `Listed` ← scripts/verify/observer.ts:167
- `ProcEntry` ← scripts/verify/observer.ts:192
- `bwrapSteps` ← scripts/verify/observer.ts:203
- `startObserver` ← scripts/verify/observer.ts:236
- `measureAgentContext` ← scripts/agent-context-budget.ts:84
- `compareAgentContext` ← scripts/agent-context-budget.ts:147
- `AgentWaitBudgetSchema` ← scripts/agent-wait-budget.ts:55
- `AgentWaitBudget` ← scripts/agent-wait-budget.ts:64

## Config

- `process.env.TEAMAI_COMMAND_TABLE_ONLY` ← scripts/command-table.ts
- `process.env.GITHUB_TOKEN` ← scripts/update-model-prices.ts
