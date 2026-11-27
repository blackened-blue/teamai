---
title: github__Tencent__teamai-cli error
domain: code-knowledge
source:
  - src/providers/cnb/index.ts
  - src/providers/gitcode/index.ts
  - src/providers/github/index.ts
  - src/providers/gitlab/index.ts
  - src/providers/tgit/index.ts
  - src/builtin-hooks.ts
  - src/codex-trust.ts
  - src/config.ts
  - src/dashboard-collector.ts
  - src/dashboard.ts
  - src/deep-enrich.ts
  - src/doctor.ts
  - src/enrich-with-ai.ts
  - src/git-exclude.ts
  - src/hook-dispatch-cli.ts
  - src/hook-fast-path.ts
  - src/hooks.ts
  - src/import-from-mr.ts
  - src/import-from-repo.ts
  - src/import-local.ts
  - src/init.ts
  - oxlint-plugin-teamai/failure-codes.js
---

# Error

- `RepoNotFoundError` ← src/providers/cnb/index.ts:57 [EXTRACTED]
  ```
  throw new RepoNotFoundError(repo);
  ```
- `RepoNotFoundError` ← src/providers/gitcode/index.ts:104 [EXTRACTED]
  ```
  throw new RepoNotFoundError(repo);
  ```
- `RepoNotFoundError` ← src/providers/github/index.ts:50 [EXTRACTED]
  ```
  throw new RepoNotFoundError(repo);
  ```
- `RepoNotFoundError` ← src/providers/gitlab/index.ts:64 [EXTRACTED]
  ```
  throw new RepoNotFoundError(repo);
  ```
- `RepoNotFoundError` ← src/providers/tgit/index.ts:49 [EXTRACTED]
  ```
  throw new RepoNotFoundError(repo);
  ```
- `LOGIN_DEFERRED_ENV` ← src/builtin-hooks.ts:11 [INFERRED]
  ```
  import { LOGIN_DEFERRED_ENV } from './hook-fast-path.js';
  ```
- `AppServerError` ← src/codex-trust.ts:475 [EXTRACTED]
  ```
  throw new AppServerError(`config/batchWrite ${keyPath}: status ${result.status ?? 'missing'}`);
  ```
- `NotInitializedError` ← src/config.ts:895 [EXTRACTED]
  ```
  throw new NotInitializedError('teamai is not initialized. Run `teamai init` first.');
  ```
- `TeamConfigNotFoundError` ← src/config.ts:917 [EXTRACTED]
  ```
  throw new TeamConfigNotFoundError('Team config (teamai.yaml) not found. Check your repo path.');
  ```
- `UnreadableProjectConfigError` ← src/config.ts:1542 [EXTRACTED]
  ```
  if (unreadable) throw new UnreadableProjectConfigError(unreadable);
  ```
- `TRANSCRIPT_INTERRUPT_PREFIX` ← src/dashboard-collector.ts:17 [INFERRED]
  ```
  import { DASHBOARD_COMPACTION_THRESHOLD, DASHBOARD_IDLE_TIMEOUT_MS, DASHBOARD_STALE_TIMEOUT_MS, DASHBOARD_STOPPED_DISPLAY_MS, CORRECTION_WINDOW_MS, CORRECTION_KEYWORDS, TRANSCRIPT_INTERRUPT_PREFIX, TRANSCRIPT_SYSTEM_PREFIXES, stripInjectedPrompt, TRANSCRIPT_REJECT_MARKERS, TRANSCRIPT_HOST_BLOCK_MARKERS, COPILOT_TOOL_ID, getDataHome, getMachineDashboardDir, type DashboardEvent, type DashboardEventType, type DashboardSession, type SessionMetrics, type RequestCostMetrics, type LocalConfig } from './types.js';
  ```
- `HttpError` ← src/dashboard.ts:241 [EXTRACTED]
  ```
  if (!config) throw new HttpError(400, 'Select a workspace with a teamai config.');
  ```
- `INFERRED` ← src/deep-enrich.ts:249 [INFERRED]
  ```
  const confidenceCounts = { EXTRACTED: 0, INFERRED: 0, AMBIGUOUS: 0 };
  ```
- `LOGIN_DEFERRED_ENV` ← src/doctor.ts:16 [INFERRED]
  ```
  import { LOGIN_DEFERRED_ENV } from './hook-fast-path.js';
  ```
- `INFERRED` ← src/enrich-with-ai.ts:242 [INFERRED]
  ```
  confidence: 'INFERRED' as const,
  ```
- `TypeError` ← src/git-exclude.ts:73 [EXTRACTED]
  ```
  if (!OWNER.test(owner)) throw new TypeError(`Invalid git exclude owner "${owner}": use [a-z0-9/_%-] (encodeOwnerSegment)`);
  ```
- `NotReadableError` ← src/git-exclude.ts:529 [EXTRACTED]
  ```
  throw new NotReadableError(file, code ?? (e instanceof Error ? e.message : String(e)));
  ```
- `NotWritableError` ← src/git-exclude.ts:561 [EXTRACTED]
  ```
  throw new NotWritableError(file, await existingAncestor(file), e.code === 'EEXIST' || e.code === 'ENOTDIR');
  ```
- `STDERR` ← src/hook-dispatch-cli.ts:5 [INFERRED]
  ```
  * payload; all log lines go to STDERR (see setStderrOnly below).
  ```
- `LOGIN_DEFERRED_ENV` ← src/hook-fast-path.ts:50 [INFERRED]
  ```
  export const LOGIN_DEFERRED_ENV = 'TEAMAI_HOOK_LOGIN';
  ```
- `LOGIN_DEFERRED_COMMAND_RE` ← src/hooks.ts:2118 [INFERRED]
  ```
  const LOGIN_DEFERRED_COMMAND_RE = /^if \[ -x [^\]]+ \]; then [^;]+; else (.+); fi \|\| true$/;
  ```
- `ImportInputError` ← src/import-from-mr.ts:151 [EXTRACTED]
  ```
  if (!runDir) throw new ImportInputError(`${RUN_DIR_ENV} is not set. teamai import draft-mr is a step of a ${WORKFLOW} run.`);
  ```
- `ImportInputError` ← src/import-from-repo.ts:96 [EXTRACTED]
  ```
  throw new ImportInputError(`${flag} is not JSON. Pass what the ${WORKFLOW} step passes.`);
  ```
- `ImportInputError` ← src/import-local.ts:117 [EXTRACTED]
  ```
  throw new ImportInputError(`${flag} is not JSON. Pass what the ${workflow} step passes.`);
  ```
- `NoRoleSelectedError` ← src/init.ts:559 [EXTRACTED]
  ```
  throw new NoRoleSelectedError('A primary role is required.');
  ```
- `LIMIT_FAILURES` ← oxlint-plugin-teamai/failure-codes.js:6 [INFERRED]
  ```
  /** Literal codes stay owned by their runtime declarations, including LIMIT_FAILURES. */
  ```
- `JUDGE_FAILURES` ← oxlint-plugin-teamai/failure-codes.js:41 [INFERRED]
  ```
  const answers = [...literalStrings('src/workflow/failure-codes.ts', 'FAILURE_CODES'), ...literalStrings('src/scorers/label.ts', 'JUDGE_FAILURES')];
  ```
- `KNOWN_FAILURE_CODES` ← oxlint-plugin-teamai/failure-codes.js:44 [INFERRED]
  ```
  export const KNOWN_FAILURE_CODES = new Set([...diagnostics, ...answers]);
  ```
- `CANCEL_FAILED` ← oxlint-plugin-teamai/failure-codes.js:46 [INFERRED]
  ```
  /** The string constants `@teamai/runtime-protocol` exports, by name, such as `CANCEL_FAILED`: a code a step may take from it. */
  ```