# Linked Reminders — 放到 iPhone 主屏幕

## 文件
- `index.html` — app 本体
- `manifest.webmanifest`、`sw.js` — 让它能全屏打开、离线可用
- `apple-touch-icon.png`、`icon-192.png`、`icon-512.png` — 图标

## 用 GitHub Pages 免费托管（约 5 分钟）
1. 登录 github.com（没有账号先注册）。
2. 右上角 **+ → New repository**，名字填 `reminders`，选 **Public**，点 **Create repository**。
3. 在新仓库页面点 **uploading an existing file**，把解压后的这些文件全部拖进去（拖文件，不是拖文件夹），点 **Commit changes**。
4. 进入仓库的 **Settings → Pages**，Source 选 **Deploy from a branch**，Branch 选 **main**、目录 **/(root)**，点 **Save**。
5. 等 1–2 分钟，刷新该页面，顶部会出现网址：`https://你的用户名.github.io/reminders/`

## 装到 iPhone
1. 用 **Safari** 打开上面的网址。
2. 点底部 **分享** → **添加到主屏幕** → **添加**。
3. 之后从主屏幕的橙色图标打开，全屏运行，断网也能用。

## 须知
- 待办数据只保存在这台 iPhone 里，不会上传到 GitHub（仓库公开的只是代码）。
- 删除主屏幕图标会同时删除数据；换手机前请先用右上角分享按钮 **Export to Excel** 备份，到新手机上 **Import from Excel** 恢复。
- 导出时会弹出系统分享面板，选「存储到文件」即可保存 .xlsx。
- 以后更新：在仓库里重新上传新的 `index.html` 覆盖即可，手机上重新打开 app 会自动拿到新版本。
