# Changelog

## [0.0.4] - 未发布

### 新增

- 无

### 修复

- 无

### 变更

- **破坏性变更**：包名与 PyPI 发布名从 `notenotice` 改为 `funnotice`，以匹配仓库名。原先 `import notenotice` / `pip install notenotice` 的用法需迁移为 `import funnotice` / `pip install funnotice`。
- 源码目录迁移到 `src/funnotice/` 标准布局。

### 废弃

- 旧 `notenotice` PyPI 包计划发布一个最终版本，转发依赖到 `funnotice`（需要仓库所有者手动操作，不在本次改动范围内，见 [farfarfun/todo-list#441](https://github.com/farfarfun/todo-list/issues/441)）。
