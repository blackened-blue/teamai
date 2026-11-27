# Team Wiki Router

## 产品域路由

| 域 | 入口 | 核心职责 | 路由关键词 |
|---|---|---|---|
| 其他 | [[code/github__Tencent__teamai-cli/index]] | **13807 facts** extracted from 1040 files. Graph: 7307 nodes, 18743 edges. | src, oxlint-plugin-teamai, scripts, packages, tsup.config.ts, vitest.config.ts |

## 路由规则

1. **按组件名匹配** → 路由关键词列对应域
2. **跨仓库依赖问题** → 查 graph-index.json 的 DEPENDS_ON 边
3. **接口/API 问题** → 优先匹配有 interfaces.md 的仓库
4. **调用链/排障** → 查对应仓库的 dependency-paths.md
5. **模块职责概述** → 查 overview.md 或 modules/*.md
