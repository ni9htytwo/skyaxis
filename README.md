# SkyAxis 天域枢 · 解决方案说明书
Interactive solution brief for SkyAxis — a human-machine collaborative ops platform for energy/industrial sites. Single-file HTML demo with a live site-map simulation. 
人机协同监管台 **SkyAxis 天域枢** 的产品说明页 —— 一个纯前端、单文件的交互式信息图，用来向新能源场站 / 工业园区的值班主管介绍"人员、车辆、机器人、无人机同一张图"的调度理念。

🔗 **在线预览**： `https://ni9htytwo.github.io/skyaxis/`

## 页面包含什么

- **实时态势模拟地图**：人员、车辆、巡检机器人、无人机在同一张场站地图上移动，可点击查看状态、按图层筛选，并有一键"触发异常"演练，模拟报警 → 就地派单 → 处置 → 复盘的全流程
- **为什么现有工具解决不了**：SCADA / 安防 / 飞控三套系统各自为政的问题，附"四块屏 vs 一张图"的可切换对比演示
- **核心能力**：六张可展开的能力卡片
- **系统架构**：呈现层 / 平台层 / 数据层三层结构，鼠标悬停或点击查看说明
- **PoC 合作时间线**：四步走的概念验证合作流程，可点击每一步查看详情
- **移动端适配**：已做过专门的移动端阅读优化（导航、地图横滑、触控热区等），手机打开也能正常看

## 技术栈

纯 `HTML / CSS / JavaScript`，无构建步骤、无依赖、无框架。唯一的外部资源是 Google Fonts（Noto Serif SC / Noto Sans SC / IBM Plex Mono）。所有交互（地图动画、演练流程、图表切换）都是原生 JS 实现。

## 本地预览

直接用浏览器打开 HTML 文件即可，不需要起服务、不需要装依赖：

```bash
# 克隆仓库后
open index.html        # macOS
# 或双击文件 / 拖进浏览器
```

## 部署到 GitHub Pages

1. 把 HTML 文件重命名为 `index.html`，放在仓库根目录（或 `/docs` 目录）
2. 仓库 Settings → Pages → Source 选择对应分支和目录 → Save
3. 稍等片刻，GitHub 会给出访问链接（通常是 `https://<用户名>.github.io/<仓库名>/`）

## 目录结构

```
.
└── index.html   # 页面全部内容（结构 / 样式 / 脚本）都在这一个文件里
```

## 说明

这是一份对外的解决方案说明 / 销售物料页面，用于概念验证（PoC）合作沟通，页面中的态势地图、事件日志等均为**模拟演示数据**，非真实场站接入数据。

---

天域世界 SkyWorld · SkyAxis 天域枢

