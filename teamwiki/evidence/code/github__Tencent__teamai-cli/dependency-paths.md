---
title: github__Tencent__teamai-cli dependency paths
domain: code-knowledge
---

# Dependency Paths

Static import dependency paths (not runtime call traces).

17 dependency path(s) traced from entry points (max depth 4).

## HandlerRegistration (src/hook-handlers.ts)

- [entry] `HandlerRegistration` ← src/hook-handlers.ts:29
      - [data] `HookStdinSchema` ← src/hook-dispatch.ts:27
    - [service] `GIT_HOOK_EVENTS` ← src/git-hook.ts:35
    - [service] `TEAMAI_BIN_DIR` ← src/builtin-hooks.ts:39
    - [service] `FOREGROUND_PAYLOAD_KEYS` ← src/hook-fast-path.ts:40

## PULL_TIMEOUT_MS (src/hook-handlers.ts)

- [entry] `PULL_TIMEOUT_MS` ← src/hook-handlers.ts:109
      - [data] `HookStdinSchema` ← src/hook-dispatch.ts:27
    - [service] `GIT_HOOK_EVENTS` ← src/git-hook.ts:35
    - [service] `TEAMAI_BIN_DIR` ← src/builtin-hooks.ts:39
    - [service] `FOREGROUND_PAYLOAD_KEYS` ← src/hook-fast-path.ts:40

## buildAdoptedSummary (src/hook-handlers.ts)

- [entry] `buildAdoptedSummary` ← src/hook-handlers.ts:668
      - [data] `HookStdinSchema` ← src/hook-dispatch.ts:27
    - [service] `GIT_HOOK_EVENTS` ← src/git-hook.ts:35
    - [service] `TEAMAI_BIN_DIR` ← src/builtin-hooks.ts:39
    - [service] `FOREGROUND_PAYLOAD_KEYS` ← src/hook-fast-path.ts:40

## eligibleUpvotes (src/hook-handlers.ts)

- [entry] `eligibleUpvotes` ← src/hook-handlers.ts:683
      - [data] `HookStdinSchema` ← src/hook-dispatch.ts:27
    - [service] `GIT_HOOK_EVENTS` ← src/git-hook.ts:35
    - [service] `TEAMAI_BIN_DIR` ← src/builtin-hooks.ts:39
    - [service] `FOREGROUND_PAYLOAD_KEYS` ← src/hook-fast-path.ts:40

## buildHandlerRegistry (src/hook-handlers.ts)

- [entry] `buildHandlerRegistry` ← src/hook-handlers.ts:1354
      - [data] `HookStdinSchema` ← src/hook-dispatch.ts:27
    - [service] `GIT_HOOK_EVENTS` ← src/git-hook.ts:35
    - [service] `TEAMAI_BIN_DIR` ← src/builtin-hooks.ts:39
    - [service] `FOREGROUND_PAYLOAD_KEYS` ← src/hook-fast-path.ts:40

## filterHandlersForConfig (src/hook-handlers.ts)

- [entry] `filterHandlersForConfig` ← src/hook-handlers.ts:1472
      - [data] `HookStdinSchema` ← src/hook-dispatch.ts:27
    - [service] `GIT_HOOK_EVENTS` ← src/git-hook.ts:35
    - [service] `TEAMAI_BIN_DIR` ← src/builtin-hooks.ts:39
    - [service] `FOREGROUND_PAYLOAD_KEYS` ← src/hook-fast-path.ts:40

## observerReads (scripts/verify/observer.ts)

    - [service] `observerReads` ← scripts/verify/observer.ts:58

## attemptsObserved (scripts/verify/observer.ts)

    - [service] `attemptsObserved` ← scripts/verify/observer.ts:68

## Listed (scripts/verify/observer.ts)

    - [service] `Listed` ← scripts/verify/observer.ts:167

## ProcEntry (scripts/verify/observer.ts)

    - [service] `ProcEntry` ← scripts/verify/observer.ts:192

## bwrapSteps (scripts/verify/observer.ts)

    - [service] `bwrapSteps` ← scripts/verify/observer.ts:203

## startObserver (scripts/verify/observer.ts)

    - [service] `startObserver` ← scripts/verify/observer.ts:236

## getHandler (src/resources/index.ts)

- [entry] `getHandler` ← src/resources/index.ts:36

## getAllHandlers (src/resources/index.ts)

- [entry] `getAllHandlers` ← src/resources/index.ts:40

## HookHandler (src/hook-dispatch.ts)

- [entry] `HookHandler` ← src/hook-dispatch.ts:38

## HandlerRegistration (src/hook-dispatch.ts)

- [entry] `HandlerRegistration` ← src/hook-dispatch.ts:52

## main (scripts/verify/observer.ts)

    - [service] `main` ← scripts/verify/observer.ts:1
