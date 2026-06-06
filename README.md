# SQLad

本地 AI 数据便签。跟 AI 说话，数据自己出现。

## 下载

| 平台 | 下载 |
|---|---|
| 🪟 Windows | [sqlad.exe](https://github.com/cuiJY-still-in-school/SQLad/releases/latest/download/sqlad.exe) |
| 🍎 macOS | [sqlad.dmg](https://github.com/cuiJY-still-in-school/SQLad/releases/latest/download/sqlad.dmg) |
| 🐧 Linux | [sqlad.deb](https://github.com/cuiJY-still-in-school/SQLad/releases/latest/download/sqlad.deb) |

> 发布页找最新版：https://github.com/cuiJY-still-in-school/SQLad/releases

## 怎么用

- **左边**：跟 AI 说话。建表、查数据、画图、连外部服务——都是它的事。
- **右边**：数据表格。点单元格直接改，列头右键排序/隐藏。
- **⚙️ 右上角**：配 AI、看已连的服务。
- **拖文件**：CSV / JSON 丢窗口自动建表。

## 开发

```bash
bun install
bun run tauri dev
```

打包：

```bash
bun run build
cd src-tauri && cargo build --release
```

## 技术栈

Tauri 2 · Rust · React 19 · MUI 6 · Glide Data Grid · SQLite · Axum

## 数据在哪

`~/.local/share/SQLad/`（Linux）/ `%APPDATA%/SQLad/`（Windows）/ `~/Library/Application Support/SQLad/`（macOS）
