# 视频动效：Remotion 官方 Skills

- 官方技能集合：https://github.com/remotion-dev/skills
- 对应源码：https://github.com/remotion-dev/remotion/tree/main/packages/skills
- 参考版本：039e8a2fc78b67efc228d5645367838b85818a1c
- 官方说明：https://www.remotion.dev/docs/ai/skills
- 框架授权：https://github.com/remotion-dev/remotion/blob/main/LICENSE.md
- 收录方式：官方安装入口和本说明，不复制镜像源码。独立技能镜像未附带单独 LICENSE，运行框架遵循官方适用许可。

## 效果

编排文字、图片、视频、音乐与时间轴，输出动态标题、片尾、卡点、字幕或视频背景。海浪和帆船等素材需另行准备或生成，技能本身不包含所有素材。

## 官方安装入口

在已安装 Node.js 的环境中，可以按官方说明运行：

```powershell
npx skills add remotion-dev/skills
```

此命令会安装官方技能，但不等于完整视频项目与所有依赖已经准备好。本次未运行此命令。

## 常用技能

- remotion-best-practices：通用入口。
- remotion-create：新建项目或片段。
- remotion-markup：布局、文字、媒体与动画编排。
- remotion-studio：启动预览。
- remotion-render：渲染视频或静态帧。
- remotion-captions：字幕。
- remotion-docs：查询官方文档。

输出通常为视频；将视频用于 PPT 时，文字通常不能在 PowerPoint 中逐项修改。
