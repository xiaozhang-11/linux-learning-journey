# Day 6：查找与搜索

## 学习目标
- 按名称查找文件
- 在文件内容中搜索关键词
- 递归搜索
- 用管道组合命令

## 常用命令
| 命令 | 作用 |
|------|------|
| `find . -name "*.txt"` | 查找所有 txt 文件 |
| `find . -type f -name "*.log"` | 查找所有 log 文件 |
| `grep "keyword" file` | 在文件中搜索关键词 |
| `grep -r "keyword" dir/` | 递归搜索目录 |
| `grep -n "keyword" file` | 显示行号 |
| `grep -v "keyword" file` | 反向筛选（不包含关键词的行） |
| `history | grep "git"` | 筛选历史命令 |

## 踩坑记录
`grep -r必须在目录上使用，不能直接用于文件名`
