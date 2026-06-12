# 目标树 (GoalTree)

Obsidian 目标细化与进度追踪插件。

## 功能

- 层级目标管理（目标 → 阶段 → 分组 → 任务 → 子任务）
- 可视化进度追踪（彩虹色进度条、圆环统计）
- 拖拽排序与吸附
- 任务状态流转（等待中 → 进行中 → 已完成 / 取消）
- 日期标记
- 关联 Obsidian 笔记（点击跳转，同步更新）
- 序号格式：目标（中文数字）、阶段（阿拉伯数字）、分组（字母）、任务（罗马数字）

## 安装

### 手动安装

1. 下载本仓库
2. 将整个文件夹放入 Obsidian 插件目录：`{vault}/.obsidian/plugins/goaltree-tasks/`
3. 重启 Obsidian，在设置 → 社区插件中启用「目标树」

### 通过 BRAT 安装

1. 安装 [BRAT](https://github.com/TfTHacker/obsidian42-brat) 插件
2. 在 BRAT 设置中添加本仓库的 GitHub URL

## 使用

- 点击左侧 Ribbon 图标（树形图标）或使用命令面板打开「目标树」
- 在目标树面板中点击「添加」按钮创建新目标
- 右键任务打开操作菜单（添加子任务、重命名、设置日期等）
- 勾选任务切换完成状态

## 开发

本插件为 Obsidian 社区插件，基于 [Obsidian Plugin API](https://github.com/obsidianmd/obsidian-api) 开发。

```
.
├── main.js        # 插件主文件
├── styles.css     # 样式
├── manifest.json  # 插件清单
└── data.json      # 数据存储
```

## License

MIT
