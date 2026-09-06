# Linux 命令行学习之旅
> 2026 年暑期，我在 Windows 11 + WSL2 (Ubuntu 24.04) 环境下，用两周时间完成了 Linux 基础命令的纯键盘实战训练。本仓库记录了我的完整学习过程。

## 📚 学习路径
- Day 1：文件与目录基础（`mkdir`、`cd`、`pwd`、`touch`、`ls`）
- Day 2：复制、移动、重命名（`cp`、`mv`、`rm`）
- Day 3：查看文件内容（`cat`、`head`、`tail`、`less`、`nano`）
- Day 4：编写并编译 C 程序（`gcc`、`./`、`vim` 入门）
- Day 5：权限管理（`chmod`、`chown`）
- Day 6：查找与搜索（`find`、`grep`、`history | grep`）
- Day 7：进程管理（`ps`、`kill`、`top`、后台运行 `&`）
- Day 8：Git 与 Linux 联动（`clone`、`add`、`commit`、`push`）
- Day 9：压缩打包与系统信息（`tar`、`zip`、`df`、`free`、`du`）
- Day 10：脚本编写入门（`#!/bin/bash`、`chmod +x`、自动化脚本）

## 💻 环境
- 操作系统：Windows 11 + WSL2
- Linux 发行版：Ubuntu 24.04 LTS
- 终端：全程键盘操作，无鼠标

## 🛠️ 核心命令一览
`ls`, `cd`, `pwd`, `mkdir`, `touch`, `cp`, `mv`, `rm`, `cat`, `head`, `tail`, `less`, `nano`, `vim`, `gcc`, `chmod`, `chown`, `find`, `grep`, `ps`, `kill`, `top`, `tar`, `zip`, `df`, `free`, `du`, `git`, `ssh-keygen`

## 📖 每日笔记
详见 [`daily-notes/`](./daily-notes) 目录。

## 🧪 示例代码
练习中编写的 C 程序和 Shell 脚本放在 [`examples/`](./examples) 目录。

## 💡 踩坑心得
- 路径大小写敏感：`Users` 不是 `users`，初学时在这里栽过跟头。
- 权限问题：记得 `chmod +x` 才能执行脚本。
- WSL 磁盘丢失：遇到过两次，后来把代码放在 `/mnt/c/` 下（Windows 分区）永久安全。
- `tar -C` 参数：目标目录必须存在且拼写完整。
- `git log --oneline`（注意是 `oneline` 一个词）才能显示简洁提交记录。

## 🔗 相关链接
- 我的 GitHub：https://github.com/xiaozhang-11
- 本仓库：https://github.com/xiaozhang-11/linux-learning-journey
