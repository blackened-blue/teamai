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
  - src/pull.ts
  - src/role-assignments.ts
  - src/roles.ts
  - src/shared-instruction-source.ts
  - src/team-ref.ts
  - src/types.ts
  - src/update.ts
  - src/ci/extract-mr.ts
  - src/dashboard/benchmarks.ts
  - src/dashboard/distribution.ts
  - src/dashboard/http.ts
  - src/dashboard/judging-view.ts
  - src/dashboard/scorers.ts
  - src/dashboard/workflow-runs.ts
  - src/maintenance/paths.ts
  - src/resources/env-loader.ts
  - src/scorers/attempts-upgrade.ts
  - src/scorers/label.ts
  - src/scorers/marks.ts
  - src/scorers/score-labels.ts
  - src/session-flow/sync.ts
  - src/utils/branch-worktree.ts
  - src/utils/git.ts
  - src/utils/import-lock.ts
  - src/utils/json.ts
  - src/utils/reports-branch.ts
  - src/wiki-engine/knowledge-reconciler.ts
  - src/wiki-engine/manifest-schema.ts
  - src/wiki-engine/reconciler-v2-types.ts
  - src/workflow/conformance-interpreter.ts
  - src/workflow/expression.ts
  - src/workflow/failure-codes.ts
  - src/workflow/protocol.ts
  - src/workflow/requirements.ts
  - src/workflow/snapshot.ts
  - src/workflow/step-state.ts
  - src/workflow/store.ts
  - packages/runtime-kit/src/serve.ts
  - packages/runtime-paseo/src/conversation.ts
  - packages/runtime-paseo/src/runtime.ts
  - packages/runtime-paseo/src/sandbox.ts
  - packages/runtime-protocol/src/protocol.ts
  - packages/runtime-sandbox/src/bounded-tail.ts
  - packages/runtime-sandbox/src/exec.ts
  - packages/runtime-sandbox/src/prompt.ts
  - packages/runtime-sandbox/src/step.ts
  - packages/runtime-t3/src/conversation.ts
  - packages/runtime-t3/src/t3.ts
  - packages/shared/src/regular-file.ts
  - packages/tool-agy/src/session-adapter.ts
  - packages/tool-copilot/src/session-adapter.ts
  - packages/tool-cursor/src/session-adapter.ts
  - packages/tool-hermes/src/session-adapter.ts
  - packages/tool-muse/src/session-adapter.ts
  - packages/tool-opencode/src/session-adapter.ts
  - packages/tool-pi/src/session-adapter.ts
  - src/providers/cnb/cnb-cli.ts
  - src/providers/gitcode/gitcode-api.ts
  - src/providers/github/gh-cli.ts
  - src/providers/gitlab/gitlab-api.ts
  - src/providers/tgit/gf-cli.ts
  - src/wiki-engine/code-knowledge/code-extractors.ts
  - src/wiki-engine/code-knowledge/code-graph.ts
  - src/wiki-engine/core/graph-index.schema.ts
  - src/wiki-engine/core/wiki-protocol.ts
  - src/workflow/fleet/member.ts
  - src/workflow/fleet/owner.ts
  - src/workflow/runtimes/attempt.ts
  - src/workflow/runtimes/cancelled.ts
  - src/workflow/runtimes/tool-caller.ts
  - src/workflow/steps/runtime-steps.ts
  - packages/runtime-sandbox/src/providers/cli.ts
  - packages/runtime-sandbox/src/providers/vercel.ts
  - src/wiki-engine/code-knowledge/ast/call-resolver.ts
  - src/wiki-engine/code-knowledge/ast/walk.ts
  - src/wiki-engine/code-knowledge/extractors/go.ts
  - src/wiki-engine/code-knowledge/extractors/java.ts
  - src/wiki-engine/code-knowledge/extractors/python.ts
  - src/wiki-engine/code-knowledge/extractors/rust.ts
  - src/wiki-engine/code-knowledge/extractors/scala.ts
  - src/wiki-engine/code-knowledge/extractors/swift.ts
  - src/wiki-engine/code-knowledge/extractors/typescript.ts
  - oxlint-plugin-teamai/failure-codes.js
  - oxlint-plugin-teamai/rules/workflow-failure-codes.js
  - .github/scripts/erosion-summary.py
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
- `FILE_NOT_FOUND_ERROR_CODE` ← src/pull.ts:117 [INFERRED]
  ```
  const FILE_NOT_FOUND_ERROR_CODE = 'ENOENT';
  ```
- `RoleAssignmentsNotFoundError` ← src/role-assignments.ts:182 [EXTRACTED]
  ```
  if (content === null) throw new RoleAssignmentsNotFoundError(where);
  ```
- `RolesManifestNotFoundError` ← src/roles.ts:153 [EXTRACTED]
  ```
  throw new RolesManifestNotFoundError(manifestPath);
  ```
- `SHARED_INSTRUCTION_PREFERRED_DIR` ← src/shared-instruction-source.ts:26 [INFERRED]
  ```
  export const SHARED_INSTRUCTION_PREFERRED_DIR: SharedInstructionSourceDir = 'agentsmd';
  ```
- `DirtyTeamRepoError` ← src/team-ref.ts:135 [EXTRACTED]
  ```
  if (paths.length > 0) throw new DirtyTeamRepoError(target, paths);
  ```
- `DetachedRecoveryError` ← src/team-ref.ts:189 [EXTRACTED]
  ```
  throw new DetachedRecoveryError(error);
  ```
- `TRANSCRIPT_INTERRUPT_PREFIX` ← src/types.ts:2510 [INFERRED]
  ```
  export const TRANSCRIPT_INTERRUPT_PREFIX = '[Request interrupted by user';
  ```
- `LockDirectoryGoneError` ← src/update.ts:800 [EXTRACTED]
  ```
  if (!createParent && errnoCode(err) === 'ENOENT' && !(await fse.pathExists(path.dirname(resolved)))) throw new LockDirectoryGoneError(resolved);
  ```
- `ImportInputError` ← src/ci/extract-mr.ts:51 [EXTRACTED]
  ```
  if (drafted === undefined) throw new ImportInputError(`--learnings holds no learning. Pass what the ${WORKFLOW} step passes.`);
  ```
- `HttpError` ← src/dashboard/benchmarks.ts:37 [EXTRACTED]
  ```
  if (!parsed.success) throw new HttpError(400, `Benchmark history takes window ${BENCHMARK_WINDOWS.join(', ')} and a suite name.`);
  ```
- `HttpError` ← src/dashboard/distribution.ts:27 [EXTRACTED]
  ```
  throw new HttpError(409, `Roles are assigned in ${ROLE_ASSIGNMENTS_FILE} in the team repo and cannot be changed here. `
  ```
- `HttpError` ← src/dashboard/http.ts:60 [EXTRACTED]
  ```
  if (size > MAX_JSON_BODY_BYTES) throw new HttpError(400, 'Request body too large.');
  ```
- `JUDGE_FAILED` ← src/dashboard/judging-view.ts:43 [INFERRED]
  ```
  const JUDGE_FAILED=${JSON.stringify(FAILED)}, JUDGING_STATE=${JSON.stringify(STATE)}, JUDGING_MEANS=${JSON.stringify(MEANS)}, RESCORED=${JSON.stringify(RESCORED)}, MARK_LAPSES=${MARK_LAPSES};
  ```
- `HttpError` ← src/dashboard/scorers.ts:53 [EXTRACTED]
  ```
  throw new HttpError(400, `Scorer results take window ${SCORER_WINDOWS.join(', ')}, a grouping the page offers, a commit as hex digits, and up to ${FAILING_MAX} failing labels.`);
  ```
- `HttpError` ← src/dashboard/workflow-runs.ts:611 [EXTRACTED]
  ```
  if (!parsed.success) throw new HttpError(400, 'Send run, step, pass and choice of the HITL request you answer.');
  ```
- `CheckoutLockedError` ← src/maintenance/paths.ts:68 [EXTRACTED]
  ```
  throw new CheckoutLockedError(checkout, refreshed.lockPath);
  ```
- `CheckoutUnavailableError` ← src/maintenance/paths.ts:70 [EXTRACTED]
  ```
  throw new CheckoutUnavailableError(checkout, refreshed.reason);
  ```
- `SyncLockedError` ← src/maintenance/paths.ts:108 [EXTRACTED]
  ```
  throw new SyncLockedError();
  ```
- `EnvScopesUnreadableError` ← src/resources/env-loader.ts:238 [EXTRACTED]
  ```
  throw new EnvScopesUnreadableError(update.reason);
  ```
- `JUDGE_FAILURES` ← src/scorers/attempts-upgrade.ts:13 [INFERRED]
  ```
  import { JUDGE_FAILURES, RunSubjectSchema, SessionSubjectSchema, type JudgeFailureCode, type ScoreLabel } from './label.js';
  ```
- `JUDGE_FAILURES` ← src/scorers/label.ts:95 [INFERRED]
  ```
  export const JUDGE_FAILURES = ['judge_failed', 'lease_expired', 'evidence_empty', 'judge_answer_invalid', 'judge_tool_unavailable', 'check_could_not_run'] as const;
  ```
- `JUDGE_FAILURES` ← src/scorers/marks.ts:15 [INFERRED]
  ```
  import { JUDGE_FAILURES, type JudgeFailureCode, type RunSubject } from './label.js';
  ```
- `JUDGE_FAILURES` ← src/scorers/score-labels.ts:22 [INFERRED]
  ```
  import { JUDGE_FAILURES, labelVersion, ScoreLabelSchema, type Decider, type JudgeFailureCode, type ScoreLabel } from './label.js';
  ```
- `AggregateError` ← src/session-flow/sync.ts:1282 [EXTRACTED]
  ```
  throw new AggregateError([error, ...failures], `Session archive rollback failed; original files kept at ${files.flatMap((f) => (f.backedUp ? [f.backup] : [])).join(', ')}`, { cause: error });
  ```
- `ForeignCheckoutError` ← src/utils/branch-worktree.ts:496 [EXTRACTED]
  ```
  throw new ForeignCheckoutError(
  ```
- `CheckoutRefusedError` ← src/utils/branch-worktree.ts:507 [EXTRACTED]
  ```
  throw new CheckoutRefusedError(
  ```
- `DetachedTeamRepoError` ← src/utils/git.ts:797 [EXTRACTED]
  ```
  throw new DetachedTeamRepoError(await getDefaultBranch(localPath));
  ```
- `ImportLockHeldError` ← src/utils/import-lock.ts:209 [EXTRACTED]
  ```
  if (!taken.held || !taken.value) throw new ImportLockHeldError(await refusal(lockPath));
  ```
- `SyntaxError` ← src/utils/json.ts:33 [EXTRACTED]
  ```
  throw new SyntaxError(`${first === undefined ? 'no value' : printParseErrorCode(first.error)} at offset ${first?.offset ?? 0}`);
  ```
- `EmptyRepoError` ← src/utils/reports-branch.ts:316 [EXTRACTED]
  ```
  throw new EmptyRepoError(repoRoot);
  ```
- `CheckoutRefusedError` ← src/utils/reports-branch.ts:331 [EXTRACTED]
  ```
  throw new CheckoutRefusedError(
  ```
- `DirtyPreviewError` ← src/utils/reports-branch.ts:447 [EXTRACTED]
  ```
  throw new DirtyPreviewError(repoRoot);
  ```
- `PreviewFetchError` ← src/utils/reports-branch.ts:487 [EXTRACTED]
  ```
  if (!options.allowStale) throw new PreviewFetchError(e);
  ```
- `MISSING_PATH_ERROR_CODE` ← src/wiki-engine/knowledge-reconciler.ts:113 [INFERRED]
  ```
  const MISSING_PATH_ERROR_CODE = 'ENOENT';
  ```
- `INFERRED` ← src/wiki-engine/manifest-schema.ts:25 [INFERRED]
  ```
  export type ManifestConfidence = "EXTRACTED" | "INFERRED" | "AMBIGUOUS";
  ```
- `INFERRED` ← src/wiki-engine/reconciler-v2-types.ts:21 [INFERRED]
  ```
  if (score >= 0.5) return "INFERRED";
  ```
- `PREPARE_FAILURES` ← src/workflow/conformance-interpreter.ts:642 [INFERRED]
  ```
  const PREPARE_FAILURES = new Set(['setup_failed', 'workspace_base', 'merge_conflict']);
  ```
- `ExpressionError` ← src/workflow/expression.ts:200 [EXTRACTED]
  ```
  if (end >= source.length) throw new ExpressionError(column, "a string is not closed with '");
  ```
- `LIMIT_FAILURES` ← src/workflow/failure-codes.ts:1 [INFERRED]
  ```
  import { LIMIT_FAILURES } from './requirements.js';
  ```
- `JUDGE_FAILURES` ← src/workflow/failure-codes.ts:8 [INFERRED]
  ```
  * `src/workflow` that is neither listed here nor a judge's (`JUDGE_FAILURES`), so a new code teamai sets on a step
  ```
- `CANCEL_FAILED` ← src/workflow/failure-codes.ts:105 [INFERRED]
  ```
  // A stop a step runtime could not confirm (the protocol's CANCEL_FAILED), which a fleet owner and a setup a teamai
  ```
- `EX_DATAERR` ← src/workflow/protocol.ts:1096 [INFERRED]
  ```
  * The status a command exits with when its input is wrong, `EX_DATAERR` of sysexits.h: running it again with the same
  ```
- `LIMIT_FAILURES` ← src/workflow/requirements.ts:222 [INFERRED]
  ```
  export const LIMIT_FAILURES = [
  ```
- `HANDED_FAILURE_MESSAGE` ← src/workflow/snapshot.ts:254 [INFERRED]
  ```
  const HANDED_FAILURE_MESSAGE = 'The details stay on the machine that ran this step.';
  ```
- `DELIVERY_FAILURE_CODES` ← src/workflow/step-state.ts:464 [INFERRED]
  ```
  const DELIVERY_FAILURE_CODES = ['delivery_failed', 'protected_path'] as const;
  ```
- `RunRemovedError` ← src/workflow/store.ts:387 [EXTRACTED]
  ```
  if (tried.held ? tried.value === 'removed' : tried.isDirectoryGone) throw new RunRemovedError(run, { wasRecorded, dataHome });
  ```
- `RunsRemovalLockTakenError` ← src/workflow/store.ts:391 [EXTRACTED]
  ```
  throw new RunsRemovalLockTakenError(run, { lock: removal, pid: await lockPid(removal) });
  ```
- `CANCEL_FAILED` ← packages/runtime-kit/src/serve.ts:4 [INFERRED]
  ```
  import { CANCEL_FAILED, OpIdSchema, RUNTIME_PROTOCOL, RUNTIME_PROTOCOL_ENV, RuntimeHandleSchema, RuntimeRequestSchema, type OpId, type RuntimeRequest } from '@teamai/runtime-protocol';
  ```
- `CANCEL_FAILED` ← packages/runtime-paseo/src/conversation.ts:5 [INFERRED]
  ```
  CANCEL_FAILED, PromptResultSchema, PromptSessionSchema, type PromptUsageSchema, RUN_DIR_ENV, WORKFLOW_DIR_ENV, type OpId, type OpState, type PromptResult, type RuntimeDisplay,
  ```
- `CANCEL_FAILED` ← packages/runtime-paseo/src/runtime.ts:5 [INFERRED]
  ```
  import { CANCEL_FAILED, type OpId, type OpState, type RuntimeFailure, type RuntimeMessage, type RuntimeRequest } from '@teamai/runtime-protocol';
  ```
- `CANCEL_FAILED` ← packages/runtime-paseo/src/sandbox.ts:1 [INFERRED]
  ```
  import { CANCEL_FAILED, type RuntimeFailure, type RuntimeRequest } from '@teamai/runtime-protocol';
  ```
- `CANCEL_FAILED` ← packages/runtime-protocol/src/protocol.ts:161 [INFERRED]
  ```
  export const CANCEL_FAILED = 'cancel_failed';
  ```
- `PROMPT_FAILURE_CODES` ← packages/runtime-protocol/src/protocol.ts:601 [INFERRED]
  ```
  export const PROMPT_FAILURE_CODES = ['model_unavailable', 'tool_unavailable', 'agent_unavailable', 'tool_failed', 'usage_limited'] as const;
  ```
- `STDERR_CHARS` ← packages/runtime-sandbox/src/bounded-tail.ts:12 [INFERRED]
  ```
  export const STDERR_CHARS = 8000;
  ```
- `CANCEL_FAILED` ← packages/runtime-sandbox/src/exec.ts:1 [INFERRED]
  ```
  import { boundedStdout, CANCEL_FAILED, EXITED_STDOUT_CHARS, type ExecRequestSchema, type OpId, type OpState, type PromptRequestSchema, type RuntimeFailure } from '@teamai/runtime-protocol';
  ```
- `CANCEL_FAILED` ← packages/runtime-sandbox/src/prompt.ts:1 [INFERRED]
  ```
  import { CANCEL_FAILED, PromptResultSchema, type ConfinedPrompt, type OpId, type PromptRequestSchema, type RuntimeFailure } from '@teamai/runtime-protocol';
  ```
- `STDERR_CHARS` ← packages/runtime-sandbox/src/step.ts:7 [INFERRED]
  ```
  import { boundedTail, STDERR_CHARS } from './bounded-tail.js';
  ```
- `CANCEL_FAILED` ← packages/runtime-t3/src/conversation.ts:4 [INFERRED]
  ```
  CANCEL_FAILED, PromptResultSchema, RUN_DIR_ENV, WORKFLOW_DIR_ENV,
  ```
- `T3Error` ← packages/runtime-t3/src/t3.ts:284 [EXTRACTED]
  ```
  if (result.isError) throw new T3Error(tool, texts.join(' ') || `T3 refused ${tool}.`, refusalIn(texts.join(' ')));
  ```
- `UnauthorizedError` ← packages/runtime-t3/src/t3.ts:413 [EXTRACTED]
  ```
  const approved: OAuthClientProvider = { ...auth, redirectToAuthorization: () => { throw new UnauthorizedError('T3 Code granted a sign-in narrower than the run needs.'); } };
  ```
- `NotRegularFileError` ← packages/shared/src/regular-file.ts:63 [EXTRACTED]
  ```
  if (!stats.isFile()) throw new NotRegularFileError(file, stats);
  ```
- `ToolUnavailableError` ← packages/tool-agy/src/session-adapter.ts:107 [EXTRACTED]
  ```
  throw new ToolUnavailableError(
  ```
- `ToolUnavailableError` ← packages/tool-copilot/src/session-adapter.ts:219 [EXTRACTED]
  ```
  throw new ToolUnavailableError('TeamAI cannot write Copilot sessions: Copilot resumes only its own event log.');
  ```
- `ToolUnavailableError` ← packages/tool-cursor/src/session-adapter.ts:497 [EXTRACTED]
  ```
  throw new ToolUnavailableError(
  ```
- `ToolUnavailableError` ← packages/tool-hermes/src/session-adapter.ts:146 [EXTRACTED]
  ```
  throw new ToolUnavailableError(
  ```
- `ToolUnavailableError` ← packages/tool-muse/src/session-adapter.ts:256 [EXTRACTED]
  ```
  throw new ToolUnavailableError('TeamAI cannot write Muse sessions: Muse resumes only its own append-only event log.');
  ```
- `ToolUnavailableError` ← packages/tool-opencode/src/session-adapter.ts:485 [EXTRACTED]
  ```
  throw new ToolUnavailableError(
  ```
- `ToolUnavailableError` ← packages/tool-pi/src/session-adapter.ts:407 [EXTRACTED]
  ```
  throw new ToolUnavailableError(`TeamAI cannot write ${this.id} sessions: ${this.id} resumes only its own JSONL session graph.`);
  ```
- `CnbRepoNotFoundError` ← src/providers/cnb/cnb-cli.ts:297 [EXTRACTED]
  ```
  throw new CnbRepoNotFoundError(repo);
  ```
- `OrganizationNotFoundError` ← src/providers/cnb/cnb-cli.ts:372 [EXTRACTED]
  ```
  throw new OrganizationNotFoundError(owner, cnbOrganizationCreateUrl());
  ```
- `RepoCreatePermissionError` ← src/providers/cnb/cnb-cli.ts:379 [EXTRACTED]
  ```
  throw new RepoCreatePermissionError(`${owner}/${repo}`, cnbRepoCreateUrl());
  ```
- `GitCodeRepoNotFoundError` ← src/providers/gitcode/gitcode-api.ts:254 [EXTRACTED]
  ```
  throw new GitCodeRepoNotFoundError(repo);
  ```
- `RepoNotFoundError` ← src/providers/github/gh-cli.ts:458 [EXTRACTED]
  ```
  throw new RepoNotFoundError(repo);
  ```
- `GitLabRepoNotFoundError` ← src/providers/gitlab/gitlab-api.ts:252 [EXTRACTED]
  ```
  throw new GitLabRepoNotFoundError(repo);
  ```
- `RepoNotFoundError` ← src/providers/tgit/gf-cli.ts:472 [EXTRACTED]
  ```
  throw new RepoNotFoundError(repo);
  ```
- `INFERRED` ← src/wiki-engine/code-knowledge/code-extractors.ts:12 [INFERRED]
  ```
  confidence: "EXTRACTED" | "INFERRED" | "AMBIGUOUS";
  ```
- `INFERRED` ← src/wiki-engine/code-knowledge/code-graph.ts:21 [INFERRED]
  ```
  confidence: fact.confidence === "EXTRACTED" ? "EXTRACTED" as const : "INFERRED" as const,
  ```
- `INFERRED` ← src/wiki-engine/core/graph-index.schema.ts:75 [INFERRED]
  ```
  ["medium", "INFERRED"],
  ```
- `INFERRED` ← src/wiki-engine/core/wiki-protocol.ts:20 [INFERRED]
  ```
  export type WikiConfidence = "EXTRACTED" | "INFERRED" | "AMBIGUOUS";
  ```
- `STDERR_KEPT` ← src/workflow/fleet/member.ts:71 [INFERRED]
  ```
  const STDERR_KEPT = 4_000;
  ```
- `CANCEL_FAILED` ← src/workflow/fleet/owner.ts:13 [INFERRED]
  ```
  import { CANCEL_FAILED, CanSchema, ISOLATION_LEVELS, RuntimeOptionsSchema, WAKE_COMMAND, WORKSPACE_MODES, type OpId, type OpState, type RuntimeFailure, type RuntimeOptions } from '@teamai/runtime-protocol';
  ```
- `CANCEL_FAILED` ← src/workflow/runtimes/attempt.ts:24 [INFERRED]
  ```
  import { CANCEL_FAILED, CanSchema, OpIdSchema, RuntimeDisplaySchema, RuntimeFailureSchema, type OpId, type OpState, type PlaceView, type RuntimeDisplay, type RuntimeFailure } from '@teamai/runtime-protocol';
  ```
- `CANCEL_FAILED` ← src/workflow/runtimes/cancelled.ts:16 [INFERRED]
  ```
  import { CANCEL_FAILED } from '@teamai/runtime-protocol';
  ```
- `CallError` ← src/workflow/runtimes/tool-caller.ts:88 [EXTRACTED]
  ```
  throw new CallError('override_invalid', `${unreadable.join(' ')} teamai cannot tell which ai.tool applies here, so no AI call runs until that is fixed.`);
  ```
- `PROMPT_FAILURE_CODES` ← src/workflow/steps/runtime-steps.ts:10 [INFERRED]
  ```
  import { PROMPT_FAILURE_CODES, type PlaceView, type PromptLease, type RuntimeFailure } from '@teamai/runtime-protocol';
  ```
- `STDERR_KEPT` ← src/workflow/steps/runtime-steps.ts:33 [INFERRED]
  ```
  const STDERR_KEPT = 64 * 1024;
  ```
- `STDERR_CHARS` ← packages/runtime-sandbox/src/providers/cli.ts:6 [INFERRED]
  ```
  import { boundedTail, STDERR_CHARS } from '../bounded-tail.js';
  ```
- `STDERR_CHARS` ← packages/runtime-sandbox/src/providers/vercel.ts:10 [INFERRED]
  ```
  import { boundedTail, STDERR_CHARS } from '../bounded-tail.js';
  ```
- `INFERRED` ← src/wiki-engine/code-knowledge/ast/call-resolver.ts:110 [INFERRED]
  ```
  return { ...site, resolvedTargetFile: importedFile, confidence: "INFERRED" };
  ```
- `INFERRED` ← src/wiki-engine/code-knowledge/ast/walk.ts:185 [INFERRED]
  ```
  confidence: "INFERRED"
  ```
- `INFERRED` ← src/wiki-engine/code-knowledge/extractors/go.ts:76 [INFERRED]
  ```
  facts.push(makeFact("config", `tag:${structTag[1]}`, file.relativePath, lineNumber, line, "INFERRED"));
  ```
- `INFERRED` ← src/wiki-engine/code-knowledge/extractors/java.ts:89 [INFERRED]
  ```
  facts.push(makeFact("config", propRef[1], file.relativePath, lineNumber, line, "INFERRED"));
  ```
- `INFERRED` ← src/wiki-engine/code-knowledge/extractors/python.ts:78 [INFERRED]
  ```
  facts.push(makeFact("config", dotenvRead[1], file.relativePath, lineNumber, line, "INFERRED"));
  ```
- `INFERRED` ← src/wiki-engine/code-knowledge/extractors/rust.ts:50 [INFERRED]
  ```
  facts.push(makeFact("component", `mod:${privateMod[1]}`, file.relativePath, lineNumber, line, "INFERRED"));
  ```
- `INFERRED` ← src/wiki-engine/code-knowledge/extractors/scala.ts:110 [INFERRED]
  ```
  facts.push(makeFact("error", typeName, file.relativePath, lineNumber, line, "INFERRED"));
  ```
- `INFERRED` ← src/wiki-engine/code-knowledge/extractors/swift.ts:69 [INFERRED]
  ```
  facts.push(makeFact("error", typeDecl[2], file.relativePath, lineNumber, line, "INFERRED"));
  ```
- `INFERRED` ← src/wiki-engine/code-knowledge/extractors/typescript.ts:41 [INFERRED]
  ```
  facts.push(makeFact("component", exportDefault[1], file.relativePath, lineNumber, line, "INFERRED"));
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
- `KNOWN_FAILURE_CODES` ← oxlint-plugin-teamai/rules/workflow-failure-codes.js:3 [INFERRED]
  ```
  import { KNOWN_FAILURE_CODES, PROTOCOL_STRING_CONSTANTS } from '../failure-codes.js';
  ```
- `SystemExit` ← .github/scripts/erosion-summary.py:147 [INFERRED]
  ```
  raise SystemExit(main())
  ```