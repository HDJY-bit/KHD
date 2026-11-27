# KHD

本仓库是一个 Agent 技能集合。技能放在 `.agents/skills/<技能标识>/`，每个技能以该目录下的 `SKILL.md` 为入口。

在 Codex 任务里输入 `$` 加上技能标识，再写明要做的事。

## 交互式立体图解（`anatomy`）

把技术概念做成精细、可交互的等轴测立体图：用真实物体的结构解释原理，而不是方框和箭头。技能可以画 SVG、加入 WebGL 效果，并把成品图印成 A4 或 Letter PDF。

- 目录：`.agents/skills/anatomy/`
- 中文说明：`.agents/skills/anatomy/README-中文.md`
- 调用：在 Codex 中输入 `$anatomy`。Claude Code、Antigravity、OpenCode 和 MiniMax Code 中使用 `/anatomy`。
- 同步：2026-11-27（Asia/Shanghai）从上游默认分支完整同步，来源为 [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy)（`main` @ `1482e8469b0a9e0d8cc18ea2740a01423d29ae80`）。
- 许可证：Anatomy 技能携带上游 MIT 许可证，全文在 `.agents/skills/anatomy/LICENSE`。

## 费曼学习法（`feiman-learning`）

用自己的话复述概念，再通过追问、纠错和迁移测试判断是否真的学会。可以从头学习，也可以闭卷检验。

- 目录：`.agents/skills/feiman-learning/`
- 中文说明：`.agents/skills/feiman-learning/README-中文.md`
- 调用：在 Codex 中输入 `$feiman-learning`。

费曼学习法目录没有许可证文件。本仓库根目录也没有为整个仓库声明许可证。
