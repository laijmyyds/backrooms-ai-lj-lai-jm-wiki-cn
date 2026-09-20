# The Backrooms · AI-LJ-LAI-JM 中文维基

本仓库用于存放The Backrooms · AI-LJ-LAI-JM 中文维基的样式表、组件样式及相关工具文件。

站点地址：[https://backrooms-ai-lj-lai-jm.wikidot.com](https://backrooms-ai-lj-lai-jm.wikidot.com)

---

## 文件说明

| 文件 | 说明 |
|------|------|
| `Literary Archive.css` | 站点主样式表。负责全局布局、配色、顶栏、侧边栏、按钮、评分组件等基础样式。基于Liminal Theme修改。 |
| `component-styles.css` | 组件样式表。负责 SD 难度指示器、IETS、CECS、PLAS、评分组件等自定义组件的配色与布局。 |
| `yslb.html` | 站长写的唐碧小游戏。 |
| `《小猪佩奇》中人物关系与潜在故事线中隐藏的社会问题即启示.md` | 正经的论文。 |
| `数字时代下传统阅读与数字阅读的认知差异及其教育启示.md` | 论文。 |

---

## 使用方式

两个 CSS 文件通过 jsDelivr 引入 Wikidot 站点：

```css
@import url("https://cdn.jsdelivr.net/gh/laijmyyds/backrooms-ai-lj-lai-jm-wiki-cn@main/Literary Archive.css");
@import url("https://cdn.jsdelivr.net/gh/laijmyyds/backrooms-ai-lj-lai-jm-wiki-cn@main/component-styles.css?v=20260916");
