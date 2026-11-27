---
title: github__Tencent__teamai-cli — packages module
domain: code-knowledge
source: [packages/]
---

# packages

**1218 facts** (interface: 408, component: 747, config: 40, error: 23)

**Depends on**: src, oxlint-plugin-teamai, scripts
**Depended by**: src, scripts, .github

## Core components

- `BUILT_IN_FACTS` ← packages/tool-definitions/src/facts.ts:24 (74 refs)
- `tools` ← packages/tool-agy/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-claude/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-codebuddy/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-codex/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-copilot/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-cursor/src/definitions.ts:4 (61 refs)
- `BUILT_IN_TOOLS` ← packages/tool-definitions/src/registry.ts:26 (61 refs)
- `SIGN_INS` ← packages/tool-definitions/src/registry.ts:30 (61 refs)
- `stepLaunchOf` ← packages/tool-definitions/src/registry.ts:36 (61 refs)
- `tools` ← packages/tool-dsh/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-hermes/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-joycode/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-kiro/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-muse/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-openclaw/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-opencode/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-pi/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-qoder/src/definitions.ts:4 (61 refs)
- `tools` ← packages/tool-trae/src/definitions.ts:4 (61 refs)

## Config

- `process.env.CLAUDE_CONFIG_DIR` ← packages/tool-claude/src/testing/index.ts
- `process.env.CODEX_HOME` ← packages/tool-codex/src/testing/index.ts
- `process.env.TEAMAI_WORKFLOW_RESULT` ← packages/tool-codex/src/testing/index.ts
- `process.env.TMPDIR` ← packages/tool-codex/src/testing/index.ts
- `process.env.PASEO_HOME` ← packages/runtime-paseo/src/providers.ts
- `RUNTIME_PROTOCOL_ENV` ← packages/runtime-protocol/src/protocol.ts
- `RUN_DIR_ENV` ← packages/runtime-protocol/src/protocol.ts
- `WORKFLOW_DIR_ENV` ← packages/runtime-protocol/src/protocol.ts
- `process.env.OPENCODE_CONFIG` ← packages/runtime-tools/src/confined.ts
- `process.env.PATH` ← packages/shared/src/exec.ts

## Errors

- `CANCEL_FAILED` ← packages/runtime-kit/src/serve.ts
- `CANCEL_FAILED` ← packages/runtime-paseo/src/conversation.ts
- `CANCEL_FAILED` ← packages/runtime-paseo/src/runtime.ts
- `CANCEL_FAILED` ← packages/runtime-paseo/src/sandbox.ts
- `CANCEL_FAILED` ← packages/runtime-protocol/src/protocol.ts
- `PROMPT_FAILURE_CODES` ← packages/runtime-protocol/src/protocol.ts
- `STDERR_CHARS` ← packages/runtime-sandbox/src/bounded-tail.ts
- `CANCEL_FAILED` ← packages/runtime-sandbox/src/exec.ts
- `CANCEL_FAILED` ← packages/runtime-sandbox/src/prompt.ts
- `STDERR_CHARS` ← packages/runtime-sandbox/src/step.ts
