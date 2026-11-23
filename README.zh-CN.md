# Jellyfin for YesPlayMusic

[English](README.md) · 简体中文

[YesPlayMusic](https://github.com/qier222/YesPlayMusic) 3.0 官方 Jellyfin 音乐源插件。

## 安装

- **方式一（推荐）**：打开 YesPlayMusic → **设置 → 插件 → 官方插件**，找到 **Jellyfin** 点击安装。
- **方式二**：打开 **设置 → 插件 → 安装插件**，粘贴 `github.com/qier222/ypm-plugin-jellyfin`。

## 配置

1. 在 **设置 → 插件 → Jellyfin → ⋯ → 插件设置…** 中填写：
   - **服务器地址**：例如 `http://127.0.0.1:8096`
   - **用户名** 和 **密码**（或填写 **API 密钥** 跳过账密登录）
   - **音乐库 ID（可选）**：只浏览某一个音乐库时填写，留空显示全部
2. 在「音乐来源」里切换到 **Jellyfin** 即可使用。

## 功能

- 首页：最近添加、最近播放、最常播放、歌单、随机专辑与推荐
- 完整曲库浏览（歌曲、专辑、艺人、歌单）与搜索
- 专辑、艺人、歌单详情页，支持创建、重命名、删除歌单以及增删、排序歌曲
- 喜欢歌曲、收藏专辑、关注艺人（同步 Jellyfin 收藏夹）与最近播放
- 原码直出（高音质 / 无损）或 192 kbps MP3 转码（标准音质），自动上报播放记录
- 原生同步歌词（Jellyfin 10.9+ `/Audio/{id}/Lyrics`）与相似歌曲
- 多语言界面支持

## 协议

[MIT](LICENSE)
