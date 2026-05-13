# 🐍 贪吃蛇进化版 - Web 版

这是 Pygame 贪吃蛇游戏通过 Pygbag 编译的 WebAssembly 版本。

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库（例如 `snake-game`）
2. 将本目录所有文件上传到仓库
3. 仓库 Settings → Pages → 选择 main 分支
4. 等待几分钟，你的网址就是 `https://你的用户名.github.io/snake-game/`

## 生成 Android APK

1. 打开 https://pwabuilder.com
2. 输入你的 GitHub Pages 网址
3. 点击 "Package for Android"
4. 下载 APK 安装到手机

## 本地运行

```bash
python -m http.server 8000
# 浏览器访问 http://localhost:8000
```
