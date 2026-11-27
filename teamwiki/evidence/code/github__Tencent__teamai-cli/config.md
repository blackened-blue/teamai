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
  - src/member-settings-report.ts
  - src/mr-hint.ts
  - src/pull.ts
  - src/recall-provenance.ts
  - src/recall-toggle.ts
  - src/recall.ts
  - src/skill-command.ts
  - src/todowrite-hint.ts
  - src/types.ts
  - src/update.ts
  - scripts/verify/world.ts
  - src/models/switch.ts
  - src/pkg/pkg-hint.ts
  - src/providers/registry.ts
  - src/resources/env-loader.ts
  - src/utils/git-discovery.ts
  - src/utils/git-env.ts
  - src/utils/git-ref-files.ts
  - src/utils/git.ts
  - src/utils/repo-cache.ts
  - src/utils/session-id.ts
  - src/utils/shell-profile.ts
  - src/workflow/member-tools.ts
  - src/workflow/requirements.ts
  - packages/runtime-paseo/src/providers.ts
  - packages/runtime-protocol/src/protocol.ts
  - packages/runtime-tools/src/confined.ts
  - packages/shared/src/exec.ts
  - packages/shared/src/home.ts
  - packages/shared/src/log.ts
  - packages/shared/src/lookpath.ts
  - packages/shared/src/redact.ts
  - packages/tool-codebuddy/src/ide-history.ts
  - packages/tool-codex/src/codex-desktop.ts
  - packages/tool-cursor/src/cursor-store.ts
  - packages/tool-muse/src/muse-session.ts
  - packages/tool-pi/src/sessions.ts
  - packages/tool-testing/src/conformance.ts
  - src/providers/cnb/cnb-cli.ts
  - src/providers/gitcode/gitcode-api.ts
  - src/providers/github/gh-cli.ts
  - src/providers/gitlab/gitlab-api.ts
  - src/providers/gitlab/mr-fetch.ts
  - src/providers/gitlab/repo-url.ts
  - src/workflow/conformance/delivery.ts
  - src/workflow/fleet/guardian-mode.ts
  - src/workflow/runtimes/sandbox-profiles.ts
  - packages/runtime-paseo/src/daemon/connect.ts
  - packages/runtime-paseo/src/testing/attempt-socket.ts
  - packages/runtime-sandbox/src/providers/vercel.ts
  - packages/runtime-sandbox/src/testing/this-machine.ts
  - packages/runtime-sandbox/src/testing/vercel-fake-sdk.ts
  - packages/runtime-t3/src/testing/harness.ts
  - packages/tool-codex/src/testing/fake-codex.ts
  - packages/tool-core/src/sessions/sqlite.ts
  - packages/tool-opencode/src/testing/fake-opencode.ts
  - oxlint-plugin-teamai/rules/home-env.js
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
- `process.env.TEAMAI_AI_TOOL` ← src/member-settings-report.ts:349 [EXTRACTED]
  ```
  if (key === 'ai.tool' && process.env.TEAMAI_AI_TOOL) levels.push(settingSource('environment', process.env.TEAMAI_AI_TOOL, undefined, 'TEAMAI_AI_TOOL'));
  ```
- `process.env.TEAMAI_RECALL_DISABLED` ← src/member-settings-report.ts:351 [EXTRACTED]
  ```
  if (key === 'recallEnabled' && process.env.TEAMAI_RECALL_DISABLED === '1') levels.push(settingSource('environment', false, undefined, 'TEAMAI_RECALL_DISABLED'));
  ```
- `process.env.TEAMAI_CONTRIBUTE_HINT_DISABLED` ← src/member-settings-report.ts:353 [EXTRACTED]
  ```
  if (key === 'contributeHintEnabled' && process.env.TEAMAI_CONTRIBUTE_HINT_DISABLED === '1') levels.push(settingSource('environment', false, undefined, 'TEAMAI_CONTRIBUTE_HINT_DISABLED'));
  ```
- `process.env.TEAMAI_MR_HINT_DISABLED` ← src/member-settings-report.ts:355 [EXTRACTED]
  ```
  if (key === 'mrHintEnabled' && process.env.TEAMAI_MR_HINT_DISABLED === '1') levels.push(settingSource('environment', false, undefined, 'TEAMAI_MR_HINT_DISABLED'));
  ```
- `process.env.TEAMAI_MR_HINT_DISABLED` ← src/mr-hint.ts:466 [EXTRACTED]
  ```
  return process.env.TEAMAI_MR_HINT_DISABLED !== '1' && await mrHintAllowed(localConfig);
  ```
- `process.env.TEAMAI_MR_HINT_CWD` ← src/mr-hint.ts:496 [EXTRACTED]
  ```
  const rawCwd = process.env.TEAMAI_MR_HINT_CWD ?? process.cwd();
  ```
- `process.env.TEAMAI_GIT_HOOK` ← src/pull.ts:3803 [EXTRACTED]
  ```
  const hookEnv = process.env.TEAMAI_GIT_HOOK;
  ```
- `process.env.TEAMAI_PREPARE_CHECKOUT` ← src/pull.ts:3804 [EXTRACTED]
  ```
  const prepareEnv = process.env.TEAMAI_PREPARE_CHECKOUT;
  ```
- `RECALL_TRACE_ENV` ← src/recall-provenance.ts:26 [EXTRACTED]
  ```
  export const RECALL_TRACE_ENV = 'TEAMAI_BENCHMARK_RECALL_TRACE';
  ```
- `process.env.TEAMAI_RECALL_DISABLED` ← src/recall-toggle.ts:213 [EXTRACTED]
  ```
  if (process.env.TEAMAI_RECALL_DISABLED === '1') {
  ```
- `process.env.TEAMAI_RECALL_DISABLED` ← src/recall.ts:1533 [EXTRACTED]
  ```
  if (process.env.TEAMAI_RECALL_DISABLED !== '1' && !options.dryRun) {
  ```
- `process.env.TEAMAI_SKILL_DOWNLOAD_HOSTS` ← src/skill-command.ts:42 [EXTRACTED]
  ```
  const raw = process.env.TEAMAI_SKILL_DOWNLOAD_HOSTS;
  ```
- `process.env.TEAMAI_RECALL_DISABLED` ← src/todowrite-hint.ts:139 [EXTRACTED]
  ```
  if (process.env.TEAMAI_RECALL_DISABLED === '1') return;
  ```
- `LOCAL_CONFIG_INSTALL_KEYS` ← src/types.ts:1109 [EXTRACTED]
  ```
  export const LOCAL_CONFIG_INSTALL_KEYS = [
  ```
- `TEAMAI_ENV_START` ← src/types.ts:2064 [EXTRACTED]
  ```
  export const TEAMAI_ENV_START = '# [teamai:env:start]';
  ```
- `TEAMAI_ENV_END` ← src/types.ts:2065 [EXTRACTED]
  ```
  export const TEAMAI_ENV_END = '# [teamai:env:end]';
  ```
- `DASHBOARD_DEFAULT_PORT` ← src/types.ts:2467 [EXTRACTED]
  ```
  export const DASHBOARD_DEFAULT_PORT = 3721;
  ```
- `CURSOR_CONFIG_TOOL_ID` ← src/types.ts:3047 [EXTRACTED]
  ```
  export const CURSOR_CONFIG_TOOL_ID = 'cursor-config';
  ```
- `process.env.XDG_CONFIG_HOME` ← src/types.ts:3270 [EXTRACTED]
  ```
  const xdg = process.env.XDG_CONFIG_HOME?.trim();
  ```
- `process.env.TEAMAI_HOOKS_DISABLED` ← src/types.ts:4221 [EXTRACTED]
  ```
  return process.env.TEAMAI_HOOKS_DISABLED === '1' || process.env.TEAMAI_HOOKS_DISABLED === 'true';
  ```
- `process.env.TEAMAI_NPM_REGISTRY` ← src/update.ts:65 [EXTRACTED]
  ```
  const override = process.env.TEAMAI_NPM_REGISTRY?.trim();
  ```
- `process.env.PATH` ← scripts/verify/world.ts:255 [EXTRACTED]
  ```
  const PATH = (process.env.PATH ?? '').split(':').filter((dir) => !dir.endsWith(`${path.sep}node_modules${path.sep}.bin`)).join(':');
  ```
- `process.env.LANG` ← scripts/verify/world.ts:330 [EXTRACTED]
  ```
  LANG: process.env.LANG ?? 'C.UTF-8',
  ```
- `process.env.TERM` ← scripts/verify/world.ts:331 [EXTRACTED]
  ```
  TERM: process.env.TERM ?? 'dumb',
  ```
- `process.env.OPENCODE_CONFIG` ← src/models/switch.ts:141 [EXTRACTED]
  ```
  const custom = process.env.OPENCODE_CONFIG?.trim();
  ```
- `process.env.TEAMAI_PACKAGE_HINT_DISABLED` ← src/pkg/pkg-hint.ts:85 [EXTRACTED]
  ```
  if (process.env.TEAMAI_PACKAGE_HINT_DISABLED === '1') return null;
  ```
- `process.env.TEAMAI_DEFAULT_PROVIDER` ← src/providers/registry.ts:54 [EXTRACTED]
  ```
  const override = process.env.TEAMAI_DEFAULT_PROVIDER?.trim();
  ```
- `process.env.TEAMAI_GITLAB_HOST` ← src/providers/registry.ts:181 [EXTRACTED]
  ```
  const override = process.env.TEAMAI_GITLAB_HOST?.trim().toLowerCase();
  ```
- `process.env.GITLAB_URL` ← src/providers/registry.ts:185 [EXTRACTED]
  ```
  const gitlabUrl = process.env.GITLAB_URL?.trim();
  ```
- `process.env.SHELL` ← src/resources/env-loader.ts:545 [EXTRACTED]
  ```
  export async function directoryEnv(localConfig: LocalConfig, dir: string, shell = process.env.SHELL ?? ''): Promise<DirectoryEnv> {
  ```
- `process.env.GIT_DIR` ← src/utils/git-discovery.ts:43 [EXTRACTED]
  ```
  if (process.env.GIT_DIR || process.env.GIT_WORK_TREE || process.env.GIT_COMMON_DIR) return false;
  ```
- `process.env.GIT_CEILING_DIRECTORIES` ← src/utils/git-discovery.ts:101 [EXTRACTED]
  ```
  const search = [process.env.GIT_CEILING_DIRECTORIES, process.env.GIT_DISCOVERY_ACROSS_FILESYSTEM];
  ```
- `NON_INTERACTIVE_GIT_ENV` ← src/utils/git-env.ts:30 [EXTRACTED]
  ```
  export const NON_INTERACTIVE_GIT_ENV = {
  ```
- `GIT_REPOSITORY_ENV` ← src/utils/git-env.ts:58 [EXTRACTED]
  ```
  export const GIT_REPOSITORY_ENV = [
  ```
- `process.env.GIT_DIR` ← src/utils/git-ref-files.ts:25 [EXTRACTED]
  ```
  if (process.env.GIT_DIR || process.env.GIT_COMMON_DIR || process.env.GIT_CEILING_DIRECTORIES) return null;
  ```
- `process.env.PATH` ← src/utils/git.ts:48 [EXTRACTED]
  ```
  const pathEnv = options.pathEnv ?? process.env.PATH ?? '';
  ```
- `process.env.TEAMAI_INIT_PUSH_TIMEOUT_MS` ← src/utils/git.ts:189 [EXTRACTED]
  ```
  const raw = process.env.TEAMAI_INIT_PUSH_TIMEOUT_MS;
  ```
- `process.env.TEAMAI_CACHE_DIR` ← src/utils/repo-cache.ts:19 [EXTRACTED]
  ```
  return process.env.TEAMAI_CACHE_DIR ?? path.join(getUserHome(), '.teamai', 'cache', 'repos');
  ```
- `AGENT_SESSION_ENV` ← src/utils/session-id.ts:23 [EXTRACTED]
  ```
  export const AGENT_SESSION_ENV = [
  ```
- `process.env.CLAUDE_SESSION_ID` ← src/utils/session-id.ts:158 [EXTRACTED]
  ```
  if (process.env.CLAUDE_SESSION_ID) {
  ```
- `process.env.SHELL` ← src/utils/shell-profile.ts:43 [EXTRACTED]
  ```
  shell: string = process.env.SHELL ?? '',
  ```
- `process.env.ZDOTDIR` ← src/utils/shell-profile.ts:52 [EXTRACTED]
  ```
  return path.join(process.env.ZDOTDIR || home, '.zshenv');
  ```
- `process.env.TEAMAI_AI_TOOL` ← src/workflow/member-tools.ts:22 [EXTRACTED]
  ```
  const env = process.env.TEAMAI_AI_TOOL;
  ```
- `SANDBOX_WITHHELD_ENV` ← src/workflow/requirements.ts:95 [EXTRACTED]
  ```
  export const SANDBOX_WITHHELD_ENV = [
  ```
- `DRIVER_ENV_REACH` ← src/workflow/requirements.ts:192 [EXTRACTED]
  ```
  export const DRIVER_ENV_REACH = [false, 'commands', true, 'member'] as const satisfies ReadonlyArray<Can['env'] | 'member'>;
  ```
- `process.env.PASEO_HOME` ← packages/runtime-paseo/src/providers.ts:214 [EXTRACTED]
  ```
  const homeFlag = process.env.PASEO_HOME ? ` --home ${paseoDir}` : '';
  ```
- `RUNTIME_PROTOCOL_ENV` ← packages/runtime-protocol/src/protocol.ts:92 [EXTRACTED]
  ```
  export const RUNTIME_PROTOCOL_ENV = 'TEAMAI_RUNTIME_PROTOCOL';
  ```
- `RUN_DIR_ENV` ← packages/runtime-protocol/src/protocol.ts:114 [EXTRACTED]
  ```
  export const RUN_DIR_ENV = 'TEAMAI_RUN_DIR';
  ```
- `WORKFLOW_DIR_ENV` ← packages/runtime-protocol/src/protocol.ts:120 [EXTRACTED]
  ```
  export const WORKFLOW_DIR_ENV = 'TEAMAI_WORKFLOW_DIR';
  ```
- `process.env.OPENCODE_CONFIG` ← packages/runtime-tools/src/confined.ts:194 [EXTRACTED]
  ```
  const text = await optionalFile(process.env.OPENCODE_CONFIG || path.join(request.home, 'opencode.json'));
  ```
- `process.env.PATH` ← packages/shared/src/exec.ts:264 [EXTRACTED]
  ```
  const pathEnv = env?.PATH ?? env?.Path ?? process.env.PATH;
  ```
- `process.env.HOME` ← packages/shared/src/home.ts:63 [EXTRACTED]
  ```
  const home = process.env.HOME?.trim()
  ```
- `process.env.USERPROFILE` ← packages/shared/src/home.ts:64 [EXTRACTED]
  ```
  || process.env.USERPROFILE?.trim()
  ```
- `PROGRESS_STREAMS_ENV` ← packages/shared/src/log.ts:40 [EXTRACTED]
  ```
  export const PROGRESS_STREAMS_ENV = 'TEAMAI_PROGRESS_STREAMS';
  ```
- `process.env.PATH` ← packages/shared/src/lookpath.ts:14 [EXTRACTED]
  ```
  /** PATH-equivalent string. Defaults to `process.env.PATH`. */
  ```
- `process.env.PATHEXT` ← packages/shared/src/lookpath.ts:16 [EXTRACTED]
  ```
  /** PATHEXT-equivalent string. Defaults to `process.env.PATHEXT`. */
  ```
- `MIN_ENV_VALUE_LENGTH` ← packages/shared/src/redact.ts:62 [EXTRACTED]
  ```
  export const MIN_ENV_VALUE_LENGTH = 8;
  ```
- `process.env.TEAMAI_CODEBUDDY_IDE_DATA` ← packages/tool-codebuddy/src/ide-history.ts:159 [EXTRACTED]
  ```
  const override = process.env.TEAMAI_CODEBUDDY_IDE_DATA?.trim();
  ```
- `process.env.APPDATA` ← packages/tool-codebuddy/src/ide-history.ts:169 [EXTRACTED]
  ```
  process.env.APPDATA ?? path.join(home, 'AppData', 'Roaming'),
  ```
- `process.env.XDG_CONFIG_HOME` ← packages/tool-codebuddy/src/ide-history.ts:175 [EXTRACTED]
  ```
  process.env.XDG_CONFIG_HOME ?? path.join(home, '.config'),
  ```
- `process.env.LOCALAPPDATA` ← packages/tool-codex/src/codex-desktop.ts:19 [EXTRACTED]
  ```
  const localAppData = process.env.LOCALAPPDATA;
  ```
- `process.env.XDG_CONFIG_HOME` ← packages/tool-cursor/src/cursor-store.ts:49 [EXTRACTED]
  ```
  return path.join(process.env.XDG_CONFIG_HOME?.trim() || path.join(home, '.config'), 'Cursor');
  ```
- `process.env.XDG_DATA_HOME` ← packages/tool-muse/src/muse-session.ts:20 [EXTRACTED]
  ```
  const dataHome = process.env.XDG_DATA_HOME?.trim() || path.join(getUserHome(), '.local', 'share');
  ```
- `process.env.PI_CODING_AGENT_SESSION_DIR` ← packages/tool-pi/src/sessions.ts:10 [EXTRACTED]
  ```
  adapter: (storeDir): AgentAdapter => new PiAdapter('pi', storeDir, !process.env.PI_CODING_AGENT_SESSION_DIR),
  ```
- `process.env.PATH` ← packages/tool-testing/src/conformance.ts:259 [EXTRACTED]
  ```
  vi.stubEnv('PATH', `${dir}${path.delimiter}${process.env.PATH ?? ''}`);
  ```
- `process.env.TEAMAI_CNB_HOST` ← src/providers/cnb/cnb-cli.ts:40 [EXTRACTED]
  ```
  export const CNB_HOST = process.env.TEAMAI_CNB_HOST?.trim() || 'cnb.cool';
  ```
- `process.env.CNB_TOKEN` ← src/providers/cnb/cnb-cli.ts:150 [EXTRACTED]
  ```
  return process.env.CNB_TOKEN ?? process.env.CNB_ACCESS_TOKEN ?? null;
  ```
- `process.env.CNB_USERNAME` ← src/providers/cnb/cnb-cli.ts:185 [EXTRACTED]
  ```
  return process.env.CNB_USERNAME?.trim() || null;
  ```
- `process.env.GITCODE_TOKEN` ← src/providers/gitcode/gitcode-api.ts:44 [EXTRACTED]
  ```
  for (const raw of [process.env.GITCODE_TOKEN, process.env.GC_TOKEN]) {
  ```
- `process.env.GITHUB_TOKEN` ← src/providers/github/gh-cli.ts:162 [EXTRACTED]
  ```
  return process.env.GITHUB_TOKEN ?? process.env.GH_TOKEN ?? null;
  ```
- `process.env.GITLAB_API_PREFIX` ← src/providers/gitlab/gitlab-api.ts:44 [EXTRACTED]
  ```
  const prefix = process.env.GITLAB_API_PREFIX?.trim().replace(/^\/+|\/+$/g, '') || 'api/v4';
  ```
- `process.env.GITLAB_URL` ← src/providers/gitlab/gitlab-api.ts:50 [EXTRACTED]
  ```
  const gitlabUrl = process.env.GITLAB_URL?.trim();
  ```
- `process.env.TEAMAI_GITLAB_HOST` ← src/providers/gitlab/gitlab-api.ts:84 [EXTRACTED]
  ```
  const override = process.env.TEAMAI_GITLAB_HOST?.trim().toLowerCase();
  ```
- `process.env.GITLAB_TOKEN` ← src/providers/gitlab/gitlab-api.ts:100 [EXTRACTED]
  ```
  process.env.GITLAB_TOKEN,
  ```
- `process.env.GITLAB_PRIVATE_TOKEN` ← src/providers/gitlab/gitlab-api.ts:101 [EXTRACTED]
  ```
  process.env.GITLAB_PRIVATE_TOKEN,
  ```
- `process.env.GITLAB_PAT` ← src/providers/gitlab/gitlab-api.ts:102 [EXTRACTED]
  ```
  process.env.GITLAB_PAT,
  ```
- `process.env.GITLAB_API_PREFIX` ← src/providers/gitlab/mr-fetch.ts:75 [EXTRACTED]
  ```
  const apiPrefix = process.env.GITLAB_API_PREFIX?.trim().replace(/^\/+|\/+$/g, '') || 'api/v4';
  ```
- `process.env.TEAMAI_GITLAB_HOST` ← src/providers/gitlab/repo-url.ts:15 [EXTRACTED]
  ```
  const direct = process.env.TEAMAI_GITLAB_HOST?.trim();
  ```
- `process.env.GITLAB_URL` ← src/providers/gitlab/repo-url.ts:19 [EXTRACTED]
  ```
  const gitlabUrl = process.env.GITLAB_URL?.trim();
  ```
- `process.env.SHIP_OPEN` ← src/workflow/conformance/delivery.ts:44 [EXTRACTED]
  ```
  command: node -e "require('fs').copyFileSync(process.env.SHIP_OPEN, process.env.SHIP_SAW)"
  ```
- `process.env.FIX_CI_PATCH` ← src/workflow/conformance/delivery.ts:117 [EXTRACTED]
  ```
  command: node -e "if (process.env.FIX_CI_PATCH) require('fs').writeFileSync('fix.txt', 'F')"
  ```
- `FLEET_GUARDIAN_ENV` ← src/workflow/fleet/guardian-mode.ts:6 [EXTRACTED]
  ```
  export const FLEET_GUARDIAN_ENV = 'TEAMAI_FLEET_GUARDIAN';
  ```
- `PROFILE_OPTION` ← src/workflow/runtimes/sandbox-profiles.ts:34 [EXTRACTED]
  ```
  export const PROFILE_OPTION = 'profile';
  ```
- `process.env.CODEX_HOME` ← packages/runtime-paseo/src/daemon/connect.ts:137 [EXTRACTED]
  ```
  const moved = homeDir === '.codex' ? process.env.CODEX_HOME : undefined;
  ```
- `process.env.XDG_DATA_HOME` ← packages/runtime-paseo/src/daemon/connect.ts:183 [EXTRACTED]
  ```
  const homes = [providerHome, process.env.XDG_DATA_HOME, path.join(getUserHome(), '.local', 'share')];
  ```
- `process.env.PASEO_AGENT_ID` ← packages/runtime-paseo/src/testing/attempt-socket.ts:127 [EXTRACTED]
  ```
  client.on('connect', () => client.write(JSON.stringify({ ask: { tool: ${JSON.stringify(tool)}, agent: process.env.PASEO_AGENT_ID || null, cwd: process.env.PASEO_AGENT_CWD || process.cwd() } }) + '\\n'));
  ```
- `process.env.VERCEL_OIDC_TOKEN` ← packages/runtime-sandbox/src/providers/vercel.ts:111 [EXTRACTED]
  ```
  process.env.VERCEL_OIDC_TOKEN = oidc;
  ```
- `process.env.SANDBOX_TEST_SYSTEM_BIN` ← packages/runtime-sandbox/src/testing/this-machine.ts:6 [EXTRACTED]
  ```
  export const SYSTEM_BIN = process.env.SANDBOX_TEST_SYSTEM_BIN || '/usr/bin';
  ```
- `process.env.SANDBOX_TEST_PLATFORM` ← packages/runtime-sandbox/src/testing/this-machine.ts:8 [EXTRACTED]
  ```
  export const PLATFORM: NodeJS.Platform = z.enum(['aix', 'android', 'darwin', 'freebsd', 'haiku', 'linux', 'openbsd', 'sunos', 'win32', 'cygwin', 'netbsd']).catch(process.platform).parse(process.env.SANDBOX_TEST_PLATFORM);
  ```
- `process.env.SANDBOX_TEST_OS_RELEASE` ← packages/runtime-sandbox/src/testing/this-machine.ts:10 [EXTRACTED]
  ```
  export const OS_RELEASE = process.env.SANDBOX_TEST_OS_RELEASE ? [process.env.SANDBOX_TEST_OS_RELEASE] : ['/etc/os-release', '/usr/lib/os-release'];
  ```
- `process.env.FAKE_VERCEL_STATE` ← packages/runtime-sandbox/src/testing/vercel-fake-sdk.ts:30 [EXTRACTED]
  ```
  const state = process.env.FAKE_VERCEL_STATE ?? '/nonexistent';
  ```
- `process.env.FAKE_VERCEL_IMAGE` ← packages/runtime-sandbox/src/testing/vercel-fake-sdk.ts:31 [EXTRACTED]
  ```
  const image = process.env.FAKE_VERCEL_IMAGE ?? '/nonexistent';
  ```
- `process.env.VERCEL_OIDC_TOKEN` ← packages/runtime-sandbox/src/testing/vercel-fake-sdk.ts:139 [EXTRACTED]
  ```
  log('create', { name, persistent: params.persistent, timeout: params.timeout, runtime: params.runtime, source: params.source, tags: params.tags, auth: ['token', 'teamId', 'projectId'].filter((key) => key in params), oidc: process.env.VERCEL_OIDC_TOKEN !== undefined });
  ```
- `process.env.T3CODE_HOME` ← packages/runtime-t3/src/testing/harness.ts:353 [EXTRACTED]
  ```
  const base = values('--base-dir')[0] ?? process.env.T3CODE_HOME ?? path.join(process.env.HOME, '.t3');
  ```
- `process.env.CODEX_HOME` ← packages/tool-codex/src/testing/fake-codex.ts:27 [EXTRACTED]
  ```
  require('node:fs').mkdirSync(require('node:path').join(process.env.CODEX_HOME || require('node:path').join(require('node:os').homedir(), '.codex'), 'tmp', 'arg0', 'codex-arg0fake'), { recursive: true });
  ```
- `process.env.PATH` ← packages/tool-codex/src/testing/fake-codex.ts:142 [EXTRACTED]
  ```
  return (process.env.PATH ?? '').split(path.delimiter)
  ```
- `process.env.PATH` ← packages/tool-core/src/sessions/sqlite.ts:24 [EXTRACTED]
  ```
  const onPath = (process.env.PATH ?? '')
  ```
- `process.env.XDG_DATA_HOME` ← packages/tool-opencode/src/testing/fake-opencode.ts:27 [EXTRACTED]
  ```
  const root = path.join(process.env.XDG_DATA_HOME || '', 'fake-opencode');
  ```
- `process.env.OPENCODE_SERVER_PASSWORD` ← packages/tool-opencode/src/testing/fake-opencode.ts:46 [EXTRACTED]
  ```
  const expected = 'Basic ' + Buffer.from('opencode:' + (process.env.OPENCODE_SERVER_PASSWORD || '')).toString('base64');
  ```
- `process.env.HOME` ← oxlint-plugin-teamai/rules/home-env.js:12 [EXTRACTED]
  ```
  docs: { description: 'Use getUserHome instead of reading process.env.HOME directly.' },
  ```