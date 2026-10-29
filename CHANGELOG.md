# Changelog

## [Unreleased]

- 接收联盟移出的实训基地管理内容：`data/context`、`data/brochure`、`data/journal`、`data/profile` 四个子仓各新增 `default/` 记忆集——意图一篇、SVIP 特权一篇、日志三篇、组织档案一篇。
- 配齐 `data/` 与 `docs/` 子模块：按命名契约 `quanttide-{类型}-of-training-base` 新建 17 个子仓库（`data/` 11 个、`docs/` 6 个）；`apps/` 与 `examples/` 保持原样。
- `data/library` 与 `data/profile` 由仓库内直接组织改为子模块，原有各一份文档分别迁入 `quanttide-library-of-training-base` 与 `quanttide-profile-of-training-base`。
- README 概述去掉「本仓库不设下级子仓库」，`default/` 更正为 `defaults/`，补目录说明。
- 新增子模块 `apps/qtgame-tycoon`，指向 `quanttide/qtgame-tycoon`。
- 新增子模块 `apps/qtgame-weiqi`，指向 `quanttide/qtgame-weiqi`。
- 子模块 `examples/quanttide-asset-lab` 引入 second-brain-init 技能原始资料至 `src/cli/`。
- 新增子模块 `examples/quanttide-asset-lab`，指向 `quanttide/quanttide-asset-lab`。
- 初始化仓库：量潮实训基地主体档案。
- data/journal 子模块更新：迁入实训基地实录 35 篇（2026-08~09，自量潮科技日志仓）
- data/journal 子模块更新：7 篇业务设计日志移回公司日志仓
