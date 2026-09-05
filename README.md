# 🌌 SEO Keyword Galaxy

[![HTML5](https://img.shields.io/badge/Built%20with-HTML5-orange?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![JavaScript](https://img.shields.io/badge/Language-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![No Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen?style=flat-square)]()
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey?style=flat-square)](LICENSE)

交互式 SEO 关键词分析与可视化工具。输入种子关键词或粘贴文章，生成可视化的"关键词星系"，展示词语间的关系。

> **100% 浏览器端运行** — 无服务器、无 API Key、数据不离开你的浏览器。

---

## ✨ 核心特性

### 🔭 关键词星系可视化
交互式 SVG 图表，支持**拖拽、缩放、点击查看**。可视化关键词聚类、关系和缺口——比电子表格直观得多。

### 🔄 多数据源
- **种子关键词扩展**：输入关键词，获取相关词汇
- **文章分析**：粘贴任意文章，提取关键词聚类
- **CSV/TSV 导入**：导入你自己的关键词数据

### ⚔️ 对比模式
两个种子关键词并排对比，找出重叠、独特机会和竞争缺口。

### 📊 真实信号层
导入你自己的搜索量/排名数据，在可视化上叠加真实表现指标。

### 📝 内容管线
从关键词自动生成：
- **P0/P1/P2 主题优先级**
- **内容大纲**（含建议章节）
- **内链建议**（基于关键词关系）

---

## 🚀 快速开始

### 方式一：直接打开
在浏览器中打开 `index.html`，无需构建、无需服务器。

### 方式二：克隆

```bash
git clone https://github.com/wawa-03/seo-keyword-graph.git
cd seo-keyword-graph
start index.html  # Windows
open index.html    # macOS
```

---

## 🎮 使用方法

1. 在搜索栏输入**种子关键词**（如"美妆"）
2. 星系图渲染相关关键词为交互式节点图
3. **点击任意节点**查看详情、相关词和内容建议
4. **拖拽重新排列**可视化
5. **滚轮缩放**
6. 切换到**对比模式**同时分析两个关键词
7. **导出**分析结果为 CSV 或 Markdown

---

## 💡 使用场景

| 场景 | 你能得到什么 |
|---|---|
| 博客内容规划 | 主题聚类 + 内容大纲 |
| SEO 审计 | 关键词缺口分析 |
| 竞品研究 | 对比模式显示重叠 |
| 内容团队简报 | P0/P1/P2 优先级主题列表 |
| 链接建设 | 内链建议 |

---

## 🛠 技术实现

- **纯前端**：HTML5 + CSS3 + JavaScript（零依赖）
- **可视化**：SVG 交互式图形
- **关键词扩展**：客户端算法（可接入真实 API）
- **性能**：虚拟滚动、按需渲染

---

## 📊 数据说明

- 当前关键词指标为**演示估算值**（非真实搜索量）
- 生产使用可接入真实 API（5118、百度指数、Google Keyword Planner）
- 所有数据处理在浏览器端完成，隐私安全

---

## 🤝 Contributing

发现 bug 或有功能建议？请 open issue 或 PR！

## 📄 License

[CC BY-NC-SA 4.0](LICENSE)

---

**Built by [Wawa](https://github.com/wawa-03)** — Full-stack developer specializing in AI automation and data-driven tools.
