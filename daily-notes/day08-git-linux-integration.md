# Day 8：Git 与 Linux 联动

## 学习目标
- 在 Linux 中配置 Git
- 生成 SSH 密钥并绑定到 GitHub
- 克隆远程仓库
- 修改、提交、推送

## 常用命令
| 命令 | 作用 |
|------|------|
| `git config --global user.name "name"` | 配置用户名 |
| `git config --global user.email "email"` | 配置邮箱 |
| `ssh-keygen -t rsa -b 4096 -C "email"` | 生成 SSH 密钥 |
| `cat ~/.ssh/id_rsa.pub` | 查看公钥 |
| `git clone git@github.com:user/repo.git` | 克隆远程仓库 |
| `git add file` | 暂存修改 |
| `git commit -m "msg"` | 提交到本地仓库 |
| `git push origin master` | 推送到远程仓库 |


##记录
`SSH公钥必须添加到GitHub的Settings的SSH and GPG keys中`
`git log --online,才能显示提交记录`

