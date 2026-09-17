<div align="center">

# 📷 DxO 离线镜像

**DxO 全家桶 macOS 官方安装包 —— 每日自动跟随官方,直发 GitHub Release**

[![自动同步](https://github.com/LOVECHEN/dxo-release/actions/workflows/daily-download.yml/badge.svg)](https://github.com/LOVECHEN/dxo-release/actions/workflows/daily-download.yml)
[![最近更新](https://img.shields.io/github/release-date/LOVECHEN/dxo-release?label=最近更新&color=4c8bf5)](https://github.com/LOVECHEN/dxo-release/releases)

[**⬇️ 全部版本**](https://github.com/LOVECHEN/dxo-release/releases)

</div>

---

## ⬇️ 下载

进入对应产品的最新 Release，下载官方**原始安装包**（macOS `.dmg`）：

| 产品 | 打开 |
|------|------|
| 🖼️ **DxO PhotoLab 9** | [![](https://img.shields.io/github/v/release/LOVECHEN/dxo-release?filter=photolab9-*&label=PhotoLab%209&color=2f7d32)](https://github.com/LOVECHEN/dxo-release/releases?q=photolab9) |
| 🎞️ **DxO FilmPack 8** | [![](https://img.shields.io/github/v/release/LOVECHEN/dxo-release?filter=filmpack8-*&label=FilmPack%208&color=b58900)](https://github.com/LOVECHEN/dxo-release/releases?q=filmpack8) |
| 📐 **DxO ViewPoint 5** | [![](https://img.shields.io/github/v/release/LOVECHEN/dxo-release?filter=viewpoint5-*&label=ViewPoint%205&color=4c8bf5)](https://github.com/LOVECHEN/dxo-release/releases?q=viewpoint5) |
| 🌅 **DxO PureRAW 6** | [![](https://img.shields.io/github/v/release/LOVECHEN/dxo-release?filter=pureraw6-*&label=PureRAW%206&color=e07b39)](https://github.com/LOVECHEN/dxo-release/releases?q=pureraw6) |
| 🎨 **Nik Collection 9** | [![](https://img.shields.io/github/v/release/LOVECHEN/dxo-release?filter=nikcollection9-*&label=Nik%20Collection%209&color=8e44ad)](https://github.com/LOVECHEN/dxo-release/releases?q=nikcollection9) |

> - 资产文件名带**真实点版本号**（如 `DxO_PhotoLab_9.8.0.dmg`、`Nik_Collection_9.0.0.dmg`），macOS 均为 Universal（Apple Silicon + Intel）。
> - Release 以点版本号标记（tag 形如 `photolab9-9.8.0`）——官方一更新，这里就跟一版。
> - 每个 Release 附 `checksums.sha256`，下载后可校验完整性。
> - 个别安装包 > 2GiB（GitHub 单文件上限），会**分卷**为 `xxx.dmg.part.*`；下载全部分卷后按 Release 说明 `cat` 合并即可。

---

## 🔄 工作方式

一个每日 GitHub Action 探测官方安装包是否更新（`Last-Modified`），有更新就拉取官方原包、生成 SHA-256、发一个新 Release。全过程只镜像官方公开分发的文件，不做任何改动。

## ⚖️ 声明

本仓库仅**镜像 DxO 官方公开分发的安装包**，不含任何破解 / 授权绕过 / 修改。版权归 DxO Labs 所有，请遵守 [DxO 官方条款](https://www.dxo.com)。安装包为试用版，正式使用请购买官方授权。

## 📄 License

MIT（仅指本仓库的下载器 workflow；DxO 软件本身版权归 DxO Labs）。
