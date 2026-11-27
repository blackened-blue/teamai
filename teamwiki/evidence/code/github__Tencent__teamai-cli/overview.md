---
title: github__Tencent__teamai-cli overview
domain: code-knowledge
---

# github__Tencent__teamai-cli

**13807 facts** extracted from 1040 files.
Graph: 7307 nodes, 18743 edges.

## Module Structure

| Module | Facts | Components | Interfaces |
|--------|-------|------------|------------|
| src | 6067 | 4108 | 1764 |
| packages | 1218 | 747 | 408 |
| oxlint-plugin-teamai | 175 | 152 | 17 |
| scripts | 171 | 139 | 27 |

## Dependencies

- **src** → oxlint-plugin-teamai, tsup.config.ts, vitest.config.ts, vitest.e2e.config.ts, vitest.windows.config.ts, packages, scripts, .github
- **scripts** → packages, src
- **packages** → src, oxlint-plugin-teamai, scripts
- **vitest.windows.config.ts** → vitest.config.ts
- **.github** → src, packages

## Interfaces

Types: MQ(2)

## Key Dependency Paths

- WebhookEndpointSchema (src/types.ts): WebhookEndpointSchema → TOOL_IDS → SESSION_PLATFORM_FACTS → reportCommandError → applyNonInteractiveGitEnv → resetBundledRuntimeCache → ToolPathsSchema → PackageScopeSchema → CheckoutLockedError → findPromotionCandidates → antiSlopRules → noArrayFilterMapRule → noChainedTypeAssertionsRule → noConditionalEmptyObjectSpreadRule → noKnownValueWideningRule → noModuleMockingRule → LAUNCH_ADAPTERS → useToolInstances → defineRule → teamToolInstances → runsOwnBinary → toolHomeVariableNames → readWorkspaceChildren → PROJECT_RESOURCE_TYPES → syncFolders → resolveRealCwd → RoleIdSchema → usesMemberFilters → gitBinary → GitAnswers → gitFindsNoRepository → mergeTeamConfig → parseYaml → filterExistingTopLevelPaths → isCaseInsensitiveFs → RUN_MODES → isInteractive → prompts → placeOf → serveAttemptSocket → TAIL_CHARS → givenCredentials → probeBinary → recordStore → paseoKeyOf → judging → EVIDENCE_DIR → settleLateUsageReport → dropIndexesAfterRebuild → resolveLegacyRole → extractToml → publishQueuedLearnings
- WebhookEndpoint (src/types.ts): WebhookEndpoint → TOOL_IDS → SESSION_PLATFORM_FACTS → reportCommandError → applyNonInteractiveGitEnv → resetBundledRuntimeCache → ToolPathsSchema → PackageScopeSchema → CheckoutLockedError → findPromotionCandidates → antiSlopRules → noArrayFilterMapRule → noChainedTypeAssertionsRule → noConditionalEmptyObjectSpreadRule → noKnownValueWideningRule → noModuleMockingRule → LAUNCH_ADAPTERS → useToolInstances → defineRule → teamToolInstances → runsOwnBinary → toolHomeVariableNames → readWorkspaceChildren → PROJECT_RESOURCE_TYPES → syncFolders → resolveRealCwd → RoleIdSchema → usesMemberFilters → gitBinary → GitAnswers → gitFindsNoRepository → mergeTeamConfig → parseYaml → filterExistingTopLevelPaths → isCaseInsensitiveFs → RUN_MODES → isInteractive → prompts → placeOf → serveAttemptSocket → TAIL_CHARS → givenCredentials → probeBinary → recordStore → paseoKeyOf → judging → EVIDENCE_DIR → settleLateUsageReport → dropIndexesAfterRebuild → resolveLegacyRole → extractToml → publishQueuedLearnings
- WorkflowsHandler (src/resources/workflows.ts): WorkflowsHandler → FOLDER_MARKERS → syncFolders → isPlainJson → JsonValueSchema → resolveRealCwd → ToolArgumentsSchema → ToolPathsSchema → TOOL_IDS → SESSION_PLATFORM_FACTS → reportCommandError → antiSlopRules → LAUNCH_ADAPTERS → useToolInstances → teamToolInstances → runsOwnBinary → defineRule → importedName → FAMILY → readWorkspaceChildren → PROJECT_RESOURCE_TYPES → PackageScopeSchema → gitBinary → isCaseInsensitiveFs → RUN_MODES → isInteractive → prompts → settleLateUsageReport → SCORER_MARKER → WORKFLOW_MARKER → FolderFiles → listRepoFilesRecursive → ResourceHandler → classifyCopy → PackageAdapter → resolveLegacyRole → RoleIdSchema → extractToml → CODE_COLLECTION_VERSION → mapKindToEvidenceType → isMetadataRelation → isPlaceableType → isSafeNamespaceSegment → isManifestV2 → isActiveNamespace → RESOURCE_LAYOUTS → packageRoot
- getHandler (src/resources/index.ts): getHandler → ResourceHandler → ToolPathsSchema → TOOL_IDS → useToolInstances → defineRule → readWorkspaceChildren → gitBinary → RUN_MODES → PackageScopeSchema → syncFolders → isPlainJson → JsonValueSchema → resolveRealCwd → ToolArgumentsSchema → classifyCopy → MCP_EXCLUDE_OWNER → WRITER_IDS → assertSafePath → PackageAdapter → CODEX_TOOL → RESOURCE_LAYOUTS → FOLDER_MARKERS → isSafeNamespaceSegment → isManifestV2 → packageRoot → isActiveNamespace → FolderFiles → TeamSkillSource → FrontmatterDateSchema → RulesHandler → RuleFolders → PATH_VARIABLES → splitRuleFrontmatter → resolveDocsDestination → usesMemberFilters → PROJECT_RESOURCE_TYPES → isPlaceableType → unknownEnvVariableKeys → listRepoFilesRecursive → resolveLegacyRole → extractToml
- getAllHandlers (src/resources/index.ts): getAllHandlers → ResourceHandler → ToolPathsSchema → TOOL_IDS → useToolInstances → defineRule → readWorkspaceChildren → gitBinary → RUN_MODES → PackageScopeSchema → syncFolders → isPlainJson → JsonValueSchema → resolveRealCwd → ToolArgumentsSchema → classifyCopy → MCP_EXCLUDE_OWNER → WRITER_IDS → assertSafePath → PackageAdapter → CODEX_TOOL → RESOURCE_LAYOUTS → FOLDER_MARKERS → isSafeNamespaceSegment → isManifestV2 → packageRoot → isActiveNamespace → FolderFiles → TeamSkillSource → FrontmatterDateSchema → RulesHandler → RuleFolders → PATH_VARIABLES → splitRuleFrontmatter → resolveDocsDestination → usesMemberFilters → PROJECT_RESOURCE_TYPES → isPlaceableType → unknownEnvVariableKeys → listRepoFilesRecursive → resolveLegacyRole → extractToml
