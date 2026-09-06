# Day 1：文件与目录基础

## 学习目标
- 熟悉终端基本操作
- 创建目录、文件
- 查看当前路径、列出文件

## 常用命令
| 命令 | 作用 |
|------|------|
| mkdir dir | 创建目录 |
| cd dir | 切换目录 |
| pwd | 显示当前绝对路径 |
| touch file | 创建空文件 |
| ls | 列出当前目录内容 |
| ls -la | 列出所有文件（含隐藏）及权限 |

## 实战练习
bash
mkdir -p ~/practice/day1
cd ~/practice/day1
pwd
touch readme.txt project.c main.py
ls -la
