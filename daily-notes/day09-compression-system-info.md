# Day 9：压缩打包与系统信息

## 学习目标
- 打包并压缩文件（tar / zip）
- 解压到指定目录
- 查看磁盘空间和内存
- 查看文件夹大小

## 常用命令
| 命令 | 作用 |
|------|------|
| `tar -czvf archive.tar.gz dir/` | 打包并压缩 |
| `tar -xzvf archive.tar.gz` | 解压到当前目录 |
| `tar -xzvf archive.tar.gz -C target/` | 解压到指定目录 |
| `zip -r archive.zip dir/` | 压缩为 zip 格式 |
| `df -h` | 查看磁盘使用 |
| `free -h` | 查看内存使用 |
| `du -sh dir/` | 查看文件夹总大小 |

##记录
`-C后面必须跟已存在的目录名`
`zip可能需要安装: sudo apt install zip unzip -y`
`df -h 中表示人类可读格式`
