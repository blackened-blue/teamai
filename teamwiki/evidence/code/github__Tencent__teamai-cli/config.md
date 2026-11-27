---
title: github__Tencent__teamai-cli config
domain: code-knowledge
source:
  - src/index.ts
  - src/utils/cache-index.ts
  - src/providers/git/index.ts
  - src/providers/gitcode/index.ts
  - packages/tool-claude/src/testing/index.ts
  - packages/tool-codex/src/testing/index.ts
  - src/wiki-engine/code-knowledge/ast/index.ts
  - scripts/command-table.ts
  - scripts/update-model-prices.ts
  - src/api-key.ts
  - src/autocompact-reconcile.ts
  - src/bridged-team-hooks.ts
  - src/bundled-runtime.ts
  - src/config.ts
  - src/doctor-delivery.ts
  - src/doctor.ts
  - src/dsh-hooks.ts
  - src/env-reserved.ts
  - src/git-exclude.ts
  - src/git-hook.ts
  - src/hook-dispatch-cli.ts
  - src/hook-fast-path.ts
  - src/hook-handlers.ts
  - src/hooks.ts
  - src/install-prefix.ts
  - src/installations.ts
  - src/launch-context.ts
---

# Config

- `process.env.TEAMAI_COMMAND_TABLE_ONLY` ← src/index.ts:2711 [EXTRACTED]
  ```
  if (!process.env.TEAMAI_COMMAND_TABLE_ONLY) {
  ```
- `process.env.TEAMAI_DRY_RUN` ← src/index.ts:2720 [EXTRACTED]
  ```
  if (args.includes('--dry-run')) process.env.TEAMAI_DRY_RUN = '1';
  ```
- `process.env.TEAMAI_CACHE_DIR` ← src/utils/cache-index.ts:97 [EXTRACTED]
  ```
  return process.env.TEAMAI_CACHE_DIR ?? path.join(getUserHome(), '.teamai', 'cache', 'repos');
  ```
- `process.env.TEAMAI_CACHE_MAX_BYTES` ← src/utils/cache-index.ts:311 [EXTRACTED]
  ```
  const envVal = process.env.TEAMAI_CACHE_MAX_BYTES;
  ```
- `process.env.GIT_AUTHOR_NAME` ← src/providers/git/index.ts:50 [EXTRACTED]
  ```
  for (const candidate of [configured, process.env.GIT_AUTHOR_NAME ?? '', osUsername]) {
  ```
- `process.env.GITCODE_TOKEN` ← src/providers/gitcode/index.ts:81 [EXTRACTED]
  ```
  process.env.GITCODE_TOKEN = token;
  ```
- `process.env.CLAUDE_CONFIG_DIR` ← packages/tool-claude/src/testing/index.ts:38 [EXTRACTED]
  ```
  const project = path.join(process.env.CLAUDE_CONFIG_DIR || path.join(process.env.HOME || '', '.claude'), 'projects', dir);
  ```
- `process.env.CODEX_HOME` ← packages/tool-codex/src/testing/index.ts:38 [EXTRACTED]
  ```
  const sessions = path.join(process.env.CODEX_HOME || path.join(process.env.HOME || '', '.codex'), 'sessions');
  ```
- `process.env.TEAMAI_WORKFLOW_RESULT` ← packages/tool-codex/src/testing/index.ts:46 [EXTRACTED]
  ```
  const result = process.env.TEAMAI_WORKFLOW_RESULT;
  ```
- `process.env.TMPDIR` ← packages/tool-codex/src/testing/index.ts:54 [EXTRACTED]
  ```
  const writable = [cwd, excludes('exclude_slash_tmp') ? undefined : '/tmp', excludes('exclude_tmpdir_env_var') ? undefined : process.env.TMPDIR, ...args.flatMap((arg, index) => args[index - 1] === '--add-dir' ? [arg] : [])]
  ```
- `process.env.TEAMAI_SKIP_AST` ← src/wiki-engine/code-knowledge/ast/index.ts:20 [EXTRACTED]
  ```
  if (process.env.TEAMAI_SKIP_AST === "1") {
  ```
- `process.env.TEAMAI_COMMAND_TABLE_ONLY` ← scripts/command-table.ts:3 [EXTRACTED]
  ```
  const previous = process.env.TEAMAI_COMMAND_TABLE_ONLY;
  ```
- `process.env.GITHUB_TOKEN` ← scripts/update-model-prices.ts:25 [EXTRACTED]
  ```
  if (process.env.GITHUB_TOKEN) headers.set('authorization', `Bearer ${process.env.GITHUB_TOKEN}`);
  ```
- `process.env.TEAMAI_API_TOKEN` ← src/api-key.ts:31 [EXTRACTED]
  ```
  const fromEnv = process.env.TEAMAI_API_TOKEN || process.env.TEAMAI_API_KEY;
  ```
- `process.env.CLAUDE_CODE_AUTO_COMPACT_WINDOW` ← src/autocompact-reconcile.ts:191 [EXTRACTED]
  ```
  if (process.env.CLAUDE_CODE_AUTO_COMPACT_WINDOW || env?.CLAUDE_CODE_AUTO_COMPACT_WINDOW !== undefined) {
  ```
- `process.env.CODEBUDDY_AUTO_COMPACT_WINDOW` ← src/autocompact-reconcile.ts:255 [EXTRACTED]
  ```
  if (process.env.CODEBUDDY_AUTO_COMPACT_WINDOW) {
  ```
- `process.env.TERMINAL_CWD` ← src/bridged-team-hooks.ts:203 [EXTRACTED]
  ```
  if (process.env.TERMINAL_CWD) payload.cwd = process.env.TERMINAL_CWD;
  ```
- `process.env.WORKBUDDY_CONFIG_DIR` ← src/bundled-runtime.ts:66 [EXTRACTED]
  ```
  const roots = [process.env.WORKBUDDY_CONFIG_DIR, path.join(home, '.workbuddy'), path.join(home, '.workbuddy-ai')];
  ```
- `process.env.PATH` ← src/bundled-runtime.ts:298 [EXTRACTED]
  ```
  process.env.PATH = [...prepend, ...entries, ...append].join(path.delimiter);
  ```
- `BROKEN_CONFIG_ADVICE` ← src/config.ts:840 [EXTRACTED]
  ```
  export const BROKEN_CONFIG_ADVICE = 'Fix the file, or move it aside and run `teamai init` to write a new one.';
  ```
- `process.env.SHELL` ← src/doctor-delivery.ts:2446 [EXTRACTED]
  ```
  const shell = process.env.SHELL ?? '';
  ```
- `process.env.PI_CODING_AGENT_DIR` ← src/doctor.ts:411 [EXTRACTED]
  ```
  const piHome = process.env.PI_CODING_AGENT_DIR?.trim();
  ```
- `DSH_HOOK_CONFIG_FILE` ← src/dsh-hooks.ts:20 [EXTRACTED]
  ```
  export const DSH_HOOK_CONFIG_FILE = 'hooks.json';
  ```
- `process.env.DSH_PERMISSION_MODE` ← src/dsh-hooks.ts:130 [EXTRACTED]
  ```
  if (process.env.DSH_PERMISSION_MODE === 'danger-full-access') return null;
  ```
- `TEAM_ENV_RESERVED_NAMES` ← src/env-reserved.ts:17 [EXTRACTED]
  ```
  export const TEAM_ENV_RESERVED_NAMES = [
  ```
- `process.env.XDG_CONFIG_HOME` ← src/git-exclude.ts:456 [EXTRACTED]
  ```
  ? path.join(process.env.XDG_CONFIG_HOME || path.join(getUserHome(), '.config'), 'git', 'ignore')
  ```
- `process.env.PATH` ← src/git-hook.ts:131 [EXTRACTED]
  ```
  let version = gitVersions.get(process.env.PATH);
  ```
- `process.env.COPILOT_PROJECT_DIR` ← src/hook-dispatch-cli.ts:596 [EXTRACTED]
  ```
  const copilotProject = process.env.COPILOT_PROJECT_DIR?.trim();
  ```
- `LAUNCHED_BY_ENV` ← src/hook-fast-path.ts:28 [EXTRACTED]
  ```
  export const LAUNCHED_BY_ENV = 'TEAMAI_LAUNCHED_BY';
  ```
- `ATTEMPT_ENV` ← src/hook-fast-path.ts:32 [EXTRACTED]
  ```
  export const ATTEMPT_ENV = 'TEAMAI_WORKFLOW_ATTEMPT';
  ```
- `HTTP_ENDPOINT_ENVS` ← src/hook-fast-path.ts:43 [EXTRACTED]
  ```
  export const HTTP_ENDPOINT_ENVS = ['TEAMAI_HTTP_ENDPOINT', 'TEAMAI_ENDPOINT', 'TEAMAI_API_BASE_URL'] as const;
  ```
- `LOGIN_DEFERRED_ENV` ← src/hook-fast-path.ts:50 [EXTRACTED]
  ```
  export const LOGIN_DEFERRED_ENV = 'TEAMAI_HOOK_LOGIN';
  ```
- `process.env.GIT_REFLOG_ACTION` ← src/hook-handlers.ts:372 [EXTRACTED]
  ```
  if (!await isRebaseFastForward(args, process.env.GIT_REFLOG_ACTION, cwd)) return null;
  ```
- `process.env.TEAMAI_ADOPTION_EVAL_LOG` ← src/hook-handlers.ts:833 [EXTRACTED]
  ```
  if (process.env.TEAMAI_ADOPTION_EVAL_LOG) {
  ```
- `process.env.COPILOT_PROJECT_DIR` ← src/hooks.ts:2556 [EXTRACTED]
  ```
  const project = projectConfig && (process.env.COPILOT_PROJECT_DIR?.trim()
  ```
- `process.env.VOLTA_HOME` ← src/install-prefix.ts:50 [EXTRACTED]
  ```
  export function isVoltaPackageImage(filePath: string, voltaHome = process.env.VOLTA_HOME): boolean {
  ```
- `process.env.TEAMAI_DRY_RUN` ← src/installations.ts:138 [EXTRACTED]
  ```
  if (process.env.TEAMAI_DRY_RUN === '1') return null;
  ```
- `RUN_MODE_ENV` ← src/launch-context.ts:27 [EXTRACTED]
  ```
  export const RUN_MODE_ENV = 'TEAMAI_MODE';
  ```
- `ATTEMPT_ENV` ← src/launch-context.ts:81 [EXTRACTED]
  ```
  export const ATTEMPT_ENV = 'TEAMAI_WORKFLOW_ATTEMPT';
  ```
- `STEP_COMMAND_ENV` ← src/launch-context.ts:97 [EXTRACTED]
  ```
  export const STEP_COMMAND_ENV = 'TEAMAI_WORKFLOW_STEP_COMMAND';
  ```
- `EPHEMERAL_CONFIG_ENV` ← src/launch-context.ts:106 [EXTRACTED]
  ```
  export const EPHEMERAL_CONFIG_ENV = 'TEAMAI_EPHEMERAL_CONFIG';
  ```
- `LAUNCHED_BY_ENV` ← src/launch-context.ts:109 [EXTRACTED]
  ```
  export const LAUNCHED_BY_ENV = 'TEAMAI_LAUNCHED_BY';
  ```