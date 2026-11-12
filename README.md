<p align="center">
  <img alt="Stellar-LTS 标志" src="https://api.minio.yyds.pink/halo-docs/2024/11/icon.svg" width="128">
</p>

# Stellar-LTS

<p align="center">基于 Halo Stellar 主题的非官方长期支持版本，内置文档系统，支持标签组件和动态数据组件。</p>

原 Halo 移植项目停止维护后，本仓库由 **bi1kbu** 独立维护，以兼容性维护、问题修复和细节改进为主要方向。**Stellar-LTS 是社区维护的非官方分支，不代表原作者、Hexo Stellar 项目或 Halo 官方，也不表示获得其官方授权或背书。**

### 项目来源与署名

本 README 保留双署名，区分原作者与长期支持版本维护者：

- 原 Halo 移植作者：[困困鱼（chengzhongxue）](https://github.com/chengzhongxue)，原项目为 [Halo Stellar](https://github.com/chengzhongxue/halo-theme-stellar)。
- LTS 维护者：[bi1kbu](https://github.com/bi1kbu)，维护仓库为 [Stellar-LTS](https://github.com/bi1kbu/halo-theme-stellar)。

主题最初移植自 [xaoxuu 的 Hexo Stellar](https://github.com/xaoxuu/hexo-theme-stellar)，保留对原设计与项目来源的致谢。原 Halo 作者署名用于注明来源，不表示其参与本分支维护。

### 名称与兼容性

- `spec.displayName`（显示名称）：`Stellar-LTS`，用于 Halo 后台主题列表及主题元信息。
- `metadata.name`（主题唯一标识）：保持 `theme-stellar`；仓库名、包名、资源路径、设置名称与配置存储名称暂不变更。
- `spec.requires`（Halo 版本要求）：`>=2.22.1`，以 [theme.yaml](theme.yaml) 为准。

本仓库是 Halo 主题，没有独立插件包；所依赖的第三方插件继续使用原名称。由于主题唯一标识保持不变，Stellar-LTS 与原版使用同一主题身份，不作为两个独立主题并行安装。已安装环境更新这些元数据后，可在 Halo 后台执行“重载主题配置”。

### 上游预览与文档

![原版 Stellar 主题预览](https://api.minio.yyds.pink/halo-docs/2024/11/Snipaste_2024-11-07_13-04-15.png)

- [原作者演示站](https://demo.kunkunyu.com)
- [原版 Stellar 使用文档](https://docs.kunkunyu.com/docs/stellar)

以上为上游资源，仅供参考，可能与本分支存在差异；Stellar-LTS 的变更与问题反馈以本仓库为准。

### 插件支持

Stellar-LTS 主题支持以下 Halo 插件：

- [X] 友情链接（/links）：https://halo.run/store/apps/app-hfbQg
- [X] 瞬间（/moments）：https://halo.run/store/apps/app-SnwWD
- [X] 图库（/photos）：https://www.halo.run/store/apps/app-BmQJW

为了获得更好的体验，你还可以安装以下插件（如果需要）：
- highlight.js 代码高亮：https://halo.run/store/apps/app-sqpgf

### 使用说明
> 1、部分功能是使用插件进行支持
- [X] 文章目录
- [X] [代码高亮/语言/复制](https://github.com/halo-sigs/plugin-highlightjs)（插件）
- [x] [文章搜索](https://github.com/halo-sigs/plugin-search-widget)（插件）
- [X] [评论系统](https://github.com/halo-sigs/plugin-comment-widget)（插件）
- [x] [友情链接](https://github.com/halo-sigs/plugin-links)（插件）
- [X] [瞬间](https://halo.run/store/apps/app-SnwWD)（插件）
- [X] [图库](https://www.halo.run/store/apps/app-BmQJW)（插件）
- [x] 其他功能

### 待办事项

- [ ] 细节优化

### 🏭 贡献

如果你想帮助完善 Stellar-LTS 主题，欢迎：

- 为本仓库点亮星标。
- 在 [问题反馈](https://github.com/bi1kbu/halo-theme-stellar/issues) 中报告问题或提出建议。
- 修复问题并提交 [拉取请求](https://github.com/bi1kbu/halo-theme-stellar/pulls)。

### 💬 反馈与上游社区

Stellar-LTS 的问题和建议请提交到本仓库的[问题反馈](https://github.com/bi1kbu/halo-theme-stellar/issues)，由 LTS 维护者处理。

原项目的交流群与赞助信息可查阅[上游项目说明](https://github.com/chengzhongxue/halo-theme-stellar#readme)，这些渠道不作为 Stellar-LTS 的维护或支持入口。

### 许可证

沿用 [MIT License](LICENSE)，保留原作者版权声明，并为本分支的修改补充 LTS 维护者署名。
