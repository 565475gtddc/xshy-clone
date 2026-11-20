# 像素火影·次世代 工程重建

Unity 2022.3.33f1 / Android arm64 / IL2CPP。

## 现状
- 原包资源已用 AssetRipper 2.0 全量导出（场景、预制体、图鉴/选人/战斗 UI、角色帧、动画）。
- 原包为 IL2CPP，导出脚本是空壳（只有字段，没有方法体），游戏逻辑需要按原版重写为 C#。

## 目录（待推送）
- `unity/`  Unity 工程（Assets + ProjectSettings）
- `.github/workflows/` 构建流水线（激活授权 + 出 APK）
