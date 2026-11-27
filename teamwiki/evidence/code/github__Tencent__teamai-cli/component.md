---
title: github__Tencent__teamai-cli component
domain: code-knowledge
source:
  - src/index.ts
  - src/rebuild-wiki-index.ts
  - oxlint-plugin-teamai/anti-slop/index.ts
  - scripts/verify/observer.ts
  - src/resources/index.ts
  - src/token-usage/index.ts
  - src/utils/cache-index.ts
  - src/utils/search-index.ts
  - packages/runtime-tools/src/index.ts
  - packages/tool-agy/src/index.ts
  - packages/tool-claude/src/index.ts
  - packages/tool-codebuddy/src/index.ts
  - packages/tool-codex/src/index.ts
  - packages/tool-copilot/src/index.ts
  - packages/tool-cursor/src/index.ts
  - packages/tool-dsh/src/index.ts
  - packages/tool-hermes/src/index.ts
  - packages/tool-joycode/src/index.ts
  - packages/tool-kiro/src/index.ts
  - packages/tool-muse/src/index.ts
  - packages/tool-openclaw/src/index.ts
  - packages/tool-opencode/src/index.ts
  - packages/tool-pi/src/index.ts
  - packages/tool-qoder/src/index.ts
  - packages/tool-trae/src/index.ts
  - packages/tool-zcode/src/index.ts
  - src/providers/cnb/index.ts
  - src/providers/git/index.ts
  - src/providers/gitcode/index.ts
  - src/providers/github/index.ts
  - src/providers/gitlab/index.ts
  - src/providers/tgit/index.ts
  - src/session-flow/adapters/index.ts
  - packages/tool-claude/src/testing/index.ts
  - packages/tool-codex/src/testing/index.ts
  - packages/tool-opencode/src/testing/index.ts
  - src/wiki-engine/code-knowledge/ast/index.ts
  - src/wiki-engine/code-knowledge/extractors/index.ts
  - tsup.config.ts
  - vitest.config.ts
  - vitest.e2e.config.ts
  - vitest.windows.config.ts
  - scripts/agent-context-budget.ts
  - scripts/agent-wait-budget.ts
  - scripts/ci-recipe.ts
  - scripts/command-table.ts
  - scripts/commands-reference.ts
  - scripts/doc-check.ts
  - scripts/glossary-avoid.ts
  - scripts/model-prices.ts
  - scripts/tool-support.ts
  - src/agent-observation.ts
  - src/agent-skills.ts
  - src/agent-version.ts
  - src/agy-hook-io.ts
  - src/agy-hooks.ts
  - src/api-key.ts
  - src/autocompact-reconcile.ts
  - src/bootstrap.ts
  - src/bridged-team-hooks.ts
  - src/builtin-agents.ts
  - src/builtin-hooks.ts
  - src/builtin-rules.ts
  - src/builtin-skills.ts
  - src/bundled-runtime.ts
  - src/cache-cmd.ts
  - src/checkout-roles.ts
  - src/claude-hook-host.ts
  - src/cli-int.ts
  - src/cli-skill-names.ts
  - src/clone.ts
  - src/coauthor-reconcile.ts
  - src/code-knowledge-recall.ts
  - src/codebase-cmd.ts
  - src/codebase-extract.ts
  - src/codebase-freshness.ts
  - src/codebase-upgrade-wiki.ts
  - src/codebase-wiki-lint.ts
  - src/codebase.ts
  - src/codebuddy-team-hooks.ts
  - src/codex-project-trust.ts
  - src/codex-team-hooks.ts
  - src/codex-trust.ts
  - src/command-shell.ts
  - src/config.ts
  - src/contribute-check.ts
  - src/contribute.ts
  - src/copilot-hook-claim.ts
  - src/cursor-user-rules.ts
  - src/dashboard-collector.ts
  - src/dashboard-html.ts
  - src/dashboard-scope.ts
  - src/dashboard.ts
  - src/deep-enrich.ts
  - src/default-driver.ts
  - src/default-drivers.ts
  - src/default-folders.ts
  - src/default-scorers.ts
  - src/default-workflows.ts
  - src/digest-failures.ts
  - src/digest.ts
  - src/doctor-agent-models.ts
  - src/doctor-delivery.ts
  - src/doctor-git-exclude.ts
  - src/doctor-sandboxes.ts
  - src/doctor-scorers.ts
  - src/doctor.ts
  - src/driver-identity.ts
  - src/dry-run-guard.ts
  - src/dsh-hooks.ts
  - src/enrich-with-ai.ts
  - src/env-advisories.ts
  - src/env-commands.ts
  - src/env-exec.ts
  - src/env-listing.ts
  - src/env-reserved.ts
  - src/env-resolution.ts
  - src/env-sh-exports.ts
  - src/exclude.ts
  - src/folder-markers.ts
  - src/git-exclude-delivered.ts
  - src/git-exclude-notices.ts
  - src/git-exclude.ts
  - src/git-hook.ts
  - src/graph-aggregate.ts
  - src/hermes-config.ts
  - src/hermes-hooks.ts
  - src/hook-command.ts
  - src/hook-dispatch-cli.ts
  - src/hook-dispatch.ts
  - src/hook-fast-path.ts
  - src/hook-handlers.ts
  - src/hooks-cmd.ts
  - src/hooks.ts
  - src/import-codebase.ts
  - src/import-from-mr.ts
  - src/import-from-repo.ts
  - src/import-iwiki.ts
  - src/import-local.ts
  - src/import-mr.ts
  - src/import-org.ts
  - src/import-repo-list.ts
  - src/import-repo.ts
  - src/import.ts
  - src/init.ts
  - src/install-prefix.ts
  - src/installations.ts
  - src/instruction-targets.ts
  - src/iwiki-dual.ts
  - src/kiro-hooks.ts
  - src/known-agents.ts
  - src/launch-context.ts
  - oxlint-plugin-teamai/failure-codes.js
  - oxlint-plugin-teamai/fs-calls.js
  - oxlint-plugin-teamai/imports.js
  - oxlint-plugin-teamai/index.js
  - oxlint-plugin-teamai/utils.js
---

# Component

- `reportCommandError` ← src/index.ts:91 [EXTRACTED]
  ```
  export async function reportCommandError(cause: unknown): Promise<void> {
  ```
- `rebuildWikiIndex` ← src/rebuild-wiki-index.ts:34 [EXTRACTED]
  ```
  export async function rebuildWikiIndex(teamwikiRoot: string): Promise<void> {
  ```
- `antiSlopRules` ← oxlint-plugin-teamai/anti-slop/index.ts:21 [EXTRACTED]
  ```
  export const antiSlopRules = {
  ```
- `observerReads` ← scripts/verify/observer.ts:58 [EXTRACTED]
  ```
  export function observerReads(provider: string): boolean {
  ```
- `attemptsObserved` ← scripts/verify/observer.ts:68 [EXTRACTED]
  ```
  export function attemptsObserved(world: Pick<World, 'dir'>): { kind: 'read'; attempts: Set<string> } | { kind: 'unreadable'; why: string } {
  ```
- `bwrapSteps` ← scripts/verify/observer.ts:203 [EXTRACTED]
  ```
  export function bwrapSteps(procs: readonly ProcEntry[], roots: readonly string[]): Array<{ bwrap: string; steps: string[] }> {
  ```
- `startObserver` ← scripts/verify/observer.ts:236 [EXTRACTED]
  ```
  export function startObserver(world: World, { pass, label, listed = listedHere }: { pass: ReadonlyMap<string, string>; label: string; listed?: Ask }) {
  ```
- `getHandler` ← src/resources/index.ts:36 [EXTRACTED]
  ```
  export function getHandler<TType extends ResourceType>(type: TType): (typeof handlers)[TType] {
  ```
- `getAllHandlers` ← src/resources/index.ts:40 [EXTRACTED]
  ```
  export function getAllHandlers(): ResourceHandler[] {
  ```
- `isTokenFormatId` ← src/token-usage/index.ts:27 [EXTRACTED]
  ```
  export function isTokenFormatId(format: string): format is TokenFormatId {
  ```
- `readTokenUsage` ← src/token-usage/index.ts:32 [EXTRACTED]
  ```
  export function readTokenUsage(format: TokenFormatId, source: TokenSource): Promise<TokenReading> {
  ```
- `parsePositiveInteger` ← src/utils/cache-index.ts:83 [EXTRACTED]
  ```
  export function parsePositiveInteger(value: string): number | undefined {
  ```
- `getCacheRoot` ← src/utils/cache-index.ts:96 [EXTRACTED]
  ```
  export function getCacheRoot(): string {
  ```
- `loadCacheIndex` ← src/utils/cache-index.ts:125 [EXTRACTED]
  ```
  export async function loadCacheIndex(): Promise<CacheIndex> {
  ```
- `saveCacheIndex` ← src/utils/cache-index.ts:157 [EXTRACTED]
  ```
  export async function saveCacheIndex(idx: CacheIndex): Promise<void> {
  ```
- `statDirSize` ← src/utils/cache-index.ts:178 [EXTRACTED]
  ```
  export async function statDirSize(absPath: string): Promise<number> {
  ```
- `touchCacheEntry` ← src/utils/cache-index.ts:250 [EXTRACTED]
  ```
  export async function touchCacheEntry(args: {
  ```
- `gcCache` ← src/utils/cache-index.ts:303 [EXTRACTED]
  ```
  export async function gcCache(opts?: GcOptions): Promise<GcResult> {
  ```
- `getCacheStatus` ← src/utils/cache-index.ts:436 [EXTRACTED]
  ```
  export async function getCacheStatus(): Promise<{
  ```
- `dropIndexesAfterRebuild` ← src/utils/search-index.ts:53 [EXTRACTED]
  ```
  export async function dropIndexesAfterRebuild(localConfig: LocalConfig): Promise<void> {
  ```
- `dropIndexesAfterSourceUpdate` ← src/utils/search-index.ts:64 [EXTRACTED]
  ```
  export async function dropIndexesAfterSourceUpdate(localConfig: LocalConfig): Promise<void> {
  ```
- `dropCheckoutIndexes` ← src/utils/search-index.ts:77 [EXTRACTED]
  ```
  export async function dropCheckoutIndexes(dataHome: string, keep?: string): Promise<void> {
  ```
- `dropAllSearchIndexes` ← src/utils/search-index.ts:103 [EXTRACTED]
  ```
  export async function dropAllSearchIndexes(dataHome: string): Promise<void> {
  ```
- `inferDomain` ← src/utils/search-index.ts:281 [EXTRACTED]
  ```
  export function inferDomain(
  ```
- `parseLearningDoc` ← src/utils/search-index.ts:365 [EXTRACTED]
  ```
  export function parseLearningDoc(
  ```
- `titleFromFilename` ← src/utils/search-index.ts:400 [EXTRACTED]
  ```
  export function titleFromFilename(filename: string): string {
  ```
- `buildIndex` ← src/utils/search-index.ts:1047 [EXTRACTED]
  ```
  export async function buildIndex(
  ```
- `indexInMemory` ← src/utils/search-index.ts:1097 [EXTRACTED]
  ```
  export async function indexInMemory(opts: BuildIndexOptions): Promise<SearchIndex> {
  ```
- `isLegacyIndex` ← src/utils/search-index.ts:1278 [EXTRACTED]
  ```
  export function isLegacyIndex(index: SearchIndex | null): boolean {
  ```
- `loadIndex` ← src/utils/search-index.ts:1294 [EXTRACTED]
  ```
  export async function loadIndex(indexPath?: string): Promise<SearchIndex | null> {
  ```
- `TITLE_LENGTH_SCALE` ← src/utils/search-index.ts:1357 [EXTRACTED]
  ```
  export const TITLE_LENGTH_SCALE = 4.5;
  ```
- `search` ← src/utils/search-index.ts:1395 [EXTRACTED]
  ```
  export function search(
  ```
- `toolsStepRuntime` ← packages/runtime-tools/src/index.ts:101 [EXTRACTED]
  ```
  export function toolsStepRuntime<TCan = Can>(deps: ToolsRuntimeDeps<TCan>): ToolsStepRuntime<TCan> {
  ```
- `family` ← packages/tool-agy/src/index.ts:12 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms, tokens, detect } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-claude/src/index.ts:9 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms, tokens: { 'claude-jsonl': readClaudeJsonl }, detect } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-codebuddy/src/index.ts:12 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms, tokens, detect } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-codex/src/index.ts:8 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms, tokens: { 'codex-rollout': readCodexRollout }, detect: {} } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-copilot/src/index.ts:7 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms, tokens: {}, detect: {} } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-cursor/src/index.ts:8 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms, tokens: {}, detect } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-dsh/src/index.ts:6 [EXTRACTED]
  ```
  export const family = { tools, launch: {}, platforms: {}, tokens: {}, detect } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-hermes/src/index.ts:8 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms, tokens: {}, detect } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-joycode/src/index.ts:7 [EXTRACTED]
  ```
  export const family = { tools, launch: {}, platforms, tokens: { 'codex-rollout': readCodexRollout }, detect: {} } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-kiro/src/index.ts:6 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms: {}, tokens: {}, detect: {} } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-muse/src/index.ts:12 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms, tokens, detect } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-openclaw/src/index.ts:7 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms: {}, tokens: {}, detect } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-opencode/src/index.ts:11 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms, tokens, detect: {} } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-pi/src/index.ts:12 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms, tokens, detect } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-qoder/src/index.ts:8 [EXTRACTED]
  ```
  export const family = { tools, launch, platforms, tokens: { 'claude-jsonl': readClaudeJsonl }, detect: {} } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-trae/src/index.ts:5 [EXTRACTED]
  ```
  export const family = { tools, launch: {}, platforms: {}, tokens: {}, detect: {} } as const satisfies ToolFamily;
  ```
- `family` ← packages/tool-zcode/src/index.ts:5 [EXTRACTED]
  ```
  export const family = { tools, launch: {}, platforms: {}, tokens: {}, detect: {} } as const satisfies ToolFamily;
  ```
- `CNBProvider` ← src/providers/cnb/index.ts:21 [EXTRACTED]
  ```
  export class CNBProvider implements GitProvider {
  ```
- `normalizeGitIdentity` ← src/providers/git/index.ts:12 [EXTRACTED]
  ```
  export function normalizeGitIdentity(value: string): string | null {
  ```
- `GenericGitProvider` ← src/providers/git/index.ts:65 [EXTRACTED]
  ```
  export class GenericGitProvider implements GitProvider {
  ```
- `GitCodeProvider` ← src/providers/gitcode/index.ts:29 [EXTRACTED]
  ```
  export class GitCodeProvider implements GitProvider {
  ```
- `GitHubProvider` ← src/providers/github/index.ts:19 [EXTRACTED]
  ```
  export class GitHubProvider implements GitProvider {
  ```
- `GitLabProvider` ← src/providers/gitlab/index.ts:26 [EXTRACTED]
  ```
  export class GitLabProvider implements GitProvider {
  ```
- `TGitProvider` ← src/providers/tgit/index.ts:18 [EXTRACTED]
  ```
  export class TGitProvider implements GitProvider {
  ```
- `storeDirOf` ← src/session-flow/adapters/index.ts:147 [EXTRACTED]
  ```
  export function storeDirOf(platform: string, root: SessionStoreRoot): string {
  ```
- `adapterAt` ← src/session-flow/adapters/index.ts:158 [EXTRACTED]
  ```
  export function adapterAt({ platform, storeDir }: { platform: string; storeDir: string }): AgentAdapter {
  ```
- `adapterOn` ← src/session-flow/adapters/index.ts:169 [EXTRACTED]
  ```
  export function adapterOn(platform: string, root: SessionStoreRoot): AgentAdapter {
  ```
- `getAdapter` ← src/session-flow/adapters/index.ts:173 [EXTRACTED]
  ```
  export function getAdapter(platform: string, toolRoots?: LocalConfig['toolRoots']): AgentAdapter {
  ```
- `listAvailablePlatforms` ← src/session-flow/adapters/index.ts:177 [EXTRACTED]
  ```
  export function listAvailablePlatforms(): string[] {
  ```
- `listInstalledPlatforms` ← src/session-flow/adapters/index.ts:181 [EXTRACTED]
  ```
  export function listInstalledPlatforms(toolRoots?: LocalConfig['toolRoots'], projectPath = process.cwd()): string[] {
  ```
- `claudeFake` ← packages/tool-claude/src/testing/index.ts:13 [EXTRACTED]
  ```
  export const claudeFake = {
  ```
- `codexFake` ← packages/tool-codex/src/testing/index.ts:18 [EXTRACTED]
  ```
  export const codexFake = {
  ```
- `opencodeFake` ← packages/tool-opencode/src/testing/index.ts:9 [EXTRACTED]
  ```
  export const opencodeFake = {
  ```
- `astAvailable` ← src/wiki-engine/code-knowledge/ast/index.ts:19 [EXTRACTED]
  ```
  export function astAvailable(): boolean {
  ```
- `extractStructuralGraph` ← src/wiki-engine/code-knowledge/ast/index.ts:45 [EXTRACTED]
  ```
  export async function extractStructuralGraph(
  ```
- `extractStructuralGraphAsFacts` ← src/wiki-engine/code-knowledge/ast/index.ts:235 [EXTRACTED]
  ```
  export async function extractStructuralGraphAsFacts(
  ```
- `formatAstStatsSummary` ← src/wiki-engine/code-knowledge/ast/index.ts:244 [EXTRACTED]
  ```
  export function formatAstStatsSummary(stats: StructuralGraphResult["stats"]): string {
  ```
- `extractForLanguage` ← src/wiki-engine/code-knowledge/extractors/index.ts:48 [EXTRACTED]
  ```
  export function extractForLanguage(language: string, files: CodeCollectedFile[], context?: ExtractorContext): CodeFact[] {
  ```
- `supportedLanguages` ← src/wiki-engine/code-knowledge/extractors/index.ts:61 [EXTRACTED]
  ```
  export function supportedLanguages(): string[] {
  ```
- `defineConfig` ← tsup.config.ts:48 [INFERRED]
  ```
  export default defineConfig({
  ```
- `defineConfig` ← vitest.config.ts:3 [INFERRED]
  ```
  export default defineConfig({
  ```
- `defineConfig` ← vitest.e2e.config.ts:3 [INFERRED]
  ```
  export default defineConfig({
  ```
- `defineConfig` ← vitest.windows.config.ts:5 [INFERRED]
  ```
  export default defineConfig({
  ```
- `measureAgentContext` ← scripts/agent-context-budget.ts:84 [EXTRACTED]
  ```
  export async function measureAgentContext() {
  ```
- `compareAgentContext` ← scripts/agent-context-budget.ts:147 [EXTRACTED]
  ```
  export function compareAgentContext(head: Budget, base: Budget) {
  ```
- `AgentWaitBudgetSchema` ← scripts/agent-wait-budget.ts:55 [EXTRACTED]
  ```
  export const AgentWaitBudgetSchema = z.object({
  ```
- `readLines` ← scripts/agent-wait-budget.ts:109 [EXTRACTED]
  ```
  export const readLines = (file: string): string[] => (fs.existsSync(file) ? fs.readFileSync(file, 'utf8').split('\n').slice(0, -1).filter(Boolean) : []);
  ```
- `fileSystemCalls` ← scripts/agent-wait-budget.ts:131 [EXTRACTED]
  ```
  export function fileSystemCalls(records: readonly NodeRecord[]) {
  ```
- `otherProcesses` ← scripts/agent-wait-budget.ts:144 [EXTRACTED]
  ```
  export function otherProcesses(records: readonly NodeRecord[]) {
  ```
- `measureAgentWait` ← scripts/agent-wait-budget.ts:508 [EXTRACTED]
  ```
  export async function measureAgentWait(options: { keep: boolean }) {
  ```
- `compareAgentWait` ← scripts/agent-wait-budget.ts:795 [EXTRACTED]
  ```
  export function compareAgentWait(head: AgentWaitBudget, base: AgentWaitBudget) {
  ```
- `main` ← scripts/agent-wait-budget.ts:853 [EXTRACTED]
  ```
  export async function main(args: readonly string[]): Promise<number> {
  ```
- `ciRecipesOf` ← scripts/ci-recipe.ts:18 [EXTRACTED]
  ```
  export function ciRecipesOf(file: string): CiRecipe[] {
  ```
- `runCommandsOf` ← scripts/ci-recipe.ts:29 [EXTRACTED]
  ```
  export function runCommandsOf(recipe: CiRecipe): string[] {
  ```
- `loadCommandTable` ← scripts/command-table.ts:2 [EXTRACTED]
  ```
  export async function loadCommandTable() {
  ```
- `COMMANDS_REFERENCE_PATH` ← scripts/commands-reference.ts:17 [EXTRACTED]
  ```
  export const COMMANDS_REFERENCE_PATH = 'skill-data/core/references/commands.md';
  ```
- `renderCommandsReference` ← scripts/commands-reference.ts:78 [EXTRACTED]
  ```
  export function renderCommandsReference(program: Command): string {
  ```
- `check` ← scripts/doc-check.ts:2 [EXTRACTED]
  ```
  export async function check(name: string, run: () => void | Promise<void>, cleanup?: () => void): Promise<void> {
  ```
- `GLOSSARY_PATH` ← scripts/glossary-avoid.ts:4 [EXTRACTED]
  ```
  export const GLOSSARY_PATH = 'docs/dev/glossary.md';
  ```
- `avoidSpellings` ← scripts/glossary-avoid.ts:7 [EXTRACTED]
  ```
  export function avoidSpellings(root: string): string[] {
  ```
- `findAvoidSpellings` ← scripts/glossary-avoid.ts:58 [EXTRACTED]
  ```
  export function findAvoidSpellings(root: string) {
  ```
- `catalogFromLiteLlm` ← scripts/model-prices.ts:125 [EXTRACTED]
  ```
  export function catalogFromLiteLlm(document: JsonValue, source: { revision: string; date: string }): PriceCatalog {
  ```
- `parseCatalog` ← scripts/model-prices.ts:168 [EXTRACTED]
  ```
  export function parseCatalog(json: JsonValue): PriceCatalog {
  ```
- `formatCatalog` ← scripts/model-prices.ts:173 [EXTRACTED]
  ```
  export function formatCatalog(catalog: PriceCatalog): string {
  ```
- `describeCatalogChange` ← scripts/model-prices.ts:182 [EXTRACTED]
  ```
  export function describeCatalogChange(before: PriceCatalog, after: PriceCatalog): string {
  ```
- `TOOL_SUPPORT_PAGES` ← scripts/tool-support.ts:17 [EXTRACTED]
  ```
  export const TOOL_SUPPORT_PAGES = {
  ```
- `renderToolSupportPage` ← scripts/tool-support.ts:241 [EXTRACTED]
  ```
  export function renderToolSupportPage(lang: ToolSupportLang): string {
  ```
- `ObservedModelSchema` ← src/agent-observation.ts:47 [EXTRACTED]
  ```
  export const ObservedModelSchema = z.object({ requested: Name.optional(), reported: Name.optional(), alias: Name.optional() });
  ```
- `ObservedEffortSchema` ← src/agent-observation.ts:51 [EXTRACTED]
  ```
  export const ObservedEffortSchema = z.object({ requested: Label.optional(), reported: Label.optional() });
  ```
- `CommitStateSchema` ← src/agent-observation.ts:56 [EXTRACTED]
  ```
  export const CommitStateSchema = z.object({ commit: z.string().regex(COMMIT), dirty: z.boolean() });
  ```
- `AgentObservationSchema` ← src/agent-observation.ts:61 [EXTRACTED]
  ```
  export const AgentObservationSchema = z.object({
  ```
- `UsedSchema` ← src/agent-observation.ts:78 [EXTRACTED]
  ```
  export const UsedSchema = z.object({ skills: z.array(z.string().min(1)) });
  ```
- `ReportedAgentSchema` ← src/agent-observation.ts:88 [EXTRACTED]
  ```
  export const ReportedAgentSchema = z.object({
  ```
- `PreparedAgentSchema` ← src/agent-observation.ts:102 [EXTRACTED]
  ```
  export const PreparedAgentSchema = ReportedAgentSchema.extend({
  ```
- `isRecordableName` ← src/agent-observation.ts:116 [EXTRACTED]
  ```
  export function isRecordableName(value: string): boolean {
  ```
- `isRecordableLabel` ← src/agent-observation.ts:120 [EXTRACTED]
  ```
  export function isRecordableLabel(value: string): boolean {
  ```
- `observeLaunch` ← src/agent-observation.ts:152 [EXTRACTED]
  ```
  export async function observeLaunch(launch: ToolLaunch): Promise<ReportedAgent> {
  ```
- `observeCheckout` ← src/agent-observation.ts:165 [EXTRACTED]
  ```
  export async function observeCheckout(launch: ToolLaunch): Promise<PreparedAgent> {
  ```
- `observedModel` ← src/agent-observation.ts:219 [EXTRACTED]
  ```
  export function observedModel(values: { requested?: string; reported?: string; alias?: string }): ObservedModel | undefined {
  ```
- `observedEffort` ← src/agent-observation.ts:224 [EXTRACTED]
  ```
  export function observedEffort(values: { requested?: string; reported?: string }): ObservedEffort | undefined {
  ```
- `settleObservation` ← src/agent-observation.ts:246 [EXTRACTED]
  ```
  export function settleObservation(
  ```
- `parseReportedAgent` ← src/agent-observation.ts:335 [EXTRACTED]
  ```
  export const parseReportedAgent = ReportedAgentFieldSchema.parse;
  ```
- `agentHarnessOf` ← src/agent-observation.ts:355 [EXTRACTED]
  ```
  export function agentHarnessOf(agent: RecordedAgent | undefined): AgentHarness | undefined {
  ```
- `sameHarness` ← src/agent-observation.ts:384 [EXTRACTED]
  ```
  export function sameHarness(left: AgentObservation, right: AgentObservation, { comparesTeam = true }: { comparesTeam?: boolean } = {}): boolean {
  ```
- `harnessChanges` ← src/agent-observation.ts:411 [EXTRACTED]
  ```
  export function harnessChanges(before: AgentHarness, after: AgentHarness): HarnessChange[] {
  ```
- `readRecordedAgent` ← src/agent-observation.ts:436 [EXTRACTED]
  ```
  export const readRecordedAgent = RecordedAgentFieldSchema.parse;
  ```
- `parseReportedUsed` ← src/agent-observation.ts:451 [EXTRACTED]
  ```
  export const parseReportedUsed = ReportedUsedFieldSchema.parse;
  ```
- `buildClassifyContext` ← src/agent-skills.ts:60 [EXTRACTED]
  ```
  export async function buildClassifyContext(localConfig: LocalConfig): Promise<ClassifyContext> {
  ```
- `collectTeamRepoSkills` ← src/agent-skills.ts:96 [EXTRACTED]
  ```
  export async function collectTeamRepoSkills(repoPath: string): Promise<Map<string, { namespace?: string }>> {
  ```
- `classifySkill` ← src/agent-skills.ts:109 [EXTRACTED]
  ```
  export function classifySkill(name: string, ctx: ClassifyContext, skillPath?: string): SkillSource {
  ```
- `classifyInstalledSkill` ← src/agent-skills.ts:136 [EXTRACTED]
  ```
  export async function classifyInstalledSkill(name: string, ctx: ClassifyContext, skillDir: string): Promise<SkillSource> {
  ```
- `formatSkillSource` ← src/agent-skills.ts:141 [EXTRACTED]
  ```
  export function formatSkillSource(source: SkillSource): string {
  ```
- `scanAgentSkills` ← src/agent-skills.ts:161 [EXTRACTED]
  ```
  export async function scanAgentSkills(agent: ResolvedAgent, ctx: ClassifyContext): Promise<AgentSkillsView> {
  ```
- `scanInstalledAgents` ← src/agent-skills.ts:218 [EXTRACTED]
  ```
  export async function scanInstalledAgents(
  ```
- `readSkillDescription` ← src/agent-skills.ts:239 [EXTRACTED]
  ```
  export async function readSkillDescription(skillMdPath: string): Promise<string> {
  ```
- `truncate` ← src/agent-skills.ts:253 [EXTRACTED]
  ```
  export function truncate(text: string, max: number): string {
  ```
- `getAgentVersion` ← src/agent-version.ts:63 [EXTRACTED]
  ```
  export async function getAgentVersion(agentType: string): Promise<string> {
  ```
- `clearVersionCache` ← src/agent-version.ts:84 [EXTRACTED]
  ```
  export function clearVersionCache(): void {
  ```
- `agyToolsFor` ← src/agy-hook-io.ts:53 [EXTRACTED]
  ```
  export function agyToolsFor(claudeTools: JsonValue | undefined): string[] {
  ```
- `agyHookPayload` ← src/agy-hook-io.ts:92 [EXTRACTED]
  ```
  export function agyHookPayload(event: string, payload: HookStdin): HookStdin | null {
  ```
- `agyHookReply` ← src/agy-hook-io.ts:152 [EXTRACTED]
  ```
  export function agyHookReply(event: string, result: AgyHookResult): string {
  ```
- `agyHookFile` ← src/agy-hooks.ts:13 [EXTRACTED]
  ```
  export function agyHookFile(): string {
  ```
- `reconcileAgyHooks` ← src/agy-hooks.ts:62 [EXTRACTED]
  ```
  export async function reconcileAgyHooks(options: { removeAll?: boolean } = {}): Promise<void> {
  ```
- `hasAgyHooks` ← src/agy-hooks.ts:80 [EXTRACTED]
  ```
  export async function hasAgyHooks(): Promise<boolean> {
  ```
- `getApiKeyPath` ← src/api-key.ts:22 [EXTRACTED]
  ```
  export function getApiKeyPath(): string {
  ```
- `resolveApiKey` ← src/api-key.ts:30 [EXTRACTED]
  ```
  export function resolveApiKey(): string | null {
  ```
- `saveApiKey` ← src/api-key.ts:49 [EXTRACTED]
  ```
  export async function saveApiKey(key: string): Promise<void> {
  ```
- `autoCompactRecordPath` ← src/autocompact-reconcile.ts:99 [EXTRACTED]
  ```
  export function autoCompactRecordPath(): string {
  ```
- `loadAutoCompactRecord` ← src/autocompact-reconcile.ts:103 [EXTRACTED]
  ```
  export async function loadAutoCompactRecord(): Promise<Record<string, string>> {
  ```
- `saveAutoCompactRecord` ← src/autocompact-reconcile.ts:115 [EXTRACTED]
  ```
  export async function saveAutoCompactRecord(record: Readonly<Record<string, string>>): Promise<void> {
  ```
- `reconcileAutoCompactLocked` ← src/autocompact-reconcile.ts:126 [EXTRACTED]
  ```
  export async function reconcileAutoCompactLocked(
  ```
- `spliceCodexAutoCompact` ← src/autocompact-reconcile.ts:448 [EXTRACTED]
  ```
  export function spliceCodexAutoCompact(source: string, value: number | null): string {
  ```
- `reconcileAutoCompactForConfig` ← src/autocompact-reconcile.ts:537 [EXTRACTED]
  ```
  export async function reconcileAutoCompactForConfig(
  ```
- `readSelfModeMarker` ← src/bootstrap.ts:48 [EXTRACTED]
  ```
  export async function readSelfModeMarker(dir: string): Promise<{ repo?: string; provider?: string } | null> {
  ```
- `previewSelfBootstrap` ← src/bootstrap.ts:229 [EXTRACTED]
  ```
  export async function previewSelfBootstrap(dir?: string): Promise<LocalConfig | null> {
  ```
- `bootstrapSelfMode` ← src/bootstrap.ts:253 [EXTRACTED]
  ```
  export async function bootstrapSelfMode(
  ```
- `isBridgedTeamHookTool` ← src/bridged-team-hooks.ts:91 [EXTRACTED]
  ```
  export function isBridgedTeamHookTool(tool: string): boolean {
  ```
- `bridgedTeamHookDir` ← src/bridged-team-hooks.ts:96 [EXTRACTED]
  ```
  export function bridgedTeamHookDir(): string {
  ```
- `bridgedTeamHookFile` ← src/bridged-team-hooks.ts:101 [EXTRACTED]
  ```
  export function bridgedTeamHookFile(tool: string): string {
  ```
- `bridgedTeamHookEvents` ← src/bridged-team-hooks.ts:140 [EXTRACTED]
  ```
  export async function bridgedTeamHookEvents(tool: string): Promise<Map<string, number>> {
  ```
- `runBridgedTeamHooks` ← src/bridged-team-hooks.ts:376 [EXTRACTED]
  ```
  export async function runBridgedTeamHooks(tool: string, event: string, raw: string): Promise<BridgeReply> {
  ```
- `RECALL_AGENT` ← src/builtin-agents.ts:42 [EXTRACTED]
  ```
  export const RECALL_AGENT = 'teamai-recall';
  ```
- `BUILTIN_AGENT_NAMES` ← src/builtin-agents.ts:49 [EXTRACTED]
  ```
  export const BUILTIN_AGENT_NAMES = new Set<string>([RECALL_AGENT]);
  ```
- `builtinAgentsReplacedByTeam` ← src/builtin-agents.ts:62 [EXTRACTED]
  ```
  export async function builtinAgentsReplacedByTeam(
  ```
- `shippedAgentRender` ← src/builtin-agents.ts:160 [EXTRACTED]
  ```
  export function shippedAgentRender(stem: string, tool: AgentToolId, scope: Scope): RenderResult | undefined {
  ```
- `deployBuiltinAgents` ← src/builtin-agents.ts:226 [EXTRACTED]
  ```
  export async function deployBuiltinAgents(
  ```
- `TEAMAI_BIN_DIR` ← src/builtin-hooks.ts:39 [EXTRACTED]
  ```
  export const TEAMAI_BIN_DIR = '.teamai/bin';
  ```
- `isShellDependentTool` ← src/builtin-hooks.ts:50 [EXTRACTED]
  ```
  export function isShellDependentTool(tool: string): boolean {
  ```
- `hasShell` ← src/builtin-hooks.ts:66 [EXTRACTED]
  ```
  export function hasShell(): boolean {
  ```
- `_resetShellCache` ← src/builtin-hooks.ts:79 [EXTRACTED]
  ```
  export function _resetShellCache(): void {
  ```
- `resolveTeamaiEntryScript` ← src/builtin-hooks.ts:89 [EXTRACTED]
  ```
  export function resolveTeamaiEntryScript(): string | null {
  ```
- `resolveCliEntry` ← src/builtin-hooks.ts:107 [EXTRACTED]
  ```
  export function resolveCliEntry(): string | null {
  ```
- `teamaiWrapperPath` ← src/builtin-hooks.ts:112 [EXTRACTED]
  ```
  export function teamaiWrapperPath(): string {
  ```
- `teamaiWrapperSource` ← src/builtin-hooks.ts:117 [EXTRACTED]
  ```
  export function teamaiWrapperSource({ node, entry }: { node: string; entry: string }): string {
  ```
- `ensureTeamaiWrapper` ← src/builtin-hooks.ts:157 [EXTRACTED]
  ```
  export function ensureTeamaiWrapper(): string | null {
  ```
- `skipToolsWithoutShell` ← src/builtin-hooks.ts:227 [EXTRACTED]
  ```
  export function skipToolsWithoutShell(tools: string[]): Set<string> {
  ```
- `getDispatchCommand` ← src/builtin-hooks.ts:291 [EXTRACTED]
  ```
  export function getDispatchCommand(event: string, tool: string, matcher?: string, binPath?: string): string {
  ```
- `toolUsesPwshShell` ← src/builtin-hooks.ts:332 [EXTRACTED]
  ```
  export function toolUsesPwshShell(tool: string): boolean {
  ```
- `getTeamHookDispatchCommand` ← src/builtin-hooks.ts:344 [EXTRACTED]
  ```
  export function getTeamHookDispatchCommand(event: string, tool: string): string {
  ```
- `getCodebuddyTeamHookDispatchCommand` ← src/builtin-hooks.ts:358 [EXTRACTED]
  ```
  export function getCodebuddyTeamHookDispatchCommand(
  ```
- `getTeamHookDispatchCommandWindows` ← src/builtin-hooks.ts:380 [EXTRACTED]
  ```
  export function getTeamHookDispatchCommandWindows(event: string, tool: string): string {
  ```
- `getRawDispatchCommand` ← src/builtin-hooks.ts:390 [EXTRACTED]
  ```
  export function getRawDispatchCommand(event: string, tool: string, matcher?: string): string {
  ```
- `POST_TOOL_USE_WILDCARD_KEY` ← src/builtin-hooks.ts:455 [EXTRACTED]
  ```
  export const POST_TOOL_USE_WILDCARD_KEY = 'Hook dispatch post-tool-use wildcard';
  ```
- `RETIRED_TODOWRITE_HOOK_KEY` ← src/builtin-hooks.ts:464 [EXTRACTED]
  ```
  export const RETIRED_TODOWRITE_HOOK_KEY = 'Hook dispatch post-tool-use TodoWrite';
  ```
- `builtinHookDefs` ← src/builtin-hooks.ts:527 [EXTRACTED]
  ```
  export function builtinHookDefs(tool: string, form: BuiltinHookForm = WAITED_LOGIN_FORM): HookDef[] {
  ```
- `retiredBuiltinHookDefs` ← src/builtin-hooks.ts:537 [EXTRACTED]
  ```
  export function retiredBuiltinHookDefs(tool: string): HookDef[] {
  ```
- `builtinHookForm` ← src/builtin-hooks.ts:562 [EXTRACTED]
  ```
  export async function builtinHookForm(tool: string, destination: 'user' | 'project'): Promise<BuiltinHookForm> {
  ```
- `recognisedBuiltinHookDefs` ← src/builtin-hooks.ts:599 [EXTRACTED]
  ```
  export function recognisedBuiltinHookDefs(tool: string): HookDef[] {
  ```
- `installedBuiltinHookDefs` ← src/builtin-hooks.ts:742 [EXTRACTED]
  ```
  export function installedBuiltinHookDefs(tool: string, settingsDriven: boolean): HookDef[] {
  ```
- `takesAllBuiltins` ← src/builtin-hooks.ts:771 [EXTRACTED]
  ```
  export function takesAllBuiltins(tool: string): boolean {
  ```
- `applyBuiltinOverride` ← src/builtin-hooks.ts:788 [EXTRACTED]
  ```
  export function applyBuiltinOverride(defs: HookDef[], override?: BuiltinHookOverride): HookDef[] {
  ```
- `BUILTIN_RULE_NAMES` ← src/builtin-rules.ts:38 [EXTRACTED]
  ```
  export const BUILTIN_RULE_NAMES = new Set<string>(['teamai-recall']);
  ```
- `TEAMAI_CONTEXT_RULE_NAME` ← src/builtin-rules.ts:47 [EXTRACTED]
  ```
  export const TEAMAI_CONTEXT_RULE_NAME = 'teamai-context';
  ```
- `EXCLUDED_RULE_NAMES` ← src/builtin-rules.ts:53 [EXTRACTED]
  ```
  export const EXCLUDED_RULE_NAMES = new Set<string>([
  ```
- `deployBuiltinRules` ← src/builtin-rules.ts:66 [EXTRACTED]
  ```
  export async function deployBuiltinRules(
  ```
- `isDeployedRecallRule` ← src/builtin-rules.ts:197 [EXTRACTED]
  ```
  export function isDeployedRecallRule(content: string): boolean {
  ```
- `RECALL_RULE_NAME` ← src/builtin-rules.ts:202 [EXTRACTED]
  ```
  export const RECALL_RULE_NAME = 'teamai-recall';
  ```
- `resolveRecall` ← src/builtin-rules.ts:300 [EXTRACTED]
  ```
  export async function resolveRecall(language: TeamaiConfig['language'], repoPath?: string): Promise<RecallResolution> {
  ```
- `recallTexts` ← src/builtin-rules.ts:323 [EXTRACTED]
  ```
  export async function recallTexts(language: TeamaiConfig['language'], repoPath?: string): Promise<RecallTexts> {
  ```
- `builtinSkillsTarget` ← src/builtin-skills.ts:104 [EXTRACTED]
  ```
  export async function builtinSkillsTarget(
  ```
- `pruneLegacyBuiltinSkills` ← src/builtin-skills.ts:124 [EXTRACTED]
  ```
  export async function pruneLegacyBuiltinSkills(
  ```
- `keptStubLine` ← src/builtin-skills.ts:238 [EXTRACTED]
  ```
  export async function keptStubLine(destDir: string, skillName: string): Promise<string | null> {
  ```
- `deployBuiltinSkills` ← src/builtin-skills.ts:272 [EXTRACTED]
  ```
  export async function deployBuiltinSkills(
  ```
- `resetBundledRuntimeCache` ← src/bundled-runtime.ts:30 [EXTRACTED]
  ```
  export function resetBundledRuntimeCache(): void {
  ```
- `resolveWorkbuddyNode` ← src/bundled-runtime.ts:84 [EXTRACTED]
  ```
  export function resolveWorkbuddyNode(platform: NodeJS.Platform = process.platform): string | null {
  ```
- `resolveCodebuddyNode` ← src/bundled-runtime.ts:94 [EXTRACTED]
  ```
  export function resolveCodebuddyNode(): string | null {
  ```
- `queryGitInstallPath` ← src/bundled-runtime.ts:156 [EXTRACTED]
  ```
  export function queryGitInstallPath(): string | null {
  ```
- `findGitBashWindows` ← src/bundled-runtime.ts:183 [EXTRACTED]
  ```
  export function findGitBashWindows(
  ```
- `ensureBundledRuntimeOnPath` ← src/bundled-runtime.ts:272 [EXTRACTED]
  ```
  export function ensureBundledRuntimeOnPath(platform: NodeJS.Platform = process.platform): void {
  ```
- `bundledShellFor` ← src/bundled-runtime.ts:319 [EXTRACTED]
  ```
  export function bundledShellFor(tool: string): string | null {
  ```
- `cacheCmd` ← src/cache-cmd.ts:72 [EXTRACTED]
  ```
  export async function cacheCmd(opts: CacheCmdOptions): Promise<void> {
  ```
- `recordCheckoutRole` ← src/checkout-roles.ts:59 [EXTRACTED]
  ```
  export async function recordCheckoutRole(input: { config: LocalConfig; checkout: string; role: string }): Promise<CheckoutRoleWrite> {
  ```
- `clearCheckoutRole` ← src/checkout-roles.ts:80 [EXTRACTED]
  ```
  export async function clearCheckoutRole(input: { config: LocalConfig; checkout: string }): Promise<CheckoutRoleWrite> {
  ```
- `withCheckoutRole` ← src/checkout-roles.ts:105 [EXTRACTED]
  ```
  export async function withCheckoutRole(config: LocalConfig): Promise<LocalConfig> {
  ```
- `copilotRunsEntries` ← src/claude-hook-host.ts:34 [EXTRACTED]
  ```
  export function copilotRunsEntries(data: JsonValue): Array<[string, JsonValue | undefined, string]> {
  ```
- `COPILOT_RUNS_ENTRIES_SOURCE` ← src/claude-hook-host.ts:76 [EXTRACTED]
  ```
  export const COPILOT_RUNS_ENTRIES_SOURCE = [
  ```
- `claudeHookUsesPowerShell` ← src/claude-hook-host.ts:135 [EXTRACTED]
  ```
  export function claudeHookUsesPowerShell(
  ```
- `LEGACY_CLAUDE_HOOK_OTHER_HOST_SKIP` ← src/claude-hook-host.ts:154 [EXTRACTED]
  ```
  export const LEGACY_CLAUDE_HOOK_OTHER_HOST_SKIP = LEGACY_POSIX_CLAUDE_HOOK_OTHER_HOST_SKIP;
  ```
- `claudeHookOtherHostSkip` ← src/claude-hook-host.ts:161 [EXTRACTED]
  ```
  export function claudeHookOtherHostSkip(
  ```
- `readsClaudeSettings` ← src/claude-hook-host.ts:247 [EXTRACTED]
  ```
  export function readsClaudeSettings(tool: string, where: { readonly file: string } | { readonly place: DeliveryPlace | undefined }): boolean {
  ```
- `claudeHookRunsInAnotherHost` ← src/claude-hook-host.ts:265 [EXTRACTED]
  ```
  export function claudeHookRunsInAnotherHost(tool: string, env: NodeJS.ProcessEnv = process.env, includeGlobalCopilot = true, place?: DeliveryPlace): boolean {
  ```
- `parseIntOption` ← src/cli-int.ts:7 [EXTRACTED]
  ```
  export function parseIntOption(name: string, value: string, min: number, max = Number.MAX_SAFE_INTEGER): number {
  ```
- `BUILTIN_SKILL_NAMES` ← src/cli-skill-names.ts:7 [EXTRACTED]
  ```
  export const BUILTIN_SKILL_NAMES = new Set(['teamai']);
  ```
- `LEGACY_BUILTIN_SKILL_NAMES` ← src/cli-skill-names.ts:19 [EXTRACTED]
  ```
  export const LEGACY_BUILTIN_SKILL_NAMES = new Set([
  ```
- `LEGACY_RECALL_SKILL_NAMES` ← src/cli-skill-names.ts:29 [EXTRACTED]
  ```
  export const LEGACY_RECALL_SKILL_NAMES = new Set(['teamai-share-learnings']);
  ```
- `isCliOwnedSkillName` ← src/cli-skill-names.ts:36 [EXTRACTED]
  ```
  export function isCliOwnedSkillName(name: string): boolean {
  ```
- `shallowClone` ← src/clone.ts:271 [EXTRACTED]
  ```
  export async function shallowClone(
  ```
- `shallowFetch` ← src/clone.ts:376 [EXTRACTED]
  ```
  export async function shallowFetch(
  ```
- `remoteHeadSha` ← src/clone.ts:408 [EXTRACTED]
  ```
  export async function remoteHeadSha(
  ```
- `spliceCodexAttribution` ← src/coauthor-reconcile.ts:414 [EXTRACTED]
  ```
  export function spliceCodexAttribution(source: string, enabled: boolean): string {
  ```
- `coAuthorLocalSettingsFiles` ← src/coauthor-reconcile.ts:501 [EXTRACTED]
  ```
  export async function coAuthorLocalSettingsFiles(
  ```
- `reconcileCoAuthorForConfig` ← src/coauthor-reconcile.ts:535 [EXTRACTED]
  ```
  export async function reconcileCoAuthorForConfig(
  ```
- `extractSourceDescriptions` ← src/code-knowledge-recall.ts:455 [EXTRACTED]
  ```
  export function extractSourceDescriptions(sources: string[], pageContent: string): SourceAnchor[] {
  ```
- `queryCodeKnowledge` ← src/code-knowledge-recall.ts:637 [EXTRACTED]
  ```
  export async function queryCodeKnowledge(
  ```
- `startDeepEnrich` ← src/codebase-cmd.ts:49 [EXTRACTED]
  ```
  export async function startDeepEnrich({ target, project, maxModules = 0, publish = false, json, command }: {
  ```
- `hiddenDeepEnrichTarget` ← src/codebase-cmd.ts:82 [EXTRACTED]
  ```
  export async function hiddenDeepEnrichTarget(wikiRoot: string | undefined): Promise<TeamwikiTarget> {
  ```
- `codebaseCmd` ← src/codebase-cmd.ts:114 [EXTRACTED]
  ```
  export async function codebaseCmd(opts: CodebaseCmdOptions): Promise<void> {
  ```
- `defaultProjectSlug` ← src/codebase-extract.ts:611 [EXTRACTED]
  ```
  export async function defaultProjectSlug(dir: string): Promise<string> {
  ```
- `checkoutName` ← src/codebase-extract.ts:636 [EXTRACTED]
  ```
  export async function checkoutName(dir: string): Promise<string> {
  ```
- `sourceRepositoryMetadata` ← src/codebase-extract.ts:749 [EXTRACTED]
  ```
  export async function sourceRepositoryMetadata(
  ```
- `extractCodebase` ← src/codebase-extract.ts:807 [EXTRACTED]
  ```
  export async function extractCodebase(opts: ExtractCodebaseOptions): Promise<boolean> {
  ```
- `annotateCodebaseSourceFreshness` ← src/codebase-freshness.ts:342 [EXTRACTED]
  ```
  export async function annotateCodebaseSourceFreshness(
  ```
- `upgradeCodebaseWiki` ← src/codebase-upgrade-wiki.ts:26 [EXTRACTED]
  ```
  export async function upgradeCodebaseWiki(opts: UpgradeCodebaseWikiOptions): Promise<void> {
  ```
- `lintTeamwiki` ← src/codebase-wiki-lint.ts:54 [EXTRACTED]
  ```
  export async function lintTeamwiki(opts: {
  ```
- `formatWikiLintReport` ← src/codebase-wiki-lint.ts:247 [EXTRACTED]
  ```
  export function formatWikiLintReport(report: WikiLintReport): string {
  ```
- `formatResourceGraphLine` ← src/codebase-wiki-lint.ts:300 [EXTRACTED]
  ```
  export function formatResourceGraphLine(graph: LintResourceGraph): string {
  ```
- `gatherRepoContext` ← src/codebase.ts:33 [EXTRACTED]
  ```
  export async function gatherRepoContext(repoPath: string): Promise<string> {
  ```
- `encodeCodebuddyProjectGate` ← src/codebuddy-team-hooks.ts:22 [EXTRACTED]
  ```
  export function encodeCodebuddyProjectGate(root: string, children: readonly string[] = []): string {
  ```
- `decodeCodebuddyProjectGate` ← src/codebuddy-team-hooks.ts:27 [EXTRACTED]
  ```
  export function decodeCodebuddyProjectGate(value: string): CodebuddyProjectGate | null {
  ```
- `parseCodebuddyTeamGate` ← src/codebuddy-team-hooks.ts:50 [EXTRACTED]
  ```
  export function parseCodebuddyTeamGate(command: string): RenderedCodebuddyTeamGate | null {
  ```
- `codebuddyTeamHookPayload` ← src/codebuddy-team-hooks.ts:75 [EXTRACTED]
  ```
  export function codebuddyTeamHookPayload(command: string): string | null {
  ```
- `regateCodebuddyTeamHookCommand` ← src/codebuddy-team-hooks.ts:82 [EXTRACTED]
  ```
  export function regateCodebuddyTeamHookCommand(
  ```
- `isCodebuddyTeamGateForProject` ← src/codebuddy-team-hooks.ts:111 [EXTRACTED]
  ```
  export function isCodebuddyTeamGateForProject(command: string, root: string): boolean {
  ```
- `runCodebuddyTeamHook` ← src/codebuddy-team-hooks.ts:152 [EXTRACTED]
  ```
  export async function runCodebuddyTeamHook(
  ```
- `codexProjectTrust` ← src/codex-project-trust.ts:30 [EXTRACTED]
  ```
  export async function codexProjectTrust(gate: Extract<ReadGate, { kind: 'codex-project-trust' }>): Promise<CodexProjectTrust> {
  ```
- `codexTrustFix` ← src/codex-project-trust.ts:65 [EXTRACTED]
  ```
  export function codexTrustFix(trust: Exclude<CodexProjectTrust, { kind: 'trusted' }>, gate: Extract<ReadGate, { kind: 'codex-project-trust' }>, cause: string): string {
  ```
- `isCodexTeamHookDispatcher` ← src/codex-team-hooks.ts:89 [EXTRACTED]
  ```
  export function isCodexTeamHookDispatcher(command: string): boolean {
  ```
- `codexTeamHookIndexPath` ← src/codex-team-hooks.ts:94 [EXTRACTED]
  ```
  export function codexTeamHookIndexPath(): string {
  ```
- `codexDispatcherProjects` ← src/codex-team-hooks.ts:108 [EXTRACTED]
  ```
  export async function codexDispatcherProjects(): Promise<string[]> {
  ```
- `codexDispatcherCheckouts` ← src/codex-team-hooks.ts:113 [EXTRACTED]
  ```
  export async function codexDispatcherCheckouts(project: string): Promise<Record<string, CodexTeamHook[]> | undefined> {
  ```
- `runsFromCodexDispatcher` ← src/codex-team-hooks.ts:118 [EXTRACTED]
  ```
  export async function runsFromCodexDispatcher(project: string, checkout?: string): Promise<boolean> {
  ```
- `dispatchedCodexHooks` ← src/codex-team-hooks.ts:123 [EXTRACTED]
  ```
  export async function dispatchedCodexHooks(project: string, checkout?: string): Promise<CodexTeamHook[] | undefined> {
  ```
- `setCodexDispatcherHooks` ← src/codex-team-hooks.ts:134 [EXTRACTED]
  ```
  export async function setCodexDispatcherHooks(project: string, hooks: CodexTeamHook[] | null, checkout?: string): Promise<boolean> {
  ```
- `reconcileCodexDispatchers` ← src/codex-team-hooks.ts:199 [EXTRACTED]
  ```
  export async function reconcileCodexDispatchers(hooksFile: string, codexTrust: CodexTrustPolicy): Promise<void> {
  ```
- `runCodexDispatcher` ← src/codex-team-hooks.ts:300 [EXTRACTED]
  ```
  export async function runCodexDispatcher(event: string): Promise<number> {
  ```
- `codexBuildsIdentity` ← src/codex-trust.ts:146 [EXTRACTED]
  ```
  export async function codexBuildsIdentity(commands?: readonly string[]): Promise<string> {
  ```
- `oldestCodexBuildVersion` ← src/codex-trust.ts:184 [EXTRACTED]
  ```
  export async function oldestCodexBuildVersion(): Promise<string | null> {
  ```
- `codexBuildSkewMessage` ← src/codex-trust.ts:274 [EXTRACTED]
  ```
  export function codexBuildSkewMessage(skew: CodexBuildSkew): string {
  ```
- `trustCodexProject` ← src/codex-trust.ts:503 [EXTRACTED]
  ```
  export async function trustCodexProject(req: CodexAt & { project: string }): Promise<CodexTrust> {
  ```
- `removeOwnedCodexProjectTrust` ← src/codex-trust.ts:516 [EXTRACTED]
  ```
  export async function removeOwnedCodexProjectTrust(req: CodexAt & { project: string }): Promise<
  ```
- `trustCodexHooks` ← src/codex-trust.ts:586 [EXTRACTED]
  ```
  export async function trustCodexHooks(req: CodexHookTrustRequest): Promise<CodexTrust> {
  ```
- `keepCodexHookTrust` ← src/codex-trust.ts:641 [EXTRACTED]
  ```
  export async function keepCodexHookTrust(
  ```
- `readCodexHookTrust` ← src/codex-trust.ts:714 [EXTRACTED]
  ```
  export async function readCodexHookTrust(req: Omit<CodexHookTrustRequest, 'project'>): Promise<CodexHookTrustReport> {
  ```
- `commandShell` ← src/command-shell.ts:12 [EXTRACTED]
  ```
  export function commandShell(env: NodeJS.ProcessEnv) {
  ```
- `resolveLegacyRole` ← src/config.ts:86 [EXTRACTED]
  ```
  export async function resolveLegacyRole(config: LocalConfig): Promise<LocalConfig> {
  ```
- `refreshRoleAssignment` ← src/config.ts:237 [EXTRACTED]
  ```
  export async function refreshRoleAssignment(config: LocalConfig): Promise<void> {
  ```
- `loadTeamConfig` ← src/config.ts:309 [EXTRACTED]
  ```
  export async function loadTeamConfig(repoPath: string, member: LocalConfig | null): Promise<TeamaiConfig | null> {
  ```
- `teamToolIds` ← src/config.ts:335 [EXTRACTED]
  ```
  export async function teamToolIds(repoPath: string, teamConfig: TeamaiConfig | null): Promise<string[]> {
  ```
- `loadTeamAgentLanguage` ← src/config.ts:351 [EXTRACTED]
  ```
  export async function loadTeamAgentLanguage(
  ```
- `loadMemberSettings` ← src/config.ts:497 [EXTRACTED]
  ```
  export async function loadMemberSettings(configPath = expandHome(getUserConfigPath())): Promise<MemberSettings> {
  ```
- `machineWorkflowAllowProblem` ← src/config.ts:532 [EXTRACTED]
  ```
  export async function machineWorkflowAllowProblem(): Promise<string | undefined> {
  ```
- `ownMemberSettings` ← src/config.ts:622 [EXTRACTED]
  ```
  export function ownMemberSettings(config: LocalConfig): MemberSettings {
  ```
- `markMemberSettingsWritten` ← src/config.ts:640 [EXTRACTED]
  ```
  export function markMemberSettingsWritten(config: LocalConfig, written: MemberSettings): LocalConfig {
  ```
- `hasUserScopeInstall` ← src/config.ts:679 [EXTRACTED]
  ```
  export async function hasUserScopeInstall(): Promise<boolean> {
  ```
- `loadLocalConfig` ← src/config.ts:708 [EXTRACTED]
  ```
  export async function loadLocalConfig(options: LoadOptions = {}): Promise<LocalConfig | null> {
  ```
- `saveLocalConfig` ← src/config.ts:781 [EXTRACTED]
  ```
  export async function saveLocalConfig(config: LocalConfig): Promise<void> {
  ```
- `loadState` ← src/config.ts:803 [EXTRACTED]
  ```
  export async function loadState(): Promise<State> {
  ```
- `saveState` ← src/config.ts:814 [EXTRACTED]
  ```
  export async function saveState(state: State): Promise<void> {
  ```
- `NotInitializedError` ← src/config.ts:827 [EXTRACTED]
  ```
  export class NotInitializedError extends Error {
  ```
- `TeamConfigNotFoundError` ← src/config.ts:832 [EXTRACTED]
  ```
  export class TeamConfigNotFoundError extends Error {
  ```
- `describeUnreadableConfig` ← src/config.ts:847 [EXTRACTED]
  ```
  export function describeUnreadableConfig(problem: string): string {
  ```
- `UnreadableProjectConfigError` ← src/config.ts:851 [EXTRACTED]
  ```
  export class UnreadableProjectConfigError extends Error {
  ```
- `isUninitialized` ← src/config.ts:862 [EXTRACTED]
  ```
  export async function isUninitialized(cwd?: string): Promise<boolean> {
  ```
- `requireInit` ← src/config.ts:875 [EXTRACTED]
  ```
  export async function requireInit(options: LoadOptions = {}): Promise<TeamaiInit> {
  ```
- `throwMissingOrInvalid` ← src/config.ts:893 [EXTRACTED]
  ```
  export async function throwMissingOrInvalid(configPath: string): Promise<never> {
  ```
- `loadTeamConfigIfPresent` ← src/config.ts:933 [EXTRACTED]
  ```
  export async function loadTeamConfigIfPresent(repoPath: string, member: LocalConfig | null): Promise<TeamaiConfig | null> {
  ```
- `loadLocalConfigForScope` ← src/config.ts:950 [EXTRACTED]
  ```
  export async function loadLocalConfigForScope(
  ```
- `saveLocalConfigForScope` ← src/config.ts:996 [EXTRACTED]
  ```
  export async function saveLocalConfigForScope(
  ```
- `loadStateForScope` ← src/config.ts:1035 [EXTRACTED]
  ```
  export async function loadStateForScope(localConfig: LocalConfig): Promise<State> {
  ```
- `saveStateForScope` ← src/config.ts:1047 [EXTRACTED]
  ```
  export async function saveStateForScope(state: State, localConfig: LocalConfig): Promise<void> {
  ```
- `resolveProjectDataHome` ← src/config.ts:1079 [EXTRACTED]
  ```
  export async function resolveProjectDataHome(projectRoot: string, options: LoadOptions = {}): Promise<string> {
  ```
- `resolveDataHomeForScope` ← src/config.ts:1100 [EXTRACTED]
  ```
  export async function resolveDataHomeForScope(scope: Scope, projectRoot?: string): Promise<string> {
  ```
- `resolveConfigForDir` ← src/config.ts:1126 [EXTRACTED]
  ```
  export async function resolveConfigForDir(
  ```
- `resolveMemberToolRoots` ← src/config.ts:1163 [EXTRACTED]
  ```
  export async function resolveMemberToolRoots(
  ```
- `detectProjectConfig` ← src/config.ts:1181 [EXTRACTED]
  ```
  export async function detectProjectConfig(
  ```
- `readEphemeralConfig` ← src/config.ts:1263 [EXTRACTED]
  ```
  export async function readEphemeralConfig(file: string, cwd: string): Promise<LocalConfig | null> {
  ```
- `readConfigFrom` ← src/config.ts:1314 [EXTRACTED]
  ```
  export async function readConfigFrom(
  ```
- `findUnreadableProjectConfig` ← src/config.ts:1492 [EXTRACTED]
  ```
  export async function findUnreadableProjectConfig(cwd?: string, options: LoadOptions = {}): Promise<string | null> {
  ```
- `requireInitForScope` ← src/config.ts:1504 [EXTRACTED]
  ```
  export async function requireInitForScope(
  ```
- `autoDetectInit` ← src/config.ts:1535 [EXTRACTED]
  ```
  export async function autoDetectInit(cwd?: string, options: LoadOptions & { children?: boolean } = {}): Promise<TeamaiInit> {
  ```
- `sanitizeSessionId` ← src/contribute-check.ts:76 [EXTRACTED]
  ```
  export function sanitizeSessionId(sessionId: string): string {
  ```
- `readContributeState` ← src/contribute-check.ts:146 [EXTRACTED]
  ```
  export async function readContributeState(sessionId: string): Promise<ContributeState> {
  ```
- `writeContributeState` ← src/contribute-check.ts:180 [EXTRACTED]
  ```
  export async function writeContributeState(sessionId: string, state: ContributeState): Promise<void> {
  ```
- `REMINDER_RECORD_DAYS` ← src/contribute-check.ts:205 [EXTRACTED]
  ```
  export const REMINDER_RECORD_DAYS = 30;
  ```
- `cleanupStaleSessions` ← src/contribute-check.ts:252 [EXTRACTED]
  ```
  export async function cleanupStaleSessions(dir: string, currentSessionId: string): Promise<void> {
  ```
- `readReminderDecisions` ← src/contribute-check.ts:309 [EXTRACTED]
  ```
  export async function readReminderDecisions(): Promise<Map<string, boolean>> {
  ```
- `computeSmartScore` ← src/contribute-check.ts:358 [EXTRACTED]
  ```
  export function computeSmartScore(params: FrictionReminderParams, events: DashboardEvent[], friction?: SessionFriction): number {
  ```
- `hasGitCommitInSession` ← src/contribute-check.ts:405 [EXTRACTED]
  ```
  export function hasGitCommitInSession(cwd: string, sessionStartIso: string): boolean {
  ```
- `applyPhase2Adjustments` ← src/contribute-check.ts:427 [EXTRACTED]
  ```
  export function applyPhase2Adjustments(
  ```
- `contributeCheckForSession` ← src/contribute-check.ts:653 [EXTRACTED]
  ```
  export async function contributeCheckForSession(
  ```
- `takePendingHint` ← src/contribute-check.ts:828 [EXTRACTED]
  ```
  export async function takePendingHint(sessionId: string): Promise<string | null> {
  ```
- `contributeCheck` ← src/contribute-check.ts:850 [EXTRACTED]
  ```
  export async function contributeCheck(toolArg?: string): Promise<void> {
  ```
- `markContributed` ← src/contribute-check.ts:911 [EXTRACTED]
  ```
  export async function markContributed(sessionId: string): Promise<void> {
  ```
- `resolveLearningsSubdir` ← src/contribute.ts:45 [EXTRACTED]
  ```
  export async function resolveLearningsSubdir(localConfig: LocalConfig): Promise<string> {
  ```
- `rebuildIndexAfterContribute` ← src/contribute.ts:68 [EXTRACTED]
  ```
  export async function rebuildIndexAfterContribute(localConfig: LocalConfig): Promise<void> {
  ```
- `KEPT_FOR_ITS_INSTALL` ← src/contribute.ts:120 [EXTRACTED]
  ```
  export const KEPT_FOR_ITS_INSTALL =
  ```
- `KEPT_UNTIL_CHECKOUT_SETTLED` ← src/contribute.ts:124 [EXTRACTED]
  ```
  export const KEPT_UNTIL_CHECKOUT_SETTLED =
  ```
- `generateFilename` ← src/contribute.ts:136 [EXTRACTED]
  ```
  export function generateFilename(title?: string): string {
  ```
- `contribute` ← src/contribute.ts:334 [EXTRACTED]
  ```
  export async function contribute(
  ```
- `claimCopilotHookEvent` ← src/copilot-hook-claim.ts:60 [EXTRACTED]
  ```
  export function claimCopilotHookEvent(event: string, matcher: string, raw: string, env: NodeJS.ProcessEnv = process.env): boolean {
  ```
- `cursorUserRulesDir` ← src/cursor-user-rules.ts:43 [EXTRACTED]
  ```
  export async function cursorUserRulesDir(teamConfig: TeamaiConfig, userConfig: LocalConfig): Promise<string | undefined> {
  ```
- `cursorUserRulesText` ← src/cursor-user-rules.ts:50 [EXTRACTED]
  ```
  export async function cursorUserRulesText(teamConfig: TeamaiConfig, userConfig: LocalConfig): Promise<string | null> {
  ```
- `cursorUserRulesContext` ← src/cursor-user-rules.ts:63 [EXTRACTED]
  ```
  export async function cursorUserRulesContext(workspace: string, config: LocalConfig): Promise<string | null> {
  ```
- `readLastAssistantOutput` ← src/dashboard-collector.ts:79 [EXTRACTED]
  ```
  export async function readLastAssistantOutput(transcriptPath: string): Promise<string> {
  ```
- `REQUEST_LOG_RETENTION_DAYS` ← src/dashboard-collector.ts:150 [EXTRACTED]
  ```
  export const REQUEST_LOG_RETENTION_DAYS = 90;
  ```
- `scanTranscriptStop` ← src/dashboard-collector.ts:297 [EXTRACTED]
  ```
  export async function scanTranscriptStop(transcriptPath: string): Promise<TranscriptScanResult> {
  ```
- `TranscriptEntrySchema` ← src/dashboard-collector.ts:327 [EXTRACTED]
  ```
  export const TranscriptEntrySchema = z.object({
  ```
- `isHumanPromptEntry` ← src/dashboard-collector.ts:345 [EXTRACTED]
  ```
  export function isHumanPromptEntry(entry: TranscriptEntry): boolean {
  ```
- `resolveCopilotUsageTranscript` ← src/dashboard-collector.ts:741 [EXTRACTED]
  ```
  export function resolveCopilotUsageTranscript(
  ```
- `countInterventions` ← src/dashboard-collector.ts:949 [EXTRACTED]
  ```
  export async function countInterventions(
  ```
- `parseHookEvent` ← src/dashboard-collector.ts:1075 [EXTRACTED]
  ```
  export async function parseHookEvent(
  ```
- `getEventsPath` ← src/dashboard-collector.ts:1375 [EXTRACTED]
  ```
  export function getEventsPath(): string {
  ```
- `readLocalRequestRecords` ← src/dashboard-collector.ts:1397 [EXTRACTED]
  ```
  export async function readLocalRequestRecords(): Promise<Map<string, LocalRequestRecord>> {
  ```
- `reconcileRequestLog` ← src/dashboard-collector.ts:1441 [EXTRACTED]
  ```
  export async function reconcileRequestLog(
  ```
- `dataHomeKey` ← src/dashboard-collector.ts:1511 [EXTRACTED]
  ```
  export async function dataHomeKey(dataHome: string): Promise<string> {
  ```
- `appendEvent` ← src/dashboard-collector.ts:1671 [EXTRACTED]
  ```
  export async function appendEvent(event: DashboardEvent | SessionOutcomeEvent): Promise<void> {
  ```
- `SESSION_OUTCOME_RETENTION_MS` ← src/dashboard-collector.ts:1756 [EXTRACTED]
  ```
  export const SESSION_OUTCOME_RETENTION_MS = 30 * 24 * 60 * 60 * 1000;
  ```
- `readSessionOutcomes` ← src/dashboard-collector.ts:1759 [EXTRACTED]
  ```
  export async function readSessionOutcomes(eventsPath?: string): Promise<SessionOutcomeEvent[]> {
  ```
- `dedupeEvents` ← src/dashboard-collector.ts:1823 [EXTRACTED]
  ```
  export function dedupeEvents(events: DashboardEvent[]): DashboardEvent[] {
  ```
- `readEvents` ← src/dashboard-collector.ts:1856 [EXTRACTED]
  ```
  export async function readEvents(eventsPath?: string): Promise<DashboardEvent[]> {
  ```
- `rebuildSessions` ← src/dashboard-collector.ts:1890 [EXTRACTED]
  ```
  export function rebuildSessions(events: DashboardEvent[], outcomes: readonly SessionOutcomeEvent[] = []): DashboardSession[] {
  ```
- `memberEvents` ← src/dashboard-collector.ts:2075 [EXTRACTED]
  ```
  export function memberEvents(events: DashboardEvent[]): DashboardEvent[] {
  ```
- `sessionRuns` ← src/dashboard-collector.ts:2096 [EXTRACTED]
  ```
  export function sessionRuns(events: DashboardEvent[]): Map<string, SessionRun> {
  ```
- `aggregateSessionMetrics` ← src/dashboard-collector.ts:2123 [EXTRACTED]
  ```
  export function aggregateSessionMetrics(
  ```
- `aggregateSessionInterventions` ← src/dashboard-collector.ts:2348 [EXTRACTED]
  ```
  export function aggregateSessionInterventions(
  ```
- `compactEvents` ← src/dashboard-collector.ts:2373 [EXTRACTED]
  ```
  export async function compactEvents(eventsPath?: string): Promise<void> {
  ```
- `recordedHookCwd` ← src/dashboard-collector.ts:2516 [EXTRACTED]
  ```
  export async function recordedHookCwd(hookData: HookStdin, tool: string): Promise<string | undefined> {
  ```
- `hookScopeDir` ← src/dashboard-collector.ts:2556 [EXTRACTED]
  ```
  export async function hookScopeDir(hookData: HookStdin, tool: string): Promise<string | undefined> {
  ```
- `resolveHookScopeFor` ← src/dashboard-collector.ts:2591 [EXTRACTED]
  ```
  export async function resolveHookScopeFor(hookData: HookStdin, tool: string): Promise<{ config: LocalConfig | null; dir: string | undefined }> {
  ```
- `resolveHookConfig` ← src/dashboard-collector.ts:2620 [EXTRACTED]
  ```
  export async function resolveHookConfig(hookData: HookStdin, tool: string): Promise<LocalConfig | null> {
  ```
- `eventRepoAnchor` ← src/dashboard-collector.ts:2644 [EXTRACTED]
  ```
  export async function eventRepoAnchor(cwd: string | undefined, sessionId: string): Promise<string | undefined> {
  ```
- `GIT_AT_START_PAYLOAD_KEY` ← src/dashboard-collector.ts:2660 [EXTRACTED]
  ```
  export const GIT_AT_START_PAYLOAD_KEY = 'teamai_git_at_start';
  ```
- `gitStateIn` ← src/dashboard-collector.ts:2666 [EXTRACTED]
  ```
  export function gitStateIn(payload: HookStdin): HeadState | null | undefined {
  ```
- `readGitStateAtStart` ← src/dashboard-collector.ts:2677 [EXTRACTED]
  ```
  export async function readGitStateAtStart(cwd: string): Promise<HeadState | null> {
  ```
- `addGitStateAtStart` ← src/dashboard-collector.ts:2698 [EXTRACTED]
  ```
  export async function addGitStateAtStart(event: DashboardEvent, known?: HeadState | null): Promise<void> {
  ```
- `GIT_AT_STOP_PAYLOAD_KEY` ← src/dashboard-collector.ts:2709 [EXTRACTED]
  ```
  export const GIT_AT_STOP_PAYLOAD_KEY = 'teamai_git_at_stop';
  ```
- `gitStateAtStopIn` ← src/dashboard-collector.ts:2717 [EXTRACTED]
  ```
  export function gitStateAtStopIn(payload: HookStdin): GitStateAtStop | null | undefined {
  ```
- `readGitStateAtStop` ← src/dashboard-collector.ts:2728 [EXTRACTED]
  ```
  export async function readGitStateAtStop(cwd: string): Promise<GitStateAtStop | null> {
  ```
- `addGitHeadAtStop` ← src/dashboard-collector.ts:2745 [EXTRACTED]
  ```
  export async function addGitHeadAtStop(event: DashboardEvent, known?: GitStateAtStop | null): Promise<void> {
  ```
- `dashboardReport` ← src/dashboard-collector.ts:2782 [EXTRACTED]
  ```
  export async function dashboardReport(toolArg?: string): Promise<void> {
  ```
- `getDashboardHtml` ← src/dashboard-html.ts:7 [EXTRACTED]
  ```
  export function getDashboardHtml(_port: number): string {
  ```
- `filterEventsByScope` ← src/dashboard-scope.ts:53 [EXTRACTED]
  ```
  export async function filterEventsByScope(
  ```
- `runsOfLog` ← src/dashboard-scope.ts:336 [EXTRACTED]
  ```
  export async function runsOfLog(events: DashboardEvent[]): Promise<DashboardEvent[]> {
  ```
- `startDashboard` ← src/dashboard.ts:52 [EXTRACTED]
  ```
  export async function startDashboard(port?: number): Promise<void> {
  ```
- `DeepEnrich` ← src/deep-enrich.ts:1337 [EXTRACTED]
  ```
  export const DeepEnrich = { targetOf, plan, write, graph, finish, publish } as const;
  ```
- `resolveDefaultDriver` ← src/default-driver.ts:23 [EXTRACTED]
  ```
  export async function resolveDefaultDriver(config: LocalConfig, team: Pick<TeamaiConfig, 'workflows'> | null): Promise<ResolvedDefaultDriver> {
  ```
- `drivesHere` ← src/default-driver.ts:75 [EXTRACTED]
  ```
  export async function drivesHere(config: LocalConfig, name: DriverName): Promise<boolean> {
  ```
- `driveByDefault` ← src/default-driver.ts:80 [EXTRACTED]
  ```
  export async function driveByDefault(config: LocalConfig): Promise<DefaultDrive> {
  ```
- `awaitsOf` ← src/default-driver.ts:90 [EXTRACTED]
  ```
  export function awaitsOf(decided: DefaultDrive): RunState['awaits'] {
  ```
- `awaitsLine` ← src/default-driver.ts:98 [EXTRACTED]
  ```
  export async function awaitsLine(config: LocalConfig, run: string, driver: DriverName): Promise<string> {
  ```
- `leftOpenLine` ← src/default-driver.ts:117 [EXTRACTED]
  ```
  export function leftOpenLine(run: string, workflow: string): string {
  ```
- `teamaiPackageDir` ← src/default-drivers.ts:11 [EXTRACTED]
  ```
  export function teamaiPackageDir(): string {
  ```
- `shippedDriverFile` ← src/default-drivers.ts:25 [EXTRACTED]
  ```
  export function shippedDriverFile(name: string): string {
  ```
- `teamaiBin` ← src/default-drivers.ts:37 [EXTRACTED]
  ```
  export function teamaiBin(name: string, packageDir = teamaiPackageDir()): string | undefined {
  ```
- `DefaultFolders` ← src/default-folders.ts:519 [EXTRACTED]
  ```
  export const DefaultFolders = { names, isName, read, load, problems, compare } as const;
  ```
- `DefaultScorers` ← src/default-scorers.ts:156 [EXTRACTED]
  ```
  export const DefaultScorers = { NAMES, VARIABLES, isName, shipped, problems, fillIn } as const;
  ```
- `RunOriginSchema` ← src/default-workflows.ts:106 [EXTRACTED]
  ```
  export const RunOriginSchema = z.discriminatedUnion('source', [
  ```
- `DefaultWorkflows` ← src/default-workflows.ts:171 [EXTRACTED]
  ```
  export const DefaultWorkflows = { PREFIX, SHARE_LEARNINGS, layer, isShipped, originOf, sourceOfRun, overrideProblems, callerWarnings, isGuarded } as const;
  ```
- `DigestFailures` ← src/digest-failures.ts:75 [EXTRACTED]
  ```
  export const DigestFailures = { WINDOW_DAYS, read, print } as const;
  ```
- `buildSkillChangePathspec` ← src/digest.ts:112 [EXTRACTED]
  ```
  export function buildSkillChangePathspec(subdir = '') {
  ```
- `summarizeInterventions` ← src/digest.ts:307 [EXTRACTED]
  ```
  export function summarizeInterventions(teamStats: UserStats[]): InterventionSummary | null {
  ```
- `splitByRunMode` ← src/digest.ts:350 [EXTRACTED]
  ```
  export function splitByRunMode(teamStats: UserStats[], count: (stats: UserModeStats | undefined) => number): RunModeSplit {
  ```
- `formatOutcomeLines` ← src/digest.ts:377 [EXTRACTED]
  ```
  export function formatOutcomeLines(teamStats: UserStats[]): string[] {
  ```
- `formatTokenCount` ← src/digest.ts:414 [EXTRACTED]
  ```
  export function formatTokenCount(n: number): string {
  ```
- `summarizeConversation` ← src/digest.ts:426 [EXTRACTED]
  ```
  export function summarizeConversation(teamStats: UserStats[]): ConversationSummary | null {
  ```
- `summarizeTeamTrends` ← src/digest.ts:451 [EXTRACTED]
  ```
  export function summarizeTeamTrends(teamStats: UserStats[], now = new Date()): ReturnType<typeof summarizeTrendWindow> | null {
  ```
- `formatTrendLines` ← src/digest.ts:479 [EXTRACTED]
  ```
  export function formatTrendLines(periods: { current: TrendPeriod; previous: TrendPeriod }): string[] {
  ```
- `generateDigest` ← src/digest.ts:495 [EXTRACTED]
  ```
  export async function generateDigest(): Promise<void> {
  ```
- `heldAgentNames` ← src/doctor-agent-models.ts:95 [EXTRACTED]
  ```
  export async function heldAgentNames(ctx: DoctorContext): Promise<Set<string>> {
  ```
- `buildAgentModelChecks` ← src/doctor-agent-models.ts:114 [EXTRACTED]
  ```
  export async function buildAgentModelChecks(ctx: DoctorContext, stage: CheckStage): Promise<Check[]> {
  ```
- `loadFailure` ← src/doctor-agent-models.ts:172 [EXTRACTED]
  ```
  export function loadFailure(aliases: ModelAliases): string | undefined {
  ```
- `agentModelNotes` ← src/doctor-agent-models.ts:193 [EXTRACTED]
  ```
  export async function agentModelNotes(ctx: DoctorContext): Promise<string[]> {
  ```
- `aliasNamespaceNotes` ← src/doctor-agent-models.ts:283 [EXTRACTED]
  ```
  export async function aliasNamespaceNotes(ctx: DoctorContext): Promise<string[]> {
  ```
- `nameList` ← src/doctor-delivery.ts:248 [EXTRACTED]
  ```
  export function nameList(names: string[]): string {
  ```
- `readGateChecks` ← src/doctor-delivery.ts:256 [EXTRACTED]
  ```
  export async function readGateChecks(gates: readonly ReadGate[], held: Held): Promise<Check[]> {
  ```
- `toolPathsDroppedKeyNotes` ← src/doctor-delivery.ts:306 [EXTRACTED]
  ```
  export function toolPathsDroppedKeyNotes(ctx: DoctorContext): string[] {
  ```
- `buildDeliveryChecks` ← src/doctor-delivery.ts:352 [EXTRACTED]
  ```
  export async function buildDeliveryChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildSkillDirChecks` ← src/doctor-delivery.ts:460 [EXTRACTED]
  ```
  export async function buildSkillDirChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `skillReadNotes` ← src/doctor-delivery.ts:601 [EXTRACTED]
  ```
  export async function skillReadNotes(ctx: DoctorContext): Promise<string[]> {
  ```
- `buildRecordedPlaceChecks` ← src/doctor-delivery.ts:672 [EXTRACTED]
  ```
  export async function buildRecordedPlaceChecks(ctx: DoctorContext, resource: 'rules' | 'blocks'): Promise<Check[]> {
  ```
- `recordedPlaceNotes` ← src/doctor-delivery.ts:714 [EXTRACTED]
  ```
  export async function recordedPlaceNotes(ctx: DoctorContext, resource: 'rules' | 'blocks'): Promise<string[]> {
  ```
- `buildRulesDeliveryChecks` ← src/doctor-delivery.ts:752 [EXTRACTED]
  ```
  export async function buildRulesDeliveryChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildAgentsDeliveryChecks` ← src/doctor-delivery.ts:1421 [EXTRACTED]
  ```
  export async function buildAgentsDeliveryChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildAgentPlaceChecks` ← src/doctor-delivery.ts:1603 [EXTRACTED]
  ```
  export async function buildAgentPlaceChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `mcpTransportNotes` ← src/doctor-delivery.ts:1752 [EXTRACTED]
  ```
  export async function mcpTransportNotes(ctx: DoctorContext): Promise<string[]> {
  ```
- `buildMcpDeliveryChecks` ← src/doctor-delivery.ts:1805 [EXTRACTED]
  ```
  export async function buildMcpDeliveryChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildMcpReadFileChecks` ← src/doctor-delivery.ts:1944 [EXTRACTED]
  ```
  export async function buildMcpReadFileChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildLocalAgentMcpLocationChecks` ← src/doctor-delivery.ts:2002 [EXTRACTED]
  ```
  export async function buildLocalAgentMcpLocationChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildHookReadGateChecks` ← src/doctor-delivery.ts:2041 [EXTRACTED]
  ```
  export async function buildHookReadGateChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildMcpReadGateChecks` ← src/doctor-delivery.ts:2072 [EXTRACTED]
  ```
  export async function buildMcpReadGateChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildMcpGitExcludeCheck` ← src/doctor-delivery.ts:2116 [EXTRACTED]
  ```
  export async function buildMcpGitExcludeCheck(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildEntryScopeKeyCheck` ← src/doctor-delivery.ts:2231 [EXTRACTED]
  ```
  export async function buildEntryScopeKeyCheck(ctx: DoctorContext): Promise<Check[]> {
  ```
- `retiredBuiltinOverrideNotes` ← src/doctor-delivery.ts:2255 [EXTRACTED]
  ```
  export async function retiredBuiltinOverrideNotes(ctx: DoctorContext): Promise<string[]> {
  ```
- `buildEntryResolutionChecks` ← src/doctor-delivery.ts:2275 [EXTRACTED]
  ```
  export async function buildEntryResolutionChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildSecretValuesCheck` ← src/doctor-delivery.ts:2293 [EXTRACTED]
  ```
  export function buildSecretValuesCheck(ctx: DoctorContext): Check[] {
  ```
- `entryNamespaceNotes` ← src/doctor-delivery.ts:2317 [EXTRACTED]
  ```
  export async function entryNamespaceNotes(ctx: DoctorContext): Promise<string[]> {
  ```
- `buildEnvDeliveryCheck` ← src/doctor-delivery.ts:2369 [EXTRACTED]
  ```
  export async function buildEnvDeliveryCheck(ctx: DoctorContext): Promise<Check[]> {
  ```
- `envLoaderNotes` ← src/doctor-delivery.ts:2441 [EXTRACTED]
  ```
  export async function envLoaderNotes(ctx: DoctorContext): Promise<string[]> {
  ```
- `buildDocsCheck` ← src/doctor-delivery.ts:2677 [EXTRACTED]
  ```
  export async function buildDocsCheck(ctx: DoctorContext): Promise<Check[]> {
  ```
- `keptDocNotes` ← src/doctor-delivery.ts:2791 [EXTRACTED]
  ```
  export async function keptDocNotes(ctx: DoctorContext): Promise<string[]> {
  ```
- `buildNamespaceNotes` ← src/doctor-delivery.ts:2857 [EXTRACTED]
  ```
  export async function buildNamespaceNotes(ctx: DoctorContext): Promise<string[]> {
  ```
- `buildInstructionDeliveryChecks` ← src/doctor-delivery.ts:2976 [EXTRACTED]
  ```
  export async function buildInstructionDeliveryChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildDeliveredGitExcludeChecks` ← src/doctor-git-exclude.ts:152 [EXTRACTED]
  ```
  export async function buildDeliveredGitExcludeChecks(ctx: DoctorContext): Promise<Check[]> {
  ```
- `buildLocalAgentGitExcludeChecks` ← src/doctor-git-exclude.ts:244 [EXTRACTED]
  ```
  export async function buildLocalAgentGitExcludeChecks(): Promise<Check[]> {
  ```
- `localAgentGitExcludeNotes` ← src/doctor-git-exclude.ts:257 [EXTRACTED]
  ```
  export async function localAgentGitExcludeNotes(): Promise<string[]> {
  ```
- `deliveredGitExcludeNotes` ← src/doctor-git-exclude.ts:269 [EXTRACTED]
  ```
  export async function deliveredGitExcludeNotes(ctx: DoctorContext): Promise<string[]> {
  ```
- `buildSandboxProfileChecks` ← src/doctor-sandboxes.ts:20 [EXTRACTED]
  ```
  export async function buildSandboxProfileChecks({ localConfig, teamConfig }: { localConfig: LocalConfig; teamConfig: Pick<TeamaiConfig, 'workflows'> | null }, checkout: string): Promise<Check[]> {
  ```
- `scorerNotes` ← src/doctor-scorers.ts:98 [EXTRACTED]
  ```
  export async function scorerNotes(localConfig: LocalConfig, { resolveTool }: { resolveTool?: ResolveTool } = {}): Promise<string[]> {
  ```
- `resolveDoctorContext` ← src/doctor.ts:787 [EXTRACTED]
  ```
  export async function resolveDoctorContext(options: { gitContext?: GitContext } = {}): Promise<DoctorContext | null> {
  ```
- `buildChecks` ← src/doctor.ts:857 [EXTRACTED]
  ```
  export async function buildChecks(ctx: DoctorContext, stage: CheckStage = 'doctor'): Promise<Check[]> {
  ```
- `runChecks` ← src/doctor.ts:1120 [EXTRACTED]
  ```
  export async function runChecks(
  ```
- `formatCheckResult` ← src/doctor.ts:1167 [EXTRACTED]
  ```
  export function formatCheckResult({ name, ok, warning, fix }: CheckResult): string[] {
  ```
- `doctor` ← src/doctor.ts:1187 [EXTRACTED]
  ```
  export async function doctor(options: DoctorOptions): Promise<boolean> {
  ```
- `DriverSchema` ← src/driver-identity.ts:6 [EXTRACTED]
  ```
  export const DriverSchema = z.object({ kind: z.string(), machine: z.string(), workspace: z.string() });
  ```
- `driverIdentity` ← src/driver-identity.ts:9 [EXTRACTED]
  ```
  export function driverIdentity(kind: string, workspace: string): z.infer<typeof DriverSchema> {
  ```
- `sameDriver` ← src/driver-identity.ts:22 [EXTRACTED]
  ```
  export function sameDriver(left: z.infer<typeof DriverSchema>, right: z.infer<typeof DriverSchema>): boolean {
  ```
- `NO_DRY_RUN_PREVIEW` ← src/dry-run-guard.ts:112 [EXTRACTED]
  ```
  export const NO_DRY_RUN_PREVIEW = {
  ```
- `noDryRunPreview` ← src/dry-run-guard.ts:192 [EXTRACTED]
  ```
  export function noDryRunPreview(command: string): string {
  ```
- `dryRunRefusal` ← src/dry-run-guard.ts:197 [EXTRACTED]
  ```
  export function dryRunRefusal(command: Command): string | undefined {
  ```
- `DSH_PATCH_FILE` ← src/dsh-hooks.ts:21 [EXTRACTED]
  ```
  export const DSH_PATCH_FILE = 'cordis.patch.yml';
  ```
- `DSH_HOOK_PLUGIN_ID` ← src/dsh-hooks.ts:22 [EXTRACTED]
  ```
  export const DSH_HOOK_PLUGIN_ID = 'teamai-hooks-claude-code';
  ```
- `DSH_HOOK_PLUGIN_PACKAGE` ← src/dsh-hooks.ts:23 [EXTRACTED]
  ```
  export const DSH_HOOK_PLUGIN_PACKAGE = '@deepseek-ai/dsh-hooks-claude-code';
  ```
- `isDshInstalled` ← src/dsh-hooks.ts:29 [EXTRACTED]
  ```
  export async function isDshInstalled(): Promise<boolean> {
  ```
- `resolveDshHookConfigPath` ← src/dsh-hooks.ts:33 [EXTRACTED]
  ```
  export function resolveDshHookConfigPath(): string {
  ```
- `resolveDshPatchPath` ← src/dsh-hooks.ts:42 [EXTRACTED]
  ```
  export function resolveDshPatchPath(): string {
  ```
- `resolveDshHomePatchPath` ← src/dsh-hooks.ts:49 [EXTRACTED]
  ```
  export function resolveDshHomePatchPath(): string {
  ```
- `isDshHooksMounted` ← src/dsh-hooks.ts:111 [EXTRACTED]
  ```
  export async function isDshHooksMounted(configPath: string): Promise<boolean> {
  ```
- `dshSandboxNote` ← src/dsh-hooks.ts:127 [EXTRACTED]
  ```
  export async function dshSandboxNote(localConfig: Pick<LocalConfig, 'disabledAgents' | 'enabledAgents'>): Promise<string | null> {
  ```
- `reconcileDshHooks` ← src/dsh-hooks.ts:153 [EXTRACTED]
  ```
  export async function reconcileDshHooks(
  ```
- `groupFactsByModule` ← src/enrich-with-ai.ts:123 [EXTRACTED]
  ```
  export function groupFactsByModule(facts: CodeFact[]): Map<string, CodeFact[]> {
  ```
- `buildFallbackManifest` ← src/enrich-with-ai.ts:154 [EXTRACTED]
  ```
  export function buildFallbackManifest(ctx: {
  ```
- `describeEvidenceManifest` ← src/enrich-with-ai.ts:200 [EXTRACTED]
  ```
  export function describeEvidenceManifest(source: 'ai' | 'fallback' | 'none', componentCount: number): string | undefined {
  ```
- `writeEnrichResult` ← src/enrich-with-ai.ts:305 [EXTRACTED]
  ```
  export async function writeEnrichResult(result: EnrichResult, evidenceDir: string): Promise<string> {
  ```
- `CodebaseEnrich` ← src/enrich-with-ai.ts:466 [EXTRACTED]
  ```
  export const CodebaseEnrich = { targetOf, plan, repliesOf, summary, write } as const;
  ```
- `parseEdgeProvenance` ← src/enrich-with-ai.ts:480 [EXTRACTED]
  ```
  export function parseEdgeProvenance(detail: string): EdgeProvenance {
  ```
- `edgeProvenanceRank` ← src/enrich-with-ai.ts:502 [EXTRACTED]
  ```
  export function edgeProvenanceRank(provenance: EdgeProvenance): number {
  ```
- `edgeReason` ← src/enrich-with-ai.ts:520 [EXTRACTED]
  ```
  export function edgeReason(from: string, to: string, relation: string): string {
  ```
- `writeManifest` ← src/enrich-with-ai.ts:531 [EXTRACTED]
  ```
  export async function writeManifest(manifest: CodebaseOutputManifestV2, outputDir: string): Promise<string> {
  ```
- `envAdvisories` ← src/env-advisories.ts:41 [EXTRACTED]
  ```
  export async function envAdvisories(
  ```
- `reportMissingSecrets` ← src/env-advisories.ts:109 [EXTRACTED]
  ```
  export async function reportMissingSecrets(localConfig: LocalConfig, teamEnv?: TeamEnv): Promise<void> {
  ```
- `describeEnvAdvisory` ← src/env-advisories.ts:141 [EXTRACTED]
  ```
  export function describeEnvAdvisory(advisory: EnvAdvisory): string {
  ```
- `envList` ← src/env-commands.ts:34 [EXTRACTED]
  ```
  export async function envList(options: GlobalOptions & { reveal?: boolean }): Promise<void> {
  ```
- `envSet` ← src/env-commands.ts:80 [EXTRACTED]
  ```
  export async function envSet(
  ```
- `envUnset` ← src/env-commands.ts:198 [EXTRACTED]
  ```
  export async function envUnset(key: string, options: GlobalOptions & { global?: boolean }): Promise<void> {
  ```
- `envAdd` ← src/env-commands.ts:424 [EXTRACTED]
  ```
  export async function envAdd(
  ```
- `envRemove` ← src/env-commands.ts:619 [EXTRACTED]
  ```
  export async function envRemove(
  ```
- `commandSignalPolicy` ← src/env-exec.ts:60 [EXTRACTED]
  ```
  export function commandSignalPolicy(reachesCommand: boolean): CommandSignalPolicy {
  ```
- `terminalReachesCommand` ← src/env-exec.ts:74 [EXTRACTED]
  ```
  export async function terminalReachesCommand(): Promise<boolean> {
  ```
- `envExec` ← src/env-exec.ts:87 [EXTRACTED]
  ```
  export async function envExec(words: readonly string[], options: GlobalOptions, cwd = process.cwd()): Promise<ExecOutcome> {
  ```
- `exitLike` ← src/env-exec.ts:127 [EXTRACTED]
  ```
  export function exitLike(outcome: ExecOutcome): void {
  ```
- `stepEnvironment` ← src/env-exec.ts:414 [EXTRACTED]
  ```
  export async function stepEnvironment(
  ```
- `withRunningCli` ← src/env-exec.ts:438 [EXTRACTED]
  ```
  export function withRunningCli(env: NodeJS.ProcessEnv): NodeJS.ProcessEnv {
  ```
- `envListing` ← src/env-listing.ts:36 [EXTRACTED]
  ```
  export function envListing(teamEnv: TeamEnv, options: { reveal?: boolean; verbose?: boolean }): EnvListing {
  ```
- `isReservedTeamEnvKey` ← src/env-reserved.ts:25 [EXTRACTED]
  ```
  export function isReservedTeamEnvKey(key: string): boolean {
  ```
- `reservedTeamEnvKeys` ← src/env-reserved.ts:33 [EXTRACTED]
  ```
  export function reservedTeamEnvKeys(keys: Iterable<string>): string[] {
  ```
- `reservedTeamEnvWarning` ← src/env-reserved.ts:38 [EXTRACTED]
  ```
  export function reservedTeamEnvWarning(keys: Iterable<string>): string | null {
  ```
- `resolveTeamEnv` ← src/env-resolution.ts:117 [EXTRACTED]
  ```
  export async function resolveTeamEnv(
  ```
- `resolvesTeamEnv` ← src/env-resolution.ts:189 [EXTRACTED]
  ```
  export function resolvesTeamEnv(localConfig: LocalConfig): boolean {
  ```
- `appliedTeamEnv` ← src/env-resolution.ts:208 [EXTRACTED]
  ```
  export function appliedTeamEnv(teamEnv: TeamEnv): AppliedTeamEnv {
  ```
- `effectiveTeamEnvVariables` ← src/env-resolution.ts:264 [EXTRACTED]
  ```
  export function effectiveTeamEnvVariables(teamEnv: TeamEnv): readonly ResolvedEntry<EnvVariable>[] {
  ```
- `collectTeamSecrets` ← src/env-resolution.ts:377 [EXTRACTED]
  ```
  export async function collectTeamSecrets(localConfig: LocalConfig, env: NodeJS.ProcessEnv = process.env): Promise<Record<string, string>> {
  ```
- `knownSecrets` ← src/env-resolution.ts:405 [EXTRACTED]
  ```
  export async function knownSecrets(localConfig: LocalConfig, env: NodeJS.ProcessEnv = process.env): Promise<Record<string, string>> {
  ```
- `secretKey` ← src/env-resolution.ts:416 [EXTRACTED]
  ```
  export function secretKey(label: string): string {
  ```
- `secretState` ← src/env-resolution.ts:420 [EXTRACTED]
  ```
  export function secretState(secrets: StoreResolution<SecretValue>, key: string): SecretState {
  ```
- `envShVariables` ← src/env-resolution.ts:425 [EXTRACTED]
  ```
  export function envShVariables(
  ```
- `keptFromUserScope` ← src/env-resolution.ts:443 [EXTRACTED]
  ```
  export function keptFromUserScope(localConfig: LocalConfig, teamEnv: TeamEnv, exported: readonly EnvVariable[]): string[] {
  ```
- `variablesKeptWarning` ← src/env-resolution.ts:456 [EXTRACTED]
  ```
  export function variablesKeptWarning(reason: string): string {
  ```
- `resolveWorkflowEnv` ← src/env-resolution.ts:475 [EXTRACTED]
  ```
  export async function resolveWorkflowEnv(localConfig: LocalConfig, live: NodeJS.ProcessEnv = process.env): Promise<WorkflowEnv> {
  ```
- `exportDigest` ← src/env-sh-exports.ts:30 [EXTRACTED]
  ```
  export function exportDigest(key: string, value: string): string {
  ```
- `isEnvShMarker` ← src/env-sh-exports.ts:46 [EXTRACTED]
  ```
  export function isEnvShMarker(key: string): boolean {
  ```
- `envShMarker` ← src/env-sh-exports.ts:60 [EXTRACTED]
  ```
  export function envShMarker(
  ```
- `markedAsExported` ← src/env-sh-exports.ts:76 [EXTRACTED]
  ```
  export function markedAsExported(env: NodeJS.ProcessEnv): (key: string, value: string) => boolean {
  ```
- `envShExportsPath` ← src/env-sh-exports.ts:87 [EXTRACTED]
  ```
  export function envShExportsPath(envShPath: string): string {
  ```
- `readEnvShExports` ← src/env-sh-exports.ts:114 [EXTRACTED]
  ```
  export async function readEnvShExports(envShPath: string): Promise<EnvShExports> {
  ```
- `recordEnvShExports` ← src/env-sh-exports.ts:119 [EXTRACTED]
  ```
  export async function recordEnvShExports(envShPath: string, exports: Iterable<readonly [string, string]>): Promise<EnvShExports> {
  ```
- `excludeList` ← src/exclude.ts:36 [EXTRACTED]
  ```
  export async function excludeList(_options: GlobalOptions): Promise<void> {
  ```
- `excludeAdd` ← src/exclude.ts:52 [EXTRACTED]
  ```
  export async function excludeAdd(skills: string[], options: GlobalOptions): Promise<void> {
  ```
- `excludeRemove` ← src/exclude.ts:80 [EXTRACTED]
  ```
  export async function excludeRemove(skills: string[], options: GlobalOptions): Promise<void> {
  ```
- `FOLDER_MARKERS` ← src/folder-markers.ts:19 [EXTRACTED]
  ```
  export const FOLDER_MARKERS = {
  ```
- `holdsMarker` ← src/folder-markers.ts:38 [EXTRACTED]
  ```
  export async function holdsMarker(dir: string, marker: string | null): Promise<boolean> {
  ```
- `WRITER_IDS` ← src/git-exclude-delivered.ts:35 [EXTRACTED]
  ```
  export const WRITER_IDS = [
  ```
- `DELIVERED_OWNER` ← src/git-exclude-delivered.ts:45 [EXTRACTED]
  ```
  export const DELIVERED_OWNER = 'delivered';
  ```
- `createDeliveryRecorder` ← src/git-exclude-delivered.ts:78 [EXTRACTED]
  ```
  export function createDeliveryRecorder(): DeliveryRecorder {
  ```
- `deliveredOwner` ← src/git-exclude-delivered.ts:122 [EXTRACTED]
  ```
  export function deliveredOwner(localConfig: LocalConfig): GitExcludeOwner {
  ```
- `deliveredOwnerElsewhere` ← src/git-exclude-delivered.ts:133 [EXTRACTED]
  ```
  export function deliveredOwnerElsewhere(localConfig: LocalConfig): GitExcludeOwner {
  ```
- `DELIVERED_FOLDERS_OWNER` ← src/git-exclude-delivered.ts:167 [EXTRACTED]
  ```
  export const DELIVERED_FOLDERS_OWNER = 'delivered-folders';
  ```
- `excludeDeliveredFolders` ← src/git-exclude-delivered.ts:175 [EXTRACTED]
  ```
  export async function excludeDeliveredFolders(localConfig: LocalConfig, dir: string): Promise<void> {
  ```
- `deliveredUnion` ← src/git-exclude-delivered.ts:232 [EXTRACTED]
  ```
  export async function deliveredUnion(checkouts: ListedCheckout[]): Promise<DeliveredUnion> {
  ```
- `describeForeign` ← src/git-exclude-delivered.ts:318 [EXTRACTED]
  ```
  export function describeForeign(foreign: ForeignPath[]): string[] {
  ```
- `describeUnreadableGitExcludeSetting` ← src/git-exclude-delivered.ts:335 [EXTRACTED]
  ```
  export function describeUnreadableGitExcludeSetting(localConfig: LocalConfig): string {
  ```
- `applyDeliveredGitExclude` ← src/git-exclude-delivered.ts:363 [EXTRACTED]
  ```
  export async function applyDeliveredGitExclude(
  ```
- `reportDeliveredGitExclude` ← src/git-exclude-delivered.ts:439 [EXTRACTED]
  ```
  export async function reportDeliveredGitExclude(
  ```
- `localAgentGitExcludeNotices` ← src/git-exclude-notices.ts:50 [EXTRACTED]
  ```
  export function localAgentGitExcludeNotices(): GitExcludeNoticesHome {
  ```
- `isBackgroundPull` ← src/git-exclude-notices.ts:61 [EXTRACTED]
  ```
  export function isBackgroundPull(options: Pick<GlobalOptions, 'silent' | 'gitHook'>): boolean {
  ```
- `readGitExcludeNotices` ← src/git-exclude-notices.ts:98 [EXTRACTED]
  ```
  export async function readGitExcludeNotices(home: GitExcludeNoticesHome): Promise<GitExcludeNotices> {
  ```
- `noticeGitExclude` ← src/git-exclude-notices.ts:134 [EXTRACTED]
  ```
  export async function noticeGitExclude(home: GitExcludeNoticesHome, message: string, options: Pick<GlobalOptions, 'silent' | 'gitHook'>): Promise<void> {
  ```
- `recordGitExcludeFailure` ← src/git-exclude-notices.ts:148 [EXTRACTED]
  ```
  export async function recordGitExcludeFailure(home: GitExcludeNoticesHome, message: string): Promise<void> {
  ```
- `clearGitExcludeFailure` ← src/git-exclude-notices.ts:154 [EXTRACTED]
  ```
  export async function clearGitExcludeFailure(home: GitExcludeNoticesHome): Promise<void> {
  ```
- `sayGitExcludeNotices` ← src/git-exclude-notices.ts:164 [EXTRACTED]
  ```
  export async function sayGitExcludeNotices(home: GitExcludeNoticesHome): Promise<boolean> {
  ```
- `MCP_EXCLUDE_OWNER` ← src/git-exclude.ts:44 [EXTRACTED]
  ```
  export const MCP_EXCLUDE_OWNER = 'mcp-exclude';
  ```
- `MCP_EXCLUDE_START` ← src/git-exclude.ts:45 [EXTRACTED]
  ```
  export const MCP_EXCLUDE_START = '# [teamai:mcp-exclude:start] project MCP configs holding resolved ${VAR} values';
  ```
- `MCP_EXCLUDE_END` ← src/git-exclude.ts:46 [EXTRACTED]
  ```
  export const MCP_EXCLUDE_END = '# [teamai:mcp-exclude:end]';
  ```
- `encodeOwnerSegment` ← src/git-exclude.ts:55 [EXTRACTED]
  ```
  export function encodeOwnerSegment(name: string): string {
  ```
- `withOwnerLines` ← src/git-exclude.ts:189 [EXTRACTED]
  ```
  export function withOwnerLines(content: string, owner: string, lines: string[]): string | null {
  ```
- `gitExcludeFile` ← src/git-exclude.ts:242 [EXTRACTED]
  ```
  export async function gitExcludeFile(dir: string, context?: GitContext): Promise<{ excludeFile: string; root: string; prefix: string } | null> {
  ```
- `gitExcludeFiles` ← src/git-exclude.ts:249 [EXTRACTED]
  ```
  export async function gitExcludeFiles(
  ```
- `existingAncestor` ← src/git-exclude.ts:273 [EXTRACTED]
  ```
  export async function existingAncestor(file: string): Promise<string> {
  ```
- `realFilePath` ← src/git-exclude.ts:300 [EXTRACTED]
  ```
  export async function realFilePath(file: string): Promise<string> {
  ```
- `gitPathOf` ← src/git-exclude.ts:321 [EXTRACTED]
  ```
  export async function gitPathOf(file: string): Promise<{ label: string; path: string }> {
  ```
- `gitTracking` ← src/git-exclude.ts:338 [EXTRACTED]
  ```
  export async function gitTracking(file: string): Promise<GitTracking> {
  ```
- `gitTracks` ← src/git-exclude.ts:363 [EXTRACTED]
  ```
  export async function gitTracks(
  ```
- `gitUntracked` ← src/git-exclude.ts:384 [EXTRACTED]
  ```
  export async function gitUntracked(file: string, at: 'landed' | 'entry' = 'landed'): Promise<boolean> {
  ```
- `ignoredByMembersRule` ← src/git-exclude.ts:408 [EXTRACTED]
  ```
  export async function ignoredByMembersRule(file: string): Promise<boolean> {
  ```
- `NotWritableError` ← src/git-exclude.ts:500 [EXTRACTED]
  ```
  export class NotWritableError extends Error {
  ```
- `NotReadableError` ← src/git-exclude.ts:511 [EXTRACTED]
  ```
  export class NotReadableError extends Error {
  ```
- `_setExcludeLockRetryMs` ← src/git-exclude.ts:536 [EXTRACTED]
  ```
  export function _setExcludeLockRetryMs(ms: number): void {
  ```
- `updateFileLocked` ← src/git-exclude.ts:551 [EXTRACTED]
  ```
  export async function updateFileLocked(
  ```
- `GitContext` ← src/git-exclude.ts:675 [EXTRACTED]
  ```
  export class GitContext {
  ```
- `sync` ← src/git-exclude.ts:858 [EXTRACTED]
  ```
  export async function sync(
  ```
- `ensure` ← src/git-exclude.ts:1089 [EXTRACTED]
  ```
  export async function ensure(
  ```
- `remove` ← src/git-exclude.ts:1289 [EXTRACTED]
  ```
  export async function remove(
  ```
- `report` ← src/git-exclude.ts:1424 [EXTRACTED]
  ```
  export async function report(owner: GitExcludeOwner, expectedPaths: Iterable<string>, context = new GitContext()): Promise<GitExcludeReport> {
  ```
- `excludeLines` ← src/git-exclude.ts:1485 [EXTRACTED]
  ```
  export function excludeLines(content: string, owner: string): string[] | null {
  ```
- `updateExcludeLines` ← src/git-exclude.ts:1496 [EXTRACTED]
  ```
  export function updateExcludeLines(excludeFile: string, owner: string, edit: (lines: string[]) => string[] | null): Promise<ExcludeUpdate> {
  ```
- `stateHomeRecord` ← src/git-exclude.ts:1512 [EXTRACTED]
  ```
  export function stateHomeRecord(stateHome: string, owner: string): GitExcludeFileRecord {
  ```
- `GIT_HOOK_EVENTS` ← src/git-hook.ts:35 [EXTRACTED]
  ```
  export const GIT_HOOK_EVENTS = ['post-checkout', 'post-merge', 'post-rewrite'] as const;
  ```
- `GIT_HOOK_TOOL` ← src/git-hook.ts:40 [EXTRACTED]
  ```
  export const GIT_HOOK_TOOL = 'git';
  ```
- `gitHookCommand` ← src/git-hook.ts:52 [EXTRACTED]
  ```
  export function gitHookCommand(event: GitHookEvent): string {
  ```
- `guardedGitHookLine` ← src/git-hook.ts:61 [EXTRACTED]
  ```
  export function guardedGitHookLine(event: GitHookEvent): string {
  ```
- `gitHookStatus` ← src/git-hook.ts:139 [EXTRACTED]
  ```
  export async function gitHookStatus(repoDir: string): Promise<GitHookStatus> {
  ```
- `describeMissingGitHook` ← src/git-hook.ts:177 [EXTRACTED]
  ```
  export function describeMissingGitHook(status: Exclude<GitHookStatus, { installed: true }>): string {
  ```
- `installGitHook` ← src/git-hook.ts:227 [EXTRACTED]
  ```
  export async function installGitHook(repoDir: string, opts: { dryRun?: boolean } = {}): Promise<GitHookInstall> {
  ```
- `removeGitHook` ← src/git-hook.ts:358 [EXTRACTED]
  ```
  export async function removeGitHook(repoDir: string, opts: { dryRun?: boolean } = {}): Promise<string[]> {
  ```
- `isNewCheckout` ← src/git-hook.ts:409 [EXTRACTED]
  ```
  export function isNewCheckout(args: readonly string[]): boolean {
  ```
- `isRebaseFastForward` ← src/git-hook.ts:425 [EXTRACTED]
  ```
  export async function isRebaseFastForward(
  ```
- `clearGitHookRepositoryEnv` ← src/git-hook.ts:442 [EXTRACTED]
  ```
  export function clearGitHookRepositoryEnv(env: NodeJS.ProcessEnv = process.env): void {
  ```
- `isGitHookEvent` ← src/git-hook.ts:469 [EXTRACTED]
  ```
  export function isGitHookEvent(value: unknown): value is GitHookEvent {
  ```
- `recordGitHookFailure` ← src/git-hook.ts:474 [EXTRACTED]
  ```
  export async function recordGitHookFailure(config: LocalConfig, failure: GitHookFailure): Promise<void> {
  ```
- `readGitHookFailure` ← src/git-hook.ts:480 [EXTRACTED]
  ```
  export async function readGitHookFailure(config: LocalConfig): Promise<GitHookFailure | null> {
  ```
- `clearGitHookFailure` ← src/git-hook.ts:486 [EXTRACTED]
  ```
  export async function clearGitHookFailure(config: LocalConfig): Promise<void> {
  ```
- `describeGitHookFailure` ← src/git-hook.ts:490 [EXTRACTED]
  ```
  export function describeGitHookFailure(failure: GitHookFailure): GitHookFailureReport {
  ```
- `buildAggregatedGraph` ← src/graph-aggregate.ts:21 [EXTRACTED]
  ```
  export async function buildAggregatedGraph(teamwikiRoot: string) {
  ```
- `scopeGlobalGraph` ← src/graph-aggregate.ts:194 [EXTRACTED]
  ```
  export async function scopeGlobalGraph(
  ```
- `aggregateGlobalGraph` ← src/graph-aggregate.ts:447 [EXTRACTED]
  ```
  export async function aggregateGlobalGraph(
  ```
- `getHermesConfigPath` ← src/hermes-config.ts:15 [EXTRACTED]
  ```
  export function getHermesConfigPath(home = toolHome('hermes')): string {
  ```
- `hermesContextFileBudget` ← src/hermes-config.ts:23 [EXTRACTED]
  ```
  export async function hermesContextFileBudget(): Promise<{ limit: number; explicit: boolean; error?: string }> {
  ```
- `upsertSoulRules` ← src/hermes-config.ts:137 [EXTRACTED]
  ```
  export async function upsertSoulRules(soulPath: string, rulesText: string): Promise<void> {
  ```
- `readSoulRules` ← src/hermes-config.ts:164 [EXTRACTED]
  ```
  export async function readSoulRules(soulPath: string): Promise<string | null> {
  ```
- `removeSoulRules` ← src/hermes-config.ts:181 [EXTRACTED]
  ```
  export async function removeSoulRules(soulPath: string): Promise<void> {
  ```
- `getHermesAllowlistPath` ← src/hermes-config.ts:186 [EXTRACTED]
  ```
  export function getHermesAllowlistPath(home = toolHome('hermes')): string {
  ```
- `upsertHermesHook` ← src/hermes-config.ts:245 [EXTRACTED]
  ```
  export async function upsertHermesHook(
  ```
- `removeHermesHookByCommand` ← src/hermes-config.ts:283 [EXTRACTED]
  ```
  export async function removeHermesHookByCommand(command: string, home = toolHome('hermes')): Promise<void> {
  ```
- `addHermesAllowlist` ← src/hermes-config.ts:333 [EXTRACTED]
  ```
  export async function addHermesAllowlist(event: string, command: string): Promise<boolean> {
  ```
- `hasHermesHookCommands` ← src/hermes-config.ts:352 [EXTRACTED]
  ```
  export async function hasHermesHookCommands(commands: readonly string[], home = toolHome('hermes')): Promise<boolean> {
  ```
- `removeHermesAllowlist` ← src/hermes-config.ts:378 [EXTRACTED]
  ```
  export async function removeHermesAllowlist(event: string, command: string, home = toolHome('hermes')): Promise<void> {
  ```
- `enableHermesPlugin` ← src/hermes-config.ts:396 [EXTRACTED]
  ```
  export async function enableHermesPlugin(name: string): Promise<boolean> {
  ```
- `disableHermesPlugin` ← src/hermes-config.ts:412 [EXTRACTED]
  ```
  export async function disableHermesPlugin(name: string, home = toolHome('hermes')): Promise<void> {
  ```
- `isHermesPluginDisabled` ← src/hermes-config.ts:431 [EXTRACTED]
  ```
  export async function isHermesPluginDisabled(name: string): Promise<boolean> {
  ```
- `isHermesPluginEnabled` ← src/hermes-config.ts:438 [EXTRACTED]
  ```
  export async function isHermesPluginEnabled(name: string): Promise<boolean> {
  ```
- `HERMES_INSTRUCTIONS_PLUGIN` ← src/hermes-hooks.ts:34 [EXTRACTED]
  ```
  export const HERMES_INSTRUCTIONS_PLUGIN = 'teamai-instructions';
  ```
- `HERMES_SECTION_LIMIT` ← src/hermes-hooks.ts:40 [EXTRACTED]
  ```
  export const HERMES_SECTION_LIMIT = 4000;
  ```
- `HERMES_INSTRUCTIONS_SECTION` ← src/hermes-hooks.ts:43 [EXTRACTED]
  ```
  export const HERMES_INSTRUCTIONS_SECTION = 'teamai.instructions';
  ```
- `lastInstructionsSection` ← src/hermes-hooks.ts:61 [EXTRACTED]
  ```
  export async function lastInstructionsSection(home = toolHome('hermes')): Promise<InstructionsSection> {
  ```
- `getInstructionsPluginDir` ← src/hermes-hooks.ts:85 [EXTRACTED]
  ```
  export function getInstructionsPluginDir(home = toolHome('hermes')): string {
  ```
- `removeHermesA2aControl` ← src/hermes-hooks.ts:226 [EXTRACTED]
  ```
  export async function removeHermesA2aControl(home = toolHome('hermes'), { strict = false } = {}): Promise<void> {
  ```
- `ownsInstructionsPlugin` ← src/hermes-hooks.ts:241 [EXTRACTED]
  ```
  export async function ownsInstructionsPlugin(home = toolHome('hermes')): Promise<boolean> {
  ```
- `foreignInstructionsPlugin` ← src/hermes-hooks.ts:250 [EXTRACTED]
  ```
  export function foreignInstructionsPlugin(): string {
  ```
- `buildInstructionsPlugin` ← src/hermes-hooks.ts:268 [EXTRACTED]
  ```
  export function buildInstructionsPlugin(entry = resolveCliEntry()): HermesInstructionsPlugin {
  ```
- `getReportScriptPath` ← src/hermes-hooks.ts:318 [EXTRACTED]
  ```
  export function getReportScriptPath(home = toolHome('hermes')): string {
  ```
- `getTeamHookScriptPath` ← src/hermes-hooks.ts:342 [EXTRACTED]
  ```
  export function getTeamHookScriptPath(home = toolHome('hermes')): string {
  ```
- `refreshHermesTeamHooks` ← src/hermes-hooks.ts:404 [EXTRACTED]
  ```
  export async function refreshHermesTeamHooks(): Promise<void> {
  ```
- `injectHermesHooks` ← src/hermes-hooks.ts:451 [EXTRACTED]
  ```
  export async function injectHermesHooks(): Promise<void> {
  ```
- `hasHermesHooks` ← src/hermes-hooks.ts:499 [EXTRACTED]
  ```
  export async function hasHermesHooks(home = toolHome('hermes')): Promise<boolean> {
  ```
- `removeHermesHooks` ← src/hermes-hooks.ts:517 [EXTRACTED]
  ```
  export async function removeHermesHooks(home = toolHome('hermes')): Promise<void> {
  ```
- `removeHermesAgentHook` ← src/hermes-hooks.ts:558 [EXTRACTED]
  ```
  export async function removeHermesAgentHook(opts: {
  ```
- `runHookCommand` ← src/hook-command.ts:21 [EXTRACTED]
  ```
  export function runHookCommand(command: string, opts: { cwd: string | undefined; timeout: number; stdin: string }): Promise<HookRun> {
  ```
- `salvageStdinFields` ← src/hook-dispatch-cli.ts:130 [EXTRACTED]
  ```
  export function salvageStdinFields(raw: string): Partial<Record<SalvageableStdinField, string>> {
  ```
- `trySpawnDetachedViaWmi` ← src/hook-dispatch-cli.ts:191 [EXTRACTED]
  ```
  export async function trySpawnDetachedViaWmi(
  ```
- `sweepStalePayloads` ← src/hook-dispatch-cli.ts:342 [EXTRACTED]
  ```
  export function sweepStalePayloads(dir = os.tmpdir(), now = Date.now(), platform = process.platform): number {
  ```
- `parseStdin` ← src/hook-dispatch-cli.ts:370 [EXTRACTED]
  ```
  export function parseStdin(raw: string, event: string): HookStdin {
  ```
- `hookDispatchCli` ← src/hook-dispatch-cli.ts:461 [EXTRACTED]
  ```
  export async function hookDispatchCli(
  ```
- `HookStdinSchema` ← src/hook-dispatch.ts:27 [EXTRACTED]
  ```
  export const HookStdinSchema = z.preprocess((payload) => JSON.parse(JSON.stringify(payload) ?? 'null'), JsonObjectSchema);
  ```
- `stdinString` ← src/hook-dispatch.ts:32 [EXTRACTED]
  ```
  export function stdinString(stdin: HookStdin, field: string): string | undefined {
  ```
- `CURSOR_HOOK_CONTEXT_LIMIT` ← src/hook-dispatch.ts:74 [EXTRACTED]
  ```
  export const CURSOR_HOOK_CONTEXT_LIMIT = 10_000;
  ```
- `mergeHookOutputs` ← src/hook-dispatch.ts:136 [EXTRACTED]
  ```
  export function mergeHookOutputs(outputs: string[]): string | null {
  ```
- `createDispatcher` ← src/hook-dispatch.ts:206 [EXTRACTED]
  ```
  export function createDispatcher(config: DispatcherConfig): Dispatcher {
  ```
- `FOREGROUND_PAYLOAD_KEYS` ← src/hook-fast-path.ts:40 [EXTRACTED]
  ```
  export const FOREGROUND_PAYLOAD_KEYS = ['teamai_run', 'teamai_launch'] as const;
  ```
- `argvVerdict` ← src/hook-fast-path.ts:91 [EXTRACTED]
  ```
  export function argvVerdict(argv: readonly string[], env: NodeJS.ProcessEnv, platform: NodeJS.Platform): ArgvVerdict {
  ```
- `childPayload` ← src/hook-fast-path.ts:123 [EXTRACTED]
  ```
  export function childPayload(raw: string): { payload: string; sessionId: string } | null {
  ```
- `isHttpEnrolled` ← src/hook-fast-path.ts:164 [EXTRACTED]
  ```
  export function isHttpEnrolled(env: NodeJS.ProcessEnv): boolean {
  ```
- `promptAnswersInForeground` ← src/hook-fast-path.ts:184 [EXTRACTED]
  ```
  export function promptAnswersInForeground(sessionId: string, env: NodeJS.ProcessEnv): boolean {
  ```
- `runHookFastPath` ← src/hook-fast-path.ts:231 [EXTRACTED]
  ```
  export async function runHookFastPath(
  ```
- `runLoginDeferredHook` ← src/hook-fast-path.ts:261 [EXTRACTED]
  ```
  export async function runLoginDeferredHook(
  ```
- `recordLoginEnrolment` ← src/hook-fast-path.ts:308 [EXTRACTED]
  ```
  export function recordLoginEnrolment(raw: string, env: NodeJS.ProcessEnv): void {
  ```
- `PULL_TIMEOUT_MS` ← src/hook-handlers.ts:109 [EXTRACTED]
  ```
  export const PULL_TIMEOUT_MS = 120_000;
  ```
- `buildAdoptedSummary` ← src/hook-handlers.ts:668 [EXTRACTED]
  ```
  export function buildAdoptedSummary(adoptedDocIds: readonly string[]): string {
  ```
- `eligibleUpvotes` ← src/hook-handlers.ts:683 [EXTRACTED]
  ```
  export function eligibleUpvotes(
  ```
- `buildHandlerRegistry` ← src/hook-handlers.ts:1354 [EXTRACTED]
  ```
  export function buildHandlerRegistry(): HandlerRegistration[] {
  ```
- `filterHandlersForConfig` ← src/hook-handlers.ts:1472 [EXTRACTED]
  ```
  export function filterHandlersForConfig(
  ```
- `hooksInject` ← src/hooks-cmd.ts:147 [EXTRACTED]
  ```
  export async function hooksInject(options: GlobalOptions): Promise<void> {
  ```
- `hooksList` ← src/hooks-cmd.ts:189 [EXTRACTED]
  ```
  export async function hooksList(_options: GlobalOptions): Promise<void> {
  ```
- `hooksRemove` ← src/hooks-cmd.ts:374 [EXTRACTED]
  ```
  export async function hooksRemove(_options: GlobalOptions): Promise<void> {
  ```
- `OPENCLAW_TOOLS` ← src/hooks.ts:80 [EXTRACTED]
  ```
  export const OPENCLAW_TOOLS = new Set(['openclaw', 'qclaw', 'easyclaw', 'autoclaw']);
  ```
- `TEAMAI_HOOK_SUBCOMMANDS` ← src/hooks.ts:83 [EXTRACTED]
  ```
  export const TEAMAI_HOOK_SUBCOMMANDS = ['hook-dispatch'] as const;
  ```
- `TEAMAI_LEGACY_HOOK_SUBCOMMANDS` ← src/hooks.ts:86 [EXTRACTED]
  ```
  export const TEAMAI_LEGACY_HOOK_SUBCOMMANDS = ['pull', 'update', 'track', 'track-slash', 'dashboard-report', 'contribute-check', 'auto-recall', 'todowrite-hint', 'mr-hint'] as const;
  ```
- `isCodexTrustGatedTool` ← src/hooks.ts:250 [EXTRACTED]
  ```
  export function isCodexTrustGatedTool(tool: string): boolean {
  ```
- `codexTrustPolicy` ← src/hooks.ts:283 [EXTRACTED]
  ```
  export function codexTrustPolicy(localConfig: Pick<LocalConfig, 'codexTrustEnabled' | 'toolRoots'>): CodexTrustPolicy {
  ```
- `codexTrustReminder` ← src/hooks.ts:295 [EXTRACTED]
  ```
  export function codexTrustReminder(): string {
  ```
- `reportCodexTrust` ← src/hooks.ts:306 [EXTRACTED]
  ```
  export function reportCodexTrust(trust: CodexTrust | undefined, mode: 'all' | 'problems'): void {
  ```
- `teamHookHistory` ← src/hooks.ts:477 [EXTRACTED]
  ```
  export function teamHookHistory(localConfig: LocalConfig): TeamHookHistory {
  ```
- `keptTeamHookEntries` ← src/hooks.ts:511 [EXTRACTED]
  ```
  export async function keptTeamHookEntries(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<string[]> {
  ```
- `hasUnrecordedTeamHooks` ← src/hooks.ts:534 [EXTRACTED]
  ```
  export async function hasUnrecordedTeamHooks(
  ```
- `codexGroupCommand` ← src/hooks.ts:593 [EXTRACTED]
  ```
  export function codexGroupCommand(group: JsonValue | undefined): string {
  ```
- `getToolCheckouts` ← src/hooks.ts:835 [EXTRACTED]
  ```
  export function getToolCheckouts(manifest: SharedHooksManifest, tool: string): string[] {
  ```
- `setToolCheckouts` ← src/hooks.ts:845 [EXTRACTED]
  ```
  export function setToolCheckouts(manifest: SharedHooksManifest, tool: string, checkouts: string[]): void {
  ```
- `unregisterCheckoutFromSharedManifest` ← src/hooks.ts:857 [EXTRACTED]
  ```
  export async function unregisterCheckoutFromSharedManifest(
  ```
- `migrateLegacyManagedHooks` ← src/hooks.ts:889 [EXTRACTED]
  ```
  export async function migrateLegacyManagedHooks(localConfig: LocalConfig): Promise<void> {
  ```
- `canonicalProjectRoot` ← src/hooks.ts:957 [EXTRACTED]
  ```
  export function canonicalProjectRoot(projectRoot: string): string {
  ```
- `resolveMainCheckoutHooks` ← src/hooks.ts:1322 [EXTRACTED]
  ```
  export async function resolveMainCheckoutHooks(
  ```
- `mainCheckoutHookFile` ← src/hooks.ts:1525 [EXTRACTED]
  ```
  export function mainCheckoutHookFile(mainCheckout: MainCheckoutHooks | null | undefined, tool: string): string | null {
  ```
- `codexTeamHookProject` ← src/hooks.ts:1535 [EXTRACTED]
  ```
  export async function codexTeamHookProject(localConfig: LocalConfig): Promise<string | null> {
  ```
- `codexTeamHookCheckout` ← src/hooks.ts:1548 [EXTRACTED]
  ```
  export async function codexTeamHookCheckout(localConfig: LocalConfig): Promise<string | null> {
  ```
- `stopCodexTeamHookDispatch` ← src/hooks.ts:1595 [EXTRACTED]
  ```
  export async function stopCodexTeamHookDispatch(
  ```
- `selfLocalTeamHookFile` ← src/hooks.ts:1840 [EXTRACTED]
  ```
  export function selfLocalTeamHookFile(
  ```
- `releaseRemovedCheckoutHooks` ← src/hooks.ts:1953 [EXTRACTED]
  ```
  export async function releaseRemovedCheckoutHooks(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<void> {
  ```
- `copilotBuiltinDisabled` ← src/hooks.ts:2532 [EXTRACTED]
  ```
  export async function copilotBuiltinDisabled(localConfig: LocalConfig | null, event: string, matcher: string): Promise<boolean> {
  ```
- `copilotBuiltinInstalled` ← src/hooks.ts:2549 [EXTRACTED]
  ```
  export async function copilotBuiltinInstalled(event: string, matcher: string, projectConfig: LocalConfig | null): Promise<boolean> {
  ```
- `removeCopilotGlobalBuiltins` ← src/hooks.ts:2578 [EXTRACTED]
  ```
  export async function removeCopilotGlobalBuiltins(): Promise<void> {
  ```
- `editCodexHookFile` ← src/hooks.ts:2748 [EXTRACTED]
  ```
  export async function editCodexHookFile(
  ```
- `AGENT_HOOK_EVENTS` ← src/hooks.ts:3140 [EXTRACTED]
  ```
  export const AGENT_HOOK_EVENTS = new Set<string>([
  ```
- `isAgentHookSupportedTool` ← src/hooks.ts:3157 [EXTRACTED]
  ```
  export function isAgentHookSupportedTool(tool: string): boolean {
  ```
- `runsTeamHookOn` ← src/hooks.ts:3179 [EXTRACTED]
  ```
  export function runsTeamHookOn(tool: string, event: string): boolean {
  ```
- `isAgentHookEvent` ← src/hooks.ts:3209 [EXTRACTED]
  ```
  export function isAgentHookEvent(event: string): boolean {
  ```
- `agentHookDescription` ← src/hooks.ts:3217 [EXTRACTED]
  ```
  export function agentHookDescription(slug: string): string {
  ```
- `applyAgentHook` ← src/hooks.ts:3238 [EXTRACTED]
  ```
  export async function applyAgentHook(
  ```
- `removeAgentHook` ← src/hooks.ts:3313 [EXTRACTED]
  ```
  export async function removeAgentHook(
  ```
- `applyBridgedAgentHook` ← src/hooks.ts:3371 [EXTRACTED]
  ```
  export async function applyBridgedAgentHook(tool: string, def: AgentHookDef): Promise<void> {
  ```
- `hasBridgedAgentHook` ← src/hooks.ts:3377 [EXTRACTED]
  ```
  export async function hasBridgedAgentHook(tool: string, slug: string): Promise<boolean> {
  ```
- `removeBridgedAgentHook` ← src/hooks.ts:3384 [EXTRACTED]
  ```
  export async function removeBridgedAgentHook(tool: string, slug: string): Promise<void> {
  ```
- `readHookFile` ← src/hooks.ts:3473 [EXTRACTED]
  ```
  export async function readHookFile<T>(file: string, fallback: T, format: HookFormat, syntax: JsonSyntax): Promise<T> {
  ```
- `reconcileHooks` ← src/hooks.ts:3501 [EXTRACTED]
  ```
  export async function reconcileHooks(
  ```
- `injectHooks` ← src/hooks.ts:3637 [EXTRACTED]
  ```
  export async function injectHooks(settingsPath: string, tool?: string, codexTrust?: CodexTrustPolicy): Promise<void> {
  ```
- `removeHooks` ← src/hooks.ts:3642 [EXTRACTED]
  ```
  export async function removeHooks(settingsPath: string, tool?: string): Promise<void> {
  ```
- `builtinHookFormOf` ← src/hooks.ts:3658 [EXTRACTED]
  ```
  export async function builtinHookFormOf({ tool, settingsPath, from, toolRoots }: {
  ```
- `getHookStatus` ← src/hooks.ts:3775 [EXTRACTED]
  ```
  export async function getHookStatus(
  ```
- `hasTeamaiHooks` ← src/hooks.ts:3795 [EXTRACTED]
  ```
  export async function hasTeamaiHooks(
  ```
- `injectHooksToAllTools` ← src/hooks.ts:4059 [EXTRACTED]
  ```
  export async function injectHooksToAllTools(toolPaths: Record<string, { settings?: string }>, baseDir?: string, filterAgents?: string[], toolRoots?: Record<string, string>, codexTrust?: CodexTrustPolicy): Promise<void> {
  ```
- `reconcileHooksToAllTools` ← src/hooks.ts:4177 [EXTRACTED]
  ```
  export async function reconcileHooksToAllTools(
  ```
- `trustCodexAgentHook` ← src/hooks.ts:4828 [EXTRACTED]
  ```
  export async function trustCodexAgentHook(settingsPath: string, event: string, command: string): Promise<CodexTrust> {
  ```
- `trustCodexForScope` ← src/hooks.ts:4999 [EXTRACTED]
  ```
  export async function trustCodexForScope(
  ```
- `readCodexHookTrustForScope` ← src/hooks.ts:5079 [EXTRACTED]
  ```
  export async function readCodexHookTrustForScope(
  ```
- `sweepLegacyProjectHooks` ← src/hooks.ts:5122 [EXTRACTED]
  ```
  export async function sweepLegacyProjectHooks(
  ```
- `reconcileTeamHooksForConfig` ← src/hooks.ts:5275 [EXTRACTED]
  ```
  export async function reconcileTeamHooksForConfig(
  ```
- `deliveredHookFiles` ← src/hooks.ts:5540 [EXTRACTED]
  ```
  export async function deliveredHookFiles(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<string[]> {
  ```
- `unreadableHookFiles` ← src/hooks.ts:5555 [EXTRACTED]
  ```
  export async function unreadableHookFiles(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<string[]> {
  ```
- `judgeTeamaiOnlyCodexHooks` ← src/hooks.ts:5618 [EXTRACTED]
  ```
  export async function judgeTeamaiOnlyCodexHooks(
  ```
- `describeUnappliedTeamHooks` ← src/hooks.ts:5712 [EXTRACTED]
  ```
  export function describeUnappliedTeamHooks(result: { builtins: BuiltinsOnly }): string {
  ```
- `localCheckoutSlug` ← src/import-codebase.ts:265 [EXTRACTED]
  ```
  export async function localCheckoutSlug(opts: { sourceDir: string; slug: string; wikiRoot: string }): Promise<string> {
  ```
- `ownLegacySlug` ← src/import-codebase.ts:348 [EXTRACTED]
  ```
  export async function ownLegacySlug(opts: { sourceDir: string; slug: string; wikiRoot: string }): Promise<string> {
  ```
- `extractToStaging` ← src/import-codebase.ts:433 [EXTRACTED]
  ```
  export async function extractToStaging(opts: ImportCodebaseOptions & { stagingRoot: string }): Promise<boolean> {
  ```
- `publishStaging` ← src/import-codebase.ts:460 [EXTRACTED]
  ```
  export async function publishStaging(opts: StagedCodebase & { legacySlug?: string; skipEnrich?: boolean }): Promise<void> {
  ```
- `reconcileTeamwiki` ← src/import-codebase.ts:644 [EXTRACTED]
  ```
  export async function reconcileTeamwiki(wikiRoot: string): Promise<void> {
  ```
- `warnIncompleteDeepEnrich` ← src/import-codebase.ts:663 [EXTRACTED]
  ```
  export function warnIncompleteDeepEnrich({ slug, output }: {
  ```
- `refreshTeamwikiIndexes` ← src/import-codebase.ts:682 [EXTRACTED]
  ```
  export async function refreshTeamwikiIndexes(wikiRoot: string): Promise<void> {
  ```
- `publishTeamwikiViaMR` ← src/import-codebase.ts:699 [EXTRACTED]
  ```
  export async function publishTeamwikiViaMR(team: TeamaiInit, message: string): Promise<void> {
  ```
- `ImportFromMr` ← src/import-from-mr.ts:441 [EXTRACTED]
  ```
  export const ImportFromMr = { WORKFLOW, fetch, draft, publish, finish, start } as const;
  ```
- `ImportInputError` ← src/import-from-repo.ts:86 [EXTRACTED]
  ```
  export class ImportInputError extends Error {
  ```
- `ImportFromRepo` ← src/import-from-repo.ts:544 [EXTRACTED]
  ```
  export const ImportFromRepo = { start, stage, publish, finishItem, finish, importedOf } as const;
  ```
- `ImportFromIwiki` ← src/import-iwiki.ts:224 [EXTRACTED]
  ```
  export const ImportFromIwiki = { fetch, publish, start } as const;
  ```
- `reconcileIwikiWithCodebase` ← src/import-iwiki.ts:253 [EXTRACTED]
  ```
  export async function reconcileIwikiWithCodebase(
  ```
- `ImportLearnings` ← src/import-local.ts:352 [EXTRACTED]
  ```
  export const ImportLearnings = { scanRules, readCandidate, classifyReply, writeLearnings, publishRules, start, startRules, parseFlag, parseBoolean, NOBODY_REVIEWS } as const;
  ```
- `fetchMR` ← src/import-mr.ts:19 [EXTRACTED]
  ```
  export async function fetchMR(url: string, opts: MRFetchOptions): Promise<MRData> {
  ```
- `formatMrThreads` ← src/import-mr.ts:87 [EXTRACTED]
  ```
  export function formatMrThreads(threads: MRThread[], mrAuthor: string | undefined, budget = THREADS_BUDGET): string {
  ```
- `parseLearningDraft` ← src/import-mr.ts:148 [EXTRACTED]
  ```
  export function parseLearningDraft(raw: string): ParsedLearningDraft {
  ```
- `extractRepoUrlFromMrUrl` ← src/import-mr.ts:178 [EXTRACTED]
  ```
  export function extractRepoUrlFromMrUrl(mrUrl: string): string {
  ```
- `importFromOrg` ← src/import-org.ts:157 [EXTRACTED]
  ```
  export async function importFromOrg(opts: ImportFromOrgOptions): Promise<void> {
  ```
- `importFromRepoList` ← src/import-repo-list.ts:61 [EXTRACTED]
  ```
  export async function importFromRepoList(opts: ImportFromRepoListOptions): Promise<RepoListImport> {
  ```
- `detectCrossRepoEdges` ← src/import-repo.ts:51 [EXTRACTED]
  ```
  export function detectCrossRepoEdges(
  ```
- `repoSlugForUrl` ← src/import-repo.ts:210 [EXTRACTED]
  ```
  export function repoSlugForUrl(url: string): string {
  ```
- `repoSourceOf` ← src/import-repo.ts:234 [EXTRACTED]
  ```
  export function repoSourceOf(url: string): RepoSource {
  ```
- `previewRepoImport` ← src/import-repo.ts:266 [EXTRACTED]
  ```
  export async function previewRepoImport(source: RepoSource, opts: RepoFetchOptions & { output?: string }): Promise<void> {
  ```
- `fetchRepo` ← src/import-repo.ts:310 [EXTRACTED]
  ```
  export async function fetchRepo(source: RepoSource, opts: RepoFetchOptions & { evidenceDest: string }): Promise<RepoFetched> {
  ```
- `recordRepoSync` ← src/import-repo.ts:371 [EXTRACTED]
  ```
  export async function recordRepoSync(source: RepoSource, sha: string): Promise<void> {
  ```
- `writeRepoNarrative` ← src/import-repo.ts:385 [EXTRACTED]
  ```
  export async function writeRepoNarrative(evidenceDest: string, slug: string, answer: string): Promise<void> {
  ```
- `writeExplicitDomain` ← src/import-repo.ts:420 [EXTRACTED]
  ```
  export async function writeExplicitDomain(evidenceDest: string, domain: string): Promise<void> {
  ```
- `importCmd` ← src/import.ts:96 [EXTRACTED]
  ```
  export async function importCmd(opts: ImportOptions): Promise<void> {
  ```
- `ALL_PROJECTS_SELECTOR` ← src/init.ts:572 [EXTRACTED]
  ```
  export const ALL_PROJECTS_SELECTOR = 'all';
  ```
- `resolveActiveProjects` ← src/init.ts:595 [EXTRACTED]
  ```
  export async function resolveActiveProjects(
  ```
- `resolveInitScope` ← src/init.ts:727 [EXTRACTED]
  ```
  export function resolveInitScope(
  ```
- `resolveInheritUserScope` ← src/init.ts:777 [EXTRACTED]
  ```
  export function resolveInheritUserScope(
  ```
- `resolveInitRepo` ← src/init.ts:795 [EXTRACTED]
  ```
  export function resolveInitRepo(
  ```
- `resolveInitProvider` ← src/init.ts:815 [EXTRACTED]
  ```
  export function resolveInitProvider(raw: string | undefined): ProviderName | undefined {
  ```
- `initHttp` ← src/init.ts:936 [EXTRACTED]
  ```
  export async function initHttp(
  ```
- `buildSelfModeGitignore` ← src/init.ts:1273 [EXTRACTED]
  ```
  export function buildSelfModeGitignore(): string {
  ```
- `buildProjectScopeGitignore` ← src/init.ts:1333 [EXTRACTED]
  ```
  export function buildProjectScopeGitignore(): string {
  ```
- `migrateSelfModeGitignoreContent` ← src/init.ts:1369 [EXTRACTED]
  ```
  export function migrateSelfModeGitignoreContent(content: string) {
  ```
- `migrateSelfModeGitignore` ← src/init.ts:1424 [EXTRACTED]
  ```
  export async function migrateSelfModeGitignore(localConfig: LocalConfig): Promise<void> {
  ```
- `resolveSelfModeSelection` ← src/init.ts:1458 [EXTRACTED]
  ```
  export function resolveSelfModeSelection(indices: number[], detected: string[]): string[] {
  ```
- `promptForSelfModeAgents` ← src/init.ts:1490 [EXTRACTED]
  ```
  export async function promptForSelfModeAgents(options: {
  ```
- `initSelfMode` ← src/init.ts:1565 [EXTRACTED]
  ```
  export async function initSelfMode(options: GlobalOptions & {
  ```
- `isSelfModeTeam` ← src/init.ts:2065 [EXTRACTED]
  ```
  export async function isSelfModeTeam(repoDir: string): Promise<boolean> {
  ```
- `init` ← src/init.ts:2073 [EXTRACTED]
  ```
  export async function init(options: GlobalOptions & {
  ```
- `prefixFromEntryPath` ← src/install-prefix.ts:17 [EXTRACTED]
  ```
  export function prefixFromEntryPath(entry: string, posix: boolean): { prefix: string; global: boolean } | null {
  ```
- `isVoltaPackageImage` ← src/install-prefix.ts:50 [EXTRACTED]
  ```
  export function isVoltaPackageImage(filePath: string, voltaHome = process.env.VOLTA_HOME): boolean {
  ```
- `installationsPath` ← src/installations.ts:44 [EXTRACTED]
  ```
  export function installationsPath(): string {
  ```
- `packageDirFromEntry` ← src/installations.ts:49 [EXTRACTED]
  ```
  export function packageDirFromEntry(entry: string): string {
  ```
- `readInstallations` ← src/installations.ts:53 [EXTRACTED]
  ```
  export function readInstallations(): InstallationRecord[] {
  ```
- `describeInstallation` ← src/installations.ts:88 [EXTRACTED]
  ```
  export function describeInstallation(entry: string, version: string, now = new Date().toISOString()): InstallationRecord {
  ```
- `registersRunningInstallation` ← src/installations.ts:122 [EXTRACTED]
  ```
  export function registersRunningInstallation(args: readonly string[]): boolean {
  ```
- `registerRunningInstallation` ← src/installations.ts:135 [EXTRACTED]
  ```
  export function registerRunningInstallation(now = Date.now()): InstallationRecord | null {
  ```
- `selectOtherInstallation` ← src/installations.ts:179 [EXTRACTED]
  ```
  export function selectOtherInstallation(latest: string, runningEntry: string): InstallationRecord | null {
  ```
- `readInstalledVersion` ← src/installations.ts:201 [EXTRACTED]
  ```
  export function readInstalledVersion(pkgDir: string): string | null {
  ```
- `setInstallationUpdate` ← src/installations.ts:212 [EXTRACTED]
  ```
  export function setInstallationUpdate(
  ```
- `installationNotes` ← src/installations.ts:241 [EXTRACTED]
  ```
  export function installationNotes(): string[] {
  ```
- `deliversInstructionsByHook` ← src/instruction-targets.ts:140 [EXTRACTED]
  ```
  export function deliversInstructionsByHook(tool: string, scope: Scope): boolean {
  ```
- `instructionHookText` ← src/instruction-targets.ts:155 [EXTRACTED]
  ```
  export function instructionHookText(blocks: InstructionBlocks, recall: boolean): string {
  ```
- `nativeProjectInstructions` ← src/instruction-targets.ts:163 [EXTRACTED]
  ```
  export async function nativeProjectInstructions(tool: string, projectRoot: string): Promise<string> {
  ```
- `instructionHookTextFor` ← src/instruction-targets.ts:172 [EXTRACTED]
  ```
  export async function instructionHookTextFor(teamConfig: TeamaiConfig, localConfig: LocalConfig, tool: string): Promise<string> {
  ```
- `hookLimitProblem` ← src/instruction-targets.ts:193 [EXTRACTED]
  ```
  export function hookLimitProblem(hook: InstructionHook, text: string): string | null {
  ```
- `channelReadiness` ← src/instruction-targets.ts:208 [EXTRACTED]
  ```
  export async function channelReadiness(
  ```
- `instructionHookChannelInstallable` ← src/instruction-targets.ts:342 [EXTRACTED]
  ```
  export async function instructionHookChannelInstallable(tool: string): Promise<boolean> {
  ```
- `instructionChannelProblems` ← src/instruction-targets.ts:366 [EXTRACTED]
  ```
  export async function instructionChannelProblems(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<string[]> {
  ```
- `unreadableRulesFileMessage` ← src/instruction-targets.ts:403 [EXTRACTED]
  ```
  export async function unreadableRulesFileMessage(tool: string, gate: { readonly file: string }): Promise<string> {
  ```
- `instructionTargetOf` ← src/instruction-targets.ts:413 [EXTRACTED]
  ```
  export function instructionTargetOf(place: FilePlace, recall = false): InstructionTarget {
  ```
- `resolveInstructionTargets` ← src/instruction-targets.ts:418 [EXTRACTED]
  ```
  export async function resolveInstructionTargets(
  ```
- `retiredFilesOfReached` ← src/instruction-targets.ts:497 [EXTRACTED]
  ```
  export async function retiredFilesOfReached(
  ```
- `registerOpencodeContext` ← src/instruction-targets.ts:533 [EXTRACTED]
  ```
  export async function registerOpencodeContext(
  ```
- `holdsInstructionBlocks` ← src/instruction-targets.ts:672 [EXTRACTED]
  ```
  export async function holdsInstructionBlocks(file: string): Promise<boolean> {
  ```
- `holdsOnlyInstructionBlocks` ← src/instruction-targets.ts:679 [EXTRACTED]
  ```
  export async function holdsOnlyInstructionBlocks(file: string): Promise<boolean> {
  ```
- `clearInstructionFile` ← src/instruction-targets.ts:783 [EXTRACTED]
  ```
  export async function clearInstructionFile(
  ```
- `planInstructionFiles` ← src/instruction-targets.ts:821 [EXTRACTED]
  ```
  export async function planInstructionFiles(
  ```
- `applyInstructionPlan` ← src/instruction-targets.ts:873 [EXTRACTED]
  ```
  export async function applyInstructionPlan(
  ```
- `buildDualContext` ← src/iwiki-dual.ts:38 [EXTRACTED]
  ```
  export function buildDualContext(docs: IWikiDocument[]): string {
  ```
- `writeSections` ← src/iwiki-dual.ts:158 [EXTRACTED]
  ```
  export async function writeSections(flags: SectionsFlags): Promise<Record<string, never>> {
  ```
- `kiroHookFile` ← src/kiro-hooks.ts:26 [EXTRACTED]
  ```
  export function kiroHookFile(): string {
  ```
- `kiroTeamHookFile` ← src/kiro-hooks.ts:34 [EXTRACTED]
  ```
  export function kiroTeamHookFile(): string {
  ```
- `reconcileKiroTeamHooks` ← src/kiro-hooks.ts:65 [EXTRACTED]
  ```
  export async function reconcileKiroTeamHooks(): Promise<void> {
  ```
- `buildKiroHooks` ← src/kiro-hooks.ts:78 [EXTRACTED]
  ```
  export function buildKiroHooks(): string {
  ```
- `ownsKiroHooks` ← src/kiro-hooks.ts:85 [EXTRACTED]
  ```
  export async function ownsKiroHooks(): Promise<boolean> {
  ```
- `hasKiroHooks` ← src/kiro-hooks.ts:103 [EXTRACTED]
  ```
  export async function hasKiroHooks(): Promise<boolean> {
  ```
- `injectKiroHooks` ← src/kiro-hooks.ts:147 [EXTRACTED]
  ```
  export async function injectKiroHooks(projectRoot?: string): Promise<void> {
  ```
- `removeKiroHooks` ← src/kiro-hooks.ts:188 [EXTRACTED]
  ```
  export async function removeKiroHooks(): Promise<void> {
  ```
- `SELF_MODE_AGENT_CHOICES` ← src/known-agents.ts:27 [EXTRACTED]
  ```
  export const SELF_MODE_AGENT_CHOICES = ['claude', 'codex', 'cursor', 'copilot', 'pi', 'joycode', 'codebuddy', 'workbuddy', 'muse', 'agy'] as const satisfies readonly ToolId[];
  ```
- `normalizeAgentList` ← src/known-agents.ts:38 [EXTRACTED]
  ```
  export function normalizeAgentList(agent?: string | string[]): string[] {
  ```
- `seedSelfModeToolDirs` ← src/known-agents.ts:187 [EXTRACTED]
  ```
  export async function seedSelfModeToolDirs(
  ```
- `detectHomeInstalledAgents` ← src/known-agents.ts:328 [EXTRACTED]
  ```
  export async function detectHomeInstalledAgents(
  ```
- `getEffectiveAgents` ← src/known-agents.ts:360 [EXTRACTED]
  ```
  export function getEffectiveAgents(
  ```
- `detectInstalledAgents` ← src/known-agents.ts:400 [EXTRACTED]
  ```
  export async function detectInstalledAgents(localConfig: LocalConfig, teamConfig: TeamaiConfig, host: Host = realHost()): Promise<ResolvedAgent[]> {
  ```
- `RUN_MODES` ← src/launch-context.ts:20 [EXTRACTED]
  ```
  export const RUN_MODES = ['attended', 'unattended'] as const;
  ```
- `RunModeSchema` ← src/launch-context.ts:24 [EXTRACTED]
  ```
  export const RunModeSchema = z.enum(RUN_MODES);
  ```
- `explainRunMode` ← src/launch-context.ts:43 [EXTRACTED]
  ```
  export function explainRunMode(env: NodeJS.ProcessEnv): ExplainedRunMode {
  ```
- `agreedRunMode` ← src/launch-context.ts:58 [EXTRACTED]
  ```
  export function agreedRunMode(modes: Iterable<RunMode | undefined>): RunMode | undefined {
  ```
- `resolveRunMode` ← src/launch-context.ts:66 [EXTRACTED]
  ```
  export function resolveRunMode(env: NodeJS.ProcessEnv): RunMode {
  ```
- `attemptMarker` ← src/launch-context.ts:88 [EXTRACTED]
  ```
  export function attemptMarker(env: NodeJS.ProcessEnv): string | undefined {
  ```
- `launchedBy` ← src/launch-context.ts:116 [EXTRACTED]
  ```
  export function launchedBy(vars: Readonly<Record<string, string | undefined>>): string | undefined {
  ```
- `SessionRunSchema` ← src/launch-context.ts:125 [EXTRACTED]
  ```
  export const SessionRunSchema = z.object({ runMode: RunModeSchema, launchedBy: z.string().min(1).optional() });
  ```
- `SESSION_RUN_PAYLOAD_KEY` ← src/launch-context.ts:130 [EXTRACTED]
  ```
  export const SESSION_RUN_PAYLOAD_KEY = 'teamai_run';
  ```
- `sessionRun` ← src/launch-context.ts:133 [EXTRACTED]
  ```
  export function sessionRun(env: NodeJS.ProcessEnv): SessionRun {
  ```
- `readSessionRun` ← src/launch-context.ts:150 [EXTRACTED]
  ```
  export const readSessionRun = ForwardedSessionRunSchema.parse;
  ```
- `LAUNCH_PAYLOAD_KEY` ← src/launch-context.ts:162 [EXTRACTED]
  ```
  export const LAUNCH_PAYLOAD_KEY = 'teamai_launch';
  ```
- `launchEnv` ← src/launch-context.ts:188 [EXTRACTED]
  ```
  export function launchEnv(launch: Launch) {
  ```
- `readLaunch` ← src/launch-context.ts:193 [EXTRACTED]
  ```
  export const readLaunch = LaunchSchema.parse;
  ```
- `workflowLaunch` ← src/launch-context.ts:196 [EXTRACTED]
  ```
  export async function workflowLaunch(config: LocalConfig, tool: string): Promise<Launch | undefined> {
  ```
- `launchHoldsCheckout` ← src/launch-context.ts:210 [EXTRACTED]
  ```
  export async function launchHoldsCheckout(config: LocalConfig, launch: Launch): Promise<boolean> {
  ```
- `KNOWN_FAILURE_CODES` ← oxlint-plugin-teamai/failure-codes.js:44 [EXTRACTED]
  ```
  export const KNOWN_FAILURE_CODES = new Set([...diagnostics, ...answers]);
  ```
- `PROTOCOL_STRING_CONSTANTS` ← oxlint-plugin-teamai/failure-codes.js:47 [EXTRACTED]
  ```
  export const PROTOCOL_STRING_CONSTANTS = new Map(
  ```
- `FS` ← oxlint-plugin-teamai/fs-calls.js:6 [EXTRACTED]
  ```
  export const FS = new Set(['fs', 'node:fs', 'fs/promises', 'node:fs/promises', 'fs-extra']);
  ```
- `isFsModule` ← oxlint-plugin-teamai/fs-calls.js:69 [EXTRACTED]
  ```
  export function isFsModule(sourceCode, node) {
  ```
- `fsFunctionOf` ← oxlint-plugin-teamai/fs-calls.js:108 [EXTRACTED]
  ```
  export function fsFunctionOf(sourceCode, callee) {
  ```
- `openKindOf` ← oxlint-plugin-teamai/fs-calls.js:151 [EXTRACTED]
  ```
  export function openKindOf(flags) {
  ```
- `refersToValue` ← oxlint-plugin-teamai/fs-calls.js:172 [EXTRACTED]
  ```
  export function refersToValue(node) {
  ```
- `isCalled` ← oxlint-plugin-teamai/fs-calls.js:194 [EXTRACTED]
  ```
  export function isCalled(node) {
  ```
- `passesOnFsModule` ← oxlint-plugin-teamai/fs-calls.js:206 [EXTRACTED]
  ```
  export function passesOnFsModule(sourceCode, node) {
  ```
- `reExportsFsModule` ← oxlint-plugin-teamai/fs-calls.js:221 [EXTRACTED]
  ```
  export function reExportsFsModule(node) {
  ```
- `PASSED_ON_MESSAGE` ← oxlint-plugin-teamai/fs-calls.js:226 [EXTRACTED]
  ```
  export const PASSED_ON_MESSAGE = 'This re-exports or passes on a file module, so the reads and writes made through it are out of this rule\'s sight: a wrapper module or a function given the module would read a FIFO a step left without the rule seeing it. Use the module where it stands, or pass on a helper of @teamai/shared/regular-file.';
  ```
- `importedName` ← oxlint-plugin-teamai/imports.js:12 [EXTRACTED]
  ```
  export function importedName(specifier) {
  ```
- `namesExport` ← oxlint-plugin-teamai/imports.js:28 [EXTRACTED]
  ```
  export function namesExport(sourceCode, node, { modules, name }) {
  ```
- `importVisitors` ← oxlint-plugin-teamai/imports.js:93 [EXTRACTED]
  ```
  export function importVisitors(
  ```
- `sourceImport` ← oxlint-plugin-teamai/imports.js:140 [EXTRACTED]
  ```
  export function sourceImport(/** @type {string} */ from, /** @type {string} */ specifier) {
  ```
- `dynamicImports` ← oxlint-plugin-teamai/imports.js:182 [EXTRACTED]
  ```
  export function dynamicImports(file) {
  ```
- `sourceModules` ← oxlint-plugin-teamai/imports.js:199 [EXTRACTED]
  ```
  export function sourceModules(file, includeTypes) {
  ```
- `reachesSource` ← oxlint-plugin-teamai/imports.js:226 [EXTRACTED]
  ```
  export function reachesSource(/** @type {string} */ from, /** @type {(file: string) => boolean} */ forbidden, includeTypes = true) {
  ```
- `definePlugin` ← oxlint-plugin-teamai/index.js:56 [INFERRED]
  ```
  export default definePlugin({
  ```
- `FAMILY` ← oxlint-plugin-teamai/utils.js:10 [EXTRACTED]
  ```
  export const FAMILY = /^tool-(?!(?:core|testing|definitions|launch)$)/;
  ```
- `PROCESS_STARTERS` ← oxlint-plugin-teamai/utils.js:16 [EXTRACTED]
  ```
  export const PROCESS_STARTERS = new Set([
  ```
- `lintedPath` ← oxlint-plugin-teamai/utils.js:39 [EXTRACTED]
  ```
  export function lintedPath(context) {
  ```
- `isOneOf` ← oxlint-plugin-teamai/utils.js:49 [EXTRACTED]
  ```
  export function isOneOf(context, files) {
  ```
- `manifest` ← oxlint-plugin-teamai/utils.js:78 [EXTRACTED]
  ```
  export function manifest(dir) {
  ```
- `workspaceRoot` ← oxlint-plugin-teamai/utils.js:95 [EXTRACTED]
  ```
  export function workspaceRoot(dir) {
  ```
- `workspaceFile` ← oxlint-plugin-teamai/utils.js:114 [EXTRACTED]
  ```
  export function workspaceFile(root, specifier) {
  ```
- `sourcePath` ← oxlint-plugin-teamai/utils.js:151 [EXTRACTED]
  ```
  export function sourcePath(context) {
  ```
- `repositoryPath` ← oxlint-plugin-teamai/utils.js:164 [EXTRACTED]
  ```
  export function repositoryPath(context) {
  ```
- `isTestSupportPath` ← oxlint-plugin-teamai/utils.js:179 [EXTRACTED]
  ```
  export function isTestSupportPath(file) {
  ```
- `inTestSupport` ← oxlint-plugin-teamai/utils.js:188 [EXTRACTED]
  ```
  export function inTestSupport(context) {
  ```
- `isProductionSource` ← oxlint-plugin-teamai/utils.js:197 [EXTRACTED]
  ```
  export function isProductionSource(file) {
  ```
- `isScriptSource` ← oxlint-plugin-teamai/utils.js:209 [EXTRACTED]
  ```
  export function isScriptSource(file) {
  ```
- `inProductionSource` ← oxlint-plugin-teamai/utils.js:218 [EXTRACTED]
  ```
  export function inProductionSource(context) {
  ```
- `scopedFiles` ← oxlint-plugin-teamai/utils.js:227 [EXTRACTED]
  ```
  export function scopedFiles(files) {
  ```
- `stringLiteralValue` ← oxlint-plugin-teamai/utils.js:240 [EXTRACTED]
  ```
  export function stringLiteralValue(node) {
  ```
- `variableOf` ← oxlint-plugin-teamai/utils.js:252 [EXTRACTED]
  ```
  export function variableOf(sourceCode, node, name) {
  ```