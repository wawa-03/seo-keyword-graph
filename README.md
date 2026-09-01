# SEO Keyword Graph

An interactive, browser-based keyword analysis and visualization tool. Input a seed keyword or paste an article, and it generates a visual "keyword galaxy" showing relationships between terms.

## Features

- **Keyword Galaxy Visualization**: Interactive SVG graph with drag, zoom, and click-to-inspect
- **Multiple Data Sources**: Seed keyword expansion, article text analysis, CSV/TSV import
- **Comparison Mode**: Compare two seed keywords side-by-side
- **Real Signal Layer**: Import your own search data to overlay real metrics
- **Content Pipeline**: Auto-generate topic lists (P0/P1/P2), content outlines, internal link suggestions, and TDK (Title/Description/Keywords)
- **Export**: JSON, CSV, Markdown export

## How to Use

1. Open `index.html` in any modern browser
2. Enter a seed keyword (e.g., "美妆")
3. Click "生成关键词地图" (Generate Keyword Map)
4. Click nodes to see metrics and content suggestions

## Tech Stack

- Pure HTML/CSS/JavaScript (no dependencies)
- SVG-based interactive graph
- Client-side keyword expansion and analysis

## Demo

Just open the HTML file in your browser — no server needed.

## Notes

- Keyword metrics are demo estimates (not real search volume)
- For production use, integrate with real APIs (5118, Baidu Index, Google Keyword Planner)

## License

MIT
