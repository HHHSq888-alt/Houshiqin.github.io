# BUT · 在册人生（站点子目录版）

本目录是《但是 BUT》短片游戏界面，作为子目录部署到你的 GitHub Pages 项目站。
部署后访问：`https://<你的用户名>.github.io/Houshiqin.github.io/BUT/`

## 文件
- `index.html` —— 「我的回放 #2125」单屏（电影成片里出现的那一屏，可点击）
- `but_netizen_page.html` —— 「人生册 / Life Register」其他被记录对象的人册流页（游戏内其他屏，设计交付用）

## 放到仓库的步骤
1. 把本目录里的 `index.html` 与 `but_netizen_page.html` 复制到仓库的 `BUT/` 文件夹
2. 提交并推送：
   ```bash
   git add BUT/
   git commit -m "Add BUT 在册人生 interactive screen"
   git push
   ```
3. 等待约 1 分钟，Pages 自动更新

## 说明
两文件均为纯静态、内联全部 CSS/SVG，**无外部依赖、无构建步骤**。子目录部署下相对链接正常工作，直接丢进 `BUT/` 即可。
如想让两屏互链，可在 `index.html` 顶部加一个指向 `but_netizen_page.html` 的链接。
