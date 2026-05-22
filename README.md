# 方块纪元：征伐（Block Era: Conquest）

官方开源 Wiki 仓库，用于维护《方块纪元：征伐》的规则、技能、事件与单位数据。内容以 Markdown 形式组织，适合作为规则编写、版本迭代与协作维护的统一来源。本 README 仅作为仓库说明，不是 Wiki 首页。

## 访问 Wiki

要访问本Wiki，请前往我们的网站：https://mclm.gitbook.io/bec

## 项目定位

- 目标：提供完整、可检索、可版本化的游戏规则与数据资料库。
- 受众：规则维护者、内容策划、编辑与社区贡献者。
- 形态：纯 Markdown 文档，按目录分层管理。

## 亮点与特性

- 统一索引体系：`SUMMARY.md` + 目录 `00-index.md` 双入口。
- 可版本化：以 `rules/12-version/` 记录变更。
- 结构清晰：规则、技能、事件、单位数据分层管理。
- 易维护：编号与目录一致，便于协作扩展。

## 导航方式

- 目录树入口：`SUMMARY.md`
- 规则总索引：`rules/00-index.md`

## 内容体系

- 规则正文：`rules/01-overview/` 至 `rules/08-deckbuilding/`
- 技能词典：`rules/09-skills/`
- 事件牌：`rules/10-events/`
- 单位牌数据：`rules/11-unit-data/`
- 版本变更：`rules/12-version/`

## 常用入口

- [规则文档](rules/00-index.md)
- [技能词典](skills/00-index.md)
- [事件牌效果说明](events/00-index.md)
- [单位牌数据表](unit-data/00-index.md)
- [版本信息](version/00-index.md)

## 目录结构

- `rules/`：规则与数据主体
- `rules/01-overview/`：项目概览
- `rules/02-core-concepts/`：核心概念
- `rules/03-flow/`：流程规则
- `rules/04-combat/`：战斗规则
- `rules/05-card-types/`：卡牌类型
- `rules/06-unit-attributes/`：单位属性
- `rules/07-fatigue/`：疲劳机制
- `rules/08-deckbuilding/`：组牌规则
- `rules/09-skills/`：技能词典
- `rules/10-events/`：事件牌
- `rules/11-unit-data/`：单位牌数据
- `rules/12-version/`：版本变更

## 使用方式

- 阅读：从 `rules/00-index.md` 或 `SUMMARY.md` 开始逐级浏览。
- 检索：优先通过 `00-index.md` 进入目录，再定位条目。
- 维护：按现有目录结构新增或修改条目，保持标题与编号一致。

## 文档约定

- 文件命名：`NN-名称.md`，`NN` 为两位编号（如 `03-flow`、`01-wood-sword.md`）。
- 索引文件：每个目录使用 `00-index.md` 作为入口。
- 目录同步：新增/移动条目后必须更新 `SUMMARY.md` 与对应目录的 `00-index.md`。
- 术语一致：同一术语保持统一译名与定义，必要时在索引页补充说明。
- 标题规范：标题层级不跳级，一级标题仅用于页面标题。

## 维护流程（建议）

1. 在对应目录新增条目或修订内容。
2. 更新该目录的 `00-index.md`。
3. 更新 `SUMMARY.md` 中的目录树。
4. 自检链接与标题编号是否一致。

## 质量检查清单

- 目录树：`SUMMARY.md` 是否包含新增页面。
- 索引页：`00-index.md` 是否已更新。
- 链接：是否存在断链或路径错误。
- 编号：文件编号与索引顺序是否一致。
- 术语：是否与词典或已有条目保持一致。

## 贡献方式

- 规则修订：请说明修改动机与影响范围。
- 新增内容：请标注来源或依据（如内部设计稿、版本变更说明）。
- 结构调整：涉及目录结构变更时请同时修改索引与目录树。

## 版本与发布

- 版本记录：集中维护于 `rules/12-version/`。
- 重大变更：请在版本记录中说明变更范围与影响。
- 命名建议：版本号采用 `主版本.次版本.修订` 形式。

## 版权与许可

- 许可协议见 `LICENSE`。
