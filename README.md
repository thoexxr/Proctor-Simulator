# App Store 上架页面（技术支持 / 隐私政策）

本目录是可直接用于 **GitHub Pages** 的静态网页，包含五语（简体中文、繁體中文、English、日本語、한국어）内容。

## 文件说明

| 文件 | 用途 | App Store Connect 填写位置 |
|---|---|---|
| `index.html` | 首页（导航） | 无需填写 |
| `support.html` | 技术支持页（操作方式/系统要求/FAQ/联系方式） | **技术支持网址 (Support URL)** |
| `privacy.html` | 隐私政策页（数据实践/本地存储/Game Center） | **隐私政策网址 (Privacy Policy URL)** |
| `styles.css` | 样式（请勿删除） | — |

## 上传到 GitHub 并开启 Pages

1. 在 GitHub 新建一个公开仓库，例如 `proctor-pages`。
2. 把本目录里的**全部文件**上传到仓库根目录（保持文件名不变）。
3. 打开仓库 **Settings → Pages**：
   - Source 选择 **Deploy from a branch**；
   - Branch 选择 **main**、目录选 **/ (root)**，保存。
4. 等待约 1 分钟，Pages 会给出网址，形如：
   `https://<你的用户名>.github.io/proctor-pages/`

## 填入 App Store Connect

- 技术支持网址：`https://<你的用户名>.github.io/proctor-pages/support.html`
- 隐私政策网址：`https://<你的用户名>.github.io/proctor-pages/privacy.html`

> 提示：浏览器先打开上述链接确认能正常显示后再填写。页面顶部可点击切换五种语言，均为同一网址，无需为每种语言单独建链接。

## 内容依据（与实际 App 一致）

- 无账号注册、无 HTTP 网络请求、无内购、无广告、无第三方追踪/分析；
- 仅本地保存：设置（语言/亮度/音量/静音）、成就与最佳成绩（`user://` 目录）；
- 排行榜与成就通过 Apple Game Center 处理，受 Apple 隐私政策约束；
- 联系邮箱：1132387609@qq.com。
