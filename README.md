# Total OPC Website — GitHub Pages 部署包（Swap 版）

## 📦 文件结构

```
github-deploy-v2-swap/
├── index.html         语言选择入口页（原 login.html，根域名直接进入）
├── cn.html            CN 简体中文（首页内容）
├── uk.html            UK English
├── my.html            MY Bahasa Melayu
├── hk.html            HK 繁體中文
├── th.html            TH ภาษาไทย
├── id.html            ID Bahasa Indonesia
├── jp.html            JP 日本語
├── kr.html            KR 한국어
├── images/            全部图片（74 张本地化）
└── README.md
```

## 🌐 访问路径

| 路径 | 内容 |
|---|---|
| `/` 或 `/index.html` | **语言选择入口页**（8 个语言大图卡片） |
| `/cn.html` | CN 简体中文 |
| `/uk.html` | UK English |
| `/my.html` | MY Bahasa Melayu |
| `/hk.html` | HK 繁體中文 |
| `/th.html` | TH ภาษาไทย |
| `/id.html` | ID Bahasa Indonesia |
| `/jp.html` | JP 日本語 |
| `/kr.html` | KR 한국어 |

## 🆚 与 V2 区别

- **V2**（`github-deploy-v2.zip`）：根域名 → CN 中文首页
- **V2-swap**（`github-deploy-v2-swap.zip`）：根域名 → **语言选择大图页**

## 🔧 关键修复

swap 之后修复了 9 处 `./index.html` 链接 → `./cn.html`：

| 页面 | 修复点 |
|---|---|
| `index.html`（原 login） | CN 大图卡片 |
| `cn.html` | lang-menu 的 CN 项 |
| `uk.html` | lang-menu 的 CN 项 |
| `my.html` | lang-menu 的 CN 项 |
| `hk.html` | lang-menu 的 CN 项 |
| `th.html` | lang-menu 的 CN 项 |
| `id.html` | lang-menu 的 CN 项 |
| `jp.html` | lang-menu 的 CN 项 |
| `kr.html` | lang-menu 的 CN 项 |

## 🚀 部署

把整个 `github-deploy-v2-swap/` 内容推到 GitHub repo 根目录即可。
