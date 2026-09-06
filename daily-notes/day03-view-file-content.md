# Day 3：查看文件内容

## 学习目标
- 查看整个文件
- 查看文件头尾
- 分页浏览
- 使用简单编辑器

## 常用命令
| 命令 | 作用 |
|------|------|
| `cat file` | 显示全部内容 |
| `head -n N file` | 显示前 N 行 |
| `tail -n N file` | 显示后 N 行 |
| `less file` | 分页浏览（空格翻页，q 退出） |
| `nano file` | 简单文本编辑器 |
| `echo "text" > file` | 覆盖写入文件 |
| `echo "text" >> file` | 追加写入文件 |

## 实战练习
```bash
cd ~/practice/day1
echo "Hello Linux" > hello.txt
echo "Line 2" >> hello.txt
echo "Line 3" >> hello.txt
cat hello.txt
head -n 2 hello.txt
tail -n 2 hello.txt
less hello.txt
nano hello.txt
  

##记录
less中退出按q，不是ctrl+C
>会覆盖原文件,>>才是追加
