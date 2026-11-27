# 交互式立体图解

**English name:** Anatomy — Interactive Isometric Explainer  
**Skill ID:** `anatomy`

## 用途

将技术概念转化为精细、可交互的等轴测立体图。适用于产品结构、机械原理、系统架构、算法工作方式和技术文章配图。设计原则是让真实的物体结构本身解释概念，而不是只画方框和箭头。画面使用四色明暗和正确的遮挡顺序，放在带标题、提示和实时读数的图框里，并可以加入与等轴测视角一致的 WebGL 效果（火焰、排气、水面、焦散、灯光）。需要纸质稿时，可以从成品图导出 A4 或 Letter PDF，格式包括海报、工程图和讲义。

## 在 Codex 中使用

在项目任务中输入 `$anatomy`，并描述要解释的概念。例如：

> $anatomy 请制作一张可交互的等轴测立体图，解释亚马逊 FBA 入仓流程，用中文标注关键步骤。

Claude Code、Antigravity、OpenCode 和 MiniMax Code 中对应命令是 `/anatomy`。

## 本目录内容

本目录是上游技能的完整副本，包含 `SKILL.md`、`kit/`、`examples/`、`references/`、`scripts/`、`tests/`、`evals/`、`LICENSE`，以及上游 README、变更记录和示例图。可打印页的说明与实现在 `references/print.md`、`scripts/print.mjs`、`scripts/print-sheet.mjs` 和 `kit/pdf-button.mjs`；`examples/push-button/` 是带 PDF 按钮的示例。`agents/openai.yaml` 保留本仓库的中文显示名。

## 环境要求

- Node.js 20.10 或更高版本。
- Chrome 或 Chromium，用于截图和浏览器检查。
- 技能本身不需要 `npm install`。

## 来源与许可证

- 上游仓库：<https://github.com/wheresryan22/anatomy>
- 同步自上游默认分支 `main` 的提交 `1482e8469b0a9e0d8cc18ea2740a01423d29ae80`
- 同步日期：2026-11-27（Asia/Shanghai）
- 本技能采用上游 MIT 许可证，全文见本目录 [`LICENSE`](LICENSE)。
