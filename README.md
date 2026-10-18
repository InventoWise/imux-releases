# iMux 发布

这里只放 iMux 的发布产物，源码不在这里。

- 需要 macOS 14+ 和 tmux 3.3+（iMux 不自带 tmux，用你 Mac 上的那一份；没装就 `brew install tmux`）。
- 下载页：https://imux-release.inventowise.com/（按钮总是指向最新版 DMG）。也可以在 [Releases](https://github.com/InventoWise/imux-releases/releases)，下载最新的 `iMux-<版本>.dmg`，打开后把 iMux 拖进「应用程序」（`.zip` 给应用内更新用）。
- `index.html`、`icon-256.png`、`favicon.png` 是下载页，可以随时改；应用内更新读 `appcast.xml`（经 GitHub Pages 发布在 https://imux-release.inventowise.com/appcast.xml）。这个文件由发版脚本生成并签名，不要手改。
