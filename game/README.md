# 🐍 代码之外，来一局？

给 GitHub 主页访客做的贪吃蛇，无需依赖、登录或构建。

## 本地试玩

下载本目录后，用浏览器打开 [index.html](index.html)。

- 方向键或 WASD 转向，也支持手机方向按钮和棋盘滑动。
- 点击“开始游戏”开始；空格或“暂停”按钮暂停与继续。
- 吃一颗亮点得 10 分，撞墙或碰到身体则结束。
- 切换窗口自动暂停；最高分保存在当前浏览器，无法存储时仍可正常游戏。

## 放到 GitHub 主页

GitHub README 不能直接运行 JavaScript 游戏，需要通过网页入口打开。

1. 将本目录连同 README 和 assets 上传到 bbcdabao/bbcdabao 仓库。
2. 在仓库 Settings → Pages 中选择 Deploy from a branch，选择 main 分支和 / (root)，保存。
3. 等待部署成功，在 Pages 设置中确认最终网址，再打开游戏路径 /game/。

使用默认项目站点地址时，入口为 https://bbcdabao.github.io/bbcdabao/game/ 。若已配置自定义域名，请使用实际网址，并同步修改两份 README 中的试玩链接。

**当前文件只准备了入口，不代表 GitHub Pages 已启用。** 确认上线后，可以删除两份 README 链接文案里的“启用后可用”提示。
