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
  - src/launch-registry.ts
  - src/lint-resource-graph.ts
  - src/locate.ts
  - src/manifest-schema.ts
  - src/mcp-git-exclude.ts
  - src/mcp-reconcile.ts
  - src/mcp-resolved-files.ts
  - src/member-env.ts
  - src/member-settings-report.ts
  - src/members.ts
  - src/migrate.ts
  - src/mr-hint.ts
  - src/namespace-resolver.ts
  - src/namespaced-entries.ts
  - src/openclaw-home.ts
  - src/outcomes.ts
  - src/pid-monitor.ts
  - src/plugin-lifecycle.ts
  - src/projects.ts
  - src/pull.ts
  - src/push-file.ts
  - src/push-namespaces.ts
  - src/read-gates.ts
  - src/recall-adoption.ts
  - src/recall-log.ts
  - src/recall-provenance.ts
  - src/recall.ts
  - src/resource-namespaces.ts
  - src/resource-relations.ts
  - src/review-branch.ts
  - src/review-cmd.ts
  - src/review-store.ts
  - src/role-assignments.ts
  - src/roles-cmd.ts
  - src/roles.ts
  - src/save-session.ts
  - src/score-commands.ts
  - src/score-drain.ts
  - src/score-verbs.ts
  - src/secret-store.ts
  - src/section-patcher.ts
  - src/self-improvement.ts
  - src/session-analytics.ts
  - src/session-collector.ts
  - src/session-outcomes.ts
  - src/session-owners.ts
  - src/session-trends.ts
  - src/shared-instruction-source.ts
  - src/skill-command.ts
  - src/skill-content.ts
  - src/skill-directory.ts
  - src/skill-owned-files.ts
  - src/skill-use.ts
  - src/source.ts
  - src/stats.ts
  - src/status.ts
  - src/team-push.ts
  - src/team-ref.ts
  - src/team-scripts.ts
  - src/teamai-only-files.ts
  - src/tool-home-record.ts
  - src/tool-home.ts
  - src/tool-instances.ts
  - src/tool-registry.ts
  - src/tools.ts
  - src/types.ts
  - src/update-policy.ts
  - src/update.ts
  - src/usage-tracker.ts
  - src/viz.ts
  - src/votes.ts
  - src/webhook-formatters.ts
  - src/workflow-commands.ts
  - src/workflow-drive.ts
  - src/workflow-offers.ts
  - src/workflow-published-runs.ts
  - src/workspace-children.ts
  - scripts/verify/instances.ts
  - scripts/verify/ledger.ts
  - scripts/verify/leftovers.ts
  - scripts/verify/secrets.ts
  - scripts/verify/shipped-homes.ts
  - scripts/verify/target.ts
  - scripts/verify/world.ts
  - src/benchmark/agent-match.ts
  - src/benchmark/arm-workflow.ts
  - src/benchmark/calibration.ts
  - src/benchmark/estimate.ts
  - src/benchmark/history.ts
  - src/benchmark/pairing.ts
  - src/benchmark/plan.ts
  - src/benchmark/report.ts
  - src/benchmark/result.ts
  - src/benchmark/run-plan.ts
  - src/benchmark/start.ts
  - src/benchmark/suite-cache.ts
  - src/benchmark/suite.ts
  - src/benchmark/table.ts
  - src/benchmark/terms.ts
  - src/benchmark/trial.ts
  - src/benchmark/verdicts.ts
  - src/ci/extract-mr.ts
  - src/ci/mr-comment.ts
  - src/ci/read-rejections.ts
  - src/dashboard/benchmarks.ts
  - src/dashboard/delivery.ts
  - src/dashboard/distribution.ts
  - src/dashboard/http.ts
  - src/dashboard/improvement.ts
  - src/dashboard/judging-health.ts
  - src/dashboard/layered-resources.ts
  - src/dashboard/member-settings.ts
  - src/dashboard/resources-skills.ts
  - src/dashboard/resources.ts
  - src/dashboard/scorers.ts
  - src/dashboard/self-improvement.ts
  - src/dashboard/session-sharing.ts
  - src/dashboard/token-costs.ts
  - src/dashboard/workflow-runs.ts
  - src/dashboard/workspaces.ts
  - src/maintenance/confidence.ts
  - src/maintenance/paths.ts
  - src/maintenance/promote.ts
  - src/maintenance/promotion-publish.ts
  - src/maintenance/prune.ts
  - src/maintenance/quality-update.ts
  - src/models/aliases.ts
  - src/models/profile.ts
  - src/models/switch.ts
  - src/pkg/commands.ts
  - src/pkg/env-detect.ts
  - src/pkg/pkg-hint.ts
  - src/pkg/types.ts
  - src/providers/registry.ts
  - src/providers/types.ts
  - src/repo-list/schema.ts
  - src/resources/agent-format.ts
  - src/resources/agents.ts
  - src/resources/base.ts
  - src/resources/delivered-copies.ts
  - src/resources/delivered-folders.ts
  - src/resources/desired.ts
  - src/resources/docs.ts
  - src/resources/env-loader.ts
  - src/resources/env.ts
  - src/resources/folder-files.ts
  - src/resources/hooks.ts
  - src/resources/inherited-folders.ts
  - src/resources/layered-entries.ts
  - src/resources/mcp-format.ts
  - src/resources/mcp.ts
  - src/resources/opencode-config.ts
  - src/resources/places.ts
  - src/resources/resolver.ts
  - src/resources/rule-format.ts
  - src/resources/rules.ts
  - src/resources/secrets.ts
  - src/resources/skills.ts
  - src/resources/team-skill-source.ts
  - src/scorers/attempts-upgrade.ts
  - src/scorers/batch.ts
  - src/scorers/cache.ts
  - src/scorers/check-run.ts
  - src/scorers/check.ts
  - src/scorers/definition.ts
  - src/scorers/evidence-dir.ts
  - src/scorers/evidence.ts
  - src/scorers/failure-links.ts
  - src/scorers/folder.ts
  - src/scorers/generated-questions.ts
  - src/scorers/isolation.ts
  - src/scorers/judge-model.ts
  - src/scorers/judging-workflows.ts
  - src/scorers/label-store.ts
  - src/scorers/label.ts
  - src/scorers/marks.ts
  - src/scorers/named-subject.ts
  - src/scorers/pass-scoring.ts
  - src/scorers/pin.ts
  - src/scorers/results.ts
  - src/scorers/run-judging.ts
  - src/scorers/run-scorers.ts
  - src/scorers/score-attempt.ts
  - src/scorers/score-labels.ts
  - src/scorers/score-override.ts
  - src/scorers/score-plan.ts
  - src/scorers/score-stage.ts
  - src/scorers/score-subjects.ts
  - src/scorers/scoring-evidence.ts
  - src/scorers/scoring-stages.ts
  - src/scorers/settings.ts
  - src/scorers/skill-evidence.ts
  - src/scorers/subject.ts
  - src/scorers/team-sync.ts
  - src/scorers/tried-file.ts
  - src/scorers/try-scorer.ts
  - src/session-flow/agent-session.ts
  - src/session-flow/archive.ts
  - src/session-flow/captures.ts
  - src/session-flow/finished-sessions.ts
  - src/session-flow/migrate.ts
  - src/session-flow/scoring.ts
  - src/session-flow/scrub.ts
  - src/session-flow/search.ts
  - src/session-flow/session-cmd-shared.ts
  - src/session-flow/session-evidence.ts
  - src/session-flow/session-policy.ts
  - src/session-flow/session-publish.ts
  - src/session-flow/session-work.ts
  - src/session-flow/sync.ts
  - src/session-flow/task-candidates.ts
  - src/token-usage/pricing.ts
  - src/utils/branch-worktree.ts
  - src/utils/frontmatter.ts
  - src/utils/fs.ts
  - src/utils/git-answers.ts
  - src/utils/git-ref-files.ts
  - src/utils/git.ts
  - src/utils/iwiki-client.ts
  - src/utils/jsonl-store.ts
  - src/utils/learnings-publish.ts
  - src/utils/learnings-roots.ts
  - src/utils/partition.ts
  - src/utils/pending-learnings.ts
  - src/utils/pending-push.ts
  - src/utils/reports-branch.ts
  - src/utils/session-id.ts
  - src/utils/shell-command.ts
  - src/utils/shell-profile.ts
  - src/utils/tags.ts
  - src/utils/team-codebase-paths.ts
  - src/utils/team-history.ts
  - src/utils/team-revision.ts
  - src/utils/teamwiki-root.ts
  - src/utils/tool-call.ts
  - src/utils/tool-names.ts
  - src/wiki-engine/call-chain-tracer.ts
  - src/wiki-engine/interface-scanner.ts
  - src/wiki-engine/knowledge-reconciler.ts
  - src/wiki-engine/manifest-schema.ts
  - src/wiki-engine/reconciler-v2-types.ts
  - src/workflow/admission.ts
  - src/workflow/attempt-marker.ts
  - src/workflow/attempt-result.ts
  - src/workflow/cache.ts
  - src/workflow/clone.ts
  - src/workflow/confined-launch.ts
  - src/workflow/confined-place.ts
  - src/workflow/confined-step.ts
  - src/workflow/conformance-interpreter.ts
  - src/workflow/delivery-ledger.ts
  - src/workflow/delivery-schema.ts
  - src/workflow/describe.ts
  - src/workflow/driver-name.ts
  - src/workflow/engine.ts
  - src/workflow/ephemeral-scope.ts
  - src/workflow/expression.ts
  - src/workflow/failure-codes.ts
  - src/workflow/fan-out.ts
  - src/workflow/folder.ts
  - src/workflow/handoff.ts
  - src/workflow/judge-work.ts
  - src/workflow/kept-setting.ts
  - src/workflow/lease-wire.ts
  - src/workflow/leftovers.ts
  - src/workflow/limits.ts
  - src/workflow/loop.ts
  - src/workflow/member-tools.ts
  - src/workflow/parse-context.ts
  - src/workflow/part-of-step.ts
  - src/workflow/pr-delivery.ts
  - src/workflow/pr-url.ts
  - src/workflow/protocol.ts
  - src/workflow/reads.ts
  - src/workflow/records.ts
  - src/workflow/requirements.ts
  - src/workflow/reserved-drivers.ts
  - src/workflow/retention.ts
  - src/workflow/run-controls.ts
  - src/workflow/scope.ts
  - src/workflow/session-apps.ts
  - src/workflow/shell-command.ts
  - src/workflow/snapshot.ts
  - src/workflow/step-model.ts
  - src/workflow/step-path.ts
  - src/workflow/step-state.ts
  - src/workflow/store.ts
  - src/workflow/team-pin.ts
  - src/workflow/template.ts
  - src/workflow/types.ts
  - src/workflow/usage-limits.ts
  - src/workflow/whole-workflow.ts
  - src/workflow/workspace.ts
  - src/workflow/worktree.ts
  - oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts
  - oxlint-plugin-teamai/anti-slop/shared/function-parameters.ts
  - oxlint-plugin-teamai/anti-slop/shared/type-alias-resolution.ts
  - packages/provider-core/src/contract.ts
  - packages/provider-core/src/registry.ts
  - packages/runtime-kit/src/answering.ts
  - packages/runtime-kit/src/journal.ts
  - packages/runtime-kit/src/ledger.ts
  - packages/runtime-kit/src/outer.ts
  - packages/runtime-kit/src/places.ts
  - packages/runtime-kit/src/serve.ts
  - packages/runtime-paseo/src/conversation.ts
  - packages/runtime-paseo/src/journal.ts
  - packages/runtime-paseo/src/offer.ts
  - packages/runtime-paseo/src/options.ts
  - packages/runtime-paseo/src/process-state.ts
  - packages/runtime-paseo/src/providers.ts
  - packages/runtime-paseo/src/runtime.ts
  - packages/runtime-paseo/src/sandbox.ts
  - packages/runtime-paseo/src/workspace.ts
  - packages/runtime-protocol/src/protocol.ts
  - packages/runtime-protocol/src/step-runtime.ts
  - packages/runtime-sandbox/src/attempt-socket.ts
  - packages/runtime-sandbox/src/bounded-tail.ts
  - packages/runtime-sandbox/src/exec.ts
  - packages/runtime-sandbox/src/journal.ts
  - packages/runtime-sandbox/src/judge.ts
  - packages/runtime-sandbox/src/loopback.ts
  - packages/runtime-sandbox/src/options.ts
  - packages/runtime-sandbox/src/provider.ts
  - packages/runtime-sandbox/src/runtime.ts
  - packages/runtime-sandbox/src/sign-in.ts
  - packages/runtime-sandbox/src/warm.ts
  - packages/runtime-sandbox/src/wrapper.ts
  - packages/runtime-t3/src/add-instance.ts
  - packages/runtime-t3/src/added-projects.ts
  - packages/runtime-t3/src/auth.ts
  - packages/runtime-t3/src/conversation.ts
  - packages/runtime-t3/src/instances.ts
  - packages/runtime-t3/src/journal.ts
  - packages/runtime-t3/src/options.ts
  - packages/runtime-t3/src/runtime.ts
  - packages/runtime-t3/src/sessions.ts
  - packages/runtime-t3/src/settings.ts
  - packages/runtime-t3/src/t3-command.ts
  - packages/runtime-t3/src/t3.ts
  - packages/runtime-t3/src/tool-instances.ts
  - packages/runtime-testing/src/connect.ts
  - packages/runtime-tools/src/confined.ts
  - packages/runtime-tools/src/step.ts
  - packages/shared/src/exec.ts
  - packages/shared/src/fs-failure.ts
  - packages/shared/src/json.ts
  - packages/shared/src/lookpath.ts
  - packages/shared/src/process-group.ts
  - packages/shared/src/redact.ts
  - packages/shared/src/regular-file.ts
  - packages/tool-codebuddy/src/codebuddy-adapter.ts
  - packages/tool-codebuddy/src/ide-history.ts
  - packages/tool-codebuddy/src/workbuddy-store.ts
  - packages/tool-core/src/definition.ts
  - packages/tool-core/src/detect.ts
  - packages/tool-core/src/family.ts
  - packages/tool-core/src/instance.ts
  - packages/tool-core/src/launch.ts
  - packages/tool-core/src/registry.ts
  - packages/tool-core/src/stdout.ts
  - packages/tool-core/src/step-usage.ts
  - packages/tool-core/src/tokens.ts
  - packages/tool-cursor/src/cursor-store.ts
  - packages/tool-launch/src/call-launch.ts
  - packages/tool-launch/src/confined-launch.ts
  - packages/tool-launch/src/run-step-launch.ts
  - packages/tool-testing/src/conformance.ts
  - packages/tool-testing/src/fake-agent.ts
  - packages/tool-testing/src/replay-transcript.ts
  - scripts/verify/leftovers/processes.ts
  - src/pkg/adapters/base.ts
  - src/pkg/adapters/claude-plugin.ts
  - src/providers/cnb/cnb-cli.ts
  - src/providers/gitcode/gitcode-api.ts
  - src/providers/github/gh-cli.ts
  - src/providers/gitlab/gitlab-api.ts
  - src/providers/gitlab/mr-fetch.ts
  - src/providers/tgit/gf-cli.ts
  - src/providers/tgit/rest-auth.ts
  - src/session-flow/adapters/platform-facts.ts
  - src/wiki-engine/adapters/templates.ts
  - src/wiki-engine/code-knowledge/code-collector.ts
  - src/wiki-engine/code-knowledge/code-extractors.ts
  - src/wiki-engine/code-knowledge/code-fact-kind.ts
  - src/wiki-engine/code-knowledge/code-incremental.ts
  - src/wiki-engine/core/graph-index.schema.ts
  - src/wiki-engine/core/wiki-protocol.ts
  - src/workflow/conformance/delivery.ts
  - src/workflow/conformance/git.ts
  - src/workflow/discovery/generated-marker.ts
  - src/workflow/discovery/render.ts
  - src/workflow/fleet/fence.ts
  - src/workflow/fleet/gate.ts
  - src/workflow/fleet/guardian-stop.ts
  - src/workflow/fleet/member.ts
  - src/workflow/fleet/owner.ts
  - src/workflow/fleet/record.ts
  - src/workflow/place/clone.ts
  - src/workflow/place/place.ts
  - src/workflow/place/reader.ts
  - src/workflow/place/record.ts
  - src/workflow/place/role-copy.ts
  - src/workflow/place/setup.ts
  - src/workflow/place/team.ts
  - src/workflow/place/worktree-snapshot.ts
  - src/workflow/runtimes/attempt.ts
  - src/workflow/runtimes/cancelled.ts
  - src/workflow/runtimes/definitions.ts
  - src/workflow/runtimes/entry-identity.ts
  - src/workflow/runtimes/held.ts
  - src/workflow/runtimes/host.ts
  - src/workflow/runtimes/layers.ts
  - src/workflow/runtimes/locate.ts
  - src/workflow/runtimes/login.ts
  - src/workflow/runtimes/protocol.ts
  - src/workflow/runtimes/sandbox-profiles.ts
  - src/workflow/runtimes/sources.ts
  - src/workflow/runtimes/tool-caller.ts
  - src/workflow/steps/git-locks.ts
  - src/workflow/steps/prompt.ts
  - src/workflow/steps/runtime-steps.ts
  - oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-between-statements.ts
  - oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-options.d.ts
  - packages/runtime-paseo/src/daemon/client.ts
  - packages/runtime-paseo/src/daemon/connect.ts
  - packages/runtime-paseo/src/daemon/host.ts
  - packages/runtime-paseo/src/daemon/sign-in.ts
  - packages/runtime-paseo/src/testing/attempt-socket.ts
  - packages/runtime-paseo/src/testing/fake-daemon.ts
  - packages/runtime-paseo/src/testing/harness.ts
  - packages/runtime-paseo/src/testing/suite.ts
  - packages/runtime-sandbox/src/providers/cli.ts
  - packages/runtime-sandbox/src/providers/container.ts
  - packages/runtime-sandbox/src/providers/native.ts
  - packages/runtime-sandbox/src/providers/seatbelt.ts
  - packages/runtime-sandbox/src/providers/vercel-copy.ts
  - packages/runtime-sandbox/src/testing/harness.ts
  - packages/runtime-sandbox/src/testing/leaks.ts
  - packages/runtime-sandbox/src/testing/native-harness.ts
  - packages/runtime-t3/src/testing/harness.ts
  - packages/tool-codebuddy/src/testing/ide-history.ts
  - packages/tool-codex/src/testing/fake-codex.ts
  - packages/tool-core/src/sessions/base.ts
  - packages/tool-core/src/sessions/ids.ts
  - packages/tool-core/src/sessions/ir.ts
  - packages/tool-core/src/sessions/platform.ts
  - packages/tool-opencode/src/testing/fake-opencode.ts
  - src/wiki-engine/code-knowledge/ast/call-resolver.ts
  - src/wiki-engine/code-knowledge/ast/import-resolver.ts
  - src/wiki-engine/code-knowledge/ast/module-scope.ts
  - src/wiki-engine/code-knowledge/ast/parser-registry.ts
  - src/wiki-engine/code-knowledge/ast/types.ts
  - src/wiki-engine/code-knowledge/ast/walk.ts
  - src/workflow/drivers/local/local-driver.ts
  - src/workflow/drivers/skill/child-brief.ts
  - src/workflow/drivers/skill/job.ts
  - src/workflow/drivers/skill/literals.ts
  - src/workflow/drivers/skill/preflight.ts
  - src/workflow/drivers/skill/session-host-profiles.ts
  - src/workflow/drivers/skill/skill-driver.ts
  - src/workflow/drivers/skill/skill-state.ts
  - src/workflow/drivers/skill/tick.ts
  - src/workflow/drivers/skill/transitions.ts
  - src/workflow/drivers/skill/turn.ts
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
- `LaunchAdapterId` ← src/launch-registry.ts:30 [EXTRACTED]
  ```
  export type LaunchAdapterId = keyof typeof LAUNCH_ADAPTERS;
  ```
- `LaunchedToolId` ← src/launch-registry.ts:33 [EXTRACTED]
  ```
  export type LaunchedToolId = { [T in ToolId]: DescriptorOf<T>['launch'] extends 'none' ? never : T }[ToolId];
  ```
- `LaunchAdapterOf` ← src/launch-registry.ts:36 [EXTRACTED]
  ```
  export type LaunchAdapterOf<T extends LaunchedToolId> = (typeof LAUNCH_ADAPTERS)[DescriptorOf<T>['launch']];
  ```
- `LaunchOrderTool` ← src/launch-registry.ts:47 [EXTRACTED]
  ```
  export type LaunchOrderTool = (typeof LAUNCH_ORDER)[number];
  ```
- `ToolWith` ← src/launch-registry.ts:81 [EXTRACTED]
  ```
  export type ToolWith<P extends Profile> = { [T in LaunchOrderTool]: LaunchAdapterOf<T> extends { readonly [K in P]: StepLaunch | ConfinedLaunch } ? T : never }[LaunchOrderTool];
  ```
- `LaunchTool` ← src/launch-registry.ts:90 [EXTRACTED]
  ```
  export type LaunchTool = ToolWith<'step'>;
  ```
- `LaunchTarget` ← src/launch-registry.ts:101 [EXTRACTED]
  ```
  export interface LaunchTarget {
  ```
- `ToolCommandEnv` ← src/launch-registry.ts:142 [EXTRACTED]
  ```
  export type ToolCommandEnv = Readonly<Record<string, string>>;
  ```
- `ToolCommandHome` ← src/launch-registry.ts:149 [EXTRACTED]
  ```
  export type ToolCommandHome =
  ```
- `DeliveredToolCommandEnv` ← src/launch-registry.ts:209 [EXTRACTED]
  ```
  export type DeliveredToolCommandEnv =
  ```
- `ConfinedTool` ← src/launch-registry.ts:253 [EXTRACTED]
  ```
  export type ConfinedTool = ToolWith<'confined'>;
  ```
- `LintUnresolvedRelation` ← src/lint-resource-graph.ts:25 [EXTRACTED]
  ```
  export interface LintUnresolvedRelation {
  ```
- `LintResourceGraph` ← src/lint-resource-graph.ts:36 [EXTRACTED]
  ```
  export interface LintResourceGraph {
  ```
- `LintScopeGraph` ← src/lint-resource-graph.ts:45 [EXTRACTED]
  ```
  export interface LintScopeGraph {
  ```
- `Install` ← src/locate.ts:35 [EXTRACTED]
  ```
  export type Install = {
  ```
- `DeliveryPlace` ← src/locate.ts:57 [EXTRACTED]
  ```
  export type DeliveryPlace = Pick<Install, 'scope' | 'toolPaths' | 'toolRoots'>;
  ```
- `Resource` ← src/locate.ts:98 [EXTRACTED]
  ```
  export type Resource = 'skills' | 'rules' | 'blocks' | 'agents' | 'mcp' | 'hooks' | 'sessions';
  ```
- `KnowledgeResource` ← src/locate.ts:110 [EXTRACTED]
  ```
  export type KnowledgeResource = (typeof KNOWLEDGE_RESOURCES)[number];
  ```
- `DirPlace` ← src/locate.ts:117 [EXTRACTED]
  ```
  export type DirPlace = { readonly kind: 'dir'; readonly path: string };
  ```
- `FilePlace` ← src/locate.ts:125 [EXTRACTED]
  ```
  export type FilePlace = { readonly kind: 'file'; readonly path: string; readonly owned: boolean; readonly header: BlocksHeader | null };
  ```
- `EntryPlace` ← src/locate.ts:131 [EXTRACTED]
  ```
  export type EntryPlace = { readonly kind: 'entry'; readonly path: string; readonly key: readonly [string, ...string[]]; readonly projectKey?: string };
  ```
- `Place` ← src/locate.ts:133 [EXTRACTED]
  ```
  export type Place = DirPlace | FilePlace | EntryPlace;
  ```
- `PlaceOf` ← src/locate.ts:136 [EXTRACTED]
  ```
  export type PlaceOf = {
  ```
- `Read` ← src/locate.ts:153 [EXTRACTED]
  ```
  export type Read = {
  ```
- `Gate` ← src/locate.ts:164 [EXTRACTED]
  ```
  export type Gate =
  ```
- `ReadGate` ← src/locate.ts:175 [EXTRACTED]
  ```
  export type ReadGate =
  ```
- `Retired` ← src/locate.ts:218 [EXTRACTED]
  ```
  export type Retired<P extends Place> = {
  ```
- `SidecarFile` ← src/locate.ts:238 [EXTRACTED]
  ```
  export type SidecarFile = { readonly kind: 'file'; readonly path: string; readonly owned: true; readonly header: null };
  ```
- `FilesChannel` ← src/locate.ts:245 [EXTRACTED]
  ```
  export type FilesChannel<P extends Place> = Common<P> & {
  ```
- `RunTimeChannel` ← src/locate.ts:253 [EXTRACTED]
  ```
  export type RunTimeChannel<P extends Place> = Common<P> & {
  ```
- `SilentChannel` ← src/locate.ts:262 [EXTRACTED]
  ```
  export type SilentChannel<P extends Place> = Common<P> & { readonly channel: 'none' | 'unknown' };
  ```
- `Located` ← src/locate.ts:264 [EXTRACTED]
  ```
  export type Located<P extends Place> = FilesChannel<P> | RunTimeChannel<P> | SilentChannel<P>;
  ```
- `McpLookup` ← src/locate.ts:307 [EXTRACTED]
  ```
  export type McpLookup = { readonly files: readonly string[]; readonly mapped: string };
  ```
- `Location` ← src/locate.ts:310 [EXTRACTED]
  ```
  export type Location<R extends Resource = Resource> = LocationOf[R];
  ```
- `Unread` ← src/locate.ts:449 [EXTRACTED]
  ```
  export type Unread =
  ```
- `Session` ← src/locate.ts:458 [EXTRACTED]
  ```
  export type Session =
  ```
- `SessionStoreRoot` ← src/locate.ts:1654 [EXTRACTED]
  ```
  export type SessionStoreRoot =
  ```
- `ManifestKind` ← src/manifest-schema.ts:52 [EXTRACTED]
  ```
  export type ManifestKind = 'projects' | 'roles' | 'members';
  ```
- `HandDeclaredResourceType` ← src/manifest-schema.ts:95 [EXTRACTED]
  ```
  export type HandDeclaredResourceType = typeof HAND_DECLARED_RESOURCE_TYPES[number];
  ```
- `NamespaceEntry` ← src/manifest-schema.ts:291 [EXTRACTED]
  ```
  export interface NamespaceEntry {
  ```
- `GitExclusion` ← src/mcp-git-exclude.ts:127 [EXTRACTED]
  ```
  export type GitExclusion =
  ```
- `McpReconcileOptions` ← src/mcp-reconcile.ts:124 [EXTRACTED]
  ```
  export interface McpReconcileOptions {
  ```
- `McpChange` ← src/mcp-reconcile.ts:141 [EXTRACTED]
  ```
  export interface McpChange {
  ```
- `McpReconcileResult` ← src/mcp-reconcile.ts:172 [EXTRACTED]
  ```
  export interface McpReconcileResult {
  ```
- `McpTarget` ← src/mcp-reconcile.ts:335 [EXTRACTED]
  ```
  export interface McpTarget {
  ```
- `McpKey` ← src/mcp-reconcile.ts:378 [EXTRACTED]
  ```
  export type McpKey = EntryPlace['key'];
  ```
- `JsonDoc` ← src/mcp-reconcile.ts:804 [EXTRACTED]
  ```
  export interface JsonDoc {
  ```
- `McpDocStorage` ← src/mcp-reconcile.ts:828 [EXTRACTED]
  ```
  export type McpDocStorage =
  ```
- `DesiredMcpEntry` ← src/mcp-reconcile.ts:1333 [EXTRACTED]
  ```
  export interface DesiredMcpEntry {
  ```
- `DesiredMcpContext` ← src/mcp-reconcile.ts:1344 [EXTRACTED]
  ```
  export interface DesiredMcpContext {
  ```
- `DesiredMcp` ← src/mcp-reconcile.ts:1386 [EXTRACTED]
  ```
  export interface DesiredMcp {
  ```
- `UnrecordedMcpOwner` ← src/mcp-reconcile.ts:1517 [EXTRACTED]
  ```
  export type UnrecordedMcpOwner = 'teamai' | 'another tool' | 'member';
  ```
- `RecordedMcpFile` ← src/mcp-reconcile.ts:2151 [EXTRACTED]
  ```
  export interface RecordedMcpFile {
  ```
- `McpOwnedFor` ← src/mcp-reconcile.ts:2377 [EXTRACTED]
  ```
  export type McpOwnedFor = (target: McpTarget, options?: { bare?: boolean }) => readonly string[];
  ```
- `McpOwner` ← src/mcp-reconcile.ts:2767 [EXTRACTED]
  ```
  export interface McpOwner {
  ```
- `McpOwners` ← src/mcp-reconcile.ts:2774 [EXTRACTED]
  ```
  export interface McpOwners {
  ```
- `ResolvedMcpFile` ← src/mcp-resolved-files.ts:24 [EXTRACTED]
  ```
  export interface ResolvedMcpFile {
  ```
- `ResolvedMcpFiles` ← src/mcp-resolved-files.ts:33 [EXTRACTED]
  ```
  export interface ResolvedMcpFiles {
  ```
- `McpFileObservation` ← src/mcp-resolved-files.ts:42 [EXTRACTED]
  ```
  export interface McpFileObservation {
  ```
- `MemberEnvironment` ← src/member-env.ts:28 [EXTRACTED]
  ```
  export type MemberEnvironment = (key: string) => string | undefined;
  ```
- `MemberSettingLevel` ← src/member-settings-report.ts:32 [EXTRACTED]
  ```
  export type MemberSettingLevel = 'environment' | 'scope' | 'machine' | 'team' | 'http-team' | 'default';
  ```
- `MemberSettingSource` ← src/member-settings-report.ts:34 [EXTRACTED]
  ```
  export interface MemberSettingSource {
  ```
- `MemberSettingsReport` ← src/member-settings-report.ts:43 [EXTRACTED]
  ```
  export interface MemberSettingsReport {
  ```
- `MemberSettingRow` ← src/member-settings-report.ts:78 [EXTRACTED]
  ```
  export interface MemberSettingRow {
  ```
- `MemberConfigMerge` ← src/members.ts:57 [EXTRACTED]
  ```
  export interface MemberConfigMerge {
  ```
- `MigrationPlan` ← src/migrate.ts:78 [EXTRACTED]
  ```
  export type MigrationPlan = {
  ```
- `MigrationResult` ← src/migrate.ts:370 [EXTRACTED]
  ```
  export type MigrationResult = 'migrated' | 'skipped' | 'busy' | 'dry-run';
  ```
- `MRSummary` ← src/mr-hint.ts:51 [EXTRACTED]
  ```
  export interface MRSummary {
  ```
- `RemoteRepo` ← src/mr-hint.ts:148 [EXTRACTED]
  ```
  export interface RemoteRepo {
  ```
- `NamespaceCandidate` ← src/namespace-resolver.ts:101 [EXTRACTED]
  ```
  export interface NamespaceCandidate<T> {
  ```
- `ResolvedNamespaceItem` ← src/namespace-resolver.ts:109 [EXTRACTED]
  ```
  export interface ResolvedNamespaceItem<T> extends NamespaceCandidate<T> {
  ```
- `NamespaceConflict` ← src/namespace-resolver.ts:114 [EXTRACTED]
  ```
  export interface NamespaceConflict<T> {
  ```
- `NamespaceResolution` ← src/namespace-resolver.ts:126 [EXTRACTED]
  ```
  export type NamespaceResolution<T> =
  ```
- `NamespaceOverride` ← src/namespace-resolver.ts:216 [EXTRACTED]
  ```
  export interface NamespaceOverride {
  ```
- `EntryType` ← src/namespaced-entries.ts:40 [EXTRACTED]
  ```
  export type EntryType = 'env' | 'hooks' | 'mcp' | 'models';
  ```
- `EntryLayout` ← src/namespaced-entries.ts:59 [EXTRACTED]
  ```
  export interface EntryLayout {
  ```
- `EntryFile` ← src/namespaced-entries.ts:102 [EXTRACTED]
  ```
  export interface EntryFile {
  ```
- `EntryFileRead` ← src/namespaced-entries.ts:141 [EXTRACTED]
  ```
  export type EntryFileRead<E> =
  ```
- `EntryScopeKeys` ← src/namespaced-entries.ts:152 [EXTRACTED]
  ```
  export interface EntryScopeKeys {
  ```
- `EntryReaderBase` ← src/namespaced-entries.ts:238 [EXTRACTED]
  ```
  export interface EntryReaderBase<E> {
  ```
- `EntryReader` ← src/namespaced-entries.ts:253 [EXTRACTED]
  ```
  export type EntryReader<E> = EntryReaderBase<E> & {
  ```
- `ResolvedEntry` ← src/namespaced-entries.ts:271 [EXTRACTED]
  ```
  export interface ResolvedEntry<E> {
  ```
- `EntryFailure` ← src/namespaced-entries.ts:285 [EXTRACTED]
  ```
  export type EntryFailure = (
  ```
- `EntryNotice` ← src/namespaced-entries.ts:303 [EXTRACTED]
  ```
  export interface EntryNotice {
  ```
- `EntryResolution` ← src/namespaced-entries.ts:308 [EXTRACTED]
  ```
  export type EntryResolution<E> =
  ```
- `OpenclawWorkspace` ← src/openclaw-home.ts:59 [EXTRACTED]
  ```
  export type OpenclawWorkspace =
  ```
- `WorkOutcome` ← src/outcomes.ts:18 [EXTRACTED]
  ```
  export type WorkOutcome = z.infer<typeof WorkOutcomeSchema>;
  ```
- `OutcomeKind` ← src/outcomes.ts:20 [EXTRACTED]
  ```
  export type OutcomeKind = WorkOutcome['kind'];
  ```
- `SessionUsage` ← src/outcomes.ts:90 [EXTRACTED]
  ```
  export type SessionUsage = z.infer<typeof SessionUsageSchema>;
  ```
- `SessionOutcomeEvent` ← src/outcomes.ts:109 [EXTRACTED]
  ```
  export type SessionOutcomeEvent = z.infer<typeof SessionOutcomeEventSchema>;
  ```
- `ProcessEntry` ← src/pid-monitor.ts:29 [EXTRACTED]
  ```
  export interface ProcessEntry {
  ```
- `PluginDescriptor` ← src/plugin-lifecycle.ts:11 [EXTRACTED]
  ```
  export interface PluginDescriptor {
  ```
- `PluginState` ← src/plugin-lifecycle.ts:24 [EXTRACTED]
  ```
  export interface PluginState {
  ```
- `ReconcileDeps` ← src/plugin-lifecycle.ts:50 [EXTRACTED]
  ```
  export interface ReconcileDeps {
  ```
- `PluginConfig` ← src/plugin-lifecycle.ts:268 [EXTRACTED]
  ```
  export interface PluginConfig {
  ```
- `ProjectResourceType` ← src/projects.ts:21 [EXTRACTED]
  ```
  export type ProjectResourceType = typeof PROJECT_RESOURCE_TYPES[number];
  ```
- `AllProjectResourceType` ← src/projects.ts:26 [EXTRACTED]
  ```
  export type AllProjectResourceType = typeof ALL_PROJECT_RESOURCE_TYPES[number];
  ```
- `TeamProject` ← src/projects.ts:77 [EXTRACTED]
  ```
  export type TeamProject = z.infer<typeof ProjectSchema>;
  ```
- `ProjectsManifest` ← src/projects.ts:79 [EXTRACTED]
  ```
  export type ProjectsManifest = z.infer<typeof ProjectsManifestSchema>;
  ```
- `NamespaceMergeMode` ← src/projects.ts:336 [EXTRACTED]
  ```
  export type NamespaceMergeMode = 'union' | 'intersect';
  ```
- `CheckoutRecord` ← src/pull.ts:1129 [EXTRACTED]
  ```
  export type CheckoutRecord = NonNullable<State['lastPullByWorkspace']>[string];
  ```
- `CheckoutBases` ← src/pull.ts:1296 [EXTRACTED]
  ```
  export type CheckoutBases =
  ```
- `DeliveryGap` ← src/pull.ts:1373 [EXTRACTED]
  ```
  export type DeliveryGap = 'no_record' | 'pending_full_sync' | 'awaiting_full_sync' | 'no_baseline'
  ```
- `TeamDelivery` ← src/pull.ts:1376 [EXTRACTED]
  ```
  export type TeamDelivery =
  ```
- `PullDelivery` ← src/pull.ts:1850 [EXTRACTED]
  ```
  export type PullDelivery = 'delivered' | 'unchanged' | 'skipped' | 'failed';
  ```
- `PullOutcome` ← src/pull.ts:1853 [EXTRACTED]
  ```
  export type PullOutcome = { completed: boolean; delivery?: PullDelivery };
  ```
- `PushFileOptions` ← src/push-file.ts:34 [EXTRACTED]
  ```
  export interface PushFileOptions {
  ```
- `PlaceableType` ← src/push-namespaces.ts:24 [EXTRACTED]
  ```
  export type PlaceableType =
  ```
- `NamespaceResolution` ← src/push-namespaces.ts:178 [EXTRACTED]
  ```
  export type NamespaceResolution =
  ```
- `Held` ← src/read-gates.ts:25 [EXTRACTED]
  ```
  export type Held = { readonly summary: string; readonly noun: string; readonly names: readonly string[] };
  ```
- `ReadGateVerdict` ← src/read-gates.ts:33 [EXTRACTED]
  ```
  export type ReadGateVerdict =
  ```
- `AdoptionResult` ← src/recall-adoption.ts:196 [EXTRACTED]
  ```
  export interface AdoptionResult {
  ```
- `RecallSessionSummary` ← src/recall-adoption.ts:608 [EXTRACTED]
  ```
  export interface RecallSessionSummary {
  ```
- `RelatedRef` ← src/recall-log.ts:34 [EXTRACTED]
  ```
  export interface RelatedRef {
  ```
- `RecalledDoc` ← src/recall-log.ts:43 [EXTRACTED]
  ```
  export interface RecalledDoc {
  ```
- `Actor` ← src/recall-log.ts:62 [EXTRACTED]
  ```
  export interface Actor {
  ```
- `RunLine` ← src/recall-log.ts:70 [EXTRACTED]
  ```
  export interface RunLine {
  ```
- `ClaimLine` ← src/recall-log.ts:94 [EXTRACTED]
  ```
  export interface ClaimLine extends Actor {
  ```
- `EvidenceLine` ← src/recall-log.ts:107 [EXTRACTED]
  ```
  export interface EvidenceLine extends Actor {
  ```
- `LinkLine` ← src/recall-log.ts:123 [EXTRACTED]
  ```
  export interface LinkLine {
  ```
- `ConsumedLine` ← src/recall-log.ts:130 [EXTRACTED]
  ```
  export interface ConsumedLine {
  ```
- `CreditLine` ← src/recall-log.ts:142 [EXTRACTED]
  ```
  export interface CreditLine {
  ```
- `CountedLine` ← src/recall-log.ts:154 [EXTRACTED]
  ```
  export interface CountedLine {
  ```
- `RecallLogLine` ← src/recall-log.ts:161 [EXTRACTED]
  ```
  export type RecallLogLine = RunLine | ClaimLine | EvidenceLine | LinkLine | ConsumedLine | CreditLine | CountedLine;
  ```
- `IndexProvenance` ← src/recall-provenance.ts:16 [EXTRACTED]
  ```
  export type IndexProvenance = z.infer<typeof IndexProvenance>;
  ```
- `RecallObservation` ← src/recall-provenance.ts:24 [EXTRACTED]
  ```
  export type RecallObservation = z.infer<typeof RecallObservation>;
  ```
- `RankableResult` ← src/recall.ts:222 [EXTRACTED]
  ```
  export interface RankableResult {
  ```
- `RelationContext` ← src/recall.ts:349 [EXTRACTED]
  ```
  export interface RelationContext {
  ```
- `DerivedEdges` ← src/recall.ts:688 [EXTRACTED]
  ```
  export interface DerivedEdges {
  ```
- `NamespaceDeclarations` ← src/resource-namespaces.ts:379 [EXTRACTED]
  ```
  export interface NamespaceDeclarations {
  ```
- `ResourceRelationType` ← src/resource-relations.ts:27 [EXTRACTED]
  ```
  export type ResourceRelationType = (typeof RESOURCE_RELATIONS)[number];
  ```
- `RelationResourceKind` ← src/resource-relations.ts:44 [EXTRACTED]
  ```
  export type RelationResourceKind = 'rule' | 'doc' | 'learning' | 'skill' | 'teamwiki';
  ```
- `RelationVia` ← src/resource-relations.ts:47 [EXTRACTED]
  ```
  export type RelationVia = 'declared' | 'link';
  ```
- `StoredRelation` ← src/resource-relations.ts:50 [EXTRACTED]
  ```
  export interface StoredRelation {
  ```
- `RelationSeverity` ← src/resource-relations.ts:56 [EXTRACTED]
  ```
  export type RelationSeverity = 'fail' | 'warn';
  ```
- `FindingLevel` ← src/review-branch.ts:82 [EXTRACTED]
  ```
  export type FindingLevel = 'fail' | 'warn' | 'info';
  ```
- `FindingCheck` ← src/review-branch.ts:85 [EXTRACTED]
  ```
  export type FindingCheck = 'structure' | 'naming' | 'duplicates' | 'format' | 'relations' | 'leaks' | 'safety' | 'workflows' | 'scorers' | 'sessions' | 'models';
  ```
- `Finding` ← src/review-branch.ts:88 [EXTRACTED]
  ```
  export interface Finding {
  ```
- `BranchReview` ← src/review-branch.ts:98 [EXTRACTED]
  ```
  export interface BranchReview {
  ```
- `ReviewBase` ← src/review-branch.ts:234 [EXTRACTED]
  ```
  export interface ReviewBase {
  ```
- `ReviewBranchOptions` ← src/review-branch.ts:1912 [EXTRACTED]
  ```
  export interface ReviewBranchOptions extends GlobalOptions {
  ```
- `ReviewCmdOptions` ← src/review-cmd.ts:29 [EXTRACTED]
  ```
  export interface ReviewCmdOptions extends GlobalOptions {
  ```
- `Risk` ← src/review-store.ts:24 [EXTRACTED]
  ```
  export type Risk = typeof RISKS[number];
  ```
- `PendingReviewPayload` ← src/review-store.ts:28 [EXTRACTED]
  ```
  export type PendingReviewPayload = z.infer<typeof PendingReviewPayloadSchema>;
  ```
- `PendingReviewItem` ← src/review-store.ts:30 [EXTRACTED]
  ```
  export interface PendingReviewItem {
  ```
- `ReviewDecision` ← src/review-store.ts:44 [EXTRACTED]
  ```
  export interface ReviewDecision {
  ```
- `RoleAssignments` ← src/role-assignments.ts:44 [EXTRACTED]
  ```
  export type RoleAssignments = z.infer<typeof RoleAssignmentsSchema>;
  ```
- `RoleSource` ← src/role-assignments.ts:47 [EXTRACTED]
  ```
  export type RoleSource = 'assigned' | 'default' | 'local' | 'none';
  ```
- `AssignedRoles` ← src/role-assignments.ts:211 [EXTRACTED]
  ```
  export interface AssignedRoles {
  ```
- `EffectiveRoles` ← src/roles-cmd.ts:163 [EXTRACTED]
  ```
  export interface EffectiveRoles {
  ```
- `RoleResourceType` ← src/roles.ts:14 [EXTRACTED]
  ```
  export type RoleResourceType = typeof ROLE_RESOURCE_TYPES[number];
  ```
- `TeamRole` ← src/roles.ts:44 [EXTRACTED]
  ```
  export type TeamRole = z.infer<typeof RoleSchema>;
  ```
- `RolesManifest` ← src/roles.ts:46 [EXTRACTED]
  ```
  export type RolesManifest = z.infer<typeof RolesManifestSchema>;
  ```
- `ResourceNamespaces` ← src/roles.ts:66 [EXTRACTED]
  ```
  export type ResourceNamespaces = Record<RoleResourceType | 'learnings', string[]>
  ```
- `RoleDeclaration` ← src/roles.ts:193 [EXTRACTED]
  ```
  export type RoleDeclaration =
  ```
- `SaveSessionOptions` ← src/save-session.ts:33 [EXTRACTED]
  ```
  export interface SaveSessionOptions extends GlobalOptions {
  ```
- `ScoreOptions` ← src/score-commands.ts:20 [EXTRACTED]
  ```
  export interface ScoreOptions {
  ```
- `DrainResult` ← src/score-drain.ts:64 [EXTRACTED]
  ```
  export interface DrainResult {
  ```
- `ScoreVerbContext` ← src/score-verbs.ts:29 [EXTRACTED]
  ```
  export interface ScoreVerbContext {
  ```
- `ScoreVerbAnswer` ← src/score-verbs.ts:39 [EXTRACTED]
  ```
  export type ScoreVerbAnswer = { ok: true; output: JsonObject } | Refused;
  ```
- `EvidenceOptions` ← src/score-verbs.ts:66 [EXTRACTED]
  ```
  export interface EvidenceOptions {
  ```
- `PlanOptions` ← src/score-verbs.ts:86 [EXTRACTED]
  ```
  export interface PlanOptions extends EvidenceOptions {
  ```
- `StageOptions` ← src/score-verbs.ts:132 [EXTRACTED]
  ```
  export interface StageOptions {
  ```
- `LabelOptions` ← src/score-verbs.ts:153 [EXTRACTED]
  ```
  export interface LabelOptions {
  ```
- `WriteOptions` ← src/score-verbs.ts:168 [EXTRACTED]
  ```
  export interface WriteOptions {
  ```
- `SubjectsOptions` ← src/score-verbs.ts:224 [EXTRACTED]
  ```
  export interface SubjectsOptions {
  ```
- `ReportOptions` ← src/score-verbs.ts:255 [EXTRACTED]
  ```
  export interface ReportOptions {
  ```
- `StoredEntryKind` ← src/secret-store.ts:29 [EXTRACTED]
  ```
  export type StoredEntryKind = z.infer<typeof StoredEntryKindSchema>;
  ```
- `StoredSecret` ← src/secret-store.ts:36 [EXTRACTED]
  ```
  export type StoredSecret = z.infer<typeof StoredSecretSchema>;
  ```
- `SecretStore` ← src/secret-store.ts:50 [EXTRACTED]
  ```
  export type SecretStore = z.infer<typeof SecretStoreSchema>;
  ```
- `SecretStoreRead` ← src/secret-store.ts:53 [EXTRACTED]
  ```
  export type SecretStoreRead =
  ```
- `SecretStoreUpdate` ← src/secret-store.ts:201 [EXTRACTED]
  ```
  export type SecretStoreUpdate =
  ```
- `ManagedSection` ← src/section-patcher.ts:6 [EXTRACTED]
  ```
  export interface ManagedSection {
  ```
- `SectionedMarkdown` ← src/section-patcher.ts:22 [EXTRACTED]
  ```
  export interface SectionedMarkdown {
  ```
- `AnchorMerge` ← src/section-patcher.ts:28 [EXTRACTED]
  ```
  export interface AnchorMerge {
  ```
- `Unusable` ← src/self-improvement.ts:65 [EXTRACTED]
  ```
  export type Unusable = 'tracked_changes' | 'not_recorded' | 'not_in_checkout';
  ```
- `Picked` ← src/self-improvement.ts:67 [EXTRACTED]
  ```
  export type Picked = {
  ```
- `Improvement` ← src/self-improvement.ts:210 [EXTRACTED]
  ```
  export type Improvement = Picked & { hasProposal: boolean };
  ```
- `RepoStat` ← src/session-analytics.ts:17 [EXTRACTED]
  ```
  export interface RepoStat {
  ```
- `TimeAnalytics` ← src/session-analytics.ts:72 [EXTRACTED]
  ```
  export interface TimeAnalytics {
  ```
- `SessionSummary` ← src/session-collector.ts:34 [EXTRACTED]
  ```
  export interface SessionSummary {
  ```
- `RenderOptions` ← src/session-collector.ts:165 [EXTRACTED]
  ```
  export interface RenderOptions {
  ```
- `FinishedSession` ← src/session-outcomes.ts:56 [EXTRACTED]
  ```
  export type FinishedSession = Pick<SessionOutcomeEvent, 'sessionId' | 'tool' | 'runMode' | 'outcomes'> & { counted: SessionUsage };
  ```
- `OutcomeFold` ← src/session-outcomes.ts:70 [EXTRACTED]
  ```
  export interface OutcomeFold {
  ```
- `FoldInput` ← src/session-outcomes.ts:76 [EXTRACTED]
  ```
  export interface FoldInput {
  ```
- `CountedSession` ← src/session-outcomes.ts:368 [EXTRACTED]
  ```
  export type CountedSession = FinishedSession & { countedAt: string };
  ```
- `OutcomeSummary` ← src/session-outcomes.ts:371 [EXTRACTED]
  ```
  export interface OutcomeSummary {
  ```
- `ReportedInterventions` ← src/session-owners.ts:22 [EXTRACTED]
  ```
  export type ReportedInterventions = Record<string, { interrupt: number; toolReject: number; correction: number }>;
  ```
- `ReportedSegments` ← src/session-owners.ts:25 [EXTRACTED]
  ```
  export type ReportedSegments = Record<string, {
  ```
- `ReportedPromptTokens` ← src/session-owners.ts:33 [EXTRACTED]
  ```
  export type ReportedPromptTokens = Record<string, { prompts: number; tokens: TokenUsage; segments?: ReportedSegments }>;
  ```
- `ReportedSnapshotName` ← src/session-owners.ts:38 [EXTRACTED]
  ```
  export type ReportedSnapshotName = typeof REPORTED_SNAPSHOTS[number];
  ```
- `ScopeSnapshots` ← src/session-owners.ts:116 [EXTRACTED]
  ```
  export interface ScopeSnapshots {
  ```
- `OwnerCredit` ← src/session-owners.ts:188 [EXTRACTED]
  ```
  export interface OwnerCredit {
  ```
- `SessionOwnerState` ← src/session-owners.ts:377 [EXTRACTED]
  ```
  export interface SessionOwnerState {
  ```
- `DailySessionSnapshot` ← src/session-trends.ts:11 [EXTRACTED]
  ```
  export interface DailySessionSnapshot {
  ```
- `ReportedDailySessions` ← src/session-trends.ts:30 [EXTRACTED]
  ```
  export type ReportedDailySessions = Record<string, DailySessionSnapshot>;
  ```
- `DailySessionSplit` ← src/session-trends.ts:236 [EXTRACTED]
  ```
  export interface DailySessionSplit {
  ```
- `DailyStatsDelta` ← src/session-trends.ts:300 [EXTRACTED]
  ```
  export interface DailyStatsDelta {
  ```
- `TrendPeriod` ← src/session-trends.ts:382 [EXTRACTED]
  ```
  export interface TrendPeriod {
  ```
- `TrendWindow` ← src/session-trends.ts:393 [EXTRACTED]
  ```
  export interface TrendWindow {
  ```
- `SessionCostPeriod` ← src/session-trends.ts:443 [EXTRACTED]
  ```
  export interface SessionCostPeriod {
  ```
- `SessionCostWindow` ← src/session-trends.ts:449 [EXTRACTED]
  ```
  export interface SessionCostWindow {
  ```
- `SharedInstructionSourceDir` ← src/shared-instruction-source.ts:19 [EXTRACTED]
  ```
  export type SharedInstructionSourceDir = typeof SHARED_INSTRUCTION_SOURCE_DIRS[number];
  ```
- `SkillCommandType` ← src/skill-command.ts:23 [EXTRACTED]
  ```
  export type SkillCommandType = 'install_skill' | 'uninstall_skill' | 'update_skill';
  ```
- `SkillCommand` ← src/skill-command.ts:26 [EXTRACTED]
  ```
  export interface SkillCommand {
  ```
- `SkillBlock` ← src/skill-content.ts:72 [EXTRACTED]
  ```
  export type SkillBlock =
  ```
- `SkillBlockReason` ← src/skill-content.ts:77 [EXTRACTED]
  ```
  export type SkillBlockReason = SkillBlock['reason'];
  ```
- `ShareGate` ← src/skill-content.ts:84 [EXTRACTED]
  ```
  export type ShareGate =
  ```
- `TeamDetection` ← src/skill-content.ts:96 [EXTRACTED]
  ```
  export type TeamDetection =
  ```
- `PackagedSkill` ← src/skill-content.ts:231 [EXTRACTED]
  ```
  export interface PackagedSkill {
  ```
- `PackagedSkillRoots` ← src/skill-content.ts:240 [EXTRACTED]
  ```
  export interface PackagedSkillRoots {
  ```
- `ServableSkillResolution` ← src/skill-content.ts:317 [EXTRACTED]
  ```
  export type ServableSkillResolution =
  ```
- `BlockedSkill` ← src/skill-content.ts:323 [EXTRACTED]
  ```
  export type BlockedSkill = { kind: 'blocked'; name: string } & SkillBlock;
  ```
- `SkillBlockMessage` ← src/skill-content.ts:366 [EXTRACTED]
  ```
  export interface SkillBlockMessage {
  ```
- `SkillGetOptions` ← src/skill-content.ts:490 [EXTRACTED]
  ```
  export interface SkillGetOptions {
  ```
- `SkillCatalogEntry` ← src/skill-content.ts:630 [EXTRACTED]
  ```
  export type SkillCatalogEntry =
  ```
- `SkillDirectoryBlock` ← src/skill-directory.ts:7 [EXTRACTED]
  ```
  export type SkillDirectoryBlock =
  ```
- `OwnedSkillFiles` ← src/skill-owned-files.ts:28 [EXTRACTED]
  ```
  export type OwnedSkillFiles = ReadonlyMap<string, ReadonlySet<string>>;
  ```
- `PruneResult` ← src/skill-owned-files.ts:150 [EXTRACTED]
  ```
  export interface PruneResult {
  ```
- `SkillCandidate` ← src/skill-use.ts:56 [EXTRACTED]
  ```
  export type SkillCandidate = { readonly skill: string; readonly file?: string };
  ```
- `DeliveredSkillInfo` ← src/skill-use.ts:348 [EXTRACTED]
  ```
  export type DeliveredSkillInfo = z.infer<typeof DeliveredSkillInfoSchema>;
  ```
- `InstallationRecord` ← src/source.ts:129 [EXTRACTED]
  ```
  export interface InstallationRecord { path: string; teamCheckout: string | null }
  ```
- `ShowStatsOptions` ← src/stats.ts:240 [EXTRACTED]
  ```
  export interface ShowStatsOptions {
  ```
- `ListOptions` ← src/status.ts:44 [EXTRACTED]
  ```
  export interface ListOptions extends GlobalOptions {
  ```
- `DroppedRollout` ← src/team-push.ts:469 [EXTRACTED]
  ```
  export interface DroppedRollout {
  ```
- `TakeReported` ← src/team-push.ts:955 [EXTRACTED]
  ```
  export type TakeReported<T> = (run: T, left: T, runId: string) => { taken: T; left: T } | undefined;
  ```
- `UsageReportOutcome` ← src/team-push.ts:1075 [EXTRACTED]
  ```
  export type UsageReportOutcome = 'reported' | 'nothing' | 'unreported';
  ```
- `ResolvedTeamRef` ← src/team-ref.ts:7 [EXTRACTED]
  ```
  export type ResolvedTeamRef = { ref: string; kind: 'branch' | 'tag' | 'commit'; commit: string };
  ```
- `TeamRefBlock` ← src/team-ref.ts:17 [EXTRACTED]
  ```
  export type TeamRefBlock = 'no_workspace' | 'user_scope' | 'self' | 'http';
  ```
- `TeamRepoTransition` ← src/team-ref.ts:89 [EXTRACTED]
  ```
  export type TeamRepoTransition = { label: string } & (
  ```
- `RemovedTeamResources` ← src/team-ref.ts:193 [EXTRACTED]
  ```
  export type RemovedTeamResources = Record<'skills' | 'rules' | 'agents', Set<string>>;
  ```
- `TeamScriptEvent` ← src/team-scripts.ts:40 [EXTRACTED]
  ```
  export type TeamScriptEvent = (typeof TEAM_SCRIPT_EVENTS)[number];
  ```
- `TeamScriptResult` ← src/team-scripts.ts:53 [EXTRACTED]
  ```
  export interface TeamScriptResult {
  ```
- `TeamScriptOptions` ← src/team-scripts.ts:60 [EXTRACTED]
  ```
  export interface TeamScriptOptions {
  ```
- `TeamaiOnlyState` ← src/teamai-only-files.ts:35 [EXTRACTED]
  ```
  export type TeamaiOnlyState = 'teamai-only' | 'mixed' | 'tracked' | 'unknown';
  ```
- `SharedFileJudgement` ← src/teamai-only-files.ts:37 [EXTRACTED]
  ```
  export interface SharedFileJudgement {
  ```
- `ToolHomeChange` ← src/tool-home-record.ts:9 [EXTRACTED]
  ```
  export type ToolHomeChange = { readonly tool: string; readonly variable: string; readonly dir: string | null; readonly previous?: string };
  ```
- `Host` ← src/tool-home.ts:14 [EXTRACTED]
  ```
  export type Host = {
  ```
- `EnvToolHome` ← src/tool-home.ts:112 [EXTRACTED]
  ```
  export type EnvToolHome = { readonly dir: string; readonly variable: string; readonly kind: 'own' | 'xdg' | 'platform-default' };
  ```
- `OmpProfile` ← src/tool-home.ts:205 [EXTRACTED]
  ```
  export interface OmpProfile {
  ```
- `ToolHomesHistory` ← src/tool-home.ts:477 [EXTRACTED]
  ```
  export type ToolHomesHistory = Readonly<Record<string, readonly string[]>>;
  ```
- `ToolHomesRead` ← src/tool-home.ts:524 [EXTRACTED]
  ```
  export type ToolHomesRead =
  ```
- `InstanceSource` ← src/tool-instances.ts:31 [EXTRACTED]
  ```
  export type InstanceSource = 'team' | 'personal';
  ```
- `ResolvedToolInstance` ← src/tool-instances.ts:52 [EXTRACTED]
  ```
  export interface ResolvedToolInstance extends DeclaredToolFile, ToolInstance<ToolId> {
  ```
- `ResolvedToolAdjustment` ← src/tool-instances.ts:57 [EXTRACTED]
  ```
  export interface ResolvedToolAdjustment extends DeclaredToolFile {
  ```
- `DeclaredTool` ← src/tool-instances.ts:64 [EXTRACTED]
  ```
  export type DeclaredTool = ResolvedToolInstance | ResolvedToolAdjustment;
  ```
- `RefusedInstance` ← src/tool-instances.ts:88 [EXTRACTED]
  ```
  export interface RefusedInstance {
  ```
- `TeamToolTree` ← src/tool-instances.ts:299 [EXTRACTED]
  ```
  export interface TeamToolTree extends TeamTree {
  ```
- `TeamCommand` ← src/tool-instances.ts:669 [EXTRACTED]
  ```
  export type TeamCommand =
  ```
- `UnacceptedTeamCommand` ← src/tool-instances.ts:674 [EXTRACTED]
  ```
  export interface UnacceptedTeamCommand {
  ```
- `UnacceptedCommand` ← src/tool-instances.ts:781 [EXTRACTED]
  ```
  export interface UnacceptedCommand {
  ```
- `InstancePurpose` ← src/tool-registry.ts:51 [EXTRACTED]
  ```
  export type InstancePurpose = 'use' | 'guard';
  ```
- `DescriptorOf` ← src/tool-registry.ts:115 [EXTRACTED]
  ```
  export type DescriptorOf<T extends ToolId> = (typeof TOOLS)[T];
  ```
- `DeliveredModelTool` ← src/tool-registry.ts:336 [EXTRACTED]
  ```
  export type DeliveredModelTool = { [T in ToolId]: DescriptorOf<T> extends { readonly receivesDeliveredModels: true } ? T : never }[ToolId];
  ```
- `InstanceBase` ← src/tool-registry.ts:345 [EXTRACTED]
  ```
  export type InstanceBase = { [T in ToolId]: DescriptorOf<T> extends { readonly instances: true } ? T : never }[ToolId];
  ```
- `ShippedDescriptor` ← src/tools.ts:11 [EXTRACTED]
  ```
  export type ShippedDescriptor = ToolDescriptor<ShippedIds>;
  ```
- `ToolId` ← src/tools.ts:46 [EXTRACTED]
  ```
  export type ToolId = (typeof TOOL_IDS)[number];
  ```
- `InlineRulesWithoutBlocksFile` ← src/tools.ts:98 [EXTRACTED]
  ```
  export type InlineRulesWithoutBlocksFile = {
  ```
- `ToolsWithTwoMcpFormats` ← src/tools.ts:104 [EXTRACTED]
  ```
  export type ToolsWithTwoMcpFormats = {
  ```
- `AgentToolId` ← src/tools.ts:111 [EXTRACTED]
  ```
  export type AgentToolId = {
  ```
- `Scope` ← src/types.ts:86 [EXTRACTED]
  ```
  export type Scope = z.infer<typeof ScopeEnum>;
  ```
- `SourceConfig` ← src/types.ts:435 [EXTRACTED]
  ```
  export type SourceConfig = z.infer<typeof SourceConfigSchema>;
  ```
- `SourceInstallManifest` ← src/types.ts:438 [EXTRACTED]
  ```
  export interface SourceInstallManifest {
  ```
- `ProviderName` ← src/types.ts:465 [EXTRACTED]
  ```
  export type ProviderName = z.infer<typeof ProviderNameSchema>;
  ```
- `TeamaiConfig` ← src/types.ts:868 [EXTRACTED]
  ```
  export type TeamaiConfig = z.infer<typeof TeamaiConfigSchema>;
  ```
- `MemberConfig` ← src/types.ts:887 [EXTRACTED]
  ```
  export type MemberConfig = z.infer<typeof MemberConfigSchema>;
  ```
- `DriverTuning` ← src/types.ts:902 [EXTRACTED]
  ```
  export type DriverTuning = z.infer<typeof DriverTuningSchema>;
  ```
- `MemberWorkflowSettings` ← src/types.ts:933 [EXTRACTED]
  ```
  export type MemberWorkflowSettings = z.infer<typeof MemberWorkflowSettingsSchema>;
  ```
- `MemberSettings` ← src/types.ts:1013 [EXTRACTED]
  ```
  export type MemberSettings = z.infer<typeof MemberSettingsSchema>;
  ```
- `MemberSettingsOverlay` ← src/types.ts:1019 [EXTRACTED]
  ```
  export interface MemberSettingsOverlay {
  ```
- `LocalConfig` ← src/types.ts:1140 [EXTRACTED]
  ```
  export type LocalConfig = z.infer<typeof LocalConfigSchema> & {
  ```
- `RoleAssignment` ← src/types.ts:1176 [EXTRACTED]
  ```
  export interface RoleAssignment {
  ```
- `LocalConfigInput` ← src/types.ts:1183 [EXTRACTED]
  ```
  export type LocalConfigInput = z.input<typeof LocalConfigSchema>;
  ```
- `PendingPushItem` ← src/types.ts:1244 [EXTRACTED]
  ```
  export type PendingPushItem = z.infer<typeof PendingPushItemSchema>;
  ```
- `PendingPush` ← src/types.ts:1246 [EXTRACTED]
  ```
  export type PendingPush = z.infer<typeof PendingPushSchema>;
  ```
- `RecordedAgentModel` ← src/types.ts:1265 [EXTRACTED]
  ```
  export type RecordedAgentModel = z.infer<typeof RecordedAgentModelSchema>;
  ```
- `AgentModelRecords` ← src/types.ts:1268 [EXTRACTED]
  ```
  export type AgentModelRecords = Record<string, Record<string, RecordedAgentModel>>;
  ```
- `CodexBuild` ← src/types.ts:1273 [EXTRACTED]
  ```
  export type CodexBuild = z.infer<typeof CodexBuildSchema>;
  ```
- `CodexBuildSkew` ← src/types.ts:1281 [EXTRACTED]
  ```
  export type CodexBuildSkew = z.infer<typeof CodexBuildSkewSchema>;
  ```
- `PlacementRecord` ← src/types.ts:1286 [EXTRACTED]
  ```
  export type PlacementRecord = z.infer<typeof PlacementRecordSchema>;
  ```
- `DeliverySelection` ← src/types.ts:1306 [EXTRACTED]
  ```
  export type DeliverySelection = z.infer<typeof DeliverySelectionSchema>;
  ```
- `State` ← src/types.ts:1511 [EXTRACTED]
  ```
  export type State = z.infer<typeof StateSchema>;
  ```
- `TagsConfig` ← src/types.ts:1526 [EXTRACTED]
  ```
  export interface TagsConfig {
  ```
- `ResourceType` ← src/types.ts:1533 [EXTRACTED]
  ```
  export type ResourceType =
  ```
- `ResourceItemStatus` ← src/types.ts:1550 [EXTRACTED]
  ```
  export type ResourceItemStatus = 'new' | 'modified';
  ```
- `ResourceItem` ← src/types.ts:1552 [EXTRACTED]
  ```
  export interface ResourceItem {
  ```
- `ResourceDiff` ← src/types.ts:1573 [EXTRACTED]
  ```
  export interface ResourceDiff {
  ```
- `DeliveryTarget` ← src/types.ts:1580 [EXTRACTED]
  ```
  export interface DeliveryTarget {
  ```
- `CopyOrigin` ← src/types.ts:1625 [EXTRACTED]
  ```
  export interface CopyOrigin {
  ```
- `HookDef` ← src/types.ts:1657 [EXTRACTED]
  ```
  export interface HookDef {
  ```
- `TeamHookFolder` ← src/types.ts:1688 [EXTRACTED]
  ```
  export interface TeamHookFolder {
  ```
- `HookPayload` ← src/types.ts:1722 [EXTRACTED]
  ```
  export type HookPayload = z.infer<typeof HookPayloadSchema>;
  ```
- `McpTransport` ← src/types.ts:1735 [EXTRACTED]
  ```
  export type McpTransport = 'stdio' | 'http' | 'sse';
  ```
- `McpServerDef` ← src/types.ts:1737 [EXTRACTED]
  ```
  export interface McpServerDef {
  ```
- `ManagedMcpRecord` ← src/types.ts:1760 [EXTRACTED]
  ```
  export interface ManagedMcpRecord {
  ```
- `ManagedMcpManifest` ← src/types.ts:1793 [EXTRACTED]
  ```
  export type ManagedMcpManifest = Record<string, ManagedMcpRecord[]>;
  ```
- `GlobalOptions` ← src/types.ts:1870 [EXTRACTED]
  ```
  export interface GlobalOptions {
  ```
- `UsageEvent` ← src/types.ts:2106 [EXTRACTED]
  ```
  export interface UsageEvent {
  ```
- `UserStats` ← src/types.ts:2120 [EXTRACTED]
  ```
  export interface UserStats {
  ```
- `OutcomeCounts` ← src/types.ts:2197 [EXTRACTED]
  ```
  export type OutcomeCounts = SessionUsage & { sessions: number };
  ```
- `UserOutcomeStats` ← src/types.ts:2200 [EXTRACTED]
  ```
  export type UserOutcomeStats = Partial<Record<RunMode | 'notRecorded', Partial<Record<OutcomeKind | 'none', OutcomeCounts>>>>;
  ```
- `UserModeStats` ← src/types.ts:2203 [EXTRACTED]
  ```
  export type UserModeStats = Pick<UserStats, 'interventions' | 'prompts' | 'tokens' | 'daily'>;
  ```
- `RunModeSplit` ← src/types.ts:2206 [EXTRACTED]
  ```
  export type RunModeSplit = Record<RunMode | 'notRecorded', number>;
  ```
- `DailyUserStats` ← src/types.ts:2209 [EXTRACTED]
  ```
  export interface DailyUserStats {
  ```
- `UserInterventionStats` ← src/types.ts:2225 [EXTRACTED]
  ```
  export interface UserInterventionStats {
  ```
- `SessionMetrics` ← src/types.ts:2259 [EXTRACTED]
  ```
  export interface SessionMetrics {
  ```
- `DashboardSessionStatus` ← src/types.ts:2282 [EXTRACTED]
  ```
  export type DashboardSessionStatus = 'running' | 'waiting_for_input' | 'error' | 'idle' | 'stopped';
  ```
- `DashboardEventType` ← src/types.ts:2284 [EXTRACTED]
  ```
  export type DashboardEventType = 'session_start' | 'session_end' | 'tool_use' | 'prompt_submit' | 'stop' | 'process_exit';
  ```
- `DashboardEvent` ← src/types.ts:2286 [EXTRACTED]
  ```
  export interface DashboardEvent {
  ```
- `RequestCostMetrics` ← src/types.ts:2407 [EXTRACTED]
  ```
  export interface RequestCostMetrics {
  ```
- `DashboardSession` ← src/types.ts:2415 [EXTRACTED]
  ```
  export interface DashboardSession {
  ```
- `SessionFriction` ← src/types.ts:2582 [EXTRACTED]
  ```
  export interface SessionFriction {
  ```
- `ContributeState` ← src/types.ts:2590 [EXTRACTED]
  ```
  export interface ContributeState {
  ```
- `SessionShareOffered` ← src/types.ts:2633 [EXTRACTED]
  ```
  export type SessionShareOffered = z.infer<typeof SessionShareOfferedSchema>;
  ```
- `LearningDocMeta` ← src/types.ts:2671 [EXTRACTED]
  ```
  export interface LearningDocMeta {
  ```
- `KnowledgeType` ← src/types.ts:2679 [EXTRACTED]
  ```
  export type KnowledgeType = 'learnings' | 'docs' | 'rules' | 'skills';
  ```
- `KnowledgeDomain` ← src/types.ts:2690 [EXTRACTED]
  ```
  export type KnowledgeDomain = 'technical' | 'ops' | 'support' | 'neutral';
  ```
- `SearchIndexEntry` ← src/types.ts:2693 [EXTRACTED]
  ```
  export interface SearchIndexEntry {
  ```
- `SearchIndexFileCache` ← src/types.ts:2735 [EXTRACTED]
  ```
  export interface SearchIndexFileCache {
  ```
- `SearchIndex` ← src/types.ts:2747 [EXTRACTED]
  ```
  export interface SearchIndex {
  ```
- `UserVotes` ← src/types.ts:2778 [EXTRACTED]
  ```
  export type UserVotes = z.infer<typeof UserVotesSchema>;
  ```
- `VoteEntryV2` ← src/types.ts:2798 [EXTRACTED]
  ```
  export type VoteEntryV2 = z.infer<typeof VoteEntryV2Schema>;
  ```
- `VoteDelta` ← src/types.ts:2812 [EXTRACTED]
  ```
  export type VoteDelta = z.infer<typeof VoteDeltaSchema>;
  ```
- `UpvoteLedger` ← src/types.ts:2861 [EXTRACTED]
  ```
  export type UpvoteLedger = z.infer<typeof UpvoteLedgerSchema>;
  ```
- `PendingVoteSync` ← src/types.ts:2871 [EXTRACTED]
  ```
  export type PendingVoteSync = z.infer<typeof PendingVoteSyncSchema>;
  ```
- `UserVotesV2` ← src/types.ts:2892 [EXTRACTED]
  ```
  export type UserVotesV2 = z.infer<typeof UserVotesV2Schema>;
  ```
- `CultureFrontmatter` ← src/types.ts:2952 [EXTRACTED]
  ```
  export type CultureFrontmatter = z.infer<typeof CultureFrontmatterSchema>;
  ```
- `RelocatableTool` ← src/types.ts:3053 [EXTRACTED]
  ```
  export interface RelocatableTool {
  ```
- `HomePaths` ← src/types.ts:3071 [EXTRACTED]
  ```
  export type HomePaths = {
  ```
- `RelocatableToolTable` ← src/types.ts:3175 [EXTRACTED]
  ```
  export interface RelocatableToolTable {
  ```
- `ToolRootRejection` ← src/types.ts:3191 [EXTRACTED]
  ```
  export type ToolRootRejection =
  ```
- `DataBranch` ← src/types.ts:3801 [EXTRACTED]
  ```
  export type DataBranch = typeof DATA_BRANCHES[number];
  ```
- `HookScopeResolution` ← src/types.ts:4091 [EXTRACTED]
  ```
  export interface HookScopeResolution {
  ```
- `MRData` ← src/types.ts:4231 [EXTRACTED]
  ```
  export interface MRData {
  ```
- `MRThreadNote` ← src/types.ts:4255 [EXTRACTED]
  ```
  export interface MRThreadNote {
  ```
- `MRThread` ← src/types.ts:4262 [EXTRACTED]
  ```
  export interface MRThread {
  ```
- `MRFetchOptions` ← src/types.ts:4273 [EXTRACTED]
  ```
  export interface MRFetchOptions {
  ```
- `LearningDraft` ← src/types.ts:4281 [EXTRACTED]
  ```
  export interface LearningDraft {
  ```
- `CodebaseSuggestion` ← src/types.ts:4291 [EXTRACTED]
  ```
  export interface CodebaseSuggestion {
  ```
- `WebhookEndpoint` ← src/types.ts:4316 [EXTRACTED]
  ```
  export type WebhookEndpoint = z.infer<typeof WebhookEndpointSchema>;
  ```
- `WebhookConfig` ← src/types.ts:4318 [EXTRACTED]
  ```
  export type WebhookConfig = z.infer<typeof WebhookConfigSchema>;
  ```
- `WebhookPayload` ← src/types.ts:4320 [EXTRACTED]
  ```
  export interface WebhookPayload {
  ```
- `UpdatePolicy` ← src/update-policy.ts:3 [EXTRACTED]
  ```
  export type UpdatePolicy = 'auto' | 'prompt' | 'skip';
  ```
- `NpmCommand` ← src/update.ts:111 [EXTRACTED]
  ```
  export interface NpmCommand {
  ```
- `LockHolder` ← src/update.ts:424 [EXTRACTED]
  ```
  export type LockHolder = z.infer<typeof LockPayloadSchema>;
  ```
- `CheckResult` ← src/update.ts:1019 [EXTRACTED]
  ```
  export interface CheckResult {
  ```
- `UpdateOutcome` ← src/update.ts:1108 [EXTRACTED]
  ```
  export type UpdateOutcome = 'ok' | 'skipped' | 'failed' | 'unreachable';
  ```
- `UpdateOptions` ← src/update.ts:1530 [EXTRACTED]
  ```
  export interface UpdateOptions {
  ```
- `SkillRootsInput` ← src/usage-tracker.ts:126 [EXTRACTED]
  ```
  export type SkillRootsInput = {
  ```
- `VizOptions` ← src/viz.ts:38 [EXTRACTED]
  ```
  export interface VizOptions {
  ```
- `EntryMetric` ← src/viz.ts:46 [EXTRACTED]
  ```
  export interface EntryMetric {
  ```
- `CoverageStat` ← src/viz.ts:59 [EXTRACTED]
  ```
  export interface CoverageStat {
  ```
- `TrendPoint` ← src/viz.ts:69 [EXTRACTED]
  ```
  export interface TrendPoint {
  ```
- `AuthorStat` ← src/viz.ts:76 [EXTRACTED]
  ```
  export interface AuthorStat {
  ```
- `MaintenanceCandidates` ← src/viz.ts:83 [EXTRACTED]
  ```
  export interface MaintenanceCandidates {
  ```
- `VizSource` ← src/viz.ts:90 [EXTRACTED]
  ```
  export interface VizSource {
  ```
- `RelationStats` ← src/viz.ts:101 [EXTRACTED]
  ```
  export interface RelationStats {
  ```
- `VizData` ← src/viz.ts:118 [EXTRACTED]
  ```
  export interface VizData {
  ```
- `VizSummary` ← src/viz.ts:652 [EXTRACTED]
  ```
  export interface VizSummary {
  ```
- `LockedResult` ← src/votes.ts:40 [EXTRACTED]
  ```
  export interface LockedResult<T> {
  ```
- `AdoptionVerdict` ← src/votes.ts:423 [EXTRACTED]
  ```
  export interface AdoptionVerdict {
  ```
- `RecallAdoptionCredit` ← src/votes.ts:429 [EXTRACTED]
  ```
  export type RecallAdoptionCredit = Pick<CreditLine, 'session' | 'doc' | 'source' | 'adopted'>;
  ```
- `StagedVotes` ← src/votes.ts:632 [EXTRACTED]
  ```
  export interface StagedVotes {
  ```
- `FeishuMessage` ← src/webhook-formatters.ts:5 [EXTRACTED]
  ```
  export interface FeishuMessage {
  ```
- `WecomMessage` ← src/webhook-formatters.ts:11 [EXTRACTED]
  ```
  export interface WecomMessage {
  ```
- `GenericWebhookMessage` ← src/webhook-formatters.ts:17 [EXTRACTED]
  ```
  export type GenericWebhookMessage = Pick<WebhookPayload, 'event' | 'timestamp' | 'tool' | 'sessionId' | 'cwd' | 'team' | 'username' | 'data'>;
  ```
- `WebhookMessage` ← src/webhook-formatters.ts:20 [EXTRACTED]
  ```
  export type WebhookMessage = FeishuMessage | WecomMessage | GenericWebhookMessage;
  ```
- `StartOptions` ← src/workflow-commands.ts:499 [EXTRACTED]
  ```
  export type StartOptions = {
  ```
- `ShortcutStart` ← src/workflow-commands.ts:513 [EXTRACTED]
  ```
  export interface ShortcutStart {
  ```
- `ShortcutRun` ← src/workflow-commands.ts:772 [EXTRACTED]
  ```
  export interface ShortcutRun {
  ```
- `ShortcutEnd` ← src/workflow-commands.ts:806 [EXTRACTED]
  ```
  export type ShortcutEnd = z.infer<typeof ShortcutDoneSchema>;
  ```
- `DriveOn` ← src/workflow-drive.ts:13 [EXTRACTED]
  ```
  export type DriveOn = { kind: 'named'; name: DriverName } | { kind: 'opened'; opened: OpenedDriver };
  ```
- `Proposal` ← src/workflow-offers.ts:16 [EXTRACTED]
  ```
  export type Proposal = { value?: unknown; why: string };
  ```
- `Taker` ← src/workflow-published-runs.ts:35 [EXTRACTED]
  ```
  export type Taker = { caller: InvokeCaller; hasPerson: boolean } & ({ driver: 'local'; tools: Record<string, string>; sandbox: boolean; autoApprove?: boolean } | { driver: 'skill' });
  ```
- `Lack` ← src/workflow-published-runs.ts:38 [EXTRACTED]
  ```
  export interface Lack {
  ```
- `Offer` ← src/workflow-published-runs.ts:44 [EXTRACTED]
  ```
  export interface Offer {
  ```
- `PublishedRun` ← src/workflow-published-runs.ts:65 [EXTRACTED]
  ```
  export interface PublishedRun {
  ```
- `ResumableRun` ← src/workflow-published-runs.ts:81 [EXTRACTED]
  ```
  export type ResumableRun =
  ```
- `LocalStanding` ← src/workflow-published-runs.ts:91 [EXTRACTED]
  ```
  export type LocalStanding =
  ```
- `ChildSelection` ← src/workspace-children.ts:41 [EXTRACTED]
  ```
  export type ChildSelection = Pick<LocalConfig, 'primaryRole' | 'additionalRoles' | 'projects' | 'subscribedTags' | 'excludedSkills'>;
  ```
- `WorkspaceChild` ← src/workspace-children.ts:43 [EXTRACTED]
  ```
  export interface WorkspaceChild {
  ```
- `LeftOutChild` ← src/workspace-children.ts:54 [EXTRACTED]
  ```
  export interface LeftOutChild {
  ```
- `WorkspaceChildren` ← src/workspace-children.ts:60 [EXTRACTED]
  ```
  export interface WorkspaceChildren {
  ```
- `HeldBackItem` ← src/workspace-children.ts:265 [EXTRACTED]
  ```
  export interface HeldBackItem<TItem> {
  ```
- `OwnedInstructionExcludes` ← src/workspace-children.ts:360 [EXTRACTED]
  ```
  export type OwnedInstructionExcludes = Readonly<Record<string, readonly string[]>>;
  ```
- `InstallInstance` ← scripts/verify/instances.ts:60 [EXTRACTED]
  ```
  export interface InstallInstance {
  ```
- `LedgerRules` ← scripts/verify/ledger.ts:450 [EXTRACTED]
  ```
  export interface LedgerRules {
  ```
- `Attribution` ← scripts/verify/leftovers.ts:19 [EXTRACTED]
  ```
  export type Attribution =
  ```
- `Ties` ← scripts/verify/leftovers.ts:26 [EXTRACTED]
  ```
  export interface Ties {
  ```
- `WorldTies` ← scripts/verify/leftovers.ts:35 [EXTRACTED]
  ```
  export interface WorldTies {
  ```
- `Tier` ← scripts/verify/leftovers.ts:69 [EXTRACTED]
  ```
  export type Tier = 'basic' | 'middle' | 'driver';
  ```
- `TierEvidence` ← scripts/verify/leftovers.ts:71 [EXTRACTED]
  ```
  export interface TierEvidence {
  ```
- `Finding` ← scripts/verify/leftovers.ts:89 [EXTRACTED]
  ```
  export interface Finding {
  ```
- `Observed` ← scripts/verify/leftovers.ts:101 [EXTRACTED]
  ```
  export type Observed =
  ```
- `LeftoverContext` ← scripts/verify/leftovers.ts:106 [EXTRACTED]
  ```
  export interface LeftoverContext {
  ```
- `CleanupRule` ← scripts/verify/leftovers.ts:117 [EXTRACTED]
  ```
  export type CleanupRule = { kind: 'remove' } | { kind: 'keep' } | { kind: 'refuse'; found: string; unseen: string };
  ```
- `LeftoverKind` ← scripts/verify/leftovers.ts:120 [EXTRACTED]
  ```
  export interface LeftoverKind {
  ```
- `RecordScan` ← scripts/verify/leftovers.ts:154 [EXTRACTED]
  ```
  export interface RecordScan {
  ```
- `CleanupPlan` ← scripts/verify/leftovers.ts:365 [EXTRACTED]
  ```
  export type CleanupPlan =
  ```
- `EnvVerdict` ← scripts/verify/secrets.ts:94 [EXTRACTED]
  ```
  export type EnvVerdict = { kind: 'ok' } | { kind: 'leak'; names: string[] };
  ```
- `ShippedHome` ← scripts/verify/shipped-homes.ts:17 [EXTRACTED]
  ```
  export interface ShippedHome {
  ```
- `Target` ← scripts/verify/target.ts:16 [EXTRACTED]
  ```
  export type Target = { kind: 'world' } | { kind: 'member'; name: string };
  ```
- `Member` ← scripts/verify/world.ts:42 [EXTRACTED]
  ```
  export type Member = z.infer<typeof MemberSchema>;
  ```
- `World` ← scripts/verify/world.ts:75 [EXTRACTED]
  ```
  export type World = z.infer<typeof WorldSchema>;
  ```
- `Probed` ← scripts/verify/world.ts:265 [EXTRACTED]
  ```
  export interface Probed {
  ```
- `Writers` ← scripts/verify/world.ts:692 [EXTRACTED]
  ```
  export type Writers = z.infer<typeof WritersSchema>;
  ```
- `Comparison` ← src/benchmark/agent-match.ts:14 [EXTRACTED]
  ```
  export type Comparison = (typeof COMPARISONS)[number];
  ```
- `PinnedArmWorkflow` ← src/benchmark/arm-workflow.ts:21 [EXTRACTED]
  ```
  export interface PinnedArmWorkflow {
  ```
- `CalibrationSubject` ← src/benchmark/calibration.ts:33 [EXTRACTED]
  ```
  export interface CalibrationSubject {
  ```
- `JudgeCalls` ← src/benchmark/estimate.ts:18 [EXTRACTED]
  ```
  export interface JudgeCalls {
  ```
- `BenchmarkRunInput` ← src/benchmark/history.ts:25 [EXTRACTED]
  ```
  export interface BenchmarkRunInput {
  ```
- `ArmPairs` ← src/benchmark/history.ts:37 [EXTRACTED]
  ```
  export interface ArmPairs {
  ```
- `Regression` ← src/benchmark/history.ts:48 [EXTRACTED]
  ```
  export type Regression =
  ```
- `BenchmarkHistoryQuery` ← src/benchmark/history.ts:56 [EXTRACTED]
  ```
  export interface BenchmarkHistoryQuery {
  ```
- `RunPoint` ← src/benchmark/history.ts:63 [EXTRACTED]
  ```
  export type RunPoint = PassRate & { run: string; startedAt: string };
  ```
- `SuiteSummary` ← src/benchmark/history.ts:65 [EXTRACTED]
  ```
  export interface SuiteSummary {
  ```
- `PooledRate` ← src/benchmark/history.ts:79 [EXTRACTED]
  ```
  export type PooledRate = PassRate & { low: number; high: number; runs: number };
  ```
- `PooledArm` ← src/benchmark/history.ts:85 [EXTRACTED]
  ```
  export type PooledArm = PooledRate & Pick<ArmResults, 'deviations' | 'notVerified' | 'correctnessScore'> & { usage: Omit<ArmUsage, 'arm'> };
  ```
- `ArmSeries` ← src/benchmark/history.ts:92 [EXTRACTED]
  ```
  export interface ArmSeries {
  ```
- `SuiteVersion` ← src/benchmark/history.ts:111 [EXTRACTED]
  ```
  export interface SuiteVersion {
  ```
- `ScorerView` ← src/benchmark/history.ts:118 [EXTRACTED]
  ```
  export interface ScorerView {
  ```
- `TaskView` ← src/benchmark/history.ts:125 [EXTRACTED]
  ```
  export interface TaskView {
  ```
- `ArmDimension` ← src/benchmark/history.ts:140 [EXTRACTED]
  ```
  export type ArmDimension = (typeof ARM_DIMENSIONS)[number];
  ```
- `ArmComparison` ← src/benchmark/history.ts:149 [EXTRACTED]
  ```
  export interface ArmComparison {
  ```
- `UncomparedArms` ← src/benchmark/history.ts:167 [EXTRACTED]
  ```
  export interface UncomparedArms {
  ```
- `PooledAgainst` ← src/benchmark/history.ts:179 [EXTRACTED]
  ```
  export type PooledAgainst = Omit<ArmAgainst, 'dominance'> & { key: string; dominance?: Dominance };
  ```
- `JudgeName` ← src/benchmark/history.ts:182 [EXTRACTED]
  ```
  export type JudgeName = Pick<Extract<NonNullable<TrialVerdict['decider']>, { by: 'judge' }>, 'tool' | 'model' | 'effort'>;
  ```
- `ScorerJudging` ← src/benchmark/history.ts:190 [EXTRACTED]
  ```
  export interface ScorerJudging {
  ```
- `SuiteCalibration` ← src/benchmark/history.ts:209 [EXTRACTED]
  ```
  export interface SuiteCalibration {
  ```
- `TeamConfig` ← src/benchmark/history.ts:217 [EXTRACTED]
  ```
  export interface TeamConfig {
  ```
- `TeamRevisionView` ← src/benchmark/history.ts:232 [EXTRACTED]
  ```
  export interface TeamRevisionView {
  ```
- `SuiteView` ← src/benchmark/history.ts:238 [EXTRACTED]
  ```
  export interface SuiteView {
  ```
- `RunRow` ← src/benchmark/history.ts:272 [EXTRACTED]
  ```
  export interface RunRow extends PassRate {
  ```
- `BenchmarkHistoryView` ← src/benchmark/history.ts:296 [EXTRACTED]
  ```
  export interface BenchmarkHistoryView {
  ```
- `PairSide` ← src/benchmark/pairing.ts:20 [EXTRACTED]
  ```
  export interface PairSide {
  ```
- `PairExclusion` ← src/benchmark/pairing.ts:26 [EXTRACTED]
  ```
  export type PairExclusion =
  ```
- `PairComparison` ← src/benchmark/pairing.ts:30 [EXTRACTED]
  ```
  export type PairComparison = { kind: 'compared' } | { kind: 'excluded'; because: PairExclusion };
  ```
- `ExcludedPairs` ← src/benchmark/pairing.ts:33 [EXTRACTED]
  ```
  export interface ExcludedPairs {
  ```
- `PlannedArm` ← src/benchmark/plan.ts:51 [EXTRACTED]
  ```
  export type PlannedArm = z.infer<typeof PlannedArmSchema>;
  ```
- `PlannedCheck` ← src/benchmark/plan.ts:55 [EXTRACTED]
  ```
  export type PlannedCheck = z.infer<typeof PlannedCheckSchema>;
  ```
- `PlannedTask` ← src/benchmark/plan.ts:79 [EXTRACTED]
  ```
  export type PlannedTask = z.infer<typeof PlannedTaskSchema>;
  ```
- `PlannedTrial` ← src/benchmark/plan.ts:93 [EXTRACTED]
  ```
  export type PlannedTrial = z.infer<typeof PlannedTrialSchema>;
  ```
- `CostRange` ← src/benchmark/plan.ts:98 [EXTRACTED]
  ```
  export type CostRange = z.infer<typeof CostRangeSchema>;
  ```
- `BenchmarkEstimate` ← src/benchmark/plan.ts:125 [EXTRACTED]
  ```
  export type BenchmarkEstimate = z.infer<typeof BenchmarkEstimateSchema>;
  ```
- `PlannedScorer` ← src/benchmark/plan.ts:140 [EXTRACTED]
  ```
  export type PlannedScorer = z.infer<typeof PlannedScorerSchema>;
  ```
- `PinnedRubric` ← src/benchmark/plan.ts:146 [EXTRACTED]
  ```
  export interface PinnedRubric {
  ```
- `PlannedJudge` ← src/benchmark/plan.ts:157 [EXTRACTED]
  ```
  export type PlannedJudge = z.infer<typeof PlannedJudgeSchema>;
  ```
- `BenchmarkPlan` ← src/benchmark/plan.ts:200 [EXTRACTED]
  ```
  export type BenchmarkPlan = z.infer<typeof BenchmarkPlanSchema>;
  ```
- `CompiledBundle` ← src/benchmark/plan.ts:339 [EXTRACTED]
  ```
  export interface CompiledBundle {
  ```
- `BenchmarkReport` ← src/benchmark/report.ts:31 [EXTRACTED]
  ```
  export interface BenchmarkReport {
  ```
- `TrialResult` ← src/benchmark/result.ts:31 [EXTRACTED]
  ```
  export type TrialResult = (typeof TRIAL_RESULTS)[number];
  ```
- `Baseline` ← src/benchmark/result.ts:36 [EXTRACTED]
  ```
  export type Baseline = (typeof BASELINES)[number];
  ```
- `BenchmarkRecord` ← src/benchmark/result.ts:138 [EXTRACTED]
  ```
  export type BenchmarkRecord = z.infer<typeof BenchmarkRecordSchema>;
  ```
- `BenchmarkRunRecord` ← src/benchmark/result.ts:155 [EXTRACTED]
  ```
  export type BenchmarkRunRecord = z.infer<typeof BenchmarkRunRecordSchema>;
  ```
- `RunPlan` ← src/benchmark/run-plan.ts:11 [EXTRACTED]
  ```
  export interface RunPlan {
  ```
- `Chosen` ← src/benchmark/start.ts:60 [EXTRACTED]
  ```
  export interface Chosen {
  ```
- `BenchmarkPlanned` ← src/benchmark/start.ts:70 [EXTRACTED]
  ```
  export interface BenchmarkPlanned {
  ```
- `SyncTeamResult` ← src/benchmark/suite-cache.ts:29 [EXTRACTED]
  ```
  export interface SyncTeamResult extends SyncScoredWorkflowsResult {
  ```
- `TeamChoice` ← src/benchmark/suite.ts:57 [EXTRACTED]
  ```
  export type TeamChoice =
  ```
- `ArmValues` ← src/benchmark/suite.ts:131 [EXTRACTED]
  ```
  export type ArmValues = z.infer<typeof ArmValuesSchema>;
  ```
- `TaskSource` ← src/benchmark/suite.ts:353 [EXTRACTED]
  ```
  export type TaskSource = z.infer<typeof TaskSourceSchema>;
  ```
- `CheckFile` ← src/benchmark/suite.ts:488 [EXTRACTED]
  ```
  export interface CheckFile {
  ```
- `FileMode` ← src/benchmark/suite.ts:495 [EXTRACTED]
  ```
  export type FileMode = '100644' | '100755';
  ```
- `TaskCheck` ← src/benchmark/suite.ts:501 [EXTRACTED]
  ```
  export interface TaskCheck {
  ```
- `TaskJudge` ← src/benchmark/suite.ts:512 [EXTRACTED]
  ```
  export type TaskJudge =
  ```
- `Task` ← src/benchmark/suite.ts:524 [EXTRACTED]
  ```
  export interface Task {
  ```
- `Arm` ← src/benchmark/suite.ts:546 [EXTRACTED]
  ```
  export interface Arm {
  ```
- `Suite` ← src/benchmark/suite.ts:559 [EXTRACTED]
  ```
  export interface Suite {
  ```
- `SourceFile` ← src/benchmark/suite.ts:582 [EXTRACTED]
  ```
  export interface SourceFile {
  ```
- `SuiteFile` ← src/benchmark/suite.ts:588 [EXTRACTED]
  ```
  export interface SuiteFile {
  ```
- `SuiteParse` ← src/benchmark/suite.ts:594 [EXTRACTED]
  ```
  export type SuiteParse =
  ```
- `ArmResults` ← src/benchmark/table.ts:20 [EXTRACTED]
  ```
  export interface ArmResults extends Pick<RecordedArm, 'tool' | 'model' | 'effort' | 'source' | 'team' | 'role' | 'recall'> {
  ```
- `PassRate` ← src/benchmark/table.ts:44 [EXTRACTED]
  ```
  export interface PassRate {
  ```
- `Median` ← src/benchmark/table.ts:50 [EXTRACTED]
  ```
  export interface Median {
  ```
- `CostTotal` ← src/benchmark/table.ts:56 [EXTRACTED]
  ```
  export type CostTotal =
  ```
- `ArmUsage` ← src/benchmark/table.ts:64 [EXTRACTED]
  ```
  export interface ArmUsage {
  ```
- `CostPerPassedTrial` ← src/benchmark/table.ts:76 [EXTRACTED]
  ```
  export interface CostPerPassedTrial {
  ```
- `ArmAgainst` ← src/benchmark/table.ts:86 [EXTRACTED]
  ```
  export interface ArmAgainst {
  ```
- `Dominance` ← src/benchmark/table.ts:101 [EXTRACTED]
  ```
  export type Dominance = { passRate: 'same' | 'higher' | 'lower'; costRatio: number } & ({ kind: 'dominates' } | { kind: 'dominated' } | { kind: 'neither' });
  ```
- `ArmScorerResults` ← src/benchmark/table.ts:104 [EXTRACTED]
  ```
  export interface ArmScorerResults {
  ```
- `JudgeCalibration` ← src/benchmark/table.ts:120 [EXTRACTED]
  ```
  export interface JudgeCalibration {
  ```
- `BenchmarkTable` ← src/benchmark/table.ts:127 [EXTRACTED]
  ```
  export interface BenchmarkTable {
  ```
- `SkillLoads` ← src/benchmark/table.ts:164 [EXTRACTED]
  ```
  export interface SkillLoads {
  ```
- `TextTable` ← src/benchmark/table.ts:171 [EXTRACTED]
  ```
  export interface TextTable {
  ```
- `BenchmarkCells` ← src/benchmark/table.ts:177 [EXTRACTED]
  ```
  export interface BenchmarkCells {
  ```
- `BenchmarkTableInput` ← src/benchmark/table.ts:204 [EXTRACTED]
  ```
  export interface BenchmarkTableInput {
  ```
- `ObservedTrial` ← src/benchmark/table.ts:209 [EXTRACTED]
  ```
  export interface ObservedTrial {
  ```
- `ArmStanding` ← src/benchmark/table.ts:359 [EXTRACTED]
  ```
  export interface ArmStanding {
  ```
- `PairedInterval` ← src/benchmark/table.ts:741 [EXTRACTED]
  ```
  export interface PairedInterval {
  ```
- `RoutingValue` ← src/benchmark/table.ts:772 [EXTRACTED]
  ```
  export type RoutingValue = (typeof ROUTING_VALUES)[number];
  ```
- `ResourceSplit` ← src/benchmark/table.ts:775 [EXTRACTED]
  ```
  export interface ResourceSplit {
  ```
- `ResourceEffectRow` ← src/benchmark/table.ts:784 [EXTRACTED]
  ```
  export interface ResourceEffectRow {
  ```
- `ResourceEffect` ← src/benchmark/table.ts:798 [EXTRACTED]
  ```
  export interface ResourceEffect {
  ```
- `ArmTeam` ← src/benchmark/terms.ts:23 [EXTRACTED]
  ```
  export type ArmTeam = z.infer<typeof ArmTeamSchema>;
  ```
- `SkillChanges` ← src/benchmark/terms.ts:36 [EXTRACTED]
  ```
  export type SkillChanges = z.infer<typeof SkillChangesSchema>;
  ```
- `TrialLimits` ← src/benchmark/terms.ts:51 [EXTRACTED]
  ```
  export type TrialLimits = z.infer<typeof TrialLimitsSchema>;
  ```
- `CommittedSuite` ← src/benchmark/trial.ts:41 [EXTRACTED]
  ```
  export type CommittedSuite = z.infer<typeof CommittedSuiteSchema>;
  ```
- `TrialVerdict` ← src/benchmark/verdicts.ts:59 [EXTRACTED]
  ```
  export type TrialVerdict = z.infer<typeof TrialVerdictSchema>;
  ```
- `EntryVerdict` ← src/benchmark/verdicts.ts:77 [EXTRACTED]
  ```
  export type EntryVerdict = z.infer<typeof EntryVerdictSchema>;
  ```
- `TrialCalibration` ← src/benchmark/verdicts.ts:89 [EXTRACTED]
  ```
  export type TrialCalibration = z.infer<typeof TrialCalibrationSchema>;
  ```
- `EntryCalibration` ← src/benchmark/verdicts.ts:91 [EXTRACTED]
  ```
  export type EntryCalibration = TrialCalibration & { step: string; pass: number };
  ```
- `CiExtractMrOptions` ← src/ci/extract-mr.ts:27 [EXTRACTED]
  ```
  export interface CiExtractMrOptions {
  ```
- `CommentResult` ← src/ci/mr-comment.ts:38 [EXTRACTED]
  ```
  export interface CommentResult {
  ```
- `RejectionResult` ← src/ci/read-rejections.ts:34 [EXTRACTED]
  ```
  export interface RejectionResult {
  ```
- `TeamCommit` ← src/dashboard/benchmarks.ts:130 [EXTRACTED]
  ```
  export interface TeamCommit {
  ```
- `TeamDiff` ← src/dashboard/benchmarks.ts:136 [EXTRACTED]
  ```
  export interface TeamDiff {
  ```
- `RoleArm` ← src/dashboard/benchmarks.ts:142 [EXTRACTED]
  ```
  export interface RoleArm {
  ```
- `BenchmarkPage` ← src/dashboard/benchmarks.ts:153 [EXTRACTED]
  ```
  export type BenchmarkPage = BenchmarkHistoryView & { teamCommits: Record<string, TeamCommit>; teamDiffs: Record<string, TeamDiff>; roleArms: RoleArm[] };
  ```
- `NamespaceType` ← src/dashboard/delivery.ts:16 [EXTRACTED]
  ```
  export type NamespaceType = typeof NAMESPACE_TYPES[number];
  ```
- `Namespaces` ← src/dashboard/delivery.ts:18 [EXTRACTED]
  ```
  export type Namespaces = Record<NamespaceType, string[]>;
  ```
- `Delivery` ← src/dashboard/delivery.ts:29 [EXTRACTED]
  ```
  export interface Delivery {
  ```
- `DistributionSelection` ← src/dashboard/distribution.ts:31 [EXTRACTED]
  ```
  export interface DistributionSelection {
  ```
- `JsonBody` ← src/dashboard/http.ts:24 [EXTRACTED]
  ```
  export type JsonBody = z.infer<typeof JsonBodySchema>;
  ```
- `DayPoint` ← src/dashboard/improvement.ts:22 [EXTRACTED]
  ```
  export interface DayPoint { date: string; ended: number; succeeded: number; corrected: number; prompts: number; durationMs: number; costMicros: number; priced: number; cacheRead: number; cacheEligible: number; members: number }
  ```
- `SkillUse` ← src/dashboard/improvement.ts:25 [EXTRACTED]
  ```
  export interface SkillUse { name: string; namespace?: string; uses: number; users: number; lastUsed: string | null }
  ```
- `DocAdoption` ← src/dashboard/improvement.ts:31 [EXTRACTED]
  ```
  export interface DocAdoption { docId: string; recalledSessions: number; toolCredits: number; judgeCredits: number; judged: number; ratio: number }
  ```
- `ImprovementData` ← src/dashboard/improvement.ts:33 [EXTRACTED]
  ```
  export interface ImprovementData {
  ```
- `MissingLabel` ← src/dashboard/judging-health.ts:22 [EXTRACTED]
  ```
  export interface MissingLabel {
  ```
- `JudgingHealth` ← src/dashboard/judging-health.ts:32 [EXTRACTED]
  ```
  export interface JudgingHealth {
  ```
- `LayeredResourceType` ← src/dashboard/layered-resources.ts:40 [EXTRACTED]
  ```
  export type LayeredResourceType = 'workflows' | 'hooks' | 'mcp' | 'benchmarks' | 'rules';
  ```
- `ResourceLayer` ← src/dashboard/layered-resources.ts:43 [EXTRACTED]
  ```
  export type ResourceLayer =
  ```
- `ResourcePlace` ← src/dashboard/layered-resources.ts:49 [EXTRACTED]
  ```
  export interface ResourcePlace {
  ```
- `ResourceState` ← src/dashboard/layered-resources.ts:61 [EXTRACTED]
  ```
  export type ResourceState =
  ```
- `ResourceFolder` ← src/dashboard/layered-resources.ts:76 [EXTRACTED]
  ```
  export interface ResourceFolder {
  ```
- `LayeredResource` ← src/dashboard/layered-resources.ts:98 [EXTRACTED]
  ```
  export interface LayeredResource extends ResourcePlace {
  ```
- `LayeredResourceList` ← src/dashboard/layered-resources.ts:107 [EXTRACTED]
  ```
  export interface LayeredResourceList {
  ```
- `DefaultHookResource` ← src/dashboard/layered-resources.ts:119 [EXTRACTED]
  ```
  export interface DefaultHookResource extends DefaultFolderComparison {
  ```
- `LayeredResources` ← src/dashboard/layered-resources.ts:131 [EXTRACTED]
  ```
  export interface LayeredResources {
  ```
- `MemberSettingsPanel` ← src/dashboard/member-settings.ts:12 [EXTRACTED]
  ```
  export type MemberSettingsPanel =
  ```
- `DashboardSkill` ← src/dashboard/resources-skills.ts:24 [EXTRACTED]
  ```
  export interface DashboardSkill {
  ```
- `SkillsInventory` ← src/dashboard/resources-skills.ts:96 [EXTRACTED]
  ```
  export interface SkillsInventory {
  ```
- `SkillExclusionResult` ← src/dashboard/resources-skills.ts:229 [EXTRACTED]
  ```
  export type SkillExclusionResult =
  ```
- `DashboardRule` ← src/dashboard/resources.ts:23 [EXTRACTED]
  ```
  export interface DashboardRule {
  ```
- `ScorerQuery` ← src/dashboard/scorers.ts:32 [EXTRACTED]
  ```
  export type ScorerQuery = Omit<ScorerResultsQuery, 'split'> & { commit?: string };
  ```
- `ScorerLoop` ← src/dashboard/self-improvement.ts:36 [EXTRACTED]
  ```
  export type ScorerLoop = {
  ```
- `RequestCounts` ← src/dashboard/self-improvement.ts:53 [EXTRACTED]
  ```
  export type RequestCounts = { open: number; merged: number; closed: number };
  ```
- `Requests` ← src/dashboard/self-improvement.ts:56 [EXTRACTED]
  ```
  export type Requests = ({ kind: 'answered' } & RequestCounts) | { kind: 'unknown' };
  ```
- `Impact` ← src/dashboard/self-improvement.ts:59 [EXTRACTED]
  ```
  export type Impact = Omit<Split, 'commit'>;
  ```
- `ProposalRequest` ← src/dashboard/self-improvement.ts:62 [EXTRACTED]
  ```
  export type ProposalRequest = { kind: 'open'; url: string; openedAt: string } | { kind: 'not_open' } | { kind: 'unknown' };
  ```
- `Proof` ← src/dashboard/self-improvement.ts:68 [EXTRACTED]
  ```
  export type Proof = {
  ```
- `ProofArm` ← src/dashboard/self-improvement.ts:76 [EXTRACTED]
  ```
  export type ProofArm = { arm: string; tool: string };
  ```
- `Change` ← src/dashboard/self-improvement.ts:88 [EXTRACTED]
  ```
  export type Change =
  ```
- `ClosedChange` ← src/dashboard/self-improvement.ts:94 [EXTRACTED]
  ```
  export type ClosedChange = { state: 'closed'; scorer: string; title: string; url: string; openedAt: string; at: string };
  ```
- `Setup` ← src/dashboard/self-improvement.ts:101 [EXTRACTED]
  ```
  export type Setup = {
  ```
- `LoopRun` ← src/dashboard/self-improvement.ts:108 [EXTRACTED]
  ```
  export type LoopRun = Pick<LocalRunRow | ReportedRunRow, 'run' | 'status' | 'startedAt' | 'endedAt' | 'source'> & { username?: string };
  ```
- `SelfImprovementView` ← src/dashboard/self-improvement.ts:110 [EXTRACTED]
  ```
  export type SelfImprovementView = {
  ```
- `CapturedSessions` ← src/dashboard/session-sharing.ts:23 [EXTRACTED]
  ```
  export type CapturedSessions = { attended: Settled & { active: number }; unattended: Settled & { waitingForDrain: number } };
  ```
- `SessionSharing` ← src/dashboard/session-sharing.ts:25 [EXTRACTED]
  ```
  export type SessionSharing =
  ```
- `TokenCostSummary` ← src/dashboard/token-costs.ts:11 [EXTRACTED]
  ```
  export type TokenCostSummary = {
  ```
- `LocalRunRow` ← src/dashboard/workflow-runs.ts:131 [EXTRACTED]
  ```
  export type LocalRunRow = RunRow & {
  ```
- `ReportedRunRow` ← src/dashboard/workflow-runs.ts:147 [EXTRACTED]
  ```
  export type ReportedRunRow = RunRow & { source: 'reported'; username: string };
  ```
- `RunBranches` ← src/dashboard/workflow-runs.ts:187 [EXTRACTED]
  ```
  export type RunBranches = Exclude<SettledBranches, { state: 'kept' }> | KeptRunBranches;
  ```
- `RunDetail` ← src/dashboard/workflow-runs.ts:191 [EXTRACTED]
  ```
  export type RunDetail = { run: LocalRunRow | ReportedRunRow; steps: StepRow[]; scoring: ScoringTotal; benchmark?: BenchmarkCells; branches?: RunBranches; held?: HeldSteps };
  ```
- `HandoffRow` ← src/dashboard/workflow-runs.ts:194 [EXTRACTED]
  ```
  export type HandoffRow = PublishedRun & { isMine: boolean };
  ```
- `ReportedHistory` ← src/dashboard/workflow-runs.ts:197 [EXTRACTED]
  ```
  export type ReportedHistory = { state: 'ok'; runs: ReportedRunRow[]; handoffs: HandoffRow[] } | { state: 'unavailable' };
  ```
- `DashboardWorkspace` ← src/dashboard/workspaces.ts:13 [EXTRACTED]
  ```
  export interface DashboardWorkspace {
  ```
- `ConfidenceFactors` ← src/maintenance/confidence.ts:15 [EXTRACTED]
  ```
  export interface ConfidenceFactors {
  ```
- `MaintenancePaths` ← src/maintenance/paths.ts:9 [EXTRACTED]
  ```
  export interface MaintenancePaths {
  ```
- `PromotionCandidate` ← src/maintenance/promote.ts:19 [EXTRACTED]
  ```
  export interface PromotionCandidate {
  ```
- `PromotionThresholds` ← src/maintenance/promote.ts:32 [EXTRACTED]
  ```
  export type PromotionThresholds = DefaultFolderParams<'workflows', 'teamai-promote-learning'>;
  ```
- `PromotionCandidatesQuery` ← src/maintenance/promote.ts:42 [EXTRACTED]
  ```
  export interface PromotionCandidatesQuery {
  ```
- `PromotionCategory` ← src/maintenance/promote.ts:166 [EXTRACTED]
  ```
  export type PromotionCategory = z.infer<typeof PromotionCategorySchema>;
  ```
- `PromotedContent` ← src/maintenance/promotion-publish.ts:21 [EXTRACTED]
  ```
  export type PromotedContent = { kind: 'rewritten'; text: string } | { kind: 'as-written'; why: string };
  ```
- `PruneCandidate` ← src/maintenance/prune.ts:12 [EXTRACTED]
  ```
  export interface PruneCandidate {
  ```
- `PruneOptions` ← src/maintenance/prune.ts:20 [EXTRACTED]
  ```
  export interface PruneOptions {
  ```
- `StaleEntry` ← src/maintenance/quality-update.ts:15 [EXTRACTED]
  ```
  export interface StaleEntry {
  ```
- `StaleGates` ← src/maintenance/quality-update.ts:25 [EXTRACTED]
  ```
  export type StaleGates = DefaultFolderParams<'workflows', 'teamai-draft-learning-updates'>;
  ```
- `RelatedAdoptedLearningsOptions` ← src/maintenance/quality-update.ts:210 [EXTRACTED]
  ```
  export interface RelatedAdoptedLearningsOptions {
  ```
- `DraftEntry` ← src/maintenance/quality-update.ts:357 [EXTRACTED]
  ```
  export interface DraftEntry {
  ```
- `AliasWarning` ← src/models/aliases.ts:155 [EXTRACTED]
  ```
  export interface AliasWarning {
  ```
- `TeamAlias` ← src/models/aliases.ts:163 [EXTRACTED]
  ```
  export interface TeamAlias {
  ```
- `InactiveAliasFile` ← src/models/aliases.ts:169 [EXTRACTED]
  ```
  export interface InactiveAliasFile {
  ```
- `ModelAliases` ← src/models/aliases.ts:175 [EXTRACTED]
  ```
  export type ModelAliases =
  ```
- `ResolutionStep` ← src/models/aliases.ts:211 [EXTRACTED]
  ```
  export type ResolutionStep = 'extras' | 'literal' | 'switched' | 'local' | 'team' | 'default';
  ```
- `ModelResolution` ← src/models/aliases.ts:221 [EXTRACTED]
  ```
  export type ModelResolution =
  ```
- `NoModel` ← src/models/aliases.ts:226 [EXTRACTED]
  ```
  export type NoModel = 'unmapped' | 'local' | 'switched' | 'unresolved';
  ```
- `ModelProtocol` ← src/models/profile.ts:30 [EXTRACTED]
  ```
  export type ModelProtocol = z.infer<typeof ModelProtocolSchema>;
  ```
- `ModelAgent` ← src/models/profile.ts:45 [EXTRACTED]
  ```
  export type ModelAgent = z.infer<typeof ModelAgentSchema>;
  ```
- `ModelGroup` ← src/models/profile.ts:73 [EXTRACTED]
  ```
  export type ModelGroup = z.infer<typeof ModelGroupSchema>;
  ```
- `ModelProfile` ← src/models/profile.ts:94 [EXTRACTED]
  ```
  export type ModelProfile = z.infer<typeof ModelProfileSchema>;
  ```
- `ModelProfilesFile` ← src/models/profile.ts:147 [EXTRACTED]
  ```
  export type ModelProfilesFile = z.infer<typeof ModelProfilesFileSchema>;
  ```
- `ModelProfileSource` ← src/models/profile.ts:149 [EXTRACTED]
  ```
  export type ModelProfileSource = 'team' | 'local';
  ```
- `ProfileRef` ← src/models/profile.ts:151 [EXTRACTED]
  ```
  export interface ProfileRef {
  ```
- `TeamModelProfiles` ← src/models/profile.ts:161 [EXTRACTED]
  ```
  export interface TeamModelProfiles extends ModelProfilesFile {
  ```
- `StoredModelInput` ← src/models/profile.ts:166 [EXTRACTED]
  ```
  export interface StoredModelInput {
  ```
- `StoredModelInputs` ← src/models/profile.ts:171 [EXTRACTED]
  ```
  export type StoredModelInputs = Record<string, { API_KEY?: StoredModelInput }>;
  ```
- `ResolvedModelRoute` ← src/models/profile.ts:180 [EXTRACTED]
  ```
  export interface ResolvedModelRoute {
  ```
- `ResolvedModelProfile` ← src/models/profile.ts:185 [EXTRACTED]
  ```
  export interface ResolvedModelProfile extends ProfileRef {
  ```
- `UnadoptedLegacyFile` ← src/models/profile.ts:409 [EXTRACTED]
  ```
  export interface UnadoptedLegacyFile {
  ```
- `ModelSwitchResult` ← src/models/switch.ts:78 [EXTRACTED]
  ```
  export interface ModelSwitchResult {
  ```
- `ActiveModelProfile` ← src/models/switch.ts:85 [EXTRACTED]
  ```
  export interface ActiveModelProfile {
  ```
- `SwitchOptions` ← src/models/switch.ts:1500 [EXTRACTED]
  ```
  export interface SwitchOptions {
  ```
- `LiveModelSwitch` ← src/models/switch.ts:1841 [EXTRACTED]
  ```
  export type LiveModelSwitch = { readonly ok: true; readonly switched: boolean } | { readonly ok: false; readonly reason: string };
  ```
- `PackageDoctorReport` ← src/pkg/commands.ts:323 [EXTRACTED]
  ```
  export interface PackageDoctorReport {
  ```
- `EnvironmentVersion` ← src/pkg/env-detect.ts:3 [EXTRACTED]
  ```
  export interface EnvironmentVersion {
  ```
- `DeclaredPackageCounts` ← src/pkg/pkg-hint.ts:25 [EXTRACTED]
  ```
  export interface DeclaredPackageCounts {
  ```
- `PackageScope` ← src/pkg/types.ts:5 [EXTRACTED]
  ```
  export type PackageScope = z.infer<typeof PackageScopeSchema>;
  ```
- `NpmSpec` ← src/pkg/types.ts:91 [EXTRACTED]
  ```
  export type NpmSpec = z.infer<typeof NpmSpecSchema>;
  ```
- `ClaudeMarketplace` ← src/pkg/types.ts:93 [EXTRACTED]
  ```
  export type ClaudeMarketplace = z.infer<typeof ClaudeMarketplaceSchema>;
  ```
- `ClaudePluginSpec` ← src/pkg/types.ts:95 [EXTRACTED]
  ```
  export type ClaudePluginSpec = z.infer<typeof ClaudePluginSpecSchema>;
  ```
- `ClaudeEcosystem` ← src/pkg/types.ts:97 [EXTRACTED]
  ```
  export type ClaudeEcosystem = z.infer<typeof ClaudeEcosystemSchema>;
  ```
- `PackageSet` ← src/pkg/types.ts:99 [EXTRACTED]
  ```
  export type PackageSet = z.infer<typeof PackageSetSchema>;
  ```
- `PackageManifest` ← src/pkg/types.ts:101 [EXTRACTED]
  ```
  export type PackageManifest = z.infer<typeof PackageManifestSchema>;
  ```
- `NpmLockEntry` ← src/pkg/types.ts:144 [EXTRACTED]
  ```
  export type NpmLockEntry = z.infer<typeof NpmLockEntrySchema>;
  ```
- `ClaudeMarketplaceLock` ← src/pkg/types.ts:146 [EXTRACTED]
  ```
  export type ClaudeMarketplaceLock = z.infer<typeof ClaudeMarketplaceLockSchema>;
  ```
- `ClaudePluginLock` ← src/pkg/types.ts:148 [EXTRACTED]
  ```
  export type ClaudePluginLock = z.infer<typeof ClaudePluginLockSchema>;
  ```
- `PackageLock` ← src/pkg/types.ts:150 [EXTRACTED]
  ```
  export type PackageLock = z.infer<typeof PackageLockSchema>;
  ```
- `PackageStatus` ← src/pkg/types.ts:152 [EXTRACTED]
  ```
  export interface PackageStatus {
  ```
- `OriginProvider` ← src/providers/registry.ts:233 [EXTRACTED]
  ```
  export type OriginProvider =
  ```
- `GitProvider` ← src/providers/types.ts:25 [EXTRACTED]
  ```
  export type GitProvider = Provider<MRData>;
  ```
- `RepoListEntry` ← src/repo-list/schema.ts:31 [EXTRACTED]
  ```
  export type RepoListEntry = z.infer<typeof RepoListEntrySchema>;
  ```
- `RepoListOrgEntry` ← src/repo-list/schema.ts:33 [EXTRACTED]
  ```
  export type RepoListOrgEntry = z.infer<typeof RepoListOrgEntrySchema>;
  ```
- `RepoListItem` ← src/repo-list/schema.ts:35 [EXTRACTED]
  ```
  export type RepoListItem = z.infer<typeof RepoListItemSchema>;
  ```
- `RepoListFile` ← src/repo-list/schema.ts:37 [EXTRACTED]
  ```
  export type RepoListFile = z.infer<typeof RepoListFileSchema>;
  ```
- `ToolName` ← src/resources/agent-format.ts:16 [EXTRACTED]
  ```
  export type ToolName = AgentToolId;
  ```
- `AgentFileExtension` ← src/resources/agent-format.ts:18 [EXTRACTED]
  ```
  export type AgentFileExtension = '.agent.md' | '.md' | '.toml' | '.json';
  ```
- `ParsedValue` ← src/resources/agent-format.ts:61 [EXTRACTED]
  ```
  export type ParsedValue = string | number | bigint | boolean | null | Date | ParsedValue[] | ParsedFields;
  ```
- `ParsedFields` ← src/resources/agent-format.ts:64 [EXTRACTED]
  ```
  export interface ParsedFields { [key: string]: ParsedValue }
  ```
- `AgentSpec` ← src/resources/agent-format.ts:102 [EXTRACTED]
  ```
  export interface AgentSpec {
  ```
- `ParseResult` ← src/resources/agent-format.ts:131 [EXTRACTED]
  ```
  export type ParseResult =
  ```
- `RenderResult` ← src/resources/agent-format.ts:220 [EXTRACTED]
  ```
  export interface RenderResult {
  ```
- `ReverseResult` ← src/resources/agent-format.ts:752 [EXTRACTED]
  ```
  export type ReverseResult =
  ```
- `MergeConflict` ← src/resources/agent-format.ts:1147 [EXTRACTED]
  ```
  export interface MergeConflict {
  ```
- `MergeResult` ← src/resources/agent-format.ts:1154 [EXTRACTED]
  ```
  export type MergeResult =
  ```
- `ResolvedAgentModel` ← src/resources/agent-format.ts:1298 [EXTRACTED]
  ```
  export interface ResolvedAgentModel {
  ```
- `AgentResourceItem` ← src/resources/agents.ts:56 [EXTRACTED]
  ```
  export interface AgentResourceItem extends ResourceItem {
  ```
- `AgentTool` ← src/resources/agents.ts:2381 [EXTRACTED]
  ```
  export interface AgentTool {
  ```
- `RedeployedCopy` ← src/resources/agents.ts:2392 [EXTRACTED]
  ```
  export type RedeployedCopy = DeliveryTarget & { reason: 'model' | 'missing' | 'render' };
  ```
- `PlacementRecords` ← src/resources/base.ts:6 [EXTRACTED]
  ```
  export type PlacementRecords = Pick<State, 'placedRules' | 'placedAgents'>;
  ```
- `ScanForPushOptions` ← src/resources/base.ts:27 [EXTRACTED]
  ```
  export interface ScanForPushOptions {
  ```
- `DeliveredHashes` ← src/resources/delivered-copies.ts:27 [EXTRACTED]
  ```
  export type DeliveredHashes = Record<string, string>;
  ```
- `DeliveredFile` ← src/resources/delivered-copies.ts:34 [EXTRACTED]
  ```
  export interface DeliveredFile {
  ```
- `CopyVerdict` ← src/resources/delivered-copies.ts:40 [EXTRACTED]
  ```
  export type CopyVerdict =
  ```
- `DeliveryLedger` ← src/resources/delivered-copies.ts:66 [EXTRACTED]
  ```
  export interface DeliveryLedger {
  ```
- `SkillFileOwners` ← src/resources/delivered-copies.ts:429 [EXTRACTED]
  ```
  export interface SkillFileOwners {
  ```
- `DeliveredFolderType` ← src/resources/delivered-folders.ts:34 [EXTRACTED]
  ```
  export type DeliveredFolderType = 'hooks' | 'rules' | 'agents' | 'mcp';
  ```
- `DeliveredFolderRef` ← src/resources/delivered-folders.ts:37 [EXTRACTED]
  ```
  export interface DeliveredFolderRef {
  ```
- `FolderIdentity` ← src/resources/delivered-folders.ts:84 [EXTRACTED]
  ```
  export type FolderIdentity =
  ```
- `PlacedFolders` ← src/resources/delivered-folders.ts:360 [EXTRACTED]
  ```
  export interface PlacedFolders {
  ```
- `FolderDelivery` ← src/resources/delivered-folders.ts:578 [EXTRACTED]
  ```
  export interface FolderDelivery {
  ```
- `RolePullContext` ← src/resources/desired.ts:32 [EXTRACTED]
  ```
  export interface RolePullContext {
  ```
- `DeliveryConflict` ← src/resources/desired.ts:136 [EXTRACTED]
  ```
  export interface DeliveryConflict {
  ```
- `DesiredItems` ← src/resources/desired.ts:143 [EXTRACTED]
  ```
  export type DesiredItems =
  ```
- `DesiredSkills` ← src/resources/desired.ts:268 [EXTRACTED]
  ```
  export type DesiredSkills = Extract<DesiredItems, { kind: 'resolved' }> & {
  ```
- `ShadowedSkill` ← src/resources/desired.ts:290 [EXTRACTED]
  ```
  export interface ShadowedSkill {
  ```
- `DesiredRules` ← src/resources/desired.ts:622 [EXTRACTED]
  ```
  export interface DesiredRules {
  ```
- `DocsSearchWhitelist` ← src/resources/docs.ts:49 [EXTRACTED]
  ```
  export interface DocsSearchWhitelist {
  ```
- `DesiredDocs` ← src/resources/docs.ts:535 [EXTRACTED]
  ```
  export interface DesiredDocs {
  ```
- `DirectoryEnv` ← src/resources/env-loader.ts:517 [EXTRACTED]
  ```
  export type DirectoryEnv =
  ```
- `EnvVariable` ← src/resources/env.ts:55 [EXTRACTED]
  ```
  export type EnvVariable = z.infer<typeof EnvVariableSchema>;
  ```
- `EnvYaml` ← src/resources/env.ts:57 [EXTRACTED]
  ```
  export type EnvYaml = z.infer<typeof EnvYamlSchema>;
  ```
- `EnvYamlRead` ← src/resources/env.ts:65 [EXTRACTED]
  ```
  export type EnvYamlRead =
  ```
- `FolderFile` ← src/resources/folder-files.ts:6 [EXTRACTED]
  ```
  export interface FolderFile {
  ```
- `FolderFileProblem` ← src/resources/folder-files.ts:13 [EXTRACTED]
  ```
  export interface FolderFileProblem {
  ```
- `FolderFilesRead` ← src/resources/folder-files.ts:19 [EXTRACTED]
  ```
  export type FolderFilesRead =
  ```
- `TeamHook` ← src/resources/hooks.ts:63 [EXTRACTED]
  ```
  export type TeamHook = z.infer<typeof TeamHookSchema>;
  ```
- `TeamHookDefinition` ← src/resources/hooks.ts:69 [EXTRACTED]
  ```
  export type TeamHookDefinition =
  ```
- `TeamHookFolder` ← src/resources/hooks.ts:74 [EXTRACTED]
  ```
  export type TeamHookFolder = { readonly kind: 'folder'; readonly hook: TeamHook; readonly files: readonly FolderFile[]; readonly version: string };
  ```
- `HooksYaml` ← src/resources/hooks.ts:76 [EXTRACTED]
  ```
  export type HooksYaml = z.infer<typeof HooksYamlSchema>;
  ```
- `BuiltinOverride` ← src/resources/hooks.ts:78 [EXTRACTED]
  ```
  export type BuiltinOverride = z.infer<typeof BuiltinOverrideSchema>;
  ```
- `BuiltinOverrideRead` ← src/resources/hooks.ts:232 [EXTRACTED]
  ```
  export type BuiltinOverrideRead = { known: true; override: BuiltinOverride | undefined } | { known: false };
  ```
- `DefaultHookReplacement` ← src/resources/hooks.ts:301 [EXTRACTED]
  ```
  export type DefaultHookReplacement = (
  ```
- `FolderFileLayer` ← src/resources/inherited-folders.ts:10 [EXTRACTED]
  ```
  export type FolderFileLayer = 'team' | 'teamai';
  ```
- `InheritedFolder` ← src/resources/inherited-folders.ts:13 [EXTRACTED]
  ```
  export interface InheritedFolder<TFile extends { readonly path: string }> {
  ```
- `Inheritance` ← src/resources/inherited-folders.ts:20 [EXTRACTED]
  ```
  export interface Inheritance {
  ```
- `PlaceFolderRead` ← src/resources/layered-entries.ts:27 [EXTRACTED]
  ```
  export type PlaceFolderRead<E> =
  ```
- `LayeredEntryType` ← src/resources/layered-entries.ts:33 [EXTRACTED]
  ```
  export interface LayeredEntryType<TEntry, E> {
  ```
- `PlacedDefinition` ← src/resources/layered-entries.ts:45 [EXTRACTED]
  ```
  export interface PlacedDefinition<TEntry, E> {
  ```
- `PlaceNote` ← src/resources/layered-entries.ts:52 [EXTRACTED]
  ```
  export interface PlaceNote {
  ```
- `LayeredPlaceRead` ← src/resources/layered-entries.ts:59 [EXTRACTED]
  ```
  export type LayeredPlaceRead<TEntry, E> =
  ```
- `MarkerFolderRead` ← src/resources/layered-entries.ts:86 [EXTRACTED]
  ```
  export type MarkerFolderRead<T> =
  ```
- `ResolveResult` ← src/resources/mcp-format.ts:205 [EXTRACTED]
  ```
  export interface ResolveResult {
  ```
- `McpJsonEntry` ← src/resources/mcp-format.ts:259 [EXTRACTED]
  ```
  export type McpJsonEntry = JsonObject;
  ```
- `TeamMcpServer` ← src/resources/mcp.ts:57 [EXTRACTED]
  ```
  export type TeamMcpServer = z.infer<typeof TeamMcpServerSchema>;
  ```
- `McpYaml` ← src/resources/mcp.ts:59 [EXTRACTED]
  ```
  export type McpYaml = z.infer<typeof McpYamlSchema>;
  ```
- `TeamMcpDefinition` ← src/resources/mcp.ts:116 [EXTRACTED]
  ```
  export type TeamMcpDefinition =
  ```
- `TeamMcpFolder` ← src/resources/mcp.ts:121 [EXTRACTED]
  ```
  export type TeamMcpFolder = { readonly kind: 'folder'; readonly server: TeamMcpServer; readonly files: readonly FolderFile[]; readonly version: string };
  ```
- `OpencodeRuleGlobs` ← src/resources/opencode-config.ts:41 [EXTRACTED]
  ```
  export interface OpencodeRuleGlobs {
  ```
- `OpencodeRulesTarget` ← src/resources/opencode-config.ts:57 [EXTRACTED]
  ```
  export interface OpencodeRulesTarget extends OpencodeRuleGlobs {
  ```
- `OpencodeContextReference` ← src/resources/opencode-config.ts:281 [EXTRACTED]
  ```
  export interface OpencodeContextReference {
  ```
- `PlacesRecord` ← src/resources/places.ts:12 [EXTRACTED]
  ```
  export type PlacesRecord = NonNullable<CheckoutRecord['places']>;
  ```
- `PlacedResource` ← src/resources/places.ts:15 [EXTRACTED]
  ```
  export type PlacedResource = keyof PlacesRecord;
  ```
- `Places` ← src/resources/places.ts:18 [EXTRACTED]
  ```
  export type Places = NonNullable<PlacesRecord[PlacedResource]>;
  ```
- `SessionToolHomes` ← src/resources/places.ts:21 [EXTRACTED]
  ```
  export type SessionToolHomes = NonNullable<CheckoutRecord['sessionToolHomes']>;
  ```
- `LeftPlace` ← src/resources/places.ts:152 [EXTRACTED]
  ```
  export type LeftPlace = { readonly place: string; readonly tool: string; readonly currentPlace: string };
  ```
- `ResourceLayout` ← src/resources/resolver.ts:13 [EXTRACTED]
  ```
  export interface ResourceLayout<TEntry = never> {
  ```
- `EntryListRead` ← src/resources/resolver.ts:44 [EXTRACTED]
  ```
  export type EntryListRead<TEntry> =
  ```
- `ResourceDiagnostic` ← src/resources/resolver.ts:53 [EXTRACTED]
  ```
  export interface ResourceDiagnostic {
  ```
- `ResourceSource` ← src/resources/resolver.ts:60 [EXTRACTED]
  ```
  export type ResourceSource<TEntry> =
  ```
- `LayeredItem` ← src/resources/resolver.ts:68 [EXTRACTED]
  ```
  export type LayeredItem<TEntry, TShipped> =
  ```
- `TeamItem` ← src/resources/resolver.ts:73 [EXTRACTED]
  ```
  export type TeamItem<TEntry> =
  ```
- `LayeredResolution` ← src/resources/resolver.ts:78 [EXTRACTED]
  ```
  export type LayeredResolution<TEntry, TShipped> =
  ```
- `ShippedFile` ← src/resources/resolver.ts:88 [EXTRACTED]
  ```
  export interface ShippedFile {
  ```
- `TeamaiLayer` ← src/resources/resolver.ts:97 [EXTRACTED]
  ```
  export interface TeamaiLayer<TShipped> {
  ```
- `TeamTree` ← src/resources/resolver.ts:103 [EXTRACTED]
  ```
  export interface TeamTree {
  ```
- `ResourceTree` ← src/resources/resolver.ts:111 [EXTRACTED]
  ```
  export interface ResourceTree<TShipped> {
  ```
- `FolderMarkerRead` ← src/resources/resolver.ts:222 [EXTRACTED]
  ```
  export type FolderMarkerRead =
  ```
- `TeamLayer` ← src/resources/resolver.ts:472 [EXTRACTED]
  ```
  export interface TeamLayer<TEntry> {
  ```
- `ListedResolution` ← src/resources/resolver.ts:512 [EXTRACTED]
  ```
  export type ListedResolution<TEntry, TShipped> = Exclude<LayeredResolution<TEntry, TShipped>, { readonly kind: 'missing' }>;
  ```
- `ResourceSurvey` ← src/resources/resolver.ts:515 [EXTRACTED]
  ```
  export interface ResourceSurvey<TEntry, TShipped> {
  ```
- `PickedName` ← src/resources/resolver.ts:556 [EXTRACTED]
  ```
  export type PickedName<T> = { readonly kind: 'resolved'; readonly item: ResolvedNamespaceItem<T> } | NamespaceConflict<T>;
  ```
- `PlainLayout` ← src/resources/resolver.ts:589 [EXTRACTED]
  ```
  export type PlainLayout<TEntry = never> = ResourceLayout<TEntry> & { readonly entryList?: undefined; readonly nameRule?: undefined };
  ```
- `WalkedItem` ← src/resources/resolver.ts:602 [EXTRACTED]
  ```
  export interface WalkedItem {
  ```
- `ResourceWalk` ← src/resources/resolver.ts:608 [EXTRACTED]
  ```
  export interface ResourceWalk {
  ```
- `RuleFormat` ← src/resources/rule-format.ts:36 [EXTRACTED]
  ```
  export interface RuleFormat {
  ```
- `InstructionBlock` ← src/resources/rule-format.ts:218 [EXTRACTED]
  ```
  export type InstructionBlock = 'culture' | 'claudemd' | 'recall' | 'team-rules';
  ```
- `LegacyRuleDir` ← src/resources/rule-format.ts:232 [EXTRACTED]
  ```
  export interface LegacyRuleDir {
  ```
- `LegacyRuleCopies` ← src/resources/rules.ts:52 [EXTRACTED]
  ```
  export interface LegacyRuleCopies {
  ```
- `RuleTextContext` ← src/resources/rules.ts:2031 [EXTRACTED]
  ```
  export interface RuleTextContext {
  ```
- `SecretDeclaration` ← src/resources/secrets.ts:36 [EXTRACTED]
  ```
  export type SecretDeclaration = z.infer<typeof SecretDeclarationSchema>;
  ```
- `WrittenSecretDeclaration` ← src/resources/secrets.ts:41 [EXTRACTED]
  ```
  export type WrittenSecretDeclaration = z.infer<typeof WrittenSecretDeclarationSchema>;
  ```
- `SecretDeclarations` ← src/resources/secrets.ts:141 [EXTRACTED]
  ```
  export type SecretDeclarations = { readonly kind: 'absent' } | EntryResolution<SecretDeclaration>;
  ```
- `KnownNamespaces` ← src/resources/secrets.ts:148 [EXTRACTED]
  ```
  export interface KnownNamespaces {
  ```
- `SharedSkillOwnership` ← src/resources/skills.ts:66 [EXTRACTED]
  ```
  export type SharedSkillOwnership = (sharedDir: string) => Promise<boolean>;
  ```
- `SkillTargetRequest` ← src/resources/skills.ts:206 [EXTRACTED]
  ```
  export interface SkillTargetRequest {
  ```
- `TeamSkill` ← src/resources/skills.ts:403 [EXTRACTED]
  ```
  export interface TeamSkill {
  ```
- `TeamSkillsRead` ← src/resources/skills.ts:413 [EXTRACTED]
  ```
  export interface TeamSkillsRead {
  ```
- `CopyDestination` ← src/resources/skills.ts:888 [EXTRACTED]
  ```
  export type CopyDestination =
  ```
- `TeamSkillIndex` ← src/resources/skills.ts:908 [EXTRACTED]
  ```
  export interface TeamSkillIndex {
  ```
- `TeamSkillSource` ← src/resources/team-skill-source.ts:15 [EXTRACTED]
  ```
  export type TeamSkillSource = string;
  ```
- `CarriedMark` ← src/scorers/attempts-upgrade.ts:19 [EXTRACTED]
  ```
  export type CarriedMark = { kind: 'labelled' } | { kind: 'failed'; code: JudgeFailureCode } | { kind: 'open'; lapses: number; requestedAt?: string };
  ```
- `JudgeCallFacts` ← src/scorers/batch.ts:18 [EXTRACTED]
  ```
  export interface JudgeCallFacts {
  ```
- `JudgeAnswer` ← src/scorers/batch.ts:52 [EXTRACTED]
  ```
  export type JudgeAnswer = z.infer<typeof JudgeAnswerSchema>;
  ```
- `Verdict` ← src/scorers/batch.ts:54 [EXTRACTED]
  ```
  export interface Verdict {
  ```
- `SyncScorerOptions` ← src/scorers/cache.ts:20 [EXTRACTED]
  ```
  export type SyncScorerOptions = { scopeLabel?: string } & (
  ```
- `SyncScorerResult` ← src/scorers/cache.ts:26 [EXTRACTED]
  ```
  export interface SyncScorerResult {
  ```
- `CachedScorer` ← src/scorers/cache.ts:59 [EXTRACTED]
  ```
  export type CachedScorer = Omit<CacheEntry, 'content'> & { definition: ScorerDefinition };
  ```
- `CheckRun` ← src/scorers/check-run.ts:33 [EXTRACTED]
  ```
  export type CheckRun =
  ```
- `CheckCause` ← src/scorers/check.ts:18 [EXTRACTED]
  ```
  export type CheckCause = (typeof CHECK_CAUSES)[number];
  ```
- `CheckVerdict` ← src/scorers/check.ts:21 [EXTRACTED]
  ```
  export type CheckVerdict =
  ```
- `CheckOutput` ← src/scorers/check.ts:42 [EXTRACTED]
  ```
  export type CheckOutput = z.infer<typeof CheckOutputSchema>;
  ```
- `CheckResult` ← src/scorers/check.ts:44 [EXTRACTED]
  ```
  export type CheckResult = (typeof CHECK_RESULTS)[number];
  ```
- `Added` ← src/scorers/check.ts:111 [EXTRACTED]
  ```
  export type Added = z.infer<typeof AddedSchema>;
  ```
- `Stage` ← src/scorers/definition.ts:37 [EXTRACTED]
  ```
  export type Stage = (typeof STAGES)[number];
  ```
- `ScorerLabel` ← src/scorers/definition.ts:85 [EXTRACTED]
  ```
  export type ScorerLabel = z.infer<typeof LabelSchema>;
  ```
- `ScorerDefinition` ← src/scorers/definition.ts:87 [EXTRACTED]
  ```
  export type ScorerDefinition = z.infer<typeof FrontmatterSchema> & {
  ```
- `ScorerDiagnostic` ← src/scorers/definition.ts:95 [EXTRACTED]
  ```
  export interface ScorerDiagnostic {
  ```
- `ParsedScorer` ← src/scorers/definition.ts:103 [EXTRACTED]
  ```
  export type ParsedScorer = { ok: true; definition: ScorerDefinition } | { ok: false; diagnostics: ScorerDiagnostic[] };
  ```
- `GroupRecord` ← src/scorers/evidence-dir.ts:54 [EXTRACTED]
  ```
  export type GroupRecord = z.infer<typeof GroupRecordSchema>;
  ```
- `EvidenceOutput` ← src/scorers/evidence-dir.ts:57 [EXTRACTED]
  ```
  export interface EvidenceOutput {
  ```
- `EvidenceGap` ← src/scorers/evidence.ts:15 [EXTRACTED]
  ```
  export type EvidenceGap = (typeof EVIDENCE_GAPS)[number];
  ```
- `Rubrics` ← src/scorers/evidence.ts:64 [EXTRACTED]
  ```
  export type Rubrics = readonly [ScorerDefinition, ...ScorerDefinition[]];
  ```
- `LinkedLearning` ← src/scorers/failure-links.ts:20 [EXTRACTED]
  ```
  export type LinkedLearning = { id: string; path: string };
  ```
- `FailureLinks` ← src/scorers/failure-links.ts:23 [EXTRACTED]
  ```
  export type FailureLinks = {
  ```
- `ScorerFolderFile` ← src/scorers/folder.ts:31 [EXTRACTED]
  ```
  export type ScorerFolderFile = z.infer<typeof ScorerFolderFileSchema>;
  ```
- `ScorerFolderRead` ← src/scorers/folder.ts:34 [EXTRACTED]
  ```
  export type ScorerFolderRead =
  ```
- `QuestionSession` ← src/scorers/generated-questions.ts:21 [EXTRACTED]
  ```
  export interface QuestionSession {
  ```
- `GeneratedQuestion` ← src/scorers/generated-questions.ts:27 [EXTRACTED]
  ```
  export interface GeneratedQuestion {
  ```
- `QuestionLookup` ← src/scorers/generated-questions.ts:33 [EXTRACTED]
  ```
  export type QuestionLookup = { ok: true; question: GeneratedQuestion } | { ok: false; why: string };
  ```
- `WrittenQuestionLabel` ← src/scorers/generated-questions.ts:36 [EXTRACTED]
  ```
  export interface WrittenQuestionLabel {
  ```
- `QuestionSwitches` ← src/scorers/generated-questions.ts:43 [EXTRACTED]
  ```
  export type QuestionSwitches = Pick<Extract<ScopeScoring, { ok: true }>, 'skillRouting' | 'recallAdoption'>;
  ```
- `QuestionFamily` ← src/scorers/generated-questions.ts:45 [EXTRACTED]
  ```
  export interface QuestionFamily {
  ```
- `IsolationSetting` ← src/scorers/isolation.ts:13 [EXTRACTED]
  ```
  export interface IsolationSetting {
  ```
- `RequiredIsolation` ← src/scorers/isolation.ts:18 [EXTRACTED]
  ```
  export interface RequiredIsolation {
  ```
- `JudgeModelChoice` ← src/scorers/judge-model.ts:30 [EXTRACTED]
  ```
  export type JudgeModelChoice<Tool extends string = string> =
  ```
- `ScoreItemStep` ← src/scorers/judging-workflows.ts:18 [EXTRACTED]
  ```
  export type ScoreItemStep = 'evidence' | 'judge' | 'label' | 'write' | 'publish' | 'settle';
  ```
- `LabelDelivery` ← src/scorers/label-store.ts:89 [EXTRACTED]
  ```
  export type LabelDelivery = { state: 'published' } | { state: 'pending' | 'unsupported'; reason: string };
  ```
- `PassScore` ← src/scorers/label-store.ts:95 [EXTRACTED]
  ```
  export type PassScore = Pick<ScoreLabel, 'scorer' | 'label' | 'score' | 'passed'> & { decidedBy?: Decider | 'hand' };
  ```
- `ScoringTotal` ← src/scorers/label-store.ts:100 [EXTRACTED]
  ```
  export interface ScoringTotal {
  ```
- `KeptLabel` ← src/scorers/label-store.ts:125 [EXTRACTED]
  ```
  export interface KeptLabel {
  ```
- `RunSubject` ← src/scorers/label.ts:16 [EXTRACTED]
  ```
  export type RunSubject = z.infer<typeof RunSubjectSchema>;
  ```
- `SessionSubject` ← src/scorers/label.ts:20 [EXTRACTED]
  ```
  export type SessionSubject = z.infer<typeof SessionSubjectSchema>;
  ```
- `SessionLabel` ← src/scorers/label.ts:81 [EXTRACTED]
  ```
  export type SessionLabel = z.infer<typeof SessionLabelSchema>;
  ```
- `Decider` ← src/scorers/label.ts:89 [EXTRACTED]
  ```
  export type Decider = (typeof DECIDERS)[number];
  ```
- `JudgeFailureCode` ← src/scorers/label.ts:97 [EXTRACTED]
  ```
  export type JudgeFailureCode = (typeof JUDGE_FAILURES)[number];
  ```
- `ScoreLabel` ← src/scorers/label.ts:136 [EXTRACTED]
  ```
  export type ScoreLabel = z.infer<typeof ScoreLabelSchema>;
  ```
- `SessionLabelContext` ← src/scorers/label.ts:144 [EXTRACTED]
  ```
  export type SessionLabelContext = z.infer<typeof SessionLabelContextSchema>;
  ```
- `JudgeCohort` ← src/scorers/label.ts:169 [EXTRACTED]
  ```
  export type JudgeCohort =
  ```
- `Demand` ← src/scorers/marks.ts:27 [EXTRACTED]
  ```
  export type Demand = (typeof DEMANDS)[number];
  ```
- `MarkKey` ← src/scorers/marks.ts:30 [EXTRACTED]
  ```
  export type MarkKey =
  ```
- `MarkState` ← src/scorers/marks.ts:40 [EXTRACTED]
  ```
  export type MarkState =
  ```
- `MarkOutcome` ← src/scorers/marks.ts:51 [EXTRACTED]
  ```
  export type MarkOutcome = { kind: 'labelled' } | { kind: 'failed'; code: JudgeFailureCode; usage?: ConfinedUsage } | { kind: 'waiting' };
  ```
- `RunStatus` ← src/scorers/marks.ts:54 [EXTRACTED]
  ```
  export interface RunStatus {
  ```
- `ReadRun` ← src/scorers/marks.ts:62 [EXTRACTED]
  ```
  export type ReadRun = (runId: string) => Promise<RunStatus | undefined>;
  ```
- `MarkFacts` ← src/scorers/marks.ts:64 [EXTRACTED]
  ```
  export interface MarkFacts {
  ```
- `Launch` ← src/scorers/marks.ts:69 [EXTRACTED]
  ```
  export interface Launch {
  ```
- `Opened` ← src/scorers/marks.ts:79 [EXTRACTED]
  ```
  export type Opened =
  ```
- `NamedSubject` ← src/scorers/named-subject.ts:34 [EXTRACTED]
  ```
  export interface NamedSubject {
  ```
- `NamedPass` ← src/scorers/named-subject.ts:42 [EXTRACTED]
  ```
  export interface NamedPass {
  ```
- `PassStarts` ← src/scorers/pass-scoring.ts:29 [EXTRACTED]
  ```
  export interface PassStarts {
  ```
- `ScoredLine` ← src/scorers/pass-scoring.ts:35 [EXTRACTED]
  ```
  export interface ScoredLine {
  ```
- `ScoredLabel` ← src/scorers/pass-scoring.ts:45 [EXTRACTED]
  ```
  export type ScoredLabel = z.infer<typeof ScoredLabelSchema>;
  ```
- `ScoredLabels` ← src/scorers/pass-scoring.ts:68 [EXTRACTED]
  ```
  export type ScoredLabels = { ok: true; labels: ScoredLabel[] } | { ok: false; reason: string };
  ```
- `PinnedScorer` ← src/scorers/pin.ts:28 [EXTRACTED]
  ```
  export type PinnedScorer = z.infer<typeof PinnedScorerSchema>;
  ```
- `ViewedLabel` ← src/scorers/results.ts:15 [EXTRACTED]
  ```
  export type ViewedLabel = {
  ```
- `Cohort` ← src/scorers/results.ts:28 [EXTRACTED]
  ```
  export type Cohort = {
  ```
- `Stats` ← src/scorers/results.ts:38 [EXTRACTED]
  ```
  export type Stats = { n: number; passed: number; failed: number; rate: number | null };
  ```
- `CohortSummary` ← src/scorers/results.ts:41 [EXTRACTED]
  ```
  export type CohortSummary = Cohort & { stats: Stats; trend: TrendWeek[]; lastScoredAt: string };
  ```
- `ScorerSummary` ← src/scorers/results.ts:44 [EXTRACTED]
  ```
  export type ScorerSummary = { scorer: string; defaultCohort: string; cohorts: CohortSummary[]; agreement?: Pick<JudgeAgreement, 'paired' | 'agree'> };
  ```
- `Dimension` ← src/scorers/results.ts:56 [EXTRACTED]
  ```
  export type Dimension = (typeof DIMENSIONS_OFFERED)[number];
  ```
- `Side` ← src/scorers/results.ts:107 [EXTRACTED]
  ```
  export type Side = 'before' | 'after';
  ```
- `Split` ← src/scorers/results.ts:110 [EXTRACTED]
  ```
  export type Split = { commit: string; before: Stats; after: Stats; notRecorded: Stats };
  ```
- `RoleOf` ← src/scorers/results.ts:113 [EXTRACTED]
  ```
  export type RoleOf = 'step' | 'member' | 'both';
  ```
- `Group` ← src/scorers/results.ts:120 [EXTRACTED]
  ```
  export type Group = { key: string; stats: Stats; interval: { low: number; high: number }; split?: Omit<Split, 'commit'> } & (
  ```
- `ScorerResultsQuery` ← src/scorers/results.ts:126 [EXTRACTED]
  ```
  export type ScorerResultsQuery = {
  ```
- `SubjectRef` ← src/scorers/results.ts:144 [EXTRACTED]
  ```
  export type SubjectRef =
  ```
- `FailingLabel` ← src/scorers/results.ts:153 [EXTRACTED]
  ```
  export type FailingLabel = {
  ```
- `Decided` ← src/scorers/results.ts:169 [EXTRACTED]
  ```
  export type Decided = { rows: Array<{ by: Decider | 'not recorded'; key: string; stats: Stats }>; beforeJudge: number };
  ```
- `HarnessFailures` ← src/scorers/results.ts:172 [EXTRACTED]
  ```
  export type HarnessFailures = { harness?: AgentHarness; failed: number };
  ```
- `RevisionChange` ← src/scorers/results.ts:175 [EXTRACTED]
  ```
  export type RevisionChange = { lastPassed: string; firstFailed: string };
  ```
- `ReminderInput` ← src/scorers/results.ts:182 [EXTRACTED]
  ```
  export type ReminderInput = { days: number; sessions: readonly string[]; hinted: ReadonlyMap<string, boolean> };
  ```
- `ReminderRow` ← src/scorers/results.ts:185 [EXTRACTED]
  ```
  export type ReminderRow = { reminder: 'yes' | 'no' | 'not recorded'; sessions: number; labelled: number; passed: number; rate: number | null };
  ```
- `ValueCount` ← src/scorers/results.ts:188 [EXTRACTED]
  ```
  export type ValueCount = { label: string; score: number; n: number };
  ```
- `TrendWeek` ← src/scorers/results.ts:191 [EXTRACTED]
  ```
  export type TrendWeek = Stats & { week: string };
  ```
- `JudgeAgreement` ← src/scorers/results.ts:194 [EXTRACTED]
  ```
  export type JudgeAgreement = {
  ```
- `Agreement` ← src/scorers/results.ts:210 [EXTRACTED]
  ```
  export type Agreement = {
  ```
- `Disagreement` ← src/scorers/results.ts:219 [EXTRACTED]
  ```
  export type Disagreement = SubjectRef & {
  ```
- `FailureStart` ← src/scorers/results.ts:229 [EXTRACTED]
  ```
  export type FailureStart = { commit: string } | { refused: 'tracked_changes' | 'not_recorded' };
  ```
- `Failure` ← src/scorers/results.ts:232 [EXTRACTED]
  ```
  export type Failure = {
  ```
- `CohortFailures` ← src/scorers/results.ts:246 [EXTRACTED]
  ```
  export type CohortFailures = Cohort & { stats: Stats; agreement?: Omit<JudgeAgreement, 'judge' | 'labels'> & { handLabelled: number } };
  ```
- `ScorerFailures` ← src/scorers/results.ts:248 [EXTRACTED]
  ```
  export type ScorerFailures = {
  ```
- `RubricLabels` ← src/scorers/results.ts:256 [EXTRACTED]
  ```
  export type RubricLabels = ReadonlyMap<string, readonly string[]>;
  ```
- `SelectedCohort` ← src/scorers/results.ts:258 [EXTRACTED]
  ```
  export type SelectedCohort = {
  ```
- `ScorerResultsView` ← src/scorers/results.ts:282 [EXTRACTED]
  ```
  export type ScorerResultsView = {
  ```
- `Unlabelled` ← src/scorers/run-judging.ts:27 [EXTRACTED]
  ```
  export type Unlabelled =
  ```
- `PassJudging` ← src/scorers/run-judging.ts:37 [EXTRACTED]
  ```
  export interface PassJudging {
  ```
- `RunJudgingState` ← src/scorers/run-judging.ts:98 [EXTRACTED]
  ```
  export interface RunJudgingState {
  ```
- `RunScorerPins` ← src/scorers/run-scorers.ts:21 [EXTRACTED]
  ```
  export type RunScorerPins = { ok: true; pins: Record<string, PinnedScorer> } | { ok: false; reason: string };
  ```
- `ScoreInstance` ← src/scorers/score-attempt.ts:20 [EXTRACTED]
  ```
  export interface ScoreInstance {
  ```
- `ScoreAttempt` ← src/scorers/score-attempt.ts:27 [EXTRACTED]
  ```
  export interface ScoreAttempt {
  ```
- `ScoreAttemptRead` ← src/scorers/score-attempt.ts:51 [EXTRACTED]
  ```
  export type ScoreAttemptRead = { ok: true; attempt: ScoreAttempt } | AttemptRefused;
  ```
- `LabelEntry` ← src/scorers/score-labels.ts:90 [EXTRACTED]
  ```
  export type LabelEntry = Entry;
  ```
- `LabelOutput` ← src/scorers/score-labels.ts:100 [EXTRACTED]
  ```
  export interface LabelOutput {
  ```
- `ScoreOverrideCode` ← src/scorers/score-override.ts:16 [EXTRACTED]
  ```
  export type ScoreOverrideCode = 'score_override_contract' | 'score_override_command' | 'score_override_workflow_step' | 'score_override_prompt' | 'score_override_confined_dir' | 'score_override_judge_prompt' | 'score_override_step_missing' | 'score_override_publish';
  ```
- `PlanGroup` ← src/scorers/score-plan.ts:37 [EXTRACTED]
  ```
  export interface PlanGroup {
  ```
- `Refusal` ← src/scorers/score-plan.ts:48 [EXTRACTED]
  ```
  export type Refusal = { ok: false; code: string; message: string };
  ```
- `PlanRequest` ← src/scorers/score-plan.ts:50 [EXTRACTED]
  ```
  export interface PlanRequest {
  ```
- `StageRecord` ← src/scorers/score-stage.ts:29 [EXTRACTED]
  ```
  export type StageRecord = z.infer<typeof StageRecordSchema>;
  ```
- `StageOutput` ← src/scorers/score-stage.ts:33 [EXTRACTED]
  ```
  export type StageOutput = { decided: boolean; pending?: boolean };
  ```
- `LapsedSubject` ← src/scorers/score-subjects.ts:109 [EXTRACTED]
  ```
  export type LapsedSubject = { subject: string; scorers: string[] };
  ```
- `JudgedFacts` ← src/scorers/scoring-evidence.ts:93 [EXTRACTED]
  ```
  export type JudgedFacts = Pick<Extract<ScoreLabel, { source: 'workflow' }>, 'used' | 'runMode' | 'agent'>;
  ```
- `StageVerdict` ← src/scorers/scoring-stages.ts:21 [EXTRACTED]
  ```
  export type StageVerdict =
  ```
- `CiVerdict` ← src/scorers/scoring-stages.ts:27 [EXTRACTED]
  ```
  export type CiVerdict = StageVerdict | { kind: 'pending'; head: string };
  ```
- `StageCheck` ← src/scorers/scoring-stages.ts:118 [EXTRACTED]
  ```
  export interface StageCheck { scorer: string; check: NonNullable<ScorerDefinition['check']>; expiresAt: string }
  ```
- `ScoringFileRead` ← src/scorers/settings.ts:51 [EXTRACTED]
  ```
  export type ScoringFileRead =
  ```
- `SessionScoring` ← src/scorers/settings.ts:142 [EXTRACTED]
  ```
  export type SessionScoring = { policies: SessionPolicies; dailyLimit: number; dailyLimitSource: PolicySource };
  ```
- `ScopeScoring` ← src/scorers/settings.ts:148 [EXTRACTED]
  ```
  export type ScopeScoring =
  ```
- `AvailableSkill` ← src/scorers/skill-evidence.ts:9 [EXTRACTED]
  ```
  export type AvailableSkill = { name: string } & DeliveredSkillInfo;
  ```
- `SkillsEvidence` ← src/scorers/skill-evidence.ts:12 [EXTRACTED]
  ```
  export interface SkillsEvidence {
  ```
- `SkillCaptures` ← src/scorers/skill-evidence.ts:18 [EXTRACTED]
  ```
  export type SkillCaptures = ReadonlyArray<{ teamSkillInfo?: Readonly<Record<string, DeliveredSkillInfo>> }>;
  ```
- `TeamSessionSubject` ← src/scorers/subject.ts:9 [EXTRACTED]
  ```
  export interface TeamSessionSubject {
  ```
- `Subject` ← src/scorers/subject.ts:14 [EXTRACTED]
  ```
  export type Subject =
  ```
- `UnknownScorer` ← src/scorers/team-sync.ts:12 [EXTRACTED]
  ```
  export type UnknownScorer = { file: string; scorer: string } & (
  ```
- `SyncScoredWorkflowsResult` ← src/scorers/team-sync.ts:49 [EXTRACTED]
  ```
  export interface SyncScoredWorkflowsResult extends SyncWorkflowResult {
  ```
- `Refusal` ← src/scorers/tried-file.ts:10 [EXTRACTED]
  ```
  export type Refusal = { ok: false; code: string; message: string };
  ```
- `TriedFile` ← src/scorers/tried-file.ts:17 [EXTRACTED]
  ```
  export interface TriedFile {
  ```
- `TryInputs` ← src/scorers/try-scorer.ts:22 [EXTRACTED]
  ```
  export interface TryInputs {
  ```
- `AgentSessionRef` ← src/session-flow/agent-session.ts:33 [EXTRACTED]
  ```
  export type AgentSessionRef = { platform: string; sessionId: string; cwd?: string; filePath?: string; storeDir?: string };
  ```
- `AgentSessionFailure` ← src/session-flow/agent-session.ts:35 [EXTRACTED]
  ```
  export type AgentSessionFailure =
  ```
- `AgentSessionCopy` ← src/session-flow/agent-session.ts:45 [EXTRACTED]
  ```
  export type AgentSessionCopy =
  ```
- `AgentSessionCopyRequest` ← src/session-flow/agent-session.ts:64 [EXTRACTED]
  ```
  export type AgentSessionCopyRequest = {
  ```
- `AgentSessionFindOptions` ← src/session-flow/agent-session.ts:74 [EXTRACTED]
  ```
  export type AgentSessionFindOptions = {
  ```
- `AgentSessionFound` ← src/session-flow/agent-session.ts:88 [EXTRACTED]
  ```
  export type AgentSessionFound =
  ```
- `AgentSessionTranscriptEntry` ← src/session-flow/agent-session.ts:101 [EXTRACTED]
  ```
  export type AgentSessionTranscriptEntry = {
  ```
- `AgentSessionListed` ← src/session-flow/agent-session.ts:111 [EXTRACTED]
  ```
  export type AgentSessionListed = AgentSessionRef &
  ```
- `AgentSessionListQuery` ← src/session-flow/agent-session.ts:114 [EXTRACTED]
  ```
  export type AgentSessionListQuery = {
  ```
- `AgentSessionList` ← src/session-flow/agent-session.ts:125 [EXTRACTED]
  ```
  export type AgentSessionList = {
  ```
- `AgentSession` ← src/session-flow/agent-session.ts:132 [EXTRACTED]
  ```
  export type AgentSession = {
  ```
- `ToolRootsLookup` ← src/session-flow/agent-session.ts:195 [EXTRACTED]
  ```
  export type ToolRootsLookup = (cwd: string | undefined) => Promise<ToolRoots>;
  ```
- `CopyWrite` ← src/session-flow/agent-session.ts:275 [EXTRACTED]
  ```
  export type CopyWrite =
  ```
- `ArchiveSessionRef` ← src/session-flow/archive.ts:29 [EXTRACTED]
  ```
  export type ArchiveSessionRef = { platform: string; sessionId: string; storeDir?: string; evidenceDir?: string };
  ```
- `ArchiveRestore` ← src/session-flow/archive.ts:31 [EXTRACTED]
  ```
  export type ArchiveRestore = { status: 'restored'; sessionId: string } | { status: 'fresh'; reason: string };
  ```
- `ArchiveDelivery` ← src/session-flow/archive.ts:33 [EXTRACTED]
  ```
  export type ArchiveDelivery<T extends ArchiveSessionRef = ArchiveSessionRef> =
  ```
- `SessionPush` ← src/session-flow/archive.ts:38 [EXTRACTED]
  ```
  export type SessionPush = { status: 'archived' } | { status: 'busy'; message: string } | { status: 'failed'; message: string };
  ```
- `SessionArchive` ← src/session-flow/archive.ts:41 [EXTRACTED]
  ```
  export type SessionArchive = {
  ```
- `SessionCapture` ← src/session-flow/captures.ts:48 [EXTRACTED]
  ```
  export type SessionCapture = z.infer<typeof SessionCaptureSchema>;
  ```
- `SessionEnd` ← src/session-flow/captures.ts:79 [EXTRACTED]
  ```
  export type SessionEnd = z.infer<typeof SessionEndSchema>;
  ```
- `CapturedSession` ← src/session-flow/captures.ts:397 [EXTRACTED]
  ```
  export interface CapturedSession {
  ```
- `FinishedSession` ← src/session-flow/finished-sessions.ts:42 [EXTRACTED]
  ```
  export interface FinishedSession {
  ```
- `ListOptions` ← src/session-flow/finished-sessions.ts:54 [EXTRACTED]
  ```
  export interface ListOptions {
  ```
- `ListContext` ← src/session-flow/finished-sessions.ts:62 [EXTRACTED]
  ```
  export interface ListContext {
  ```
- `Listed` ← src/session-flow/finished-sessions.ts:70 [EXTRACTED]
  ```
  export type Listed = { ok: true; list: FinishedSession[] } | Refusal;
  ```
- `ShareableSession` ← src/session-flow/finished-sessions.ts:73 [EXTRACTED]
  ```
  export interface ShareableSession {
  ```
- `ShareOptions` ← src/session-flow/finished-sessions.ts:81 [EXTRACTED]
  ```
  export interface ShareOptions extends ListOptions {
  ```
- `CandidateSession` ← src/session-flow/finished-sessions.ts:90 [EXTRACTED]
  ```
  export type CandidateSession = ShareableSession & TaskFields;
  ```
- `Shareable` ← src/session-flow/finished-sessions.ts:92 [EXTRACTED]
  ```
  export type Shareable =
  ```
- `RunHolder` ← src/session-flow/finished-sessions.ts:419 [EXTRACTED]
  ```
  export type RunHolder = { kind: 'driven' } | { kind: 'awaits'; driver: DriverName } | { kind: 'unassigned' };
  ```
- `FinishedStart` ← src/session-flow/finished-sessions.ts:425 [EXTRACTED]
  ```
  export type FinishedStart =
  ```
- `FidelityReport` ← src/session-flow/migrate.ts:18 [EXTRACTED]
  ```
  export interface FidelityReport {
  ```
- `MigrationPreview` ← src/session-flow/migrate.ts:151 [EXTRACTED]
  ```
  export interface MigrationPreview {
  ```
- `TeamSession` ← src/session-flow/scoring.ts:28 [EXTRACTED]
  ```
  export interface TeamSession {
  ```
- `SessionDemand` ← src/session-flow/scoring.ts:37 [EXTRACTED]
  ```
  export type SessionDemand = {
  ```
- `NamedSession` ← src/session-flow/scoring.ts:87 [EXTRACTED]
  ```
  export interface NamedSession {
  ```
- `ScrubResult` ← src/session-flow/scrub.ts:29 [EXTRACTED]
  ```
  export interface ScrubResult {
  ```
- `LocalPathRoots` ← src/session-flow/scrub.ts:41 [EXTRACTED]
  ```
  export interface LocalPathRoots {
  ```
- `SearchHit` ← src/session-flow/search.ts:18 [EXTRACTED]
  ```
  export interface SearchHit {
  ```
- `LoadedSession` ← src/session-flow/search.ts:189 [EXTRACTED]
  ```
  export interface LoadedSession {
  ```
- `ReportsArchive` ← src/session-flow/session-cmd-shared.ts:305 [EXTRACTED]
  ```
  export type ReportsArchive =
  ```
- `ArchivedEvidence` ← src/session-flow/session-evidence.ts:42 [EXTRACTED]
  ```
  export type ArchivedEvidence = z.infer<typeof ArchivedEvidenceSchema>;
  ```
- `EvidenceFile` ← src/session-flow/session-evidence.ts:44 [EXTRACTED]
  ```
  export type EvidenceFile = z.infer<typeof EvidenceFileSchema>;
  ```
- `SessionPolicy` ← src/session-flow/session-policy.ts:16 [EXTRACTED]
  ```
  export type SessionPolicy = typeof POLICIES[number];
  ```
- `PolicySource` ← src/session-flow/session-policy.ts:22 [EXTRACTED]
  ```
  export type PolicySource = { kind: 'default' } | { kind: 'setting'; key: string } | { kind: 'http-team' };
  ```
- `SessionPolicies` ← src/session-flow/session-policy.ts:42 [EXTRACTED]
  ```
  export type SessionPolicies = Record<RunMode, { policy: SessionPolicy; source: PolicySource }>;
  ```
- `StepSessionsPublished` ← src/session-flow/session-publish.ts:100 [EXTRACTED]
  ```
  export interface StepSessionsPublished {
  ```
- `JudgedTranscript` ← src/session-flow/session-work.ts:62 [EXTRACTED]
  ```
  export interface JudgedTranscript {
  ```
- `PromptOnlyRead` ← src/session-flow/session-work.ts:130 [EXTRACTED]
  ```
  export interface PromptOnlyRead {
  ```
- `StepEvidenceListing` ← src/session-flow/session-work.ts:156 [EXTRACTED]
  ```
  export type StepEvidenceListing = Omit<Extract<EvidenceFile, { kind: 'text' }>, 'text'> | Extract<EvidenceFile, { kind: 'listed' }>;
  ```
- `JudgedSession` ← src/session-flow/session-work.ts:159 [EXTRACTED]
  ```
  export interface JudgedSession {
  ```
- `SessionScorer` ← src/session-flow/session-work.ts:346 [EXTRACTED]
  ```
  export interface SessionScorer {
  ```
- `SessionCommits` ← src/session-flow/sync.ts:357 [EXTRACTED]
  ```
  export type SessionCommits = z.infer<typeof SessionCommitsSchema>;
  ```
- `SessionSyncMeta` ← src/session-flow/sync.ts:359 [EXTRACTED]
  ```
  export interface SessionSyncMeta {
  ```
- `IndexEntry` ← src/session-flow/sync.ts:500 [EXTRACTED]
  ```
  export interface IndexEntry {
  ```
- `SyncStatus` ← src/session-flow/sync.ts:580 [EXTRACTED]
  ```
  export interface SyncStatus {
  ```
- `ArchivedSessionRead` ← src/session-flow/sync.ts:587 [EXTRACTED]
  ```
  export interface ArchivedSessionRead {
  ```
- `GitCommitResult` ← src/session-flow/sync.ts:593 [EXTRACTED]
  ```
  export type GitCommitResult =
  ```
- `PullResult` ← src/session-flow/sync.ts:604 [EXTRACTED]
  ```
  export type PullResult =
  ```
- `PushResult` ← src/session-flow/sync.ts:610 [EXTRACTED]
  ```
  export type PushResult = { status: 'pushed' } | { status: 'indexes-conflicted'; indexes: string[] };
  ```
- `ArchiveWriteResult` ← src/session-flow/sync.ts:671 [EXTRACTED]
  ```
  export type ArchiveWriteResult<T> =
  ```
- `Size` ← src/session-flow/task-candidates.ts:21 [EXTRACTED]
  ```
  export type Size = Bounded | 'XL';
  ```
- `Sizes` ← src/session-flow/task-candidates.ts:24 [EXTRACTED]
  ```
  export type Sizes = Readonly<Record<Bounded, { lines: number; files: number }>>;
  ```
- `LeftOutReason` ← src/session-flow/task-candidates.ts:75 [EXTRACTED]
  ```
  export type LeftOutReason = (typeof LEFT_OUT)[keyof typeof LEFT_OUT];
  ```
- `LeftOut` ← src/session-flow/task-candidates.ts:78 [EXTRACTED]
  ```
  export interface LeftOut {
  ```
- `TaskFields` ← src/session-flow/task-candidates.ts:84 [EXTRACTED]
  ```
  export interface TaskFields {
  ```
- `Weighed` ← src/session-flow/task-candidates.ts:93 [EXTRACTED]
  ```
  export interface Weighed<T> {
  ```
- `TokenRates` ← src/token-usage/pricing.ts:9 [EXTRACTED]
  ```
  export type TokenRates = { input: number; output: number; cacheRead: number; cacheWrite: number; cacheWrite1h?: number };
  ```
- `TieredRates` ← src/token-usage/pricing.ts:12 [EXTRACTED]
  ```
  export type TieredRates = TokenRates & { above?: Array<TokenRates & { tokens: number }> };
  ```
- `ModelPrice` ← src/token-usage/pricing.ts:15 [EXTRACTED]
  ```
  export type ModelPrice = TieredRates & { fast?: TieredRates; flex?: TieredRates };
  ```
- `PriceCatalog` ← src/token-usage/pricing.ts:17 [EXTRACTED]
  ```
  export type PriceCatalog = { version: string; source: string; models: Record<string, ModelPrice> };
  ```
- `PricedTokens` ← src/token-usage/pricing.ts:26 [EXTRACTED]
  ```
  export type PricedTokens =
  ```
- `BranchWorktreeSpec` ← src/utils/branch-worktree.ts:47 [EXTRACTED]
  ```
  export interface BranchWorktreeSpec {
  ```
- `PublishResult` ← src/utils/branch-worktree.ts:66 [EXTRACTED]
  ```
  export type PublishResult =
  ```
- `EnsureWorktreeOptions` ← src/utils/branch-worktree.ts:216 [EXTRACTED]
  ```
  export interface EnsureWorktreeOptions {
  ```
- `BranchWrite` ← src/utils/branch-worktree.ts:863 [EXTRACTED]
  ```
  export interface BranchWrite {
  ```
- `BranchPushOptions` ← src/utils/branch-worktree.ts:869 [EXTRACTED]
  ```
  export interface BranchPushOptions {
  ```
- `BranchWriteContext` ← src/utils/branch-worktree.ts:1016 [EXTRACTED]
  ```
  export interface BranchWriteContext {
  ```
- `RefreshResult` ← src/utils/branch-worktree.ts:1535 [EXTRACTED]
  ```
  export type RefreshResult =
  ```
- `BranchWorktree` ← src/utils/branch-worktree.ts:1542 [EXTRACTED]
  ```
  export interface BranchWorktree {
  ```
- `FrontmatterValue` ← src/utils/frontmatter.ts:16 [EXTRACTED]
  ```
  export type FrontmatterValue = string | number | boolean | null | Date | Uint8Array | FrontmatterValue[] | FrontmatterData;
  ```
- `FrontmatterData` ← src/utils/frontmatter.ts:19 [EXTRACTED]
  ```
  export interface FrontmatterData {
  ```
- `FrontmatterSplit` ← src/utils/frontmatter.ts:24 [EXTRACTED]
  ```
  export interface FrontmatterSplit {
  ```
- `RefusedWrite` ← src/utils/fs.ts:130 [EXTRACTED]
  ```
  export interface RefusedWrite {
  ```
- `JsonObjectRead` ← src/utils/fs.ts:321 [EXTRACTED]
  ```
  export type JsonObjectRead =
  ```
- `GeneratedFileState` ← src/utils/fs.ts:720 [EXTRACTED]
  ```
  export type GeneratedFileState = 'absent' | 'teamai' | 'foreign';
  ```
- `GitAnswers` ← src/utils/git-answers.ts:17 [EXTRACTED]
  ```
  export interface GitAnswers<T> {
  ```
- `RefTip` ← src/utils/git-ref-files.ts:6 [EXTRACTED]
  ```
  export interface RefTip {
  ```
- `MrPush` ← src/utils/git.ts:1077 [EXTRACTED]
  ```
  export type MrPush = { pushed: false } | { pushed: true; prUrl: string | null };
  ```
- `RepoAnchors` ← src/utils/git.ts:1785 [EXTRACTED]
  ```
  export interface RepoAnchors {
  ```
- `WorktreeListEntry` ← src/utils/git.ts:1880 [EXTRACTED]
  ```
  export interface WorktreeListEntry {
  ```
- `CheckoutLocation` ← src/utils/git.ts:1910 [EXTRACTED]
  ```
  export interface CheckoutLocation {
  ```
- `HeadState` ← src/utils/git.ts:2314 [EXTRACTED]
  ```
  export type HeadState = { head: string; dirty: boolean };
  ```
- `GitTreeEntry` ← src/utils/git.ts:2368 [EXTRACTED]
  ```
  export interface GitTreeEntry {
  ```
- `IWikiPage` ← src/utils/iwiki-client.ts:33 [EXTRACTED]
  ```
  export interface IWikiPage {
  ```
- `IWikiDocument` ← src/utils/iwiki-client.ts:47 [EXTRACTED]
  ```
  export interface IWikiDocument {
  ```
- `LockWait` ← src/utils/jsonl-store.ts:30 [EXTRACTED]
  ```
  export interface LockWait {
  ```
- `JsonlStoreOptions` ← src/utils/jsonl-store.ts:41 [EXTRACTED]
  ```
  export interface JsonlStoreOptions {
  ```
- `PublishQueueReport` ← src/utils/learnings-publish.ts:33 [EXTRACTED]
  ```
  export interface PublishQueueReport {
  ```
- `LearningsRoots` ← src/utils/learnings-roots.ts:25 [EXTRACTED]
  ```
  export interface LearningsRoots {
  ```
- `LearningFile` ← src/utils/learnings-roots.ts:176 [EXTRACTED]
  ```
  export interface LearningFile {
  ```
- `LearningsTreeVisitor` ← src/utils/learnings-roots.ts:192 [EXTRACTED]
  ```
  export interface LearningsTreeVisitor<T> {
  ```
- `StaleWorkspace` ← src/utils/partition.ts:494 [EXTRACTED]
  ```
  export interface StaleWorkspace {
  ```
- `QueueWrite` ← src/utils/pending-learnings.ts:146 [EXTRACTED]
  ```
  export type QueueWrite =
  ```
- `QueueOwner` ← src/utils/pending-learnings.ts:308 [EXTRACTED]
  ```
  export type QueueOwner = { kind: string; remote: string };
  ```
- `PushGroup` ← src/utils/pending-push.ts:151 [EXTRACTED]
  ```
  export interface PushGroup {
  ```
- `EnsureReportsWorktreeOptions` ← src/utils/reports-branch.ts:52 [EXTRACTED]
  ```
  export type EnsureReportsWorktreeOptions = EnsureWorktreeOptions;
  ```
- `ReportsWrite` ← src/utils/reports-branch.ts:54 [EXTRACTED]
  ```
  export type ReportsWrite = BranchWrite;
  ```
- `ReportsWriteContext` ← src/utils/reports-branch.ts:56 [EXTRACTED]
  ```
  export type ReportsWriteContext = BranchWriteContext;
  ```
- `ReportsPublishResult` ← src/utils/reports-branch.ts:58 [EXTRACTED]
  ```
  export type ReportsPublishResult = PublishResult;
  ```
- `ReportsOriginRead` ← src/utils/reports-branch.ts:188 [EXTRACTED]
  ```
  export type ReportsOriginRead =
  ```
- `ReportsChange` ← src/utils/reports-branch.ts:234 [EXTRACTED]
  ```
  export interface ReportsChange<T> {
  ```
- `EnvAgentSession` ← src/utils/session-id.ts:71 [EXTRACTED]
  ```
  export interface EnvAgentSession {
  ```
- `DeriveSessionIdOptions` ← src/utils/session-id.ts:123 [EXTRACTED]
  ```
  export interface DeriveSessionIdOptions {
  ```
- `ShellOperator` ← src/utils/shell-command.ts:15 [EXTRACTED]
  ```
  export type ShellOperator = ';' | '&&' | '||' | '|' | '&';
  ```
- `Redirect` ← src/utils/shell-command.ts:17 [EXTRACTED]
  ```
  export interface Redirect {
  ```
- `SimpleCommand` ← src/utils/shell-command.ts:24 [EXTRACTED]
  ```
  export interface SimpleCommand {
  ```
- `ShellClassification` ← src/utils/shell-command.ts:33 [EXTRACTED]
  ```
  export interface ShellClassification {
  ```
- `ShellFlavor` ← src/utils/shell-command.ts:323 [EXTRACTED]
  ```
  export interface ShellFlavor {
  ```
- `EnvBlock` ← src/utils/shell-profile.ts:253 [EXTRACTED]
  ```
  export interface EnvBlock {
  ```
- `TagFilterResult` ← src/utils/tags.ts:34 [EXTRACTED]
  ```
  export interface TagFilterResult {
  ```
- `TeamCodebasePaths` ← src/utils/team-codebase-paths.ts:8 [EXTRACTED]
  ```
  export interface TeamCodebasePaths {
  ```
- `HistoricalVersion` ← src/utils/team-history.ts:20 [EXTRACTED]
  ```
  export interface HistoricalVersion {
  ```
- `HistoryRender` ← src/utils/team-history.ts:157 [EXTRACTED]
  ```
  export type HistoryRender = (content: Buffer, version: HistoricalVersion) => string | Uint8Array | null;
  ```
- `ReachableRevision` ← src/utils/team-revision.ts:10 [EXTRACTED]
  ```
  export interface ReachableRevision {
  ```
- `TeamwikiTarget` ← src/utils/teamwiki-root.ts:16 [EXTRACTED]
  ```
  export interface TeamwikiTarget {
  ```
- `ToolCategory` ← src/utils/tool-call.ts:29 [EXTRACTED]
  ```
  export type ToolCategory = 'read' | 'shell' | 'search' | 'list' | 'unknown';
  ```
- `ToolStatus` ← src/utils/tool-call.ts:31 [EXTRACTED]
  ```
  export type ToolStatus = 'success' | 'failure' | 'unknown';
  ```
- `ToolCall` ← src/utils/tool-call.ts:33 [EXTRACTED]
  ```
  export interface ToolCall {
  ```
- `CodexToolId` ← src/utils/tool-names.ts:54 [EXTRACTED]
  ```
  export type CodexToolId = { [T in ToolId]: DescriptorOf<T>['launch'] extends 'codex' ? T : never }[ToolId];
  ```
- `CallChainLayer` ← src/wiki-engine/call-chain-tracer.ts:4 [EXTRACTED]
  ```
  export type CallChainLayer = "entry" | "orchestration" | "service" | "data";
  ```
- `CallChainStep` ← src/wiki-engine/call-chain-tracer.ts:6 [EXTRACTED]
  ```
  export interface CallChainStep {
  ```
- `CallChain` ← src/wiki-engine/call-chain-tracer.ts:14 [EXTRACTED]
  ```
  export interface CallChain {
  ```
- `InterfaceType` ← src/wiki-engine/interface-scanner.ts:5 [EXTRACTED]
  ```
  export type InterfaceType = "HTTP" | "MQ" | "RPC" | "NONE";
  ```
- `InterfaceInventoryEntry` ← src/wiki-engine/interface-scanner.ts:7 [EXTRACTED]
  ```
  export interface InterfaceInventoryEntry {
  ```
- `InterfaceInventory` ← src/wiki-engine/interface-scanner.ts:15 [EXTRACTED]
  ```
  export interface InterfaceInventory {
  ```
- `ReconcileOptions` ← src/wiki-engine/knowledge-reconciler.ts:31 [EXTRACTED]
  ```
  export interface ReconcileOptions {
  ```
- `ReconcileGraphEdge` ← src/wiki-engine/knowledge-reconciler.ts:44 [EXTRACTED]
  ```
  export interface ReconcileGraphEdge {
  ```
- `ReconcileGap` ← src/wiki-engine/knowledge-reconciler.ts:53 [EXTRACTED]
  ```
  export interface ReconcileGap {
  ```
- `ReconcileConflict` ← src/wiki-engine/knowledge-reconciler.ts:59 [EXTRACTED]
  ```
  export interface ReconcileConflict {
  ```
- `ReconcileResult` ← src/wiki-engine/knowledge-reconciler.ts:66 [EXTRACTED]
  ```
  export interface ReconcileResult {
  ```
- `RelationCandidate` ← src/wiki-engine/knowledge-reconciler.ts:85 [EXTRACTED]
  ```
  export interface RelationCandidate {
  ```
- `ManifestConfidence` ← src/wiki-engine/manifest-schema.ts:25 [EXTRACTED]
  ```
  export type ManifestConfidence = "EXTRACTED" | "INFERRED" | "AMBIGUOUS";
  ```
- `ManifestEdgeSource` ← src/wiki-engine/manifest-schema.ts:28 [EXTRACTED]
  ```
  export type ManifestEdgeSource =
  ```
- `CodebaseOutputManifestV1` ← src/wiki-engine/manifest-schema.ts:57 [EXTRACTED]
  ```
  export interface CodebaseOutputManifestV1 {
  ```
- `ManifestComponentV2` ← src/wiki-engine/manifest-schema.ts:66 [EXTRACTED]
  ```
  export interface ManifestComponentV2 extends ManifestComponentBase {
  ```
- `ManifestEdgeV2` ← src/wiki-engine/manifest-schema.ts:71 [EXTRACTED]
  ```
  export interface ManifestEdgeV2 extends ManifestEdgeBase {
  ```
- `CodebaseOutputManifestV2` ← src/wiki-engine/manifest-schema.ts:78 [EXTRACTED]
  ```
  export interface CodebaseOutputManifestV2 {
  ```
- `CodebaseOutputManifest` ← src/wiki-engine/manifest-schema.ts:87 [EXTRACTED]
  ```
  export type CodebaseOutputManifest = CodebaseOutputManifestV1 | CodebaseOutputManifestV2;
  ```
- `ConfidenceFactor` ← src/wiki-engine/reconciler-v2-types.ts:5 [EXTRACTED]
  ```
  export interface ConfidenceFactor {
  ```
- `NumericConfidence` ← src/wiki-engine/reconciler-v2-types.ts:11 [EXTRACTED]
  ```
  export interface NumericConfidence {
  ```
- `ApiInterfaceMatch` ← src/wiki-engine/reconciler-v2-types.ts:36 [EXTRACTED]
  ```
  export interface ApiInterfaceMatch {
  ```
- `RuleCodeMatch` ← src/wiki-engine/reconciler-v2-types.ts:46 [EXTRACTED]
  ```
  export interface RuleCodeMatch {
  ```
- `ReconcileStaleWarning` ← src/wiki-engine/reconciler-v2-types.ts:55 [EXTRACTED]
  ```
  export interface ReconcileStaleWarning {
  ```
- `ReconcileLogEntry` ← src/wiki-engine/reconciler-v2-types.ts:66 [EXTRACTED]
  ```
  export interface ReconcileLogEntry {
  ```
- `ReconcileStats` ← src/wiki-engine/reconciler-v2-types.ts:82 [EXTRACTED]
  ```
  export interface ReconcileStats {
  ```
- `ReconcileV2Extensions` ← src/wiki-engine/reconciler-v2-types.ts:97 [EXTRACTED]
  ```
  export interface ReconcileV2Extensions {
  ```
- `Admitted` ← src/workflow/admission.ts:20 [EXTRACTED]
  ```
  export interface Admitted {
  ```
- `Candidate` ← src/workflow/admission.ts:29 [EXTRACTED]
  ```
  export type Candidate =
  ```
- `MarkedAttempt` ← src/workflow/attempt-marker.ts:14 [EXTRACTED]
  ```
  export type MarkedAttempt = z.output<typeof MarkedAttemptSchema>;
  ```
- `AgentEvidence` ← src/workflow/attempt-marker.ts:65 [EXTRACTED]
  ```
  export type AgentEvidence =
  ```
- `Nested` ← src/workflow/attempt-marker.ts:108 [EXTRACTED]
  ```
  export type Nested =
  ```
- `AttemptResultBody` ← src/workflow/attempt-result.ts:15 [EXTRACTED]
  ```
  export type AttemptResultBody = { output?: unknown; failure?: WorkflowFailure } | { raw: string };
  ```
- `SyncWorkflowOptions` ← src/workflow/cache.ts:41 [EXTRACTED]
  ```
  export interface SyncWorkflowOptions {
  ```
- `SyncWorkflowResult` ← src/workflow/cache.ts:46 [EXTRACTED]
  ```
  export interface SyncWorkflowResult {
  ```
- `WorkflowRun` ← src/workflow/cache.ts:760 [EXTRACTED]
  ```
  export interface WorkflowRun {
  ```
- `PinnedFolder` ← src/workflow/cache.ts:767 [EXTRACTED]
  ```
  export interface PinnedFolder {
  ```
- `WorkflowTree` ← src/workflow/cache.ts:773 [EXTRACTED]
  ```
  export interface WorkflowTree {
  ```
- `WorkflowBundle` ← src/workflow/cache.ts:949 [EXTRACTED]
  ```
  export interface WorkflowBundle {
  ```
- `TeamCommitReach` ← src/workflow/cache.ts:999 [EXTRACTED]
  ```
  export type TeamCommitReach =
  ```
- `TeamSelection` ← src/workflow/clone.ts:21 [EXTRACTED]
  ```
  export type TeamSelection = z.infer<typeof TeamSelectionSchema>;
  ```
- `CloneTeam` ← src/workflow/clone.ts:52 [EXTRACTED]
  ```
  export type CloneTeam = z.infer<typeof CloneTeamSchema>;
  ```
- `InstalledTeam` ← src/workflow/clone.ts:55 [EXTRACTED]
  ```
  export type InstalledTeam = Extract<CloneTeam, { revision: string }>;
  ```
- `ClonePlace` ← src/workflow/clone.ts:70 [EXTRACTED]
  ```
  export type ClonePlace = z.infer<typeof ClonePlaceSchema>;
  ```
- `ConfinedToolLevel` ← src/workflow/confined-launch.ts:67 [EXTRACTED]
  ```
  export interface ConfinedToolLevel {
  ```
- `ConfinedOffer` ← src/workflow/confined-launch.ts:96 [EXTRACTED]
  ```
  export interface ConfinedOffer {
  ```
- `ConfinedInput` ← src/workflow/confined-launch.ts:124 [EXTRACTED]
  ```
  export type ConfinedInput = Pick<ConfinedRequest, 'model' | 'dir' | 'prompt' | 'schema' | 'level' | 'timeoutMs' | 'group' | 'attempt' | 'signal'> & { tool: ConfinedTool };
  ```
- `ConfinedRun` ← src/workflow/confined-launch.ts:127 [EXTRACTED]
  ```
  export interface ConfinedRun {
  ```
- `ConfinedResult` ← src/workflow/confined-launch.ts:136 [EXTRACTED]
  ```
  export type ConfinedResult = { ok: true; reply: JsonValue; run: ConfinedRun } | ConfinedFailure;
  ```
- `ConfinedFile` ← src/workflow/confined-place.ts:33 [EXTRACTED]
  ```
  export type ConfinedFile = z.infer<typeof ConfinedFileSchema>;
  ```
- `ConfinedDir` ← src/workflow/confined-place.ts:40 [EXTRACTED]
  ```
  export type ConfinedDir = ConfinedFile & { dir: string };
  ```
- `ConfinedDirCheck` ← src/workflow/confined-place.ts:42 [EXTRACTED]
  ```
  export type ConfinedDirCheck = { ok: true; place: ConfinedDir } | { ok: false; failure: WorkflowFailure };
  ```
- `ConfinedDecision` ← src/workflow/confined-place.ts:161 [EXTRACTED]
  ```
  export type ConfinedDecision =
  ```
- `ConfinedRequest` ← src/workflow/confined-place.ts:166 [EXTRACTED]
  ```
  export interface ConfinedRequest {
  ```
- `ConfinedStepReport` ← src/workflow/confined-step.ts:29 [EXTRACTED]
  ```
  export type ConfinedStepReport = Pick<ReportInput, 'outcome' | 'outputs' | 'tool' | 'model' | 'tokens' | 'cost' | 'durationMs' | 'confined' | 'message' | 'failure'>;
  ```
- `ConfinedStepEnd` ← src/workflow/confined-step.ts:35 [EXTRACTED]
  ```
  export type ConfinedStepEnd = { kind: 'ran'; report: ConfinedStepReport } | { kind: 'unresolved'; reason: string };
  ```
- `ConfinedStepLease` ← src/workflow/confined-step.ts:38 [EXTRACTED]
  ```
  export type ConfinedStepLease = Pick<LeaseWire, 'attempt' | 'step' | 'prompt' | 'model' | 'defaultModel' | 'expiresAt' | 'limits'> & { confined: ConfinedLease };
  ```
- `ConfinedStepInput` ← src/workflow/confined-step.ts:40 [EXTRACTED]
  ```
  export interface ConfinedStepInput {
  ```
- `RuntimeConfinedInput` ← src/workflow/confined-step.ts:195 [EXTRACTED]
  ```
  export interface RuntimeConfinedInput extends Omit<ConfinedStepInput, 'resolveTool'> {
  ```
- `ScenarioJson` ← src/workflow/conformance-interpreter.ts:38 [EXTRACTED]
  ```
  export type ScenarioJson = { [key: string]: JsonValue };
  ```
- `BenchmarkSuiteFiles` ← src/workflow/conformance-interpreter.ts:57 [EXTRACTED]
  ```
  export interface BenchmarkSuiteFiles {
  ```
- `ConformanceRefusal` ← src/workflow/conformance-interpreter.ts:84 [EXTRACTED]
  ```
  export interface ConformanceRefusal {
  ```
- `WorkflowScenario` ← src/workflow/conformance-interpreter.ts:94 [EXTRACTED]
  ```
  export interface WorkflowScenario extends ScenarioBase {
  ```
- `BenchmarkScenario` ← src/workflow/conformance-interpreter.ts:105 [EXTRACTED]
  ```
  export interface BenchmarkScenario extends ScenarioBase {
  ```
- `ConformanceScenario` ← src/workflow/conformance-interpreter.ts:109 [EXTRACTED]
  ```
  export type ConformanceScenario = WorkflowScenario | BenchmarkScenario;
  ```
- `DriverProfile` ← src/workflow/conformance-interpreter.ts:163 [EXTRACTED]
  ```
  export type DriverProfile = keyof typeof DRIVER_PROFILES;
  ```
- `ConformanceOperation` ← src/workflow/conformance-interpreter.ts:196 [EXTRACTED]
  ```
  export type ConformanceOperation =
  ```
- `ConformanceExpect` ← src/workflow/conformance-interpreter.ts:262 [EXTRACTED]
  ```
  export type ConformanceExpect = <TActual>(actual: TActual, message?: string) => {
  ```
- `StartDriver` ← src/workflow/conformance-interpreter.ts:269 [EXTRACTED]
  ```
  export type StartDriver = 'local' | 'skill';
  ```
- `ConformanceClient` ← src/workflow/conformance-interpreter.ts:275 [EXTRACTED]
  ```
  export type ConformanceClient = Pick<WorkflowClient, 'next' | 'report' | 'retry' | 'cancel'> & {
  ```
- `ConformanceRunner` ← src/workflow/conformance-interpreter.ts:314 [EXTRACTED]
  ```
  export interface ConformanceRunner {
  ```
- `TeamCheckout` ← src/workflow/delivery-ledger.ts:31 [EXTRACTED]
  ```
  export type TeamCheckout = { checkout: string; target: string };
  ```
- `DeliveryApplied` ← src/workflow/delivery-ledger.ts:110 [EXTRACTED]
  ```
  export interface DeliveryApplied {
  ```
- `DeliveryReceipt` ← src/workflow/delivery-schema.ts:17 [EXTRACTED]
  ```
  export type DeliveryReceipt = z.infer<typeof DeliveryReceiptSchema>;
  ```
- `DeliveryKey` ← src/workflow/delivery-schema.ts:24 [EXTRACTED]
  ```
  export type DeliveryKey = z.infer<typeof DeliveryKeySchema>;
  ```
- `UnresolvedCreate` ← src/workflow/delivery-schema.ts:32 [EXTRACTED]
  ```
  export type UnresolvedCreate = z.infer<typeof UnresolvedCreateSchema>;
  ```
- `LocalRoute` ← src/workflow/describe.ts:13 [EXTRACTED]
  ```
  export type LocalRoute = { held: string; missing: 'env' | 'tokens' } & ({ copy: 'run' } | { copy: 'step'; opener: string });
  ```
- `GateGuards` ← src/workflow/describe.ts:16 [EXTRACTED]
  ```
  export type GateGuards =
  ```
- `WorkflowDescription` ← src/workflow/describe.ts:70 [EXTRACTED]
  ```
  export interface WorkflowDescription {
  ```
- `DriverName` ← src/workflow/driver-name.ts:13 [EXTRACTED]
  ```
  export type DriverName = z.infer<typeof DriverNameSchema>;
  ```
- `Driver` ← src/workflow/driver-name.ts:28 [EXTRACTED]
  ```
  export type Driver = typeof RESERVED_DRIVERS.local | typeof RESERVED_DRIVERS.skill | typeof RESERVED_DRIVERS.none | { external: DriverName };
  ```
- `ReportInput` ← src/workflow/engine.ts:97 [EXTRACTED]
  ```
  export interface ReportInput {
  ```
- `PersonHandoff` ← src/workflow/engine.ts:403 [EXTRACTED]
  ```
  export type PersonHandoff = { kind: 'offers' } | { kind: 'unoffered'; reason: string };
  ```
- `PersonStep` ← src/workflow/engine.ts:470 [EXTRACTED]
  ```
  export type PersonStep = { step: string; kind: StepHitl['kind'] | 'interactive' };
  ```
- `WorkflowResult` ← src/workflow/engine.ts:633 [EXTRACTED]
  ```
  export interface WorkflowResult {
  ```
- `Finished` ← src/workflow/engine.ts:689 [EXTRACTED]
  ```
  export type Finished = { kind: 'finalizing' } | { kind: 'settled'; queued: boolean };
  ```
- `RunData` ← src/workflow/engine.ts:722 [EXTRACTED]
  ```
  export type RunData = Pick<RunState, 'id' | 'status' | 'revision' | 'end' | 'failure' | 'finalizing'>;
  ```
- `RunReads` ← src/workflow/engine.ts:832 [EXTRACTED]
  ```
  export interface RunReads {
  ```
- `ToolFor` ← src/workflow/engine.ts:1682 [EXTRACTED]
  ```
  export type ToolFor = (step: Pick<WorkflowStep, 'agent' | 'tool'>) => string | undefined;
  ```
- `SoleDriver` ← src/workflow/engine.ts:1870 [EXTRACTED]
  ```
  export interface SoleDriver {
  ```
- `RuntimeOffer` ← src/workflow/engine.ts:1877 [EXTRACTED]
  ```
  export interface RuntimeOffer {
  ```
- `NextOptions` ← src/workflow/engine.ts:2175 [EXTRACTED]
  ```
  export interface NextOptions {
  ```
- `ParsedResponsePayload` ← src/workflow/engine.ts:2909 [EXTRACTED]
  ```
  export interface ParsedResponsePayload {
  ```
- `ParsedReport` ← src/workflow/engine.ts:2935 [EXTRACTED]
  ```
  export interface ParsedReport {
  ```
- `ParsedNextPayload` ← src/workflow/engine.ts:2952 [EXTRACTED]
  ```
  export interface ParsedNextPayload {
  ```
- `NextRequest` ← src/workflow/engine.ts:3134 [EXTRACTED]
  ```
  export interface NextRequest extends NextOptions {
  ```
- `EphemeralScope` ← src/workflow/ephemeral-scope.ts:16 [EXTRACTED]
  ```
  export type EphemeralScope = { config: LocalConfig; teamConfig: TeamaiConfig; close: () => Promise<void> };
  ```
- `PathField` ← src/workflow/expression.ts:13 [EXTRACTED]
  ```
  export type PathField = string | number;
  ```
- `JsonType` ← src/workflow/expression.ts:21 [EXTRACTED]
  ```
  export type JsonType = 'string' | 'number' | 'boolean' | 'null' | 'array' | 'object';
  ```
- `ExpressionPath` ← src/workflow/expression.ts:40 [EXTRACTED]
  ```
  export type ExpressionPath =
  ```
- `Expression` ← src/workflow/expression.ts:76 [EXTRACTED]
  ```
  export type Expression =
  ```
- `ExpressionStep` ← src/workflow/expression.ts:103 [EXTRACTED]
  ```
  export interface ExpressionStep {
  ```
- `ExpressionPass` ← src/workflow/expression.ts:123 [EXTRACTED]
  ```
  export interface ExpressionPass {
  ```
- `ExpressionContext` ← src/workflow/expression.ts:136 [EXTRACTED]
  ```
  export interface ExpressionContext {
  ```
- `ExpressionParse` ← src/workflow/expression.ts:147 [EXTRACTED]
  ```
  export type ExpressionParse =
  ```
- `DeclaredType` ← src/workflow/expression.ts:325 [EXTRACTED]
  ```
  export type DeclaredType =
  ```
- `TypeProblem` ← src/workflow/expression.ts:560 [EXTRACTED]
  ```
  export interface TypeProblem {
  ```
- `SchemaOf` ← src/workflow/expression.ts:591 [EXTRACTED]
  ```
  export type SchemaOf = (path: ExpressionPath) => DeclaredType | undefined;
  ```
- `FailureCode` ← src/workflow/failure-codes.ts:112 [EXTRACTED]
  ```
  export type FailureCode = (typeof FAILURE_CODES)[number];
  ```
- `SettledItems` ← src/workflow/fan-out.ts:173 [EXTRACTED]
  ```
  export interface SettledItems {
  ```
- `WorkflowFolderFile` ← src/workflow/folder.ts:28 [EXTRACTED]
  ```
  export interface WorkflowFolderFile {
  ```
- `WorkflowFolderRead` ← src/workflow/folder.ts:35 [EXTRACTED]
  ```
  export type WorkflowFolderRead =
  ```
- `HandoffError` ← src/workflow/handoff.ts:41 [EXTRACTED]
  ```
  export type HandoffError =
  ```
- `Result` ← src/workflow/handoff.ts:71 [EXTRACTED]
  ```
  export type Result<T> = { ok: true; value: T } | Refusal;
  ```
- `InFlightLease` ← src/workflow/handoff.ts:74 [EXTRACTED]
  ```
  export interface InFlightLease {
  ```
- `PublishReceipt` ← src/workflow/handoff.ts:80 [EXTRACTED]
  ```
  export interface PublishReceipt {
  ```
- `ClaimReceipt` ← src/workflow/handoff.ts:93 [EXTRACTED]
  ```
  export interface ClaimReceipt {
  ```
- `Definitions` ← src/workflow/handoff.ts:870 [EXTRACTED]
  ```
  export interface Definitions {
  ```
- `Takeover` ← src/workflow/handoff.ts:910 [EXTRACTED]
  ```
  export type Takeover = 'confirmed' | 'attended' | 'unattended';
  ```
- `CarriedRun` ← src/workflow/handoff.ts:1104 [EXTRACTED]
  ```
  export interface CarriedRun extends Pick<Definitions, 'definition' | 'workflows'> {
  ```
- `ScorablePass` ← src/workflow/judge-work.ts:13 [EXTRACTED]
  ```
  export interface ScorablePass {
  ```
- `KeptValue` ← src/workflow/kept-setting.ts:12 [EXTRACTED]
  ```
  export type KeptValue<T> = { ok: true; value: T } | { ok: false; warning: string };
  ```
- `ConfinedLease` ← src/workflow/lease-wire.ts:19 [EXTRACTED]
  ```
  export type ConfinedLease = z.infer<typeof ConfinedLeaseSchema>;
  ```
- `LeaseWire` ← src/workflow/lease-wire.ts:71 [EXTRACTED]
  ```
  export type LeaseWire = z.infer<typeof LeaseWireSchema>;
  ```
- `SettledBranches` ← src/workflow/leftovers.ts:351 [EXTRACTED]
  ```
  export type SettledBranches =
  ```
- `SweptRun` ← src/workflow/leftovers.ts:372 [EXTRACTED]
  ```
  export interface SweptRun {
  ```
- `Sweep` ← src/workflow/leftovers.ts:383 [EXTRACTED]
  ```
  export interface Sweep {
  ```
- `StartLimits` ← src/workflow/limits.ts:130 [EXTRACTED]
  ```
  export interface StartLimits {
  ```
- `Allowance` ← src/workflow/limits.ts:206 [EXTRACTED]
  ```
  export interface Allowance {
  ```
- `StepLoops` ← src/workflow/loop.ts:13 [EXTRACTED]
  ```
  export interface StepLoops {
  ```
- `LoopProblem` ← src/workflow/loop.ts:26 [EXTRACTED]
  ```
  export interface LoopProblem {
  ```
- `RunPass` ← src/workflow/loop.ts:317 [EXTRACTED]
  ```
  export type RunPass = StepPass & { step: string; within?: { step: string; pass: number } };
  ```
- `MemberToolSource` ← src/workflow/member-tools.ts:7 [EXTRACTED]
  ```
  export type MemberToolSource = 'TEAMAI_AI_TOOL' | 'ai.tool (project)' | 'ai.tool (machine)';
  ```
- `MemberTool` ← src/workflow/member-tools.ts:10 [EXTRACTED]
  ```
  export interface MemberTool {
  ```
- `CallErrorKind` ← src/workflow/member-tools.ts:39 [EXTRACTED]
  ```
  export type CallErrorKind = 'no_tool' | 'override_invalid' | 'tool_not_accepted' | 'home_gone' | 'usage_limited' | 'call_failed';
  ```
- `ParseContext` ← src/workflow/parse-context.ts:50 [EXTRACTED]
  ```
  export interface ParseContext {
  ```
- `WorkflowFiles` ← src/workflow/parse-context.ts:59 [EXTRACTED]
  ```
  export interface WorkflowFiles {
  ```
- `Child` ← src/workflow/parse-context.ts:77 [EXTRACTED]
  ```
  export interface Child {
  ```
- `GraphNode` ← src/workflow/parse-context.ts:147 [EXTRACTED]
  ```
  export interface GraphNode {
  ```
- `Position` ← src/workflow/parse-context.ts:155 [EXTRACTED]
  ```
  export interface Position {
  ```
- `StepAttempt` ← src/workflow/part-of-step.ts:66 [EXTRACTED]
  ```
  export type StepAttempt = { kind: 'running' } | { kind: 'ended'; failure: WorkflowFailure };
  ```
- `DeliveryJob` ← src/workflow/pr-delivery.ts:17 [EXTRACTED]
  ```
  export interface DeliveryJob {
  ```
- `DeliveryFault` ← src/workflow/pr-delivery.ts:38 [EXTRACTED]
  ```
  export type DeliveryFault =
  ```
- `DeliveryOutcome` ← src/workflow/pr-delivery.ts:60 [EXTRACTED]
  ```
  export type DeliveryOutcome = { ok: true; pr: PrUrl } | { ok: false; fault: DeliveryFault };
  ```
- `CreateGate` ← src/workflow/pr-delivery.ts:68 [EXTRACTED]
  ```
  export type CreateGate = () => Promise<'open' | 'refused' | 'busy'>;
  ```
- `PrUrl` ← src/workflow/pr-url.ts:21 [EXTRACTED]
  ```
  export type PrUrl = z.infer<typeof PrUrlSchema>;
  ```
- `StartedRun` ← src/workflow/protocol.ts:46 [EXTRACTED]
  ```
  export type StartedRun = z.infer<typeof StartedRunSchema>;
  ```
- `RespondVia` ← src/workflow/protocol.ts:52 [EXTRACTED]
  ```
  export type RespondVia =
  ```
- `RunVersion` ← src/workflow/protocol.ts:62 [EXTRACTED]
  ```
  export interface RunVersion {
  ```
- `WorkflowClient` ← src/workflow/protocol.ts:74 [EXTRACTED]
  ```
  export interface WorkflowClient {
  ```
- `ResumeClaim` ← src/workflow/protocol.ts:170 [EXTRACTED]
  ```
  export type ResumeClaim = 'lacking' | 'any' | 'offered';
  ```
- `CarriedRunView` ← src/workflow/protocol.ts:191 [EXTRACTED]
  ```
  export type CarriedRunView =
  ```
- `RunReadied` ← src/workflow/protocol.ts:201 [EXTRACTED]
  ```
  export type RunReadied =
  ```
- `InvokeCaller` ← src/workflow/protocol.ts:212 [EXTRACTED]
  ```
  export interface InvokeCaller {
  ```
- `InvokeAct` ← src/workflow/protocol.ts:224 [EXTRACTED]
  ```
  export type InvokeAct = { kind: 'start'; instead?: string; from?: { place: string; driver: string } } | { kind: 'continue'; run: RunId } | { kind: 'claim'; run: RunId };
  ```
- `DescribedWorkflow` ← src/workflow/protocol.ts:402 [EXTRACTED]
  ```
  export type DescribedWorkflow = { description: WorkflowDescription; judging: Judging; undeliverable?: WorkflowFailure };
  ```
- `Judging` ← src/workflow/protocol.ts:404 [EXTRACTED]
  ```
  export type Judging =
  ```
- `SessionHostPlaceRequest` ← src/workflow/protocol.ts:458 [EXTRACTED]
  ```
  export type SessionHostPlaceRequest = { kind: 'host' } | { kind: 'adopt'; dir: string };
  ```
- `SessionHostPlacePrepared` ← src/workflow/protocol.ts:467 [EXTRACTED]
  ```
  export type SessionHostPlacePrepared =
  ```
- `NextPrepare` ← src/workflow/protocol.ts:639 [EXTRACTED]
  ```
  export type NextPrepare = true | { attempt: AttemptId; adopt?: string };
  ```
- `CommandEnd` ← src/workflow/protocol.ts:1107 [EXTRACTED]
  ```
  export interface CommandEnd {
  ```
- `ConditionNode` ← src/workflow/reads.ts:11 [EXTRACTED]
  ```
  export interface ConditionNode {
  ```
- `ReadSite` ← src/workflow/reads.ts:59 [EXTRACTED]
  ```
  export interface ReadSite {
  ```
- `ReadScope` ← src/workflow/reads.ts:89 [EXTRACTED]
  ```
  export interface ReadScope {
  ```
- `SplitReads` ← src/workflow/reads.ts:251 [EXTRACTED]
  ```
  export interface SplitReads {
  ```
- `Ending` ← src/workflow/reads.ts:290 [EXTRACTED]
  ```
  export interface Ending {
  ```
- `WorkflowRunRecord` ← src/workflow/records.ts:49 [EXTRACTED]
  ```
  export type WorkflowRunRecord = {
  ```
- `CurrentWorkflowRunRecord` ← src/workflow/records.ts:131 [EXTRACTED]
  ```
  export type CurrentWorkflowRunRecord = WorkflowRunRecord & { sourceHash: string };
  ```
- `RecordState` ← src/workflow/records.ts:341 [EXTRACTED]
  ```
  export type RecordState = 'published' | 'pending';
  ```
- `RecordDelivery` ← src/workflow/records.ts:549 [EXTRACTED]
  ```
  export type RecordDelivery = { state: 'published' } | { state: 'pending'; reason: string };
  ```
- `MemberStats` ← src/workflow/records.ts:731 [EXTRACTED]
  ```
  export type MemberStats = z.infer<typeof MemberStatsSchema>;
  ```
- `WorkflowStats` ← src/workflow/records.ts:750 [EXTRACTED]
  ```
  export interface WorkflowStats {
  ```
- `Isolation` ← src/workflow/requirements.ts:9 [EXTRACTED]
  ```
  export type Isolation = z.infer<typeof IsolationSchema>;
  ```
- `Requirements` ← src/workflow/requirements.ts:33 [EXTRACTED]
  ```
  export type Requirements = z.infer<typeof RequirementsSchema>;
  ```
- `OnLimit` ← src/workflow/requirements.ts:41 [EXTRACTED]
  ```
  export type OnLimit = typeof ON_LIMIT[number];
  ```
- `Limit` ← src/workflow/requirements.ts:46 [EXTRACTED]
  ```
  export type Limit = z.infer<typeof LimitSchema>;
  ```
- `TurnLimits` ← src/workflow/requirements.ts:61 [EXTRACTED]
  ```
  export type TurnLimits = z.infer<typeof TurnLimitsSchema>;
  ```
- `Floor` ← src/workflow/requirements.ts:80 [EXTRACTED]
  ```
  export type Floor = Pick<Requirements, 'isolation' | 'network'>;
  ```
- `InEffect` ← src/workflow/requirements.ts:83 [EXTRACTED]
  ```
  export type InEffect = Omit<Requirements, 'strict'> & { floor?: Floor };
  ```
- `RequirementsLevel` ← src/workflow/requirements.ts:89 [EXTRACTED]
  ```
  export type RequirementsLevel = Requirements & Pick<InEffect, 'floor'>;
  ```
- `Setup` ← src/workflow/requirements.ts:111 [EXTRACTED]
  ```
  export type Setup = z.infer<typeof SetupSchema>;
  ```
- `StrictKey` ← src/workflow/requirements.ts:166 [EXTRACTED]
  ```
  export type StrictKey = KeysOf<'strict'>;
  ```
- `DriverCan` ← src/workflow/requirements.ts:187 [EXTRACTED]
  ```
  export type DriverCan = Omit<Can, 'env'> & {
  ```
- `DriverEnv` ← src/workflow/requirements.ts:194 [EXTRACTED]
  ```
  export type DriverEnv = (typeof DRIVER_ENV_REACH)[number];
  ```
- `DecidedCan` ← src/workflow/requirements.ts:203 [EXTRACTED]
  ```
  export type DecidedCan = Required<Omit<Can, 'default_tool'>> & Pick<Can, 'default_tool'>;
  ```
- `Allow` ← src/workflow/requirements.ts:216 [EXTRACTED]
  ```
  export type Allow = z.infer<typeof AllowSchema>;
  ```
- `Missing` ← src/workflow/requirements.ts:219 [EXTRACTED]
  ```
  export type Missing = StrictKey | keyof Floor | `workspace.${WorkspaceMode}` | `policy.${keyof Allow}`;
  ```
- `Held` ← src/workflow/requirements.ts:227 [EXTRACTED]
  ```
  export interface Held {
  ```
- `Unenforced` ← src/workflow/requirements.ts:254 [EXTRACTED]
  ```
  export type Unenforced = z.infer<typeof UnenforcedSchema>;
  ```
- `ReportedUnenforced` ← src/workflow/requirements.ts:262 [EXTRACTED]
  ```
  export type ReportedUnenforced = z.infer<typeof ReportedUnenforcedSchema>;
  ```
- `EnvScope` ← src/workflow/requirements.ts:295 [EXTRACTED]
  ```
  export type EnvScope = z.infer<typeof EnvScopeSchema>;
  ```
- `LeaseSetup` ← src/workflow/requirements.ts:300 [EXTRACTED]
  ```
  export type LeaseSetup = z.infer<typeof LeaseSetupSchema>;
  ```
- `EnvFacts` ← src/workflow/requirements.ts:361 [EXTRACTED]
  ```
  export interface EnvFacts {
  ```
- `Executor` ← src/workflow/requirements.ts:373 [EXTRACTED]
  ```
  export type Executor = 'command' | 'prompt' | 'workflow';
  ```
- `Offer` ← src/workflow/requirements.ts:400 [EXTRACTED]
  ```
  export interface Offer {
  ```
- `Terms` ← src/workflow/requirements.ts:460 [EXTRACTED]
  ```
  export interface Terms {
  ```
- `Negotiation` ← src/workflow/requirements.ts:472 [EXTRACTED]
  ```
  export type Negotiation =
  ```
- `ReservedDriverName` ← src/workflow/reserved-drivers.ts:9 [EXTRACTED]
  ```
  export type ReservedDriverName = (typeof RESERVED_DRIVERS)[keyof typeof RESERVED_DRIVERS];
  ```
- `HostDriverName` ← src/workflow/reserved-drivers.ts:12 [EXTRACTED]
  ```
  export type HostDriverName = typeof RESERVED_DRIVERS.host;
  ```
- `Retention` ← src/workflow/retention.ts:16 [EXTRACTED]
  ```
  export type Retention = { kind: 'never'; text: 'never' } | { kind: 'after'; ms: number; text: string };
  ```
- `ResolvedRetention` ← src/workflow/retention.ts:31 [EXTRACTED]
  ```
  export type ResolvedRetention = Retention & { file?: string };
  ```
- `CallerProvenance` ← src/workflow/run-controls.ts:100 [EXTRACTED]
  ```
  export interface CallerProvenance {
  ```
- `Via` ← src/workflow/run-controls.ts:110 [EXTRACTED]
  ```
  export type Via =
  ```
- `ResponseInput` ← src/workflow/run-controls.ts:181 [EXTRACTED]
  ```
  export interface ResponseInput {
  ```
- `Scope` ← src/workflow/scope.ts:15 [EXTRACTED]
  ```
  export interface Scope {
  ```
- `GrantedAllowance` ← src/workflow/scope.ts:51 [EXTRACTED]
  ```
  export interface GrantedAllowance {
  ```
- `SessionApp` ← src/workflow/session-apps.ts:12 [EXTRACTED]
  ```
  export type SessionApp = (typeof SESSION_APPS)[number];
  ```
- `CommandExit` ← src/workflow/shell-command.ts:7 [EXTRACTED]
  ```
  export type CommandExit =
  ```
- `GroupedCommandExit` ← src/workflow/shell-command.ts:90 [EXTRACTED]
  ```
  export interface GroupedCommandExit {
  ```
- `GroupedCommand` ← src/workflow/shell-command.ts:98 [EXTRACTED]
  ```
  export interface GroupedCommand {
  ```
- `HandoffOwner` ← src/workflow/snapshot.ts:28 [EXTRACTED]
  ```
  export type HandoffOwner = z.infer<typeof OwnerSchema>;
  ```
- `SnapshotBody` ← src/workflow/snapshot.ts:88 [EXTRACTED]
  ```
  export type SnapshotBody = z.infer<typeof BodySchema>;
  ```
- `RunDefinition` ← src/workflow/snapshot.ts:96 [EXTRACTED]
  ```
  export type RunDefinition = z.infer<typeof RunDefinitionSchema>;
  ```
- `Handoff` ← src/workflow/snapshot.ts:118 [EXTRACTED]
  ```
  export type Handoff = z.infer<typeof HandoffSchema>;
  ```
- `RunSnapshot` ← src/workflow/snapshot.ts:141 [EXTRACTED]
  ```
  export type RunSnapshot = z.infer<typeof SnapshotSchema>;
  ```
- `SnapshotError` ← src/workflow/snapshot.ts:143 [EXTRACTED]
  ```
  export type SnapshotError =
  ```
- `StepModel` ← src/workflow/step-model.ts:28 [EXTRACTED]
  ```
  export type StepModel = z.infer<typeof StepModelSchema>;
  ```
- `StepModelChoice` ← src/workflow/step-model.ts:34 [EXTRACTED]
  ```
  export type StepModelChoice =
  ```
- `StepModelRequest` ← src/workflow/step-model.ts:40 [EXTRACTED]
  ```
  export interface StepModelRequest {
  ```
- `ModelOrigin` ← src/workflow/step-model.ts:60 [EXTRACTED]
  ```
  export type ModelOrigin = 'step' | 'defaults';
  ```
- `StepPathSegment` ← src/workflow/step-path.ts:2 [EXTRACTED]
  ```
  export interface StepPathSegment {
  ```
- `LimitsFrom` ← src/workflow/step-state.ts:26 [EXTRACTED]
  ```
  export type LimitsFrom = z.infer<typeof LimitsFromSchema>;
  ```
- `ReleasedTokens` ← src/workflow/step-state.ts:31 [EXTRACTED]
  ```
  export type ReleasedTokens = z.infer<typeof ReleasedTokensSchema>;
  ```
- `StoppedAttempt` ← src/workflow/step-state.ts:39 [EXTRACTED]
  ```
  export type StoppedAttempt = z.infer<typeof StoppedAttemptSchema>;
  ```
- `SessionContinuation` ← src/workflow/step-state.ts:48 [EXTRACTED]
  ```
  export type SessionContinuation = z.infer<typeof SessionContinuationSchema>;
  ```
- `StepRead` ← src/workflow/step-state.ts:77 [EXTRACTED]
  ```
  export type StepRead = z.infer<typeof ReadSchema>;
  ```
- `ConfinedRunReport` ← src/workflow/step-state.ts:92 [EXTRACTED]
  ```
  export type ConfinedRunReport = z.infer<typeof ConfinedRunReportSchema>;
  ```
- `VisibleOutcome` ← src/workflow/step-state.ts:138 [EXTRACTED]
  ```
  export type VisibleOutcome = z.infer<typeof OutcomeSchema>;
  ```
- `ItemResult` ← src/workflow/step-state.ts:151 [EXTRACTED]
  ```
  export type ItemResult = z.infer<typeof ResultsSchema>[number];
  ```
- `HitlAnswer` ← src/workflow/step-state.ts:164 [EXTRACTED]
  ```
  export type HitlAnswer = z.infer<typeof AnswerSchema>;
  ```
- `Delivery` ← src/workflow/step-state.ts:172 [EXTRACTED]
  ```
  export type Delivery = z.infer<typeof DeliverySchema>;
  ```
- `StepPass` ← src/workflow/step-state.ts:191 [EXTRACTED]
  ```
  export type StepPass = z.infer<typeof StepPassSchema>;
  ```
- `ArchivedPass` ← src/workflow/step-state.ts:202 [EXTRACTED]
  ```
  export type ArchivedPass = z.infer<typeof ArchivedPassSchema>;
  ```
- `StepState` ← src/workflow/step-state.ts:293 [EXTRACTED]
  ```
  export type StepState = ReadonlyId<z.infer<typeof StepStateSchema>>;
  ```
- `StepCheckpoint` ← src/workflow/step-state.ts:297 [EXTRACTED]
  ```
  export type StepCheckpoint = ReadonlyId<z.infer<typeof StepCheckpointSchema>>;
  ```
- `HandedLease` ← src/workflow/step-state.ts:300 [EXTRACTED]
  ```
  export type HandedLease = Extract<StepCheckpoint, { status: 'leased' }>;
  ```
- `LeasedStep` ← src/workflow/step-state.ts:308 [EXTRACTED]
  ```
  export type LeasedStep = StepIn<'leased'>;
  ```
- `DeliveringStep` ← src/workflow/step-state.ts:312 [EXTRACTED]
  ```
  export type DeliveringStep = StepIn<'delivering'>;
  ```
- `UnleasedStep` ← src/workflow/step-state.ts:377 [EXTRACTED]
  ```
  export type UnleasedStep = Exclude<StepState, { status: 'leased' }>;
  ```
- `DeliveryFailure` ← src/workflow/step-state.ts:466 [EXTRACTED]
  ```
  export type DeliveryFailure = { code: (typeof DELIVERY_FAILURE_CODES)[number]; message: string };
  ```
- `RunId` ← src/workflow/store.ts:33 [EXTRACTED]
  ```
  export type RunId = z.infer<typeof RunIdSchema>;
  ```
- `AttemptId` ← src/workflow/store.ts:38 [EXTRACTED]
  ```
  export type AttemptId = z.infer<typeof AttemptIdSchema>;
  ```
- `CleanupLocked` ← src/workflow/store.ts:67 [EXTRACTED]
  ```
  export type CleanupLocked<T> = { kind: 'held'; value: T } | { kind: 'busy' };
  ```
- `RunLock` ← src/workflow/store.ts:238 [EXTRACTED]
  ```
  export type RunLock = z.infer<typeof RunLockSchema>;
  ```
- `LockTaken` ← src/workflow/store.ts:243 [EXTRACTED]
  ```
  export type LockTaken<T> = { kind: 'held'; value: T } | { kind: 'busy'; error: { code: 'driver_running'; message: string } };
  ```
- `PartOfStep` ← src/workflow/store.ts:474 [EXTRACTED]
  ```
  export type PartOfStep = z.infer<typeof PartOfStepSchema>;
  ```
- `RunUpdate` ← src/workflow/store.ts:538 [EXTRACTED]
  ```
  export type RunUpdate<T> = { status: 'done'; value: T } | { status: 'busy' } | { status: 'corrupt' };
  ```
- `TeamPin` ← src/workflow/team-pin.ts:20 [EXTRACTED]
  ```
  export type TeamPin = z.infer<typeof TeamPinSchema>;
  ```
- `PinRead` ← src/workflow/team-pin.ts:23 [EXTRACTED]
  ```
  export type PinRead<T> = { ok: true; value: T } | { ok: false; failed: string };
  ```
- `WithPath` ← src/workflow/template.ts:18 [EXTRACTED]
  ```
  export interface WithPath {
  ```
- `TemplateContext` ← src/workflow/template.ts:25 [EXTRACTED]
  ```
  export interface TemplateContext extends ExpressionContext {
  ```
- `TemplateRead` ← src/workflow/template.ts:35 [EXTRACTED]
  ```
  export type TemplateRead = { source: string; expression: Expression } | { source: string; path: WithPath } | { source: string; variable: PathField[] };
  ```
- `Template` ← src/workflow/template.ts:38 [EXTRACTED]
  ```
  export type Template = Array<string | TemplateRead>;
  ```
- `TemplateError` ← src/workflow/template.ts:46 [EXTRACTED]
  ```
  export interface TemplateError {
  ```
- `TemplateParse` ← src/workflow/template.ts:51 [EXTRACTED]
  ```
  export type TemplateParse = { ok: true; template: Template } | { ok: false; errors: TemplateError[] };
  ```
- `StepRoleSpec` ← src/workflow/template.ts:204 [EXTRACTED]
  ```
  export type StepRoleSpec = { kind: 'id'; id: string } | { kind: 'item_template'; source: string; template: Template };
  ```
- `StepExpression` ← src/workflow/template.ts:362 [EXTRACTED]
  ```
  export interface StepExpression {
  ```
- `DriverIdentity` ← src/workflow/types.ts:21 [EXTRACTED]
  ```
  export interface DriverIdentity {
  ```
- `OutputSchema` ← src/workflow/types.ts:27 [EXTRACTED]
  ```
  export type OutputSchema =
  ```
- `StepHitl` ← src/workflow/types.ts:43 [EXTRACTED]
  ```
  export interface StepHitl {
  ```
- `WorkflowStep` ← src/workflow/types.ts:77 [EXTRACTED]
  ```
  export interface WorkflowStep {
  ```
- `Budget` ← src/workflow/types.ts:184 [EXTRACTED]
  ```
  export interface Budget {
  ```
- `ForEach` ← src/workflow/types.ts:189 [EXTRACTED]
  ```
  export interface ForEach {
  ```
- `WorkflowLoop` ← src/workflow/types.ts:203 [EXTRACTED]
  ```
  export interface WorkflowLoop {
  ```
- `StepLoop` ← src/workflow/types.ts:213 [EXTRACTED]
  ```
  export interface StepLoop {
  ```
- `TeamPlace` ← src/workflow/types.ts:225 [EXTRACTED]
  ```
  export interface TeamPlace {
  ```
- `ConfinedPlace` ← src/workflow/types.ts:233 [EXTRACTED]
  ```
  export interface ConfinedPlace {
  ```
- `StepWorkspace` ← src/workflow/types.ts:238 [EXTRACTED]
  ```
  export type StepWorkspace = Exclude<typeof WORKSPACE_MODES[number], 'clone' | 'team'> | { clone: ClonePlace } | { team: TeamPlace } | ConfinedPlace;
  ```
- `EndOutcome` ← src/workflow/types.ts:248 [EXTRACTED]
  ```
  export type EndOutcome = 'succeeded' | 'failed';
  ```
- `WorkflowFrom` ← src/workflow/types.ts:251 [EXTRACTED]
  ```
  export interface WorkflowFrom {
  ```
- `StepWorkflow` ← src/workflow/types.ts:256 [EXTRACTED]
  ```
  export type StepWorkflow =
  ```
- `InlineWorkflow` ← src/workflow/types.ts:306 [EXTRACTED]
  ```
  export interface InlineWorkflow {
  ```
- `WorkflowDefaults` ← src/workflow/types.ts:315 [EXTRACTED]
  ```
  export interface WorkflowDefaults {
  ```
- `StepScorers` ← src/workflow/types.ts:332 [EXTRACTED]
  ```
  export interface StepScorers {
  ```
- `ScoringStart` ← src/workflow/types.ts:343 [EXTRACTED]
  ```
  export type ScoringStart = (typeof SCORING_STARTS)[number];
  ```
- `StartedBy` ← src/workflow/types.ts:351 [EXTRACTED]
  ```
  export type StartedBy = typeof STARTED_BY[number];
  ```
- `Invoke` ← src/workflow/types.ts:356 [EXTRACTED]
  ```
  export type Invoke = typeof INVOKE_VALUES[number];
  ```
- `WorkflowDefinition` ← src/workflow/types.ts:358 [EXTRACTED]
  ```
  export interface WorkflowDefinition {
  ```
- `WorkflowDiagnostic` ← src/workflow/types.ts:398 [EXTRACTED]
  ```
  export interface WorkflowDiagnostic {
  ```
- `StepOutcome` ← src/workflow/types.ts:438 [EXTRACTED]
  ```
  export type StepOutcome = 'success' | 'failed' | 'released';
  ```
- `RunStatus` ← src/workflow/types.ts:440 [EXTRACTED]
  ```
  export type RunStatus = 'running' | 'succeeded' | 'failed' | 'cancelled';
  ```
- `StepLease` ← src/workflow/types.ts:442 [EXTRACTED]
  ```
  export interface StepLease {
  ```
- `LeasedConfined` ← src/workflow/types.ts:468 [EXTRACTED]
  ```
  export type LeasedConfined = Pick<ConfinedLease, 'level' | 'tools'>;
  ```
- `WorkflowFailure` ← src/workflow/types.ts:470 [EXTRACTED]
  ```
  export interface WorkflowFailure {
  ```
- `Finalizing` ← src/workflow/types.ts:479 [EXTRACTED]
  ```
  export interface Finalizing {
  ```
- `RunState` ← src/workflow/types.ts:489 [EXTRACTED]
  ```
  export interface RunState {
  ```
- `AdmittedWorkflow` ← src/workflow/types.ts:639 [EXTRACTED]
  ```
  export interface AdmittedWorkflow {
  ```
- `DriveOptions` ← src/workflow/types.ts:651 [EXTRACTED]
  ```
  export interface DriveOptions {
  ```
- `KeptBranchReason` ← src/workflow/types.ts:665 [EXTRACTED]
  ```
  export type KeptBranchReason = 'pr' | 'final' | 'unmerged' | 'host';
  ```
- `RunLeftovers` ← src/workflow/types.ts:672 [EXTRACTED]
  ```
  export interface RunLeftovers {
  ```
- `RunPublication` ← src/workflow/types.ts:682 [EXTRACTED]
  ```
  export interface RunPublication {
  ```
- `CachedWorkflow` ← src/workflow/types.ts:691 [EXTRACTED]
  ```
  export interface CachedWorkflow {
  ```
- `WorkflowSource` ← src/workflow/types.ts:710 [EXTRACTED]
  ```
  export type WorkflowSource = 'team' | 'default';
  ```
- `ResolvedWorkflow` ← src/workflow/types.ts:713 [EXTRACTED]
  ```
  export type ResolvedWorkflow = CachedWorkflow & { source: WorkflowSource };
  ```
- `WorkflowEnvelope` ← src/workflow/types.ts:715 [EXTRACTED]
  ```
  export type WorkflowEnvelope =
  ```
- `LimitedOn` ← src/workflow/usage-limits.ts:146 [EXTRACTED]
  ```
  export type LimitedOn = typeof LIMITED_ON[number];
  ```
- `KeptLimit` ← src/workflow/usage-limits.ts:165 [EXTRACTED]
  ```
  export type KeptLimit = z.infer<typeof KeptLimitSchema>;
  ```
- `WhenIdle` ← src/workflow/usage-limits.ts:168 [EXTRACTED]
  ```
  export type WhenIdle =
  ```
- `UsageLimitBook` ← src/workflow/usage-limits.ts:174 [EXTRACTED]
  ```
  export interface UsageLimitBook {
  ```
- `WholeRun` ← src/workflow/whole-workflow.ts:17 [EXTRACTED]
  ```
  export type WholeRun = { step: WorkflowStep; executor: 'command' | 'prompt'; requires: InEffect };
  ```
- `WholeEnd` ← src/workflow/whole-workflow.ts:190 [EXTRACTED]
  ```
  export type WholeEnd = z.infer<typeof WholeEndSchema>;
  ```
- `WorkspaceMode` ← src/workflow/workspace.ts:19 [EXTRACTED]
  ```
  export type WorkspaceMode = typeof WORKSPACE_MODES[number];
  ```
- `StepChanges` ← src/workflow/workspace.ts:22 [EXTRACTED]
  ```
  export interface StepChanges {
  ```
- `WorkspaceContract` ← src/workflow/workspace.ts:36 [EXTRACTED]
  ```
  export type WorkspaceContract = CopyContract | z.infer<typeof TeamContractSchema>;
  ```
- `CopyContract` ← src/workflow/workspace.ts:39 [EXTRACTED]
  ```
  export type CopyContract = {
  ```
- `SessionRef` ← src/workflow/workspace.ts:75 [EXTRACTED]
  ```
  export interface SessionRef {
  ```
- `LeaseSession` ← src/workflow/workspace.ts:81 [EXTRACTED]
  ```
  export interface LeaseSession extends SessionRef {
  ```
- `WorkspacePlan` ← src/workflow/workspace.ts:85 [EXTRACTED]
  ```
  export interface WorkspacePlan {
  ```
- `Level` ← src/workflow/workspace.ts:316 [EXTRACTED]
  ```
  export interface Level {
  ```
- `WorkspaceRequest` ← src/workflow/workspace.ts:884 [EXTRACTED]
  ```
  export interface WorkspaceRequest {
  ```
- `RoleIdSpec` ← src/workflow/workspace.ts:1177 [EXTRACTED]
  ```
  export type RoleIdSpec = Extract<StepRoleSpec, { kind: 'id' }>;
  ```
- `RoleLevel` ← src/workflow/workspace.ts:1184 [EXTRACTED]
  ```
  export interface RoleLevel<TRole extends StepRoleSpec = StepRoleSpec> extends Level {
  ```
- `ResolvedRole` ← src/workflow/workspace.ts:1214 [EXTRACTED]
  ```
  export interface ResolvedRole<TRole extends StepRoleSpec = StepRoleSpec> {
  ```
- `StepCopy` ← src/workflow/workspace.ts:1239 [EXTRACTED]
  ```
  export interface StepCopy<TRole extends StepRoleSpec = StepRoleSpec> {
  ```
- `StepRole` ← src/workflow/workspace.ts:1377 [EXTRACTED]
  ```
  export type StepRole = { kind: 'role'; role: string } | { kind: 'none' } | { kind: 'unrenderable'; failure: WorkflowFailure };
  ```
- `GitResult` ← src/workflow/worktree.ts:65 [EXTRACTED]
  ```
  export interface GitResult {
  ```
- `GitAnswer` ← src/workflow/worktree.ts:86 [EXTRACTED]
  ```
  export type GitAnswer = { readonly said: 'yes' | 'no' | 'nothing'; readonly result: GitResult };
  ```
- `Git` ← src/workflow/worktree.ts:137 [EXTRACTED]
  ```
  export type Git = (cwd: string, args: string[], options?: GitOptions) => Promise<GitResult>;
  ```
- `UntrustedGit` ← src/workflow/worktree.ts:142 [EXTRACTED]
  ```
  export type UntrustedGit = Git & { readonly [UNTRUSTED]: true };
  ```
- `MemberConfig` ← src/workflow/worktree.ts:214 [EXTRACTED]
  ```
  export type MemberConfig = ReadonlySet<string>;
  ```
- `MemberRemote` ← src/workflow/worktree.ts:222 [EXTRACTED]
  ```
  export interface MemberRemote {
  ```
- `RunWorktree` ← src/workflow/worktree.ts:732 [EXTRACTED]
  ```
  export type RunWorktree =
  ```
- `UnrestoredMarker` ← src/workflow/worktree.ts:1934 [EXTRACTED]
  ```
  export type UnrestoredMarker = z.infer<typeof UnrestoredMarker>;
  ```
- `KeptChanges` ← src/workflow/worktree.ts:2153 [EXTRACTED]
  ```
  export type KeptChanges = { ref: string; modules?: string };
  ```
- `UnsafeDictionary` ← oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts:29 [EXTRACTED]
  ```
  export type UnsafeDictionary = {
  ```
- `WideningTargetKind` ← oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts:34 [EXTRACTED]
  ```
  export type WideningTargetKind =
  ```
- `WideningTarget` ← oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts:41 [EXTRACTED]
  ```
  export type WideningTarget = {
  ```
- `TypeEnvironment` ← oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts:45 [EXTRACTED]
  ```
  export type TypeEnvironment = {
  ```
- `FunctionParameter` ← oxlint-plugin-teamai/anti-slop/shared/function-parameters.ts:3 [EXTRACTED]
  ```
  export type FunctionParameter = ESTree.ParamPattern;
  ```
- `TypeAliasEnvironment` ← oxlint-plugin-teamai/anti-slop/shared/type-alias-resolution.ts:21 [EXTRACTED]
  ```
  export type TypeAliasEnvironment = {
  ```
- `ResolvedTypeMatcher` ← oxlint-plugin-teamai/anti-slop/shared/type-alias-resolution.ts:27 [EXTRACTED]
  ```
  export type ResolvedTypeMatcher = (
  ```
- `RepoInfo` ← packages/provider-core/src/contract.ts:1 [EXTRACTED]
  ```
  export interface RepoInfo {
  ```
- `PrCreateOptions` ← packages/provider-core/src/contract.ts:10 [EXTRACTED]
  ```
  export interface PrCreateOptions {
  ```
- `PullRequestRef` ← packages/provider-core/src/contract.ts:21 [EXTRACTED]
  ```
  export interface PullRequestRef {
  ```
- `CommitRef` ← packages/provider-core/src/contract.ts:28 [EXTRACTED]
  ```
  export interface CommitRef {
  ```
- `CiStatus` ← packages/provider-core/src/contract.ts:34 [EXTRACTED]
  ```
  export type CiStatus = 'passed' | 'failed' | 'pending' | 'none';
  ```
- `PullRequestLookup` ← packages/provider-core/src/contract.ts:36 [EXTRACTED]
  ```
  export interface PullRequestLookup {
  ```
- `PullRequestRecord` ← packages/provider-core/src/contract.ts:42 [EXTRACTED]
  ```
  export type PullRequestRecord = { url: string; title: string; openedAt: string } & (
  ```
- `MergedAs` ← packages/provider-core/src/contract.ts:48 [EXTRACTED]
  ```
  export type MergedAs = { head: string; commit: string };
  ```
- `OrgRepoInfo` ← packages/provider-core/src/contract.ts:62 [EXTRACTED]
  ```
  export interface OrgRepoInfo {
  ```
- `Provider` ← packages/provider-core/src/contract.ts:74 [EXTRACTED]
  ```
  export interface Provider<TMergeRequest = unknown> {
  ```
- `ProviderDefinition` ← packages/provider-core/src/registry.ts:1 [EXTRACTED]
  ```
  export interface ProviderDefinition<TName extends string = string, TProvider = unknown> {
  ```
- `ProviderRegistry` ← packages/provider-core/src/registry.ts:9 [EXTRACTED]
  ```
  export interface ProviderRegistry<TName extends string, TProvider> {
  ```
- `Answering` ← packages/runtime-kit/src/answering.ts:11 [EXTRACTED]
  ```
  export interface Answering {
  ```
- `RecordRead` ← packages/runtime-kit/src/journal.ts:18 [EXTRACTED]
  ```
  export type RecordRead<TRecord> = { kind: 'found'; record: TRecord } | { kind: 'missing' } | { kind: 'unreadable'; file: string; why: string };
  ```
- `RecordStore` ← packages/runtime-kit/src/journal.ts:20 [EXTRACTED]
  ```
  export interface RecordStore<TRecord> {
  ```
- `OpEnd` ← packages/runtime-kit/src/ledger.ts:4 [EXTRACTED]
  ```
  export type OpEnd = Exclude<OpState, { state: 'running' }>;
  ```
- `CancelMark` ← packages/runtime-kit/src/ledger.ts:7 [EXTRACTED]
  ```
  export type CancelMark = 'cancelled-unseen' | 'cancel-unread';
  ```
- `OpLedger` ← packages/runtime-kit/src/ledger.ts:15 [EXTRACTED]
  ```
  export interface OpLedger<TRun = unknown> {
  ```
- `OuterHandle` ← packages/runtime-kit/src/outer.ts:26 [EXTRACTED]
  ```
  export type OuterHandle = z.infer<typeof OuterHandleSchema>;
  ```
- `Registration` ← packages/runtime-kit/src/outer.ts:71 [EXTRACTED]
  ```
  export interface Registration {
  ```
- `PlaceWork` ← packages/runtime-kit/src/places.ts:7 [EXTRACTED]
  ```
  export interface PlaceWork {
  ```
- `RuntimeHandlers` ← packages/runtime-kit/src/serve.ts:23 [EXTRACTED]
  ```
  export type RuntimeHandlers = { readonly [TType in Exclude<RuntimeRequest['type'], 'wake'>]: Handler<TType> } & { readonly wake?: Handler<'wake'> };
  ```
- `ServeRuntime` ← packages/runtime-kit/src/serve.ts:25 [EXTRACTED]
  ```
  export interface ServeRuntime {
  ```
- `WorktreePlace` ← packages/runtime-paseo/src/conversation.ts:33 [EXTRACTED]
  ```
  export type WorktreePlace = Extract<Place, { kind: 'worktree' }> & { workspace: NonNullable<Place['workspace']> };
  ```
- `Launch` ← packages/runtime-paseo/src/conversation.ts:36 [EXTRACTED]
  ```
  export interface Launch {
  ```
- `Conversations` ← packages/runtime-paseo/src/conversation.ts:1111 [EXTRACTED]
  ```
  export type Conversations = ReturnType<typeof conversations>;
  ```
- `Place` ← packages/runtime-paseo/src/journal.ts:64 [EXTRACTED]
  ```
  export type Place = z.infer<typeof PlaceSchema>;
  ```
- `AgentCreate` ← packages/runtime-paseo/src/journal.ts:98 [EXTRACTED]
  ```
  export type AgentCreate = Omit<z.infer<typeof AgentCreateSchema>, 'env'> & { env?: z.infer<typeof AgentEnvSchema> };
  ```
- `PromptRecord` ← packages/runtime-paseo/src/journal.ts:147 [EXTRACTED]
  ```
  export type PromptRecord = z.infer<typeof PromptRecordSchema>;
  ```
- `AgentPrompt` ← packages/runtime-paseo/src/journal.ts:149 [EXTRACTED]
  ```
  export type AgentPrompt = Extract<PromptRecord, { kind: 'agent' }>;
  ```
- `Conversation` ← packages/runtime-paseo/src/journal.ts:154 [EXTRACTED]
  ```
  export type Conversation = z.infer<typeof ConversationSchema>;
  ```
- `Journal` ← packages/runtime-paseo/src/journal.ts:323 [EXTRACTED]
  ```
  export type Journal = ReturnType<typeof journal>;
  ```
- `Offer` ← packages/runtime-paseo/src/offer.ts:19 [EXTRACTED]
  ```
  export type Offer = { runs: 'steps-and-judges' } | { runs: 'steps'; noJudge: string } | { runs: 'nothing'; reason: string };
  ```
- `Offered` ← packages/runtime-paseo/src/offer.ts:33 [EXTRACTED]
  ```
  export interface Offered {
  ```
- `PaseoOptions` ← packages/runtime-paseo/src/options.ts:20 [EXTRACTED]
  ```
  export type PaseoOptions = z.infer<typeof OptionsSchema>;
  ```
- `Following` ← packages/runtime-paseo/src/process-state.ts:19 [EXTRACTED]
  ```
  export interface Following {
  ```
- `ProcessState` ← packages/runtime-paseo/src/process-state.ts:26 [EXTRACTED]
  ```
  export interface ProcessState {
  ```
- `PaseoTool` ← packages/runtime-paseo/src/providers.ts:28 [EXTRACTED]
  ```
  export type PaseoTool = 'claude' | 'codex' | 'opencode';
  ```
- `CustomProviders` ← packages/runtime-paseo/src/providers.ts:80 [EXTRACTED]
  ```
  export type CustomProviders = z.infer<typeof CustomProvidersSchema>;
  ```
- `ProviderToAdd` ← packages/runtime-paseo/src/providers.ts:105 [EXTRACTED]
  ```
  export interface ProviderToAdd {
  ```
- `ProviderFound` ← packages/runtime-paseo/src/providers.ts:126 [EXTRACTED]
  ```
  export type ProviderFound = { provider: string } | { cannot: string } | { add: ProviderToAdd };
  ```
- `EnsureProvider` ← packages/runtime-paseo/src/providers.ts:279 [EXTRACTED]
  ```
  export type EnsureProvider = ReturnType<typeof providerAdds>;
  ```
- `Serving` ← packages/runtime-paseo/src/runtime.ts:50 [EXTRACTED]
  ```
  export interface Serving {
  ```
- `Through` ← packages/runtime-paseo/src/sandbox.ts:23 [EXTRACTED]
  ```
  export type Through = NonNullable<Extract<Place, { kind: 'worktree' }>['through']>;
  ```
- `ConfinedPlace` ← packages/runtime-paseo/src/workspace.ts:16 [EXTRACTED]
  ```
  export type ConfinedPlace = Extract<Place, { kind: 'confined' }>;
  ```
- `RuntimeMode` ← packages/runtime-protocol/src/protocol.ts:134 [EXTRACTED]
  ```
  export type RuntimeMode = (typeof RUNTIME_MODES)[number];
  ```
- `OpId` ← packages/runtime-protocol/src/protocol.ts:139 [EXTRACTED]
  ```
  export type OpId = z.infer<typeof OpIdSchema>;
  ```
- `RuntimeOptions` ← packages/runtime-protocol/src/protocol.ts:174 [EXTRACTED]
  ```
  export type RuntimeOptions = z.infer<typeof RuntimeOptionsSchema>;
  ```
- `PlaceView` ← packages/runtime-protocol/src/protocol.ts:189 [EXTRACTED]
  ```
  export type PlaceView = z.infer<typeof PlaceViewSchema>;
  ```
- `RuntimeFailure` ← packages/runtime-protocol/src/protocol.ts:194 [EXTRACTED]
  ```
  export type RuntimeFailure = z.infer<typeof RuntimeFailureSchema>;
  ```
- `RuntimeDisplay` ← packages/runtime-protocol/src/protocol.ts:217 [EXTRACTED]
  ```
  export type RuntimeDisplay = z.infer<typeof RuntimeDisplaySchema>;
  ```
- `PromptResult` ← packages/runtime-protocol/src/protocol.ts:249 [EXTRACTED]
  ```
  export type PromptResult = z.infer<typeof PromptResultSchema>;
  ```
- `PromptLease` ← packages/runtime-protocol/src/protocol.ts:307 [EXTRACTED]
  ```
  export type PromptLease = z.infer<typeof PromptLeaseSchema>;
  ```
- `Can` ← packages/runtime-protocol/src/protocol.ts:377 [EXTRACTED]
  ```
  export type Can = z.infer<typeof CanSchema>;
  ```
- `ConfinedOffer` ← packages/runtime-protocol/src/protocol.ts:379 [EXTRACTED]
  ```
  export type ConfinedOffer = z.infer<typeof ConfinedOfferSchema>;
  ```
- `InitCredentials` ← packages/runtime-protocol/src/protocol.ts:389 [EXTRACTED]
  ```
  export type InitCredentials = z.infer<typeof InitCredentialsSchema>;
  ```
- `InitInstance` ← packages/runtime-protocol/src/protocol.ts:408 [EXTRACTED]
  ```
  export type InitInstance = z.infer<typeof InitInstanceSchema>;
  ```
- `InitHomeEnv` ← packages/runtime-protocol/src/protocol.ts:419 [EXTRACTED]
  ```
  export type InitHomeEnv = z.infer<typeof InitHomeEnvSchema>;
  ```
- `ConfinedPrompt` ← packages/runtime-protocol/src/protocol.ts:520 [EXTRACTED]
  ```
  export type ConfinedPrompt = z.infer<typeof ConfinedPromptSchema>;
  ```
- `WakeRequest` ← packages/runtime-protocol/src/protocol.ts:565 [EXTRACTED]
  ```
  export type WakeRequest = z.infer<typeof WakeRequestSchema>;
  ```
- `RuntimeRequest` ← packages/runtime-protocol/src/protocol.ts:593 [EXTRACTED]
  ```
  export type RuntimeRequest = z.infer<typeof RuntimeRequestSchema>;
  ```
- `ConfinedKept` ← packages/runtime-protocol/src/protocol.ts:606 [EXTRACTED]
  ```
  export type ConfinedKept = z.infer<typeof ConfinedKeptSchema>;
  ```
- `OpState` ← packages/runtime-protocol/src/protocol.ts:647 [EXTRACTED]
  ```
  export type OpState = z.infer<typeof OpStateSchema>;
  ```
- `RuntimeMessage` ← packages/runtime-protocol/src/protocol.ts:752 [EXTRACTED]
  ```
  export type RuntimeMessage = z.infer<typeof RuntimeMessageSchema>;
  ```
- `OpenRequest` ← packages/runtime-protocol/src/step-runtime.ts:23 [EXTRACTED]
  ```
  export type OpenRequest = Omit<z.infer<typeof OpenRequestSchema>, 'type'>;
  ```
- `ExecRequest` ← packages/runtime-protocol/src/step-runtime.ts:26 [EXTRACTED]
  ```
  export type ExecRequest = Omit<z.infer<typeof ExecRequestSchema>, 'type'>;
  ```
- `ExecKind` ← packages/runtime-protocol/src/step-runtime.ts:33 [EXTRACTED]
  ```
  export type ExecKind = 'setup' | 'command' | 'tool' | 'workflow';
  ```
- `PromptRequest` ← packages/runtime-protocol/src/step-runtime.ts:36 [EXTRACTED]
  ```
  export type PromptRequest = Omit<z.infer<typeof PromptRequestSchema>, 'type'>;
  ```
- `Opened` ← packages/runtime-protocol/src/step-runtime.ts:38 [EXTRACTED]
  ```
  export type Opened = { kind: 'ready'; handle: string; display?: RuntimeDisplay } | { kind: 'failed'; failure: RuntimeFailure };
  ```
- `Lost` ← packages/runtime-protocol/src/step-runtime.ts:53 [EXTRACTED]
  ```
  export type Lost = { kind: 'lost'; failure: RuntimeFailure };
  ```
- `ExecEnd` ← packages/runtime-protocol/src/step-runtime.ts:61 [EXTRACTED]
  ```
  export type ExecEnd = { kind: 'exited'; code: number; stdout: string } | { kind: 'cancelled'; stdout?: string } | { kind: 'failed'; failure: RuntimeFailure; isStepOutcome?: true } | Lost;
  ```
- `PromptStopped` ← packages/runtime-protocol/src/step-runtime.ts:66 [EXTRACTED]
  ```
  export type PromptStopped = NonNullable<FinishedState['stopped']>;
  ```
- `PromptEnd` ← packages/runtime-protocol/src/step-runtime.ts:72 [EXTRACTED]
  ```
  export type PromptEnd =
  ```
- `WakeEnd` ← packages/runtime-protocol/src/step-runtime.ts:82 [EXTRACTED]
  ```
  export type WakeEnd = { kind: 'woken'; where: string; display?: RuntimeDisplay } | { kind: 'failed'; failure: RuntimeFailure } | Lost;
  ```
- `Reattached` ← packages/runtime-protocol/src/step-runtime.ts:89 [EXTRACTED]
  ```
  export type Reattached = { kind: 'gone' } | { kind: 'alive'; ops: OpState[]; display?: RuntimeDisplay; partGone?: string } | { kind: 'failed'; failure: RuntimeFailure };
  ```
- `Accepted` ← packages/runtime-protocol/src/step-runtime.ts:92 [EXTRACTED]
  ```
  export interface Accepted {
  ```
- `ExecQuestion` ← packages/runtime-protocol/src/step-runtime.ts:97 [EXTRACTED]
  ```
  export type ExecQuestion = { step: string; kind: 'approve' | 'choose'; message: string; options: string[]; required: boolean; default?: string };
  ```
- `ExecAnswer` ← packages/runtime-protocol/src/step-runtime.ts:100 [EXTRACTED]
  ```
  export type ExecAnswer = { choice: string; note?: string } | { refused: string };
  ```
- `ExecEvents` ← packages/runtime-protocol/src/step-runtime.ts:102 [EXTRACTED]
  ```
  export interface ExecEvents {
  ```
- `Initialized` ← packages/runtime-protocol/src/step-runtime.ts:128 [EXTRACTED]
  ```
  export type Initialized<TCan = Can> =
  ```
- `StepRuntime` ← packages/runtime-protocol/src/step-runtime.ts:136 [EXTRACTED]
  ```
  export interface StepRuntime<TCan = Can> {
  ```
- `SocketRequest` ← packages/runtime-sandbox/src/attempt-socket.ts:44 [EXTRACTED]
  ```
  export type SocketRequest = z.infer<typeof SocketRequestSchema>;
  ```
- `Ask` ← packages/runtime-sandbox/src/attempt-socket.ts:46 [EXTRACTED]
  ```
  export type Ask = Extract<SocketRequest, { ask: unknown }>['ask'];
  ```
- `Grant` ← packages/runtime-sandbox/src/attempt-socket.ts:57 [EXTRACTED]
  ```
  export type Grant = z.infer<typeof GrantSchema>;
  ```
- `Answer` ← packages/runtime-sandbox/src/attempt-socket.ts:65 [EXTRACTED]
  ```
  export type Answer = z.infer<typeof AnswerSchema>;
  ```
- `Answering` ← packages/runtime-sandbox/src/attempt-socket.ts:84 [EXTRACTED]
  ```
  export type Answering = (ask: Ask) => Promise<{ ok: true; grant: Grant } | { ok: false; failure: RuntimeFailure }>;
  ```
- `AttemptSocket` ← packages/runtime-sandbox/src/attempt-socket.ts:86 [EXTRACTED]
  ```
  export interface AttemptSocket {
  ```
- `BoundedTail` ← packages/runtime-sandbox/src/bounded-tail.ts:14 [EXTRACTED]
  ```
  export interface BoundedTail {
  ```
- `ExecOperations` ← packages/runtime-sandbox/src/exec.ts:497 [EXTRACTED]
  ```
  export type ExecOperations = ReturnType<typeof execOperations>;
  ```
- `Outcome` ← packages/runtime-sandbox/src/journal.ts:28 [EXTRACTED]
  ```
  export type Outcome = z.infer<typeof OutcomeSchema>;
  ```
- `ExecRecord` ← packages/runtime-sandbox/src/journal.ts:33 [EXTRACTED]
  ```
  export type ExecRecord = z.infer<typeof ExecRecordSchema>;
  ```
- `PlaceRecord` ← packages/runtime-sandbox/src/journal.ts:56 [EXTRACTED]
  ```
  export type PlaceRecord = z.infer<typeof PlaceRecordSchema>;
  ```
- `JournalId` ← packages/runtime-sandbox/src/journal.ts:64 [EXTRACTED]
  ```
  export type JournalId = z.infer<typeof JournalIdSchema>;
  ```
- `KnownInstances` ← packages/runtime-sandbox/src/journal.ts:82 [EXTRACTED]
  ```
  export type KnownInstances = z.infer<typeof InstancesSchema>;
  ```
- `Journal` ← packages/runtime-sandbox/src/journal.ts:178 [EXTRACTED]
  ```
  export type Journal = ReturnType<typeof journal>;
  ```
- `JudgeLaunch` ← packages/runtime-sandbox/src/judge.ts:39 [EXTRACTED]
  ```
  export interface JudgeLaunch {
  ```
- `JudgeReading` ← packages/runtime-sandbox/src/judge.ts:45 [EXTRACTED]
  ```
  export type JudgeReading = { ok: true; session: string; result: PromptResult; usage?: TokenUsage } | { ok: false; message: string };
  ```
- `Judge` ← packages/runtime-sandbox/src/judge.ts:223 [EXTRACTED]
  ```
  export interface Judge {
  ```
- `OnThisMachine` ← packages/runtime-sandbox/src/loopback.ts:35 [EXTRACTED]
  ```
  export interface OnThisMachine {
  ```
- `ContainerEngine` ← packages/runtime-sandbox/src/options.ts:37 [EXTRACTED]
  ```
  export type ContainerEngine = (typeof CONTAINER_ENGINES)[number];
  ```
- `NativeProvider` ← packages/runtime-sandbox/src/options.ts:42 [EXTRACTED]
  ```
  export type NativeProvider = (typeof NATIVE_SANDBOXES)[number];
  ```
- `SandboxProviderName` ← packages/runtime-sandbox/src/options.ts:47 [EXTRACTED]
  ```
  export type SandboxProviderName = (typeof PROVIDERS)[number];
  ```
- `WarmOptions` ← packages/runtime-sandbox/src/options.ts:76 [EXTRACTED]
  ```
  export type WarmOptions = z.infer<typeof ContainerWarmSchema>;
  ```
- `VercelWarmOptions` ← packages/runtime-sandbox/src/options.ts:117 [EXTRACTED]
  ```
  export type VercelWarmOptions = z.infer<typeof VercelWarmSchema>;
  ```
- `VercelOptions` ← packages/runtime-sandbox/src/options.ts:137 [EXTRACTED]
  ```
  export type VercelOptions = z.infer<typeof VercelOptionsSchema>;
  ```
- `SandboxOptions` ← packages/runtime-sandbox/src/options.ts:141 [EXTRACTED]
  ```
  export type SandboxOptions = z.infer<typeof ContainerOptionsSchema> | z.infer<typeof SbxOptionsSchema> | z.infer<typeof NativeOptionsSchema> | VercelOptions;
  ```
- `ProfileOption` ← packages/runtime-sandbox/src/options.ts:146 [EXTRACTED]
  ```
  export type ProfileOption = z.infer<typeof ProfileSchema>;
  ```
- `ParsedOptions` ← packages/runtime-sandbox/src/options.ts:149 [EXTRACTED]
  ```
  export type ParsedOptions = SandboxOptions & { readonly profile?: ProfileOption };
  ```
- `Unavailable` ← packages/runtime-sandbox/src/provider.ts:6 [EXTRACTED]
  ```
  export type Unavailable = NonNullable<Extract<RuntimeMessage, { type: 'init'; ok: true }>['unavailable']>;
  ```
- `PlaceKey` ← packages/runtime-sandbox/src/provider.ts:26 [EXTRACTED]
  ```
  export interface PlaceKey {
  ```
- `ExecSpec` ← packages/runtime-sandbox/src/provider.ts:98 [EXTRACTED]
  ```
  export interface ExecSpec {
  ```
- `ExecEnd` ← packages/runtime-sandbox/src/provider.ts:107 [EXTRACTED]
  ```
  export type ExecEnd = { kind: 'exited'; code: number } | { kind: 'failed'; failure: RuntimeFailure };
  ```
- `Judges` ← packages/runtime-sandbox/src/provider.ts:110 [EXTRACTED]
  ```
  export interface Judges {
  ```
- `HostRoute` ← packages/runtime-sandbox/src/provider.ts:124 [EXTRACTED]
  ```
  export type HostRoute = z.infer<typeof HostRouteSchema>;
  ```
- `WarmedImage` ← packages/runtime-sandbox/src/provider.ts:127 [EXTRACTED]
  ```
  export interface WarmedImage { image: string }
  ```
- `SandboxOpen` ← packages/runtime-sandbox/src/provider.ts:130 [EXTRACTED]
  ```
  export interface SandboxOpen {
  ```
- `Provider` ← packages/runtime-sandbox/src/provider.ts:228 [EXTRACTED]
  ```
  export type Provider = Sandboxing & (
  ```
- `Ready` ← packages/runtime-sandbox/src/runtime.ts:42 [EXTRACTED]
  ```
  export interface Ready {
  ```
- `RuntimeDeps` ← packages/runtime-sandbox/src/runtime.ts:80 [EXTRACTED]
  ```
  export interface RuntimeDeps {
  ```
- `SignInProvider` ← packages/runtime-sandbox/src/sign-in.ts:23 [EXTRACTED]
  ```
  export type SignInProvider = 'sbx' | 'docker' | 'podman' | 'seatbelt' | 'bwrap' | 'vercel';
  ```
- `UnusedGateways` ← packages/runtime-sandbox/src/sign-in.ts:112 [EXTRACTED]
  ```
  export type UnusedGateways = Record<string, { ownSignIn: readonly string[]; notice: string }>;
  ```
- `MissingCommand` ← packages/runtime-sandbox/src/sign-in.ts:130 [EXTRACTED]
  ```
  export type MissingCommand = (command: string, tool: string) => { holder: string; fix: string } | undefined;
  ```
- `WarmPlan` ← packages/runtime-sandbox/src/warm.ts:66 [EXTRACTED]
  ```
  export interface WarmPlan {
  ```
- `WarmRemoval` ← packages/runtime-sandbox/src/warm.ts:203 [EXTRACTED]
  ```
  export interface WarmRemoval {
  ```
- `WrapperEnd` ← packages/runtime-sandbox/src/wrapper.ts:21 [EXTRACTED]
  ```
  export type WrapperEnd = { code: number } | { signal: NodeJS.Signals };
  ```
- `NewInstance` ← packages/runtime-t3/src/add-instance.ts:28 [EXTRACTED]
  ```
  export interface NewInstance {
  ```
- `AddedInstance` ← packages/runtime-t3/src/add-instance.ts:40 [EXTRACTED]
  ```
  export type AddedInstance =
  ```
- `AddedProject` ← packages/runtime-t3/src/added-projects.ts:21 [EXTRACTED]
  ```
  export type AddedProject = z.infer<typeof AddedProjectSchema>;
  ```
- `AddedProjects` ← packages/runtime-t3/src/added-projects.ts:23 [EXTRACTED]
  ```
  export interface AddedProjects {
  ```
- `SignInAccess` ← packages/runtime-t3/src/auth.ts:37 [EXTRACTED]
  ```
  export type SignInAccess = Extract<StepMode, 'auto' | 'full-access'>;
  ```
- `SignIn` ← packages/runtime-t3/src/auth.ts:157 [EXTRACTED]
  ```
  export interface SignIn {
  ```
- `SilentSignIn` ← packages/runtime-t3/src/auth.ts:294 [EXTRACTED]
  ```
  export type SilentSignIn = { ok: true } | { ok: false; reason: string };
  ```
- `Running` ← packages/runtime-t3/src/conversation.ts:99 [EXTRACTED]
  ```
  export interface Running {
  ```
- `PromptRequest` ← packages/runtime-t3/src/conversation.ts:114 [EXTRACTED]
  ```
  export type PromptRequest = Extract<RuntimeRequest, { type: 'prompt' }>;
  ```
- `Conversations` ← packages/runtime-t3/src/conversation.ts:1124 [EXTRACTED]
  ```
  export type Conversations = ReturnType<typeof conversations>;
  ```
- `NotAdded` ← packages/runtime-t3/src/instances.ts:25 [EXTRACTED]
  ```
  export type NotAdded = { ok: false; kind: 'not-added'; why: string } | { ok: false; kind: 'not-ready'; id: string; why: string };
  ```
- `InstanceAdder` ← packages/runtime-t3/src/instances.ts:217 [EXTRACTED]
  ```
  export type InstanceAdder = ReturnType<typeof instanceAdder>;
  ```
- `ThreadRecord` ← packages/runtime-t3/src/journal.ts:67 [EXTRACTED]
  ```
  export type ThreadRecord = z.infer<typeof ThreadSchema>;
  ```
- `LaunchRecord` ← packages/runtime-t3/src/journal.ts:85 [EXTRACTED]
  ```
  export type LaunchRecord = z.infer<typeof LaunchSchema>;
  ```
- `OpRecord` ← packages/runtime-t3/src/journal.ts:121 [EXTRACTED]
  ```
  export type OpRecord = z.infer<typeof OpRecordSchema>;
  ```
- `KeptOp` ← packages/runtime-t3/src/journal.ts:126 [EXTRACTED]
  ```
  export type KeptOp = z.infer<typeof KeptOpSchema>;
  ```
- `PlaceRecord` ← packages/runtime-t3/src/journal.ts:137 [EXTRACTED]
  ```
  export type PlaceRecord = Place & {
  ```
- `PlaceRead` ← packages/runtime-t3/src/journal.ts:147 [EXTRACTED]
  ```
  export type PlaceRead = { kind: 'found'; place: PlaceRecord } | { kind: 'missing' } | { kind: 'unreadable'; file: string; why: string; handle?: string };
  ```
- `Journal` ← packages/runtime-t3/src/journal.ts:158 [EXTRACTED]
  ```
  export interface Journal {
  ```
- `T3Options` ← packages/runtime-t3/src/options.ts:37 [EXTRACTED]
  ```
  export type T3Options = z.infer<typeof OptionsSchema>;
  ```
- `WorkMode` ← packages/runtime-t3/src/runtime.ts:47 [EXTRACTED]
  ```
  export type WorkMode = Exclude<RuntimeMode, 'recover' | 'check'>;
  ```
- `Connected` ← packages/runtime-t3/src/runtime.ts:49 [EXTRACTED]
  ```
  export interface Connected {
  ```
- `ServeOptions` ← packages/runtime-t3/src/runtime.ts:56 [EXTRACTED]
  ```
  export interface ServeOptions {
  ```
- `Reached` ← packages/runtime-t3/src/runtime.ts:93 [EXTRACTED]
  ```
  export interface Reached {
  ```
- `Session` ← packages/runtime-t3/src/runtime.ts:101 [EXTRACTED]
  ```
  export interface Session extends Reached {
  ```
- `Reach` ← packages/runtime-t3/src/runtime.ts:122 [EXTRACTED]
  ```
  export type Reach = { ok: true; reached: Reached } | { ok: false; failure: RuntimeFailure };
  ```
- `Serving` ← packages/runtime-t3/src/runtime.ts:125 [EXTRACTED]
  ```
  export interface Serving {
  ```
- `Driver` ← packages/runtime-t3/src/sessions.ts:39 [EXTRACTED]
  ```
  export type Driver = keyof typeof DRIVERS;
  ```
- `ToolId` ← packages/runtime-t3/src/sessions.ts:41 [EXTRACTED]
  ```
  export type ToolId = (typeof DRIVERS)[Driver]['tool'];
  ```
- `KeptSession` ← packages/runtime-t3/src/sessions.ts:74 [EXTRACTED]
  ```
  export type KeptSession = { id: string; transcript?: string };
  ```
- `SessionLookup` ← packages/runtime-t3/src/sessions.ts:80 [EXTRACTED]
  ```
  export type SessionLookup =
  ```
- `T3RuntimeMode` ← packages/runtime-t3/src/settings.ts:16 [EXTRACTED]
  ```
  export type T3RuntimeMode = (typeof RUNTIME_MODES)[number];
  ```
- `ModelSelection` ← packages/runtime-t3/src/settings.ts:24 [EXTRACTED]
  ```
  export type ModelSelection = z.infer<typeof ModelSelectionSchema>;
  ```
- `ProjectScript` ← packages/runtime-t3/src/settings.ts:28 [EXTRACTED]
  ```
  export type ProjectScript = z.infer<typeof ScriptSchema>;
  ```
- `ProjectSettings` ← packages/runtime-t3/src/settings.ts:63 [EXTRACTED]
  ```
  export interface ProjectSettings {
  ```
- `T3Command` ← packages/runtime-t3/src/t3-command.ts:36 [EXTRACTED]
  ```
  export interface T3Command {
  ```
- `Environment` ← packages/runtime-t3/src/t3.ts:16 [EXTRACTED]
  ```
  export type Environment = z.infer<typeof EnvironmentSchema>;
  ```
- `Provider` ← packages/runtime-t3/src/t3.ts:41 [EXTRACTED]
  ```
  export type Provider = z.infer<typeof ProviderSchema>;
  ```
- `Project` ← packages/runtime-t3/src/t3.ts:56 [EXTRACTED]
  ```
  export type Project = z.infer<typeof ProjectSchema>;
  ```
- `EnvironmentLink` ← packages/runtime-t3/src/t3.ts:61 [EXTRACTED]
  ```
  export type EnvironmentLink = z.infer<typeof EnvironmentLinkSchema>;
  ```
- `Waited` ← packages/runtime-t3/src/t3.ts:83 [EXTRACTED]
  ```
  export type Waited = z.infer<typeof WaitedSchema>;
  ```
- `ThreadShell` ← packages/runtime-t3/src/t3.ts:101 [EXTRACTED]
  ```
  export type ThreadShell = z.infer<typeof ThreadShellSchema>;
  ```
- `ListedThread` ← packages/runtime-t3/src/t3.ts:117 [EXTRACTED]
  ```
  export type ListedThread = z.infer<typeof ListedThreadSchema>;
  ```
- `StepMode` ← packages/runtime-t3/src/t3.ts:145 [EXTRACTED]
  ```
  export type StepMode = (typeof STEP_MODES)[number];
  ```
- `NewThread` ← packages/runtime-t3/src/t3.ts:148 [EXTRACTED]
  ```
  export interface NewThread {
  ```
- `Launch` ← packages/runtime-t3/src/t3.ts:162 [EXTRACTED]
  ```
  export interface Launch extends NewThread {
  ```
- `T3` ← packages/runtime-t3/src/t3.ts:222 [EXTRACTED]
  ```
  export interface T3 {
  ```
- `ServedTool` ← packages/runtime-t3/src/tool-instances.ts:27 [EXTRACTED]
  ```
  export type ServedTool = Pick<InitInstance, 'name' | 'tool' | 'command' | 'home'>;
  ```
- `InstanceLookup` ← packages/runtime-t3/src/tool-instances.ts:30 [EXTRACTED]
  ```
  export interface InstanceLookup {
  ```
- `ServedInstances` ← packages/runtime-t3/src/tool-instances.ts:44 [EXTRACTED]
  ```
  export interface ServedInstances {
  ```
- `Line` ← packages/runtime-testing/src/connect.ts:10 [EXTRACTED]
  ```
  export type Line = z.infer<typeof LineSchema>;
  ```
- `Connection` ← packages/runtime-testing/src/connect.ts:12 [EXTRACTED]
  ```
  export interface Connection {
  ```
- `ConfinedDeps` ← packages/runtime-tools/src/confined.ts:20 [EXTRACTED]
  ```
  export interface ConfinedDeps {
  ```
- `ConfinedAttempt` ← packages/runtime-tools/src/confined.ts:40 [EXTRACTED]
  ```
  export interface ConfinedAttempt { readonly run: string; readonly attempt: string }
  ```
- `ConfinedLoginHold` ← packages/runtime-tools/src/confined.ts:43 [EXTRACTED]
  ```
  export type ConfinedLoginHold =
  ```
- `ConfinedFamily` ← packages/runtime-tools/src/confined.ts:48 [EXTRACTED]
  ```
  export type ConfinedFamily = 'claude' | 'codex' | 'codebuddy' | 'cursor' | 'pi' | 'agy' | 'opencode';
  ```
- `ConfinedRequest` ← packages/runtime-tools/src/confined.ts:51 [EXTRACTED]
  ```
  export interface ConfinedRequest {
  ```
- `ConfinedFailureCode` ← packages/runtime-tools/src/confined.ts:82 [EXTRACTED]
  ```
  export type ConfinedFailureCode = 'confined_tool_unavailable' | 'confined_failed' | 'confined_reply_invalid' | 'usage_limited' | 'login_held' | 'login_missing' | 'login_not_written_back';
  ```
- `ConfinedFailure` ← packages/runtime-tools/src/confined.ts:85 [EXTRACTED]
  ```
  export type ConfinedFailure = { ok: false; code: ConfinedFailureCode; message: string; raw?: string; reported?: string; usage?: ConfinedUsage };
  ```
- `ConfinedEnd` ← packages/runtime-tools/src/confined.ts:88 [EXTRACTED]
  ```
  export type ConfinedEnd =
  ```
- `StepRun` ← packages/runtime-tools/src/step.ts:11 [EXTRACTED]
  ```
  export interface StepRun extends StepLaunchInput, StepLimits {
  ```
- `StepRunResult` ← packages/runtime-tools/src/step.ts:20 [EXTRACTED]
  ```
  export type StepRunResult = StepLaunchResult;
  ```
- `StepLauncher` ← packages/runtime-tools/src/step.ts:23 [EXTRACTED]
  ```
  export interface StepLauncher {
  ```
- `ToolSpawn` ← packages/runtime-tools/src/step.ts:29 [EXTRACTED]
  ```
  export type ToolSpawn = (command: string, args: string[], options: SpawnOptions) => ChildProcess;
  ```
- `ToolResolve` ← packages/runtime-tools/src/step.ts:31 [EXTRACTED]
  ```
  export type ToolResolve = (command: string) => string | null;
  ```
- `StepLaunchDeps` ← packages/runtime-tools/src/step.ts:37 [EXTRACTED]
  ```
  export interface StepLaunchDeps {
  ```
- `ExecOptions` ← packages/shared/src/exec.ts:16 [EXTRACTED]
  ```
  export interface ExecOptions {
  ```
- `ExecResult` ← packages/shared/src/exec.ts:23 [EXTRACTED]
  ```
  export interface ExecResult {
  ```
- `CommandExecutor` ← packages/shared/src/exec.ts:29 [EXTRACTED]
  ```
  export type CommandExecutor = (
  ```
- `BatchLaunch` ← packages/shared/src/exec.ts:228 [EXTRACTED]
  ```
  export type BatchLaunch =
  ```
- `Processes` ← packages/shared/src/exec.ts:308 [EXTRACTED]
  ```
  export interface Processes {
  ```
- `FsFailure` ← packages/shared/src/fs-failure.ts:14 [EXTRACTED]
  ```
  export type FsFailure = z.infer<typeof FsFailureSchema>;
  ```
- `JsonValue` ← packages/shared/src/json.ts:6 [EXTRACTED]
  ```
  export type JsonValue = z.infer<typeof JsonValueSchema>;
  ```
- `JsonObject` ← packages/shared/src/json.ts:9 [EXTRACTED]
  ```
  export type JsonObject = { [key: string]: JsonValue };
  ```
- `JsonlRecord` ← packages/shared/src/json.ts:15 [EXTRACTED]
  ```
  export type JsonlRecord = JsonObject;
  ```
- `JsonSyntax` ← packages/shared/src/json.ts:46 [EXTRACTED]
  ```
  export type JsonSyntax = 'json' | 'jsonc' | 'json-comments' | 'json5';
  ```
- `LookPathOptions` ← packages/shared/src/lookpath.ts:12 [EXTRACTED]
  ```
  export interface LookPathOptions {
  ```
- `ProcessRead` ← packages/shared/src/process-group.ts:28 [EXTRACTED]
  ```
  export interface ProcessRead { readonly ps: readonly string[]; readonly spawned: boolean }
  ```
- `ProcessIdentity` ← packages/shared/src/process-group.ts:207 [EXTRACTED]
  ```
  export type ProcessIdentity = z.infer<typeof ProcessIdentitySchema>;
  ```
- `ProcessVerdict` ← packages/shared/src/process-group.ts:214 [EXTRACTED]
  ```
  export type ProcessVerdict = 'same' | 'other' | 'foreign' | 'unknown';
  ```
- `OwnGroups` ← packages/shared/src/process-group.ts:386 [EXTRACTED]
  ```
  export interface OwnGroups { pgid: number; foreground: number }
  ```
- `SignalOutcome` ← packages/shared/src/process-group.ts:509 [EXTRACTED]
  ```
  export type SignalOutcome = 'sent' | 'gone' | 'denied' | 'refused';
  ```
- `RedactOptions` ← packages/shared/src/redact.ts:113 [EXTRACTED]
  ```
  export interface RedactOptions {
  ```
- `NotRegularFileKind` ← packages/shared/src/regular-file.ts:22 [EXTRACTED]
  ```
  export type NotRegularFileKind = 'a link' | 'a pipe' | 'a directory' | 'a device' | 'a socket' | 'a special file';
  ```
- `CopyTreeOptions` ← packages/shared/src/regular-file.ts:284 [EXTRACTED]
  ```
  export interface CopyTreeOptions {
  ```
- `CbRecord` ← packages/tool-codebuddy/src/codebuddy-adapter.ts:163 [EXTRACTED]
  ```
  export type CbRecord = z.infer<typeof CbRecordSchema>;
  ```
- `CbFunctionCallProviderData` ← packages/tool-codebuddy/src/codebuddy-adapter.ts:171 [EXTRACTED]
  ```
  export interface CbFunctionCallProviderData {
  ```
- `CbWrittenLine` ← packages/tool-codebuddy/src/codebuddy-adapter.ts:187 [EXTRACTED]
  ```
  export type CbWrittenLine =
  ```
- `IdeConversation` ← packages/tool-codebuddy/src/ide-history.ts:51 [EXTRACTED]
  ```
  export type IdeConversation = {
  ```
- `IdeConversationRead` ← packages/tool-codebuddy/src/ide-history.ts:69 [EXTRACTED]
  ```
  export type IdeConversationRead = z.infer<typeof IdeConversationReadSchema>;
  ```
- `IdeSyncResult` ← packages/tool-codebuddy/src/ide-history.ts:87 [EXTRACTED]
  ```
  export interface IdeSyncResult {
  ```
- `IdeAsset` ← packages/tool-codebuddy/src/ide-history.ts:343 [EXTRACTED]
  ```
  export interface IdeAsset {
  ```
- `IdeBlock` ← packages/tool-codebuddy/src/ide-history.ts:970 [EXTRACTED]
  ```
  export type IdeBlock = z.infer<typeof IdeBlockSchema>;
  ```
- `IdeMessageParsed` ← packages/tool-codebuddy/src/ide-history.ts:973 [EXTRACTED]
  ```
  export interface IdeMessageParsed {
  ```
- `IdeConversationEntry` ← packages/tool-codebuddy/src/ide-history.ts:983 [EXTRACTED]
  ```
  export interface IdeConversationEntry {
  ```
- `RegisterWorkBuddySessionArgs` ← packages/tool-codebuddy/src/workbuddy-store.ts:123 [EXTRACTED]
  ```
  export interface RegisterWorkBuddySessionArgs {
  ```
- `RegisterWorkBuddyResult` ← packages/tool-codebuddy/src/workbuddy-store.ts:137 [EXTRACTED]
  ```
  export interface RegisterWorkBuddyResult {
  ```
- `McpFormat` ← packages/tool-core/src/definition.ts:4 [EXTRACTED]
  ```
  export type McpFormat = 'claude' | 'cursor' | 'buddy' | 'codex' | 'opencode' | 'copilot' | 'pi' | 'muse' | 'agy' | 'openclaw' | 'hermes' | 'dsh';
  ```
- `RuleFormatId` ← packages/tool-core/src/definition.ts:7 [EXTRACTED]
  ```
  export type RuleFormatId = 'cursor-mdc' | 'joycode' | 'copilot-instructions' | 'kiro-steering' | 'qoder' | 'trae' | 'codebuddy' | 'omp' | 'agy';
  ```
- `DescriptorIds` ← packages/tool-core/src/definition.ts:14 [EXTRACTED]
  ```
  export interface DescriptorIds {
  ```
- `Evidence` ← packages/tool-core/src/definition.ts:22 [EXTRACTED]
  ```
  export type Evidence = 'verified' | 'source' | 'docs' | 'assumed';
  ```
- `SkillCall` ← packages/tool-core/src/definition.ts:25 [EXTRACTED]
  ```
  export type SkillCall = { readonly name: string; readonly evidence: Evidence };
  ```
- `PromptForm` ← packages/tool-core/src/definition.ts:32 [EXTRACTED]
  ```
  export type PromptForm = '$name' | 'skill-block' | 'command-uri' | 'markdown-mention' | '/name';
  ```
- `SkillLoad` ← packages/tool-core/src/definition.ts:34 [EXTRACTED]
  ```
  export type SkillLoad =
  ```
- `HomeMove` ← packages/tool-core/src/definition.ts:39 [EXTRACTED]
  ```
  export type HomeMove =
  ```
- `Home` ← packages/tool-core/src/definition.ts:85 [EXTRACTED]
  ```
  export type Home = {
  ```
- `HomeRead` ← packages/tool-core/src/definition.ts:97 [EXTRACTED]
  ```
  export type HomeRead = { readonly base: 'home'; readonly path: string; readonly when?: 'workspaceUnderHome'; readonly evidence: Evidence };
  ```
- `ProjectRead` ← packages/tool-core/src/definition.ts:100 [EXTRACTED]
  ```
  export type ProjectRead = {
  ```
- `CodebuddyConfigFile` ← packages/tool-core/src/definition.ts:108 [EXTRACTED]
  ```
  export type CodebuddyConfigFile = { readonly in: 'codebuddy-config-dir'; readonly path: '.codebuddy.json' };
  ```
- `FirstExistingRead` ← packages/tool-core/src/definition.ts:111 [EXTRACTED]
  ```
  export type FirstExistingRead =
  ```
- `SkillReads` ← packages/tool-core/src/definition.ts:121 [EXTRACTED]
  ```
  export type SkillReads = {
  ```
- `ChannelProbe` ← packages/tool-core/src/definition.ts:136 [EXTRACTED]
  ```
  export type ChannelProbe = 'codex-hooks' | 'zcode-session-start' | 'dsh-session-start' | 'muse-session-start' | 'pi-extension' | 'omp-extension' | 'hermes-plugin';
  ```
- `RunTimeVia` ← packages/tool-core/src/definition.ts:139 [EXTRACTED]
  ```
  export type RunTimeVia = 'session-hook' | 'extension' | 'plugin';
  ```
- `ReadGateKind` ← packages/tool-core/src/definition.ts:146 [EXTRACTED]
  ```
  export type ReadGateKind = 'codex-project-trust' | 'pi-project-trust' | 'muse-workspace-trust' | 'copilot-folder-trust' | 'qoder-folder-trust'
  ```
- `BlocksHeader` ← packages/tool-core/src/definition.ts:151 [EXTRACTED]
  ```
  export type BlocksHeader = 'always-apply' | 'apply-to-all' | 'trigger-always-on' | 'inclusion-always';
  ```
- `RunTime` ← packages/tool-core/src/definition.ts:154 [EXTRACTED]
  ```
  export type RunTime = { readonly channel: RunTimeVia; readonly probe: ChannelProbe; readonly limit?: number; readonly evidence: Evidence };
  ```
- `Activation` ← packages/tool-core/src/definition.ts:161 [EXTRACTED]
  ```
  export type Activation =
  ```
- `RulesDir` ← packages/tool-core/src/definition.ts:166 [EXTRACTED]
  ```
  export type RulesDir<R> = { readonly channel: 'dir'; readonly format: RuleFormatId | 'verbatim'; readonly reads: Reads<R>; readonly activation?: Activation };
  ```
- `RulesInline` ← packages/tool-core/src/definition.ts:169 [EXTRACTED]
  ```
  export type RulesInline = { readonly channel: 'inline'; readonly label: string };
  ```
- `RulesChannels` ← packages/tool-core/src/definition.ts:171 [EXTRACTED]
  ```
  export type RulesChannels = Scoped<RulesDir<HomeRead> | RulesInline, RulesDir<HomeRead | ProjectRead> | RunTime>;
  ```
- `BlocksFile` ← packages/tool-core/src/definition.ts:174 [EXTRACTED]
  ```
  export type BlocksFile = { readonly owned?: true; readonly header?: BlocksHeader } & (
  ```
- `BlocksTarget` ← packages/tool-core/src/definition.ts:189 [EXTRACTED]
  ```
  export type BlocksTarget<R> = {
  ```
- `BlocksChannels` ← packages/tool-core/src/definition.ts:200 [EXTRACTED]
  ```
  export type BlocksChannels = Scoped<BlocksTarget<HomeRead>, BlocksTarget<HomeRead | ProjectRead> | RunTime> & {
  ```
- `AgentsTarget` ← packages/tool-core/src/definition.ts:210 [EXTRACTED]
  ```
  export type AgentsTarget<R> = { readonly reads: Reads<R>; readonly readGates?: readonly ReadGateKind[] };
  ```
- `AgentsChannels` ← packages/tool-core/src/definition.ts:212 [EXTRACTED]
  ```
  export type AgentsChannels = Scoped<AgentsTarget<HomeRead>, AgentsTarget<HomeRead | ProjectRead>>;
  ```
- `McpUser` ← packages/tool-core/src/definition.ts:228 [EXTRACTED]
  ```
  export type McpUser = McpCommon<HomeRead | FirstExistingRead>;
  ```
- `McpProject` ← packages/tool-core/src/definition.ts:230 [EXTRACTED]
  ```
  export type McpProject<TTool extends string = string> = McpCommon<HomeRead | ProjectRead | FirstExistingRead> & {
  ```
- `McpChannels` ← packages/tool-core/src/definition.ts:249 [EXTRACTED]
  ```
  export type McpChannels<TTool extends string = string> = Scoped<McpUser, McpProject<TTool>> & {
  ```
- `HookFormat` ← packages/tool-core/src/definition.ts:255 [EXTRACTED]
  ```
  export type HookFormat = 'claude' | 'cursor' | 'codex' | 'copilot' | 'zcode';
  ```
- `HookSettings` ← packages/tool-core/src/definition.ts:258 [EXTRACTED]
  ```
  export type HookSettings<R> = {
  ```
- `HookAdapterId` ← packages/tool-core/src/definition.ts:268 [EXTRACTED]
  ```
  export type HookAdapterId = 'opencode-plugin' | 'pi-extension' | 'omp-extension' | 'hermes-plugin' | 'openclaw-hook' | 'dsh-hooks' | 'kiro-hooks' | 'agy-hooks';
  ```
- `HookAdapter` ← packages/tool-core/src/definition.ts:270 [EXTRACTED]
  ```
  export type HookAdapter = { readonly channel: 'adapter'; readonly adapter: HookAdapterId; readonly evidence: Evidence; readonly readGates?: readonly ReadGateKind[] };
  ```
- `HooksChannels` ← packages/tool-core/src/definition.ts:277 [EXTRACTED]
  ```
  export type HooksChannels = {
  ```
- `InstallGate` ← packages/tool-core/src/definition.ts:367 [EXTRACTED]
  ```
  export type InstallGate = 'home-edition' | 'home' | 'own-root';
  ```
- `SupportCell` ← packages/tool-core/src/definition.ts:377 [EXTRACTED]
  ```
  export type SupportCell = `${'✓' | '◐' | '✗' | '+' | '—'}${'v' | 's' | 'd' | 't'}` | '?';
  ```
- `Support` ← packages/tool-core/src/definition.ts:380 [EXTRACTED]
  ```
  export type Support = SupportCell | { readonly cell: SupportCell; readonly note: string };
  ```
- `ToolFeatures` ← packages/tool-core/src/definition.ts:383 [EXTRACTED]
  ```
  export type ToolFeatures = {
  ```
- `FolderReach` ← packages/tool-core/src/definition.ts:411 [EXTRACTED]
  ```
  export type FolderReach =
  ```
- `ToolDescriptor` ← packages/tool-core/src/definition.ts:416 [EXTRACTED]
  ```
  export type ToolDescriptor<TIds extends DescriptorIds = DescriptorIds> = {
  ```
- `VersionDetector` ← packages/tool-core/src/detect.ts:8 [EXTRACTED]
  ```
  export type VersionDetector =
  ```
- `VersionProbe` ← packages/tool-core/src/detect.ts:13 [EXTRACTED]
  ```
  export type VersionProbe = (command: string, args: string[]) => Promise<string>;
  ```
- `ToolFamilyFacts` ← packages/tool-core/src/family.ts:12 [EXTRACTED]
  ```
  export interface ToolFamilyFacts {
  ```
- `ToolFamily` ← packages/tool-core/src/family.ts:25 [EXTRACTED]
  ```
  export interface ToolFamily extends ToolFamilyFacts {
  ```
- `ToolInstance` ← packages/tool-core/src/instance.ts:6 [EXTRACTED]
  ```
  export interface ToolInstance<TBase extends string = string> {
  ```
- `ToolInstanceHome` ← packages/tool-core/src/instance.ts:16 [EXTRACTED]
  ```
  export interface ToolInstanceHome {
  ```
- `InstancePlatform` ← packages/tool-core/src/instance.ts:27 [EXTRACTED]
  ```
  export type InstancePlatform = string & { readonly [instancePlatform]: true };
  ```
- `ConfinedAccess` ← packages/tool-core/src/launch.ts:9 [EXTRACTED]
  ```
  export type ConfinedAccess = (typeof ACCESS_LEVELS)[number];
  ```
- `ConfinedLevel` ← packages/tool-core/src/launch.ts:14 [EXTRACTED]
  ```
  export type ConfinedLevel = (typeof CONFINED_LEVELS)[number];
  ```
- `CallReading` ← packages/tool-core/src/launch.ts:17 [EXTRACTED]
  ```
  export type CallReading = { ok: true; text: string; tokens?: TokenUsage; session?: string } | { ok: false; message?: string };
  ```
- `CallOutput` ← packages/tool-core/src/launch.ts:20 [EXTRACTED]
  ```
  export interface CallOutput {
  ```
- `CallInput` ← packages/tool-core/src/launch.ts:42 [EXTRACTED]
  ```
  export interface CallInput {
  ```
- `CallLaunch` ← packages/tool-core/src/launch.ts:53 [EXTRACTED]
  ```
  export interface CallLaunch {
  ```
- `UnattendedLaunch` ← packages/tool-core/src/launch.ts:76 [EXTRACTED]
  ```
  export type UnattendedLaunch = { readonly args: readonly string[]; readonly evidence: Evidence } | 'none';
  ```
- `StepArgsInput` ← packages/tool-core/src/launch.ts:79 [EXTRACTED]
  ```
  export interface StepArgsInput {
  ```
- `StepArgsHow` ← packages/tool-core/src/launch.ts:99 [EXTRACTED]
  ```
  export interface StepArgsHow {
  ```
- `StepLaunch` ← packages/tool-core/src/launch.ts:109 [EXTRACTED]
  ```
  export interface StepLaunch {
  ```
- `ConfinedLaunch` ← packages/tool-core/src/launch.ts:131 [EXTRACTED]
  ```
  export interface ConfinedLaunch {
  ```
- `GatewayVariables` ← packages/tool-core/src/launch.ts:144 [EXTRACTED]
  ```
  export interface GatewayVariables {
  ```
- `SignInVariables` ← packages/tool-core/src/launch.ts:154 [EXTRACTED]
  ```
  export interface SignInVariables {
  ```
- `LaunchAdapter` ← packages/tool-core/src/launch.ts:161 [EXTRACTED]
  ```
  export interface LaunchAdapter {
  ```
- `RegisteredTool` ← packages/tool-core/src/registry.ts:7 [EXTRACTED]
  ```
  export interface RegisteredTool<TPlatform extends string = string> {
  ```
- `ResolvedTool` ← packages/tool-core/src/registry.ts:12 [EXTRACTED]
  ```
  export interface ResolvedTool<TId extends string, TInstance extends ToolInstance<TId> = ToolInstance<TId>> {
  ```
- `ToolRegistry` ← packages/tool-core/src/registry.ts:19 [EXTRACTED]
  ```
  export interface ToolRegistry<TTools, TPlatform extends string, TInstance extends ToolInstance<keyof TTools & string> = ToolInstance<keyof TTools & string>> {
  ```
- `TokenUsage` ← packages/tool-core/src/stdout.ts:5 [EXTRACTED]
  ```
  export interface TokenUsage {
  ```
- `ConfinedUsage` ← packages/tool-core/src/stdout.ts:21 [EXTRACTED]
  ```
  export type ConfinedUsage = z.infer<typeof ConfinedUsageSchema>;
  ```
- `ToolReport` ← packages/tool-core/src/stdout.ts:24 [EXTRACTED]
  ```
  export interface ToolReport {
  ```
- `ErrorKind` ← packages/tool-core/src/stdout.ts:44 [EXTRACTED]
  ```
  export type ErrorKind = 'usage_limit' | 'other';
  ```
- `AgyRun` ← packages/tool-core/src/stdout.ts:308 [EXTRACTED]
  ```
  export interface AgyRun {
  ```
- `StepTokenFormat` ← packages/tool-core/src/step-usage.ts:19 [EXTRACTED]
  ```
  export type StepTokenFormat = keyof typeof STEP_FORMATS;
  ```
- `Unmeasured` ← packages/tool-core/src/step-usage.ts:25 [EXTRACTED]
  ```
  export type Unmeasured = { cause: string; next: string };
  ```
- `StepUsage` ← packages/tool-core/src/step-usage.ts:28 [EXTRACTED]
  ```
  export type StepUsage = { kind: 'measured'; usage: ReportedTokens } | { kind: 'unmeasured'; why: Unmeasured };
  ```
- `TokenUsage` ← packages/tool-core/src/tokens.ts:15 [EXTRACTED]
  ```
  export interface TokenUsage {
  ```
- `TokenSnapshotScope` ← packages/tool-core/src/tokens.ts:27 [EXTRACTED]
  ```
  export type TokenSnapshotScope = 'session' | 'transcript';
  ```
- `TokenSpeed` ← packages/tool-core/src/tokens.ts:52 [EXTRACTED]
  ```
  export type TokenSpeed = 'standard' | 'fast' | 'flex';
  ```
- `TokenSource` ← packages/tool-core/src/tokens.ts:59 [EXTRACTED]
  ```
  export type TokenSource = {
  ```
- `TokenRequest` ← packages/tool-core/src/tokens.ts:68 [EXTRACTED]
  ```
  export type TokenRequest = {
  ```
- `TokenReading` ← packages/tool-core/src/tokens.ts:85 [EXTRACTED]
  ```
  export type TokenReading = {
  ```
- `TokenFormat` ← packages/tool-core/src/tokens.ts:98 [EXTRACTED]
  ```
  export type TokenFormat = (source: TokenSource, processes: Processes) => Promise<TokenReading>;
  ```
- `CursorComposerTool` ← packages/tool-cursor/src/cursor-store.ts:265 [EXTRACTED]
  ```
  export interface CursorComposerTool {
  ```
- `CursorComposerMessage` ← packages/tool-cursor/src/cursor-store.ts:278 [EXTRACTED]
  ```
  export interface CursorComposerMessage {
  ```
- `RegisterCursorComposerArgs` ← packages/tool-cursor/src/cursor-store.ts:293 [EXTRACTED]
  ```
  export interface RegisterCursorComposerArgs {
  ```
- `RegisterResult` ← packages/tool-cursor/src/cursor-store.ts:573 [EXTRACTED]
  ```
  export interface RegisterResult {
  ```
- `HeadlessRun` ← packages/tool-launch/src/call-launch.ts:10 [EXTRACTED]
  ```
  export interface HeadlessRun {
  ```
- `HeadlessProcess` ← packages/tool-launch/src/call-launch.ts:19 [EXTRACTED]
  ```
  export interface HeadlessProcess {
  ```
- `HeadlessStarter` ← packages/tool-launch/src/call-launch.ts:28 [EXTRACTED]
  ```
  export type HeadlessStarter = (launch: { stdin: string; onOutput: (text: string, stream: 'stdout' | 'stderr') => void }) => HeadlessProcess | { notStarted: string };
  ```
- `CallTool` ← packages/tool-launch/src/call-launch.ts:87 [EXTRACTED]
  ```
  export interface CallTool {
  ```
- `CallLaunchHost` ← packages/tool-launch/src/call-launch.ts:95 [EXTRACTED]
  ```
  export interface CallLaunchHost {
  ```
- `CallEnd` ← packages/tool-launch/src/call-launch.ts:100 [EXTRACTED]
  ```
  export type CallEnd =
  ```
- `ConfinedArgsInput` ← packages/tool-launch/src/confined-launch.ts:28 [EXTRACTED]
  ```
  export type ConfinedArgsInput =
  ```
- `StepFamily` ← packages/tool-launch/src/run-step-launch.ts:12 [EXTRACTED]
  ```
  export type StepFamily = 'claude' | 'codebuddy' | 'codex' | 'opencode' | 'agy';
  ```
- `StepFailure` ← packages/tool-launch/src/run-step-launch.ts:15 [EXTRACTED]
  ```
  export interface StepFailure {
  ```
- `StepResultBody` ← packages/tool-launch/src/run-step-launch.ts:21 [EXTRACTED]
  ```
  export interface StepResultBody {
  ```
- `StepStop` ← packages/tool-launch/src/run-step-launch.ts:27 [EXTRACTED]
  ```
  export type StepStop = 'timeout' | 'budget' | 'max_turns';
  ```
- `StepTool` ← packages/tool-launch/src/run-step-launch.ts:30 [EXTRACTED]
  ```
  export interface StepTool {
  ```
- `AgentSetting` ← packages/tool-launch/src/run-step-launch.ts:38 [EXTRACTED]
  ```
  export type AgentSetting = string | number | bigint | boolean | null | Date | readonly AgentSetting[] | { readonly [key: string]: AgentSetting };
  ```
- `StepLaunchInput` ← packages/tool-launch/src/run-step-launch.ts:41 [EXTRACTED]
  ```
  export interface StepLaunchInput {
  ```
- `StepLimits` ← packages/tool-launch/src/run-step-launch.ts:69 [EXTRACTED]
  ```
  export interface StepLimits {
  ```
- `StepLaunchHost` ← packages/tool-launch/src/run-step-launch.ts:83 [EXTRACTED]
  ```
  export interface StepLaunchHost {
  ```
- `ToolClosed` ← packages/tool-launch/src/run-step-launch.ts:93 [EXTRACTED]
  ```
  export type ToolClosed = { exitCode: number; stdout: string; error?: NodeJS.ErrnoException } | { failure: StepFailure };
  ```
- `ToolProcess` ← packages/tool-launch/src/run-step-launch.ts:96 [EXTRACTED]
  ```
  export interface ToolProcess {
  ```
- `ToolLauncher` ← packages/tool-launch/src/run-step-launch.ts:116 [EXTRACTED]
  ```
  export type ToolLauncher = ToolStart & { readonly [conformantLauncher]: true };
  ```
- `StepLaunchResult` ← packages/tool-launch/src/run-step-launch.ts:132 [EXTRACTED]
  ```
  export type StepLaunchResult =
  ```
- `RecordedCall` ← packages/tool-testing/src/conformance.ts:23 [EXTRACTED]
  ```
  export interface RecordedCall {
  ```
- `RecordedUsage` ← packages/tool-testing/src/conformance.ts:29 [EXTRACTED]
  ```
  export interface RecordedUsage {
  ```
- `RecordedVersion` ← packages/tool-testing/src/conformance.ts:39 [EXTRACTED]
  ```
  export type RecordedVersion = { readonly command: string; readonly stdout: string; readonly version: string } | { readonly unrecorded: string };
  ```
- `FamilyRecordings` ← packages/tool-testing/src/conformance.ts:42 [EXTRACTED]
  ```
  export interface FamilyRecordings {
  ```
- `FakeAgentBehaviour` ← packages/tool-testing/src/fake-agent.ts:22 [EXTRACTED]
  ```
  export type FakeAgentBehaviour = keyof typeof FAKE_AGENT_MARKERS;
  ```
- `FakeAgentRecording` ← packages/tool-testing/src/fake-agent.ts:31 [EXTRACTED]
  ```
  export interface FakeAgentRecording {
  ```
- `FakeAgentOptions` ← packages/tool-testing/src/fake-agent.ts:39 [EXTRACTED]
  ```
  export interface FakeAgentOptions {
  ```
- `FakeAgentCall` ← packages/tool-testing/src/fake-agent.ts:59 [EXTRACTED]
  ```
  export type FakeAgentCall = z.infer<typeof Call>;
  ```
- `FakeAgent` ← packages/tool-testing/src/fake-agent.ts:61 [EXTRACTED]
  ```
  export interface FakeAgent {
  ```
- `ReplayTarget` ← packages/tool-testing/src/replay-transcript.ts:6 [EXTRACTED]
  ```
  export interface ReplayTarget {
  ```
- `RecordedTranscript` ← packages/tool-testing/src/replay-transcript.ts:17 [EXTRACTED]
  ```
  export type RecordedTranscript = {
  ```
- `Proc` ← scripts/verify/leftovers/processes.ts:8 [EXTRACTED]
  ```
  export interface Proc {
  ```
- `PackageInstallContext` ← src/pkg/adapters/base.ts:5 [EXTRACTED]
  ```
  export interface PackageInstallContext {
  ```
- `ClaudePluginListItem` ← src/pkg/adapters/claude-plugin.ts:30 [EXTRACTED]
  ```
  export type ClaudePluginListItem = z.infer<typeof ClaudePluginListItemSchema>;
  ```
- `ClaudeMarketplaceListItem` ← src/pkg/adapters/claude-plugin.ts:42 [EXTRACTED]
  ```
  export type ClaudeMarketplaceListItem = z.infer<typeof ClaudeMarketplaceListItemSchema>;
  ```
- `ClaudeLockSection` ← src/pkg/adapters/claude-plugin.ts:44 [EXTRACTED]
  ```
  export interface ClaudeLockSection {
  ```
- `CnbExecResult` ← src/providers/cnb/cnb-cli.ts:45 [EXTRACTED]
  ```
  export interface CnbExecResult {
  ```
- `CnbPullCreateOptions` ← src/providers/cnb/cnb-cli.ts:388 [EXTRACTED]
  ```
  export interface CnbPullCreateOptions {
  ```
- `GitCodePullCreateOptions` ← src/providers/gitcode/gitcode-api.ts:292 [EXTRACTED]
  ```
  export interface GitCodePullCreateOptions {
  ```
- `GhExecResult` ← src/providers/github/gh-cli.ts:52 [EXTRACTED]
  ```
  export interface GhExecResult {
  ```
- `GhPrCreateOptions` ← src/providers/github/gh-cli.ts:542 [EXTRACTED]
  ```
  export interface GhPrCreateOptions {
  ```
- `GitLabMrCreateOptions` ← src/providers/gitlab/gitlab-api.ts:327 [EXTRACTED]
  ```
  export interface GitLabMrCreateOptions {
  ```
- `ParsedGitLabMR` ← src/providers/gitlab/mr-fetch.ts:14 [EXTRACTED]
  ```
  export interface ParsedGitLabMR {
  ```
- `GfExecResult` ← src/providers/tgit/gf-cli.ts:42 [EXTRACTED]
  ```
  export interface GfExecResult {
  ```
- `GfMrCreateOptions` ← src/providers/tgit/gf-cli.ts:500 [EXTRACTED]
  ```
  export interface GfMrCreateOptions {
  ```
- `TGitAuthScheme` ← src/providers/tgit/rest-auth.ts:5 [EXTRACTED]
  ```
  export type TGitAuthScheme = 'private-token' | 'bearer';
  ```
- `TGitCredential` ← src/providers/tgit/rest-auth.ts:8 [EXTRACTED]
  ```
  export interface TGitCredential {
  ```
- `TGitAuthHeaders` ← src/providers/tgit/rest-auth.ts:14 [EXTRACTED]
  ```
  export type TGitAuthHeaders = { Authorization: string } | { 'PRIVATE-TOKEN': string };
  ```
- `TGitFetchInit` ← src/providers/tgit/rest-auth.ts:17 [EXTRACTED]
  ```
  export type TGitFetchInit = Omit<RequestInit, 'headers'> & { headers?: Record<string, string> };
  ```
- `SessionPlatform` ← src/session-flow/adapters/platform-facts.ts:30 [EXTRACTED]
  ```
  export type SessionPlatform = keyof typeof SESSION_PLATFORM_FACTS;
  ```
- `StoredSessionPlatform` ← src/session-flow/adapters/platform-facts.ts:33 [EXTRACTED]
  ```
  export type StoredSessionPlatform = {
  ```
- `DomainGroup` ← src/wiki-engine/adapters/templates.ts:1 [EXTRACTED]
  ```
  export interface DomainGroup {
  ```
- `ProjectEntry` ← src/wiki-engine/adapters/templates.ts:7 [EXTRACTED]
  ```
  export interface ProjectEntry {
  ```
- `ModuleEntry` ← src/wiki-engine/adapters/templates.ts:14 [EXTRACTED]
  ```
  export interface ModuleEntry {
  ```
- `IndexStats` ← src/wiki-engine/adapters/templates.ts:102 [EXTRACTED]
  ```
  export interface IndexStats {
  ```
- `GraphReadmeOptions` ← src/wiki-engine/adapters/templates.ts:183 [EXTRACTED]
  ```
  export interface GraphReadmeOptions {
  ```
- `SourceManifest` ← src/wiki-engine/code-knowledge/code-collector.ts:58 [EXTRACTED]
  ```
  export type SourceManifest = z.infer<typeof SourceManifestSchema>;
  ```
- `CodeCollectedFile` ← src/wiki-engine/code-knowledge/code-collector.ts:60 [EXTRACTED]
  ```
  export interface CodeCollectedFile {
  ```
- `CodeCollectionManifest` ← src/wiki-engine/code-knowledge/code-collector.ts:88 [EXTRACTED]
  ```
  export interface CodeCollectionManifest {
  ```
- `CollectCodeOptions` ← src/wiki-engine/code-knowledge/code-collector.ts:96 [EXTRACTED]
  ```
  export interface CollectCodeOptions {
  ```
- `RepoEntry` ← src/wiki-engine/code-knowledge/code-collector.ts:287 [EXTRACTED]
  ```
  export interface RepoEntry {
  ```
- `MultiRepoCollectOptions` ← src/wiki-engine/code-knowledge/code-collector.ts:293 [EXTRACTED]
  ```
  export interface MultiRepoCollectOptions {
  ```
- `MultiRepoManifest` ← src/wiki-engine/code-knowledge/code-collector.ts:299 [EXTRACTED]
  ```
  export interface MultiRepoManifest {
  ```
- `CodeFact` ← src/wiki-engine/code-knowledge/code-extractors.ts:5 [EXTRACTED]
  ```
  export interface CodeFact {
  ```
- `CodeFactKind` ← src/wiki-engine/code-knowledge/code-fact-kind.ts:2 [EXTRACTED]
  ```
  export type CodeFactKind = "component" | "interface" | "config" | "error" | "data" | "style" | "relation";
  ```
- `CodeEvidenceType` ← src/wiki-engine/code-knowledge/code-fact-kind.ts:4 [EXTRACTED]
  ```
  export type CodeEvidenceType = "definition" | "implementation" | "usage" | "schema" | "config";
  ```
- `CodeIncrementalChange` ← src/wiki-engine/code-knowledge/code-incremental.ts:9 [EXTRACTED]
  ```
  export interface CodeIncrementalChange {
  ```
- `RelationType` ← src/wiki-engine/core/graph-index.schema.ts:28 [EXTRACTED]
  ```
  export type RelationType = (typeof RELATION_TYPES)[number];
  ```
- `GraphNode` ← src/wiki-engine/core/graph-index.schema.ts:30 [EXTRACTED]
  ```
  export interface GraphNode {
  ```
- `GraphEdgeSource` ← src/wiki-engine/core/graph-index.schema.ts:64 [EXTRACTED]
  ```
  export type GraphEdgeSource = (typeof GRAPH_EDGE_SOURCES)[number];
  ```
- `GraphEdge` ← src/wiki-engine/core/graph-index.schema.ts:88 [EXTRACTED]
  ```
  export interface GraphEdge {
  ```
- `GraphIndex` ← src/wiki-engine/core/graph-index.schema.ts:134 [EXTRACTED]
  ```
  export interface GraphIndex {
  ```
- `GraphValidationIssue` ← src/wiki-engine/core/graph-index.schema.ts:366 [EXTRACTED]
  ```
  export interface GraphValidationIssue {
  ```
- `GraphValidationResult` ← src/wiki-engine/core/graph-index.schema.ts:371 [EXTRACTED]
  ```
  export interface GraphValidationResult {
  ```
- `GraphHealthMetrics` ← src/wiki-engine/core/graph-index.schema.ts:447 [EXTRACTED]
  ```
  export interface GraphHealthMetrics {
  ```
- `WikiCategory` ← src/wiki-engine/core/wiki-protocol.ts:3 [EXTRACTED]
  ```
  export type WikiCategory =
  ```
- `WikiConfidence` ← src/wiki-engine/core/wiki-protocol.ts:20 [EXTRACTED]
  ```
  export type WikiConfidence = "EXTRACTED" | "INFERRED" | "AMBIGUOUS";
  ```
- `WikiReviewState` ← src/wiki-engine/core/wiki-protocol.ts:22 [EXTRACTED]
  ```
  export type WikiReviewState = "draft" | "needs-review" | "accepted";
  ```
- `WikiPageStatus` ← src/wiki-engine/core/wiki-protocol.ts:24 [EXTRACTED]
  ```
  export type WikiPageStatus = "draft" | "usable" | "stale" | "deprecated";
  ```
- `WikiEvidenceType` ← src/wiki-engine/core/wiki-protocol.ts:32 [EXTRACTED]
  ```
  export type WikiEvidenceType = "definition" | "implementation" | "usage" | "schema" | "config";
  ```
- `WikiEvidence` ← src/wiki-engine/core/wiki-protocol.ts:34 [EXTRACTED]
  ```
  export interface WikiEvidence {
  ```
- `WikiPageMetadata` ← src/wiki-engine/core/wiki-protocol.ts:48 [EXTRACTED]
  ```
  export interface WikiPageMetadata {
  ```
- `WikiPageDraft` ← src/wiki-engine/core/wiki-protocol.ts:66 [EXTRACTED]
  ```
  export interface WikiPageDraft {
  ```
- `LocalAiCommandIssue` ← src/wiki-engine/core/wiki-protocol.ts:75 [EXTRACTED]
  ```
  export interface LocalAiCommandIssue {
  ```
- `LocalAiCommandResult` ← src/wiki-engine/core/wiki-protocol.ts:82 [EXTRACTED]
  ```
  export interface LocalAiCommandResult {
  ```
- `LocalCompilePhase` ← src/wiki-engine/core/wiki-protocol.ts:96 [EXTRACTED]
  ```
  export type LocalCompilePhase =
  ```
- `LocalCompileProgress` ← src/wiki-engine/core/wiki-protocol.ts:108 [EXTRACTED]
  ```
  export interface LocalCompileProgress {
  ```
- `DeliveryExpectation` ← src/workflow/conformance/delivery.ts:2 [EXTRACTED]
  ```
  export interface DeliveryExpectation {
  ```
- `DeliveryConformanceScenario` ← src/workflow/conformance/delivery.ts:25 [EXTRACTED]
  ```
  export interface DeliveryConformanceScenario {
  ```
- `FixCiConformanceScenario` ← src/workflow/conformance/delivery.ts:99 [EXTRACTED]
  ```
  export interface FixCiConformanceScenario {
  ```
- `GitConformanceName` ← src/workflow/conformance/git.ts:4 [EXTRACTED]
  ```
  export type GitConformanceName = 'base.commit' | 'base.ref' | `steps.${string}.commit` | `steps.${string}.branch`;
  ```
- `GitConformanceScenario` ← src/workflow/conformance/git.ts:15 [EXTRACTED]
  ```
  export interface GitConformanceScenario {
  ```
- `Generated` ← src/workflow/discovery/generated-marker.ts:29 [EXTRACTED]
  ```
  export type Generated = { kind: 'ours'; name: string; edited: boolean } | { kind: 'theirs' };
  ```
- `AdvertisedWorkflow` ← src/workflow/discovery/render.ts:7 [EXTRACTED]
  ```
  export interface AdvertisedWorkflow {
  ```
- `StepFence` ← src/workflow/fleet/fence.ts:39 [EXTRACTED]
  ```
  export interface StepFence {
  ```
- `FencedCommand` ← src/workflow/fleet/fence.ts:50 [EXTRACTED]
  ```
  export type FencedCommand = { kind: 'group'; id: number } | { kind: 'tree'; pid: number };
  ```
- `GuardianFs` ← src/workflow/fleet/fence.ts:83 [EXTRACTED]
  ```
  export type GuardianFs = {
  ```
- `HeardAnswer` ← src/workflow/fleet/gate.ts:10 [EXTRACTED]
  ```
  export type HeardAnswer = { write: string; question: ExecQuestion; answer: ExecAnswer };
  ```
- `GateQuestions` ← src/workflow/fleet/gate.ts:12 [EXTRACTED]
  ```
  export type GateQuestions = {
  ```
- `GuardianStop` ← src/workflow/fleet/guardian-stop.ts:20 [EXTRACTED]
  ```
  export type GuardianStop = z.infer<typeof GuardianStopSchema>;
  ```
- `GuardianInput` ← src/workflow/fleet/guardian-stop.ts:25 [EXTRACTED]
  ```
  export type GuardianInput = z.infer<typeof GuardianInputSchema>;
  ```
- `MemberPlace` ← src/workflow/fleet/member.ts:84 [EXTRACTED]
  ```
  export type MemberPlace = {
  ```
- `OpenWake` ← src/workflow/fleet/owner.ts:150 [EXTRACTED]
  ```
  export type OpenWake = (entry: { use: string; options: RuntimeOptions }) => Promise<{ ok: true; runtime: StepRuntime<DriverCan>; wakes: boolean } | { ok: false; failure: WorkflowFailure }>;
  ```
- `FleetLease` ← src/workflow/fleet/record.ts:82 [EXTRACTED]
  ```
  export type FleetLease = z.infer<typeof FleetLeaseSchema>;
  ```
- `LeaseValues` ← src/workflow/fleet/record.ts:109 [EXTRACTED]
  ```
  export type LeaseValues = z.infer<typeof LeaseValuesSchema>;
  ```
- `FleetResult` ← src/workflow/fleet/record.ts:134 [EXTRACTED]
  ```
  export type FleetResult = z.infer<typeof FleetResultSchema>;
  ```
- `FleetRecord` ← src/workflow/fleet/record.ts:258 [EXTRACTED]
  ```
  export type FleetRecord = z.infer<typeof FleetRecordSchema>;
  ```
- `Offered` ← src/workflow/fleet/record.ts:260 [EXTRACTED]
  ```
  export type Offered = Extract<FleetRecord, { state: 'offered' }>;
  ```
- `Claimed` ← src/workflow/fleet/record.ts:262 [EXTRACTED]
  ```
  export type Claimed = Extract<FleetRecord, { state: 'claimed' }>;
  ```
- `Cancelling` ← src/workflow/fleet/record.ts:264 [EXTRACTED]
  ```
  export type Cancelling = Extract<FleetRecord, { state: 'cancelling' }>;
  ```
- `HeldAttempt` ← src/workflow/fleet/record.ts:267 [EXTRACTED]
  ```
  export type HeldAttempt = Extract<FleetRecord, { state: 'claimed' | 'asking' | 'answered' }>;
  ```
- `Asking` ← src/workflow/fleet/record.ts:269 [EXTRACTED]
  ```
  export type Asking = Extract<FleetRecord, { state: 'asking' }>;
  ```
- `FleetError` ← src/workflow/fleet/record.ts:301 [EXTRACTED]
  ```
  export type FleetError =
  ```
- `OpenAttempt` ← src/workflow/fleet/record.ts:805 [EXTRACTED]
  ```
  export type OpenAttempt = Extract<FleetRecord, { state: 'offered' | 'claimed' | 'asking' | 'answered' | 'cancelling' }>;
  ```
- `MemberRecord` ← src/workflow/fleet/record.ts:861 [EXTRACTED]
  ```
  export type MemberRecord = Exclude<FleetRecord, Offered | Extract<FleetRecord, { state: 'withdrawn' }>>;
  ```
- `LockWait` ← src/workflow/fleet/record.ts:882 [EXTRACTED]
  ```
  export type LockWait = { until: number; signal?: AbortSignal };
  ```
- `WakeNote` ← src/workflow/fleet/record.ts:1031 [EXTRACTED]
  ```
  export type WakeNote = z.infer<typeof WakeNoteSchema>;
  ```
- `CloneLease` ← src/workflow/place/clone.ts:156 [EXTRACTED]
  ```
  export interface CloneLease {
  ```
- `PreparedClone` ← src/workflow/place/clone.ts:285 [EXTRACTED]
  ```
  export interface PreparedClone {
  ```
- `PlaceLease` ← src/workflow/place/place.ts:114 [EXTRACTED]
  ```
  export type PlaceLease = Pick<LeaseWire, 'attempt' | 'step' | 'prompt' | 'answer' | 'interactive' | 'readOnly' | 'writes' | 'workspace' | 'setup' | 'expiresAt' | 'tool' | 'role' | 'envScope'> & { executor: 'command' | 'prompt' };
  ```
- `PlacePrepared` ← src/workflow/place/place.ts:151 [EXTRACTED]
  ```
  export type PlacePrepared =
  ```
- `SetupOn` ← src/workflow/place/place.ts:693 [EXTRACTED]
  ```
  export type SetupOn = (setup: { command: string; dir: string; env: Record<string, string>; unset: string[]; signal: AbortSignal | undefined }) => Promise<SetupExit | { failure: WorkflowFailure }>;
  ```
- `StepEnd` ← src/workflow/place/place.ts:814 [EXTRACTED]
  ```
  export interface StepEnd {
  ```
- `ReadCopy` ← src/workflow/place/reader.ts:90 [EXTRACTED]
  ```
  export type ReadCopy = { read: StepRead } & (
  ```
- `DataAt` ← src/workflow/place/record.ts:66 [EXTRACTED]
  ```
  export type DataAt = z.infer<typeof DataAtSchema>;
  ```
- `PlaceRecord` ← src/workflow/place/record.ts:143 [EXTRACTED]
  ```
  export type PlaceRecord = z.infer<typeof PlaceRecordSchema>;
  ```
- `RoleDeliveryGap` ← src/workflow/place/role-copy.ts:117 [EXTRACTED]
  ```
  export type RoleDeliveryGap =
  ```
- `CloneRoleGap` ← src/workflow/place/role-copy.ts:154 [EXTRACTED]
  ```
  export type CloneRoleGap =
  ```
- `RoleNotDelivered` ← src/workflow/place/role-copy.ts:167 [EXTRACTED]
  ```
  export type RoleNotDelivered =
  ```
- `SetupRun` ← src/workflow/place/setup.ts:19 [EXTRACTED]
  ```
  export interface SetupRun {
  ```
- `SetupExit` ← src/workflow/place/setup.ts:41 [EXTRACTED]
  ```
  export interface SetupExit {
  ```
- `SetupElsewhere` ← src/workflow/place/setup.ts:46 [EXTRACTED]
  ```
  export type SetupElsewhere = (signal: AbortSignal | undefined) => Promise<SetupExit | { failure: WorkflowFailure }>;
  ```
- `TeamStart` ← src/workflow/place/team.ts:47 [EXTRACTED]
  ```
  export type TeamStart = { root: string; dir: string; target: string; base: string; start: string; found?: string };
  ```
- `WorktreeSnapshot` ← src/workflow/place/worktree-snapshot.ts:9 [EXTRACTED]
  ```
  export interface WorktreeSnapshot {
  ```
- `ExecRuntimeTool` ← src/workflow/runtimes/attempt.ts:47 [EXTRACTED]
  ```
  export type ExecRuntimeTool = (typeof EXEC_RUNTIME_TOOLS)[number];
  ```
- `RuntimeOrigin` ← src/workflow/runtimes/attempt.ts:82 [EXTRACTED]
  ```
  export type RuntimeOrigin = z.infer<typeof RuntimeOriginSchema>;
  ```
- `AttemptRuntimeRecord` ← src/workflow/runtimes/attempt.ts:146 [EXTRACTED]
  ```
  export type AttemptRuntimeRecord = z.infer<typeof AttemptRuntimeRecordSchema>;
  ```
- `AttemptPlacement` ← src/workflow/runtimes/attempt.ts:182 [EXTRACTED]
  ```
  export type AttemptPlacement =
  ```
- `AttemptExecEnd` ← src/workflow/runtimes/attempt.ts:529 [EXTRACTED]
  ```
  export type AttemptExecEnd = ExecEnd | { kind: 'interrupted' } | { kind: 'left' };
  ```
- `AttemptRun` ← src/workflow/runtimes/attempt.ts:536 [EXTRACTED]
  ```
  export interface AttemptRun {
  ```
- `AttemptSends` ← src/workflow/runtimes/attempt.ts:643 [EXTRACTED]
  ```
  export type AttemptSends = ReturnType<typeof attemptSends>;
  ```
- `RunnerHolding` ← src/workflow/runtimes/cancelled.ts:39 [EXTRACTED]
  ```
  export type RunnerHolding = (config: LocalConfig, run: RunId, attempt: AttemptId) => Promise<boolean>;
  ```
- `StoppedAttempts` ← src/workflow/runtimes/cancelled.ts:137 [EXTRACTED]
  ```
  export interface StoppedAttempts {
  ```
- `HeldPlace` ← src/workflow/runtimes/cancelled.ts:151 [EXTRACTED]
  ```
  export type HeldPlace = { held: 'open'; record: AttemptRuntimeRecord } | { held: 'unreadable'; why: string };
  ```
- `PlaceMaybeHeld` ← src/workflow/runtimes/cancelled.ts:154 [EXTRACTED]
  ```
  export type PlaceMaybeHeld = { run: RunId; attempt: AttemptId } & HeldPlace;
  ```
- `LeftInProcess` ← src/workflow/runtimes/cancelled.ts:231 [EXTRACTED]
  ```
  export type LeftInProcess = { kind: 'ended' } | { kind: 'kept'; left: readonly number[] } | { kind: 'on_runtime'; left: readonly number[] };
  ```
- `DriverDefinition` ← src/workflow/runtimes/definitions.ts:81 [EXTRACTED]
  ```
  export type DriverDefinition = z.infer<typeof DriverDefinitionSchema>;
  ```
- `DefinitionSource` ← src/workflow/runtimes/definitions.ts:84 [EXTRACTED]
  ```
  export type DefinitionSource = 'personal' | 'team' | 'shipped' | 'builtin';
  ```
- `ResolvedDriver` ← src/workflow/runtimes/definitions.ts:86 [EXTRACTED]
  ```
  export interface ResolvedDriver {
  ```
- `RuntimeEntryIdentity` ← src/workflow/runtimes/entry-identity.ts:17 [EXTRACTED]
  ```
  export interface RuntimeEntryIdentity {
  ```
- `RuntimeResourcePart` ← src/workflow/runtimes/entry-identity.ts:28 [EXTRACTED]
  ```
  export interface RuntimeResourcePart {
  ```
- `RecordedEntry` ← src/workflow/runtimes/entry-identity.ts:47 [EXTRACTED]
  ```
  export interface RecordedEntry {
  ```
- `HeldSteps` ← src/workflow/runtimes/held.ts:24 [EXTRACTED]
  ```
  export type HeldSteps = z.infer<typeof HeldStepsSchema>;
  ```
- `AnswerReport` ← src/workflow/runtimes/host.ts:18 [EXTRACTED]
  ```
  export type AnswerReport = Pick<ReportInput, 'outcome' | 'outputs' | 'tool' | 'tokens' | 'durationMs' | 'message' | 'failure'>;
  ```
- `AnswerInput` ← src/workflow/runtimes/host.ts:68 [EXTRACTED]
  ```
  export interface AnswerInput {
  ```
- `HostStepRuntime` ← src/workflow/runtimes/host.ts:120 [EXTRACTED]
  ```
  export interface HostStepRuntime extends StepRuntime<DriverCan> {
  ```
- `LayeredKind` ← src/workflow/runtimes/layers.ts:26 [EXTRACTED]
  ```
  export type LayeredKind = 'drivers' | 'runtimes' | 'sandboxes';
  ```
- `Layer` ← src/workflow/runtimes/layers.ts:28 [EXTRACTED]
  ```
  export type Layer = 'personal' | 'team' | 'teamai';
  ```
- `LayerItem` ← src/workflow/runtimes/layers.ts:58 [EXTRACTED]
  ```
  export type LayerItem =
  ```
- `LayerRefusal` ← src/workflow/runtimes/layers.ts:64 [EXTRACTED]
  ```
  export type LayerRefusal =
  ```
- `LayerFind` ← src/workflow/runtimes/layers.ts:78 [EXTRACTED]
  ```
  export type LayerFind =
  ```
- `RuntimeLayer` ← src/workflow/runtimes/locate.ts:50 [EXTRACTED]
  ```
  export type RuntimeLayer = Layer;
  ```
- `RuntimeLaunch` ← src/workflow/runtimes/locate.ts:53 [EXTRACTED]
  ```
  export type RuntimeLaunch = { readonly kind: 'node'; readonly file: string } | { readonly kind: 'executable'; readonly executable: string };
  ```
- `RuntimeTrust` ← src/workflow/runtimes/locate.ts:60 [EXTRACTED]
  ```
  export type RuntimeTrust = { readonly kind: 'none' } | { readonly kind: 'folder'; readonly dir: string; readonly copy?: string } | { readonly kind: 'command'; readonly command: string };
  ```
- `ExternalRuntime` ← src/workflow/runtimes/locate.ts:63 [EXTRACTED]
  ```
  export interface ExternalRuntime {
  ```
- `BuiltInRuntime` ← src/workflow/runtimes/locate.ts:98 [EXTRACTED]
  ```
  export type BuiltInRuntime = (typeof BUILT_IN_RUNTIMES)[keyof typeof BUILT_IN_RUNTIMES];
  ```
- `RuntimeSource` ← src/workflow/runtimes/locate.ts:108 [EXTRACTED]
  ```
  export type RuntimeSource = { readonly kind: 'builtin'; readonly name: BuiltInRuntime } | ExternalRuntime;
  ```
- `PinnedRuntime` ← src/workflow/runtimes/locate.ts:381 [EXTRACTED]
  ```
  export type PinnedRuntime = { ok: true; source: ExternalRuntime; remove: () => Promise<void> };
  ```
- `PinProblem` ← src/workflow/runtimes/locate.ts:453 [EXTRACTED]
  ```
  export type PinProblem = { kind: 'uncopied'; why: string } | { kind: 'link'; link: string } | { kind: 'unreadable'; why: string };
  ```
- `LoginTool` ← src/workflow/runtimes/login.ts:35 [EXTRACTED]
  ```
  export type LoginTool = (typeof LOGIN_TOOLS)[number];
  ```
- `LoginSource` ← src/workflow/runtimes/login.ts:75 [EXTRACTED]
  ```
  export type LoginSource = z.infer<typeof LoginSourceSchema>;
  ```
- `LoginLock` ← src/workflow/runtimes/login.ts:98 [EXTRACTED]
  ```
  export type LoginLock = z.infer<typeof LoginLockSchema>;
  ```
- `LoginWait` ← src/workflow/runtimes/login.ts:197 [EXTRACTED]
  ```
  export type LoginWait = z.infer<typeof LoginWaitSchema>;
  ```
- `EndedLogin` ← src/workflow/runtimes/login.ts:382 [EXTRACTED]
  ```
  export type EndedLogin = { wasHeld: false; notBack: WorkflowFailure } | { wasHeld: true; notBack?: WorkflowFailure };
  ```
- `Shown` ← src/workflow/runtimes/protocol.ts:12 [EXTRACTED]
  ```
  export type Shown = { kind: 'none' } | { kind: 'shown'; display: RuntimeDisplay } | { kind: 'dropped'; reason: string };
  ```
- `OpEvent` ← src/workflow/runtimes/protocol.ts:24 [EXTRACTED]
  ```
  export type OpEvent = z.infer<typeof OpEvent>;
  ```
- `HandleEvent` ← src/workflow/runtimes/protocol.ts:26 [EXTRACTED]
  ```
  export type HandleEvent = z.infer<typeof HandleEvent>;
  ```
- `RuntimeMessage` ← src/workflow/runtimes/protocol.ts:28 [EXTRACTED]
  ```
  export type RuntimeMessage = z.infer<typeof Message>;
  ```
- `SandboxProfile` ← src/workflow/runtimes/sandbox-profiles.ts:37 [EXTRACTED]
  ```
  export interface SandboxProfile {
  ```
- `EngineOptions` ← src/workflow/runtimes/sources.ts:73 [EXTRACTED]
  ```
  export interface EngineOptions {
  ```
- `EnvCredential` ← src/workflow/runtimes/sources.ts:79 [EXTRACTED]
  ```
  export interface EnvCredential {
  ```
- `OpenedRuntime` ← src/workflow/runtimes/sources.ts:180 [EXTRACTED]
  ```
  export type OpenedRuntime =
  ```
- `OpenedDriver` ← src/workflow/runtimes/sources.ts:209 [EXTRACTED]
  ```
  export interface OpenedDriver {
  ```
- `DriverPurpose` ← src/workflow/runtimes/sources.ts:271 [EXTRACTED]
  ```
  export type DriverPurpose = 'run' | 'stop' | 'check';
  ```
- `SandboxEntryCheck` ← src/workflow/runtimes/sources.ts:657 [EXTRACTED]
  ```
  export interface SandboxEntryCheck {
  ```
- `CallResult` ← src/workflow/runtimes/tool-caller.ts:21 [EXTRACTED]
  ```
  export type CallResult = { text: string; tool: string; tokens?: TokenUsage };
  ```
- `ReplyResult` ← src/workflow/runtimes/tool-caller.ts:24 [EXTRACTED]
  ```
  export type ReplyResult<T> = CallResult & { reply: T | undefined; asked: number };
  ```
- `CallOptions` ← src/workflow/runtimes/tool-caller.ts:26 [EXTRACTED]
  ```
  export interface CallOptions {
  ```
- `ReplyOptions` ← src/workflow/runtimes/tool-caller.ts:43 [EXTRACTED]
  ```
  export interface ReplyOptions extends CallOptions {
  ```
- `ToolCaller` ← src/workflow/runtimes/tool-caller.ts:48 [EXTRACTED]
  ```
  export interface ToolCaller {
  ```
- `ToolCallerDeps` ← src/workflow/runtimes/tool-caller.ts:73 [EXTRACTED]
  ```
  export interface ToolCallerDeps {
  ```
- `GitLockPlace` ← src/workflow/steps/git-locks.ts:12 [EXTRACTED]
  ```
  export type GitLockPlace = 'clone' | 'worktree' | 'member';
  ```
- `AskPerson` ← src/workflow/steps/prompt.ts:49 [EXTRACTED]
  ```
  export type AskPerson = (question: string, signal: AbortSignal) => Promise<string | undefined>;
  ```
- `StagedLease` ← src/workflow/steps/prompt.ts:53 [EXTRACTED]
  ```
  export interface StagedLease extends LeaseWire {
  ```
- `LaunchChoice` ← src/workflow/steps/prompt.ts:107 [EXTRACTED]
  ```
  export type LaunchChoice = { ok: true; tool: LaunchTool; target: LaunchTarget; warnings: string[] } | { ok: false; failure: WorkflowFailure; tool?: string; warnings: string[] };
  ```
- `PromptRuntime` ← src/workflow/steps/prompt.ts:240 [EXTRACTED]
  ```
  export type PromptRuntime = {
  ```
- `PromptOffer` ← src/workflow/steps/prompt.ts:255 [EXTRACTED]
  ```
  export type PromptOffer = Omit<PromptRuntime, 'run' | 'teamEnv' | 'conversationHeld'>;
  ```
- `StepEnv` ← src/workflow/steps/runtime-steps.ts:60 [EXTRACTED]
  ```
  export interface StepEnv {
  ```
- `StartedCommand` ← src/workflow/steps/runtime-steps.ts:100 [EXTRACTED]
  ```
  export interface StartedCommand {
  ```
- `SetUp` ← src/workflow/steps/runtime-steps.ts:191 [EXTRACTED]
  ```
  export type SetUp = (signal: AbortSignal | undefined) => Promise<WorkflowFailure | undefined>;
  ```
- `NodeTestObject` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-between-statements.ts:45 [EXTRACTED]
  ```
  export interface NodeTestObject {
  ```
- `PolicyStatementOption` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-between-statements.ts:53 [EXTRACTED]
  ```
  export type PolicyStatementOption<Extra extends string = never> =
  ```
- `PolicyOptions` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-between-statements.ts:58 [EXTRACTED]
  ```
  export type PolicyOptions<Extra extends string = never> = {
  ```
- `PaddingType` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-options.d.ts:5 [EXTRACTED]
  ```
  export type PaddingType = 'any' | 'never' | 'always'
  ```
- `StatementOption` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-options.d.ts:6 [EXTRACTED]
  ```
  export type StatementOption =
  ```
- `StatementMatcher` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-options.d.ts:9 [EXTRACTED]
  ```
  export type StatementMatcher =
  ```
- `StatementType` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-options.d.ts:12 [EXTRACTED]
  ```
  export type StatementType =
  ```
- `PaddingLineBetweenStatementsSchema0` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-options.d.ts:69 [EXTRACTED]
  ```
  export type PaddingLineBetweenStatementsSchema0 = {
  ```
- `SelectorOption` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-options.d.ts:75 [EXTRACTED]
  ```
  export interface SelectorOption {
  ```
- `MessageIds` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-options.d.ts:85 [EXTRACTED]
  ```
  export type MessageIds =
  ```
- `PaseoClient` ← packages/runtime-paseo/src/daemon/client.ts:49 [EXTRACTED]
  ```
  export interface PaseoClient {
  ```
- `StepMode` ← packages/runtime-paseo/src/daemon/connect.ts:34 [EXTRACTED]
  ```
  export type StepMode = { kind: 'unset' } | { kind: 'asks'; id: string } | { kind: 'tightened'; id: string; insteadOf: string } | { kind: 'bypass'; id: string };
  ```
- `ConfiguredModes` ← packages/runtime-paseo/src/daemon/connect.ts:37 [EXTRACTED]
  ```
  export type ConfiguredModes = Partial<Record<PaseoTool, string>>;
  ```
- `Model` ← packages/runtime-paseo/src/daemon/connect.ts:200 [EXTRACTED]
  ```
  export interface Model {
  ```
- `Creation` ← packages/runtime-paseo/src/daemon/connect.ts:208 [EXTRACTED]
  ```
  export type Creation = { outcome: 'created' } | { outcome: 'unsent' | 'failed'; cause: string };
  ```
- `WaitEnd` ← packages/runtime-paseo/src/daemon/connect.ts:210 [EXTRACTED]
  ```
  export type WaitEnd = Awaited<ReturnType<DaemonClient['waitForFinish']>>;
  ```
- `Target` ← packages/runtime-paseo/src/daemon/connect.ts:216 [EXTRACTED]
  ```
  export interface Target {
  ```
- `InstalledTool` ← packages/runtime-paseo/src/daemon/connect.ts:230 [EXTRACTED]
  ```
  export type InstalledTool =
  ```
- `ProviderHome` ← packages/runtime-paseo/src/daemon/connect.ts:239 [EXTRACTED]
  ```
  export interface ProviderHome {
  ```
- `Added` ← packages/runtime-paseo/src/daemon/connect.ts:256 [EXTRACTED]
  ```
  export type Added = { provider: string; added: boolean; home?: string; providerHome?: string } | { cannot: string; added: boolean };
  ```
- `ToolChoices` ← packages/runtime-paseo/src/daemon/connect.ts:259 [EXTRACTED]
  ```
  export interface ToolChoices {
  ```
- `Daemon` ← packages/runtime-paseo/src/daemon/connect.ts:270 [EXTRACTED]
  ```
  export interface Daemon {
  ```
- `SavedHost` ← packages/runtime-paseo/src/daemon/host.ts:12 [EXTRACTED]
  ```
  export interface SavedHost {
  ```
- `Host` ← packages/runtime-paseo/src/daemon/host.ts:19 [EXTRACTED]
  ```
  export interface Host {
  ```
- `SignIn` ← packages/runtime-paseo/src/daemon/sign-in.ts:32 [EXTRACTED]
  ```
  export type SignIn = { canRun: false; problem: string } | { canRun: true; home?: string };
  ```
- `RunsIn` ← packages/runtime-paseo/src/daemon/sign-in.ts:42 [EXTRACTED]
  ```
  export interface RunsIn {
  ```
- `SocketLine` ← packages/runtime-paseo/src/testing/attempt-socket.ts:21 [EXTRACTED]
  ```
  export type SocketLine = z.infer<typeof LineSchema>;
  ```
- `FakeAttemptSocket` ← packages/runtime-paseo/src/testing/attempt-socket.ts:29 [EXTRACTED]
  ```
  export interface FakeAttemptSocket {
  ```
- `Behaviour` ← packages/runtime-paseo/src/testing/fake-daemon.ts:199 [EXTRACTED]
  ```
  export type Behaviour = z.input<typeof BehaviourSchema>;
  ```
- `Runtime` ← packages/runtime-paseo/src/testing/harness.ts:27 [EXTRACTED]
  ```
  export interface Runtime {
  ```
- `PassedInstance` ← packages/runtime-paseo/src/testing/suite.ts:84 [EXTRACTED]
  ```
  export type PassedInstance = InitInstance & { readonly homeEnv: readonly string[] };
  ```
- `Ran` ← packages/runtime-sandbox/src/providers/cli.ts:42 [EXTRACTED]
  ```
  export type Ran = { kind: 'ran'; code: number; stdout: string; stderr: string } | { kind: 'unstartable' | 'timed_out'; message: string };
  ```
- `Cli` ← packages/runtime-sandbox/src/providers/cli.ts:44 [EXTRACTED]
  ```
  export interface Cli {
  ```
- `Mount` ← packages/runtime-sandbox/src/providers/cli.ts:121 [EXTRACTED]
  ```
  export interface Mount {
  ```
- `Host` ← packages/runtime-sandbox/src/providers/container.ts:170 [EXTRACTED]
  ```
  export interface Host {
  ```
- `NativeSandbox` ← packages/runtime-sandbox/src/providers/native.ts:32 [EXTRACTED]
  ```
  export interface NativeSandbox {
  ```
- `Sandboxed` ← packages/runtime-sandbox/src/providers/native.ts:44 [EXTRACTED]
  ```
  export interface Sandboxed {
  ```
- `SeatbeltProfile` ← packages/runtime-sandbox/src/providers/seatbelt.ts:134 [EXTRACTED]
  ```
  export interface SeatbeltProfile {
  ```
- `TarEntry` ← packages/runtime-sandbox/src/providers/vercel-copy.ts:14 [EXTRACTED]
  ```
  export type TarEntry = { at: string; mode: number } & ({ kind: 'file'; data: Buffer } | { kind: 'dir' } | { kind: 'link'; target: string } | { kind: 'hardlink'; target: string });
  ```
- `FakeEngine` ← packages/runtime-sandbox/src/testing/harness.ts:45 [EXTRACTED]
  ```
  export interface FakeEngine {
  ```
- `Message` ← packages/runtime-sandbox/src/testing/harness.ts:232 [EXTRACTED]
  ```
  export type Message = Line;
  ```
- `Connection` ← packages/runtime-sandbox/src/testing/harness.ts:234 [EXTRACTED]
  ```
  export interface Connection {
  ```
- `Scope` ← packages/runtime-sandbox/src/testing/leaks.ts:18 [EXTRACTED]
  ```
  export interface Scope {
  ```
- `NativeHost` ← packages/runtime-sandbox/src/testing/native-harness.ts:15 [EXTRACTED]
  ```
  export interface NativeHost {
  ```
- `Place` ← packages/runtime-sandbox/src/testing/native-harness.ts:101 [EXTRACTED]
  ```
  export interface Place {
  ```
- `FakeAgent` ← packages/runtime-t3/src/testing/harness.ts:31 [EXTRACTED]
  ```
  export interface FakeAgent {
  ```
- `FakeProvider` ← packages/runtime-t3/src/testing/harness.ts:58 [EXTRACTED]
  ```
  export interface FakeProvider {
  ```
- `FakeT3Config` ← packages/runtime-t3/src/testing/harness.ts:66 [EXTRACTED]
  ```
  export interface FakeT3Config {
  ```
- `FakeCall` ← packages/runtime-t3/src/testing/harness.ts:154 [EXTRACTED]
  ```
  export type FakeCall = z.infer<typeof CallSchema>;
  ```
- `FakeThread` ← packages/runtime-t3/src/testing/harness.ts:171 [EXTRACTED]
  ```
  export type FakeThread = z.infer<typeof ThreadSchema>;
  ```
- `FakeT3` ← packages/runtime-t3/src/testing/harness.ts:183 [EXTRACTED]
  ```
  export interface FakeT3 {
  ```
- `FixtureConv` ← packages/tool-codebuddy/src/testing/ide-history.ts:34 [EXTRACTED]
  ```
  export interface FixtureConv {
  ```
- `FakeCodexState` ← packages/tool-codex/src/testing/fake-codex.ts:106 [EXTRACTED]
  ```
  export interface FakeCodexState {
  ```
- `SessionMeta` ← packages/tool-core/src/sessions/base.ts:10 [EXTRACTED]
  ```
  export interface SessionMeta {
  ```
- `SessionReadRef` ← packages/tool-core/src/sessions/base.ts:29 [EXTRACTED]
  ```
  export interface SessionReadRef {
  ```
- `Subagent` ← packages/tool-core/src/sessions/base.ts:44 [EXTRACTED]
  ```
  export interface Subagent {
  ```
- `SubagentsRead` ← packages/tool-core/src/sessions/base.ts:58 [EXTRACTED]
  ```
  export type SubagentsRead = { status: 'read'; agents: Subagent[] } | { status: 'unread'; reason: string };
  ```
- `SessionIdFormat` ← packages/tool-core/src/sessions/ids.ts:26 [EXTRACTED]
  ```
  export type SessionIdFormat = 'uuid' | 'opencode' | 'hermes';
  ```
- `TextBlock` ← packages/tool-core/src/sessions/ir.ts:22 [EXTRACTED]
  ```
  export interface TextBlock {
  ```
- `ThinkingBlock` ← packages/tool-core/src/sessions/ir.ts:27 [EXTRACTED]
  ```
  export interface ThinkingBlock {
  ```
- `ToolCallBlock` ← packages/tool-core/src/sessions/ir.ts:33 [EXTRACTED]
  ```
  export interface ToolCallBlock {
  ```
- `ToolArguments` ← packages/tool-core/src/sessions/ir.ts:43 [EXTRACTED]
  ```
  export type ToolArguments = z.infer<typeof ToolArgumentsSchema>;
  ```
- `ToolResultBlock` ← packages/tool-core/src/sessions/ir.ts:66 [EXTRACTED]
  ```
  export interface ToolResultBlock {
  ```
- `ImageBlock` ← packages/tool-core/src/sessions/ir.ts:80 [EXTRACTED]
  ```
  export interface ImageBlock {
  ```
- `ContentBlock` ← packages/tool-core/src/sessions/ir.ts:97 [EXTRACTED]
  ```
  export type ContentBlock = TextBlock | ThinkingBlock | ToolCallBlock | ToolResultBlock | ImageBlock;
  ```
- `MessageMetadata` ← packages/tool-core/src/sessions/ir.ts:195 [EXTRACTED]
  ```
  export interface MessageMetadata {
  ```
- `Message` ← packages/tool-core/src/sessions/ir.ts:202 [EXTRACTED]
  ```
  export interface Message {
  ```
- `MessageRecord` ← packages/tool-core/src/sessions/ir.ts:212 [EXTRACTED]
  ```
  export interface MessageRecord {
  ```
- `SessionMetadata` ← packages/tool-core/src/sessions/ir.ts:267 [EXTRACTED]
  ```
  export interface SessionMetadata {
  ```
- `Session` ← packages/tool-core/src/sessions/ir.ts:276 [EXTRACTED]
  ```
  export interface Session {
  ```
- `SessionRecord` ← packages/tool-core/src/sessions/ir.ts:288 [EXTRACTED]
  ```
  export interface SessionRecord {
  ```
- `SessionStore` ← packages/tool-core/src/sessions/platform.ts:13 [EXTRACTED]
  ```
  export type SessionStore<TTool extends string = string> =
  ```
- `SessionPlatformFacts` ← packages/tool-core/src/sessions/platform.ts:23 [EXTRACTED]
  ```
  export interface SessionPlatformFacts<TTool extends string = string> {
  ```
- `SessionHost` ← packages/tool-core/src/sessions/platform.ts:48 [EXTRACTED]
  ```
  export interface SessionHost {
  ```
- `StoredPlatformDefinition` ← packages/tool-core/src/sessions/platform.ts:57 [EXTRACTED]
  ```
  export type StoredPlatformDefinition<TTool extends string = string> = SessionPlatformFacts<TTool> & {
  ```
- `SelfLocatingPlatformDefinition` ← packages/tool-core/src/sessions/platform.ts:70 [EXTRACTED]
  ```
  export type SelfLocatingPlatformDefinition<TTool extends string = string> = SessionPlatformFacts<TTool> & {
  ```
- `SessionPlatformDefinition` ← packages/tool-core/src/sessions/platform.ts:77 [EXTRACTED]
  ```
  export type SessionPlatformDefinition<TTool extends string = string> = StoredPlatformDefinition<TTool> | SelfLocatingPlatformDefinition<TTool>;
  ```
- `OpencodeExport` ← packages/tool-opencode/src/testing/fake-opencode.ts:154 [EXTRACTED]
  ```
  export type OpencodeExport = z.infer<typeof OpencodeExportSchema>;
  ```
- `ImportBindingMap` ← src/wiki-engine/code-knowledge/ast/call-resolver.ts:6 [EXTRACTED]
  ```
  export interface ImportBindingMap {
  ```
- `TsconfigPathsConfig` ← src/wiki-engine/code-knowledge/ast/import-resolver.ts:17 [EXTRACTED]
  ```
  export interface TsconfigPathsConfig {
  ```
- `ResolvedImport` ← src/wiki-engine/code-knowledge/ast/import-resolver.ts:22 [EXTRACTED]
  ```
  export interface ResolvedImport {
  ```
- `SwiftMemberName` ← src/wiki-engine/code-knowledge/ast/module-scope.ts:68 [EXTRACTED]
  ```
  export interface SwiftMemberName {
  ```
- `SwiftModuleSymbolIndex` ← src/wiki-engine/code-knowledge/ast/module-scope.ts:73 [EXTRACTED]
  ```
  export interface SwiftModuleSymbolIndex {
  ```
- `GrammarVariant` ← src/wiki-engine/code-knowledge/ast/parser-registry.ts:10 [EXTRACTED]
  ```
  export type GrammarVariant = (typeof GRAMMAR_VARIANTS)[number];
  ```
- `AstSymbolKind` ← src/wiki-engine/code-knowledge/ast/types.ts:4 [EXTRACTED]
  ```
  export type AstSymbolKind = "function" | "class" | "interface" | "method" | "variable";
  ```
- `AstSymbol` ← src/wiki-engine/code-knowledge/ast/types.ts:6 [EXTRACTED]
  ```
  export interface AstSymbol {
  ```
- `AstImport` ← src/wiki-engine/code-knowledge/ast/types.ts:16 [EXTRACTED]
  ```
  export interface AstImport {
  ```
- `AstCallSite` ← src/wiki-engine/code-knowledge/ast/types.ts:26 [EXTRACTED]
  ```
  export interface AstCallSite {
  ```
- `AstImplementsSite` ← src/wiki-engine/code-knowledge/ast/types.ts:68 [EXTRACTED]
  ```
  export interface AstImplementsSite {
  ```
- `StructuralRelation` ← src/wiki-engine/code-knowledge/ast/types.ts:75 [EXTRACTED]
  ```
  export type StructuralRelation = "DEPENDS_ON" | "REFERENCES" | "IMPLEMENTS";
  ```
- `StructuralEdge` ← src/wiki-engine/code-knowledge/ast/types.ts:77 [EXTRACTED]
  ```
  export interface StructuralEdge {
  ```
- `AstExtractionGap` ← src/wiki-engine/code-knowledge/ast/types.ts:87 [EXTRACTED]
  ```
  export interface AstExtractionGap {
  ```
- `AstExtractionStats` ← src/wiki-engine/code-knowledge/ast/types.ts:93 [EXTRACTED]
  ```
  export interface AstExtractionStats {
  ```
- `StructuralGraphResult` ← src/wiki-engine/code-knowledge/ast/types.ts:104 [EXTRACTED]
  ```
  export interface StructuralGraphResult {
  ```
- `FileWalkResult` ← src/wiki-engine/code-knowledge/ast/walk.ts:17 [EXTRACTED]
  ```
  export interface FileWalkResult {
  ```
- `LocalHitl` ← src/workflow/drivers/local/local-driver.ts:117 [EXTRACTED]
  ```
  export interface LocalHitl extends StepHitl {
  ```
- `LocalDriverOptions` ← src/workflow/drivers/local/local-driver.ts:193 [EXTRACTED]
  ```
  export interface LocalDriverOptions {
  ```
- `DriverRuntimes` ← src/workflow/drivers/local/local-driver.ts:226 [EXTRACTED]
  ```
  export interface DriverRuntimes {
  ```
- `ChildResult` ← src/workflow/drivers/skill/child-brief.ts:39 [EXTRACTED]
  ```
  export type ChildResult = z.infer<typeof ChildResultSchema>;
  ```
- `Job` ← src/workflow/drivers/skill/job.ts:16 [EXTRACTED]
  ```
  export interface Job {
  ```
- `Literal` ← src/workflow/drivers/skill/literals.ts:10 [EXTRACTED]
  ```
  export type Literal = z.infer<typeof LiteralSchema>;
  ```
- `Invocation` ← src/workflow/drivers/skill/literals.ts:15 [EXTRACTED]
  ```
  export type Invocation = typeof INVOCATIONS[number];
  ```
- `StartAnswer` ← src/workflow/drivers/skill/preflight.ts:18 [EXTRACTED]
  ```
  export type StartAnswer = 'confirmed' | 'inputs' | 'parallel' | 'hitl' | 'tool';
  ```
- `HitlMode` ← src/workflow/drivers/skill/preflight.ts:35 [EXTRACTED]
  ```
  export type HitlMode = typeof HITL_MODES[number];
  ```
- `StartCheck` ← src/workflow/drivers/skill/preflight.ts:37 [EXTRACTED]
  ```
  export type StartCheck =
  ```
- `Proposed` ← src/workflow/drivers/skill/preflight.ts:389 [EXTRACTED]
  ```
  export type Proposed = Readonly<Record<string, { value?: unknown; why: string }>>;
  ```
- `SessionHostChoice` ← src/workflow/drivers/skill/session-host-profiles.ts:14 [EXTRACTED]
  ```
  export type SessionHostChoice = typeof SESSION_HOST_CHOICES[number];
  ```
- `SessionHostProfile` ← src/workflow/drivers/skill/session-host-profiles.ts:17 [EXTRACTED]
  ```
  export interface SessionHostProfile {
  ```
- `ConfinedJudge` ← src/workflow/drivers/skill/session-host-profiles.ts:92 [EXTRACTED]
  ```
  export interface ConfinedJudge {
  ```
- `SkillCall` ← src/workflow/drivers/skill/skill-driver.ts:38 [EXTRACTED]
  ```
  export type SkillCall =
  ```
- `RunnerJob` ← src/workflow/drivers/skill/skill-driver.ts:67 [EXTRACTED]
  ```
  export interface RunnerJob {
  ```
- `CommandRun` ← src/workflow/drivers/skill/skill-driver.ts:75 [EXTRACTED]
  ```
  export interface CommandRun {
  ```
- `Runners` ← src/workflow/drivers/skill/skill-driver.ts:83 [EXTRACTED]
  ```
  export interface Runners {
  ```
- `SkillContext` ← src/workflow/drivers/skill/skill-driver.ts:97 [EXTRACTED]
  ```
  export interface SkillContext {
  ```
- `ReportBody` ← src/workflow/drivers/skill/skill-state.ts:49 [EXTRACTED]
  ```
  export type ReportBody = z.infer<typeof ReportBodySchema>;
  ```
- `ModelPick` ← src/workflow/drivers/skill/skill-state.ts:60 [EXTRACTED]
  ```
  export type ModelPick = z.infer<typeof ModelPickSchema>;
  ```
- `Dispatch` ← src/workflow/drivers/skill/skill-state.ts:87 [EXTRACTED]
  ```
  export type Dispatch = z.infer<typeof DispatchSchema>;
  ```
- `StopReason` ← src/workflow/drivers/skill/skill-state.ts:102 [EXTRACTED]
  ```
  export type StopReason = typeof STOP_REASONS[number];
  ```
- `PlaceAsk` ← src/workflow/drivers/skill/skill-state.ts:107 [EXTRACTED]
  ```
  export type PlaceAsk = z.infer<typeof PlaceAskSchema>;
  ```
- `AttemptState` ← src/workflow/drivers/skill/skill-state.ts:145 [EXTRACTED]
  ```
  export type AttemptState = z.infer<typeof AttemptStateSchema>;
  ```
- `TurnEvent` ← src/workflow/drivers/skill/skill-state.ts:173 [EXTRACTED]
  ```
  export type TurnEvent = z.infer<typeof TurnEventSchema>;
  ```
- `Gate` ← src/workflow/drivers/skill/skill-state.ts:195 [EXTRACTED]
  ```
  export type Gate = z.infer<typeof GateSchema>;
  ```
- `SkillState` ← src/workflow/drivers/skill/skill-state.ts:260 [EXTRACTED]
  ```
  export type SkillState = z.infer<typeof SkillStateSchema>;
  ```
- `UnansweredSessionHost` ← src/workflow/drivers/skill/skill-state.ts:263 [EXTRACTED]
  ```
  export type UnansweredSessionHost = Exclude<SkillState['host'], { kind: 'chosen' }>;
  ```
- `ForegroundCall` ← src/workflow/drivers/skill/tick.ts:513 [EXTRACTED]
  ```
  export type ForegroundCall =
  ```
- `TransitionRow` ← src/workflow/drivers/skill/transitions.ts:25 [EXTRACTED]
  ```
  export interface TransitionRow {
  ```
- `RowId` ← src/workflow/drivers/skill/transitions.ts:154 [EXTRACTED]
  ```
  export type RowId = typeof TRANSITIONS[number]['id'];
  ```
- `ReadLease` ← src/workflow/drivers/skill/transitions.ts:157 [EXTRACTED]
  ```
  export type ReadLease = { attempt: AttemptId; step: string; revision: number; expiresAt?: string } & (
  ```
- `AskedGate` ← src/workflow/drivers/skill/transitions.ts:169 [EXTRACTED]
  ```
  export type AskedGate = Omit<Gate, 'seq' | 'decide'>;
  ```
- `EngineReply` ← src/workflow/drivers/skill/transitions.ts:171 [EXTRACTED]
  ```
  export type EngineReply =
  ```
- `RespondReply` ← src/workflow/drivers/skill/transitions.ts:185 [EXTRACTED]
  ```
  export type RespondReply = { kind: 'answered'; step: string; pass: number; choice: string; channel: string; agent: boolean } | { kind: 'error'; error: WorkflowFailure };
  ```
- `ReportReply` ← src/workflow/drivers/skill/transitions.ts:188 [EXTRACTED]
  ```
  export type ReportReply = { kind: 'reported'; outcome: Extract<TurnEvent, { kind: 'settled' }>['outcome']; failure?: WorkflowFailure } | { kind: 'error'; error: WorkflowFailure };
  ```
- `AppReadiness` ← src/workflow/drivers/skill/transitions.ts:200 [EXTRACTED]
  ```
  export type AppReadiness = 'unchecked' | 'ready' | 'not-ready';
  ```
- `DescribeInput` ← src/workflow/drivers/skill/transitions.ts:202 [EXTRACTED]
  ```
  export interface DescribeInput {
  ```
- `JudgedBy` ← src/workflow/drivers/skill/transitions.ts:208 [EXTRACTED]
  ```
  export type JudgedBy = { kind: 'here'; tool: string } | { kind: 'session'; tool: string };
  ```
- `StartInput` ← src/workflow/drivers/skill/transitions.ts:230 [EXTRACTED]
  ```
  export interface StartInput { name: string; check: StartCheck; denied?: string; local?: string; attended?: string; prompts: boolean; judge?: JudgedBy }
  ```
- `Effect` ← src/workflow/drivers/skill/transitions.ts:233 [EXTRACTED]
  ```
  export type Effect =
  ```
- `Refusal` ← src/workflow/drivers/skill/transitions.ts:252 [EXTRACTED]
  ```
  export type Refusal =
  ```
- `BackgroundDriver` ← src/workflow/drivers/skill/transitions.ts:273 [EXTRACTED]
  ```
  export interface BackgroundDriver { driver: string; steps: string }
  ```
- `DescribeVerdict` ← src/workflow/drivers/skill/transitions.ts:283 [EXTRACTED]
  ```
  export type DescribeVerdict =
  ```
- `StartRun` ← src/workflow/drivers/skill/transitions.ts:294 [EXTRACTED]
  ```
  export interface StartRun { parallel: number; hitl: HitlMode; sessionHost: UnansweredSessionHost; judge?: JudgedBy }
  ```
- `Answer` ← src/workflow/drivers/skill/transitions.ts:303 [EXTRACTED]
  ```
  export type Answer = Refused | Relayed;
  ```
- `TurnAnswer` ← src/workflow/drivers/skill/transitions.ts:309 [EXTRACTED]
  ```
  export interface TurnAnswer {
  ```
- `Moved` ← src/workflow/drivers/skill/transitions.ts:319 [EXTRACTED]
  ```
  export interface Moved<R extends RowId> {
  ```
- `MovedWithEffects` ← src/workflow/drivers/skill/transitions.ts:325 [EXTRACTED]
  ```
  export interface MovedWithEffects<R extends RowId> extends Moved<R> {
  ```
- `Answered` ← src/workflow/drivers/skill/transitions.ts:330 [EXTRACTED]
  ```
  export interface Answered<R extends RowId, A extends Answer = Answer> {
  ```
- `TickTurn` ← src/workflow/drivers/skill/transitions.ts:336 [EXTRACTED]
  ```
  export interface TickTurn {
  ```
- `ResumeAnswers` ← src/workflow/drivers/skill/transitions.ts:491 [EXTRACTED]
  ```
  export interface ResumeAnswers { parallel?: number; hitl?: HitlMode; judge?: false }
  ```
- `DescribedInput` ← src/workflow/drivers/skill/turn.ts:21 [EXTRACTED]
  ```
  export type DescribedInput = { name: string; type: OutputSchema; value?: unknown; why?: string };
  ```
- `DescribeAsk` ← src/workflow/drivers/skill/turn.ts:24 [EXTRACTED]
  ```
  export type DescribeAsk =
  ```
- `DispatchAction` ← src/workflow/drivers/skill/turn.ts:53 [EXTRACTED]
  ```
  export interface DispatchAction {
  ```
- `PlaceAction` ← src/workflow/drivers/skill/turn.ts:85 [EXTRACTED]
  ```
  export interface PlaceAction {
  ```
- `StopAction` ← src/workflow/drivers/skill/turn.ts:100 [EXTRACTED]
  ```
  export interface StopAction {
  ```
- `GateAction` ← src/workflow/drivers/skill/turn.ts:115 [EXTRACTED]
  ```
  export interface GateAction {
  ```
- `PersonAction` ← src/workflow/drivers/skill/turn.ts:127 [EXTRACTED]
  ```
  export interface PersonAction {
  ```
- `HandoffAction` ← src/workflow/drivers/skill/turn.ts:142 [EXTRACTED]
  ```
  export interface HandoffAction {
  ```
- `OfferedAction` ← src/workflow/drivers/skill/turn.ts:155 [EXTRACTED]
  ```
  export interface OfferedAction {
  ```
- `Action` ← src/workflow/drivers/skill/turn.ts:163 [EXTRACTED]
  ```
  export type Action =
  ```
- `RunningEntry` ← src/workflow/drivers/skill/turn.ts:179 [EXTRACTED]
  ```
  export interface RunningEntry {
  ```
- `Waiting` ← src/workflow/drivers/skill/turn.ts:191 [EXTRACTED]
  ```
  export interface Waiting {
  ```
- `Turn` ← src/workflow/drivers/skill/turn.ts:198 [EXTRACTED]
  ```
  export interface Turn {
  ```
- `SkillError` ← src/workflow/drivers/skill/turn.ts:217 [EXTRACTED]
  ```
  export interface SkillError {
  ```
- `SkillAnswer` ← src/workflow/drivers/skill/turn.ts:343 [EXTRACTED]
  ```
  export type SkillAnswer =
  ```