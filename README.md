# Pocket Arcade · 口袋街机

一个独立的、可用手机和电脑玩的静态网页小游戏网站。

包含四款游戏：

- `snake.html` — 贪吃蛇（键盘、触摸滑动、屏幕方向键）
- `maze.html` — 迷宫吃豆（原创迷宫和角色，受经典吃豆玩法启发）
- `blocks.html` — 方块下落（七种方块、下落消行）
- `match.html` — 缤纷三消（8×8 交换消除）

`index.html` 是首页；`styles.css` 是共享样式。无第三方依赖、无数据库。最高分使用 localStorage 保存。

## 本地打开

解压 ZIP 后双击 `index.html`。或者在文件夹运行：

```bash
python -m http.server 8000
```

然后打开 http://localhost:8000/。

## GitHub Pages 上线

1. 在 GitHub 创建一个新的 Public 仓库，建议叫 `pocket-arcade`（不要改动已有的 `reaction-test`）。
2. 上传本站文件到仓库根目录。
3. 打开 Settings → Pages，Source 设置为 Deploy from a branch，Branch 为 `main`，Folder 为 `/(root)`。
4. 保存，等待部署完成。

预计访问地址形如 `https://<你的用户名>.github.io/pocket-arcade/`。

## 说明

作品使用独立的原创游戏界面与程序代码，未使用其他商业游戏的素材。网站没有用户账号，浏览器本地的成绩记录换设备或清除缓存后会消失。暂不提供联网排行榜。