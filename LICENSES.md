# SVPlayer 开源许可声明 / Open Source Licenses

SVPlayer（iPhone、iPad、Mac、Apple TV）整体或部分使用了下列开源组件。感谢各项目作者与贡献者。
SVPlayer (iPhone, iPad, Mac and Apple TV) uses the following open-source components, in whole or in part. Thanks to their authors and contributors.

| 组件 Component | 许可证 License | 源码 Source | 说明 Notes |
|---|---|---|---|
| AetherEngine | LGPL-3.0，附 App Store / TestFlight 分发例外<br>LGPL-3.0 with the App Store / TestFlight exception | 上游 Upstream: [superuser404notfound/AetherEngine](https://github.com/superuser404notfound/AetherEngine)<br>**SVPlayer 修改版 Modified source: [ggttol/AetherEngine-svplayer](https://github.com/ggttol/AetherEngine-svplayer)** | Copyright (C) 2026 Vincent Herbst。SVPlayer 对其做了修改，修改内容与日期见修改版仓库的 [SVPLAYER-MODIFICATIONS.md](https://github.com/ggttol/AetherEngine-svplayer/blob/main/SVPLAYER-MODIFICATIONS.md)。<br>Modified by SVPlayer; see SVPLAYER-MODIFICATIONS.md in the modified repository for what changed and when. |
| FFmpeg（FFmpegBuild 3.16.0，FFmpeg n8.1.3） | LGPL-2.1-or-later | [FFmpeg/FFmpeg](https://github.com/FFmpeg/FFmpeg) · [superuser404notfound/FFmpegBuild](https://github.com/superuser404notfound/FFmpegBuild) | 以动态库方式使用，未启用 GPL 组件。<br>Linked as dynamic frameworks; no GPL components enabled. |
| dav1d | BSD-2-Clause | [videolan/dav1d](https://code.videolan.org/videolan/dav1d) | 随 FFmpegBuild 提供。Bundled with FFmpegBuild. |
| zimg | WTFPL | [sekrit-twc/zimg](https://github.com/sekrit-twc/zimg) | 随 FFmpegBuild 提供。Bundled with FFmpegBuild. |
| zvbi | LGPL-2.1-or-later | [zapping-vbi/zvbi](https://github.com/zapping-vbi/zvbi) | 随 FFmpegBuild 提供。Bundled with FFmpegBuild. |
| LibDovi | MIT | [superuser404notfound/LibDovi](https://github.com/superuser404notfound/LibDovi) | 杜比视界元数据解析。Dolby Vision metadata parsing. |
| SMBClient | MIT | [kishikawakatsumi/SMBClient](https://github.com/kishikawakatsumi/SMBClient) | SMB 浏览、播放与下载（Build 34 起替代 libsmb2）。SMB browsing, playback and downloads (replaces libsmb2 from Build 34). |

## 关于 LGPL / About the LGPL

- 上述 LGPL 组件的许可证全文随 App 一起提供（App 内「设置 → 关于 → 开源致谢」），也可在各项目仓库中查看。
- SVPlayer 修改过的 AetherEngine 源码完整公开在 [ggttol/AetherEngine-svplayer](https://github.com/ggttol/AetherEngine-svplayer)，保留了上游完整提交历史，`git diff 572a8f7` 即可查看全部修改。
- 未修改的 LGPL 组件，可从上表的上游地址获取对应版本源码。
- 如需获取与某个已发布版本对应的源码，或对本声明有疑问，请在本仓库提交 Issue。

- The full license texts of the LGPL components ship with the app (Settings → About → Open Source) and are available in each project's repository.
- The complete source of SVPlayer's modified AetherEngine is public at ggttol/AetherEngine-svplayer, with the full upstream history; `git diff 572a8f7` shows every change.
- Unmodified LGPL components can be obtained from the upstream links above.
- To request the source matching a specific release, or for questions about this notice, open an issue in this repository.

专利相关功能（TrueHD / DTS:X 对象音频、杜比视界双层与 FEL 曲线、静帧重整形）在 SVPlayer 中保持关闭。
Patent-sensitive features (TrueHD / DTS:X object audio, dual-layer Dolby Vision, FEL curves and still reshaping) are disabled in SVPlayer.

_最后更新 Last updated: 2026-11-21（Build 34）_
