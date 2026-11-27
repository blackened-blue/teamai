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
  - src/launch-registry.ts
  - src/lint-resource-graph.ts
  - src/locate.ts
  - src/machine-id.ts
  - src/manifest-edit.ts
  - src/manifest-schema.ts
  - src/mcp-cmd.ts
  - src/mcp-git-exclude.ts
  - src/mcp-reconcile.ts
  - src/mcp-resolved-files.ts
  - src/member-env.ts
  - src/member-settings-report.ts
  - src/members.ts
  - src/migrate.ts
  - src/models-cmd.ts
  - src/mr-hint.ts
  - src/namespace-resolver.ts
  - src/namespaced-entries.ts
  - src/omp-hooks.ts
  - src/openclaw-home.ts
  - src/openclaw-hooks.ts
  - src/opencode-hooks.ts
  - src/opencode-version.ts
  - src/outcomes.ts
  - src/package-info.ts
  - src/pi-hooks.ts
  - src/pid-monitor.ts
  - src/plugin-lifecycle.ts
  - src/post-pull.ts
  - src/project-agent-root.ts
  - src/projects-cmd.ts
  - src/projects.ts
  - src/pull.ts
  - src/push-file.ts
  - src/push-namespaces.ts
  - src/push.ts
  - src/read-gates.ts
  - src/read-only.ts
  - src/recall-adoption.ts
  - src/recall-log.ts
  - src/recall-provenance.ts
  - src/recall-quality.ts
  - src/recall-toggle.ts
  - src/recall.ts
  - src/remove.ts
  - src/resource-namespaces.ts
  - src/resource-relations.ts
  - src/review-branch.ts
  - src/review-cmd.ts
  - src/review-store.ts
  - src/role-assignments.ts
  - src/roles-cmd.ts
  - src/roles.ts
  - src/save-session.ts
  - src/scope-selection.ts
  - src/score-commands.ts
  - src/score-drain.ts
  - src/score-verbs.ts
  - src/script-commands.ts
  - src/secret-store.ts
  - src/section-patcher.ts
  - src/self-improvement.ts
  - src/session-analytics.ts
  - src/session-collector.ts
  - src/session-outcomes.ts
  - src/session-owners.ts
  - src/session-share.ts
  - src/session-to-task.ts
  - src/session-trends.ts
  - src/shared-instruction-source.ts
  - src/skill-cmd.ts
  - src/skill-command.ts
  - src/skill-content.ts
  - src/skill-directory.ts
  - src/skill-health.ts
  - src/skill-owned-files.ts
  - src/skill-recommend.ts
  - src/skill-use.ts
  - src/source.ts
  - src/stats.ts
  - src/status.ts
  - src/tags.ts
  - src/team-push.ts
  - src/team-ref.ts
  - src/team-scripts.ts
  - src/teamai-only-files.ts
  - src/todowrite-hint.ts
  - src/tool-home-record.ts
  - src/tool-home.ts
  - src/tool-instances.ts
  - src/tool-registry.ts
  - src/tools.ts
  - src/types.ts
  - src/uninstall.ts
  - src/update-policy.ts
  - src/update.ts
  - src/usage-tracker.ts
  - src/version.ts
  - src/viz-render.ts
  - src/viz.ts
  - src/votes.ts
  - src/webhook-formatters.ts
  - src/webhook.ts
  - src/workflow-commands.ts
  - src/workflow-drive.ts
  - src/workflow-offers.ts
  - src/workflow-published-runs.ts
  - src/workspace-children.ts
  - scripts/doc-checks/read-markdown.ts
  - scripts/verify/doctor.ts
  - scripts/verify/help.ts
  - scripts/verify/instances.ts
  - scripts/verify/ledger.ts
  - scripts/verify/leftovers.ts
  - scripts/verify/members.ts
  - scripts/verify/reap.ts
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
  - src/benchmark/team-without.ts
  - src/benchmark/terms.ts
  - src/benchmark/trial.ts
  - src/benchmark/verdicts.ts
  - src/ci/extract-mr.ts
  - src/ci/gitlab-paginate.ts
  - src/ci/mr-comment.ts
  - src/ci/read-rejections.ts
  - src/dashboard/agent-harness-view.ts
  - src/dashboard/benchmarks-client.ts
  - src/dashboard/benchmarks.ts
  - src/dashboard/chart-fit-view.ts
  - src/dashboard/client.ts
  - src/dashboard/delivery.ts
  - src/dashboard/distribution.ts
  - src/dashboard/handoff-view.ts
  - src/dashboard/http.ts
  - src/dashboard/improvement-client.ts
  - src/dashboard/improvement.ts
  - src/dashboard/judging-health.ts
  - src/dashboard/judging-view.ts
  - src/dashboard/layered-resources-view.ts
  - src/dashboard/layered-resources.ts
  - src/dashboard/locales.ts
  - src/dashboard/member-settings-view.ts
  - src/dashboard/member-settings.ts
  - src/dashboard/resources-skills.ts
  - src/dashboard/resources.ts
  - src/dashboard/run-branches-view.ts
  - src/dashboard/run-steps-view.ts
  - src/dashboard/scorers-client.ts
  - src/dashboard/scorers.ts
  - src/dashboard/self-improvement-client.ts
  - src/dashboard/self-improvement.ts
  - src/dashboard/session-sharing-view.ts
  - src/dashboard/session-sharing.ts
  - src/dashboard/shell.ts
  - src/dashboard/styles.ts
  - src/dashboard/token-costs.ts
  - src/dashboard/tokens-view.ts
  - src/dashboard/workflow-runs.ts
  - src/dashboard/workspaces.ts
  - src/maintenance/confidence.ts
  - src/maintenance/hot-cold.ts
  - src/maintenance/paths.ts
  - src/maintenance/promote.ts
  - src/maintenance/promotion-publish.ts
  - src/maintenance/prune.ts
  - src/maintenance/quality-update.ts
  - src/models/agy-gateway.ts
  - src/models/aliases.ts
  - src/models/profile.ts
  - src/models/switch.ts
  - src/pkg/commands.ts
  - src/pkg/env-detect.ts
  - src/pkg/manifest.ts
  - src/pkg/pkg-hint.ts
  - src/pkg/register-command.ts
  - src/pkg/types.ts
  - src/providers/mr-threads.ts
  - src/providers/registry.ts
  - src/repo-list/schema.ts
  - src/repo-list/store.ts
  - src/resources/agent-folders.ts
  - src/resources/agent-format.ts
  - src/resources/agents.ts
  - src/resources/agy-plugin.ts
  - src/resources/agy-rule.ts
  - src/resources/base.ts
  - src/resources/codebuddy-rule.ts
  - src/resources/copilot-instructions.ts
  - src/resources/cursor-mdc.ts
  - src/resources/delivered-copies.ts
  - src/resources/delivered-folders.ts
  - src/resources/desired.ts
  - src/resources/docs.ts
  - src/resources/env-key.ts
  - src/resources/env-loader.ts
  - src/resources/env.ts
  - src/resources/folder-files.ts
  - src/resources/hooks.ts
  - src/resources/inherited-folders.ts
  - src/resources/joycode-rule.ts
  - src/resources/kiro-steering.ts
  - src/resources/layered-entries.ts
  - src/resources/marketplace.ts
  - src/resources/mcp-format.ts
  - src/resources/mcp.ts
  - src/resources/omp-rule.ts
  - src/resources/opencode-config.ts
  - src/resources/places.ts
  - src/resources/qoder-rule.ts
  - src/resources/repo-resource.ts
  - src/resources/resolver.ts
  - src/resources/rule-folders.ts
  - src/resources/rule-format.ts
  - src/resources/rules.ts
  - src/resources/secrets.ts
  - src/resources/skills.ts
  - src/resources/team-rule.ts
  - src/resources/team-skill-source.ts
  - src/resources/trae-rule.ts
  - src/resources/workflows.ts
  - src/scorers/adoption.ts
  - src/scorers/attempts-upgrade.ts
  - src/scorers/batch.ts
  - src/scorers/cache.ts
  - src/scorers/check-run.ts
  - src/scorers/check.ts
  - src/scorers/definition.ts
  - src/scorers/engine-hooks.ts
  - src/scorers/evidence-dir.ts
  - src/scorers/evidence.ts
  - src/scorers/failure-links.ts
  - src/scorers/folder.ts
  - src/scorers/generated-questions.ts
  - src/scorers/home.ts
  - src/scorers/isolation.ts
  - src/scorers/judge-model.ts
  - src/scorers/judges-here.ts
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
  - src/scorers/sampling.ts
  - src/scorers/score-answer.ts
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
  - src/scorers/skill-routing.ts
  - src/scorers/subject.ts
  - src/scorers/team-sync.ts
  - src/scorers/tried-file.ts
  - src/scorers/try-scorer.ts
  - src/session-flow/agent-session.ts
  - src/session-flow/archive.ts
  - src/session-flow/captures.ts
  - src/session-flow/finished-sessions.ts
  - src/session-flow/migrate.ts
  - src/session-flow/register-gate.ts
  - src/session-flow/scoring.ts
  - src/session-flow/scrub.ts
  - src/session-flow/search.ts
  - src/session-flow/session-cmd-shared.ts
  - src/session-flow/session-cmd.ts
  - src/session-flow/session-evidence.ts
  - src/session-flow/session-migrate-cmd.ts
  - src/session-flow/session-policy.ts
  - src/session-flow/session-publish.ts
  - src/session-flow/session-work.ts
  - src/session-flow/sync.ts
  - src/session-flow/task-candidates.ts
  - src/token-usage/model-name.ts
  - src/token-usage/pricing.ts
  - src/utils/agent-path.ts
  - src/utils/async.ts
  - src/utils/branch-worktree.ts
  - src/utils/canonical-json.ts
  - src/utils/claudemd.ts
  - src/utils/data-branches.ts
  - src/utils/dedup.ts
  - src/utils/defined-fields.ts
  - src/utils/duration.ts
  - src/utils/frontmatter.ts
  - src/utils/fs.ts
  - src/utils/git-answers.ts
  - src/utils/git-discovery.ts
  - src/utils/git-env.ts
  - src/utils/git-ref-files.ts
  - src/utils/git.ts
  - src/utils/glob.ts
  - src/utils/hook-cwd.ts
  - src/utils/hook-output.ts
  - src/utils/hook-source.ts
  - src/utils/hook-stdin.ts
  - src/utils/http-log.ts
  - src/utils/import-lock.ts
  - src/utils/iwiki-client.ts
  - src/utils/json.ts
  - src/utils/jsonl-store.ts
  - src/utils/learnings-branch.ts
  - src/utils/learnings-mirror.ts
  - src/utils/learnings-publish.ts
  - src/utils/learnings-roots.ts
  - src/utils/markdown-links.ts
  - src/utils/mcp-manifest.ts
  - src/utils/partition.ts
  - src/utils/path-safety.ts
  - src/utils/pending-learnings.ts
  - src/utils/pending-push.ts
  - src/utils/powershell.ts
  - src/utils/pre-push-sync.ts
  - src/utils/prompt.ts
  - src/utils/repo-attribution.ts
  - src/utils/repo-cache.ts
  - src/utils/reports-branch.ts
  - src/utils/session-id.ts
  - src/utils/shell-command.ts
  - src/utils/shell-profile.ts
  - src/utils/tags.ts
  - src/utils/team-codebase-paths.ts
  - src/utils/team-history.ts
  - src/utils/team-revision.ts
  - src/utils/teamwiki-root.ts
  - src/utils/tokenizer.ts
  - src/utils/toml.ts
  - src/utils/tool-call.ts
  - src/utils/tool-names.ts
  - src/utils/warn-once.ts
  - src/utils/yaml.ts
  - src/wiki-engine/call-chain-tracer.ts
  - src/wiki-engine/code-graph-overlay.ts
  - src/wiki-engine/interface-scanner.ts
  - src/wiki-engine/knowledge-reconciler.ts
  - src/wiki-engine/manifest-schema.ts
  - src/wiki-engine/reconciler-v2-types.ts
  - src/workflow/admission.ts
  - src/workflow/attempt-marker.ts
  - src/workflow/attempt-result.ts
  - src/workflow/cache.ts
  - src/workflow/cli-start.ts
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
  - src/workflow/output.ts
  - src/workflow/parse-context.ts
  - src/workflow/parse-hitl.ts
  - src/workflow/parse-roles.ts
  - src/workflow/parse.ts
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
  - src/workflow/run-location.ts
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
  - src/workflow/writes.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-array-filter-map.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-chained-type-assertions.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-conditional-empty-object-spread.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-known-value-widening.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-module-mocking.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-object-parameters.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-reduce-accumulator-copy.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-reflect-apply.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-reflect-get.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-runtime-typeof.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-shape-in-symbol-names.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-unknown-parameters.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-unknown-returns.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-unknown-type-aliases.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-unsafe-dictionary-type.ts
  - oxlint-plugin-teamai/anti-slop/rules/no-widen-then-assert.ts
  - oxlint-plugin-teamai/anti-slop/rules/require-safety-comment-for-type-assertion.ts
  - oxlint-plugin-teamai/anti-slop/shared/array-method.ts
  - oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts
  - oxlint-plugin-teamai/anti-slop/shared/function-parameters.ts
  - oxlint-plugin-teamai/anti-slop/shared/lexical-type-parameters.ts
  - oxlint-plugin-teamai/anti-slop/shared/reflect-method.ts
  - oxlint-plugin-teamai/anti-slop/shared/scope.ts
  - oxlint-plugin-teamai/anti-slop/shared/type-alias-resolution.ts
  - packages/provider-core/src/contract.ts
  - packages/provider-core/src/registry.ts
  - packages/runtime-kit/src/answering.ts
  - packages/runtime-kit/src/journal.ts
  - packages/runtime-kit/src/ledger.ts
  - packages/runtime-kit/src/outer.ts
  - packages/runtime-kit/src/places.ts
  - packages/runtime-kit/src/repository.ts
  - packages/runtime-kit/src/serve.ts
  - packages/runtime-kit/src/wake.ts
  - packages/runtime-paseo/src/conversation.ts
  - packages/runtime-paseo/src/host-commands.ts
  - packages/runtime-paseo/src/journal.ts
  - packages/runtime-paseo/src/judge.ts
  - packages/runtime-paseo/src/offer.ts
  - packages/runtime-paseo/src/options.ts
  - packages/runtime-paseo/src/providers.ts
  - packages/runtime-paseo/src/runtime.ts
  - packages/runtime-paseo/src/sandbox.ts
  - packages/runtime-paseo/src/usage.ts
  - packages/runtime-paseo/src/wake.ts
  - packages/runtime-paseo/src/workspace.ts
  - packages/runtime-protocol/src/protocol.ts
  - packages/runtime-protocol/src/state-root.ts
  - packages/runtime-protocol/src/step-runtime.ts
  - packages/runtime-protocol/src/step-runtime.type-test.ts
  - packages/runtime-sandbox/src/attempt-socket.ts
  - packages/runtime-sandbox/src/bounded-tail.ts
  - packages/runtime-sandbox/src/deadline.ts
  - packages/runtime-sandbox/src/exec.ts
  - packages/runtime-sandbox/src/journal-root.ts
  - packages/runtime-sandbox/src/journal.ts
  - packages/runtime-sandbox/src/judge.ts
  - packages/runtime-sandbox/src/loopback.ts
  - packages/runtime-sandbox/src/options.ts
  - packages/runtime-sandbox/src/outer.ts
  - packages/runtime-sandbox/src/prompt.ts
  - packages/runtime-sandbox/src/provider-commands.ts
  - packages/runtime-sandbox/src/provider.ts
  - packages/runtime-sandbox/src/provider.type-test.ts
  - packages/runtime-sandbox/src/runtime.ts
  - packages/runtime-sandbox/src/sign-in.ts
  - packages/runtime-sandbox/src/step.ts
  - packages/runtime-sandbox/src/sweep.ts
  - packages/runtime-sandbox/src/this-machine.ts
  - packages/runtime-sandbox/src/warm.ts
  - packages/runtime-sandbox/src/wrapper.ts
  - packages/runtime-t3/src/add-instance.ts
  - packages/runtime-t3/src/added-projects.ts
  - packages/runtime-t3/src/auth.ts
  - packages/runtime-t3/src/conversation.ts
  - packages/runtime-t3/src/host-commands.ts
  - packages/runtime-t3/src/instances.ts
  - packages/runtime-t3/src/journal.ts
  - packages/runtime-t3/src/judge.ts
  - packages/runtime-t3/src/offer.ts
  - packages/runtime-t3/src/options.ts
  - packages/runtime-t3/src/place.ts
  - packages/runtime-t3/src/runtime.ts
  - packages/runtime-t3/src/sessions.ts
  - packages/runtime-t3/src/settings.ts
  - packages/runtime-t3/src/t3-command.ts
  - packages/runtime-t3/src/t3.ts
  - packages/runtime-t3/src/tool-instances.ts
  - packages/runtime-t3/src/wake.ts
  - packages/runtime-t3/src/within.ts
  - packages/runtime-testing/src/bundle.ts
  - packages/runtime-testing/src/connect.ts
  - packages/runtime-testing/src/leaks.ts
  - packages/runtime-tools/src/answer.ts
  - packages/runtime-tools/src/confined.ts
  - packages/runtime-tools/src/headless.ts
  - packages/runtime-tools/src/step.ts
  - packages/shared/src/cli-path.ts
  - packages/shared/src/debug-log.ts
  - packages/shared/src/entries-under.ts
  - packages/shared/src/exec.ts
  - packages/shared/src/fs-failure.ts
  - packages/shared/src/home.ts
  - packages/shared/src/json.ts
  - packages/shared/src/log.ts
  - packages/shared/src/lookpath.ts
  - packages/shared/src/process-group.ts
  - packages/shared/src/redact.ts
  - packages/shared/src/regular-file.ts
  - packages/shared/src/timer.ts
  - packages/shared/src/type-of-service.ts
  - packages/shared/src/yaml.ts
  - packages/tool-agy/src/agy-transcript.ts
  - packages/tool-agy/src/definitions.ts
  - packages/tool-agy/src/detect.ts
  - packages/tool-agy/src/facts.ts
  - packages/tool-agy/src/launch.ts
  - packages/tool-agy/src/session-adapter.ts
  - packages/tool-agy/src/sessions.ts
  - packages/tool-claude/src/definitions.ts
  - packages/tool-claude/src/detect.ts
  - packages/tool-claude/src/facts.ts
  - packages/tool-claude/src/launch.ts
  - packages/tool-claude/src/sessions.ts
  - packages/tool-codebuddy/src/codebuddy-adapter.ts
  - packages/tool-codebuddy/src/codebuddy-ide-adapter.ts
  - packages/tool-codebuddy/src/codebuddy-tokens.ts
  - packages/tool-codebuddy/src/definitions.ts
  - packages/tool-codebuddy/src/detect.ts
  - packages/tool-codebuddy/src/facts.ts
  - packages/tool-codebuddy/src/ide-history.ts
  - packages/tool-codebuddy/src/launch.ts
  - packages/tool-codebuddy/src/sessions.ts
  - packages/tool-codebuddy/src/workbuddy-adapter.ts
  - packages/tool-codebuddy/src/workbuddy-store.ts
  - packages/tool-codex/src/codex-desktop.ts
  - packages/tool-codex/src/definitions.ts
  - packages/tool-codex/src/facts.ts
  - packages/tool-codex/src/launch.ts
  - packages/tool-codex/src/sessions.ts
  - packages/tool-copilot/src/definitions.ts
  - packages/tool-copilot/src/facts.ts
  - packages/tool-copilot/src/launch.ts
  - packages/tool-copilot/src/session-adapter.ts
  - packages/tool-copilot/src/sessions.ts
  - packages/tool-core/src/definition.ts
  - packages/tool-core/src/detect.ts
  - packages/tool-core/src/instance.ts
  - packages/tool-core/src/launch.ts
  - packages/tool-core/src/registry.ts
  - packages/tool-core/src/reply.ts
  - packages/tool-core/src/stdout.ts
  - packages/tool-core/src/step-usage.ts
  - packages/tool-core/src/tokens.ts
  - packages/tool-core/src/usage-limit.ts
  - packages/tool-cursor/src/cursor-store.ts
  - packages/tool-cursor/src/definitions.ts
  - packages/tool-cursor/src/detect.ts
  - packages/tool-cursor/src/facts.ts
  - packages/tool-cursor/src/launch.ts
  - packages/tool-cursor/src/session-adapter.ts
  - packages/tool-cursor/src/sessions.ts
  - packages/tool-definitions/src/facts.ts
  - packages/tool-definitions/src/registry.ts
  - packages/tool-dsh/src/definitions.ts
  - packages/tool-dsh/src/detect.ts
  - packages/tool-dsh/src/facts.ts
  - packages/tool-hermes/src/definitions.ts
  - packages/tool-hermes/src/detect.ts
  - packages/tool-hermes/src/facts.ts
  - packages/tool-hermes/src/launch.ts
  - packages/tool-hermes/src/session-adapter.ts
  - packages/tool-hermes/src/sessions.ts
  - packages/tool-joycode/src/definitions.ts
  - packages/tool-joycode/src/facts.ts
  - packages/tool-joycode/src/sessions.ts
  - packages/tool-kiro/src/definitions.ts
  - packages/tool-kiro/src/facts.ts
  - packages/tool-kiro/src/launch.ts
  - packages/tool-launch/src/call-launch.ts
  - packages/tool-launch/src/confined-launch.ts
  - packages/tool-launch/src/run-step-launch.ts
  - packages/tool-muse/src/definitions.ts
  - packages/tool-muse/src/detect.ts
  - packages/tool-muse/src/facts.ts
  - packages/tool-muse/src/launch.ts
  - packages/tool-muse/src/muse-session.ts
  - packages/tool-muse/src/session-adapter.ts
  - packages/tool-muse/src/sessions.ts
  - packages/tool-openclaw/src/definitions.ts
  - packages/tool-openclaw/src/detect.ts
  - packages/tool-openclaw/src/facts.ts
  - packages/tool-openclaw/src/launch.ts
  - packages/tool-opencode/src/definitions.ts
  - packages/tool-opencode/src/facts.ts
  - packages/tool-opencode/src/launch.ts
  - packages/tool-opencode/src/opencode-db.ts
  - packages/tool-opencode/src/session-adapter.ts
  - packages/tool-opencode/src/sessions.ts
  - packages/tool-pi/src/definitions.ts
  - packages/tool-pi/src/detect.ts
  - packages/tool-pi/src/facts.ts
  - packages/tool-pi/src/launch.ts
  - packages/tool-pi/src/pi-session.ts
  - packages/tool-pi/src/session-adapter.ts
  - packages/tool-pi/src/sessions.ts
  - packages/tool-qoder/src/definitions.ts
  - packages/tool-qoder/src/facts.ts
  - packages/tool-qoder/src/launch.ts
  - packages/tool-qoder/src/sessions.ts
  - packages/tool-testing/src/conformance.ts
  - packages/tool-testing/src/fake-agent.ts
  - packages/tool-testing/src/fake-cli.ts
  - packages/tool-testing/src/replay-transcript.ts
  - packages/tool-trae/src/definitions.ts
  - packages/tool-trae/src/facts.ts
  - packages/tool-zcode/src/definitions.ts
  - packages/tool-zcode/src/facts.ts
  - scripts/verify/leftovers/containers.ts
  - scripts/verify/leftovers/places.ts
  - scripts/verify/leftovers/processes.ts
  - src/pkg/adapters/base.ts
  - src/pkg/adapters/claude-plugin.ts
  - src/pkg/adapters/npm.ts
  - src/providers/cnb/cnb-cli.ts
  - src/providers/git/repo-url.ts
  - src/providers/gitcode/gitcode-api.ts
  - src/providers/gitcode/mr-fetch.ts
  - src/providers/gitcode/org.ts
  - src/providers/gitcode/repo-url.ts
  - src/providers/github/gh-cli.ts
  - src/providers/github/gh-org.ts
  - src/providers/github/mr-fetch.ts
  - src/providers/github/repo-url.ts
  - src/providers/gitlab/gitlab-api.ts
  - src/providers/gitlab/mr-fetch.ts
  - src/providers/gitlab/org.ts
  - src/providers/gitlab/probe.ts
  - src/providers/gitlab/repo-url.ts
  - src/providers/tgit/gf-cli.ts
  - src/providers/tgit/gf-org.ts
  - src/providers/tgit/mr-fetch.ts
  - src/providers/tgit/oauth-token.ts
  - src/providers/tgit/repo-url.ts
  - src/providers/tgit/rest-auth.ts
  - src/session-flow/adapters/platform-facts.ts
  - src/token-usage/formats/copilot-shutdown.ts
  - src/wiki-engine/adapters/templates.ts
  - src/wiki-engine/code-knowledge/code-collector.ts
  - src/wiki-engine/code-knowledge/code-extractors.ts
  - src/wiki-engine/code-knowledge/code-fact-kind.ts
  - src/wiki-engine/code-knowledge/code-graph.ts
  - src/wiki-engine/code-knowledge/code-incremental.ts
  - src/wiki-engine/core/graph-index.schema.ts
  - src/wiki-engine/core/wiki-protocol.ts
  - src/workflow/conformance/delivery.ts
  - src/workflow/conformance/place.ts
  - src/workflow/discovery/generated-marker.ts
  - src/workflow/discovery/render.ts
  - src/workflow/discovery/workflow-skills.ts
  - src/workflow/fleet/beats.ts
  - src/workflow/fleet/fence.ts
  - src/workflow/fleet/gate.ts
  - src/workflow/fleet/guardian-stop.ts
  - src/workflow/fleet/member.ts
  - src/workflow/fleet/owner.ts
  - src/workflow/fleet/record.ts
  - src/workflow/place/adopted.ts
  - src/workflow/place/clone.ts
  - src/workflow/place/created.ts
  - src/workflow/place/data.ts
  - src/workflow/place/overlay.ts
  - src/workflow/place/place.ts
  - src/workflow/place/reader.ts
  - src/workflow/place/record.ts
  - src/workflow/place/role-copy.ts
  - src/workflow/place/setup.ts
  - src/workflow/place/team-without.ts
  - src/workflow/place/team.ts
  - src/workflow/place/worktree-snapshot.ts
  - src/workflow/place/writer.ts
  - src/workflow/runtimes/attempt.ts
  - src/workflow/runtimes/cancelled.ts
  - src/workflow/runtimes/composed.ts
  - src/workflow/runtimes/definitions.ts
  - src/workflow/runtimes/entry-identity.ts
  - src/workflow/runtimes/held.ts
  - src/workflow/runtimes/host.ts
  - src/workflow/runtimes/layers.ts
  - src/workflow/runtimes/locate.ts
  - src/workflow/runtimes/login.ts
  - src/workflow/runtimes/protocol.ts
  - src/workflow/runtimes/resource-folder.ts
  - src/workflow/runtimes/retry-command.ts
  - src/workflow/runtimes/sandbox-profiles.ts
  - src/workflow/runtimes/sources.ts
  - src/workflow/runtimes/stdio.ts
  - src/workflow/runtimes/tool-caller.ts
  - src/workflow/steps/git-locks.ts
  - src/workflow/steps/prompt.ts
  - src/workflow/steps/runtime-steps.ts
  - oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-ast.ts
  - oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-between-statements.ts
  - packages/runtime-paseo/src/daemon/address.ts
  - packages/runtime-paseo/src/daemon/app-client.ts
  - packages/runtime-paseo/src/daemon/client.ts
  - packages/runtime-paseo/src/daemon/connect.ts
  - packages/runtime-paseo/src/daemon/host.ts
  - packages/runtime-paseo/src/daemon/sign-in.ts
  - packages/runtime-paseo/src/testing/asar.ts
  - packages/runtime-paseo/src/testing/attempt-socket.ts
  - packages/runtime-paseo/src/testing/fake-daemon.ts
  - packages/runtime-paseo/src/testing/harness.ts
  - packages/runtime-paseo/src/testing/suite.ts
  - packages/runtime-sandbox/src/providers/bwrap.ts
  - packages/runtime-sandbox/src/providers/cli.ts
  - packages/runtime-sandbox/src/providers/container.ts
  - packages/runtime-sandbox/src/providers/native.ts
  - packages/runtime-sandbox/src/providers/sbx.ts
  - packages/runtime-sandbox/src/providers/seatbelt.ts
  - packages/runtime-sandbox/src/providers/vercel-copy.ts
  - packages/runtime-sandbox/src/providers/vercel.ts
  - packages/runtime-sandbox/src/testing/harness.ts
  - packages/runtime-sandbox/src/testing/leaks.ts
  - packages/runtime-sandbox/src/testing/native-harness.ts
  - packages/runtime-sandbox/src/testing/process-provider.ts
  - packages/runtime-sandbox/src/testing/this-machine.ts
  - packages/runtime-sandbox/src/testing/vercel-fake-sdk.ts
  - packages/runtime-t3/src/testing/harness.ts
  - packages/runtime-t3/src/testing/suite.ts
  - packages/tool-codebuddy/src/testing/ide-history.ts
  - packages/tool-codex/src/testing/fake-codex.ts
  - packages/tool-core/src/formats/claude-code.ts
  - packages/tool-core/src/formats/claude-jsonl.ts
  - packages/tool-core/src/formats/codex-rollout.ts
  - packages/tool-core/src/formats/codex.ts
  - packages/tool-core/src/sessions/base.ts
  - packages/tool-core/src/sessions/fs.ts
  - packages/tool-core/src/sessions/ids.ts
  - packages/tool-core/src/sessions/ir.ts
  - packages/tool-core/src/sessions/platform.ts
  - packages/tool-core/src/sessions/sqlite.ts
  - packages/tool-core/src/sessions/title.ts
  - packages/tool-launch/src/testing/launcher-conformance.ts
  - packages/tool-opencode/src/testing/fake-opencode.ts
  - src/wiki-engine/code-knowledge/ast/adapt-code-facts.ts
  - src/wiki-engine/code-knowledge/ast/call-resolver.ts
  - src/wiki-engine/code-knowledge/ast/import-bindings.ts
  - src/wiki-engine/code-knowledge/ast/import-resolver.ts
  - src/wiki-engine/code-knowledge/ast/merge-edges.ts
  - src/wiki-engine/code-knowledge/ast/module-scope.ts
  - src/wiki-engine/code-knowledge/ast/parser-registry.ts
  - src/wiki-engine/code-knowledge/ast/queries.ts
  - src/wiki-engine/code-knowledge/ast/walk.ts
  - src/wiki-engine/code-knowledge/extractors/config.ts
  - src/wiki-engine/code-knowledge/extractors/go.ts
  - src/wiki-engine/code-knowledge/extractors/java.ts
  - src/wiki-engine/code-knowledge/extractors/python.ts
  - src/wiki-engine/code-knowledge/extractors/rust.ts
  - src/wiki-engine/code-knowledge/extractors/scala.ts
  - src/wiki-engine/code-knowledge/extractors/swift.ts
  - src/wiki-engine/code-knowledge/extractors/typescript.ts
  - src/workflow/drivers/local/local-driver.ts
  - src/workflow/drivers/skill/child-brief.ts
  - src/workflow/drivers/skill/child-model.ts
  - src/workflow/drivers/skill/engine-replies.ts
  - src/workflow/drivers/skill/job.ts
  - src/workflow/drivers/skill/journal.ts
  - src/workflow/drivers/skill/literals.ts
  - src/workflow/drivers/skill/preflight.ts
  - src/workflow/drivers/skill/session-host-profiles.ts
  - src/workflow/drivers/skill/skill-driver.ts
  - src/workflow/drivers/skill/skill-runner.ts
  - src/workflow/drivers/skill/skill-state.ts
  - src/workflow/drivers/skill/tick.ts
  - src/workflow/drivers/skill/transitions.ts
  - src/workflow/drivers/skill/turn.ts
  - oxlint-plugin-teamai/failure-codes.js
  - oxlint-plugin-teamai/fs-calls.js
  - oxlint-plugin-teamai/imports.js
  - oxlint-plugin-teamai/index.js
  - oxlint-plugin-teamai/utils.js
  - oxlint-plugin-teamai/rules/attempt-abort.js
  - oxlint-plugin-teamai/rules/attempt-marker-reads.js
  - oxlint-plugin-teamai/rules/attempt-reattach.js
  - oxlint-plugin-teamai/rules/attempt-result-writes.js
  - oxlint-plugin-teamai/rules/config-load-options.js
  - oxlint-plugin-teamai/rules/configured-tool-paths.js
  - oxlint-plugin-teamai/rules/family-facts.js
  - oxlint-plugin-teamai/rules/git-exit-code.js
  - oxlint-plugin-teamai/rules/home-env.js
  - oxlint-plugin-teamai/rules/launch-env.js
  - oxlint-plugin-teamai/rules/launch-through-workflows.js
  - oxlint-plugin-teamai/rules/launcher-conformance.js
  - oxlint-plugin-teamai/rules/learnings-root.js
  - oxlint-plugin-teamai/rules/mock-source.js
  - oxlint-plugin-teamai/rules/no-low-value-comments.js
  - oxlint-plugin-teamai/rules/no-provider-merge.js
  - oxlint-plugin-teamai/rules/opencode-major.js
  - oxlint-plugin-teamai/rules/package-boundaries.js
  - oxlint-plugin-teamai/rules/piped-git.js
  - oxlint-plugin-teamai/rules/process-reads.js
  - oxlint-plugin-teamai/rules/readline-error.js
  - oxlint-plugin-teamai/rules/recursive-readdir.js
  - oxlint-plugin-teamai/rules/regular-file-reads.js
  - oxlint-plugin-teamai/rules/remove-delivered.js
  - oxlint-plugin-teamai/rules/rules-locate.js
  - oxlint-plugin-teamai/rules/runtime-serve.js
  - oxlint-plugin-teamai/rules/shipped-tool-ids.js
  - oxlint-plugin-teamai/rules/signal-owner.js
  - oxlint-plugin-teamai/rules/spawn-command.js
  - oxlint-plugin-teamai/rules/step-path-writes.js
  - oxlint-plugin-teamai/rules/suppression-reason.js
  - oxlint-plugin-teamai/rules/test-seams.js
  - oxlint-plugin-teamai/rules/tool-facts.js
  - oxlint-plugin-teamai/rules/tool-family-shape.js
  - oxlint-plugin-teamai/rules/tool-home-env.js
  - oxlint-plugin-teamai/rules/tool-registry.js
  - oxlint-plugin-teamai/rules/uncached-entry.js
  - oxlint-plugin-teamai/rules/unspawned-child.js
  - oxlint-plugin-teamai/rules/untrusted-finish-git.js
  - oxlint-plugin-teamai/rules/windows-tests.js
  - oxlint-plugin-teamai/rules/workflow-boundaries.js
  - oxlint-plugin-teamai/rules/workflow-failure-codes.js
  - oxlint-plugin-teamai/rules/worktree-removal.js
  - oxlint-plugin-teamai/rules/yaml-parse.js
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
- `LAUNCH_ADAPTERS` ← src/launch-registry.ts:13 [EXTRACTED]
  ```
  export const LAUNCH_ADAPTERS = {
  ```
- `LAUNCH_ORDER` ← src/launch-registry.ts:45 [EXTRACTED]
  ```
  export const LAUNCH_ORDER = ['claude', 'claude-internal', 'tclaude', 'codex', 'codex-internal', 'tcodex', 'opencode', 'codebuddy', 'workbuddy', 'openclaw', 'cursor', 'copilot', 'qoder', 'kiro', 'pi', 'omp', 'muse', 'hermes', 'agy'] as const satisfies readonly LaunchedToolId[];
  ```
- `launchAdapterIdOf` ← src/launch-registry.ts:50 [EXTRACTED]
  ```
  export function launchAdapterIdOf<T extends LaunchedToolId>(tool: T): DescriptorOf<T>['launch'] {
  ```
- `launchAdapterOf` ← src/launch-registry.ts:54 [EXTRACTED]
  ```
  export function launchAdapterOf<T extends LaunchedToolId>(tool: T): LaunchAdapterOf<T> {
  ```
- `executableOf` ← src/launch-registry.ts:59 [EXTRACTED]
  ```
  export function executableOf(tool: LaunchOrderTool): string {
  ```
- `executablesOf` ← src/launch-registry.ts:69 [EXTRACTED]
  ```
  export function executablesOf(tool: string): string[] {
  ```
- `LAUNCH_TOOLS` ← src/launch-registry.ts:88 [EXTRACTED]
  ```
  export const LAUNCH_TOOLS = toolsWith('step');
  ```
- `isLaunchTool` ← src/launch-registry.ts:92 [EXTRACTED]
  ```
  export function isLaunchTool(value: string): value is LaunchTool {
  ```
- `launchTargetOf` ← src/launch-registry.ts:108 [EXTRACTED]
  ```
  export function launchTargetOf(name: string): LaunchTarget | undefined {
  ```
- `homeVariableOf` ← src/launch-registry.ts:120 [EXTRACTED]
  ```
  export function homeVariableOf(tool: string): string | undefined {
  ```
- `deliveredHomeVariableOf` ← src/launch-registry.ts:135 [EXTRACTED]
  ```
  export function deliveredHomeVariableOf(tool: ToolId): string | undefined {
  ```
- `toolCommandEnv` ← src/launch-registry.ts:164 [EXTRACTED]
  ```
  export function toolCommandEnv(name: string, home: Extract<ToolCommandHome, { kind: 'at' }>): ToolCommandEnv;
  ```
- `launchExecutableOf` ← src/launch-registry.ts:244 [EXTRACTED]
  ```
  export function launchExecutableOf(target: Pick<LaunchTarget, 'instance'> & { readonly tool: LaunchOrderTool }): string | null {
  ```
- `CONFINED_TOOLS` ← src/launch-registry.ts:251 [EXTRACTED]
  ```
  export const CONFINED_TOOLS = toolsWith('confined');
  ```
- `computeLintResourceGraph` ← src/lint-resource-graph.ts:60 [EXTRACTED]
  ```
  export function computeLintResourceGraph(scopes: readonly LintScopeGraph[]): LintResourceGraph {
  ```
- `memberScopeGraphs` ← src/lint-resource-graph.ts:211 [EXTRACTED]
  ```
  export async function memberScopeGraphs(opts: { dryRun?: boolean; config?: LocalConfig } = {}): Promise<LintScopeGraph[] | null> {
  ```
- `lintResourceGraph` ← src/lint-resource-graph.ts:295 [EXTRACTED]
  ```
  export async function lintResourceGraph(opts: { dryRun?: boolean } = {}): Promise<LintResourceGraph | null> {
  ```
- `deliveryPlaceOf` ← src/locate.ts:60 [EXTRACTED]
  ```
  export function deliveryPlaceOf(team: Pick<TeamaiConfig, 'toolPaths'>, local: Pick<LocalConfig, 'scope' | 'toolRoots'>): DeliveryPlace {
  ```
- `installOf` ← src/locate.ts:65 [EXTRACTED]
  ```
  export function installOf(
  ```
- `KNOWLEDGE_RESOURCES` ← src/locate.ts:108 [EXTRACTED]
  ```
  export const KNOWLEDGE_RESOURCES = ['skills', 'rules', 'blocks', 'agents'] as const satisfies readonly Resource[];
  ```
- `SHARED_AGENT_SKILLS_PATH` ← src/locate.ts:313 [EXTRACTED]
  ```
  export const SHARED_AGENT_SKILLS_PATH = '.agents/skills';
  ```
- `locatingOnce` ← src/locate.ts:343 [EXTRACTED]
  ```
  export function locatingOnce<T>(walk: () => Promise<T>, host: Host = realHost()): Promise<T> {
  ```
- `locate` ← src/locate.ts:358 [EXTRACTED]
  ```
  export async function locate<R extends Resource>(tool: string, resource: R, install: Install, host?: Host): Promise<Location<R>> {
  ```
- `resolvedPathOn` ← src/locate.ts:382 [EXTRACTED]
  ```
  export async function resolvedPathOn(host: Host, file: string): Promise<string> {
  ```
- `writable` ← src/locate.ts:415 [EXTRACTED]
  ```
  export function writable<P extends Place>(location: Located<P>): P | null {
  ```
- `ownOf` ← src/locate.ts:420 [EXTRACTED]
  ```
  export function ownOf<P extends Place>(location: Located<P>): P | null {
  ```
- `workspaceHooksOf` ← src/locate.ts:425 [EXTRACTED]
  ```
  export function workspaceHooksOf(location: Location<'hooks'>): EntryPlace | null {
  ```
- `isInstalledFor` ← src/locate.ts:430 [EXTRACTED]
  ```
  export function isInstalledFor(location: { readonly gates: readonly Gate[] }): boolean {
  ```
- `writesOf` ← src/locate.ts:435 [EXTRACTED]
  ```
  export function writesOf<P extends Place>(location: Located<P> & Beside<P>): P[] {
  ```
- `cleanupOf` ← src/locate.ts:442 [EXTRACTED]
  ```
  export function cleanupOf<P extends Place>(location: Located<P> & Beside<P>): Place[] {
  ```
- `unreadWrites` ← src/locate.ts:468 [EXTRACTED]
  ```
  export function unreadWrites<P extends Place>(
  ```
- `agentsDirAt` ← src/locate.ts:605 [EXTRACTED]
  ```
  export function agentsDirAt(tool: string, place: DeliveryPlace, host: Host = realHost()): string | null {
  ```
- `userViewOf` ← src/locate.ts:706 [EXTRACTED]
  ```
  export async function userViewOf(install: Install, host: Host = realHost()): Promise<Install> {
  ```
- `openclawWorkspaceDir` ← src/locate.ts:834 [EXTRACTED]
  ```
  export async function openclawWorkspaceDir(host: Host = realHost()): Promise<string | null> {
  ```
- `hookSettingsFile` ← src/locate.ts:1488 [EXTRACTED]
  ```
  export function hookSettingsFile(tool: string, baseDir: string, relative: string, host: Host = realHost()): string {
  ```
- `toolPathUnder` ← src/locate.ts:1493 [EXTRACTED]
  ```
  export function toolPathUnder(tool: string, baseDir: string, relative: string, host: Host = realHost()): string {
  ```
- `hookAdapterDir` ← src/locate.ts:1498 [EXTRACTED]
  ```
  export function hookAdapterDir(adapter: Exclude<HookAdapterId, 'openclaw-hook'>, host: Host = realHost()): string {
  ```
- `hookAdapterDirIn` ← src/locate.ts:1503 [EXTRACTED]
  ```
  export function hookAdapterDirIn(adapter: Exclude<HookAdapterId, 'openclaw-hook' | 'dsh-hooks'>, home: string, host: Host = realHost()): string {
  ```
- `earlierHookAdapterDir` ← src/locate.ts:1511 [EXTRACTED]
  ```
  export async function earlierHookAdapterDir(adapter: Exclude<HookAdapterId, 'openclaw-hook'>, host: Host = realHost()): Promise<string | null> {
  ```
- `sessionStoreDir` ← src/locate.ts:1665 [EXTRACTED]
  ```
  export function sessionStoreDir(
  ```
- `getMachineId` ← src/machine-id.ts:37 [EXTRACTED]
  ```
  export function getMachineId(): string {
  ```
- `detectMachineId` ← src/machine-id.ts:45 [EXTRACTED]
  ```
  export function detectMachineId(platform: NodeJS.Platform = process.platform): string {
  ```
- `deriveLocalAgentId` ← src/machine-id.ts:116 [EXTRACTED]
  ```
  export function deriveLocalAgentId(agentType: string, machineId: string, installPath: string): string {
  ```
- `deriveInstanceId` ← src/machine-id.ts:125 [EXTRACTED]
  ```
  export function deriveInstanceId(agentType: string, localAgentId: string): string {
  ```
- `pullLatest` ← src/manifest-edit.ts:9 [EXTRACTED]
  ```
  export async function pullLatest(repoPath: string): Promise<void> {
  ```
- `runManifestEdit` ← src/manifest-edit.ts:30 [EXTRACTED]
  ```
  export async function runManifestEdit(
  ```
- `pushManifestChange` ← src/manifest-edit.ts:68 [EXTRACTED]
  ```
  export async function pushManifestChange(input: {
  ```
- `isSafeNamespaceSegment` ← src/manifest-schema.ts:55 [EXTRACTED]
  ```
  export function isSafeNamespaceSegment(seg: string): boolean {
  ```
- `NAMESPACE_RULE` ← src/manifest-schema.ts:62 [EXTRACTED]
  ```
  export const NAMESPACE_RULE = "resource namespace must be a single path segment (no '/', '\\', ':' or control characters, no trailing '.' or space, which also rules out '.' and '..', and not a Windows device name such as 'CON' or 'COM1')";
  ```
- `NamespaceSegmentSchema` ← src/manifest-schema.ts:69 [EXTRACTED]
  ```
  export const NamespaceSegmentSchema = z.string().min(1).refine(isSafeNamespaceSegment, {
  ```
- `HAND_DECLARED_RESOURCE_TYPES` ← src/manifest-schema.ts:82 [EXTRACTED]
  ```
  export const HAND_DECLARED_RESOURCE_TYPES = [
  ```
- `RESERVED_DOCS_DIR` ← src/manifest-schema.ts:105 [EXTRACTED]
  ```
  export const RESERVED_DOCS_DIR = 'team-codebase';
  ```
- `HandDeclaredNamespaceFields` ← src/manifest-schema.ts:113 [EXTRACTED]
  ```
  export const HandDeclaredNamespaceFields = {
  ```
- `warnUnknownResourceKeys` ← src/manifest-schema.ts:138 [EXTRACTED]
  ```
  export function warnUnknownResourceKeys(
  ```
- `assertSafeFallbackNamespaces` ← src/manifest-schema.ts:159 [EXTRACTED]
  ```
  export function assertSafeFallbackNamespaces(ids: string[], source: string): string[] {
  ```
- `fallbackNamespaceError` ← src/manifest-schema.ts:171 [EXTRACTED]
  ```
  export function fallbackNamespaceError(ids: string[], source: string): string | null {
  ```
- `parseManifest` ← src/manifest-schema.ts:185 [EXTRACTED]
  ```
  export function parseManifest<S extends z.ZodType>(schema: S, raw: JsonValue | z.output<S>, kind: ManifestKind): z.infer<S> {
  ```
- `readManifestFile` ← src/manifest-schema.ts:234 [EXTRACTED]
  ```
  export async function readManifestFile(manifestPath: string, kind: ManifestKind): Promise<string | null> {
  ```
- `emptyManifestError` ← src/manifest-schema.ts:260 [EXTRACTED]
  ```
  export function emptyManifestError(kind: ManifestKind, where: string): Error {
  ```
- `parseManifestOnce` ← src/manifest-schema.ts:275 [EXTRACTED]
  ```
  export function parseManifestOnce<T>(manifestPath: string, content: string, parse: (content: string) => T): T {
  ```
- `caseFoldKey` ← src/manifest-schema.ts:306 [EXTRACTED]
  ```
  export function caseFoldKey(name: string): string {
  ```
- `assertNoCaseAliasedNamespaces` ← src/manifest-schema.ts:317 [EXTRACTED]
  ```
  export function assertNoCaseAliasedNamespaces(entries: Iterable<NamespaceEntry>, kind: string): void {
  ```
- `mcpList` ← src/mcp-cmd.ts:37 [EXTRACTED]
  ```
  export async function mcpList(_options: GlobalOptions): Promise<void> {
  ```
- `mcpInject` ← src/mcp-cmd.ts:159 [EXTRACTED]
  ```
  export async function mcpInject(
  ```
- `mcpRemove` ← src/mcp-cmd.ts:190 [EXTRACTED]
  ```
  export async function mcpRemove(options: GlobalOptions): Promise<void> {
  ```
- `carriesResolvedValue` ← src/mcp-git-exclude.ts:37 [EXTRACTED]
  ```
  export function carriesResolvedValue(
  ```
- `carriesLocalAgentCredential` ← src/mcp-git-exclude.ts:58 [EXTRACTED]
  ```
  export function carriesLocalAgentCredential<TEntry>(entry: TEntry): boolean {
  ```
- `resolvedVariableIn` ← src/mcp-git-exclude.ts:99 [EXTRACTED]
  ```
  export function resolvedVariableIn(
  ```
- `ensureExcludedFromGit` ← src/mcp-git-exclude.ts:143 [EXTRACTED]
  ```
  export async function ensureExcludedFromGit(
  ```
- `excludeFromGit` ← src/mcp-git-exclude.ts:164 [EXTRACTED]
  ```
  export async function excludeFromGit(file: string, options: { rerun?: string; holds?: string } = {}): Promise<void> {
  ```
- `findMcpGitExcludes` ← src/mcp-git-exclude.ts:182 [EXTRACTED]
  ```
  export async function findMcpGitExcludes(dirs: Iterable<string>): Promise<Map<string, Array<{ pattern: string; files: string[] }>>> {
  ```
- `mcpExcludePatternPath` ← src/mcp-git-exclude.ts:213 [EXTRACTED]
  ```
  export function mcpExcludePatternPath(pattern: string): string {
  ```
- `removeMcpGitExclude` ← src/mcp-git-exclude.ts:221 [EXTRACTED]
  ```
  export async function removeMcpGitExclude(excludeFile: string, patterns: string[]): Promise<ExcludeUpdate> {
  ```
- `describeKeptMemberServer` ← src/mcp-reconcile.ts:168 [EXTRACTED]
  ```
  export function describeKeptMemberServer(server: string, file: string): string {
  ```
- `buildVarTable` ← src/mcp-reconcile.ts:221 [EXTRACTED]
  ```
  export async function buildVarTable(localConfig: LocalConfig, teamEnv?: TeamEnv): Promise<Record<string, string>> {
  ```
- `teamMcpRefusal` ← src/mcp-reconcile.ts:309 [EXTRACTED]
  ```
  export function teamMcpRefusal(localConfig: LocalConfig, teamConfig: TeamaiConfig, resolved: ResolvedEntry<TeamMcpDefinition>): string | null {
  ```
- `mcpKeyOf` ← src/mcp-reconcile.ts:380 [EXTRACTED]
  ```
  export function mcpKeyOf(target: Pick<McpTarget, 'format' | 'key'>): McpKey {
  ```
- `claudeProjectKey` ← src/mcp-reconcile.ts:394 [EXTRACTED]
  ```
  export async function claudeProjectKey(checkoutRoot: string): Promise<string> {
  ```
- `mcpManifestKey` ← src/mcp-reconcile.ts:418 [EXTRACTED]
  ```
  export function mcpManifestKey(target: Pick<McpTarget, 'tool' | 'projectScope' | 'projectKey'>): string {
  ```
- `describeMcpLocation` ← src/mcp-reconcile.ts:438 [EXTRACTED]
  ```
  export function describeMcpLocation(target: Pick<McpTarget, 'file' | 'projectKey'>): string {
  ```
- `projectMcpLocations` ← src/mcp-reconcile.ts:512 [EXTRACTED]
  ```
  export async function projectMcpLocations(
  ```
- `mcpRelocated` ← src/mcp-reconcile.ts:531 [EXTRACTED]
  ```
  export async function mcpRelocated(teamConfig: TeamaiConfig, localConfig: LocalConfig, tool: string): Promise<boolean> {
  ```
- `recordedFileOf` ← src/mcp-reconcile.ts:563 [EXTRACTED]
  ```
  export function recordedFileOf(target: Pick<McpTarget, 'file' | 'mappedFile' | 'unmovedFile'>, record: ManagedMcpRecord): string {
  ```
- `recordedMcpTarget` ← src/mcp-reconcile.ts:577 [EXTRACTED]
  ```
  export async function recordedMcpTarget(target: McpTarget, record: ManagedMcpRecord): Promise<McpTarget> {
  ```
- `sameMcpPlace` ← src/mcp-reconcile.ts:584 [EXTRACTED]
  ```
  export async function sameMcpPlace(a: McpTarget, b: McpTarget): Promise<boolean> {
  ```
- `sameMcpFile` ← src/mcp-reconcile.ts:592 [EXTRACTED]
  ```
  export async function sameMcpFile(a: string, b: string): Promise<boolean> {
  ```
- `shadowedMcpRecords` ← src/mcp-reconcile.ts:601 [EXTRACTED]
  ```
  export async function shadowedMcpRecords(localConfig: LocalConfig, target: McpTarget): Promise<Map<string, string[]>> {
  ```
- `mcpCleanupFiles` ← src/mcp-reconcile.ts:623 [EXTRACTED]
  ```
  export async function mcpCleanupFiles(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<string[]> {
  ```
- `resolveMcpTargets` ← src/mcp-reconcile.ts:646 [EXTRACTED]
  ```
  export async function resolveMcpTargets(
  ```
- `unrecordedMcpTool` ← src/mcp-reconcile.ts:746 [EXTRACTED]
  ```
  export function unrecordedMcpTool(target: McpTarget, targets: McpTarget[], writers: readonly string[] = []): boolean {
  ```
- `unmappedMcpDefaults` ← src/mcp-reconcile.ts:760 [EXTRACTED]
  ```
  export async function unmappedMcpDefaults(targets: McpTarget[]): Promise<Set<McpTarget>> {
  ```
- `unrecordedUnmappedMcpDefaults` ← src/mcp-reconcile.ts:779 [EXTRACTED]
  ```
  export async function unrecordedUnmappedMcpDefaults(
  ```
- `readJsonDoc` ← src/mcp-reconcile.ts:843 [EXTRACTED]
  ```
  export async function readJsonDoc(
  ```
- `writeJsonDoc` ← src/mcp-reconcile.ts:1010 [EXTRACTED]
  ```
  export async function writeJsonDoc(
  ```
- `restoreMcpDoc` ← src/mcp-reconcile.ts:1155 [EXTRACTED]
  ```
  export async function restoreMcpDoc(file: string, doc: Pick<JsonDoc, 'raw'>): Promise<void> {
  ```
- `writeMcpJson` ← src/mcp-reconcile.ts:1202 [EXTRACTED]
  ```
  export async function writeMcpJson(file: string, data: JsonValue, options?: { mode?: number }): Promise<void> {
  ```
- `spliceCodexBlock` ← src/mcp-reconcile.ts:1241 [EXTRACTED]
  ```
  export function spliceCodexBlock(source: string, name: string, block: string | null): string {
  ```
- `codexBlockIn` ← src/mcp-reconcile.ts:1310 [EXTRACTED]
  ```
  export function codexBlockIn(source: string, name: string): string | null {
  ```
- `codexServerNames` ← src/mcp-reconcile.ts:1320 [EXTRACTED]
  ```
  export function codexServerNames(source: string): string[] {
  ```
- `buildDesiredMcpContext` ← src/mcp-reconcile.ts:1353 [EXTRACTED]
  ```
  export async function buildDesiredMcpContext(
  ```
- `desiredMcpForTarget` ← src/mcp-reconcile.ts:1392 [EXTRACTED]
  ```
  export function desiredMcpForTarget(
  ```
- `claimedByOtherTools` ← src/mcp-reconcile.ts:1524 [EXTRACTED]
  ```
  export async function claimedByOtherTools(
  ```
- `memberMcpServers` ← src/mcp-reconcile.ts:1612 [EXTRACTED]
  ```
  export async function memberMcpServers(
  ```
- `installedMcpEntries` ← src/mcp-reconcile.ts:1653 [EXTRACTED]
  ```
  export async function installedMcpEntries(
  ```
- `installedMcpEntryTexts` ← src/mcp-reconcile.ts:1682 [EXTRACTED]
  ```
  export async function installedMcpEntryTexts(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<Array<{ readonly file: string; readonly text: string }>> {
  ```
- `loadMcpManifest` ← src/mcp-reconcile.ts:1711 [EXTRACTED]
  ```
  export async function loadMcpManifest(
  ```
- `readMcpManifest` ← src/mcp-reconcile.ts:1733 [EXTRACTED]
  ```
  export async function readMcpManifest(localConfig: LocalConfig): Promise<ManagedMcpManifest> {
  ```
- `saveMcpManifest` ← src/mcp-reconcile.ts:1771 [EXTRACTED]
  ```
  export async function saveMcpManifest(localConfig: LocalConfig, manifestPath: string, manifest: ManagedMcpManifest): Promise<void> {
  ```
- `keptMcpEntries` ← src/mcp-reconcile.ts:1823 [EXTRACTED]
  ```
  export async function keptMcpEntries(
  ```
- `resolvedValueEvidence` ← src/mcp-reconcile.ts:1868 [EXTRACTED]
  ```
  export async function resolvedValueEvidence(
  ```
- `unclaimedMcpServers` ← src/mcp-reconcile.ts:1925 [EXTRACTED]
  ```
  export async function unclaimedMcpServers(target: McpTarget, claimed: readonly string[]): Promise<string[]> {
  ```
- `judgeTeamaiOnlyMcpConfigs` ← src/mcp-reconcile.ts:1953 [EXTRACTED]
  ```
  export async function judgeTeamaiOnlyMcpConfigs(
  ```
- `opencodeV1Servers` ← src/mcp-reconcile.ts:2054 [EXTRACTED]
  ```
  export async function opencodeV1Servers(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<{ file: string; names: string[] } | null> {
  ```
- `recordedMcpTargets` ← src/mcp-reconcile.ts:2167 [EXTRACTED]
  ```
  export async function recordedMcpTargets(cfg: LocalConfig, known: McpTarget[]): Promise<Map<string, RecordedMcpFile>> {
  ```
- `earlierMappedMcpTargets` ← src/mcp-reconcile.ts:2226 [EXTRACTED]
  ```
  export async function earlierMappedMcpTargets(
  ```
- `recordedMcpFileEvidence` ← src/mcp-reconcile.ts:2324 [EXTRACTED]
  ```
  export async function recordedMcpFileEvidence(targets: McpTarget[], owned?: McpOwnedFor): Promise<string | null> {
  ```
- `ownedByMappers` ← src/mcp-reconcile.ts:2383 [EXTRACTED]
  ```
  export function ownedByMappers(mappedBy: readonly string[], manifest: ManagedMcpManifest | undefined): McpOwnedFor | undefined {
  ```
- `earlierMappedMcpFileEvidence` ← src/mcp-reconcile.ts:2402 [EXTRACTED]
  ```
  export async function earlierMappedMcpFileEvidence(
  ```
- `projectWorktreeConfigs` ← src/mcp-reconcile.ts:2471 [EXTRACTED]
  ```
  export async function projectWorktreeConfigs(localConfig: LocalConfig): Promise<LocalConfig[]> {
  ```
- `mcpConfigsNotProvenClean` ← src/mcp-reconcile.ts:2518 [EXTRACTED]
  ```
  export async function mcpConfigsNotProvenClean(
  ```
- `mcpTargetAgent` ← src/mcp-reconcile.ts:2699 [EXTRACTED]
  ```
  export function mcpTargetAgent(target: McpTarget): string {
  ```
- `mcpTargetAgents` ← src/mcp-reconcile.ts:2704 [EXTRACTED]
  ```
  export function mcpTargetAgents(target: McpTarget): string[] {
  ```
- `mcpTargetTakes` ← src/mcp-reconcile.ts:2709 [EXTRACTED]
  ```
  export function mcpTargetTakes(target: McpTarget, tools: readonly string[] | undefined): boolean {
  ```
- `mcpTargetExcluded` ← src/mcp-reconcile.ts:2713 [EXTRACTED]
  ```
  export function mcpTargetExcluded(localConfig: LocalConfig, target: McpTarget): boolean {
  ```
- `unreadMcpPlaces` ← src/mcp-reconcile.ts:2732 [EXTRACTED]
  ```
  export async function unreadMcpPlaces(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<string[]> {
  ```
- `noteManagedMcpHome` ← src/mcp-reconcile.ts:2800 [EXTRACTED]
  ```
  export async function noteManagedMcpHome(dataHome: string): Promise<void> {
  ```
- `mcpOwnersOf` ← src/mcp-reconcile.ts:2867 [EXTRACTED]
  ```
  export async function mcpOwnersOf(
  ```
- `adoptMcpEntriesForOwners` ← src/mcp-reconcile.ts:2919 [EXTRACTED]
  ```
  export async function adoptMcpEntriesForOwners(
  ```
- `reconcileMcpForConfig` ← src/mcp-reconcile.ts:2955 [EXTRACTED]
  ```
  export async function reconcileMcpForConfig(
  ```
- `withMcpLock` ← src/mcp-reconcile.ts:2966 [EXTRACTED]
  ```
  export async function withMcpLock<T>(body: () => Promise<T>): Promise<T> {
  ```
- `localAgentCredentialFiles` ← src/mcp-reconcile.ts:3073 [EXTRACTED]
  ```
  export async function localAgentCredentialFiles(localConfig: LocalConfig, targets: McpTarget[]): Promise<McpTarget[]> {
  ```
- `protectLocalAgentMcpConfigs` ← src/mcp-reconcile.ts:3121 [EXTRACTED]
  ```
  export async function protectLocalAgentMcpConfigs(
  ```
- `releaseCleanMcpGitExcludes` ← src/mcp-reconcile.ts:3310 [EXTRACTED]
  ```
  export async function releaseCleanMcpGitExcludes(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<void> {
  ```
- `isTeamaiBareCopy` ← src/mcp-reconcile.ts:3899 [EXTRACTED]
  ```
  export function isTeamaiBareCopy(doc: Pick<JsonDoc, 'beside'>, name: string, owned: readonly ManagedMcpRecord[]): boolean {
  ```
- `ownsJsonMcpEntry` ← src/mcp-reconcile.ts:3906 [EXTRACTED]
  ```
  export function ownsJsonMcpEntry(
  ```
- `logLeftMcpFiles` ← src/mcp-reconcile.ts:4238 [EXTRACTED]
  ```
  export function logLeftMcpFiles(localConfig: LocalConfig, target: McpTarget, left: readonly ManagedMcpRecord[]): void {
  ```
- `removeLocalScopeMcpServers` ← src/mcp-reconcile.ts:4613 [EXTRACTED]
  ```
  export async function removeLocalScopeMcpServers(dataHome: string, toolRoots?: Record<string, string>): Promise<string[]> {
  ```
- `deleteEmptiedMcpFile` ← src/mcp-reconcile.ts:4673 [EXTRACTED]
  ```
  export async function deleteEmptiedMcpFile(file: string, serverKey: string | McpKey | null = MCP_SERVER_KEY.claude): Promise<boolean> {
  ```
- `writeCodexAtomic` ← src/mcp-reconcile.ts:5035 [EXTRACTED]
  ```
  export async function writeCodexAtomic(file: string, content: string): Promise<void> {
  ```
- `resolvedMcpFilesPath` ← src/mcp-resolved-files.ts:63 [EXTRACTED]
  ```
  export function resolvedMcpFilesPath(cfg: LocalConfig): string | null {
  ```
- `readResolvedMcpFiles` ← src/mcp-resolved-files.ts:94 [EXTRACTED]
  ```
  export async function readResolvedMcpFiles(cfg: LocalConfig): Promise<ResolvedMcpFiles> {
  ```
- `updateResolvedMcpFiles` ← src/mcp-resolved-files.ts:113 [EXTRACTED]
  ```
  export function updateResolvedMcpFiles(cfg: LocalConfig, edit: (files: Record<string, ResolvedMcpFile>) => boolean): Promise<ExcludeUpdate> {
  ```
- `trackResolvedMcpFiles` ← src/mcp-resolved-files.ts:130 [EXTRACTED]
  ```
  export function trackResolvedMcpFiles(cfg: LocalConfig, targets: Array<{ tool: string; file: string }>): Promise<ExcludeUpdate> {
  ```
- `untrackResolvedMcpFiles` ← src/mcp-resolved-files.ts:147 [EXTRACTED]
  ```
  export function untrackResolvedMcpFiles(cfg: LocalConfig, targets: Array<{ tool: string; file: string }>): Promise<ExcludeUpdate> {
  ```
- `recordUnverifiedMcpServers` ← src/mcp-resolved-files.ts:170 [EXTRACTED]
  ```
  export function recordUnverifiedMcpServers(cfg: LocalConfig, found: Array<{ file: string; names: string[] }>): Promise<ExcludeUpdate> {
  ```
- `settleResolvedMcpFiles` ← src/mcp-resolved-files.ts:200 [EXTRACTED]
  ```
  export function settleResolvedMcpFiles(
  ```
- `memberEnvironment` ← src/member-env.ts:53 [EXTRACTED]
  ```
  export async function memberEnvironment(
  ```
- `memberEnvironmentWithoutScope` ← src/member-env.ts:67 [EXTRACTED]
  ```
  export function memberEnvironmentWithoutScope(dataHomes: readonly string[], env: NodeJS.ProcessEnv = process.env): Promise<MemberEnvironment> {
  ```
- `memberSettingRows` ← src/member-settings-report.ts:88 [EXTRACTED]
  ```
  export function memberSettingRows(reports: MemberSettingsReport[]): MemberSettingRow[] {
  ```
- `memberSettingLines` ← src/member-settings-report.ts:98 [EXTRACTED]
  ```
  export function memberSettingLines(reports: MemberSettingsReport[], scope: LocalConfig['scope']): string[] {
  ```
- `memberSettingsReport` ← src/member-settings-report.ts:238 [EXTRACTED]
  ```
  export async function memberSettingsReport(ctx: { localConfig: LocalConfig; teamConfig: TeamaiConfig | null }): Promise<MemberSettingsReport[]> {
  ```
- `machineUnreadKeys` ← src/member-settings-report.ts:456 [EXTRACTED]
  ```
  export async function machineUnreadKeys(): Promise<string[]> {
  ```
- `getMemberConfig` ← src/members.ts:13 [EXTRACTED]
  ```
  export async function getMemberConfig(repoPath: string, username: string): Promise<MemberConfig | null> {
  ```
- `memberReadRoots` ← src/members.ts:35 [EXTRACTED]
  ```
  export function memberReadRoots(primary: string, localConfig: LocalConfig): string[] {
  ```
- `readMemberConfig` ← src/members.ts:46 [EXTRACTED]
  ```
  export async function readMemberConfig(roots: string[], username: string): Promise<MemberConfig | null> {
  ```
- `mergeMemberConfig` ← src/members.ts:69 [EXTRACTED]
  ```
  export function mergeMemberConfig(
  ```
- `listMembers` ← src/members.ts:104 [EXTRACTED]
  ```
  export async function listMembers(options: GlobalOptions): Promise<void> {
  ```
- `planMigration` ← src/migrate.ts:201 [EXTRACTED]
  ```
  export async function planMigration(cwd?: string, options: { dryRun?: boolean } = {}): Promise<MigrationPlan | null> {
  ```
- `runMigration` ← src/migrate.ts:391 [EXTRACTED]
  ```
  export async function runMigration(
  ```
- `maybeMigrate` ← src/migrate.ts:578 [EXTRACTED]
  ```
  export async function maybeMigrate(opts: { dryRun?: boolean } = {}): Promise<MigrationResult | undefined> {
  ```
- `queueKeptInCheckout` ← src/migrate.ts:618 [EXTRACTED]
  ```
  export async function queueKeptInCheckout(
  ```
- `modelsList` ← src/models-cmd.ts:347 [EXTRACTED]
  ```
  export async function modelsList(reference?: string): Promise<void> {
  ```
- `modelsAdd` ← src/models-cmd.ts:458 [EXTRACTED]
  ```
  export async function modelsAdd(id: string, options: AddOptions): Promise<void> {
  ```
- `modelsConfigure` ← src/models-cmd.ts:501 [EXTRACTED]
  ```
  export async function modelsConfigure(reference: string, options: ConfigureOptions): Promise<void> {
  ```
- `modelsSwitch` ← src/models-cmd.ts:644 [EXTRACTED]
  ```
  export async function modelsSwitch(reference: string | undefined, options: SwitchOptions): Promise<void> {
  ```
- `modelsRestore` ← src/models-cmd.ts:690 [EXTRACTED]
  ```
  export async function modelsRestore(options: SwitchOptions): Promise<void> {
  ```
- `modelsRemove` ← src/models-cmd.ts:706 [EXTRACTED]
  ```
  export async function modelsRemove(reference: string): Promise<void> {
  ```
- `syncTeamModelProfiles` ← src/models-cmd.ts:741 [EXTRACTED]
  ```
  export async function syncTeamModelProfiles(localConfig: LocalConfig, options: { dryRun?: boolean } = {}): Promise<string | undefined> {
  ```
- `parseRemoteToRepo` ← src/mr-hint.ts:165 [EXTRACTED]
  ```
  export function parseRemoteToRepo(remoteUrl: string): RemoteRepo | null {
  ```
- `buildHintMessage` ← src/mr-hint.ts:402 [EXTRACTED]
  ```
  export function buildHintMessage(
  ```
- `computeMrHintOutput` ← src/mr-hint.ts:581 [EXTRACTED]
  ```
  export async function computeMrHintOutput(
  ```
- `stashMrHint` ← src/mr-hint.ts:603 [EXTRACTED]
  ```
  export async function stashMrHint(
  ```
- `takePendingMrHint` ← src/mr-hint.ts:620 [EXTRACTED]
  ```
  export async function takePendingMrHint(sessionId: string, localConfig?: LocalConfig | null): Promise<string | null> {
  ```
- `MrHintOffer` ← src/mr-hint.ts:703 [EXTRACTED]
  ```
  export const MrHintOffer = { proposals } as const;
  ```
- `mrHint` ← src/mr-hint.ts:710 [EXTRACTED]
  ```
  export async function mrHint(tool?: string): Promise<void> {
  ```
- `isActiveNamespace` ← src/namespace-resolver.ts:33 [EXTRACTED]
  ```
  export function isActiveNamespace(active: readonly string[], namespace: string): boolean {
  ```
- `activeNamespaceRank` ← src/namespace-resolver.ts:48 [EXTRACTED]
  ```
  export function activeNamespaceRank(active: readonly string[], namespace: string | null): number {
  ```
- `declaredDirectories` ← src/namespace-resolver.ts:74 [EXTRACTED]
  ```
  export function declaredDirectories(
  ```
- `itemCandidate` ← src/namespace-resolver.ts:131 [EXTRACTED]
  ```
  export function itemCandidate(item: ResourceItem): NamespaceCandidate<ResourceItem> {
  ```
- `resolveNamespacedItems` ← src/namespace-resolver.ts:146 [EXTRACTED]
  ```
  export function resolveNamespacedItems<T>(
  ```
- `firstConflict` ← src/namespace-resolver.ts:209 [EXTRACTED]
  ```
  export function firstConflict<T>(conflicts: readonly NamespaceConflict<T>[], active: readonly string[]): NamespaceConflict<T> | undefined {
  ```
- `resolveRootOverrides` ← src/namespace-resolver.ts:229 [EXTRACTED]
  ```
  export function resolveRootOverrides<T>(
  ```
- `describeOverride` ← src/namespace-resolver.ts:253 [EXTRACTED]
  ```
  export function describeOverride(type: string, override: NamespaceOverride): string {
  ```
- `repeatedNames` ← src/namespace-resolver.ts:258 [EXTRACTED]
  ```
  export function repeatedNames<T>(
  ```
- `entryLayout` ← src/namespaced-entries.ts:74 [EXTRACTED]
  ```
  export function entryLayout(type: EntryType): EntryLayout {
  ```
- `entryFilePath` ← src/namespaced-entries.ts:90 [EXTRACTED]
  ```
  export function entryFilePath(where: EntryType | EntryLayout, namespace: string | null): string {
  ```
- `entryFileAbsolutePath` ← src/namespaced-entries.ts:97 [EXTRACTED]
  ```
  export function entryFileAbsolutePath(repoPath: string, where: EntryType | EntryLayout, namespace: string | null): string {
  ```
- `listEntryFiles` ← src/namespaced-entries.ts:113 [EXTRACTED]
  ```
  export async function listEntryFiles(repoPath: string, where: EntryType | EntryLayout): Promise<EntryFile[]> {
  ```
- `writtenList` ← src/namespaced-entries.ts:158 [EXTRACTED]
  ```
  export function writtenList(document: JsonValue | undefined, listKey: string): JsonValue | undefined {
  ```
- `unknownEntryKeys` ← src/namespaced-entries.ts:168 [EXTRACTED]
  ```
  export function unknownEntryKeys<E>(
  ```
- `missingTopLevelKeyReason` ← src/namespaced-entries.ts:199 [EXTRACTED]
  ```
  export function missingTopLevelKeyReason(document: JsonValue | undefined, schema: z.ZodObject): string | null {
  ```
- `readEntryFileText` ← src/namespaced-entries.ts:217 [EXTRACTED]
  ```
  export async function readEntryFileText(
  ```
- `activeEntryNamespaces` ← src/namespaced-entries.ts:331 [EXTRACTED]
  ```
  export async function activeEntryNamespaces(
  ```
- `namespaceDir` ← src/namespaced-entries.ts:355 [EXTRACTED]
  ```
  export function namespaceDir(dirs: readonly string[], namespace: string): string {
  ```
- `resolveEntries` ← src/namespaced-entries.ts:365 [EXTRACTED]
  ```
  export async function resolveEntries<E>(
  ```
- `resolveWorkspaceEntries` ← src/namespaced-entries.ts:472 [EXTRACTED]
  ```
  export async function resolveWorkspaceEntries<E>(
  ```
- `resolveEntriesFor` ← src/namespaced-entries.ts:550 [EXTRACTED]
  ```
  export async function resolveEntriesFor<E>(
  ```
- `keepScopedEntry` ← src/namespaced-entries.ts:574 [EXTRACTED]
  ```
  export async function keepScopedEntry(
  ```
- `moveTo` ← src/namespaced-entries.ts:637 [EXTRACTED]
  ```
  export function moveTo(files: readonly string[]): string {
  ```
- `TargetFiles` ← src/namespaced-entries.ts:651 [EXTRACTED]
  ```
  export class TargetFiles {
  ```
- `describeEntryFailure` ← src/namespaced-entries.ts:714 [EXTRACTED]
  ```
  export function describeEntryFailure(failure: EntryFailure): string {
  ```
- `reportEntryResolution` ← src/namespaced-entries.ts:750 [EXTRACTED]
  ```
  export function reportEntryResolution(resolution: EntryResolution<unknown>): void {
  ```
- `reportUndeliveredEntryNotices` ← src/namespaced-entries.ts:761 [EXTRACTED]
  ```
  export function reportUndeliveredEntryNotices(resolution: Pick<EntryResolution<unknown>, 'notices'>): void {
  ```
- `describeOrigin` ← src/namespaced-entries.ts:772 [EXTRACTED]
  ```
  export function describeOrigin(entry: ResolvedEntry<unknown>): string {
  ```
- `describeOrigins` ← src/namespaced-entries.ts:779 [EXTRACTED]
  ```
  export function describeOrigins(entries: readonly ResolvedEntry<unknown>[]): string {
  ```
- `describeEntryNotes` ← src/namespaced-entries.ts:798 [EXTRACTED]
  ```
  export function describeEntryNotes(where: EntryType | EntryLayout, resolution: EntryResolution<unknown>): string[] {
  ```
- `entryNamespaceFromFlags` ← src/namespaced-entries.ts:829 [EXTRACTED]
  ```
  export async function entryNamespaceFromFlags(
  ```
- `OMP_HOOK_FILE` ← src/omp-hooks.ts:50 [EXTRACTED]
  ```
  export const OMP_HOOK_FILE = 'teamai-hooks.ts';
  ```
- `buildOmpExtensionSource` ← src/omp-hooks.ts:87 [EXTRACTED]
  ```
  export function buildOmpExtensionSource(): string {
  ```
- `teamaiHooks` ← src/omp-hooks.ts:179 [EXTRACTED]
  ```
  export default function teamaiHooks(pi) {
  ```
- `injectOmpHooks` ← src/omp-hooks.ts:314 [EXTRACTED]
  ```
  export async function injectOmpHooks(): Promise<void> {
  ```
- `removeOmpHooks` ← src/omp-hooks.ts:331 [EXTRACTED]
  ```
  export async function removeOmpHooks(dir = hookAdapterDir('omp-extension')): Promise<void> {
  ```
- `hasOmpHooks` ← src/omp-hooks.ts:342 [EXTRACTED]
  ```
  export async function hasOmpHooks(dir = hookAdapterDir('omp-extension')): Promise<boolean> {
  ```
- `resolveOpenclawStateDir` ← src/openclaw-home.ts:33 [EXTRACTED]
  ```
  export function resolveOpenclawStateDir(): string {
  ```
- `OPENCLAW_TEAM_HOOK_PLUGIN` ← src/openclaw-home.ts:38 [EXTRACTED]
  ```
  export const OPENCLAW_TEAM_HOOK_PLUGIN = 'teamai-team-hooks';
  ```
- `openclawTeamHookPluginIn` ← src/openclaw-home.ts:44 [EXTRACTED]
  ```
  export function openclawTeamHookPluginIn(stateDir: string, host: Host = realHost()): string {
  ```
- `resolveOpenclawConfigPath` ← src/openclaw-home.ts:49 [EXTRACTED]
  ```
  export function resolveOpenclawConfigPath(host: Host = realHost(), stateDir: string = resolveOpenclawStateDir()): string {
  ```
- `resolveOpenclawWorkspace` ← src/openclaw-home.ts:81 [EXTRACTED]
  ```
  export async function resolveOpenclawWorkspace(
  ```
- `openclawBootstrapBudget` ← src/openclaw-home.ts:108 [EXTRACTED]
  ```
  export async function openclawBootstrapBudget(): Promise<{ limit: number; config: string; error?: string }> {
  ```
- `resolveOpenClawHooksDir` ← src/openclaw-hooks.ts:51 [EXTRACTED]
  ```
  export function resolveOpenClawHooksDir(tool: string): string {
  ```
- `OPENCLAW_HOOK_DIR` ← src/openclaw-hooks.ts:58 [EXTRACTED]
  ```
  export const OPENCLAW_HOOK_DIR = 'teamai-status-report';
  ```
- `OPENCLAW_A2A_CONTROL_RECORD` ← src/openclaw-hooks.ts:64 [EXTRACTED]
  ```
  export const OPENCLAW_A2A_CONTROL_RECORD = 'openclaw-a2a-control.json';
  ```
- `OPENCLAW_HOOK_KEY` ← src/openclaw-hooks.ts:79 [EXTRACTED]
  ```
  export const OPENCLAW_HOOK_KEY = OPENCLAW_HOOK_DIR;
  ```
- `handler` ← src/openclaw-hooks.ts:138 [EXTRACTED]
  ```
  export default async function handler(event?: HookEvent): Promise<void> {
  ```
- `async` ← src/openclaw-hooks.ts:138 [INFERRED]
  ```
  export default async function handler(event?: HookEvent): Promise<void> {
  ```
- `injectOpenClawHooks` ← src/openclaw-hooks.ts:175 [EXTRACTED]
  ```
  export async function injectOpenClawHooks(tool = 'openclaw'): Promise<void> {
  ```
- `refreshOpenClawTeamHooks` ← src/openclaw-hooks.ts:211 [EXTRACTED]
  ```
  export async function refreshOpenClawTeamHooks(): Promise<void> {
  ```
- `rememberExistingOpenClawA2aControl` ← src/openclaw-hooks.ts:252 [EXTRACTED]
  ```
  export async function rememberExistingOpenClawA2aControl(): Promise<void> {
  ```
- `hasRecordedOpenClawA2aControl` ← src/openclaw-hooks.ts:275 [EXTRACTED]
  ```
  export function hasRecordedOpenClawA2aControl(): Promise<boolean> {
  ```
- `refreshOpenClawA2aControl` ← src/openclaw-hooks.ts:342 [EXTRACTED]
  ```
  export async function refreshOpenClawA2aControl(entry = resolveCliEntry()): Promise<void> {
  ```
- `removeOpenClawA2aControl` ← src/openclaw-hooks.ts:383 [EXTRACTED]
  ```
  export async function removeOpenClawA2aControl(): Promise<void> {
  ```
- `removeRecordedOpenClawA2aControls` ← src/openclaw-hooks.ts:391 [EXTRACTED]
  ```
  export async function removeRecordedOpenClawA2aControls(): Promise<string[]> {
  ```
- `removeOpenClawTeamHooks` ← src/openclaw-hooks.ts:542 [EXTRACTED]
  ```
  export async function removeOpenClawTeamHooks(): Promise<void> {
  ```
- `pluginsOf` ← src/openclaw-hooks.ts:596 [EXTRACTED]
  ```
  export function pluginsOf(config: ConfigObject): ConfigObject {
  ```
- `teamHookPluginBlocker` ← src/openclaw-hooks.ts:608 [EXTRACTED]
  ```
  export function teamHookPluginBlocker(plugins: ConfigObject, id = OPENCLAW_TEAM_HOOK_PLUGIN): string | null {
  ```
- `openclawHookEnabledIn` ← src/openclaw-hooks.ts:776 [EXTRACTED]
  ```
  export function openclawHookEnabledIn(config: ConfigObject): boolean {
  ```
- `removeOpenClawHookEntry` ← src/openclaw-hooks.ts:880 [EXTRACTED]
  ```
  export async function removeOpenClawHookEntry(hookKey: string = OPENCLAW_HOOK_KEY): Promise<void> {
  ```
- `removeOpenClawHooks` ← src/openclaw-hooks.ts:920 [EXTRACTED]
  ```
  export async function removeOpenClawHooks(hooksDir: string): Promise<void> {
  ```
- `removeOpenClawAgentHook` ← src/openclaw-hooks.ts:946 [EXTRACTED]
  ```
  export async function removeOpenClawAgentHook(opts: {
  ```
- `OPENCODE_PLUGIN_DIR` ← src/opencode-hooks.ts:39 [EXTRACTED]
  ```
  export const OPENCODE_PLUGIN_DIR = 'plugin';
  ```
- `OPENCODE_HOOK_FILE` ← src/opencode-hooks.ts:42 [EXTRACTED]
  ```
  export const OPENCODE_HOOK_FILE = 'teamai-hooks.ts';
  ```
- `OPENCODE_MCP_FILE` ← src/opencode-hooks.ts:48 [EXTRACTED]
  ```
  export const OPENCODE_MCP_FILE = 'teamai-mcp.json';
  ```
- `opencodeMcpFile` ← src/opencode-hooks.ts:51 [EXTRACTED]
  ```
  export function opencodeMcpFile(projectRoot: string): string {
  ```
- `resolveOpencodePluginDir` ← src/opencode-hooks.ts:65 [EXTRACTED]
  ```
  export function resolveOpencodePluginDir(baseDir: string, scope: 'project' | 'user'): string {
  ```
- `buildPluginSource` ← src/opencode-hooks.ts:92 [EXTRACTED]
  ```
  export function buildPluginSource(userConfigDir = toolHome('opencode'), entry = resolveCliEntry()): string {
  ```
- `injectOpencodeHooks` ← src/opencode-hooks.ts:480 [EXTRACTED]
  ```
  export async function injectOpencodeHooks(baseDir: string, scope: 'project' | 'user'): Promise<void> {
  ```
- `opencodeContextPlugin` ← src/opencode-hooks.ts:502 [EXTRACTED]
  ```
  export async function opencodeContextPlugin(): Promise<{ file: string; ready: boolean }> {
  ```
- `opencodeDeliversThroughPlugin` ← src/opencode-hooks.ts:519 [EXTRACTED]
  ```
  export async function opencodeDeliversThroughPlugin(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<boolean> {
  ```
- `removeOpencodeHooks` ← src/opencode-hooks.ts:528 [EXTRACTED]
  ```
  export async function removeOpencodeHooks(baseDir: string, scope: 'project' | 'user'): Promise<void> {
  ```
- `removeOpencodePlugin` ← src/opencode-hooks.ts:533 [EXTRACTED]
  ```
  export async function removeOpencodePlugin(pluginDir: string): Promise<void> {
  ```
- `removeOpencodeAgentHook` ← src/opencode-hooks.ts:555 [EXTRACTED]
  ```
  export async function removeOpencodeAgentHook(opts: {
  ```
- `opencodeMajorVersion` ← src/opencode-version.ts:16 [EXTRACTED]
  ```
  export function opencodeMajorVersion(binary = 'opencode'): Promise<number> {
  ```
- `WorkOutcomeSchema` ← src/outcomes.ts:12 [EXTRACTED]
  ```
  export const WorkOutcomeSchema = z.discriminatedUnion('kind', [
  ```
- `OUTCOME_MODES` ← src/outcomes.ts:23 [EXTRACTED]
  ```
  export const OUTCOME_MODES = [...RUN_MODES, 'notRecorded'] as const;
  ```
- `OUTCOME_ROWS` ← src/outcomes.ts:26 [EXTRACTED]
  ```
  export const OUTCOME_ROWS = ['pr', 'commit', 'learning', 'none'] as const satisfies ReadonlyArray<OutcomeKind | 'none'>;
  ```
- `addCounts` ← src/outcomes.ts:29 [EXTRACTED]
  ```
  export function addCounts(row: OutcomeCounts | undefined, added: OutcomeCounts): OutcomeCounts {
  ```
- `addOutcomeStats` ← src/outcomes.ts:38 [EXTRACTED]
  ```
  export function addOutcomeStats(existing: UserOutcomeStats | undefined, delta: UserOutcomeStats): UserOutcomeStats {
  ```
- `uniqueOutcomes` ← src/outcomes.ts:53 [EXTRACTED]
  ```
  export function uniqueOutcomes(outcomes: Iterable<WorkOutcome>): WorkOutcome[] {
  ```
- `outcomeValue` ← src/outcomes.ts:66 [EXTRACTED]
  ```
  export function outcomeValue(outcome: WorkOutcome): string {
  ```
- `learningIdOf` ← src/outcomes.ts:80 [EXTRACTED]
  ```
  export function learningIdOf(relPath: string): string {
  ```
- `SessionUsageSchema` ← src/outcomes.ts:85 [EXTRACTED]
  ```
  export const SessionUsageSchema = z.object({
  ```
- `SessionOutcomeEventSchema` ← src/outcomes.ts:97 [EXTRACTED]
  ```
  export const SessionOutcomeEventSchema = z.object({
  ```
- `packageRoot` ← src/package-info.ts:38 [EXTRACTED]
  ```
  export function packageRoot(): string {
  ```
- `getCurrentVersion` ← src/package-info.ts:54 [EXTRACTED]
  ```
  export function getCurrentVersion(): string {
  ```
- `getCurrentPackageName` ← src/package-info.ts:69 [EXTRACTED]
  ```
  export function getCurrentPackageName(): string {
  ```
- `PI_HOOK_FILE` ← src/pi-hooks.ts:33 [EXTRACTED]
  ```
  export const PI_HOOK_FILE = 'teamai-hooks.ts';
  ```
- `resolvePiProjectExtensionsDir` ← src/pi-hooks.ts:38 [EXTRACTED]
  ```
  export function resolvePiProjectExtensionsDir(baseDir: string): string {
  ```
- `buildPiExtensionSource` ← src/pi-hooks.ts:43 [EXTRACTED]
  ```
  export function buildPiExtensionSource(entry = resolveCliEntry()): string {
  ```
- `teamaiHooks` ← src/pi-hooks.ts:90 [EXTRACTED]
  ```
  export default function teamaiHooks(pi) {
  ```
- `injectPiHooks` ← src/pi-hooks.ts:268 [EXTRACTED]
  ```
  export async function injectPiHooks(): Promise<void> {
  ```
- `removePiHooks` ← src/pi-hooks.ts:286 [EXTRACTED]
  ```
  export async function removePiHooks(extensionsDir = hookAdapterDir('pi-extension')): Promise<void> {
  ```
- `removePiProjectHooks` ← src/pi-hooks.ts:295 [EXTRACTED]
  ```
  export async function removePiProjectHooks(baseDir: string): Promise<void> {
  ```
- `hasPiAgentHook` ← src/pi-hooks.ts:319 [EXTRACTED]
  ```
  export async function hasPiAgentHook(slug: string, dir?: string): Promise<boolean> {
  ```
- `removePiAgentHook` ← src/pi-hooks.ts:326 [EXTRACTED]
  ```
  export async function removePiAgentHook(slug: string): Promise<void> {
  ```
- `hasPiHooks` ← src/pi-hooks.ts:338 [EXTRACTED]
  ```
  export async function hasPiHooks(extensionsDir = hookAdapterDir('pi-extension')): Promise<boolean> {
  ```
- `parseProcessTable` ← src/pid-monitor.ts:40 [EXTRACTED]
  ```
  export function parseProcessTable(text: string): Map<number, ProcessEntry> {
  ```
- `getParentPid` ← src/pid-monitor.ts:137 [EXTRACTED]
  ```
  export function getParentPid(pid: number): number | undefined {
  ```
- `getProcessComm` ← src/pid-monitor.ts:168 [EXTRACTED]
  ```
  export function getProcessComm(pid: number): string | undefined {
  ```
- `walkToNonShell` ← src/pid-monitor.ts:191 [EXTRACTED]
  ```
  export function walkToNonShell(
  ```
- `resolveMonitorPid` ← src/pid-monitor.ts:226 [EXTRACTED]
  ```
  export function resolveMonitorPid(hookPpid: number): number {
  ```
- `isProcessAlive` ← src/pid-monitor.ts:237 [EXTRACTED]
  ```
  export function isProcessAlive(pid: number): boolean {
  ```
- `commandFingerprint` ← src/plugin-lifecycle.ts:95 [EXTRACTED]
  ```
  export function commandFingerprint(d: PluginDescriptor): string {
  ```
- `reconcilePlugins` ← src/plugin-lifecycle.ts:126 [EXTRACTED]
  ```
  export async function reconcilePlugins(
  ```
- `teardownAllPlugins` ← src/plugin-lifecycle.ts:231 [EXTRACTED]
  ```
  export async function teardownAllPlugins(deps: ReconcileDeps): Promise<void> {
  ```
- `parseGetConfig` ← src/plugin-lifecycle.ts:324 [EXTRACTED]
  ```
  export const parseGetConfig = GetConfigSchema.parse;
  ```
- `substituteVars` ← src/plugin-lifecycle.ts:327 [EXTRACTED]
  ```
  export function substituteVars(cmd: string, vars: Record<string, string>): string {
  ```
- `unresolvedPlaceholders` ← src/plugin-lifecycle.ts:334 [EXTRACTED]
  ```
  export function unresolvedPlaceholders(cmd: string): string[] {
  ```
- `COLD_PULL_WORST_CASE_MS` ← src/post-pull.ts:40 [EXTRACTED]
  ```
  export const COLD_PULL_WORST_CASE_MS = 25_000;
  ```
- `POST_PULL_BUDGET_SEC` ← src/post-pull.ts:48 [EXTRACTED]
  ```
  export const POST_PULL_BUDGET_SEC = 90;
  ```
- `runDeclaredPostPull` ← src/post-pull.ts:73 [EXTRACTED]
  ```
  export async function runDeclaredPostPull(
  ```
- `runPostPull` ← src/post-pull.ts:167 [EXTRACTED]
  ```
  export async function runPostPull(
  ```
- `createProjectToolRoots` ← src/project-agent-root.ts:57 [EXTRACTED]
  ```
  export async function createProjectToolRoots(options: {
  ```
- `seedInheritedCheckoutRoots` ← src/project-agent-root.ts:152 [EXTRACTED]
  ```
  export async function seedInheritedCheckoutRoots(cwd: string): Promise<'seeded' | 'not-needed' | 'source-missing'> {
  ```
- `seedProjectAgentRoot` ← src/project-agent-root.ts:170 [EXTRACTED]
  ```
  export async function seedProjectAgentRoot(tool: string, cwd?: string): Promise<void> {
  ```
- `projectsList` ← src/projects-cmd.ts:45 [EXTRACTED]
  ```
  export async function projectsList(_options: GlobalOptions): Promise<void> {
  ```
- `projectsSet` ← src/projects-cmd.ts:116 [EXTRACTED]
  ```
  export async function projectsSet(
  ```
- `projectsMembers` ← src/projects-cmd.ts:169 [EXTRACTED]
  ```
  export async function projectsMembers(
  ```
- `projectsAdd` ← src/projects-cmd.ts:342 [EXTRACTED]
  ```
  export async function projectsAdd(
  ```
- `projectsUpdate` ← src/projects-cmd.ts:380 [EXTRACTED]
  ```
  export async function projectsUpdate(
  ```
- `projectsRemove` ← src/projects-cmd.ts:442 [EXTRACTED]
  ```
  export async function projectsRemove(projectId: string, options: GlobalOptions): Promise<void> {
  ```
- `PROJECT_RESOURCE_TYPES` ← src/projects.ts:19 [EXTRACTED]
  ```
  export const PROJECT_RESOURCE_TYPES = ['knowledge', 'skills', 'learnings', 'agents'] as const;
  ```
- `ALL_PROJECT_RESOURCE_TYPES` ← src/projects.ts:24 [EXTRACTED]
  ```
  export const ALL_PROJECT_RESOURCE_TYPES = [...PROJECT_RESOURCE_TYPES, ...HAND_DECLARED_RESOURCE_TYPES] as const;
  ```
- `projectNamespaceEntries` ← src/projects.ts:131 [EXTRACTED]
  ```
  export function projectNamespaceEntries(manifest: ProjectsManifest): NamespaceEntry[] {
  ```
- `loadProjectsManifest` ← src/projects.ts:146 [EXTRACTED]
  ```
  export async function loadProjectsManifest(repoPath: string): Promise<ProjectsManifest | null> {
  ```
- `validateProjectsManifest` ← src/projects.ts:170 [EXTRACTED]
  ```
  export function validateProjectsManifest(manifest: ProjectsManifest): ProjectsManifest {
  ```
- `saveProjectsManifest` ← src/projects.ts:174 [EXTRACTED]
  ```
  export async function saveProjectsManifest(repoPath: string, manifest: ProjectsManifest): Promise<void> {
  ```
- `findProject` ← src/projects.ts:187 [EXTRACTED]
  ```
  export function findProject(manifest: ProjectsManifest, projectId: string): TeamProject | undefined {
  ```
- `listProjectIds` ← src/projects.ts:191 [EXTRACTED]
  ```
  export function listProjectIds(manifest: ProjectsManifest): string[] {
  ```
- `describeProjects` ← src/projects.ts:195 [EXTRACTED]
  ```
  export function describeProjects(projects: Array<Pick<TeamProject, 'id' | 'name' | 'description'>>): string[] {
  ```
- `unknownProjectMessage` ← src/projects.ts:204 [EXTRACTED]
  ```
  export function unknownProjectMessage(manifest: ProjectsManifest, projectId: string): string {
  ```
- `resolveProjectResourceNamespaces` ← src/projects.ts:228 [EXTRACTED]
  ```
  export function resolveProjectResourceNamespaces(input: {
  ```
- `resolveActiveLearningsNamespaces` ← src/projects.ts:271 [EXTRACTED]
  ```
  export async function resolveActiveLearningsNamespaces(
  ```
- `mergeNamespaces` ← src/projects.ts:338 [EXTRACTED]
  ```
  export function mergeNamespaces(
  ```
- `settleLateUsageReport` ← src/pull.ts:124 [EXTRACTED]
  ```
  export async function settleLateUsageReport(): Promise<void> {
  ```
- `cleanupInactiveNamespaceSkills` ← src/pull.ts:414 [EXTRACTED]
  ```
  export async function cleanupInactiveNamespaceSkills(
  ```
- `checkoutKey` ← src/pull.ts:1059 [EXTRACTED]
  ```
  export async function checkoutKey(projectRoot: string): Promise<string> {
  ```
- `liveCheckoutRecords` ← src/pull.ts:1085 [EXTRACTED]
  ```
  export async function liveCheckoutRecords(
  ```
- `projectCheckouts` ← src/pull.ts:1115 [EXTRACTED]
  ```
  export async function projectCheckouts(localConfig: LocalConfig): Promise<string[]> {
  ```
- `checkoutBaseRevs` ← src/pull.ts:1155 [EXTRACTED]
  ```
  export function checkoutBaseRevs(record: CheckoutRecord | undefined): string[] {
  ```
- `addPushBaseRev` ← src/pull.ts:1163 [EXTRACTED]
  ```
  export function addPushBaseRev(record: CheckoutRecord, rev: string): void {
  ```
- `checkoutRecordKey` ← src/pull.ts:1173 [EXTRACTED]
  ```
  export async function checkoutRecordKey(localConfig: LocalConfig): Promise<string | undefined> {
  ```
- `resolveCheckoutBases` ← src/pull.ts:1300 [EXTRACTED]
  ```
  export async function resolveCheckoutBases(
  ```
- `userScopeRecord` ← src/pull.ts:1332 [EXTRACTED]
  ```
  export async function userScopeRecord(state: State): Promise<CheckoutRecord> {
  ```
- `deliveringCheckoutRecord` ← src/pull.ts:1350 [EXTRACTED]
  ```
  export async function deliveringCheckoutRecord(localConfig: LocalConfig, state?: State): Promise<CheckoutRecord | undefined> {
  ```
- `teamDelivery` ← src/pull.ts:1400 [EXTRACTED]
  ```
  export async function teamDelivery(localConfig: LocalConfig, tool: string, options: { beforeOwnPull?: boolean } = {}): Promise<TeamDelivery> {
  ```
- `deliveredHashes` ← src/pull.ts:1433 [EXTRACTED]
  ```
  export async function deliveredHashes(localConfig: LocalConfig, state?: State): Promise<DeliveredHashes | undefined> {
  ```
- `recordedAgentModels` ← src/pull.ts:1443 [EXTRACTED]
  ```
  export async function recordedAgentModels(localConfig: LocalConfig, state?: State): Promise<AgentModelRecords> {
  ```
- `deliverySelection` ← src/pull.ts:1583 [EXTRACTED]
  ```
  export function deliverySelection(localConfig: LocalConfig): DeliverySelection {
  ```
- `editDeliveryRecord` ← src/pull.ts:1639 [EXTRACTED]
  ```
  export async function editDeliveryRecord(localConfig: LocalConfig): Promise<{ ledger: DeliveryLedger; save: () => Promise<void> }> {
  ```
- `compileCulture` ← src/pull.ts:3385 [EXTRACTED]
  ```
  export function compileCulture(raw: string): string | null {
  ```
- `compileClaudemd` ← src/pull.ts:3464 [EXTRACTED]
  ```
  export function compileClaudemd(contents: string[]): string | null {
  ```
- `resolveInstructionBlocks` ← src/pull.ts:3489 [EXTRACTED]
  ```
  export async function resolveInstructionBlocks(
  ```
- `compileDirectRecallRulesBlock` ← src/pull.ts:3655 [EXTRACTED]
  ```
  export async function compileDirectRecallRulesBlock(language?: 'en' | 'zh', repoPath?: string): Promise<string> {
  ```
- `compileRecallRulesBlock` ← src/pull.ts:3673 [EXTRACTED]
  ```
  export async function compileRecallRulesBlock(language?: 'en' | 'zh', repoPath?: string): Promise<string> {
  ```
- `pull` ← src/pull.ts:3777 [EXTRACTED]
  ```
  export async function pull(
  ```
- `syncDeliveredGitExclude` ← src/pull.ts:4471 [EXTRACTED]
  ```
  export async function syncDeliveredGitExclude(
  ```
- `liveDeliveredLists` ← src/pull.ts:4637 [EXTRACTED]
  ```
  export async function liveDeliveredLists(
  ```
- `isFilePush` ← src/push-file.ts:47 [EXTRACTED]
  ```
  export function isFilePush(options: PushFileOptions): boolean {
  ```
- `pushFile` ← src/push-file.ts:100 [EXTRACTED]
  ```
  export async function pushFile(options: GlobalOptions & PushFileOptions, result?: { completed: boolean }): Promise<void> {
  ```
- `isPlaceableType` ← src/push-namespaces.ts:59 [EXTRACTED]
  ```
  export function isPlaceableType(type: ResourceType | string): type is PlaceableType {
  ```
- `NAMESPACE_AXIS` ← src/push-namespaces.ts:69 [EXTRACTED]
  ```
  export const NAMESPACE_AXIS = {
  ```
- `isNestedPlaceableType` ← src/push-namespaces.ts:103 [EXTRACTED]
  ```
  export function isNestedPlaceableType(type: PlaceableType): boolean {
  ```
- `isAtSharedRoot` ← src/push-namespaces.ts:114 [EXTRACTED]
  ```
  export function isAtSharedRoot(item: ResourceItem): boolean {
  ```
- `declaredNamespaceFor` ← src/push-namespaces.ts:126 [EXTRACTED]
  ```
  export function declaredNamespaceFor(
  ```
- `withNamespace` ← src/push-namespaces.ts:146 [EXTRACTED]
  ```
  export function withNamespace(relativePath: string, namespace: string, rootSegments = 1): string {
  ```
- `rootSegmentsFor` ← src/push-namespaces.ts:153 [EXTRACTED]
  ```
  export function rootSegmentsFor(type: PlaceableType): number {
  ```
- `namespaceOfPlacedPath` ← src/push-namespaces.ts:162 [EXTRACTED]
  ```
  export function namespaceOfPlacedPath(type: PlaceableType, placedPath: string): string | undefined {
  ```
- `skillNamespacePath` ← src/push-namespaces.ts:173 [EXTRACTED]
  ```
  export function skillNamespacePath(namespace: string, name: string): string {
  ```
- `resolveRoleNamespace` ← src/push-namespaces.ts:194 [EXTRACTED]
  ```
  export function resolveRoleNamespace(
  ```
- `resolveProjectNamespace` ← src/push-namespaces.ts:234 [EXTRACTED]
  ```
  export function resolveProjectNamespace(
  ```
- `placedResourcePath` ← src/push-namespaces.ts:293 [EXTRACTED]
  ```
  export function placedResourcePath(
  ```
- `filterExistingTopLevelPaths` ← src/push.ts:66 [EXTRACTED]
  ```
  export async function filterExistingTopLevelPaths(
  ```
- `collectUnsafeDirtyPaths` ← src/push.ts:652 [EXTRACTED]
  ```
  export function collectUnsafeDirtyPaths(
  ```
- `explicitBranchRefusal` ← src/push.ts:1230 [EXTRACTED]
  ```
  export async function explicitBranchRefusal(
  ```
- `push` ← src/push.ts:1266 [EXTRACTED]
  ```
  export async function push(
  ```
- `readGateCheckName` ← src/read-gates.ts:41 [EXTRACTED]
  ```
  export function readGateCheckName(gate: ReadGate, noun: string): string {
  ```
- `readGateVerdict` ← src/read-gates.ts:75 [EXTRACTED]
  ```
  export async function readGateVerdict(gate: ReadGate, held: Held): Promise<ReadGateVerdict> {
  ```
- `assertNotReadOnly` ← src/read-only.ts:10 [EXTRACTED]
  ```
  export function assertNotReadOnly(localConfig: LocalConfig, op: string): void {
  ```
- `recordToolCall` ← src/recall-adoption.ts:141 [EXTRACTED]
  ```
  export async function recordToolCall(stdin: HookStdin, tool: string, config: LocalConfig): Promise<void> {
  ```
- `creditAdoptedDocs` ← src/recall-adoption.ts:346 [EXTRACTED]
  ```
  export async function creditAdoptedDocs(config: LocalConfig, sessionId: string): Promise<AdoptionResult> {
  ```
- `adoptionCandidates` ← src/recall-adoption.ts:537 [EXTRACTED]
  ```
  export async function adoptionCandidates(config: LocalConfig, sessionId: string): Promise<RecalledDoc[]> {
  ```
- `creditAdoptionVerdicts` ← src/recall-adoption.ts:556 [EXTRACTED]
  ```
  export async function creditAdoptionVerdicts(config: LocalConfig, sessionId: string, verdicts: readonly AdoptionVerdict[]): Promise<AdoptionVerdict[] | null> {
  ```
- `recalledDocsForSession` ← src/recall-adoption.ts:600 [EXTRACTED]
  ```
  export async function recalledDocsForSession(config: LocalConfig, sessionId: string): Promise<RecalledDoc[]> {
  ```
- `recallSessions` ← src/recall-adoption.ts:634 [EXTRACTED]
  ```
  export async function recallSessions(config: LocalConfig, limit: number): Promise<RecallSessionSummary[]> {
  ```
- `drainRecallLog` ← src/recall-adoption.ts:679 [EXTRACTED]
  ```
  export async function drainRecallLog(config: LocalConfig): Promise<void> {
  ```
- `recallLogPath` ← src/recall-log.ts:170 [EXTRACTED]
  ```
  export function recallLogPath(config: LocalConfig): string {
  ```
- `appendRecallLine` ← src/recall-log.ts:179 [EXTRACTED]
  ```
  export async function appendRecallLine(config: LocalConfig, line: RecallLogLine): Promise<void> {
  ```
- `appendRecallLines` ← src/recall-log.ts:184 [EXTRACTED]
  ```
  export async function appendRecallLines(config: LocalConfig, lines: RecallLogLine[]): Promise<void> {
  ```
- `readRecallLog` ← src/recall-log.ts:189 [EXTRACTED]
  ```
  export async function readRecallLog(config: LocalConfig): Promise<RecallLogLine[]> {
  ```
- `IndexProvenance` ← src/recall-provenance.ts:10 [EXTRACTED]
  ```
  export const IndexProvenance = z.object({
  ```
- `RecallObservation` ← src/recall-provenance.ts:18 [EXTRACTED]
  ```
  export const RecallObservation = z.object({
  ```
- `recordRecallIndexes` ← src/recall-provenance.ts:33 [EXTRACTED]
  ```
  export async function recordRecallIndexes(env: NodeJS.ProcessEnv, indexes: readonly SearchIndex[]): Promise<void> {
  ```
- `mergeRecallObservations` ← src/recall-provenance.ts:43 [EXTRACTED]
  ```
  export function mergeRecallObservations(observed: readonly RecallObservation[]): RecallObservation {
  ```
- `readRecallObservation` ← src/recall-provenance.ts:54 [EXTRACTED]
  ```
  export async function readRecallObservation(dir: string, attempt: string): Promise<RecallObservation> {
  ```
- `recordRecallQuality` ← src/recall-quality.ts:114 [EXTRACTED]
  ```
  export function recordRecallQuality(sessionId: string, results: SearchResult[], query?: string): void {
  ```
- `readRecallQuality` ← src/recall-quality.ts:151 [EXTRACTED]
  ```
  export function readRecallQuality(sessionId: string): { topScore: number; hitCount: number; missCount: number } | null {
  ```
- `removeRecallAgentAndRule` ← src/recall-toggle.ts:30 [EXTRACTED]
  ```
  export async function removeRecallAgentAndRule(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<number> {
  ```
- `recallDisable` ← src/recall-toggle.ts:146 [EXTRACTED]
  ```
  export async function recallDisable(opts: GlobalOptions): Promise<void> {
  ```
- `recallEnable` ← src/recall-toggle.ts:185 [EXTRACTED]
  ```
  export async function recallEnable(opts: GlobalOptions): Promise<void> {
  ```
- `recallStatus` ← src/recall-toggle.ts:203 [EXTRACTED]
  ```
  export async function recallStatus(_opts: GlobalOptions): Promise<void> {
  ```
- `LEARNINGS_RELEVANCE_RATIO` ← src/recall.ts:91 [EXTRACTED]
  ```
  export const LEARNINGS_RELEVANCE_RATIO = 1.35;
  ```
- `LEARNINGS_ABSOLUTE_FLOOR` ← src/recall.ts:105 [EXTRACTED]
  ```
  export const LEARNINGS_ABSOLUTE_FLOOR = 4.0;
  ```
- `isRelevantScore` ← src/recall.ts:125 [EXTRACTED]
  ```
  export function isRelevantScore(
  ```
- `computeIdfBaseline` ← src/recall.ts:154 [EXTRACTED]
  ```
  export function computeIdfBaseline(indexes: SearchIndex[], domain?: KnowledgeDomain): number {
  ```
- `normalizeLearningsScoreForRanking` ← src/recall.ts:190 [EXTRACTED]
  ```
  export function normalizeLearningsScoreForRanking(score: number, idfBaseline: number): number {
  ```
- `rankingScoreOf` ← src/recall.ts:239 [EXTRACTED]
  ```
  export function rankingScoreOf(result: RankableResult, idfBaseline: number): number {
  ```
- `collectCodePages` ← src/recall.ts:402 [EXTRACTED]
  ```
  export function collectCodePages(
  ```
- `buildRelationContext` ← src/recall.ts:476 [EXTRACTED]
  ```
  export async function buildRelationContext(args: {
  ```
- `resolveRelationTarget` ← src/recall.ts:541 [EXTRACTED]
  ```
  export function resolveRelationTarget(ctx: RelationContext, target: string): string | null {
  ```
- `relationLines` ← src/recall.ts:630 [EXTRACTED]
  ```
  export function relationLines(
  ```
- `relatedRefsOf` ← src/recall.ts:673 [EXTRACTED]
  ```
  export function relatedRefsOf(
  ```
- `computeDerivedRelations` ← src/recall.ts:701 [EXTRACTED]
  ```
  export function computeDerivedRelations(
  ```
- `formatResults` ← src/recall.ts:741 [EXTRACTED]
  ```
  export function formatResults(
  ```
- `autoUpvote` ← src/recall.ts:840 [EXTRACTED]
  ```
  export async function autoUpvote(
  ```
- `recall` ← src/recall.ts:1094 [EXTRACTED]
  ```
  export async function recall(
  ```
- `remove` ← src/remove.ts:16 [EXTRACTED]
  ```
  export async function remove(
  ```
- `usesMemberFilters` ← src/resource-namespaces.ts:46 [EXTRACTED]
  ```
  export function usesMemberFilters(config: Pick<LocalConfig, 'stepRole'>): boolean {
  ```
- `withStepRoleKnowledge` ← src/resource-namespaces.ts:54 [EXTRACTED]
  ```
  export function withStepRoleKnowledge(manifest: RolesManifest | null, stepRole: string, member: ResourceNamespaces): ResourceNamespaces {
  ```
- `workflowNamespacesOf` ← src/resource-namespaces.ts:111 [EXTRACTED]
  ```
  export async function workflowNamespacesOf(config: LocalConfig): Promise<readonly string[] | 'legacy'> {
  ```
- `resolveResourceNamespaces` ← src/resource-namespaces.ts:127 [EXTRACTED]
  ```
  export async function resolveResourceNamespaces(localConfig: LocalConfig): Promise<ResolvedResourceNamespaces | null> {
  ```
- `isNamespaceDir` ← src/resource-namespaces.ts:391 [EXTRACTED]
  ```
  export function isNamespaceDir(type: PlaceableType, dir: string, declarations: NamespaceDeclarations): boolean {
  ```
- `deliversEveryNamespace` ← src/resource-namespaces.ts:407 [EXTRACTED]
  ```
  export async function deliversEveryNamespace(localConfig: LocalConfig): Promise<boolean> {
  ```
- `RESOURCE_RELATIONS` ← src/resource-relations.ts:25 [EXTRACTED]
  ```
  export const RESOURCE_RELATIONS = ['MAPS_TO', 'REFERENCES', 'SUPERSEDES', 'CONFLICTS_WITH'] as const;
  ```
- `classifyTreePath` ← src/resource-relations.ts:95 [EXTRACTED]
  ```
  export function classifyTreePath(treePath: string): RelationResourceKind | null {
  ```
- `normalizeTargetPath` ← src/resource-relations.ts:112 [EXTRACTED]
  ```
  export function normalizeTargetPath(raw: string): string | null {
  ```
- `teamwikiCodebaseSlug` ← src/resource-relations.ts:133 [EXTRACTED]
  ```
  export function teamwikiCodebaseSlug(treePath: string): string | null {
  ```
- `parseRelatedBlock` ← src/resource-relations.ts:155 [EXTRACTED]
  ```
  export function parseRelatedBlock(
  ```
- `relationsFromLinks` ← src/resource-relations.ts:259 [EXTRACTED]
  ```
  export function relationsFromLinks(
  ```
- `reviewBranchDir` ← src/review-branch.ts:1785 [EXTRACTED]
  ```
  export async function reviewBranchDir(branch: string, repoDir: string, base: ReviewBase | null = null): Promise<BranchReview> {
  ```
- `resolveBranchRef` ← src/review-branch.ts:1846 [EXTRACTED]
  ```
  export async function resolveBranchRef(repoPath: string, branch: string): Promise<string | null> {
  ```
- `materializeRef` ← src/review-branch.ts:1868 [EXTRACTED]
  ```
  export async function materializeRef(repoPath: string, ref: string, destDir: string): Promise<number> {
  ```
- `reviewBranchCmd` ← src/review-branch.ts:1945 [EXTRACTED]
  ```
  export async function reviewBranchCmd(options: ReviewBranchOptions): Promise<void> {
  ```
- `reviewCmd` ← src/review-cmd.ts:192 [EXTRACTED]
  ```
  export async function reviewCmd(opts: ReviewCmdOptions): Promise<void> {
  ```
- `PENDING_REVIEW_PATH` ← src/review-store.ts:51 [EXTRACTED]
  ```
  export const PENDING_REVIEW_PATH = '.teamai/pending-review.jsonl';
  ```
- `getPendingReviewPath` ← src/review-store.ts:68 [EXTRACTED]
  ```
  export function getPendingReviewPath(cwd: string): string {
  ```
- `computeReviewId` ← src/review-store.ts:75 [EXTRACTED]
  ```
  export function computeReviewId(
  ```
- `inferRisk` ← src/review-store.ts:92 [EXTRACTED]
  ```
  export function inferRisk(target: { file: string; section?: string }): Risk {
  ```
- `loadPendingReview` ← src/review-store.ts:173 [EXTRACTED]
  ```
  export async function loadPendingReview(cwd: string): Promise<PendingReviewItem[]> {
  ```
- `savePendingReview` ← src/review-store.ts:234 [EXTRACTED]
  ```
  export async function savePendingReview(cwd: string, items: PendingReviewItem[]): Promise<void> {
  ```
- `appendPendingReview` ← src/review-store.ts:245 [EXTRACTED]
  ```
  export async function appendPendingReview(
  ```
- `decidePendingReview` ← src/review-store.ts:274 [EXTRACTED]
  ```
  export async function decidePendingReview(
  ```
- `removePendingReview` ← src/review-store.ts:293 [EXTRACTED]
  ```
  export async function removePendingReview(cwd: string, id: string): Promise<boolean> {
  ```
- `ROLE_ASSIGNMENTS_FILE` ← src/role-assignments.ts:13 [EXTRACTED]
  ```
  export const ROLE_ASSIGNMENTS_FILE = 'manifest/members.yaml';
  ```
- `RoleAssignmentsNotFoundError` ← src/role-assignments.ts:55 [EXTRACTED]
  ```
  export class RoleAssignmentsNotFoundError extends Error {
  ```
- `loadRoleAssignments` ← src/role-assignments.ts:164 [EXTRACTED]
  ```
  export async function loadRoleAssignments(repoPath: string, repo: { kind?: string } = {}): Promise<RoleAssignments> {
  ```
- `loadRoleAssignmentsIfPresent` ← src/role-assignments.ts:201 [EXTRACTED]
  ```
  export async function loadRoleAssignmentsIfPresent(repoPath: string, repo: { kind?: string } = {}): Promise<RoleAssignments | null> {
  ```
- `resolveAssignedRoles` ← src/role-assignments.ts:223 [EXTRACTED]
  ```
  export function resolveAssignedRoles(
  ```
- `rolesInit` ← src/roles-cmd.ts:26 [EXTRACTED]
  ```
  export async function rolesInit(options: GlobalOptions): Promise<void> {
  ```
- `effectiveRoles` ← src/roles-cmd.ts:180 [EXTRACTED]
  ```
  export function effectiveRoles(localConfig: LocalConfig): EffectiveRoles {
  ```
- `assignedRolesNotice` ← src/roles-cmd.ts:197 [EXTRACTED]
  ```
  export function assignedRolesNotice(effective: ReturnType<typeof effectiveRoles>): string {
  ```
- `rolesList` ← src/roles-cmd.ts:203 [EXTRACTED]
  ```
  export async function rolesList(options: { json?: boolean } = {}): Promise<void> {
  ```
- `rolesSet` ← src/roles-cmd.ts:267 [EXTRACTED]
  ```
  export async function rolesSet(
  ```
- `rolesAdd` ← src/roles-cmd.ts:346 [EXTRACTED]
  ```
  export async function rolesAdd(
  ```
- `rolesRemove` ← src/roles-cmd.ts:419 [EXTRACTED]
  ```
  export async function rolesRemove(
  ```
- `rolesUpdate` ← src/roles-cmd.ts:482 [EXTRACTED]
  ```
  export async function rolesUpdate(
  ```
- `RoleIdSchema` ← src/roles.ts:54 [EXTRACTED]
  ```
  export const RoleIdSchema = z.string().regex(ROLE_ID, 'must be the id of a role in manifest/roles.yaml, such as review');
  ```
- `isRoleId` ← src/roles.ts:57 [EXTRACTED]
  ```
  export function isRoleId(value: string): boolean {
  ```
- `NAMESPACED_RESOURCE_TYPES` ← src/roles.ts:72 [EXTRACTED]
  ```
  export const NAMESPACED_RESOURCE_TYPES = [...ROLE_RESOURCE_TYPES, ...HAND_DECLARED_RESOURCE_TYPES] as const;
  ```
- `roleNamespaceEntries` ← src/roles.ts:123 [EXTRACTED]
  ```
  export function roleNamespaceEntries(manifest: RolesManifest): NamespaceEntry[] {
  ```
- `RolesManifestNotFoundError` ← src/roles.ts:138 [EXTRACTED]
  ```
  export class RolesManifestNotFoundError extends Error {
  ```
- `loadRolesManifest` ← src/roles.ts:145 [EXTRACTED]
  ```
  export async function loadRolesManifest(repoPath: string): Promise<RolesManifest> {
  ```
- `loadRolesManifestIfPresent` ← src/roles.ts:177 [EXTRACTED]
  ```
  export async function loadRolesManifestIfPresent(repoPath: string): Promise<RolesManifest | null> {
  ```
- `roleDeclaration` ← src/roles.ts:200 [EXTRACTED]
  ```
  export async function roleDeclaration(repoPath: string, role?: string): Promise<RoleDeclaration> {
  ```
- `saveRolesManifest` ← src/roles.ts:218 [EXTRACTED]
  ```
  export async function saveRolesManifest(repoPath: string, manifest: RolesManifest): Promise<void> {
  ```
- `findRole` ← src/roles.ts:231 [EXTRACTED]
  ```
  export function findRole(manifest: RolesManifest, roleId: string): TeamRole | undefined {
  ```
- `listRoleIds` ← src/roles.ts:235 [EXTRACTED]
  ```
  export function listRoleIds(manifest: RolesManifest): string[] {
  ```
- `describeRoles` ← src/roles.ts:239 [EXTRACTED]
  ```
  export function describeRoles(roles: Array<Pick<TeamRole, 'id' | 'description'>>): string[] {
  ```
- `resolveRoleResourceNamespaces` ← src/roles.ts:255 [EXTRACTED]
  ```
  export function resolveRoleResourceNamespaces(input: {
  ```
- `activeRoleIds` ← src/roles.ts:299 [EXTRACTED]
  ```
  export function activeRoleIds(
  ```
- `saveSession` ← src/save-session.ts:55 [EXTRACTED]
  ```
  export async function saveSession(options: SaveSessionOptions): Promise<void> {
  ```
- `saveScopeSelection` ← src/scope-selection.ts:15 [EXTRACTED]
  ```
  export async function saveScopeSelection(localConfig: LocalConfig, updatedConfig: LocalConfig): Promise<void> {
  ```
- `scoreCommand` ← src/score-commands.ts:252 [EXTRACTED]
  ```
  export async function scoreCommand(options: ScoreOptions): Promise<void> {
  ```
- `Drain` ← src/score-drain.ts:551 [EXTRACTED]
  ```
  export const Drain = { run, print, hasFailed, drainsUnattendedRun } as const;
  ```
- `ScoreVerbs` ← src/score-verbs.ts:271 [EXTRACTED]
  ```
  export const ScoreVerbs = { plan, evidence, stage, label, write, publish, settle, subjects, report } as const;
  ```
- `scoreVerbCommand` ← src/score-verbs.ts:292 [EXTRACTED]
  ```
  export async function scoreVerbCommand(verb: (ctx: ScoreVerbContext) => Promise<ScoreVerbAnswer>): Promise<void> {
  ```
- `scriptRun` ← src/script-commands.ts:14 [EXTRACTED]
  ```
  export async function scriptRun(eventName: string): Promise<void> {
  ```
- `storedEntryKind` ← src/secret-store.ts:39 [EXTRACTED]
  ```
  export function storedEntryKind(entry: StoredSecret): StoredEntryKind {
  ```
- `getTeamSecretsPath` ← src/secret-store.ts:63 [EXTRACTED]
  ```
  export function getTeamSecretsPath(localConfig: LocalConfig): string {
  ```
- `getMachineSecretsPath` ← src/secret-store.ts:145 [EXTRACTED]
  ```
  export function getMachineSecretsPath(): string {
  ```
- `readSecretStore` ← src/secret-store.ts:155 [EXTRACTED]
  ```
  export async function readSecretStore(filePath: string): Promise<SecretStoreRead> {
  ```
- `writeSecretStore` ← src/secret-store.ts:196 [EXTRACTED]
  ```
  export async function writeSecretStore(filePath: string, values: SecretStore): Promise<void> {
  ```
- `updateSecretStore` ← src/secret-store.ts:211 [EXTRACTED]
  ```
  export async function updateSecretStore(
  ```
- `storedSecretValue` ← src/secret-store.ts:247 [EXTRACTED]
  ```
  export function storedSecretValue(entry: StoredSecret, env: NodeJS.ProcessEnv = process.env): string | undefined {
  ```
- `hashBody` ← src/section-patcher.ts:64 [EXTRACTED]
  ```
  export function hashBody(body: string): string {
  ```
- `splitToSections` ← src/section-patcher.ts:86 [EXTRACTED]
  ```
  export function splitToSections(md: string): SectionedMarkdown {
  ```
- `joinSections` ← src/section-patcher.ts:153 [EXTRACTED]
  ```
  export function joinSections(prelude: string, sections: ManagedSection[]): string {
  ```
- `parseSections` ← src/section-patcher.ts:190 [EXTRACTED]
  ```
  export function parseSections(md: string): SectionedMarkdown {
  ```
- `patchManagedSection` ← src/section-patcher.ts:297 [EXTRACTED]
  ```
  export function patchManagedSection(
  ```
- `mergeWithAnchors` ← src/section-patcher.ts:374 [EXTRACTED]
  ```
  export function mergeWithAnchors(
  ```
- `SelfImprovement` ← src/self-improvement.ts:242 [EXTRACTED]
  ```
  export const SelfImprovement = { WORKFLOW, SUITE, BRANCH_PREFIX, TASK_FILE, holdsProposal, pick, wouldImprove, commandOf, branchOf, commitsIn, coveringTasks, plan } as const;
  ```
- `attributeByRepo` ← src/session-analytics.ts:32 [EXTRACTED]
  ```
  export function attributeByRepo(events: DashboardEvent[]): RepoStat[] {
  ```
- `timeAnalytics` ← src/session-analytics.ts:92 [EXTRACTED]
  ```
  export function timeAnalytics(events: DashboardEvent[]): TimeAnalytics {
  ```
- `renderHourSparkline` ← src/session-analytics.ts:152 [EXTRACTED]
  ```
  export function renderHourSparkline(byHour: number[]): string {
  ```
- `isValuable` ← src/session-collector.ts:75 [EXTRACTED]
  ```
  export function isValuable(summary: Pick<SessionSummary, 'interventionCount' | 'distinctTools'>): boolean {
  ```
- `collectSession` ← src/session-collector.ts:83 [EXTRACTED]
  ```
  export function collectSession(sessionId: string, events: DashboardEvent[]): SessionSummary | null {
  ```
- `renderSessionMarkdown` ← src/session-collector.ts:175 [EXTRACTED]
  ```
  export function renderSessionMarkdown(summary: SessionSummary, options: RenderOptions = {}): string {
  ```
- `monthKey` ← src/session-collector.ts:208 [EXTRACTED]
  ```
  export function monthKey(summary: SessionSummary): string {
  ```
- `appendMonthlyLog` ← src/session-collector.ts:220 [EXTRACTED]
  ```
  export async function appendMonthlyLog(
  ```
- `pruneMonthlyLogs` ← src/session-collector.ts:268 [EXTRACTED]
  ```
  export async function pruneMonthlyLogs(
  ```
- `SessionOutcomes` ← src/session-outcomes.ts:426 [EXTRACTED]
  ```
  export const SessionOutcomes = { fold, markReported, summarize } as const;
  ```
- `REPORTED_SNAPSHOTS` ← src/session-owners.ts:36 [EXTRACTED]
  ```
  export const REPORTED_SNAPSHOTS = ['interventions', 'prompt-tokens', 'daily-sessions'] as const;
  ```
- `sharedSnapshotPath` ← src/session-owners.ts:41 [EXTRACTED]
  ```
  export function sharedSnapshotPath(name: ReportedSnapshotName): string {
  ```
- `snapshotPathIn` ← src/session-owners.ts:46 [EXTRACTED]
  ```
  export function snapshotPathIn(dataHome: string, name: ReportedSnapshotName | 'outcomes'): string {
  ```
- `reportedSize` ← src/session-owners.ts:107 [EXTRACTED]
  ```
  export const reportedSize = ReportedSizeSchema.parse;
  ```
- `readSnapshotsIn` ← src/session-owners.ts:122 [EXTRACTED]
  ```
  export async function readSnapshotsIn(dataHome: string | undefined): Promise<ScopeSnapshots> {
  ```
- `interventionsEntry` ← src/session-owners.ts:139 [EXTRACTED]
  ```
  export const interventionsEntry = InterventionsEntrySchema.parse;
  ```
- `promptTokensEntry` ← src/session-owners.ts:156 [EXTRACTED]
  ```
  export const promptTokensEntry = PromptTokensEntrySchema.parse;
  ```
- `showsReported` ← src/session-owners.ts:175 [EXTRACTED]
  ```
  export function showsReported(own: ScopeSnapshots, shared: ScopeSnapshots, id: string): boolean {
  ```
- `readOwnerCredits` ← src/session-owners.ts:331 [EXTRACTED]
  ```
  export async function readOwnerCredits(): Promise<Map<string, OwnerCredit>> {
  ```
- `readSessionOwners` ← src/session-owners.ts:372 [EXTRACTED]
  ```
  export async function readSessionOwners(options: { dryRun?: boolean; suppressMigrationNotice?: boolean } = {}): Promise<Map<string, string>> {
  ```
- `readSessionOwnerState` ← src/session-owners.ts:382 [EXTRACTED]
  ```
  export async function readSessionOwnerState(options: { dryRun?: boolean; suppressMigrationNotice?: boolean } = {}): Promise<SessionOwnerState> {
  ```
- `reportedBeyondShared` ← src/session-owners.ts:424 [EXTRACTED]
  ```
  export async function reportedBeyondShared(
  ```
- `recordSessionOwners` ← src/session-owners.ts:437 [EXTRACTED]
  ```
  export async function recordSessionOwners(sessionIds: Iterable<string>, key: string): Promise<void> {
  ```
- `creditedPrompts` ← src/session-owners.ts:461 [EXTRACTED]
  ```
  export async function creditedPrompts(credit: OwnerCredit, transcripts: string[]): Promise<number | undefined> {
  ```
- `SessionShare` ← src/session-share.ts:189 [EXTRACTED]
  ```
  export const SessionShare = { offer, reminderOffer, proposals } as const;
  ```
- `SessionToTask` ← src/session-to-task.ts:169 [EXTRACTED]
  ```
  export const SessionToTask = { proposals } as const;
  ```
- `aggregateDailySessions` ← src/session-trends.ts:63 [EXTRACTED]
  ```
  export function aggregateDailySessions(events: DashboardEvent[]): Map<string, DailySessionSnapshot> {
  ```
- `SnapshotCountSchema` ← src/session-trends.ts:120 [EXTRACTED]
  ```
  export const SnapshotCountSchema = z.number().catch(0);
  ```
- `parseRequestDaily` ← src/session-trends.ts:137 [EXTRACTED]
  ```
  export const parseRequestDaily = RequestDailySchema.parse;
  ```
- `addRequestDaily` ← src/session-trends.ts:140 [EXTRACTED]
  ```
  export function addRequestDaily(
  ```
- `parseDailySnapshot` ← src/session-trends.ts:197 [EXTRACTED]
  ```
  export const parseDailySnapshot = DailySnapshotEntrySchema.optional().catch(undefined).parse;
  ```
- `takeDailySession` ← src/session-trends.ts:248 [EXTRACTED]
  ```
  export function takeDailySession(
  ```
- `computeDailyStatsDelta` ← src/session-trends.ts:306 [EXTRACTED]
  ```
  export function computeDailyStatsDelta(
  ```
- `mergeDailyStats` ← src/session-trends.ts:357 [EXTRACTED]
  ```
  export function mergeDailyStats(
  ```
- `summarizeTrendWindow` ← src/session-trends.ts:422 [EXTRACTED]
  ```
  export function summarizeTrendWindow(
  ```
- `summarizeSessionCosts` ← src/session-trends.ts:458 [EXTRACTED]
  ```
  export function summarizeSessionCosts(sessions: Map<string, DailySessionSnapshot>, now = new Date()): SessionCostWindow {
  ```
- `SHARED_INSTRUCTION_SOURCE_DIRS` ← src/shared-instruction-source.ts:17 [EXTRACTED]
  ```
  export const SHARED_INSTRUCTION_SOURCE_DIRS = ['claudemd', 'agentsmd'] as const;
  ```
- `existingSharedInstructionDirs` ← src/shared-instruction-source.ts:38 [EXTRACTED]
  ```
  export async function existingSharedInstructionDirs(repoPath: string): Promise<SharedInstructionSourceDir[]> {
  ```
- `shadowedSharedInstructionFiles` ← src/shared-instruction-source.ts:77 [EXTRACTED]
  ```
  export async function shadowedSharedInstructionFiles(
  ```
- `skillShow` ← src/skill-cmd.ts:52 [EXTRACTED]
  ```
  export async function skillShow(name: string, options: GlobalOptions): Promise<void> {
  ```
- `skillList` ← src/skill-cmd.ts:165 [EXTRACTED]
  ```
  export async function skillList(options: GlobalOptions & { json?: boolean }): Promise<void> {
  ```
- `installSkillZip` ← src/skill-command.ts:172 [EXTRACTED]
  ```
  export async function installSkillZip(
  ```
- `executeSkillCommand` ← src/skill-command.ts:248 [EXTRACTED]
  ```
  export async function executeSkillCommand(cmd: SkillCommand, targetSkillsDir: string): Promise<void> {
  ```
- `SKILL_DIR_PLACEHOLDER` ← src/skill-content.ts:30 [EXTRACTED]
  ```
  export const SKILL_DIR_PLACEHOLDER = '{SKILL_DIR}';
  ```
- `detectTeam` ← src/skill-content.ts:101 [EXTRACTED]
  ```
  export async function detectTeam(cwd?: string, options: { dryRun?: boolean } = {}): Promise<TeamDetection> {
  ```
- `shareGate` ← src/skill-content.ts:153 [EXTRACTED]
  ```
  export async function shareGate(cwd?: string, options: { dryRun?: boolean } = {}): Promise<ShareGate> {
  ```
- `shareBlock` ← src/skill-content.ts:171 [EXTRACTED]
  ```
  export async function shareBlock({ localConfig, teamConfig }: TeamaiInit): Promise<SkillBlock | null> {
  ```
- `firstLine` ← src/skill-content.ts:184 [EXTRACTED]
  ```
  export function firstLine(text: string): string {
  ```
- `contributeHintAllowed` ← src/skill-content.ts:201 [EXTRACTED]
  ```
  export async function contributeHintAllowed(cwd?: string): Promise<boolean> {
  ```
- `packagedSkillRoots` ← src/skill-content.ts:248 [EXTRACTED]
  ```
  export function packagedSkillRoots(): PackagedSkillRoots {
  ```
- `listServableSkills` ← src/skill-content.ts:281 [EXTRACTED]
  ```
  export async function listServableSkills(roots: PackagedSkillRoots = packagedSkillRoots()): Promise<PackagedSkill[]> {
  ```
- `resolveServableSkill` ← src/skill-content.ts:332 [EXTRACTED]
  ```
  export async function resolveServableSkill(
  ```
- `blockNote` ← src/skill-content.ts:359 [EXTRACTED]
  ```
  export function blockNote(reason: SkillBlockReason, env: NodeJS.ProcessEnv = process.env): string {
  ```
- `blockMessage` ← src/skill-content.ts:377 [EXTRACTED]
  ```
  export function blockMessage(
  ```
- `renderSkill` ← src/skill-content.ts:444 [EXTRACTED]
  ```
  export async function renderSkill(skill: PackagedSkill, options: { full?: boolean } = {}): Promise<string> {
  ```
- `refuseBlocked` ← src/skill-content.ts:483 [EXTRACTED]
  ```
  export function refuseBlocked(blocked: BlockedSkill): void {
  ```
- `skillGet` ← src/skill-content.ts:499 [EXTRACTED]
  ```
  export async function skillGet(names: string[], options: SkillGetOptions = {}): Promise<void> {
  ```
- `skillPath` ← src/skill-content.ts:588 [EXTRACTED]
  ```
  export async function skillPath(name: string): Promise<void> {
  ```
- `skillCatalog` ← src/skill-content.ts:634 [EXTRACTED]
  ```
  export async function skillCatalog(
  ```
- `findSkillDirectoryBlock` ← src/skill-directory.ts:21 [EXTRACTED]
  ```
  export async function findSkillDirectoryBlock(
  ```
- `allowsSkillDirectory` ← src/skill-directory.ts:62 [EXTRACTED]
  ```
  export async function allowsSkillDirectory(baseDir: string, target: string, options: { keepSkillLink?: boolean } = {}): Promise<boolean> {
  ```
- `describeSkippedSkillDirectory` ← src/skill-directory.ts:67 [EXTRACTED]
  ```
  export function describeSkippedSkillDirectory(skillName: string, tool: string, block: SkillDirectoryBlock): string {
  ```
- `describeSkillDirectoryBlock` ← src/skill-directory.ts:79 [EXTRACTED]
  ```
  export function describeSkillDirectoryBlock(block: SkillDirectoryBlock): string {
  ```
- `calculateSkillHealth` ← src/skill-health.ts:21 [EXTRACTED]
  ```
  export function calculateSkillHealth(
  ```
- `scoreToStars` ← src/skill-health.ts:41 [EXTRACTED]
  ```
  export function scoreToStars(score: number): string {
  ```
- `calculateTeamHealth` ← src/skill-health.ts:50 [EXTRACTED]
  ```
  export function calculateTeamHealth(
  ```
- `packagedSkillDigest` ← src/skill-owned-files.ts:23 [EXTRACTED]
  ```
  export function packagedSkillDigest(content: Buffer): string {
  ```
- `ownedSkillFiles` ← src/skill-owned-files.ts:35 [EXTRACTED]
  ```
  export async function ownedSkillFiles(skillName: string, paths?: readonly string[]): Promise<OwnedSkillFiles> {
  ```
- `isOwnedFile` ← src/skill-owned-files.ts:56 [EXTRACTED]
  ```
  export async function isOwnedFile(file: string, relative: string, owned: OwnedSkillFiles, generatedStub?: string): Promise<boolean> {
  ```
- `walkFiles` ← src/skill-owned-files.ts:94 [EXTRACTED]
  ```
  export async function walkFiles(dir: string, prefix = ''): Promise<string[]> {
  ```
- `prunedWhole` ← src/skill-owned-files.ts:166 [EXTRACTED]
  ```
  export function prunedWhole(result: PruneResult): boolean {
  ```
- `removeOwnedFiles` ← src/skill-owned-files.ts:183 [EXTRACTED]
  ```
  export async function removeOwnedFiles(
  ```
- `skillsGuardBase` ← src/skill-owned-files.ts:291 [EXTRACTED]
  ```
  export async function skillsGuardBase(scopeRoot: string, skillsDir: string): Promise<string> {
  ```
- `getRecommendations` ← src/skill-recommend.ts:50 [EXTRACTED]
  ```
  export async function getRecommendations(
  ```
- `displayRecommendations` ← src/skill-recommend.ts:83 [EXTRACTED]
  ```
  export function displayRecommendations(
  ```
- `typedIn` ← src/skill-use.ts:223 [EXTRACTED]
  ```
  export function typedIn(message: Message, block: ContentBlock): string {
  ```
- `skillCandidates` ← src/skill-use.ts:331 [EXTRACTED]
  ```
  export function skillCandidates(event: HookEvent, tool: string): SkillCandidate[] {
  ```
- `DeliveredSkillInfoSchema` ← src/skill-use.ts:342 [EXTRACTED]
  ```
  export const DeliveredSkillInfoSchema = z.object({
  ```
- `deliveredTeamSkills` ← src/skill-use.ts:357 [EXTRACTED]
  ```
  export async function deliveredTeamSkills(config: LocalConfig, cwd: string, delivered: DeliveredHashes, rev: string): Promise<{
  ```
- `recordedTeamSkills` ← src/skill-use.ts:452 [EXTRACTED]
  ```
  export function recordedTeamSkills(candidates: readonly SkillCandidate[], teamSkills: Readonly<Record<string, readonly string[]>>, cwd: string): string[] {
  ```
- `usedSkills` ← src/skill-use.ts:469 [EXTRACTED]
  ```
  export function usedSkills(
  ```
- `creditToolCall` ← src/skill-use.ts:608 [EXTRACTED]
  ```
  export async function creditToolCall(stdin: HookEvent, tool: string, config: LocalConfig): Promise<string[]> {
  ```
- `creditPromptMentions` ← src/skill-use.ts:623 [EXTRACTED]
  ```
  export async function creditPromptMentions(stdin: HookEvent, tool: string, config: LocalConfig): Promise<void> {
  ```
- `listInstallationRecords` ← src/source.ts:132 [EXTRACTED]
  ```
  export async function listInstallationRecords(): Promise<InstallationRecord[]> {
  ```
- `getSourceManifestPath` ← src/source.ts:149 [EXTRACTED]
  ```
  export function getSourceManifestPath(sourceName: string, localConfig: LocalConfig): string {
  ```
- `sourceAdd` ← src/source.ts:454 [EXTRACTED]
  ```
  export async function sourceAdd(repoUrl: string, options: { name?: string } & GlobalOptions): Promise<void> {
  ```
- `sourceRemove` ← src/source.ts:551 [EXTRACTED]
  ```
  export async function sourceRemove(name: string, options: GlobalOptions): Promise<void> {
  ```
- `sourceList` ← src/source.ts:693 [EXTRACTED]
  ```
  export async function sourceList(): Promise<void> {
  ```
- `sourceAddHttp` ← src/source.ts:751 [EXTRACTED]
  ```
  export async function sourceAddHttp(
  ```
- `sourceRemoveHttp` ← src/source.ts:808 [EXTRACTED]
  ```
  export async function sourceRemoveHttp(options: GlobalOptions): Promise<void> {
  ```
- `sourceBrowse` ← src/source.ts:822 [EXTRACTED]
  ```
  export async function sourceBrowse(name: string, options: GlobalOptions): Promise<void> {
  ```
- `pullSources` ← src/source.ts:905 [EXTRACTED]
  ```
  export async function pullSources(localConfig: LocalConfig, options: GlobalOptions, recorder?: DeliveryRecorder): Promise<void> {
  ```
- `sourceSyncWarnings` ← src/source.ts:1387 [EXTRACTED]
  ```
  export function sourceSyncWarnings(name: string, sourceConfig: TeamaiConfig | null): string[] {
  ```
- `deriveSourceName` ← src/source.ts:1412 [EXTRACTED]
  ```
  export function deriveSourceName(repoUrl: string): string | null {
  ```
- `getSourcePathOwners` ← src/source.ts:1623 [EXTRACTED]
  ```
  export async function getSourcePathOwners(currentManifest?: string): Promise<SourcePathOwner[]> {
  ```
- `getSourceSkillOrigins` ← src/source.ts:1908 [EXTRACTED]
  ```
  export async function getSourceSkillOrigins(localConfig: LocalConfig): Promise<Map<string, string>> {
  ```
- `getSourcePushQuarantineNames` ← src/source.ts:1926 [EXTRACTED]
  ```
  export async function getSourcePushQuarantineNames(localConfig: LocalConfig): Promise<Set<string>> {
  ```
- `aggregateUsage` ← src/stats.ts:24 [EXTRACTED]
  ```
  export function aggregateUsage(events: UsageEvent[]): SkillStats[] {
  ```
- `showStats` ← src/stats.ts:253 [EXTRACTED]
  ```
  export async function showStats(options: ShowStatsOptions = {}): Promise<void> {
  ```
- `status` ← src/status.ts:56 [EXTRACTED]
  ```
  export async function status(options: GlobalOptions): Promise<void> {
  ```
- `list` ← src/status.ts:327 [EXTRACTED]
  ```
  export async function list(type: string | undefined, options: ListOptions): Promise<void> {
  ```
- `tagsList` ← src/tags.ts:55 [EXTRACTED]
  ```
  export async function tagsList(): Promise<void> {
  ```
- `tagsSubscribe` ← src/tags.ts:119 [EXTRACTED]
  ```
  export async function tagsSubscribe(tags: string[], options: GlobalOptions): Promise<void> {
  ```
- `tagsUnsubscribe` ← src/tags.ts:164 [EXTRACTED]
  ```
  export async function tagsUnsubscribe(tags: string[], options: GlobalOptions): Promise<void> {
  ```
- `tagsAdd` ← src/tags.ts:210 [EXTRACTED]
  ```
  export async function tagsAdd(
  ```
- `tagsRemove` ← src/tags.ts:264 [EXTRACTED]
  ```
  export async function tagsRemove(
  ```
- `mergeStats` ← src/team-push.ts:98 [EXTRACTED]
  ```
  export function mergeStats(
  ```
- `teamSharedSkillNames` ← src/team-push.ts:147 [EXTRACTED]
  ```
  export async function teamSharedSkillNames(repoRoot: string): Promise<Set<string>> {
  ```
- `mergeStatsWithinTeamSkills` ← src/team-push.ts:165 [EXTRACTED]
  ```
  export function mergeStatsWithinTeamSkills(
  ```
- `readReportedInterventions` ← src/team-push.ts:263 [EXTRACTED]
  ```
  export async function readReportedInterventions(config: LocalConfig | undefined, persist = true, ownerState?: SessionOwnerState): Promise<ReportedInterventions> {
  ```
- `interventionCounts` ← src/team-push.ts:281 [EXTRACTED]
  ```
  export function interventionCounts(metrics: Map<string, SessionMetrics>): Map<string, ReportedInterventions[string]> {
  ```
- `computeInterventionDelta` ← src/team-push.ts:359 [EXTRACTED]
  ```
  export function computeInterventionDelta(
  ```
- `mergeInterventionStats` ← src/team-push.ts:380 [EXTRACTED]
  ```
  export function mergeInterventionStats(
  ```
- `readReportedPromptTokens` ← src/team-push.ts:407 [EXTRACTED]
  ```
  export async function readReportedPromptTokens(config: LocalConfig | undefined, persist = true, ownerState?: SessionOwnerState): Promise<ReportedPromptTokens> {
  ```
- `droppedRollouts` ← src/team-push.ts:489 [EXTRACTED]
  ```
  export function droppedRollouts(
  ```
- `computePromptTokenDelta` ← src/team-push.ts:584 [EXTRACTED]
  ```
  export function computePromptTokenDelta(
  ```
- `withDroppedRollouts` ← src/team-push.ts:633 [EXTRACTED]
  ```
  export function withDroppedRollouts(
  ```
- `mergePromptTokenStats` ← src/team-push.ts:676 [EXTRACTED]
  ```
  export function mergePromptTokenStats(
  ```
- `metricsAsOf` ← src/team-push.ts:872 [EXTRACTED]
  ```
  export function metricsAsOf(events: DashboardEvent[], at: number | undefined): Map<string, SessionMetrics> | undefined {
  ```
- `snapshotWrittenAt` ← src/team-push.ts:881 [EXTRACTED]
  ```
  export async function snapshotWrittenAt(config: LocalConfig | undefined): Promise<number | undefined> {
  ```
- `reportedBaselines` ← src/team-push.ts:902 [EXTRACTED]
  ```
  export async function reportedBaselines(
  ```
- `adoptBareKeys` ← src/team-push.ts:976 [EXTRACTED]
  ```
  export function adoptBareKeys<T>(
  ```
- `reportUsage` ← src/team-push.ts:1087 [EXTRACTED]
  ```
  export async function reportUsage(
  ```
- `TeamRefError` ← src/team-ref.ts:9 [EXTRACTED]
  ```
  export class TeamRefError extends Error {
  ```
- `teamRefBlocker` ← src/team-ref.ts:19 [EXTRACTED]
  ```
  export function teamRefBlocker(project: LocalConfig | null, user: LocalConfig | null): { block: TeamRefBlock; message: string } | null {
  ```
- `teamRefNotice` ← src/team-ref.ts:33 [EXTRACTED]
  ```
  export function teamRefNotice(ref: string, commit: string, defaultBranch: string): string {
  ```
- `resolveTeamRef` ← src/team-ref.ts:37 [EXTRACTED]
  ```
  export async function resolveTeamRef(localPath: string, ref: string, signal?: AbortSignal): Promise<ResolvedTeamRef> {
  ```
- `DirtyTeamRepoError` ← src/team-ref.ts:75 [EXTRACTED]
  ```
  export class DirtyTeamRepoError extends Error {
  ```
- `DetachedRecoveryError` ← src/team-ref.ts:83 [EXTRACTED]
  ```
  export class DetachedRecoveryError extends Error {
  ```
- `transitionTeamRepo` ← src/team-ref.ts:94 [EXTRACTED]
  ```
  export async function transitionTeamRepo(
  ```
- `removedTeamResources` ← src/team-ref.ts:195 [EXTRACTED]
  ```
  export async function removedTeamResources(localPath: string, previous: string, current: string): Promise<RemovedTeamResources> {
  ```
- `POST_DEPLOY_BUDGET_SEC` ← src/team-scripts.ts:36 [EXTRACTED]
  ```
  export const POST_DEPLOY_BUDGET_SEC = 15;
  ```
- `TEAM_SCRIPT_EVENTS` ← src/team-scripts.ts:38 [EXTRACTED]
  ```
  export const TEAM_SCRIPT_EVENTS = ['preInit', 'postInit', 'prePull', 'postPull', 'postDeploy'] as const;
  ```
- `isTeamScriptEvent` ← src/team-scripts.ts:44 [EXTRACTED]
  ```
  export function isTeamScriptEvent(value: string): value is TeamScriptEvent {
  ```
- `teamScriptPrompts` ← src/team-scripts.ts:49 [EXTRACTED]
  ```
  export function teamScriptPrompts(event: TeamScriptEvent): boolean {
  ```
- `teamScriptEnv` ← src/team-scripts.ts:85 [EXTRACTED]
  ```
  export async function teamScriptEnv(localConfig: LocalConfig): Promise<NodeJS.ProcessEnv> {
  ```
- `runTeamScript` ← src/team-scripts.ts:111 [EXTRACTED]
  ```
  export async function runTeamScript(
  ```
- `syncMcpAfterPostInit` ← src/team-scripts.ts:177 [EXTRACTED]
  ```
  export async function syncMcpAfterPostInit(localConfig: LocalConfig): Promise<void> {
  ```
- `judgeTeamaiOnlyFiles` ← src/teamai-only-files.ts:52 [EXTRACTED]
  ```
  export async function judgeTeamaiOnlyFiles(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<SharedFileJudgement[]> {
  ```
- `keptOutByMcpExclude` ← src/teamai-only-files.ts:98 [EXTRACTED]
  ```
  export async function keptOutByMcpExclude(files: readonly string[]): Promise<Set<string>> {
  ```
- `describeNoLongerTeamaiOnly` ← src/teamai-only-files.ts:106 [EXTRACTED]
  ```
  export async function describeNoLongerTeamaiOnly(file: string, projectRoot: string): Promise<string> {
  ```
- `describeUnknownTracking` ← src/teamai-only-files.ts:114 [EXTRACTED]
  ```
  export async function describeUnknownTracking(judgement: SharedFileJudgement, projectRoot: string, kept: boolean): Promise<string> {
  ```
- `retireOpencodeV1Instructions` ← src/teamai-only-files.ts:166 [EXTRACTED]
  ```
  export async function retireOpencodeV1Instructions(
  ```
- `opencodeV1Leftovers` ← src/teamai-only-files.ts:199 [EXTRACTED]
  ```
  export async function opencodeV1Leftovers(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<Array<{ file: string; entries: string[] }>> {
  ```
- `getTodoWriteHintCachePath` ← src/todowrite-hint.ts:44 [EXTRACTED]
  ```
  export function getTodoWriteHintCachePath(sessionId: string): string {
  ```
- `shouldSkipTodoWriteHint` ← src/todowrite-hint.ts:84 [EXTRACTED]
  ```
  export function shouldSkipTodoWriteHint(sessionId: string): boolean {
  ```
- `readStdin` ← src/todowrite-hint.ts:98 [EXTRACTED]
  ```
  export async function readStdin(): Promise<HookInput | null> {
  ```
- `buildHintMessage` ← src/todowrite-hint.ts:125 [EXTRACTED]
  ```
  export function buildHintMessage(hook: DefaultFolder<'hooks', 'teamai-todowrite-hint'>, language?: TextLanguage): string {
  ```
- `todoWriteHint` ← src/todowrite-hint.ts:138 [EXTRACTED]
  ```
  export async function todoWriteHint(tool?: string): Promise<void> {
  ```
- `nextToolHomes` ← src/tool-home-record.ts:46 [EXTRACTED]
  ```
  export async function nextToolHomes(
  ```
- `recordToolHomes` ← src/tool-home-record.ts:123 [EXTRACTED]
  ```
  export async function recordToolHomes(by: 'init' | 'pull', host: Host = realHost()): Promise<readonly ToolHomeChange[]> {
  ```
- `describeToolHomeChange` ← src/tool-home-record.ts:146 [EXTRACTED]
  ```
  export function describeToolHomeChange({ tool, variable, dir }: ToolHomeChange): string {
  ```
- `toolHomeVariableNames` ← src/tool-home.ts:46 [EXTRACTED]
  ```
  export function toolHomeVariableNames(): ReadonlySet<string> {
  ```
- `realHost` ← src/tool-home.ts:66 [EXTRACTED]
  ```
  export function realHost(overrides: Partial<Pick<Host, 'env' | 'home'>> = {}): Host {
  ```
- `homeEnvOf` ← src/tool-home.ts:97 [EXTRACTED]
  ```
  export function homeEnvOf(tool: ToolId): string | undefined {
  ```
- `envToolHome` ← src/tool-home.ts:122 [EXTRACTED]
  ```
  export function envToolHome(tool: ToolId, host: Host = realHost()): EnvToolHome | null {
  ```
- `ompProfile` ← src/tool-home.ts:211 [EXTRACTED]
  ```
  export function ompProfile(env: Readonly<Record<string, string | undefined>>): OmpProfile {
  ```
- `toolHome` ← src/tool-home.ts:282 [EXTRACTED]
  ```
  export function toolHome(tool: ToolId, host: Host = realHost()): string {
  ```
- `envInstanceHome` ← src/tool-home.ts:294 [EXTRACTED]
  ```
  export function envInstanceHome(home: ToolInstanceHome, host: Host = realHost()): EnvToolHome | null {
  ```
- `instanceHomeDir` ← src/tool-home.ts:305 [EXTRACTED]
  ```
  export function instanceHomeDir({ name, home }: { readonly name: string; readonly home: ToolInstanceHome }, host: Host = realHost()): string {
  ```
- `instanceHomeAfterInit` ← src/tool-home.ts:316 [EXTRACTED]
  ```
  export function instanceHomeAfterInit({ name, home }: { readonly name: string; readonly home: ToolInstanceHome }, host: Host = realHost()): string {
  ```
- `toolHomeOf` ← src/tool-home.ts:330 [EXTRACTED]
  ```
  export function toolHomeOf(name: string, host: Host = realHost()): { readonly root: string; readonly dir: string } | undefined {
  ```
- `movedToolHome` ← src/tool-home.ts:342 [EXTRACTED]
  ```
  export function movedToolHome(tool: ToolId, host: Host = realHost()): string | null {
  ```
- `toolHomesAcrossProfiles` ← src/tool-home.ts:364 [EXTRACTED]
  ```
  export async function toolHomesAcrossProfiles(tool: 'hermes' | 'omp' | 'opencode', host: Host = realHost()): Promise<string[]> {
  ```
- `recordedHomes` ← src/tool-home.ts:425 [EXTRACTED]
  ```
  export function recordedHomes(host: Pick<Host, 'toolHomes'>): Readonly<Record<string, string>> {
  ```
- `defaultToolHome` ← src/tool-home.ts:430 [EXTRACTED]
  ```
  export function defaultToolHome(tool: ToolId, host: Pick<Host, 'home' | 'path'>): string {
  ```
- `homeRoot` ← src/tool-home.ts:435 [EXTRACTED]
  ```
  export function homeRoot(tool: ToolId): string {
  ```
- `isSameDirOn` ← src/tool-home.ts:442 [EXTRACTED]
  ```
  export function isSameDirOn(host: Pick<Host, 'platform' | 'path'>, one: string, other: string): boolean {
  ```
- `absoluteOn` ← src/tool-home.ts:450 [EXTRACTED]
  ```
  export function absoluteOn(value: string, host: Host): string {
  ```
- `expandHomeOn` ← src/tool-home.ts:457 [EXTRACTED]
  ```
  export function expandHomeOn(value: string, host: Pick<Host, 'home' | 'platform' | 'path'>): string {
  ```
- `toolHomesPath` ← src/tool-home.ts:468 [EXTRACTED]
  ```
  export function toolHomesPath(): string {
  ```
- `toolHomesHistoryPath` ← src/tool-home.ts:473 [EXTRACTED]
  ```
  export function toolHomesHistoryPath(): string {
  ```
- `reloadToolHomesHistory` ← src/tool-home.ts:485 [EXTRACTED]
  ```
  export function reloadToolHomesHistory(): ToolHomesHistory {
  ```
- `rememberToolHome` ← src/tool-home.ts:506 [EXTRACTED]
  ```
  export async function rememberToolHome(tool: string, home: string): Promise<void> {
  ```
- `describeInvalidToolHomes` ← src/tool-home.ts:518 [EXTRACTED]
  ```
  export function describeInvalidToolHomes(error: string): string {
  ```
- `reloadToolHomes` ← src/tool-home.ts:542 [EXTRACTED]
  ```
  export function reloadToolHomes(): ToolHomesRead {
  ```
- `parseToolHomes` ← src/tool-home.ts:552 [EXTRACTED]
  ```
  export function parseToolHomes(file: string): ToolHomesRead {
  ```
- `saveToolHomes` ← src/tool-home.ts:587 [EXTRACTED]
  ```
  export async function saveToolHomes(homes: Readonly<Record<string, string>>): Promise<void> {
  ```
- `teamToolInstances` ← src/tool-instances.ts:311 [EXTRACTED]
  ```
  export async function teamToolInstances(team: TeamTree): Promise<DeclaredTool[]> {
  ```
- `PERSONAL_TOOLS_DIR` ← src/tool-instances.ts:340 [EXTRACTED]
  ```
  export const PERSONAL_TOOLS_DIR = 'tools';
  ```
- `personalToolsDir` ← src/tool-instances.ts:343 [EXTRACTED]
  ```
  export function personalToolsDir(): string {
  ```
- `personalToolInstances` ← src/tool-instances.ts:348 [EXTRACTED]
  ```
  export async function personalToolInstances(): Promise<DeclaredTool[]> {
  ```
- `ignorePersonalToolInstances` ← src/tool-instances.ts:371 [EXTRACTED]
  ```
  export function ignorePersonalToolInstances(): void {
  ```
- `resetToolInstancesForTests` ← src/tool-instances.ts:377 [EXTRACTED]
  ```
  export function resetToolInstancesForTests(): void {
  ```
- `judgeInstanceHomesAsInit` ← src/tool-instances.ts:390 [EXTRACTED]
  ```
  export function judgeInstanceHomesAsInit(): void {
  ```
- `declaredTable` ← src/tool-instances.ts:399 [EXTRACTED]
  ```
  export function declaredTable({ repos, own: mine }: {
  ```
- `leftInstanceHookFiles` ← src/tool-instances.ts:517 [EXTRACTED]
  ```
  export function leftInstanceHookFiles({ name, homes, current, toolRoots, toolPaths }: {
  ```
- `effectivePathsOf` ← src/tool-instances.ts:570 [EXTRACTED]
  ```
  export function effectivePathsOf(instance: DeclaredTool, toolPaths: TeamaiConfig['toolPaths']): z.infer<typeof ToolPathsSchema> | undefined {
  ```
- `defaultPathsOf` ← src/tool-instances.ts:578 [EXTRACTED]
  ```
  export function defaultPathsOf(instance: DeclaredTool, toolPaths: TeamaiConfig['toolPaths']): z.infer<typeof ToolPathsSchema> {
  ```
- `instanceReadPath` ← src/tool-instances.ts:590 [EXTRACTED]
  ```
  export function instanceReadPath(instance: DeclaredTool, { from, relative }: { from: 'home' | 'project'; relative: string }): string {
  ```
- `withToolInstances` ← src/tool-instances.ts:601 [EXTRACTED]
  ```
  export async function withToolInstances(tree: TeamToolTree, config: TeamaiConfig): Promise<TeamaiConfig> {
  ```
- `acceptTeamCommand` ← src/tool-instances.ts:705 [EXTRACTED]
  ```
  export async function acceptTeamCommand(
  ```
- `acceptedCommandOf` ← src/tool-instances.ts:765 [EXTRACTED]
  ```
  export function acceptedCommandOf(instance: DeclaredTool): string | undefined {
  ```
- `askingOnce` ← src/tool-instances.ts:788 [EXTRACTED]
  ```
  export function askingOnce(ask: (question: string) => Promise<string | undefined>): (question: string) => Promise<string | undefined> {
  ```
- `acceptToolCommand` ← src/tool-instances.ts:802 [EXTRACTED]
  ```
  export async function acceptToolCommand(
  ```
- `useToolInstances` ← src/tool-registry.ts:39 [EXTRACTED]
  ```
  export function useToolInstances(instances: ReadonlyMap<string, DeclaredTool>, declared: ReadonlyMap<string, DeclaredTool> = instances): void {
  ```
- `toolInstancesFor` ← src/tool-registry.ts:54 [EXTRACTED]
  ```
  export function toolInstancesFor(purpose: InstancePurpose): DeclaredTool[] {
  ```
- `baseToolOf` ← src/tool-registry.ts:76 [EXTRACTED]
  ```
  export function baseToolOf(name: string): string {
  ```
- `toolRootsKeyOf` ← src/tool-registry.ts:84 [EXTRACTED]
  ```
  export function toolRootsKeyOf(name: string): string {
  ```
- `baseDescriptorOf` ← src/tool-registry.ts:95 [EXTRACTED]
  ```
  export function baseDescriptorOf(name: string): ShippedDescriptor | undefined {
  ```
- `runsSteps` ← src/tool-registry.ts:102 [EXTRACTED]
  ```
  export function runsSteps(name: string): boolean {
  ```
- `hasDefaultHomeLeftovers` ← src/tool-registry.ts:122 [EXTRACTED]
  ```
  export function hasDefaultHomeLeftovers(tool: ToolId): boolean {
  ```
- `homeVariables` ← src/tool-registry.ts:129 [EXTRACTED]
  ```
  export function homeVariables(tool: ToolId): readonly string[] {
  ```
- `skillsFollowSession` ← src/tool-registry.ts:158 [EXTRACTED]
  ```
  export function skillsFollowSession(tool: string): boolean {
  ```
- `installGateOf` ← src/tool-registry.ts:163 [EXTRACTED]
  ```
  export function installGateOf(tool: ToolId): InstallGate | undefined {
  ```
- `platformForTool` ← src/tool-registry.ts:176 [EXTRACTED]
  ```
  export function platformForTool(tool: string): string | undefined {
  ```
- `toolsWithoutSessions` ← src/tool-registry.ts:181 [EXTRACTED]
  ```
  export function toolsWithoutSessions(tools: readonly string[]): string[] {
  ```
- `platformFactsOf` ← src/tool-registry.ts:186 [EXTRACTED]
  ```
  export function platformFactsOf(platform: string): SessionPlatformFacts | undefined {
  ```
- `toolForPlatform` ← src/tool-registry.ts:193 [EXTRACTED]
  ```
  export function toolForPlatform(platform: string): string {
  ```
- `folderReachOf` ← src/tool-registry.ts:215 [EXTRACTED]
  ```
  export function folderReachOf(tool: string): FolderReach {
  ```
- `channelsOf` ← src/tool-registry.ts:220 [EXTRACTED]
  ```
  export function channelsOf(tool: string): Pick<ShippedDescriptor, 'rules' | 'blocks' | 'agents' | 'mcp' | 'hooks'> {
  ```
- `selfLocalSettingsOf` ← src/tool-registry.ts:228 [EXTRACTED]
  ```
  export function selfLocalSettingsOf(tool: string): string | null {
  ```
- `isAgentToolId` ← src/tool-registry.ts:237 [EXTRACTED]
  ```
  export function isAgentToolId(tool: string): tool is AgentToolId {
  ```
- `agentFormatOf` ← src/tool-registry.ts:245 [EXTRACTED]
  ```
  export function agentFormatOf(tool: string): AgentToolId | undefined {
  ```
- `ruleFormatIdOf` ← src/tool-registry.ts:255 [EXTRACTED]
  ```
  export function ruleFormatIdOf(tool: string): RuleFormatId | 'verbatim' {
  ```
- `runTimeRulesOf` ← src/tool-registry.ts:266 [EXTRACTED]
  ```
  export function runTimeRulesOf(tool: string): RunTimeVia | null {
  ```
- `hookSettingsFormatOf` ← src/tool-registry.ts:297 [EXTRACTED]
  ```
  export function hookSettingsFormatOf(tool: string): HookFormat | null {
  ```
- `hookSyntaxOf` ← src/tool-registry.ts:306 [EXTRACTED]
  ```
  export function hookSyntaxOf(tool: string): JsonSyntax {
  ```
- `mcpSyntaxOf` ← src/tool-registry.ts:315 [EXTRACTED]
  ```
  export function mcpSyntaxOf(tool: string, scope: 'user' | 'project'): JsonSyntax {
  ```
- `hookFormatOf` ← src/tool-registry.ts:322 [EXTRACTED]
  ```
  export function hookFormatOf(tool: string): HookFormat {
  ```
- `mcpFormatOf` ← src/tool-registry.ts:327 [EXTRACTED]
  ```
  export function mcpFormatOf(tool: string): McpFormat | null {
  ```
- `isInstanceBase` ← src/tool-registry.ts:347 [EXTRACTED]
  ```
  export function isInstanceBase(tool: string): tool is InstanceBase {
  ```
- `mcpScopeFor` ← src/tool-registry.ts:360 [EXTRACTED]
  ```
  export function mcpScopeFor(tool: string, scope: 'user' | 'project'): 'user' | 'project' {
  ```
- `TOOL_IDS` ← src/tools.ts:17 [EXTRACTED]
  ```
  export const TOOL_IDS = [
  ```
- `STEP_LAUNCH_ADAPTERS` ← src/tools.ts:52 [EXTRACTED]
  ```
  export const STEP_LAUNCH_ADAPTERS = ['claude', 'codex', 'opencode', 'codebuddy', 'agy'] as const satisfies readonly LaunchAdapterId[];
  ```
- `TOOLS` ← src/tools.ts:67 [EXTRACTED]
  ```
  export const TOOLS = {
  ```
- `ToolPathsSchema` ← src/types.ts:25 [EXTRACTED]
  ```
  export const ToolPathsSchema = z.object({
  ```
- `ScopeEnum` ← src/types.ts:84 [EXTRACTED]
  ```
  export const ScopeEnum = z.enum(['user', 'project'], { error: unknownScopeError });
  ```
- `InstallScopeSchema` ← src/types.ts:94 [EXTRACTED]
  ```
  export const InstallScopeSchema = z
  ```
- `parseInstallScope` ← src/types.ts:99 [EXTRACTED]
  ```
  export function parseInstallScope(value: string): Scope {
  ```
- `installScopeName` ← src/types.ts:108 [EXTRACTED]
  ```
  export function installScopeName(scope: Scope): 'user' | 'workspace' {
  ```
- `SharingConfigSchema` ← src/types.ts:114 [EXTRACTED]
  ```
  export const SharingConfigSchema = z.object({
  ```
- `getInterventionSharing` ← src/types.ts:242 [EXTRACTED]
  ```
  export function getInterventionSharing(config: {
  ```
- `getHooksSharing` ← src/types.ts:249 [EXTRACTED]
  ```
  export function getHooksSharing(config: { sharing?: { hooks?: { autoApply?: boolean; requireTeamScripts?: boolean } } }) {
  ```
- `getMcpSharing` ← src/types.ts:259 [EXTRACTED]
  ```
  export function getMcpSharing(config: {
  ```
- `getRecallSharing` ← src/types.ts:272 [EXTRACTED]
  ```
  export function getRecallSharing(config: { sharing?: { recall?: { enabled?: boolean } } }) {
  ```
- `isGitExcludeEnabled` ← src/types.ts:284 [EXTRACTED]
  ```
  export function isGitExcludeEnabled(
  ```
- `resolveGitExclude` ← src/types.ts:300 [EXTRACTED]
  ```
  export function resolveGitExclude(
  ```
- `isUnmigratedDataHome` ← src/types.ts:310 [EXTRACTED]
  ```
  export function isUnmigratedDataHome(localConfig: { scope?: string; projectRoot?: string; dataHome?: string }): boolean {
  ```
- `isRecallEnabled` ← src/types.ts:320 [EXTRACTED]
  ```
  export function isRecallEnabled(
  ```
- `isContributeHintEnabled` ← src/types.ts:336 [EXTRACTED]
  ```
  export function isContributeHintEnabled(
  ```
- `isMrHintEnabled` ← src/types.ts:355 [EXTRACTED]
  ```
  export function isMrHintEnabled(
  ```
- `isUsageReportEnabled` ← src/types.ts:368 [EXTRACTED]
  ```
  export function isUsageReportEnabled(
  ```
- `resolveCoAuthor` ← src/types.ts:382 [EXTRACTED]
  ```
  export function resolveCoAuthor(
  ```
- `resolveAutoCompactTokens` ← src/types.ts:397 [EXTRACTED]
  ```
  export function resolveAutoCompactTokens(
  ```
- `SourceConfigSchema` ← src/types.ts:428 [EXTRACTED]
  ```
  export const SourceConfigSchema = z.object({
  ```
- `SOURCE_PULL_TTL_MS` ← src/types.ts:458 [EXTRACTED]
  ```
  export const SOURCE_PULL_TTL_MS = 24 * 60 * 60 * 1000;
  ```
- `TEAMAI_SOURCES_DIR` ← src/types.ts:460 [EXTRACTED]
  ```
  export const TEAMAI_SOURCES_DIR = path.join(getUserHome(), '.teamai', 'sources');
  ```
- `ProviderNameSchema` ← src/types.ts:463 [EXTRACTED]
  ```
  export const ProviderNameSchema = z.enum(['tgit', 'github', 'cnb', 'gitlab', 'gitcode', 'git']);
  ```
- `TeamaiConfigBaseSchema` ← src/types.ts:761 [EXTRACTED]
  ```
  export const TeamaiConfigBaseSchema = z.object({
  ```
- `TeamaiConfigSchema` ← src/types.ts:846 [EXTRACTED]
  ```
  export const TeamaiConfigSchema = TeamaiConfigBaseSchema.superRefine((config, ctx) => {
  ```
- `MemberConfigSchema` ← src/types.ts:872 [EXTRACTED]
  ```
  export const MemberConfigSchema = z.object({
  ```
- `WorkflowToolSchema` ← src/types.ts:892 [EXTRACTED]
  ```
  export const WorkflowToolSchema = z.string().min(1);
  ```
- `DriverTuningSchema` ← src/types.ts:900 [EXTRACTED]
  ```
  export const DriverTuningSchema = z.object({ runtimes: z.record(z.string(), z.record(z.string(), JsonValueSchema)) }).strict();
  ```
- `MemberWorkflowSettingsSchema` ← src/types.ts:904 [EXTRACTED]
  ```
  export const MemberWorkflowSettingsSchema = z.object({
  ```
- `MemberSettingsSchema` ← src/types.ts:935 [EXTRACTED]
  ```
  export const MemberSettingsSchema = z.object({
  ```
- `LocalConfigSchema` ← src/types.ts:1026 [EXTRACTED]
  ```
  export const LocalConfigSchema = z.object({
  ```
- `PendingPushItemSchema` ← src/types.ts:1191 [EXTRACTED]
  ```
  export const PendingPushItemSchema = z.object({
  ```
- `PendingPushSchema` ← src/types.ts:1231 [EXTRACTED]
  ```
  export const PendingPushSchema = z.object({
  ```
- `DeliverySelectionSchema` ← src/types.ts:1292 [EXTRACTED]
  ```
  export const DeliverySelectionSchema = z.object({
  ```
- `StateSchema` ← src/types.ts:1308 [EXTRACTED]
  ```
  export const StateSchema = z.object({
  ```
- `HookPayloadSchema` ← src/types.ts:1706 [EXTRACTED]
  ```
  export const HookPayloadSchema = z.looseObject({
  ```
- `managedMcpManifestKey` ← src/types.ts:1826 [EXTRACTED]
  ```
  export function managedMcpManifestKey(tool: string, projectScope: boolean): string {
  ```
- `managedMcpWorkspaceId` ← src/types.ts:1833 [EXTRACTED]
  ```
  export function managedMcpWorkspaceId(workspaceRoot: string): string {
  ```
- `managedMcpManifestPath` ← src/types.ts:1849 [EXTRACTED]
  ```
  export function managedMcpManifestPath(dataHome: string, workspaceRoot?: string): string {
  ```
- `legacyManagedMcpManifestPath` ← src/types.ts:1864 [EXTRACTED]
  ```
  export function legacyManagedMcpManifestPath(dataHome: string): string {
  ```
- `getTeamaiHomeDir` ← src/types.ts:1975 [EXTRACTED]
  ```
  export function getTeamaiHomeDir(): string {
  ```
- `getTrustDir` ← src/types.ts:1983 [EXTRACTED]
  ```
  export function getTrustDir(): string {
  ```
- `getUserConfigPath` ← src/types.ts:1988 [EXTRACTED]
  ```
  export function getUserConfigPath(): string {
  ```
- `getUserStatePath` ← src/types.ts:1993 [EXTRACTED]
  ```
  export function getUserStatePath(): string {
  ```
- `getMachineDashboardDir` ← src/types.ts:2001 [EXTRACTED]
  ```
  export function getMachineDashboardDir(): string {
  ```
- `getSessionStateDir` ← src/types.ts:2009 [EXTRACTED]
  ```
  export function getSessionStateDir(): string {
  ```
- `getTokenPath` ← src/types.ts:2014 [EXTRACTED]
  ```
  export function getTokenPath(): string {
  ```
- `getUpdateLockPath` ← src/types.ts:2019 [EXTRACTED]
  ```
  export function getUpdateLockPath(): string {
  ```
- `TEAMAI_RULES_START` ← src/types.ts:2041 [EXTRACTED]
  ```
  export const TEAMAI_RULES_START = '<!-- [teamai:rules:start] -->';
  ```
- `TEAMAI_RULES_END` ← src/types.ts:2042 [EXTRACTED]
  ```
  export const TEAMAI_RULES_END = '<!-- [teamai:rules:end] -->';
  ```
- `TEAMAI_HOOK_DESCRIPTION_PREFIX` ← src/types.ts:2044 [EXTRACTED]
  ```
  export const TEAMAI_HOOK_DESCRIPTION_PREFIX = '[teamai]';
  ```
- `TEAMAI_CUSTOM_HOOK_PREFIX` ← src/types.ts:2052 [EXTRACTED]
  ```
  export const TEAMAI_CUSTOM_HOOK_PREFIX = '[teamai:hook:';
  ```
- `TEAMAI_AGENT_HOOK_PREFIX` ← src/types.ts:2062 [EXTRACTED]
  ```
  export const TEAMAI_AGENT_HOOK_PREFIX = '[teamai:agent-hook:';
  ```
- `TEAMAI_TEAM_RULES_START` ← src/types.ts:2072 [EXTRACTED]
  ```
  export const TEAMAI_TEAM_RULES_START = '<!-- [teamai:team-rules:start] -->';
  ```
- `TEAMAI_TEAM_RULES_END` ← src/types.ts:2073 [EXTRACTED]
  ```
  export const TEAMAI_TEAM_RULES_END = '<!-- [teamai:team-rules:end] -->';
  ```
- `TEAMAI_CULTURE_START` ← src/types.ts:2074 [EXTRACTED]
  ```
  export const TEAMAI_CULTURE_START = '<!-- [teamai:culture:start] -->';
  ```
- `TEAMAI_CULTURE_END` ← src/types.ts:2075 [EXTRACTED]
  ```
  export const TEAMAI_CULTURE_END = '<!-- [teamai:culture:end] -->';
  ```
- `TEAMAI_CLAUDEMD_START` ← src/types.ts:2077 [EXTRACTED]
  ```
  export const TEAMAI_CLAUDEMD_START = '<!-- [teamai:claudemd:start] -->';
  ```
- `TEAMAI_CLAUDEMD_END` ← src/types.ts:2078 [EXTRACTED]
  ```
  export const TEAMAI_CLAUDEMD_END = '<!-- [teamai:claudemd:end] -->';
  ```
- `TEAMAI_RECALL_RULES_START` ← src/types.ts:2081 [EXTRACTED]
  ```
  export const TEAMAI_RECALL_RULES_START = '<!-- [teamai:recall-rules:start] -->';
  ```
- `TEAMAI_RECALL_RULES_END` ← src/types.ts:2082 [EXTRACTED]
  ```
  export const TEAMAI_RECALL_RULES_END = '<!-- [teamai:recall-rules:end] -->';
  ```
- `SKILL_NAME_CHARS` ← src/types.ts:2087 [EXTRACTED]
  ```
  export const SKILL_NAME_CHARS = '[a-zA-Z0-9_\\-:.]';
  ```
- `SKILL_NAME_REGEX` ← src/types.ts:2090 [EXTRACTED]
  ```
  export const SKILL_NAME_REGEX = new RegExp(`^${SKILL_NAME_CHARS}{1,200}$`);
  ```
- `getSessionLogsDir` ← src/types.ts:2102 [EXTRACTED]
  ```
  export function getSessionLogsDir(): string {
  ```
- `UsageEventSchema` ← src/types.ts:2112 [EXTRACTED]
  ```
  export const UsageEventSchema = z.object({
  ```
- `parseUserStats` ← src/types.ts:2180 [EXTRACTED]
  ```
  export function parseUserStats(content: string): UserStats | null {
  ```
- `DASHBOARD_IDLE_TIMEOUT_MS` ← src/types.ts:2470 [EXTRACTED]
  ```
  export const DASHBOARD_IDLE_TIMEOUT_MS = 5 * 60 * 1000;
  ```
- `DASHBOARD_STALE_TIMEOUT_MS` ← src/types.ts:2473 [EXTRACTED]
  ```
  export const DASHBOARD_STALE_TIMEOUT_MS = 30 * 60 * 1000;
  ```
- `DASHBOARD_COMPACTION_THRESHOLD` ← src/types.ts:2476 [EXTRACTED]
  ```
  export const DASHBOARD_COMPACTION_THRESHOLD = 5_000;
  ```
- `DASHBOARD_STOPPED_DISPLAY_MS` ← src/types.ts:2479 [EXTRACTED]
  ```
  export const DASHBOARD_STOPPED_DISPLAY_MS = 30 * 1000;
  ```
- `DASHBOARD_PID_CHECK_INTERVAL_MS` ← src/types.ts:2482 [EXTRACTED]
  ```
  export const DASHBOARD_PID_CHECK_INTERVAL_MS = 15_000;
  ```
- `CORRECTION_WINDOW_MS` ← src/types.ts:2498 [EXTRACTED]
  ```
  export const CORRECTION_WINDOW_MS = 60 * 1000;
  ```
- `CORRECTION_KEYWORDS` ← src/types.ts:2501 [EXTRACTED]
  ```
  export const CORRECTION_KEYWORDS = [
  ```
- `TRANSCRIPT_INTERRUPT_PREFIX` ← src/types.ts:2510 [EXTRACTED]
  ```
  export const TRANSCRIPT_INTERRUPT_PREFIX = '[Request interrupted by user';
  ```
- `TRANSCRIPT_SYSTEM_PREFIXES` ← src/types.ts:2516 [EXTRACTED]
  ```
  export const TRANSCRIPT_SYSTEM_PREFIXES = [
  ```
- `stripInjectedPrompt` ← src/types.ts:2528 [EXTRACTED]
  ```
  export function stripInjectedPrompt(raw: string): string {
  ```
- `TRANSCRIPT_REJECT_MARKERS` ← src/types.ts:2546 [EXTRACTED]
  ```
  export const TRANSCRIPT_REJECT_MARKERS = [
  ```
- `TRANSCRIPT_HOST_BLOCK_MARKERS` ← src/types.ts:2559 [EXTRACTED]
  ```
  export const TRANSCRIPT_HOST_BLOCK_MARKERS = [
  ```
- `SessionShareOfferedSchema` ← src/types.ts:2631 [EXTRACTED]
  ```
  export const SessionShareOfferedSchema = z.object({ publish: z.boolean(), scorers: z.array(z.string()) });
  ```
- `CONTRIBUTE_FASTPATH_TTL_MS` ← src/types.ts:2644 [EXTRACTED]
  ```
  export const CONTRIBUTE_FASTPATH_TTL_MS = 5 * 60 * 1000;
  ```
- `CONTRIBUTE_GIT_COMMIT_DOWNWEIGHT` ← src/types.ts:2647 [EXTRACTED]
  ```
  export const CONTRIBUTE_GIT_COMMIT_DOWNWEIGHT = 0;
  ```
- `SEARCH_INDEX_VERSION` ← src/types.ts:2732 [EXTRACTED]
  ```
  export const SEARCH_INDEX_VERSION = 8;
  ```
- `UserVotesSchema` ← src/types.ts:2774 [EXTRACTED]
  ```
  export const UserVotesSchema = z.looseObject({
  ```
- `UserVotesV2Schema` ← src/types.ts:2879 [EXTRACTED]
  ```
  export const UserVotesV2Schema = z.looseObject({
  ```
- `getUserLearningsDir` ← src/types.ts:2898 [EXTRACTED]
  ```
  export function getUserLearningsDir(): string {
  ```
- `getUserSearchIndexPath` ← src/types.ts:2904 [EXTRACTED]
  ```
  export function getUserSearchIndexPath(): string {
  ```
- `getUserVotesDir` ← src/types.ts:2914 [EXTRACTED]
  ```
  export function getUserVotesDir(): string {
  ```
- `getVotesDir` ← src/types.ts:2925 [EXTRACTED]
  ```
  export function getVotesDir(config: LocalConfig): string {
  ```
- `CultureCompanySchema` ← src/types.ts:2934 [EXTRACTED]
  ```
  export const CultureCompanySchema = z.object({
  ```
- `CultureTeamSchema` ← src/types.ts:2941 [EXTRACTED]
  ```
  export const CultureTeamSchema = z.object({
  ```
- `CultureFrontmatterSchema` ← src/types.ts:2947 [EXTRACTED]
  ```
  export const CultureFrontmatterSchema = z.object({
  ```
- `resolveBaseDir` ← src/types.ts:2973 [EXTRACTED]
  ```
  export function resolveBaseDir(localConfig: Pick<LocalConfig, 'scope' | 'projectRoot'>): string {
  ```
- `COPILOT_TOOL_ID` ← src/types.ts:2988 [EXTRACTED]
  ```
  export const COPILOT_TOOL_ID = 'copilot';
  ```
- `CLAUDE_TOOL_ID` ← src/types.ts:2990 [EXTRACTED]
  ```
  export const CLAUDE_TOOL_ID = 'claude';
  ```
- `CODEX_TOOL_ID` ← src/types.ts:2995 [EXTRACTED]
  ```
  export const CODEX_TOOL_ID = 'codex';
  ```
- `WORKBUDDY_TOOL_ID` ← src/types.ts:3005 [EXTRACTED]
  ```
  export const WORKBUDDY_TOOL_ID = 'workbuddy';
  ```
- `WORKBUDDY_TOOL_ROOT` ← src/types.ts:3006 [EXTRACTED]
  ```
  export const WORKBUDDY_TOOL_ROOT = '.workbuddy';
  ```
- `WORKBUDDY_AI_ROOT` ← src/types.ts:3009 [EXTRACTED]
  ```
  export const WORKBUDDY_AI_ROOT = '.workbuddy-ai';
  ```
- `WORKBUDDY_LAST_LAUNCH_FILE` ← src/types.ts:3012 [EXTRACTED]
  ```
  export const WORKBUDDY_LAST_LAUNCH_FILE = 'last-launch.json';
  ```
- `MUSE_TOOL_ID` ← src/types.ts:3033 [EXTRACTED]
  ```
  export const MUSE_TOOL_ID = 'muse';
  ```
- `CURSOR_DATA_TOOL_ID` ← src/types.ts:3046 [EXTRACTED]
  ```
  export const CURSOR_DATA_TOOL_ID = 'cursor-data';
  ```
- `isOutsideUserHome` ← src/types.ts:3112 [EXTRACTED]
  ```
  export function isOutsideUserHome(dir: string, at: HomePaths = processHomePaths()): boolean {
  ```
- `toolRootRejection` ← src/types.ts:3200 [EXTRACTED]
  ```
  export function toolRootRejection(dir: string, at: HomePaths = processHomePaths()): ToolRootRejection | null {
  ```
- `toolRootRejectionText` ← src/types.ts:3212 [EXTRACTED]
  ```
  export function toolRootRejectionText(rejection: ToolRootRejection): string {
  ```
- `detectToolRoot` ← src/types.ts:3246 [EXTRACTED]
  ```
  export function detectToolRoot(tool: string, env: NodeJS.ProcessEnv = process.env): string | null {
  ```
- `cursorConfigDir` ← src/types.ts:3265 [EXTRACTED]
  ```
  export function cursorConfigDir(toolRoots?: Record<string, string>): string {
  ```
- `isAgentDisabled` ← src/types.ts:3278 [EXTRACTED]
  ```
  export function isAgentDisabled(localConfig: { disabledAgents?: string[] }, tool: string): boolean {
  ```
- `SELF_KNOWLEDGE_SCAN_KEY` ← src/types.ts:3294 [EXTRACTED]
  ```
  export const SELF_KNOWLEDGE_SCAN_KEY = '__teamai_self_knowledge__';
  ```
- `isAgentExcluded` ← src/types.ts:3296 [EXTRACTED]
  ```
  export function isAgentExcluded(
  ```
- `toolInstallRoot` ← src/types.ts:3317 [EXTRACTED]
  ```
  export function toolInstallRoot(toolPath: string): string {
  ```
- `relativeInside` ← src/types.ts:3331 [EXTRACTED]
  ```
  export function relativeInside(value: string, dir: string): string | undefined {
  ```
- `toolGateRoot` ← src/types.ts:3359 [EXTRACTED]
  ```
  export function toolGateRoot(
  ```
- `TOOL_ROOT_FIELDS` ← src/types.ts:3382 [EXTRACTED]
  ```
  export const TOOL_ROOT_FIELDS = ['skills', 'rules', 'settings', 'hooks', 'claudemd', 'agents', 'mcp'] as const;
  ```
- `warnSessionsOnlyToolRoot` ← src/types.ts:3403 [EXTRACTED]
  ```
  export function warnSessionsOnlyToolRoot(tool: string, resolved: string, at: HomePaths = processHomePaths()): void {
  ```
- `applyToolRoots` ← src/types.ts:3514 [EXTRACTED]
  ```
  export function applyToolRoots(
  ```
- `toolPathRoots` ← src/types.ts:3558 [EXTRACTED]
  ```
  export function toolPathRoots(paths: z.infer<typeof ToolPathsSchema>): Set<string> {
  ```
- `rerootToolPaths` ← src/types.ts:3569 [EXTRACTED]
  ```
  export function rerootToolPaths(paths: z.infer<typeof ToolPathsSchema>, newRoot: string): z.infer<typeof ToolPathsSchema> {
  ```
- `workbuddyLaunchedFrom` ← src/types.ts:3586 [EXTRACTED]
  ```
  export function workbuddyLaunchedFrom(
  ```
- `scopedToolPaths` ← src/types.ts:3717 [EXTRACTED]
  ```
  export function scopedToolPaths(
  ```
- `isSelfMode` ← src/types.ts:3762 [EXTRACTED]
  ```
  export function isSelfMode(localConfig: { repo: { kind?: string } }): boolean {
  ```
- `selfModeGitignorePath` ← src/types.ts:3767 [EXTRACTED]
  ```
  export function selfModeGitignorePath(localConfig: Pick<LocalConfig, 'repo' | 'projectRoot'>): string | undefined {
  ```
- `usesBranchWorktree` ← src/types.ts:3782 [EXTRACTED]
  ```
  export function usesBranchWorktree(localConfig: { repo: { kind?: string } }): boolean {
  ```
- `REPORTS_BRANCH` ← src/types.ts:3787 [EXTRACTED]
  ```
  export const REPORTS_BRANCH = 'teamai-reports';
  ```
- `REPORTS_WORKTREE_DIRNAME` ← src/types.ts:3790 [EXTRACTED]
  ```
  export const REPORTS_WORKTREE_DIRNAME = 'reports-wt';
  ```
- `LEARNINGS_BRANCH` ← src/types.ts:3793 [EXTRACTED]
  ```
  export const LEARNINGS_BRANCH = 'teamai-learnings';
  ```
- `LEARNINGS_WORKTREE_DIRNAME` ← src/types.ts:3796 [EXTRACTED]
  ```
  export const LEARNINGS_WORKTREE_DIRNAME = 'learnings-wt';
  ```
- `DATA_BRANCHES` ← src/types.ts:3799 [EXTRACTED]
  ```
  export const DATA_BRANCHES = [REPORTS_BRANCH, LEARNINGS_BRANCH] as const;
  ```
- `isDataBranch` ← src/types.ts:3803 [EXTRACTED]
  ```
  export function isDataBranch(branch: string): branch is DataBranch {
  ```
- `KNOWLEDGE_WORKTREE_DIRNAME` ← src/types.ts:3808 [EXTRACTED]
  ```
  export const KNOWLEDGE_WORKTREE_DIRNAME = 'knowledge-wt';
  ```
- `KNOWLEDGE_LOCK_FILENAME` ← src/types.ts:3811 [EXTRACTED]
  ```
  export const KNOWLEDGE_LOCK_FILENAME = '.knowledge-lock';
  ```
- `REPORTS_LOCK_FILENAME` ← src/types.ts:3824 [EXTRACTED]
  ```
  export const REPORTS_LOCK_FILENAME = '.reports-lock';
  ```
- `SELF_BRANCH_HOME_DIRNAME` ← src/types.ts:3832 [EXTRACTED]
  ```
  export const SELF_BRANCH_HOME_DIRNAME = 'side-branches';
  ```
- `LEARNINGS_LOCK_FILENAME` ← src/types.ts:3835 [EXTRACTED]
  ```
  export const LEARNINGS_LOCK_FILENAME = '.learnings-lock';
  ```
- `BOOTSTRAP_LOCK_FILENAME` ← src/types.ts:3838 [EXTRACTED]
  ```
  export const BOOTSTRAP_LOCK_FILENAME = '.bootstrap-lock';
  ```
- `SYNC_LOCK_FILENAME` ← src/types.ts:3847 [EXTRACTED]
  ```
  export const SYNC_LOCK_FILENAME = '.sync-lock';
  ```
- `getKnowledgeDir` ← src/types.ts:3856 [EXTRACTED]
  ```
  export function getKnowledgeDir(localConfig: LocalConfig): string {
  ```
- `getDataHome` ← src/types.ts:3876 [EXTRACTED]
  ```
  export function getDataHome(localConfig: LocalConfig): string {
  ```
- `getProjectSearchIndexPath` ← src/types.ts:3894 [EXTRACTED]
  ```
  export function getProjectSearchIndexPath(localConfig: LocalConfig): string {
  ```
- `getReportsDir` ← src/types.ts:3918 [EXTRACTED]
  ```
  export function getReportsDir(localConfig: LocalConfig): string {
  ```
- `getWorktreeDir` ← src/types.ts:3936 [EXTRACTED]
  ```
  export function getWorktreeDir(localConfig: LocalConfig, dirname: string): string {
  ```
- `getBusinessRoot` ← src/types.ts:3953 [EXTRACTED]
  ```
  export function getBusinessRoot(localConfig: LocalConfig): string {
  ```
- `getTeamaiHome` ← src/types.ts:3962 [EXTRACTED]
  ```
  export function getTeamaiHome(scope: Scope, projectRoot?: string): string {
  ```
- `getEnvBackupPath` ← src/types.ts:3990 [EXTRACTED]
  ```
  export function getEnvBackupPath(localConfig: LocalConfig): string {
  ```
- `getConfigPath` ← src/types.ts:4005 [EXTRACTED]
  ```
  export function getConfigPath(scope: Scope, projectRoot?: string): string {
  ```
- `getStatePath` ← src/types.ts:4014 [EXTRACTED]
  ```
  export function getStatePath(localConfig: LocalConfig): string {
  ```
- `getCheckoutRolesPath` ← src/types.ts:4023 [EXTRACTED]
  ```
  export function getCheckoutRolesPath(localConfig: LocalConfig): string {
  ```
- `getManagedHooksPath` ← src/types.ts:4037 [EXTRACTED]
  ```
  export function getManagedHooksPath(localConfig: LocalConfig): string {
  ```
- `getUserManagedHooksPath` ← src/types.ts:4050 [EXTRACTED]
  ```
  export function getUserManagedHooksPath(): string {
  ```
- `legacyManagedHooksPath` ← src/types.ts:4060 [EXTRACTED]
  ```
  export function legacyManagedHooksPath(projectRoot: string): string {
  ```
- `resolveHookScope` ← src/types.ts:4097 [EXTRACTED]
  ```
  export function resolveHookScope(
  ```
- `hookToolPathsForConfig` ← src/types.ts:4119 [EXTRACTED]
  ```
  export function hookToolPathsForConfig(teamConfig: TeamaiConfig, localConfig: LocalConfig): TeamaiConfig['toolPaths'] {
  ```
- `resolveToolRootDir` ← src/types.ts:4131 [EXTRACTED]
  ```
  export function resolveToolRootDir(
  ```
- `recordedToolHomeDir` ← src/types.ts:4145 [EXTRACTED]
  ```
  export function recordedToolHomeDir(
  ```
- `recordedToolRootDir` ← src/types.ts:4159 [EXTRACTED]
  ```
  export function recordedToolRootDir(
  ```
- `resolveLegacyProjectHookScope` ← src/types.ts:4193 [EXTRACTED]
  ```
  export function resolveLegacyProjectHookScope(
  ```
- `getPushignorePath` ← src/types.ts:4212 [EXTRACTED]
  ```
  export function getPushignorePath(): string {
  ```
- `areTeamHooksDisabled` ← src/types.ts:4220 [EXTRACTED]
  ```
  export function areTeamHooksDisabled(): boolean {
  ```
- `WebhookEndpointSchema` ← src/types.ts:4302 [EXTRACTED]
  ```
  export const WebhookEndpointSchema = z.object({
  ```
- `WebhookConfigSchema` ← src/types.ts:4311 [EXTRACTED]
  ```
  export const WebhookConfigSchema = z.object({
  ```
- `getWebhookSharing` ← src/types.ts:4332 [EXTRACTED]
  ```
  export function getWebhookSharing(config: {
  ```
- `uninstall` ← src/uninstall.ts:3766 [EXTRACTED]
  ```
  export async function uninstall(opts: UninstallOptions): Promise<void> {
  ```
- `VERSION_CHECK_TIMEOUT` ← src/update-policy.ts:5 [EXTRACTED]
  ```
  export const VERSION_CHECK_TIMEOUT = 5_000;
  ```
- `INSTALL_TIMEOUT` ← src/update-policy.ts:6 [EXTRACTED]
  ```
  export const INSTALL_TIMEOUT = 60_000;
  ```
- `HOOK_REFRESH_TIMEOUT` ← src/update-policy.ts:7 [EXTRACTED]
  ```
  export const HOOK_REFRESH_TIMEOUT = 15_000;
  ```
- `UPDATE_BUDGET_MS` ← src/update-policy.ts:10 [EXTRACTED]
  ```
  export const UPDATE_BUDGET_MS = VERSION_CHECK_TIMEOUT + INSTALL_TIMEOUT + HOOK_REFRESH_TIMEOUT + 10_000;
  ```
- `resolveEffectiveUpdatePolicy` ← src/update-policy.ts:17 [EXTRACTED]
  ```
  export function resolveEffectiveUpdatePolicy(
  ```
- `withUpdatePolicy` ← src/update-policy.ts:37 [EXTRACTED]
  ```
  export function withUpdatePolicy(
  ```
- `withAutoUpdate` ← src/update-policy.ts:51 [EXTRACTED]
  ```
  export function withAutoUpdate(
  ```
- `resolveRegistryForPackage` ← src/update.ts:64 [EXTRACTED]
  ```
  export function resolveRegistryForPackage(pkgName: string): string {
  ```
- `resolveNpmCommand` ← src/update.ts:116 [EXTRACTED]
  ```
  export function resolveNpmCommand(): NpmCommand {
  ```
- `restoreInterruptedInstall` ← src/update.ts:172 [EXTRACTED]
  ```
  export function restoreInterruptedInstall(pkgDir: string): string | null {
  ```
- `restoreInterruptedBins` ← src/update.ts:237 [EXTRACTED]
  ```
  export function restoreInterruptedBins(pkgDir: string, prefix: string): string[] {
  ```
- `fetchLatestVersion` ← src/update.ts:319 [EXTRACTED]
  ```
  export async function fetchLatestVersion(
  ```
- `isCacheValid` ← src/update.ts:353 [EXTRACTED]
  ```
  export function isCacheValid(lastCheck: string | null, ttlMs: number = CACHE_TTL_MS): boolean {
  ```
- `lockHolder` ← src/update.ts:390 [EXTRACTED]
  ```
  export async function lockHolder(): Promise<Omit<LockPayload, 'owner'>> {
  ```
- `LockHolderFields` ← src/update.ts:414 [EXTRACTED]
  ```
  export const LockHolderFields = {
  ```
- `lockState` ← src/update.ts:465 [EXTRACTED]
  ```
  export async function lockState(resolved: string, { signal }: { signal?: AbortSignal } = {}): Promise<'live' | 'stale' | 'missing'> {
  ```
- `isHolderGone` ← src/update.ts:519 [EXTRACTED]
  ```
  export async function isHolderGone(
  ```
- `LockDirectoryGoneError` ← src/update.ts:697 [EXTRACTED]
  ```
  export class LockDirectoryGoneError extends Error {
  ```
- `acquireLock` ← src/update.ts:729 [EXTRACTED]
  ```
  export async function acquireLock(
  ```
- `releaseLock` ← src/update.ts:815 [EXTRACTED]
  ```
  export async function releaseLock(lockPath?: string): Promise<void> {
  ```
- `withFileLock` ← src/update.ts:845 [EXTRACTED]
  ```
  export async function withFileLock<T>(
  ```
- `sweepHeldLocksOnExit` ← src/update.ts:888 [EXTRACTED]
  ```
  export function sweepHeldLocksOnExit(): void {
  ```
- `listZombieLocks` ← src/update.ts:979 [EXTRACTED]
  ```
  export async function listZombieLocks(roots: string[]): Promise<string[]> {
  ```
- `removeZombieLocks` ← src/update.ts:1000 [EXTRACTED]
  ```
  export async function removeZombieLocks(roots: string[]): Promise<string[]> {
  ```
- `checkForUpdate` ← src/update.ts:1035 [EXTRACTED]
  ```
  export async function checkForUpdate(options?: { force?: boolean; dryRun?: boolean }): Promise<CheckResult> {
  ```
- `doUpdate` ← src/update.ts:1229 [EXTRACTED]
  ```
  export async function doUpdate(runningScope: LocalConfig | null, options?: { force?: boolean; automatic?: boolean }): Promise<UpdateOutcome> {
  ```
- `update` ← src/update.ts:1558 [EXTRACTED]
  ```
  export async function update(options: UpdateOptions): Promise<void> {
  ```
- `extractSkillName` ← src/usage-tracker.ts:76 [EXTRACTED]
  ```
  export function extractSkillName(toolInput: string | z.input<typeof SkillToolInputSchema>): string | null {
  ```
- `isValidSkillName` ← src/usage-tracker.ts:121 [EXTRACTED]
  ```
  export function isValidSkillName(name: string): boolean {
  ```
- `skillRoots` ← src/usage-tracker.ts:144 [EXTRACTED]
  ```
  export async function skillRoots({ config, toolRoots, hookCwd, tool: callingTool }: SkillRootsInput): Promise<string[]> {
  ```
- `skillExistsOnDisk` ← src/usage-tracker.ts:175 [EXTRACTED]
  ```
  export async function skillExistsOnDisk(skillName: string, roots: readonly string[]): Promise<boolean> {
  ```
- `isInstalledSkillFile` ← src/usage-tracker.ts:184 [EXTRACTED]
  ```
  export async function isInstalledSkillFile(skillName: string, file: string, roots: readonly string[]): Promise<boolean> {
  ```
- `appendUsageEvent` ← src/usage-tracker.ts:214 [EXTRACTED]
  ```
  export async function appendUsageEvent(event: UsageEvent, config: LocalConfig): Promise<void> {
  ```
- `readUsageEvents` ← src/usage-tracker.ts:231 [EXTRACTED]
  ```
  export async function readUsageEvents(config: LocalConfig): Promise<UsageEvent[]> {
  ```
- `truncateUsageAfterReport` ← src/usage-tracker.ts:252 [EXTRACTED]
  ```
  export async function truncateUsageAfterReport(reportedCount: number, config: LocalConfig): Promise<void> {
  ```
- `USAGE_EVENT_CAP` ← src/usage-tracker.ts:263 [EXTRACTED]
  ```
  export const USAGE_EVENT_CAP = 5_000;
  ```
- `capUsageEvents` ← src/usage-tracker.ts:273 [EXTRACTED]
  ```
  export async function capUsageEvents(config: LocalConfig): Promise<void> {
  ```
- `updateKnownSkills` ← src/usage-tracker.ts:340 [EXTRACTED]
  ```
  export async function updateKnownSkills(skillName: string): Promise<void> {
  ```
- `readKnownSkills` ← src/usage-tracker.ts:369 [EXTRACTED]
  ```
  export async function readKnownSkills(): Promise<Set<string>> {
  ```
- `track` ← src/usage-tracker.ts:416 [EXTRACTED]
  ```
  export async function track(rawToolName: string, toolInput: string, tool?: string): Promise<void> {
  ```
- `trackFromStdin` ← src/usage-tracker.ts:461 [EXTRACTED]
  ```
  export async function trackFromStdin(toolArg?: string): Promise<void> {
  ```
- `trackSlashCommand` ← src/usage-tracker.ts:475 [EXTRACTED]
  ```
  export async function trackSlashCommand(toolArg?: string): Promise<void> {
  ```
- `compareVersions` ← src/version.ts:7 [EXTRACTED]
  ```
  export function compareVersions(a: string, b: string): number {
  ```
- `renderDashboardReport` ← src/viz-render.ts:474 [EXTRACTED]
  ```
  export function renderDashboardReport(data: VizData) {
  ```
- `renderReport` ← src/viz-render.ts:824 [EXTRACTED]
  ```
  export function renderReport(data: VizData): string {
  ```
- `resolveVizRoot` ← src/viz.ts:183 [EXTRACTED]
  ```
  export async function resolveVizRoot(opts: VizOptions): Promise<VizPaths> {
  ```
- `aggregateTeamVotes` ← src/viz.ts:315 [EXTRACTED]
  ```
  export async function aggregateTeamVotes(votesDir: string): Promise<{
  ```
- `buildVizData` ← src/viz.ts:548 [EXTRACTED]
  ```
  export async function buildVizData(paths: VizPaths): Promise<VizData> {
  ```
- `generateReportHtml` ← src/viz.ts:644 [EXTRACTED]
  ```
  export async function generateReportHtml(opts: VizOptions = {}): Promise<string> {
  ```
- `getVizSummary` ← src/viz.ts:665 [EXTRACTED]
  ```
  export async function getVizSummary(opts: VizOptions = {}): Promise<VizSummary> {
  ```
- `getDashboardContext` ← src/viz.ts:678 [EXTRACTED]
  ```
  export async function getDashboardContext(opts: VizOptions = {}) {
  ```
- `withVotesLock` ← src/votes.ts:45 [EXTRACTED]
  ```
  export async function withVotesLock<T>(
  ```
- `pruneUpvoteLedger` ← src/votes.ts:109 [EXTRACTED]
  ```
  export async function pruneUpvoteLedger(votePath: string): Promise<void> {
  ```
- `migrateV1ToV2` ← src/votes.ts:125 [EXTRACTED]
  ```
  export function migrateV1ToV2(v1: UserVotes): UserVotesV2 {
  ```
- `readUserVotesFromContent` ← src/votes.ts:192 [EXTRACTED]
  ```
  export function readUserVotesFromContent(content: string): UserVotesV2 {
  ```
- `readUserVotes` ← src/votes.ts:203 [EXTRACTED]
  ```
  export async function readUserVotes(votePath: string): Promise<UserVotesV2> {
  ```
- `loadUserVotes` ← src/votes.ts:213 [EXTRACTED]
  ```
  export async function loadUserVotes(votePath: string): Promise<UserVotesV2> {
  ```
- `saveUserVotes` ← src/votes.ts:232 [EXTRACTED]
  ```
  export async function saveUserVotes(votePath: string, votes: UserVotesV2): Promise<void> {
  ```
- `incrementRecalled` ← src/votes.ts:242 [EXTRACTED]
  ```
  export async function incrementRecalled(votePath: string, docIds: string[]): Promise<boolean> {
  ```
- `incrementUpvoted` ← src/votes.ts:286 [EXTRACTED]
  ```
  export async function incrementUpvoted(
  ```
- `countRecalledSessions` ← src/votes.ts:373 [EXTRACTED]
  ```
  export async function countRecalledSessions({ votePath, sessionId, docIds }: { votePath: string; sessionId: string; docIds: readonly string[] }): Promise<boolean> {
  ```
- `forgetSessionIdentities` ← src/votes.ts:405 [EXTRACTED]
  ```
  export async function forgetSessionIdentities({ votePath, named }: { votePath: string; named: ReadonlySet<string> }): Promise<boolean> {
  ```
- `creditRecallAdoptions` ← src/votes.ts:436 [EXTRACTED]
  ```
  export async function creditRecallAdoptions({ votePath, credits }: { votePath: string; credits: readonly RecallAdoptionCredit[] }): Promise<RecallAdoptionCredit[] | null> {
  ```
- `mergeDeltas` ← src/votes.ts:487 [EXTRACTED]
  ```
  export function mergeDeltas(local: UserVotesV2, remote: UserVotesV2): UserVotesV2 {
  ```
- `hasPendingVoteDeltas` ← src/votes.ts:549 [EXTRACTED]
  ```
  export async function hasPendingVoteDeltas(localVotesDir: string, username: string): Promise<boolean> {
  ```
- `syncVotesToTeam` ← src/votes.ts:590 [EXTRACTED]
  ```
  export async function syncVotesToTeam(
  ```
- `readIndexVoteFiles` ← src/votes.ts:648 [EXTRACTED]
  ```
  export async function readIndexVoteFiles(config: LocalConfig): Promise<Array<{ path: string; content: string }>> {
  ```
- `stageVotesMerge` ← src/votes.ts:756 [EXTRACTED]
  ```
  export async function stageVotesMerge(
  ```
- `confirmVotesSynced` ← src/votes.ts:825 [EXTRACTED]
  ```
  export async function confirmVotesSynced(
  ```
- `recallFeedback` ← src/votes.ts:841 [EXTRACTED]
  ```
  export async function recallFeedback(opts: { positive?: string; negative?: string; dryRun?: boolean }): Promise<void> {
  ```
- `formatFeishuMessage` ← src/webhook-formatters.ts:25 [EXTRACTED]
  ```
  export function formatFeishuMessage(payload: WebhookPayload): FeishuMessage {
  ```
- `formatWecomMessage` ← src/webhook-formatters.ts:75 [EXTRACTED]
  ```
  export function formatWecomMessage(payload: WebhookPayload): WecomMessage {
  ```
- `formatGenericJson` ← src/webhook-formatters.ts:122 [EXTRACTED]
  ```
  export function formatGenericJson(payload: WebhookPayload): GenericWebhookMessage {
  ```
- `sendWebhook` ← src/webhook.ts:11 [EXTRACTED]
  ```
  export async function sendWebhook(
  ```
- `loadWebhookConfig` ← src/webhook.ts:147 [EXTRACTED]
  ```
  export async function loadWebhookConfig(
  ```
- `listWebhooks` ← src/webhook.ts:162 [EXTRACTED]
  ```
  export async function listWebhooks(): Promise<WebhookEndpoint[]> {
  ```
- `testWebhook` ← src/webhook.ts:170 [EXTRACTED]
  ```
  export async function testWebhook(url?: string, options: { dryRun?: boolean } = {}): Promise<void> {
  ```
- `workflowStart` ← src/workflow-commands.ts:505 [EXTRACTED]
  ```
  export async function workflowStart(name: string, options: StartOptions): Promise<void> {
  ```
- `startWorkflow` ← src/workflow-commands.ts:544 [EXTRACTED]
  ```
  export async function startWorkflow(name: string, options: StartOptions, shortcut: ShortcutStart = {}): Promise<WorkflowEnvelope | undefined> {
  ```
- `runShortcut` ← src/workflow-commands.ts:816 [EXTRACTED]
  ```
  export async function runShortcut({ workflow, inputs, command, json, nobodyAnswers, preview = false, teamRepo }: ShortcutRun): Promise<ShortcutEnd | undefined> {
  ```
- `workflowNext` ← src/workflow-commands.ts:1151 [EXTRACTED]
  ```
  export async function workflowNext(runId: string, options: {
  ```
- `workflowReport` ← src/workflow-commands.ts:1216 [EXTRACTED]
  ```
  export async function workflowReport(runId: string, options: { json?: string; driver?: string; attempt?: string; modelUnavailable?: boolean }): Promise<void> {
  ```
- `workflowRespond` ← src/workflow-commands.ts:1286 [EXTRACTED]
  ```
  export async function workflowRespond(runId: string, step: string, choice: string, options: { note?: string; pass?: string; json?: string; driver?: string }): Promise<void> {
  ```
- `workflowRetry` ← src/workflow-commands.ts:1343 [EXTRACTED]
  ```
  export async function workflowRetry(runId: string, step: string): Promise<void> {
  ```
- `workflowCancel` ← src/workflow-commands.ts:1360 [EXTRACTED]
  ```
  export async function workflowCancel(runId: string, step?: string, options: { release?: string } = {}): Promise<void> {
  ```
- `workflowPublish` ← src/workflow-commands.ts:1414 [EXTRACTED]
  ```
  export async function workflowPublish(runId: string, options: { sessions?: boolean } = {}): Promise<void> {
  ```
- `workflowResume` ← src/workflow-commands.ts:1466 [EXTRACTED]
  ```
  export async function workflowResume(runId: string | undefined, options: ResumeOptions): Promise<void> {
  ```
- `benchmarkPlan` ← src/workflow-commands.ts:1973 [EXTRACTED]
  ```
  export async function benchmarkPlan(suite: string, options: { aliases?: string; tasks?: string; arms?: string }): Promise<void> {
  ```
- `benchmarkReport` ← src/workflow-commands.ts:2013 [EXTRACTED]
  ```
  export async function benchmarkReport(): Promise<void> {
  ```
- `benchmarkRun` ← src/workflow-commands.ts:2034 [EXTRACTED]
  ```
  export async function benchmarkRun(suite: string, options: { driver?: string; sandbox?: boolean; memberAliases?: boolean; task?: string[]; arm?: string[]; failOnRegression?: boolean }): Promise<void> {
  ```
- `benchmarkTry` ← src/workflow-commands.ts:2137 [EXTRACTED]
  ```
  export async function benchmarkTry(file: string): Promise<void> {
  ```
- `selfImprovementRun` ← src/workflow-commands.ts:2151 [EXTRACTED]
  ```
  export async function selfImprovementRun(scorer: string, options: { suite: string; driver?: string; tools?: string; sandbox?: boolean }): Promise<void> {
  ```
- `shortcutDriver` ← src/workflow-commands.ts:2198 [EXTRACTED]
  ```
  export async function shortcutDriver(config: LocalConfig, asked: string | undefined): Promise<{ driver?: string; byDefault?: DefaultDrive } | undefined> {
  ```
- `driveRun` ← src/workflow-drive.ts:19 [EXTRACTED]
  ```
  export async function driveRun(config: LocalConfig, run: string, on: DriveOn, { cwd, options }: { cwd: string; options: LocalDriverOptions }): Promise<WorkflowEnvelope> {
  ```
- `definedDrive` ← src/workflow-drive.ts:34 [EXTRACTED]
  ```
  export function definedDrive(opened: OpenedDriver | undefined, tools: Record<string, string>): Pick<LocalDriverOptions, 'tools' | 'runtimes'> {
  ```
- `unsupportedDriver` ← src/workflow-drive.ts:44 [EXTRACTED]
  ```
  export function unsupportedDriver(driver: string): WorkflowFailure {
  ```
- `WorkflowOffers` ← src/workflow-offers.ts:88 [EXTRACTED]
  ```
  export const WorkflowOffers = { proposals, contractInputs, offerable } as const;
  ```
- `PublishedRuns` ← src/workflow-published-runs.ts:386 [EXTRACTED]
  ```
  export const PublishedRuns = { list, candidates, resumable, standing } as const;
  ```
- `readWorkspaceChildren` ← src/workspace-children.ts:83 [EXTRACTED]
  ```
  export async function readWorkspaceChildren(workspace: LocalConfig): Promise<LocalConfig> {
  ```
- `deliveredMembers` ← src/workspace-children.ts:140 [EXTRACTED]
  ```
  export async function deliveredMembers(config: LocalConfig): Promise<readonly LocalConfig[] | null> {
  ```
- `deliveredLearningsNamespaces` ← src/workspace-children.ts:188 [EXTRACTED]
  ```
  export async function deliveredLearningsNamespaces(config: LocalConfig): Promise<string[]> {
  ```
- `selectedProjects` ← src/workspace-children.ts:203 [EXTRACTED]
  ```
  export function selectedProjects(config: LocalConfig): string[] {
  ```
- `formatProjectsManifestWarning` ← src/workspace-children.ts:214 [EXTRACTED]
  ```
  export function formatProjectsManifestWarning(
  ```
- `safeDeliveredLearningsNamespaces` ← src/workspace-children.ts:251 [EXTRACTED]
  ```
  export async function safeDeliveredLearningsNamespaces(
  ```
- `unionMemberItems` ← src/workspace-children.ts:278 [EXTRACTED]
  ```
  export async function unionMemberItems<TItem>(input: {
  ```
- `describeWorkspaceChildren` ← src/workspace-children.ts:306 [EXTRACTED]
  ```
  export function describeWorkspaceChildren(config: LocalConfig): string[] {
  ```
- `summarizeWorkspaceChildren` ← src/workspace-children.ts:325 [EXTRACTED]
  ```
  export function summarizeWorkspaceChildren(config: LocalConfig): string | null {
  ```
- `hasWorkspaceChildren` ← src/workspace-children.ts:337 [EXTRACTED]
  ```
  export function hasWorkspaceChildren(config: Pick<LocalConfig, 'children'>): boolean {
  ```
- `findAncestorWorkspaces` ← src/workspace-children.ts:349 [EXTRACTED]
  ```
  export async function findAncestorWorkspaces(childRoot: string): Promise<string[]> {
  ```
- `ownedInstructionExcludesOf` ← src/workspace-children.ts:366 [EXTRACTED]
  ```
  export function ownedInstructionExcludesOf(recorded: NonNullable<State['lastPullByWorkspace']>[string]['claudeMdExcludes'], claudeSettings: string | undefined): OwnedInstructionExcludes {
  ```
- `syncWorkspaceInstructionExcludes` ← src/workspace-children.ts:388 [EXTRACTED]
  ```
  export async function syncWorkspaceInstructionExcludes(input: {
  ```
- `readMarkdown` ← scripts/doc-checks/read-markdown.ts:4 [EXTRACTED]
  ```
  export function readMarkdown(file: string): string {
  ```
- `probeHostCommand` ← scripts/verify/doctor.ts:20 [EXTRACTED]
  ```
  export function probeHostCommand(argv: readonly string[], { timeoutMs = 20_000 }: { timeoutMs?: number } = {}): { ok: true; first: string; stdout: string } | { ok: false; why: string } {
  ```
- `cheapestListed` ← scripts/verify/doctor.ts:62 [EXTRACTED]
  ```
  export function cheapestListed(catalog: string): string | undefined {
  ```
- `sbxNotSignedIn` ← scripts/verify/doctor.ts:96 [EXTRACTED]
  ```
  export function sbxNotSignedIn(at: string, said: string): string | undefined {
  ```
- `sbxInWorld` ← scripts/verify/doctor.ts:101 [EXTRACTED]
  ```
  export function sbxInWorld(runId: string, ran: { code: number | null; why: string }) {
  ```
- `doctorDrivers` ← scripts/verify/doctor.ts:135 [EXTRACTED]
  ```
  export async function doctorDrivers(line: (good: boolean, text: string) => void, { world }: { world?: World } = {}): Promise<void> {
  ```
- `helpFor` ← scripts/verify/help.ts:137 [EXTRACTED]
  ```
  export function helpFor(topic: string | undefined): string {
  ```
- `toolInstancesIn` ← scripts/verify/instances.ts:26 [EXTRACTED]
  ```
  export async function toolInstancesIn(home: string): Promise<DeclaredTool[]> {
  ```
- `installConfigs` ← scripts/verify/instances.ts:46 [EXTRACTED]
  ```
  export function installConfigs(home: string): unknown[] {
  ```
- `installInstances` ← scripts/verify/instances.ts:100 [EXTRACTED]
  ```
  export async function installInstances(home: string, { env, cwd }: { env: Readonly<Record<string, string>>; cwd: string }): Promise<InstallInstance[]> {
  ```
- `recordInstallInstances` ← scripts/verify/instances.ts:115 [EXTRACTED]
  ```
  export function recordInstallInstances(world: Pick<World, 'dir'>, home: string, seen: readonly InstallInstance[]): void {
  ```
- `recordedInstallInstances` ← scripts/verify/instances.ts:127 [EXTRACTED]
  ```
  export function recordedInstallInstances(world: Pick<World, 'dir'>, home: string): InstallInstance[] {
  ```
- `judgedInstances` ← scripts/verify/instances.ts:137 [EXTRACTED]
  ```
  export function judgedInstances(seen: readonly InstallInstance[]): DeclaredTool[] {
  ```
- `namingWorld` ← scripts/verify/ledger.ts:101 [EXTRACTED]
  ```
  export function namingWorld(dir: string, world: Pick<World, 'runId' | 'dir'>, since: number, found: string[], unreadable: string[], depth = 0): void {
  ```
- `hostUnreadableNote` ← scripts/verify/ledger.ts:169 [EXTRACTED]
  ```
  export function hostUnreadableNote(file: string, since: number): string {
  ```
- `hostHomes` ← scripts/verify/ledger.ts:219 [EXTRACTED]
  ```
  export function hostHomes(world: Pick<World, 'dir'>, instances: readonly DeclaredTool[]): string[] {
  ```
- `environmentNotes` ← scripts/verify/ledger.ts:227 [EXTRACTED]
  ```
  export function environmentNotes(world: Pick<World, 'bin' | 'members'>): string[] {
  ```
- `ledgerRules` ← scripts/verify/ledger.ts:490 [EXTRACTED]
  ```
  export function ledgerRules(instances: readonly DeclaredTool[], moved: readonly ShippedHome[] = []): LedgerRules {
  ```
- `unobservedEntries` ← scripts/verify/ledger.ts:582 [EXTRACTED]
  ```
  export function unobservedEntries(before: Readonly<Record<string, string>>, after: Readonly<Record<string, string>>) {
  ```
- `uninstallChanges` ← scripts/verify/ledger.ts:639 [EXTRACTED]
  ```
  export function uninstallChanges({ place, before, after, writers, repository, rules }: {
  ```
- `ledgerVerdict` ← scripts/verify/ledger.ts:785 [EXTRACTED]
  ```
  export function ledgerVerdict(sections: readonly Section[]): string {
  ```
- `runLedger` ← scripts/verify/ledger.ts:798 [EXTRACTED]
  ```
  export async function runLedger(world: World): Promise<{ verdict: string; leaks: number }> {
  ```
- `attributeLeftover` ← scripts/verify/leftovers.ts:57 [EXTRACTED]
  ```
  export function attributeLeftover(ties: Ties, self: WorldTies, others: readonly WorldTies[]): Attribution {
  ```
- `worldTier` ← scripts/verify/leftovers.ts:82 [EXTRACTED]
  ```
  export function worldTier(evidence: TierEvidence): Tier {
  ```
- `probeHere` ← scripts/verify/leftovers.ts:131 [EXTRACTED]
  ```
  export function probeHere(argv: readonly string[], { timeoutMs = 30_000 }: { timeoutMs?: number } = {}): { kind: 'missing' } | { kind: 'ran'; code: number | null; stdout: string; stderr: string; why: string } {
  ```
- `linesOf` ← scripts/verify/leftovers.ts:246 [EXTRACTED]
  ```
  export function linesOf(title: string, observed: readonly Observed[], mask: (text: string) => string) {
  ```
- `tiesOnThisMachine` ← scripts/verify/leftovers.ts:322 [EXTRACTED]
  ```
  export async function tiesOnThisMachine(world: World | undefined): Promise<{ self: WorldTies | undefined; others: WorldTies[] }> {
  ```
- `leftoversSection` ← scripts/verify/leftovers.ts:336 [EXTRACTED]
  ```
  export async function leftoversSection(world: World): Promise<{ observe(): Promise<{ leaks: string[]; notes: string[] }> }> {
  ```
- `removeLeftover` ← scripts/verify/leftovers.ts:370 [EXTRACTED]
  ```
  export function removeLeftover({ command, gone }: { command: readonly string[]; gone?: RegExp }): { ok: true; wasThere: boolean } | { ok: false; why: string } {
  ```
- `cleanupPlan` ← scripts/verify/leftovers.ts:380 [EXTRACTED]
  ```
  export function cleanupPlan(rows: ReadonlyArray<{ onCleanup: CleanupRule; observed: readonly Observed[] }>): CleanupPlan {
  ```
- `planCleanup` ← scripts/verify/leftovers.ts:419 [EXTRACTED]
  ```
  export async function planCleanup(world: World): Promise<CleanupPlan> {
  ```
- `MEMBER_NAME` ← scripts/verify/members.ts:13 [EXTRACTED]
  ```
  export const MEMBER_NAME = /^[a-z][a-z0-9-]{0,11}$/;
  ```
- `ORIGIN_URL` ← scripts/verify/members.ts:16 [EXTRACTED]
  ```
  export const ORIGIN_URL = 'https://teamai.test/world/project.git';
  ```
- `parseMachine` ← scripts/verify/members.ts:19 [EXTRACTED]
  ```
  export function parseMachine(flags: readonly string[]): 'host' | 'container' {
  ```
- `memberLayout` ← scripts/verify/members.ts:32 [EXTRACTED]
  ```
  export function memberLayout(world: Pick<World, 'dir' | 'runId'>, { name, tmpRoot }: { name: string; tmpRoot: string }) {
  ```
- `setupBaseline` ← scripts/verify/members.ts:45 [EXTRACTED]
  ```
  export function setupBaseline(baseline: Readonly<Record<string, string>>, before: Readonly<Record<string, string>>, after: Readonly<Record<string, string>>) {
  ```
- `ensureOrigin` ← scripts/verify/members.ts:71 [EXTRACTED]
  ```
  export function ensureOrigin(world: World): World {
  ```
- `removeMachines` ← scripts/verify/members.ts:127 [EXTRACTED]
  ```
  export function removeMachines(world: Pick<World, 'runId' | 'members'>): { ok: true; removed: string[] } | { ok: false; why: string } {
  ```
- `machineName` ← scripts/verify/members.ts:163 [EXTRACTED]
  ```
  export function machineName(world: Pick<World, 'runId'>, name: string): string {
  ```
- `addMember` ← scripts/verify/members.ts:171 [EXTRACTED]
  ```
  export function addMember(world: World, { name, machine = 'host' }: { name: string; machine?: 'host' | 'container' }): World {
  ```
- `parseReapArgs` ← scripts/verify/reap.ts:16 [EXTRACTED]
  ```
  export function parseReapArgs(args: readonly string[]): { ok: true; run: string | undefined; isDeleting: boolean; named: string[] } | { ok: false; message: string } {
  ```
- `vercelSignIn` ← scripts/verify/reap.ts:33 [EXTRACTED]
  ```
  export function vercelSignIn(env: NodeJS.ProcessEnv): { ok: true; credentials: { token?: string; teamId?: string; projectId?: string } } | { ok: false; missing: string } {
  ```
- `judgeRemote` ← scripts/verify/reap.ts:53 [EXTRACTED]
  ```
  export function judgeRemote({ listed, self, others, named }: { listed: unknown; self: WorldTies | undefined; others: readonly WorldTies[]; named: readonly string[] }) {
  ```
- `reap` ← scripts/verify/reap.ts:67 [EXTRACTED]
  ```
  export async function reap(args: readonly string[], loadWorld: (run: string) => World): Promise<number> {
  ```
- `reportRemote` ← scripts/verify/reap.ts:110 [EXTRACTED]
  ```
  export function reportRemote(found: ReturnType<typeof judgeRemote>) {
  ```
- `splitPassOption` ← scripts/verify/secrets.ts:11 [EXTRACTED]
  ```
  export function splitPassOption(argv: readonly string[]) {
  ```
- `passedKeys` ← scripts/verify/secrets.ts:19 [EXTRACTED]
  ```
  export function passedKeys(names: readonly string[], env: NodeJS.ProcessEnv): { ok: true; keys: Map<string, string> } | { ok: false; missing: string[] } {
  ```
- `worldRedactor` ← scripts/verify/secrets.ts:28 [EXTRACTED]
  ```
  export function worldRedactor({ passed, harnessEnv }: { passed: ReadonlyMap<string, string>; harnessEnv: NodeJS.ProcessEnv }): (text: string) => string {
  ```
- `ledgerRedactor` ← scripts/verify/secrets.ts:39 [EXTRACTED]
  ```
  export function ledgerRedactor({ passedNames, harnessEnv }: { passedNames: readonly string[]; harnessEnv: NodeJS.ProcessEnv }) {
  ```
- `lineRedactor` ← scripts/verify/secrets.ts:46 [EXTRACTED]
  ```
  export function lineRedactor(mask: (text: string) => string) {
  ```
- `parseEnviron` ← scripts/verify/secrets.ts:67 [EXTRACTED]
  ```
  export function parseEnviron(text: string): Map<string, string> {
  ```
- `declaredCredentialNames` ← scripts/verify/secrets.ts:79 [EXTRACTED]
  ```
  export function declaredCredentialNames(document: JsonValue): string[] {
  ```
- `judgeSandboxEnv` ← scripts/verify/secrets.ts:102 [EXTRACTED]
  ```
  export function judgeSandboxEnv({ env, canary, secrets, declared }: { env: ReadonlyMap<string, string>; canary: string; secrets: ReadonlyMap<string, string>; declared: ReadonlySet<string> }): EnvVerdict {
  ```
- `movedShippedHomes` ← scripts/verify/shipped-homes.ts:37 [EXTRACTED]
  ```
  export function movedShippedHomes(home: string, { env, cwd }: { env: Readonly<Record<string, string>>; cwd: string }): ShippedHome[] {
  ```
- `recordShippedHomes` ← scripts/verify/shipped-homes.ts:67 [EXTRACTED]
  ```
  export function recordShippedHomes(world: Pick<World, 'dir'>, home: string, seen: readonly ShippedHome[]): void {
  ```
- `recordedShippedHomes` ← scripts/verify/shipped-homes.ts:79 [EXTRACTED]
  ```
  export function recordedShippedHomes(world: Pick<World, 'dir'>, home: string): ShippedHome[] {
  ```
- `parseTarget` ← scripts/verify/target.ts:19 [EXTRACTED]
  ```
  export function parseTarget(arg: string | undefined) {
  ```
- `memberOf` ← scripts/verify/target.ts:37 [EXTRACTED]
  ```
  export function memberOf(world: World, name: string): Member {
  ```
- `containerCommand` ← scripts/verify/target.ts:76 [EXTRACTED]
  ```
  export function containerCommand({ container, env, pass, cwd, argv, harnessEnv }: { container: string; env: Readonly<Record<string, string>>; pass: ReadonlyMap<string, string>; cwd: string; argv: readonly string[]; harnessEnv: NodeJS.ProcessEnv }) {
  ```
- `runOn` ← scripts/verify/target.ts:114 [EXTRACTED]
  ```
  export async function runOn(world: World, target: Target, argv: readonly string[], { pass }: { pass: ReadonlyMap<string, string> }): Promise<{ exit: number; log: string }> {
  ```
- `watchSandboxes` ← scripts/verify/target.ts:213 [EXTRACTED]
  ```
  export function watchSandboxes(world: Pick<World, 'home' | 'members'>, { start }: { start: () => Promise<{ stop(): Promise<string[]> }> }) {
  ```
- `captureOn` ← scripts/verify/target.ts:242 [EXTRACTED]
  ```
  export function captureOn(world: World, target: Target, argv: readonly string[], { timeoutMs = 30_000 }: { timeoutMs?: number } = {}) {
  ```
- `machinesOf` ← scripts/verify/target.ts:252 [EXTRACTED]
  ```
  export function machinesOf(world: World): Array<{ label: string; target: Target; platform: NodeJS.Platform }> {
  ```
- `hostInstalls` ← scripts/verify/target.ts:265 [EXTRACTED]
  ```
  export function hostInstalls(world: World) {
  ```
- `REPO_ROOT` ← scripts/verify/world.ts:17 [EXTRACTED]
  ```
  export const REPO_ROOT = path.resolve(path.dirname(fileURLToPath(import.meta.url)), '..', '..');
  ```
- `WORLDS_ROOT` ← scripts/verify/world.ts:18 [EXTRACTED]
  ```
  export const WORLDS_ROOT = path.join(os.tmpdir(), 'teamai-verify');
  ```
- `TEAM_URL` ← scripts/verify/world.ts:21 [EXTRACTED]
  ```
  export const TEAM_URL = 'https://teamai.test/team/repo.git';
  ```
- `UNREADABLE` ← scripts/verify/world.ts:100 [EXTRACTED]
  ```
  export const UNREADABLE = 'unreadable';
  ```
- `GONE` ← scripts/verify/world.ts:115 [EXTRACTED]
  ```
  export const GONE = Symbol('gone');
  ```
- `present` ← scripts/verify/world.ts:118 [EXTRACTED]
  ```
  export function present<T>(read: () => T): T | typeof GONE {
  ```
- `worldFiles` ← scripts/verify/world.ts:132 [EXTRACTED]
  ```
  export function worldFiles(world: Pick<World, 'home' | 'project'>) {
  ```
- `gitconfigText` ← scripts/verify/world.ts:174 [EXTRACTED]
  ```
  export function gitconfigText({ name, email, urls }: { name: string; email: string; urls: ReadonlyArray<{ repo: string; url: string }> }): string {
  ```
- `git` ← scripts/verify/world.ts:180 [EXTRACTED]
  ```
  export function git(cwd: string, ...args: string[]): string {
  ```
- `checkoutStatus` ← scripts/verify/world.ts:184 [EXTRACTED]
  ```
  export function checkoutStatus(): string[] {
  ```
- `teamRefs` ← scripts/verify/world.ts:188 [EXTRACTED]
  ```
  export function teamRefs(team: string) {
  ```
- `quote` ← scripts/verify/world.ts:202 [EXTRACTED]
  ```
  export const quote = (value: string): string => `'${value.replace(/'/g, `'\\''`)}'`;
  ```
- `TOOL_COMMANDS` ← scripts/verify/world.ts:204 [EXTRACTED]
  ```
  export const TOOL_COMMANDS = ['claude', 'codex', 'codebuddy', 'opencode'] as const;
  ```
- `runtimeHostCommands` ← scripts/verify/world.ts:216 [EXTRACTED]
  ```
  export async function runtimeHostCommands({ root = REPO_ROOT }: { root?: string } = {}): Promise<Array<{ runtime: string; commands: readonly string[] }>> {
  ```
- `worldCommandNames` ← scripts/verify/world.ts:232 [EXTRACTED]
  ```
  export async function worldCommandNames({ root }: { root?: string } = {}): Promise<string[]> {
  ```
- `worldTmpDir` ← scripts/verify/world.ts:240 [EXTRACTED]
  ```
  export function worldTmpDir({ root, runId, member }: { root: string; runId: string; member?: string | undefined }): string {
  ```
- `shortTmpRoot` ← scripts/verify/world.ts:245 [EXTRACTED]
  ```
  export function shortTmpRoot(): string {
  ```
- `hostCommand` ← scripts/verify/world.ts:254 [EXTRACTED]
  ```
  export function hostCommand(name: string): string | undefined {
  ```
- `runProbe` ← scripts/verify/world.ts:278 [EXTRACTED]
  ```
  export function runProbe({ command, args, shown = [command, ...args], cwd, env, timeoutMs, maxBuffer = 64 * 1024 ** 2 }: { command: string; args: readonly string[]; shown?: readonly string[]; cwd: string; env?: NodeJS.ProcessEnv; timeoutMs: number; maxBuffer?: number }): Probed {
  ```
- `worldHomes` ← scripts/verify/world.ts:306 [EXTRACTED]
  ```
  export function worldHomes(world: { home: string; members?: ReadonlyArray<{ home: string }> | undefined }): string[] {
  ```
- `runtimeStateDirs` ← scripts/verify/world.ts:311 [EXTRACTED]
  ```
  export function runtimeStateDirs(world: Pick<World, 'home' | 'members'>): string[] {
  ```
- `CANARY_NAME` ← scripts/verify/world.ts:316 [EXTRACTED]
  ```
  export const CANARY_NAME = 'VERIFY_WORLD_CANARY';
  ```
- `worldEnv` ← scripts/verify/world.ts:319 [EXTRACTED]
  ```
  export function worldEnv({ home, tmp, bin, fakes, tools, npmCache }: { home: string; tmp: string; bin: string; fakes: string; tools: string; npmCache: string }) {
  ```
- `createWorld` ← scripts/verify/world.ts:361 [EXTRACTED]
  ```
  export async function createWorld(): Promise<World> {
  ```
- `packCheckout` ← scripts/verify/world.ts:382 [EXTRACTED]
  ```
  export function packCheckout({ into }: { into: string }) {
  ```
- `updateWorld` ← scripts/verify/world.ts:501 [EXTRACTED]
  ```
  export function updateWorld(world: Pick<World, 'dir'>, change: (fresh: World) => World): World {
  ```
- `rewriteLocked` ← scripts/verify/world.ts:514 [EXTRACTED]
  ```
  export function rewriteLocked<T>(file: string, rewrite: (text: string | undefined) => { value: T; text: string }, { waitMs = 30_000 }: { waitMs?: number } = {}): T {
  ```
- `refuseCleaned` ← scripts/verify/world.ts:582 [EXTRACTED]
  ```
  export function refuseCleaned(world: Pick<World, 'runId' | 'cleanedAt'>): void {
  ```
- `markDriverSeen` ← scripts/verify/world.ts:587 [EXTRACTED]
  ```
  export function markDriverSeen(world: Pick<World, 'runId' | 'driverSeen'>): void {
  ```
- `tmpDirsOutside` ← scripts/verify/world.ts:593 [EXTRACTED]
  ```
  export function tmpDirsOutside(world: Pick<World, 'dir' | 'tmp' | 'members'>) {
  ```
- `loadWorld` ← scripts/verify/world.ts:601 [EXTRACTED]
  ```
  export function loadWorld(runId: string | undefined): World {
  ```
- `liveWorlds` ← scripts/verify/world.ts:648 [EXTRACTED]
  ```
  export function liveWorlds() {
  ```
- `worldWritersFile` ← scripts/verify/world.ts:695 [EXTRACTED]
  ```
  export function worldWritersFile(world: Pick<World, 'dir'>): string {
  ```
- `loadWriters` ← scripts/verify/world.ts:700 [EXTRACTED]
  ```
  export function loadWriters(file: string): Writers {
  ```
- `recordWriters` ← scripts/verify/world.ts:705 [EXTRACTED]
  ```
  export function recordWriters(file: string, args: readonly string[], before: Record<string, string>, after: Record<string, string>): void {
  ```
- `writeCommandLog` ← scripts/verify/world.ts:722 [EXTRACTED]
  ```
  export function writeCommandLog(world: Pick<World, 'logs'>, args: readonly string[], output: string, status: number | null): string {
  ```
- `runInWorld` ← scripts/verify/world.ts:745 [EXTRACTED]
  ```
  export function runInWorld(world: World, args: readonly string[]): number {
  ```
- `COMPARISONS` ← src/benchmark/agent-match.ts:12 [EXTRACTED]
  ```
  export const COMPARISONS = ['match', 'deviation', 'not_verified'] as const;
  ```
- `compareAgent` ← src/benchmark/agent-match.ts:22 [EXTRACTED]
  ```
  export function compareAgent(arm: Pick<BenchmarkRecord['arms'][number], 'tool' | 'model' | 'team' | 'role'>, observed: AgentObservation): Comparison {
  ```
- `compareJudge` ← src/benchmark/agent-match.ts:46 [EXTRACTED]
  ```
  export function compareJudge(planned: PlannedJudge, judge: Extract<ScoreLabel['judge'], { kind: 'model' }>): Comparison {
  ```
- `pinArmWorkflow` ← src/benchmark/arm-workflow.ts:43 [EXTRACTED]
  ```
  export async function pinArmWorkflow(
  ```
- `isMixedTask` ← src/benchmark/calibration.ts:15 [EXTRACTED]
  ```
  export function isMixedTask(task: PlannedTask): boolean {
  ```
- `isCalibrationCandidate` ← src/benchmark/calibration.ts:20 [EXTRACTED]
  ```
  export function isCalibrationCandidate(task: PlannedTask, output: CheckOutput | undefined): boolean {
  ```
- `isCalibrationSampled` ← src/benchmark/calibration.ts:28 [EXTRACTED]
  ```
  export function isCalibrationSampled({ runId, step }: { runId: string; step: string }, rate: number): boolean {
  ```
- `calibrationSubjects` ← src/benchmark/calibration.ts:42 [EXTRACTED]
  ```
  export function calibrationSubjects(run: RunState, { plan, prefix }: RunPlan, within?: string): CalibrationSubject[] {
  ```
- `judgeCallsOf` ← src/benchmark/estimate.ts:30 [EXTRACTED]
  ```
  export function judgeCallsOf({ trials, tasks, judges, definitions, calibrationRate, batch }: {
  ```
- `estimateOf` ← src/benchmark/estimate.ts:54 [EXTRACTED]
  ```
  export function estimateOf({ plan, calls, earlier }: { plan: Pick<BenchmarkPlan, 'suite' | 'arms' | 'trials'>; calls: JudgeCalls; earlier: readonly BenchmarkRunInput[] }): BenchmarkEstimate {
  ```
- `formatEstimate` ← src/benchmark/estimate.ts:123 [EXTRACTED]
  ```
  export function formatEstimate(estimate: BenchmarkEstimate, { suite, arms, tasks, repetitions }: { suite: string; arms: number; tasks: number; repetitions: number }): string[] {
  ```
- `BENCHMARK_WINDOWS` ← src/benchmark/history.ts:54 [EXTRACTED]
  ```
  export const BENCHMARK_WINDOWS = [30, 90, 365] as const;
  ```
- `ARM_DIMENSIONS` ← src/benchmark/history.ts:138 [EXTRACTED]
  ```
  export const ARM_DIMENSIONS = ['team', 'tool', 'model', 'workflow', 'role'] as const;
  ```
- `armKey` ← src/benchmark/history.ts:327 [EXTRACTED]
  ```
  export function armKey({ name, tool, model, effort, team, workflow, role }: Pick<Arm, 'name' | 'tool' | 'model' | 'effort' | 'team' | 'workflow' | 'role'>): string {
  ```
- `regressionOf` ← src/benchmark/history.ts:816 [EXTRACTED]
  ```
  export function regressionOf(current: BenchmarkRunInput, earlier: readonly BenchmarkRunInput[]): Regression {
  ```
- `formatRegression` ← src/benchmark/history.ts:853 [EXTRACTED]
  ```
  export function formatRegression(regression: Regression, suite: string): string[] {
  ```
- `runComparisons` ← src/benchmark/history.ts:881 [EXTRACTED]
  ```
  export function runComparisons(input: BenchmarkRunInput): ArmComparison[] {
  ```
- `BenchmarkHistory` ← src/benchmark/history.ts:885 [EXTRACTED]
  ```
  export const BenchmarkHistory = {
  ```
- `comparePair` ← src/benchmark/pairing.ts:41 [EXTRACTED]
  ```
  export function comparePair(from: PairSide, to: PairSide): PairComparison {
  ```
- `compareTrials` ← src/benchmark/pairing.ts:58 [EXTRACTED]
  ```
  export function compareTrials({ from, fromTasks, to, toTasks }: { from: Trial; fromTasks: BenchmarkRecord['tasks']; to: Trial; toTasks: BenchmarkRecord['tasks'] }): PairComparison | undefined {
  ```
- `splitPairs` ← src/benchmark/pairing.ts:74 [EXTRACTED]
  ```
  export function splitPairs<TPair>(pairs: ReadonlyArray<{ pair: TPair; comparison: PairComparison }>) {
  ```
- `formatExcluded` ← src/benchmark/pairing.ts:96 [EXTRACTED]
  ```
  export function formatExcluded(excluded: readonly ExcludedPairs[]): string {
  ```
- `BenchmarkEstimateSchema` ← src/benchmark/plan.ts:107 [EXTRACTED]
  ```
  export const BenchmarkEstimateSchema = z.object({
  ```
- `PlannedJudgeSchema` ← src/benchmark/plan.ts:155 [EXTRACTED]
  ```
  export const PlannedJudgeSchema = z.object({ tool: z.string().min(1), model: z.string() }).strict();
  ```
- `BENCHMARK_PLAN_SCHEMA_VERSION` ← src/benchmark/plan.ts:163 [EXTRACTED]
  ```
  export const BENCHMARK_PLAN_SCHEMA_VERSION = 3;
  ```
- `BenchmarkPlanSchema` ← src/benchmark/plan.ts:171 [EXTRACTED]
  ```
  export const BenchmarkPlanSchema = z.object({
  ```
- `trialsOf` ← src/benchmark/plan.ts:206 [EXTRACTED]
  ```
  export function trialsOf(tasks: readonly Pick<Task, 'id'>[], arms: readonly Pick<PlannedArm, 'name' | 'workflow'>[], repetitions: number, parallel = 1): PlannedTrial[] {
  ```
- `checkStepOf` ← src/benchmark/plan.ts:235 [EXTRACTED]
  ```
  export function checkStepOf({ step }: Pick<PlannedTrial, 'step'>): string {
  ```
- `baselineStepOf` ← src/benchmark/plan.ts:240 [EXTRACTED]
  ```
  export function baselineStepOf(task: string): string {
  ```
- `freezePlan` ← src/benchmark/plan.ts:249 [EXTRACTED]
  ```
  export function freezePlan(input: {
  ```
- `runSourceHash` ← src/benchmark/plan.ts:326 [EXTRACTED]
  ```
  export function runSourceHash({ suite, tasks }: { suite: Pick<BenchmarkPlan['suite'], 'sourceHash'>; tasks: ReadonlyArray<Pick<BenchmarkPlan['tasks'][number], 'id' | 'sourceHash'>> }): string {
  ```
- `compileBundle` ← src/benchmark/plan.ts:376 [EXTRACTED]
  ```
  export function compileBundle(
  ```
- `addedOf` ← src/benchmark/plan.ts:510 [EXTRACTED]
  ```
  export function addedOf(check: TaskCheck, checkFiles: Added | undefined): Added[] {
  ```
- `trialScorersOf` ← src/benchmark/plan.ts:542 [EXTRACTED]
  ```
  export function trialScorersOf(suite: Pick<Suite, 'scorers'>, task: Pick<Task, 'id' | 'scorers' | 'judge'>): string[] {
  ```
- `correctnessScorerName` ← src/benchmark/plan.ts:551 [EXTRACTED]
  ```
  export function correctnessScorerName(task: string): string {
  ```
- `CORRECTNESS_SCORERS` ← src/benchmark/plan.ts:556 [EXTRACTED]
  ```
  export const CORRECTNESS_SCORERS = 'teamai:correctness';
  ```
- `isCorrectnessScorer` ← src/benchmark/plan.ts:561 [EXTRACTED]
  ```
  export function isCorrectnessScorer(scorer: string): boolean {
  ```
- `reportBenchmark` ← src/benchmark/report.ts:49 [EXTRACTED]
  ```
  export async function reportBenchmark(env: NodeJS.ProcessEnv, secrets: Record<string, string>): Promise<{ report: BenchmarkReport } | { failure: WorkflowFailure }> {
  ```
- `TRIAL_RESULTS` ← src/benchmark/result.ts:29 [EXTRACTED]
  ```
  export const TRIAL_RESULTS = ['passed', 'failed', 'error', 'unscored', 'not_run'] as const;
  ```
- `BENCHMARK_RECORD_SCHEMA_VERSION` ← src/benchmark/result.ts:42 [EXTRACTED]
  ```
  export const BENCHMARK_RECORD_SCHEMA_VERSION = 2;
  ```
- `BenchmarkRecordSchema` ← src/benchmark/result.ts:53 [EXTRACTED]
  ```
  export const BenchmarkRecordSchema = z.object({
  ```
- `BenchmarkRunRecordSchema` ← src/benchmark/result.ts:141 [EXTRACTED]
  ```
  export const BenchmarkRunRecordSchema = BenchmarkRecordSchema.extend({
  ```
- `benchmarkRecordFile` ← src/benchmark/result.ts:158 [EXTRACTED]
  ```
  export function benchmarkRecordFile(runsRoot: string, run: string): string {
  ```
- `benchmarkRecord` ← src/benchmark/result.ts:167 [EXTRACTED]
  ```
  export function benchmarkRecord(run: RunState, { plan, prefix }: RunPlan, verdicts: readonly EntryVerdict[], calibrations: readonly EntryCalibration[] = []): BenchmarkRecord {
  ```
- `uncheckedChecks` ← src/benchmark/result.ts:429 [EXTRACTED]
  ```
  export function uncheckedChecks(run: RunState, { plan, prefix }: RunPlan): string[] {
  ```
- `unmeasuredTrials` ← src/benchmark/result.ts:472 [EXTRACTED]
  ```
  export function unmeasuredTrials(run: RunState, trials: BenchmarkRecord['trials']): string[] {
  ```
- `unlaunchedTrial` ← src/benchmark/result.ts:499 [EXTRACTED]
  ```
  export function unlaunchedTrial(run: RunState, step: string): boolean {
  ```
- `trialsUnattended` ← src/benchmark/run-plan.ts:23 [EXTRACTED]
  ```
  export function trialsUnattended(run: RunState, producer: string): boolean {
  ```
- `planOfRun` ← src/benchmark/run-plan.ts:42 [EXTRACTED]
  ```
  export function planOfRun(run: RunState, under?: string): { found: RunPlan } | { failure: WorkflowFailure } {
  ```
- `plannedJudgesOf` ← src/benchmark/run-plan.ts:86 [EXTRACTED]
  ```
  export function plannedJudgesOf(run: RunState, step: string): BenchmarkPlan['judges'] {
  ```
- `planBenchmark` ← src/benchmark/start.ts:80 [EXTRACTED]
  ```
  export async function planBenchmark(config: LocalConfig, name: string, options: BenchmarkStart): Promise<{ planned: BenchmarkPlanned; generated: CompiledBundle['scorers']; timeoutMs: number } | { refused: Refusal }> {
  ```
- `planStep` ← src/benchmark/start.ts:130 [EXTRACTED]
  ```
  export async function planStep(name: string, env: NodeJS.ProcessEnv, { memberAliases, chosen }: Pick<BenchmarkStart, 'memberAliases' | 'chosen'>): Promise<{ planned: BenchmarkPlanned } | { failure: WorkflowFailure }> {
  ```
- `tryBenchmarkTask` ← src/benchmark/start.ts:664 [EXTRACTED]
  ```
  export async function tryBenchmarkTask(file: string, options: { checkout: string; signal?: AbortSignal; progress: (line: string) => void }): Promise<WorkflowEnvelope> {
  ```
- `syncTeamDefinitions` ← src/benchmark/suite-cache.ts:38 [EXTRACTED]
  ```
  export async function syncTeamDefinitions(config: LocalConfig, options: SyncScorerOptions = {}): Promise<SyncTeamResult> {
  ```
- `readSuiteFiles` ← src/benchmark/suite-cache.ts:59 [EXTRACTED]
  ```
  export async function readSuiteFiles(dir: string, relativeDir: string, tasks: readonly SourceFile[]): Promise<SuiteFile[]> {
  ```
- `loadCachedSuite` ← src/benchmark/suite-cache.ts:103 [EXTRACTED]
  ```
  export async function loadCachedSuite(config: LocalConfig, name: string): Promise<Suite | null> {
  ```
- `listCachedSuites` ← src/benchmark/suite-cache.ts:125 [EXTRACTED]
  ```
  export async function listCachedSuites(config: LocalConfig): Promise<Suite[]> {
  ```
- `suiteDirectories` ← src/benchmark/suite-cache.ts:156 [EXTRACTED]
  ```
  export async function suiteDirectories(config: LocalConfig): Promise<string[]> {
  ```
- `TaskSourceSchema` ← src/benchmark/suite.ts:349 [EXTRACTED]
  ```
  export const TaskSourceSchema = z.union([SessionSubjectSchema.strict(), RunSubjectSchema.strict()], {
  ```
- `taskSourceOf` ← src/benchmark/suite.ts:358 [EXTRACTED]
  ```
  export function taskSourceOf(text: string): TaskSource | undefined {
  ```
- `TaskJudge` ← src/benchmark/suite.ts:517 [EXTRACTED]
  ```
  export const TaskJudge = {
  ```
- `parseSuite` ← src/benchmark/suite.ts:606 [EXTRACTED]
  ```
  export function parseSuite(input: { suite: SourceFile; tasks: readonly SourceFile[]; files?: readonly SuiteFile[]; isAlias?: (model: string) => boolean }): SuiteParse {
  ```
- `defaultsArmOf` ← src/benchmark/suite.ts:694 [EXTRACTED]
  ```
  export function defaultsArmOf({ defaults, arms }: Pick<Suite, 'defaults' | 'arms'>): Arm | undefined {
  ```
- `checkFilesNamed` ← src/benchmark/suite.ts:702 [EXTRACTED]
  ```
  export function checkFilesNamed(tasks: readonly SourceFile[]): string[] {
  ```
- `observedTrials` ← src/benchmark/table.ts:215 [EXTRACTED]
  ```
  export function observedTrials(record: BenchmarkTableInput): ObservedTrial[] {
  ```
- `usageOf` ← src/benchmark/table.ts:223 [EXTRACTED]
  ```
  export function usageOf(trials: readonly ObservedTrial[]): Omit<ArmUsage, 'arm'> {
  ```
- `agentCostsOf` ← src/benchmark/table.ts:235 [EXTRACTED]
  ```
  export function agentCostsOf(trials: readonly ObservedTrial[]): Array<RecordedTrial['cost']> {
  ```
- `deviationsOf` ← src/benchmark/table.ts:261 [EXTRACTED]
  ```
  export function deviationsOf(arm: RecordedArm, trials: readonly ObservedTrial[]): Pick<ArmResults, 'deviations' | 'notVerified'> {
  ```
- `benchmarkTable` ← src/benchmark/table.ts:275 [EXTRACTED]
  ```
  export function benchmarkTable(record: BenchmarkTableInput): BenchmarkTable {
  ```
- `dominanceOf` ← src/benchmark/table.ts:368 [EXTRACTED]
  ```
  export function dominanceOf({ mine, theirs }: { mine: ArmStanding; theirs: ArmStanding }): Dominance | undefined {
  ```
- `calibrationOf` ← src/benchmark/table.ts:408 [EXTRACTED]
  ```
  export function calibrationOf(trials: readonly RecordedTrial[]): JudgeCalibration[] {
  ```
- `selfJudgedOf` ← src/benchmark/table.ts:441 [EXTRACTED]
  ```
  export function selfJudgedOf({ arms, judges = {} }: BenchmarkRecord): BenchmarkTable['selfJudged'] {
  ```
- `benchmarkCells` ← src/benchmark/table.ts:462 [EXTRACTED]
  ```
  export function benchmarkCells(table: BenchmarkTable): BenchmarkCells {
  ```
- `formatResourceEffect` ← src/benchmark/table.ts:562 [EXTRACTED]
  ```
  export function formatResourceEffect(effect: ResourceEffect): string {
  ```
- `formatBenchmarkTable` ← src/benchmark/table.ts:615 [EXTRACTED]
  ```
  export function formatBenchmarkTable(table: BenchmarkTable): string {
  ```
- `costTotal` ← src/benchmark/table.ts:670 [EXTRACTED]
  ```
  export function costTotal(parts: ReadonlyArray<RecordedTrial['cost']>): CostTotal {
  ```
- `formatEstimateAmount` ← src/benchmark/table.ts:694 [EXTRACTED]
  ```
  export function formatEstimateAmount(value: number): string {
  ```
- `formatCostRange` ← src/benchmark/table.ts:699 [EXTRACTED]
  ```
  export function formatCostRange({ low, high, unit }: Pick<CostRange, 'low' | 'high' | 'unit'>): string {
  ```
- `wilson` ← src/benchmark/table.ts:730 [EXTRACTED]
  ```
  export function wilson({ passed, planned }: PassRate) {
  ```
- `pairedDifference` ← src/benchmark/table.ts:751 [EXTRACTED]
  ```
  export function pairedDifference({ both, toOnly, fromOnly, neither }: { both: number; toOnly: number; fromOnly: number; neither: number }): PairedInterval {
  ```
- `ROUTING_VALUES` ← src/benchmark/table.ts:770 [EXTRACTED]
  ```
  export const ROUTING_VALUES = ['fit', 'idle', 'extra', 'missed', 'unknown'] as const;
  ```
- `resourceEffects` ← src/benchmark/table.ts:827 [EXTRACTED]
  ```
  export function resourceEffects(record: BenchmarkTableInput): ResourceEffect[] {
  ```
- `withoutRefusal` ← src/benchmark/team-without.ts:54 [EXTRACTED]
  ```
  export async function withoutRefusal(
  ```
- `teamFilesAt` ← src/benchmark/team-without.ts:92 [EXTRACTED]
  ```
  export async function teamFilesAt(
  ```
- `coveredSkillName` ← src/benchmark/team-without.ts:112 [EXTRACTED]
  ```
  export function coveredSkillName(listed: string, files: readonly string[]): string | undefined {
  ```
- `skillDefinitionOf` ← src/benchmark/team-without.ts:119 [EXTRACTED]
  ```
  export function skillDefinitionOf(skill: string): string {
  ```
- `armSources` ← src/benchmark/team-without.ts:133 [EXTRACTED]
  ```
  export function armSources(planned: readonly CoveringArm[], pulled: string): Array<{ source: ArmSource; arms: string[] }> {
  ```
- `coveredDelivery` ← src/benchmark/team-without.ts:168 [EXTRACTED]
  ```
  export async function coveredDelivery(
  ```
- `leavesOut` ← src/benchmark/team-without.ts:319 [EXTRACTED]
  ```
  export function leavesOut(paths: readonly string[], file: string): boolean {
  ```
- `BENCHMARK_NAME` ← src/benchmark/terms.ts:9 [EXTRACTED]
  ```
  export const BENCHMARK_NAME = /^[A-Za-z0-9][A-Za-z0-9_-]*$/;
  ```
- `BenchmarkNameSchema` ← src/benchmark/terms.ts:10 [EXTRACTED]
  ```
  export const BenchmarkNameSchema = z.string().regex(BENCHMARK_NAME, 'must be letters, digits, "-" or "_", with no "."');
  ```
- `ArmTeamSchema` ← src/benchmark/terms.ts:16 [EXTRACTED]
  ```
  export const ArmTeamSchema = z.discriminatedUnion('kind', [
  ```
- `SkillChangesSchema` ← src/benchmark/terms.ts:30 [EXTRACTED]
  ```
  export const SkillChangesSchema = z.object({
  ```
- `TrialLimitsSchema` ← src/benchmark/terms.ts:43 [EXTRACTED]
  ```
  export const TrialLimitsSchema = z.object({
  ```
- `commitCheckFiles` ← src/benchmark/trial.ts:44 [EXTRACTED]
  ```
  export async function commitCheckFiles(cache: string, suite: Suite): Promise<{ ok: true; suite: CommittedSuite } | { ok: false; task: string; failed: string }> {
  ```
- `trialBlocker` ← src/benchmark/trial.ts:123 [EXTRACTED]
  ```
  export async function trialBlocker(config: LocalConfig): Promise<string | undefined> {
  ```
- `toolUnavailableNotice` ← src/benchmark/trial.ts:131 [EXTRACTED]
  ```
  export function toolUnavailableNotice(arm: Pick<PlannedArm, 'name' | 'tool'>): string {
  ```
- `outdatedBenchmarkPlan` ← src/benchmark/trial.ts:140 [EXTRACTED]
  ```
  export function outdatedBenchmarkPlan(run: RunState): WorkflowFailure | undefined {
  ```
- `prepareCheckPlace` ← src/benchmark/trial.ts:182 [EXTRACTED]
  ```
  export async function prepareCheckPlace({ config, run, attempt, dir }: { config: LocalConfig; run: RunState; attempt: string; dir: string }): Promise<WorkflowFailure | undefined> {
  ```
- `decideCheckReport` ← src/benchmark/trial.ts:216 [EXTRACTED]
  ```
  export async function decideCheckReport({ config, run, report }: { config: LocalConfig; run: RunState; report: EndedReport }): Promise<EndedReport> {
  ```
- `TrialVerdictSchema` ← src/benchmark/verdicts.ts:48 [EXTRACTED]
  ```
  export const TrialVerdictSchema = z.object({
  ```
- `EntryVerdictSchema` ← src/benchmark/verdicts.ts:64 [EXTRACTED]
  ```
  export const EntryVerdictSchema = TrialVerdictSchema.extend({
  ```
- `TrialScoringCostSchema` ← src/benchmark/verdicts.ts:73 [EXTRACTED]
  ```
  export const TrialScoringCostSchema = z.union([ScoringCostSchema, z.object({ complete: z.literal(false) }).strict()]);
  ```
- `TrialCalibrationSchema` ← src/benchmark/verdicts.ts:84 [EXTRACTED]
  ```
  export const TrialCalibrationSchema = z.object({
  ```
- `isDecidedByCheck` ← src/benchmark/verdicts.ts:251 [EXTRACTED]
  ```
  export function isDecidedByCheck(task: PlannedTask, output: CheckOutput | undefined): boolean {
  ```
- `TrialVerdicts` ← src/benchmark/verdicts.ts:321 [EXTRACTED]
  ```
  export const TrialVerdicts = {
  ```
- `CiExtractMr` ← src/ci/extract-mr.ts:425 [EXTRACTED]
  ```
  export const CiExtractMr = { WORKFLOW, start, comment, write, artifacts } as const;
  ```
- `paginateGitLab` ← src/ci/gitlab-paginate.ts:25 [EXTRACTED]
  ```
  export async function paginateGitLab<T>(
  ```
- `githubApiUrl` ← src/ci/mr-comment.ts:32 [EXTRACTED]
  ```
  export function githubApiUrl(): string {
  ```
- `parseMrUrl` ← src/ci/mr-comment.ts:55 [EXTRACTED]
  ```
  export function parseMrUrl(url: string): ParsedMrUrl {
  ```
- `formatComment` ← src/ci/mr-comment.ts:97 [EXTRACTED]
  ```
  export function formatComment(
  ```
- `postOrUpdateMrComment` ← src/ci/mr-comment.ts:436 [EXTRACTED]
  ```
  export async function postOrUpdateMrComment(
  ```
- `formatIndividualComment` ← src/ci/mr-comment.ts:502 [EXTRACTED]
  ```
  export function formatIndividualComment(
  ```
- `postIndividualComments` ← src/ci/mr-comment.ts:557 [EXTRACTED]
  ```
  export async function postIndividualComments(
  ```
- `postCodebaseGraphComment` ← src/ci/mr-comment.ts:745 [EXTRACTED]
  ```
  export async function postCodebaseGraphComment(
  ```
- `extractMarkerId` ← src/ci/read-rejections.ts:50 [EXTRACTED]
  ```
  export function extractMarkerId(body: string): string | null {
  ```
- `readRejections` ← src/ci/read-rejections.ts:274 [EXTRACTED]
  ```
  export async function readRejections(mrUrl: string): Promise<RejectionResult> {
  ```
- `shouldWrite` ← src/ci/read-rejections.ts:301 [EXTRACTED]
  ```
  export function shouldWrite(markerId: string, rejections: RejectionResult, _provider: 'github' | 'tgit' | 'gitlab'): boolean {
  ```
- `agentHarnessView` ← src/dashboard/agent-harness-view.ts:10 [EXTRACTED]
  ```
  export const agentHarnessView = `
  ```
- `benchmarksClient` ← src/dashboard/benchmarks-client.ts:12 [EXTRACTED]
  ```
  export const benchmarksClient = `
  ```
- `parseBenchmarkQuery` ← src/dashboard/benchmarks.ts:30 [EXTRACTED]
  ```
  export function parseBenchmarkQuery(params: URLSearchParams): BenchmarkHistoryQuery {
  ```
- `publishedBenchmarkRuns` ← src/dashboard/benchmarks.ts:108 [EXTRACTED]
  ```
  export async function publishedBenchmarkRuns(config: LocalConfig, { refresh }: { refresh: boolean }): Promise<BenchmarkRunInput[]> {
  ```
- `benchmarkHistory` ← src/dashboard/benchmarks.ts:235 [EXTRACTED]
  ```
  export async function benchmarkHistory({ config, query, now = new Date(), refresh = true }: {
  ```
- `benchmarkRuns` ← src/dashboard/benchmarks.ts:248 [EXTRACTED]
  ```
  export async function benchmarkRuns(config: LocalConfig, { refresh }: { refresh: boolean }): Promise<BenchmarkRunInput[]> {
  ```
- `chartFitView` ← src/dashboard/chart-fit-view.ts:8 [EXTRACTED]
  ```
  export const chartFitView = `
  ```
- `dashboardClient` ← src/dashboard/client.ts:17 [EXTRACTED]
  ```
  export const dashboardClient = `(() => {
  ```
- `NAMESPACE_TYPES` ← src/dashboard/delivery.ts:14 [EXTRACTED]
  ```
  export const NAMESPACE_TYPES = ['skills', 'knowledge', 'agents', 'learnings'] as const;
  ```
- `pickNamespaces` ← src/dashboard/delivery.ts:20 [EXTRACTED]
  ```
  export function pickNamespaces(resources: Partial<Record<NamespaceType, string[]>>): Namespaces {
  ```
- `resolveDelivery` ← src/dashboard/delivery.ts:51 [EXTRACTED]
  ```
  export async function resolveDelivery(config: LocalConfig): Promise<Delivery> {
  ```
- `diffDelivery` ← src/dashboard/delivery.ts:104 [EXTRACTED]
  ```
  export function diffDelivery(before: Delivery, after: Delivery, manifests: Manifests) {
  ```
- `readDistribution` ← src/dashboard/distribution.ts:169 [EXTRACTED]
  ```
  export async function readDistribution(ownConfig: LocalConfig) {
  ```
- `previewDistribution` ← src/dashboard/distribution.ts:203 [EXTRACTED]
  ```
  export async function previewDistribution(ownConfig: LocalConfig, body: JsonBody) {
  ```
- `saveRoles` ← src/dashboard/distribution.ts:231 [EXTRACTED]
  ```
  export async function saveRoles(ownConfig: LocalConfig, body: JsonBody): Promise<void> {
  ```
- `saveProjects` ← src/dashboard/distribution.ts:239 [EXTRACTED]
  ```
  export async function saveProjects(ownConfig: LocalConfig, body: JsonBody): Promise<void> {
  ```
- `handoffView` ← src/dashboard/handoff-view.ts:9 [EXTRACTED]
  ```
  export const handoffView = `
  ```
- `HttpError` ← src/dashboard/http.ts:12 [EXTRACTED]
  ```
  export class HttpError extends Error {
  ```
- `isLocalWrite` ← src/dashboard/http.ts:31 [EXTRACTED]
  ```
  export function isLocalWrite(req: http.IncomingMessage, port: number): boolean {
  ```
- `readJsonBody` ← src/dashboard/http.ts:51 [EXTRACTED]
  ```
  export async function readJsonBody(req: http.IncomingMessage): Promise<JsonBody> {
  ```
- `improvementClient` ← src/dashboard/improvement-client.ts:6 [EXTRACTED]
  ```
  export const improvementClient = `
  ```
- `buildImprovement` ← src/dashboard/improvement.ts:138 [EXTRACTED]
  ```
  export async function buildImprovement(
  ```
- `judgingHealth` ← src/dashboard/judging-health.ts:116 [EXTRACTED]
  ```
  export async function judgingHealth(config: LocalConfig, now: string): Promise<JudgingHealth> {
  ```
- `judgingView` ← src/dashboard/judging-view.ts:42 [EXTRACTED]
  ```
  export const judgingView = `
  ```
- `layeredResourcesView` ← src/dashboard/layered-resources-view.ts:9 [EXTRACTED]
  ```
  export const layeredResourcesView = `
  ```
- `collectLayeredResources` ← src/dashboard/layered-resources.ts:654 [EXTRACTED]
  ```
  export async function collectLayeredResources(config: LocalConfig, teamConfig: TeamaiConfig): Promise<LayeredResources> {
  ```
- `dashboardMessages` ← src/dashboard/locales.ts:2 [EXTRACTED]
  ```
  export const dashboardMessages = {
  ```
- `memberSettingsView` ← src/dashboard/member-settings-view.ts:5 [EXTRACTED]
  ```
  export const memberSettingsView = `
  ```
- `readMemberSettingsPanel` ← src/dashboard/member-settings.ts:16 [EXTRACTED]
  ```
  export async function readMemberSettingsPanel(config: LocalConfig): Promise<MemberSettingsPanel> {
  ```
- `collectSkillsInventory` ← src/dashboard/resources-skills.ts:111 [EXTRACTED]
  ```
  export async function collectSkillsInventory(
  ```
- `skillDetail` ← src/dashboard/resources-skills.ts:214 [EXTRACTED]
  ```
  export async function skillDetail(
  ```
- `setSkillExclusion` ← src/dashboard/resources-skills.ts:240 [EXTRACTED]
  ```
  export async function setSkillExclusion(
  ```
- `FrontmatterDescriptionSchema` ← src/dashboard/resources.ts:21 [EXTRACTED]
  ```
  export const FrontmatterDescriptionSchema = z.object({ description: z.string().optional().catch(undefined) }).catch({});
  ```
- `collectRulesInventory` ← src/dashboard/resources.ts:58 [EXTRACTED]
  ```
  export async function collectRulesInventory(
  ```
- `runBranchesView` ← src/dashboard/run-branches-view.ts:17 [EXTRACTED]
  ```
  export const runBranchesView = `
  ```
- `runStepsView` ← src/dashboard/run-steps-view.ts:22 [EXTRACTED]
  ```
  export const runStepsView = `
  ```
- `scorersClient` ← src/dashboard/scorers-client.ts:36 [EXTRACTED]
  ```
  export const scorersClient = `
  ```
- `parseScorerQuery` ← src/dashboard/scorers.ts:45 [EXTRACTED]
  ```
  export function parseScorerQuery(params: URLSearchParams): ScorerQuery {
  ```
- `rubricLabelsOf` ← src/dashboard/scorers.ts:266 [EXTRACTED]
  ```
  export async function rubricLabelsOf(config: LocalConfig, labels: readonly ScoreLabel[]): Promise<RubricLabels> {
  ```
- `sidesOf` ← src/dashboard/scorers.ts:333 [EXTRACTED]
  ```
  export async function sidesOf(config: LocalConfig, commit: string, revisions: ReadonlySet<string>): Promise<Map<string, Side>> {
  ```
- `readScorerLabels` ← src/dashboard/scorers.ts:377 [EXTRACTED]
  ```
  export async function readScorerLabels(config: LocalConfig, { refresh = true }: { refresh?: boolean } = {}): Promise<ViewedLabel[]> {
  ```
- `scorerResults` ← src/dashboard/scorers.ts:427 [EXTRACTED]
  ```
  export async function scorerResults({ config, query, now = new Date(), events, refresh = true }: {
  ```
- `selfImprovementClient` ← src/dashboard/self-improvement-client.ts:7 [EXTRACTED]
  ```
  export const selfImprovementClient = `
  ```
- `selfImprovementView` ← src/dashboard/self-improvement.ts:390 [EXTRACTED]
  ```
  export async function selfImprovementView({ config, now = new Date(), refresh = true }: { config: LocalConfig; now?: Date; refresh?: boolean }): Promise<SelfImprovementView> {
  ```
- `sessionSharingView` ← src/dashboard/session-sharing-view.ts:5 [EXTRACTED]
  ```
  export const sessionSharingView = `
  ```
- `readSessionSharing` ← src/dashboard/session-sharing.ts:138 [EXTRACTED]
  ```
  export async function readSessionSharing(config: LocalConfig, { env, platform, now }: { env: NodeJS.ProcessEnv; platform: NodeJS.Platform; now: string }): Promise<SessionSharing> {
  ```
- `dashboardShell` ← src/dashboard/shell.ts:1 [EXTRACTED]
  ```
  export const dashboardShell = `<aside><div class="brand"><svg viewBox="0 0 96 96" aria-hidden="true"><rect width="96" height="96" rx="22" fill="#15161a"/><g transform="translate(-9.6,-9.6) scale(1.2)"><g stroke="#fafafb" stroke-width="2.6" stroke-linecap="round" opacity=".9"><path d="M30 30L48 48M66 30L48 48M30 66L48 48M66 66L48 48"/></g><g fill="#fafafb"><circle cx="30" cy="30" r="5.6"/><circle cx="66" cy="30" r="5.6"/><circle cx="30" cy="66" r="5.6"/><circle cx="66" cy="66" r="5.6"/></g><rect x="39" y="39" width="18" height="18" rx="2.6" fill="#0052D9"/></g></svg>TeamAI<small>CLI</small></div><div class="workspace"><label for="workspace">Workspace</label><select id="workspace" aria-label="Workspace"><option>Loading…</option></select><small id="workspace-root"></small></div><nav id="nav" aria-label="Pages"></nav><div class="sidebar-bottom"><span class="dot"></span>Local workspace</div></aside>
  ```
- `dashboardStyles` ← src/dashboard/styles.ts:2 [EXTRACTED]
  ```
  export const dashboardStyles = `
  ```
- `summarizeTokenCosts` ← src/dashboard/token-costs.ts:62 [EXTRACTED]
  ```
  export function summarizeTokenCosts(
  ```
- `tokensView` ← src/dashboard/tokens-view.ts:7 [EXTRACTED]
  ```
  export const tokensView = `
  ```
- `listedRuns` ← src/dashboard/workflow-runs.ts:355 [EXTRACTED]
  ```
  export async function listedRuns(config: LocalConfig): Promise<RunState[]> {
  ```
- `listLocalRuns` ← src/dashboard/workflow-runs.ts:364 [EXTRACTED]
  ```
  export async function listLocalRuns(config: LocalConfig): Promise<LocalRunRow[]> {
  ```
- `listReportedRuns` ← src/dashboard/workflow-runs.ts:389 [EXTRACTED]
  ```
  export async function listReportedRuns(config: LocalConfig): Promise<ReportedRunRow[]> {
  ```
- `listHandoffs` ← src/dashboard/workflow-runs.ts:409 [EXTRACTED]
  ```
  export async function listHandoffs(config: LocalConfig): Promise<HandoffRow[]> {
  ```
- `workflowRunDetail` ← src/dashboard/workflow-runs.ts:561 [EXTRACTED]
  ```
  export async function workflowRunDetail(config: LocalConfig, source: 'local' | 'reported', runId: string): Promise<RunDetail | undefined> {
  ```
- `answerFromDashboard` ← src/dashboard/workflow-runs.ts:608 [EXTRACTED]
  ```
  export async function answerFromDashboard(config: LocalConfig, body: JsonBody): Promise<{ answered: unknown }> {
  ```
- `dashboardWorkspaces` ← src/dashboard/workspaces.ts:63 [EXTRACTED]
  ```
  export async function dashboardWorkspaces(events: DashboardEvent[]): Promise<DashboardWorkspace[]> {
  ```
- `workspaceEvents` ← src/dashboard/workspaces.ts:153 [EXTRACTED]
  ```
  export function workspaceEvents(events: DashboardEvent[], workspace: DashboardWorkspace, workspaces: DashboardWorkspace[]): DashboardEvent[] {
  ```
- `ownSessionEvents` ← src/dashboard/workspaces.ts:164 [EXTRACTED]
  ```
  export function ownSessionEvents(events: DashboardEvent[], workspace: DashboardWorkspace, workspaces: DashboardWorkspace[]): DashboardEvent[] {
  ```
- `adoptionRatio` ← src/maintenance/confidence.ts:42 [EXTRACTED]
  ```
  export function adoptionRatio(factors: ConfidenceFactors): number {
  ```
- `computeConfidence` ← src/maintenance/confidence.ts:65 [EXTRACTED]
  ```
  export function computeConfidence(factors: ConfidenceFactors): number {
  ```
- `addVoteEntry` ← src/maintenance/confidence.ts:99 [EXTRACTED]
  ```
  export function addVoteEntry(factors: ConfidenceFactors | undefined, entry: VoteEntryV2): ConfidenceFactors {
  ```
- `aggregateConfidenceFactors` ← src/maintenance/confidence.ts:118 [EXTRACTED]
  ```
  export async function aggregateConfidenceFactors(votesDir: string): Promise<Map<string, ConfidenceFactors>> {
  ```
- `computeAllConfidence` ← src/maintenance/confidence.ts:141 [EXTRACTED]
  ```
  export async function computeAllConfidence(votesDir: string): Promise<Map<string, number>> {
  ```
- `writeBackConfidence` ← src/maintenance/confidence.ts:155 [EXTRACTED]
  ```
  export async function writeBackConfidence(
  ```
- `HOT_THRESHOLD` ← src/maintenance/hot-cold.ts:4 [EXTRACTED]
  ```
  export const HOT_THRESHOLD = 0.5;
  ```
- `ZERO_EVIDENCE_WEIGHT` ← src/maintenance/hot-cold.ts:12 [EXTRACTED]
  ```
  export const ZERO_EVIDENCE_WEIGHT = 0.8;
  ```
- `hotnessFor` ← src/maintenance/hot-cold.ts:22 [EXTRACTED]
  ```
  export function hotnessFor(confidence: number | undefined): number {
  ```
- `annotateHotness` ← src/maintenance/hot-cold.ts:33 [EXTRACTED]
  ```
  export function annotateHotness(
  ```
- `CheckoutLockedError` ← src/maintenance/paths.ts:27 [EXTRACTED]
  ```
  export class CheckoutLockedError extends Error {
  ```
- `CheckoutUnavailableError` ← src/maintenance/paths.ts:43 [EXTRACTED]
  ```
  export class CheckoutUnavailableError extends Error {
  ```
- `SyncLockedError` ← src/maintenance/paths.ts:54 [EXTRACTED]
  ```
  export class SyncLockedError extends Error {
  ```
- `resolveMaintenancePaths` ← src/maintenance/paths.ts:91 [EXTRACTED]
  ```
  export async function resolveMaintenancePaths(
  ```
- `findPromotionCandidates` ← src/maintenance/promote.ts:50 [EXTRACTED]
  ```
  export async function findPromotionCandidates({ learningsDirs, votesDir, knowledgeCheckout: checkout, namespaces, thresholds }: PromotionCandidatesQuery): Promise<PromotionCandidate[]> {
  ```
- `fetchPromotionRefs` ← src/maintenance/promote.ts:124 [EXTRACTED]
  ```
  export async function fetchPromotionRefs(knowledgeCheckout: string): Promise<void> {
  ```
- `PromotionCategorySchema` ← src/maintenance/promote.ts:164 [EXTRACTED]
  ```
  export const PromotionCategorySchema = z.enum(['skills', 'rules', 'docs']);
  ```
- `promotionTarget` ← src/maintenance/promote.ts:169 [EXTRACTED]
  ```
  export function promotionTarget(filename: string, category: PromotionCategory): string {
  ```
- `writePromotion` ← src/maintenance/promote.ts:181 [EXTRACTED]
  ```
  export async function writePromotion(
  ```
- `markPromoted` ← src/maintenance/promote.ts:223 [EXTRACTED]
  ```
  export async function markPromoted(
  ```
- `chooseCategory` ← src/maintenance/promote.ts:255 [EXTRACTED]
  ```
  export function chooseCategory(choice: { given: string; chosen: string; reason: string; suggested: PromotionCategory }) {
  ```
- `assertCanPromote` ← src/maintenance/promotion-publish.ts:24 [EXTRACTED]
  ```
  export function assertCanPromote(localConfig: LocalConfig): void {
  ```
- `promotionCandidate` ← src/maintenance/promotion-publish.ts:33 [EXTRACTED]
  ```
  export function promotionCandidate(candidates: readonly PromotionCandidate[], learningId: string): PromotionCandidate {
  ```
- `PromoteLearning` ← src/maintenance/promotion-publish.ts:144 [EXTRACTED]
  ```
  export const PromoteLearning = { publish, parsePublished, mark } as const;
  ```
- `findPruneCandidates` ← src/maintenance/prune.ts:34 [EXTRACTED]
  ```
  export async function findPruneCandidates(
  ```
- `executePrune` ← src/maintenance/prune.ts:92 [EXTRACTED]
  ```
  export async function executePrune(
  ```
- `findStaleEntries` ← src/maintenance/quality-update.ts:31 [EXTRACTED]
  ```
  export async function findStaleEntries(
  ```
- `reportStaleEntries` ← src/maintenance/quality-update.ts:189 [EXTRACTED]
  ```
  export function reportStaleEntries(entries: StaleEntry[]): void {
  ```
- `findRelatedAdoptedLearnings` ← src/maintenance/quality-update.ts:215 [EXTRACTED]
  ```
  export async function findRelatedAdoptedLearnings(
  ```
- `DraftLearningUpdates` ← src/maintenance/quality-update.ts:434 [EXTRACTED]
  ```
  export const DraftLearningUpdates = { stale, context, writeDraft, parseResults, report } as const;
  ```
- `agyKeyFilePath` ← src/models/agy-gateway.ts:15 [EXTRACTED]
  ```
  export function agyKeyFilePath(): string {
  ```
- `agyKeyFunction` ← src/models/agy-gateway.ts:23 [EXTRACTED]
  ```
  export function agyKeyFunction(key: { envRef: string } | { value: string }, baseUrl: string): string {
  ```
- `agyGatewayOf` ← src/models/agy-gateway.ts:45 [EXTRACTED]
  ```
  export function agyGatewayOf(content: string, env: NodeJS.ProcessEnv): { GEMINI_API_KEY: string; GOOGLE_GEMINI_BASE_URL: string } | undefined {
  ```
- `agyGatewayEnv` ← src/models/agy-gateway.ts:56 [EXTRACTED]
  ```
  export function agyGatewayEnv(env: NodeJS.ProcessEnv): Record<string, string> {
  ```
- `isNativeModelAlias` ← src/models/aliases.ts:72 [EXTRACTED]
  ```
  export function isNativeModelAlias(model: string): boolean {
  ```
- `TEAM_ALIASES_FILE` ← src/models/aliases.ts:79 [EXTRACTED]
  ```
  export const TEAM_ALIASES_FILE = 'models/aliases.yaml';
  ```
- `localAliasesPath` ← src/models/aliases.ts:94 [EXTRACTED]
  ```
  export function localAliasesPath(): string {
  ```
- `noModelReason` ← src/models/aliases.ts:232 [EXTRACTED]
  ```
  export function noModelReason(resolution: ModelResolution): NoModel {
  ```
- `noModelCause` ← src/models/aliases.ts:237 [EXTRACTED]
  ```
  export function noModelCause(resolution: ModelResolution, tool: string): string {
  ```
- `modelValueProblem` ← src/models/aliases.ts:255 [EXTRACTED]
  ```
  export function modelValueProblem(value: string | undefined): string | undefined {
  ```
- `loadModelAliases` ← src/models/aliases.ts:268 [EXTRACTED]
  ```
  export async function loadModelAliases(localConfig: LocalConfig): Promise<ModelAliases> {
  ```
- `loadTeamModelAliases` ← src/models/aliases.ts:294 [EXTRACTED]
  ```
  export async function loadTeamModelAliases(localConfig: LocalConfig): Promise<ModelAliases> {
  ```
- `isModelAlias` ← src/models/aliases.ts:568 [EXTRACTED]
  ```
  export function isModelAlias(aliases: ModelAliases, model: string): boolean {
  ```
- `aliasWarningsFor` ← src/models/aliases.ts:579 [EXTRACTED]
  ```
  export function aliasWarningsFor(aliases: ModelAliases, spec: AgentSpec, receiver: string, place: DeliveryPlace): string[] {
  ```
- `agentModelToolOf` ← src/models/aliases.ts:644 [EXTRACTED]
  ```
  export function agentModelToolOf(receiver: string, place: DeliveryPlace): string {
  ```
- `resolveAgentModel` ← src/models/aliases.ts:656 [EXTRACTED]
  ```
  export function resolveAgentModel(aliases: ModelAliases, spec: AgentSpec, receiver: string, place: DeliveryPlace): ModelResolution {
  ```
- `resolveModelValue` ← src/models/aliases.ts:678 [EXTRACTED]
  ```
  export function resolveModelValue(aliases: ModelAliases, model: string, tool: string, extras?: ToolExtras): ModelResolution {
  ```
- `ModelProtocolSchema` ← src/models/profile.ts:22 [EXTRACTED]
  ```
  export const ModelProtocolSchema = z.enum([
  ```
- `ModelAgentSchema` ← src/models/profile.ts:33 [EXTRACTED]
  ```
  export const ModelAgentSchema = z.enum([
  ```
- `API_KEY_PLACEHOLDER` ← src/models/profile.ts:52 [EXTRACTED]
  ```
  export const API_KEY_PLACEHOLDER = '${API_KEY}';
  ```
- `ModelProfileSchema` ← src/models/profile.ts:75 [EXTRACTED]
  ```
  export const ModelProfileSchema = z.object({
  ```
- `profileRoutes` ← src/models/profile.ts:96 [EXTRACTED]
  ```
  export function profileRoutes(profile: ModelProfile): Partial<Record<ModelProtocol, string[]>> {
  ```
- `profileModels` ← src/models/profile.ts:108 [EXTRACTED]
  ```
  export function profileModels(profile: ModelProfile): string[] {
  ```
- `profileAgents` ← src/models/profile.ts:112 [EXTRACTED]
  ```
  export function profileAgents(profile: ModelProfile): ModelAgent[] {
  ```
- `ModelProfilesFileSchema` ← src/models/profile.ts:129 [EXTRACTED]
  ```
  export const ModelProfilesFileSchema = z.object({
  ```
- `getLocalProfilesPath` ← src/models/profile.ts:194 [EXTRACTED]
  ```
  export function getLocalProfilesPath(): string {
  ```
- `getLocalValuesPath` ← src/models/profile.ts:198 [EXTRACTED]
  ```
  export function getLocalValuesPath(): string {
  ```
- `isRepoReference` ← src/models/profile.ts:208 [EXTRACTED]
  ```
  export function isRepoReference(value: string): boolean {
  ```
- `getTeamValuesPath` ← src/models/profile.ts:225 [EXTRACTED]
  ```
  export function getTeamValuesPath(localConfig: LocalConfig): string {
  ```
- `getTeamIdentity` ← src/models/profile.ts:286 [EXTRACTED]
  ```
  export function getTeamIdentity(localConfig: LocalConfig): string {
  ```
- `unadoptedLegacyFiles` ← src/models/profile.ts:433 [EXTRACTED]
  ```
  export async function unadoptedLegacyFiles(
  ```
- `sameTeamIdentity` ← src/models/profile.ts:495 [EXTRACTED]
  ```
  export function sameTeamIdentity(stored: string | undefined, localConfig: LocalConfig): boolean {
  ```
- `findTeamValuesPath` ← src/models/profile.ts:538 [EXTRACTED]
  ```
  export async function findTeamValuesPath(
  ```
- `teamProfilesFrom` ← src/models/profile.ts:635 [EXTRACTED]
  ```
  export function teamProfilesFrom(entries: readonly ResolvedEntry<ModelProfile>[]): TeamModelProfiles {
  ```
- `inactiveNamespaceDefines` ← src/models/profile.ts:644 [EXTRACTED]
  ```
  export async function inactiveNamespaceDefines(repoPath: string, active: readonly string[], id: string): Promise<boolean> {
  ```
- `brokenTeamProfileFiles` ← src/models/profile.ts:657 [EXTRACTED]
  ```
  export async function brokenTeamProfileFiles(repoPath: string): Promise<string[]> {
  ```
- `loadLocalProfiles` ← src/models/profile.ts:669 [EXTRACTED]
  ```
  export async function loadLocalProfiles(): Promise<ModelProfilesFile> {
  ```
- `saveLocalProfiles` ← src/models/profile.ts:673 [EXTRACTED]
  ```
  export async function saveLocalProfiles(file: ModelProfilesFile): Promise<void> {
  ```
- `loadModelInputs` ← src/models/profile.ts:678 [EXTRACTED]
  ```
  export async function loadModelInputs(filePath: string): Promise<StoredModelInputs> {
  ```
- `saveModelInputs` ← src/models/profile.ts:705 [EXTRACTED]
  ```
  export async function saveModelInputs(filePath: string, values: StoredModelInputs): Promise<void> {
  ```
- `withTeamValuesLock` ← src/models/profile.ts:719 [EXTRACTED]
  ```
  export async function withTeamValuesLock<T>(filePath: string, run: () => Promise<T>): Promise<T> {
  ```
- `mergeModelInputs` ← src/models/profile.ts:740 [EXTRACTED]
  ```
  export function mergeModelInputs(into: StoredModelInputs, later: StoredModelInputs): StoredModelInputs {
  ```
- `resolveProfileRef` ← src/models/profile.ts:744 [EXTRACTED]
  ```
  export function resolveProfileRef(
  ```
- `profileRefName` ← src/models/profile.ts:785 [EXTRACTED]
  ```
  export function profileRefName(ref: ProfileRef): string {
  ```
- `profileOrigin` ← src/models/profile.ts:790 [EXTRACTED]
  ```
  export function profileOrigin(profile: ModelProfile): string {
  ```
- `gatewaySuffix` ← src/models/profile.ts:795 [EXTRACTED]
  ```
  export function gatewaySuffix(ref: ProfileRef, preposition: 'at' | 'for'): string {
  ```
- `storedApiKey` ← src/models/profile.ts:810 [EXTRACTED]
  ```
  export function storedApiKey(ref: ProfileRef, values: StoredModelInputs): StoredModelInput | undefined {
  ```
- `setStoredApiKey` ← src/models/profile.ts:815 [EXTRACTED]
  ```
  export function setStoredApiKey(ref: ProfileRef, values: StoredModelInputs, input: StoredModelInput): void {
  ```
- `bindLegacyTeamKeys` ← src/models/profile.ts:831 [EXTRACTED]
  ```
  export function bindLegacyTeamKeys(
  ```
- `hasApiKeyForAnotherGateway` ← src/models/profile.ts:858 [EXTRACTED]
  ```
  export function hasApiKeyForAnotherGateway(ref: ProfileRef, values: StoredModelInputs): boolean {
  ```
- `isApiKeyConfigured` ← src/models/profile.ts:866 [EXTRACTED]
  ```
  export function isApiKeyConfigured(stored: StoredModelInput | undefined): boolean {
  ```
- `resolveProfile` ← src/models/profile.ts:870 [EXTRACTED]
  ```
  export function resolveProfile(
  ```
- `refusedLegacyValueKeys` ← src/models/switch.ts:319 [EXTRACTED]
  ```
  export async function refusedLegacyValueKeys(): Promise<ReadonlySet<string>> {
  ```
- `refuseLegacyValue` ← src/models/switch.ts:326 [EXTRACTED]
  ```
  export async function refuseLegacyValue(key: string): Promise<void> {
  ```
- `switchModelProfile` ← src/models/switch.ts:1515 [EXTRACTED]
  ```
  export async function switchModelProfile(
  ```
- `restoreModelProfiles` ← src/models/switch.ts:1725 [EXTRACTED]
  ```
  export async function restoreModelProfiles(
  ```
- `activeModelProfiles` ← src/models/switch.ts:1824 [EXTRACTED]
  ```
  export async function activeModelProfiles(): Promise<Partial<Record<ModelAgent, ActiveModelProfile>>> {
  ```
- `liveModelSwitches` ← src/models/switch.ts:1851 [EXTRACTED]
  ```
  export async function liveModelSwitches(localConfig: Pick<LocalConfig, 'toolRoots'>): Promise<Record<ModelAgent, LiveModelSwitch>> {
  ```
- `switchedGatewayOrigins` ← src/models/switch.ts:1887 [EXTRACTED]
  ```
  export async function switchedGatewayOrigins(localConfig: LocalConfig): Promise<Map<string, string[]>> {
  ```
- `isModelProfileManaged` ← src/models/switch.ts:1978 [EXTRACTED]
  ```
  export async function isModelProfileManaged(agent: ModelAgent): Promise<boolean> {
  ```
- `pkgInstall` ← src/pkg/commands.ts:216 [EXTRACTED]
  ```
  export async function pkgInstall(
  ```
- `pkgDoctorReport` ← src/pkg/commands.ts:328 [EXTRACTED]
  ```
  export async function pkgDoctorReport(
  ```
- `detectPackageEnvironment` ← src/pkg/env-detect.ts:15 [EXTRACTED]
  ```
  export async function detectPackageEnvironment(
  ```
- `PACKAGE_MANIFEST_FILENAME` ← src/pkg/manifest.ts:21 [EXTRACTED]
  ```
  export const PACKAGE_MANIFEST_FILENAME = 'teamai.yaml';
  ```
- `PACKAGE_LOCK_FILENAME` ← src/pkg/manifest.ts:22 [EXTRACTED]
  ```
  export const PACKAGE_LOCK_FILENAME = 'teamai.lock';
  ```
- `packageManifestPath` ← src/pkg/manifest.ts:24 [EXTRACTED]
  ```
  export function packageManifestPath(repoPath: string): string {
  ```
- `packageLockPath` ← src/pkg/manifest.ts:28 [EXTRACTED]
  ```
  export function packageLockPath(cwd: string): string {
  ```
- `packageLockDir` ← src/pkg/manifest.ts:44 [EXTRACTED]
  ```
  export async function packageLockDir(localConfig: LocalConfig, options: { readOnly?: boolean } = {}): Promise<string> {
  ```
- `loadPackageManifest` ← src/pkg/manifest.ts:115 [EXTRACTED]
  ```
  export async function loadPackageManifest(repoPath: string): Promise<PackageManifest> {
  ```
- `savePackageManifest` ← src/pkg/manifest.ts:137 [EXTRACTED]
  ```
  export async function savePackageManifest(
  ```
- `loadPackageLock` ← src/pkg/manifest.ts:150 [EXTRACTED]
  ```
  export async function loadPackageLock(cwd: string): Promise<PackageLock | null> {
  ```
- `savePackageLock` ← src/pkg/manifest.ts:162 [EXTRACTED]
  ```
  export async function savePackageLock(cwd: string, lock: PackageLock): Promise<void> {
  ```
- `packageDeclarationHash` ← src/pkg/manifest.ts:183 [EXTRACTED]
  ```
  export function packageDeclarationHash(manifest: PackageManifest): string {
  ```
- `sharedPackageDeclarationHash` ← src/pkg/manifest.ts:195 [EXTRACTED]
  ```
  export function sharedPackageDeclarationHash(manifest: PackageManifest): string {
  ```
- `projectNpmDeclarationHash` ← src/pkg/manifest.ts:208 [EXTRACTED]
  ```
  export function projectNpmDeclarationHash(manifest: PackageManifest): string | null {
  ```
- `packageProjectKey` ← src/pkg/manifest.ts:215 [EXTRACTED]
  ```
  export function packageProjectKey(cwd: string): string {
  ```
- `hasPackageDeclarations` ← src/pkg/manifest.ts:229 [EXTRACTED]
  ```
  export function hasPackageDeclarations(manifest: PackageManifest): boolean {
  ```
- `buildPackageHintMessage` ← src/pkg/pkg-hint.ts:32 [EXTRACTED]
  ```
  export function buildPackageHintMessage(hook: DefaultFolder<'hooks', 'teamai-package-hint'>, { npm, claude, marketplace }: DeclaredPackageCounts, language: TextLanguage): string {
  ```
- `computePackageHintOutput` ← src/pkg/pkg-hint.ts:113 [EXTRACTED]
  ```
  export async function computePackageHintOutput(cwd: string): Promise<string | null> {
  ```
- `claimPackageHintOutput` ← src/pkg/pkg-hint.ts:162 [EXTRACTED]
  ```
  export async function claimPackageHintOutput(
  ```
- `packageManifestHashForCwd` ← src/pkg/pkg-hint.ts:180 [EXTRACTED]
  ```
  export async function packageManifestHashForCwd(cwd: string): Promise<string | null> {
  ```
- `stashPackageHintAfterPull` ← src/pkg/pkg-hint.ts:191 [EXTRACTED]
  ```
  export async function stashPackageHintAfterPull(
  ```
- `takePendingPackageHint` ← src/pkg/pkg-hint.ts:213 [EXTRACTED]
  ```
  export async function takePendingPackageHint(sessionId: string): Promise<string | null> {
  ```
- `registerPackagesCommand` ← src/pkg/register-command.ts:26 [EXTRACTED]
  ```
  export function registerPackagesCommand(
  ```
- `PackageScopeSchema` ← src/pkg/types.ts:3 [EXTRACTED]
  ```
  export const PackageScopeSchema = z.enum(['user', 'project', 'local']);
  ```
- `NpmSpecSchema` ← src/pkg/types.ts:7 [EXTRACTED]
  ```
  export const NpmSpecSchema = z.object({
  ```
- `ClaudeMarketplaceSchema` ← src/pkg/types.ts:30 [EXTRACTED]
  ```
  export const ClaudeMarketplaceSchema = z.object({
  ```
- `ClaudePluginSpecSchema` ← src/pkg/types.ts:36 [EXTRACTED]
  ```
  export const ClaudePluginSpecSchema = z.object({
  ```
- `ClaudeEcosystemSchema` ← src/pkg/types.ts:42 [EXTRACTED]
  ```
  export const ClaudeEcosystemSchema = z.object({
  ```
- `PackageSetSchema` ← src/pkg/types.ts:47 [EXTRACTED]
  ```
  export const PackageSetSchema = z.object({
  ```
- `PackageManifestSchema` ← src/pkg/types.ts:52 [EXTRACTED]
  ```
  export const PackageManifestSchema = z.object({
  ```
- `NpmLockEntrySchema` ← src/pkg/types.ts:103 [EXTRACTED]
  ```
  export const NpmLockEntrySchema = z.object({
  ```
- `ClaudeMarketplaceLockSchema` ← src/pkg/types.ts:113 [EXTRACTED]
  ```
  export const ClaudeMarketplaceLockSchema = z.object({
  ```
- `ClaudePluginLockSchema` ← src/pkg/types.ts:121 [EXTRACTED]
  ```
  export const ClaudePluginLockSchema = z.object({
  ```
- `PackageLockSchema` ← src/pkg/types.ts:129 [EXTRACTED]
  ```
  export const PackageLockSchema = z.object({
  ```
- `TEAMAI_COMMENT_SIGNATURE` ← src/providers/mr-threads.ts:15 [EXTRACTED]
  ```
  export const TEAMAI_COMMENT_SIGNATURE = '_Auto-generated by `teamai ci extract-mr`_';
  ```
- `isTeamaiComment` ← src/providers/mr-threads.ts:18 [EXTRACTED]
  ```
  export function isTeamaiComment(body: string): boolean {
  ```
- `pruneThreads` ← src/providers/mr-threads.ts:26 [EXTRACTED]
  ```
  export function pruneThreads(threads: MRThread[]): MRThread[] {
  ```
- `getDefaultProvider` ← src/providers/registry.ts:53 [EXTRACTED]
  ```
  export function getDefaultProvider(): string {
  ```
- `detectProvider` ← src/providers/registry.ts:84 [EXTRACTED]
  ```
  export function detectProvider(input: string): string {
  ```
- `detectProviderForInit` ← src/providers/registry.ts:125 [EXTRACTED]
  ```
  export async function detectProviderForInit(input: string): Promise<string> {
  ```
- `getProvider` ← src/providers/registry.ts:204 [EXTRACTED]
  ```
  export function getProvider(providerName?: string): GitProvider {
  ```
- `getProviderFromUrl` ← src/providers/registry.ts:220 [EXTRACTED]
  ```
  export function getProviderFromUrl(repoUrl: string): GitProvider {
  ```
- `providerForRemote` ← src/providers/registry.ts:243 [EXTRACTED]
  ```
  export function providerForRemote(remoteUrl: string): OriginProvider {
  ```
- `RepoListEntrySchema` ← src/repo-list/schema.ts:5 [EXTRACTED]
  ```
  export const RepoListEntrySchema = z.object({
  ```
- `RepoListOrgEntrySchema` ← src/repo-list/schema.ts:14 [EXTRACTED]
  ```
  export const RepoListOrgEntrySchema = z.object({
  ```
- `RepoListItemSchema` ← src/repo-list/schema.ts:23 [EXTRACTED]
  ```
  export const RepoListItemSchema = z.union([RepoListOrgEntrySchema, RepoListEntrySchema]);
  ```
- `RepoListFileSchema` ← src/repo-list/schema.ts:26 [EXTRACTED]
  ```
  export const RepoListFileSchema = z.object({
  ```
- `isOrgEntry` ← src/repo-list/schema.ts:45 [EXTRACTED]
  ```
  export function isOrgEntry(item: RepoListItem): item is RepoListOrgEntry {
  ```
- `loadRepoList` ← src/repo-list/store.ts:20 [EXTRACTED]
  ```
  export async function loadRepoList(filePath: string): Promise<RepoListFile> {
  ```
- `AgentFolders` ← src/resources/agent-folders.ts:139 [EXTRACTED]
  ```
  export const AgentFolders = { isFolder, pathOf, render, origin, deliver, prune, namedBy, isDelivered } as const;
  ```
- `AGENT_FILE_EXTENSIONS` ← src/resources/agent-format.ts:26 [EXTRACTED]
  ```
  export const AGENT_FILE_EXTENSIONS = ['.agent.md', '.md', '.toml', '.json'] as const satisfies readonly AgentFileExtension[];
  ```
- `agentStemFromFilename` ← src/resources/agent-format.ts:32 [EXTRACTED]
  ```
  export function agentStemFromFilename(filename: string): string | null {
  ```
- `agentFileExtensionForTool` ← src/resources/agent-format.ts:40 [EXTRACTED]
  ```
  export function agentFileExtensionForTool(tool: ToolName): AgentFileExtension {
  ```
- `parseAgentYaml` ← src/resources/agent-format.ts:145 [EXTRACTED]
  ```
  export function parseAgentYaml(content: string, filename: string): ParseResult {
  ```
- `serializeAgentYaml` ← src/resources/agent-format.ts:213 [EXTRACTED]
  ```
  export function serializeAgentYaml(spec: AgentSpec): string {
  ```
- `renderForClaude` ← src/resources/agent-format.ts:229 [EXTRACTED]
  ```
  export function renderForClaude(spec: AgentSpec): RenderResult {
  ```
- `renderForJoycode` ← src/resources/agent-format.ts:241 [EXTRACTED]
  ```
  export function renderForJoycode(spec: AgentSpec): RenderResult {
  ```
- `renderForWorkbuddy` ← src/resources/agent-format.ts:252 [EXTRACTED]
  ```
  export function renderForWorkbuddy(spec: AgentSpec): RenderResult {
  ```
- `KIRO_SESSION_START_COMMAND` ← src/resources/agent-format.ts:260 [EXTRACTED]
  ```
  export const KIRO_SESSION_START_COMMAND = getDispatchCommand('session-start', 'kiro');
  ```
- `renderForKiro` ← src/resources/agent-format.ts:298 [EXTRACTED]
  ```
  export function renderForKiro(spec: AgentSpec): RenderResult {
  ```
- `renderForCodex` ← src/resources/agent-format.ts:322 [EXTRACTED]
  ```
  export function renderForCodex(spec: AgentSpec): RenderResult {
  ```
- `renderForCursor` ← src/resources/agent-format.ts:333 [EXTRACTED]
  ```
  export function renderForCursor(spec: AgentSpec): RenderResult {
  ```
- `renderForCopilot` ← src/resources/agent-format.ts:395 [EXTRACTED]
  ```
  export function renderForCopilot(spec: AgentSpec): RenderResult {
  ```
- `museAgentDrops` ← src/resources/agent-format.ts:464 [EXTRACTED]
  ```
  export function museAgentDrops(spec: AgentSpec) {
  ```
- `renderForMuse` ← src/resources/agent-format.ts:474 [EXTRACTED]
  ```
  export function renderForMuse(spec: AgentSpec): RenderResult {
  ```
- `renderForAgy` ← src/resources/agent-format.ts:497 [EXTRACTED]
  ```
  export function renderForAgy(spec: AgentSpec, resolved?: ResolvedAgentModel): RenderResult {
  ```
- `reverseFromAgy` ← src/resources/agent-format.ts:510 [EXTRACTED]
  ```
  export function reverseFromAgy(filePath: string, content: string): ReverseResult {
  ```
- `agentRejection` ← src/resources/agent-format.ts:528 [EXTRACTED]
  ```
  export function agentRejection({ tool, name, spec, scope }: {
  ```
- `traeExtrasClashes` ← src/resources/agent-format.ts:554 [EXTRACTED]
  ```
  export function traeExtrasClashes(spec: AgentSpec): string[] {
  ```
- `reverseFromTrae` ← src/resources/agent-format.ts:585 [EXTRACTED]
  ```
  export function reverseFromTrae(filePath: string, content: string): ReverseResult {
  ```
- `renderForOpencode` ← src/resources/agent-format.ts:605 [EXTRACTED]
  ```
  export function renderForOpencode(spec: AgentSpec, resolved?: ParsedFields): RenderResult {
  ```
- `reverseFromClaude` ← src/resources/agent-format.ts:793 [EXTRACTED]
  ```
  export function reverseFromClaude(filePath: string, content: string): ReverseResult {
  ```
- `reverseFromCopilot` ← src/resources/agent-format.ts:836 [EXTRACTED]
  ```
  export function reverseFromCopilot(filePath: string, content: string): ReverseResult {
  ```
- `reverseFromCodebuddy` ← src/resources/agent-format.ts:879 [EXTRACTED]
  ```
  export function reverseFromCodebuddy(filePath: string, content: string): ReverseResult {
  ```
- `reverseFromJoycode` ← src/resources/agent-format.ts:899 [EXTRACTED]
  ```
  export function reverseFromJoycode(filePath: string, content: string): ReverseResult {
  ```
- `reverseFromWorkbuddy` ← src/resources/agent-format.ts:917 [EXTRACTED]
  ```
  export function reverseFromWorkbuddy(filePath: string, content: string): ReverseResult {
  ```
- `reverseFromMuse` ← src/resources/agent-format.ts:937 [EXTRACTED]
  ```
  export function reverseFromMuse(filePath: string, content: string): ReverseResult {
  ```
- `reverseFromKiro` ← src/resources/agent-format.ts:955 [EXTRACTED]
  ```
  export function reverseFromKiro(filePath: string, content: string): ReverseResult {
  ```
- `reverseFromCodex` ← src/resources/agent-format.ts:1010 [EXTRACTED]
  ```
  export function reverseFromCodex(filePath: string, content: string): ReverseResult {
  ```
- `reverseFromCursor` ← src/resources/agent-format.ts:1057 [EXTRACTED]
  ```
  export function reverseFromCursor(filePath: string, content: string): ReverseResult {
  ```
- `reverseFromOpencode` ← src/resources/agent-format.ts:1105 [EXTRACTED]
  ```
  export function reverseFromOpencode(filePath: string, content: string): ReverseResult {
  ```
- `mergeReverseResults` ← src/resources/agent-format.ts:1177 [EXTRACTED]
  ```
  export function mergeReverseResults(
  ```
- `toolExtrasFor` ← src/resources/agent-format.ts:1251 [EXTRACTED]
  ```
  export function toolExtrasFor(spec: AgentSpec, tool: ToolName): ParsedFields | undefined {
  ```
- `inheritedExtras` ← src/resources/agent-format.ts:1264 [EXTRACTED]
  ```
  export function inheritedExtras(spec: AgentSpec, tool: ToolName, scope: Scope | undefined): { readonly from: ToolName; readonly extras: ParsedFields } | undefined {
  ```
- `agentEffortField` ← src/resources/agent-format.ts:1277 [EXTRACTED]
  ```
  export function agentEffortField(tool: ToolName): string | undefined {
  ```
- `renderForTool` ← src/resources/agent-format.ts:1315 [EXTRACTED]
  ```
  export function renderForTool(spec: AgentSpec, tool: ToolName, resolved?: ResolvedAgentModel, scope?: Scope): RenderResult {
  ```
- `reverseByTool` ← src/resources/agent-format.ts:1360 [EXTRACTED]
  ```
  export function reverseByTool(tool: ToolName, filePath: string, content: string): ReverseResult {
  ```
- `ownedAgentDirectories` ← src/resources/agents.ts:112 [EXTRACTED]
  ```
  export async function ownedAgentDirectories(
  ```
- `selectAgentsForDirectory` ← src/resources/agents.ts:144 [EXTRACTED]
  ```
  export function selectAgentsForDirectory(
  ```
- `resolveAgentsForDirectory` ← src/resources/agents.ts:182 [EXTRACTED]
  ```
  export function resolveAgentsForDirectory(
  ```
- `AgentsHandler` ← src/resources/agents.ts:201 [EXTRACTED]
  ```
  export class AgentsHandler extends ResourceHandler {
  ```
- `reportHeldAgents` ← src/resources/agents.ts:1784 [EXTRACTED]
  ```
  export function reportHeldAgents(ledger: DeliveryLedger, dryRunScope?: string): number {
  ```
- `updateJoycodeAgentIndex` ← src/resources/agents.ts:1881 [EXTRACTED]
  ```
  export async function updateJoycodeAgentIndex(
  ```
- `listTeamAgentDirs` ← src/resources/agents.ts:1988 [EXTRACTED]
  ```
  export async function listTeamAgentDirs(teamAgentsDir: string): Promise<TeamAgentDir[]> {
  ```
- `listTeamAgentFolders` ← src/resources/agents.ts:2004 [EXTRACTED]
  ```
  export async function listTeamAgentFolders(teamAgentsDir: string): Promise<TeamAgentFolder[]> {
  ```
- `findTeamAgentFiles` ← src/resources/agents.ts:2096 [EXTRACTED]
  ```
  export async function findTeamAgentFiles(teamAgentsDir: string, stem: string): Promise<TeamAgentFile[]> {
  ```
- `targetsTool` ← src/resources/agents.ts:2387 [EXTRACTED]
  ```
  export function targetsTool(spec: AgentSpec, { tool, format }: AgentTool): boolean {
  ```
- `agentOrigin` ← src/resources/agents.ts:2423 [EXTRACTED]
  ```
  export function agentOrigin(teamConfig: Pick<TeamaiConfig, 'toolPaths'>, localConfig: LocalConfig, stem: string, target: AgentTool, aliases: ModelAliases): CopyOrigin {
  ```
- `removedAgentOrigin` ← src/resources/agents.ts:2475 [EXTRACTED]
  ```
  export async function removedAgentOrigin(teamConfig: Pick<TeamaiConfig, 'toolPaths'>, localConfig: LocalConfig, stem: string, tool: string): Promise<CopyOrigin> {
  ```
- `ownsAgentCopy` ← src/resources/agents.ts:2492 [EXTRACTED]
  ```
  export async function ownsAgentCopy(
  ```
- `sameAgentModel` ← src/resources/agents.ts:2564 [EXTRACTED]
  ```
  export function sameAgentModel(a: RecordedAgentModel, b: RecordedAgentModel): boolean {
  ```
- `ensureAgyPluginManifest` ← src/resources/agy-plugin.ts:19 [EXTRACTED]
  ```
  export async function ensureAgyPluginManifest(mcpFile: string): Promise<void> {
  ```
- `removeAgyPluginManifest` ← src/resources/agy-plugin.ts:31 [EXTRACTED]
  ```
  export async function removeAgyPluginManifest(mcpFile: string): Promise<void> {
  ```
- `teamRuleToAgyRule` ← src/resources/agy-rule.ts:21 [EXTRACTED]
  ```
  export function teamRuleToAgyRule(rawTeamRule: string): string {
  ```
- `ResourceHandler` ← src/resources/base.ts:36 [EXTRACTED]
  ```
  export abstract class ResourceHandler {
  ```
- `teamRuleToCodebuddyRule` ← src/resources/codebuddy-rule.ts:18 [EXTRACTED]
  ```
  export function teamRuleToCodebuddyRule(rawTeamRule: string): string {
  ```
- `teamRuleToCopilotInstructions` ← src/resources/copilot-instructions.ts:12 [EXTRACTED]
  ```
  export function teamRuleToCopilotInstructions(rawTeamRule: string): string {
  ```
- `mergeCopilotBodyIntoTeamMd` ← src/resources/copilot-instructions.ts:28 [EXTRACTED]
  ```
  export function mergeCopilotBodyIntoTeamMd(
  ```
- `copilotInstructionsBodyEqualsTeamMd` ← src/resources/copilot-instructions.ts:46 [EXTRACTED]
  ```
  export function copilotInstructionsBodyEqualsTeamMd(
  ```
- `teamRuleToCursorMdc` ← src/resources/cursor-mdc.ts:73 [EXTRACTED]
  ```
  export function teamRuleToCursorMdc(rawTeamRule: string): string {
  ```
- `classifyCopy` ← src/resources/delivered-copies.ts:56 [EXTRACTED]
  ```
  export function classifyCopy(files: readonly DeliveredFile[]): CopyVerdict {
  ```
- `openLedger` ← src/resources/delivered-copies.ts:109 [EXTRACTED]
  ```
  export function openLedger(
  ```
- `contentHash` ← src/resources/delivered-copies.ts:128 [EXTRACTED]
  ```
  export function contentHash(content: string | Buffer): string {
  ```
- `recordedUnder` ← src/resources/delivered-copies.ts:143 [EXTRACTED]
  ```
  export function recordedUnder(hashes: DeliveredHashes, dest: string): string[] {
  ```
- `recordedSkillDir` ← src/resources/delivered-copies.ts:152 [EXTRACTED]
  ```
  export function recordedSkillDir(hashes: DeliveredHashes, dir: string): string | undefined {
  ```
- `isUneditedSkillCopy` ← src/resources/delivered-copies.ts:194 [EXTRACTED]
  ```
  export async function isUneditedSkillCopy(previous: DeliveredHashes, dest: string): Promise<boolean> {
  ```
- `isTeamSkillAsDelivered` ← src/resources/delivered-copies.ts:215 [EXTRACTED]
  ```
  export async function isTeamSkillAsDelivered(previous: DeliveredHashes, dest: string, teamDir: string): Promise<boolean> {
  ```
- `isRecordedFromTeamSkill` ← src/resources/delivered-copies.ts:230 [EXTRACTED]
  ```
  export async function isRecordedFromTeamSkill(
  ```
- `isTeamaiCopy` ← src/resources/delivered-copies.ts:273 [EXTRACTED]
  ```
  export async function isTeamaiCopy(file: string, origin: CopyOrigin): Promise<boolean> {
  ```
- `notTeamaisReason` ← src/resources/delivered-copies.ts:315 [EXTRACTED]
  ```
  export function notTeamaisReason(resource: string, origin: 'team' | 'source' = 'team'): string {
  ```
- `describeMembersFile` ← src/resources/delivered-copies.ts:324 [EXTRACTED]
  ```
  export function describeMembersFile(file: string, resource: string, origin: 'team' | 'source' = 'team'): string {
  ```
- `describeMembersLink` ← src/resources/delivered-copies.ts:333 [EXTRACTED]
  ```
  export function describeMembersLink(file: string, resource: string, origin: 'team' | 'source' = 'team'): string {
  ```
- `describeSkippedLink` ← src/resources/delivered-copies.ts:342 [EXTRACTED]
  ```
  export function describeSkippedLink(link: string, skill: string): string {
  ```
- `describeKeptEntry` ← src/resources/delivered-copies.ts:347 [EXTRACTED]
  ```
  export async function describeKeptEntry(file: string, resource: string, origin: 'team' | 'source' = 'team'): Promise<string> {
  ```
- `membersLinkAt` ← src/resources/delivered-copies.ts:357 [EXTRACTED]
  ```
  export async function membersLinkAt(file: string): Promise<string | null> {
  ```
- `isTeamaiSkillCopy` ← src/resources/delivered-copies.ts:371 [EXTRACTED]
  ```
  export async function isTeamaiSkillCopy(
  ```
- `ownsSkillDir` ← src/resources/delivered-copies.ts:401 [EXTRACTED]
  ```
  export async function ownsSkillDir(
  ```
- `teamaiSkillFiles` ← src/resources/delivered-copies.ts:434 [EXTRACTED]
  ```
  export async function teamaiSkillFiles(
  ```
- `deliveredSkillFiles` ← src/resources/delivered-copies.ts:470 [EXTRACTED]
  ```
  export async function deliveredSkillFiles(source: string, dest: string, blocked: readonly string[] = []): Promise<string[]> {
  ```
- `describeKeptDir` ← src/resources/delivered-copies.ts:500 [EXTRACTED]
  ```
  export async function describeKeptDir(dir: string, resource: string, command: string): Promise<string> {
  ```
- `describeMembersDirLeft` ← src/resources/delivered-copies.ts:508 [EXTRACTED]
  ```
  export function describeMembersDirLeft(dir: string, resource: string, command: string): string {
  ```
- `isLink` ← src/resources/delivered-copies.ts:513 [EXTRACTED]
  ```
  export async function isLink(file: string): Promise<boolean> {
  ```
- `holdsNonRegular` ← src/resources/delivered-copies.ts:522 [EXTRACTED]
  ```
  export async function holdsNonRegular(dir: string): Promise<boolean> {
  ```
- `holdsGitDir` ← src/resources/delivered-copies.ts:531 [EXTRACTED]
  ```
  export async function holdsGitDir(dir: string): Promise<boolean> {
  ```
- `judgeCopy` ← src/resources/delivered-copies.ts:598 [EXTRACTED]
  ```
  export async function judgeCopy(previous: DeliveredHashes | undefined, item: ResourceItem, target: DeliveryTarget): Promise<CopyVerdict> {
  ```
- `blockingEntries` ← src/resources/delivered-copies.ts:622 [EXTRACTED]
  ```
  export async function blockingEntries(dest: string, sourcePath: string): Promise<string[]> {
  ```
- `keepsEditedCopy` ← src/resources/delivered-copies.ts:679 [EXTRACTED]
  ```
  export async function keepsEditedCopy(ledger: DeliveryLedger, item: ResourceItem, target: DeliveryTarget): Promise<boolean> {
  ```
- `judgeRemoval` ← src/resources/delivered-copies.ts:716 [EXTRACTED]
  ```
  export async function judgeRemoval(
  ```
- `keepsTrackedCopy` ← src/resources/delivered-copies.ts:761 [EXTRACTED]
  ```
  export async function keepsTrackedCopy(dest: string, movedTo?: string): Promise<boolean> {
  ```
- `recordDelivered` ← src/resources/delivered-copies.ts:779 [EXTRACTED]
  ```
  export async function recordDelivered(hashes: DeliveredHashes, dest: string, skillSource?: string): Promise<void> {
  ```
- `recordedUnchanged` ← src/resources/delivered-copies.ts:799 [EXTRACTED]
  ```
  export async function recordedUnchanged(previous: DeliveredHashes | undefined, file: string, recordAt: string = file): Promise<boolean> {
  ```
- `adoptRecord` ← src/resources/delivered-copies.ts:810 [EXTRACTED]
  ```
  export function adoptRecord(ledger: DeliveryLedger, file: string, hash: string): boolean {
  ```
- `forgetDelivered` ← src/resources/delivered-copies.ts:818 [EXTRACTED]
  ```
  export function forgetDelivered(hashes: DeliveredHashes, dest: string): void {
  ```
- `removeDelivered` ← src/resources/delivered-copies.ts:827 [EXTRACTED]
  ```
  export async function removeDelivered(ledger: DeliveryLedger | undefined, dest: string): Promise<void> {
  ```
- `reportKept` ← src/resources/delivered-copies.ts:842 [EXTRACTED]
  ```
  export function reportKept(ledger: DeliveryLedger, scopeLabel: string): number {
  ```
- `PATH_VARIABLES` ← src/resources/delivered-folders.ts:44 [EXTRACTED]
  ```
  export const PATH_VARIABLES = {
  ```
- `DELIVERED_DIR` ← src/resources/delivered-folders.ts:52 [EXTRACTED]
  ```
  export const DELIVERED_DIR = 'delivered';
  ```
- `DeliveredFolders` ← src/resources/delivered-folders.ts:637 [EXTRACTED]
  ```
  export const DeliveredFolders = { root, worktreeRoot, checkoutRoot, pathOf, versionedPathOf, identify, anyVersionPathOf, withoutVersions, namedIn, sync, place, deliver, prune, placeholder, mentions, render, renderFor } as const;
  ```
- `buildRolePullContext` ← src/resources/desired.ts:47 [EXTRACTED]
  ```
  export async function buildRolePullContext(localConfig: LocalConfig): Promise<RolePullContext | null> {
  ```
- `filterRulesByKnowledgeNamespaces` ← src/resources/desired.ts:112 [EXTRACTED]
  ```
  export function filterRulesByKnowledgeNamespaces(
  ```
- `describeDeliveryConflict` ← src/resources/desired.ts:153 [EXTRACTED]
  ```
  export function describeDeliveryConflict({ type, conflict }: DeliveryConflict): string {
  ```
- `filterAgentsByNamespaces` ← src/resources/desired.ts:182 [EXTRACTED]
  ```
  export function filterAgentsByNamespaces(
  ```
- `scanRoleAwareSkills` ← src/resources/desired.ts:239 [EXTRACTED]
  ```
  export async function scanRoleAwareSkills(
  ```
- `resolveDesiredSkills` ← src/resources/desired.ts:392 [EXTRACTED]
  ```
  export async function resolveDesiredSkills(
  ```
- `deliveredSkillSources` ← src/resources/desired.ts:478 [EXTRACTED]
  ```
  export async function deliveredSkillSources(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<ReadonlySet<string> | null> {
  ```
- `indexedSkills` ← src/resources/desired.ts:565 [EXTRACTED]
  ```
  export async function indexedSkills(
  ```
- `indexedRuleFiles` ← src/resources/desired.ts:578 [EXTRACTED]
  ```
  export async function indexedRuleFiles(
  ```
- `deliveredIndexSources` ← src/resources/desired.ts:594 [EXTRACTED]
  ```
  export async function deliveredIndexSources(
  ```
- `resolveDesiredRules` ← src/resources/desired.ts:647 [EXTRACTED]
  ```
  export async function resolveDesiredRules(
  ```
- `resolveDesiredAgents` ← src/resources/desired.ts:750 [EXTRACTED]
  ```
  export async function resolveDesiredAgents(
  ```
- `resolveTeamAgents` ← src/resources/desired.ts:769 [EXTRACTED]
  ```
  export async function resolveTeamAgents(
  ```
- `collectClaudemdFiles` ← src/resources/desired.ts:802 [EXTRACTED]
  ```
  export async function collectClaudemdFiles(
  ```
- `resolveDocsDestination` ← src/resources/docs.ts:24 [EXTRACTED]
  ```
  export function resolveDocsDestination(teamConfig: TeamaiConfig, localConfig: LocalConfig): string {
  ```
- `keepDocsSearchWhitelist` ← src/resources/docs.ts:68 [EXTRACTED]
  ```
  export async function keepDocsSearchWhitelist(
  ```
- `removeDocsSearchWhitelist` ← src/resources/docs.ts:100 [EXTRACTED]
  ```
  export async function removeDocsSearchWhitelist(projectRoot: string, options: { dryRun?: boolean } = {}): Promise<{ file: string; removed: boolean; failure: string | null }> {
  ```
- `listDocFiles` ← src/resources/docs.ts:166 [EXTRACTED]
  ```
  export async function listDocFiles(dir: string): Promise<string[]> {
  ```
- `listStaleDocDirectories` ← src/resources/docs.ts:184 [EXTRACTED]
  ```
  export async function listStaleDocDirectories(source: string | undefined, destination: string): Promise<string[]> {
  ```
- `isPrunableDoc` ← src/resources/docs.ts:214 [EXTRACTED]
  ```
  export async function isPrunableDoc(file: string, rel: string, repoPath: string): Promise<boolean> {
  ```
- `isLinkedDocsRoot` ← src/resources/docs.ts:250 [EXTRACTED]
  ```
  export async function isLinkedDocsRoot(dir: string): Promise<boolean> {
  ```
- `describeLinkedDocsRoot` ← src/resources/docs.ts:255 [EXTRACTED]
  ```
  export function describeLinkedDocsRoot(dir: string, command: 'pull' | 'uninstall'): string {
  ```
- `removeTeamDocs` ← src/resources/docs.ts:267 [EXTRACTED]
  ```
  export async function removeTeamDocs(dir: string, repoPath: string): Promise<string[]> {
  ```
- `describeKeptRemovedDoc` ← src/resources/docs.ts:358 [EXTRACTED]
  ```
  export async function describeKeptRemovedDoc(target: string, rel: string, repoPath: string, link: boolean): Promise<string | null> {
  ```
- `describeMembersDocDirectory` ← src/resources/docs.ts:373 [EXTRACTED]
  ```
  export async function describeMembersDocDirectory(dir: string, rel: string, repoPath: string): Promise<string | null> {
  ```
- `isPrunedDoc` ← src/resources/docs.ts:392 [EXTRACTED]
  ```
  export async function isPrunedDoc(file: string, rel: string, repoPath: string): Promise<boolean> {
  ```
- `isTeamDocsDirectory` ← src/resources/docs.ts:417 [EXTRACTED]
  ```
  export async function isTeamDocsDirectory(localDocsDir: string, repoPath: string): Promise<boolean> {
  ```
- `resolveDesiredDocs` ← src/resources/docs.ts:551 [EXTRACTED]
  ```
  export async function resolveDesiredDocs(repoPath: string, inactiveNamespaces: readonly string[]): Promise<DesiredDocs> {
  ```
- `resolveDocsForDirectory` ← src/resources/docs.ts:575 [EXTRACTED]
  ```
  export async function resolveDocsForDirectory(localConfig: LocalConfig): Promise<DesiredDocs> {
  ```
- `membersDocs` ← src/resources/docs.ts:591 [EXTRACTED]
  ```
  export async function membersDocs(desired: DesiredDocs, localDocsDir: string, repoPath: string): Promise<string[]> {
  ```
- `deliveredDocFiles` ← src/resources/docs.ts:647 [EXTRACTED]
  ```
  export function deliveredDocFiles(desired: DesiredDocs, members: readonly string[]): string[] {
  ```
- `DocsHandler` ← src/resources/docs.ts:729 [EXTRACTED]
  ```
  export class DocsHandler extends ResourceHandler {
  ```
- `envTable` ← src/resources/env-key.ts:17 [EXTRACTED]
  ```
  export function envTable<V>(entries: Iterable<readonly [string, V]> = []): Record<string, V> {
  ```
- `envValue` ← src/resources/env-key.ts:26 [EXTRACTED]
  ```
  export function envValue(env: NodeJS.ProcessEnv, key: string): string | undefined {
  ```
- `envName` ← src/resources/env-key.ts:31 [EXTRACTED]
  ```
  export function envName(key: string): string {
  ```
- `sameEnvName` ← src/resources/env-key.ts:36 [EXTRACTED]
  ```
  export function sameEnvName(names: Iterable<string>, key: string): string | undefined {
  ```
- `envNamePattern` ← src/resources/env-key.ts:49 [EXTRACTED]
  ```
  export function envNamePattern(key: string): string {
  ```
- `envNamePatternKey` ← src/resources/env-key.ts:56 [EXTRACTED]
  ```
  export function envNamePatternKey(pattern: string): string {
  ```
- `envLoaderPath` ← src/resources/env-loader.ts:29 [EXTRACTED]
  ```
  export function envLoaderPath(): string {
  ```
- `envExecBashEnvPath` ← src/resources/env-loader.ts:34 [EXTRACTED]
  ```
  export function envExecBashEnvPath(): string {
  ```
- `writeEnvExecBashEnv` ← src/resources/env-loader.ts:111 [EXTRACTED]
  ```
  export async function writeEnvExecBashEnv(): Promise<string> {
  ```
- `registerEnvScope` ← src/resources/env-loader.ts:204 [EXTRACTED]
  ```
  export async function registerEnvScope(localConfig: LocalConfig, inShells: boolean, { envChanged = false }: { envChanged?: boolean } = {}): Promise<void> {
  ```
- `markEnvScopePending` ← src/resources/env-loader.ts:260 [EXTRACTED]
  ```
  export async function markEnvScopePending(projectRoot: string): Promise<void> {
  ```
- `EnvScopesUnreadableError` ← src/resources/env-loader.ts:277 [EXTRACTED]
  ```
  export class EnvScopesUnreadableError extends Error {
  ```
- `userEnvInShells` ← src/resources/env-loader.ts:309 [EXTRACTED]
  ```
  export async function userEnvInShells(): Promise<boolean> {
  ```
- `unregisterEnvScope` ← src/resources/env-loader.ts:320 [EXTRACTED]
  ```
  export async function unregisterEnvScope(localConfig: LocalConfig): Promise<void> {
  ```
- `isLastEnvScope` ← src/resources/env-loader.ts:339 [EXTRACTED]
  ```
  export async function isLastEnvScope(localConfig: LocalConfig): Promise<boolean> {
  ```
- `hasEnvLoadingScope` ← src/resources/env-loader.ts:361 [EXTRACTED]
  ```
  export async function hasEnvLoadingScope(except?: LocalConfig): Promise<boolean> {
  ```
- `removeEnvLoader` ← src/resources/env-loader.ts:377 [EXTRACTED]
  ```
  export async function removeEnvLoader(): Promise<void> {
  ```
- `envLoaderFilesForProjects` ← src/resources/env-loader.ts:402 [EXTRACTED]
  ```
  export async function envLoaderFilesForProjects(): Promise<{ files: string[]; partitions: string[] }> {
  ```
- `forgetUserEnvScope` ← src/resources/env-loader.ts:429 [EXTRACTED]
  ```
  export async function forgetUserEnvScope(): Promise<void> {
  ```
- `loaderShell` ← src/resources/env-loader.ts:524 [EXTRACTED]
  ```
  export function loaderShell(shell: string): 'zsh' | 'bash' | null {
  ```
- `scopeEnvFiles` ← src/resources/env-loader.ts:531 [EXTRACTED]
  ```
  export async function scopeEnvFiles(localConfig: LocalConfig): Promise<string[]> {
  ```
- `directoryEnv` ← src/resources/env-loader.ts:545 [EXTRACTED]
  ```
  export async function directoryEnv(localConfig: LocalConfig, dir: string, shell = process.env.SHELL ?? ''): Promise<DirectoryEnv> {
  ```
- `writeEnvLoader` ← src/resources/env-loader.ts:628 [EXTRACTED]
  ```
  export async function writeEnvLoader(): Promise<void> {
  ```
- `unknownEnvVariableKeys` ← src/resources/env.ts:60 [EXTRACTED]
  ```
  export function unknownEnvVariableKeys(variable: EnvVariable): string[] {
  ```
- `describeMissingVariablesKey` ← src/resources/env.ts:125 [EXTRACTED]
  ```
  export function describeMissingVariablesKey(raw: JsonValue | undefined): string | null {
  ```
- `maskEnvValue` ← src/resources/env.ts:147 [EXTRACTED]
  ```
  export function maskEnvValue(value: string): string {
  ```
- `parseEnvFile` ← src/resources/env.ts:162 [EXTRACTED]
  ```
  export function parseEnvFile(content: string): Map<string, string> {
  ```
- `parseEnvFileKept` ← src/resources/env.ts:232 [EXTRACTED]
  ```
  export function parseEnvFileKept(content: string): Set<string> {
  ```
- `readEnvBackup` ← src/resources/env.ts:250 [EXTRACTED]
  ```
  export async function readEnvBackup(localConfig: LocalConfig): Promise<Record<string, string>> {
  ```
- `EnvHandler` ← src/resources/env.ts:370 [EXTRACTED]
  ```
  export class EnvHandler extends ResourceHandler {
  ```
- `FolderFiles` ← src/resources/folder-files.ts:82 [EXTRACTED]
  ```
  export const FolderFiles = { read, describe, text } as const;
  ```
- `HooksYamlSchema` ← src/resources/hooks.ts:58 [EXTRACTED]
  ```
  export const HooksYamlSchema = z.object({
  ```
- `teamHooksYamlPath` ← src/resources/hooks.ts:81 [EXTRACTED]
  ```
  export function teamHooksYamlPath(repoPath: string): string {
  ```
- `parseTeamHooks` ← src/resources/hooks.ts:155 [EXTRACTED]
  ```
  export function parseTeamHooks(content: string): TeamHook[] | null {
  ```
- `readHookFolder` ← src/resources/hooks.ts:168 [EXTRACTED]
  ```
  export async function readHookFolder(full: string, folderPath: string, id: string): Promise<PlaceFolderRead<TeamHookFolder>> {
  ```
- `teamHookToDef` ← src/resources/hooks.ts:214 [EXTRACTED]
  ```
  export function teamHookToDef(h: TeamHook): HookDef {
  ```
- `resolveTeamHookEntries` ← src/resources/hooks.ts:240 [EXTRACTED]
  ```
  export async function resolveTeamHookEntries(
  ```
- `readBuiltinOverride` ← src/resources/hooks.ts:249 [EXTRACTED]
  ```
  export async function readBuiltinOverride(localConfig: LocalConfig): Promise<BuiltinOverrideRead> {
  ```
- `readBuiltinDisabledListing` ← src/resources/hooks.ts:264 [EXTRACTED]
  ```
  export async function readBuiltinDisabledListing(
  ```
- `readDefaultHookReplacements` ← src/resources/hooks.ts:351 [EXTRACTED]
  ```
  export async function readDefaultHookReplacements(localConfig: LocalConfig): Promise<DefaultHookReplacement[]> {
  ```
- `defaultHookRefusals` ← src/resources/hooks.ts:359 [EXTRACTED]
  ```
  export async function defaultHookRefusals(root: string): Promise<Array<{ readonly path: string; readonly messages: readonly string[] }>> {
  ```
- `hookFolderPath` ← src/resources/hooks.ts:396 [EXTRACTED]
  ```
  export function hookFolderPath(localConfig: LocalConfig, folder: TeamHookFolder, namespace: string | null): string {
  ```
- `historicalFolderHookDef` ← src/resources/hooks.ts:427 [EXTRACTED]
  ```
  export function historicalFolderHookDef(localConfig: LocalConfig, relativePath: string, content: string): HookDef | null {
  ```
- `teamScriptRefusal` ← src/resources/hooks.ts:452 [EXTRACTED]
  ```
  export function teamScriptRefusal(localConfig: LocalConfig, teamConfig: TeamaiConfig, resolved: ResolvedEntry<TeamHookDefinition>): string | null {
  ```
- `resolveTeamHooks` ← src/resources/hooks.ts:468 [EXTRACTED]
  ```
  export async function resolveTeamHooks(
  ```
- `deliverHookFolders` ← src/resources/hooks.ts:536 [EXTRACTED]
  ```
  export async function deliverHookFolders(localConfig: LocalConfig, folders: readonly FolderDelivery[]): Promise<void> {
  ```
- `pruneHookFolders` ← src/resources/hooks.ts:549 [EXTRACTED]
  ```
  export async function pruneHookFolders(localConfig: LocalConfig, folders: readonly FolderDelivery[], installed: readonly string[]): Promise<void> {
  ```
- `HooksHandler` ← src/resources/hooks.ts:565 [EXTRACTED]
  ```
  export class HooksHandler extends ResourceHandler {
  ```
- `InheritedFolders` ← src/resources/inherited-folders.ts:75 [EXTRACTED]
  ```
  export const InheritedFolders = { merge, inheritanceOf, describe, strayMessage } as const;
  ```
- `teamRuleToJoycodeRule` ← src/resources/joycode-rule.ts:24 [EXTRACTED]
  ```
  export function teamRuleToJoycodeRule(rawTeamRule: string): string {
  ```
- `joycodeQuotedGlobsWarning` ← src/resources/joycode-rule.ts:39 [EXTRACTED]
  ```
  export function joycodeQuotedGlobsWarning(file: string, rawCopy: string): string | null {
  ```
- `teamRuleToKiroSteering` ← src/resources/kiro-steering.ts:20 [EXTRACTED]
  ```
  export function teamRuleToKiroSteering(rawTeamRule: string): string {
  ```
- `parseMarker` ← src/resources/layered-entries.ts:64 [EXTRACTED]
  ```
  export function parseMarker<TSchema extends z.ZodObject>(
  ```
- `readMarkerFolder` ← src/resources/layered-entries.ts:92 [EXTRACTED]
  ```
  export async function readMarkerFolder<TSchema extends z.ZodObject>(
  ```
- `LayeredEntries` ← src/resources/layered-entries.ts:285 [EXTRACTED]
  ```
  export const LayeredEntries = { resolve, readPlace } as const;
  ```
- `refreshMarketplace` ← src/resources/marketplace.ts:80 [EXTRACTED]
  ```
  export async function refreshMarketplace(repoPath: string): Promise<boolean> {
  ```
- `DSH_MCP_PLUGIN` ← src/resources/mcp-format.ts:26 [EXTRACTED]
  ```
  export const DSH_MCP_PLUGIN = '@deepseek-ai/dsh-mcp-client';
  ```
- `dshMcpPatchId` ← src/resources/mcp-format.ts:32 [EXTRACTED]
  ```
  export function dshMcpPatchId(serverName: string): string {
  ```
- `serverNameProblem` ← src/resources/mcp-format.ts:37 [EXTRACTED]
  ```
  export function serverNameProblem(format: McpFormat, name: string): string | null {
  ```
- `sameServerKey` ← src/resources/mcp-format.ts:83 [EXTRACTED]
  ```
  export function sameServerKey(a: McpFormat, b: McpFormat): boolean {
  ```
- `supportsTransport` ← src/resources/mcp-format.ts:119 [EXTRACTED]
  ```
  export function supportsTransport(format: McpFormat, transport: McpTransport): boolean {
  ```
- `supportsEnvExpansion` ← src/resources/mcp-format.ts:135 [EXTRACTED]
  ```
  export function supportsEnvExpansion(
  ```
- `planCodexHeaders` ← src/resources/mcp-format.ts:156 [EXTRACTED]
  ```
  export function planCodexHeaders(headers: Record<string, string> = {}): CodexHeaderPlan {
  ```
- `referencedVars` ← src/resources/mcp-format.ts:187 [EXTRACTED]
  ```
  export function referencedVars(def: McpServerDef): string[] {
  ```
- `placeholderValue` ← src/resources/mcp-format.ts:212 [EXTRACTED]
  ```
  export function placeholderValue(vars: Record<string, string>, name: string): string | undefined {
  ```
- `resolvePlaceholders` ← src/resources/mcp-format.ts:223 [EXTRACTED]
  ```
  export function resolvePlaceholders(def: McpServerDef, vars: Record<string, string>): ResolveResult {
  ```
- `renderJsonEntry` ← src/resources/mcp-format.ts:474 [EXTRACTED]
  ```
  export function renderJsonEntry(format: Exclude<McpFormat, 'codex'>, def: McpServerDef): McpJsonEntry {
  ```
- `renderCodexBlock` ← src/resources/mcp-format.ts:511 [EXTRACTED]
  ```
  export function renderCodexBlock(def: McpServerDef): string {
  ```
- `entryHash` ← src/resources/mcp-format.ts:562 [EXTRACTED]
  ```
  export function entryHash<TValue>(rendered: TValue): string {
  ```
- `UntypedStdioEntrySchema` ← src/resources/mcp-format.ts:567 [EXTRACTED]
  ```
  export const UntypedStdioEntrySchema = z.looseObject({ type: z.undefined().optional(), command: z.string(), url: z.undefined().optional() });
  ```
- `museEntryHash` ← src/resources/mcp-format.ts:570 [EXTRACTED]
  ```
  export function museEntryHash(rendered: JsonValue | undefined): string {
  ```
- `McpYamlSchema` ← src/resources/mcp.ts:53 [EXTRACTED]
  ```
  export const McpYamlSchema = z.object({
  ```
- `parseTeamMcpServers` ← src/resources/mcp.ts:94 [EXTRACTED]
  ```
  export function parseTeamMcpServers(content: string): TeamMcpServer[] | null {
  ```
- `readTeamMcpFile` ← src/resources/mcp.ts:101 [EXTRACTED]
  ```
  export async function readTeamMcpFile(absolutePath: string, relativePath: string): Promise<EntryFileRead<TeamMcpServer> | null> {
  ```
- `readMcpFolder` ← src/resources/mcp.ts:164 [EXTRACTED]
  ```
  export async function readMcpFolder(full: string, folderPath: string, name: string): Promise<PlaceFolderRead<TeamMcpFolder>> {
  ```
- `mcpFolderPath` ← src/resources/mcp.ts:221 [EXTRACTED]
  ```
  export function mcpFolderPath(localConfig: LocalConfig, folder: TeamMcpFolder, namespace: string | null): string {
  ```
- `teamMcpDef` ← src/resources/mcp.ts:229 [EXTRACTED]
  ```
  export function teamMcpDef(localConfig: LocalConfig, resolved: ResolvedEntry<TeamMcpDefinition>): McpServerDef {
  ```
- `historicalFolderMcpServer` ← src/resources/mcp.ts:252 [EXTRACTED]
  ```
  export function historicalFolderMcpServer(localConfig: LocalConfig, relativePath: string, content: string): { readonly server: TeamMcpServer; readonly def: McpServerDef } | null {
  ```
- `deliverMcpFolders` ← src/resources/mcp.ts:287 [EXTRACTED]
  ```
  export async function deliverMcpFolders(
  ```
- `pruneMcpFolders` ← src/resources/mcp.ts:312 [EXTRACTED]
  ```
  export async function pruneMcpFolders(
  ```
- `teamMcpToDef` ← src/resources/mcp.ts:326 [EXTRACTED]
  ```
  export function teamMcpToDef(s: TeamMcpServer): McpServerDef {
  ```
- `McpHandler` ← src/resources/mcp.ts:344 [EXTRACTED]
  ```
  export class McpHandler extends ResourceHandler {
  ```
- `teamRuleToOmpRule` ← src/resources/omp-rule.ts:20 [EXTRACTED]
  ```
  export function teamRuleToOmpRule(rawTeamRule: string): string {
  ```
- `opencodeRulesGlob` ← src/resources/opencode-config.ts:31 [EXTRACTED]
  ```
  export function opencodeRulesGlob(configFileAbs: string, rulesDirAbs: string): string {
  ```
- `opencodeProjectConfig` ← src/resources/opencode-config.ts:52 [EXTRACTED]
  ```
  export function opencodeProjectConfig(projectRoot: string): string {
  ```
- `opencodeProjectRuleGlobs` ← src/resources/opencode-config.ts:76 [EXTRACTED]
  ```
  export function opencodeProjectRuleGlobs(
  ```
- `opencodeRuleGlobs` ← src/resources/opencode-config.ts:106 [EXTRACTED]
  ```
  export function opencodeRuleGlobs(
  ```
- `reconcileOpencodeInstructionSet` ← src/resources/opencode-config.ts:138 [EXTRACTED]
  ```
  export async function reconcileOpencodeInstructionSet(
  ```
- `reconcileOpencodeInstructions` ← src/resources/opencode-config.ts:239 [EXTRACTED]
  ```
  export async function reconcileOpencodeInstructions(
  ```
- `readOpencodeInstructionList` ← src/resources/opencode-config.ts:254 [EXTRACTED]
  ```
  export async function readOpencodeInstructionList(configFile: string): Promise<JsonValue[] | null> {
  ```
- `opencodeContextReference` ← src/resources/opencode-config.ts:286 [EXTRACTED]
  ```
  export function opencodeContextReference(contextFile: string, scope: 'user' | 'project', projectRoot: string): OpencodeContextReference {
  ```
- `opencodeV1ClaudeFile` ← src/resources/opencode-config.ts:302 [EXTRACTED]
  ```
  export function opencodeV1ClaudeFile(home: string): string {
  ```
- `placesRecordOf` ← src/resources/places.ts:44 [EXTRACTED]
  ```
  export function placesRecordOf(record: Pick<CheckoutRecord, 'places' | 'skillDirs'> | undefined): PlacesRecord | undefined {
  ```
- `placesOf` ← src/resources/places.ts:51 [EXTRACTED]
  ```
  export async function placesOf(install: Install, host: Host = realHost()): Promise<PlacesRecord> {
  ```
- `sessionToolHomesOf` ← src/resources/places.ts:67 [EXTRACTED]
  ```
  export function sessionToolHomesOf(current: PlacesRecord, host: Host = realHost()): SessionToolHomes {
  ```
- `placesUnmoved` ← src/resources/places.ts:83 [EXTRACTED]
  ```
  export async function placesUnmoved(
  ```
- `samePlace` ← src/resources/places.ts:109 [EXTRACTED]
  ```
  export async function samePlace(a: string, b: string): Promise<boolean> {
  ```
- `amongPlaces` ← src/resources/places.ts:125 [EXTRACTED]
  ```
  export async function amongPlaces(place: string, places: readonly string[]): Promise<boolean> {
  ```
- `samePlaces` ← src/resources/places.ts:132 [EXTRACTED]
  ```
  export async function samePlaces(recorded: Places, current: Places): Promise<boolean> {
  ```
- `settlePlaces` ← src/resources/places.ts:162 [EXTRACTED]
  ```
  export async function settlePlaces({ previous, current, incomplete, followsSession }: {
  ```
- `recordPlaces` ← src/resources/places.ts:204 [EXTRACTED]
  ```
  export async function recordPlaces({ previous, current, incomplete, scopeLabel, host = realHost() }: {
  ```
- `teamRuleToQoderRule` ← src/resources/qoder-rule.ts:23 [EXTRACTED]
  ```
  export function teamRuleToQoderRule(rawTeamRule: string): string {
  ```
- `listRepoFilesRecursive` ← src/resources/repo-resource.ts:14 [EXTRACTED]
  ```
  export async function listRepoFilesRecursive(dir: string, baseDir = dir): Promise<string[]> {
  ```
- `placedCopy` ← src/resources/repo-resource.ts:44 [EXTRACTED]
  ```
  export async function placedCopy(
  ```
- `scanRepoResourceForPush` ← src/resources/repo-resource.ts:116 [EXTRACTED]
  ```
  export async function scanRepoResourceForPush(
  ```
- `pushRepoResourceItem` ← src/resources/repo-resource.ts:217 [EXTRACTED]
  ```
  export async function pushRepoResourceItem(
  ```
- `RepoResourceHandler` ← src/resources/repo-resource.ts:238 [EXTRACTED]
  ```
  export class RepoResourceHandler extends ResourceHandler {
  ```
- `RESOURCE_LAYOUTS` ← src/resources/resolver.ts:120 [EXTRACTED]
  ```
  export const RESOURCE_LAYOUTS = {
  ```
- `folderPlacesOf` ← src/resources/resolver.ts:150 [EXTRACTED]
  ```
  export function folderPlacesOf(file: string): string[] {
  ```
- `markerFolderOf` ← src/resources/resolver.ts:161 [EXTRACTED]
  ```
  export function markerFolderOf(layout: ResourceLayout<unknown>, file: string): string | undefined {
  ```
- `readFolderMarker` ← src/resources/resolver.ts:232 [EXTRACTED]
  ```
  export async function readFolderMarker(layout: ResourceLayout<unknown>, at: { readonly full: string; readonly path: string }): Promise<FolderMarkerRead> {
  ```
- `isLanguageVariant` ← src/resources/resolver.ts:294 [EXTRACTED]
  ```
  export function isLanguageVariant(base: string, file: string): boolean {
  ```
- `folderFilesNote` ← src/resources/resolver.ts:315 [EXTRACTED]
  ```
  export function folderFilesNote(folderPath: string, marker: string, files: readonly string[]): string {
  ```
- `isSymlink` ← src/resources/resolver.ts:503 [EXTRACTED]
  ```
  export async function isSymlink(file: string): Promise<boolean> {
  ```
- `Resources` ← src/resources/resolver.ts:685 [EXTRACTED]
  ```
  export const Resources = { list, resolve, survey, pick, layer, walk, inherited } as const;
  ```
- `RuleFolders` ← src/resources/rule-folders.ts:241 [EXTRACTED]
  ```
  export const RuleFolders = { isFolder, pathOf, isDelivered, deliveredNames, languageFile, readTextFile, text, composeText, variantNotes, render, sync, grant, grantSettingsFile } as const;
  ```
- `ruleFormatById` ← src/resources/rule-format.ts:75 [EXTRACTED]
  ```
  export function ruleFormatById(id: RuleFormatId): RuleFormat {
  ```
- `ruleFormatForTool` ← src/resources/rule-format.ts:80 [EXTRACTED]
  ```
  export function ruleFormatForTool(tool: string): RuleFormat | undefined {
  ```
- `renderRuleForTool` ← src/resources/rule-format.ts:92 [EXTRACTED]
  ```
  export function renderRuleForTool(tool: string, rawTeamRule: string): string {
  ```
- `deliveredRenders` ← src/resources/rule-format.ts:100 [EXTRACTED]
  ```
  export function deliveredRenders(tool: string): Array<(rawTeamRule: string) => string> {
  ```
- `flatStem` ← src/resources/rule-format.ts:105 [EXTRACTED]
  ```
  export function flatStem(name: string): string {
  ```
- `ruleStemsForTool` ← src/resources/rule-format.ts:117 [EXTRACTED]
  ```
  export function ruleStemsForTool(tool: string, teamNames: Iterable<string>): Map<string, string> {
  ```
- `flatStemSharers` ← src/resources/rule-format.ts:131 [EXTRACTED]
  ```
  export function flatStemSharers(tool: string, name: string, teamNames: Iterable<string>): string[] {
  ```
- `teamRuleNameForFile` ← src/resources/rule-format.ts:145 [EXTRACTED]
  ```
  export function teamRuleNameForFile(tool: string, stem: string, stems: ReadonlyMap<string, string>): string | undefined {
  ```
- `flatStemsOfRemoved` ← src/resources/rule-format.ts:163 [EXTRACTED]
  ```
  export function flatStemsOfRemoved(tool: string, removed: Iterable<string>, teamNames: Iterable<string>): Set<string> {
  ```
- `sharesRulesDirWithMember` ← src/resources/rule-format.ts:180 [EXTRACTED]
  ```
  export function sharesRulesDirWithMember(tool: string): boolean {
  ```
- `ruleFileExtensionForTool` ← src/resources/rule-format.ts:189 [EXTRACTED]
  ```
  export function ruleFileExtensionForTool(tool: string): RuleFormat['extension'] {
  ```
- `usesMdcRules` ← src/resources/rule-format.ts:194 [EXTRACTED]
  ```
  export function usesMdcRules(tool: string): boolean {
  ```
- `usesCopilotInstructions` ← src/resources/rule-format.ts:199 [EXTRACTED]
  ```
  export function usesCopilotInstructions(tool: string): boolean {
  ```
- `getsRulesFromSessionHook` ← src/resources/rule-format.ts:208 [EXTRACTED]
  ```
  export function getsRulesFromSessionHook(tool: string): boolean {
  ```
- `getsRulesFromExtension` ← src/resources/rule-format.ts:213 [EXTRACTED]
  ```
  export function getsRulesFromExtension(tool: string): boolean {
  ```
- `keptLegacyCopiesWarning` ← src/resources/rule-format.ts:266 [EXTRACTED]
  ```
  export function keptLegacyCopiesWarning(files: readonly string[], entry: LegacyRuleDir): string {
  ```
- `RULE_FILE_EXTENSIONS` ← src/resources/rule-format.ts:357 [EXTRACTED]
  ```
  export const RULE_FILE_EXTENSIONS = ['.instructions.md', '.mdc', '.md'] as const;
  ```
- `ruleStemFromFilename` ← src/resources/rule-format.ts:363 [EXTRACTED]
  ```
  export function ruleStemFromFilename(filename: string): string | null {
  ```
- `isLegacyCursorRuleFile` ← src/resources/rule-format.ts:378 [EXTRACTED]
  ```
  export function isLegacyCursorRuleFile(tool: string, filename: string): boolean {
  ```
- `RulesHandler` ← src/resources/rules.ts:70 [EXTRACTED]
  ```
  export class RulesHandler extends ResourceHandler {
  ```
- `readTeamRules` ← src/resources/rules.ts:1691 [EXTRACTED]
  ```
  export async function readTeamRules(repoPath: string): Promise<{ rules: ResourceItem[]; problems: ResourceDiagnostic[]; folderNotes: readonly ResourceDiagnostic[] }> {
  ```
- `rulesReceivingTools` ← src/resources/rules.ts:1762 [EXTRACTED]
  ```
  export async function rulesReceivingTools(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<readonly string[]> {
  ```
- `inlineRulesLabelOf` ← src/resources/rules.ts:1802 [EXTRACTED]
  ```
  export function inlineRulesLabelOf(tool: string): string | null {
  ```
- `inlineRulesLocationOf` ← src/resources/rules.ts:1814 [EXTRACTED]
  ```
  export async function inlineRulesLocationOf(tool: string, install: Install): Promise<Location<'blocks'> | null> {
  ```
- `unreadableConfigOf` ← src/resources/rules.ts:1819 [EXTRACTED]
  ```
  export function unreadableConfigOf(location: { readonly gates: readonly Gate[] }): Extract<Gate, { kind: 'readable-config' }> | undefined {
  ```
- `unreadRulesDir` ← src/resources/rules.ts:1836 [EXTRACTED]
  ```
  export function unreadRulesDir(tool: string, dir: string, localConfig: LocalConfig): LegacyRuleDir | undefined {
  ```
- `ruleOrigin` ← src/resources/rules.ts:1919 [EXTRACTED]
  ```
  export function ruleOrigin(tool: string, repoPath: string, relativePath: string): CopyOrigin {
  ```
- `ownsRuleCopy` ← src/resources/rules.ts:1946 [EXTRACTED]
  ```
  export async function ownsRuleCopy(
  ```
- `isLegacyLayoutCopy` ← src/resources/rules.ts:1966 [EXTRACTED]
  ```
  export async function isLegacyLayoutCopy(
  ```
- `inlinedRulesText` ← src/resources/rules.ts:2056 [EXTRACTED]
  ```
  export async function inlinedRulesText(rules: ResourceItem[], at: RuleTextContext): Promise<string> {
  ```
- `teamRulesBlock` ← src/resources/rules.ts:2081 [EXTRACTED]
  ```
  export async function teamRulesBlock(rules: ResourceItem[], at: RuleTextContext): Promise<string | null> {
  ```
- `teamRulesContext` ← src/resources/rules.ts:2114 [EXTRACTED]
  ```
  export async function teamRulesContext(teamConfig: TeamaiConfig, localConfig: LocalConfig): Promise<string | null> {
  ```
- `ruleChannelNotes` ← src/resources/rules.ts:2130 [EXTRACTED]
  ```
  export async function ruleChannelNotes(localConfig: LocalConfig): Promise<string[]> {
  ```
- `unknownSecretDeclarationKeys` ← src/resources/secrets.ts:44 [EXTRACTED]
  ```
  export function unknownSecretDeclarationKeys(declaration: WrittenSecretDeclaration): string[] {
  ```
- `readSecretsForEdit` ← src/resources/secrets.ts:108 [EXTRACTED]
  ```
  export async function readSecretsForEdit(
  ```
- `writeSecretsFile` ← src/resources/secrets.ts:131 [EXTRACTED]
  ```
  export async function writeSecretsFile(absolutePath: string, secrets: readonly object[]): Promise<void> {
  ```
- `resolveSecretDeclarations` ← src/resources/secrets.ts:156 [EXTRACTED]
  ```
  export async function resolveSecretDeclarations(
  ```
- `declaredSecretKeys` ← src/resources/secrets.ts:185 [EXTRACTED]
  ```
  export function declaredSecretKeys(declarations: Exclude<SecretDeclarations, { kind: 'failed' }>): ReadonlySet<string>;
  ```
- `CODEX_TOOL` ← src/resources/skills.ts:40 [EXTRACTED]
  ```
  export const CODEX_TOOL = 'codex';
  ```
- `readsCodexSharedSkills` ← src/resources/skills.ts:43 [EXTRACTED]
  ```
  export function readsCodexSharedSkills(tool: string): boolean {
  ```
- `mayDeleteSkillCopy` ← src/resources/skills.ts:48 [EXTRACTED]
  ```
  export async function mayDeleteSkillCopy(localConfig: LocalConfig, skillDir: string): Promise<boolean> {
  ```
- `describeOutsideSkillLink` ← src/resources/skills.ts:55 [EXTRACTED]
  ```
  export function describeOutsideSkillLink(skillDir: string): string {
  ```
- `codexSkillConflictLine` ← src/resources/skills.ts:69 [EXTRACTED]
  ```
  export function codexSkillConflictLine(skillName: string, configuredSkillsPath: string): string {
  ```
- `codexSkillsSplit` ← src/resources/skills.ts:122 [EXTRACTED]
  ```
  export async function codexSkillsSplit(
  ```
- `resolveSkillDestination` ← src/resources/skills.ts:155 [EXTRACTED]
  ```
  export async function resolveSkillDestination(
  ```
- `skillTargetsFor` ← src/resources/skills.ts:230 [EXTRACTED]
  ```
  export function skillTargetsFor(
  ```
- `skillOrigin` ← src/resources/skills.ts:290 [EXTRACTED]
  ```
  export function skillOrigin(repoPath: string, name: string): CopyOrigin {
  ```
- `ensureSkillFrontmatter` ← src/resources/skills.ts:316 [EXTRACTED]
  ```
  export async function ensureSkillFrontmatter(skillDir: string, skillName: string): Promise<boolean> {
  ```
- `withSkillFrontmatter` ← src/resources/skills.ts:344 [EXTRACTED]
  ```
  export function withSkillFrontmatter(content: string, skillName: string): string {
  ```
- `readTeamSkills` ← src/resources/skills.ts:428 [EXTRACTED]
  ```
  export async function readTeamSkills(repoPath: string): Promise<TeamSkillsRead> {
  ```
- `teamSkillItem` ← src/resources/skills.ts:482 [EXTRACTED]
  ```
  export function teamSkillItem(skill: TeamSkill): ResourceItem {
  ```
- `scanTeamRepoNamespaces` ← src/resources/skills.ts:491 [EXTRACTED]
  ```
  export async function scanTeamRepoNamespaces(repoPath: string): Promise<string[]> {
  ```
- `resolvePushSkillNamespaces` ← src/resources/skills.ts:553 [EXTRACTED]
  ```
  export async function resolvePushSkillNamespaces(localConfig: LocalConfig): Promise<string[] | null> {
  ```
- `recordedOrigin` ← src/resources/skills.ts:606 [EXTRACTED]
  ```
  export async function recordedOrigin<TCopy extends { dir: string }>(
  ```
- `createSkillPushItem` ← src/resources/skills.ts:655 [EXTRACTED]
  ```
  export function createSkillPushItem(input: {
  ```
- `readTeamSkillIndex` ← src/resources/skills.ts:920 [EXTRACTED]
  ```
  export async function readTeamSkillIndex(repoPath: string, scopedNamespaces: string[] | null): Promise<TeamSkillIndex> {
  ```
- `resolveDestination` ← src/resources/skills.ts:1014 [EXTRACTED]
  ```
  export async function resolveDestination(input: {
  ```
- `SkillsHandler` ← src/resources/skills.ts:1105 [EXTRACTED]
  ```
  export class SkillsHandler extends ResourceHandler {
  ```
- `splitRuleFrontmatter` ← src/resources/team-rule.ts:28 [EXTRACTED]
  ```
  export function splitRuleFrontmatter(raw: string): { block: string; body: string } {
  ```
- `teamRuleData` ← src/resources/team-rule.ts:68 [EXTRACTED]
  ```
  export function teamRuleData(raw: string): ParsedFields {
  ```
- `verbatimRule` ← src/resources/team-rule.ts:88 [EXTRACTED]
  ```
  export const verbatimRule = (rawTeamRule: string): string => rawTeamRule;
  ```
- `teamRuleBody` ← src/resources/team-rule.ts:96 [EXTRACTED]
  ```
  export function teamRuleBody(raw: string): string {
  ```
- `rulePaths` ← src/resources/team-rule.ts:126 [EXTRACTED]
  ```
  export function rulePaths(data: ParsedFields): string[] {
  ```
- `expandBraces` ← src/resources/team-rule.ts:147 [EXTRACTED]
  ```
  export function expandBraces(glob: string): string[] {
  ```
- `mergeRuleBodyIntoTeamMd` ← src/resources/team-rule.ts:186 [EXTRACTED]
  ```
  export function mergeRuleBodyIntoTeamMd(rawToolRule: string, existingTeamMd: string | null): string {
  ```
- `ruleBodyEqualsTeamMd` ← src/resources/team-rule.ts:207 [EXTRACTED]
  ```
  export function ruleBodyEqualsTeamMd(rawToolRule: string, rawTeamRule: string): boolean {
  ```
- `TeamSkillSource` ← src/resources/team-skill-source.ts:100 [EXTRACTED]
  ```
  export const TeamSkillSource = { isFile, isDescribed, describes, name, skillMd, files, fileAt, copyTo, equalsCopy, isInCopy, sameFiles } as const;
  ```
- `teamRuleToTraeRule` ← src/resources/trae-rule.ts:24 [EXTRACTED]
  ```
  export function teamRuleToTraeRule(rawTeamRule: string): string {
  ```
- `WorkflowsHandler` ← src/resources/workflows.ts:25 [EXTRACTED]
  ```
  export class WorkflowsHandler extends RepoResourceHandler {
  ```
- `adoptionScorerName` ← src/scorers/adoption.ts:34 [EXTRACTED]
  ```
  export function adoptionScorerName(doc: string): string {
  ```
- `carriedMarks` ← src/scorers/attempts-upgrade.ts:130 [EXTRACTED]
  ```
  export async function carriedMarks(config: LocalConfig, now: string): Promise<Array<{ key: MarkKey; mark: CarriedMark }>> {
  ```
- `batchesScorers` ← src/scorers/batch.ts:13 [EXTRACTED]
  ```
  export function batchesScorers(layers: { step?: boolean; workflow?: boolean; team?: boolean }): boolean {
  ```
- `judgeCallKey` ← src/scorers/batch.ts:39 [EXTRACTED]
  ```
  export function judgeCallKey({ name, model, tool, require, stages, isAlone, family }: JudgeCallFacts, batch: boolean): string {
  ```
- `JudgeAnswerSchema` ← src/scorers/batch.ts:50 [EXTRACTED]
  ```
  export const JudgeAnswerSchema = z.union([LabelAnswerSchema, BatchAnswerSchema]);
  ```
- `verdictsOf` ← src/scorers/batch.ts:65 [EXTRACTED]
  ```
  export function verdictsOf<T>(
  ```
- `scorerSourceHash` ← src/scorers/cache.ts:38 [EXTRACTED]
  ```
  export function scorerSourceHash(content: string, files: readonly ScorerFolderFile[] = []): string {
  ```
- `SCORING_FILE` ← src/scorers/cache.ts:62 [EXTRACTED]
  ```
  export const SCORING_FILE = 'scoring.yaml';
  ```
- `NOT_A_SCORER` ← src/scorers/cache.ts:64 [EXTRACTED]
  ```
  export const NOT_A_SCORER = 'not a scorer file; scorers/ holds <name>.md and <namespace>/<name>.md scorers, <name>/SCORER.md and <namespace>/<name>/SCORER.md scorer folders, scoring.yaml settings and an optional README.md';
  ```
- `defaultScorerRubric` ← src/scorers/cache.ts:90 [EXTRACTED]
  ```
  export async function defaultScorerRubric(config: LocalConfig, name: DefaultScorerName): Promise<{ file: string; content: string; overridden: boolean }> {
  ```
- `loadCachedScorer` ← src/scorers/cache.ts:122 [EXTRACTED]
  ```
  export async function loadCachedScorer(config: LocalConfig, name: string): Promise<CachedScorer | null> {
  ```
- `anyScorerChecks` ← src/scorers/cache.ts:134 [EXTRACTED]
  ```
  export async function anyScorerChecks(config: LocalConfig, names: readonly string[]): Promise<boolean> {
  ```
- `cachedScorerNames` ← src/scorers/cache.ts:143 [EXTRACTED]
  ```
  export async function cachedScorerNames(config: LocalConfig): Promise<string[]> {
  ```
- `pinScorers` ← src/scorers/cache.ts:155 [EXTRACTED]
  ```
  export async function pinScorers(config: LocalConfig, names: Iterable<string>): Promise<Record<string, PinnedScorer>> {
  ```
- `scorerNamespaces` ← src/scorers/cache.ts:230 [EXTRACTED]
  ```
  export async function scorerNamespaces(config: LocalConfig, dirs: readonly string[]): Promise<{ active: string[]; shared: string[] }> {
  ```
- `scorerSources` ← src/scorers/cache.ts:261 [EXTRACTED]
  ```
  export function scorerSources({ relativePath, content, files }: { relativePath: string; content: string; files?: readonly ScorerFolderFile[] }): Array<{ path: string; content: string; readsCrlfAsLf?: boolean }> {
  ```
- `syncScorerDefinitions` ← src/scorers/cache.ts:291 [EXTRACTED]
  ```
  export async function syncScorerDefinitions(config: LocalConfig, options: SyncScorerOptions = {}): Promise<SyncScorerResult> {
  ```
- `runCheckAt` ← src/scorers/check-run.ts:67 [EXTRACTED]
  ```
  export async function runCheckAt(input: {
  ```
- `restoreProtected` ← src/scorers/check-run.ts:103 [EXTRACTED]
  ```
  export async function restoreProtected({ clone, startingCommit, protect, sources, env, expiresAt }: {
  ```
- `writeAdded` ← src/scorers/check-run.ts:231 [EXTRACTED]
  ```
  export async function writeAdded({ clone, add, sources, env, expiresAt }: {
  ```
- `CHECK_CAUSES` ← src/scorers/check.ts:16 [EXTRACTED]
  ```
  export const CHECK_CAUSES = ['not_found', 'not_executable', 'signal', 'timeout', 'spawn_failed', 'prepare_failed'] as const;
  ```
- `CHECK_RESULTS` ← src/scorers/check.ts:29 [EXTRACTED]
  ```
  export const CHECK_RESULTS = ['passed', 'failed', 'could_not_run'] as const satisfies ReadonlyArray<CheckVerdict['verdict']>;
  ```
- `CheckOutputSchema` ← src/scorers/check.ts:36 [EXTRACTED]
  ```
  export const CheckOutputSchema = z.discriminatedUnion('result', [
  ```
- `checkLabel` ← src/scorers/check.ts:51 [EXTRACTED]
  ```
  export function checkLabel<TLabel extends { score: number }>(result: 'passed' | 'failed', labels: readonly [TLabel, ...TLabel[]]): TLabel {
  ```
- `isRelativePath` ← src/scorers/check.ts:59 [EXTRACTED]
  ```
  export function isRelativePath(value: string): boolean {
  ```
- `RepoPathSchema` ← src/scorers/check.ts:68 [EXTRACTED]
  ```
  export const RepoPathSchema = z.string().min(1).refine(
  ```
- `segmentPattern` ← src/scorers/check.ts:78 [EXTRACTED]
  ```
  export function segmentPattern(segment: string): RegExp | undefined {
  ```
- `CheckRunSchema` ← src/scorers/check.ts:99 [EXTRACTED]
  ```
  export const CheckRunSchema = z.object({
  ```
- `AddedSchema` ← src/scorers/check.ts:109 [EXTRACTED]
  ```
  export const AddedSchema = z.object({ kind: z.enum(['solution', 'suite']), commit: CommitSchema, paths: z.array(z.string().min(1)).nonempty() }).strict();
  ```
- `checkVerdict` ← src/scorers/check.ts:125 [EXTRACTED]
  ```
  export function checkVerdict(exit: CommandExit, platform: NodeJS.Platform): CheckVerdict {
  ```
- `isScorerFile` ← src/scorers/definition.ts:17 [EXTRACTED]
  ```
  export function isScorerFile(value: string): boolean {
  ```
- `STAGES` ← src/scorers/definition.ts:35 [EXTRACTED]
  ```
  export const STAGES = ['check', 'ci', 'protected'] as const;
  ```
- `formatScorerDiagnostic` ← src/scorers/definition.ts:105 [EXTRACTED]
  ```
  export function formatScorerDiagnostic(diagnostic: ScorerDiagnostic): string {
  ```
- `parseScorer` ← src/scorers/definition.ts:124 [EXTRACTED]
  ```
  export function parseScorer(relativePath: string, content: string): ParsedScorer {
  ```
- `prepareCheckPlace` ← src/scorers/engine-hooks.ts:34 [EXTRACTED]
  ```
  export async function prepareCheckPlace(input: Parameters<typeof BenchmarkChecks.prepareCheckPlace>[0]): ReturnType<typeof BenchmarkChecks.prepareCheckPlace> {
  ```
- `outdatedBenchmarkPlan` ← src/scorers/engine-hooks.ts:39 [EXTRACTED]
  ```
  export async function outdatedBenchmarkPlan(run: RunState): Promise<ReturnType<typeof BenchmarkChecks.outdatedBenchmarkPlan>> {
  ```
- `decideCheckReport` ← src/scorers/engine-hooks.ts:45 [EXTRACTED]
  ```
  export async function decideCheckReport(input: Parameters<typeof BenchmarkChecks.decideCheckReport>[0]): ReturnType<typeof BenchmarkChecks.decideCheckReport> {
  ```
- `startedByPasses` ← src/scorers/engine-hooks.ts:54 [EXTRACTED]
  ```
  export async function startedByPasses(config: LocalConfig, runId: string, options: { client: Pick<WorkflowClient, 'start'>; mode: RunMode }): Promise<StartedRun[]> {
  ```
- `scoredLabels` ← src/scorers/engine-hooks.ts:63 [EXTRACTED]
  ```
  export function scoredLabels(outputs: Record<string, JsonValue> | undefined): ScoredLabels {
  ```
- `verifiedScorers` ← src/scorers/engine-hooks.ts:71 [EXTRACTED]
  ```
  export async function verifiedScorers(config: LocalConfig, names: readonly string[], run?: RunState): Promise<{ ok: true; scorers: string[] } | { ok: false; reason: string }> {
  ```
- `removeStagedEvidence` ← src/scorers/engine-hooks.ts:79 [EXTRACTED]
  ```
  export async function removeStagedEvidence(config: LocalConfig, subjects: ReadonlyArray<{ runId: string; step: string; pass: number }>): Promise<void> {
  ```
- `rubricsOf` ← src/scorers/evidence-dir.ts:77 [EXTRACTED]
  ```
  export function rubricsOf(scorers: GroupRecord['scorers'], dir?: string): Rubrics | undefined {
  ```
- `readRecord` ← src/scorers/evidence-dir.ts:142 [EXTRACTED]
  ```
  export async function readRecord<T>(file: string, schema: z.ZodType<T>): Promise<T | undefined> {
  ```
- `EvidenceDir` ← src/scorers/evidence-dir.ts:249 [EXTRACTED]
  ```
  export const EvidenceDir = {
  ```
- `EVIDENCE_GAPS` ← src/scorers/evidence.ts:10 [EXTRACTED]
  ```
  export const EVIDENCE_GAPS = [
  ```
- `EVIDENCE_MAX_CHARS` ← src/scorers/evidence.ts:18 [EXTRACTED]
  ```
  export const EVIDENCE_MAX_CHARS = 200_000;
  ```
- `SESSION_MAX_CHARS` ← src/scorers/evidence.ts:21 [EXTRACTED]
  ```
  export const SESSION_MAX_CHARS = 80_000;
  ```
- `SUBAGENT_MAX_CHARS` ← src/scorers/evidence.ts:22 [EXTRACTED]
  ```
  export const SUBAGENT_MAX_CHARS = 20_000;
  ```
- `TOOL_CALL_MAX_CHARS` ← src/scorers/evidence.ts:25 [EXTRACTED]
  ```
  export const TOOL_CALL_MAX_CHARS = 2_000;
  ```
- `evidenceDirOf` ← src/scorers/evidence.ts:30 [EXTRACTED]
  ```
  export function evidenceDirOf(scoresDir: string, attempt: string): string {
  ```
- `subjectEvidenceDirOf` ← src/scorers/evidence.ts:38 [EXTRACTED]
  ```
  export function subjectEvidenceDirOf(scoresDir: string, subject: RunSubject): string {
  ```
- `removeSubjectEvidence` ← src/scorers/evidence.ts:43 [EXTRACTED]
  ```
  export async function removeSubjectEvidence(scoresDir: string, subjects: readonly RunSubject[]): Promise<void> {
  ```
- `keepEnds` ← src/scorers/evidence.ts:54 [EXTRACTED]
  ```
  export function keepEnds(text: string, max: number): string {
  ```
- `rubricPrompt` ← src/scorers/evidence.ts:71 [EXTRACTED]
  ```
  export function rubricPrompt(rubrics: Rubrics): string {
  ```
- `answerSchema` ← src/scorers/evidence.ts:97 [EXTRACTED]
  ```
  export function answerSchema(rubrics: Rubrics): JsonValue {
  ```
- `fencedEvidence` ← src/scorers/evidence.ts:115 [EXTRACTED]
  ```
  export function fencedEvidence(sections: ReadonlyArray<{ title: string; body: string }>, files: string): string {
  ```
- `isEvidenceReady` ← src/scorers/evidence.ts:131 [EXTRACTED]
  ```
  export async function isEvidenceReady(dir: string): Promise<boolean> {
  ```
- `writeEvidence` ← src/scorers/evidence.ts:139 [EXTRACTED]
  ```
  export async function writeEvidence(dir: string, fill: (tmp: string) => Promise<void>): Promise<void> {
  ```
- `sweepEvidence` ← src/scorers/evidence.ts:156 [EXTRACTED]
  ```
  export async function sweepEvidence(scoresDir: string, remove: ReadonlySet<string>): Promise<void> {
  ```
- `FailureLinks` ← src/scorers/failure-links.ts:77 [EXTRACTED]
  ```
  export const FailureLinks = { read } as const;
  ```
- `SCORER_MARKER` ← src/scorers/folder.ts:18 [EXTRACTED]
  ```
  export const SCORER_MARKER = FOLDER_MARKERS.scorers.marker;
  ```
- `ScorerFolderFileSchema` ← src/scorers/folder.ts:29 [EXTRACTED]
  ```
  export const ScorerFolderFileSchema = z.object({ path: FolderPathSchema, content: z.string() });
  ```
- `ScorerFolder` ← src/scorers/folder.ts:84 [EXTRACTED]
  ```
  export const ScorerFolder = { marks, read, mentions, fileFormProblem, dirIn, render, write } as const;
  ```
- `GeneratedQuestions` ← src/scorers/generated-questions.ts:65 [EXTRACTED]
  ```
  export const GeneratedQuestions = {
  ```
- `scoresDir` ← src/scorers/home.ts:6 [EXTRACTED]
  ```
  export function scoresDir(config: LocalConfig): string {
  ```
- `scoresLocked` ← src/scorers/home.ts:14 [EXTRACTED]
  ```
  export async function scoresLocked<T>(config: LocalConfig, name: 'labels' | 'marks', change: () => Promise<T>): Promise<{ status: 'done'; value: T } | { status: 'busy' }> {
  ```
- `scoringUnavailable` ← src/scorers/home.ts:38 [EXTRACTED]
  ```
  export function scoringUnavailable(config: LocalConfig): string | undefined {
  ```
- `scorerIsolationSource` ← src/scorers/isolation.ts:8 [EXTRACTED]
  ```
  export function scorerIsolationSource(scorer: string, relativePath = `scorers/${scorer}.md`): string {
  ```
- `requiredIsolation` ← src/scorers/isolation.ts:30 [EXTRACTED]
  ```
  export function requiredIsolation(settings: readonly IsolationSetting[]): RequiredIsolation {
  ```
- `unknownIsolationText` ← src/scorers/isolation.ts:42 [EXTRACTED]
  ```
  export function unknownIsolationText({ source, value }: { source: string; value: string }): string {
  ```
- `scorerModelUnavailableText` ← src/scorers/judge-model.ts:23 [EXTRACTED]
  ```
  export function scorerModelUnavailableText(scorer: string, asked: string, cause: string, reason: keyof typeof NO_MODEL_FIX): string {
  ```
- `chooseJudgeModel` ← src/scorers/judge-model.ts:39 [EXTRACTED]
  ```
  export function chooseJudgeModel<Tool extends string>(aliases: ModelAliases, scorer: Pick<ScorerDefinition, 'name' | 'model'>, tools: readonly Tool[]): JudgeModelChoice<Tool> {
  ```
- `verifiedScorers` ← src/scorers/judges-here.ts:21 [EXTRACTED]
  ```
  export async function verifiedScorers(config: LocalConfig, names: readonly string[], pinned?: Record<string, PinnedScorer>): Promise<{ ok: true; scorers: string[] } | { ok: false; reason: string }> {
  ```
- `judgeUnavailable` ← src/scorers/judges-here.ts:39 [EXTRACTED]
  ```
  export async function judgeUnavailable(config: LocalConfig, scorers: Record<string, { pin: PinnedScorer; tool: string }>): Promise<string | undefined> {
  ```
- `SCORE_WORKFLOW` ← src/scorers/judging-workflows.ts:7 [EXTRACTED]
  ```
  export const SCORE_WORKFLOW = 'teamai-score';
  ```
- `FINISHED_WORKFLOW` ← src/scorers/judging-workflows.ts:10 [EXTRACTED]
  ```
  export const FINISHED_WORKFLOW = 'teamai-finished-sessions';
  ```
- `TRY_SCORER_WORKFLOW` ← src/scorers/judging-workflows.ts:13 [EXTRACTED]
  ```
  export const TRY_SCORER_WORKFLOW = 'teamai-try-scorer';
  ```
- `ScoreItem` ← src/scorers/judging-workflows.ts:37 [EXTRACTED]
  ```
  export const ScoreItem = { stepOf, groupOf } as const;
  ```
- `reasoningPath` ← src/scorers/label-store.ts:25 [EXTRACTED]
  ```
  export function reasoningPath(config: LocalConfig, id: string): string {
  ```
- `shareFailedLabelHint` ← src/scorers/label-store.ts:33 [EXTRACTED]
  ```
  export function shareFailedLabelHint(reasoningFile: string, sessionId?: string): string {
  ```
- `LabelStore` ← src/scorers/label-store.ts:181 [EXTRACTED]
  ```
  export const LabelStore = {
  ```
- `RunSubjectSchema` ← src/scorers/label.ts:14 [EXTRACTED]
  ```
  export const RunSubjectSchema = z.object({ runId: z.string().min(1), step: z.string().min(1), pass: z.number().int().positive() });
  ```
- `SessionSubjectSchema` ← src/scorers/label.ts:18 [EXTRACTED]
  ```
  export const SessionSubjectSchema = z.object({ platform: z.string().min(1), sessionId: z.string().min(1) });
  ```
- `sumUsage` ← src/scorers/label.ts:23 [EXTRACTED]
  ```
  export function sumUsage(first: ConfinedUsage | undefined, second: ConfinedUsage | undefined): ConfinedUsage | undefined {
  ```
- `ModelJudgeSchema` ← src/scorers/label.ts:46 [EXTRACTED]
  ```
  export const ModelJudgeSchema = z.object({
  ```
- `DECIDERS` ← src/scorers/label.ts:87 [EXTRACTED]
  ```
  export const DECIDERS = ['check', 'ci', 'protected', 'judge'] as const;
  ```
- `JUDGE_FAILURES` ← src/scorers/label.ts:95 [EXTRACTED]
  ```
  export const JUDGE_FAILURES = ['judge_failed', 'lease_expired', 'evidence_empty', 'judge_answer_invalid', 'judge_tool_unavailable', 'check_could_not_run'] as const;
  ```
- `isStageDecider` ← src/scorers/label.ts:104 [EXTRACTED]
  ```
  export function isStageDecider(by: Decider | undefined): boolean {
  ```
- `ScoreLabelSchema` ← src/scorers/label.ts:119 [EXTRACTED]
  ```
  export const ScoreLabelSchema = z.discriminatedUnion('source', [
  ```
- `SessionLabelContextSchema` ← src/scorers/label.ts:142 [EXTRACTED]
  ```
  export const SessionLabelContextSchema = SessionLabelSchema.pick({ agent: true, used: true, runMode: true }).required({ used: true }).extend({ prompt: z.string() });
  ```
- `parseScoreLabel` ← src/scorers/label.ts:147 [EXTRACTED]
  ```
  export function parseScoreLabel(value: JsonValue): ScoreLabel | undefined {
  ```
- `parseScoreLabels` ← src/scorers/label.ts:154 [EXTRACTED]
  ```
  export function parseScoreLabels(text: string): ScoreLabel[] {
  ```
- `labelJudge` ← src/scorers/label.ts:198 [EXTRACTED]
  ```
  export function labelJudge(label: Pick<KeyedLabel, 'judge' | 'decidedBy'>): JudgeCohort {
  ```
- `labelId` ← src/scorers/label.ts:212 [EXTRACTED]
  ```
  export function labelId(label: KeyedLabel): string {
  ```
- `labelVersion` ← src/scorers/label.ts:220 [EXTRACTED]
  ```
  export function labelVersion(label: ScoreLabel): string {
  ```
- `newestLabels` ← src/scorers/label.ts:225 [EXTRACTED]
  ```
  export function newestLabels(labels: Iterable<ScoreLabel>): ScoreLabel[] {
  ```
- `MARK_LAPSES` ← src/scorers/marks.ts:19 [EXTRACTED]
  ```
  export const MARK_LAPSES = 4;
  ```
- `MARK_WINDOW_MS` ← src/scorers/marks.ts:22 [EXTRACTED]
  ```
  export const MARK_WINDOW_MS = 14 * 24 * 60 * 60 * 1000;
  ```
- `DEMANDS` ← src/scorers/marks.ts:24 [EXTRACTED]
  ```
  export const DEMANDS = ['auto', 'named'] as const;
  ```
- `Marks` ← src/scorers/marks.ts:374 [EXTRACTED]
  ```
  export const Marks = {
  ```
- `NamedSubject` ← src/scorers/named-subject.ts:221 [EXTRACTED]
  ```
  export const NamedSubject = { ofPass, ofSession } as const;
  ```
- `PassScoring` ← src/scorers/pass-scoring.ts:170 [EXTRACTED]
  ```
  export const PassScoring = {
  ```
- `PinnedScorerSchema` ← src/scorers/pin.ts:9 [EXTRACTED]
  ```
  export const PinnedScorerSchema = z.object({
  ```
- `pinnedDefinition` ← src/scorers/pin.ts:32 [EXTRACTED]
  ```
  export function pinnedDefinition(name: string, pin: PinnedScorer): ScorerDefinition | undefined {
  ```
- `DIMENSIONS_OFFERED` ← src/scorers/results.ts:54 [EXTRACTED]
  ```
  export const DIMENSIONS_OFFERED = ['tool', 'model', 'teamRevision', 'definition', 'role', 'project', 'tag', 'fingerprint', 'skill', 'decidedBy'] as const;
  ```
- `FAILING_PAGE` ← src/scorers/results.ts:138 [EXTRACTED]
  ```
  export const FAILING_PAGE = 25;
  ```
- `FAILING_MAX` ← src/scorers/results.ts:141 [EXTRACTED]
  ```
  export const FAILING_MAX = 1000;
  ```
- `SCORER_WINDOWS` ← src/scorers/results.ts:291 [EXTRACTED]
  ```
  export const SCORER_WINDOWS = [7, 30, 90, 180] as const;
  ```
- `ScorerResults` ← src/scorers/results.ts:733 [EXTRACTED]
  ```
  export const ScorerResults = {
  ```
- `RunJudging` ← src/scorers/run-judging.ts:170 [EXTRACTED]
  ```
  export const RunJudging = {
  ```
- `RunScorers` ← src/scorers/run-scorers.ts:97 [EXTRACTED]
  ```
  export const RunScorers = {
  ```
- `isSampled` ← src/scorers/sampling.ts:10 [EXTRACTED]
  ```
  export function isSampled(scorer: string, subject: RunSubject | SessionSubject, samplingRate: number): boolean {
  ```
- `isKeySampled` ← src/scorers/sampling.ts:15 [EXTRACTED]
  ```
  export function isKeySampled(key: JsonObject, rate: number): boolean {
  ```
- `ScoreAnswer` ← src/scorers/score-answer.ts:224 [EXTRACTED]
  ```
  export const ScoreAnswer = { of } as const;
  ```
- `ScoreAttempt` ← src/scorers/score-attempt.ts:109 [EXTRACTED]
  ```
  export const ScoreAttempt = {
  ```
- `LABEL_CODES` ← src/scorers/score-labels.ts:78 [EXTRACTED]
  ```
  export const LABEL_CODES = [...JUDGE_FAILURES, 'ci_pending'] as const;
  ```
- `keepsLabelsLocal` ← src/scorers/score-labels.ts:299 [EXTRACTED]
  ```
  export function keepsLabelsLocal(run: RunState, step: string): boolean {
  ```
- `ScoreLabels` ← src/scorers/score-labels.ts:303 [EXTRACTED]
  ```
  export const ScoreLabels = {
  ```
- `ScoreOverride` ← src/scorers/score-override.ts:260 [EXTRACTED]
  ```
  export const ScoreOverride = { problems, callerWarnings, callerProblems } as const;
  ```
- `plannedSessionPins` ← src/scorers/score-plan.ts:127 [EXTRACTED]
  ```
  export async function plannedSessionPins(attempt: ScoreAttempt, subject: Exclude<Subject, { kind: 'run' }>, names: readonly string[]): Promise<Record<string, PinnedScorer>> {
  ```
- `markFacts` ← src/scorers/score-plan.ts:168 [EXTRACTED]
  ```
  export function markFacts(config: LocalConfig, now: string): MarkFacts {
  ```
- `scorerStages` ← src/scorers/score-plan.ts:183 [EXTRACTED]
  ```
  export function scorerStages(attempt: ScoreAttempt, definition: Pick<ScorerDefinition, 'stages' | 'check'>): Stage[] {
  ```
- `judgeablePass` ← src/scorers/score-plan.ts:202 [EXTRACTED]
  ```
  export async function judgeablePass(config: LocalConfig, subject: RunSubject): Promise<{ ok: true; config: LocalConfig; run: RunState; pass: RunPass; step: WorkflowStep } | Refusal> {
  ```
- `planGroups` ← src/scorers/score-plan.ts:358 [EXTRACTED]
  ```
  export async function planGroups(request: PlanRequest): Promise<{ ok: true; groups: PlanGroup[] } | Refusal> {
  ```
- `CHECK_TIMEOUT_MS` ← src/scorers/score-stage.ts:19 [EXTRACTED]
  ```
  export const CHECK_TIMEOUT_MS = 30 * 60 * 1000;
  ```
- `StageRecordSchema` ← src/scorers/score-stage.ts:22 [EXTRACTED]
  ```
  export const StageRecordSchema = z.discriminatedUnion('kind', [
  ```
- `ScoreStage` ← src/scorers/score-stage.ts:89 [EXTRACTED]
  ```
  export const ScoreStage = {
  ```
- `ScoreSubjects` ← src/scorers/score-subjects.ts:111 [EXTRACTED]
  ```
  export const ScoreSubjects = {
  ```
- `evidencePlan` ← src/scorers/scoring-evidence.ts:41 [EXTRACTED]
  ```
  export function evidencePlan(run: RunState, subject: RunSubject, settling?: RunPass) {
  ```
- `isDelivered` ← src/scorers/scoring-evidence.ts:89 [EXTRACTED]
  ```
  export function isDelivered(run: RunState, subject: RunSubject): boolean {
  ```
- `judgedFacts` ← src/scorers/scoring-evidence.ts:99 [EXTRACTED]
  ```
  export function judgedFacts(run: RunState, subject: RunSubject): JudgedFacts {
  ```
- `missingEvidence` ← src/scorers/scoring-evidence.ts:121 [EXTRACTED]
  ```
  export async function missingEvidence(config: LocalConfig, run: RunState, subject: RunSubject): Promise<string[]> {
  ```
- `collectEvidence` ← src/scorers/scoring-evidence.ts:244 [EXTRACTED]
  ```
  export async function collectEvidence(
  ```
- `stageEvidence` ← src/scorers/scoring-evidence.ts:342 [EXTRACTED]
  ```
  export async function stageEvidence(config: LocalConfig, run: RunState, subject: RunSubject, source: {
  ```
- `evidenceHash` ← src/scorers/scoring-evidence.ts:366 [EXTRACTED]
  ```
  export async function evidenceHash(dir: string): Promise<string | undefined> {
  ```
- `buildEvidence` ← src/scorers/scoring-evidence.ts:384 [EXTRACTED]
  ```
  export async function buildEvidence(config: LocalConfig, run: RunState, subject: RunSubject, rubrics: Rubrics, dir: string): Promise<{ ok: true } | { ok: false; code: 'evidence_empty' }> {
  ```
- `failingLabel` ← src/scorers/scoring-stages.ts:34 [EXTRACTED]
  ```
  export function failingLabel(definition: Pick<ScorerDefinition, 'labels' | 'passingScore'>): ScorerLabel {
  ```
- `passOf` ← src/scorers/scoring-stages.ts:40 [EXTRACTED]
  ```
  export const passOf = (run: RunState, subject: RunSubject): StepPass | undefined =>
  ```
- `ciStage` ← src/scorers/scoring-stages.ts:48 [EXTRACTED]
  ```
  export async function ciStage(run: RunState, subject: RunSubject, pass: StepPass | undefined): Promise<CiVerdict> {
  ```
- `protectedStage` ← src/scorers/scoring-stages.ts:73 [EXTRACTED]
  ```
  export function protectedStage(pass: StepPass | undefined): StageVerdict {
  ```
- `checkStage` ← src/scorers/scoring-stages.ts:83 [EXTRACTED]
  ```
  export async function checkStage(run: RunState, subject: RunSubject, pass: StepPass | undefined, { scorer, check, expiresAt }: StageCheck): Promise<StageVerdict> {
  ```
- `parseScoringFile` ← src/scorers/settings.ts:55 [EXTRACTED]
  ```
  export function parseScoringFile(relativePath: string, text: string): ScoringFileRead {
  ```
- `SESSION_DAILY_LIMIT` ← src/scorers/settings.ts:136 [EXTRACTED]
  ```
  export const SESSION_DAILY_LIMIT = 10;
  ```
- `upvoteJudgeAliasNotes` ← src/scorers/settings.ts:225 [EXTRACTED]
  ```
  export function upvoteJudgeAliasNotes(): string[] {
  ```
- `scopeScoring` ← src/scorers/settings.ts:259 [EXTRACTED]
  ```
  export async function scopeScoring(config: LocalConfig): Promise<ScopeScoring> {
  ```
- `skillsEvidence` ← src/scorers/skill-evidence.ts:26 [EXTRACTED]
  ```
  export function skillsEvidence(
  ```
- `availableTeamSkills` ← src/scorers/skill-evidence.ts:49 [EXTRACTED]
  ```
  export function availableTeamSkills(captures: SkillCaptures): AvailableSkill[] | undefined {
  ```
- `ROUTING_PREFIX` ← src/scorers/skill-routing.ts:19 [EXTRACTED]
  ```
  export const ROUTING_PREFIX = 'teamai:routing:';
  ```
- `isRoutingScorer` ← src/scorers/skill-routing.ts:22 [EXTRACTED]
  ```
  export function isRoutingScorer(value: string): boolean {
  ```
- `routingScorerName` ← src/scorers/skill-routing.ts:27 [EXTRACTED]
  ```
  export function routingScorerName({ name, namespace }: AvailableSkill): string {
  ```
- `parseRoutingScorer` ← src/scorers/skill-routing.ts:32 [EXTRACTED]
  ```
  export function parseRoutingScorer(value: string): { skill: string; namespace?: string } | undefined {
  ```
- `routingSkillOf` ← src/scorers/skill-routing.ts:45 [EXTRACTED]
  ```
  export function routingSkillOf(name: { skill: string; namespace?: string }, available: readonly AvailableSkill[]): AvailableSkill | undefined {
  ```
- `routingScorer` ← src/scorers/skill-routing.ts:54 [EXTRACTED]
  ```
  export function routingScorer(rubric: string, skill: AvailableSkill): GeneratedQuestion {
  ```
- `routingScorers` ← src/scorers/skill-routing.ts:62 [EXTRACTED]
  ```
  export async function routingScorers(config: LocalConfig, skills: readonly AvailableSkill[]): Promise<GeneratedQuestion[]> {
  ```
- `routingQuestionOf` ← src/scorers/skill-routing.ts:88 [EXTRACTED]
  ```
  export async function routingQuestionOf(config: LocalConfig, value: string, available: readonly AvailableSkill[] | undefined): Promise<{ ok: true; question: GeneratedQuestion } | { ok: false; why: string }> {
  ```
- `Subject` ← src/scorers/subject.ts:47 [EXTRACTED]
  ```
  export const Subject = {
  ```
- `formatUnknownScorer` ← src/scorers/team-sync.ts:19 [EXTRACTED]
  ```
  export function formatUnknownScorer(unknown: UnknownScorer): string {
  ```
- `syncScorersThenWorkflows` ← src/scorers/team-sync.ts:120 [EXTRACTED]
  ```
  export async function syncScorersThenWorkflows(config: LocalConfig, options: SyncScorerOptions = {}): Promise<SyncScoredWorkflowsResult> {
  ```
- `refused` ← src/scorers/tried-file.ts:12 [EXTRACTED]
  ```
  export function refused(code: string, message: string): Refusal {
  ```
- `TriedFile` ← src/scorers/tried-file.ts:78 [EXTRACTED]
  ```
  export const TriedFile = { readAll } as const;
  ```
- `TryScorer` ← src/scorers/try-scorer.ts:199 [EXTRACTED]
  ```
  export const TryScorer = { prepare, report } as const;
  ```
- `noAdapter` ← src/session-flow/agent-session.ts:147 [EXTRACTED]
  ```
  export function noAdapter(
  ```
- `recordedToolRoots` ← src/session-flow/agent-session.ts:192 [EXTRACTED]
  ```
  export const recordedToolRoots = (cwd: string | undefined): Promise<ToolRoots> =>
  ```
- `toolRootsLookup` ← src/session-flow/agent-session.ts:198 [EXTRACTED]
  ```
  export function toolRootsLookup(): ToolRootsLookup {
  ```
- `writeCopyOnce` ← src/session-flow/agent-session.ts:304 [EXTRACTED]
  ```
  export async function writeCopyOnce(
  ```
- `sessionKey` ← src/session-flow/agent-session.ts:592 [EXTRACTED]
  ```
  export const sessionKey = ({ platform, sessionId }: Pick<AgentSessionRef, 'platform' | 'sessionId'>): string => `${platform}\0${sessionId}`;
  ```
- `AgentSession` ← src/session-flow/agent-session.ts:594 [EXTRACTED]
  ```
  export const AgentSession = { list, copy, find, transcript, platformForTool, toolsWithoutSessions, toolForPlatform } as const satisfies AgentSession;
  ```
- `openSessionArchive` ← src/session-flow/archive.ts:59 [EXTRACTED]
  ```
  export function openSessionArchive(config: LocalConfig): SessionArchive {
  ```
- `archiveSessions` ← src/session-flow/archive.ts:158 [EXTRACTED]
  ```
  export async function archiveSessions<T extends ArchiveSessionRef>(
  ```
- `pushSession` ← src/session-flow/archive.ts:248 [EXTRACTED]
  ```
  export async function pushSession(config: LocalConfig, ref: ArchiveSessionRef): Promise<SessionPush> {
  ```
- `SessionCaptureSchema` ← src/session-flow/captures.ts:27 [EXTRACTED]
  ```
  export const SessionCaptureSchema = z.object({
  ```
- `CAPTURE_PAYLOAD_KEY` ← src/session-flow/captures.ts:51 [EXTRACTED]
  ```
  export const CAPTURE_PAYLOAD_KEY = 'teamai_capture';
  ```
- `SessionCaptures` ← src/session-flow/captures.ts:521 [EXTRACTED]
  ```
  export const SessionCaptures = { finishedAfter, atStart, atStop, addToolVersion, checkoutDelivery, markTeamChanged, read, list, markDrained, platformsOf, agentOf, archivedFacts, reportedModelOf, runModeOf, sweep } as const;
  ```
- `FinishedSessions` ← src/session-flow/finished-sessions.ts:503 [EXTRACTED]
  ```
  export const FinishedSessions = { list, shareable, start, reachedScopes, backgroundScopes } as const;
  ```
- `fidelityFromSession` ← src/session-flow/migrate.ts:32 [EXTRACTED]
  ```
  export function fidelityFromSession(session: Session, targetPlatform: string): FidelityReport {
  ```
- `degradeThinkingBlocks` ← src/session-flow/migrate.ts:129 [EXTRACTED]
  ```
  export function degradeThinkingBlocks(session: Session, targetPlatform: string): Session {
  ```
- `resolveTargetCwd` ← src/session-flow/migrate.ts:178 [EXTRACTED]
  ```
  export function resolveTargetCwd(
  ```
- `previewMigration` ← src/session-flow/migrate.ts:191 [EXTRACTED]
  ```
  export function previewMigration(
  ```
- `shouldRegisterSessionFlowCommands` ← src/session-flow/register-gate.ts:2 [EXTRACTED]
  ```
  export function shouldRegisterSessionFlowCommands(
  ```
- `nativeSession` ← src/session-flow/scoring.ts:99 [EXTRACTED]
  ```
  export async function nativeSession(from: LocalConfig, demand: SessionDemand): Promise<NamedSession | Failure> {
  ```
- `pushedSession` ← src/session-flow/scoring.ts:126 [EXTRACTED]
  ```
  export async function pushedSession(config: LocalConfig, { name, author }: TeamSession, identities: ReadonlyArray<string | null> = [getRepoIdentity(process.cwd())]): Promise<NamedSession | Failure> {
  ```
- `titleSpellsLocalPath` ← src/session-flow/scrub.ts:272 [EXTRACTED]
  ```
  export function titleSpellsLocalPath(title: string, roots: LocalPathRoots, cwd: string): boolean {
  ```
- `textScrubber` ← src/session-flow/scrub.ts:290 [EXTRACTED]
  ```
  export function textScrubber(cwd: string, opts: { secrets?: Record<string, string>; localPaths?: LocalPathRoots } = {}): (text: string) => string {
  ```
- `scrubSession` ← src/session-flow/scrub.ts:314 [EXTRACTED]
  ```
  export function scrubSession(
  ```
- `tokenize` ← src/session-flow/search.ts:39 [EXTRACTED]
  ```
  export function tokenize(text: string): string[] {
  ```
- `SessionSearchEngine` ← src/session-flow/search.ts:200 [EXTRACTED]
  ```
  export class SessionSearchEngine {
  ```
- `listedCounts` ← src/session-flow/session-cmd-shared.ts:30 [EXTRACTED]
  ```
  export function listedCounts(m: AgentSessionListed, { includeSize = false } = {}): string {
  ```
- `safeText` ← src/session-flow/session-cmd-shared.ts:50 [EXTRACTED]
  ```
  export function safeText(value: string): string {
  ```
- `closeStdin` ← src/session-flow/session-cmd-shared.ts:88 [EXTRACTED]
  ```
  export function closeStdin(): void {
  ```
- `ask` ← src/session-flow/session-cmd-shared.ts:101 [EXTRACTED]
  ```
  export function ask(question: string): Promise<string> {
  ```
- `confirmUnredactedArchive` ← src/session-flow/session-cmd-shared.ts:143 [EXTRACTED]
  ```
  export async function confirmUnredactedArchive(
  ```
- `safeGetAdapter` ← src/session-flow/session-cmd-shared.ts:167 [EXTRACTED]
  ```
  export async function safeGetAdapter(platform: string, cwd: string | undefined) {
  ```
- `authorForCwd` ← src/session-flow/session-cmd-shared.ts:187 [EXTRACTED]
  ```
  export function authorForCwd(cwd: string | undefined, fallback: string): string {
  ```
- `resolveRepoIdentity` ← src/session-flow/session-cmd-shared.ts:203 [EXTRACTED]
  ```
  export function resolveRepoIdentity(cwd?: string): string | null {
  ```
- `deriveArchiveIdentity` ← src/session-flow/session-cmd-shared.ts:220 [EXTRACTED]
  ```
  export function deriveArchiveIdentity(session: { cwd: string }, platform: string): string | null {
  ```
- `sessionArchiveRoot` ← src/session-flow/session-cmd-shared.ts:236 [EXTRACTED]
  ```
  export function sessionArchiveRoot(config: LocalConfig): string | undefined {
  ```
- `resolveRepoRoot` ← src/session-flow/session-cmd-shared.ts:248 [EXTRACTED]
  ```
  export async function resolveRepoRoot(
  ```
- `sessionArchives` ← src/session-flow/session-cmd-shared.ts:282 [EXTRACTED]
  ```
  export async function sessionArchives(
  ```
- `REPORTS_ARCHIVE_BUSY` ← src/session-flow/session-cmd-shared.ts:301 [EXTRACTED]
  ```
  export const REPORTS_ARCHIVE_BUSY =
  ```
- `archiveToReports` ← src/session-flow/session-cmd-shared.ts:316 [EXTRACTED]
  ```
  export async function archiveToReports(
  ```
- `pushToRemote` ← src/session-flow/session-cmd-shared.ts:349 [EXTRACTED]
  ```
  export async function pushToRemote(syncMgr: SyncManager, repoRoot: string): Promise<boolean> {
  ```
- `pushArchive` ← src/session-flow/session-cmd-shared.ts:361 [EXTRACTED]
  ```
  export async function pushArchive(syncMgr: SyncManager, repoRoot: string): Promise<{ status: 'pushed' } | { status: 'failed'; reason: string }> {
  ```
- `pullArchive` ← src/session-flow/session-cmd-shared.ts:385 [EXTRACTED]
  ```
  export async function pullArchive(syncMgr: SyncManager, repoRoot: string): Promise<{ status: 'pulled'; rebuilt: number } | { status: 'failed'; reason: string }> {
  ```
- `runGitStep` ← src/session-flow/session-cmd-shared.ts:438 [EXTRACTED]
  ```
  export function runGitStep<T>(step: () => T, repoRoot: string, what: string): T {
  ```
- `archiveBusyMessage` ← src/session-flow/session-cmd-shared.ts:448 [EXTRACTED]
  ```
  export function archiveBusyMessage(repoRoot: string, lockPath: string): string {
  ```
- `mergeBusyMessage` ← src/session-flow/session-cmd-shared.ts:453 [EXTRACTED]
  ```
  export function mergeBusyMessage(repoRoot: string, lockPath: string): string {
  ```
- `reportArchiveBusy` ← src/session-flow/session-cmd-shared.ts:458 [EXTRACTED]
  ```
  export function reportArchiveBusy(repoRoot: string, lockPath: string): void {
  ```
- `printEnvelope` ← src/session-flow/session-cmd-shared.ts:465 [EXTRACTED]
  ```
  export function printEnvelope(envelope: WorkflowEnvelope): void {
  ```
- `listSource` ← src/session-flow/session-cmd-shared.ts:476 [EXTRACTED]
  ```
  export async function listSource({
  ```
- `registerSessionFlowCommands` ← src/session-flow/session-cmd.ts:322 [EXTRACTED]
  ```
  export function registerSessionFlowCommands(sessionCmd: Command): void {
  ```
- `ArchivedEvidenceSchema` ← src/session-flow/session-evidence.ts:40 [EXTRACTED]
  ```
  export const ArchivedEvidenceSchema = z.object({ version: z.literal(1), files: z.array(EvidenceFileSchema), leftOut: z.number().int().positive().optional() }).strict();
  ```
- `SessionEvidence` ← src/session-flow/session-evidence.ts:165 [EXTRACTED]
  ```
  export const SessionEvidence = { collect } as const;
  ```
- `registerMigrationCommand` ← src/session-flow/session-migrate-cmd.ts:693 [EXTRACTED]
  ```
  export function registerMigrationCommand(sessionCmd: Command, isDryRun: () => boolean): void {
  ```
- `SessionPolicy` ← src/session-flow/session-policy.ts:150 [EXTRACTED]
  ```
  export const SessionPolicy = { read, resolve, readPublish, publish, publishDefaults, setBy } as const;
  ```
- `SessionPublish` ← src/session-flow/session-publish.ts:292 [EXTRACTED]
  ```
  export const SessionPublish = { steps, waitingSteps, isRecorded, archivedAt, recordArchived } as const;
  ```
- `judgedTranscript` ← src/session-flow/session-work.ts:85 [EXTRACTED]
  ```
  export function judgedTranscript(
  ```
- `firstPrompt` ← src/session-flow/session-work.ts:122 [EXTRACTED]
  ```
  export function firstPrompt(session: Session): string {
  ```
- `firstPromptOnly` ← src/session-flow/session-work.ts:139 [EXTRACTED]
  ```
  export function firstPromptOnly(found: { session: Session }): PromptOnlyRead {
  ```
- `judgeSession` ← src/session-flow/session-work.ts:175 [EXTRACTED]
  ```
  export function judgeSession({ platform, found, captures, mask, agent: archived, evidence }: {
  ```
- `writeSessionEvidence` ← src/session-flow/session-work.ts:303 [EXTRACTED]
  ```
  export async function writeSessionEvidence(dir: string, judged: JudgedSession, rubrics: Rubrics, files: Readonly<Record<string, string>> = {}): Promise<void> {
  ```
- `sessionLabel` ← src/session-flow/session-work.ts:328 [EXTRACTED]
  ```
  export function sessionLabel(verdict: Omit<SessionLabel, 'source' | 'subject' | 'agent' | 'used' | 'runMode'>, subject: SessionSubject, context: SessionLabelContext): SessionLabel {
  ```
- `SessionWork` ← src/session-flow/session-work.ts:588 [EXTRACTED]
  ```
  export const SessionWork = { finished, read, readPushed, scopeCwd, sampledScorers, samplingScorers, sessionScorers, generatedQuestions, pinsOf, isGone } as const;
  ```
- `archivedCwd` ← src/session-flow/sync.ts:68 [EXTRACTED]
  ```
  export async function archivedCwd(cwd: string, projectRoot?: string): Promise<string> {
  ```
- `publishedPathRoots` ← src/session-flow/sync.ts:111 [EXTRACTED]
  ```
  export async function publishedPathRoots(cwd: string): Promise<LocalPathRoots> {
  ```
- `getGitAuthor` ← src/session-flow/sync.ts:145 [EXTRACTED]
  ```
  export function getGitAuthor(cwd?: string): string {
  ```
- `getRepoIdentity` ← src/session-flow/sync.ts:176 [EXTRACTED]
  ```
  export function getRepoIdentity(cwd?: string): string | null {
  ```
- `repoIdentitiesOf` ← src/session-flow/sync.ts:197 [EXTRACTED]
  ```
  export function repoIdentitiesOf(url: string, cwd?: string): string[] {
  ```
- `canonicalizeRemote` ← src/session-flow/sync.ts:221 [EXTRACTED]
  ```
  export function canonicalizeRemote(remote: string): string {
  ```
- `encodeRepoIdentity` ← src/session-flow/sync.ts:268 [EXTRACTED]
  ```
  export function encodeRepoIdentity(identity: string): string {
  ```
- `decodeRepoIdentity` ← src/session-flow/sync.ts:295 [EXTRACTED]
  ```
  export function decodeRepoIdentity(encoded: string): string {
  ```
- `generateSessionName` ← src/session-flow/sync.ts:344 [EXTRACTED]
  ```
  export function generateSessionName(platform: string, title: string, createdAt: string): string {
  ```
- `SessionCommitsSchema` ← src/session-flow/sync.ts:355 [EXTRACTED]
  ```
  export const SessionCommitsSchema = z.object({ start: CommitStateSchema.optional(), end: CommitStateSchema.optional() });
  ```
- `defaultSyncMeta` ← src/session-flow/sync.ts:451 [EXTRACTED]
  ```
  export function defaultSyncMeta(
  ```
- `withSessionPublicationLock` ← src/session-flow/sync.ts:676 [EXTRACTED]
  ```
  export async function withSessionPublicationLock<T>(
  ```
- `withSessionIndexLock` ← src/session-flow/sync.ts:706 [EXTRACTED]
  ```
  export async function withSessionIndexLock<T>(
  ```
- `SyncManager` ← src/session-flow/sync.ts:734 [EXTRACTED]
  ```
  export class SyncManager {
  ```
- `LEFT_OUT` ← src/session-flow/task-candidates.ts:64 [EXTRACTED]
  ```
  export const LEFT_OUT = {
  ```
- `TaskCandidates` ← src/session-flow/task-candidates.ts:194 [EXTRACTED]
  ```
  export const TaskCandidates = { parseSizes, suiteIn, weigh, leftOutLine } as const;
  ```
- `canonicalModelName` ← src/token-usage/model-name.ts:8 [EXTRACTED]
  ```
  export function canonicalModelName(model: string): string {
  ```
- `PRICE_CATALOG_VERSION` ← src/token-usage/pricing.ts:22 [EXTRACTED]
  ```
  export const PRICE_CATALOG_VERSION = CATALOG.version;
  ```
- `priceTokens` ← src/token-usage/pricing.ts:46 [EXTRACTED]
  ```
  export function priceTokens(
  ```
- `isAbsolutePath` ← src/utils/agent-path.ts:14 [EXTRACTED]
  ```
  export function isAbsolutePath(p: string): boolean {
  ```
- `resolvePath` ← src/utils/agent-path.ts:28 [EXTRACTED]
  ```
  export function resolvePath(file: string, base?: string): string {
  ```
- `pathKey` ← src/utils/agent-path.ts:40 [EXTRACTED]
  ```
  export function pathKey(p: string): string {
  ```
- `withoutReadSelector` ← src/utils/agent-path.ts:62 [EXTRACTED]
  ```
  export function withoutReadSelector(p: string): string {
  ```
- `samePath` ← src/utils/agent-path.ts:82 [EXTRACTED]
  ```
  export function samePath(a: string, b: string): boolean {
  ```
- `isWithin` ← src/utils/agent-path.ts:87 [EXTRACTED]
  ```
  export function isWithin(file: string, dir: string): boolean {
  ```
- `withTimeout` ← src/utils/async.ts:21 [EXTRACTED]
  ```
  export async function withTimeout<T>(
  ```
- `isPublished` ← src/utils/branch-worktree.ts:73 [EXTRACTED]
  ```
  export function isPublished(result: PublishResult): boolean {
  ```
- `isDelivered` ← src/utils/branch-worktree.ts:83 [EXTRACTED]
  ```
  export function isDelivered(result: PublishResult): boolean {
  ```
- `gitRoot` ← src/utils/branch-worktree.ts:92 [EXTRACTED]
  ```
  export function gitRoot(localConfig: LocalConfig): string {
  ```
- `fetchTrackingRef` ← src/utils/branch-worktree.ts:178 [EXTRACTED]
  ```
  export async function fetchTrackingRef(git: SimpleGit, branch: string): Promise<void> {
  ```
- `refusedFetch` ← src/utils/branch-worktree.ts:190 [EXTRACTED]
  ```
  export async function refusedFetch(git: SimpleGit, cause: unknown, dir: string): Promise<RefusedWrite | undefined> {
  ```
- `CheckoutRefusedError` ← src/utils/branch-worktree.ts:648 [EXTRACTED]
  ```
  export class CheckoutRefusedError extends Error {
  ```
- `failureReason` ← src/utils/branch-worktree.ts:662 [EXTRACTED]
  ```
  export function failureReason(cause: unknown): string {
  ```
- `ForeignCheckoutError` ← src/utils/branch-worktree.ts:681 [EXTRACTED]
  ```
  export class ForeignCheckoutError extends CheckoutRefusedError {
  ```
- `createBranchWorktree` ← src/utils/branch-worktree.ts:1595 [EXTRACTED]
  ```
  export function createBranchWorktree(spec: BranchWorktreeSpec): BranchWorktree {
  ```
- `canonicalJson` ← src/utils/canonical-json.ts:3 [EXTRACTED]
  ```
  export function canonicalJson(value: unknown): string {
  ```
- `injectClaudeMdSection` ← src/utils/claudemd.ts:19 [EXTRACTED]
  ```
  export async function injectClaudeMdSection(
  ```
- `removeClaudeMdSection` ← src/utils/claudemd.ts:57 [EXTRACTED]
  ```
  export async function removeClaudeMdSection(
  ```
- `DataBranches` ← src/utils/data-branches.ts:177 [EXTRACTED]
  ```
  export const DataBranches = {
  ```
- `extractKeywords` ← src/utils/dedup.ts:28 [EXTRACTED]
  ```
  export function extractKeywords(text: string): Set<string> {
  ```
- `overlapRatio` ← src/utils/dedup.ts:59 [EXTRACTED]
  ```
  export function overlapRatio(a: Set<string>, b: Set<string>): number {
  ```
- `findOverlappingLearnings` ← src/utils/dedup.ts:120 [EXTRACTED]
  ```
  export async function findOverlappingLearnings(
  ```
- `definedFields` ← src/utils/defined-fields.ts:5 [EXTRACTED]
  ```
  export function definedFields<TFields extends object>(fields: TFields): TFields {
  ```
- `durationMs` ← src/utils/duration.ts:5 [EXTRACTED]
  ```
  export function durationMs(text: string): number | undefined {
  ```
- `FrontmatterDateSchema` ← src/utils/frontmatter.ts:6 [EXTRACTED]
  ```
  export const FrontmatterDateSchema = z.union([
  ```
- `splitFrontmatter` ← src/utils/frontmatter.ts:64 [EXTRACTED]
  ```
  export function splitFrontmatter(content: string): FrontmatterSplit {
  ```
- `parseFrontmatter` ← src/utils/frontmatter.ts:104 [EXTRACTED]
  ```
  export function parseFrontmatter(content: string): Pick<FrontmatterSplit, 'data' | 'body'> {
  ```
- `stripFrontmatter` ← src/utils/frontmatter.ts:111 [EXTRACTED]
  ```
  export function stripFrontmatter(content: string): string {
  ```
- `hasFrontmatter` ← src/utils/frontmatter.ts:116 [EXTRACTED]
  ```
  export function hasFrontmatter(content: string): boolean {
  ```
- `stringifyFrontmatter` ← src/utils/frontmatter.ts:125 [EXTRACTED]
  ```
  export function stringifyFrontmatter(data: FrontmatterData, body: string): string {
  ```
- `syncFolders` ← src/utils/fs.ts:30 [EXTRACTED]
  ```
  export function syncFolders(dir: string) {
  ```
- `isIgnored` ← src/utils/fs.ts:37 [EXTRACTED]
  ```
  export function isIgnored(name: string): boolean {
  ```
- `DRAFT_SUFFIX` ← src/utils/fs.ts:45 [EXTRACTED]
  ```
  export const DRAFT_SUFFIX = '.draft.md';
  ```
- `isDraft` ← src/utils/fs.ts:48 [EXTRACTED]
  ```
  export function isDraft(file: string): boolean {
  ```
- `errnoCode` ← src/utils/fs.ts:58 [EXTRACTED]
  ```
  export function errnoCode(cause: unknown): string | undefined {
  ```
- `RefusedWriteError` ← src/utils/fs.ts:136 [EXTRACTED]
  ```
  export class RefusedWriteError extends Error {
  ```
- `refusedWrite` ← src/utils/fs.ts:148 [EXTRACTED]
  ```
  export function refusedWrite(cause: unknown, { gitCwd }: { gitCwd?: string } = {}): RefusedWrite | undefined {
  ```
- `refusedWriteIn` ← src/utils/fs.ts:169 [EXTRACTED]
  ```
  export async function refusedWriteIn(folder: string): Promise<RefusedWrite | undefined> {
  ```
- `refusedWriteAdvice` ← src/utils/fs.ts:184 [EXTRACTED]
  ```
  export function refusedWriteAdvice({ folder, code }: RefusedWrite): string {
  ```
- `ensureDir` ← src/utils/fs.ts:191 [EXTRACTED]
  ```
  export async function ensureDir(dir: string): Promise<void> {
  ```
- `readFileSafe` ← src/utils/fs.ts:198 [EXTRACTED]
  ```
  export async function readFileSafe(filePath: string): Promise<string | null> {
  ```
- `readFileIfExists` ← src/utils/fs.ts:212 [EXTRACTED]
  ```
  export async function readFileIfExists(filePath: string): Promise<string | null> {
  ```
- `writeFile` ← src/utils/fs.ts:224 [EXTRACTED]
  ```
  export async function writeFile(filePath: string, content: string | Uint8Array): Promise<void> {
  ```
- `symlinkTarget` ← src/utils/fs.ts:237 [EXTRACTED]
  ```
  export async function symlinkTarget(filePath: string): Promise<string> {
  ```
- `writeFileAtomic` ← src/utils/fs.ts:272 [EXTRACTED]
  ```
  export async function writeFileAtomic(
  ```
- `readJson` ← src/utils/fs.ts:303 [EXTRACTED]
  ```
  export async function readJson<T = unknown>(filePath: string): Promise<T | null> {
  ```
- `readJsonObject` ← src/utils/fs.ts:331 [EXTRACTED]
  ```
  export async function readJsonObject(filePath: string, syntax: JsonSyntax = 'json'): Promise<JsonObjectRead> {
  ```
- `writeJsonKeepingComments` ← src/utils/fs.ts:353 [EXTRACTED]
  ```
  export async function writeJsonKeepingComments<T>(
  ```
- `writeJson` ← src/utils/fs.ts:373 [EXTRACTED]
  ```
  export async function writeJson<T>(filePath: string, data: T): Promise<void> {
  ```
- `writeJsonAtomic` ← src/utils/fs.ts:392 [EXTRACTED]
  ```
  export async function writeJsonAtomic<T>(
  ```
- `copyDir` ← src/utils/fs.ts:432 [EXTRACTED]
  ```
  export async function copyDir(
  ```
- `stagingLeftIn` ← src/utils/fs.ts:507 [EXTRACTED]
  ```
  export async function stagingLeftIn(parent: string): Promise<{ left: string[]; inUse: string[] }> {
  ```
- `pruneEmptyDirs` ← src/utils/fs.ts:573 [EXTRACTED]
  ```
  export async function pruneEmptyDirs(target: string): Promise<boolean> {
  ```
- `copyFile` ← src/utils/fs.ts:607 [EXTRACTED]
  ```
  export async function copyFile(src: string, dest: string): Promise<void> {
  ```
- `listDirs` ← src/utils/fs.ts:616 [EXTRACTED]
  ```
  export async function listDirs(dirPath: string): Promise<string[]> {
  ```
- `listFiles` ← src/utils/fs.ts:628 [EXTRACTED]
  ```
  export async function listFiles(dirPath: string): Promise<string[]> {
  ```
- `listFilesRecursive` ← src/utils/fs.ts:640 [EXTRACTED]
  ```
  export async function listFilesRecursive(dirPath: string): Promise<string[]> {
  ```
- `hasVcsMetadataRecursive` ← src/utils/fs.ts:677 [EXTRACTED]
  ```
  export async function hasVcsMetadataRecursive(dir: string): Promise<boolean> {
  ```
- `isSameRealPath` ← src/utils/fs.ts:704 [EXTRACTED]
  ```
  export async function isSameRealPath(left: string, right: string): Promise<boolean> {
  ```
- `pathExists` ← src/utils/fs.ts:710 [EXTRACTED]
  ```
  export async function pathExists(p: string): Promise<boolean> {
  ```
- `generatedFileState` ← src/utils/fs.ts:722 [EXTRACTED]
  ```
  export async function generatedFileState(file: string, marker: string): Promise<GeneratedFileState> {
  ```
- `remove` ← src/utils/fs.ts:733 [EXTRACTED]
  ```
  export async function remove(p: string): Promise<void> {
  ```
- `getFileMtime` ← src/utils/fs.ts:741 [EXTRACTED]
  ```
  export async function getFileMtime(filePath: string): Promise<number> {
  ```
- `getDirLatestMtime` ← src/utils/fs.ts:755 [EXTRACTED]
  ```
  export async function getDirLatestMtime(dirPath: string): Promise<number> {
  ```
- `fileHash` ← src/utils/fs.ts:784 [EXTRACTED]
  ```
  export async function fileHash(filePath: string): Promise<string | null> {
  ```
- `fileContentEqualToBuffer` ← src/utils/fs.ts:799 [EXTRACTED]
  ```
  export async function fileContentEqualToBuffer(filePath: string, buffer: Buffer): Promise<boolean> {
  ```
- `fileContentEqual` ← src/utils/fs.ts:812 [EXTRACTED]
  ```
  export async function fileContentEqual(fileA: string, fileB: string): Promise<boolean> {
  ```
- `dirContentEqual` ← src/utils/fs.ts:828 [EXTRACTED]
  ```
  export async function dirContentEqual(dirA: string, dirB: string, ignore?: string[]): Promise<boolean> {
  ```
- `dirTeamSubsetEqual` ← src/utils/fs.ts:870 [EXTRACTED]
  ```
  export async function dirTeamSubsetEqual(
  ```
- `writeIfChanged` ← src/utils/fs.ts:929 [EXTRACTED]
  ```
  export async function writeIfChanged(filePath: string, content: string): Promise<boolean> {
  ```
- `GitAnswers` ← src/utils/git-answers.ts:26 [EXTRACTED]
  ```
  export const GitAnswers = {
  ```
- `gitFindsNoRepository` ← src/utils/git-discovery.ts:42 [EXTRACTED]
  ```
  export async function gitFindsNoRepository(dir: string): Promise<boolean> {
  ```
- `repositoryStamp` ← src/utils/git-discovery.ts:72 [EXTRACTED]
  ```
  export async function repositoryStamp(dir: string): Promise<{ stamp: string; gitDir: string } | null> {
  ```
- `linkedWorktreesStamp` ← src/utils/git-discovery.ts:149 [EXTRACTED]
  ```
  export async function linkedWorktreesStamp(commonDir: string): Promise<string | null> {
  ```
- `applyNonInteractiveGitEnv` ← src/utils/git-env.ts:43 [EXTRACTED]
  ```
  export function applyNonInteractiveGitEnv(): void {
  ```
- `withoutGitRepositoryEnv` ← src/utils/git-env.ts:77 [EXTRACTED]
  ```
  export function withoutGitRepositoryEnv(env: NodeJS.ProcessEnv = process.env): NodeJS.ProcessEnv {
  ```
- `readFetchedDefaultFromFiles` ← src/utils/git-ref-files.ts:24 [EXTRACTED]
  ```
  export async function readFetchedDefaultFromFiles(dir: string): Promise<RefTip | null> {
  ```
- `gitBinary` ← src/utils/git.ts:44 [EXTRACTED]
  ```
  export function gitBinary(
  ```
- `disableGitTerminalPrompt` ← src/utils/git.ts:163 [EXTRACTED]
  ```
  export function disableGitTerminalPrompt(): void {
  ```
- `gitBlockTimeoutMs` ← src/utils/git.ts:188 [EXTRACTED]
  ```
  export function gitBlockTimeoutMs(): number {
  ```
- `longPathConfig` ← src/utils/git.ts:208 [EXTRACTED]
  ```
  export function longPathConfig(platform: NodeJS.Platform = process.platform): string[] {
  ```
- `longPathArgs` ← src/utils/git.ts:213 [EXTRACTED]
  ```
  export function longPathArgs(platform: NodeJS.Platform = process.platform): string[] {
  ```
- `createGit` ← src/utils/git.ts:227 [EXTRACTED]
  ```
  export function createGit(basePath?: string, abort?: AbortSignal): SimpleGit {
  ```
- `readBlobs` ← src/utils/git.ts:261 [EXTRACTED]
  ```
  export async function readBlobs(repoPath: string, specs: readonly string[]): Promise<Array<Buffer | null>> {
  ```
- `createGitWithBlockTimeout` ← src/utils/git.ts:308 [EXTRACTED]
  ```
  export function createGitWithBlockTimeout(basePath?: string, abort?: AbortSignal): SimpleGit {
  ```
- `GitStalledError` ← src/utils/git.ts:384 [EXTRACTED]
  ```
  export class GitStalledError extends GitError {
  ```
- `endProcessTree` ← src/utils/git.ts:430 [EXTRACTED]
  ```
  export async function endProcessTree(child: Pick<ChildProcess, 'pid' | 'kill'>): Promise<void> {
  ```
- `commitSkippingHooks` ← src/utils/git.ts:468 [EXTRACTED]
  ```
  export async function commitSkippingHooks(
  ```
- `isGitRepo` ← src/utils/git.ts:516 [EXTRACTED]
  ```
  export async function isGitRepo(localPath: string): Promise<boolean> {
  ```
- `initRepo` ← src/utils/git.ts:528 [EXTRACTED]
  ```
  export async function initRepo(remote: string, localPath: string): Promise<void> {
  ```
- `configureGitUser` ← src/utils/git.ts:542 [EXTRACTED]
  ```
  export async function configureGitUser(
  ```
- `getHeadRev` ← src/utils/git.ts:567 [EXTRACTED]
  ```
  export async function getHeadRev(localPath: string): Promise<string> {
  ```
- `getRemoteUrl` ← src/utils/git.ts:578 [EXTRACTED]
  ```
  export async function getRemoteUrl(localPath: string, remoteName = 'origin'): Promise<string | null> {
  ```
- `getConfiguredRemoteUrl` ← src/utils/git.ts:591 [EXTRACTED]
  ```
  export async function getConfiguredRemoteUrl(localPath: string, remoteName = 'origin'): Promise<string | null> {
  ```
- `checkoutCredentials` ← src/utils/git.ts:608 [EXTRACTED]
  ```
  export async function checkoutCredentials(localPath: string): Promise<Array<[string, string]>> {
  ```
- `redactGitCredentials` ← src/utils/git.ts:628 [EXTRACTED]
  ```
  export function redactGitCredentials(url: string): string {
  ```
- `normalizeRepoUrlForCompare` ← src/utils/git.ts:641 [EXTRACTED]
  ```
  export function normalizeRepoUrlForCompare(url: string): string {
  ```
- `remotesMatch` ← src/utils/git.ts:665 [EXTRACTED]
  ```
  export function remotesMatch(a: string, b: string): boolean {
  ```
- `repoIdentity` ← src/utils/git.ts:687 [EXTRACTED]
  ```
  export function repoIdentity(url: string): string {
  ```
- `hasCommits` ← src/utils/git.ts:718 [EXTRACTED]
  ```
  export async function hasCommits(localPath: string): Promise<boolean> {
  ```
- `commitPaths` ← src/utils/git.ts:744 [EXTRACTED]
  ```
  export async function commitPaths(
  ```
- `DetachedTeamRepoError` ← src/utils/git.ts:782 [EXTRACTED]
  ```
  export class DetachedTeamRepoError extends Error {
  ```
- `assertAttachedTeamRepo` ← src/utils/git.ts:793 [EXTRACTED]
  ```
  export async function assertAttachedTeamRepo(git: SimpleGit, localPath: string): Promise<void> {
  ```
- `pullRepo` ← src/utils/git.ts:819 [EXTRACTED]
  ```
  export async function pullRepo(localPath: string, abort?: AbortSignal): Promise<string> {
  ```
- `pullRepoFastForward` ← src/utils/git.ts:898 [EXTRACTED]
  ```
  export async function pullRepoFastForward(localPath: string): Promise<string> {
  ```
- `getDefaultBranch` ← src/utils/git.ts:910 [EXTRACTED]
  ```
  export async function getDefaultBranch(localPath: string): Promise<string> {
  ```
- `pushRepoDirectly` ← src/utils/git.ts:958 [EXTRACTED]
  ```
  export async function pushRepoDirectly(
  ```
- `pushLearningToOrigin` ← src/utils/git.ts:1024 [EXTRACTED]
  ```
  export async function pushLearningToOrigin(
  ```
- `autoPushTeamRepo` ← src/utils/git.ts:1054 [EXTRACTED]
  ```
  export async function autoPushTeamRepo(repoPath: string, message: string, files: string[] = ['.']): Promise<boolean> {
  ```
- `autoPushViaMR` ← src/utils/git.ts:1084 [EXTRACTED]
  ```
  export async function autoPushViaMR(
  ```
- `isMetadataOnlyDiff` ← src/utils/git.ts:1127 [EXTRACTED]
  ```
  export function isMetadataOnlyDiff(diff: string): boolean {
  ```
- `remoteBranchExists` ← src/utils/git.ts:1164 [EXTRACTED]
  ```
  export async function remoteBranchExists(
  ```
- `pushRepoBranch` ← src/utils/git.ts:1204 [EXTRACTED]
  ```
  export async function pushRepoBranch(
  ```
- `prepareExplicitBranch` ← src/utils/git.ts:1347 [EXTRACTED]
  ```
  export async function prepareExplicitBranch(localPath: string, branchName: string): Promise<void> {
  ```
- `checkoutMaster` ← src/utils/git.ts:1692 [EXTRACTED]
  ```
  export async function checkoutMaster(localPath: string): Promise<void> {
  ```
- `PUSH_BRANCH_PREFIX` ← src/utils/git.ts:1700 [EXTRACTED]
  ```
  export const PUSH_BRANCH_PREFIX = 'teamai/push/';
  ```
- `generateBranchName` ← src/utils/git.ts:1705 [EXTRACTED]
  ```
  export function generateBranchName(username: string): string {
  ```
- `unusedBranchName` ← src/utils/git.ts:1719 [EXTRACTED]
  ```
  export async function unusedBranchName(localPath: string, username: string): Promise<string> {
  ```
- `isDedicatedRepoRoot` ← src/utils/git.ts:1752 [EXTRACTED]
  ```
  export async function isDedicatedRepoRoot(repoPath: string): Promise<boolean> {
  ```
- `resolveAnchors` ← src/utils/git.ts:1821 [EXTRACTED]
  ```
  export async function resolveAnchors(cwd?: string): Promise<RepoAnchors | null> {
  ```
- `parseWorktreeList` ← src/utils/git.ts:1891 [EXTRACTED]
  ```
  export function parseWorktreeList(output: string): WorktreeListEntry[] {
  ```
- `checkoutLocation` ← src/utils/git.ts:1937 [EXTRACTED]
  ```
  export async function checkoutLocation(dir: string): Promise<CheckoutLocation | null> {
  ```
- `gitCommonDir` ← src/utils/git.ts:1969 [EXTRACTED]
  ```
  export async function gitCommonDir(cwd: string): Promise<string | null> {
  ```
- `nearestGitEntry` ← src/utils/git.ts:1994 [EXTRACTED]
  ```
  export async function nearestGitEntry(dir: string): Promise<string | null> {
  ```
- `isLiveCheckout` ← src/utils/git.ts:2017 [EXTRACTED]
  ```
  export async function isLiveCheckout(root: string, commonDir: string): Promise<boolean> {
  ```
- `isLiveProjectCheckout` ← src/utils/git.ts:2024 [EXTRACTED]
  ```
  export async function isLiveProjectCheckout(root: string, repoAnchor: string): Promise<boolean> {
  ```
- `checkoutForRepoAnchor` ← src/utils/git.ts:2031 [EXTRACTED]
  ```
  export async function checkoutForRepoAnchor(anchor: string, recordedRoot?: string): Promise<string | null> {
  ```
- `listWorktrees` ← src/utils/git.ts:2118 [EXTRACTED]
  ```
  export async function listWorktrees(cwd?: string): Promise<string[]> {
  ```
- `completeWorktreeList` ← src/utils/git.ts:2136 [EXTRACTED]
  ```
  export async function completeWorktreeList(cwd: string, commonDir: string): Promise<string[] | null> {
  ```
- `resetToCleanMaster` ← src/utils/git.ts:2162 [EXTRACTED]
  ```
  export async function resetToCleanMaster(git: SimpleGit, localPath: string): Promise<void> {
  ```
- `hashObject` ← src/utils/git.ts:2193 [EXTRACTED]
  ```
  export async function hashObject(repoPath: string, filePath: string): Promise<string | null> {
  ```
- `blobInHistory` ← src/utils/git.ts:2208 [EXTRACTED]
  ```
  export async function blobInHistory(
  ```
- `pathDeletedSince` ← src/utils/git.ts:2232 [EXTRACTED]
  ```
  export async function pathDeletedSince(
  ```
- `pathAddedSince` ← src/utils/git.ts:2242 [EXTRACTED]
  ```
  export async function pathAddedSince(
  ```
- `getFileContentWhenAdded` ← src/utils/git.ts:2274 [EXTRACTED]
  ```
  export async function getFileContentWhenAdded(repoPath: string, filePath: string): Promise<Buffer | null> {
  ```
- `getHeadCommit` ← src/utils/git.ts:2287 [EXTRACTED]
  ```
  export async function getHeadCommit(localPath: string, rev = 'HEAD', abort?: AbortSignal): Promise<string | null> {
  ```
- `getMergeBase` ← src/utils/git.ts:2296 [EXTRACTED]
  ```
  export async function getMergeBase(localPath: string, left: string, right: string): Promise<string | null> {
  ```
- `getCurrentBranch` ← src/utils/git.ts:2305 [EXTRACTED]
  ```
  export async function getCurrentBranch(localPath: string, abort?: AbortSignal): Promise<string | null> {
  ```
- `getHeadState` ← src/utils/git.ts:2324 [EXTRACTED]
  ```
  export async function getHeadState(cwd: string, abort?: AbortSignal): Promise<HeadState | null> {
  ```
- `HEAD_STATUS` ← src/utils/git.ts:2329 [EXTRACTED]
  ```
  export const HEAD_STATUS = ['--no-optional-locks', 'status', '--porcelain=v2', '--branch', '--untracked-files=no'] as const;
  ```
- `headStateOf` ← src/utils/git.ts:2332 [EXTRACTED]
  ```
  export function headStateOf(out: string): HeadState | null {
  ```
- `headBranchOf` ← src/utils/git.ts:2342 [EXTRACTED]
  ```
  export function headBranchOf(out: string): string | null {
  ```
- `getHeadAndBranch` ← src/utils/git.ts:2349 [EXTRACTED]
  ```
  export async function getHeadAndBranch(cwd: string, abort?: AbortSignal): Promise<{ state: HeadState; branch: string | null } | null> {
  ```
- `isPastVersionOf` ← src/utils/git.ts:2361 [EXTRACTED]
  ```
  export async function isPastVersionOf(repoPath: string, absFile: string, relPath: string): Promise<boolean> {
  ```
- `listTreeAtRev` ← src/utils/git.ts:2374 [EXTRACTED]
  ```
  export async function listTreeAtRev(repoPath: string, rev: string, dir: string): Promise<GitTreeEntry[]> {
  ```
- `listFilesAtRev` ← src/utils/git.ts:2396 [EXTRACTED]
  ```
  export async function listFilesAtRev(repoPath: string, rev: string, dir: string): Promise<string[]> {
  ```
- `getFileContentAtRev` ← src/utils/git.ts:2409 [EXTRACTED]
  ```
  export async function getFileContentAtRev(
  ```
- `readFileAtRev` ← src/utils/git.ts:2430 [EXTRACTED]
  ```
  export async function readFileAtRev(repoPath: string, rev: string, filePath: string): Promise<{ text: string } | { absent: true }> {
  ```
- `getRepoStatus` ← src/utils/git.ts:2442 [EXTRACTED]
  ```
  export async function getRepoStatus(localPath: string): Promise<{ ahead: number; behind: number; modified: string[] }> {
  ```
- `matchGlob` ← src/utils/glob.ts:25 [EXTRACTED]
  ```
  export function matchGlob(glob: string, path: string): boolean {
  ```
- `resolveHookCwd` ← src/utils/hook-cwd.ts:13 [EXTRACTED]
  ```
  export function resolveHookCwd(data: HookPayload): string | undefined {
  ```
- `RELAY_TO_USER_PREFIX` ← src/utils/hook-output.ts:11 [EXTRACTED]
  ```
  export const RELAY_TO_USER_PREFIX =
  ```
- `hostShowsStopPayload` ← src/utils/hook-output.ts:23 [EXTRACTED]
  ```
  export function hostShowsStopPayload(tool: string): boolean {
  ```
- `relayWhenHidden` ← src/utils/hook-output.ts:35 [EXTRACTED]
  ```
  export function relayWhenHidden(message: string, tool: string): string {
  ```
- `formatStopHookOutput` ← src/utils/hook-output.ts:56 [EXTRACTED]
  ```
  export function formatStopHookOutput(message: string, tool: string): string {
  ```
- `hookSourceMatches` ← src/utils/hook-source.ts:9 [EXTRACTED]
  ```
  export async function hookSourceMatches(actual: string | null, expected: string): Promise<boolean> {
  ```
- `readStdin` ← src/utils/hook-stdin.ts:28 [EXTRACTED]
  ```
  export async function readStdin(
  ```
- `handOffHookStdin` ← src/utils/hook-stdin.ts:79 [EXTRACTED]
  ```
  export function handOffHookStdin(raw: string): void {
  ```
- `takeHandedOffHookStdin` ← src/utils/hook-stdin.ts:84 [EXTRACTED]
  ```
  export function takeHandedOffHookStdin(): string | undefined {
  ```
- `redactHeaders` ← src/utils/http-log.ts:28 [EXTRACTED]
  ```
  export function redactHeaders(headers: Record<string, string>): Record<string, string> {
  ```
- `logHttpRequest` ← src/utils/http-log.ts:43 [EXTRACTED]
  ```
  export function logHttpRequest(
  ```
- `logHttpResponse` ← src/utils/http-log.ts:59 [EXTRACTED]
  ```
  export function logHttpResponse(
  ```
- `ImportLockHeldError` ← src/utils/import-lock.ts:96 [EXTRACTED]
  ```
  export class ImportLockHeldError extends Error {
  ```
- `acquireImportLock` ← src/utils/import-lock.ts:177 [EXTRACTED]
  ```
  export async function acquireImportLock(holder: string, runDir?: string): Promise<() => Promise<void>> {
  ```
- `isImportInProgress` ← src/utils/import-lock.ts:264 [EXTRACTED]
  ```
  export async function isImportInProgress(teamRepoPath: string): Promise<boolean> {
  ```
- `IWikiClient` ← src/utils/iwiki-client.ts:83 [EXTRACTED]
  ```
  export class IWikiClient {
  ```
- `isPlainJson` ← src/utils/json.ts:8 [EXTRACTED]
  ```
  export function isPlainJson(text: string): boolean {
  ```
- `parseJsonAs` ← src/utils/json.ts:21 [EXTRACTED]
  ```
  export function parseJsonAs(text: string, syntax: JsonSyntax): JsonValue {
  ```
- `editJsonText` ← src/utils/json.ts:83 [EXTRACTED]
  ```
  export function editJsonText(original: string, next: JsonValue): string {
  ```
- `appendJsonl` ← src/utils/jsonl-store.ts:62 [EXTRACTED]
  ```
  export async function appendJsonl<Entry extends object>(filePath: string, record: Entry, options: JsonlStoreOptions = {}): Promise<string | null> {
  ```
- `appendJsonlBatch` ← src/utils/jsonl-store.ts:71 [EXTRACTED]
  ```
  export async function appendJsonlBatch(filePath: string, records: object[], options: JsonlStoreOptions = {}): Promise<string | null> {
  ```
- `readJsonl` ← src/utils/jsonl-store.ts:98 [EXTRACTED]
  ```
  export async function readJsonl(filePath: string, options: { includePending?: boolean } = {}): Promise<JsonlRecord[]> {
  ```
- `rewriteJsonl` ← src/utils/jsonl-store.ts:137 [EXTRACTED]
  ```
  export async function rewriteJsonl(
  ```
- `learningsBranch` ← src/utils/learnings-branch.ts:16 [EXTRACTED]
  ```
  export const learningsBranch = createBranchWorktree({
  ```
- `mirrorLearnings` ← src/utils/learnings-mirror.ts:47 [EXTRACTED]
  ```
  export async function mirrorLearnings(
  ```
- `addLearningToCache` ← src/utils/learnings-mirror.ts:155 [EXTRACTED]
  ```
  export async function addLearningToCache(
  ```
- `publishQueuedLearnings` ← src/utils/learnings-publish.ts:65 [EXTRACTED]
  ```
  export async function publishQueuedLearnings(
  ```
- `syncLockPath` ← src/utils/learnings-publish.ts:179 [EXTRACTED]
  ```
  export function syncLockPath(localConfig: LocalConfig): string | null {
  ```
- `publishLearningsMaintenance` ← src/utils/learnings-publish.ts:384 [EXTRACTED]
  ```
  export async function publishLearningsMaintenance(
  ```
- `learningsRoots` ← src/utils/learnings-roots.ts:76 [EXTRACTED]
  ```
  export function learningsRoots(localConfig: LocalConfig): LearningsRoots {
  ```
- `indexableLearningsRoots` ← src/utils/learnings-roots.ts:112 [EXTRACTED]
  ```
  export async function indexableLearningsRoots(
  ```
- `knowledgeRoots` ← src/utils/learnings-roots.ts:146 [EXTRACTED]
  ```
  export async function knowledgeRoots(localConfig: LocalConfig): Promise<string[]> {
  ```
- `isUnderRoots` ← src/utils/learnings-roots.ts:169 [EXTRACTED]
  ```
  export function isUnderRoots(absPath: string, roots: readonly string[]): boolean {
  ```
- `walkLearningsTree` ← src/utils/learnings-roots.ts:207 [EXTRACTED]
  ```
  export async function walkLearningsTree<T>(
  ```
- `listLearningFiles` ← src/utils/learnings-roots.ts:254 [EXTRACTED]
  ```
  export async function listLearningFiles(
  ```
- `isInWriteRoot` ← src/utils/learnings-roots.ts:296 [EXTRACTED]
  ```
  export function isInWriteRoot(absPath: string, rootPath: string): boolean {
  ```
- `localLinkTargets` ← src/utils/markdown-links.ts:234 [EXTRACTED]
  ```
  export function localLinkTargets(markdown: string): string[] {
  ```
- `loadProjectMcpManifest` ← src/utils/mcp-manifest.ts:45 [EXTRACTED]
  ```
  export async function loadProjectMcpManifest(
  ```
- `saveProjectMcpManifest` ← src/utils/mcp-manifest.ts:139 [EXTRACTED]
  ```
  export async function saveProjectMcpManifest(
  ```
- `isCaseInsensitiveFs` ← src/utils/partition.ts:68 [EXTRACTED]
  ```
  export function isCaseInsensitiveFs(probeDir?: string): boolean {
  ```
- `resetCaseProbeCache` ← src/utils/partition.ts:159 [EXTRACTED]
  ```
  export function resetCaseProbeCache(): void {
  ```
- `projectSlug` ← src/utils/partition.ts:221 [EXTRACTED]
  ```
  export function projectSlug(anchor: string): string {
  ```
- `legacyProjectSlug` ← src/utils/partition.ts:242 [EXTRACTED]
  ```
  export function legacyProjectSlug(anchor: string): string {
  ```
- `earlierProjectSlugs` ← src/utils/partition.ts:258 [EXTRACTED]
  ```
  export function earlierProjectSlugs(anchor: string): string[] {
  ```
- `projectDataHome` ← src/utils/partition.ts:274 [EXTRACTED]
  ```
  export function projectDataHome(anchor: string): string {
  ```
- `resolvePartitionDir` ← src/utils/partition.ts:322 [EXTRACTED]
  ```
  export async function resolvePartitionDir(anchor: string, options: { dryRun?: boolean } = {}): Promise<string> {
  ```
- `projectsRootDir` ← src/utils/partition.ts:449 [EXTRACTED]
  ```
  export function projectsRootDir(home = getUserHome()): string {
  ```
- `writeAnchorFile` ← src/utils/partition.ts:459 [EXTRACTED]
  ```
  export async function writeAnchorFile(partitionDir: string, anchor: string): Promise<void> {
  ```
- `readAnchorFile` ← src/utils/partition.ts:465 [EXTRACTED]
  ```
  export async function readAnchorFile(partitionDir: string): Promise<string | null> {
  ```
- `writeWorkspaceRoot` ← src/utils/partition.ts:484 [EXTRACTED]
  ```
  export async function writeWorkspaceRoot(dataHome: string, root: string): Promise<void> {
  ```
- `staleWorkspaces` ← src/utils/partition.ts:515 [EXTRACTED]
  ```
  export async function staleWorkspaces(dataHome: string, currentRoot: string): Promise<StaleWorkspace[]> {
  ```
- `pruneWorkspaceDirs` ← src/utils/partition.ts:555 [EXTRACTED]
  ```
  export async function pruneWorkspaceDirs(dataHome: string, currentRoot: string): Promise<string[]> {
  ```
- `assertSafePath` ← src/utils/path-safety.ts:15 [EXTRACTED]
  ```
  export function assertSafePath(target: string, allowedRoots: string[]): void {
  ```
- `assertWithinRoot` ← src/utils/path-safety.ts:42 [EXTRACTED]
  ```
  export function assertWithinRoot(root: string, candidate: string, message?: string): void {
  ```
- `resolveReal` ← src/utils/path-safety.ts:66 [EXTRACTED]
  ```
  export function resolveReal(p: string): string {
  ```
- `defaultAllowedRoots` ← src/utils/path-safety.ts:85 [EXTRACTED]
  ```
  export function defaultAllowedRoots(): string[] {
  ```
- `assertSafeResourceName` ← src/utils/path-safety.ts:104 [EXTRACTED]
  ```
  export function assertSafeResourceName(name: string): void {
  ```
- `pendingLearningsDir` ← src/utils/pending-learnings.ts:27 [EXTRACTED]
  ```
  export function pendingLearningsDir(localConfig: LocalConfig): string {
  ```
- `queueLockPath` ← src/utils/pending-learnings.ts:44 [EXTRACTED]
  ```
  export async function queueLockPath(home: string): Promise<string> {
  ```
- `queueHome` ← src/utils/pending-learnings.ts:52 [EXTRACTED]
  ```
  export function queueHome(localConfig: LocalConfig): string {
  ```
- `acquireQueueLock` ← src/utils/pending-learnings.ts:74 [EXTRACTED]
  ```
  export async function acquireQueueLock(
  ```
- `withQueueLock` ← src/utils/pending-learnings.ts:89 [EXTRACTED]
  ```
  export async function withQueueLock<T>(
  ```
- `queueWriteRefusal` ← src/utils/pending-learnings.ts:152 [EXTRACTED]
  ```
  export function queueWriteRefusal(result: Exclude<QueueWrite, { status: 'saved' }>): string {
  ```
- `savePendingLearning` ← src/utils/pending-learnings.ts:176 [EXTRACTED]
  ```
  export async function savePendingLearning(
  ```
- `listPendingForInstall` ← src/utils/pending-learnings.ts:206 [EXTRACTED]
  ```
  export async function listPendingForInstall(
  ```
- `readPendingForInstall` ← src/utils/pending-learnings.ts:231 [EXTRACTED]
  ```
  export async function readPendingForInstall(
  ```
- `listPendingLearnings` ← src/utils/pending-learnings.ts:261 [EXTRACTED]
  ```
  export async function listPendingLearnings(localConfig: LocalConfig): Promise<string[]> {
  ```
- `readPendingLearning` ← src/utils/pending-learnings.ts:276 [EXTRACTED]
  ```
  export async function readPendingLearning(
  ```
- `dropPendingLearning` ← src/utils/pending-learnings.ts:291 [EXTRACTED]
  ```
  export async function dropPendingLearning(
  ```
- `installKind` ← src/utils/pending-learnings.ts:299 [EXTRACTED]
  ```
  export function installKind(localConfig: LocalConfig): string {
  ```
- `queueOwner` ← src/utils/pending-learnings.ts:310 [EXTRACTED]
  ```
  export function queueOwner(localConfig: LocalConfig): QueueOwner {
  ```
- `sameQueueOwner` ← src/utils/pending-learnings.ts:315 [EXTRACTED]
  ```
  export function sameQueueOwner(a: QueueOwner, b: QueueOwner): boolean {
  ```
- `countQueued` ← src/utils/pending-learnings.ts:320 [EXTRACTED]
  ```
  export async function countQueued(dir: string): Promise<number> {
  ```
- `setAsideQueueOnModeSwitch` ← src/utils/pending-learnings.ts:335 [EXTRACTED]
  ```
  export async function setAsideQueueOnModeSwitch(
  ```
- `setAsideCheckoutQueue` ← src/utils/pending-learnings.ts:381 [EXTRACTED]
  ```
  export async function setAsideCheckoutQueue(queue: string, next: LocalConfig, from: QueueOwner): Promise<string | null> {
  ```
- `listQueuesIn` ← src/utils/pending-learnings.ts:427 [EXTRACTED]
  ```
  export async function listQueuesIn(dataHome: string): Promise<Array<{ dir: string; count: number }>> {
  ```
- `isRecordedItem` ← src/utils/pending-push.ts:35 [EXTRACTED]
  ```
  export function isRecordedItem(recorded: PendingPushItem, item: ResourceItem): boolean {
  ```
- `recordedNamespace` ← src/utils/pending-push.ts:47 [EXTRACTED]
  ```
  export function recordedNamespace(recorded: PendingPushItem): string | undefined {
  ```
- `openPrDestinations` ← src/utils/pending-push.ts:63 [EXTRACTED]
  ```
  export async function openPrDestinations(input: {
  ```
- `dropClosedPendingPushes` ← src/utils/pending-push.ts:87 [EXTRACTED]
  ```
  export async function dropClosedPendingPushes(repoPath: string, pending: PendingPush[]): Promise<PendingPush[]> {
  ```
- `prunePendingPushes` ← src/utils/pending-push.ts:111 [EXTRACTED]
  ```
  export async function prunePendingPushes(
  ```
- `findPendingForItem` ← src/utils/pending-push.ts:146 [EXTRACTED]
  ```
  export function findPendingForItem(pending: PendingPush[], item: ResourceItem): PendingPush[] {
  ```
- `planPushGroups` ← src/utils/pending-push.ts:167 [EXTRACTED]
  ```
  export function planPushGroups(
  ```
- `partiallySelectedEntries` ← src/utils/pending-push.ts:197 [EXTRACTED]
  ```
  export function partiallySelectedEntries(
  ```
- `pendingNamespaceFor` ← src/utils/pending-push.ts:212 [EXTRACTED]
  ```
  export function pendingNamespaceFor(entry: PendingPush, item: ResourceItem): string | undefined {
  ```
- `recordPendingPush` ← src/utils/pending-push.ts:219 [EXTRACTED]
  ```
  export function recordPendingPush(state: State, entry: PendingPush): void {
  ```
- `toPendingItems` ← src/utils/pending-push.ts:231 [EXTRACTED]
  ```
  export async function toPendingItems(items: ResourceItem[], repoPath: string): Promise<PendingPush['items']> {
  ```
- `isPlacement` ← src/utils/pending-push.ts:281 [EXTRACTED]
  ```
  export function isPlacement(item: ResourceItem): boolean {
  ```
- `reconcilePlacementRecords` ← src/utils/pending-push.ts:360 [EXTRACTED]
  ```
  export async function reconcilePlacementRecords(
  ```
- `windowsPowerShell` ← src/utils/powershell.ts:12 [EXTRACTED]
  ```
  export function windowsPowerShell(): string {
  ```
- `syncTeamUpdatesToLocal` ← src/utils/pre-push-sync.ts:60 [EXTRACTED]
  ```
  export async function syncTeamUpdatesToLocal(
  ```
- `isInteractive` ← src/utils/prompt.ts:27 [EXTRACTED]
  ```
  export function isInteractive(): boolean {
  ```
- `envFlag` ← src/utils/prompt.ts:34 [EXTRACTED]
  ```
  export function envFlag(name: string, env: NodeJS.ProcessEnv = process.env): boolean {
  ```
- `closePrompt` ← src/utils/prompt.ts:57 [EXTRACTED]
  ```
  export function closePrompt(): void {
  ```
- `askQuestion` ← src/utils/prompt.ts:94 [EXTRACTED]
  ```
  export function askQuestion(prompt: string, defaultValue?: string): Promise<string> {
  ```
- `askSecret` ← src/utils/prompt.ts:109 [EXTRACTED]
  ```
  export function askSecret(prompt: string): Promise<string> {
  ```
- `readStdin` ← src/utils/prompt.ts:165 [EXTRACTED]
  ```
  export async function readStdin(): Promise<string> {
  ```
- `askConfirmation` ← src/utils/prompt.ts:178 [EXTRACTED]
  ```
  export function askConfirmation(
  ```
- `parseSelection` ← src/utils/prompt.ts:204 [EXTRACTED]
  ```
  export function parseSelection(input: string, maxItems: number): number[] | null {
  ```
- `askSelection` ← src/utils/prompt.ts:248 [EXTRACTED]
  ```
  export async function askSelection(
  ```
- `canonicalRepo` ← src/utils/repo-attribution.ts:29 [EXTRACTED]
  ```
  export function canonicalRepo(identity: string): string | null {
  ```
- `attributeRepo` ← src/utils/repo-attribution.ts:57 [EXTRACTED]
  ```
  export function attributeRepo(cwd: string | undefined): string {
  ```
- `repoKeys` ← src/utils/repo-attribution.ts:88 [EXTRACTED]
  ```
  export function repoKeys(events: DashboardEvent[]): Map<string, string> {
  ```
- `repoName` ← src/utils/repo-attribution.ts:138 [EXTRACTED]
  ```
  export function repoName(anchor: string): string {
  ```
- `repoLabel` ← src/utils/repo-attribution.ts:152 [EXTRACTED]
  ```
  export function repoLabel(key: string, allKeys: Iterable<string>): string {
  ```
- `assertSafeRepoCachePath` ← src/utils/repo-cache.ts:25 [EXTRACTED]
  ```
  export function assertSafeRepoCachePath(cacheDir: string): void {
  ```
- `getRepoCacheDir` ← src/utils/repo-cache.ts:44 [EXTRACTED]
  ```
  export function getRepoCacheDir(provider: string, owner: string, repo: string): string {
  ```
- `getRepoSlug` ← src/utils/repo-cache.ts:66 [EXTRACTED]
  ```
  export function getRepoSlug(provider: string, owner: string, repo: string): string {
  ```
- `writeLastSync` ← src/utils/repo-cache.ts:78 [EXTRACTED]
  ```
  export async function writeLastSync(cacheDir: string, sha: string): Promise<void> {
  ```
- `readLastSync` ← src/utils/repo-cache.ts:89 [EXTRACTED]
  ```
  export async function readLastSync(
  ```
- `ensureCacheRoot` ← src/utils/repo-cache.ts:112 [EXTRACTED]
  ```
  export async function ensureCacheRoot(): Promise<string> {
  ```
- `reportsBranch` ← src/utils/reports-branch.ts:44 [EXTRACTED]
  ```
  export const reportsBranch = createBranchWorktree({
  ```
- `ensureReportsWorktree` ← src/utils/reports-branch.ts:61 [EXTRACTED]
  ```
  export function ensureReportsWorktree(
  ```
- `indexableVotesDir` ← src/utils/reports-branch.ts:75 [EXTRACTED]
  ```
  export async function indexableVotesDir(localConfig: LocalConfig): Promise<string | undefined> {
  ```
- `refreshReportsWorktree` ← src/utils/reports-branch.ts:91 [EXTRACTED]
  ```
  export function refreshReportsWorktree(
  ```
- `readableReportsWorktree` ← src/utils/reports-branch.ts:105 [EXTRACTED]
  ```
  export async function readableReportsWorktree(
  ```
- `commitAndPushReports` ← src/utils/reports-branch.ts:148 [EXTRACTED]
  ```
  export async function commitAndPushReports(
  ```
- `readReportsOriginFile` ← src/utils/reports-branch.ts:167 [EXTRACTED]
  ```
  export async function readReportsOriginFile(
  ```
- `readReportsOriginFiles` ← src/utils/reports-branch.ts:181 [EXTRACTED]
  ```
  export async function readReportsOriginFiles(worktree: string, relPaths: readonly string[]): Promise<Map<string, string | null>> {
  ```
- `reportsRefusedMessage` ← src/utils/reports-branch.ts:198 [EXTRACTED]
  ```
  export function reportsRefusedMessage(cause: unknown, { gitCwd }: { gitCwd?: string } = {}): string | undefined {
  ```
- `fetchReportsOriginFile` ← src/utils/reports-branch.ts:211 [EXTRACTED]
  ```
  export async function fetchReportsOriginFile(dir: string, relPath: string, update?: ReportsWriteContext): Promise<ReportsOriginRead> {
  ```
- `updateReports` ← src/utils/reports-branch.ts:254 [EXTRACTED]
  ```
  export async function updateReports<T = never>(
  ```
- `EmptyRepoError` ← src/utils/reports-branch.ts:278 [EXTRACTED]
  ```
  export class EmptyRepoError extends Error {
  ```
- `withKnowledgeWorktree` ← src/utils/reports-branch.ts:301 [EXTRACTED]
  ```
  export async function withKnowledgeWorktree<T>(
  ```
- `PreviewFetchError` ← src/utils/reports-branch.ts:408 [EXTRACTED]
  ```
  export class PreviewFetchError extends Error {
  ```
- `DirtyPreviewError` ← src/utils/reports-branch.ts:416 [EXTRACTED]
  ```
  export class DirtyPreviewError extends Error {
  ```
- `withDefaultBranchPreview` ← src/utils/reports-branch.ts:433 [EXTRACTED]
  ```
  export async function withDefaultBranchPreview<T>(
  ```
- `agentSessionIdFromEnv` ← src/utils/session-id.ts:52 [EXTRACTED]
  ```
  export async function agentSessionIdFromEnv(): Promise<string | undefined> {
  ```
- `agentSessionFromEnv` ← src/utils/session-id.ts:81 [EXTRACTED]
  ```
  export async function agentSessionFromEnv(): Promise<EnvAgentSession> {
  ```
- `deriveSessionId` ← src/utils/session-id.ts:139 [EXTRACTED]
  ```
  export function deriveSessionId(
  ```
- `deriveDispatchSessionId` ← src/utils/session-id.ts:178 [EXTRACTED]
  ```
  export function deriveDispatchSessionId(
  ```
- `simpleCommands` ← src/utils/shell-command.ts:82 [EXTRACTED]
  ```
  export function simpleCommands(command: string, home?: string): SimpleCommand[] {
  ```
- `commandWords` ← src/utils/shell-command.ts:168 [EXTRACTED]
  ```
  export function commandWords(words: string[]): string[] {
  ```
- `classifyShellCommand` ← src/utils/shell-command.ts:518 [EXTRACTED]
  ```
  export function classifyShellCommand(command: string, flavor: ShellFlavor = {}, succeeded = false): ShellClassification {
  ```
- `namedReads` ← src/utils/shell-command.ts:532 [EXTRACTED]
  ```
  export function namedReads(command: string, flavor: ShellFlavor = {}): string[] {
  ```
- `SHELL_PROFILE_CANDIDATE_NAMES` ← src/utils/shell-profile.ts:8 [EXTRACTED]
  ```
  export const SHELL_PROFILE_CANDIDATE_NAMES = ['.zshenv', '.zshrc', '.bashrc', '.bash_profile', '.bash_login', '.profile'];
  ```
- `detectShellProfile` ← src/utils/shell-profile.ts:41 [EXTRACTED]
  ```
  export async function detectShellProfile(
  ```
- `envLoaderProfile` ← src/utils/shell-profile.ts:81 [EXTRACTED]
  ```
  export async function envLoaderProfile(
  ```
- `envLoaderProfiles` ← src/utils/shell-profile.ts:112 [EXTRACTED]
  ```
  export async function envLoaderProfiles(
  ```
- `isWindowsFormPath` ← src/utils/shell-profile.ts:211 [EXTRACTED]
  ```
  export function isWindowsFormPath(value: string): boolean {
  ```
- `toGeneratedForm` ← src/utils/shell-profile.ts:216 [EXTRACTED]
  ```
  export function toGeneratedForm(envShPath: string): string {
  ```
- `sameFile` ← src/utils/shell-profile.ts:233 [EXTRACTED]
  ```
  export function sameFile(a: string, b: string, platform: NodeJS.Platform = process.platform): boolean {
  ```
- `shellQuoteValue` ← src/utils/shell-profile.ts:248 [EXTRACTED]
  ```
  export function shellQuoteValue(value: string): string {
  ```
- `findEnvBlocks` ← src/utils/shell-profile.ts:267 [EXTRACTED]
  ```
  export function findEnvBlocks(profileContent: string): EnvBlock[] {
  ```
- `findEnvBlockFor` ← src/utils/shell-profile.ts:294 [EXTRACTED]
  ```
  export function findEnvBlockFor(profileContent: string, envShPath: string): EnvBlock | null {
  ```
- `envBlockSourcesPath` ← src/utils/shell-profile.ts:314 [EXTRACTED]
  ```
  export function envBlockSourcesPath(block: string, envShPath: string): boolean {
  ```
- `envBlockReferencesDataHome` ← src/utils/shell-profile.ts:389 [EXTRACTED]
  ```
  export function envBlockReferencesDataHome(block: string, envShPath: string): boolean {
  ```
- `resolveActiveShellProfile` ← src/utils/shell-profile.ts:595 [EXTRACTED]
  ```
  export async function resolveActiveShellProfile(
  ```
- `loadTagsConfig` ← src/utils/tags.ts:46 [EXTRACTED]
  ```
  export async function loadTagsConfig(repoPath: string): Promise<TagsConfig | null> {
  ```
- `filterByTags` ← src/utils/tags.ts:72 [EXTRACTED]
  ```
  export function filterByTags(
  ```
- `saveTagsConfig` ← src/utils/tags.ts:113 [EXTRACTED]
  ```
  export async function saveTagsConfig(repoPath: string, config: TagsConfig): Promise<void> {
  ```
- `collectTagStats` ← src/utils/tags.ts:127 [EXTRACTED]
  ```
  export function collectTagStats(
  ```
- `TEAM_CODEBASE_DIR` ← src/utils/team-codebase-paths.ts:5 [EXTRACTED]
  ```
  export const TEAM_CODEBASE_DIR = 'team-codebase';
  ```
- `getTeamCodebasePaths` ← src/utils/team-codebase-paths.ts:26 [EXTRACTED]
  ```
  export function getTeamCodebasePaths(cwd: string, output?: string): TeamCodebasePaths {
  ```
- `safeDomainSlug` ← src/utils/team-codebase-paths.ts:46 [EXTRACTED]
  ```
  export function safeDomainSlug(name: string): string {
  ```
- `historicalVersions` ← src/utils/team-history.ts:37 [EXTRACTED]
  ```
  export async function historicalVersions(
  ```
- `readBlob` ← src/utils/team-history.ts:76 [EXTRACTED]
  ```
  export async function readBlob(repoPath: string, blob: string): Promise<Buffer | null> {
  ```
- `readRenderedBlob` ← src/utils/team-history.ts:93 [EXTRACTED]
  ```
  export async function readRenderedBlob(repoPath: string, blob: string, path: string): Promise<Buffer | null> {
  ```
- `blobIdOf` ← src/utils/team-history.ts:106 [EXTRACTED]
  ```
  export async function blobIdOf(repoPath: string, content: string | Uint8Array): Promise<string> {
  ```
- `matchesHistory` ← src/utils/team-history.ts:166 [EXTRACTED]
  ```
  export async function matchesHistory(
  ```
- `historicalContents` ← src/utils/team-history.ts:224 [EXTRACTED]
  ```
  export async function historicalContents(
  ```
- `remotelyReachableRevision` ← src/utils/team-revision.ts:30 [EXTRACTED]
  ```
  export async function remotelyReachableRevision(root: string): Promise<ReachableRevision | undefined> {
  ```
- `withoutStaleTeamRevision` ← src/utils/team-revision.ts:45 [EXTRACTED]
  ```
  export async function withoutStaleTeamRevision<T extends { teamRevision?: string }>(root: string, cached: T | null): Promise<T | null> {
  ```
- `revisionHoldsSources` ← src/utils/team-revision.ts:57 [EXTRACTED]
  ```
  export async function revisionHoldsSources(
  ```
- `resolveTeamwiki` ← src/utils/teamwiki-root.ts:30 [EXTRACTED]
  ```
  export async function resolveTeamwiki(opts: { output?: string; dryRun?: boolean } = {}): Promise<TeamwikiTarget> {
  ```
- `assertTeamwikiWritable` ← src/utils/teamwiki-root.ts:42 [EXTRACTED]
  ```
  export async function assertTeamwikiWritable(target: TeamwikiTarget | undefined): Promise<void> {
  ```
- `lockTeamwiki` ← src/utils/teamwiki-root.ts:56 [EXTRACTED]
  ```
  export async function lockTeamwiki(target: TeamwikiTarget, runDir?: string): Promise<() => Promise<void>> {
  ```
- `teamwikiAt` ← src/utils/teamwiki-root.ts:66 [EXTRACTED]
  ```
  export async function teamwikiAt(wikiRoot: string): Promise<TeamwikiTarget> {
  ```
- `whileTeamwikiLocked` ← src/utils/teamwiki-root.ts:88 [EXTRACTED]
  ```
  export async function whileTeamwikiLocked<T>(wikiRoot: string, write: () => Promise<T>): Promise<T> {
  ```
- `MAX_TOKENIZE_CHARS` ← src/utils/tokenizer.ts:24 [EXTRACTED]
  ```
  export const MAX_TOKENIZE_CHARS = 50_000;
  ```
- `tokenize` ← src/utils/tokenizer.ts:28 [EXTRACTED]
  ```
  export function tokenize(text: string): string[] {
  ```
- `tokenCount` ← src/utils/tokenizer.ts:89 [EXTRACTED]
  ```
  export function tokenCount(text: string): number {
  ```
- `wordSegments` ← src/utils/tokenizer.ts:130 [EXTRACTED]
  ```
  export function wordSegments(text: string): string[] {
  ```
- `withoutTomlBom` ← src/utils/toml.ts:2 [EXTRACTED]
  ```
  export function withoutTomlBom(source: string): string {
  ```
- `classifyToolCall` ← src/utils/tool-call.ts:296 [EXTRACTED]
  ```
  export function classifyToolCall(stdin: HookPayload, agent?: string): ToolCall {
  ```
- `normalizeToolName` ← src/utils/tool-names.ts:28 [EXTRACTED]
  ```
  export function normalizeToolName(name: string): string {
  ```
- `normalizeAgentType` ← src/utils/tool-names.ts:40 [EXTRACTED]
  ```
  export function normalizeAgentType(name: string): string {
  ```
- `isCodexTool` ← src/utils/tool-names.ts:59 [EXTRACTED]
  ```
  export function isCodexTool(tool: string): boolean {
  ```
- `stopStdoutUnsupported` ← src/utils/tool-names.ts:73 [EXTRACTED]
  ```
  export function stopStdoutUnsupported(tool: string | undefined): boolean {
  ```
- `warnOnce` ← src/utils/warn-once.ts:11 [EXTRACTED]
  ```
  export function warnOnce(message: string): boolean {
  ```
- `errorOnce` ← src/utils/warn-once.ts:20 [EXTRACTED]
  ```
  export function errorOnce(message: string): void {
  ```
- `debugOnce` ← src/utils/warn-once.ts:34 [EXTRACTED]
  ```
  export function debugOnce(message: string): void {
  ```
- `resetWarnOnce` ← src/utils/warn-once.ts:41 [EXTRACTED]
  ```
  export function resetWarnOnce(): void {
  ```
- `mergeTeamConfig` ← src/utils/yaml.ts:6 [EXTRACTED]
  ```
  export function mergeTeamConfig(base: string | null, pending: string, destination: string | null): string {
  ```
- `traceCallChains` ← src/wiki-engine/call-chain-tracer.ts:81 [EXTRACTED]
  ```
  export function traceCallChains(facts: CodeFact[], files: CodeCollectedFile[]): CallChain[] {
  ```
- `buildIndexHubOverlay` ← src/wiki-engine/code-graph-overlay.ts:9 [EXTRACTED]
  ```
  export function buildIndexHubOverlay(
  ```
- `scanInterfaces` ← src/wiki-engine/interface-scanner.ts:69 [EXTRACTED]
  ```
  export async function scanInterfaces(files: CodeCollectedFile[]): Promise<InterfaceInventory> {
  ```
- `reconcileKnowledge` ← src/wiki-engine/knowledge-reconciler.ts:347 [EXTRACTED]
  ```
  export async function reconcileKnowledge(options: ReconcileOptions): Promise<ReconcileResult> {
  ```
- `isManifestV2` ← src/wiki-engine/manifest-schema.ts:89 [EXTRACTED]
  ```
  export function isManifestV2(manifest: CodebaseOutputManifest): manifest is CodebaseOutputManifestV2 {
  ```
- `labelFromScore` ← src/wiki-engine/reconciler-v2-types.ts:18 [EXTRACTED]
  ```
  export function labelFromScore(score: number): WikiConfidence {
  ```
- `buildConfidence` ← src/wiki-engine/reconciler-v2-types.ts:27 [EXTRACTED]
  ```
  export function buildConfidence(factors: ConfidenceFactor[]): NumericConfidence {
  ```
- `admitWorkflow` ← src/workflow/admission.ts:43 [EXTRACTED]
  ```
  export async function admitWorkflow(
  ```
- `heldSecret` ← src/workflow/admission.ts:228 [EXTRACTED]
  ```
  export function heldSecret<TValue>(value: TValue, secrets: Record<string, string>): string | undefined {
  ```
- `markedAttempt` ← src/workflow/attempt-marker.ts:20 [EXTRACTED]
  ```
  export function markedAttempt(env: NodeJS.ProcessEnv): MarkedAttempt | undefined {
  ```
- `attemptEnv` ← src/workflow/attempt-marker.ts:28 [EXTRACTED]
  ```
  export function attemptEnv(config: LocalConfig, run: string, attempt: string, mode: RunMode): Partial<Record<typeof EPHEMERAL_CONFIG_ENV, string>> & Record<typeof ATTEMPT_ENV | typeof RUN_MODE_ENV | typeof RUN_DIR_ENV, string> {
  ```
- `commandStepEnv` ← src/workflow/attempt-marker.ts:41 [EXTRACTED]
  ```
  export function commandStepEnv(config: LocalConfig, run: string, attempt: string, mode: RunMode): ReturnType<typeof attemptEnv> & Partial<Record<typeof STEP_COMMAND_ENV, string>> {
  ```
- `isCommandStep` ← src/workflow/attempt-marker.ts:50 [EXTRACTED]
  ```
  export function isCommandStep(env: NodeJS.ProcessEnv): boolean {
  ```
- `isAttemptRunner` ← src/workflow/attempt-marker.ts:57 [EXTRACTED]
  ```
  export function isAttemptRunner(env: NodeJS.ProcessEnv, run: string, attempt: string): boolean {
  ```
- `agentEvidence` ← src/workflow/attempt-marker.ts:72 [EXTRACTED]
  ```
  export function agentEvidence(env: NodeJS.ProcessEnv): AgentEvidence {
  ```
- `withoutOuterSessionMarkers` ← src/workflow/attempt-marker.ts:89 [EXTRACTED]
  ```
  export function withoutOuterSessionMarkers(env: NodeJS.ProcessEnv): NodeJS.ProcessEnv {
  ```
- `withoutAgentEvidence` ← src/workflow/attempt-marker.ts:97 [EXTRACTED]
  ```
  export function withoutAgentEvidence(env: NodeJS.ProcessEnv): NodeJS.ProcessEnv {
  ```
- `nestedCall` ← src/workflow/attempt-marker.ts:117 [EXTRACTED]
  ```
  export function nestedCall(env: NodeJS.ProcessEnv): Extract<Nested, { kind: 'marker' }> | undefined {
  ```
- `nestedStart` ← src/workflow/attempt-marker.ts:124 [EXTRACTED]
  ```
  export async function nestedStart(env: NodeJS.ProcessEnv, cwd: string): Promise<Nested | undefined> {
  ```
- `nestedWorkflowError` ← src/workflow/attempt-marker.ts:141 [EXTRACTED]
  ```
  export function nestedWorkflowError(nested: Nested): WorkflowFailure {
  ```
- `AttemptResult` ← src/workflow/attempt-result.ts:60 [EXTRACTED]
  ```
  export const AttemptResult = { write, mask, removeLeft } as const;
  ```
- `namespaceConflictOf` ← src/workflow/cache.ts:159 [EXTRACTED]
  ```
  export async function namespaceConflictOf(config: LocalConfig, name: string): Promise<string | undefined> {
  ```
- `loadCachedWorkflow` ← src/workflow/cache.ts:173 [EXTRACTED]
  ```
  export async function loadCachedWorkflow(config: LocalConfig, name: string): Promise<ResolvedWorkflow | null> {
  ```
- `startingAlias` ← src/workflow/cache.ts:188 [EXTRACTED]
  ```
  export async function startingAlias(config: LocalConfig, { name, alias }: { name: string; alias?: string }): Promise<string | undefined> {
  ```
- `resolveStart` ← src/workflow/cache.ts:197 [EXTRACTED]
  ```
  export async function resolveStart(config: LocalConfig, name: string): Promise<{ config: LocalConfig; workflow: ResolvedWorkflow | null }> {
  ```
- `listCachedWorkflows` ← src/workflow/cache.ts:218 [EXTRACTED]
  ```
  export async function listCachedWorkflows(config: LocalConfig): Promise<ResolvedWorkflow[]> {
  ```
- `workflowFileNames` ← src/workflow/cache.ts:279 [EXTRACTED]
  ```
  export async function workflowFileNames(dir: string): Promise<string[]> {
  ```
- `syncWorkflowDefinitions` ← src/workflow/cache.ts:298 [EXTRACTED]
  ```
  export async function syncWorkflowDefinitions(config: LocalConfig, options: SyncWorkflowOptions): Promise<SyncWorkflowResult> {
  ```
- `dropsKeptVersion` ← src/workflow/cache.ts:721 [EXTRACTED]
  ```
  export function dropsKeptVersion(diagnostics: WorkflowDiagnostic[]): boolean {
  ```
- `workflowsRunBy` ← src/workflow/cache.ts:730 [EXTRACTED]
  ```
  export function workflowsRunBy(definition: { steps: WorkflowStep[] }, prefix = ''): WorkflowRun[] {
  ```
- `loadWorkflowTree` ← src/workflow/cache.ts:866 [EXTRACTED]
  ```
  export async function loadWorkflowTree(
  ```
- `folderOf` ← src/workflow/cache.ts:960 [EXTRACTED]
  ```
  export function folderOf(cached: CachedWorkflow): PinnedFolder | undefined {
  ```
- `loadWorkflowBundle` ← src/workflow/cache.ts:964 [EXTRACTED]
  ```
  export async function loadWorkflowBundle(config: LocalConfig, name: string): Promise<WorkflowBundle | { failed: string }> {
  ```
- `loadWorkflowBundleAt` ← src/workflow/cache.ts:984 [EXTRACTED]
  ```
  export async function loadWorkflowBundleAt(config: LocalConfig, name: string, revision: string): Promise<WorkflowBundle | { failed: string }> {
  ```
- `teamCommitReach` ← src/workflow/cache.ts:1004 [EXTRACTED]
  ```
  export async function teamCommitReach(config: LocalConfig, revision: string): Promise<TeamCommitReach> {
  ```
- `withTeamRevision` ← src/workflow/cache.ts:1027 [EXTRACTED]
  ```
  export async function withTeamRevision<T>(
  ```
- `startAsCli` ← src/workflow/cli-start.ts:11 [EXTRACTED]
  ```
  export function startAsCli(client: Pick<WorkflowClient, 'start'>, name: string, { mode, ...options }: Omit<Parameters<WorkflowClient['start']>[1], 'caller' | 'startedBy' | 'instead'> & { mode: RunMode }): Promise<WorkflowEnvelope> {
  ```
- `CommitSchema` ← src/workflow/clone.ts:8 [EXTRACTED]
  ```
  export const CommitSchema = z.string().regex(/^[0-9a-f]{40}$/, 'must be a full 40-character commit');
  ```
- `TeamSelectionSchema` ← src/workflow/clone.ts:11 [EXTRACTED]
  ```
  export const TeamSelectionSchema = z.object({
  ```
- `TeamPathSchema` ← src/workflow/clone.ts:27 [EXTRACTED]
  ```
  export const TeamPathSchema = z.string().refine(
  ```
- `CloneTeamSchema` ← src/workflow/clone.ts:47 [EXTRACTED]
  ```
  export const CloneTeamSchema = z.union([
  ```
- `ClonePlaceSchema` ← src/workflow/clone.ts:64 [EXTRACTED]
  ```
  export const ClonePlaceSchema = z.object({
  ```
- `isConfinedTool` ← src/workflow/confined-launch.ts:33 [EXTRACTED]
  ```
  export function isConfinedTool(value: string): value is ConfinedTool {
  ```
- `installedConfinedTools` ← src/workflow/confined-launch.ts:38 [EXTRACTED]
  ```
  export function installedConfinedTools(preferred: readonly string[], { resolveTool = resolveCliPath }: ToolLookup = {}): ConfinedTool[] {
  ```
- `confinedEnvNames` ← src/workflow/confined-launch.ts:58 [EXTRACTED]
  ```
  export function confinedEnvNames(tool: string): readonly string[] {
  ```
- `confinedAccess` ← src/workflow/confined-launch.ts:63 [EXTRACTED]
  ```
  export function confinedAccess(tool: ConfinedTool): ConfinedAccess {
  ```
- `confinedToolLevel` ← src/workflow/confined-launch.ts:74 [EXTRACTED]
  ```
  export async function confinedToolLevel(tool: ConfinedTool, { resolveTool = resolveCliPath }: ToolLookup = {}): Promise<ConfinedToolLevel | undefined> {
  ```
- `confinedToolLevels` ← src/workflow/confined-launch.ts:89 [EXTRACTED]
  ```
  export async function confinedToolLevels({ resolveTool = resolveCliPath }: ToolLookup = {}): Promise<ConfinedToolLevel[]> {
  ```
- `confinedOffers` ← src/workflow/confined-launch.ts:106 [EXTRACTED]
  ```
  export async function confinedOffers(lookup: ToolLookup = {}): Promise<ConfinedOffer[]> {
  ```
- `runConfined` ← src/workflow/confined-launch.ts:195 [EXTRACTED]
  ```
  export async function runConfined(input: ConfinedInput, { resolveTool = resolveCliPath }: ToolLookup = {}): Promise<ConfinedResult> {
  ```
- `CONFINED_FILE` ← src/workflow/confined-place.ts:19 [EXTRACTED]
  ```
  export const CONFINED_FILE = 'confined.json';
  ```
- `ConfinedFileSchema` ← src/workflow/confined-place.ts:26 [EXTRACTED]
  ```
  export const ConfinedFileSchema = z.object({
  ```
- `checkConfinedDir` ← src/workflow/confined-place.ts:125 [EXTRACTED]
  ```
  export async function checkConfinedDir({ step, runDir, dir }: { step: string; runDir: string; dir: string }): Promise<ConfinedDirCheck> {
  ```
- `confinedCandidates` ← src/workflow/confined-place.ts:152 [EXTRACTED]
  ```
  export function confinedCandidates(offers: Offers, { level, prefer, require }: Pick<ConfinedFile, 'level' | 'prefer' | 'require'>): string[] {
  ```
- `decideConfined` ← src/workflow/confined-place.ts:197 [EXTRACTED]
  ```
  export async function decideConfined(request: ConfinedRequest): Promise<ConfinedDecision> {
  ```
- `runConfinedStep` ← src/workflow/confined-step.ts:137 [EXTRACTED]
  ```
  export async function runConfinedStep(input: ConfinedStepInput): Promise<ConfinedStepEnd> {
  ```
- `runConfinedStepOnRuntime` ← src/workflow/confined-step.ts:211 [EXTRACTED]
  ```
  export async function runConfinedStepOnRuntime(input: RuntimeConfinedInput): Promise<ConfinedStepEnd> {
  ```
- `PARALLEL_ROOTS` ← src/workflow/conformance-interpreter.ts:19 [EXTRACTED]
  ```
  export const PARALLEL_ROOTS = `schemaVersion: v1alpha1
  ```
- `controlsYaml` ← src/workflow/conformance-interpreter.ts:33 [EXTRACTED]
  ```
  export function controlsYaml(steps: string): string {
  ```
- `bothSkillProfiles` ← src/workflow/conformance-interpreter.ts:90 [EXTRACTED]
  ```
  export function bothSkillProfiles<T>(refusal: T) {
  ```
- `DRIVER_PROFILES` ← src/workflow/conformance-interpreter.ts:117 [EXTRACTED]
  ```
  export const DRIVER_PROFILES = {
  ```
- `DRIVERS_UNDER_TEST` ← src/workflow/conformance-interpreter.ts:166 [EXTRACTED]
  ```
  export const DRIVERS_UNDER_TEST = ['local', 'skill', 'skill-bare'] as const satisfies readonly DriverProfile[];
  ```
- `PROFILES_UNDER_TEST` ← src/workflow/conformance-interpreter.ts:173 [EXTRACTED]
  ```
  export const PROFILES_UNDER_TEST = [...DRIVERS_UNDER_TEST, 't3', 'paseo', 'sandbox'] as const satisfies readonly DriverProfile[];
  ```
- `profileDriver` ← src/workflow/conformance-interpreter.ts:176 [EXTRACTED]
  ```
  export function profileDriver(profile: DriverProfile): DriverIdentity {
  ```
- `inProcessConformanceClient` ← src/workflow/conformance-interpreter.ts:292 [EXTRACTED]
  ```
  export function inProcessConformanceClient(
  ```
- `profileLacks` ← src/workflow/conformance-interpreter.ts:351 [EXTRACTED]
  ```
  export function profileLacks(profile: DriverProfile, scenario: { yaml: string; workflows?: Record<string, string> } | BenchmarkScenario): string | undefined {
  ```
- `speaksAsDriverUnderTest` ← src/workflow/conformance-interpreter.ts:365 [EXTRACTED]
  ```
  export function speaksAsDriverUnderTest(scenario: ConformanceScenario): boolean {
  ```
- `runConformanceScenario` ← src/workflow/conformance-interpreter.ts:397 [EXTRACTED]
  ```
  export async function runConformanceScenario(scenario: ConformanceScenario, runner: ConformanceRunner, profile: DriverProfile): Promise<void> {
  ```
- `driveByProtocol` ← src/workflow/conformance-interpreter.ts:660 [EXTRACTED]
  ```
  export async function driveByProtocol(input: {
  ```
- `deliveringStep` ← src/workflow/delivery-ledger.ts:20 [EXTRACTED]
  ```
  export function deliveringStep(run: RunState, key: DeliveryKey): DeliveringStep | undefined {
  ```
- `nextDelivery` ← src/workflow/delivery-ledger.ts:46 [EXTRACTED]
  ```
  export function nextDelivery(
  ```
- `unresolvedCreate` ← src/workflow/delivery-ledger.ts:82 [EXTRACTED]
  ```
  export function unresolvedCreate(run: RunState, tried: readonly Omit<UnresolvedCreate, 'lookups'>[], team?: TeamCheckout): { create: UnresolvedCreate; checkout: string } | undefined {
  ```
- `sameCreate` ← src/workflow/delivery-ledger.ts:89 [EXTRACTED]
  ```
  export function sameCreate(a: Omit<UnresolvedCreate, 'lookups'>, b: Omit<UnresolvedCreate, 'lookups'>): boolean {
  ```
- `completeDelivery` ← src/workflow/delivery-ledger.ts:124 [EXTRACTED]
  ```
  export function completeDelivery(
  ```
- `resolveCreate` ← src/workflow/delivery-ledger.ts:151 [EXTRACTED]
  ```
  export function resolveCreate(run: RunState, create: UnresolvedCreate, found: Awaited<ReturnType<typeof findDelivered>>): DeliveryApplied {
  ```
- `CommitIdSchema` ← src/workflow/delivery-schema.ts:6 [EXTRACTED]
  ```
  export const CommitIdSchema = z.string().regex(/^(?:[0-9a-f]{40}|[0-9a-f]{64})$/);
  ```
- `DeliveryReceiptSchema` ← src/workflow/delivery-schema.ts:9 [EXTRACTED]
  ```
  export const DeliveryReceiptSchema = z.object({
  ```
- `UnresolvedCreateSchema` ← src/workflow/delivery-schema.ts:27 [EXTRACTED]
  ```
  export const UnresolvedCreateSchema = DeliveryKeySchema.extend({
  ```
- `needsAiTool` ← src/workflow/describe.ts:58 [EXTRACTED]
  ```
  export function needsAiTool(facts: Pick<WorkflowDescription['facts'], 'prompts' | 'scored' | 'produced'>): boolean {
  ```
- `definitionNeedsAiTool` ← src/workflow/describe.ts:63 [EXTRACTED]
  ```
  export function definitionNeedsAiTool(definition: WorkflowDefinition, workflows: Record<string, WorkflowDefinition>): boolean {
  ```
- `describeWorkflow` ← src/workflow/describe.ts:159 [EXTRACTED]
  ```
  export function describeWorkflow(input: {
  ```
- `DriverNameSchema` ← src/workflow/driver-name.ts:11 [EXTRACTED]
  ```
  export const DriverNameSchema = z.string().regex(DRIVER_NAME).brand<'DriverName'>();
  ```
- `LOCAL_DRIVER` ← src/workflow/driver-name.ts:16 [EXTRACTED]
  ```
  export const LOCAL_DRIVER = DriverNameSchema.parse(RESERVED_DRIVERS.local);
  ```
- `LOCAL_DEFINITION` ← src/workflow/driver-name.ts:19 [EXTRACTED]
  ```
  export const LOCAL_DEFINITION = DriverNameSchema.parse('teamai-local');
  ```
- `HOST_DRIVER` ← src/workflow/driver-name.ts:25 [EXTRACTED]
  ```
  export const HOST_DRIVER = DriverNameSchema.parse(RESERVED_DRIVERS.host);
  ```
- `parseDriver` ← src/workflow/driver-name.ts:32 [EXTRACTED]
  ```
  export function parseDriver(name: unknown): { ok: true; driver: Driver } | { ok: false; reason: string } {
  ```
- `SETTLED_ATTEMPTS_LIMIT` ← src/workflow/engine.ts:95 [EXTRACTED]
  ```
  export const SETTLED_ATTEMPTS_LIMIT = 32;
  ```
- `error` ← src/workflow/engine.ts:153 [EXTRACTED]
  ```
  export function error(code: string, message: string): Extract<WorkflowEnvelope, { error: unknown }> {
  ```
- `ok` ← src/workflow/engine.ts:161 [EXTRACTED]
  ```
  export function ok(value: EnvelopeData): WorkflowEnvelope {
  ```
- `withIgnored` ← src/workflow/engine.ts:169 [EXTRACTED]
  ```
  export function withIgnored(envelope: WorkflowEnvelope, ignored: string[]): WorkflowEnvelope {
  ```
- `withRun` ← src/workflow/engine.ts:191 [EXTRACTED]
  ```
  export async function withRun(
  ```
- `workflowLabel` ← src/workflow/engine.ts:253 [EXTRACTED]
  ```
  export function workflowLabel(scope: Scope): string {
  ```
- `fromRequirements` ← src/workflow/engine.ts:258 [EXTRACTED]
  ```
  export function fromRequirements(run: RunState, path: string): InEffect[] {
  ```
- `respondCommand` ← src/workflow/engine.ts:352 [EXTRACTED]
  ```
  export function respondCommand(run: string, step: string, choice: string, pass: number): string {
  ```
- `personSteps` ← src/workflow/engine.ts:477 [EXTRACTED]
  ```
  export function personSteps(run: RunState, now: string, { autoApprove }: { autoApprove: boolean }): PersonStep[] {
  ```
- `finishRun` ← src/workflow/engine.ts:695 [EXTRACTED]
  ```
  export async function finishRun(
  ```
- `runData` ← src/workflow/engine.ts:725 [EXTRACTED]
  ```
  export function runData(run: RunState): RunData {
  ```
- `parseReads` ← src/workflow/engine.ts:852 [EXTRACTED]
  ```
  export function parseReads(run: RunState, scope: Scope): RunReads | string {
  ```
- `reconcileRun` ← src/workflow/engine.ts:1432 [EXTRACTED]
  ```
  export function reconcileRun(run: RunState, now: string): Settled {
  ```
- `admitStart` ← src/workflow/engine.ts:1481 [EXTRACTED]
  ```
  export async function admitStart(
  ```
- `startRun` ← src/workflow/engine.ts:1534 [EXTRACTED]
  ```
  export async function startRun(
  ```
- `createRun` ← src/workflow/engine.ts:1577 [EXTRACTED]
  ```
  export async function createRun(
  ```
- `promptTool` ← src/workflow/engine.ts:1688 [EXTRACTED]
  ```
  export function promptTool(step: WorkflowStep, toolFor: ToolFor | undefined): string | undefined {
  ```
- `restartQueued` ← src/workflow/engine.ts:1839 [EXTRACTED]
  ```
  export function restartQueued(run: RunState, driver: DriverIdentity, queued: ReadonlySet<string>, now: string): void {
  ```
- `leaseNext` ← src/workflow/engine.ts:2367 [EXTRACTED]
  ```
  export async function leaseNext(config: LocalConfig, runId: string, driver: DriverIdentity, options: NextOptions = {}): Promise<WorkflowEnvelope> {
  ```
- `parseResponsePayload` ← src/workflow/engine.ts:2917 [EXTRACTED]
  ```
  export function parseResponsePayload(value: unknown): ParsedResponsePayload | string {
  ```
- `parseReport` ← src/workflow/engine.ts:2958 [EXTRACTED]
  ```
  export function parseReport(value: unknown): ParsedReport | string {
  ```
- `parseNextPayload` ← src/workflow/engine.ts:3139 [EXTRACTED]
  ```
  export function parseNextPayload(value: unknown): ParsedNextPayload | string {
  ```
- `resumableSessions` ← src/workflow/engine.ts:3302 [EXTRACTED]
  ```
  export function resumableSessions(run: RunState): LeaseSession[] {
  ```
- `continuedConversations` ← src/workflow/engine.ts:3313 [EXTRACTED]
  ```
  export function continuedConversations(run: RunState): Array<SessionRef & { workspace: string }> {
  ```
- `reportable` ← src/workflow/engine.ts:3487 [EXTRACTED]
  ```
  export async function reportable(config: LocalConfig, runId: string, report: ReportInput): Promise<boolean> {
  ```
- `reportAttempt` ← src/workflow/engine.ts:3563 [EXTRACTED]
  ```
  export async function reportAttempt(config: LocalConfig, runId: string, report: ReportInput, secrets?: Record<string, string>): Promise<WorkflowEnvelope> {
  ```
- `EphemeralScope` ← src/workflow/ephemeral-scope.ts:59 [EXTRACTED]
  ```
  export const EphemeralScope = { open } as const;
  ```
- `isIndex` ← src/workflow/expression.ts:16 [EXTRACTED]
  ```
  export function isIndex(field: PathField | undefined): field is number {
  ```
- `jsonType` ← src/workflow/expression.ts:27 [EXTRACTED]
  ```
  export function jsonType(value: JsonValue): JsonType {
  ```
- `branchNames` ← src/workflow/expression.ts:88 [EXTRACTED]
  ```
  export function branchNames(results: Array<{ branch?: string }> | undefined): string[] | undefined {
  ```
- `parseFields` ← src/workflow/expression.ts:276 [EXTRACTED]
  ```
  export function parseFields(text: string): { ok: true; fields: PathField[] } | { ok: false; message: string } {
  ```
- `stepFieldSchema` ← src/workflow/expression.ts:340 [EXTRACTED]
  ```
  export function stepFieldSchema(field: Extract<ExpressionPath, { root: 'steps' }>['field'], output: OutputSchema | undefined, forEach: boolean, choices?: string[]): DeclaredType | undefined {
  ```
- `typeProblems` ← src/workflow/expression.ts:632 [EXTRACTED]
  ```
  export function typeProblems(expression: Expression, schemaOf: SchemaOf = () => undefined): TypeProblem[] {
  ```
- `parseExpression` ← src/workflow/expression.ts:679 [EXTRACTED]
  ```
  export function parseExpression(source: string): ExpressionParse {
  ```
- `readsLikeExpression` ← src/workflow/expression.ts:703 [EXTRACTED]
  ```
  export function readsLikeExpression(source: string, path: RegExp): boolean {
  ```
- `isRecord` ← src/workflow/expression.ts:738 [EXTRACTED]
  ```
  export function isRecord(value: unknown): value is Record<string, unknown> {
  ```
- `fieldsText` ← src/workflow/expression.ts:744 [EXTRACTED]
  ```
  export function fieldsText(fields: PathField[]): string {
  ```
- `resolvePath` ← src/workflow/expression.ts:749 [EXTRACTED]
  ```
  export function resolvePath(path: ExpressionPath, context: ExpressionContext): JsonValue {
  ```
- `pathValue` ← src/workflow/expression.ts:754 [EXTRACTED]
  ```
  export function pathValue(path: ExpressionPath, context: ExpressionContext): JsonValue | undefined {
  ```
- `schemaAt` ← src/workflow/expression.ts:763 [EXTRACTED]
  ```
  export function schemaAt(schema: DeclaredType, fields: PathField[]): DeclaredType | undefined {
  ```
- `isTruthy` ← src/workflow/expression.ts:795 [EXTRACTED]
  ```
  export function isTruthy(value: JsonValue): boolean {
  ```
- `evaluateExpression` ← src/workflow/expression.ts:829 [EXTRACTED]
  ```
  export function evaluateExpression(expression: Expression, context: ExpressionContext): JsonValue {
  ```
- `expressionPaths` ← src/workflow/expression.ts:871 [EXTRACTED]
  ```
  export function expressionPaths(expression: Expression): ExpressionPath[] {
  ```
- `FAILURE_CODES` ← src/workflow/failure-codes.ts:11 [EXTRACTED]
  ```
  export const FAILURE_CODES = [
  ```
- `isFailureCode` ← src/workflow/failure-codes.ts:115 [EXTRACTED]
  ```
  export function isFailureCode(code: string): code is FailureCode {
  ```
- `isItem` ← src/workflow/fan-out.ts:16 [EXTRACTED]
  ```
  export function isItem(state: StepState): boolean {
  ```
- `itemsOf` ← src/workflow/fan-out.ts:21 [EXTRACTED]
  ```
  export function itemsOf(run: RunState, state: StepState): StepState[] {
  ```
- `addItems` ← src/workflow/fan-out.ts:26 [EXTRACTED]
  ```
  export function addItems(run: RunState, state: StepState, items: unknown[]): void {
  ```
- `expandItems` ← src/workflow/fan-out.ts:48 [EXTRACTED]
  ```
  export function expandItems(id: string, value: JsonValue | undefined): unknown[] | WorkflowFailure {
  ```
- `itemsAfter` ← src/workflow/fan-out.ts:87 [EXTRACTED]
  ```
  export function itemsAfter(id: string, items: unknown[]): number[][] | WorkflowFailure {
  ```
- `afterStanding` ← src/workflow/fan-out.ts:127 [EXTRACTED]
  ```
  export function afterStanding(after: StepState[]): 'ready' | 'waiting' | 'skip' {
  ```
- `startedItems` ← src/workflow/fan-out.ts:134 [EXTRACTED]
  ```
  export function startedItems(items: StepState[]): number {
  ```
- `itemLimit` ← src/workflow/fan-out.ts:142 [EXTRACTED]
  ```
  export function itemLimit(step: Pick<WorkflowStep, 'id' | 'forEach'>, inputs: RunState['inputs']): { ok: true; limit: number | undefined } | { ok: false; message: string } {
  ```
- `itemLimitMismatch` ← src/workflow/fan-out.ts:158 [EXTRACTED]
  ```
  export function itemLimitMismatch(steps: readonly WorkflowStep[], inputs: RunState['inputs']): string | undefined {
  ```
- `itemsSettled` ← src/workflow/fan-out.ts:183 [EXTRACTED]
  ```
  export function itemsSettled(
  ```
- `keptResults` ← src/workflow/fan-out.ts:197 [EXTRACTED]
  ```
  export function keptResults(run: RunState, state: StepState, definition: WorkflowStep | undefined): ItemResult[] | undefined {
  ```
- `WORKFLOW_MARKER` ← src/workflow/folder.ts:22 [EXTRACTED]
  ```
  export const WORKFLOW_MARKER = FOLDER_MARKERS.workflows.marker;
  ```
- `WorkflowFolder` ← src/workflow/folder.ts:228 [EXTRACTED]
  ```
  export const WorkflowFolder = { MAX_BYTES, read, withinLimit, shipped, hash, dir, env, named, pin, prune } as const;
  ```
- `publishRun` ← src/workflow/handoff.ts:266 [EXTRACTED]
  ```
  export async function publishRun(config: LocalConfig, runId: string, options: OfferOptions): Promise<Result<PublishReceipt>> {
  ```
- `STALE_WINDOW_MS` ← src/workflow/handoff.ts:770 [EXTRACTED]
  ```
  export const STALE_WINDOW_MS = 60 * 60_000;
  ```
- `publishRunEnd` ← src/workflow/handoff.ts:800 [EXTRACTED]
  ```
  export async function publishRunEnd(config: LocalConfig, runId: string, checkout: string): Promise<HandoffError | undefined> {
  ```
- `offerToPerson` ← src/workflow/handoff.ts:845 [EXTRACTED]
  ```
  export async function offerToPerson(config: LocalConfig, runId: string, options: Pick<OfferOptions, 'checkout' | 'live'>): Promise<string | undefined> {
  ```
- `offeredToPerson` ← src/workflow/handoff.ts:857 [EXTRACTED]
  ```
  export function offeredToPerson(runId: string, steps: readonly string[], resume: string): string {
  ```
- `claimRun` ← src/workflow/handoff.ts:893 [EXTRACTED]
  ```
  export async function claimRun(config: LocalConfig, runId: string, options: { checkout: string; takeover?: Takeover }): Promise<Result<ClaimReceipt>> {
  ```
- `takeoverFor` ← src/workflow/handoff.ts:913 [EXTRACTED]
  ```
  export function takeoverFor({ mode, confirmed }: { mode: RunMode; confirmed: boolean }): Takeover {
  ```
- `claimOffered` ← src/workflow/handoff.ts:923 [EXTRACTED]
  ```
  export async function claimOffered(config: LocalConfig, runId: string, options: { checkout: string }): Promise<Result<ClaimReceipt>> {
  ```
- `leaseRefusal` ← src/workflow/handoff.ts:939 [EXTRACTED]
  ```
  export async function leaseRefusal(config: LocalConfig, runId: string, { throttled }: { throttled: boolean }): Promise<HandoffError | undefined> {
  ```
- `resumeRun` ← src/workflow/handoff.ts:989 [EXTRACTED]
  ```
  export async function resumeRun(config: LocalConfig, runId: string, options: { claim: boolean; checkout: string; takeover?: Takeover }): Promise<Result<ClaimReceipt | null>> {
  ```
- `settledSteps` ← src/workflow/handoff.ts:1019 [EXTRACTED]
  ```
  export function settledSteps({ steps, definition, workflows = {} }: { steps: ReadonlyArray<{ id: string; status: string; loopFinal?: boolean }>; definition: WorkflowDefinition; workflows?: Record<string, WorkflowDefinition> }): string[] {
  ```
- `carriedRun` ← src/workflow/handoff.ts:1116 [EXTRACTED]
  ```
  export async function carriedRun(config: LocalConfig, runId: string, { published: alreadyPublished, claim = false }: { published: boolean; claim?: boolean }): Promise<Result<CarriedRun | undefined>> {
  ```
- `reconcileTakenCopies` ← src/workflow/handoff.ts:1143 [EXTRACTED]
  ```
  export async function reconcileTakenCopies(config: LocalConfig, runId: string, active: string): Promise<WorkflowFailure | undefined> {
  ```
- `takeoverRefusal` ← src/workflow/handoff.ts:1341 [EXTRACTED]
  ```
  export async function takeoverRefusal(config: LocalConfig, snapshot: RunSnapshot, takeover: Takeover): Promise<HandoffError | undefined> {
  ```
- `handedRun` ← src/workflow/handoff.ts:1430 [EXTRACTED]
  ```
  export function handedRun(snapshot: RunSnapshot, definitions: Definitions, handed = handedOver(snapshot, definitions)): RunState {
  ```
- `definitionsOf` ← src/workflow/handoff.ts:1450 [EXTRACTED]
  ```
  export async function definitionsOf(config: LocalConfig, snapshot: { run: string } & RunDefinition & Partial<Pick<RunSnapshot, 'teamPin'>>): Promise<Result<Definitions>> {
  ```
- `settledHere` ← src/workflow/judge-work.ts:19 [EXTRACTED]
  ```
  export function settledHere(run: RunState, pass: RunPass, install: string): boolean {
  ```
- `judgeablePasses` ← src/workflow/judge-work.ts:27 [EXTRACTED]
  ```
  export function judgeablePasses(run: RunState): Array<{ pass: RunPass; definition: WorkflowStep }> {
  ```
- `scoredPasses` ← src/workflow/judge-work.ts:46 [EXTRACTED]
  ```
  export function scoredPasses(run: RunState, install: string): ScorablePass[] {
  ```
- `resolveKeptSetting` ← src/workflow/kept-setting.ts:15 [EXTRACTED]
  ```
  export async function resolveKeptSetting<T>(
  ```
- `ConfinedLeaseSchema` ← src/workflow/lease-wire.ts:17 [EXTRACTED]
  ```
  export const ConfinedLeaseSchema = z.object({ dir: z.string().min(1), level: ConfinedLevelSchema, schema: z.string().min(1).optional(), tools: z.array(z.string().min(1)).min(1) });
  ```
- `LeaseIdSchema` ← src/workflow/lease-wire.ts:22 [EXTRACTED]
  ```
  export const LeaseIdSchema = z.object({ attempt: AttemptIdSchema, revision: z.number().int() });
  ```
- `LeaseWireSchema` ← src/workflow/lease-wire.ts:25 [EXTRACTED]
  ```
  export const LeaseWireSchema = LeaseIdSchema.extend({
  ```
- `warnNotDeleted` ← src/workflow/leftovers.ts:185 [EXTRACTED]
  ```
  export function warnNotDeleted(runId: string, failed: RunLeftovers['failed']): void {
  ```
- `cleanUpSucceededRun` ← src/workflow/leftovers.ts:248 [EXTRACTED]
  ```
  export async function cleanUpSucceededRun(
  ```
- `restoreRecordedBranches` ← src/workflow/leftovers.ts:291 [EXTRACTED]
  ```
  export async function restoreRecordedBranches(run: RunState, checkout: string): Promise<RunLeftovers['failed']> {
  ```
- `settledBranches` ← src/workflow/leftovers.ts:355 [EXTRACTED]
  ```
  export function settledBranches(run: RunState): SettledBranches | undefined {
  ```
- `sweepLeftovers` ← src/workflow/leftovers.ts:679 [EXTRACTED]
  ```
  export async function sweepLeftovers(config: LocalConfig, team: Pick<TeamaiConfig, 'workflows'> | null, { now, checkout }: { now: number; checkout: string }): Promise<Sweep> {
  ```
- `ownDeadline` ← src/workflow/limits.ts:32 [EXTRACTED]
  ```
  export function ownDeadline(run: RunState, state: StepState, step: WorkflowStep, now: string): string | undefined {
  ```
- `spentTokens` ← src/workflow/limits.ts:45 [EXTRACTED]
  ```
  export function spentTokens(run: RunState, under: (id: string) => boolean): number {
  ```
- `spentUsage` ← src/workflow/limits.ts:81 [EXTRACTED]
  ```
  export function spentUsage(run: RunState): Required<TokenUsage> {
  ```
- `countLateTokens` ← src/workflow/limits.ts:105 [EXTRACTED]
  ```
  export function countLateTokens(run: RunState, stopped: StoppedAttempt, tokens: TokenUsage): void {
  ```
- `startLimits` ← src/workflow/limits.ts:122 [EXTRACTED]
  ```
  export function startLimits(run: RunState, state: StepState, step: WorkflowStep, now: string): StartLimits {
  ```
- `budgetSpent` ← src/workflow/limits.ts:143 [EXTRACTED]
  ```
  export function budgetSpent(run: RunState, scope: Scope): number {
  ```
- `itemsSpent` ← src/workflow/limits.ts:148 [EXTRACTED]
  ```
  export function itemsSpent(run: RunState, state: StepState): number {
  ```
- `runDeadline` ← src/workflow/limits.ts:156 [EXTRACTED]
  ```
  export function runDeadline(run: RunState): string | undefined {
  ```
- `leaseDeadline` ← src/workflow/limits.ts:164 [EXTRACTED]
  ```
  export function leaseDeadline(run: RunState, state: LeasedStep): string | undefined {
  ```
- `expire` ← src/workflow/limits.ts:179 [EXTRACTED]
  ```
  export function expire(run: RunState, now: string): WorkflowResult | undefined {
  ```
- `spentAllowances` ← src/workflow/limits.ts:235 [EXTRACTED]
  ```
  export function spentAllowances(run: RunState, scope: Scope): string[] {
  ```
- `allowanceInUse` ← src/workflow/limits.ts:243 [EXTRACTED]
  ```
  export function allowanceInUse(run: RunState, scope: Scope): string | undefined {
  ```
- `turnLimits` ← src/workflow/limits.ts:261 [EXTRACTED]
  ```
  export function turnLimits(run: RunState, scope: Scope, step: WorkflowStep): TurnLimits | undefined {
  ```
- `spendAllowances` ← src/workflow/limits.ts:310 [EXTRACTED]
  ```
  export function spendAllowances(run: RunState, scope: Scope, limits: TurnLimits, limit: Limit): void {
  ```
- `idleLimit` ← src/workflow/limits.ts:327 [EXTRACTED]
  ```
  export function idleLimit(config: LocalConfig): { ms?: number } | { failure: WorkflowFailure } {
  ```
- `budgetLeft` ← src/workflow/limits.ts:347 [EXTRACTED]
  ```
  export function budgetLeft(run: RunState, path: string): number | undefined {
  ```
- `ancestors` ← src/workflow/loop.ts:33 [EXTRACTED]
  ```
  export function ancestors(needs: Map<string, string[]>, id: string): Set<string> {
  ```
- `stepLoops` ← src/workflow/loop.ts:53 [EXTRACTED]
  ```
  export function stepLoops(steps: LoopStep[]): StepLoops {
  ```
- `firstCycle` ← src/workflow/loop.ts:73 [EXTRACTED]
  ```
  export function firstCycle(ids: string[], edges: Map<string, string[]>): string[] | undefined {
  ```
- `loopProblems` ← src/workflow/loop.ts:115 [EXTRACTED]
  ```
  export function loopProblems(steps: LoopStep[], reads: Map<string, Set<string>>, looping: boolean): LoopProblem[] {
  ```
- `loopSettled` ← src/workflow/loop.ts:187 [EXTRACTED]
  ```
  export function loopSettled(owner: StepState | undefined): boolean {
  ```
- `decideStepLoop` ← src/workflow/loop.ts:218 [EXTRACTED]
  ```
  export function decideStepLoop(run: RunState, owner: Extract<StepState, { status: 'succeeded' }>, loop: StepLoop, holds: boolean, range: StepState[]): void {
  ```
- `exhaustedAtStart` ← src/workflow/loop.ts:240 [EXTRACTED]
  ```
  export function exhaustedAtStart(owner: Extract<StepState, { status: 'pending' }>, loop: StepLoop, settledAt: number): boolean {
  ```
- `decideRound` ← src/workflow/loop.ts:254 [EXTRACTED]
  ```
  export function decideRound(
  ```
- `isUnder` ← src/workflow/loop.ts:285 [EXTRACTED]
  ```
  export function isUnder(path: string): (id: string) => boolean {
  ```
- `archiveUnder` ← src/workflow/loop.ts:290 [EXTRACTED]
  ```
  export function archiveUnder(run: RunState, path: string): void {
  ```
- `archiveSteps` ← src/workflow/loop.ts:298 [EXTRACTED]
  ```
  export function archiveSteps(run: RunState, ids: ReadonlySet<string>): void {
  ```
- `runPasses` ← src/workflow/loop.ts:323 [EXTRACTED]
  ```
  export function runPasses(run: RunState, currentPass: (state: StepState) => StepPass | undefined = passOf): RunPass[] {
  ```
- `passRange` ← src/workflow/loop.ts:335 [EXTRACTED]
  ```
  export function passRange(pass: StepPass): { branch: string; from: string; to: string; source: 'changes' | 'read' } | undefined {
  ```
- `firstSettled` ← src/workflow/loop.ts:348 [EXTRACTED]
  ```
  export function firstSettled<T extends RunPass>(passes: readonly T[]): T | undefined {
  ```
- `passesWithin` ← src/workflow/loop.ts:363 [EXTRACTED]
  ```
  export function passesWithin(run: RunState, all: readonly RunPass[], step: string, pass: number): RunPass[] {
  ```
- `firstPass` ← src/workflow/loop.ts:383 [EXTRACTED]
  ```
  export function firstPass(run: RunState, path: string): number {
  ```
- `passesOf` ← src/workflow/loop.ts:409 [EXTRACTED]
  ```
  export function passesOf(state: StepState): ExpressionPass[] {
  ```
- `previousPass` ← src/workflow/loop.ts:416 [EXTRACTED]
  ```
  export function previousPass(state: StepState): ExpressionStep {
  ```
- `memberTools` ← src/workflow/member-tools.ts:21 [EXTRACTED]
  ```
  export async function memberTools(scope: LocalConfig | undefined): Promise<MemberTool[]> {
  ```
- `CallError` ← src/workflow/member-tools.ts:41 [EXTRACTED]
  ```
  export class CallError extends Error {
  ```
- `isOverrideInvalid` ← src/workflow/member-tools.ts:53 [EXTRACTED]
  ```
  export function isOverrideInvalid(error: unknown): error is CallError & { kind: 'override_invalid' } {
  ```
- `BundleSchema` ← src/workflow/output.ts:7 [EXTRACTED]
  ```
  export const BundleSchema = z.object({
  ```
- `outputMismatch` ← src/workflow/output.ts:22 [EXTRACTED]
  ```
  export function outputMismatch(schema: OutputSchema, value: unknown, path = 'output'): string | null {
  ```
- `expectedOutput` ← src/workflow/output.ts:116 [EXTRACTED]
  ```
  export function expectedOutput(schema: OutputSchema | undefined): string {
  ```
- `isYamlNode` ← src/workflow/parse-context.ts:8 [EXTRACTED]
  ```
  export function isYamlNode(value: unknown): value is Node {
  ```
- `locate` ← src/workflow/parse-context.ts:12 [EXTRACTED]
  ```
  export function locate(file: string, lineCounter: LineCounter, node: Node | null | undefined, field: string, message: string): WorkflowDiagnostic {
  ```
- `scalarOf` ← src/workflow/parse-context.ts:33 [EXTRACTED]
  ```
  export function scalarOf<T>(node: Node | null | undefined, schema: z.ZodType<T>): T | undefined {
  ```
- `scalarString` ← src/workflow/parse-context.ts:40 [EXTRACTED]
  ```
  export function scalarString(node: Node | null | undefined): string | undefined {
  ```
- `scalarText` ← src/workflow/parse-context.ts:45 [EXTRACTED]
  ```
  export function scalarText(node: Node | null | undefined): string | undefined {
  ```
- `undeclaredOutput` ← src/workflow/parse-context.ts:84 [EXTRACTED]
  ```
  export function undeclaredOutput(children: Map<string, Child>, path: ExpressionPath): string | undefined {
  ```
- `unavailableField` ← src/workflow/parse-context.ts:100 [EXTRACTED]
  ```
  export function unavailableField(path: ExpressionPath, forEach: boolean, choices: string[] | undefined, delivers: boolean): string | undefined {
  ```
- `undeclaredField` ← src/workflow/parse-context.ts:129 [EXTRACTED]
  ```
  export function undeclaredField(path: ExpressionPath, output: OutputSchema | undefined, forEach: boolean, choices?: string[]): string | undefined {
  ```
- `position` ← src/workflow/parse-context.ts:160 [EXTRACTED]
  ```
  export function position(lineCounter: LineCounter, node: Node | null | undefined): Position {
  ```
- `unknownKey` ← src/workflow/parse-context.ts:167 [EXTRACTED]
  ```
  export function unknownKey(file: string, lineCounter: LineCounter, node: Node | null | undefined, field: string, key: string): WorkflowDiagnostic {
  ```
- `valueNode` ← src/workflow/parse-context.ts:175 [EXTRACTED]
  ```
  export function valueNode(map: Node | null | undefined, key: string): Node | undefined {
  ```
- `parseHitl` ← src/workflow/parse-hitl.ts:7 [EXTRACTED]
  ```
  export function parseHitl(kind: StepHitl['kind'], node: Node | null | undefined, field: string, ctx: ParseContext): StepHitl | undefined {
  ```
- `roleDiagnostics` ← src/workflow/parse-roles.ts:181 [EXTRACTED]
  ```
  export function roleDiagnostics(root: Node, workflow: Pick<WorkflowDefinition, 'defaults' | 'workspace'> & { steps: readonly WorkflowStep[] }, ctx: ParseContext): WorkflowDiagnostic[] {
  ```
- `INVOKE_ALIAS_SINCE` ← src/workflow/parse.ts:39 [EXTRACTED]
  ```
  export const INVOKE_ALIAS_SINCE = '0.28.0';
  ```
- `STEP_ROLE_SINCE` ← src/workflow/parse.ts:45 [EXTRACTED]
  ```
  export const STEP_ROLE_SINCE = '0.29.0';
  ```
- `workflowFolderName` ← src/workflow/parse.ts:101 [EXTRACTED]
  ```
  export function workflowFolderName(file: string): string | undefined {
  ```
- `formatDiagnostic` ← src/workflow/parse.ts:107 [EXTRACTED]
  ```
  export function formatDiagnostic(diagnostic: WorkflowDiagnostic): string {
  ```
- `parseWorkflow` ← src/workflow/parse.ts:236 [EXTRACTED]
  ```
  export function parseWorkflow(file: string, content: string, files?: WorkflowFiles): {
  ```
- `workflowField` ← src/workflow/parse.ts:1303 [EXTRACTED]
  ```
  export function workflowField(output: OutputSchema | undefined): string | undefined {
  ```
- `promptFileDiagnostics` ← src/workflow/parse.ts:2288 [EXTRACTED]
  ```
  export function promptFileDiagnostics(
  ```
- `resolveFolderFiles` ← src/workflow/parse.ts:2350 [EXTRACTED]
  ```
  export function resolveFolderFiles(
  ```
- `stepField` ← src/workflow/parse.ts:2389 [EXTRACTED]
  ```
  export function stepField(trail: number[]): string {
  ```
- `commandStepPart` ← src/workflow/part-of-step.ts:30 [EXTRACTED]
  ```
  export async function commandStepPart(config: LocalConfig, env: NodeJS.ProcessEnv): Promise<PartOfStep | undefined> {
  ```
- `recordPart` ← src/workflow/part-of-step.ts:40 [EXTRACTED]
  ```
  export async function recordPart(config: LocalConfig, partOf: PartOfStep, run: RunId): Promise<void> {
  ```
- `partsOf` ← src/workflow/part-of-step.ts:47 [EXTRACTED]
  ```
  export async function partsOf(config: LocalConfig, partOf: PartOfStep): Promise<RunId[]> {
  ```
- `isPartOf` ← src/workflow/part-of-step.ts:61 [EXTRACTED]
  ```
  export function isPartOf(partOf: PartOfStep | undefined, { run, attempt }: PartOfStep): boolean {
  ```
- `judgeStepAttempt` ← src/workflow/part-of-step.ts:116 [EXTRACTED]
  ```
  export async function judgeStepAttempt(config: LocalConfig, partOf: PartOfStep, now: string): Promise<StepAttempt> {
  ```
- `stoppedFailure` ← src/workflow/part-of-step.ts:140 [EXTRACTED]
  ```
  export async function stoppedFailure(config: LocalConfig, partOf: PartOfStep, now: string): Promise<WorkflowFailure> {
  ```
- `DELIVERY_TIMEOUT_MS` ← src/workflow/pr-delivery.ts:71 [EXTRACTED]
  ```
  export const DELIVERY_TIMEOUT_MS = 30_000;
  ```
- `deliverPr` ← src/workflow/pr-delivery.ts:89 [EXTRACTED]
  ```
  export async function deliverPr(job: DeliveryJob, gate: CreateGate): Promise<DeliveryOutcome | 'busy'> {
  ```
- `reportedPrMismatch` ← src/workflow/pr-delivery.ts:195 [EXTRACTED]
  ```
  export async function reportedPrMismatch(
  ```
- `findDelivered` ← src/workflow/pr-delivery.ts:214 [EXTRACTED]
  ```
  export async function findDelivered(
  ```
- `deliveredCi` ← src/workflow/pr-delivery.ts:229 [EXTRACTED]
  ```
  export async function deliveredCi({ checkout, commit }: { checkout: string; commit: string }): Promise<
  ```
- `deliveryFailure` ← src/workflow/pr-delivery.ts:322 [EXTRACTED]
  ```
  export function deliveryFailure({ runId, key, recordedHead, openedBy }: Pick<DeliveryJob, 'runId' | 'key' | 'recordedHead' | 'openedBy'>, fault: DeliveryFault): DeliveryFailure {
  ```
- `PrUrlSchema` ← src/workflow/pr-url.ts:9 [EXTRACTED]
  ```
  export const PrUrlSchema = z.string().transform((value, ctx) => {
  ```
- `sanitizePrUrl` ← src/workflow/pr-url.ts:45 [EXTRACTED]
  ```
  export function sanitizePrUrl(value: unknown): { url: PrUrl; reason?: never } | { url?: never; reason: string } {
  ```
- `StartedRunSchema` ← src/workflow/protocol.ts:44 [EXTRACTED]
  ```
  export const StartedRunSchema = z.object({ run: RunIdSchema, step: z.string(), pass: z.number().int().positive(), scorers: z.array(z.string()) });
  ```
- `invokeDeniedMessage` ← src/workflow/protocol.ts:244 [EXTRACTED]
  ```
  export function invokeDeniedMessage(name: string, evidence: Exclude<AgentEvidence, { kind: 'none' }>, act: InvokeAct): string {
  ```
- `INVOKE_ASK_NEED` ← src/workflow/protocol.ts:261 [EXTRACTED]
  ```
  export const INVOKE_ASK_NEED = 'the team asks that a person agree before it starts (invoke: ask)';
  ```
- `unattendedReason` ← src/workflow/protocol.ts:264 [EXTRACTED]
  ```
  export function unattendedReason(name: string, needs: string, act: 'start' | 'continue'): string {
  ```
- `invokeRefusal` ← src/workflow/protocol.ts:277 [EXTRACTED]
  ```
  export function invokeRefusal(definition: WorkflowDefinition | undefined, caller: InvokeCaller, act: InvokeAct): WorkflowFailure | undefined {
  ```
- `resumeRefusal` ← src/workflow/protocol.ts:332 [EXTRACTED]
  ```
  export async function resumeRefusal(
  ```
- `continuedAttempt` ← src/workflow/protocol.ts:356 [EXTRACTED]
  ```
  export async function continuedAttempt(config: LocalConfig, run: RunId, step: string): Promise<{ step: string; attempt: AttemptId } | undefined> {
  ```
- `workflowNotFound` ← src/workflow/protocol.ts:391 [EXTRACTED]
  ```
  export function workflowNotFound(name: string): WorkflowFailure {
  ```
- `verifiedLeftOpen` ← src/workflow/protocol.ts:447 [EXTRACTED]
  ```
  export function verifiedLeftOpen(scorers: readonly string[]): string {
  ```
- `unreadablePlace` ← src/workflow/protocol.ts:541 [EXTRACTED]
  ```
  export function unreadablePlace(run: RunId): WorkflowFailure {
  ```
- `preparedPlace` ← src/workflow/protocol.ts:597 [EXTRACTED]
  ```
  export async function preparedPlace(input: Parameters<typeof preparePlace>[0]): Promise<PlacePrepared> {
  ```
- `inProcessClient` ← src/workflow/protocol.ts:653 [EXTRACTED]
  ```
  export function inProcessClient({ config, env }: { config: LocalConfig; env: WorkflowEnv }): WorkflowClient {
  ```
- `managedReport` ← src/workflow/protocol.ts:996 [EXTRACTED]
  ```
  export async function managedReport(input: { config: LocalConfig; runId: string; report: ReportInput; secrets: Record<string, string>; lock: RunLock | undefined; changed?: readonly string[] }): Promise<WorkflowEnvelope> {
  ```
- `INPUT_REJECTED_EXIT` ← src/workflow/protocol.ts:1099 [EXTRACTED]
  ```
  export const INPUT_REJECTED_EXIT = 65;
  ```
- `commandExitMessage` ← src/workflow/protocol.ts:1102 [EXTRACTED]
  ```
  export function commandExitMessage(exitCode: number): string {
  ```
- `commandEnd` ← src/workflow/protocol.ts:1120 [EXTRACTED]
  ```
  export function commandEnd(result: { exitCode: number; stdout: string; stderr: string }): CommandEnd {
  ```
- `isRefusal` ← src/workflow/protocol.ts:1139 [EXTRACTED]
  ```
  export function isRefusal<TParsed extends object>(parsed: TParsed | string): parsed is string {
  ```
- `commandOutputs` ← src/workflow/protocol.ts:1144 [EXTRACTED]
  ```
  export function commandOutputs(stdout: string): JsonValue | undefined {
  ```
- `conditionDiagnostics` ← src/workflow/reads.ts:19 [EXTRACTED]
  ```
  export function conditionDiagnostics({ file, lineCounter }: ParseContext, conditions: ConditionNode[], reads: ReadSite[]): WorkflowDiagnostic[] {
  ```
- `expressionSite` ← src/workflow/reads.ts:40 [EXTRACTED]
  ```
  export function expressionSite(
  ```
- `readScope` ← src/workflow/reads.ts:107 [EXTRACTED]
  ```
  export function readScope(
  ```
- `readDiagnostics` ← src/workflow/reads.ts:133 [EXTRACTED]
  ```
  export function readDiagnostics(file: string, sites: ReadSite[], scope: ReadScope): WorkflowDiagnostic[] {
  ```
- `splitReads` ← src/workflow/reads.ts:256 [EXTRACTED]
  ```
  export function splitReads(sites: ReadSite[], ids: Set<string> | undefined): SplitReads {
  ```
- `endDiagnostics` ← src/workflow/reads.ts:300 [EXTRACTED]
  ```
  export function endDiagnostics(
  ```
- `RECORDS_DIR` ← src/workflow/records.ts:139 [EXTRACTED]
  ```
  export const RECORDS_DIR = 'workflows/runs';
  ```
- `recordPath` ← src/workflow/records.ts:142 [EXTRACTED]
  ```
  export function recordPath(runId: string): string {
  ```
- `BENCHMARK_RECORDS_DIR` ← src/workflow/records.ts:147 [EXTRACTED]
  ```
  export const BENCHMARK_RECORDS_DIR = 'benchmarks/runs';
  ```
- `benchmarkRecordPath` ← src/workflow/records.ts:150 [EXTRACTED]
  ```
  export function benchmarkRecordPath(runId: string): string {
  ```
- `buildStartRecord` ← src/workflow/records.ts:163 [EXTRACTED]
  ```
  export function buildStartRecord(
  ```
- `buildEndRecord` ← src/workflow/records.ts:218 [EXTRACTED]
  ```
  export function buildEndRecord(
  ```
- `RunRecordFieldsSchema` ← src/workflow/records.ts:299 [EXTRACTED]
  ```
  export const RunRecordFieldsSchema = z.object({
  ```
- `pullRequestBranches` ← src/workflow/records.ts:307 [EXTRACTED]
  ```
  export function pullRequestBranches(run: Pick<RunState, 'id' | 'deliveries'>): string[] {
  ```
- `mergeRecord` ← src/workflow/records.ts:321 [EXTRACTED]
  ```
  export function mergeRecord(origin: WorkflowRunRecord | null, next: WorkflowRunRecord): WorkflowRunRecord {
  ```
- `queueRunRecord` ← src/workflow/records.ts:355 [EXTRACTED]
  ```
  export async function queueRunRecord(
  ```
- `publishRunRecords` ← src/workflow/records.ts:386 [EXTRACTED]
  ```
  export async function publishRunRecords(config: LocalConfig): Promise<RecordState> {
  ```
- `runRecordState` ← src/workflow/records.ts:395 [EXTRACTED]
  ```
  export async function runRecordState(config: LocalConfig, run: RunState): Promise<RecordState | undefined> {
  ```
- `runRecordStates` ← src/workflow/records.ts:400 [EXTRACTED]
  ```
  export async function runRecordStates(config: LocalConfig, runs: RunState[]): Promise<Map<string, RecordState>> {
  ```
- `queueBenchmarkRecord` ← src/workflow/records.ts:438 [EXTRACTED]
  ```
  export async function queueBenchmarkRecord(config: LocalConfig, record: QueuedBenchmark, secrets: Record<string, string>): Promise<boolean> {
  ```
- `pendingBenchmarkRuns` ← src/workflow/records.ts:450 [EXTRACTED]
  ```
  export async function pendingBenchmarkRuns(config: LocalConfig): Promise<Set<string>> {
  ```
- `enqueueRecord` ← src/workflow/records.ts:479 [EXTRACTED]
  ```
  export async function enqueueRecord(config: LocalConfig, record: CurrentWorkflowRunRecord, secrets: Record<string, string>): Promise<void> {
  ```
- `removeQueuedEndRecord` ← src/workflow/records.ts:489 [EXTRACTED]
  ```
  export async function removeQueuedEndRecord(config: LocalConfig, runId: string): Promise<void> {
  ```
- `pendingRecords` ← src/workflow/records.ts:494 [EXTRACTED]
  ```
  export async function pendingRecords(config: LocalConfig): Promise<WorkflowRunRecord[]> {
  ```
- `publishPendingRecords` ← src/workflow/records.ts:560 [EXTRACTED]
  ```
  export async function publishPendingRecords(config: LocalConfig, options: { run?: string } = {}): Promise<RecordDelivery> {
  ```
- `ensureDigestFields` ← src/workflow/records.ts:739 [EXTRACTED]
  ```
  export function ensureDigestFields(existing: MemberStats, username: string): MemberStats {
  ```
- `mergeWorkflowStats` ← src/workflow/records.ts:769 [EXTRACTED]
  ```
  export function mergeWorkflowStats(
  ```
- `statsDeltaRecords` ← src/workflow/records.ts:821 [EXTRACTED]
  ```
  export function statsDeltaRecords(
  ```
- `LabelSchema` ← src/workflow/requirements.ts:14 [EXTRACTED]
  ```
  export const LabelSchema = z.string().regex(/^[a-z0-9][a-z0-9._-]*$/, 'must be lowercase letters, digits, dot, dash or underscore');
  ```
- `RequirementsSchema` ← src/workflow/requirements.ts:24 [EXTRACTED]
  ```
  export const RequirementsSchema = z.object({
  ```
- `ON_LIMIT` ← src/workflow/requirements.ts:39 [EXTRACTED]
  ```
  export const ON_LIMIT = ['end_turn', 'fail'] as const;
  ```
- `LimitSchema` ← src/workflow/requirements.ts:44 [EXTRACTED]
  ```
  export const LimitSchema = z.enum(['timeout', 'budget', 'max_turns']);
  ```
- `TurnLimitsSchema` ← src/workflow/requirements.ts:53 [EXTRACTED]
  ```
  export const TurnLimitsSchema = z.object({
  ```
- `setsLimit` ← src/workflow/requirements.ts:63 [EXTRACTED]
  ```
  export function setsLimit(limits: TurnLimits, limit: Limit): boolean {
  ```
- `SetupSchema` ← src/workflow/requirements.ts:109 [EXTRACTED]
  ```
  export const SetupSchema = z.object({ command: z.string().trim().min(1), requires: SetupRequirementsSchema.optional() }).strict();
  ```
- `DriverEnvSchema` ← src/workflow/requirements.ts:197 [EXTRACTED]
  ```
  export const DriverEnvSchema = z.literal(DRIVER_ENV_REACH, { error: "Expected true, false, 'commands' or 'member'" });
  ```
- `AllowSchema` ← src/workflow/requirements.ts:211 [EXTRACTED]
  ```
  export const AllowSchema = z.object({
  ```
- `LIMIT_FAILURES` ← src/workflow/requirements.ts:222 [EXTRACTED]
  ```
  export const LIMIT_FAILURES = [
  ```
- `UnenforcedSchema` ← src/workflow/requirements.ts:239 [EXTRACTED]
  ```
  export const UnenforcedSchema = z.discriminatedUnion('requirement', [
  ```
- `ReportedUnenforcedSchema` ← src/workflow/requirements.ts:260 [EXTRACTED]
  ```
  export const ReportedUnenforcedSchema = z.array(z.enum(['max_turns', 'budget'])) satisfies z.ZodType<BestEffortKey[]>;
  ```
- `reportedUnenforced` ← src/workflow/requirements.ts:268 [EXTRACTED]
  ```
  export function reportedUnenforced(keys: ReportedUnenforced, asked: { maxTurns?: number; tokens?: number }): Unenforced[] | string {
  ```
- `EnvScopeSchema` ← src/workflow/requirements.ts:293 [EXTRACTED]
  ```
  export const EnvScopeSchema = z.object({ provide: z.array(z.string()), withhold: z.array(z.string()) });
  ```
- `LeaseSetupSchema` ← src/workflow/requirements.ts:298 [EXTRACTED]
  ```
  export const LeaseSetupSchema = z.object({ command: z.string(), envScope: EnvScopeSchema.optional() });
  ```
- `mergeRequirements` ← src/workflow/requirements.ts:307 [EXTRACTED]
  ```
  export function mergeRequirements(...levels: ReadonlyArray<RequirementsLevel | undefined>): InEffect {
  ```
- `lackedLabels` ← src/workflow/requirements.ts:338 [EXTRACTED]
  ```
  export function lackedLabels(requires: Pick<InEffect, 'labels'>, declared: readonly string[] | undefined): string[] {
  ```
- `inProcessRuntimeOf` ← src/workflow/requirements.ts:439 [EXTRACTED]
  ```
  export function inProcessRuntimeOf({ isPrompt, isAnswer }: { isPrompt: boolean; isAnswer: boolean }): 'tools' | 'host' {
  ```
- `isPinnedToHost` ← src/workflow/requirements.ts:453 [EXTRACTED]
  ```
  export function isPinnedToHost({ step, executor, inShippedWorkflow, requires }: {
  ```
- `envScopeOf` ← src/workflow/requirements.ts:494 [EXTRACTED]
  ```
  export function envScopeOf(keys: readonly string[], { floor = {}, guarded }: { floor?: Floor; guarded: readonly string[] }): EnvScope {
  ```
- `negotiate` ← src/workflow/requirements.ts:509 [EXTRACTED]
  ```
  export function negotiate(offer: Offer, can: DriverCan, allow: Allow, env: EnvFacts): Negotiation {
  ```
- `envAdvice` ← src/workflow/requirements.ts:598 [EXTRACTED]
  ```
  export function envAdvice(keys: readonly string[], declared: ReadonlySet<string>): string {
  ```
- `lacksTool` ← src/workflow/requirements.ts:623 [EXTRACTED]
  ```
  export function lacksTool(tool: string, can: Pick<DriverCan, 'tools'>): boolean {
  ```
- `unionUnenforced` ← src/workflow/requirements.ts:655 [EXTRACTED]
  ```
  export function unionUnenforced(stored: readonly Unenforced[], added: readonly Unenforced[]): Unenforced[] {
  ```
- `requiredEnvKeys` ← src/workflow/requirements.ts:664 [EXTRACTED]
  ```
  export function requiredEnvKeys(definitions: ReadonlyArray<{ defaults?: WorkflowDefaults; setup?: Setup; steps: WorkflowStep[] }>): Set<string> {
  ```
- `heldFor` ← src/workflow/requirements.ts:685 [EXTRACTED]
  ```
  export function heldFor(step: string, missing: readonly Missing[]): Held {
  ```
- `RESERVED_DRIVERS` ← src/workflow/reserved-drivers.ts:7 [EXTRACTED]
  ```
  export const RESERVED_DRIVERS = { local: 'local', skill: 'skill', none: 'none', fleet: 'fleet', host: 'host' } as const;
  ```
- `isReservedDriver` ← src/workflow/reserved-drivers.ts:17 [EXTRACTED]
  ```
  export function isReservedDriver(name: string): name is ReservedDriverName {
  ```
- `parseRetention` ← src/workflow/retention.ts:19 [EXTRACTED]
  ```
  export function parseRetention(value: unknown): Retention | undefined {
  ```
- `retentionEnds` ← src/workflow/retention.ts:34 [EXTRACTED]
  ```
  export function retentionEnds(settledAt: string, retention: Retention): number | undefined {
  ```
- `runRetainedUntil` ← src/workflow/retention.ts:42 [EXTRACTED]
  ```
  export function runRetainedUntil(run: Pick<RunState, 'retainedUntil' | 'updatedAt'>, retention: Retention): number | undefined {
  ```
- `ownRunSweptAt` ← src/workflow/retention.ts:50 [EXTRACTED]
  ```
  export function ownRunSweptAt(run: Pick<RunState, 'retainedUntil' | 'updatedAt'>, retention: Retention): number | undefined {
  ```
- `resolveRetention` ← src/workflow/retention.ts:58 [EXTRACTED]
  ```
  export async function resolveRetention(config: LocalConfig, team: Pick<TeamaiConfig, 'workflows'> | null): Promise<ResolvedRetention> {
  ```
- `callerProvenance` ← src/workflow/run-controls.ts:105 [EXTRACTED]
  ```
  export function callerProvenance(env: NodeJS.ProcessEnv, stdin: { isTTY?: boolean }): CallerProvenance {
  ```
- `respondProvenance` ← src/workflow/run-controls.ts:178 [EXTRACTED]
  ```
  export const respondProvenance = Provenance.decide;
  ```
- `respondToHitl` ← src/workflow/run-controls.ts:217 [EXTRACTED]
  ```
  export async function respondToHitl(config: LocalConfig, runId: string, secrets: Record<string, string>, input: ResponseInput): Promise<WorkflowEnvelope> {
  ```
- `cancelRun` ← src/workflow/run-controls.ts:289 [EXTRACTED]
  ```
  export async function cancelRun(
  ```
- `endRunsPartOf` ← src/workflow/run-controls.ts:356 [EXTRACTED]
  ```
  export async function endRunsPartOf(config: LocalConfig, partOf: PartOfStep): Promise<string[]> {
  ```
- `restartCommand` ← src/workflow/run-controls.ts:694 [EXTRACTED]
  ```
  export function restartCommand(run: RunState): string {
  ```
- `retriedRunsAgain` ← src/workflow/run-controls.ts:846 [EXTRACTED]
  ```
  export function retriedRunsAgain(answer: WorkflowEnvelope): string[] {
  ```
- `retryStep` ← src/workflow/run-controls.ts:851 [EXTRACTED]
  ```
  export async function retryStep(config: LocalConfig, runId: string, secrets: Record<string, string>, step: string): Promise<WorkflowEnvelope> {
  ```
- `projectPartitions` ← src/workflow/run-location.ts:19 [EXTRACTED]
  ```
  export async function projectPartitions(): Promise<LocalConfig[]> {
  ```
- `partitionConfig` ← src/workflow/run-location.ts:45 [EXTRACTED]
  ```
  export async function partitionConfig(partition: LocalConfig, anchor?: string): Promise<LocalConfig | null> {
  ```
- `existingCheckout` ← src/workflow/run-location.ts:56 [EXTRACTED]
  ```
  export async function existingCheckout(run: RunState | 'corrupt'): Promise<string | undefined> {
  ```
- `findRunConfig` ← src/workflow/run-location.ts:63 [EXTRACTED]
  ```
  export async function findRunConfig(runId: string, current?: LocalConfig): Promise<{ config: LocalConfig; run: RunState } | { error: WorkflowFailure }> {
  ```
- `findAttemptRun` ← src/workflow/run-location.ts:112 [EXTRACTED]
  ```
  export async function findAttemptRun(env: NodeJS.ProcessEnv): Promise<{ config: LocalConfig; run: RunState; step: LeasedStep } | { error: WorkflowFailure }> {
  ```
- `topScope` ← src/workflow/scope.ts:69 [EXTRACTED]
  ```
  export function topScope(run: RunState): Scope {
  ```
- `finallyScope` ← src/workflow/scope.ts:85 [EXTRACTED]
  ```
  export function finallyScope(run: RunState): Scope {
  ```
- `childScope` ← src/workflow/scope.ts:117 [EXTRACTED]
  ```
  export function childScope(run: RunState, scope: Scope, states: StepState[], state: StepState, step: WorkflowStep): Scope | undefined {
  ```
- `stepDefinitions` ← src/workflow/scope.ts:145 [EXTRACTED]
  ```
  export function stepDefinitions(run: Pick<RunState, 'definition' | 'workflows' | 'admitted'>): (path: string) => WorkflowStep | undefined {
  ```
- `privateSteps` ← src/workflow/scope.ts:172 [EXTRACTED]
  ```
  export function privateSteps(run: Pick<RunState, 'definition' | 'workflows' | 'admitted'>): (path: string) => boolean {
  ```
- `workflowBatch` ← src/workflow/scope.ts:192 [EXTRACTED]
  ```
  export function workflowBatch(run: RunState, step: string): boolean | undefined {
  ```
- `openPrivateStep` ← src/workflow/scope.ts:211 [EXTRACTED]
  ```
  export function openPrivateStep(run: RunState): string | undefined {
  ```
- `statesIn` ← src/workflow/scope.ts:238 [EXTRACTED]
  ```
  export function statesIn(run: RunState, scope: Scope): StepState[] {
  ```
- `insertChildren` ← src/workflow/scope.ts:259 [EXTRACTED]
  ```
  export function insertChildren(run: RunState, runner: StepState, children: StepState[]): void {
  ```
- `localId` ← src/workflow/scope.ts:273 [EXTRACTED]
  ```
  export function localId(scope: Scope, state: StepState): string {
  ```
- `contextOf` ← src/workflow/scope.ts:286 [EXTRACTED]
  ```
  export function contextOf(scope: Scope, states: StepState[], reader?: StepState): TemplateContext {
  ```
- `locateStep` ← src/workflow/scope.ts:331 [EXTRACTED]
  ```
  export function locateStep(run: RunState, path: string): { scope: Scope; step: WorkflowStep } | undefined {
  ```
- `leaseContext` ← src/workflow/scope.ts:355 [EXTRACTED]
  ```
  export function leaseContext(run: RunState, path: string): { step: WorkflowStep; context: TemplateContext; requires: InEffect } | undefined {
  ```
- `SESSION_APPS` ← src/workflow/session-apps.ts:6 [EXTRACTED]
  ```
  export const SESSION_APPS = [
  ```
- `sessionAppOf` ← src/workflow/session-apps.ts:15 [EXTRACTED]
  ```
  export function sessionAppOf(env: NodeJS.ProcessEnv): SessionApp | undefined {
  ```
- `STOPPED_EXIT_CODE` ← src/workflow/shell-command.ts:19 [EXTRACTED]
  ```
  export const STOPPED_EXIT_CODE = 130;
  ```
- `shellArgv` ← src/workflow/shell-command.ts:22 [EXTRACTED]
  ```
  export function shellArgv(command: string): string[] {
  ```
- `runShellCommand` ← src/workflow/shell-command.ts:33 [EXTRACTED]
  ```
  export async function runShellCommand({ command, cwd, env, signal, expiresAt, stderr = 'keep' }: {
  ```
- `startGroupedCommand` ← src/workflow/shell-command.ts:115 [EXTRACTED]
  ```
  export function startGroupedCommand(input: { command: string; cwd: string; env: NodeJS.ProcessEnv; detached: boolean; group: string; onStderr?: (chunk: string) => void }): GroupedCommand {
  ```
- `RunDefinitionSchema` ← src/workflow/snapshot.ts:94 [EXTRACTED]
  ```
  export const RunDefinitionSchema = BodySchema.pick({ name: true, sourceHash: true, definitionHash: true, teamRevision: true, origin: true });
  ```
- `runDefinition` ← src/workflow/snapshot.ts:99 [EXTRACTED]
  ```
  export function runDefinition(run: Pick<RunState, 'name' | 'sourceHash' | 'teamRevision' | 'origin' | 'definition' | 'workflows'>): RunDefinition {
  ```
- `SNAPSHOTS_DIR` ← src/workflow/snapshot.ts:151 [EXTRACTED]
  ```
  export const SNAPSHOTS_DIR = 'workflows/runs';
  ```
- `snapshotPath` ← src/workflow/snapshot.ts:153 [EXTRACTED]
  ```
  export function snapshotPath(runId: string): string {
  ```
- `snapshotText` ← src/workflow/snapshot.ts:158 [EXTRACTED]
  ```
  export function snapshotText(snapshot: RunSnapshot): string {
  ```
- `definitionHash` ← src/workflow/snapshot.ts:163 [EXTRACTED]
  ```
  export function definitionHash(definition: WorkflowDefinition, workflows: Record<string, WorkflowDefinition> = {}): string {
  ```
- `snapshotBody` ← src/workflow/snapshot.ts:168 [EXTRACTED]
  ```
  export function snapshotBody(snapshot: RunSnapshot): SnapshotBody {
  ```
- `parseSnapshot` ← src/workflow/snapshot.ts:178 [EXTRACTED]
  ```
  export function parseSnapshot(text: string, runId: string): Parsed<RunSnapshot> {
  ```
- `projectRun` ← src/workflow/snapshot.ts:404 [EXTRACTED]
  ```
  export function projectRun(run: RunState, secrets: Record<string, string>): Parsed<SnapshotBody> {
  ```
- `firstUnfit` ← src/workflow/snapshot.ts:457 [EXTRACTED]
  ```
  export function firstUnfit(value: JsonValue | undefined, envSecrets: Record<string, string>, at: Array<string | number> = []): { at: Array<string | number>; unfit: Unfit } | undefined {
  ```
- `StepModelSchema` ← src/workflow/step-model.ts:26 [EXTRACTED]
  ```
  export const StepModelSchema = z.object({ name: z.string().min(1), effort: z.string().min(1).optional() }).strict();
  ```
- `stepModelUnavailableText` ← src/workflow/step-model.ts:74 [EXTRACTED]
  ```
  export function stepModelUnavailableText(step: string, origin: ModelOrigin, value: string, cause: string, reason: NoModel): string {
  ```
- `chooseStepModel` ← src/workflow/step-model.ts:94 [EXTRACTED]
  ```
  export async function chooseStepModel(request: StepModelRequest): Promise<StepModelChoice> {
  ```
- `loadDeployedAgent` ← src/workflow/step-model.ts:143 [EXTRACTED]
  ```
  export async function loadDeployedAgent(input: {
  ```
- `INDEX` ← src/workflow/step-path.ts:8 [EXTRACTED]
  ```
  export const INDEX = '0|[1-9][0-9]*';
  ```
- `parseStepPath` ← src/workflow/step-path.ts:15 [EXTRACTED]
  ```
  export function parseStepPath(path: string): StepPathSegment[] {
  ```
- `LimitsFromSchema` ← src/workflow/step-state.ts:24 [EXTRACTED]
  ```
  export const LimitsFromSchema = z.object({ at: z.string(), tokens: z.number() });
  ```
- `ReleasedTokensSchema` ← src/workflow/step-state.ts:29 [EXTRACTED]
  ```
  export const ReleasedTokensSchema = z.object({ step: z.string(), attempt: z.string(), tokens: TokenUsageSchema });
  ```
- `StoppedAttemptSchema` ← src/workflow/step-state.ts:37 [EXTRACTED]
  ```
  export const StoppedAttemptSchema = z.object({ attempt: z.string(), step: z.string(), driver: DriverSchema, stoppedAt: z.string() });
  ```
- `SessionContinuationSchema` ← src/workflow/step-state.ts:46 [EXTRACTED]
  ```
  export const SessionContinuationSchema = z.object({ from: SessionRefSchema, to: SessionRefSchema });
  ```
- `ChangesSchema` ← src/workflow/step-state.ts:62 [EXTRACTED]
  ```
  export const ChangesSchema = z.object({
  ```
- `ReadSchema` ← src/workflow/step-state.ts:71 [EXTRACTED]
  ```
  export const ReadSchema = z.object({
  ```
- `ConfinedRunReportSchema` ← src/workflow/step-state.ts:83 [EXTRACTED]
  ```
  export const ConfinedRunReportSchema = z.object({
  ```
- `OutcomeSchema` ← src/workflow/step-state.ts:135 [EXTRACTED]
  ```
  export const OutcomeSchema = z.enum(['success', 'failed', 'timeout', 'skipped', 'cancelled']);
  ```
- `StepPassSchema` ← src/workflow/step-state.ts:175 [EXTRACTED]
  ```
  export const StepPassSchema = z.object({
  ```
- `ArchivedPassSchema` ← src/workflow/step-state.ts:194 [EXTRACTED]
  ```
  export const ArchivedPassSchema = StepPassSchema.extend({
  ```
- `StepStateSchema` ← src/workflow/step-state.ts:288 [EXTRACTED]
  ```
  export const StepStateSchema = z.discriminatedUnion('status', [LeasedSchema, ...SHARED_VARIANTS]);
  ```
- `StepCheckpointSchema` ← src/workflow/step-state.ts:295 [EXTRACTED]
  ```
  export const StepCheckpointSchema = z.discriminatedUnion('status', [HandedLeaseSchema, ...SHARED_VARIANTS]);
  ```
- `visibleOutcome` ← src/workflow/step-state.ts:329 [EXTRACTED]
  ```
  export function visibleOutcome(step: Extract<StepState, { status: keyof typeof VISIBLE_OUTCOMES }>): VisibleOutcome {
  ```
- `waitForAnswer` ← src/workflow/step-state.ts:349 [EXTRACTED]
  ```
  export function waitForAnswer(state: StepState): StepIn<'waiting'> {
  ```
- `answerHitl` ← src/workflow/step-state.ts:354 [EXTRACTED]
  ```
  export function answerHitl(state: StepIn<'waiting'>, answer: HitlAnswer): PendingStep {
  ```
- `resetPending` ← src/workflow/step-state.ts:359 [EXTRACTED]
  ```
  export function resetPending(state: StepState): PendingStep {
  ```
- `resetIteration` ← src/workflow/step-state.ts:364 [EXTRACTED]
  ```
  export function resetIteration(state: StepState): void {
  ```
- `skip` ← src/workflow/step-state.ts:368 [EXTRACTED]
  ```
  export function skip(state: StepState, settledAt: number, message: string): SkippedStep {
  ```
- `release` ← src/workflow/step-state.ts:373 [EXTRACTED]
  ```
  export function release(state: LeasedStep | HandedLease): PendingStep {
  ```
- `takeOver` ← src/workflow/step-state.ts:384 [EXTRACTED]
  ```
  export function takeOver(step: StepCheckpoint, mode: WorkspaceMode | undefined): UnleasedStep {
  ```
- `attemptOfStep` ← src/workflow/step-state.ts:409 [EXTRACTED]
  ```
  export function attemptOfStep(state: StepState): string | undefined {
  ```
- `lease` ← src/workflow/step-state.ts:431 [EXTRACTED]
  ```
  export function lease(state: StepState, held: StepLease): LeasedStep {
  ```
- `start` ← src/workflow/step-state.ts:439 [EXTRACTED]
  ```
  export function start(state: StepState, inputs?: RunningStep['inputs'], limits: Pick<RunningStep, 'expiresAt' | 'limitsFrom'> = {}): RunningStep {
  ```
- `succeed` ← src/workflow/step-state.ts:447 [EXTRACTED]
  ```
  export function succeed(state: StepState, settlement: Settlement<SucceededStep>): SucceededStep {
  ```
- `startDelivery` ← src/workflow/step-state.ts:452 [EXTRACTED]
  ```
  export function startDelivery(state: StepState, settlement: Settlement<SucceededStep>, delivery: Delivery): DeliveringStep {
  ```
- `delivered` ← src/workflow/step-state.ts:457 [EXTRACTED]
  ```
  export function delivered(state: DeliveringStep, pr: PrUrl): SucceededStep {
  ```
- `deliveryFailed` ← src/workflow/step-state.ts:469 [EXTRACTED]
  ```
  export function deliveryFailed(state: DeliveringStep, failure: DeliveryFailure): FailedStep {
  ```
- `redeliver` ← src/workflow/step-state.ts:476 [EXTRACTED]
  ```
  export function redeliver(state: FailedStep, delivery: Delivery): DeliveringStep {
  ```
- `fail` ← src/workflow/step-state.ts:482 [EXTRACTED]
  ```
  export function fail(state: StepState, settlement: Settlement<FailedStep>): FailedStep {
  ```
- `stopAttempt` ← src/workflow/step-state.ts:504 [EXTRACTED]
  ```
  export function stopAttempt(run: RunState, state: LeasedStep, now: string): void {
  ```
- `timeOut` ← src/workflow/step-state.ts:510 [EXTRACTED]
  ```
  export function timeOut(state: LeasedStep | RunningStep, failure: WorkflowFailure & { code: 'timeout' }, settledAt: number, results?: ItemResult[]): FailedStep {
  ```
- `cancel` ← src/workflow/step-state.ts:519 [EXTRACTED]
  ```
  export function cancel(state: StepIn<'pending' | 'waiting' | 'leased' | 'running' | 'delivering'>, failure: WorkflowFailure, settledAt: number, results?: ItemResult[]): CancelledStep {
  ```
- `wasLeased` ← src/workflow/step-state.ts:530 [EXTRACTED]
  ```
  export function wasLeased(state: StepState): boolean {
  ```
- `passOf` ← src/workflow/step-state.ts:535 [EXTRACTED]
  ```
  export function passOf(state: StepState): StepPass | undefined {
  ```
- `agentPassOf` ← src/workflow/step-state.ts:546 [EXTRACTED]
  ```
  export function agentPassOf(state: StepState): StepPass | undefined {
  ```
- `agentSucceeded` ← src/workflow/step-state.ts:551 [EXTRACTED]
  ```
  export function agentSucceeded(pass: StepPass): boolean {
  ```
- `repend` ← src/workflow/step-state.ts:563 [EXTRACTED]
  ```
  export function repend(state: StepState, iteration?: number): PendingStep {
  ```
- `nextRound` ← src/workflow/step-state.ts:576 [EXTRACTED]
  ```
  export function nextRound(state: RunningStep): RunningStep {
  ```
- `endLoop` ← src/workflow/step-state.ts:581 [EXTRACTED]
  ```
  export function endLoop(owner: SucceededStep, iteration: number): SucceededStep {
  ```
- `exhaust` ← src/workflow/step-state.ts:589 [EXTRACTED]
  ```
  export function exhaust(state: SucceededStep | PendingStep, failure: WorkflowFailure, settledAt: number, iteration?: number): FailedStep {
  ```
- `stopped` ← src/workflow/step-state.ts:602 [EXTRACTED]
  ```
  export function stopped(step: StepState): boolean {
  ```
- `inProgress` ← src/workflow/step-state.ts:624 [EXTRACTED]
  ```
  export function inProgress(step: StepState): boolean {
  ```
- `cancellable` ← src/workflow/step-state.ts:646 [EXTRACTED]
  ```
  export function cancellable(step: StepState): step is StepIn<'pending' | 'waiting' | 'leased' | 'running' | 'delivering'> {
  ```
- `settled` ← src/workflow/step-state.ts:668 [EXTRACTED]
  ```
  export function settled(step: StepState | undefined): step is Extract<StepState, { status: 'succeeded' | 'failed' | 'skipped' | 'cancelled' }> {
  ```
- `stopWhere` ← src/workflow/step-state.ts:698 [EXTRACTED]
  ```
  export function stopWhere(run: RunState, under: (id: string) => boolean, failure: WorkflowFailure, settledAt: number, now: string): string[] {
  ```
- `isRunId` ← src/workflow/store.ts:27 [EXTRACTED]
  ```
  export function isRunId(runId: string): boolean {
  ```
- `RunIdSchema` ← src/workflow/store.ts:31 [EXTRACTED]
  ```
  export const RunIdSchema = z.string().regex(RUN_ID, 'Run id must look like r followed by 8 or 16 hex digits').brand<'RunId'>();
  ```
- `AttemptIdSchema` ← src/workflow/store.ts:36 [EXTRACTED]
  ```
  export const AttemptIdSchema = z.string().regex(/^a[0-9a-f]{8}$/, 'Attempt id must look like a followed by 8 hex digits').brand<'AttemptId'>();
  ```
- `generateRunId` ← src/workflow/store.ts:41 [EXTRACTED]
  ```
  export function generateRunId(): string {
  ```
- `runsDir` ← src/workflow/store.ts:49 [EXTRACTED]
  ```
  export function runsDir(config: LocalConfig): string {
  ```
- `runsDirIn` ← src/workflow/store.ts:54 [EXTRACTED]
  ```
  export function runsDirIn(dataHome: string): string {
  ```
- `runFilePath` ← src/workflow/store.ts:58 [EXTRACTED]
  ```
  export function runFilePath(config: LocalConfig, runId: string): string {
  ```
- `runLockPath` ← src/workflow/store.ts:62 [EXTRACTED]
  ```
  export function runLockPath(config: LocalConfig, runId: string): string {
  ```
- `withCleanupLock` ← src/workflow/store.ts:74 [EXTRACTED]
  ```
  export async function withCleanupLock<T>(config: LocalConfig, runId: string, action: () => Promise<T>): Promise<CleanupLocked<T>> {
  ```
- `deliveryLockPath` ← src/workflow/store.ts:87 [EXTRACTED]
  ```
  export function deliveryLockPath(config: LocalConfig, runId: string): string {
  ```
- `runsRemovalLockIn` ← src/workflow/store.ts:96 [EXTRACTED]
  ```
  export function runsRemovalLockIn(dataHome: string): string {
  ```
- `RUNS_REMOVAL_LOCK_WAIT` ← src/workflow/store.ts:100 [EXTRACTED]
  ```
  export const RUNS_REMOVAL_LOCK_WAIT = { attempts: 50, delayMs: 200 } as const;
  ```
- `driverLockPath` ← src/workflow/store.ts:102 [EXTRACTED]
  ```
  export function driverLockPath(config: LocalConfig, runId: string): string {
  ```
- `runScratchDir` ← src/workflow/store.ts:107 [EXTRACTED]
  ```
  export function runScratchDir(config: LocalConfig, run: string): string {
  ```
- `attemptsDir` ← src/workflow/store.ts:112 [EXTRACTED]
  ```
  export function attemptsDir(config: LocalConfig, run: RunId): string {
  ```
- `attemptsDirIn` ← src/workflow/store.ts:117 [EXTRACTED]
  ```
  export function attemptsDirIn(runs: string, run: RunId): string {
  ```
- `attemptDir` ← src/workflow/store.ts:122 [EXTRACTED]
  ```
  export function attemptDir(config: LocalConfig, run: RunId, attempt: AttemptId): string {
  ```
- `skillStatePath` ← src/workflow/store.ts:127 [EXTRACTED]
  ```
  export function skillStatePath(config: LocalConfig, run: RunId): string {
  ```
- `placeRecordPath` ← src/workflow/store.ts:132 [EXTRACTED]
  ```
  export function placeRecordPath(config: LocalConfig, run: RunId, attempt: AttemptId): string {
  ```
- `attemptOutDir` ← src/workflow/store.ts:140 [EXTRACTED]
  ```
  export function attemptOutDir(config: LocalConfig, run: RunId, attempt: AttemptId): string {
  ```
- `attemptStdoutPath` ← src/workflow/store.ts:148 [EXTRACTED]
  ```
  export function attemptStdoutPath(config: LocalConfig, run: RunId, attempt: AttemptId): string {
  ```
- `keepAttemptStdout` ← src/workflow/store.ts:161 [EXTRACTED]
  ```
  export async function keepAttemptStdout(config: LocalConfig, { run, attempt, stdout, secrets }: { run: RunId; attempt: AttemptId; stdout: string; secrets: Record<string, string> }): Promise<string | undefined> {
  ```
- `ATTEMPT_RESULT_FILE` ← src/workflow/store.ts:179 [EXTRACTED]
  ```
  export const ATTEMPT_RESULT_FILE = 'result.json';
  ```
- `attemptResultPath` ← src/workflow/store.ts:186 [EXTRACTED]
  ```
  export function attemptResultPath(config: LocalConfig, run: RunId, attempt: AttemptId): string {
  ```
- `attemptOutcomesPath` ← src/workflow/store.ts:194 [EXTRACTED]
  ```
  export function attemptOutcomesPath(config: LocalConfig, run: RunId, attempt: AttemptId): string {
  ```
- `appendAttemptOutcome` ← src/workflow/store.ts:203 [EXTRACTED]
  ```
  export async function appendAttemptOutcome(config: LocalConfig, { run, attempt }: { run: RunId; attempt: AttemptId }, outcome: WorkOutcome): Promise<'appended' | 'unknown_run'> {
  ```
- `readAttemptOutcomes` ← src/workflow/store.ts:213 [EXTRACTED]
  ```
  export async function readAttemptOutcomes(config: LocalConfig, run: string, attempt: string): Promise<WorkOutcome[]> {
  ```
- `RunRemovedError` ← src/workflow/store.ts:250 [EXTRACTED]
  ```
  export class RunRemovedError extends Error {
  ```
- `RunsRemovalLockTakenError` ← src/workflow/store.ts:264 [EXTRACTED]
  ```
  export class RunsRemovalLockTakenError extends Error {
  ```
- `runRemovalRefusal` ← src/workflow/store.ts:272 [EXTRACTED]
  ```
  export function runRemovalRefusal(cause: unknown) {
  ```
- `isRunHere` ← src/workflow/store.ts:283 [EXTRACTED]
  ```
  export async function isRunHere(config: LocalConfig, run: RunId): Promise<boolean> {
  ```
- `runsDrivenIn` ← src/workflow/store.ts:301 [EXTRACTED]
  ```
  export async function runsDrivenIn(runs: string): Promise<Array<{ run: RunId; pid: number | undefined }>> {
  ```
- `takeRunLock` ← src/workflow/store.ts:348 [EXTRACTED]
  ```
  export async function takeRunLock<T>(config: LocalConfig, run: RunId, body: (lock: RunLock) => Promise<T>, { waitMs }: { waitMs: number }): Promise<LockTaken<T>> {
  ```
- `withRunLock` ← src/workflow/store.ts:398 [EXTRACTED]
  ```
  export async function withRunLock<T>(
  ```
- `withRunnerLock` ← src/workflow/store.ts:423 [EXTRACTED]
  ```
  export async function withRunnerLock<T>(config: LocalConfig, run: RunId, attempt: AttemptId, body: () => Promise<T>): Promise<T | 'held'> {
  ```
- `runnerAlive` ← src/workflow/store.ts:436 [EXTRACTED]
  ```
  export async function runnerAlive(config: LocalConfig, run: RunId, attempt: AttemptId): Promise<boolean> {
  ```
- `TeamPinSchema` ← src/workflow/store.ts:444 [EXTRACTED]
  ```
  export const TeamPinSchema = z.object({ revision: z.string().regex(/^[0-9a-f]{40,64}$/), patch: z.string().regex(/^[0-9a-f]{64}$/).optional() }).strict();
  ```
- `isRunState` ← src/workflow/store.ts:463 [EXTRACTED]
  ```
  export function isRunState(value: unknown): value is RunState {
  ```
- `PartOfStepSchema` ← src/workflow/store.ts:472 [EXTRACTED]
  ```
  export const PartOfStepSchema = z.object({ run: RunIdSchema, attempt: AttemptIdSchema }).strict();
  ```
- `readRun` ← src/workflow/store.ts:504 [EXTRACTED]
  ```
  export async function readRun(config: LocalConfig, runId: string): Promise<RunState | 'missing' | 'corrupt'> {
  ```
- `readRuns` ← src/workflow/store.ts:522 [EXTRACTED]
  ```
  export async function readRuns(config: LocalConfig): Promise<RunState[]> {
  ```
- `updateRun` ← src/workflow/store.ts:558 [EXTRACTED]
  ```
  export async function updateRun<T>(
  ```
- `installOwner` ← src/workflow/store.ts:590 [EXTRACTED]
  ```
  export async function installOwner(config: LocalConfig): Promise<HandoffOwner> {
  ```
- `TeamPin` ← src/workflow/team-pin.ts:80 [EXTRACTED]
  ```
  export const TeamPin = {
  ```
- `isTemplateRead` ← src/workflow/template.ts:41 [EXTRACTED]
  ```
  export function isTemplateRead(part: string | TemplateRead): part is TemplateRead {
  ```
- `findTemplate` ← src/workflow/template.ts:102 [EXTRACTED]
  ```
  export function findTemplate(text: string, item: boolean): string | undefined {
  ```
- `parseTemplate` ← src/workflow/template.ts:143 [EXTRACTED]
  ```
  export function parseTemplate(text: string, item: boolean, variables: readonly string[] = []): TemplateParse {
  ```
- `templateExpressions` ← src/workflow/template.ts:190 [EXTRACTED]
  ```
  export function templateExpressions(template: Template): Expression[] {
  ```
- `templatePaths` ← src/workflow/template.ts:195 [EXTRACTED]
  ```
  export function templatePaths(template: Template): ExpressionPath[] {
  ```
- `stepRoleSpec` ← src/workflow/template.ts:207 [EXTRACTED]
  ```
  export function stepRoleSpec(role: string): StepRoleSpec {
  ```
- `templateWithPaths` ← src/workflow/template.ts:217 [EXTRACTED]
  ```
  export function templateWithPaths(template: Template): WithPath[] {
  ```
- `renderText` ← src/workflow/template.ts:241 [EXTRACTED]
  ```
  export function renderText(template: Template, context: TemplateContext): string {
  ```
- `renderLeaseText` ← src/workflow/template.ts:249 [EXTRACTED]
  ```
  export function renderLeaseText(context: TemplateContext, state: Pick<StepState, 'id'>, { what, text }: { what: string; text: string }): string | WorkflowFailure {
  ```
- `renderValue` ← src/workflow/template.ts:262 [EXTRACTED]
  ```
  export function renderValue(template: Template, context: TemplateContext): JsonValue {
  ```
- `stringsIn` ← src/workflow/template.ts:272 [EXTRACTED]
  ```
  export function stringsIn(value: unknown): string[] {
  ```
- `templatedTexts` ← src/workflow/template.ts:287 [EXTRACTED]
  ```
  export function templatedTexts(step: Pick<WorkflowStep, 'prompt' | 'answer' | 'env' | 'with' | 'hitl' | 'model' | 'workspace' | 'writes' | 'forEach'>): Array<{ what: string; text: string }> {
  ```
- `confinedTemplateErrors` ← src/workflow/template.ts:315 [EXTRACTED]
  ```
  export function confinedTemplateErrors(template: Template): TemplateError[] {
  ```
- `modelTemplateErrors` ← src/workflow/template.ts:323 [EXTRACTED]
  ```
  export function modelTemplateErrors(text: string, template: Template): TemplateError[] {
  ```
- `writesTemplateErrors` ← src/workflow/template.ts:336 [EXTRACTED]
  ```
  export function writesTemplateErrors(template: Template): TemplateError[] {
  ```
- `maxParallelTemplateErrors` ← src/workflow/template.ts:346 [EXTRACTED]
  ```
  export function maxParallelTemplateErrors(text: string, template: Template, inputs: Record<string, OutputSchema> | undefined): TemplateError[] {
  ```
- `stepExpressions` ← src/workflow/template.ts:371 [EXTRACTED]
  ```
  export function stepExpressions(step: Pick<WorkflowStep, 'if' | 'loop' | 'break' | 'forEach'>): StepExpression[] {
  ```
- `stepPaths` ← src/workflow/template.ts:385 [EXTRACTED]
  ```
  export function stepPaths(step: WorkflowStep, bindsItem: boolean): ExpressionPath[] {
  ```
- `renderStrings` ← src/workflow/template.ts:406 [EXTRACTED]
  ```
  export function renderStrings(value: unknown, context: TemplateContext): { ok: true; value: unknown } | { ok: false; error: TemplateError } {
  ```
- `onlyPersonAnswers` ← src/workflow/types.ts:61 [EXTRACTED]
  ```
  export function onlyPersonAnswers(hitl: Pick<StepHitl, 'kind' | 'required' | 'default'>, { autoApprove }: { autoApprove: boolean }): boolean {
  ```
- `unattendedChoice` ← src/workflow/types.ts:69 [EXTRACTED]
  ```
  export function unattendedChoice(hitl: Pick<StepHitl, 'kind' | 'required' | 'default'>, { autoApprove }: { autoApprove: boolean }): string | undefined {
  ```
- `STEP_ACTIONS` ← src/workflow/types.ts:241 [EXTRACTED]
  ```
  export const STEP_ACTIONS = { command: 'command', prompt: 'prompt', prompt_file: 'promptFile', answer: 'answer', answer_file: 'answerFile', workflow: 'workflow' } as const satisfies Record<string, keyof WorkflowStep>;
  ```
- `hasAction` ← src/workflow/types.ts:244 [EXTRACTED]
  ```
  export function hasAction(step: WorkflowStep): boolean {
  ```
- `stepWorkflow` ← src/workflow/types.ts:262 [EXTRACTED]
  ```
  export function stepWorkflow({ workflow }: Pick<WorkflowStep, 'workflow'>): StepWorkflow | undefined {
  ```
- `isWorkflowFile` ← src/workflow/types.ts:271 [EXTRACTED]
  ```
  export function isWorkflowFile(workflow: WorkflowDefinition | InlineWorkflow): workflow is WorkflowDefinition {
  ```
- `workflowRunBy` ← src/workflow/types.ts:280 [EXTRACTED]
  ```
  export function workflowRunBy(
  ```
- `SCORING_STARTS` ← src/workflow/types.ts:341 [EXTRACTED]
  ```
  export const SCORING_STARTS = ['auto', 'workflow'] as const;
  ```
- `STARTED_BY` ← src/workflow/types.ts:349 [EXTRACTED]
  ```
  export const STARTED_BY = ['person', 'agent', 'cli'] as const;
  ```
- `INVOKE_VALUES` ← src/workflow/types.ts:354 [EXTRACTED]
  ```
  export const INVOKE_VALUES = ['allow', 'ask', 'deny'] as const;
  ```
- `isWorkflowError` ← src/workflow/types.ts:721 [EXTRACTED]
  ```
  export function isWorkflowError(
  ```
- `KeptLimitSchema` ← src/workflow/usage-limits.ts:152 [EXTRACTED]
  ```
  export const KeptLimitSchema = z.object({
  ```
- `UsageLimits` ← src/workflow/usage-limits.ts:294 [EXTRACTED]
  ```
  export const UsageLimits = {
  ```
- `wholeFit` ← src/workflow/whole-workflow.ts:27 [EXTRACTED]
  ```
  export function wholeFit(
  ```
- `wholeRunDefinition` ← src/workflow/whole-workflow.ts:71 [EXTRACTED]
  ```
  export function wholeRunDefinition(
  ```
- `inlineReads` ← src/workflow/whole-workflow.ts:154 [EXTRACTED]
  ```
  export function inlineReads(inline: InlineWorkflow): Array<{ what: string; paths: ExpressionPath[] }> {
  ```
- `wholeInputs` ← src/workflow/whole-workflow.ts:167 [EXTRACTED]
  ```
  export function wholeInputs(step: Pick<WorkflowStep, 'with'>, child: Pick<WorkflowDefinition, 'defaults'>, context: TemplateContext): { inputs: JsonValue } | { error: string } {
  ```
- `WholeEndSchema` ← src/workflow/whole-workflow.ts:181 [EXTRACTED]
  ```
  export const WholeEndSchema = z.object({
  ```
- `CopyContractSchema` ← src/workflow/workspace.ts:63 [EXTRACTED]
  ```
  export const CopyContractSchema = z.discriminatedUnion('mode', CopyContractOptions) satisfies z.ZodType<CopyContract>;
  ```
- `TeamContractSchema` ← src/workflow/workspace.ts:66 [EXTRACTED]
  ```
  export const TeamContractSchema = z.object({ mode: z.literal('team'), branch: z.string().min(1), publish: z.literal(true).optional() });
  ```
- `WorkspaceContractSchema` ← src/workflow/workspace.ts:68 [EXTRACTED]
  ```
  export const WorkspaceContractSchema = z.discriminatedUnion('mode', [...CopyContractOptions, TeamContractSchema]) satisfies z.ZodType<WorkspaceContract>;
  ```
- `isPublishContract` ← src/workflow/workspace.ts:71 [EXTRACTED]
  ```
  export function isPublishContract(contract: WorkspaceContract): boolean {
  ```
- `runBranchPrefix` ← src/workflow/workspace.ts:98 [EXTRACTED]
  ```
  export function runBranchPrefix(runId: string): string {
  ```
- `branchName` ← src/workflow/workspace.ts:103 [EXTRACTED]
  ```
  export function branchName(runId: string, stepPath: string, pass: number): string {
  ```
- `resolveMode` ← src/workflow/workspace.ts:120 [EXTRACTED]
  ```
  export function resolveMode(step: WorkflowStep, ancestors: readonly WorkflowStep[]): WorkspaceMode {
  ```
- `cloneOf` ← src/workflow/workspace.ts:165 [EXTRACTED]
  ```
  export function cloneOf(step: WorkflowStep): ClonePlace | undefined {
  ```
- `contractClone` ← src/workflow/workspace.ts:172 [EXTRACTED]
  ```
  export function contractClone(contract: WorkspaceContract | undefined): ClonePlace | undefined {
  ```
- `confinedOf` ← src/workflow/workspace.ts:177 [EXTRACTED]
  ```
  export function confinedOf(step: WorkflowStep): string | undefined {
  ```
- `isIsolated` ← src/workflow/workspace.ts:194 [EXTRACTED]
  ```
  export function isIsolated(run: Pick<RunState, 'definition' | 'workflows'>): boolean {
  ```
- `worksInTeam` ← src/workflow/workspace.ts:203 [EXTRACTED]
  ```
  export function worksInTeam(run: Pick<RunState, 'definition' | 'workflows'>): boolean {
  ```
- `runsInCheckout` ← src/workflow/workspace.ts:219 [EXTRACTED]
  ```
  export function runsInCheckout(step: WorkflowStep, ancestors: readonly WorkflowStep[]): boolean {
  ```
- `writesBranch` ← src/workflow/workspace.ts:227 [EXTRACTED]
  ```
  export function writesBranch(step: WorkflowStep, outer: readonly Level[], childOf: ChildOf): boolean {
  ```
- `deliveryProblem` ← src/workflow/workspace.ts:241 [EXTRACTED]
  ```
  export function deliveryProblem(
  ```
- `stepMode` ← src/workflow/workspace.ts:290 [EXTRACTED]
  ```
  export function stepMode(run: StepTree, path: string): WorkspaceMode | undefined {
  ```
- `runLevels` ← src/workflow/workspace.ts:306 [EXTRACTED]
  ```
  export function runLevels(definition: Pick<WorkflowDefinition, 'workspace'>): WorkflowStep[] {
  ```
- `isRunLevel` ← src/workflow/workspace.ts:311 [EXTRACTED]
  ```
  export function isRunLevel(step: WorkflowStep): boolean {
  ```
- `levelsInside` ← src/workflow/workspace.ts:326 [EXTRACTED]
  ```
  export function levelsInside<TLevel extends Level>(outer: readonly TLevel[], level: TLevel, child: WorkflowDefinition | InlineWorkflow | undefined): TLevel[] {
  ```
- `sharedWorkspace` ← src/workflow/workspace.ts:398 [EXTRACTED]
  ```
  export function sharedWorkspace(run: RunState, path: string): string | undefined {
  ```
- `basePinBranch` ← src/workflow/workspace.ts:421 [EXTRACTED]
  ```
  export function basePinBranch(runId: string): string {
  ```
- `runCopyBranch` ← src/workflow/workspace.ts:426 [EXTRACTED]
  ```
  export function runCopyBranch(runId: string): string {
  ```
- `runCopyToMerge` ← src/workflow/workspace.ts:434 [EXTRACTED]
  ```
  export function runCopyToMerge(run: Pick<RunState, 'id' | 'status' | 'definition' | 'copies' | 'base'>): string | undefined {
  ```
- `deliverableOf` ← src/workflow/workspace.ts:472 [EXTRACTED]
  ```
  export function deliverableOf(run: RunState, state: StepState, step: WorkflowStep, changes?: StepChanges): Omit<Delivery, 'reported'> | undefined {
  ```
- `workLeftUndelivered` ← src/workflow/workspace.ts:503 [EXTRACTED]
  ```
  export function workLeftUndelivered(run: RunState, state: StepState): { branch: string; head: string; child: { step: string; branch: string } } | undefined {
  ```
- `childWorkOff` ← src/workflow/workspace.ts:517 [EXTRACTED]
  ```
  export function childWorkOff(run: RunState, state: StepState, branch: string): Array<{ step: string; branch: string; commit: string }> {
  ```
- `deliveryTarget` ← src/workflow/workspace.ts:532 [EXTRACTED]
  ```
  export function deliveryTarget(run: Pick<RunState, 'base' | 'copies' | 'deliveries'>, branch: string): string | undefined {
  ```
- `sessionSource` ← src/workflow/workspace.ts:804 [EXTRACTED]
  ```
  export function sessionSource(run: RunState, scope: Scope, name: string): { state: StepState; definition: WorkflowStep } | undefined {
  ```
- `sessionOf` ← src/workflow/workspace.ts:823 [EXTRACTED]
  ```
  export function sessionOf(run: RunState, scope: Scope, state: StepState, definition: WorkflowStep): LeaseSession | WorkflowFailure | undefined {
  ```
- `planWorkspace` ← src/workflow/workspace.ts:895 [EXTRACTED]
  ```
  export function planWorkspace(
  ```
- `cloneBranchOf` ← src/workflow/workspace.ts:1167 [EXTRACTED]
  ```
  export function cloneBranchOf(run: StepTree & Pick<RunState, 'id'>, path: string): string | undefined {
  ```
- `roleLevelOf` ← src/workflow/workspace.ts:1190 [EXTRACTED]
  ```
  export function roleLevelOf(step: WorkflowStep, defaultRole: string | undefined): RoleLevel {
  ```
- `writtenRole` ← src/workflow/workspace.ts:1201 [EXTRACTED]
  ```
  export function writtenRole(role: StepRoleSpec): string {
  ```
- `resolvedRoleOf` ← src/workflow/workspace.ts:1223 [EXTRACTED]
  ```
  export function resolvedRoleOf<TRole extends StepRoleSpec>(levels: readonly RoleLevel<TRole>[]): ResolvedRole<TRole> | undefined {
  ```
- `copyOf` ← src/workflow/workspace.ts:1249 [EXTRACTED]
  ```
  export function copyOf<TRole extends StepRoleSpec>(levels: readonly RoleLevel<TRole>[]): StepCopy<TRole> | undefined {
  ```
- `copyRoleConflict` ← src/workflow/workspace.ts:1274 [EXTRACTED]
  ```
  export function copyRoleConflict<TRole extends StepRoleSpec>(levels: readonly RoleLevel<TRole>[]): { copy: StepCopy<TRole>; resolved: ResolvedRole<TRole> | undefined } | undefined {
  ```
- `stepRoleOf` ← src/workflow/workspace.ts:1383 [EXTRACTED]
  ```
  export function stepRoleOf(run: StepTree, path: string): StepRole {
  ```
- `opensCopy` ← src/workflow/workspace.ts:1393 [EXTRACTED]
  ```
  export function opensCopy(step: WorkflowStep): boolean {
  ```
- `plannedBranch` ← src/workflow/workspace.ts:1402 [EXTRACTED]
  ```
  export function plannedBranch(run: RunState, scope: Scope, state: StepState, definition: WorkflowStep): string | undefined {
  ```
- `protectedPaths` ← src/workflow/worktree.ts:55 [EXTRACTED]
  ```
  export function protectedPaths(changed: readonly string[]): string[] {
  ```
- `GIT_NOT_STARTED` ← src/workflow/worktree.ts:75 [EXTRACTED]
  ```
  export const GIT_NOT_STARTED = 127;
  ```
- `GIT_STOPPED` ← src/workflow/worktree.ts:78 [EXTRACTED]
  ```
  export const GIT_STOPPED = 124;
  ```
- `unstartedGit` ← src/workflow/worktree.ts:92 [EXTRACTED]
  ```
  export function unstartedGit({ cwd, error, isCwdThere }: { cwd: string; error: Error; isCwdThere: boolean }): GitResult {
  ```
- `stoppedGit` ← src/workflow/worktree.ts:101 [EXTRACTED]
  ```
  export function stoppedGit(why: string, stderr: string): GitResult {
  ```
- `gitAnswer` ← src/workflow/worktree.ts:109 [EXTRACTED]
  ```
  export function gitAnswer(result: GitResult): GitAnswer {
  ```
- `unansweredGit` ← src/workflow/worktree.ts:117 [EXTRACTED]
  ```
  export function unansweredGit(question: string, result: GitResult): Error {
  ```
- `saidYes` ← src/workflow/worktree.ts:122 [EXTRACTED]
  ```
  export function saidYes(answer: GitAnswer, question: string): boolean {
  ```
- `yesOutput` ← src/workflow/worktree.ts:129 [EXTRACTED]
  ```
  export function yesOutput(answer: GitAnswer, question: string): string {
  ```
- `git` ← src/workflow/worktree.ts:157 [EXTRACTED]
  ```
  export function git(cwd: string, args: string[], options?: GitOptions): Promise<GitResult> {
  ```
- `boundedGit` ← src/workflow/worktree.ts:174 [EXTRACTED]
  ```
  export function boundedGit(expiresAt: string | undefined, env: NodeJS.ProcessEnv = process.env): Git {
  ```
- `untrustedGit` ← src/workflow/worktree.ts:195 [EXTRACTED]
  ```
  export function untrustedGit(env: NodeJS.ProcessEnv, expiresAt?: string, kept: MemberConfig = NO_MEMBER_CONFIG): UntrustedGit {
  ```
- `keptOriginUrl` ← src/workflow/worktree.ts:233 [EXTRACTED]
  ```
  export function keptOriginUrl(kept: MemberConfig): string | undefined {
  ```
- `pushTargets` ← src/workflow/worktree.ts:242 [EXTRACTED]
  ```
  export function pushTargets(kept: MemberConfig): { url: string; kept: MemberConfig }[] {
  ```
- `readMemberConfig` ← src/workflow/worktree.ts:257 [EXTRACTED]
  ```
  export async function readMemberConfig(dir: string): Promise<string[] | { error: string }> {
  ```
- `hostGitEnv` ← src/workflow/worktree.ts:288 [EXTRACTED]
  ```
  export function hostGitEnv(env: NodeJS.ProcessEnv = process.env): NodeJS.ProcessEnv {
  ```
- `remoteGit` ← src/workflow/worktree.ts:361 [EXTRACTED]
  ```
  export async function remoteGit(dir: string, member: MemberRemote, args: string[], runGit: Git, options?: GitOptions): Promise<GitResult> {
  ```
- `worktreePath` ← src/workflow/worktree.ts:597 [EXTRACTED]
  ```
  export function worktreePath(main: string, branch: string): string {
  ```
- `stepCheckout` ← src/workflow/worktree.ts:604 [EXTRACTED]
  ```
  export function stepCheckout(active: string, branch: string | undefined): string {
  ```
- `worktreeCheckout` ← src/workflow/worktree.ts:609 [EXTRACTED]
  ```
  export function worktreeCheckout(dir: string): string | undefined {
  ```
- `gitPath` ← src/workflow/worktree.ts:619 [EXTRACTED]
  ```
  export async function gitPath(cwd: string, name: string, runGit: Git = git): Promise<string | undefined> {
  ```
- `removeWorktreeSetup` ← src/workflow/worktree.ts:662 [EXTRACTED]
  ```
  export async function removeWorktreeSetup(checkout: string, { dryRun = false, gone = [] }: { dryRun?: boolean; gone?: readonly string[] } = {}): Promise<string[]> {
  ```
- `runWorktreesOf` ← src/workflow/worktree.ts:773 [EXTRACTED]
  ```
  export async function runWorktreesOf(checkouts: readonly string[]): Promise<{ worktrees: Array<{ checkout: string; worktree: RunWorktree }>; unread: Array<{ checkout: string; error: string }> }> {
  ```
- `removeRunWorktree` ← src/workflow/worktree.ts:854 [EXTRACTED]
  ```
  export async function removeRunWorktree(checkout: string, worktree: Extract<RunWorktree, { kind: 'removable' }>): Promise<{ ok: true } | { ok: false; reason: string }> {
  ```
- `hooksPath` ← src/workflow/worktree.ts:866 [EXTRACTED]
  ```
  export function hooksPath(main: string): string {
  ```
- `headCommit` ← src/workflow/worktree.ts:871 [EXTRACTED]
  ```
  export async function headCommit(cwd: string): Promise<{ ref?: string; commit: string } | undefined> {
  ```
- `ensureWorktree` ← src/workflow/worktree.ts:891 [EXTRACTED]
  ```
  export async function ensureWorktree(main: string, branch: string, start: string): Promise<{ dir: string; created: boolean } | { error: string }> {
  ```
- `setupUnfinished` ← src/workflow/worktree.ts:935 [EXTRACTED]
  ```
  export async function setupUnfinished(dir: string): Promise<boolean> {
  ```
- `markSetup` ← src/workflow/worktree.ts:941 [EXTRACTED]
  ```
  export async function markSetup(dir: string, state: 'unfinished' | 'finished'): Promise<void> {
  ```
- `offBranch` ← src/workflow/worktree.ts:954 [EXTRACTED]
  ```
  export async function offBranch(dir: string, branch: string, runGit: Git = git): Promise<string | undefined> {
  ```
- `reconcileCopy` ← src/workflow/worktree.ts:972 [EXTRACTED]
  ```
  export async function reconcileCopy(main: string, branch: string, expected: string): Promise<{ error: string } | undefined> {
  ```
- `worktreeHooks` ← src/workflow/worktree.ts:1035 [EXTRACTED]
  ```
  export async function worktreeHooks(dir: string, hooks: string): Promise<void> {
  ```
- `clearWorktreeHooks` ← src/workflow/worktree.ts:1049 [EXTRACTED]
  ```
  export async function clearWorktreeHooks(dir: string): Promise<void> {
  ```
- `fetchMissingCommits` ← src/workflow/worktree.ts:1058 [EXTRACTED]
  ```
  export async function fetchMissingCommits(
  ```
- `mergeBranch` ← src/workflow/worktree.ts:1090 [EXTRACTED]
  ```
  export async function mergeBranch(dir: string, commit: string, runGit: Git): Promise<
  ```
- `applyBaseConfig` ← src/workflow/worktree.ts:1124 [EXTRACTED]
  ```
  export async function applyBaseConfig(
  ```
- `reopenConfigConflicts` ← src/workflow/worktree.ts:1266 [EXTRACTED]
  ```
  export async function reopenConfigConflicts(dir: string, saved: string, runGit: Git): Promise<void> {
  ```
- `savedConfigPaths` ← src/workflow/worktree.ts:1277 [EXTRACTED]
  ```
  export async function savedConfigPaths(saved: string): Promise<readonly string[]> {
  ```
- `saveConfig` ← src/workflow/worktree.ts:1287 [EXTRACTED]
  ```
  export async function saveConfig(dir: string, saved: string, paths: readonly string[] = AGENT_PATHS): Promise<void> {
  ```
- `replaceConfig` ← src/workflow/worktree.ts:1300 [EXTRACTED]
  ```
  export async function replaceConfig(dir: string, from: string): Promise<void> {
  ```
- `worktreeContentKey` ← src/workflow/worktree.ts:1342 [EXTRACTED]
  ```
  export async function worktreeContentKey(dir: string, relative: string, run: Git): Promise<string> {
  ```
- `recordConfigOverlay` ← src/workflow/worktree.ts:1352 [EXTRACTED]
  ```
  export async function recordConfigOverlay(dir: string, saved: string): Promise<void> {
  ```
- `unchangedOverlayPaths` ← src/workflow/worktree.ts:1363 [EXTRACTED]
  ```
  export async function unchangedOverlayPaths(dir: string, saved: string, dirty: readonly string[]): Promise<{ paths: ReadonlySet<string> } | { error: string }> {
  ```
- `restoreUneditedConfig` ← src/workflow/worktree.ts:1398 [EXTRACTED]
  ```
  export async function restoreUneditedConfig(dir: string, _commit: string, saved: string, runGit: Git): Promise<string | undefined> {
  ```
- `commitWork` ← src/workflow/worktree.ts:1622 [EXTRACTED]
  ```
  export async function commitWork(
  ```
- `pushIfOrigin` ← src/workflow/worktree.ts:1662 [EXTRACTED]
  ```
  export async function pushIfOrigin(dir: string, branch: string, commits: string[], runGit: UntrustedGit, member: MemberRemote): Promise<'pushed' | 'no-origin' | 'unchanged' | { error: string }> {
  ```
- `forgetUpstream` ← src/workflow/worktree.ts:1701 [EXTRACTED]
  ```
  export async function forgetUpstream(checkout: string, branch: string, { dryRun = false } = {}): Promise<string[]> {
  ```
- `removeWorktree` ← src/workflow/worktree.ts:1908 [EXTRACTED]
  ```
  export async function removeWorktree(main: string, dir: string): Promise<{ ok: true } | { ok: false; reason: string }> {
  ```
- `forgetGoneWorktrees` ← src/workflow/worktree.ts:1925 [EXTRACTED]
  ```
  export async function forgetGoneWorktrees(main: string): Promise<{ ok: true } | { ok: false; reason: string }> {
  ```
- `markReadCopy` ← src/workflow/worktree.ts:1975 [EXTRACTED]
  ```
  export async function markReadCopy(dir: string, { branch, step }: { branch: string; step: string }, runGit: Git): Promise<{ found: string[] } | { error: string }> {
  ```
- `releaseReadCopy` ← src/workflow/worktree.ts:1995 [EXTRACTED]
  ```
  export async function releaseReadCopy(dir: string): Promise<void> {
  ```
- `unrestoredCopy` ← src/workflow/worktree.ts:2009 [EXTRACTED]
  ```
  export async function unrestoredCopy(dir: string): Promise<
  ```
- `keptSentence` ← src/workflow/worktree.ts:2155 [EXTRACTED]
  ```
  export function keptSentence(kept: KeptChanges): string {
  ```
- `putBackCopy` ← src/workflow/worktree.ts:2166 [EXTRACTED]
  ```
  export async function putBackCopy({ dir, branch, commit, found, changed, attempt, step, run }: {
  ```
- `Writes` ← src/workflow/writes.ts:56 [EXTRACTED]
  ```
  export const Writes = { isCheckoutPath, isRenderedPath, inCheckout, keeps } as const;
  ```
- `noArrayFilterMapRule` ← oxlint-plugin-teamai/anti-slop/rules/no-array-filter-map.ts:6 [EXTRACTED]
  ```
  export const noArrayFilterMapRule = defineRule({
  ```
- `noChainedTypeAssertionsRule` ← oxlint-plugin-teamai/anti-slop/rules/no-chained-type-assertions.ts:54 [EXTRACTED]
  ```
  export const noChainedTypeAssertionsRule = defineRule({
  ```
- `noConditionalEmptyObjectSpreadRule` ← oxlint-plugin-teamai/anti-slop/rules/no-conditional-empty-object-spread.ts:26 [EXTRACTED]
  ```
  export const noConditionalEmptyObjectSpreadRule = defineRule({
  ```
- `noKnownValueWideningRule` ← oxlint-plugin-teamai/anti-slop/rules/no-known-value-widening.ts:271 [EXTRACTED]
  ```
  export const noKnownValueWideningRule = defineRule({
  ```
- `noModuleMockingRule` ← oxlint-plugin-teamai/anti-slop/rules/no-module-mocking.ts:58 [EXTRACTED]
  ```
  export const noModuleMockingRule = defineRule({
  ```
- `noObjectParametersRule` ← oxlint-plugin-teamai/anti-slop/rules/no-object-parameters.ts:24 [EXTRACTED]
  ```
  export const noObjectParametersRule = defineRule({
  ```
- `noReduceAccumulatorCopyRule` ← oxlint-plugin-teamai/anti-slop/rules/no-reduce-accumulator-copy.ts:68 [EXTRACTED]
  ```
  export const noReduceAccumulatorCopyRule = defineRule({
  ```
- `noReflectApplyRule` ← oxlint-plugin-teamai/anti-slop/rules/no-reflect-apply.ts:6 [EXTRACTED]
  ```
  export const noReflectApplyRule = defineRule({
  ```
- `noReflectGetRule` ← oxlint-plugin-teamai/anti-slop/rules/no-reflect-get.ts:6 [EXTRACTED]
  ```
  export const noReflectGetRule = defineRule({
  ```
- `noRuntimeTypeofRule` ← oxlint-plugin-teamai/anti-slop/rules/no-runtime-typeof.ts:36 [EXTRACTED]
  ```
  export const noRuntimeTypeofRule = defineRule({
  ```
- `noForbiddenTermInSymbolNamesRule` ← oxlint-plugin-teamai/anti-slop/rules/no-shape-in-symbol-names.ts:18 [EXTRACTED]
  ```
  export const noForbiddenTermInSymbolNamesRule = defineRule({
  ```
- `noUnknownParametersRule` ← oxlint-plugin-teamai/anti-slop/rules/no-unknown-parameters.ts:28 [EXTRACTED]
  ```
  export const noUnknownParametersRule = defineRule({
  ```
- `noUnknownReturnsRule` ← oxlint-plugin-teamai/anti-slop/rules/no-unknown-returns.ts:21 [EXTRACTED]
  ```
  export const noUnknownReturnsRule = defineRule({
  ```
- `noUnknownTypeAliasesRule` ← oxlint-plugin-teamai/anti-slop/rules/no-unknown-type-aliases.ts:12 [EXTRACTED]
  ```
  export const noUnknownTypeAliasesRule = defineRule({
  ```
- `noUnsafeDictionaryTypeRule` ← oxlint-plugin-teamai/anti-slop/rules/no-unsafe-dictionary-type.ts:105 [EXTRACTED]
  ```
  export const noUnsafeDictionaryTypeRule = defineRule({
  ```
- `noWidenThenAssertRule` ← oxlint-plugin-teamai/anti-slop/rules/no-widen-then-assert.ts:315 [EXTRACTED]
  ```
  export const noWidenThenAssertRule = defineRule({
  ```
- `requireSafetyCommentForTypeAssertionRule` ← oxlint-plugin-teamai/anti-slop/rules/require-safety-comment-for-type-assertion.ts:82 [EXTRACTED]
  ```
  export const requireSafetyCommentForTypeAssertionRule = defineRule({
  ```
- `unwrapArrayExpression` ← oxlint-plugin-teamai/anti-slop/shared/array-method.ts:4 [EXTRACTED]
  ```
  export function unwrapArrayExpression(node: ESTree.Node): ESTree.Node {
  ```
- `resolveArrayBinding` ← oxlint-plugin-teamai/anti-slop/shared/array-method.ts:19 [EXTRACTED]
  ```
  export function resolveArrayBinding(sourceCode: SourceCode, node: ESTree.Node): Variable | null {
  ```
- `arrayMethodTarget` ← oxlint-plugin-teamai/anti-slop/shared/array-method.ts:32 [EXTRACTED]
  ```
  export function arrayMethodTarget(
  ```
- `isKnownArrayExpression` ← oxlint-plugin-teamai/anti-slop/shared/array-method.ts:60 [EXTRACTED]
  ```
  export function isKnownArrayExpression(
  ```
- `createTypeEnvironment` ← oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts:57 [EXTRACTED]
  ```
  export function createTypeEnvironment(
  ```
- `classifyUnsafeDictionaryValue` ← oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts:296 [EXTRACTED]
  ```
  export function classifyUnsafeDictionaryValue(
  ```
- `classifyUnsafeDictionary` ← oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts:304 [EXTRACTED]
  ```
  export function classifyUnsafeDictionary(
  ```
- `classifyWideningTarget` ← oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts:320 [EXTRACTED]
  ```
  export function classifyWideningTarget(
  ```
- `isPopulatedObjectExpression` ← oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts:480 [EXTRACTED]
  ```
  export function isPopulatedObjectExpression(expression: ESTree.Expression): boolean {
  ```
- `isKnownEvidenceExpression` ← oxlint-plugin-teamai/anti-slop/shared/dictionary-types.ts:493 [EXTRACTED]
  ```
  export function isKnownEvidenceExpression(expression: ESTree.Expression): boolean {
  ```
- `containsUnknownType` ← oxlint-plugin-teamai/anti-slop/shared/function-parameters.ts:6 [EXTRACTED]
  ```
  export function containsUnknownType(type: ESTree.TSType): boolean {
  ```
- `functionParameterTypeAnnotation` ← oxlint-plugin-teamai/anti-slop/shared/function-parameters.ts:13 [EXTRACTED]
  ```
  export function functionParameterTypeAnnotation(
  ```
- `functionParameterBindingName` ← oxlint-plugin-teamai/anti-slop/shared/function-parameters.ts:29 [EXTRACTED]
  ```
  export function functionParameterBindingName(
  ```
- `lexicalTypeParameterNames` ← oxlint-plugin-teamai/anti-slop/shared/lexical-type-parameters.ts:35 [EXTRACTED]
  ```
  export function lexicalTypeParameterNames(
  ```
- `isGlobalReflectMethodCall` ← oxlint-plugin-teamai/anti-slop/shared/reflect-method.ts:13 [EXTRACTED]
  ```
  export function isGlobalReflectMethodCall(
  ```
- `resolveVariable` ← oxlint-plugin-teamai/anti-slop/shared/scope.ts:4 [EXTRACTED]
  ```
  export function resolveVariable(
  ```
- `createTypeAliasEnvironment` ← oxlint-plugin-teamai/anti-slop/shared/type-alias-resolution.ts:117 [EXTRACTED]
  ```
  export function createTypeAliasEnvironment(
  ```
- `visibleTypeAlias` ← oxlint-plugin-teamai/anti-slop/shared/type-alias-resolution.ts:164 [EXTRACTED]
  ```
  export function visibleTypeAlias(
  ```
- `hasVisibleTypeBinding` ← oxlint-plugin-teamai/anti-slop/shared/type-alias-resolution.ts:175 [EXTRACTED]
  ```
  export function hasVisibleTypeBinding(
  ```
- `resolvedTypeMatches` ← oxlint-plugin-teamai/anti-slop/shared/type-alias-resolution.ts:212 [EXTRACTED]
  ```
  export function resolvedTypeMatches(
  ```
- `endedRequest` ← packages/provider-core/src/contract.ts:50 [EXTRACTED]
  ```
  export function endedRequest({ url, title, openedAt, state, closedAt, merge }: { url: string; title: string; openedAt: string; state: string; closedAt: string | null | undefined; merge?: MergedAs }): PullRequestRecord {
  ```
- `mergedAs` ← packages/provider-core/src/contract.ts:58 [EXTRACTED]
  ```
  export function mergedAs({ head, commit }: { head: string | null | undefined; commit: string | null | undefined }): MergedAs | undefined {
  ```
- `RepoNotFoundError` ← packages/provider-core/src/contract.ts:91 [EXTRACTED]
  ```
  export class RepoNotFoundError extends Error {
  ```
- `OrganizationNotFoundError` ← packages/provider-core/src/contract.ts:98 [EXTRACTED]
  ```
  export class OrganizationNotFoundError extends Error {
  ```
- `RepoCreatePermissionError` ← packages/provider-core/src/contract.ts:110 [EXTRACTED]
  ```
  export class RepoCreatePermissionError extends Error {
  ```
- `makeProviderRegistry` ← packages/provider-core/src/registry.ts:18 [EXTRACTED]
  ```
  export function makeProviderRegistry<
  ```
- `answering` ← packages/runtime-kit/src/answering.ts:21 [EXTRACTED]
  ```
  export function answering(handlers: RuntimeHandlers): Answering {
  ```
- `recordStore` ← packages/runtime-kit/src/journal.ts:37 [EXTRACTED]
  ```
  export function recordStore<TSchema extends z.ZodType>(dir: string, schema: TSchema): RecordStore<z.infer<TSchema>> {
  ```
- `HOLD_STALE_MS` ← packages/runtime-kit/src/journal.ts:103 [EXTRACTED]
  ```
  export const HOLD_STALE_MS = 60_000;
  ```
- `hold` ← packages/runtime-kit/src/journal.ts:191 [EXTRACTED]
  ```
  export async function hold(dir: string, key: string): Promise<() => void> {
  ```
- `opLedger` ← packages/runtime-kit/src/ledger.ts:89 [EXTRACTED]
  ```
  export function opLedger<TRun = unknown>({ name, write }: { name: string; write: (message: RuntimeMessage) => void }): OpLedger<TRun> {
  ```
- `WRAPPER_PREFIX` ← packages/runtime-kit/src/outer.ts:21 [EXTRACTED]
  ```
  export const WRAPPER_PREFIX = 'teamai-sandbox-';
  ```
- `OuterHandleSchema` ← packages/runtime-kit/src/outer.ts:24 [EXTRACTED]
  ```
  export const OuterHandleSchema = z.object({ place: z.string().min(1), socket: z.string().min(1) });
  ```
- `RegisterSchema` ← packages/runtime-kit/src/outer.ts:32 [EXTRACTED]
  ```
  export const RegisterSchema = z.object({ register: z.object({ agent: AgentSchema }) });
  ```
- `ConnectedSchema` ← packages/runtime-kit/src/outer.ts:35 [EXTRACTED]
  ```
  export const ConnectedSchema = z.object({ connected: z.object({ agent: AgentSchema }) });
  ```
- `registerLine` ← packages/runtime-kit/src/outer.ts:38 [EXTRACTED]
  ```
  export function registerLine(agent: string | null): string {
  ```
- `socketOf` ← packages/runtime-kit/src/outer.ts:43 [EXTRACTED]
  ```
  export function socketOf(outer: string): string | undefined {
  ```
- `registerThrough` ← packages/runtime-kit/src/outer.ts:83 [EXTRACTED]
  ```
  export function registerThrough({ outer, agent }: { outer: string; agent: string | null }): Promise<Registration | { ok: false; why: string }> {
  ```
- `placeWork` ← packages/runtime-kit/src/places.ts:19 [EXTRACTED]
  ```
  export function placeWork(): PlaceWork {
  ```
- `repositoryKey` ← packages/runtime-kit/src/repository.ts:11 [EXTRACTED]
  ```
  export function repositoryKey(url: string): string | undefined {
  ```
- `eachLine` ← packages/runtime-kit/src/serve.ts:55 [EXTRACTED]
  ```
  export function eachLine(input: NodeJS.ReadableStream, onLine: (text: string) => void): Promise<void> {
  ```
- `isStartedByTeamai` ← packages/runtime-kit/src/serve.ts:103 [EXTRACTED]
  ```
  export function isStartedByTeamai(env: NodeJS.ProcessEnv): boolean {
  ```
- `serveRuntime` ← packages/runtime-kit/src/serve.ts:112 [EXTRACTED]
  ```
  export function serveRuntime({ name, input = process.stdin, env, ledger, handlers, holds, stopped, debug }: ServeRuntime): Promise<number> {
  ```
- `codexWakeLine` ← packages/runtime-kit/src/wake.ts:12 [EXTRACTED]
  ```
  export function codexWakeLine(pool: string): string {
  ```
- `STOP_SETTLE_MS` ← packages/runtime-paseo/src/conversation.ts:65 [EXTRACTED]
  ```
  export const STOP_SETTLE_MS = 10_000;
  ```
- `STOP_POLL_MS` ← packages/runtime-paseo/src/conversation.ts:68 [EXTRACTED]
  ```
  export const STOP_POLL_MS = 250;
  ```
- `isStopped` ← packages/runtime-paseo/src/conversation.ts:71 [EXTRACTED]
  ```
  export const isStopped = (agent: Awaited<ReturnType<Daemon['agent']>> | 'late' | undefined): boolean => agent === null || (agent !== undefined && agent !== 'late' && agent.status !== 'running' && agent.status !== 'initializing');
  ```
- `late` ← packages/runtime-paseo/src/conversation.ts:74 [EXTRACTED]
  ```
  export const late = (deadline: number): Promise<'late'> => new Promise((resolve) => {
  ```
- `isStillRunning` ← packages/runtime-paseo/src/conversation.ts:82 [EXTRACTED]
  ```
  export async function isStillRunning(live: Daemon, agentId: string, deadline: number): Promise<boolean> {
  ```
- `isFailedStop` ← packages/runtime-paseo/src/conversation.ts:92 [EXTRACTED]
  ```
  export const isFailedStop = (outcome: OpState | undefined): boolean => outcome?.state === 'failed' && outcome.failure.code === CANCEL_FAILED;
  ```
- `agentIdOf` ← packages/runtime-paseo/src/conversation.ts:95 [EXTRACTED]
  ```
  export function agentIdOf(op: OpId): string {
  ```
- `delay` ← packages/runtime-paseo/src/conversation.ts:178 [EXTRACTED]
  ```
  export const delay = (ms: number): Promise<void> => new Promise((resolve) => setTimeout(resolve, ms));
  ```
- `withoutDaemon` ← packages/runtime-paseo/src/conversation.ts:248 [EXTRACTED]
  ```
  export const withoutDaemon = (failure: RuntimeFailure | undefined, cannot: string, then: string): RuntimeFailure => (failure
  ```
- `conversations` ← packages/runtime-paseo/src/conversation.ts:292 [EXTRACTED]
  ```
  export function conversations(state: ProcessState, { ensureProvider }: { ensureProvider: EnsureProvider }) {
  ```
- `PASEO_COMMAND` ← packages/runtime-paseo/src/host-commands.ts:2 [EXTRACTED]
  ```
  export const PASEO_COMMAND = 'paseo';
  ```
- `paseoKeyOf` ← packages/runtime-paseo/src/journal.ts:174 [EXTRACTED]
  ```
  export function paseoKeyOf(directory: string): string {
  ```
- `resolvedDir` ← packages/runtime-paseo/src/journal.ts:184 [EXTRACTED]
  ```
  export function resolvedDir(directory: string): string {
  ```
- `journal` ← packages/runtime-paseo/src/journal.ts:199 [EXTRACTED]
  ```
  export function journal(root: string) {
  ```
- `judging` ← packages/runtime-paseo/src/judge.ts:32 [EXTRACTED]
  ```
  export function judging(state: ProcessState, { conversation, adopt }: { conversation: Conversations; adopt: ReturnType<typeof workspaces>['adopt'] }) {
  ```
- `notOffered` ← packages/runtime-paseo/src/offer.ts:25 [EXTRACTED]
  ```
  export const notOffered = (offers: ReadonlyMap<string, Offer>, tool: string, isJudge: boolean): RuntimeFailure | undefined => {
  ```
- `checkOf` ← packages/runtime-paseo/src/offer.ts:83 [EXTRACTED]
  ```
  export function checkOf(found: Found): Extract<RuntimeMessage, { type: 'init' }> {
  ```
- `offerOf` ← packages/runtime-paseo/src/offer.ts:92 [EXTRACTED]
  ```
  export function offerOf(found: Found & { mode: 'attended' | 'unattended' }): Offered {
  ```
- `parseOptions` ← packages/runtime-paseo/src/options.ts:23 [EXTRACTED]
  ```
  export function parseOptions(raw: RuntimeOptions): { ok: true; options: PaseoOptions } | { ok: false; failure: RuntimeFailure } {
  ```
- `isPaseoTool` ← packages/runtime-paseo/src/providers.ts:30 [EXTRACTED]
  ```
  export function isPaseoTool(tool: string): tool is PaseoTool {
  ```
- `instanceHomeOf` ← packages/runtime-paseo/src/providers.ts:41 [EXTRACTED]
  ```
  export function instanceHomeOf(home: NonNullable<InitInstance['home']>): string {
  ```
- `homeEnvAt` ← packages/runtime-paseo/src/providers.ts:46 [EXTRACTED]
  ```
  export function homeEnvAt(homeEnv: readonly string[], dir: string): Record<string, string> {
  ```
- `shownPath` ← packages/runtime-paseo/src/providers.ts:51 [EXTRACTED]
  ```
  export function shownPath(dir: string): string {
  ```
- `homeDirOf` ← packages/runtime-paseo/src/providers.ts:58 [EXTRACTED]
  ```
  export function homeDirOf(tool: PaseoTool): string {
  ```
- `CustomProvidersSchema` ← packages/runtime-paseo/src/providers.ts:78 [EXTRACTED]
  ```
  export const CustomProvidersSchema = z.record(z.string(), z.object({ extends: z.string().optional(), command: z.array(z.string()).optional(), env: z.record(z.string(), z.string()).optional() }));
  ```
- `keptOf` ← packages/runtime-paseo/src/providers.ts:86 [EXTRACTED]
  ```
  export function keptOf(providers: CustomProviders, variables: readonly string[]): CustomProviders {
  ```
- `namedProblem` ← packages/runtime-paseo/src/providers.ts:95 [EXTRACTED]
  ```
  export const namedProblem = (named: string, tool: PaseoTool, custom: CustomProviders): string | undefined => (custom[named]?.extends === tool
  ```
- `daemonRuns` ← packages/runtime-paseo/src/providers.ts:116 [EXTRACTED]
  ```
  export function daemonRuns({ executable, command, hostPlatform }: { executable: string | undefined; command: string; hostPlatform: NodeJS.Platform | undefined }): boolean {
  ```
- `providerOf` ← packages/runtime-paseo/src/providers.ts:136 [EXTRACTED]
  ```
  export function providerOf(instance: InitInstance, tool: PaseoTool, { custom, named, home, homeEnv, onThisMachine }: {
  ```
- `addedNotice` ← packages/runtime-paseo/src/providers.ts:210 [EXTRACTED]
  ```
  export function addedNotice(url: string, { id, entry }: ProviderToAdd, name: string): string {
  ```
- `providerAdds` ← packages/runtime-paseo/src/providers.ts:220 [EXTRACTED]
  ```
  export function providerAdds(state: ProcessState) {
  ```
- `serve` ← packages/runtime-paseo/src/runtime.ts:70 [EXTRACTED]
  ```
  export async function serve({ input, env, write: emit, note, journal, startedFrom }: Serving): Promise<number> {
  ```
- `throughOf` ← packages/runtime-paseo/src/sandbox.ts:26 [EXTRACTED]
  ```
  export const throughOf = (place: Place | undefined): Through | undefined => (place?.kind === 'worktree' ? place.through : undefined);
  ```
- `openThrough` ← packages/runtime-paseo/src/sandbox.ts:39 [EXTRACTED]
  ```
  export async function openThrough(state: ProcessState, live: Daemon, request: Extract<RuntimeRequest, { type: 'open' }> & { outer: string }, target: Target): Promise<Through | RuntimeFailure> {
  ```
- `handOver` ← packages/runtime-paseo/src/sandbox.ts:79 [EXTRACTED]
  ```
  export async function handOver(live: Daemon, { record, provider, registration, stopped, isStillOurs, markSent }: {
  ```
- `readsTokens` ← packages/runtime-paseo/src/usage.ts:30 [EXTRACTED]
  ```
  export function readsTokens(tool: PaseoTool): boolean {
  ```
- `sessionUsage` ← packages/runtime-paseo/src/usage.ts:82 [EXTRACTED]
  ```
  export async function sessionUsage({ tool, toolHome, cwd, sessionId, turnSentAt }: { tool: PaseoTool; toolHome: string; cwd: string; sessionId: string; turnSentAt?: number }): Promise<StepUsage | undefined> {
  ```
- `END_OF_WAKE` ← packages/runtime-paseo/src/wake.ts:20 [EXTRACTED]
  ```
  export const END_OF_WAKE = 'When that one attempt is done, or nothing is left to claim, end: take no other work in this agent.';
  ```
- `wakes` ← packages/runtime-paseo/src/wake.ts:48 [EXTRACTED]
  ```
  export function wakes({ ledger, write, fail }: Pick<ProcessState, 'ledger' | 'write' | 'fail'>) {
  ```
- `workspaces` ← packages/runtime-paseo/src/workspace.ts:19 [EXTRACTED]
  ```
  export function workspaces(state: ProcessState, { ensureProvider, conversation }: { ensureProvider: EnsureProvider; conversation: Conversations }) {
  ```
- `RUNTIME_PROTOCOL` ← packages/runtime-protocol/src/protocol.ts:85 [EXTRACTED]
  ```
  export const RUNTIME_PROTOCOL = 1;
  ```
- `EXITED_STDOUT_CHARS` ← packages/runtime-protocol/src/protocol.ts:95 [EXTRACTED]
  ```
  export const EXITED_STDOUT_CHARS = 64 * 1024;
  ```
- `STDOUT_CUT` ← packages/runtime-protocol/src/protocol.ts:98 [EXTRACTED]
  ```
  export const STDOUT_CUT = '[teamai: only the last 64 KiB of stdout follow]\n';
  ```
- `boundedStdout` ← packages/runtime-protocol/src/protocol.ts:101 [EXTRACTED]
  ```
  export function boundedStdout(stdout: string): string {
  ```
- `RUNTIME_MODES` ← packages/runtime-protocol/src/protocol.ts:132 [EXTRACTED]
  ```
  export const RUNTIME_MODES = ['attended', 'unattended', 'recover', 'check'] as const;
  ```
- `OpIdSchema` ← packages/runtime-protocol/src/protocol.ts:137 [EXTRACTED]
  ```
  export const OpIdSchema = z.string().regex(/^op-[0-9a-f]{8,32}$/, 'An operation id looks like op- followed by hex digits').brand<'OpId'>();
  ```
- `RuntimeHandleSchema` ← packages/runtime-protocol/src/protocol.ts:142 [EXTRACTED]
  ```
  export const RuntimeHandleSchema = z.string().min(1).max(256);
  ```
- `CANCEL_FAILED` ← packages/runtime-protocol/src/protocol.ts:161 [EXTRACTED]
  ```
  export const CANCEL_FAILED = 'cancel_failed';
  ```
- `UNAVAILABLE_REASON_MAX` ← packages/runtime-protocol/src/protocol.ts:164 [EXTRACTED]
  ```
  export const UNAVAILABLE_REASON_MAX = 500;
  ```
- `fitReason` ← packages/runtime-protocol/src/protocol.ts:167 [EXTRACTED]
  ```
  export function fitReason(reason: string): string {
  ```
- `RuntimeOptionsSchema` ← packages/runtime-protocol/src/protocol.ts:172 [EXTRACTED]
  ```
  export const RuntimeOptionsSchema = z.record(z.string(), z.json());
  ```
- `PlaceViewSchema` ← packages/runtime-protocol/src/protocol.ts:181 [EXTRACTED]
  ```
  export const PlaceViewSchema = z.object({
  ```
- `RuntimeFailureSchema` ← packages/runtime-protocol/src/protocol.ts:192 [EXTRACTED]
  ```
  export const RuntimeFailureSchema = z.object({ code: z.string().min(1), message: z.string(), key: z.string().optional() });
  ```
- `RuntimeDisplaySchema` ← packages/runtime-protocol/src/protocol.ts:210 [EXTRACTED]
  ```
  export const RuntimeDisplaySchema = z.object({
  ```
- `PromptSessionSchema` ← packages/runtime-protocol/src/protocol.ts:227 [EXTRACTED]
  ```
  export const PromptSessionSchema = z.object({
  ```
- `PromptUsageSchema` ← packages/runtime-protocol/src/protocol.ts:234 [EXTRACTED]
  ```
  export const PromptUsageSchema = z.object({
  ```
- `PromptResultSchema` ← packages/runtime-protocol/src/protocol.ts:244 [EXTRACTED]
  ```
  export const PromptResultSchema = z.object({
  ```
- `PromptLeaseSchema` ← packages/runtime-protocol/src/protocol.ts:255 [EXTRACTED]
  ```
  export const PromptLeaseSchema = z.object({
  ```
- `ISOLATION_LEVELS` ← packages/runtime-protocol/src/protocol.ts:310 [EXTRACTED]
  ```
  export const ISOLATION_LEVELS = ['none', 'worktree', 'sandbox'] as const;
  ```
- `WORKSPACE_MODES` ← packages/runtime-protocol/src/protocol.ts:316 [EXTRACTED]
  ```
  export const WORKSPACE_MODES = ['read-only', 'new', 'continue', 'clone', 'team'] as const;
  ```
- `ConfinedLevelSchema` ← packages/runtime-protocol/src/protocol.ts:319 [EXTRACTED]
  ```
  export const ConfinedLevelSchema = z.enum(CONFINED_LEVELS);
  ```
- `ConfinedOfferSchema` ← packages/runtime-protocol/src/protocol.ts:322 [EXTRACTED]
  ```
  export const ConfinedOfferSchema = z.object({
  ```
- `CanSchema` ← packages/runtime-protocol/src/protocol.ts:354 [EXTRACTED]
  ```
  export const CanSchema = z.object({
  ```
- `InitCredentialsSchema` ← packages/runtime-protocol/src/protocol.ts:387 [EXTRACTED]
  ```
  export const InitCredentialsSchema = z.object({ env: z.array(z.string()), logins: z.array(z.string()) });
  ```
- `InitInstanceSchema` ← packages/runtime-protocol/src/protocol.ts:400 [EXTRACTED]
  ```
  export const InitInstanceSchema = z.object({
  ```
- `InitHomeEnvSchema` ← packages/runtime-protocol/src/protocol.ts:417 [EXTRACTED]
  ```
  export const InitHomeEnvSchema = z.record(z.string().min(1), z.array(z.string().min(1)));
  ```
- `runsCommand` ← packages/runtime-protocol/src/protocol.ts:430 [EXTRACTED]
  ```
  export function runsCommand({ executable, command, expandsHome, platform = process.platform }: { executable: string | undefined; command: string; expandsHome: boolean; platform?: NodeJS.Platform }): boolean {
  ```
- `OpenRequestSchema` ← packages/runtime-protocol/src/protocol.ts:454 [EXTRACTED]
  ```
  export const OpenRequestSchema = z.object({
  ```
- `ExecRequestSchema` ← packages/runtime-protocol/src/protocol.ts:491 [EXTRACTED]
  ```
  export const ExecRequestSchema = z.object({
  ```
- `ConfinedPromptSchema` ← packages/runtime-protocol/src/protocol.ts:513 [EXTRACTED]
  ```
  export const ConfinedPromptSchema = z.object({
  ```
- `PromptRequestSchema` ← packages/runtime-protocol/src/protocol.ts:526 [EXTRACTED]
  ```
  export const PromptRequestSchema = z.object({
  ```
- `WakeRequestSchema` ← packages/runtime-protocol/src/protocol.ts:553 [EXTRACTED]
  ```
  export const WakeRequestSchema = z.object({
  ```
- `WAKE_COMMAND` ← packages/runtime-protocol/src/protocol.ts:573 [EXTRACTED]
  ```
  export const WAKE_COMMAND = 'teamai workflow resume';
  ```
- `RuntimeRequestSchema` ← packages/runtime-protocol/src/protocol.ts:576 [EXTRACTED]
  ```
  export const RuntimeRequestSchema = z.discriminatedUnion('type', [
  ```
- `PROMPT_FAILURE_CODES` ← packages/runtime-protocol/src/protocol.ts:601 [EXTRACTED]
  ```
  export const PROMPT_FAILURE_CODES = ['model_unavailable', 'tool_unavailable', 'agent_unavailable', 'tool_failed', 'usage_limited'] as const;
  ```
- `ConfinedKeptSchema` ← packages/runtime-protocol/src/protocol.ts:604 [EXTRACTED]
  ```
  export const ConfinedKeptSchema = z.object({ level: ConfinedLevelSchema, access: z.enum(ACCESS_LEVELS) });
  ```
- `OpStateSchema` ← packages/runtime-protocol/src/protocol.ts:638 [EXTRACTED]
  ```
  export const OpStateSchema = z.discriminatedUnion('state', [
  ```
- `runtimeMessageSchemas` ← packages/runtime-protocol/src/protocol.ts:654 [EXTRACTED]
  ```
  export function runtimeMessageSchemas<TDisplay extends z.ZodType>({ display }: { display: TDisplay }) {
  ```
- `RuntimeMessageSchema` ← packages/runtime-protocol/src/protocol.ts:750 [EXTRACTED]
  ```
  export const RuntimeMessageSchema = runtimeMessageSchemas({ display: RuntimeDisplaySchema.optional() }).Message;
  ```
- `runtimeStateRoot` ← packages/runtime-protocol/src/state-root.ts:7 [EXTRACTED]
  ```
  export function runtimeStateRoot(home: string): string {
  ```
- `newOpId` ← packages/runtime-protocol/src/step-runtime.ts:18 [EXTRACTED]
  ```
  export function newOpId(): OpId {
  ```
- `isUnansweredFailure` ← packages/runtime-protocol/src/step-runtime.ts:45 [EXTRACTED]
  ```
  export function isUnansweredFailure(failure: RuntimeFailure): boolean {
  ```
- `stub` ← packages/runtime-protocol/src/step-runtime.type-test.ts:8 [EXTRACTED]
  ```
  export const stub = {
  ```
- `op` ← packages/runtime-protocol/src/step-runtime.type-test.ts:27 [EXTRACTED]
  ```
  export const op = newOpId();
  ```
- `placeOf` ← packages/runtime-sandbox/src/attempt-socket.ts:27 [EXTRACTED]
  ```
  export function placeOf(handle: string): string {
  ```
- `SocketRequestSchema` ← packages/runtime-sandbox/src/attempt-socket.ts:39 [EXTRACTED]
  ```
  export const SocketRequestSchema = z.union([
  ```
- `GrantSchema` ← packages/runtime-sandbox/src/attempt-socket.ts:49 [EXTRACTED]
  ```
  export const GrantSchema = z.object({
  ```
- `AnswerSchema` ← packages/runtime-sandbox/src/attempt-socket.ts:59 [EXTRACTED]
  ```
  export const AnswerSchema = z.union([
  ```
- `socketPathOf` ← packages/runtime-sandbox/src/attempt-socket.ts:75 [EXTRACTED]
  ```
  export function socketPathOf({ result, place }: { result: string; place: string }): string {
  ```
- `removeLeftSocket` ← packages/runtime-sandbox/src/attempt-socket.ts:109 [EXTRACTED]
  ```
  export async function removeLeftSocket(socketPath: string): Promise<void> {
  ```
- `listen` ← packages/runtime-sandbox/src/attempt-socket.ts:128 [EXTRACTED]
  ```
  export async function listen(socketPath: string, answer: Answering): Promise<{ ok: true; socket: AttemptSocket } | { ok: false; failure: RuntimeFailure }> {
  ```
- `askSocket` ← packages/runtime-sandbox/src/attempt-socket.ts:284 [EXTRACTED]
  ```
  export function askSocket(socketPath: string, ask: Ask): Promise<Answer | { unreachable: string } | { unreadable: string } | { unsafe: string }> {
  ```
- `TAIL_CHARS` ← packages/runtime-sandbox/src/bounded-tail.ts:9 [EXTRACTED]
  ```
  export const TAIL_CHARS = 64 * 1024;
  ```
- `STDERR_CHARS` ← packages/runtime-sandbox/src/bounded-tail.ts:12 [EXTRACTED]
  ```
  export const STDERR_CHARS = 8000;
  ```
- `boundedTail` ← packages/runtime-sandbox/src/bounded-tail.ts:21 [EXTRACTED]
  ```
  export function boundedTail(max = TAIL_CHARS): BoundedTail {
  ```
- `boundedEnds` ← packages/runtime-sandbox/src/bounded-tail.ts:59 [EXTRACTED]
  ```
  export function boundedEnds({ head, tail }: { head: number; tail: number }): BoundedTail {
  ```
- `BOUND_MS` ← packages/runtime-sandbox/src/deadline.ts:10 [EXTRACTED]
  ```
  export const BOUND_MS = 10_000;
  ```
- `by` ← packages/runtime-sandbox/src/deadline.ts:13 [EXTRACTED]
  ```
  export async function by<T>(deadline: number, work: Promise<T>): Promise<{ kind: 'done'; value: T } | { kind: 'late' }> {
  ```
- `givenCredentials` ← packages/runtime-sandbox/src/exec.ts:92 [EXTRACTED]
  ```
  export function givenCredentials(request: { credentials: Record<string, string>; unset: readonly string[] }, host: Ready['host']): Record<string, string> {
  ```
- `execOperations` ← packages/runtime-sandbox/src/exec.ts:97 [EXTRACTED]
  ```
  export function execOperations({ journal, ledger }: { journal: Journal; ledger: OpLedger }) {
  ```
- `sandboxJournalRoot` ← packages/runtime-sandbox/src/journal-root.ts:8 [EXTRACTED]
  ```
  export function sandboxJournalRoot(home: string): string {
  ```
- `journal` ← packages/runtime-sandbox/src/journal.ts:91 [EXTRACTED]
  ```
  export function journal(root: string) {
  ```
- `EVIDENCE_DIR` ← packages/runtime-sandbox/src/judge.ts:31 [EXTRACTED]
  ```
  export const EVIDENCE_DIR = '/evidence';
  ```
- `FILTER_PORT` ← packages/runtime-sandbox/src/judge.ts:37 [EXTRACTED]
  ```
  export const FILTER_PORT = 3128;
  ```
- `judgeTool` ← packages/runtime-sandbox/src/judge.ts:190 [EXTRACTED]
  ```
  export function judgeTool(tool: string): JudgeTool | undefined {
  ```
- `offersSignedIn` ← packages/runtime-sandbox/src/judge.ts:206 [EXTRACTED]
  ```
  export function offersSignedIn(offers: ConfinedOffer[], names: readonly string[]): ConfinedOffer[] {
  ```
- `inEvidenceDir` ← packages/runtime-sandbox/src/judge.ts:218 [EXTRACTED]
  ```
  export function inEvidenceDir(prompt: string, dir: string): string {
  ```
- `judgeOf` ← packages/runtime-sandbox/src/judge.ts:238 [EXTRACTED]
  ```
  export function judgeOf(tool: string, credentials: Record<string, string>, shell: NodeJS.ProcessEnv): { ok: true; judge: Judge } | { ok: false; failure: RuntimeFailure } {
  ```
- `noJudgeCredential` ← packages/runtime-sandbox/src/judge.ts:264 [EXTRACTED]
  ```
  export function noJudgeCredential(shell: NodeJS.ProcessEnv): RuntimeFailure {
  ```
- `ANY_HOST` ← packages/runtime-sandbox/src/judge.ts:274 [EXTRACTED]
  ```
  export const ANY_HOST = '*';
  ```
- `thisMachineRule` ← packages/runtime-sandbox/src/judge.ts:277 [EXTRACTED]
  ```
  export const thisMachineRule = (address: string): string => `!${address}`;
  ```
- `thisMachineFileRule` ← packages/runtime-sandbox/src/judge.ts:283 [EXTRACTED]
  ```
  export const thisMachineFileRule = (file: string): string => `@${file}`;
  ```
- `FILTER_SCRIPT` ← packages/runtime-sandbox/src/judge.ts:301 [EXTRACTED]
  ```
  export const FILTER_SCRIPT = String.raw`const net = require('node:net'); const http = require('node:http'); const dns = require('node:dns'); const os = require('node:os'); const fs = require('node:fs');
  ```
- `onThisMachine` ← packages/runtime-sandbox/src/loopback.ts:41 [EXTRACTED]
  ```
  export function onThisMachine(credentials: Record<string, string>): OnThisMachine[] {
  ```
- `toAlias` ← packages/runtime-sandbox/src/loopback.ts:58 [EXTRACTED]
  ```
  export function toAlias(credentials: Record<string, string>, alias: string): Record<string, string> {
  ```
- `rewrittenMasks` ← packages/runtime-sandbox/src/loopback.ts:70 [EXTRACTED]
  ```
  export function rewrittenMasks(given: Record<string, string>, sent: Record<string, string>) {
  ```
- `maskedAsGiven` ← packages/runtime-sandbox/src/loopback.ts:75 [EXTRACTED]
  ```
  export function maskedAsGiven(given: Record<string, string>, sent: Record<string, string>) {
  ```
- `inSandbox` ← packages/runtime-sandbox/src/loopback.ts:80 [EXTRACTED]
  ```
  export function inSandbox(credentials: Record<string, string>, host: HostRoute): Record<string, string> {
  ```
- `CONTAINER_ENGINES` ← packages/runtime-sandbox/src/options.ts:35 [EXTRACTED]
  ```
  export const CONTAINER_ENGINES = ['docker', 'podman'] as const;
  ```
- `NATIVE_SANDBOXES` ← packages/runtime-sandbox/src/options.ts:40 [EXTRACTED]
  ```
  export const NATIVE_SANDBOXES = ['seatbelt', 'bwrap'] as const;
  ```
- `parseOptions` ← packages/runtime-sandbox/src/options.ts:181 [EXTRACTED]
  ```
  export function parseOptions(given: RuntimeOptions): { ok: true; options: ParsedOptions } | { ok: false; failure: RuntimeFailure } {
  ```
- `attemptSockets` ← packages/runtime-sandbox/src/outer.ts:22 [EXTRACTED]
  ```
  export function attemptSockets({ journal, readyOf }: { journal: Journal; readyOf: (place: string) => Ready }) {
  ```
- `prompts` ← packages/runtime-sandbox/src/prompt.ts:29 [EXTRACTED]
  ```
  export function prompts({ journal, ledger, env, execs, creation }: {
  ```
- `PROVIDER_COMMANDS` ← packages/runtime-sandbox/src/provider-commands.ts:10 [EXTRACTED]
  ```
  export const PROVIDER_COMMANDS = {
  ```
- `COMMAND_MS` ← packages/runtime-sandbox/src/provider.ts:23 [EXTRACTED]
  ```
  export const COMMAND_MS = 9_000;
  ```
- `RUN_ID` ← packages/runtime-sandbox/src/provider.ts:32 [EXTRACTED]
  ```
  export const RUN_ID = /^r[0-9a-f]{8}(?:[0-9a-f]{8})?$/;
  ```
- `ATTEMPT_ID` ← packages/runtime-sandbox/src/provider.ts:33 [EXTRACTED]
  ```
  export const ATTEMPT_ID = /^a[0-9a-f]{8}$/;
  ```
- `handleOf` ← packages/runtime-sandbox/src/provider.ts:36 [EXTRACTED]
  ```
  export function handleOf({ run, attempt }: PlaceKey): string {
  ```
- `placeKeyOfHandle` ← packages/runtime-sandbox/src/provider.ts:41 [EXTRACTED]
  ```
  export function placeKeyOfHandle(handle: string): PlaceKey | undefined {
  ```
- `journalPrefixOf` ← packages/runtime-sandbox/src/provider.ts:51 [EXTRACTED]
  ```
  export function journalPrefixOf(owner: string): string {
  ```
- `journalSandboxName` ← packages/runtime-sandbox/src/provider.ts:56 [EXTRACTED]
  ```
  export function journalSandboxName(owner: string, { run, attempt }: PlaceKey): string {
  ```
- `journalOfSandboxName` ← packages/runtime-sandbox/src/provider.ts:61 [EXTRACTED]
  ```
  export function journalOfSandboxName(name: string): string | undefined {
  ```
- `placeOfJournalSandbox` ← packages/runtime-sandbox/src/provider.ts:66 [EXTRACTED]
  ```
  export function placeOfJournalSandbox(name: string): { owner: string; key: PlaceKey } | undefined {
  ```
- `unreachable` ← packages/runtime-sandbox/src/provider.ts:79 [EXTRACTED]
  ```
  export function unreachable(failure: RuntimeFailure, family: Provider['family'] = 'copy'): Provider {
  ```
- `HostRouteSchema` ← packages/runtime-sandbox/src/provider.ts:122 [EXTRACTED]
  ```
  export const HostRouteSchema = z.discriminatedUnion('ok', [z.object({ ok: z.literal(true), alias: z.string() }), z.object({ ok: z.literal(false), refusal: z.string() })]);
  ```
- `sandboxOf` ← packages/runtime-sandbox/src/provider.ts:234 [EXTRACTED]
  ```
  export async function sandboxOf(place: PlaceKey & { id?: string }, provider: Provider): ReturnType<Provider['find']> {
  ```
- `copies` ← packages/runtime-sandbox/src/provider.type-test.ts:12 [EXTRACTED]
  ```
  export const copies = (provider: Copy): Provider => provider;
  ```
- `uncollected` ← packages/runtime-sandbox/src/provider.type-test.ts:15 [EXTRACTED]
  ```
  export const uncollected = (provider: Omit<Copy, 'collect'>): Provider => provider;
  ```
- `binds` ← packages/runtime-sandbox/src/provider.type-test.ts:18 [EXTRACTED]
  ```
  export const binds = (provider: Bind): Provider => provider;
  ```
- `bindCollects` ← packages/runtime-sandbox/src/provider.type-test.ts:21 [EXTRACTED]
  ```
  export const bindCollects = (provider: Omit<Bind, 'collect'> & { collect: Copy['collect'] }): Provider => provider;
  ```
- `serve` ← packages/runtime-sandbox/src/runtime.ts:123 [EXTRACTED]
  ```
  export function serve({ input, write: send, journal, warn, provider: providerFor, env }: RuntimeDeps): Promise<number> {
  ```
- `SIGN_IN` ← packages/runtime-sandbox/src/sign-in.ts:54 [EXTRACTED]
  ```
  export const SIGN_IN = {
  ```
- `isGivenSignIn` ← packages/runtime-sandbox/src/sign-in.ts:103 [EXTRACTED]
  ```
  export function isGivenSignIn(tool: string, credentials: InitCredentials, login: string = tool): boolean {
  ```
- `offerSignedIn` ← packages/runtime-sandbox/src/sign-in.ts:142 [EXTRACTED]
  ```
  export function offerSignedIn({ tools, provider, credentials, stored, env = {}, instances, missing }: {
  ```
- `stepToolOf` ← packages/runtime-sandbox/src/step.ts:38 [EXTRACTED]
  ```
  export function stepToolOf(tool: string): { family: StepFamily; step: StepLaunch } | undefined {
  ```
- `sandboxProcess` ← packages/runtime-sandbox/src/step.ts:62 [EXTRACTED]
  ```
  export function sandboxProcess(provider: Provider, id: string, unset: string[]) {
  ```
- `runStep` ← packages/runtime-sandbox/src/step.ts:203 [EXTRACTED]
  ```
  export async function runStep({ request, tool, command, provider, id, env, masks }: {
  ```
- `sweep` ← packages/runtime-sandbox/src/sweep.ts:28 [EXTRACTED]
  ```
  export async function sweep({ provider, journal, warn }: { provider: Provider; journal: Journal; warn: (line: string) => void }): Promise<void> {
  ```
- `SYSTEM_BIN` ← packages/runtime-sandbox/src/this-machine.ts:8 [EXTRACTED]
  ```
  export const SYSTEM_BIN = '/usr/bin';
  ```
- `OS_RELEASE` ← packages/runtime-sandbox/src/this-machine.ts:14 [EXTRACTED]
  ```
  export const OS_RELEASE = ['/etc/os-release', '/usr/lib/os-release'];
  ```
- `WARM_REPOSITORY` ← packages/runtime-sandbox/src/warm.ts:32 [EXTRACTED]
  ```
  export const WARM_REPOSITORY = 'teamai-warm';
  ```
- `WARM_BY` ← packages/runtime-sandbox/src/warm.ts:38 [EXTRACTED]
  ```
  export const WARM_BY = `${os.hostname()}:${process.pid}`;
  ```
- `isLeftBehind` ← packages/runtime-sandbox/src/warm.ts:41 [EXTRACTED]
  ```
  export function isLeftBehind(by: string): boolean {
  ```
- `removeLeftScratch` ← packages/runtime-sandbox/src/warm.ts:51 [EXTRACTED]
  ```
  export function removeLeftScratch(): void {
  ```
- `warmFailed` ← packages/runtime-sandbox/src/warm.ts:85 [EXTRACTED]
  ```
  export function warmFailed(what: string, ran: Ran) {
  ```
- `planWarm` ← packages/runtime-sandbox/src/warm.ts:135 [EXTRACTED]
  ```
  export function planWarm({ base, recipe, checkout, profile }: { base: string; recipe: WarmOptions; checkout: string; profile?: ProfileOption }): { ok: true; plan: WarmPlan } | { ok: false; failure: RuntimeFailure } {
  ```
- `scratchOf` ← packages/runtime-sandbox/src/warm.ts:188 [EXTRACTED]
  ```
  export function scratchOf(cache: WarmPlan['cache']) {
  ```
- `savedWarm` ← packages/runtime-sandbox/src/warm.ts:209 [EXTRACTED]
  ```
  export function savedWarm(dir: string) {
  ```
- `oneBuildPerKey` ← packages/runtime-sandbox/src/warm.ts:228 [EXTRACTED]
  ```
  export function oneBuildPerKey<T>(): (key: string, build: () => Promise<T>) => Promise<T> {
  ```
- `toolExec` ← packages/runtime-sandbox/src/wrapper.ts:76 [EXTRACTED]
  ```
  export async function toolExec({ name, args, env, cwd, journal }: { name: string; args: readonly string[]; env: NodeJS.ProcessEnv; cwd: string; journal: Journal }): Promise<WrapperEnd> {
  ```
- `isInstanceId` ← packages/runtime-t3/src/add-instance.ts:59 [EXTRACTED]
  ```
  export function isInstanceId(id: string): boolean {
  ```
- `findProviderInstance` ← packages/runtime-t3/src/add-instance.ts:86 [EXTRACTED]
  ```
  export function findProviderInstance({ settings, instance, userHome }: { settings: z.infer<typeof SettingsSchema>; instance: NewInstance; userHome: string }): string | undefined {
  ```
- `addProviderInstance` ← packages/runtime-t3/src/add-instance.ts:226 [EXTRACTED]
  ```
  export async function addProviderInstance({ t3Home, lockFile, userHome, instance }: {
  ```
- `addedProjects` ← packages/runtime-t3/src/added-projects.ts:31 [EXTRACTED]
  ```
  export function addedProjects(file: string): AddedProjects {
  ```
- `validToken` ← packages/runtime-t3/src/auth.ts:99 [EXTRACTED]
  ```
  export function validToken(stateDir: string, resource: string, access: SignInAccess, now = Date.now()): OAuthTokens | undefined {
  ```
- `signInOf` ← packages/runtime-t3/src/auth.ts:109 [EXTRACTED]
  ```
  export function signInOf(stateDir: string, resource: string): string | undefined {
  ```
- `attendedSignIn` ← packages/runtime-t3/src/auth.ts:169 [EXTRACTED]
  ```
  export async function attendedSignIn({ stateDir, resource, access, silentFailure, say }: { stateDir: string; resource: string; access: SignInAccess; silentFailure?: string; say(message: string): void }): Promise<SignIn> {
  ```
- `signInSilently` ← packages/runtime-t3/src/auth.ts:302 [EXTRACTED]
  ```
  export async function signInSilently({ stateDir, resource, t3Home, t3Cli, access }: { stateDir: string; resource: URL; t3Home: string; t3Cli: T3Command; access: SignInAccess }): Promise<SilentSignIn> {
  ```
- `unattendedAuth` ← packages/runtime-t3/src/auth.ts:329 [EXTRACTED]
  ```
  export function unattendedAuth(stateDir: string, resource: string, access: SignInAccess): OAuthClientProvider {
  ```
- `STOP_WAIT_MS` ← packages/runtime-t3/src/conversation.ts:42 [EXTRACTED]
  ```
  export const STOP_WAIT_MS = 10_000;
  ```
- `tasksOf` ← packages/runtime-t3/src/conversation.ts:63 [EXTRACTED]
  ```
  export function tasksOf(listed: ListedThread[], threadId: string): ListedThread[] {
  ```
- `threadLink` ← packages/runtime-t3/src/conversation.ts:166 [EXTRACTED]
  ```
  export function threadLink(environment: Environment, threadId: string): string {
  ```
- `threadDisplay` ← packages/runtime-t3/src/conversation.ts:176 [EXTRACTED]
  ```
  export function threadDisplay(thread: ThreadRecord, environment: Environment): RuntimeDisplay {
  ```
- `endedIn` ← packages/runtime-t3/src/conversation.ts:235 [EXTRACTED]
  ```
  export function endedIn(conversation: OpRecord): OpRecord {
  ```
- `whyNotStopped` ← packages/runtime-t3/src/conversation.ts:245 [EXTRACTED]
  ```
  export async function whyNotStopped(t3: T3, thread: Pick<ThreadRecord, 'threadId' | 'turnOf'>, deadline: number): Promise<string | undefined> {
  ```
- `stillRuns` ← packages/runtime-t3/src/conversation.ts:301 [EXTRACTED]
  ```
  export function stillRuns(s: Reached, thread: ThreadRecord, why: string): string {
  ```
- `conversations` ← packages/runtime-t3/src/conversation.ts:334 [EXTRACTED]
  ```
  export function conversations({ serving, adder }: { serving: Serving; adder: InstanceAdder }) {
  ```
- `T3_COMMAND` ← packages/runtime-t3/src/host-commands.ts:2 [EXTRACTED]
  ```
  export const T3_COMMAND = 't3';
  ```
- `instanceAdder` ← packages/runtime-t3/src/instances.ts:31 [EXTRACTED]
  ```
  export function instanceAdder({ options, notice }: { options: ServeOptions; notice: Serving['notice'] }) {
  ```
- `journal` ← packages/runtime-t3/src/journal.ts:189 [EXTRACTED]
  ```
  export function journal(dir: string): Journal {
  ```
- `unreadableFailure` ← packages/runtime-t3/src/journal.ts:263 [EXTRACTED]
  ```
  export function unreadableFailure(handle: string, read: Extract<PlaceRead, { kind: 'unreadable' }>): RuntimeFailure {
  ```
- `JudgeCopyFailed` ← packages/runtime-t3/src/judge.ts:76 [EXTRACTED]
  ```
  export class JudgeCopyFailed extends Error {}
  ```
- `JudgeReleased` ← packages/runtime-t3/src/judge.ts:79 [EXTRACTED]
  ```
  export class JudgeReleased extends Error {}
  ```
- `judged` ← packages/runtime-t3/src/judge.ts:93 [EXTRACTED]
  ```
  export async function judged(t3: T3, thread: ThreadRecord): Promise<{ ok: true; result: PromptResult } | { ok: false; why: string }> {
  ```
- `launchJudge` ← packages/runtime-t3/src/judge.ts:132 [EXTRACTED]
  ```
  export async function launchJudge({ t3, request, confined, opened, journalThread, thread, known, isReleased, linkOf }: {
  ```
- `removeCopies` ← packages/runtime-t3/src/judge.ts:172 [EXTRACTED]
  ```
  export function removeCopies(known: PlaceRecord | undefined): void {
  ```
- `offer` ← packages/runtime-t3/src/offer.ts:87 [EXTRACTED]
  ```
  export function offer({ serving, adder, start, recover }: { serving: Serving; adder: InstanceAdder; start(session: Session): void; recover(): void }): (request: Extract<RuntimeRequest, { type: 'init' }>) => Promise<void> {
  ```
- `parseOptions` ← packages/runtime-t3/src/options.ts:40 [EXTRACTED]
  ```
  export function parseOptions(raw: RuntimeOptions): { ok: true; options: T3Options } | { ok: false; failure: RuntimeFailure } {
  ```
- `projectAt` ← packages/runtime-t3/src/place.ts:51 [EXTRACTED]
  ```
  export async function projectAt(t3: T3, dir: string): Promise<Project | undefined> {
  ```
- `handleFor` ← packages/runtime-t3/src/place.ts:77 [EXTRACTED]
  ```
  export function handleFor({ run, attempt }: { run: string; attempt: string }): string {
  ```
- `placeHandlers` ← packages/runtime-t3/src/place.ts:82 [EXTRACTED]
  ```
  export function placeHandlers({ serving, adder, conversations }: { serving: Serving; adder: InstanceAdder; conversations: Conversations }) {
  ```
- `serve` ← packages/runtime-t3/src/runtime.ts:142 [EXTRACTED]
  ```
  export function serve(options: ServeOptions): Promise<number> {
  ```
- `DRIVERS` ← packages/runtime-t3/src/sessions.ts:26 [EXTRACTED]
  ```
  export const DRIVERS = {
  ```
- `driverOf` ← packages/runtime-t3/src/sessions.ts:51 [EXTRACTED]
  ```
  export function driverOf(tool: string): Driver | undefined {
  ```
- `toolOf` ← packages/runtime-t3/src/sessions.ts:56 [EXTRACTED]
  ```
  export function toolOf(driver: string): ToolId | undefined {
  ```
- `CLOCK_SLACK_MS` ← packages/runtime-t3/src/sessions.ts:61 [EXTRACTED]
  ```
  export const CLOCK_SLACK_MS = 5_000;
  ```
- `canListStore` ← packages/runtime-t3/src/sessions.ts:64 [EXTRACTED]
  ```
  export function canListStore(driver: Driver, toolHome: string): boolean {
  ```
- `isDefaultToolHome` ← packages/runtime-t3/src/sessions.ts:69 [EXTRACTED]
  ```
  export function isDefaultToolHome(driver: Driver, toolHome: string): boolean {
  ```
- `sessionSince` ← packages/runtime-t3/src/sessions.ts:92 [EXTRACTED]
  ```
  export async function sessionSince({ driver, toolHome, cwd, since, other }: { driver: Driver; toolHome: string; cwd: string; since: number; other?: string }): Promise<SessionLookup> {
  ```
- `ScriptSchema` ← packages/runtime-t3/src/settings.ts:26 [EXTRACTED]
  ```
  export const ScriptSchema = z.object({ name: z.string(), runOnWorktreeCreate: z.boolean().optional(), runOnSettle: z.boolean().optional() });
  ```
- `SettingsSchema` ← packages/runtime-t3/src/settings.ts:41 [EXTRACTED]
  ```
  export const SettingsSchema = z.object({
  ```
- `readSettings` ← packages/runtime-t3/src/settings.ts:75 [EXTRACTED]
  ```
  export function readSettings(t3Home: string): Read {
  ```
- `instanceToolHome` ← packages/runtime-t3/src/settings.ts:90 [EXTRACTED]
  ```
  export function instanceToolHome(settings: Read, { instanceId, driver, userHome }: { instanceId: string; driver: Driver; userHome: string }): string {
  ```
- `homePathOf` ← packages/runtime-t3/src/settings.ts:100 [EXTRACTED]
  ```
  export function homePathOf(homePath: string, userHome: string): string {
  ```
- `projectSettings` ← packages/runtime-t3/src/settings.ts:105 [EXTRACTED]
  ```
  export function projectSettings(settings: Read, project: { id: string; scripts?: ProjectScript[] | undefined } | undefined): ProjectSettings {
  ```
- `t3HomeOf` ← packages/runtime-t3/src/t3-command.ts:14 [EXTRACTED]
  ```
  export function t3HomeOf(env: NodeJS.ProcessEnv, userHome: string): string {
  ```
- `t3UserHomeOf` ← packages/runtime-t3/src/t3-command.ts:32 [EXTRACTED]
  ```
  export function t3UserHomeOf(t3Home: string, userHome: string): string {
  ```
- `t3Command` ← packages/runtime-t3/src/t3-command.ts:48 [EXTRACTED]
  ```
  export function t3Command(env: NodeJS.ProcessEnv, t3Home: string): T3Command {
  ```
- `EnvironmentSchema` ← packages/runtime-t3/src/t3.ts:14 [EXTRACTED]
  ```
  export const EnvironmentSchema = z.object({ environmentId: z.string().min(1), label: z.string(), serverVersion: z.string().optional() });
  ```
- `OLDEST_T3` ← packages/runtime-t3/src/t3.ts:19 [EXTRACTED]
  ```
  export const OLDEST_T3 = '0.1.8';
  ```
- `tooOld` ← packages/runtime-t3/src/t3.ts:22 [EXTRACTED]
  ```
  export function tooOld({ serverVersion }: Environment): string | undefined {
  ```
- `THREAD_STATUSES` ← packages/runtime-t3/src/t3.ts:66 [EXTRACTED]
  ```
  export const THREAD_STATUSES = ['idle', 'preparing', 'queued', 'starting', 'running', 'waiting', 'completed', 'interrupted', 'failed', 'cancelled', 'rolled_back'] as const;
  ```
- `ACTIVE_STATUSES` ← packages/runtime-t3/src/t3.ts:104 [EXTRACTED]
  ```
  export const ACTIVE_STATUSES = ['preparing', 'queued', 'starting', 'running', 'waiting'] as const;
  ```
- `isActive` ← packages/runtime-t3/src/t3.ts:107 [EXTRACTED]
  ```
  export function isActive(status: string | null): boolean {
  ```
- `USAGE_LIMIT_TITLE` ← packages/runtime-t3/src/t3.ts:133 [EXTRACTED]
  ```
  export const USAGE_LIMIT_TITLE = 'Usage limit reached';
  ```
- `STEP_MODES` ← packages/runtime-t3/src/t3.ts:143 [EXTRACTED]
  ```
  export const STEP_MODES = ['full-access', 'auto', 'auto-accept-edits', 'approval-required'] as const;
  ```
- `T3Error` ← packages/runtime-t3/src/t3.ts:185 [EXTRACTED]
  ```
  export class T3Error extends Error {
  ```
- `connectT3` ← packages/runtime-t3/src/t3.ts:400 [EXTRACTED]
  ```
  export async function connectT3(resource: URL, auth: OAuthClientProvider, authorize: () => Promise<string>): Promise<T3> {
  ```
- `runsOwnBinary` ← packages/runtime-t3/src/tool-instances.ts:22 [EXTRACTED]
  ```
  export function runsOwnBinary(binaryPath: string | undefined, driver: Driver): boolean {
  ```
- `servedInstances` ← packages/runtime-t3/src/tool-instances.ts:60 [EXTRACTED]
  ```
  export function servedInstances({ instances, mapped, lookup, homeEnv }: { instances: ServedTool[]; mapped: Record<string, string> | undefined; lookup: InstanceLookup; homeEnv: InitHomeEnv }): ServedInstances {
  ```
- `driverOfProvider` ← packages/runtime-t3/src/tool-instances.ts:164 [EXTRACTED]
  ```
  export function driverOfProvider(provider: Provider): Driver | undefined {
  ```
- `teamaiToolHome` ← packages/runtime-t3/src/tool-instances.ts:173 [EXTRACTED]
  ```
  export function teamaiToolHome({ instance, driver, home, homeEnv, env, cwd }: { instance: ServedTool; driver: Driver; home: string; homeEnv: readonly string[]; env: Readonly<Record<string, string | undefined>>; cwd: string }): string {
  ```
- `tilde` ← packages/runtime-t3/src/tool-instances.ts:185 [EXTRACTED]
  ```
  export function tilde(file: string, home: string): string {
  ```
- `END_OF_WAKE` ← packages/runtime-t3/src/wake.ts:19 [EXTRACTED]
  ```
  export const END_OF_WAKE = 'When that one attempt is done, or nothing is left to claim, end: take no other work in this thread.';
  ```
- `canWake` ← packages/runtime-t3/src/wake.ts:71 [EXTRACTED]
  ```
  export async function canWake(t3: T3): Promise<boolean> {
  ```
- `wakes` ← packages/runtime-t3/src/wake.ts:118 [EXTRACTED]
  ```
  export function wakes({ serving }: { serving: Serving }) {
  ```
- `within` ← packages/runtime-t3/src/within.ts:4 [EXTRACTED]
  ```
  export async function within<TValue>(promise: Promise<TValue>, ms: number): Promise<{ answered: true; value: TValue } | { answered: false }> {
  ```
- `sleep` ← packages/runtime-t3/src/within.ts:15 [EXTRACTED]
  ```
  export function sleep(ms: number): Promise<void> {
  ```
- `bundleRuntime` ← packages/runtime-testing/src/bundle.ts:15 [EXTRACTED]
  ```
  export async function bundleRuntime({ entry, outfile, alias, plugins }: { entry: string; outfile: string } & Pick<BuildOptions, 'alias' | 'plugins'>): Promise<string> {
  ```
- `bundleOnce` ← packages/runtime-testing/src/bundle.ts:43 [EXTRACTED]
  ```
  export function bundleOnce(entry: string): Promise<string> {
  ```
- `connectRuntime` ← packages/runtime-testing/src/connect.ts:28 [EXTRACTED]
  ```
  export function connectRuntime({ executable, env, cwd }: { executable: string; env: Record<string, string>; cwd?: string }): Connection {
  ```
- `processesUnder` ← packages/runtime-testing/src/leaks.ts:14 [EXTRACTED]
  ```
  export function processesUnder(dir: string): string[] {
  ```
- `expectNothingLeft` ← packages/runtime-testing/src/leaks.ts:67 [EXTRACTED]
  ```
  export async function expectNothingLeft({ dir, connections = [], left = () => [] }: { dir: string; connections?: readonly Connection[]; left?: () => string[] }): Promise<void> {
  ```
- `answerLaunch` ← packages/runtime-tools/src/answer.ts:9 [EXTRACTED]
  ```
  export function answerLaunch({ tool, prompt, session, timeoutMs, idleTimeoutMs, signal, cwd, env, host }: {
  ```
- `confinedIsolation` ← packages/runtime-tools/src/confined.ts:113 [EXTRACTED]
  ```
  export async function confinedIsolation({ profile, family, version, dir }: { profile: ConfinedLaunch; family: ConfinedFamily; version: string; dir: string }): Promise<ConfinedLevel> {
  ```
- `runConfined` ← packages/runtime-tools/src/confined.ts:494 [EXTRACTED]
  ```
  export async function runConfined(request: ConfinedRequest, deps: ConfinedDeps): Promise<ConfinedEnd> {
  ```
- `spawnHeadless` ← packages/runtime-tools/src/headless.ts:11 [EXTRACTED]
  ```
  export function spawnHeadless(input: { executable: string; args: string[]; cwd: string; env: NodeJS.ProcessEnv; detached: boolean; group?: string }): HeadlessStarter {
  ```
- `runTool` ← packages/runtime-tools/src/headless.ts:38 [EXTRACTED]
  ```
  export async function runTool(input: { executable: string; args: string[]; cwd: string; env: NodeJS.ProcessEnv; stdin: string; timeoutMs: number; idleTimeoutMs?: number; detached: boolean; group?: string; signal?: AbortSignal }): Promise<HeadlessRun> {
  ```
- `hostProcess` ← packages/runtime-tools/src/step.ts:46 [EXTRACTED]
  ```
  export function hostProcess(spawnTool: ToolSpawn = spawnCommand): ToolLauncher {
  ```
- `stepLauncher` ← packages/runtime-tools/src/step.ts:99 [EXTRACTED]
  ```
  export function stepLauncher(deps: StepLaunchDeps, {
  ```
- `CLI_DETECT_TIMEOUT_MS` ← packages/shared/src/cli-path.ts:14 [EXTRACTED]
  ```
  export const CLI_DETECT_TIMEOUT_MS = 5_000;
  ```
- `pickWindowsCommand` ← packages/shared/src/cli-path.ts:27 [EXTRACTED]
  ```
  export function pickWindowsCommand(whereOutput: string): string | null {
  ```
- `resolveCliPath` ← packages/shared/src/cli-path.ts:132 [EXTRACTED]
  ```
  export function resolveCliPath(
  ```
- `isBareCommandName` ← packages/shared/src/cli-path.ts:143 [EXTRACTED]
  ```
  export function isBareCommandName(cmd: string): boolean {
  ```
- `resolvePathCommand` ← packages/shared/src/cli-path.ts:152 [EXTRACTED]
  ```
  export function resolvePathCommand(cmd: string, platform: NodeJS.Platform = process.platform): string | null {
  ```
- `MAX_LOG_BYTES` ← packages/shared/src/debug-log.ts:18 [EXTRACTED]
  ```
  export const MAX_LOG_BYTES = 5 * 1024 * 1024; // 5 MB
  ```
- `writeToFile` ← packages/shared/src/debug-log.ts:89 [EXTRACTED]
  ```
  export function writeToFile(level: 'DEBUG' | 'WARN' | 'ERROR', msg: string): void {
  ```
- `_setLogFilePath` ← packages/shared/src/debug-log.ts:109 [EXTRACTED]
  ```
  export function _setLogFilePath(p: string): void {
  ```
- `_resetState` ← packages/shared/src/debug-log.ts:116 [EXTRACTED]
  ```
  export function _resetState(): void {
  ```
- `entriesUnder` ← packages/shared/src/entries-under.ts:10 [EXTRACTED]
  ```
  export function entriesUnder(dir: string): Array<{ relative: string; entry: fs.Dirent }> {
  ```
- `probeBinary` ← packages/shared/src/exec.ts:102 [EXTRACTED]
  ```
  export async function probeBinary(
  ```
- `probeVersion` ← packages/shared/src/exec.ts:122 [EXTRACTED]
  ```
  export async function probeVersion(
  ```
- `formatCommand` ← packages/shared/src/exec.ts:150 [EXTRACTED]
  ```
  export function formatCommand(command: string, args: string[]): string {
  ```
- `captureTail` ← packages/shared/src/exec.ts:165 [EXTRACTED]
  ```
  export function captureTail(child: ChildProcess, maxChars: number): () => string {
  ```
- `detachPipe` ← packages/shared/src/exec.ts:191 [EXTRACTED]
  ```
  export function detachPipe(stream: Readable): void {
  ```
- `detachChild` ← packages/shared/src/exec.ts:204 [EXTRACTED]
  ```
  export function detachChild(child: ChildProcess): void {
  ```
- `batchLaunchOf` ← packages/shared/src/exec.ts:238 [EXTRACTED]
  ```
  export function batchLaunchOf(executable: string, args: readonly string[], comspec: string): BatchLaunch | undefined {
  ```
- `spawnCommand` ← packages/shared/src/exec.ts:287 [EXTRACTED]
  ```
  export function spawnCommand(executable: string, args: readonly string[], options: SpawnOptions): ChildProcess {
  ```
- `spawnCommandSync` ← packages/shared/src/exec.ts:299 [EXTRACTED]
  ```
  export function spawnCommandSync(executable: string, args: readonly string[], options: SpawnSyncOptions): SpawnSyncReturns<string | Buffer> {
  ```
- `FsFailureSchema` ← packages/shared/src/fs-failure.ts:8 [EXTRACTED]
  ```
  export const FsFailureSchema = z.object({
  ```
- `isMissing` ← packages/shared/src/fs-failure.ts:17 [EXTRACTED]
  ```
  export function isMissing({ code }: FsFailure): boolean {
  ```
- `isPermissionDenied` ← packages/shared/src/fs-failure.ts:22 [EXTRACTED]
  ```
  export function isPermissionDenied({ code }: FsFailure): boolean {
  ```
- `cannotReadBecause` ← packages/shared/src/fs-failure.ts:27 [EXTRACTED]
  ```
  export function cannotReadBecause(failure: FsFailure): string {
  ```
- `canList` ← packages/shared/src/fs-failure.ts:35 [EXTRACTED]
  ```
  export function canList(folder: string): boolean {
  ```
- `normalizeHomePath` ← packages/shared/src/home.ts:16 [EXTRACTED]
  ```
  export function normalizeHomePath(home: string): string {
  ```
- `getUserHome` ← packages/shared/src/home.ts:42 [EXTRACTED]
  ```
  export function getUserHome(): string {
  ```
- `useInstallHome` ← packages/shared/src/home.ts:52 [EXTRACTED]
  ```
  export function useInstallHome(home: string): void {
  ```
- `usesInstallHome` ← packages/shared/src/home.ts:57 [EXTRACTED]
  ```
  export function usesInstallHome(): boolean {
  ```
- `memberHome` ← packages/shared/src/home.ts:62 [EXTRACTED]
  ```
  export function memberHome(): string {
  ```
- `legacyUserHome` ← packages/shared/src/home.ts:86 [EXTRACTED]
  ```
  export function legacyUserHome(): string | null {
  ```
- `expandHome` ← packages/shared/src/home.ts:112 [EXTRACTED]
  ```
  export function expandHome(p: string): string {
  ```
- `JsonValueSchema` ← packages/shared/src/json.ts:4 [EXTRACTED]
  ```
  export const JsonValueSchema = z.json();
  ```
- `JsonObjectSchema` ← packages/shared/src/json.ts:12 [EXTRACTED]
  ```
  export const JsonObjectSchema = z.record(z.string(), JsonValueSchema) satisfies z.ZodType<JsonObject>;
  ```
- `isJsonObject` ← packages/shared/src/json.ts:22 [EXTRACTED]
  ```
  export function isJsonObject(value: unknown): value is JsonObject {
  ```
- `parseJson` ← packages/shared/src/json.ts:33 [EXTRACTED]
  ```
  export function parseJson(text: string): JsonValue {
  ```
- `mapStrings` ← packages/shared/src/json.ts:49 [EXTRACTED]
  ```
  export function mapStrings(value: JsonValue, rewrite: (text: string) => string): JsonValue {
  ```
- `lenientList` ← packages/shared/src/json.ts:59 [EXTRACTED]
  ```
  export function lenientList<T>(element: z.ZodType<T>) {
  ```
- `setVerbose` ← packages/shared/src/log.ts:11 [EXTRACTED]
  ```
  export function setVerbose(v: boolean): void {
  ```
- `setSilent` ← packages/shared/src/log.ts:15 [EXTRACTED]
  ```
  export function setSilent(s: boolean): void {
  ```
- `isSilent` ← packages/shared/src/log.ts:19 [EXTRACTED]
  ```
  export function isSilent(): boolean {
  ```
- `setStderrOnly` ← packages/shared/src/log.ts:28 [EXTRACTED]
  ```
  export function setStderrOnly(s: boolean): boolean {
  ```
- `streamOfLine` ← packages/shared/src/log.ts:45 [EXTRACTED]
  ```
  export function streamOfLine(line: string): { stream: 'stdout' | 'stderr'; text: string } {
  ```
- `withoutStreamMarks` ← packages/shared/src/log.ts:50 [EXTRACTED]
  ```
  export function withoutStreamMarks(text: string): string {
  ```
- `writeInfoLine` ← packages/shared/src/log.ts:55 [EXTRACTED]
  ```
  export function writeInfoLine(line: string): void {
  ```
- `log` ← packages/shared/src/log.ts:65 [EXTRACTED]
  ```
  export const log = {
  ```
- `spinner` ← packages/shared/src/log.ts:106 [EXTRACTED]
  ```
  export async function spinner(text: string): Promise<Ora> {
  ```
- `WIN_EXEC_EXTENSIONS` ← packages/shared/src/lookpath.ts:28 [EXTRACTED]
  ```
  export const WIN_EXEC_EXTENSIONS = ['.exe', '.cmd', '.bat'] as const;
  ```
- `SAFE_BIN_RE` ← packages/shared/src/lookpath.ts:31 [EXTRACTED]
  ```
  export const SAFE_BIN_RE = /^[A-Za-z0-9][A-Za-z0-9._-]*$/;
  ```
- `pathDirs` ← packages/shared/src/lookpath.ts:85 [EXTRACTED]
  ```
  export function pathDirs(options: LookPathOptions = {}): string[] {
  ```
- `isOnPath` ← packages/shared/src/lookpath.ts:98 [EXTRACTED]
  ```
  export function isOnPath(bin: string, options: LookPathOptions = {}): boolean {
  ```
- `findOnPath` ← packages/shared/src/lookpath.ts:103 [EXTRACTED]
  ```
  export function findOnPath(bin: string, options: LookPathOptions = {}): string | null {
  ```
- `PROCESS_READ_CHANNEL` ← packages/shared/src/process-group.ts:25 [EXTRACTED]
  ```
  export const PROCESS_READ_CHANNEL = 'teamai:process-read';
  ```
- `tellProcessRead` ← packages/shared/src/process-group.ts:33 [EXTRACTED]
  ```
  export function tellProcessRead(read: ProcessRead): void {
  ```
- `ProcessIdentitySchema` ← packages/shared/src/process-group.ts:197 [EXTRACTED]
  ```
  export const ProcessIdentitySchema = z.object({
  ```
- `isSameProcess` ← packages/shared/src/process-group.ts:274 [EXTRACTED]
  ```
  export async function isSameProcess(recorded: ProcessIdentity, { signal }: { signal?: AbortSignal } = {}): Promise<ProcessVerdict> {
  ```
- `identityOf` ← packages/shared/src/process-group.ts:294 [EXTRACTED]
  ```
  export async function identityOf(pid: number): Promise<ProcessIdentity> {
  ```
- `recordGroup` ← packages/shared/src/process-group.ts:342 [EXTRACTED]
  ```
  export function recordGroup(child: ChildProcess, dir: string, { isAttached = false }: { isAttached?: boolean } = {}): void {
  ```
- `ownGroups` ← packages/shared/src/process-group.ts:392 [EXTRACTED]
  ```
  export async function ownGroups(): Promise<OwnGroups | undefined> {
  ```
- `stopRecordedGroup` ← packages/shared/src/process-group.ts:444 [EXTRACTED]
  ```
  export async function stopRecordedGroup(dir: string): Promise<number[]> {
  ```
- `signalPid` ← packages/shared/src/process-group.ts:530 [EXTRACTED]
  ```
  export function signalPid(pid: number, name: NodeJS.Signals | 0): SignalOutcome {
  ```
- `signalChild` ← packages/shared/src/process-group.ts:539 [EXTRACTED]
  ```
  export function signalChild(child: Pick<ChildProcess, 'pid' | 'kill'>, name: Parameters<ChildProcess['kill']>[0] = 'SIGTERM'): SignalOutcome {
  ```
- `mayBeRunning` ← packages/shared/src/process-group.ts:549 [EXTRACTED]
  ```
  export function mayBeRunning(pid: number): boolean {
  ```
- `signalGroup` ← packages/shared/src/process-group.ts:554 [EXTRACTED]
  ```
  export function signalGroup(pgid: number, name: NodeJS.Signals | 0): SignalOutcome {
  ```
- `stopGroup` ← packages/shared/src/process-group.ts:564 [EXTRACTED]
  ```
  export async function stopGroup(group: Recorded): Promise<boolean> {
  ```
- `descendantsOf` ← packages/shared/src/process-group.ts:652 [EXTRACTED]
  ```
  export async function descendantsOf(pid: number): Promise<FoundProcess[]> {
  ```
- `signalStillRunning` ← packages/shared/src/process-group.ts:742 [EXTRACTED]
  ```
  export async function signalStillRunning(found: readonly FoundProcess[], name: NodeJS.Signals | 0): Promise<boolean | undefined> {
  ```
- `STOP_GRACE_MS` ← packages/shared/src/process-group.ts:749 [EXTRACTED]
  ```
  export const STOP_GRACE_MS = 5_000;
  ```
- `TREE_KILL_FLAGS` ← packages/shared/src/process-group.ts:752 [EXTRACTED]
  ```
  export const TREE_KILL_FLAGS = ['/T', '/F'] as const;
  ```
- `stopProcess` ← packages/shared/src/process-group.ts:755 [EXTRACTED]
  ```
  export function stopProcess<T>(child: ChildProcess, exit: Promise<T>, detached: boolean): (signal?: NodeJS.Signals) => Promise<T> {
  ```
- `sanitizeGitUrl` ← packages/shared/src/redact.ts:40 [EXTRACTED]
  ```
  export function sanitizeGitUrl(text: string): string {
  ```
- `redactGitCredentials` ← packages/shared/src/redact.ts:45 [EXTRACTED]
  ```
  export function redactGitCredentials(text: string, secrets: readonly string[] = []): string {
  ```
- `MIN_DECLARED_SECRET_LENGTH` ← packages/shared/src/redact.ts:65 [EXTRACTED]
  ```
  export const MIN_DECLARED_SECRET_LENGTH = 4;
  ```
- `collectEnvSecrets` ← packages/shared/src/redact.ts:129 [EXTRACTED]
  ```
  export function collectEnvSecrets(env: NodeJS.ProcessEnv = process.env) {
  ```
- `redact` ← packages/shared/src/redact.ts:150 [EXTRACTED]
  ```
  export function redact(text: string, options: RedactOptions = {}): string {
  ```
- `redactJson` ← packages/shared/src/redact.ts:197 [EXTRACTED]
  ```
  export function redactJson(value: unknown, envSecrets: Record<string, string>): unknown {
  ```
- `redactWithEnv` ← packages/shared/src/redact.ts:215 [EXTRACTED]
  ```
  export function redactWithEnv(text: string, env: NodeJS.ProcessEnv = process.env): string {
  ```
- `NotRegularFileError` ← packages/shared/src/regular-file.ts:39 [EXTRACTED]
  ```
  export class NotRegularFileError extends Error {
  ```
- `openRegularFile` ← packages/shared/src/regular-file.ts:52 [EXTRACTED]
  ```
  export async function openRegularFile(file: string): Promise<FileHandle> {
  ```
- `readRegularFile` ← packages/shared/src/regular-file.ts:73 [EXTRACTED]
  ```
  export async function readRegularFile(file: string): Promise<Buffer>;
  ```
- `readRegularFileNoLink` ← packages/shared/src/regular-file.ts:90 [EXTRACTED]
  ```
  export async function readRegularFileNoLink(file: string): Promise<Buffer>;
  ```
- `openRegularFileSync` ← packages/shared/src/regular-file.ts:116 [EXTRACTED]
  ```
  export function openRegularFileSync(file: string): number {
  ```
- `readRegularFileSync` ← packages/shared/src/regular-file.ts:133 [EXTRACTED]
  ```
  export function readRegularFileSync(file: string): Buffer;
  ```
- `openRegularFileForWrite` ← packages/shared/src/regular-file.ts:161 [EXTRACTED]
  ```
  export async function openRegularFileForWrite(file: string, { append, mode, read = false }: { append: boolean; mode?: number; read?: boolean }): Promise<FileHandle> {
  ```
- `appendRegularFile` ← packages/shared/src/regular-file.ts:188 [EXTRACTED]
  ```
  export async function appendRegularFile(file: string, data: string | Uint8Array): Promise<void> {
  ```
- `writeRegularFile` ← packages/shared/src/regular-file.ts:199 [EXTRACTED]
  ```
  export async function writeRegularFile(file: string, data: string | Uint8Array, { mode }: { mode?: number } = {}): Promise<void> {
  ```
- `writeRegularFileSync` ← packages/shared/src/regular-file.ts:210 [EXTRACTED]
  ```
  export function writeRegularFileSync(file: string, data: string | Uint8Array, { mode }: { mode?: number } = {}): void {
  ```
- `writeNewFileSync` ← packages/shared/src/regular-file.ts:241 [EXTRACTED]
  ```
  export function writeNewFileSync(file: string, data: string | Uint8Array, { mode }: { mode?: number } = {}): void {
  ```
- `copyRegularFile` ← packages/shared/src/regular-file.ts:253 [EXTRACTED]
  ```
  export async function copyRegularFile(from: string, to: string): Promise<void> {
  ```
- `copyRegularTree` ← packages/shared/src/regular-file.ts:360 [EXTRACTED]
  ```
  export async function copyRegularTree(from: string, to: string, options: CopyTreeOptions = {}): Promise<void> {
  ```
- `renameRetrying` ← packages/shared/src/regular-file.ts:404 [EXTRACTED]
  ```
  export async function renameRetrying(from: string, to: string, { isReplacing = false }: { isReplacing?: boolean } = {}): Promise<void> {
  ```
- `stagingFolder` ← packages/shared/src/regular-file.ts:426 [EXTRACTED]
  ```
  export function stagingFolder(to: string): string {
  ```
- `isStagingName` ← packages/shared/src/regular-file.ts:431 [EXTRACTED]
  ```
  export function isStagingName(name: string, of?: string): boolean {
  ```
- `mergeRegularTree` ← packages/shared/src/regular-file.ts:442 [EXTRACTED]
  ```
  export async function mergeRegularTree(from: string, to: string): Promise<void> {
  ```
- `moveRegularTree` ← packages/shared/src/regular-file.ts:472 [EXTRACTED]
  ```
  export async function moveRegularTree(from: string, to: string): Promise<void> {
  ```
- `MAX_TIMER_MS` ← packages/shared/src/timer.ts:2 [EXTRACTED]
  ```
  export const MAX_TIMER_MS = 2 ** 31 - 1;
  ```
- `ignoreTypeOfServiceRefusal` ← packages/shared/src/type-of-service.ts:19 [EXTRACTED]
  ```
  export function ignoreTypeOfServiceRefusal(): void {
  ```
- `parseYaml` ← packages/shared/src/yaml.ts:16 [EXTRACTED]
  ```
  export function parseYaml(text: string): JsonValue {
  ```
- `readAgyTranscript` ← packages/tool-agy/src/agy-transcript.ts:30 [EXTRACTED]
  ```
  export async function readAgyTranscript(source: TokenSource): Promise<TokenReading> {
  ```
- `tools` ← packages/tool-agy/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `detect` ← packages/tool-agy/src/detect.ts:4 [EXTRACTED]
  ```
  export const detect = {
  ```
- `facts` ← packages/tool-agy/src/facts.ts:23 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-agy/src/launch.ts:34 [EXTRACTED]
  ```
  export const launch = {
  ```
- `agyStoreRoots` ← packages/tool-agy/src/session-adapter.ts:77 [EXTRACTED]
  ```
  export function agyStoreRoots(cliStore: string): string[] {
  ```
- `AgyAdapter` ← packages/tool-agy/src/session-adapter.ts:81 [EXTRACTED]
  ```
  export class AgyAdapter extends AgentAdapter {
  ```
- `platforms` ← packages/tool-agy/src/sessions.ts:7 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `tools` ← packages/tool-claude/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `detect` ← packages/tool-claude/src/detect.ts:4 [EXTRACTED]
  ```
  export const detect = {
  ```
- `facts` ← packages/tool-claude/src/facts.ts:31 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-claude/src/launch.ts:25 [EXTRACTED]
  ```
  export const launch = {
  ```
- `platforms` ← packages/tool-claude/src/sessions.ts:15 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `CbContentItemSchema` ← packages/tool-codebuddy/src/codebuddy-adapter.ts:135 [EXTRACTED]
  ```
  export const CbContentItemSchema = z.object({ type: JsonValueSchema.optional(), text: coercedText() });
  ```
- `CbRecordSchema` ← packages/tool-codebuddy/src/codebuddy-adapter.ts:141 [EXTRACTED]
  ```
  export const CbRecordSchema = z.object({
  ```
- `CodeBuddyAdapter` ← packages/tool-codebuddy/src/codebuddy-adapter.ts:248 [EXTRACTED]
  ```
  export class CodeBuddyAdapter extends AgentAdapter {
  ```
- `CodeBuddyIdeAdapter` ← packages/tool-codebuddy/src/codebuddy-ide-adapter.ts:185 [EXTRACTED]
  ```
  export class CodeBuddyIdeAdapter extends AgentAdapter {
  ```
- `readCodebuddy` ← packages/tool-codebuddy/src/codebuddy-tokens.ts:168 [EXTRACTED]
  ```
  export async function readCodebuddy(source: TokenSource): Promise<TokenReading> {
  ```
- `tools` ← packages/tool-codebuddy/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `detect` ← packages/tool-codebuddy/src/detect.ts:4 [EXTRACTED]
  ```
  export const detect = {
  ```
- `facts` ← packages/tool-codebuddy/src/facts.ts:52 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect } as const satisfies ToolFamilyFacts;
  ```
- `hashWorkspace` ← packages/tool-codebuddy/src/ide-history.ts:114 [EXTRACTED]
  ```
  export function hashWorkspace(cwd: string): string | null {
  ```
- `getUserDataBase` ← packages/tool-codebuddy/src/ide-history.ts:155 [EXTRACTED]
  ```
  export function getUserDataBase(): string | null {
  ```
- `listIdeHistoryRoots` ← packages/tool-codebuddy/src/ide-history.ts:192 [EXTRACTED]
  ```
  export function listIdeHistoryRoots(): string[] {
  ```
- `findIdeHistoryDirs` ← packages/tool-codebuddy/src/ide-history.ts:230 [EXTRACTED]
  ```
  export function findIdeHistoryDirs(cwd: string, createIfMissing = false): string[] {
  ```
- `writeIdeSession` ← packages/tool-codebuddy/src/ide-history.ts:706 [EXTRACTED]
  ```
  export function writeIdeSession(session: Session, cwd: string): IdeSyncResult {
  ```
- `findIdeConversationDirs` ← packages/tool-codebuddy/src/ide-history.ts:865 [EXTRACTED]
  ```
  export function findIdeConversationDirs(convId: string): Array<{ historyDir: string; convDir: string }> {
  ```
- `deleteIdeSession` ← packages/tool-codebuddy/src/ide-history.ts:893 [EXTRACTED]
  ```
  export function deleteIdeSession(sessionId: string, cwd?: string): number {
  ```
- `readIdeConversations` ← packages/tool-codebuddy/src/ide-history.ts:1003 [EXTRACTED]
  ```
  export function readIdeConversations(historyDir: string): IdeConversationRead[] {
  ```
- `listIdeConversations` ← packages/tool-codebuddy/src/ide-history.ts:1013 [EXTRACTED]
  ```
  export function listIdeConversations(historyDirs?: string[]): IdeConversationEntry[] {
  ```
- `readIdeConversation` ← packages/tool-codebuddy/src/ide-history.ts:1130 [EXTRACTED]
  ```
  export function readIdeConversation(convDir: string, limit?: number): IdeMessageParsed[] {
  ```
- `launch` ← packages/tool-codebuddy/src/launch.ts:20 [EXTRACTED]
  ```
  export const launch = {
  ```
- `platforms` ← packages/tool-codebuddy/src/sessions.ts:9 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `WorkBuddyAdapter` ← packages/tool-codebuddy/src/workbuddy-adapter.ts:196 [EXTRACTED]
  ```
  export class WorkBuddyAdapter extends AgentAdapter {
  ```
- `registerWorkBuddySession` ← packages/tool-codebuddy/src/workbuddy-store.ts:147 [EXTRACTED]
  ```
  export function registerWorkBuddySession(args: RegisterWorkBuddySessionArgs, processes: Processes): RegisterWorkBuddyResult {
  ```
- `unregisterWorkBuddySession` ← packages/tool-codebuddy/src/workbuddy-store.ts:190 [EXTRACTED]
  ```
  export function unregisterWorkBuddySession(store: string, sessionId: string, processes: Processes): RegisterWorkBuddyResult {
  ```
- `desktopCodexBinaries` ← packages/tool-codex/src/codex-desktop.ts:10 [EXTRACTED]
  ```
  export function desktopCodexBinaries(): string[] {
  ```
- `tools` ← packages/tool-codex/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `facts` ← packages/tool-codex/src/facts.ts:43 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect: {} } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-codex/src/launch.ts:51 [EXTRACTED]
  ```
  export const launch = {
  ```
- `platforms` ← packages/tool-codex/src/sessions.ts:6 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `tools` ← packages/tool-copilot/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `facts` ← packages/tool-copilot/src/facts.ts:24 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect: {} } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-copilot/src/launch.ts:5 [EXTRACTED]
  ```
  export const launch = {
  ```
- `CopilotAdapter` ← packages/tool-copilot/src/session-adapter.ts:151 [EXTRACTED]
  ```
  export class CopilotAdapter extends AgentAdapter {
  ```
- `platforms` ← packages/tool-copilot/src/sessions.ts:7 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `UNKNOWN_READS` ← packages/tool-core/src/definition.ts:482 [EXTRACTED]
  ```
  export const UNKNOWN_READS = { user: 'unknown', project: 'unknown' } as const;
  ```
- `NONE` ← packages/tool-core/src/definition.ts:485 [EXTRACTED]
  ```
  export const NONE = { user: 'none', project: 'none' } as const;
  ```
- `UNKNOWN` ← packages/tool-core/src/definition.ts:488 [EXTRACTED]
  ```
  export const UNKNOWN = { user: 'unknown', project: 'unknown' } as const;
  ```
- `readVersion` ← packages/tool-core/src/detect.ts:16 [EXTRACTED]
  ```
  export async function readVersion(detector: VersionDetector, probe: VersionProbe): Promise<string> {
  ```
- `readPlistVersion` ← packages/tool-core/src/detect.ts:33 [EXTRACTED]
  ```
  export async function readPlistVersion(appPath: string): Promise<string> {
  ```
- `INSTANCE_KEYS` ← packages/tool-core/src/instance.ts:22 [EXTRACTED]
  ```
  export const INSTANCE_KEYS = ['schemaVersion', 'name', 'extends', 'command', 'home', 'paths'] as const;
  ```
- `ACCESS_LEVELS` ← packages/tool-core/src/launch.ts:7 [EXTRACTED]
  ```
  export const ACCESS_LEVELS = ['answer', 'read', 'full'] as const;
  ```
- `CONFINED_LEVELS` ← packages/tool-core/src/launch.ts:12 [EXTRACTED]
  ```
  export const CONFINED_LEVELS = ['best-effort', 'verified'] as const;
  ```
- `ASSUMED_OPENCODE_MAJOR` ← packages/tool-core/src/launch.ts:29 [EXTRACTED]
  ```
  export const ASSUMED_OPENCODE_MAJOR = 2;
  ```
- `opencodeMajorOf` ← packages/tool-core/src/launch.ts:35 [EXTRACTED]
  ```
  export function opencodeMajorOf(printed: string): number {
  ```
- `resultDirRule` ← packages/tool-core/src/launch.ts:122 [EXTRACTED]
  ```
  export function resultDirRule(resultDir: string): string {
  ```
- `opencodeModelArgs` ← packages/tool-core/src/launch.ts:174 [EXTRACTED]
  ```
  export function opencodeModelArgs(model: { readonly name: string; readonly effort?: string | undefined } | undefined, major: number): string[] {
  ```
- `jsonLines` ← packages/tool-core/src/launch.ts:182 [EXTRACTED]
  ```
  export function jsonLines(stdout: string): JsonValue[] {
  ```
- `failed` ← packages/tool-core/src/launch.ts:197 [EXTRACTED]
  ```
  export function failed(message: string | undefined): CallReading {
  ```
- `answered` ← packages/tool-core/src/launch.ts:202 [EXTRACTED]
  ```
  export function answered(text: string, tokens: TokenUsage | undefined, session?: string): CallReading {
  ```
- `reportedTokens` ← packages/tool-core/src/launch.ts:213 [EXTRACTED]
  ```
  export function reportedTokens(counts: TokenUsage): TokenUsage | undefined {
  ```
- `readClaudeResult` ← packages/tool-core/src/launch.ts:235 [EXTRACTED]
  ```
  export function readClaudeResult({ stdout }: CallOutput): CallReading {
  ```
- `readPlainReply` ← packages/tool-core/src/launch.ts:253 [EXTRACTED]
  ```
  export function readPlainReply({ stdout }: CallOutput): CallReading {
  ```
- `makeToolRegistry` ← packages/tool-core/src/registry.ts:45 [EXTRACTED]
  ```
  export function makeToolRegistry<
  ```
- `extractReply` ← packages/tool-core/src/reply.ts:17 [EXTRACTED]
  ```
  export function extractReply<T>(text: string, schema: z.ZodType<T>): T | undefined {
  ```
- `CostSchema` ← packages/tool-core/src/stdout.ts:12 [EXTRACTED]
  ```
  export const CostSchema = z.object({ amount: z.number().finite().nonnegative(), unit: z.string().min(1) });
  ```
- `ConfinedUsageSchema` ← packages/tool-core/src/stdout.ts:15 [EXTRACTED]
  ```
  export const ConfinedUsageSchema = z.object({
  ```
- `stoppedOnUsageLimit` ← packages/tool-core/src/stdout.ts:47 [EXTRACTED]
  ```
  export function stoppedOnUsageLimit(report: ToolReport | null | undefined, text: string): boolean {
  ```
- `budgeted` ← packages/tool-core/src/stdout.ts:223 [EXTRACTED]
  ```
  export function budgeted(tokens: TokenUsage | undefined): number {
  ```
- `addTokens` ← packages/tool-core/src/stdout.ts:228 [EXTRACTED]
  ```
  export function addTokens(current: TokenUsage | undefined, next: TokenUsage): TokenUsage {
  ```
- `readToolMetadata` ← packages/tool-core/src/stdout.ts:284 [EXTRACTED]
  ```
  export function readToolMetadata(stdout: string): ToolReport | null {
  ```
- `agyRun` ← packages/tool-core/src/stdout.ts:314 [EXTRACTED]
  ```
  export function agyRun(stdout: string): AgyRun {
  ```
- `tokenMeter` ← packages/tool-core/src/stdout.ts:386 [EXTRACTED]
  ```
  export function tokenMeter(adapter: string): (line: string) => TokenUsage | undefined {
  ```
- `toolStdout` ← packages/tool-core/src/stdout.ts:491 [EXTRACTED]
  ```
  export function toolStdout(adapter: string, stdout: string): ToolReport | null {
  ```
- `stepUsage` ← packages/tool-core/src/step-usage.ts:67 [EXTRACTED]
  ```
  export async function stepUsage({ format, transcriptPath, sessionId, turnSentAt }: { format: StepTokenFormat; transcriptPath: string; sessionId: string; turnSentAt?: number }): Promise<StepUsage> {
  ```
- `emptyTokenUsage` ← packages/tool-core/src/tokens.ts:30 [EXTRACTED]
  ```
  export function emptyTokenUsage(): TokenUsage {
  ```
- `totalTokens` ← packages/tool-core/src/tokens.ts:35 [EXTRACTED]
  ```
  export function totalTokens(t: TokenUsage | undefined): number {
  ```
- `addTokenUsage` ← packages/tool-core/src/tokens.ts:42 [EXTRACTED]
  ```
  export function addTokenUsage(a: TokenUsage | undefined, b: TokenUsage | undefined): TokenUsage {
  ```
- `INTERVENTION_SCAN_MAX_BYTES` ← packages/tool-core/src/tokens.ts:101 [EXTRACTED]
  ```
  export const INTERVENTION_SCAN_MAX_BYTES = 50 * 1024 * 1024;
  ```
- `forEachJsonLine` ← packages/tool-core/src/tokens.ts:108 [EXTRACTED]
  ```
  export async function forEachJsonLine(
  ```
- `isUsageLimitText` ← packages/tool-core/src/usage-limit.ts:10 [EXTRACTED]
  ```
  export function isUsageLimitText(text: string): boolean {
  ```
- `getCursorStateRoot` ← packages/tool-cursor/src/cursor-store.ts:35 [EXTRACTED]
  ```
  export function getCursorStateRoot(): string | null {
  ```
- `getCursorStateDbPath` ← packages/tool-cursor/src/cursor-store.ts:56 [EXTRACTED]
  ```
  export function getCursorStateDbPath(): string | null {
  ```
- `resolveCursorWorkspaceId` ← packages/tool-cursor/src/cursor-store.ts:66 [EXTRACTED]
  ```
  export function resolveCursorWorkspaceId(cwd: string): { id: string; uri: CursorUri } | null {
  ```
- `assertCursorSessionId` ← packages/tool-cursor/src/cursor-store.ts:557 [EXTRACTED]
  ```
  export function assertCursorSessionId(id: string): string | null {
  ```
- `cursorBubbleCleanupWhere` ← packages/tool-cursor/src/cursor-store.ts:567 [EXTRACTED]
  ```
  export function cursorBubbleCleanupWhere(composerId: string): string {
  ```
- `registerCursorComposer` ← packages/tool-cursor/src/cursor-store.ts:586 [EXTRACTED]
  ```
  export function registerCursorComposer(args: RegisterCursorComposerArgs, processes: Processes): RegisterResult {
  ```
- `cursorComposerExists` ← packages/tool-cursor/src/cursor-store.ts:684 [EXTRACTED]
  ```
  export function cursorComposerExists(composerId: string, processes: Processes, cwd?: string): { ok: true; exists: boolean } | { ok: false; reason: string } {
  ```
- `unregisterCursorComposer` ← packages/tool-cursor/src/cursor-store.ts:726 [EXTRACTED]
  ```
  export function unregisterCursorComposer(composerId: string, processes: Processes): RegisterResult {
  ```
- `tools` ← packages/tool-cursor/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `detect` ← packages/tool-cursor/src/detect.ts:4 [EXTRACTED]
  ```
  export const detect = {
  ```
- `facts` ← packages/tool-cursor/src/facts.ts:25 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-cursor/src/launch.ts:5 [EXTRACTED]
  ```
  export const launch = {
  ```
- `CursorAdapter` ← packages/tool-cursor/src/session-adapter.ts:162 [EXTRACTED]
  ```
  export class CursorAdapter extends AgentAdapter {
  ```
- `platforms` ← packages/tool-cursor/src/sessions.ts:7 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `BUILT_IN_FACTS` ← packages/tool-definitions/src/facts.ts:24 [EXTRACTED]
  ```
  export const BUILT_IN_FACTS = { claude, codex, qoder, joycode, pi, codebuddy, kiro, trae, zcode, openclaw, hermes, dsh, muse, copilot, opencode, agy, cursor } as const satisfies Readonly<Record<string, ToolFamilyFacts>>;
  ```
- `BUILT_IN_TOOLS` ← packages/tool-definitions/src/registry.ts:26 [EXTRACTED]
  ```
  export const BUILT_IN_TOOLS = { claude, codex, qoder, joycode, pi, codebuddy, kiro, trae, zcode, openclaw, hermes, dsh, muse, copilot, opencode, agy, cursor } as const satisfies Readonly<Record<keyof typeof BUILT_IN_FACTS, ToolFamily>>;
  ```
- `SIGN_INS` ← packages/tool-definitions/src/registry.ts:30 [EXTRACTED]
  ```
  export const SIGN_INS = { claude: claude.launch.claude.signIn, codex: codex.launch.codex.signIn, codebuddy: codebuddy.launch.codebuddy.signIn } as const;
  ```
- `stepLaunchOf` ← packages/tool-definitions/src/registry.ts:36 [EXTRACTED]
  ```
  export function stepLaunchOf(id: string): StepLaunch | undefined {
  ```
- `tools` ← packages/tool-dsh/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `detect` ← packages/tool-dsh/src/detect.ts:4 [EXTRACTED]
  ```
  export const detect = {
  ```
- `facts` ← packages/tool-dsh/src/facts.ts:6 [EXTRACTED]
  ```
  export const facts = { tools, platforms: {}, detect } as const satisfies ToolFamilyFacts;
  ```
- `tools` ← packages/tool-hermes/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `detect` ← packages/tool-hermes/src/detect.ts:4 [EXTRACTED]
  ```
  export const detect = {
  ```
- `facts` ← packages/tool-hermes/src/facts.ts:25 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-hermes/src/launch.ts:5 [EXTRACTED]
  ```
  export const launch = {
  ```
- `HermesAdapter` ← packages/tool-hermes/src/session-adapter.ts:131 [EXTRACTED]
  ```
  export class HermesAdapter extends AgentAdapter {
  ```
- `platforms` ← packages/tool-hermes/src/sessions.ts:7 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `tools` ← packages/tool-joycode/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `facts` ← packages/tool-joycode/src/facts.ts:20 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect: {} } as const satisfies ToolFamilyFacts;
  ```
- `platforms` ← packages/tool-joycode/src/sessions.ts:6 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `tools` ← packages/tool-kiro/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `facts` ← packages/tool-kiro/src/facts.ts:5 [EXTRACTED]
  ```
  export const facts = { tools, platforms: {}, detect: {} } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-kiro/src/launch.ts:5 [EXTRACTED]
  ```
  export const launch = {
  ```
- `runHeadless` ← packages/tool-launch/src/call-launch.ts:34 [EXTRACTED]
  ```
  export async function runHeadless({ start, stdin, timeoutMs, idleTimeoutMs, signal }: { start: HeadlessStarter; stdin: string; timeoutMs: number; idleTimeoutMs?: number | undefined; signal?: AbortSignal | undefined }): Promise<HeadlessRun> {
  ```
- `callLaunch` ← packages/tool-launch/src/call-launch.ts:110 [EXTRACTED]
  ```
  export async function callLaunch({ tool, prompt, session, timeoutMs, idleTimeoutMs, signal, host, start }: {
  ```
- `confinedVariables` ← packages/tool-launch/src/confined-launch.ts:14 [EXTRACTED]
  ```
  export function confinedVariables(profile: ConfinedLaunch): readonly string[] {
  ```
- `confinedArgs` ← packages/tool-launch/src/confined-launch.ts:39 [EXTRACTED]
  ```
  export function confinedArgs(input: ConfinedArgsInput): string[] {
  ```
- `confinedStdin` ← packages/tool-launch/src/confined-launch.ts:70 [EXTRACTED]
  ```
  export function confinedStdin(family: ConfinedArgsInput['family'], prompt: string): string {
  ```
- `toolLauncher` ← packages/tool-launch/src/run-step-launch.ts:123 [EXTRACTED]
  ```
  export function toolLauncher(start: ToolStart): ToolLauncher {
  ```
- `stepPrompt` ← packages/tool-launch/src/run-step-launch.ts:179 [EXTRACTED]
  ```
  export function stepPrompt(input: Pick<StepLaunchInput, 'prompt' | 'resultPath' | 'expected' | 'agent'>, { inPrompt }: { inPrompt: boolean }): string {
  ```
- `withoutPrompt` ← packages/tool-launch/src/run-step-launch.ts:235 [EXTRACTED]
  ```
  export function withoutPrompt(message: string, input: { prompt: string; agent?: { instructions: string } }): string {
  ```
- `runStepLaunch` ← packages/tool-launch/src/run-step-launch.ts:295 [EXTRACTED]
  ```
  export async function runStepLaunch({ tool, input, start, canReattach = false, limits = {}, signal, interactive, host }: {
  ```
- `tools` ← packages/tool-muse/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `detect` ← packages/tool-muse/src/detect.ts:4 [EXTRACTED]
  ```
  export const detect = {
  ```
- `facts` ← packages/tool-muse/src/facts.ts:26 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-muse/src/launch.ts:39 [EXTRACTED]
  ```
  export const launch = {
  ```
- `readMuseSession` ← packages/tool-muse/src/muse-session.ts:77 [EXTRACTED]
  ```
  export async function readMuseSession(source: TokenSource): Promise<TokenReading> {
  ```
- `MuseAdapter` ← packages/tool-muse/src/session-adapter.ts:165 [EXTRACTED]
  ```
  export class MuseAdapter extends AgentAdapter {
  ```
- `platforms` ← packages/tool-muse/src/sessions.ts:7 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `tools` ← packages/tool-openclaw/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `detect` ← packages/tool-openclaw/src/detect.ts:4 [EXTRACTED]
  ```
  export const detect = {
  ```
- `facts` ← packages/tool-openclaw/src/facts.ts:6 [EXTRACTED]
  ```
  export const facts = { tools, platforms: {}, detect } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-openclaw/src/launch.ts:29 [EXTRACTED]
  ```
  export const launch = {
  ```
- `tools` ← packages/tool-opencode/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `facts` ← packages/tool-opencode/src/facts.ts:22 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect: {} } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-opencode/src/launch.ts:54 [EXTRACTED]
  ```
  export const launch = {
  ```
- `readOpencodeDb` ← packages/tool-opencode/src/opencode-db.ts:38 [EXTRACTED]
  ```
  export async function readOpencodeDb(source: TokenSource, processes: Processes): Promise<TokenReading> {
  ```
- `OpencodeAdapter` ← packages/tool-opencode/src/session-adapter.ts:446 [EXTRACTED]
  ```
  export class OpencodeAdapter extends AgentAdapter {
  ```
- `platforms` ← packages/tool-opencode/src/sessions.ts:7 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `tools` ← packages/tool-pi/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `detect` ← packages/tool-pi/src/detect.ts:4 [EXTRACTED]
  ```
  export const detect = {
  ```
- `facts` ← packages/tool-pi/src/facts.ts:35 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-pi/src/launch.ts:36 [EXTRACTED]
  ```
  export const launch = {
  ```
- `readPiSession` ← packages/tool-pi/src/pi-session.ts:39 [EXTRACTED]
  ```
  export async function readPiSession(source: TokenSource): Promise<TokenReading> {
  ```
- `PiAdapter` ← packages/tool-pi/src/session-adapter.ts:272 [EXTRACTED]
  ```
  export class PiAdapter extends AgentAdapter {
  ```
- `platforms` ← packages/tool-pi/src/sessions.ts:7 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `tools` ← packages/tool-qoder/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `facts` ← packages/tool-qoder/src/facts.ts:38 [EXTRACTED]
  ```
  export const facts = { tools, platforms: platformFacts, detect: {} } as const satisfies ToolFamilyFacts;
  ```
- `launch` ← packages/tool-qoder/src/launch.ts:4 [EXTRACTED]
  ```
  export const launch = {
  ```
- `platforms` ← packages/tool-qoder/src/sessions.ts:6 [EXTRACTED]
  ```
  export const platforms = {
  ```
- `fixtureText` ← packages/tool-testing/src/conformance.ts:54 [EXTRACTED]
  ```
  export function fixtureText(url: URL): string {
  ```
- `describeFamily` ← packages/tool-testing/src/conformance.ts:214 [EXTRACTED]
  ```
  export function describeFamily(name: string, family: ToolFamily, recordings: FamilyRecordings): void {
  ```
- `FAKE_AGENT_MARKERS` ← packages/tool-testing/src/fake-agent.ts:9 [EXTRACTED]
  ```
  export const FAKE_AGENT_MARKERS = {
  ```
- `fakeAgent` ← packages/tool-testing/src/fake-agent.ts:78 [EXTRACTED]
  ```
  export function fakeAgent(recording: FakeAgentRecording, options: FakeAgentOptions): FakeAgent {
  ```
- `runFakeAgent` ← packages/tool-testing/src/fake-agent.ts:174 [EXTRACTED]
  ```
  export function runFakeAgent(executable: string, args: readonly string[], prompt: string, { cwd, env = {}, stopAfterOutputMs }: { cwd: string; env?: Readonly<Record<string, string>>; stopAfterOutputMs?: number }): Promise<{ stdout: string; code: number | null }> {
  ```
- `leftFakeAgents` ← packages/tool-testing/src/fake-agent.ts:194 [EXTRACTED]
  ```
  export function leftFakeAgents(): Promise<number[]> {
  ```
- `fakeCli` ← packages/tool-testing/src/fake-cli.ts:10 [EXTRACTED]
  ```
  export function fakeCli(command: string, { stdout, exitCode = 0 }: { stdout: string; exitCode?: number }): string {
  ```
- `replayTranscript` ← packages/tool-testing/src/replay-transcript.ts:40 [EXTRACTED]
  ```
  export function replayTranscript(transcript: RecordedTranscript, target: ReplayTarget): void {
  ```
- `tools` ← packages/tool-trae/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `facts` ← packages/tool-trae/src/facts.ts:5 [EXTRACTED]
  ```
  export const facts = { tools, platforms: {}, detect: {} } as const satisfies ToolFamilyFacts;
  ```
- `tools` ← packages/tool-zcode/src/definitions.ts:4 [EXTRACTED]
  ```
  export const tools = {
  ```
- `facts` ← packages/tool-zcode/src/facts.ts:5 [EXTRACTED]
  ```
  export const facts = { tools, platforms: {}, detect: {} } as const satisfies ToolFamilyFacts;
  ```
- `parseContainers` ← scripts/verify/leftovers/containers.ts:12 [EXTRACTED]
  ```
  export function parseContainers(stdout: string): Array<{ id: string; name: string; owner: string; run: string; state: string }> {
  ```
- `parseMounts` ← scripts/verify/leftovers/containers.ts:21 [EXTRACTED]
  ```
  export function parseMounts(stdout: string): Map<string, string[]> {
  ```
- `parseLabelled` ← scripts/verify/leftovers/containers.ts:30 [EXTRACTED]
  ```
  export function parseLabelled(stdout: string): Array<{ id: string; name: string; owner: string }> {
  ```
- `readPlacements` ← scripts/verify/leftovers/places.ts:15 [EXTRACTED]
  ```
  export function readPlacements(files: readonly string[]): Promise<AttemptPlacement[]> {
  ```
- `parsePs` ← scripts/verify/leftovers/processes.ts:16 [EXTRACTED]
  ```
  export function parsePs(stdout: string): Proc[] {
  ```
- `parseLsofCwd` ← scripts/verify/leftovers/processes.ts:25 [EXTRACTED]
  ```
  export function parseLsofCwd(stdout: string): Map<number, string> {
  ```
- `readDarwinTable` ← scripts/verify/leftovers/processes.ts:45 [EXTRACTED]
  ```
  export function readDarwinTable({ label, ps, lsof }: { label: string; ps: string; lsof: Captured }) {
  ```
- `parseProcLines` ← scripts/verify/leftovers/processes.ts:66 [EXTRACTED]
  ```
  export function parseProcLines(stdout: string): Proc[] {
  ```
- `pathsNamed` ← scripts/verify/leftovers/processes.ts:75 [EXTRACTED]
  ```
  export function pathsNamed(command: string): string[] {
  ```
- `lineageOf` ← scripts/verify/leftovers/processes.ts:80 [EXTRACTED]
  ```
  export function lineageOf(pid: number, procs: readonly Proc[]): Set<number> {
  ```
- `PackageAdapter` ← src/pkg/adapters/base.ts:12 [EXTRACTED]
  ```
  export abstract class PackageAdapter<TDeclaration, TLockSection> {
  ```
- `marketplaceSourceLocation` ← src/pkg/adapters/claude-plugin.ts:60 [EXTRACTED]
  ```
  export function marketplaceSourceLocation(
  ```
- `ClaudePluginAdapter` ← src/pkg/adapters/claude-plugin.ts:96 [EXTRACTED]
  ```
  export class ClaudePluginAdapter extends PackageAdapter<ClaudeEcosystem, ClaudeLockSection> {
  ```
- `extractNpmLockEntries` ← src/pkg/adapters/npm.ts:109 [EXTRACTED]
  ```
  export function extractNpmLockEntries(
  ```
- `NpmAdapter` ← src/pkg/adapters/npm.ts:131 [EXTRACTED]
  ```
  export class NpmAdapter extends PackageAdapter<NpmSpec[], NpmLockEntry[]> {
  ```
- `CNB_HOST` ← src/providers/cnb/cnb-cli.ts:40 [EXTRACTED]
  ```
  export const CNB_HOST = process.env.TEAMAI_CNB_HOST?.trim() || 'cnb.cool';
  ```
- `cnbExec` ← src/providers/cnb/cnb-cli.ts:52 [EXTRACTED]
  ```
  export function cnbExec(
  ```
- `assertCnbApiOk` ← src/providers/cnb/cnb-cli.ts:103 [EXTRACTED]
  ```
  export function assertCnbApiOk(out: string, action: string): void {
  ```
- `isCnbInstalled` ← src/providers/cnb/cnb-cli.ts:117 [EXTRACTED]
  ```
  export function isCnbInstalled(): boolean {
  ```
- `ensureCnbInstalled` ← src/providers/cnb/cnb-cli.ts:122 [EXTRACTED]
  ```
  export async function ensureCnbInstalled(): Promise<void> {
  ```
- `getCnbToken` ← src/providers/cnb/cnb-cli.ts:149 [EXTRACTED]
  ```
  export function getCnbToken(): string | null {
  ```
- `cnbIsAuthenticated` ← src/providers/cnb/cnb-cli.ts:154 [EXTRACTED]
  ```
  export function cnbIsAuthenticated(): boolean {
  ```
- `cnbWhoami` ← src/providers/cnb/cnb-cli.ts:172 [EXTRACTED]
  ```
  export function cnbWhoami(): string | null {
  ```
- `cnbLogin` ← src/providers/cnb/cnb-cli.ts:198 [EXTRACTED]
  ```
  export function cnbLogin(): void {
  ```
- `ensureCnbAuthenticated` ← src/providers/cnb/cnb-cli.ts:206 [EXTRACTED]
  ```
  export function ensureCnbAuthenticated(): string {
  ```
- `CnbRepoNotFoundError` ← src/providers/cnb/cnb-cli.ts:233 [EXTRACTED]
  ```
  export class CnbRepoNotFoundError extends Error {
  ```
- `cnbParseRepoInput` ← src/providers/cnb/cnb-cli.ts:241 [EXTRACTED]
  ```
  export function cnbParseRepoInput(input: string): RepoInfo {
  ```
- `cnbRepoClone` ← src/providers/cnb/cnb-cli.ts:282 [EXTRACTED]
  ```
  export function cnbRepoClone(repo: string, localPath: string): void {
  ```
- `cnbOrganizationCreateUrl` ← src/providers/cnb/cnb-cli.ts:323 [EXTRACTED]
  ```
  export function cnbOrganizationCreateUrl(): string {
  ```
- `cnbRepoCreateUrl` ← src/providers/cnb/cnb-cli.ts:328 [EXTRACTED]
  ```
  export function cnbRepoCreateUrl(): string {
  ```
- `cnbOrganizationExists` ← src/providers/cnb/cnb-cli.ts:339 [EXTRACTED]
  ```
  export function cnbOrganizationExists(org: string): boolean {
  ```
- `cnbCreateRepo` ← src/providers/cnb/cnb-cli.ts:359 [EXTRACTED]
  ```
  export async function cnbCreateRepo(owner: string, repo: string): Promise<void> {
  ```
- `cnbPullCreate` ← src/providers/cnb/cnb-cli.ts:404 [EXTRACTED]
  ```
  export function cnbPullCreate(opts: CnbPullCreateOptions): string {
  ```
- `parseGenericGitRepoInput` ← src/providers/git/repo-url.ts:116 [EXTRACTED]
  ```
  export function parseGenericGitRepoInput(input: string): RepoInfo {
  ```
- `parseGenericGitExistingRemote` ← src/providers/git/repo-url.ts:127 [EXTRACTED]
  ```
  export function parseGenericGitExistingRemote(input: string): RepoInfo {
  ```
- `gitcodeApiBase` ← src/providers/gitcode/gitcode-api.ts:36 [EXTRACTED]
  ```
  export function gitcodeApiBase(): string {
  ```
- `getGitCodeToken` ← src/providers/gitcode/gitcode-api.ts:43 [EXTRACTED]
  ```
  export function getGitCodeToken(): string | null {
  ```
- `readNetrcToken` ← src/providers/gitcode/gitcode-api.ts:116 [EXTRACTED]
  ```
  export function readNetrcToken(): string | null {
  ```
- `writeNetrcToken` ← src/providers/gitcode/gitcode-api.ts:138 [EXTRACTED]
  ```
  export function writeNetrcToken(token: string): void {
  ```
- `gitcodeIsAuthenticated` ← src/providers/gitcode/gitcode-api.ts:168 [EXTRACTED]
  ```
  export function gitcodeIsAuthenticated(): boolean {
  ```
- `gitcodeWhoami` ← src/providers/gitcode/gitcode-api.ts:173 [EXTRACTED]
  ```
  export async function gitcodeWhoami(): Promise<string | null> {
  ```
- `GitCodeRepoNotFoundError` ← src/providers/gitcode/gitcode-api.ts:195 [EXTRACTED]
  ```
  export class GitCodeRepoNotFoundError extends Error {
  ```
- `gitcodeRepoClone` ← src/providers/gitcode/gitcode-api.ts:233 [EXTRACTED]
  ```
  export function gitcodeRepoClone(repo: string, localPath: string): void {
  ```
- `gitcodeCreateRepo` ← src/providers/gitcode/gitcode-api.ts:265 [EXTRACTED]
  ```
  export async function gitcodeCreateRepo(owner: string, repo: string): Promise<void> {
  ```
- `gitcodePullCreate` ← src/providers/gitcode/gitcode-api.ts:321 [EXTRACTED]
  ```
  export async function gitcodePullCreate(opts: GitCodePullCreateOptions): Promise<string> {
  ```
- `gitcodeFindOpenPull` ← src/providers/gitcode/gitcode-api.ts:377 [EXTRACTED]
  ```
  export async function gitcodeFindOpenPull({ repo, source, target, timeoutMs }: PullRequestRef): Promise<string | undefined> {
  ```
- `gitcodePullHistory` ← src/providers/gitcode/gitcode-api.ts:416 [EXTRACTED]
  ```
  export async function gitcodePullHistory({ repo, source, target, timeoutMs }: PullRequestRef): Promise<PullRequestRecord[]> {
  ```
- `fetchGitCodeMR` ← src/providers/gitcode/mr-fetch.ts:76 [EXTRACTED]
  ```
  export async function fetchGitCodeMR(url: string): Promise<MRData> {
  ```
- `gitcodeListOrgRepos` ← src/providers/gitcode/org.ts:50 [EXTRACTED]
  ```
  export async function gitcodeListOrgRepos(
  ```
- `GITCODE_HOST` ← src/providers/gitcode/repo-url.ts:9 [EXTRACTED]
  ```
  export const GITCODE_HOST = 'gitcode.com';
  ```
- `parseGitCodeRepoInput` ← src/providers/gitcode/repo-url.ts:29 [EXTRACTED]
  ```
  export function parseGitCodeRepoInput(input: string): RepoInfo {
  ```
- `isGhInstalled` ← src/providers/github/gh-cli.ts:33 [EXTRACTED]
  ```
  export function isGhInstalled(): boolean {
  ```
- `ghExec` ← src/providers/github/gh-cli.ts:70 [EXTRACTED]
  ```
  export function ghExec(
  ```
- `ensureGhAvailable` ← src/providers/github/gh-cli.ts:133 [EXTRACTED]
  ```
  export async function ensureGhAvailable(): Promise<void> {
  ```
- `getGitHubToken` ← src/providers/github/gh-cli.ts:161 [EXTRACTED]
  ```
  export function getGitHubToken(): string | null {
  ```
- `ghGetOAuthToken` ← src/providers/github/gh-cli.ts:171 [EXTRACTED]
  ```
  export function ghGetOAuthToken(): string | null {
  ```
- `ghIsAuthenticated` ← src/providers/github/gh-cli.ts:194 [EXTRACTED]
  ```
  export function ghIsAuthenticated(): boolean {
  ```
- `ghFetchLogin` ← src/providers/github/gh-cli.ts:212 [EXTRACTED]
  ```
  export async function ghFetchLogin(token: string): Promise<string | null> {
  ```
- `ghAuthWhoami` ← src/providers/github/gh-cli.ts:235 [EXTRACTED]
  ```
  export async function ghAuthWhoami(): Promise<string | null> {
  ```
- `ghAuthLogin` ← src/providers/github/gh-cli.ts:260 [EXTRACTED]
  ```
  export function ghAuthLogin(): void {
  ```
- `ensureGhAuthenticated` ← src/providers/github/gh-cli.ts:283 [EXTRACTED]
  ```
  export async function ensureGhAuthenticated(): Promise<string> {
  ```
- `RepoNotFoundError` ← src/providers/github/gh-cli.ts:314 [EXTRACTED]
  ```
  export class RepoNotFoundError extends Error {
  ```
- `ghCredentialHelperFor` ← src/providers/github/gh-cli.ts:371 [EXTRACTED]
  ```
  export function ghCredentialHelperFor(ghPath: string | null, hasEnvToken: boolean): string {
  ```
- `redactCredential` ← src/providers/github/gh-cli.ts:396 [EXTRACTED]
  ```
  export function redactCredential(output: string, token: string | null): string {
  ```
- `ghRepoClone` ← src/providers/github/gh-cli.ts:431 [EXTRACTED]
  ```
  export function ghRepoClone(repo: string, localPath: string): void {
  ```
- `ghCreateRepo` ← src/providers/github/gh-cli.ts:499 [EXTRACTED]
  ```
  export async function ghCreateRepo(owner: string, repo: string): Promise<void> {
  ```
- `ghPrCreate` ← src/providers/github/gh-cli.ts:570 [EXTRACTED]
  ```
  export async function ghPrCreate(opts: GhPrCreateOptions): Promise<string> {
  ```
- `ghFindOpenPull` ← src/providers/github/gh-cli.ts:700 [EXTRACTED]
  ```
  export async function ghFindOpenPull({ repo, source, target, timeoutMs }: PullRequestRef): Promise<string | undefined> {
  ```
- `ghCommitChecks` ← src/providers/github/gh-cli.ts:729 [EXTRACTED]
  ```
  export async function ghCommitChecks({ repo, commit, timeoutMs }: CommitRef): Promise<CiStatus> {
  ```
- `ghPullHistory` ← src/providers/github/gh-cli.ts:775 [EXTRACTED]
  ```
  export async function ghPullHistory({ repo, source, target, timeoutMs }: PullRequestRef): Promise<PullRequestRecord[]> {
  ```
- `ghListOrgRepos` ← src/providers/github/gh-org.ts:177 [EXTRACTED]
  ```
  export async function ghListOrgRepos(
  ```
- `fetchGitHubPR` ← src/providers/github/mr-fetch.ts:292 [EXTRACTED]
  ```
  export async function fetchGitHubPR(url: string, opts: MRFetchOptions = {}): Promise<MRData> {
  ```
- `parseGitHubRepoInput` ← src/providers/github/repo-url.ts:15 [EXTRACTED]
  ```
  export function parseGitHubRepoInput(input: string): RepoInfo {
  ```
- `gitlabBaseUrl` ← src/providers/gitlab/gitlab-api.ts:32 [EXTRACTED]
  ```
  export function gitlabBaseUrl(): string {
  ```
- `gitlabApiBase` ← src/providers/gitlab/gitlab-api.ts:43 [EXTRACTED]
  ```
  export function gitlabApiBase(): string {
  ```
- `getGitLabToken` ← src/providers/gitlab/gitlab-api.ts:95 [EXTRACTED]
  ```
  export function getGitLabToken(): string | null {
  ```
- `gitlabIsAuthenticated` ← src/providers/gitlab/gitlab-api.ts:137 [EXTRACTED]
  ```
  export function gitlabIsAuthenticated(): boolean {
  ```
- `gitlabWhoami` ← src/providers/gitlab/gitlab-api.ts:142 [EXTRACTED]
  ```
  export async function gitlabWhoami(): Promise<string | null> {
  ```
- `ensureGitLabAvailable` ← src/providers/gitlab/gitlab-api.ts:170 [EXTRACTED]
  ```
  export async function ensureGitLabAvailable(): Promise<void> {
  ```
- `GitLabRepoNotFoundError` ← src/providers/gitlab/gitlab-api.ts:181 [EXTRACTED]
  ```
  export class GitLabRepoNotFoundError extends Error {
  ```
- `gitlabRepoClone` ← src/providers/gitlab/gitlab-api.ts:221 [EXTRACTED]
  ```
  export function gitlabRepoClone(repo: string, localPath: string): void {
  ```
- `gitlabCreateRepo` ← src/providers/gitlab/gitlab-api.ts:291 [EXTRACTED]
  ```
  export async function gitlabCreateRepo(owner: string, repo: string): Promise<void> {
  ```
- `gitlabMrCreate` ← src/providers/gitlab/gitlab-api.ts:390 [EXTRACTED]
  ```
  export async function gitlabMrCreate(opts: GitLabMrCreateOptions): Promise<string> {
  ```
- `gitlabFindOpenMr` ← src/providers/gitlab/gitlab-api.ts:453 [EXTRACTED]
  ```
  export async function gitlabFindOpenMr({ repo, source, target, timeoutMs }: PullRequestRef): Promise<string | undefined> {
  ```
- `gitlabCommitPipelines` ← src/providers/gitlab/gitlab-api.ts:487 [EXTRACTED]
  ```
  export async function gitlabCommitPipelines({ repo, commit, timeoutMs }: CommitRef): Promise<CiStatus> {
  ```
- `gitlabMrHistory` ← src/providers/gitlab/gitlab-api.ts:523 [EXTRACTED]
  ```
  export async function gitlabMrHistory({ repo, source, target, timeoutMs }: PullRequestRef): Promise<PullRequestRecord[]> {
  ```
- `parseGitLabMRUrl` ← src/providers/gitlab/mr-fetch.ts:31 [EXTRACTED]
  ```
  export function parseGitLabMRUrl(url: string): ParsedGitLabMR {
  ```
- `fetchGitLabMR` ← src/providers/gitlab/mr-fetch.ts:215 [EXTRACTED]
  ```
  export async function fetchGitLabMR(url: string, opts: MRFetchOptions = {}): Promise<MRData> {
  ```
- `gitlabListOrgRepos` ← src/providers/gitlab/org.ts:56 [EXTRACTED]
  ```
  export async function gitlabListOrgRepos(
  ```
- `probeSelfHostedGitLab` ← src/providers/gitlab/probe.ts:68 [EXTRACTED]
  ```
  export async function probeSelfHostedGitLab(
  ```
- `GITLAB_HOST` ← src/providers/gitlab/repo-url.ts:12 [EXTRACTED]
  ```
  export const GITLAB_HOST = resolveGitLabHost();
  ```
- `resolveGitLabHost` ← src/providers/gitlab/repo-url.ts:14 [EXTRACTED]
  ```
  export function resolveGitLabHost(): string {
  ```
- `parseGitLabRepoInput` ← src/providers/gitlab/repo-url.ts:44 [EXTRACTED]
  ```
  export function parseGitLabRepoInput(input: string): RepoInfo {
  ```
- `gfExec` ← src/providers/tgit/gf-cli.ts:53 [EXTRACTED]
  ```
  export function gfExec(
  ```
- `isGfInstalled` ← src/providers/tgit/gf-cli.ts:160 [EXTRACTED]
  ```
  export function isGfInstalled(): boolean {
  ```
- `ensureGfInstalled` ← src/providers/tgit/gf-cli.ts:204 [EXTRACTED]
  ```
  export async function ensureGfInstalled(): Promise<void> {
  ```
- `gfIsAuthenticated` ← src/providers/tgit/gf-cli.ts:297 [EXTRACTED]
  ```
  export function gfIsAuthenticated(): boolean {
  ```
- `gfAuthWhoami` ← src/providers/tgit/gf-cli.ts:311 [EXTRACTED]
  ```
  export function gfAuthWhoami(): string | null {
  ```
- `gfAuthLogin` ← src/providers/tgit/gf-cli.ts:331 [EXTRACTED]
  ```
  export function gfAuthLogin(): void {
  ```
- `ensureAuthenticated` ← src/providers/tgit/gf-cli.ts:344 [EXTRACTED]
  ```
  export function ensureAuthenticated(): string {
  ```
- `gfCreateRepo` ← src/providers/tgit/gf-cli.ts:393 [EXTRACTED]
  ```
  export async function gfCreateRepo(owner: string, repo: string): Promise<void> {
  ```
- `RepoNotFoundError` ← src/providers/tgit/gf-cli.ts:430 [EXTRACTED]
  ```
  export class RepoNotFoundError extends Error {
  ```
- `gfRepoClone` ← src/providers/tgit/gf-cli.ts:458 [EXTRACTED]
  ```
  export function gfRepoClone(repo: string, localPath: string): void {
  ```
- `gfMrCreate` ← src/providers/tgit/gf-cli.ts:525 [EXTRACTED]
  ```
  export function gfMrCreate(opts: GfMrCreateOptions): string {
  ```
- `tgitFindOpenMr` ← src/providers/tgit/gf-cli.ts:587 [EXTRACTED]
  ```
  export async function tgitFindOpenMr({ repo, source, target, timeoutMs }: PullRequestRef): Promise<string | undefined> {
  ```
- `tgitMrHistory` ← src/providers/tgit/gf-cli.ts:626 [EXTRACTED]
  ```
  export async function tgitMrHistory({ repo, source, target, timeoutMs }: PullRequestRef): Promise<PullRequestRecord[]> {
  ```
- `gfListOrgRepos` ← src/providers/tgit/gf-org.ts:68 [EXTRACTED]
  ```
  export async function gfListOrgRepos(
  ```
- `fetchTGitMR` ← src/providers/tgit/mr-fetch.ts:136 [EXTRACTED]
  ```
  export async function fetchTGitMR(url: string, opts: MRFetchOptions = {}): Promise<MRData> {
  ```
- `gfGetOAuthToken` ← src/providers/tgit/oauth-token.ts:19 [EXTRACTED]
  ```
  export function gfGetOAuthToken(): string | null {
  ```
- `TGIT_HOST` ← src/providers/tgit/repo-url.ts:3 [EXTRACTED]
  ```
  export const TGIT_HOST = 'git.woa.com';
  ```
- `parseTGitRepoInput` ← src/providers/tgit/repo-url.ts:13 [EXTRACTED]
  ```
  export function parseTGitRepoInput(input: string): RepoInfo {
  ```
- `getTGitToken` ← src/providers/tgit/rest-auth.ts:40 [EXTRACTED]
  ```
  export function getTGitToken(): TGitCredential {
  ```
- `tgitGitCloneUrl` ← src/providers/tgit/rest-auth.ts:80 [EXTRACTED]
  ```
  export function tgitGitCloneUrl(httpsUrl: string): string | null {
  ```
- `tryGetTGitToken` ← src/providers/tgit/rest-auth.ts:94 [EXTRACTED]
  ```
  export function tryGetTGitToken(): TGitCredential | null {
  ```
- `tgitAuthHeaders` ← src/providers/tgit/rest-auth.ts:109 [EXTRACTED]
  ```
  export function tgitAuthHeaders(token: string, scheme: TGitAuthScheme): TGitAuthHeaders {
  ```
- `tgitFetch` ← src/providers/tgit/rest-auth.ts:130 [EXTRACTED]
  ```
  export async function tgitFetch(path: string, init?: TGitFetchInit): Promise<Response> {
  ```
- `SESSION_PLATFORM_FACTS` ← src/session-flow/adapters/platform-facts.ts:6 [EXTRACTED]
  ```
  export const SESSION_PLATFORM_FACTS = {
  ```
- `isStoredSessionPlatform` ← src/session-flow/adapters/platform-facts.ts:38 [EXTRACTED]
  ```
  export function isStoredSessionPlatform(platform: SessionPlatform): platform is StoredSessionPlatform {
  ```
- `isSessionPlatform` ← src/session-flow/adapters/platform-facts.ts:42 [EXTRACTED]
  ```
  export function isSessionPlatform(platform: string): platform is SessionPlatform {
  ```
- `sessionPlatformFacts` ← src/session-flow/adapters/platform-facts.ts:46 [EXTRACTED]
  ```
  export function sessionPlatformFacts(platform: string): SessionPlatformFacts | undefined {
  ```
- `resumeCommand` ← src/session-flow/adapters/platform-facts.ts:51 [EXTRACTED]
  ```
  export function resumeCommand(platform: SessionPlatform, sessionId: string): string {
  ```
- `readCopilotShutdown` ← src/token-usage/formats/copilot-shutdown.ts:51 [EXTRACTED]
  ```
  export function readCopilotShutdown(record: JsonValue): { tokens?: TokenUsage; requests: TokenRequest[] } | undefined {
  ```
- `routerTemplate` ← src/wiki-engine/adapters/templates.ts:21 [EXTRACTED]
  ```
  export function routerTemplate(
  ```
- `indexTemplate` ← src/wiki-engine/adapters/templates.ts:110 [EXTRACTED]
  ```
  export function indexTemplate(
  ```
- `HOT_TEMPLATE` ← src/wiki-engine/adapters/templates.ts:175 [EXTRACTED]
  ```
  export const HOT_TEMPLATE = [
  ```
- `graphReadmeTemplate` ← src/wiki-engine/adapters/templates.ts:188 [EXTRACTED]
  ```
  export function graphReadmeTemplate(project: string, opts?: GraphReadmeOptions): string {
  ```
- `CODE_COLLECTION_VERSION` ← src/wiki-engine/code-knowledge/code-collector.ts:28 [EXTRACTED]
  ```
  export const CODE_COLLECTION_VERSION = 2;
  ```
- `SourceManifestSchema` ← src/wiki-engine/code-knowledge/code-collector.ts:44 [EXTRACTED]
  ```
  export const SourceManifestSchema = z.object({
  ```
- `KEY_FILE_PATTERNS` ← src/wiki-engine/code-knowledge/code-collector.ts:70 [EXTRACTED]
  ```
  export const KEY_FILE_PATTERNS = new Map<string, RegExp[]>([
  ```
- `isKeyFile` ← src/wiki-engine/code-knowledge/code-collector.ts:80 [EXTRACTED]
  ```
  export function isKeyFile(relativePath: string, language: string): boolean {
  ```
- `collectCode` ← src/wiki-engine/code-knowledge/code-collector.ts:103 [EXTRACTED]
  ```
  export async function collectCode(options: CollectCodeOptions): Promise<{ manifest: CodeCollectionManifest; files: CodeCollectedFile[]; totalCandidates: number }> {
  ```
- `isCodeFile` ← src/wiki-engine/code-knowledge/code-collector.ts:186 [EXTRACTED]
  ```
  export function isCodeFile(filePath: string): boolean {
  ```
- `gitCommit` ← src/wiki-engine/code-knowledge/code-collector.ts:209 [EXTRACTED]
  ```
  export async function gitCommit(root: string): Promise<string | undefined> {
  ```
- `isWorkingTreeClean` ← src/wiki-engine/code-knowledge/code-collector.ts:224 [EXTRACTED]
  ```
  export async function isWorkingTreeClean(root: string): Promise<boolean> {
  ```
- `gitDiffNameStatus` ← src/wiki-engine/code-knowledge/code-collector.ts:242 [EXTRACTED]
  ```
  export async function gitDiffNameStatus(
  ```
- `collectMultiRepo` ← src/wiki-engine/code-knowledge/code-collector.ts:306 [EXTRACTED]
  ```
  export async function collectMultiRepo(options: MultiRepoCollectOptions): Promise<{
  ```
- `isMetadataRelation` ← src/wiki-engine/code-knowledge/code-extractors.ts:22 [EXTRACTED]
  ```
  export function isMetadataRelation(name: string): boolean {
  ```
- `extractCodeFacts` ← src/wiki-engine/code-knowledge/code-extractors.ts:32 [EXTRACTED]
  ```
  export function extractCodeFacts(files: CodeCollectedFile[], context?: ExtractorContext): CodeFact[] {
  ```
- `mapKindToEvidenceType` ← src/wiki-engine/code-knowledge/code-fact-kind.ts:9 [EXTRACTED]
  ```
  export function mapKindToEvidenceType(kind: CodeFactKind): CodeEvidenceType {
  ```
- `buildCodeGraph` ← src/wiki-engine/code-knowledge/code-graph.ts:17 [EXTRACTED]
  ```
  export function buildCodeGraph(facts: CodeFact[]): GraphIndex {
  ```
- `detectCodeIncrementalChanges` ← src/wiki-engine/code-knowledge/code-incremental.ts:16 [EXTRACTED]
  ```
  export async function detectCodeIncrementalChanges(
  ```
- `loadFactsCache` ← src/wiki-engine/code-knowledge/code-incremental.ts:127 [EXTRACTED]
  ```
  export async function loadFactsCache(indicesDir: string): Promise<CodeFact[]> {
  ```
- `saveFactsCache` ← src/wiki-engine/code-knowledge/code-incremental.ts:142 [EXTRACTED]
  ```
  export async function saveFactsCache(indicesDir: string, facts: CodeFact[]): Promise<void> {
  ```
- `loadInterfacesCache` ← src/wiki-engine/code-knowledge/code-incremental.ts:147 [EXTRACTED]
  ```
  export async function loadInterfacesCache(indicesDir: string): Promise<InterfaceInventory> {
  ```
- `saveInterfacesCache` ← src/wiki-engine/code-knowledge/code-incremental.ts:162 [EXTRACTED]
  ```
  export async function saveInterfacesCache(
  ```
- `pruneFactsByFiles` ← src/wiki-engine/code-knowledge/code-incremental.ts:174 [EXTRACTED]
  ```
  export function pruneFactsByFiles(facts: CodeFact[], filesToRemove: Set<string>): CodeFact[] {
  ```
- `pruneInterfacesByFiles` ← src/wiki-engine/code-knowledge/code-incremental.ts:178 [EXTRACTED]
  ```
  export function pruneInterfacesByFiles(
  ```
- `mergeInterfaceInventories` ← src/wiki-engine/code-knowledge/code-incremental.ts:188 [EXTRACTED]
  ```
  export function mergeInterfaceInventories(
  ```
- `GRAPH_INDEX_SCHEMA_VERSION` ← src/wiki-engine/core/graph-index.schema.ts:16 [EXTRACTED]
  ```
  export const GRAPH_INDEX_SCHEMA_VERSION = "team-wiki.graph-index.v1" as const;
  ```
- `RELATION_TYPES` ← src/wiki-engine/core/graph-index.schema.ts:18 [EXTRACTED]
  ```
  export const RELATION_TYPES = [
  ```
- `GRAPH_EDGE_SOURCES` ← src/wiki-engine/core/graph-index.schema.ts:52 [EXTRACTED]
  ```
  export const GRAPH_EDGE_SOURCES = [
  ```
- `LEGACY_RELATIONS` ← src/wiki-engine/core/graph-index.schema.ts:80 [EXTRACTED]
  ```
  export const LEGACY_RELATIONS = new Map<string, RelationType>([
  ```
- `toPageSlug` ← src/wiki-engine/core/graph-index.schema.ts:130 [EXTRACTED]
  ```
  export function toPageSlug(relativePath: string): string {
  ```
- `parseGraphIndex` ← src/wiki-engine/core/graph-index.schema.ts:242 [EXTRACTED]
  ```
  export function parseGraphIndex(value: JsonValue): GraphIndex | null {
  ```
- `createGraphIndex` ← src/wiki-engine/core/graph-index.schema.ts:251 [EXTRACTED]
  ```
  export function createGraphIndex(nodes: GraphNode[] = [], edges: GraphEdge[] = []): GraphIndex {
  ```
- `addNode` ← src/wiki-engine/core/graph-index.schema.ts:264 [EXTRACTED]
  ```
  export function addNode(graph: GraphIndex, node: GraphNode): GraphIndex {
  ```
- `addEdge` ← src/wiki-engine/core/graph-index.schema.ts:273 [EXTRACTED]
  ```
  export function addEdge(graph: GraphIndex, edge: GraphEdge): GraphIndex {
  ```
- `addEdgeWithConfidence` ← src/wiki-engine/core/graph-index.schema.ts:289 [EXTRACTED]
  ```
  export function addEdgeWithConfidence(
  ```
- `findNeighbors` ← src/wiki-engine/core/graph-index.schema.ts:302 [EXTRACTED]
  ```
  export function findNeighbors(graph: GraphIndex, slug: string): string[] {
  ```
- `findNeighborsNHop` ← src/wiki-engine/core/graph-index.schema.ts:323 [EXTRACTED]
  ```
  export function findNeighborsNHop(
  ```
- `validateGraph` ← src/wiki-engine/core/graph-index.schema.ts:384 [EXTRACTED]
  ```
  export function validateGraph(graph: GraphIndex): GraphValidationResult {
  ```
- `computeGraphHealth` ← src/wiki-engine/core/graph-index.schema.ts:470 [EXTRACTED]
  ```
  export function computeGraphHealth(graph: GraphIndex): GraphHealthMetrics {
  ```
- `loadGraphIndex` ← src/wiki-engine/core/graph-index.schema.ts:562 [EXTRACTED]
  ```
  export async function loadGraphIndex(wikiRoot: string): Promise<GraphIndex | null> {
  ```
- `saveGraphIndex` ← src/wiki-engine/core/graph-index.schema.ts:579 [EXTRACTED]
  ```
  export async function saveGraphIndex(wikiRoot: string, graph: GraphIndex): Promise<string> {
  ```
- `mergeGraphs` ← src/wiki-engine/core/graph-index.schema.ts:597 [EXTRACTED]
  ```
  export function mergeGraphs(base: GraphIndex, overlay: GraphIndex): GraphIndex {
  ```
- `safeIgnore` ← src/wiki-engine/core/wiki-protocol.ts:155 [EXTRACTED]
  ```
  export function safeIgnore(filePath: string): boolean {
  ```
- `slugifyWiki` ← src/wiki-engine/core/wiki-protocol.ts:172 [EXTRACTED]
  ```
  export function slugifyWiki(value: string): string {
  ```
- `wikiPagePath` ← src/wiki-engine/core/wiki-protocol.ts:181 [EXTRACTED]
  ```
  export function wikiPagePath(page: Pick<WikiPageDraft, "slug" | "relativePath" | "metadata">): string {
  ```
- `normalizeRelativePagePath` ← src/wiki-engine/core/wiki-protocol.ts:192 [EXTRACTED]
  ```
  export function normalizeRelativePagePath(value: string): string {
  ```
- `wikiLinkTarget` ← src/wiki-engine/core/wiki-protocol.ts:198 [EXTRACTED]
  ```
  export function wikiLinkTarget(relativePath: string): string {
  ```
- `toPosix` ← src/wiki-engine/core/wiki-protocol.ts:202 [EXTRACTED]
  ```
  export function toPosix(value: string): string {
  ```
- `deliveryConformanceWorkflow` ← src/workflow/conformance/delivery.ts:34 [EXTRACTED]
  ```
  export const deliveryConformanceWorkflow = `schemaVersion: v1alpha1
  ```
- `fixCiConformanceWorkflow` ← src/workflow/conformance/delivery.ts:105 [EXTRACTED]
  ```
  export const fixCiConformanceWorkflow = `schemaVersion: v1alpha1
  ```
- `PLACE_CHECKOUT_FILES` ← src/workflow/conformance/place.ts:4 [EXTRACTED]
  ```
  export const PLACE_CHECKOUT_FILES = { 'README.md': '# fixture\n', 'AGENTS.md': 'Trusted base instructions.\n' } satisfies Record<string, string>;
  ```
- `markerLines` ← src/workflow/discovery/generated-marker.ts:20 [EXTRACTED]
  ```
  export function markerLines(name: string): string[] {
  ```
- `signGenerated` ← src/workflow/discovery/generated-marker.ts:25 [EXTRACTED]
  ```
  export function signGenerated(content: string, name: string): string {
  ```
- `readGenerated` ← src/workflow/discovery/generated-marker.ts:32 [EXTRACTED]
  ```
  export function readGenerated(content: string): Generated {
  ```
- `generatedSkillAt` ← src/workflow/discovery/generated-marker.ts:43 [EXTRACTED]
  ```
  export async function generatedSkillAt(skillDir: string): Promise<Generated> {
  ```
- `isUneditedGeneratedSkill` ← src/workflow/discovery/generated-marker.ts:50 [EXTRACTED]
  ```
  export async function isUneditedGeneratedSkill(skillDir: string): Promise<boolean> {
  ```
- `renderWorkflowSkill` ← src/workflow/discovery/render.ts:32 [EXTRACTED]
  ```
  export function renderWorkflowSkill(workflow: AdvertisedWorkflow, tool: string): string {
  ```
- `mayBeGeneratedSkill` ← src/workflow/discovery/workflow-skills.ts:68 [EXTRACTED]
  ```
  export function mayBeGeneratedSkill(dir: string): boolean {
  ```
- `deployWorkflowSkills` ← src/workflow/discovery/workflow-skills.ts:202 [EXTRACTED]
  ```
  export async function deployWorkflowSkills({ teamConfig, localConfig, recorder }: {
  ```
- `shadowedWorkflowSkills` ← src/workflow/discovery/workflow-skills.ts:233 [EXTRACTED]
  ```
  export async function shadowedWorkflowSkills({ teamConfig, localConfig }: { teamConfig: TeamaiConfig; localConfig: LocalConfig }): Promise<string[]> {
  ```
- `FLEET_STOP_BUDGET_MS` ← src/workflow/fleet/beats.ts:9 [EXTRACTED]
  ```
  export const FLEET_STOP_BUDGET_MS = ANSWER_WITHIN_MS + STOP_GRACE_MS;
  ```
- `MIN_STALE_AFTER_MS` ← src/workflow/fleet/beats.ts:15 [EXTRACTED]
  ```
  export const MIN_STALE_AFTER_MS = 3 * MIN_BEAT_MS + FLEET_STOP_BUDGET_MS;
  ```
- `fleetBeats` ← src/workflow/fleet/beats.ts:30 [EXTRACTED]
  ```
  export function fleetBeats(staleAfterMs: number) {
  ```
- `killBoundedCancelEnd` ← src/workflow/fleet/beats.ts:45 [EXTRACTED]
  ```
  export function killBoundedCancelEnd({ cancelAt, staleAfterMs }: { cancelAt: number; staleAfterMs: number }): number {
  ```
- `readyMarkerOf` ← src/workflow/fleet/fence.ts:78 [EXTRACTED]
  ```
  export function readyMarkerOf(file: string, owner: string): string {
  ```
- `sayGuardianReady` ← src/workflow/fleet/fence.ts:95 [EXTRACTED]
  ```
  export function sayGuardianReady(files: GuardianFs, { file, owner, marker }: { file: string; owner: string; marker: string }): 'ready' | 'retired' | 'unwritten' {
  ```
- `isFenceHeld` ← src/workflow/fleet/fence.ts:207 [EXTRACTED]
  ```
  export async function isFenceHeld(file: string, owner: string): Promise<boolean> {
  ```
- `fenceStep` ← src/workflow/fleet/fence.ts:259 [EXTRACTED]
  ```
  export async function fenceStep({ dir, command, at, claim }: { dir: string; command?: FencedCommand; at: number; claim: GuardianStop }): Promise<{ ok: true; fence: StepFence } | { ok: false; reason: string }> {
  ```
- `endLeftFence` ← src/workflow/fleet/fence.ts:342 [EXTRACTED]
  ```
  export async function endLeftFence(dir: string): Promise<void> {
  ```
- `gateQuestions` ← src/workflow/fleet/gate.ts:23 [EXTRACTED]
  ```
  export function gateQuestions(): GateQuestions {
  ```
- `GuardianStopSchema` ← src/workflow/fleet/guardian-stop.ts:10 [EXTRACTED]
  ```
  export const GuardianStopSchema = z.object({
  ```
- `GuardianInputSchema` ← src/workflow/fleet/guardian-stop.ts:23 [EXTRACTED]
  ```
  export const GuardianInputSchema = GuardianStopSchema.extend({ fence: z.string().min(1), owner: z.string().min(1) }).strict();
  ```
- `runFleetGuardian` ← src/workflow/fleet/guardian-stop.ts:40 [EXTRACTED]
  ```
  export async function runFleetGuardian(input: string): Promise<void> {
  ```
- `memberPlace` ← src/workflow/fleet/member.ts:95 [EXTRACTED]
  ```
  export function memberPlace(opened: OpenedDriver | undefined): MemberPlace | { refused: string } {
  ```
- `takeFleetAttempt` ← src/workflow/fleet/member.ts:289 [EXTRACTED]
  ```
  export async function takeFleetAttempt(config: LocalConfig, input: { pool: string; repository: string; root: string; member: HandoffOwner; secrets: Record<string, string>; place: MemberPlace }): Promise<WorkflowEnvelope> {
  ```
- `stopLeftOfClaim` ← src/workflow/fleet/member.ts:421 [EXTRACTED]
  ```
  export async function stopLeftOfClaim(config: LocalConfig, { claim, root, isEnded }: { claim: Pick<FleetRecord, 'run' | 'attempt' | 'pool'> & { lease: Pick<FleetLease, 'step'> }; root: string; isEnded: boolean }): Promise<{ kind: 'left'; message: string } | { kind: 'stopped'; nestedRun: Exclude<LeftNestedRun, { kind: 'running' }>; isLeftRunning: boolean }> {
  ```
- `CANCEL_WRITE_MS` ← src/workflow/fleet/owner.ts:49 [EXTRACTED]
  ```
  export const CANCEL_WRITE_MS = 60_000;
  ```
- `parseFleetOptions` ← src/workflow/fleet/owner.ts:70 [EXTRACTED]
  ```
  export function parseFleetOptions(options: RuntimeOptions): { ok: true; value: z.infer<typeof FleetOptionsSchema> } | { ok: false; failure: { key: string; message: string } } {
  ```
- `shadowedFleetEntries` ← src/workflow/fleet/owner.ts:110 [EXTRACTED]
  ```
  export function shadowedFleetEntries(runtimes: ReadonlyArray<{ use: string; through?: string; options?: RuntimeOptions }>): string[] {
  ```
- `fleetStepRuntime` ← src/workflow/fleet/owner.ts:389 [EXTRACTED]
  ```
  export function fleetStepRuntime({ config, masks, openWake }: { config: LocalConfig; masks: Record<string, string>; openWake?: OpenWake }): StepRuntime<DriverCan> {
  ```
- `cancelFleetAttempt` ← src/workflow/fleet/owner.ts:1248 [EXTRACTED]
  ```
  export async function cancelFleetAttempt(config: LocalConfig, run: RunId, attempt: AttemptId): Promise<{ ok: boolean; message: string }> {
  ```
- `FleetRecordSchema` ← src/workflow/fleet/record.ts:256 [EXTRACTED]
  ```
  export const FleetRecordSchema = z.discriminatedUnion('state', [OfferedSchema, ClaimedSchema, AskingSchema, AnsweredSchema, FinishedSchema, ExpiredSchema, WithdrawnSchema, CancellingSchema, CancelledSchema]);
  ```
- `isHeld` ← src/workflow/fleet/record.ts:272 [EXTRACTED]
  ```
  export function isHeld(record: FleetRecord): record is HeldAttempt {
  ```
- `attemptBranchPrefix` ← src/workflow/fleet/record.ts:308 [EXTRACTED]
  ```
  export function attemptBranchPrefix(runId: string): string {
  ```
- `attemptRef` ← src/workflow/fleet/record.ts:313 [EXTRACTED]
  ```
  export function attemptRef(run: RunId, attempt: AttemptId): string {
  ```
- `leaseValues` ← src/workflow/fleet/record.ts:391 [EXTRACTED]
  ```
  export function leaseValues(step: Pick<WorkflowStep, 'id' | 'prompt' | 'env' | 'with' | 'model' | 'workflow'>, context: TemplateContext): { values: LeaseValues } | { error: string } {
  ```
- `leaseEnv` ← src/workflow/fleet/record.ts:470 [EXTRACTED]
  ```
  export function leaseEnv(step: Pick<WorkflowStep, 'id' | 'env'>, values: LeaseValues, run: RunId): { env: Record<string, string> } | { error: string } {
  ```
- `leasePrompt` ← src/workflow/fleet/record.ts:488 [EXTRACTED]
  ```
  export function leasePrompt(step: Pick<WorkflowStep, 'id' | 'prompt' | 'with' | 'model'>, values: LeaseValues, run: RunId): { prompt: string; model?: string } | { error: string } {
  ```
- `leaseInputs` ← src/workflow/fleet/record.ts:516 [EXTRACTED]
  ```
  export function leaseInputs(step: Pick<WorkflowStep, 'id' | 'prompt' | 'env' | 'with' | 'model' | 'workflow'>, child: WorkflowDefinition | InlineWorkflow, values: LeaseValues, run: RunId): { inputs: JsonValue } | { error: string } {
  ```
- `offerAttempt` ← src/workflow/fleet/record.ts:527 [EXTRACTED]
  ```
  export async function offerAttempt(config: LocalConfig, input: {
  ```
- `claimAttempt` ← src/workflow/fleet/record.ts:547 [EXTRACTED]
  ```
  export async function claimAttempt(config: LocalConfig, offered: Offered, member: HandoffOwner): Promise<Written<Claimed>> {
  ```
- `leaveOffer` ← src/workflow/fleet/record.ts:566 [EXTRACTED]
  ```
  export async function leaveOffer(config: LocalConfig, offered: Offered, { member, why, secrets }: { member: HandoffOwner; why: string; secrets: Record<string, string> }): Promise<Written<void>> {
  ```
- `recordProgress` ← src/workflow/fleet/record.ts:589 [EXTRACTED]
  ```
  export async function recordProgress(config: LocalConfig, held: HeldAttempt, pushed: string, asked?: { question: ExecQuestion; secrets: Record<string, string> }): Promise<Written<HeldAttempt>> {
  ```
- `expireClaim` ← src/workflow/fleet/record.ts:607 [EXTRACTED]
  ```
  export async function expireClaim(config: LocalConfig, claimed: HeldAttempt | Cancelling, { lastSeenAt }: { lastSeenAt: number }): Promise<Written<Extract<FleetRecord, { state: 'expired' }>> | { ok: false; error: { code: 'fleet_expire_too_early'; message: string } }> {
  ```
- `isUnstoppedEnd` ← src/workflow/fleet/record.ts:622 [EXTRACTED]
  ```
  export function isUnstoppedEnd(record: FleetRecord): record is Extract<FleetRecord, { state: 'finished' | 'cancelled' }> & { stopped: false } {
  ```
- `confirmStop` ← src/workflow/fleet/record.ts:633 [EXTRACTED]
  ```
  export async function confirmStop(config: LocalConfig, { run, attempt, member }: { run: RunId; attempt: AttemptId; member: HandoffOwner }): Promise<Written<void>> {
  ```
- `cancelAttempt` ← src/workflow/fleet/record.ts:654 [EXTRACTED]
  ```
  export async function cancelAttempt(config: LocalConfig, record: Offered | HeldAttempt, wait?: LockWait): Promise<Written<Extract<FleetRecord, { state: 'withdrawn' | 'cancelling' }>>> {
  ```
- `answerQuestion` ← src/workflow/fleet/record.ts:666 [EXTRACTED]
  ```
  export async function answerQuestion(config: LocalConfig, asking: Asking, answer: ExecAnswer, secrets: Record<string, string>): Promise<Written<Extract<FleetRecord, { state: 'answered' }>>> {
  ```
- `answerCancel` ← src/workflow/fleet/record.ts:678 [EXTRACTED]
  ```
  export async function answerCancel(config: LocalConfig, cancelling: Cancelling, { pushed, tokens, stopped }: { pushed: string; tokens?: TokenUsage; stopped?: false }): Promise<Written<Extract<FleetRecord, { state: 'cancelled' }>>> {
  ```
- `finishAttempt` ← src/workflow/fleet/record.ts:695 [EXTRACTED]
  ```
  export async function finishAttempt(config: LocalConfig, claimed: HeldAttempt, result: FleetResult, secrets: Record<string, string>, { stopped }: { stopped?: false } = {}): Promise<Written<FleetRecord>> {
  ```
- `readAttemptRecord` ← src/workflow/fleet/record.ts:715 [EXTRACTED]
  ```
  export async function readAttemptRecord(config: LocalConfig, run: RunId, attempt: AttemptId): Promise<Written<FleetRecord | 'absent'>> {
  ```
- `listRecords` ← src/workflow/fleet/record.ts:782 [EXTRACTED]
  ```
  export async function listRecords(config: LocalConfig, run?: RunId): Promise<FleetRecord[]> {
  ```
- `listOpenAttempts` ← src/workflow/fleet/record.ts:808 [EXTRACTED]
  ```
  export async function listOpenAttempts(config: LocalConfig, repository: string): Promise<OpenAttempt[]> {
  ```
- `offersAmong` ← src/workflow/fleet/record.ts:815 [EXTRACTED]
  ```
  export function offersAmong(records: FleetRecord[], { pool, repository }: { pool: string; repository: string }): Offered[] {
  ```
- `lastGoneWork` ← src/workflow/fleet/record.ts:843 [EXTRACTED]
  ```
  export async function lastGoneWork(config: LocalConfig, { run, step }: { run: RunId; step: string }): Promise<{ attempt: AttemptId; pushed: string } | undefined> {
  ```
- `memberRecordsAmong` ← src/workflow/fleet/record.ts:869 [EXTRACTED]
  ```
  export async function memberRecordsAmong(config: LocalConfig, records: FleetRecord[], { member, repository }: { member: HandoffOwner; repository: string }): Promise<MemberRecord[]> {
  ```
- `markOffered` ← src/workflow/fleet/record.ts:960 [EXTRACTED]
  ```
  export async function markOffered(config: LocalConfig, run: RunId, attempt: AttemptId, pool: string, offer?: { op: OpId; staleAfterMs: number }): Promise<void> {
  ```
- `noteHeldFolders` ← src/workflow/fleet/record.ts:981 [EXTRACTED]
  ```
  export async function noteHeldFolders(config: LocalConfig, held: HeldAttempt, sourceHashes: readonly string[]): Promise<void> {
  ```
- `heldFolders` ← src/workflow/fleet/record.ts:992 [EXTRACTED]
  ```
  export async function heldFolders(config: LocalConfig): Promise<{ ok: true; folders: string[] } | { ok: false; why: string }> {
  ```
- `noteWake` ← src/workflow/fleet/record.ts:1039 [EXTRACTED]
  ```
  export async function noteWake(config: LocalConfig, run: RunId, attempt: AttemptId, wake: WakeNote): Promise<void> {
  ```
- `woken` ← src/workflow/fleet/record.ts:1048 [EXTRACTED]
  ```
  export function woken(marker: z.infer<typeof OfferedMarkerSchema> | undefined): string | undefined {
  ```
- `readOfferedMarker` ← src/workflow/fleet/record.ts:1057 [EXTRACTED]
  ```
  export async function readOfferedMarker(config: LocalConfig, run: RunId, attempt: AttemptId): Promise<z.infer<typeof OfferedMarkerSchema> | undefined> {
  ```
- `offeredPool` ← src/workflow/fleet/record.ts:1065 [EXTRACTED]
  ```
  export async function offeredPool(config: LocalConfig, run: RunId, attempt: AttemptId): Promise<string | undefined> {
  ```
- `fleetFailure` ← src/workflow/fleet/record.ts:1079 [EXTRACTED]
  ```
  export function fleetFailure(error: FleetError): WorkflowFailure {
  ```
- `adoptRefusal` ← src/workflow/place/adopted.ts:28 [EXTRACTED]
  ```
  export async function adoptRefusal(input: {
  ```
- `takeAdopted` ← src/workflow/place/adopted.ts:126 [EXTRACTED]
  ```
  export async function takeAdopted({ root, dir, workspace }: Omit<Adoption, 'run' | 'attempt'>): Promise<{ dir: string } | WorkflowFailure> {
  ```
- `cloneKeyOf` ← src/workflow/place/clone.ts:99 [EXTRACTED]
  ```
  export function cloneKeyOf(branch: string): string {
  ```
- `commitCacheOf` ← src/workflow/place/clone.ts:131 [EXTRACTED]
  ```
  export function commitCacheOf(config: LocalConfig, repo: string): string {
  ```
- `firstUnreachable` ← src/workflow/place/clone.ts:139 [EXTRACTED]
  ```
  export async function firstUnreachable(input: { cache: string; repo: string; commits: readonly string[]; checkout?: string }): Promise<string | undefined> {
  ```
- `openClone` ← src/workflow/place/clone.ts:180 [EXTRACTED]
  ```
  export async function openClone(input: { config: LocalConfig; run: RunId; checkout: string; lease: CloneLease }): Promise<{ dir: string } & ({ created: boolean } | { failure: WorkflowFailure })> {
  ```
- `markCloneReady` ← src/workflow/place/clone.ts:254 [EXTRACTED]
  ```
  export async function markCloneReady(config: LocalConfig, run: RunId, branch: string): Promise<void> {
  ```
- `preparedClone` ← src/workflow/place/clone.ts:267 [EXTRACTED]
  ```
  export async function preparedClone(config: LocalConfig, run: RunId, branch: string): Promise<PreparedClone | undefined> {
  ```
- `attemptCloneHome` ← src/workflow/place/clone.ts:295 [EXTRACTED]
  ```
  export async function attemptCloneHome(dir: string, env: NodeJS.ProcessEnv): Promise<string | undefined> {
  ```
- `cloneDelivery` ← src/workflow/place/clone.ts:319 [EXTRACTED]
  ```
  export async function cloneDelivery({ install, without }: { install: LocalConfig; without?: Without }, tool: string): Promise<TeamDelivery | undefined> {
  ```
- `removeClone` ← src/workflow/place/clone.ts:327 [EXTRACTED]
  ```
  export async function removeClone(config: LocalConfig, run: RunId, branch: string): Promise<void> {
  ```
- `commitClone` ← src/workflow/place/clone.ts:340 [EXTRACTED]
  ```
  export async function commitClone(input: { dir: string; branch: string; step: string; base: string; start: string; withhold: readonly string[]; expiresAt?: string }): Promise<{ changes: { branch: string; base: string; from: string; to: string; commits: string[] } } | WorkflowFailure> {
  ```
- `cloneHead` ← src/workflow/place/clone.ts:366 [EXTRACTED]
  ```
  export async function cloneHead(config: LocalConfig, run: RunId, branch: string, lease: { withhold: readonly string[]; expiresAt?: string }): Promise<HeadState | null> {
  ```
- `cloneEnv` ← src/workflow/place/clone.ts:386 [EXTRACTED]
  ```
  export function cloneEnv(withhold: readonly string[]): ReturnType<typeof stepEnvironment> {
  ```
- `sweepClones` ← src/workflow/place/clone.ts:397 [EXTRACTED]
  ```
  export async function sweepClones(config: LocalConfig, runId?: string): Promise<RunId[]> {
  ```
- `stageSettledEvidence` ← src/workflow/place/clone.ts:456 [EXTRACTED]
  ```
  export async function stageSettledEvidence(config: LocalConfig, run: RunState, succeeded: readonly string[]): Promise<void> {
  ```
- `freshClone` ← src/workflow/place/clone.ts:493 [EXTRACTED]
  ```
  export async function freshClone(root: string, commit: string, sources: readonly string[], expiresAt: string | undefined, env: NodeJS.ProcessEnv): Promise<WorkflowFailure | undefined> {
  ```
- `scratchCloneRoot` ← src/workflow/place/clone.ts:526 [EXTRACTED]
  ```
  export function scratchCloneRoot(): string {
  ```
- `leaseCommits` ← src/workflow/place/created.ts:7 [EXTRACTED]
  ```
  export function leaseCommits(workspace: CopyContract): Array<{ commit: string; branch?: string }> {
  ```
- `openWorktree` ← src/workflow/place/created.ts:19 [EXTRACTED]
  ```
  export async function openWorktree({ root, run, step, workspace, setup }: {
  ```
- `dataCheckoutOf` ← src/workflow/place/data.ts:26 [EXTRACTED]
  ```
  export function dataCheckoutOf(config: LocalConfig, run: RunId, attempt: AttemptId): string {
  ```
- `dataCheckoutsOf` ← src/workflow/place/data.ts:31 [EXTRACTED]
  ```
  export function dataCheckoutsOf(config: LocalConfig, run: string): string {
  ```
- `removeDataCheckout` ← src/workflow/place/data.ts:36 [EXTRACTED]
  ```
  export async function removeDataCheckout(config: LocalConfig, dir: string): Promise<void> {
  ```
- `openDataCheckout` ← src/workflow/place/data.ts:47 [EXTRACTED]
  ```
  export async function openDataCheckout(input: { config: LocalConfig; run: RunId; attempt: AttemptId; branch: DataBranch }): Promise<{ dir: string; at: DataAt }> {
  ```
- `finishDataCheckout` ← src/workflow/place/data.ts:155 [EXTRACTED]
  ```
  export async function finishDataCheckout(input: { config: LocalConfig; dir: string; step: string; branch: DataBranch; at: DataAt }): Promise<{ message?: string } | WorkflowFailure> {
  ```
- `applyOverlay` ← src/workflow/place/overlay.ts:16 [EXTRACTED]
  ```
  export async function applyOverlay({ root, dir, configCommit, saved, resume, step, executor, role, tool, run }: {
  ```
- `restoreOverlay` ← src/workflow/place/overlay.ts:47 [EXTRACTED]
  ```
  export async function restoreOverlay({ dir, configCommit, saved, unfinished, run }: { dir: string; configCommit: string; saved: string; unfinished?: true; run: Git }): Promise<string | undefined> {
  ```
- `unrestoredConfig` ← src/workflow/place/overlay.ts:59 [EXTRACTED]
  ```
  export function unrestoredConfig(reason: string, dir: string): string {
  ```
- `placeRoot` ← src/workflow/place/place.ts:43 [EXTRACTED]
  ```
  export async function placeRoot({ cwd, checkout }: { cwd: string; checkout: string | undefined }): Promise<string> {
  ```
- `placeOf` ← src/workflow/place/place.ts:58 [EXTRACTED]
  ```
  export function placeOf(lease: { cwd?: string; workspace?: WorkspaceContract }, root: string): string {
  ```
- `placeHeldBy` ← src/workflow/place/place.ts:72 [EXTRACTED]
  ```
  export async function placeHeldBy(input: { config: LocalConfig; run: RunId; root: string; lease: Pick<PlaceLease, 'workspace'>; others: AttemptId[]; adopt?: string }): Promise<{ behind: AttemptId; dir: string } | undefined> {
  ```
- `adoptedPlaceOf` ← src/workflow/place/place.ts:93 [EXTRACTED]
  ```
  export async function adoptedPlaceOf(input: { config: LocalConfig; run: RunId; branch: string }): Promise<string | undefined> {
  ```
- `placeLeaseOf` ← src/workflow/place/place.ts:117 [EXTRACTED]
  ```
  export function placeLeaseOf(lease: LeaseWire): PlaceLease {
  ```
- `isSetupCutShort` ← src/workflow/place/place.ts:214 [EXTRACTED]
  ```
  export async function isSetupCutShort({ config, run, attempt }: { config: LocalConfig; run: RunId; attempt: AttemptId }): Promise<boolean> {
  ```
- `preparePlace` ← src/workflow/place/place.ts:230 [EXTRACTED]
  ```
  export async function preparePlace(input: { config: LocalConfig; lock: RunLock; root: string; lease: PlaceLease; adopt?: string }): Promise<PlacePrepared> {
  ```
- `copyGit` ← src/workflow/place/place.ts:553 [EXTRACTED]
  ```
  export async function copyGit(config: LocalConfig, place: { run: RunId; root: string }): Promise<UntrustedGit> {
  ```
- `runPlaceSetup` ← src/workflow/place/place.ts:702 [EXTRACTED]
  ```
  export async function runPlaceSetup(input: { config: LocalConfig; run: RunId; attempt: AttemptId; mode: RunMode; env: Pick<WorkflowEnv, 'values' | 'facts'>; signal?: AbortSignal; on?: SetupOn }): Promise<WorkflowFailure | undefined> {
  ```
- `placeEditsOf` ← src/workflow/place/place.ts:780 [EXTRACTED]
  ```
  export async function placeEditsOf(input: { config: LocalConfig; run: RunId; attempt: AttemptId; dir: string }): Promise<{ paths: string[] } | { error: string }> {
  ```
- `refuseDirtyAdoptedCommand` ← src/workflow/place/place.ts:795 [EXTRACTED]
  ```
  export async function refuseDirtyAdoptedCommand(input: { config: LocalConfig; run: RunId; attempt: AttemptId }): Promise<WorkflowFailure | undefined> {
  ```
- `finishPlace` ← src/workflow/place/place.ts:829 [EXTRACTED]
  ```
  export async function finishPlace(input: {
  ```
- `stagePassEvidence` ← src/workflow/place/place.ts:907 [EXTRACTED]
  ```
  export async function stagePassEvidence(input: { config: LocalConfig; lock: RunLock; attempt: AttemptId; report: ReportInput }): Promise<string | undefined> {
  ```
- `abandonPlace` ← src/workflow/place/place.ts:1086 [EXTRACTED]
  ```
  export async function abandonPlace(input: { config: LocalConfig; lock: RunLock; attempt: AttemptId }): Promise<string | undefined> {
  ```
- `keepPlace` ← src/workflow/place/place.ts:1169 [EXTRACTED]
  ```
  export async function keepPlace(input: { config: LocalConfig; lock: RunLock; attempt: AttemptId }): Promise<string | undefined> {
  ```
- `releaseUnlaunchedPlace` ← src/workflow/place/place.ts:1200 [EXTRACTED]
  ```
  export async function releaseUnlaunchedPlace(input: { config: LocalConfig; lock: RunLock; attempt: AttemptId }): Promise<string | undefined> {
  ```
- `preparedCopyTeam` ← src/workflow/place/place.ts:1275 [EXTRACTED]
  ```
  export async function preparedCopyTeam(input: { config: LocalConfig; run: RunId; attempt: AttemptId; tool: string }): Promise<PreparedAgent['team']> {
  ```
- `placeRecorded` ← src/workflow/place/place.ts:1288 [EXTRACTED]
  ```
  export async function placeRecorded(input: { config: LocalConfig; run: RunId; attempt: AttemptId }): Promise<boolean> {
  ```
- `releasePlace` ← src/workflow/place/place.ts:1296 [EXTRACTED]
  ```
  export async function releasePlace(input: { config: LocalConfig; lock: RunLock; attempt: AttemptId }): Promise<'removed' | 'left'> {
  ```
- `stageReader` ← src/workflow/place/reader.ts:21 [EXTRACTED]
  ```
  export async function stageReader(dir: string, file: string, run: Git): Promise<WorktreeSnapshot> {
  ```
- `readSnapshot` ← src/workflow/place/reader.ts:30 [EXTRACTED]
  ```
  export async function readSnapshot(file: string): Promise<WorktreeSnapshot | undefined> {
  ```
- `finishReader` ← src/workflow/place/reader.ts:48 [EXTRACTED]
  ```
  export async function finishReader(input: {
  ```
- `leaveReadCopy` ← src/workflow/place/reader.ts:101 [EXTRACTED]
  ```
  export async function leaveReadCopy(input: {
  ```
- `readCopyFailure` ← src/workflow/place/reader.ts:137 [EXTRACTED]
  ```
  export function readCopyFailure(left: Exclude<ReadCopy, { state: 'untouched' }>, changed: string): WorkflowFailure {
  ```
- `PlaceFinishedSchema` ← src/workflow/place/record.ts:78 [EXTRACTED]
  ```
  export const PlaceFinishedSchema = z.object({
  ```
- `readPlaceRecord` ← src/workflow/place/record.ts:146 [EXTRACTED]
  ```
  export async function readPlaceRecord(config: LocalConfig, run: RunId, attempt: AttemptId): Promise<{ kind: 'found'; record: PlaceRecord } | { kind: 'missing' } | { kind: 'unreadable'; reason: string }> {
  ```
- `writePlaceRecord` ← src/workflow/place/record.ts:160 [EXTRACTED]
  ```
  export async function writePlaceRecord(config: LocalConfig, record: PlaceRecord): Promise<void> {
  ```
- `roleCopyRefusal` ← src/workflow/place/role-copy.ts:67 [EXTRACTED]
  ```
  export async function roleCopyRefusal(input: { team: TeamaiConfig; install: LocalConfig; role: string; host?: Host }): Promise<WorkflowFailure | undefined> {
  ```
- `copyKnowledgePaths` ← src/workflow/place/role-copy.ts:94 [EXTRACTED]
  ```
  export async function copyKnowledgePaths(input: { team: TeamaiConfig; install: LocalConfig; host?: Host }): Promise<string[]> {
  ```
- `roleNotDeliveredFailure` ← src/workflow/place/role-copy.ts:173 [EXTRACTED]
  ```
  export function roleNotDeliveredFailure(input: { role: string; step: string; notDelivered: RoleNotDelivered }): WorkflowFailure {
  ```
- `setUpWorktreeRole` ← src/workflow/place/role-copy.ts:318 [EXTRACTED]
  ```
  export async function setUpWorktreeRole(input: { dir: string; step: string; executor: Executor; role?: string; tool?: string }): Promise<{ paths: readonly string[]; tools: readonly string[] } | WorkflowFailure> {
  ```
- `launchedTools` ← src/workflow/place/role-copy.ts:366 [EXTRACTED]
  ```
  export function launchedTools(input: { executor: Executor; tool: string | undefined; enabled: readonly string[] }): string[] {
  ```
- `worktreeRoleProblem` ← src/workflow/place/role-copy.ts:388 [EXTRACTED]
  ```
  export async function worktreeRoleProblem(input: { dir: string; step: string; role: string; tools: readonly string[]; delivery?: PullDelivery }): Promise<WorkflowFailure | undefined> {
  ```
- `cloneRoleProblem` ← src/workflow/place/role-copy.ts:421 [EXTRACTED]
  ```
  export async function cloneRoleProblem(input: { install: LocalConfig; step: string; role: string; tools: readonly string[] }): Promise<WorkflowFailure | undefined> {
  ```
- `releaseWorktreeRole` ← src/workflow/place/role-copy.ts:444 [EXTRACTED]
  ```
  export async function releaseWorktreeRole(dir: string): Promise<void> {
  ```
- `runSetup` ← src/workflow/place/setup.ts:57 [EXTRACTED]
  ```
  export async function runSetup({ expiresAt, signal: caller, ...run }: SetupRun): Promise<WorkflowFailure | undefined> {
  ```
- `commitWithout` ← src/workflow/place/team-without.ts:16 [EXTRACTED]
  ```
  export async function commitWithout(git: Git, { repo, revision, paths }: { repo: string; revision: string; paths: readonly string[] }): Promise<{ commit: string } | { failed: string }> {
  ```
- `teamKeyOf` ← src/workflow/place/team.ts:49 [EXTRACTED]
  ```
  export function teamKeyOf(branch: string): string {
  ```
- `teamClonesOf` ← src/workflow/place/team.ts:54 [EXTRACTED]
  ```
  export function teamClonesOf(config: LocalConfig, run: string): string {
  ```
- `removeTeamClone` ← src/workflow/place/team.ts:63 [EXTRACTED]
  ```
  export async function removeTeamClone(config: LocalConfig, run: RunId, branch: string): Promise<void> {
  ```
- `openTeamClone` ← src/workflow/place/team.ts:74 [EXTRACTED]
  ```
  export async function openTeamClone(input: { config: LocalConfig; run: RunId; step: string; branch: string }): Promise<TeamStart | WorkflowFailure> {
  ```
- `finishTeamClone` ← src/workflow/place/team.ts:252 [EXTRACTED]
  ```
  export async function finishTeamClone(input: {
  ```
- `pathsGitWouldCommit` ← src/workflow/place/worktree-snapshot.ts:57 [EXTRACTED]
  ```
  export function pathsGitWouldCommit(text: string): string[] {
  ```
- `commitPathsOf` ← src/workflow/place/worktree-snapshot.ts:62 [EXTRACTED]
  ```
  export async function commitPathsOf(dir: string, run: Git = git): Promise<{ paths: string[] } | { error: string }> {
  ```
- `mergeStagedPaths` ← src/workflow/place/worktree-snapshot.ts:75 [EXTRACTED]
  ```
  export function mergeStagedPaths(text: string): string[] {
  ```
- `mergeStagedPathsOf` ← src/workflow/place/worktree-snapshot.ts:88 [EXTRACTED]
  ```
  export async function mergeStagedPathsOf(dir: string, run: Git = git): Promise<{ paths: string[] } | { error: string }> {
  ```
- `snapshotWorktree` ← src/workflow/place/worktree-snapshot.ts:180 [EXTRACTED]
  ```
  export async function snapshotWorktree(workspace: string, run: Git, depth = 0): Promise<WorktreeSnapshot> {
  ```
- `changedPaths` ← src/workflow/place/worktree-snapshot.ts:227 [EXTRACTED]
  ```
  export function changedPaths(before: WorktreeSnapshot, after: WorktreeSnapshot): string[] {
  ```
- `mergeBranches` ← src/workflow/place/writer.ts:18 [EXTRACTED]
  ```
  export async function mergeBranches({ dir, run, step, executor, merge, git }: {
  ```
- `rememberConflicts` ← src/workflow/place/writer.ts:73 [EXTRACTED]
  ```
  export async function rememberConflicts(dir: string, run: Git): Promise<Record<string, string>> {
  ```
- `finishWriter` ← src/workflow/place/writer.ts:157 [EXTRACTED]
  ```
  export async function finishWriter(input: {
  ```
- `recordMergePreparation` ← src/workflow/place/writer.ts:235 [EXTRACTED]
  ```
  export async function recordMergePreparation(dir: string, git: Git): Promise<string | undefined> {
  ```
- `unreportedChangesMessage` ← src/workflow/place/writer.ts:289 [EXTRACTED]
  ```
  export function unreportedChangesMessage(step: string, dir: string, paths: readonly string[], because: string): string {
  ```
- `withUnpushed` ← src/workflow/place/writer.ts:294 [EXTRACTED]
  ```
  export function withUnpushed(message: string, unpushed: string | undefined): string {
  ```
- `EXEC_RUNTIME_TOOLS` ← src/workflow/runtimes/attempt.ts:40 [EXTRACTED]
  ```
  export const EXEC_RUNTIME_TOOLS = ['claude', 'codex', 'codebuddy'] as const satisfies readonly LaunchTool[];
  ```
- `credentialSecrets` ← src/workflow/runtimes/attempt.ts:43 [EXTRACTED]
  ```
  export function credentialSecrets(use: string, values: Record<string, string>): Record<string, string> {
  ```
- `isExecRuntimeTool` ← src/workflow/runtimes/attempt.ts:49 [EXTRACTED]
  ```
  export function isExecRuntimeTool(tool: string): tool is ExecRuntimeTool {
  ```
- `attemptRuntimePath` ← src/workflow/runtimes/attempt.ts:149 [EXTRACTED]
  ```
  export function attemptRuntimePath(config: LocalConfig, run: RunId, attempt: AttemptId): string {
  ```
- `attemptRuntimeFile` ← src/workflow/runtimes/attempt.ts:154 [EXTRACTED]
  ```
  export function attemptRuntimeFile(dir: string): string {
  ```
- `recordInProcessAttempt` ← src/workflow/runtimes/attempt.ts:189 [EXTRACTED]
  ```
  export async function recordInProcessAttempt(config: LocalConfig, run: RunId, attempt: AttemptId, { runtime, driver }: { runtime: string; driver: string }): Promise<void> {
  ```
- `recordInProcessSessionHome` ← src/workflow/runtimes/attempt.ts:198 [EXTRACTED]
  ```
  export async function recordInProcessSessionHome(config: LocalConfig, run: RunId, attempt: AttemptId, home: z.infer<typeof ToolHomeSchema>): Promise<void> {
  ```
- `readAttemptPlacement` ← src/workflow/runtimes/attempt.ts:229 [EXTRACTED]
  ```
  export function readAttemptPlacement(config: LocalConfig, run: RunId, attempt: AttemptId): Promise<AttemptPlacement> {
  ```
- `readAttemptPlacementAt` ← src/workflow/runtimes/attempt.ts:234 [EXTRACTED]
  ```
  export async function readAttemptPlacementAt(file: string): Promise<AttemptPlacement> {
  ```
- `isPlaceLeftOpen` ← src/workflow/runtimes/attempt.ts:249 [EXTRACTED]
  ```
  export function isPlaceLeftOpen(placement: AttemptPlacement): placement is Extract<AttemptPlacement, { kind: 'external' }> {
  ```
- `releaseAttemptRuntime` ← src/workflow/runtimes/attempt.ts:272 [EXTRACTED]
  ```
  export async function releaseAttemptRuntime(config: LocalConfig, run: RunId, attempt: AttemptId, record: AttemptRuntimeRecord): Promise<void> {
  ```
- `maskAttemptResults` ← src/workflow/runtimes/attempt.ts:282 [EXTRACTED]
  ```
  export async function maskAttemptResults(config: LocalConfig, run: RunId, secrets: Record<string, string>): Promise<void> {
  ```
- `attemptToolHome` ← src/workflow/runtimes/attempt.ts:295 [EXTRACTED]
  ```
  export function attemptToolHome(config: LocalConfig, run: RunId, attempt: AttemptId, tool: string): string {
  ```
- `attemptSessionStore` ← src/workflow/runtimes/attempt.ts:303 [EXTRACTED]
  ```
  export async function attemptSessionStore(config: LocalConfig, run: string, attempt: string | undefined): Promise<string | undefined> {
  ```
- `attemptHoldingSession` ← src/workflow/runtimes/attempt.ts:322 [EXTRACTED]
  ```
  export async function attemptHoldingSession(config: LocalConfig, run: string, session: { tool: string; id: string }): Promise<{ attempt: AttemptId; home: string; isOwn: boolean; storeDir: string } | undefined> {
  ```
- `HeldPlace` ← src/workflow/runtimes/attempt.ts:445 [EXTRACTED]
  ```
  export const HeldPlace = { conversationOf, hold, holdsOn, toRelease } as const;
  ```
- `seedToolHome` ← src/workflow/runtimes/attempt.ts:454 [EXTRACTED]
  ```
  export async function seedToolHome({ config, run, attempt, tool, sessions }: { config: LocalConfig; run: RunId; attempt: AttemptId; tool: string; sessions: SessionRef[] }): Promise<SessionRef | undefined> {
  ```
- `seedMemberModel` ← src/workflow/runtimes/attempt.ts:492 [EXTRACTED]
  ```
  export async function seedMemberModel({ tool, dir, memberHome }: { tool: ExecRuntimeTool; dir: string; memberHome: string }): Promise<void> {
  ```
- `toolHomeVariable` ← src/workflow/runtimes/attempt.ts:521 [EXTRACTED]
  ```
  export function toolHomeVariable(tool: string): string | undefined {
  ```
- `attemptRun` ← src/workflow/runtimes/attempt.ts:625 [EXTRACTED]
  ```
  export function attemptRun({ runtime, ...input }: { config: LocalConfig; run: RunId; attempt: AttemptId; runtime: StepRuntime<DriverCan>; entry: RuntimeEntryIdentity; driver: string; sources?: readonly RuntimeOrigin[]; deadline?: string }): AttemptRun {
  ```
- `stopCancelledAttempts` ← src/workflow/runtimes/cancelled.ts:49 [EXTRACTED]
  ```
  export async function stopCancelledAttempts(config: LocalConfig, lock: RunLock, { isRunnerHolding, release }: { isRunnerHolding: RunnerHolding; release?: AttemptId | undefined }): Promise<StoppedAttempts | undefined> {
  ```
- `heldPlaceOf` ← src/workflow/runtimes/cancelled.ts:161 [EXTRACTED]
  ```
  export function heldPlaceOf(placement: AttemptPlacement): HeldPlace | undefined {
  ```
- `placesMaybeHeld` ← src/workflow/runtimes/cancelled.ts:172 [EXTRACTED]
  ```
  export async function placesMaybeHeld(runs: string): Promise<PlaceMaybeHeld[]> {
  ```
- `stopLeftInProcess` ← src/workflow/runtimes/cancelled.ts:239 [EXTRACTED]
  ```
  export async function stopLeftInProcess(config: LocalConfig, run: RunId, attempt: AttemptId): Promise<LeftInProcess> {
  ```
- `endLeftLogins` ← src/workflow/runtimes/cancelled.ts:269 [EXTRACTED]
  ```
  export async function endLeftLogins(config: LocalConfig, run: RunId, attempt: AttemptId, placed: { toolHome?: AttemptRuntimeRecord['toolHome']; isCollected?: boolean } = {}): Promise<void> {
  ```
- `releaseHeldPlaces` ← src/workflow/runtimes/cancelled.ts:290 [EXTRACTED]
  ```
  export async function releaseHeldPlaces(config: LocalConfig, run: RunId, { checkout, continued, live }: {
  ```
- `closedForOffer` ← src/workflow/runtimes/cancelled.ts:313 [EXTRACTED]
  ```
  export async function closedForOffer(config: LocalConfig, run: RunId, options: { checkout: string; live?: Parameters<typeof releaseHeldPlaces>[2]['live'] }): Promise<string | undefined> {
  ```
- `stopOnRecordedDriver` ← src/workflow/runtimes/cancelled.ts:325 [EXTRACTED]
  ```
  export async function stopOnRecordedDriver(config: LocalConfig, run: RunId, attempt: AttemptId, { checkout }: { checkout: string }): Promise<WorkflowFailure | undefined> {
  ```
- `stopLeftOperationOnRuntime` ← src/workflow/runtimes/cancelled.ts:421 [EXTRACTED]
  ```
  export async function stopLeftOperationOnRuntime(config: LocalConfig, { run, attempt, checkout }: { run: RunId; attempt: AttemptId; checkout: string }): Promise<{ kind: 'stopped' | 'none' } | { kind: 'running'; why: string }> {
  ```
- `stopLeftAttempt` ← src/workflow/runtimes/cancelled.ts:450 [EXTRACTED]
  ```
  export async function stopLeftAttempt(config: LocalConfig, run: RunId, attempt: AttemptId, checkout: string): Promise<string | undefined> {
  ```
- `closeAfterSweep` ← src/workflow/runtimes/cancelled.ts:478 [EXTRACTED]
  ```
  export async function closeAfterSweep(config: LocalConfig, runs: readonly RunId[]): Promise<void> {
  ```
- `composedOffer` ← src/workflow/runtimes/composed.ts:38 [EXTRACTED]
  ```
  export function composedOffer(outer: Offer, inner: Offer): Offer {
  ```
- `nestedOptions` ← src/workflow/runtimes/composed.ts:102 [EXTRACTED]
  ```
  export function nestedOptions(options: RuntimeOptions, names: { outer: string; inner: string }): { ok: true; outer: RuntimeOptions; inner: RuntimeOptions } | { ok: false; key: string; message: string } {
  ```
- `composedStepRuntime` ← src/workflow/runtimes/composed.ts:123 [EXTRACTED]
  ```
  export function composedStepRuntime({ outer, inner, innerCredentials }: { outer: StepRuntime<DriverCan>; inner: StepRuntime<DriverCan>; innerCredentials: Record<string, string> }): StepRuntime<DriverCan> {
  ```
- `SANDBOX_RUNTIME` ← src/workflow/runtimes/definitions.ts:53 [EXTRACTED]
  ```
  export const SANDBOX_RUNTIME = 'sandbox';
  ```
- `DriverDefinitionSchema` ← src/workflow/runtimes/definitions.ts:71 [EXTRACTED]
  ```
  export const DriverDefinitionSchema = z.object({
  ```
- `parseDriverDefinition` ← src/workflow/runtimes/definitions.ts:117 [EXTRACTED]
  ```
  export function parseDriverDefinition(file: string, text: string, location = file): { ok: true; definition: DriverDefinition } | { ok: false; failure: WorkflowFailure } {
  ```
- `resolveDriver` ← src/workflow/runtimes/definitions.ts:239 [EXTRACTED]
  ```
  export async function resolveDriver(config: LocalConfig, name: string, { personal }: { personal: boolean }): Promise<{ ok: true; driver: ResolvedDriver } | { ok: false; failure: WorkflowFailure }> {
  ```
- `SameNameSchema` ← src/workflow/runtimes/entry-identity.ts:39 [EXTRACTED]
  ```
  export const SameNameSchema = z.object({ at: z.number().int().positive(), of: z.number().int().positive() });
  ```
- `composedName` ← src/workflow/runtimes/entry-identity.ts:57 [EXTRACTED]
  ```
  export function composedName(inner: string, outer: string): string {
  ```
- `RuntimeEntryIdentity` ← src/workflow/runtimes/entry-identity.ts:148 [EXTRACTED]
  ```
  export const RuntimeEntryIdentity = { of, holds, isChangedSince, find, entryOf } as const;
  ```
- `HeldStepsSchema` ← src/workflow/runtimes/held.ts:16 [EXTRACTED]
  ```
  export const HeldStepsSchema = z.object({
  ```
- `readHeldSteps` ← src/workflow/runtimes/held.ts:30 [EXTRACTED]
  ```
  export async function readHeldSteps(config: LocalConfig, run: RunId): Promise<HeldSteps | undefined> {
  ```
- `writeHeldSteps` ← src/workflow/runtimes/held.ts:39 [EXTRACTED]
  ```
  export async function writeHeldSteps(config: LocalConfig, run: RunId, held: HeldSteps): Promise<void> {
  ```
- `answerCallTool` ← src/workflow/runtimes/host.ts:58 [EXTRACTED]
  ```
  export async function answerCallTool({ config, resolveTool }: { config: LocalConfig; resolveTool?: ToolCallerDeps['resolveTool'] }): Promise<string | undefined> {
  ```
- `checkHostOptions` ← src/workflow/runtimes/host.ts:145 [EXTRACTED]
  ```
  export function checkHostOptions(options: RuntimeOptions): { ok: true } | { ok: false; failure: { code: 'bad_option'; key: string; message: string } } {
  ```
- `hostStepRuntime` ← src/workflow/runtimes/host.ts:159 [EXTRACTED]
  ```
  export function hostStepRuntime({ config, can = {} }: { config: LocalConfig; can?: DriverCan }): HostStepRuntime {
  ```
- `PERSONAL_DIRS` ← src/workflow/runtimes/layers.ts:20 [EXTRACTED]
  ```
  export const PERSONAL_DIRS = { drivers: 'drivers', runtimes: 'runtimes', sandboxes: 'sandboxes', tools: PERSONAL_TOOLS_DIR } as const;
  ```
- `SHIPPED_PREFIX` ← src/workflow/runtimes/layers.ts:23 [EXTRACTED]
  ```
  export const SHIPPED_PREFIX = 'teamai-';
  ```
- `personalDir` ← src/workflow/runtimes/layers.ts:30 [EXTRACTED]
  ```
  export function personalDir(kind: keyof typeof PERSONAL_DIRS): string {
  ```
- `teamTreeOf` ← src/workflow/runtimes/layers.ts:38 [EXTRACTED]
  ```
  export function teamTreeOf(config: LocalConfig): TeamTree {
  ```
- `namesOf` ← src/workflow/runtimes/layers.ts:43 [EXTRACTED]
  ```
  export function namesOf(asked: string): string[] {
  ```
- `findInLayers` ← src/workflow/runtimes/layers.ts:196 [EXTRACTED]
  ```
  export async function findInLayers(kind: LayeredKind, names: readonly string[], { personal, teams, teamai = true }: { personal: boolean; teams: readonly LocalConfig[]; teamai?: boolean }): Promise<LayerFind> {
  ```
- `RUNTIME_MARKER` ← src/workflow/runtimes/locate.ts:36 [EXTRACTED]
  ```
  export const RUNTIME_MARKER = RESOURCE_LAYOUTS.runtimes.marker;
  ```
- `builtInRuntime` ← src/workflow/runtimes/locate.ts:103 [EXTRACTED]
  ```
  export function builtInRuntime(use: string): BuiltInRuntime | undefined {
  ```
- `fixOf` ← src/workflow/runtimes/locate.ts:118 [EXTRACTED]
  ```
  export function fixOf(layer: RuntimeLayer): string {
  ```
- `locateRuntime` ← src/workflow/runtimes/locate.ts:300 [EXTRACTED]
  ```
  export async function locateRuntime(driver: ResolvedDriver, use: string): Promise<{ ok: true; source: RuntimeSource } | { ok: false; failure: WorkflowFailure }> {
  ```
- `askAtTerminal` ← src/workflow/runtimes/locate.ts:361 [EXTRACTED]
  ```
  export async function askAtTerminal(question: string): Promise<boolean | undefined> {
  ```
- `pinRuntime` ← src/workflow/runtimes/locate.ts:419 [EXTRACTED]
  ```
  export async function pinRuntime(source: ExternalRuntime, { config }: { config: LocalConfig }): Promise<PinnedRuntime | { ok: false; failure: WorkflowFailure }> {
  ```
- `pinFolder` ← src/workflow/runtimes/locate.ts:459 [EXTRACTED]
  ```
  export async function pinFolder(dir: string, { config }: { config: LocalConfig }): Promise<{ ok: true; copy: string; remove: () => Promise<void> } | { ok: false; problem: PinProblem }> {
  ```
- `isRuntimeAccepted` ← src/workflow/runtimes/locate.ts:490 [EXTRACTED]
  ```
  export async function isRuntimeAccepted(source: ExternalRuntime): Promise<boolean> {
  ```
- `acceptRuntime` ← src/workflow/runtimes/locate.ts:499 [EXTRACTED]
  ```
  export async function acceptRuntime(source: RuntimeSource, { mode, canAsk, ask = askAtTerminal }: { mode: RunMode; canAsk: boolean; ask?: (question: string) => Promise<boolean | undefined> }): Promise<Acceptance> {
  ```
- `LOGIN_TOOLS` ← src/workflow/runtimes/login.ts:33 [EXTRACTED]
  ```
  export const LOGIN_TOOLS = ['codex'] as const satisfies readonly LaunchTool[];
  ```
- `loginFileOf` ← src/workflow/runtimes/login.ts:49 [EXTRACTED]
  ```
  export function loginFileOf(tool: string): string | undefined {
  ```
- `loginHome` ← src/workflow/runtimes/login.ts:56 [EXTRACTED]
  ```
  export function loginHome(tool: LoginTool): string {
  ```
- `loginCommand` ← src/workflow/runtimes/login.ts:61 [EXTRACTED]
  ```
  export function loginCommand(tool: LoginTool): string {
  ```
- `loginLockFile` ← src/workflow/runtimes/login.ts:80 [EXTRACTED]
  ```
  export function loginLockFile(tool: LoginTool): string {
  ```
- `LoginLockSchema` ← src/workflow/runtimes/login.ts:89 [EXTRACTED]
  ```
  export const LoginLockSchema = z.object({
  ```
- `loginHolder` ← src/workflow/runtimes/login.ts:118 [EXTRACTED]
  ```
  export async function loginHolder(tool: LoginTool): Promise<LoginLock | undefined> {
  ```
- `loginWaitFile` ← src/workflow/runtimes/login.ts:190 [EXTRACTED]
  ```
  export function loginWaitFile(attemptDirectory: string): string {
  ```
- `LoginWaitSchema` ← src/workflow/runtimes/login.ts:194 [EXTRACTED]
  ```
  export const LoginWaitSchema = z.object({ tool: z.enum(LOGIN_TOOLS), holder: z.object({ run: z.string(), attempt: z.string() }) });
  ```
- `holdLogin` ← src/workflow/runtimes/login.ts:205 [EXTRACTED]
  ```
  export async function holdLogin({ tool, run, attempt, toolHome, from = dedicatedSource(tool), signal, onWait }: {
  ```
- `ensureLogin` ← src/workflow/runtimes/login.ts:277 [EXTRACTED]
  ```
  export function ensureLogin(tool: LoginTool, input: { step: { run: string; id: string }; canAsk: boolean }): Promise<WorkflowFailure | undefined> {
  ```
- `endLogin` ← src/workflow/runtimes/login.ts:391 [EXTRACTED]
  ```
  export async function endLogin(tool: LoginTool, { run, attempt, toolHome, from = dedicatedSource(tool), isCollected }: { run: RunId; attempt: AttemptId; toolHome: string; from?: LoginSource; isCollected: boolean }): Promise<EndedLogin> {
  ```
- `holdLoginFrom` ← src/workflow/runtimes/login.ts:471 [EXTRACTED]
  ```
  export async function holdLoginFrom({ tool, executable, from, toolHome, run, attempt, signal }: {
  ```
- `parseRuntimeLine` ← src/workflow/runtimes/protocol.ts:31 [EXTRACTED]
  ```
  export function parseRuntimeLine(line: string): { ok: true; message: RuntimeMessage } | { ok: false; reason: string } {
  ```
- `folderEntries` ← src/workflow/runtimes/resource-folder.ts:13 [EXTRACTED]
  ```
  export async function folderEntries(dir: string): Promise<string[]> {
  ```
- `firstLink` ← src/workflow/runtimes/resource-folder.ts:30 [EXTRACTED]
  ```
  export async function firstLink(dir: string): Promise<{ ok: true; link?: string } | { ok: false; reason: string }> {
  ```
- `folderRevision` ← src/workflow/runtimes/resource-folder.ts:47 [EXTRACTED]
  ```
  export async function folderRevision(dir: string): Promise<string> {
  ```
- `stepArgument` ← src/workflow/runtimes/retry-command.ts:4 [EXTRACTED]
  ```
  export function stepArgument(step: string): string {
  ```
- `retryCommand` ← src/workflow/runtimes/retry-command.ts:9 [EXTRACTED]
  ```
  export function retryCommand({ run, step }: { run: string; step: string }): string {
  ```
- `resumeOrPublish` ← src/workflow/runtimes/retry-command.ts:14 [EXTRACTED]
  ```
  export function resumeOrPublish(run: string): string {
  ```
- `withRetry` ← src/workflow/runtimes/retry-command.ts:25 [EXTRACTED]
  ```
  export function withRetry({ code, message }: { code: string; message: string }, retry: { run: string; step: string }): string {
  ```
- `SANDBOX_MARKER` ← src/workflow/runtimes/sandbox-profiles.ts:25 [EXTRACTED]
  ```
  export const SANDBOX_MARKER = RESOURCE_LAYOUTS.sandboxes.marker;
  ```
- `locateSandboxProfile` ← src/workflow/runtimes/sandbox-profiles.ts:154 [EXTRACTED]
  ```
  export async function locateSandboxProfile(driver: ResolvedDriver, named: string | undefined): Promise<{ ok: true; profile: SandboxProfile } | { ok: false; failure: WorkflowFailure }> {
  ```
- `sandboxOptions` ← src/workflow/runtimes/sandbox-profiles.ts:191 [EXTRACTED]
  ```
  export async function sandboxOptions({ driver, named, given, from, isEntryEditable }: { driver: ResolvedDriver; named: string | undefined; given: RuntimeOptions; from: string; isEntryEditable: boolean }): Promise<{ ok: true; options: RuntimeOptions; profile: SandboxProfile } | { ok: false; failure: WorkflowFailure }> {
  ```
- `pinSandboxProfile` ← src/workflow/runtimes/sandbox-profiles.ts:227 [EXTRACTED]
  ```
  export async function pinSandboxProfile(driver: ResolvedDriver, profile: SandboxProfile): Promise<{ ok: true; options: RuntimeOptions; profile: SandboxProfile; remove: () => Promise<void> } | { ok: false; failure: WorkflowFailure }> {
  ```
- `toolsLaunchDeps` ← src/workflow/runtimes/sources.ts:46 [EXTRACTED]
  ```
  export function toolsLaunchDeps(): StepLaunchDeps {
  ```
- `engineOptions` ← src/workflow/runtimes/sources.ts:88 [EXTRACTED]
  ```
  export function engineOptions(options: RuntimeOptions): { ok: true; engine: EngineOptions; credentials: EnvCredential[]; runtime: RuntimeOptions } | { ok: false; key: string; message: string } {
  ```
- `credentialsForTool` ← src/workflow/runtimes/sources.ts:159 [EXTRACTED]
  ```
  export function credentialsForTool(credentials: Record<string, string>, found: readonly string[], tool: string): Record<string, string> {
  ```
- `disposeDriver` ← src/workflow/runtimes/sources.ts:217 [EXTRACTED]
  ```
  export async function disposeDriver(opened: OpenedDriver): Promise<void> {
  ```
- `homeEnvOf` ← src/workflow/runtimes/sources.ts:299 [EXTRACTED]
  ```
  export function homeEnvOf(instances: readonly InitInstance[]): InitHomeEnv {
  ```
- `openDriver` ← src/workflow/runtimes/sources.ts:607 [EXTRACTED]
  ```
  export async function openDriver(
  ```
- `sandboxEntryChecks` ← src/workflow/runtimes/sources.ts:669 [EXTRACTED]
  ```
  export async function sandboxEntryChecks(config: LocalConfig, name: string, checkout: string): Promise<SandboxEntryCheck[]> {
  ```
- `checkDriver` ← src/workflow/runtimes/sources.ts:703 [EXTRACTED]
  ```
  export async function checkDriver(config: LocalConfig, name: string, checkout: string): Promise<{ ok: true } | { ok: false; failure: WorkflowFailure }> {
  ```
- `ANSWER_WITHIN_MS` ← src/workflow/runtimes/stdio.ts:27 [EXTRACTED]
  ```
  export const ANSWER_WITHIN_MS = 15_000;
  ```
- `stdioStepRuntime` ← src/workflow/runtimes/stdio.ts:147 [EXTRACTED]
  ```
  export function stdioStepRuntime({ name, command, args = [], cwd, secrets = {} }: { name: string; command: string; args?: string[]; cwd?: string; secrets?: Record<string, string> }): StepRuntime<DriverCan> {
  ```
- `createToolCaller` ← src/workflow/runtimes/tool-caller.ts:117 [EXTRACTED]
  ```
  export function createToolCaller({ resolveTool = resolveCliPath, resolveScope = scopeHere }: ToolCallerDeps = {}): ToolCaller {
  ```
- `settleGitLocks` ← src/workflow/steps/git-locks.ts:20 [EXTRACTED]
  ```
  export async function settleGitLocks({ cwd, place }: { cwd: string; place: GitLockPlace }): Promise<string[]> {
  ```
- `keptLocksNotice` ← src/workflow/steps/git-locks.ts:53 [EXTRACTED]
  ```
  export function keptLocksNotice(locks: string[], tool: string): string {
  ```
- `launchToolFor` ← src/workflow/steps/prompt.ts:114 [EXTRACTED]
  ```
  export function launchToolFor(step: Pick<WorkflowStep, 'agent' | 'tool'>, config: LocalConfig, flags: Record<string, string>, members: MemberTool[], runtimeDefault?: string): LaunchChoice {
  ```
- `failureReport` ← src/workflow/steps/prompt.ts:153 [EXTRACTED]
  ```
  export function failureReport(failure: WorkflowFailure): FailedReport {
  ```
- `promptOfferOf` ← src/workflow/steps/prompt.ts:264 [EXTRACTED]
  ```
  export function promptOfferOf(opened: OpenedForPrompt): PromptOffer {
  ```
- `promptRuntimeOn` ← src/workflow/steps/prompt.ts:272 [EXTRACTED]
  ```
  export function promptRuntimeOn({ run, offered, teamEnv, conversationHeld }: { run: AttemptRun; offered: PromptOffer; teamEnv: WorkflowEnv; conversationHeld?: PromptRuntime['conversationHeld'] }): PromptRuntime {
  ```
- `runPromptStep` ← src/workflow/steps/prompt.ts:282 [EXTRACTED]
  ```
  export async function runPromptStep({ config, lock, driver, lease, adapter = stepLauncher(toolsLaunchDeps()), tools = {}, toolPaths, archive, signal, mode, staged, secrets, askPerson, onRuntime }: {
  ```
- `placeView` ← src/workflow/steps/runtime-steps.ts:41 [EXTRACTED]
  ```
  export async function placeView(config: LocalConfig, run: RunId, lease: Pick<LeaseWire, 'attempt' | 'env'>, cwd: string, toolHome: ToolCommandEnv = {}): Promise<PlaceView> {
  ```
- `runtimeStepEnv` ← src/workflow/steps/runtime-steps.ts:74 [EXTRACTED]
  ```
  export function runtimeStepEnv(lease: Pick<LeaseWire, 'envScope' | 'env' | 'attempt'>, scoped: NodeJS.ProcessEnv, { config, run, mode }: { config: LocalConfig; run: RunId; mode: RunMode }): StepEnv {
  ```
- `runtimeCommand` ← src/workflow/steps/runtime-steps.ts:112 [EXTRACTED]
  ```
  export function runtimeCommand(input: {
  ```
- `failedCommand` ← src/workflow/steps/runtime-steps.ts:181 [EXTRACTED]
  ```
  export function failedCommand(failure: WorkflowFailure): StartedCommand {
  ```
- `runtimeSetup` ← src/workflow/steps/runtime-steps.ts:197 [EXTRACTED]
  ```
  export function runtimeSetup(run: AttemptRun) {
  ```
- `runtimeLauncher` ← src/workflow/steps/runtime-steps.ts:251 [EXTRACTED]
  ```
  export function runtimeLauncher(run: AttemptRun, { view, tool, toolHome, unset, credentials, setUp }: { view: PlaceView; tool: string; toolHome: { tool: string; dir: string }; unset: string[]; credentials: Record<string, string>; setUp: SetUp }): ToolLauncher {
  ```
- `runtimePrompter` ← src/workflow/steps/runtime-steps.ts:339 [EXTRACTED]
  ```
  export function runtimePrompter(run: AttemptRun, { view, runId, step, tool, provided, unset, credentials, setUp, isThroughOuter, continues, toolHome }: {
  ```
- `LINEBREAKS` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-ast.ts:7 [EXTRACTED]
  ```
  export const LINEBREAKS = new Set(["\r\n", "\r", "\n", "\u2028", "\u2029"]);
  ```
- `isClosingBraceToken` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-ast.ts:10 [EXTRACTED]
  ```
  export const isClosingBraceToken = (token: Token): boolean =>
  ```
- `isSemicolonToken` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-ast.ts:14 [EXTRACTED]
  ```
  export const isSemicolonToken = (token: Token): boolean =>
  ```
- `isNotSemicolonToken` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-ast.ts:18 [EXTRACTED]
  ```
  export const isNotSemicolonToken = (token: Token): boolean => !isSemicolonToken(token);
  ```
- `isTokenOnSameLine` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-ast.ts:21 [EXTRACTED]
  ```
  export const isTokenOnSameLine = (left: { loc: Location }, right: { loc: Location }): boolean =>
  ```
- `isFunction` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-ast.ts:25 [EXTRACTED]
  ```
  export const isFunction = (node: ESTree.Node): boolean =>
  ```
- `isSingleLine` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-ast.ts:31 [EXTRACTED]
  ```
  export const isSingleLine = (node: ESTree.Node): boolean =>
  ```
- `skipChainExpression` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-ast.ts:35 [EXTRACTED]
  ```
  export const skipChainExpression = (node: ESTree.Node): ESTree.Node =>
  ```
- `isTopLevelExpressionStatement` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-ast.ts:39 [EXTRACTED]
  ```
  export const isTopLevelExpressionStatement = (
  ```
- `isParenthesized` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-ast.ts:47 [EXTRACTED]
  ```
  export function isParenthesized(node: ESTree.Node, sourceCode: SourceCode): boolean {
  ```
- `createPaddingLineRule` ← oxlint-plugin-teamai/anti-slop/vendor/eslint-stylistic/padding-line-between-statements.ts:612 [EXTRACTED]
  ```
  export default function createPaddingLineRule<Extra extends string = never>(
  ```
- `paseoHome` ← packages/runtime-paseo/src/daemon/address.ts:45 [EXTRACTED]
  ```
  export const paseoHome = (env: NodeJS.ProcessEnv): string => path.resolve(expandHome(env.PASEO_HOME || '~/.paseo'));
  ```
- `daemonUrl` ← packages/runtime-paseo/src/daemon/address.ts:52 [EXTRACTED]
  ```
  export function daemonUrl(env: NodeJS.ProcessEnv): { url: string } | RuntimeFailure {
  ```
- `isOnThisMachine` ← packages/runtime-paseo/src/daemon/address.ts:90 [EXTRACTED]
  ```
  export function isOnThisMachine(url: string): boolean {
  ```
- `clientInApp` ← packages/runtime-paseo/src/daemon/app-client.ts:143 [EXTRACTED]
  ```
  export function clientInApp(cli: string, { keep, unpackInto }: { keep: string; unpackInto?: string }): { dir: string } | RuntimeFailure | undefined {
  ```
- `OLDEST_PASEO` ← packages/runtime-paseo/src/daemon/client.ts:34 [EXTRACTED]
  ```
  export const OLDEST_PASEO = '0.14.0';
  ```
- `atLeast` ← packages/runtime-paseo/src/daemon/client.ts:37 [EXTRACTED]
  ```
  export function atLeast(version: string, floor: string): boolean {
  ```
- `loadClient` ← packages/runtime-paseo/src/daemon/client.ts:165 [EXTRACTED]
  ```
  export async function loadClient(env: NodeJS.ProcessEnv, { unpackInto }: { unpackInto?: string } = {}): Promise<PaseoClient | RuntimeFailure> {
  ```
- `codexHomes` ← packages/runtime-paseo/src/daemon/connect.ts:133 [EXTRACTED]
  ```
  export function codexHomes({ providerHome, homeDir }: { providerHome: string | undefined; homeDir: string }): string[] {
  ```
- `connect` ← packages/runtime-paseo/src/daemon/connect.ts:387 [EXTRACTED]
  ```
  export async function connect(url: string, paseo: PaseoClient, abandoned?: AbortSignal): Promise<Daemon | RuntimeFailure> {
  ```
- `savedHosts` ← packages/runtime-paseo/src/daemon/host.ts:32 [EXTRACTED]
  ```
  export async function savedHosts(api: PaseoApi): Promise<SavedHost[]> {
  ```
- `routedHost` ← packages/runtime-paseo/src/daemon/host.ts:39 [EXTRACTED]
  ```
  export async function routedHost(api: PaseoApi, paseo: PaseoClient, serverId: string): Promise<Host> {
  ```
- `claudeHomeIn` ← packages/runtime-paseo/src/daemon/sign-in.ts:14 [EXTRACTED]
  ```
  export function claudeHomeIn(diagnostic: string): string | undefined {
  ```
- `signInStep` ← packages/runtime-paseo/src/daemon/sign-in.ts:50 [EXTRACTED]
  ```
  export function signInStep({ runsIn, command, login }: { runsIn: RunsIn | undefined; command: string; login: string }): string {
  ```
- `codexLoginStatus` ← packages/runtime-paseo/src/daemon/sign-in.ts:59 [EXTRACTED]
  ```
  export function codexLoginStatus(codex: string, env?: NodeJS.ProcessEnv): Promise<{ code: number; answer: string }> {
  ```
- `isCodexExecutable` ← packages/runtime-paseo/src/daemon/sign-in.ts:97 [EXTRACTED]
  ```
  export function isCodexExecutable(resolved: string, platform: NodeJS.Platform = process.platform, name = 'codex'): boolean {
  ```
- `packAsar` ← packages/runtime-paseo/src/testing/asar.ts:26 [EXTRACTED]
  ```
  export function packAsar(file: string, files: Map<string, Buffer>, corrupt?: string): void {
  ```
- `clientClosure` ← packages/runtime-paseo/src/testing/asar.ts:82 [EXTRACTED]
  ```
  export function clientClosure(client: string): Map<string, Buffer> {
  ```
- `paseoApp` ← packages/runtime-paseo/src/testing/asar.ts:104 [EXTRACTED]
  ```
  export function paseoApp(dir: string, client: string, corrupt?: string): string {
  ```
- `serveAttemptSocket` ← packages/runtime-paseo/src/testing/attempt-socket.ts:44 [EXTRACTED]
  ```
  export async function serveAttemptSocket({ grants = true, holdUntil }: { grants?: boolean; holdUntil?: string } = {}): Promise<FakeAttemptSocket> {
  ```
- `writeFakeWrapper` ← packages/runtime-paseo/src/testing/attempt-socket.ts:120 [EXTRACTED]
  ```
  export function writeFakeWrapper({ bin, tool, socket }: { bin: string; tool: string; socket: string }): string {
  ```
- `startFakeDaemon` ← packages/runtime-paseo/src/testing/fake-daemon.ts:328 [EXTRACTED]
  ```
  export async function startFakeDaemon({ state, port, socket: socketPath }: { state: string; port: number; socket?: string }): Promise<{ url: string; close(): Promise<void> }> {
  ```
- `bundleRuntime` ← packages/runtime-paseo/src/testing/harness.ts:20 [EXTRACTED]
  ```
  export async function bundleRuntime(dir: string): Promise<string> {
  ```
- `TEST_CLIENT` ← packages/runtime-paseo/src/testing/harness.ts:43 [EXTRACTED]
  ```
  export const TEST_CLIENT = path.join(ROOT, 'node_modules', '@getpaseo', 'client');
  ```
- `startRuntime` ← packages/runtime-paseo/src/testing/harness.ts:49 [EXTRACTED]
  ```
  export function startRuntime(executable: string, home: string, env: Record<string, string | undefined> = {}): Runtime {
  ```
- `RUN` ← packages/runtime-paseo/src/testing/suite.ts:29 [EXTRACTED]
  ```
  export const RUN = 'r0123abcd';
  ```
- `ATTEMPT` ← packages/runtime-paseo/src/testing/suite.ts:30 [EXTRACTED]
  ```
  export const ATTEMPT = 'a0123abcd';
  ```
- `restartDaemon` ← packages/runtime-paseo/src/testing/suite.ts:33 [EXTRACTED]
  ```
  export async function restartDaemon(at: { port: number; socket?: string }): Promise<void> {
  ```
- `behave` ← packages/runtime-paseo/src/testing/suite.ts:37 [EXTRACTED]
  ```
  export const behave = (behaviour: Behaviour): void => fs.writeFileSync(path.join(daemonState, 'behaviour.json'), JSON.stringify(behaviour));
  ```
- `received` ← packages/runtime-paseo/src/testing/suite.ts:46 [EXTRACTED]
  ```
  export const received = () => {
  ```
- `createdAgent` ← packages/runtime-paseo/src/testing/suite.ts:53 [EXTRACTED]
  ```
  export const createdAgent = (op: string): string => z.string().parse(received().find((request) => request.type === 'agent.create.request' && request.idempotencyKey === op)?.agentId);
  ```
- `stopped` ← packages/runtime-paseo/src/testing/suite.ts:56 [EXTRACTED]
  ```
  export const stopped = (): unknown[] => {
  ```
- `waitedOn` ← packages/runtime-paseo/src/testing/suite.ts:63 [EXTRACTED]
  ```
  export const waitedOn = (agentId: string): boolean => {
  ```
- `start` ← packages/runtime-paseo/src/testing/suite.ts:69 [EXTRACTED]
  ```
  export const start = (env?: Record<string, string | undefined>): Runtime => {
  ```
- `isOp` ← packages/runtime-paseo/src/testing/suite.ts:76 [EXTRACTED]
  ```
  export const isOp = (op: string, event: string) => (line: RuntimeMessage): boolean => 'op' in line && line.op === op && 'event' in line && line.event === event;
  ```
- `isEnd` ← packages/runtime-paseo/src/testing/suite.ts:77 [EXTRACTED]
  ```
  export const isEnd = (op: string) => (line: RuntimeMessage): boolean => 'op' in line && line.op === op && 'event' in line && ['finished', 'failed', 'cancelled'].includes(line.event);
  ```
- `isInit` ← packages/runtime-paseo/src/testing/suite.ts:78 [EXTRACTED]
  ```
  export const isInit = (line: RuntimeMessage): boolean => 'type' in line && line.type === 'init';
  ```
- `ready` ← packages/runtime-paseo/src/testing/suite.ts:87 [EXTRACTED]
  ```
  export async function ready(runtime: Runtime, { mode = 'unattended', options = { url: daemon.url }, instances, homeEnv = SHIPPED_HOME_ENV }: { mode?: RuntimeMode; options?: RuntimeOptions; instances?: PassedInstance[]; homeEnv?: InitHomeEnv } = {}): Promise<RuntimeMessage> {
  ```
- `openRequest` ← packages/runtime-paseo/src/testing/suite.ts:95 [EXTRACTED]
  ```
  export const openRequest = (op: string, attempt: string, tool?: string) => ({
  ```
- `opened` ← packages/runtime-paseo/src/testing/suite.ts:100 [EXTRACTED]
  ```
  export async function opened(runtime: Runtime, { attempt = ATTEMPT, op = 'op-0000000a', tool }: { attempt?: string; op?: string; tool?: string } = {}): Promise<string> {
  ```
- `journalFiles` ← packages/runtime-paseo/src/testing/suite.ts:111 [EXTRACTED]
  ```
  export const journalFiles = (): string[] => {
  ```
- `agentsOf` ← packages/runtime-paseo/src/testing/suite.ts:118 [EXTRACTED]
  ```
  export const agentsOf = (): string[] => {
  ```
- `mayStartMessage` ← packages/runtime-paseo/src/testing/suite.ts:125 [EXTRACTED]
  ```
  export const mayStartMessage = (agentId: string): string => `Paseo does not show the claude agent ${agentId} yet, though its create was sent, so it may still start in the worktree. Once it appears, run teamai workflow cancel ${RUN} again, which stops it. If it never appears in Paseo, the create was refused: check that nothing of the attempt runs in the worktree, then run teamai workflow cancel ${RUN} --release ${ATTEMPT}.`;
  ```
- `delay` ← packages/runtime-paseo/src/testing/suite.ts:127 [EXTRACTED]
  ```
  export const delay = (ms: number): Promise<void> => new Promise((resolve) => setTimeout(resolve, ms));
  ```
- `cannotRun` ← packages/runtime-paseo/src/testing/suite.ts:130 [EXTRACTED]
  ```
  export const cannotRun = (tool: string, reason: string): string => `The Paseo daemon at ${daemon.url} cannot run ${tool}: ${reason}.`;
  ```
- `notInstalled` ← packages/runtime-paseo/src/testing/suite.ts:133 [EXTRACTED]
  ```
  export const notInstalled = (tool: string): string => `it is not installed where the daemon finds its tools; install ${tool} on the daemon's PATH and sign in to it there`;
  ```
- `until` ← packages/runtime-paseo/src/testing/suite.ts:136 [EXTRACTED]
  ```
  export async function until(holds: () => boolean, ms = 10_000): Promise<void> {
  ```
- `worktreeWorkspace` ← packages/runtime-paseo/src/testing/suite.ts:141 [EXTRACTED]
  ```
  export const worktreeWorkspace = (): string | undefined => DaemonStateSchema.parse(JSON.parse(fs.readFileSync(path.join(daemonState, 'agents.json'), 'utf8'))).workspaces[fs.realpathSync(worktree)];
  ```
- `promptRequest` ← packages/runtime-paseo/src/testing/suite.ts:144 [EXTRACTED]
  ```
  export const promptRequest = (handle: string, op: string, lease: Partial<z.input<typeof PromptLeaseSchema>> = {}): z.input<typeof PromptRequestSchema> => ({
  ```
- `useRuntimeSuite` ← packages/runtime-paseo/src/testing/suite.ts:154 [EXTRACTED]
  ```
  export function useRuntimeSuite(): void {
  ```
- `argsOf` ← packages/runtime-sandbox/src/providers/bwrap.ts:79 [EXTRACTED]
  ```
  export function argsOf({ argv, cwd, writable, readable, gitPaths, isDetached }: Pick<Sandboxed, 'argv' | 'cwd' | 'writable' | 'readable' | 'gitPaths' | 'isDetached'>): string[] {
  ```
- `LAUNCHABLE` ← packages/runtime-sandbox/src/providers/cli.ts:26 [EXTRACTED]
  ```
  export const LAUNCHABLE = ['claude', 'codex', 'codebuddy', 'opencode'] as const;
  ```
- `heldProbe` ← packages/runtime-sandbox/src/providers/cli.ts:32 [EXTRACTED]
  ```
  export function heldProbe(commands: readonly string[]): string[] {
  ```
- `commandsOf` ← packages/runtime-sandbox/src/providers/cli.ts:37 [EXTRACTED]
  ```
  export function commandsOf(instances: ReadonlyArray<Pick<InitInstance, 'command'>>): string[] {
  ```
- `cliOf` ← packages/runtime-sandbox/src/providers/cli.ts:63 [EXTRACTED]
  ```
  export function cliOf({ name, env, notInstalled }: { name: string; env: NodeJS.ProcessEnv; notInstalled: string }): Cli {
  ```
- `signalled` ← packages/runtime-sandbox/src/providers/cli.ts:106 [EXTRACTED]
  ```
  export function signalled({ exec, argv }: { exec: readonly string[]; argv: readonly string[] }) {
  ```
- `definedOnly` ← packages/runtime-sandbox/src/providers/cli.ts:116 [EXTRACTED]
  ```
  export function definedOnly(env: NodeJS.ProcessEnv): Record<string, string> {
  ```
- `mountsOf` ← packages/runtime-sandbox/src/providers/cli.ts:131 [EXTRACTED]
  ```
  export function mountsOf(name: string, view: PlaceView): { ok: true; mounts: Mount[] } | { ok: false; failure: RuntimeFailure } {
  ```
- `unmountable` ← packages/runtime-sandbox/src/providers/cli.ts:144 [EXTRACTED]
  ```
  export function unmountable(name: string, at: string): RuntimeFailure | undefined {
  ```
- `IDLE` ← packages/runtime-sandbox/src/providers/container.ts:62 [EXTRACTED]
  ```
  export const IDLE = `mkdir -p "$HOME"; trap 'exit 0' TERM INT; while :; do sleep 3600 & wait $!; done`;
  ```
- `containerNamed` ← packages/runtime-sandbox/src/providers/container.ts:85 [EXTRACTED]
  ```
  export function containerNamed(name: string): { kind: 'place' | 'filter' | 'network'; key: PlaceKey } | undefined {
  ```
- `containerProvider` ← packages/runtime-sandbox/src/providers/container.ts:183 [EXTRACTED]
  ```
  export function containerProvider({ engine, image, owner, host, warm, profile, state }: { engine: ContainerEngine; image: string; owner: JournalId; host: Host; warm?: WarmOptions; profile?: ProfileOption; state: string }): Provider {
  ```
- `warmImagesSaved` ← packages/runtime-sandbox/src/providers/container.ts:644 [EXTRACTED]
  ```
  export function warmImagesSaved({ engine, state }: { engine: ContainerEngine; state: string }): string[] {
  ```
- `removeWarmImages` ← packages/runtime-sandbox/src/providers/container.ts:652 [EXTRACTED]
  ```
  export async function removeWarmImages({ engine, state, env }: { engine: ContainerEngine; state: string; env: NodeJS.ProcessEnv }): Promise<WarmRemoval> {
  ```
- `onPath` ← packages/runtime-sandbox/src/providers/native.ts:88 [EXTRACTED]
  ```
  export function onPath(name: string, pathVariable: string | undefined): string | undefined {
  ```
- `realOf` ← packages/runtime-sandbox/src/providers/native.ts:105 [EXTRACTED]
  ```
  export function realOf(at: string): string {
  ```
- `isWithin` ← packages/runtime-sandbox/src/providers/native.ts:116 [EXTRACTED]
  ```
  export function isWithin(inner: string, outer: string): boolean {
  ```
- `toolRoots` ← packages/runtime-sandbox/src/providers/native.ts:131 [EXTRACTED]
  ```
  export function toolRoots(argv0: string, pathVariable: string | undefined, home: string): string[] {
  ```
- `nativeProvider` ← packages/runtime-sandbox/src/providers/native.ts:171 [EXTRACTED]
  ```
  export function nativeProvider({ sandbox, state, env, home }: { sandbox: NativeSandbox; state: string; env: NodeJS.ProcessEnv; home: string }): Provider {
  ```
- `sbxWarmTemplatesListed` ← packages/runtime-sandbox/src/providers/sbx.ts:85 [EXTRACTED]
  ```
  export function sbxWarmTemplatesListed(stdout: string): Array<{ ref: string; key: string; id?: string }> | undefined {
  ```
- `sbxKitTemplatesListed` ← packages/runtime-sandbox/src/providers/sbx.ts:93 [EXTRACTED]
  ```
  export function sbxKitTemplatesListed(stdout: string): Array<{ ref: string; id?: string }> | undefined {
  ```
- `sbxNamesListed` ← packages/runtime-sandbox/src/providers/sbx.ts:117 [EXTRACTED]
  ```
  export function sbxNamesListed(stdout: string): string[] | undefined {
  ```
- `sbxProvider` ← packages/runtime-sandbox/src/providers/sbx.ts:132 [EXTRACTED]
  ```
  export function sbxProvider({ agent, owner, env, warm, profile, state }: { agent: string | undefined; owner: JournalId; env: NodeJS.ProcessEnv; warm?: Extract<WarmOptions, { prepare: string }>; profile?: ProfileOption; state: string }): Provider {
  ```
- `warmTemplatesSaved` ← packages/runtime-sandbox/src/providers/sbx.ts:499 [EXTRACTED]
  ```
  export function warmTemplatesSaved({ state }: { state: string }): string[] {
  ```
- `removeWarmTemplates` ← packages/runtime-sandbox/src/providers/sbx.ts:508 [EXTRACTED]
  ```
  export async function removeWarmTemplates({ state, env }: { state: string; env: NodeJS.ProcessEnv }): Promise<WarmRemoval> {
  ```
- `profileOf` ← packages/runtime-sandbox/src/providers/seatbelt.ts:158 [EXTRACTED]
  ```
  export function profileOf({ writable, readable, gitPaths, memberHome, hostPorts }: Pick<Sandboxed, 'writable' | 'readable' | 'gitPaths' | 'memberHome' | 'hostPorts'>): SeatbeltProfile {
  ```
- `readTar` ← packages/runtime-sandbox/src/providers/vercel-copy.ts:57 [EXTRACTED]
  ```
  export function readTar(archive: Buffer): TarEntry[] {
  ```
- `fingerprintOf` ← packages/runtime-sandbox/src/providers/vercel-copy.ts:148 [EXTRACTED]
  ```
  export function fingerprintOf(data: Buffer): string {
  ```
- `fingerprintsOf` ← packages/runtime-sandbox/src/providers/vercel-copy.ts:153 [EXTRACTED]
  ```
  export function fingerprintsOf(root: string): Record<string, string> {
  ```
- `applyTar` ← packages/runtime-sandbox/src/providers/vercel-copy.ts:165 [EXTRACTED]
  ```
  export function applyTar(entries: TarEntry[], { roots, added = { roots: [], wentIn: {} }, kept }: { roots: string[]; added?: { roots: string[]; wentIn: Record<string, string> }; kept: string[] }): void {
  ```
- `VERCEL_AUTH` ← packages/runtime-sandbox/src/providers/vercel.ts:47 [EXTRACTED]
  ```
  export const VERCEL_AUTH = ['VERCEL_TOKEN', 'VERCEL_TEAM_ID', 'VERCEL_PROJECT_ID', 'VERCEL_OIDC_TOKEN'] as const;
  ```
- `LONGEST_MS` ← packages/runtime-sandbox/src/providers/vercel.ts:50 [EXTRACTED]
  ```
  export const LONGEST_MS = 5 * 3_600_000;
  ```
- `lifetimeOf` ← packages/runtime-sandbox/src/providers/vercel.ts:133 [EXTRACTED]
  ```
  export function lifetimeOf(timeoutMs: number | undefined, deadline: string | undefined, now: number): { ok: true; ms: number } | { ok: false; failure: RuntimeFailure } {
  ```
- `vercelProvider` ← packages/runtime-sandbox/src/providers/vercel.ts:153 [EXTRACTED]
  ```
  export function vercelProvider({ options, owner, state, env, home }: { options: VercelOptions & { readonly profile?: ProfileOption }; owner: JournalId; state: string; env: NodeJS.ProcessEnv; home: string }): Provider {
  ```
- `bundleRuntimeWith` ← packages/runtime-sandbox/src/testing/harness.ts:36 [EXTRACTED]
  ```
  export function bundleRuntimeWith({ outfile, alias, plugins }: { outfile: string } & Pick<BuildOptions, 'alias' | 'plugins'>): Promise<string> {
  ```
- `bundleRuntime` ← packages/runtime-sandbox/src/testing/harness.ts:41 [EXTRACTED]
  ```
  export function bundleRuntime(dir: string): Promise<string> {
  ```
- `fakeEngine` ← packages/runtime-sandbox/src/testing/harness.ts:119 [EXTRACTED]
  ```
  export function fakeEngine(dir: string): FakeEngine {
  ```
- `connect` ← packages/runtime-sandbox/src/testing/harness.ts:259 [EXTRACTED]
  ```
  export function connect(executable: string, env: NodeJS.ProcessEnv): Connection {
  ```
- `tempDir` ← packages/runtime-sandbox/src/testing/harness.ts:296 [EXTRACTED]
  ```
  export function tempDir(): string {
  ```
- `expectNothingLeft` ← packages/runtime-sandbox/src/testing/leaks.ts:92 [EXTRACTED]
  ```
  export function expectNothingLeft(scope: Scope): Promise<void> {
  ```
- `closeLeftovers` ← packages/runtime-sandbox/src/testing/leaks.ts:101 [EXTRACTED]
  ```
  export async function closeLeftovers(connections: Connection[]): Promise<{ invalid: string[]; recovered: Connection[] }> {
  ```
- `nativeHost` ← packages/runtime-sandbox/src/testing/native-harness.ts:55 [EXTRACTED]
  ```
  export function nativeHost(dir: string): NativeHost {
  ```
- `failStandIn` ← packages/runtime-sandbox/src/testing/native-harness.ts:84 [EXTRACTED]
  ```
  export function failStandIn(host: NativeHost, name: 'sandbox-exec' | 'bwrap', stderr: string): void {
  ```
- `RUN` ← packages/runtime-sandbox/src/testing/native-harness.ts:88 [EXTRACTED]
  ```
  export const RUN = 'r0123abcd';
  ```
- `ATTEMPT` ← packages/runtime-sandbox/src/testing/native-harness.ts:89 [EXTRACTED]
  ```
  export const ATTEMPT = 'a0123abcd';
  ```
- `HANDLE` ← packages/runtime-sandbox/src/testing/native-harness.ts:90 [EXTRACTED]
  ```
  export const HANDLE = `teamai-${RUN}-${ATTEMPT}`;
  ```
- `newOp` ← packages/runtime-sandbox/src/testing/native-harness.ts:94 [EXTRACTED]
  ```
  export function newOp(): string {
  ```
- `placeIn` ← packages/runtime-sandbox/src/testing/native-harness.ts:112 [EXTRACTED]
  ```
  export function placeIn(root: string): Place {
  ```
- `init` ← packages/runtime-sandbox/src/testing/native-harness.ts:122 [EXTRACTED]
  ```
  export async function init(connection: Connection, options: Message, credentials?: { env: string[]; logins: string[] }, instances?: Message[]): Promise<Message> {
  ```
- `openPlace` ← packages/runtime-sandbox/src/testing/native-harness.ts:129 [EXTRACTED]
  ```
  export async function openPlace(connection: Connection, at: Place, { op = newOp(), tool, credentials = {}, readonly = [at.git, at.dotGit] }: { op?: string; tool?: string; credentials?: Record<string, string>; readonly?: string[] } = {}): Promise<{ accepted: Message; ready: Message }> {
  ```
- `exec` ← packages/runtime-sandbox/src/testing/native-harness.ts:138 [EXTRACTED]
  ```
  export async function exec(connection: Connection, request: { argv: string[]; env?: Record<string, string>; unset?: string[]; credentials?: Record<string, string>; cwd: string }, op = newOp()): Promise<{ end: Message; output: string; stderr: string }> {
  ```
- `startOn` ← packages/runtime-sandbox/src/testing/native-harness.ts:147 [EXTRACTED]
  ```
  export function startOn(executable: string, host: NativeHost, open: Connection[], extra: NodeJS.ProcessEnv = {}): Connection {
  ```
- `processProvider` ← packages/runtime-sandbox/src/testing/process-provider.ts:6 [EXTRACTED]
  ```
  export function processProvider(): Provider {
  ```
- `SYSTEM_BIN` ← packages/runtime-sandbox/src/testing/this-machine.ts:6 [EXTRACTED]
  ```
  export const SYSTEM_BIN = process.env.SANDBOX_TEST_SYSTEM_BIN || '/usr/bin';
  ```
- `OS_RELEASE` ← packages/runtime-sandbox/src/testing/this-machine.ts:10 [EXTRACTED]
  ```
  export const OS_RELEASE = process.env.SANDBOX_TEST_OS_RELEASE ? [process.env.SANDBOX_TEST_OS_RELEASE] : ['/etc/os-release', '/usr/lib/os-release'];
  ```
- `Command` ← packages/runtime-sandbox/src/testing/vercel-fake-sdk.ts:69 [EXTRACTED]
  ```
  export class Command {
  ```
- `Snapshot` ← packages/runtime-sandbox/src/testing/vercel-fake-sdk.ts:106 [EXTRACTED]
  ```
  export class Snapshot {
  ```
- `Sandbox` ← packages/runtime-sandbox/src/testing/vercel-fake-sdk.ts:129 [EXTRACTED]
  ```
  export class Sandbox {
  ```
- `bundleRuntime` ← packages/runtime-t3/src/testing/harness.ts:27 [EXTRACTED]
  ```
  export async function bundleRuntime(dir: string): Promise<string> {
  ```
- `fakeT3` ← packages/runtime-t3/src/testing/harness.ts:222 [EXTRACTED]
  ```
  export function fakeT3(dir: string, workspaceRoot: string, { t3HomeInHome = false }: { t3HomeInHome?: boolean } = {}): FakeT3 {
  ```
- `PATH_WITHOUT_T3` ← packages/runtime-t3/src/testing/harness.ts:361 [EXTRACTED]
  ```
  export const PATH_WITHOUT_T3 = (process.env['PATH'] ?? '/usr/bin:/bin').split(path.delimiter).filter((entry) => entry !== '' && !fs.existsSync(path.join(entry, 't3'))).join(path.delimiter);
  ```
- `credentialsFile` ← packages/runtime-t3/src/testing/harness.ts:364 [EXTRACTED]
  ```
  export function credentialsFile(home: string): string {
  ```
- `signIn` ← packages/runtime-t3/src/testing/harness.ts:369 [EXTRACTED]
  ```
  export function signIn(t3: FakeT3, token = 'fake-t3-token-0123456789', expiresInSeconds = 3600, scope?: string): void {
  ```
- `connect` ← packages/runtime-t3/src/testing/harness.ts:384 [EXTRACTED]
  ```
  export function connect(executable: string, t3: FakeT3, env: Record<string, string> = {}, cwd?: string): Connection {
  ```
- `fakeBrowser` ← packages/runtime-t3/src/testing/harness.ts:392 [EXTRACTED]
  ```
  export function fakeBrowser(dir: string) {
  ```
- `replaceT3` ← packages/runtime-t3/src/testing/suite.ts:25 [EXTRACTED]
  ```
  export function replaceT3(fake: FakeT3): void {
  ```
- `linkTo` ← packages/runtime-t3/src/testing/suite.ts:30 [EXTRACTED]
  ```
  export const linkTo = (threadId: string | undefined): string => `t3code://threads/env-fake-1/${encodeURIComponent(threadId ?? '')}`;
  ```
- `isNotice` ← packages/runtime-t3/src/testing/suite.ts:33 [EXTRACTED]
  ```
  export const isNotice = (line: Line): boolean => line['event'] === 'notice';
  ```
- `noticesOf` ← packages/runtime-t3/src/testing/suite.ts:36 [EXTRACTED]
  ```
  export const noticesOf = (runtime: Connection): Line[] => runtime.lines.filter(isNotice);
  ```
- `start` ← packages/runtime-t3/src/testing/suite.ts:39 [EXTRACTED]
  ```
  export const start = (env: Record<string, string> = {}, cwd?: string): Connection => {
  ```
- `useT3Runtime` ← packages/runtime-t3/src/testing/suite.ts:47 [EXTRACTED]
  ```
  export function useT3Runtime(): void {
  ```
- `OPEN` ← packages/runtime-t3/src/testing/suite.ts:84 [EXTRACTED]
  ```
  export const OPEN = 'op-0000000a';
  ```
- `RUN` ← packages/runtime-t3/src/testing/suite.ts:85 [EXTRACTED]
  ```
  export const RUN = 'r7f3a91c2';
  ```
- `opened` ← packages/runtime-t3/src/testing/suite.ts:91 [EXTRACTED]
  ```
  export const opened = async (mode: 'attended' | 'unattended' = 'attended', env: Record<string, string> = {}, options: Line = {}): Promise<{ runtime: Connection; handle: string }> => {
  ```
- `prompt` ← packages/runtime-t3/src/testing/suite.ts:103 [EXTRACTED]
  ```
  export const prompt = (handle: string, op: string, lease: { [Key in keyof PromptLease]?: Line[string] | undefined } = {}) => ({
  ```
- `ended` ← packages/runtime-t3/src/testing/suite.ts:113 [EXTRACTED]
  ```
  export const ended = (runtime: Connection, op: string): Promise<Line> => runtime.next((line) => line['op'] === op && line['event'] !== 'accepted' && line['event'] !== 'display' && !isNotice(line), 20_000);
  ```
- `openOn` ← packages/runtime-t3/src/testing/suite.ts:116 [EXTRACTED]
  ```
  export const openOn = async (runtime: Connection, folder: string, op = OPEN, timeoutMs?: number): Promise<Line> => {
  ```
- `initialized` ← packages/runtime-t3/src/testing/suite.ts:123 [EXTRACTED]
  ```
  export const initialized = async (options: Line = {}, env: Record<string, string> = {}): Promise<Connection> => {
  ```
- `scriptsInProject1` ← packages/runtime-t3/src/testing/suite.ts:132 [EXTRACTED]
  ```
  export const scriptsInProject1 = (script: { name: string; command: string; runOnWorktreeCreate: boolean; runOnSettle?: boolean }) => ({
  ```
- `usePromptStep` ← packages/runtime-t3/src/testing/suite.ts:137 [EXTRACTED]
  ```
  export function usePromptStep(): void {
  ```
- `ideDataIn` ← packages/tool-codebuddy/src/testing/ide-history.ts:10 [EXTRACTED]
  ```
  export function ideDataIn(home: string): string {
  ```
- `instanceHistory` ← packages/tool-codebuddy/src/testing/ide-history.ts:15 [EXTRACTED]
  ```
  export function instanceHistory(home: string): string {
  ```
- `defaultInstanceHistory` ← packages/tool-codebuddy/src/testing/ide-history.ts:20 [EXTRACTED]
  ```
  export function defaultInstanceHistory(home: string): string {
  ```
- `md5` ← packages/tool-codebuddy/src/testing/ide-history.ts:25 [EXTRACTED]
  ```
  export function md5(text: string): string {
  ```
- `workspaceFolderOf` ← packages/tool-codebuddy/src/testing/ide-history.ts:30 [EXTRACTED]
  ```
  export function workspaceFolderOf(cwd: string): string {
  ```
- `buildWorkspace` ← packages/tool-codebuddy/src/testing/ide-history.ts:52 [EXTRACTED]
  ```
  export function buildWorkspace(historyRoot: string, cwd: string, convs: FixtureConv[]): string {
  ```
- `installFakeCodex` ← packages/tool-codex/src/testing/fake-codex.ts:117 [EXTRACTED]
  ```
  export function installFakeCodex(options: { version?: string | null; hashIgnores?: string[]; dir?: string } = {}): string {
  ```
- `fakeCodexVersionRuns` ← packages/tool-codex/src/testing/fake-codex.ts:132 [EXTRACTED]
  ```
  export function fakeCodexVersionRuns(dir: string): number {
  ```
- `pathWithoutCodex` ← packages/tool-codex/src/testing/fake-codex.ts:141 [EXTRACTED]
  ```
  export function pathWithoutCodex(): string {
  ```
- `readFakeCodexState` ← packages/tool-codex/src/testing/fake-codex.ts:147 [EXTRACTED]
  ```
  export function readFakeCodexState(codexHome: string): FakeCodexState {
  ```
- `writeFakeCodexOptions` ← packages/tool-codex/src/testing/fake-codex.ts:156 [EXTRACTED]
  ```
  export function writeFakeCodexOptions(
  ```
- `ClaudeCodeAdapter` ← packages/tool-core/src/formats/claude-code.ts:456 [EXTRACTED]
  ```
  export class ClaudeCodeAdapter extends AgentAdapter {
  ```
- `readClaudeJsonl` ← packages/tool-core/src/formats/claude-jsonl.ts:57 [EXTRACTED]
  ```
  export async function readClaudeJsonl(source: TokenSource): Promise<TokenReading> {
  ```
- `readCodexRollout` ← packages/tool-core/src/formats/codex-rollout.ts:178 [EXTRACTED]
  ```
  export async function readCodexRollout(source: TokenSource): Promise<TokenReading> {
  ```
- `CodexAdapter` ← packages/tool-core/src/formats/codex.ts:349 [EXTRACTED]
  ```
  export class CodexAdapter extends AgentAdapter {
  ```
- `ToolUnavailableError` ← packages/tool-core/src/sessions/base.ts:65 [EXTRACTED]
  ```
  export class ToolUnavailableError extends Error {
  ```
- `AgentAdapter` ← packages/tool-core/src/sessions/base.ts:69 [EXTRACTED]
  ```
  export abstract class AgentAdapter {
  ```
- `resolveRealCwd` ← packages/tool-core/src/sessions/fs.ts:32 [EXTRACTED]
  ```
  export function resolveRealCwd(cwd: string): string {
  ```
- `claudeProjectDirName` ← packages/tool-core/src/sessions/fs.ts:50 [EXTRACTED]
  ```
  export function claudeProjectDirName(realCwd: string): string {
  ```
- `encodeCwdClaude` ← packages/tool-core/src/sessions/fs.ts:62 [EXTRACTED]
  ```
  export function encodeCwdClaude(cwd: string): string {
  ```
- `encodeCwdGeneric` ← packages/tool-core/src/sessions/fs.ts:71 [EXTRACTED]
  ```
  export function encodeCwdGeneric(cwd: string): string {
  ```
- `encodeCwdCodeBuddy` ← packages/tool-core/src/sessions/fs.ts:84 [EXTRACTED]
  ```
  export function encodeCwdCodeBuddy(cwd: string): string {
  ```
- `decodeCwdClaude` ← packages/tool-core/src/sessions/fs.ts:116 [EXTRACTED]
  ```
  export function decodeCwdClaude(encoded: string): string {
  ```
- `bestEffortDecodeCwdClaude` ← packages/tool-core/src/sessions/fs.ts:131 [EXTRACTED]
  ```
  export function bestEffortDecodeCwdClaude(encoded: string): string | undefined {
  ```
- `decodeCwdGeneric` ← packages/tool-core/src/sessions/fs.ts:149 [EXTRACTED]
  ```
  export function decodeCwdGeneric(encoded: string): string {
  ```
- `coercedText` ← packages/tool-core/src/sessions/fs.ts:161 [EXTRACTED]
  ```
  export function coercedText(fallback = '') {
  ```
- `OptionalString` ← packages/tool-core/src/sessions/fs.ts:166 [EXTRACTED]
  ```
  export const OptionalString = z.string().optional().catch(undefined);
  ```
- `TextOrBlocksSchema` ← packages/tool-core/src/sessions/fs.ts:169 [EXTRACTED]
  ```
  export const TextOrBlocksSchema = z.union([z.string(), z.array(JsonValueSchema)]).optional().catch(undefined);
  ```
- `writeJsonl` ← packages/tool-core/src/sessions/fs.ts:238 [EXTRACTED]
  ```
  export function writeJsonl<TRecord extends object>(filePath: string, records: Iterable<TRecord>): void {
  ```
- `fileModifiedAt` ← packages/tool-core/src/sessions/fs.ts:262 [EXTRACTED]
  ```
  export function fileModifiedAt(p: string): string {
  ```
- `fileExists` ← packages/tool-core/src/sessions/fs.ts:270 [EXTRACTED]
  ```
  export function fileExists(p: string): boolean {
  ```
- `dirExists` ← packages/tool-core/src/sessions/fs.ts:278 [EXTRACTED]
  ```
  export function dirExists(p: string): boolean {
  ```
- `scanFiles` ← packages/tool-core/src/sessions/fs.ts:291 [EXTRACTED]
  ```
  export function scanFiles(rootDir: string, pattern: RegExp, skipped: (folder: string) => void): string[] {
  ```
- `mayReadLocalImageFile` ← packages/tool-core/src/sessions/fs.ts:350 [EXTRACTED]
  ```
  export function mayReadLocalImageFile(
  ```
- `safeFileName` ← packages/tool-core/src/sessions/fs.ts:370 [EXTRACTED]
  ```
  export function safeFileName(raw: string, fallback = 'image.png'): string {
  ```
- `removeDirRecursive` ← packages/tool-core/src/sessions/fs.ts:384 [EXTRACTED]
  ```
  export function removeDirRecursive(dirPath: string): void {
  ```
- `deriveTargetSessionId` ← packages/tool-core/src/sessions/ids.ts:39 [EXTRACTED]
  ```
  export function deriveTargetSessionId(
  ```
- `deriveOpencodeMessageIds` ← packages/tool-core/src/sessions/ids.ts:79 [EXTRACTED]
  ```
  export function deriveOpencodeMessageIds(sessionId: string, createdTimes: number[]): string[] {
  ```
- `legacyTargetSessionIds` ← packages/tool-core/src/sessions/ids.ts:135 [EXTRACTED]
  ```
  export function legacyTargetSessionIds(target: {
  ```
- `isSafeSessionFileId` ← packages/tool-core/src/sessions/ids.ts:192 [EXTRACTED]
  ```
  export function isSafeSessionFileId(sessionId: string): boolean {
  ```
- `assertSafeSessionFileId` ← packages/tool-core/src/sessions/ids.ts:201 [EXTRACTED]
  ```
  export function assertSafeSessionFileId(sessionId: string): void {
  ```
- `ToolArgumentsSchema` ← packages/tool-core/src/sessions/ir.ts:41 [EXTRACTED]
  ```
  export const ToolArgumentsSchema = JsonObjectSchema;
  ```
- `toolArgumentsFrom` ← packages/tool-core/src/sessions/ir.ts:49 [EXTRACTED]
  ```
  export function toolArgumentsFrom(stored: JsonValue | undefined): ToolArguments {
  ```
- `imagePlaceholderText` ← packages/tool-core/src/sessions/ir.ts:90 [EXTRACTED]
  ```
  export function imagePlaceholderText(block: ImageBlock): string {
  ```
- `blockToDict` ← packages/tool-core/src/sessions/ir.ts:99 [EXTRACTED]
  ```
  export function blockToDict(block: ContentBlock): ContentBlock {
  ```
- `blockFromDict` ← packages/tool-core/src/sessions/ir.ts:145 [EXTRACTED]
  ```
  export function blockFromDict(record: JsonValue): ContentBlock {
  ```
- `messageToDict` ← packages/tool-core/src/sessions/ir.ts:221 [EXTRACTED]
  ```
  export function messageToDict(msg: Message): MessageRecord {
  ```
- `MessageMetadataSchema` ← packages/tool-core/src/sessions/ir.ts:233 [EXTRACTED]
  ```
  export const MessageMetadataSchema = z
  ```
- `messageFromDict` ← packages/tool-core/src/sessions/ir.ts:250 [EXTRACTED]
  ```
  export function messageFromDict(record: JsonValue): Message {
  ```
- `sessionToDict` ← packages/tool-core/src/sessions/ir.ts:299 [EXTRACTED]
  ```
  export function sessionToDict(session: Session): SessionRecord {
  ```
- `sessionFromDict` ← packages/tool-core/src/sessions/ir.ts:333 [EXTRACTED]
  ```
  export function sessionFromDict(record: JsonValue): Session {
  ```
- `locatesOwnStore` ← packages/tool-core/src/sessions/platform.ts:80 [EXTRACTED]
  ```
  export function locatesOwnStore<TTool extends string>(platform: SessionPlatformDefinition<TTool>): platform is SelfLocatingPlatformDefinition<TTool> {
  ```
- `findSqlite3` ← packages/tool-core/src/sessions/sqlite.ts:21 [EXTRACTED]
  ```
  export function findSqlite3(platform: NodeJS.Platform = process.platform): string | null {
  ```
- `snapshotSqlite` ← packages/tool-core/src/sessions/sqlite.ts:52 [EXTRACTED]
  ```
  export async function snapshotSqlite(sqlite3: string, db: string, target: string, exec: CommandExecutor): Promise<void> {
  ```
- `cutTitle` ← packages/tool-core/src/sessions/title.ts:16 [EXTRACTED]
  ```
  export function cutTitle(text: string, maxLen = TITLE_MAX): string {
  ```
- `maskCutSecret` ← packages/tool-core/src/sessions/title.ts:27 [EXTRACTED]
  ```
  export function maskCutSecret(title: string, secrets: Record<string, string>): string {
  ```
- `isInjectedText` ← packages/tool-core/src/sessions/title.ts:60 [EXTRACTED]
  ```
  export function isInjectedText(text: string): boolean {
  ```
- `titleFromCandidates` ← packages/tool-core/src/sessions/title.ts:85 [EXTRACTED]
  ```
  export function titleFromCandidates(candidates: string[]): string {
  ```
- `cleanTitleText` ← packages/tool-core/src/sessions/title.ts:111 [EXTRACTED]
  ```
  export function cleanTitleText(text: string, maxLen = TITLE_MAX): string {
  ```
- `fallbackTitle` ← packages/tool-core/src/sessions/title.ts:124 [EXTRACTED]
  ```
  export function fallbackTitle(sessionId: string): string {
  ```
- `stripMetaBlocks` ← packages/tool-core/src/sessions/title.ts:150 [EXTRACTED]
  ```
  export function stripMetaBlocks(text: string): string {
  ```
- `extractUserText` ← packages/tool-core/src/sessions/title.ts:169 [EXTRACTED]
  ```
  export function extractUserText(text: string): string {
  ```
- `typedText` ← packages/tool-core/src/sessions/title.ts:182 [EXTRACTED]
  ```
  export function typedText(text: string): string {
  ```
- `typedTitle` ← packages/tool-core/src/sessions/title.ts:189 [EXTRACTED]
  ```
  export function typedTitle(text: string): string {
  ```
- `visibleUserText` ← packages/tool-core/src/sessions/title.ts:208 [EXTRACTED]
  ```
  export function visibleUserText(text: string): string {
  ```
- `titleFromUserText` ← packages/tool-core/src/sessions/title.ts:250 [EXTRACTED]
  ```
  export function titleFromUserText(text: string, maxLen = TITLE_MAX): string {
  ```
- `isRenderableText` ← packages/tool-core/src/sessions/title.ts:276 [EXTRACTED]
  ```
  export function isRenderableText(text: string): boolean {
  ```
- `toolLauncherConformance` ← packages/tool-launch/src/testing/launcher-conformance.ts:47 [EXTRACTED]
  ```
  export function toolLauncherConformance(name: string, adapter: () => Promise<{ start: ToolLauncher; cwd: string }>): void {
  ```
- `installFakeOpencode` ← packages/tool-opencode/src/testing/fake-opencode.ts:126 [EXTRACTED]
  ```
  export function installFakeOpencode(options: { version?: string; makesDataFolders?: boolean } = {}): string {
  ```
- `opencodeExportFixture` ← packages/tool-opencode/src/testing/fake-opencode.ts:157 [EXTRACTED]
  ```
  export function opencodeExportFixture(): OpencodeExport {
  ```
- `plantOpencodeSession` ← packages/tool-opencode/src/testing/fake-opencode.ts:164 [EXTRACTED]
  ```
  export function plantOpencodeSession(dataHome: string, session: OpencodeExport, raw?: string): void {
  ```
- `setFakeOpencodeExportError` ← packages/tool-opencode/src/testing/fake-opencode.ts:171 [EXTRACTED]
  ```
  export function setFakeOpencodeExportError(dataHome: string, message: string): void {
  ```
- `structuralEdgesToCodeFacts` ← src/wiki-engine/code-knowledge/ast/adapt-code-facts.ts:7 [EXTRACTED]
  ```
  export function structuralEdgesToCodeFacts(edges: StructuralEdge[]): CodeFact[] {
  ```
- `unresolvedImportsToGaps` ← src/wiki-engine/code-knowledge/ast/adapt-code-facts.ts:31 [EXTRACTED]
  ```
  export function unresolvedImportsToGaps(imports: AstImport[], resolvedKeys: Set<string>): UnresolvedGap[] {
  ```
- `buildImportBindingsForFile` ← src/wiki-engine/code-knowledge/ast/call-resolver.ts:13 [EXTRACTED]
  ```
  export function buildImportBindingsForFile(
  ```
- `resolveCallSites` ← src/wiki-engine/code-knowledge/ast/call-resolver.ts:55 [EXTRACTED]
  ```
  export function resolveCallSites(
  ```
- `callResolutionWeight` ← src/wiki-engine/code-knowledge/ast/call-resolver.ts:203 [EXTRACTED]
  ```
  export function callResolutionWeight(confidence: AstCallSite["confidence"]): number {
  ```
- `parseImportBindings` ← src/wiki-engine/code-knowledge/ast/import-bindings.ts:9 [EXTRACTED]
  ```
  export function parseImportBindings(
  ```
- `normalizeImportSpecifier` ← src/wiki-engine/code-knowledge/ast/import-bindings.ts:115 [EXTRACTED]
  ```
  export function normalizeImportSpecifier(specText: string, variant: GrammarVariant): string {
  ```
- `isTypeOnlyImport` ← src/wiki-engine/code-knowledge/ast/import-bindings.ts:123 [EXTRACTED]
  ```
  export function isTypeOnlyImport(importText: string, variant: GrammarVariant): boolean {
  ```
- `isExportedSymbol` ← src/wiki-engine/code-knowledge/ast/import-bindings.ts:131 [EXTRACTED]
  ```
  export function isExportedSymbol(
  ```
- `collectExportLineStarts` ← src/wiki-engine/code-knowledge/ast/import-bindings.ts:183 [EXTRACTED]
  ```
  export function collectExportLineStarts(
  ```
- `loadTsconfigPaths` ← src/wiki-engine/code-knowledge/ast/import-resolver.ts:39 [EXTRACTED]
  ```
  export async function loadTsconfigPaths(
  ```
- `resolveImportSpecifier` ← src/wiki-engine/code-knowledge/ast/import-resolver.ts:95 [EXTRACTED]
  ```
  export async function resolveImportSpecifier(
  ```
- `buildFileExistenceChecker` ← src/wiki-engine/code-knowledge/ast/import-resolver.ts:317 [EXTRACTED]
  ```
  export async function buildFileExistenceChecker(
  ```
- `mergeCodeFacts` ← src/wiki-engine/code-knowledge/ast/merge-edges.ts:11 [EXTRACTED]
  ```
  export function mergeCodeFacts(astFacts: CodeFact[], heuristicFacts: CodeFact[]): CodeFact[] {
  ```
- `swiftModuleScope` ← src/wiki-engine/code-knowledge/ast/module-scope.ts:30 [EXTRACTED]
  ```
  export function swiftModuleScope(relativePath: string): string | undefined {
  ```
- `buildSwiftModuleSymbolIndex` ← src/wiki-engine/code-knowledge/ast/module-scope.ts:101 [EXTRACTED]
  ```
  export function buildSwiftModuleSymbolIndex(
  ```
- `swiftModuleDeclaresMember` ← src/wiki-engine/code-knowledge/ast/module-scope.ts:167 [EXTRACTED]
  ```
  export function swiftModuleDeclaresMember(
  ```
- `findSwiftModuleSymbol` ← src/wiki-engine/code-knowledge/ast/module-scope.ts:193 [EXTRACTED]
  ```
  export function findSwiftModuleSymbol(
  ```
- `ensureAstReady` ← src/wiki-engine/code-knowledge/ast/parser-registry.ts:41 [EXTRACTED]
  ```
  export async function ensureAstReady(): Promise<void> {
  ```
- `getParser` ← src/wiki-engine/code-knowledge/ast/parser-registry.ts:84 [EXTRACTED]
  ```
  export function getParser(): Parser {
  ```
- `grammarForExtension` ← src/wiki-engine/code-knowledge/ast/parser-registry.ts:92 [EXTRACTED]
  ```
  export function grammarForExtension(ext: string): GrammarVariant | undefined {
  ```
- `getLanguage` ← src/wiki-engine/code-knowledge/ast/parser-registry.ts:116 [EXTRACTED]
  ```
  export function getLanguage(variant: GrammarVariant): Language {
  ```
- `getQuery` ← src/wiki-engine/code-knowledge/ast/parser-registry.ts:126 [EXTRACTED]
  ```
  export function getQuery(variant: GrammarVariant): Query {
  ```
- `resetParserRegistryForTests` ← src/wiki-engine/code-knowledge/ast/parser-registry.ts:136 [EXTRACTED]
  ```
  export function resetParserRegistryForTests(): void {
  ```
- `TS_AST_QUERY_SOURCE` ← src/wiki-engine/code-knowledge/ast/queries.ts:3 [EXTRACTED]
  ```
  export const TS_AST_QUERY_SOURCE = `
  ```
- `PYTHON_AST_QUERY_SOURCE` ← src/wiki-engine/code-knowledge/ast/queries.ts:43 [EXTRACTED]
  ```
  export const PYTHON_AST_QUERY_SOURCE = `
  ```
- `GO_AST_QUERY_SOURCE` ← src/wiki-engine/code-knowledge/ast/queries.ts:72 [EXTRACTED]
  ```
  export const GO_AST_QUERY_SOURCE = `
  ```
- `SWIFT_AST_QUERY_SOURCE` ← src/wiki-engine/code-knowledge/ast/queries.ts:120 [EXTRACTED]
  ```
  export const SWIFT_AST_QUERY_SOURCE = `
  ```
- `isAstParseableFile` ← src/wiki-engine/code-knowledge/ast/walk.ts:45 [EXTRACTED]
  ```
  export function isAstParseableFile(relativePath: string): boolean {
  ```
- `walkFile` ← src/wiki-engine/code-knowledge/ast/walk.ts:49 [EXTRACTED]
  ```
  export function walkFile(file: CodeCollectedFile): FileWalkResult {
  ```
- `extractToml` ← src/wiki-engine/code-knowledge/extractors/config.ts:13 [EXTRACTED]
  ```
  export function extractToml(files: CodeCollectedFile[]): CodeFact[] {
  ```
- `extractSql` ← src/wiki-engine/code-knowledge/extractors/config.ts:45 [EXTRACTED]
  ```
  export function extractSql(files: CodeCollectedFile[]): CodeFact[] {
  ```
- `extractGo` ← src/wiki-engine/code-knowledge/extractors/go.ts:9 [EXTRACTED]
  ```
  export function extractGo(files: CodeCollectedFile[]): CodeFact[] {
  ```
- `extractJava` ← src/wiki-engine/code-knowledge/extractors/java.ts:9 [EXTRACTED]
  ```
  export function extractJava(files: CodeCollectedFile[]): CodeFact[] {
  ```
- `extractPython` ← src/wiki-engine/code-knowledge/extractors/python.ts:10 [EXTRACTED]
  ```
  export function extractPython(files: CodeCollectedFile[]): CodeFact[] {
  ```
- `extractRust` ← src/wiki-engine/code-knowledge/extractors/rust.ts:9 [EXTRACTED]
  ```
  export function extractRust(files: CodeCollectedFile[]): CodeFact[] {
  ```
- `SCALA_WILDCARD_PREFIX` ← src/wiki-engine/code-knowledge/extractors/scala.ts:15 [EXTRACTED]
  ```
  export const SCALA_WILDCARD_PREFIX = "scala-wildcard:";
  ```
- `SCALA_DECL_PREFIX` ← src/wiki-engine/code-knowledge/extractors/scala.ts:24 [EXTRACTED]
  ```
  export const SCALA_DECL_PREFIX = "scala-decl:";
  ```
- `extractScala` ← src/wiki-engine/code-knowledge/extractors/scala.ts:36 [EXTRACTED]
  ```
  export function extractScala(files: CodeCollectedFile[], context?: ExtractorContext): CodeFact[] {
  ```
- `extractSwift` ← src/wiki-engine/code-knowledge/extractors/swift.ts:9 [EXTRACTED]
  ```
  export function extractSwift(files: CodeCollectedFile[]): CodeFact[] {
  ```
- `extractTypescript` ← src/wiki-engine/code-knowledge/extractors/typescript.ts:9 [EXTRACTED]
  ```
  export function extractTypescript(files: CodeCollectedFile[]): CodeFact[] {
  ```
- `_setDriverPollMs` ← src/workflow/drivers/local/local-driver.ts:63 [EXTRACTED]
  ```
  export function _setDriverPollMs(ms: number): void {
  ```
- `runLocalDriver` ← src/workflow/drivers/local/local-driver.ts:491 [EXTRACTED]
  ```
  export async function runLocalDriver(
  ```
- `withDriverLock` ← src/workflow/drivers/local/local-driver.ts:504 [EXTRACTED]
  ```
  export async function withDriverLock(
  ```
- `localStrictCan` ← src/workflow/drivers/local/local-driver.ts:549 [EXTRACTED]
  ```
  export function localStrictCan(config: LocalConfig, options: Pick<LocalDriverOptions, 'sandbox'>): StrictCan {
  ```
- `personAnswers` ← src/workflow/drivers/local/local-driver.ts:633 [EXTRACTED]
  ```
  export function personAnswers(mode: RunMode): boolean {
  ```
- `writeChildBrief` ← src/workflow/drivers/skill/child-brief.ts:46 [EXTRACTED]
  ```
  export async function writeChildBrief(input: {
  ```
- `readChildResult` ← src/workflow/drivers/skill/child-brief.ts:135 [EXTRACTED]
  ```
  export async function readChildResult(input: { config: LocalConfig; run: RunId; attempt: AttemptId }): Promise<ChildResult> {
  ```
- `pickChildModel` ← src/workflow/drivers/skill/child-model.ts:13 [EXTRACTED]
  ```
  export async function pickChildModel(input: {
  ```
- `readLease` ← src/workflow/drivers/skill/engine-replies.ts:16 [EXTRACTED]
  ```
  export function readLease(raw: unknown): ReadLease | undefined {
  ```
- `engineReply` ← src/workflow/drivers/skill/engine-replies.ts:90 [EXTRACTED]
  ```
  export function engineReply(run: RunId, answer: WorkflowEnvelope): NextAnswer {
  ```
- `respondReply` ← src/workflow/drivers/skill/engine-replies.ts:141 [EXTRACTED]
  ```
  export function respondReply(answer: WorkflowEnvelope): RespondReply {
  ```
- `reportReply` ← src/workflow/drivers/skill/engine-replies.ts:152 [EXTRACTED]
  ```
  export function reportReply(answer: WorkflowEnvelope): ReportReply {
  ```
- `startedOf` ← src/workflow/drivers/skill/engine-replies.ts:169 [EXTRACTED]
  ```
  export function startedOf(answer: WorkflowEnvelope): StartedRun[] {
  ```
- `readJob` ← src/workflow/drivers/skill/job.ts:25 [EXTRACTED]
  ```
  export async function readJob(config: LocalConfig, run: RunId, attempt: AttemptId): Promise<Job | undefined> {
  ```
- `writeJob` ← src/workflow/drivers/skill/job.ts:37 [EXTRACTED]
  ```
  export async function writeJob(input: { config: LocalConfig; run: RunId; attempt: AttemptId; raw: unknown; secrets: Record<string, string> }): Promise<void> {
  ```
- `journalCall` ← src/workflow/drivers/skill/journal.ts:151 [EXTRACTED]
  ```
  export async function journalCall(context: SkillContext, call: SkillCall, answer: SkillAnswer): Promise<void> {
  ```
- `INVOCATIONS` ← src/workflow/drivers/skill/literals.ts:13 [EXTRACTED]
  ```
  export const INVOCATIONS = ['teamai', 'npx teamai-cli'] as const;
  ```
- `invocationOf` ← src/workflow/drivers/skill/literals.ts:18 [EXTRACTED]
  ```
  export function invocationOf(entry: string | undefined): Invocation {
  ```
- `generatedStartPatterns` ← src/workflow/drivers/skill/literals.ts:26 [EXTRACTED]
  ```
  export function generatedStartPatterns(name: string, alias?: string): string[] {
  ```
- `describeLiteral` ← src/workflow/drivers/skill/literals.ts:31 [EXTRACTED]
  ```
  export function describeLiteral(invocation: Invocation, name: string, options: { tool?: string } = {}): Literal {
  ```
- `startLiteral` ← src/workflow/drivers/skill/literals.ts:54 [EXTRACTED]
  ```
  export function startLiteral(invocation: Invocation, name: string, options: { parallel?: number; confirmed?: boolean; hitl?: HitlMode; inputs?: boolean; noJudge?: boolean; tool?: string } = {}): Literal {
  ```
- `localStartLiteral` ← src/workflow/drivers/skill/literals.ts:71 [EXTRACTED]
  ```
  export function localStartLiteral(invocation: Invocation, name: string, options: { tool?: string } = {}): Literal {
  ```
- `appStartLiteral` ← src/workflow/drivers/skill/literals.ts:79 [EXTRACTED]
  ```
  export function appStartLiteral(invocation: Invocation, name: string, driver: string, options: { confirmed?: boolean; autoApprove?: boolean; inputs?: boolean } = {}): Literal {
  ```
- `resumeLiteral` ← src/workflow/drivers/skill/literals.ts:89 [EXTRACTED]
  ```
  export function resumeLiteral(invocation: Invocation, run: RunId, options: { tool?: string; claim?: true } = {}): Literal {
  ```
- `skillResumeLiteral` ← src/workflow/drivers/skill/literals.ts:98 [EXTRACTED]
  ```
  export function skillResumeLiteral(invocation: Invocation, run: RunId, options: { claim?: boolean; parallel?: number; hitl?: HitlMode; noJudge?: boolean; confirmed?: boolean; tool?: string } = {}): Literal {
  ```
- `skillResumeNextLiteral` ← src/workflow/drivers/skill/literals.ts:109 [EXTRACTED]
  ```
  export function skillResumeNextLiteral(invocation: Invocation, options: { parallel?: number; hitl?: HitlMode; noJudge?: boolean; confirmed?: boolean; tool?: string } = {}): Literal {
  ```
- `nextLiteral` ← src/workflow/drivers/skill/literals.ts:118 [EXTRACTED]
  ```
  export function nextLiteral(invocation: Invocation, run: RunId): Literal {
  ```
- `takeoverLiteral` ← src/workflow/drivers/skill/literals.ts:126 [EXTRACTED]
  ```
  export function takeoverLiteral(invocation: Invocation, run: RunId, options: { confirmed?: boolean } = {}): Literal {
  ```
- `pollLiteral` ← src/workflow/drivers/skill/literals.ts:130 [EXTRACTED]
  ```
  export function pollLiteral(invocation: Invocation, run: RunId): Literal {
  ```
- `chooseSessionHostLiteral` ← src/workflow/drivers/skill/literals.ts:135 [EXTRACTED]
  ```
  export function chooseSessionHostLiteral(invocation: Invocation, run: RunId, choice: SessionHostChoice): Literal {
  ```
- `ackLiteral` ← src/workflow/drivers/skill/literals.ts:140 [EXTRACTED]
  ```
  export function ackLiteral(invocation: Invocation, run: RunId, attempt: AttemptId): Literal {
  ```
- `respondLiteral` ← src/workflow/drivers/skill/literals.ts:145 [EXTRACTED]
  ```
  export function respondLiteral(invocation: Invocation, run: RunId, gate: { step: string; pass: number; choice: string }): Literal {
  ```
- `personRespondLiteral` ← src/workflow/drivers/skill/literals.ts:150 [EXTRACTED]
  ```
  export function personRespondLiteral(invocation: Invocation, run: RunId, gate: { step: string; pass: number; choice: string }): Literal {
  ```
- `reportLiteral` ← src/workflow/drivers/skill/literals.ts:154 [EXTRACTED]
  ```
  export function reportLiteral(invocation: Invocation, run: RunId, attempt: AttemptId): Literal {
  ```
- `adoptLiteral` ← src/workflow/drivers/skill/literals.ts:162 [EXTRACTED]
  ```
  export function adoptLiteral(invocation: Invocation, run: RunId, attempt: AttemptId, dir?: string): Literal {
  ```
- `unavailableLiteral` ← src/workflow/drivers/skill/literals.ts:167 [EXTRACTED]
  ```
  export function unavailableLiteral(invocation: Invocation, run: RunId, attempt: AttemptId): Literal {
  ```
- `runnerArgs` ← src/workflow/drivers/skill/literals.ts:172 [EXTRACTED]
  ```
  export function runnerArgs(run: RunId, attempt: AttemptId): string[] {
  ```
- `needsTool` ← src/workflow/drivers/skill/preflight.ts:24 [EXTRACTED]
  ```
  export function needsTool(description: WorkflowDescription, input: { tool: string | undefined; judged: boolean }): boolean {
  ```
- `HITL_MODES` ← src/workflow/drivers/skill/preflight.ts:33 [EXTRACTED]
  ```
  export const HITL_MODES = ['person', 'recommend', 'auto-approve'] as const;
  ```
- `neededAnswers` ← src/workflow/drivers/skill/preflight.ts:42 [EXTRACTED]
  ```
  export function neededAnswers(description: WorkflowDescription): StartAnswer[] {
  ```
- `localReason` ← src/workflow/drivers/skill/preflight.ts:55 [EXTRACTED]
  ```
  export function localReason(description: WorkflowDescription): string | undefined {
  ```
- `attendedReason` ← src/workflow/drivers/skill/preflight.ts:88 [EXTRACTED]
  ```
  export function attendedReason(description: WorkflowDescription, act: 'start' | 'continue'): string | undefined {
  ```
- `personClauses` ← src/workflow/drivers/skill/preflight.ts:93 [EXTRACTED]
  ```
  export function personClauses({ interactive, gates }: { interactive: readonly string[]; gates: ReadonlyArray<{ step: string; kind: 'approve' | 'choose' }> }): string[] {
  ```
- `isLeft` ← src/workflow/drivers/skill/preflight.ts:105 [EXTRACTED]
  ```
  export function isLeft(step: string, settled: ReadonlySet<string>): boolean {
  ```
- `checkStartAnswers` ← src/workflow/drivers/skill/preflight.ts:110 [EXTRACTED]
  ```
  export function checkStartAnswers(input: {
  ```
- `listOf` ← src/workflow/drivers/skill/preflight.ts:138 [EXTRACTED]
  ```
  export function listOf(items: readonly string[]): string {
  ```
- `localPromptTool` ← src/workflow/drivers/skill/preflight.ts:397 [EXTRACTED]
  ```
  export function localPromptTool({ config, tool, aiTools }: { config: LocalConfig; tool: string | undefined; aiTools: readonly string[] }): string | undefined {
  ```
- `askFor` ← src/workflow/drivers/skill/preflight.ts:409 [EXTRACTED]
  ```
  export function askFor(verdict: DescribeVerdict, description: WorkflowDescription, invocation: Invocation, judging: Judging, tools: { local?: string; session?: string }, proposed: Proposed): DescribeAsk {
  ```
- `ceilingOf` ← src/workflow/drivers/skill/preflight.ts:494 [EXTRACTED]
  ```
  export function ceilingOf(config: LocalConfig): number {
  ```
- `SESSION_HOST_CHOICES` ← src/workflow/drivers/skill/session-host-profiles.ts:12 [EXTRACTED]
  ```
  export const SESSION_HOST_CHOICES = ['h1', 'h2', 'h3', 'h4'] as const;
  ```
- `SESSION_HOST_QUESTION` ← src/workflow/drivers/skill/session-host-profiles.ts:62 [EXTRACTED]
  ```
  export const SESSION_HOST_QUESTION = 'Pick how your session host runs a child agent, the most specialized way it has: app orchestration tools, then team agents, then native subagents, else none, and you work each step yourself.';
  ```
- `canFor` ← src/workflow/drivers/skill/session-host-profiles.ts:65 [EXTRACTED]
  ```
  export function canFor(sessionHost: SessionHostChoice | undefined): DecidedCan {
  ```
- `sessionJudgeTool` ← src/workflow/drivers/skill/session-host-profiles.ts:70 [EXTRACTED]
  ```
  export function sessionJudgeTool(state: Pick<SkillState, 'sessionJudge' | 'orchestrator'>): string | undefined {
  ```
- `confinedCan` ← src/workflow/drivers/skill/session-host-profiles.ts:79 [EXTRACTED]
  ```
  export function confinedCan(state: Pick<SkillState, 'judging' | 'sessionJudge' | 'orchestrator'>): NonNullable<DriverCan['confined']> {
  ```
- `sessionOffers` ← src/workflow/drivers/skill/session-host-profiles.ts:102 [EXTRACTED]
  ```
  export async function sessionOffers(tool: string | undefined): Promise<NonNullable<DriverCan['confined']>> {
  ```
- `sessionToolJudge` ← src/workflow/drivers/skill/session-host-profiles.ts:112 [EXTRACTED]
  ```
  export async function sessionToolJudge(tool: string | undefined): Promise<ConfinedJudge | undefined> {
  ```
- `skillContext` ← src/workflow/drivers/skill/skill-driver.ts:132 [EXTRACTED]
  ```
  export async function skillContext(input: Pick<SkillContext, 'config' | 'toolPaths' | 'env' | 'cwd' | 'aiTools' | 'trace'> & { app?: SkillContext['app'] }): Promise<SkillContext> {
  ```
- `sessionDrivesRun` ← src/workflow/drivers/skill/skill-driver.ts:157 [EXTRACTED]
  ```
  export async function sessionDrivesRun(config: LocalConfig, run: RunId): Promise<boolean> {
  ```
- `isSkillRunnerHolding` ← src/workflow/drivers/skill/skill-driver.ts:172 [EXTRACTED]
  ```
  export async function isSkillRunnerHolding(config: LocalConfig, run: RunId, attempt: AttemptId): Promise<boolean> {
  ```
- `whileNoDriverHere` ← src/workflow/drivers/skill/skill-driver.ts:185 [EXTRACTED]
  ```
  export async function whileNoDriverHere<T>(config: LocalConfig, run: RunId, body: (lock: RunLock) => Promise<T>): Promise<LockTaken<T>> {
  ```
- `drivesUndoneRun` ← src/workflow/drivers/skill/skill-driver.ts:205 [EXTRACTED]
  ```
  export async function drivesUndoneRun(config: LocalConfig, session: string): Promise<boolean> {
  ```
- `parseInputsFlag` ← src/workflow/drivers/skill/skill-driver.ts:309 [EXTRACTED]
  ```
  export function parseInputsFlag(raw: string): { inputs: unknown } | { error: WorkflowFailure } {
  ```
- `parseSkillResume` ← src/workflow/drivers/skill/skill-driver.ts:344 [EXTRACTED]
  ```
  export function parseSkillResume(options: unknown, env: NodeJS.ProcessEnv): Omit<Extract<SkillCall, { kind: 'resume' }>, 'kind' | 'run'> | { error: SkillError } {
  ```
- `parseSkillCall` ← src/workflow/drivers/skill/skill-driver.ts:371 [EXTRACTED]
  ```
  export function parseSkillCall(
  ```
- `runSkillCall` ← src/workflow/drivers/skill/skill-driver.ts:460 [EXTRACTED]
  ```
  export async function runSkillCall(call: SkillCall, context: SkillContext): Promise<SkillAnswer> {
  ```
- `detachedRunners` ← src/workflow/drivers/skill/skill-runner.ts:39 [EXTRACTED]
  ```
  export function detachedRunners(config: LocalConfig): Runners {
  ```
- `runRunner` ← src/workflow/drivers/skill/skill-runner.ts:94 [EXTRACTED]
  ```
  export async function runRunner(context: SkillContext, run: RunId, attempt: AttemptId): Promise<SkillAnswer> {
  ```
- `childTitle` ← src/workflow/drivers/skill/skill-state.ts:93 [EXTRACTED]
  ```
  export function childTitle(step: string, attempt: string): string {
  ```
- `newSkillState` ← src/workflow/drivers/skill/skill-state.ts:269 [EXTRACTED]
  ```
  export function newSkillState(input: {
  ```
- `scoringSkillState` ← src/workflow/drivers/skill/skill-state.ts:290 [EXTRACTED]
  ```
  export function scoringSkillState(scored: SkillState, run: RunId, at: string): SkillState {
  ```
- `drivesRun` ← src/workflow/drivers/skill/skill-state.ts:322 [EXTRACTED]
  ```
  export function drivesRun(state: SkillState | undefined, session: string | undefined): boolean {
  ```
- `readSkillState` ← src/workflow/drivers/skill/skill-state.ts:326 [EXTRACTED]
  ```
  export async function readSkillState(config: LocalConfig, run: RunId): Promise<{ kind: 'found'; state: SkillState } | { kind: 'missing' } | { kind: 'unreadable'; reason: string }> {
  ```
- `writeSkillState` ← src/workflow/drivers/skill/skill-state.ts:341 [EXTRACTED]
  ```
  export async function writeSkillState(config: LocalConfig, lock: RunLock, state: SkillState, secrets: Record<string, string>): Promise<void> {
  ```
- `removeSkillState` ← src/workflow/drivers/skill/skill-state.ts:346 [EXTRACTED]
  ```
  export async function removeSkillState(config: LocalConfig, lock: RunLock): Promise<void> {
  ```
- `WAIT_BOUND_MS` ← src/workflow/drivers/skill/tick.ts:32 [EXTRACTED]
  ```
  export const WAIT_BOUND_MS = 100_000;
  ```
- `WAIT_POLL_MS` ← src/workflow/drivers/skill/tick.ts:35 [EXTRACTED]
  ```
  export const WAIT_POLL_MS = 2_000;
  ```
- `WAIT_GRACE_MS` ← src/workflow/drivers/skill/tick.ts:38 [EXTRACTED]
  ```
  export const WAIT_GRACE_MS = 5_000;
  ```
- `TICK_LOCK_WAIT_MS` ← src/workflow/drivers/skill/tick.ts:41 [EXTRACTED]
  ```
  export const TICK_LOCK_WAIT_MS = 30_000;
  ```
- `RUNNER_POLL_MS` ← src/workflow/drivers/skill/tick.ts:44 [EXTRACTED]
  ```
  export const RUNNER_POLL_MS = 10_000;
  ```
- `traced` ← src/workflow/drivers/skill/tick.ts:48 [EXTRACTED]
  ```
  export function traced<T extends { row: RowId } | undefined>(context: SkillContext, taken: T): T {
  ```
- `applyEffects` ← src/workflow/drivers/skill/tick.ts:62 [EXTRACTED]
  ```
  export async function applyEffects(context: SkillContext, lock: RunLock, start: SkillState, effects: readonly Effect[], unqueued: readonly AttemptId[] = []): Promise<Applied> {
  ```
- `runTick` ← src/workflow/drivers/skill/tick.ts:149 [EXTRACTED]
  ```
  export async function runTick(context: SkillContext, lock: RunLock, start: SkillState, role: 'call' | 'runner'): Promise<Ticked> {
  ```
- `plannedState` ← src/workflow/drivers/skill/tick.ts:222 [EXTRACTED]
  ```
  export function plannedState(context: SkillContext, run: RunId, planned: StartRun): SkillState {
  ```
- `foreground` ← src/workflow/drivers/skill/tick.ts:636 [EXTRACTED]
  ```
  export async function foreground(context: SkillContext, run: RunId, call: ForegroundCall): Promise<SkillAnswer> {
  ```
- `agentReport` ← src/workflow/drivers/skill/tick.ts:716 [EXTRACTED]
  ```
  export async function agentReport(context: SkillContext, run: RunId, call: { attempt: AttemptId; modelUnavailable: boolean }): Promise<SkillAnswer> {
  ```
- `poll` ← src/workflow/drivers/skill/tick.ts:763 [EXTRACTED]
  ```
  export async function poll(context: SkillContext, run: RunId): Promise<SkillAnswer> {
  ```
- `TRANSITIONS` ← src/workflow/drivers/skill/transitions.ts:35 [EXTRACTED]
  ```
  export const TRANSITIONS = [
  ```
- `judgedBy` ← src/workflow/drivers/skill/transitions.ts:211 [EXTRACTED]
  ```
  export function judgedBy(judging: Judging): JudgedBy | undefined {
  ```
- `reportedByAgent` ← src/workflow/drivers/skill/transitions.ts:380 [EXTRACTED]
  ```
  export function reportedByAgent(open: AttemptState): boolean {
  ```
- `openAttempt` ← src/workflow/drivers/skill/transitions.ts:405 [EXTRACTED]
  ```
  export function openAttempt(state: SkillState, attempt: AttemptId): AttemptState | undefined {
  ```
- `unseenEvents` ← src/workflow/drivers/skill/transitions.ts:410 [EXTRACTED]
  ```
  export function unseenEvents(state: SkillState, session: string | undefined): TurnEvent[] {
  ```
- `describeRow` ← src/workflow/drivers/skill/transitions.ts:423 [EXTRACTED]
  ```
  export function describeRow(input: DescribeInput): DescribeRow {
  ```
- `startRow` ← src/workflow/drivers/skill/transitions.ts:456 [EXTRACTED]
  ```
  export function startRow(input: StartInput): { row: 'R8' | 'R9'; refusal: Refusal } | { row: 'R29' | 'R25'; error: WorkflowFailure } | { row: 'R10'; start: StartRun } {
  ```
- `readiedRow` ← src/workflow/drivers/skill/transitions.ts:501 [EXTRACTED]
  ```
  export function readiedRow(input: { run: RunId; readied: RunReadied; kept: boolean; local?: string; mode: RunMode; attended?: string; needsTool: boolean; answers: ResumeAnswers; confirmed: boolean }):
  ```
- `unreadBeforeClaimRow` ← src/workflow/drivers/skill/transitions.ts:547 [EXTRACTED]
  ```
  export function unreadBeforeClaimRow(run: RunId, failure: WorkflowFailure): Answered<'R24', Relayed> {
  ```
- `unattendedRow` ← src/workflow/drivers/skill/transitions.ts:557 [EXTRACTED]
  ```
  export function unattendedRow(state: SkillState, answers: ResumeAnswers): Moved<'R26'> | undefined {
  ```
- `invokeRow` ← src/workflow/drivers/skill/transitions.ts:578 [EXTRACTED]
  ```
  export function invokeRow(refusal: WorkflowFailure | undefined, mode: RunMode): Answered<'R22', Relayed> | undefined {
  ```
- `callRow` ← src/workflow/drivers/skill/transitions.ts:590 [EXTRACTED]
  ```
  export function callRow(state: SkillState | undefined, input: { run: RunId; session: string | undefined; tool: string | undefined; declared?: string; at: string; takeover: boolean }): Moved<'S1' | 'S4'> | Answered<'R11' | 'S2'> {
  ```
- `runnerCallRow` ← src/workflow/drivers/skill/transitions.ts:622 [EXTRACTED]
  ```
  export function runnerCallRow(): RunnerCallRow {
  ```
- `reportCallRow` ← src/workflow/drivers/skill/transitions.ts:630 [EXTRACTED]
  ```
  export function reportCallRow(state: SkillState, attempt: AttemptId): { row: 'S6' } | undefined {
  ```
- `doneRow` ← src/workflow/drivers/skill/transitions.ts:640 [EXTRACTED]
  ```
  export function doneRow(state: SkillState): { row: 'X1' | 'X2' | 'X4' } | undefined {
  ```
- `childCap` ← src/workflow/drivers/skill/transitions.ts:647 [EXTRACTED]
  ```
  export function childCap(state: SkillState): number {
  ```
- `hasSlot` ← src/workflow/drivers/skill/transitions.ts:652 [EXTRACTED]
  ```
  export function hasSlot(state: SkillState): boolean {
  ```
- `queuedAttempts` ← src/workflow/drivers/skill/transitions.ts:679 [EXTRACTED]
  ```
  export function queuedAttempts(state: SkillState, unqueued: readonly AttemptId[] = []): AttemptId[] {
  ```
- `tickRow` ← src/workflow/drivers/skill/transitions.ts:688 [EXTRACTED]
  ```
  export function tickRow(state: SkillState, input: { role: 'call' | 'runner'; version?: RunVersion; unqueued?: readonly AttemptId[] }): { row: 'R12' | 'X7' } | { row: 'D1'; request: TickRequest } | (Moved<'X5'> & { request: TickRequest }) {
  ```
- `reopenedRow` ← src/workflow/drivers/skill/transitions.ts:716 [EXTRACTED]
  ```
  export function reopenedRow(state: SkillState, input: { reply: EngineReply; sameEnd: boolean }): Moved<'X6'> | undefined {
  ```
- `startedRow` ← src/workflow/drivers/skill/transitions.ts:724 [EXTRACTED]
  ```
  export function startedRow(state: SkillState, started: readonly StartedRun[]): Moved<'J7'> | undefined {
  ```
- `scoringTickRow` ← src/workflow/drivers/skill/transitions.ts:735 [EXTRACTED]
  ```
  export function scoringTickRow(state: SkillState): { row: 'J8'; runs: RunId[] } | undefined {
  ```
- `scoredRow` ← src/workflow/drivers/skill/transitions.ts:743 [EXTRACTED]
  ```
  export function scoredRow(state: SkillState, input: { run: RunId; ticked: SkillState; labels: ScoredLabels; error?: WorkflowFailure }): Moved<'J9' | 'J10'> | undefined {
  ```
- `chooseRow` ← src/workflow/drivers/skill/transitions.ts:779 [EXTRACTED]
  ```
  export function chooseRow(state: SkillState, input: { choice: SessionHostChoice; profile: SessionHostProfile; judgeTool?: string; judge?: ConfinedJudge }): Moved<'R13'> | Answered<'R15'> {
  ```
- `ackRow` ← src/workflow/drivers/skill/transitions.ts:801 [EXTRACTED]
  ```
  export function ackRow(state: SkillState, attempt: AttemptId): Moved<'K1' | 'K2'> | Answered<'K3' | 'R14'> {
  ```
- `adoptRow` ← src/workflow/drivers/skill/transitions.ts:820 [EXTRACTED]
  ```
  export function adoptRow(state: SkillState, input: { attempt: AttemptId; dir: string; at: string }): MovedWithEffects<'K4'> | Answered<'K5' | 'R14'> {
  ```
- `replyRow` ← src/workflow/drivers/skill/transitions.ts:846 [EXTRACTED]
  ```
  export function replyRow(state: SkillState, input: { reply: EngineReply; at: string; version?: RunVersion; idle?: WhenIdle }):
  ```
- `offeredRow` ← src/workflow/drivers/skill/transitions.ts:941 [EXTRACTED]
  ```
  export function offeredRow(input: { steps: string[]; offered: PersonHandoff; limit?: string }): { row: 'D31'; turn: TurnAnswer } | { row: 'D32'; handoff: PersonHandoff } | { row: 'D38'; waiting: Waiting; turn: TurnAnswer } {
  ```
- `giveUpRow` ← src/workflow/drivers/skill/transitions.ts:968 [EXTRACTED]
  ```
  export function giveUpRow(state: SkillState, reply: EngineReply): MovedWithEffects<'D29'> | undefined {
  ```
- `heldProbeRow` ← src/workflow/drivers/skill/transitions.ts:977 [EXTRACTED]
  ```
  export function heldProbeRow(reply: EngineReply): { row: 'D27' } | undefined {
  ```
- `gateCheckRow` ← src/workflow/drivers/skill/transitions.ts:985 [EXTRACTED]
  ```
  export function gateCheckRow(state: SkillState, reply: EngineReply): Moved<'H5'> | undefined {
  ```
- `respondedRow` ← src/workflow/drivers/skill/transitions.ts:998 [EXTRACTED]
  ```
  export function respondedRow(state: SkillState, reply: RespondReply): Moved<'H1' | 'H2'> | Answered<'H3' | 'H4', Relayed> {
  ```
- `cancelledRow` ← src/workflow/drivers/skill/transitions.ts:1014 [EXTRACTED]
  ```
  export function cancelledRow(state: SkillState, input: { attempt: AttemptId; at: string }): Moved<'D2' | 'D3' | 'D4' | 'D5'> | undefined {
  ```
- `deadlineRow` ← src/workflow/drivers/skill/transitions.ts:1047 [EXTRACTED]
  ```
  export function deadlineRow(state: SkillState, input: { attempt: AttemptId; deadline: string }): Moved<'D33'> | undefined {
  ```
- `graceRow` ← src/workflow/drivers/skill/transitions.ts:1054 [EXTRACTED]
  ```
  export function graceRow(state: SkillState): { row: 'D18' } | undefined {
  ```
- `lockBusyRow` ← src/workflow/drivers/skill/transitions.ts:1059 [EXTRACTED]
  ```
  export function lockBusyRow(run: RunId): Answered<'D19', Refused> {
  ```
- `turnRow` ← src/workflow/drivers/skill/transitions.ts:1064 [EXTRACTED]
  ```
  export function turnRow(state: SkillState, input: { session: string | undefined; ticked: TickTurn }): Moved<'D20'> & { turn: TurnAnswer; waiting?: Waiting } {
  ```
- `pollRow` ← src/workflow/drivers/skill/transitions.ts:1078 [EXTRACTED]
  ```
  export function pollRow(state: SkillState, input: { session: string | undefined; busy: boolean; boundReached: boolean; ticked: TickTurn; scoringWaits: boolean }):
  ```
- `preparedRow` ← src/workflow/drivers/skill/transitions.ts:1104 [EXTRACTED]
  ```
  export function preparedRow<TRow extends 'C1' | 'C12'>(state: SkillState, input: { attempt: AttemptId; row: TRow }): Moved<TRow> | undefined {
  ```
- `confinedEndedRow` ← src/workflow/drivers/skill/transitions.ts:1113 [EXTRACTED]
  ```
  export function confinedEndedRow(state: SkillState, input: { attempt: AttemptId; ended: ConfinedStepEnd }): MovedWithEffects<'C13'> | undefined {
  ```
- `offerRow` ← src/workflow/drivers/skill/transitions.ts:1125 [EXTRACTED]
  ```
  export function offerRow(state: SkillState, input: { attempt: AttemptId; dispatch: Dispatch }): Moved<'C2'> | undefined {
  ```
- `placeBusyRow` ← src/workflow/drivers/skill/transitions.ts:1134 [EXTRACTED]
  ```
  export function placeBusyRow(state: SkillState, input: { attempt: AttemptId; behind: AttemptId }): Moved<'C4'> | undefined {
  ```
- `unqueueRow` ← src/workflow/drivers/skill/transitions.ts:1143 [EXTRACTED]
  ```
  export function unqueueRow(state: SkillState, input: { attempt: AttemptId; at: string }): MovedWithEffects<'D9'> | undefined {
  ```
- `prepareFailedRow` ← src/workflow/drivers/skill/transitions.ts:1153 [EXTRACTED]
  ```
  export function prepareFailedRow(state: SkillState, input: { attempt: AttemptId; body: ReportBody; cause: 'place' | 'model'; changed?: readonly string[] }): MovedWithEffects<'C3' | 'C7'> | undefined {
  ```
- `exitedRow` ← src/workflow/drivers/skill/transitions.ts:1168 [EXTRACTED]
  ```
  export function exitedRow(state: SkillState, input: { attempt: AttemptId; body: ReportBody; tail?: string }): MovedWithEffects<'C8'> | undefined {
  ```
- `MAX_RUNNER_RESTARTS` ← src/workflow/drivers/skill/transitions.ts:1183 [EXTRACTED]
  ```
  export const MAX_RUNNER_RESTARTS = 3;
  ```
- `runnerFreeRow` ← src/workflow/drivers/skill/transitions.ts:1191 [EXTRACTED]
  ```
  export function runnerFreeRow(state: SkillState, input: { attempt: AttemptId; at: string; graceMs: number }): MovedWithEffects<'C10' | 'C11' | 'C14'> | undefined {
  ```
- `runnerStopRow` ← src/workflow/drivers/skill/transitions.ts:1224 [EXTRACTED]
  ```
  export function runnerStopRow(state: SkillState, attempt: AttemptId): MovedWithEffects<'C9'> | undefined {
  ```
- `reportedRow` ← src/workflow/drivers/skill/transitions.ts:1233 [EXTRACTED]
  ```
  export function reportedRow(state: SkillState, input: { attempt: AttemptId; reply: ReportReply; at: string }): Moved<'P7' | 'P8' | 'P9'> | Answered<'P10', Relayed> | undefined {
  ```
- `resendRow` ← src/workflow/drivers/skill/transitions.ts:1267 [EXTRACTED]
  ```
  export function resendRow(state: SkillState, attempt: AttemptId): MovedWithEffects<'P11'> | undefined {
  ```
- `reportRow` ← src/workflow/drivers/skill/transitions.ts:1282 [EXTRACTED]
  ```
  export function reportRow(state: SkillState, input: { attempt: AttemptId; modelUnavailable: boolean; result: ChildResult; session: string | undefined; tool: string | undefined }):
  ```
- `placingRow` ← src/workflow/drivers/skill/transitions.ts:1412 [EXTRACTED]
  ```
  export function placingRow(state: SkillState, open: Extract<AttemptState, { phase: 'preparing' }>, input: { ask: PlaceAsk; refused?: string }): Moved<'C5' | 'C6'> {
  ```
- `errorOf` ← src/workflow/drivers/skill/turn.ts:230 [EXTRACTED]
  ```
  export function errorOf(answer: Answer, context: { invocation: Invocation; same: Literal; run?: RunId; localTool?: string; tool?: string }): SkillError {
  ```
- `scoringWaits` ← src/workflow/drivers/skill/turn.ts:425 [EXTRACTED]
  ```
  export function scoringWaits(scoring: readonly SkillState[]): boolean {
  ```
- `turnOf` ← src/workflow/drivers/skill/turn.ts:498 [EXTRACTED]
  ```
  export function turnOf(state: SkillState, input: { events: TurnEvent[]; after?: NonNullable<Turn['then']>; waiting?: Waiting; quiet?: true; localTool?: string; scoring?: readonly SkillState[]; offered?: string[] }): Turn {
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
- `defineRule` ← oxlint-plugin-teamai/rules/attempt-abort.js:43 [INFERRED]
  ```
  export default defineRule({
  ```
- `MARKER_READERS` ← oxlint-plugin-teamai/rules/attempt-marker-reads.js:12 [EXTRACTED]
  ```
  export const MARKER_READERS = scopedFiles(['src/workflow/attempt-marker.ts', 'src/launch-context.ts', 'src/hook-fast-path.ts']);
  ```
- `isAttemptMarkerReadChecked` ← oxlint-plugin-teamai/rules/attempt-marker-reads.js:20 [EXTRACTED]
  ```
  export function isAttemptMarkerReadChecked(file) {
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/attempt-marker-reads.js:24 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/attempt-reattach.js:32 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/attempt-result-writes.js:33 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/config-load-options.js:34 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/configured-tool-paths.js:37 [INFERRED]
  ```
  export default defineRule({
  ```
- `FACTS_FILES` ← oxlint-plugin-teamai/rules/family-facts.js:13 [EXTRACTED]
  ```
  export const FACTS_FILES = new Set(scopedFiles([
  ```
- `startupEntries` ← oxlint-plugin-teamai/rules/family-facts.js:54 [EXTRACTED]
  ```
  export function startupEntries(root) {
  ```
- `isFactsModule` ← oxlint-plugin-teamai/rules/family-facts.js:137 [EXTRACTED]
  ```
  export function isFactsModule(relative) {
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/family-facts.js:212 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/git-exit-code.js:114 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/home-env.js:9 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/launch-env.js:22 [INFERRED]
  ```
  export default defineRule({
  ```
- `ALLOWED` ← oxlint-plugin-teamai/rules/launch-through-workflows.js:7 [EXTRACTED]
  ```
  export const ALLOWED = ['src/workflow/', 'packages/runtime-tools/', 'packages/runtime-sandbox/'];
  ```
- `LAUNCHERS` ← oxlint-plugin-teamai/rules/launch-through-workflows.js:14 [EXTRACTED]
  ```
  export const LAUNCHERS = {
  ```
- `TOOL_EXECUTABLES` ← oxlint-plugin-teamai/rules/launch-through-workflows.js:37 [EXTRACTED]
  ```
  export const TOOL_EXECUTABLES = new Set([
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/launch-through-workflows.js:65 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/launcher-conformance.js:49 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/learnings-root.js:5 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/mock-source.js:49 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/no-low-value-comments.js:32 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/no-provider-merge.js:8 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/opencode-major.js:70 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/package-boundaries.js:108 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/piped-git.js:36 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/process-reads.js:37 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/readline-error.js:140 [INFERRED]
  ```
  export default defineRule({
  ```
- `NOT_YET_MOVED` ← oxlint-plugin-teamai/rules/recursive-readdir.js:20 [EXTRACTED]
  ```
  export const NOT_YET_MOVED = new Map(Object.entries({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/recursive-readdir.js:101 [INFERRED]
  ```
  export default defineRule({
  ```
- `isReadChecked` ← oxlint-plugin-teamai/rules/regular-file-reads.js:28 [EXTRACTED]
  ```
  export function isReadChecked(file) {
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/regular-file-reads.js:32 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/remove-delivered.js:28 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/rules-locate.js:6 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/runtime-serve.js:48 [INFERRED]
  ```
  export default defineRule({
  ```
- `SHIPPED_ONLY` ← oxlint-plugin-teamai/rules/shipped-tool-ids.js:16 [EXTRACTED]
  ```
  export const SHIPPED_ONLY = new Map(Object.entries({
  ```
- `BASE_ID_COMPARISONS` ← oxlint-plugin-teamai/rules/shipped-tool-ids.js:61 [EXTRACTED]
  ```
  export const BASE_ID_COMPARISONS = new Map(Object.entries({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/shipped-tool-ids.js:223 [INFERRED]
  ```
  export default defineRule({
  ```
- `OWNER` ← oxlint-plugin-teamai/rules/signal-owner.js:8 [EXTRACTED]
  ```
  export const OWNER = scopedFiles(['packages/shared/src/process-group.ts']);
  ```
- `RUN_AS_IS` ← oxlint-plugin-teamai/rules/signal-owner.js:14 [EXTRACTED]
  ```
  export const RUN_AS_IS = scopedFiles(['packages/runtime-sandbox/src/testing/fake-engine.mjs']);
  ```
- `SCRIPT_TEXT` ← oxlint-plugin-teamai/rules/signal-owner.js:21 [EXTRACTED]
  ```
  export const SCRIPT_TEXT = scopedFiles([
  ```
- `NOT_A_CHILD` ← oxlint-plugin-teamai/rules/signal-owner.js:35 [EXTRACTED]
  ```
  export const NOT_A_CHILD = new Map([
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/signal-owner.js:201 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/spawn-command.js:44 [INFERRED]
  ```
  export default defineRule({
  ```
- `isWriteChecked` ← oxlint-plugin-teamai/rules/step-path-writes.js:37 [EXTRACTED]
  ```
  export const isWriteChecked = isReadChecked;
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/step-path-writes.js:53 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/suppression-reason.js:11 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/test-seams.js:31 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/tool-facts.js:107 [INFERRED]
  ```
  export default defineRule({
  ```
- `familySource` ← oxlint-plugin-teamai/rules/tool-family-shape.js:12 [EXTRACTED]
  ```
  export function familySource(file) {
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/tool-family-shape.js:42 [INFERRED]
  ```
  export default defineRule({
  ```
- `HOME_VARIABLES` ← oxlint-plugin-teamai/rules/tool-home-env.js:13 [EXTRACTED]
  ```
  export const HOME_VARIABLES = new Set([
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/tool-home-env.js:77 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/tool-registry.js:38 [INFERRED]
  ```
  export default defineRule({
  ```
- `UNCACHED` ← oxlint-plugin-teamai/rules/uncached-entry.js:11 [EXTRACTED]
  ```
  export const UNCACHED = new Set(scopedFiles([
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/uncached-entry.js:19 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/unspawned-child.js:38 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/untrusted-finish-git.js:70 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/windows-tests.js:23 [INFERRED]
  ```
  export default defineRule({
  ```
- `SKILL_IMPORTS` ← oxlint-plugin-teamai/rules/workflow-boundaries.js:19 [EXTRACTED]
  ```
  export const SKILL_IMPORTS = {
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/workflow-boundaries.js:165 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/workflow-failure-codes.js:6 [INFERRED]
  ```
  export default defineRule({
  ```
- `ALLOWED` ← oxlint-plugin-teamai/rules/worktree-removal.js:10 [EXTRACTED]
  ```
  export const ALLOWED = [
  ```
- `inScope` ← oxlint-plugin-teamai/rules/worktree-removal.js:32 [EXTRACTED]
  ```
  export function inScope(file) {
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/worktree-removal.js:79 [INFERRED]
  ```
  export default defineRule({
  ```
- `defineRule` ← oxlint-plugin-teamai/rules/yaml-parse.js:22 [INFERRED]
  ```
  export default defineRule({
  ```