# Ziqing Zhu

英文个人页。静态 HTML，无构建。

## 本地看（不需要开服务）

访达里双击 `打开主页.command`，或终端：

```bash
open index.html
```

不要用 `python3 -m http.server`。那个进程一关，网页就打不开。

## 上传 GitHub

```bash
git add -A
git commit -m "Update site"
git push
```

公开地址（推送后约一分钟）：https://aqkeepstudying.github.io/ziqing-zhu/

可选：和本州手册一样部署到 Cloudflare，`npx wrangler deploy`
