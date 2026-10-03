# Changelog

## [0.0.4] - 未发布

### 新增

- 无

### 修复

- 无

### 变更

- **破坏性变更**：包名与 PyPI 发布名从 `notenotice` 改为 `funnotice`，以匹配仓库名。原先 `import notenotice` / `pip install notenotice` 的用法需迁移为 `import funnotice` / `pip install funnotice`。
- 源码目录迁移到 `src/funnotice/` 标准布局。
- 开发环境加入 Ruff，并统一版本来源到 `pyproject.toml`。

### 废弃

- 旧包名 `notenotice` 从未发布到 PyPI（`pypi.org/pypi/notenotice/json` 返回 404），
  也不存在独立的 `farfarfun/notenotice` 仓库，没有需要迁移的下游用户，因此不需要也
  无法发布"最终转发版本"（见 [farfarfun/todo-list#441](https://github.com/farfarfun/todo-list/issues/441)、
  [#575](https://github.com/farfarfun/todo-list/issues/575)）。
