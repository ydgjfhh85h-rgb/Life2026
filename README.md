# Life2026 · 人生底色

此仓库用于 Cloudflare Pages 的静态 WebGL 发布，只保存网页运行资源；Unity 源工程、Library、原始素材母版、测试日志和账号秘密不放入此仓库。

当前交付范围是人生模式，版本 `v1.3-life-profile.candidate.55`。保留上手曲线 G1–G6、四种主角阶段形象、音乐和音效。网页标为「开发试玩」，完整手机性能、受控网络冷加载和设备矩阵验收仍待完成。

## Pages 配置

- Git 仓库：`ydgjfhh85h-rgb/Life2026`
- 生产分支：`main`
- 框架：`None`
- 构建命令：`exit 0`
- 根目录：仓库根目录
- 输出目录：`webgl`

`webgl/_headers` 为实际 Brotli 文件声明压缩头及 WASM/JavaScript MIME。`404.html` 保证缺失资源返回 404，`VERSION.json` 记录构建和配置。发布资源准备完成后提交至 `webgl/`。
