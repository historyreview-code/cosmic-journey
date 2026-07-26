# 宇宙系列 · Cosmos Series

五个 3D 沉浸式滚动叙事网页（Three.js + Web Speech 中文配音 + 程序化配乐），合计 ~120 个章节，从太阳系黄道面延伸到星辰大海的远方。

| 页面 | 内容 | 链接 |
| --- | --- | --- |
| `index.html` | 黄道面之谜：太阳系黄道面的形成 | `/` |
| `galaxy.html` | 3D 银河漫游：从太阳系到银河系 | `/galaxy.html` |
| `cosmos.html` | 宇宙简史：从大爆炸到黑洞 | `/cosmos.html` |
| `history.html` | 仰望星空五千年：人类探索宇宙的历史 | `/history.html` |
| `missions.html` | 揽月探火：登月与登陆火星全解（带配乐） | `/missions.html` |

## 本地运行

需要 Node.js ≥ 18：

```bash
npm start
# → http://localhost:3000
```

## 部署到任意静态托管

`index.html galaxy.html cosmos.html history.html missions.html server.js package.json` 即全部。
任何静态托管（Gitee Pages / Vercel / Netlify / Cloudflare Pages / 阿里云 OSS / 腾讯云 COS / Nginx）均可：
**Gitee Pages / Vercel / Netlify / Cloudflare Pages**：把仓库连进去，无需 server.js（静态托管直接服务 HTML）。
**OSS / COS / 自建 Nginx**：把 `*.html` 上传到 web root 即可，无需 Node。
