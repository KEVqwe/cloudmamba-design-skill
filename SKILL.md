---
name: cloudmamba-design
description: "Apply Cloud Mamba (云曼巴/云曼巴智能) brand design to websites, product interfaces, presentations, posters, social graphics, and printed collateral. Use when the user requests 云曼巴风格、云曼巴设计语言 or consistent Cloud Mamba branded output. Includes exact logo and mascot SVGs, color/font tokens, composition rules, and separate marketing/product treatments. Do not apply to unrelated brands, generic SEO/deployment, or medical advice merely because Cloud Mamba is mentioned."
---

# 云曼巴设计语言

把现有云曼巴品牌系统延续到新产物。核心是暖奶油底、墨黑粗宋体、蓝黄红平涂色块、手作毛边、云蛇标志与曼巴小队；产品工作台保留品牌识别，降低装饰密度。

## 工作顺序

1. 从用户任务判断产物、受众、尺寸与交付格式；已有页面/模板优先沿用。缺失的低风险细节自行合理选择，只有影响结果的关键缺口才询问。
2. 阅读 [品牌规则](references/brand-system.md) 和 [毛边、造型与原稿依据](references/texture-and-shape.md)。这套风格的关键是可见的文字与图形轮廓毛边，不能只匹配配色与字体。涉及产品介绍时同时阅读 [品牌定位与文案](references/positioning.md)。
3. 依产物阅读 [应用规范](references/applications.md) 的相关部分。可打开 `assets/brand-board.html` 直接查看品牌组合与组件示例。
4. 从 `assets/logos/` 选已有 SVG；从 `assets/mascots/` 选姿态。网页使用 `assets/tokens.css`、`assets/fonts.css`、`assets/rough.css`，并将 `assets/motifs/rough-filters.svg` 的整个 SVG 标记内联到页面一次。仅把滤镜文件作为图片引用不会使 CSS 滤镜生效。其他媒介读取 `assets/tokens.json`，参考 `assets/texture-study.html` 的实际效果。资源路径相对于本 skill 目录，交付时复制进目标项目并改为项目内路径。
5. 先把信息层级、文字和布局做对，再添加少量装饰。不要靠重新生成 logo 或堆满小蛇来表达品牌。
6. 按实际目标尺寸渲染并检查，修复后再交付。遵循用户已授权的修改/发布范围；使用本 skill 本身不额外授权上传、部署或发布。

## 必须保持的识别

- 正式标志使用随附原始 SVG，保持比例、眼睛与红色分叉舌头；不能用文字重排或近似云图标替代。
- 大标题用 Noto Serif SC 900；短英文标签用 Alfa Slab One；正文与操作界面用清晰的中文无衬线。随附原始字体及 OFL 许可；预览和导出前确认字体加载。不能以系统宋体回退效果验收精确复刻。
- 大面积以 `cream` / `paper` 和 `ink` 为基底；蓝、黄、红建立层级。粉、绿、梅红主要用于角色与少量点缀。
- 官网、海报、PPT 用大字号、截断圆形、粗横线、黄条标签与厚墨黑底壳的软件窗口。当前 Big Walk 套装没有整体旋转或投影，默认平直、平涂；手作感由轮廓产生。硬阴影只作为产品工作台的局部延展，不能代替原稿的厚底壳。
- 品牌中文标题、英文 slab 标题/短口号、海报黄条文字使用细密的 `roughtext`；圆形、粗线、色块、角色使用更粗的 `rough`。黄条的底色和文字分开施加滤镜。正文、数据、真实按钮文字、表单和知识图谱标签保持清楚。
- 不把 `rough` 套到整个页面或整张卡片，不给已有毛边的 Logo 再次加滤镜，不用模糊、像素锯齿或满版噪点代替轮廓毛边。小尺寸减弱并按最终显示尺寸检查。
- 中文品牌名称为“云曼巴”或“云曼巴智能”，英文为“Cloud Mamba”。当前行业边界与产品表达见定位参考，不能复制旧稿里的泛行业定位。

## 检查结果

- 识别：是否使用原标志、正确字体和色值？在1:1下文字笔画、色块与横线是否真的有毛边？放大后应是不规则的实色轮廓，不是模糊/锯齿。窗口是否为厚墨黑底壳、红黄蓝圆点？是否擅加旋转或阴影？
- 内容：消费医疗垂直、售前/售中/售后、模块协同及本体知识图谱的关系是否准确？区分现有能力与规划，不编造客户、指标或医疗效果。
- 可用性：文字清楚、对比足够、焦点可见，状态不只靠颜色；网页在窄屏与桌面均无溢出，尊重减少动效设置。
- 交付：无缺失图片、SVG 外部依赖、字体缺字、占位文案、私人绝对路径或真实客户数据。印刷品单独核对实际尺寸、出血与色彩要求。
- 汇报：给出产物与预览，说明使用的品牌元素、验证情况，以及字体或格式的实际限制。
