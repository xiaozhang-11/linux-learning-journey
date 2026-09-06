# Day 2：复制、移动、重命名

## 学习目标
- 复制文件和目录
- 移动文件
- 重命名文件
- 删除文件

## 常用命令
| 命令 | 作用 |
|------|------|
| `cp src dst` | 复制文件 |
| `mv src dst` | 移动或重命名 |
| `mkdir dir` | 创建目录 |
| `rm file` | 删除文件（不进回收站，谨慎！） |
| `rm -rf dir` | 强制删除目录及内容 |

## 实战练习
```bash
cd ~/practice/day1
cp readme.txt readme_backup.txt
mkdir backup
mv readme_backup.txt backup/
mv project.c main.c
rm readme.txt
ls -la
ls backup/


##记录
"cp必须带目标参数，不能只写源文件"
"rm删除的文件不进入回收站，删除前先用ls确定"

