# Codex 桌宠合集

这个仓库保存了已经生成好的 Codex 桌宠文件，方便在其他电脑上直接下载使用，不需要重新生成。

## 包含的桌宠

- `pets/yinyue`：银月灵狐宠物版
- `pets/Q版银月`：参考原图制作的人形 Q 版银月

每个桌宠目录都包含两个必要文件：

- `pet.json`：桌宠配置
- `spritesheet.webp`：桌宠动画图集

## 使用方法

下载或克隆本仓库后，把需要的桌宠目录复制到本机 Codex 的桌宠目录：

```powershell
Copy-Item -Recurse -Force ".\pets\yinyue" "$env:USERPROFILE\.codex\pets\yinyue"
Copy-Item -Recurse -Force ".\pets\Q版银月" "$env:USERPROFILE\.codex\pets\Q版银月"
```

复制完成后，重启 Codex，或重新加载桌宠列表。

## 目录结构

```text
codex-pets/
  pets/
    yinyue/
      pet.json
      spritesheet.webp
    Q版银月/
      pet.json
      spritesheet.webp
```

## 说明

这些文件是已经生成完成的桌宠资源。仓库的目的只是保存和分发成品，避免在新电脑上重复生成。
