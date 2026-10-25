# flutter_car · 法律文档

「洗省省自助洗车」（flutter_car）的用户协议与隐私保护政策，用于应用商店上架填写与线上公示。

---

## 📌 访问节点

本文档提供多节点访问，所有节点内容完全一致（同一份 `main` 分支源码），可按网络环境择优选用。

### 1. 应用商店填写（推荐）

| 节点类型 | 文档 | 访问 URL | 适用场景 |
| :--- | :--- | :--- | :--- |
| **🏠 GitHub Pages（官方站点，推荐）** | 用户服务协议 | `https://yyds-html.github.io/flutter_car/terms.html` | 全球可用，App Store / 应用商店审核首选 |
| **🏠 GitHub Pages（官方站点，推荐）** | 隐私保护政策 | `https://yyds-html.github.io/flutter_car/privacy.html` | 全球可用，App Store / 应用商店审核首选 |

### 2. CDN 加速节点（内容直读）

适用于需要直接拉取 HTML 源码、做版本对比或在其他站点嵌入的场景。

| 节点类型 | 访问 URL（以「用户服务协议」为例） | 适用场景 |
| :--- | :--- | :--- |
| **🚀 jsDelivr CDN（国内加速，推荐）** | `https://cdn.jsdelivr.net/gh/yyds-html/flutter_car@main/terms.html` | 国内网络免代理，边缘缓存命中快 |
| **⚡ Fastly CDN（备用镜像）** | `https://fastly.jsdelivr.net/gh/yyds-html/flutter_car@main/terms.html` | jsDelivr 主线路异常时的备用镜像 |
| **🌐 GitHub Raw（官方直链）** | `https://raw.githubusercontent.com/yyds-html/flutter_car/main/terms.html` | 全球海外直连，实时同步最新提交 |
| **📦 本地文件（离线）** | 直接下载仓库内 `terms.html` / `privacy.html` | 无网环境或需随包分发的离线归档 |

> 隐私保护政策同理，将上述链接中的 `terms.html` 替换为 `privacy.html` 即可。
>
> ⚠️ CDN 与 Raw 节点返回的是**源码**（渲染依赖浏览器），请勿直接作为应用内文本解析源；如需结构化数据，请以仓库中的 HTML 为准后再自行转换。

---

## 📄 文件说明

| 文件 | 说明 |
| :--- | :--- |
| `index.html` | 文档入口页 |
| `terms.html` | 用户服务协议正文 |
| `privacy.html` | 隐私保护政策正文 |
| `user_agreement.html` / `user-agreement.html` | 跳转至 `terms.html` 的兼容别名 |
| `privacy_policy.html` / `privacy-policy.html` | 跳转至 `privacy.html` 的兼容别名 |

> 别名页用于适配不同应用商店对文件名（下划线 / 连字符）的填写要求。

---

## 🗂 节点类型速查

| 节点类型 | 标识 | 特点 | 典型用途 |
| :--- | :--- | :--- | :--- |
| GitHub Pages | `pages` | 渲染后可读，稳定长期 | 商店审核链接、对外公示 |
| jsDelivr CDN | `jsdelivr` | 国内加速，多边缘节点 | 国内用户访问、源码拉取 |
| Fastly CDN | `fastly` | 备用镜像线路 | 主线路故障切换 |
| GitHub Raw | `raw` | 直连仓库，零缓存延迟 | 海外访问、版本比对 |
| 本地文件 | `local` | 完全离线 | 离线归档、随包分发 |

---

## 🛠 维护约定

- 正文修改后同步更新文首的「生效日期」与「版本号」。
- 协议发生实质性变更（处理目的、信息类型、第三方 SDK 变化）时，需同步在 App 内向用户重新提示并征得同意。
- 涉及主体名称、联系方式、第三方 SDK 清单的变更，请与 App 实际配置保持一致。
- 若绑定自定义域名，需在「节点类型」表中补充新节点并注明 `CNAME` 配置。
