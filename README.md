# AI 博主调研报告

> 六大平台 AI 领域头部博主全景分析 — 覆盖 B站、小红书、抖音、知乎、视频号、公众号，共计 120 位头部创作者的深度调研。

## 项目亮点

- **六大平台全覆盖** — B站、小红书、抖音、知乎、视频号、公众号，每个平台 Top 20 AI 博主
- **纯静态 HTML 幻灯片** — 零外部依赖，无需服务器，打开即用，加载飞快
- **极简科技风设计** — 暗色主题，每个报告采用对应平台品牌色，视觉统一又有辨识度
- **交互式幻灯片** — 支持滚动翻页、键盘导航（方向键/空格/PageUp/PageDown）、侧边页码跳转
- **一站式导航** — 首页整合所有平台报告，点击卡片即可切换，无需跳转多个页面
- **AI 免责声明** — 页面顶部和底部均标注"AI 搜集公开信息生成，仅供参考"

## 在线预览

| 平台 | 地址 |
|------|------|
| GitHub Pages | https://aicoder-cli.github.io/ai-blogger-research/ |
| Netlify | https://resilient-truffle-0bb406.netlify.app |
| Gitee | https://gitee.com/aicoder-cli/ai-blogger-research |

## 报告内容

每份平台报告包含 8 页幻灯片：

| 页码 | 内容 |
|------|------|
| 01 | 封面 — 平台名称、品牌色、报告周期 |
| 02 | 数据概览 — 博主总数、播放/阅读量、主流变现方式、粉丝量级分布 |
| 03-06 | 博主列表 — 每位博主的排名、粉丝量、内容标签、变现方式、代表作 |
| 07 | 趋势分析 — 6 大行业趋势深度解读 |
| 08 | 平台生态总结 — 用户画像、内容调性、商业价值、变现特点 |

## 项目结构

```
ai-blogger-reports/
├── index.html                              # 首页（一站式导航入口）
├── reports/                                # 各平台报告
│   ├── bilibili.html                       # B站 AI 博主报告
│   ├── xiaohongshu.html                    # 小红书 AI 博主报告
│   ├── douyin.html                         # 抖音 AI 博主报告
│   ├── zhihu.html                          # 知乎 AI 博主报告
│   ├── shipinhao.html                      # 视频号 AI 博主报告
│   ├── gongzhonghao.html                   # 公众号 AI 博主报告
│   ├── bilibili-ai-top20-report.html       # B站深度分析报告
│   └── bilibili-ai-top20-deep-analysis.html # B站补充分析
├── templates/                              # 调研模板
│   └── analysis-template.md                # 博主分析模板
└── assets/                                 # 引用资源（图片、字体等）
```

## 本地使用

无需安装任何依赖，直接用浏览器打开即可：

```bash
# 方式一：直接打开
open index.html

# 方式二：本地服务器（推荐，支持 iframe 嵌入）
python3 -m http.server 8080
# 然后访问 http://localhost:8080
```

## 技术特点

- **零 CDN 依赖** — 所有样式和脚本内联，离线可用
- **CSS Scroll Snap** — 原生滚动吸附，流畅的幻灯片翻页体验
- **CSS Zoom 适配** — 自动根据视口宽度缩放，兼容不同屏幕尺寸
- **iframe 沙箱** — 各平台报告独立运行，互不干扰
- **Hash 路由** — 支持 URL 直接定位到特定平台报告（如 `#douyin`）

## 免责声明

本报告由 AI 搜集公开信息自动生成，所有博主排名、粉丝数据、变现方式及影响力评估均基于公开渠道整理，可能存在滞后或偏差，不构成任何投资、合作或背书建议。数据仅供参考，请以各平台实际数据为准。

## License

MIT
