# 八六 Codex 宠物

[English](README.md) | [日本語](README.ja.md)

一个基于《爱上火车》八六的非官方同人 Codex 宠物。

## 预览

这个宠物包含 Codex 兼容的动画精灵图，覆盖以下状态：

- idle
- running-right
- running-left
- waving
- jumping
- failed
- waiting
- running
- review

## 安装

克隆或下载这个仓库，然后把 `hachiroku` 文件夹放到你的 Codex 宠物目录：

```bash
mkdir -p ~/.codex/pets
cp -R hachiroku ~/.codex/pets/
```

最终目录结构应为：

```text
~/.codex/pets/hachiroku/
  pet.json
  spritesheet.webp
```

重启或刷新 Codex，然后在宠物选择器里选择 `八六`。

## 文件

- `hachiroku/pet.json`：Codex 宠物清单文件。
- `hachiroku/spritesheet.webp`：8 x 9 的 Codex 宠物动画图集。

## 声明

这是一个非官方同人 Codex 宠物。Hachiroku / 八六、Maitetsu / 爱上火车以及相关原作内容归各自权利方所有。

本仓库与原作者或权利方没有关联，也未获得其背书。

仓库内的宠物精灵图仅供个人、非商业使用。
