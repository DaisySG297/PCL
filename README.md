# Plain Craft Launcher

> ## 本仓库是第三方二次创作（非官方）
>
> 本仓库 fork 自 [Meloong-Git/PCL](https://github.com/Meloong-Git/PCL)，由 **DaisySG297** 独立修改，**与 PCL 官方无关**，请勿将其视为官方版本。
>
> 修改内容：恢复被上游关闭的「Minecraft 下载」功能（原版 2.99.0.0 起以 `RestrictMcDownload = True` 关闭了该功能）。
> 具体改动：`Modules/ModSecret.vb` 中关闭该限制开关，并移除 `ModModpack.vb`、`PageDownloadInstall.xaml.vb` 中对应的拦截逻辑。
>
> 构建时如需微软登录 / CurseForge API，请自行在 Azure 门户申请 `ClientId` 与 API Key，通过环境变量 `PCL_MS_CLIENT_ID` / `PCL_CURSEFORGE_API_KEY` 传入，**不要提交到仓库**。
>
> 原项目作者：**龙腾猫跃**（[爱发电赞助](https://meloong.com/afd/a/LTCat)）。本仓库继续遵循原仓库的 [LICENCE](LICENCE)（《PCL 分发有限许可》与《PCL 存储库合理使用指南》）。
>
> 若需官方版本，请前往 [meloong.com/pcl](https://meloong.com/pcl)。

包含 PCL 的大部分源代码，包括 UI 库、动画模块、下载模块、Minecraft 启动模块等！<br/>
代码并不是实时更新的，它会在每次 PCL 发布更新时同步一次。<br/>
非常感谢社区的大力支持！

<br/>

### 相关资源
- [PCL 下载](https://meloong.com/pcl)：下载可免费使用的正式版 PCL！
- [PCL 功能投票](https://github.com/Meloong-Git/PCL/discussions/2)：来参加投票吧，开发者会优先处理票数较高的项目！
- [帮助文档库](https://github.com/LTCatt/PCL2Help)：PCL 内置帮助文档的存储库