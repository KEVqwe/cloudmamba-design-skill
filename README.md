# 云曼巴设计语言 Skill

将云曼巴现有品牌语言用于官网、产品工作台、PPT、海报、社交封面和印刷物料。

包含可复用规则、配色与字体 tokens、9 个原始 logo SVG 与 3 个官网紧边界版本、6 个曼巴角色 SVG，以及可离线打开的品牌参考页。品牌定位为“消费医疗全链路 AI 经营系统”。

![云曼巴标志](assets/logos/horizontal-web-color.svg)

## 安装

把整个仓库放在 Codex 的技能目录中，目录名为 `cloudmamba-design`：

```sh
git clone https://github.com/KEVqwe/cloudmamba-design-skill.git ~/.codex/skills/cloudmamba-design
```

本仓库公开可读。若配置了 `CODEX_HOME`，改用该目录下的 `skills/cloudmamba-design`。目标目录已有内容时先检查，不覆盖已有定制。安装后开启新会话，让技能目录重新被发现。

其他支持 `SKILL.md` 的工具也可安装整个目录，并保留相对文件结构。

## 使用示例

```text
使用 $cloudmamba-design，设计云曼巴售后智能体介绍页，适配手机和桌面。

使用 $cloudmamba-design，为消费医疗全链路 AI 经营系统做一套 16:9 提案。

使用 $cloudmamba-design，优化智能体工作台；保留品牌识别，优先操作清晰。
```

## 内容

- `SKILL.md`：技能触发、流程与验收标准。
- `references/`：品牌系统、应用规范、当前定位与文案。
- `assets/tokens.css` / `tokens.json`：统一颜色、字体与基础尺寸。
- `assets/logos/`：图形、横版、竖版，各有彩色/黑色/反白。
- `assets/mascots/`：站立、盘绕、游动的独立 SVG。
- `assets/motifs/`：毛边滤镜与品牌箭头。
- `assets/brand-board.html`：本地打开即可查看的响应式品牌参考页。
- `agents/openai.yaml`：Codex 显示信息。

字体文件不包含在本包中；精确复刻需要项目加载 Noto Serif SC 900 和 Alfa Slab One，离线参考页会使用系统回退字体。SVG 字标已转为路径。

品牌素材依据现有云曼巴源文件整理；通用应用建议已在规范中标明。本仓库未授予第三方使用云曼巴商标与品牌资产的许可。更新设计时同步修改规范、tokens 与参考页，保持三者一致。
