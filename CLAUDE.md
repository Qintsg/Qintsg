# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 仓库定位

- 这是 GitHub 用户 `Qintsg` 的同名特殊仓库；根目录 `README.md` 会渲染为 GitHub 个人主页内容。
- 当前仓库不是应用、库或服务项目；截至初始化时，仓库只包含个人主页 `README.md`，没有构建脚本、测试框架或运行时入口。
- 用户已说明 GitHub 名称为 `Qintsg`，涉及个人主页称谓、链接或徽章时应保持该拼写。

## 常用命令

当前仓库没有可执行项目命令，因此不要虚构 `build`、`lint` 或 `test` 命令。

- 查看仓库状态：`git status`
- 查看 README 渲染相关改动：`git diff -- README.md`
- 提交改动：`git add README.md CLAUDE.md && git commit -m "Update profile repository guidance"`

## 内容结构

- `README.md`：GitHub Profile README 的唯一展示入口，适合放置个人介绍、技能栈、项目入口、统计卡片、联系方式等内容。
- `CLAUDE.md`：给 Claude Code 的仓库操作说明，不参与 GitHub 个人主页展示。

## 修改注意事项

- 修改 `README.md` 时优先考虑 GitHub 个人主页的首屏可读性；避免把长篇说明、临时 TODO 或内部操作记录放进主页。
- 如果后续加入自动生成的徽章、统计卡片或外部图片链接，应确认这些资源在公开 GitHub 页面中可访问。
- 如果后续引入脚本、站点生成器或 CI，再补充对应的安装、构建、测试和单测命令。
