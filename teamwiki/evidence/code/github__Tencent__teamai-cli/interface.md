---
title: github__Tencent__teamai-cli interface
domain: code-knowledge
source:
  - scripts/verify/observer.ts
  - src/token-usage/index.ts
  - src/utils/cache-index.ts
  - src/utils/search-index.ts
  - packages/runtime-tools/src/index.ts
  - src/session-flow/adapters/index.ts
  - src/wiki-engine/code-knowledge/ast/index.ts
  - src/wiki-engine/code-knowledge/extractors/index.ts
  - scripts/agent-wait-budget.ts
  - scripts/ci-recipe.ts
  - scripts/tool-support.ts
  - src/agent-observation.ts
  - src/agent-skills.ts
  - src/agy-hook-io.ts
  - src/autocompact-reconcile.ts
  - src/bootstrap.ts
  - src/bridged-team-hooks.ts
  - src/builtin-agents.ts
  - src/builtin-hooks.ts
  - src/builtin-rules.ts
  - src/builtin-skills.ts
  - src/cache-cmd.ts
  - src/checkout-roles.ts
  - src/clone.ts
  - src/coauthor-reconcile.ts
  - src/code-knowledge-recall.ts
  - src/codebase-cmd.ts
  - src/codebase-extract.ts
  - src/codebase-freshness.ts
  - src/codebase-upgrade-wiki.ts
  - src/codebase-wiki-lint.ts
  - src/codebuddy-team-hooks.ts
  - src/codex-project-trust.ts
  - src/codex-team-hooks.ts
  - src/codex-trust.ts
  - src/config.ts
  - src/contribute-check.ts
  - src/dashboard-collector.ts
  - src/deep-enrich.ts
  - src/default-driver.ts
  - src/default-folders.ts
  - src/default-scorers.ts
  - src/default-workflows.ts
  - src/digest-failures.ts
  - src/digest.ts
  - src/doctor.ts
  - src/dsh-hooks.ts
  - src/enrich-with-ai.ts
  - src/env-advisories.ts
  - src/env-exec.ts
  - src/env-listing.ts
  - src/env-resolution.ts
  - src/env-sh-exports.ts
  - src/git-exclude-delivered.ts
  - src/git-exclude-notices.ts
  - src/git-exclude.ts
  - src/git-hook.ts
  - src/hermes-hooks.ts
  - src/hook-command.ts
  - src/hook-dispatch.ts
  - src/hook-fast-path.ts
  - src/hook-handlers.ts
  - src/hooks.ts
  - src/import-codebase.ts
  - src/import-from-mr.ts
  - src/import-from-repo.ts
  - src/import-local.ts
  - src/import-org.ts
  - src/import-repo-list.ts
  - src/import-repo.ts
  - src/installations.ts
  - src/instruction-targets.ts
  - src/iwiki-dual.ts
  - src/known-agents.ts
  - src/launch-context.ts
---

# Interface

- `Listed` ← scripts/verify/observer.ts:167 [EXTRACTED]
  ```
  export type Listed = { kind: 'ran'; stdout: string } | { kind: 'missing' } | { kind: 'failed'; why: string; timedOut: boolean };
  ```
- `ProcEntry` ← scripts/verify/observer.ts:192 [EXTRACTED]
  ```
  export interface ProcEntry {
  ```
- `TokenFormatId` ← src/token-usage/index.ts:25 [EXTRACTED]
  ```
  export type TokenFormatId = keyof typeof FORMATS;
  ```
- `CacheIndexEntry` ← src/utils/cache-index.ts:26 [EXTRACTED]
  ```
  export interface CacheIndexEntry {
  ```
- `CacheIndex` ← src/utils/cache-index.ts:40 [EXTRACTED]
  ```
  export interface CacheIndex {
  ```
- `GcOptions` ← src/utils/cache-index.ts:63 [EXTRACTED]
  ```
  export interface GcOptions {
  ```
- `GcResult` ← src/utils/cache-index.ts:73 [EXTRACTED]
  ```
  export interface GcResult {
  ```
- `UnreadableFile` ← src/utils/search-index.ts:466 [EXTRACTED]
  ```
  export interface UnreadableFile {
  ```
- `IndexedSkills` ← src/utils/search-index.ts:945 [EXTRACTED]
  ```
  export type IndexedSkills =
  ```
- `BuildIndexOptions` ← src/utils/search-index.ts:987 [EXTRACTED]
  ```
  export interface BuildIndexOptions {
  ```
- `SearchResult` ← src/utils/search-index.ts:1305 [EXTRACTED]
  ```
  export interface SearchResult {
  ```
- `ToolsRuntimeDeps` ← packages/runtime-tools/src/index.ts:12 [EXTRACTED]
  ```
  export interface ToolsRuntimeDeps<TCan = Can> {
  ```
- `ToolsStepRuntime` ← packages/runtime-tools/src/index.ts:23 [EXTRACTED]
  ```
  export interface ToolsStepRuntime<TCan = Can> extends StepRuntime<TCan> {
  ```
- `AdapterFactory` ← src/session-flow/adapters/index.ts:26 [EXTRACTED]
  ```
  export type AdapterFactory = (storeDir: string) => AgentAdapter;
  ```
- `AdapterRegistry` ← src/session-flow/adapters/index.ts:51 [EXTRACTED]
  ```
  export interface AdapterRegistry {
  ```
- `ExtractStructuralGraphOptions` ← src/wiki-engine/code-knowledge/ast/index.ts:40 [EXTRACTED]
  ```
  export interface ExtractStructuralGraphOptions {
  ```
- `ExtractorContext` ← src/wiki-engine/code-knowledge/extractors/index.ts:13 [EXTRACTED]
  ```
  export interface ExtractorContext {
  ```
- `AgentWaitBudget` ← scripts/agent-wait-budget.ts:64 [EXTRACTED]
  ```
  export type AgentWaitBudget = z.infer<typeof AgentWaitBudgetSchema>;
  ```
- `CiRecipe` ← scripts/ci-recipe.ts:15 [EXTRACTED]
  ```
  export type CiRecipe = z.infer<typeof RecipeSchema>;
  ```
- `ToolSupportLang` ← scripts/tool-support.ts:22 [EXTRACTED]
  ```
  export type ToolSupportLang = keyof typeof TOOL_SUPPORT_PAGES;
  ```
- `ObservedModel` ← src/agent-observation.ts:49 [EXTRACTED]
  ```
  export type ObservedModel = z.infer<typeof ObservedModelSchema>;
  ```
- `ObservedEffort` ← src/agent-observation.ts:53 [EXTRACTED]
  ```
  export type ObservedEffort = z.infer<typeof ObservedEffortSchema>;
  ```
- `CommitState` ← src/agent-observation.ts:58 [EXTRACTED]
  ```
  export type CommitState = z.infer<typeof CommitStateSchema>;
  ```
- `AgentObservation` ← src/agent-observation.ts:75 [EXTRACTED]
  ```
  export type AgentObservation = z.infer<typeof AgentObservationSchema>;
  ```
- `Used` ← src/agent-observation.ts:80 [EXTRACTED]
  ```
  export type Used = z.infer<typeof UsedSchema>;
  ```
- `ReportedAgent` ← src/agent-observation.ts:99 [EXTRACTED]
  ```
  export type ReportedAgent = z.infer<typeof ReportedAgentSchema>;
  ```
- `PreparedAgent` ← src/agent-observation.ts:106 [EXTRACTED]
  ```
  export type PreparedAgent = z.infer<typeof PreparedAgentSchema>;
  ```
- `RecordedAgent` ← src/agent-observation.ts:114 [EXTRACTED]
  ```
  export type RecordedAgent = AgentObservation | z.infer<typeof DefinitionOnlySchema>;
  ```
- `ToolLaunch` ← src/agent-observation.ts:125 [EXTRACTED]
  ```
  export type ToolLaunch = {
  ```
- `AgentHarness` ← src/agent-observation.ts:346 [EXTRACTED]
  ```
  export type AgentHarness = {
  ```
- `HarnessChange` ← src/agent-observation.ts:391 [EXTRACTED]
  ```
  export type HarnessChange =
  ```
- `SkillSource` ← src/agent-skills.ts:21 [EXTRACTED]
  ```
  export type SkillSource =
  ```
- `AgentSkill` ← src/agent-skills.ts:29 [EXTRACTED]
  ```
  export interface AgentSkill {
  ```
- `AgentSkillsView` ← src/agent-skills.ts:40 [EXTRACTED]
  ```
  export interface AgentSkillsView {
  ```
- `ClassifyContext` ← src/agent-skills.ts:45 [EXTRACTED]
  ```
  export interface ClassifyContext {
  ```
- `AgyHookResult` ← src/agy-hook-io.ts:119 [EXTRACTED]
  ```
  export interface AgyHookResult {
  ```
- `AutoCompactChange` ← src/autocompact-reconcile.ts:72 [EXTRACTED]
  ```
  export interface AutoCompactChange {
  ```
- `AutoCompactReconcileResult` ← src/autocompact-reconcile.ts:83 [EXTRACTED]
  ```
  export interface AutoCompactReconcileResult {
  ```
- `BootstrapResult` ← src/bootstrap.ts:34 [EXTRACTED]
  ```
  export type BootstrapResult = 'bootstrapped' | 'already' | 'skip';
  ```
- `BridgeReply` ← src/bridged-team-hooks.ts:291 [EXTRACTED]
  ```
  export interface BridgeReply {
  ```
- `BuiltinAgentRecord` ← src/builtin-agents.ts:114 [EXTRACTED]
  ```
  export type BuiltinAgentRecord =
  ```
- `BuiltinHookForm` ← src/builtin-hooks.ts:546 [EXTRACTED]
  ```
  export type BuiltinHookForm = { readonly unwaited: boolean; readonly loginDeferred: boolean };
  ```
- `BuiltinHookOverride` ← src/builtin-hooks.ts:776 [EXTRACTED]
  ```
  export interface BuiltinHookOverride {
  ```
- `RecallTexts` ← src/builtin-rules.ts:208 [EXTRACTED]
  ```
  export interface RecallTexts {
  ```
- `RecallFolder` ← src/builtin-rules.ts:220 [EXTRACTED]
  ```
  export interface RecallFolder {
  ```
- `RecallResolution` ← src/builtin-rules.ts:284 [EXTRACTED]
  ```
  export interface RecallResolution {
  ```
- `BuiltinSkillsTarget` ← src/builtin-skills.ts:86 [EXTRACTED]
  ```
  export interface BuiltinSkillsTarget {
  ```
- `CacheCmdOptions` ← src/cache-cmd.ts:9 [EXTRACTED]
  ```
  export interface CacheCmdOptions extends GlobalOptions {
  ```
- `CheckoutRoleWrite` ← src/checkout-roles.ts:23 [EXTRACTED]
  ```
  export type CheckoutRoleWrite =
  ```
- `CloneOpts` ← src/clone.ts:18 [EXTRACTED]
  ```
  export interface CloneOpts {
  ```
- `CloneResult` ← src/clone.ts:29 [EXTRACTED]
  ```
  export interface CloneResult {
  ```
- `CoAuthorChange` ← src/coauthor-reconcile.ts:79 [EXTRACTED]
  ```
  export interface CoAuthorChange {
  ```
- `CoAuthorReconcileResult` ← src/coauthor-reconcile.ts:94 [EXTRACTED]
  ```
  export interface CoAuthorReconcileResult {
  ```
- `SourceAnchor` ← src/code-knowledge-recall.ts:20 [EXTRACTED]
  ```
  export interface SourceAnchor {
  ```
- `CodeKnowledgeResult` ← src/code-knowledge-recall.ts:27 [EXTRACTED]
  ```
  export interface CodeKnowledgeResult {
  ```
- `QueryCodeKnowledgeOptions` ← src/code-knowledge-recall.ts:628 [EXTRACTED]
  ```
  export interface QueryCodeKnowledgeOptions {
  ```
- `CodebaseCmdOptions` ← src/codebase-cmd.ts:19 [EXTRACTED]
  ```
  export interface CodebaseCmdOptions extends GlobalOptions {
  ```
- `ExtractCodebaseOptions` ← src/codebase-extract.ts:54 [EXTRACTED]
  ```
  export interface ExtractCodebaseOptions {
  ```
- `SourceFreshness` ← src/codebase-freshness.ts:17 [EXTRACTED]
  ```
  export type SourceFreshness = 'current' | 'stale' | 'missing' | 'unknown';
  ```
- `CodebaseFreshnessResult` ← src/codebase-freshness.ts:19 [EXTRACTED]
  ```
  export interface CodebaseFreshnessResult {
  ```
- `UpgradeCodebaseWikiOptions` ← src/codebase-upgrade-wiki.ts:14 [EXTRACTED]
  ```
  export interface UpgradeCodebaseWikiOptions {
  ```
- `WikiLintSeverity` ← src/codebase-wiki-lint.ts:17 [EXTRACTED]
  ```
  export type WikiLintSeverity = 'high' | 'medium' | 'low' | 'info';
  ```
- `WikiLintIssue` ← src/codebase-wiki-lint.ts:19 [EXTRACTED]
  ```
  export interface WikiLintIssue {
  ```
- `WikiLintReport` ← src/codebase-wiki-lint.ts:26 [EXTRACTED]
  ```
  export interface WikiLintReport {
  ```
- `CodebuddyProjectGate` ← src/codebuddy-team-hooks.ts:19 [EXTRACTED]
  ```
  export type CodebuddyProjectGate = z.infer<typeof CodebuddyProjectGateSchema>;
  ```
- `RenderedCodebuddyTeamGate` ← src/codebuddy-team-hooks.ts:40 [EXTRACTED]
  ```
  export interface RenderedCodebuddyTeamGate {
  ```
- `CodexProjectTrust` ← src/codex-project-trust.ts:18 [EXTRACTED]
  ```
  export type CodexProjectTrust =
  ```
- `CodexTeamHook` ← src/codex-team-hooks.ts:33 [EXTRACTED]
  ```
  export interface CodexTeamHook {
  ```
- `CodexTrust` ← src/codex-trust.ts:28 [EXTRACTED]
  ```
  export type CodexTrust = (
  ```
- `CodexAt` ← src/codex-trust.ts:57 [EXTRACTED]
  ```
  export interface CodexAt {
  ```
- `CodexHookTrustRequest` ← src/codex-trust.ts:65 [EXTRACTED]
  ```
  export interface CodexHookTrustRequest extends CodexAt {
  ```
- `CodexHookTrustReport` ← src/codex-trust.ts:77 [EXTRACTED]
  ```
  export type CodexHookTrustReport = (
  ```
- `TeamaiInit` ← src/config.ts:837 [EXTRACTED]
  ```
  export type TeamaiInit = { localConfig: LocalConfig; teamConfig: TeamaiConfig };
  ```
- `UnreadableConfigSink` ← src/config.ts:1179 [EXTRACTED]
  ```
  export type UnreadableConfigSink = (configPath: string, error: string) => void;
  ```
- `FrictionReminderParams` ← src/contribute-check.ts:329 [EXTRACTED]
  ```
  export type FrictionReminderParams = DefaultFolderParams<'hooks', 'teamai-friction-reminder'>;
  ```
- `TranscriptScanResult` ← src/dashboard-collector.ts:131 [EXTRACTED]
  ```
  export interface TranscriptScanResult {
  ```
- `LocalRequestRecord` ← src/dashboard-collector.ts:184 [EXTRACTED]
  ```
  export type LocalRequestRecord = z.infer<typeof LocalRequestRecordSchema>;
  ```
- `TranscriptEntry` ← src/dashboard-collector.ts:337 [EXTRACTED]
  ```
  export type TranscriptEntry = z.infer<typeof TranscriptEntrySchema>;
  ```
- `ParseHookEventOptions` ← src/dashboard-collector.ts:1019 [EXTRACTED]
  ```
  export interface ParseHookEventOptions {
  ```
- `GitStateAtStop` ← src/dashboard-collector.ts:2714 [EXTRACTED]
  ```
  export type GitStateAtStop = z.infer<typeof GitAtStopPayloadSchema>;
  ```
- `ComponentBrief` ← src/deep-enrich.ts:552 [EXTRACTED]
  ```
  export interface ComponentBrief {
  ```
- `ArchitectureBrief` ← src/deep-enrich.ts:561 [EXTRACTED]
  ```
  export interface ArchitectureBrief {
  ```
- `DocReply` ← src/deep-enrich.ts:608 [EXTRACTED]
  ```
  export interface DocReply {
  ```
- `ScenariosBrief` ← src/deep-enrich.ts:902 [EXTRACTED]
  ```
  export interface ScenariosBrief {
  ```
- `DeepEnrichTarget` ← src/deep-enrich.ts:1099 [EXTRACTED]
  ```
  export interface DeepEnrichTarget {
  ```
- `DeepEnrichPlan` ← src/deep-enrich.ts:1138 [EXTRACTED]
  ```
  export interface DeepEnrichPlan {
  ```
- `DeepEnrichDoc` ← src/deep-enrich.ts:1213 [EXTRACTED]
  ```
  export type DeepEnrichDoc = { kind: 'component'; slug: string } | { kind: 'architecture' };
  ```
- `DeepEnrichEnd` ← src/deep-enrich.ts:1251 [EXTRACTED]
  ```
  export interface DeepEnrichEnd {
  ```
- `DefaultDrive` ← src/default-driver.ts:17 [EXTRACTED]
  ```
  export type DefaultDrive = { kind: 'drive' | 'awaits'; driver: DriverName } | { kind: 'unassigned' };
  ```
- `ResolvedDefaultDriver` ← src/default-driver.ts:20 [EXTRACTED]
  ```
  export interface ResolvedDefaultDriver { driver: Exclude<Driver, 'skill'>; text: string; file?: string }
  ```
- `DefaultFolderKind` ← src/default-folders.ts:137 [EXTRACTED]
  ```
  export type DefaultFolderKind = keyof typeof PARAMS;
  ```
- `DefaultFolderName` ← src/default-folders.ts:140 [EXTRACTED]
  ```
  export type DefaultFolderName<TKind extends DefaultFolderKind> = keyof (typeof PARAMS)[TKind] & keyof (typeof TEXTS)[TKind] & string;
  ```
- `DefaultFolderParams` ← src/default-folders.ts:143 [EXTRACTED]
  ```
  export type DefaultFolderParams<TKind extends DefaultFolderKind, TName extends DefaultFolderName<TKind>> =
  ```
- `DefaultFolderTextName` ← src/default-folders.ts:159 [EXTRACTED]
  ```
  export type DefaultFolderTextName<TKind extends DefaultFolderKind, TName extends DefaultFolderName<TKind>> = keyof (typeof TEXTS)[TKind][TName] & string;
  ```
- `DefaultFolderRef` ← src/default-folders.ts:166 [EXTRACTED]
  ```
  export interface DefaultFolderRef<TKind extends DefaultFolderKind, TName extends DefaultFolderName<TKind>> {
  ```
- `TextLanguage` ← src/default-folders.ts:172 [EXTRACTED]
  ```
  export type TextLanguage = TeamaiConfig['language'];
  ```
- `PickedText` ← src/default-folders.ts:175 [EXTRACTED]
  ```
  export interface PickedText<TVariable extends string> {
  ```
- `DefaultFolder` ← src/default-folders.ts:182 [EXTRACTED]
  ```
  export interface DefaultFolder<TKind extends DefaultFolderKind, TName extends DefaultFolderName<TKind>> {
  ```
- `DefaultFolderComparison` ← src/default-folders.ts:477 [EXTRACTED]
  ```
  export interface DefaultFolderComparison {
  ```
- `DefaultScorerName` ← src/default-scorers.ts:29 [EXTRACTED]
  ```
  export type DefaultScorerName = keyof typeof VARIABLES;
  ```
- `DefaultScorerValues` ← src/default-scorers.ts:32 [EXTRACTED]
  ```
  export type DefaultScorerValues<TName extends DefaultScorerName> = Record<(typeof VARIABLES)[TName][number], string>;
  ```
- `DefaultScorerCode` ← src/default-scorers.ts:35 [EXTRACTED]
  ```
  export type DefaultScorerCode = 'default_scorer_template' | 'default_scorer_variable' | 'default_scorer_invalid';
  ```
- `FilledScorer` ← src/default-scorers.ts:38 [EXTRACTED]
  ```
  export type FilledScorer = { content: string; definition: ScorerDefinition };
  ```
- `RunOrigin` ← src/default-workflows.ts:111 [EXTRACTED]
  ```
  export type RunOrigin = z.infer<typeof RunOriginSchema>;
  ```
- `ContractCode` ← src/default-workflows.ts:135 [EXTRACTED]
  ```
  export type ContractCode = 'default_override_alias' | 'judging_scored' | ScoreOverrideCode;
  ```
- `DigestFailure` ← src/digest-failures.ts:17 [EXTRACTED]
  ```
  export type DigestFailure = Failure & { task?: string; learnings?: LinkedLearning[] };
  ```
- `DigestFailuresView` ← src/digest-failures.ts:19 [EXTRACTED]
  ```
  export type DigestFailuresView = Omit<ScorerFailures, 'failures'> & { failures: DigestFailure[] };
  ```
- `InterventionSummary` ← src/digest.ts:291 [EXTRACTED]
  ```
  export interface InterventionSummary {
  ```
- `ConversationSummary` ← src/digest.ts:402 [EXTRACTED]
  ```
  export interface ConversationSummary {
  ```
- `CheckSource` ← src/doctor.ts:91 [EXTRACTED]
  ```
  export type CheckSource = 'local' | 'provider';
  ```
- `Check` ← src/doctor.ts:98 [EXTRACTED]
  ```
  export interface Check {
  ```
- `DoctorContext` ← src/doctor.ts:129 [EXTRACTED]
  ```
  export interface DoctorContext {
  ```
- `DoctorOptions` ← src/doctor.ts:150 [EXTRACTED]
  ```
  export interface DoctorOptions extends GlobalOptions {
  ```
- `CheckOutcome` ← src/doctor.ts:163 [EXTRACTED]
  ```
  export type CheckOutcome = boolean | 'warn';
  ```
- `CheckResult` ← src/doctor.ts:166 [EXTRACTED]
  ```
  export type CheckResult =
  ```
- `DoctorReport` ← src/doctor.ts:172 [EXTRACTED]
  ```
  export interface DoctorReport {
  ```
- `CheckStage` ← src/doctor.ts:838 [EXTRACTED]
  ```
  export type CheckStage = 'pull' | 'doctor';
  ```
- `DshHookReconcileOptions` ← src/dsh-hooks.ts:137 [EXTRACTED]
  ```
  export interface DshHookReconcileOptions {
  ```
- `EnrichContext` ← src/enrich-with-ai.ts:17 [EXTRACTED]
  ```
  export interface EnrichContext {
  ```
- `EnrichResult` ← src/enrich-with-ai.ts:24 [EXTRACTED]
  ```
  export interface EnrichResult {
  ```
- `ModuleBrief` ← src/enrich-with-ai.ts:54 [EXTRACTED]
  ```
  export interface ModuleBrief {
  ```
- `CodebaseEnrichTarget` ← src/enrich-with-ai.ts:321 [EXTRACTED]
  ```
  export interface CodebaseEnrichTarget {
  ```
- `CodebaseEnrichPlan` ← src/enrich-with-ai.ts:369 [EXTRACTED]
  ```
  export interface CodebaseEnrichPlan {
  ```
- `ModuleReply` ← src/enrich-with-ai.ts:384 [EXTRACTED]
  ```
  export interface ModuleReply {
  ```
- `CodebaseEnrichSummary` ← src/enrich-with-ai.ts:427 [EXTRACTED]
  ```
  export interface CodebaseEnrichSummary {
  ```
- `CodebaseEnrichWritten` ← src/enrich-with-ai.ts:444 [EXTRACTED]
  ```
  export interface CodebaseEnrichWritten {
  ```
- `EdgeProvenance` ← src/enrich-with-ai.ts:468 [EXTRACTED]
  ```
  export interface EdgeProvenance {
  ```
- `EnvAdvisory` ← src/env-advisories.ts:17 [EXTRACTED]
  ```
  export type EnvAdvisory =
  ```
- `ExecOutcome` ← src/env-exec.ts:37 [EXTRACTED]
  ```
  export type ExecOutcome =
  ```
- `CommandSignalPolicy` ← src/env-exec.ts:54 [EXTRACTED]
  ```
  export interface CommandSignalPolicy {
  ```
- `EnvListingLine` ← src/env-listing.ts:19 [EXTRACTED]
  ```
  export interface EnvListingLine {
  ```
- `EnvListing` ← src/env-listing.ts:25 [EXTRACTED]
  ```
  export interface EnvListing {
  ```
- `SecretValue` ← src/env-resolution.ts:29 [EXTRACTED]
  ```
  export interface SecretValue {
  ```
- `SecretState` ← src/env-resolution.ts:35 [EXTRACTED]
  ```
  export type SecretState = SecretValue['source'] | 'missing' | 'unreadable';
  ```
- `VariableValue` ← src/env-resolution.ts:47 [EXTRACTED]
  ```
  export interface VariableValue {
  ```
- `StoreResolution` ← src/env-resolution.ts:54 [EXTRACTED]
  ```
  export type StoreResolution<V> =
  ```
- `TeamEnv` ← src/env-resolution.ts:58 [EXTRACTED]
  ```
  export interface TeamEnv {
  ```
- `UnsetReference` ← src/env-resolution.ts:105 [EXTRACTED]
  ```
  export interface UnsetReference {
  ```
- `AppliedTeamEnv` ← src/env-resolution.ts:194 [EXTRACTED]
  ```
  export interface AppliedTeamEnv {
  ```
- `WorkflowEnv` ← src/env-resolution.ts:461 [EXTRACTED]
  ```
  export interface WorkflowEnv {
  ```
- `EnvShExports` ← src/env-sh-exports.ts:27 [EXTRACTED]
  ```
  export type EnvShExports = ReadonlyMap<string, ReadonlySet<string>>;
  ```
- `WriterId` ← src/git-exclude-delivered.ts:40 [EXTRACTED]
  ```
  export type WriterId = (typeof WRITER_IDS)[number];
  ```
- `GitExcludePaths` ← src/git-exclude-delivered.ts:43 [EXTRACTED]
  ```
  export type GitExcludePaths = Record<string, string[]>;
  ```
- `DeliveryRecorder` ← src/git-exclude-delivered.ts:59 [EXTRACTED]
  ```
  export interface DeliveryRecorder {
  ```
- `ListedCheckout` ← src/git-exclude-delivered.ts:193 [EXTRACTED]
  ```
  export interface ListedCheckout {
  ```
- `ForeignPath` ← src/git-exclude-delivered.ts:199 [EXTRACTED]
  ```
  export interface ForeignPath {
  ```
- `DeliveredUnion` ← src/git-exclude-delivered.ts:210 [EXTRACTED]
  ```
  export interface DeliveredUnion {
  ```
- `DeliveredGitExcludeOutcome` ← src/git-exclude-delivered.ts:346 [EXTRACTED]
  ```
  export interface DeliveredGitExcludeOutcome {
  ```
- `GitExcludeNotice` ← src/git-exclude-notices.ts:27 [EXTRACTED]
  ```
  export interface GitExcludeNotice {
  ```
- `GitExcludeNotices` ← src/git-exclude-notices.ts:32 [EXTRACTED]
  ```
  export interface GitExcludeNotices {
  ```
- `GitExcludeNoticesHome` ← src/git-exclude-notices.ts:47 [EXTRACTED]
  ```
  export type GitExcludeNoticesHome = LocalConfig | { stateHome: string; owner: string; label: string };
  ```
- `GitExcludeOwner` ← src/git-exclude.ts:32 [EXTRACTED]
  ```
  export interface GitExcludeOwner {
  ```
- `GitExcludeFileRecord` ← src/git-exclude.ts:38 [EXTRACTED]
  ```
  export interface GitExcludeFileRecord {
  ```
- `DamagedMarker` ← src/git-exclude.ts:86 [EXTRACTED]
  ```
  export interface DamagedMarker {
  ```
- `GitTracking` ← src/git-exclude.ts:309 [EXTRACTED]
  ```
  export type GitTracking =
  ```
- `ReincludingRule` ← src/git-exclude.ts:393 [EXTRACTED]
  ```
  export interface ReincludingRule {
  ```
- `ExcludeUpdate` ← src/git-exclude.ts:493 [EXTRACTED]
  ```
  export type ExcludeUpdate = 'written' | 'unchanged' | 'locked';
  ```
- `RefusedPath` ← src/git-exclude.ts:616 [EXTRACTED]
  ```
  export interface RefusedPath {
  ```
- `GitExcludeWrite` ← src/git-exclude.ts:810 [EXTRACTED]
  ```
  export type GitExcludeWrite =
  ```
- `GitCheckFailure` ← src/git-exclude.ts:817 [EXTRACTED]
  ```
  export interface GitCheckFailure {
  ```
- `TrackedPath` ← src/git-exclude.ts:823 [EXTRACTED]
  ```
  export interface TrackedPath {
  ```
- `GitExcludeFileSync` ← src/git-exclude.ts:828 [EXTRACTED]
  ```
  export interface GitExcludeFileSync {
  ```
- `GitExcludeSync` ← src/git-exclude.ts:841 [EXTRACTED]
  ```
  export interface GitExcludeSync {
  ```
- `GitExcludeEnsure` ← src/git-exclude.ts:1067 [EXTRACTED]
  ```
  export type GitExcludeEnsure =
  ```
- `GitExcludeLine` ← src/git-exclude.ts:1266 [EXTRACTED]
  ```
  export interface GitExcludeLine {
  ```
- `GitExcludeFileRemoval` ← src/git-exclude.ts:1272 [EXTRACTED]
  ```
  export interface GitExcludeFileRemoval {
  ```
- `GitExcludeFileReport` ← src/git-exclude.ts:1387 [EXTRACTED]
  ```
  export interface GitExcludeFileReport {
  ```
- `GitExcludeReport` ← src/git-exclude.ts:1409 [EXTRACTED]
  ```
  export interface GitExcludeReport {
  ```
- `GitHookEvent` ← src/git-hook.ts:37 [EXTRACTED]
  ```
  export type GitHookEvent = (typeof GIT_HOOK_EVENTS)[number];
  ```
- `GitHookInstall` ← src/git-hook.ts:92 [EXTRACTED]
  ```
  export type GitHookInstall =
  ```
- `GitHookStatus` ← src/git-hook.ts:96 [EXTRACTED]
  ```
  export type GitHookStatus =
  ```
- `GitHookFailure` ← src/git-hook.ts:453 [EXTRACTED]
  ```
  export type GitHookFailure =
  ```
- `GitHookFailureReport` ← src/git-hook.ts:460 [EXTRACTED]
  ```
  export interface GitHookFailureReport {
  ```
- `InstructionsSection` ← src/hermes-hooks.ts:46 [EXTRACTED]
  ```
  export type InstructionsSection =
  ```
- `HermesInstructionsPlugin` ← src/hermes-hooks.ts:263 [EXTRACTED]
  ```
  export interface HermesInstructionsPlugin {
  ```
- `HookRun` ← src/hook-command.ts:13 [EXTRACTED]
  ```
  export interface HookRun {
  ```
- `HookStdin` ← src/hook-dispatch.ts:29 [EXTRACTED]
  ```
  export type HookStdin = z.infer<typeof HookStdinSchema>;
  ```
- `HookHandler` ← src/hook-dispatch.ts:38 [EXTRACTED]
  ```
  export interface HookHandler {
  ```
- `HandlerRegistration` ← src/hook-dispatch.ts:52 [EXTRACTED]
  ```
  export interface HandlerRegistration {
  ```
- `DispatchMode` ← src/hook-dispatch.ts:90 [EXTRACTED]
  ```
  export type DispatchMode = 'all' | 'foreground' | 'background';
  ```
- `DispatchError` ← src/hook-dispatch.ts:92 [EXTRACTED]
  ```
  export interface DispatchError {
  ```
- `DispatchResult` ← src/hook-dispatch.ts:97 [EXTRACTED]
  ```
  export interface DispatchResult {
  ```
- `DispatcherConfig` ← src/hook-dispatch.ts:104 [EXTRACTED]
  ```
  export interface DispatcherConfig {
  ```
- `Dispatcher` ← src/hook-dispatch.ts:110 [EXTRACTED]
  ```
  export interface Dispatcher {
  ```
- `FastHook` ← src/hook-fast-path.ts:75 [EXTRACTED]
  ```
  export interface FastHook {
  ```
- `ArgvVerdict` ← src/hook-fast-path.ts:82 [EXTRACTED]
  ```
  export type ArgvVerdict = { kind: 'skip' } | { kind: 'full' } | { kind: 'payload'; hook: FastHook };
  ```
- `FastPathOutcome` ← src/hook-fast-path.ts:224 [EXTRACTED]
  ```
  export type FastPathOutcome = 'done' | 'full';
  ```
- `HandlerRegistration` ← src/hook-handlers.ts:29 [EXTRACTED]
  ```
  export interface HandlerRegistration {
  ```
- `HookEventNames` ← src/hooks.ts:89 [EXTRACTED]
  ```
  export interface HookEventNames {
  ```
- `HookStatus` ← src/hooks.ts:233 [EXTRACTED]
  ```
  export type HookStatus = 'installed' | 'missing';
  ```
- `CodexTrustPolicy` ← src/hooks.ts:281 [EXTRACTED]
  ```
  export type CodexTrustPolicy = { kind: 'enabled'; codexHome: string } | { kind: 'disabled' };
  ```
- `ReconcileHooksOptions` ← src/hooks.ts:407 [EXTRACTED]
  ```
  export interface ReconcileHooksOptions {
  ```
- `TeamHookHistory` ← src/hooks.ts:474 [EXTRACTED]
  ```
  export type TeamHookHistory = () => Promise<HookDef[]>;
  ```
- `ManagedHookRecord` ← src/hooks.ts:802 [EXTRACTED]
  ```
  export type ManagedHookRecord = {
  ```
- `ManagedHooksManifest` ← src/hooks.ts:813 [EXTRACTED]
  ```
  export type ManagedHooksManifest = Record<string, ManagedHookRecord[]>;
  ```
- `BuiltinsOnly` ← src/hooks.ts:821 [EXTRACTED]
  ```
  export type BuiltinsOnly = 'with-overrides' | 'defaults-where-none';
  ```
- `SharedHooksManifest` ← src/hooks.ts:830 [EXTRACTED]
  ```
  export interface SharedHooksManifest {
  ```
- `MainCheckoutHooks` ← src/hooks.ts:1292 [EXTRACTED]
  ```
  export interface MainCheckoutHooks {
  ```
- `CodexGroupSlot` ← src/hooks.ts:2733 [EXTRACTED]
  ```
  export type CodexGroupSlot = { keep: number } | { write: CodexHookMatcher };
  ```
- `AgentHookDef` ← src/hooks.ts:3145 [EXTRACTED]
  ```
  export interface AgentHookDef {
  ```
- `BuiltinHookFormSource` ← src/hooks.ts:3652 [EXTRACTED]
  ```
  export type BuiltinHookFormSource = 'installed' | 'version';
  ```
- `TeamHooksReconcile` ← src/hooks.ts:5187 [EXTRACTED]
  ```
  export type TeamHooksReconcile = {
  ```
- `ImportCodebaseOptions` ← src/import-codebase.ts:58 [EXTRACTED]
  ```
  export interface ImportCodebaseOptions {
  ```
- `StagedCodebase` ← src/import-codebase.ts:412 [EXTRACTED]
  ```
  export interface StagedCodebase {
  ```
- `MrImport` ← src/import-from-mr.ts:388 [EXTRACTED]
  ```
  export interface MrImport {
  ```
- `ImportMode` ← src/import-from-repo.ts:22 [EXTRACTED]
  ```
  export type ImportMode = z.infer<typeof ImportModeSchema>;
  ```
- `ImportItem` ← src/import-from-repo.ts:42 [EXTRACTED]
  ```
  export type ImportItem =
  ```
- `ImportSettings` ← src/import-from-repo.ts:75 [EXTRACTED]
  ```
  export interface ImportSettings {
  ```
- `StagedItem` ← src/import-from-repo.ts:158 [EXTRACTED]
  ```
  export interface StagedItem {
  ```
- `ImportedItem` ← src/import-from-repo.ts:406 [EXTRACTED]
  ```
  export interface ImportedItem {
  ```
- `ImportEnd` ← src/import-from-repo.ts:414 [EXTRACTED]
  ```
  export interface ImportEnd {
  ```
- `Candidate` ← src/import-local.ts:32 [EXTRACTED]
  ```
  export type Candidate = z.infer<typeof CandidateSchema>;
  ```
- `LearningsImport` ← src/import-local.ts:302 [EXTRACTED]
  ```
  export interface LearningsImport {
  ```
- `ImportFromOrgOptions` ← src/import-org.ts:29 [EXTRACTED]
  ```
  export interface ImportFromOrgOptions {
  ```
- `ImportFromRepoListOptions` ← src/import-repo-list.ts:8 [EXTRACTED]
  ```
  export interface ImportFromRepoListOptions {
  ```
- `RepoListImport` ← src/import-repo-list.ts:32 [EXTRACTED]
  ```
  export type RepoListImport =
  ```
- `RepoSource` ← src/import-repo.ts:220 [EXTRACTED]
  ```
  export interface RepoSource {
  ```
- `RepoFetchOptions` ← src/import-repo.ts:244 [EXTRACTED]
  ```
  export interface RepoFetchOptions {
  ```
- `RepoFetched` ← src/import-repo.ts:302 [EXTRACTED]
  ```
  export type RepoFetched = { kind: 'fetched'; sha: string; branch: string } | { kind: 'unchanged'; sha: string };
  ```
- `InstallationMethod` ← src/installations.ts:20 [EXTRACTED]
  ```
  export type InstallationMethod = z.infer<typeof InstallationMethodSchema>;
  ```
- `InstallationRecord` ← src/installations.ts:39 [EXTRACTED]
  ```
  export type InstallationRecord = z.infer<typeof InstallationRecordSchema>;
  ```
- `InstructionTarget` ← src/instruction-targets.ts:91 [EXTRACTED]
  ```
  export interface InstructionTarget {
  ```
- `InstructionHook` ← src/instruction-targets.ts:102 [EXTRACTED]
  ```
  export interface InstructionHook {
  ```
- `InstructionTargets` ← src/instruction-targets.ts:111 [EXTRACTED]
  ```
  export interface InstructionTargets {
  ```
- `InstructionBlocks` ← src/instruction-targets.ts:130 [EXTRACTED]
  ```
  export interface InstructionBlocks {
  ```
- `InstructionFileChange` ← src/instruction-targets.ts:614 [EXTRACTED]
  ```
  export interface InstructionFileChange {
  ```
- `InstructionPlan` ← src/instruction-targets.ts:621 [EXTRACTED]
  ```
  export interface InstructionPlan {
  ```
- `InstructionFileResult` ← src/instruction-targets.ts:627 [EXTRACTED]
  ```
  export interface InstructionFileResult {
  ```
- `SectionsFlags` ← src/iwiki-dual.ts:140 [EXTRACTED]
  ```
  export interface SectionsFlags {
  ```
- `AgentCategory` ← src/known-agents.ts:69 [EXTRACTED]
  ```
  export type AgentCategory = 'coding' | 'lobster' | 'central';
  ```
- `KnownAgent` ← src/known-agents.ts:71 [EXTRACTED]
  ```
  export interface KnownAgent {
  ```
- `ResolvedAgent` ← src/known-agents.ts:141 [EXTRACTED]
  ```
  export interface ResolvedAgent extends KnownAgent {
  ```
- `RunMode` ← src/launch-context.ts:22 [EXTRACTED]
  ```
  export type RunMode = typeof RUN_MODES[number];
  ```
- `RunModeSource` ← src/launch-context.ts:32 [EXTRACTED]
  ```
  export type RunModeSource = typeof RUN_MODE_ENV | 'CI' | 'default';
  ```
- `ExplainedRunMode` ← src/launch-context.ts:35 [EXTRACTED]
  ```
  export type ExplainedRunMode =
  ```
- `SessionRun` ← src/launch-context.ts:127 [EXTRACTED]
  ```
  export type SessionRun = z.infer<typeof SessionRunSchema>;
  ```
- `LaunchedBy` ← src/launch-context.ts:156 [EXTRACTED]
  ```
  export type LaunchedBy = 'workflow' | 'confined' | 'answer';
  ```
- `Launch` ← src/launch-context.ts:159 [EXTRACTED]
  ```
  export type Launch = { by: 'workflow'; tool: string; checkout: string };
  ```