# Starsector Mod Releases / Starsector模组发布中心

A public distribution repository for Starsector mods, release notes, installation instructions, and direct downloads.

这是一个公开的 Starsector 模组发布仓库，用于发布版本说明、安装指南和直接下载链接。开发源码与私有工作区保留在私有仓库中，公开仓库仅用于发行包和说明。

## Project Scope / 项目范围

- Public release mirror / 公开发布镜像
- Mod installation guide / 模组安装说明
- Download links and changelogs / 下载链接与更新日志
- Stable public access for end users / 面向最终用户的稳定公开访问

## Release Format / 版本命名规则

- Tag format: `ModID-vX.Y` / 标签格式：`ModID-vX.Y`
- Example: `aigs-v0.3` / 示例：`aigs-v0.3`
- Keep mod versions isolated across different mods / 不同模组版本互不冲突

## Download Center / 下载中心

### AI Girls Officer Pack / AI娘军官包

Current public release / 当前公开版本：[aigs-v0.3.1](https://github.com/101SHArkKnight/starsector-mod-releases/releases/tag/aigs-v0.3.1)

- English edition / 英文版: [aigs-0.3.1-en.zip](https://github.com/101SHArkKnight/starsector-mod-releases/releases/download/aigs-v0.3.1/aigs-0.3.1-en.zip)
- Chinese edition / 中文版: [aigs-0.3.1.zip](https://github.com/101SHArkKnight/starsector-mod-releases/releases/download/aigs-v0.3.1/aigs-0.3.1.zip)

Version 0.3.1 fixes Seedance's projection scan-band crash with Fast Rendering 0.9.4. Retested in-game by the author; skill stats and save identifiers are unchanged.

0.3.1 修复 Seedance 投影扫描光带与 Fast Rendering 0.9.4（快速渲染）的战斗崩溃，作者已实机复测确认，技能数值与存档标识不变。

[Previous release / 旧版 0.3](https://github.com/101SHArkKnight/starsector-mod-releases/releases/tag/aigs-v0.3)

## Installation Guide / 安装说明

1. Download one language edition only / 只下载一种语言版本
2. Extract the ZIP file / 解压 ZIP 文件
3. Copy the `aigs` folder into your Starsector `mods` directory / 把 `aigs` 文件夹放到 `Starsector/mods`
4. Launch the game and enable the mod in the launcher / 启动游戏后在启动器中启用该模组
5. Do not install both language editions at the same time / 不要同时安装两套语言包

Example path / 示例路径：

- Windows: `C:\Program Files\Steam\steamapps\common\Starsector\mods`
- Linux/macOS: `~/Starsector/mods`

## Notes / 说明

- This repository is for public distribution only / 本仓库仅用于公开发行
- Source code and private development history stay in private repositories / 源码和研发历史保留在私有仓库
- Use the mod's own folder name `aigs` to keep compatibility / 使用模组本身的目录名 `aigs` 以保持兼容性

## Recommended Release Workflow / 建议的发布流程

- Keep the private repo as the main development workspace / 保持私有仓库作为主开发工作区
- Create a release in the public repo for each stable version / 每个稳定版本在公开仓库中发布一份
- Publish the original ZIP files with original names and unchanged file contents / 公开上传原始 ZIP 文件，保持文件名和内容不变
- Update this README after every release / 每次发布后更新此 README

## Contact / 联系方式

Repository owner: `101SHArkKnight` / 仓库所有者：`101SHArkKnight`

## Disclaimer / 免责声明

This repository is provided as a public distribution channel only. It does not replace the private development repository.

本仓库仅作为公开分发渠道，不替代私有开发仓库。
