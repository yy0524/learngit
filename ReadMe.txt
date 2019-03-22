git config --global user.name <名称>
git config --global user.email <邮箱地址>
ls
mkdir <file name>
git add . 全部添加
git status 状态
git commit 提交
git commit -m "提交内容"
git rm read.txt 删除read.txt文件

国内有git.occhina.net
git push origin master origin是取远程别名
git clone https://...克隆地址
git pull <远程地址别名或者远程地址> master 拉远程代码
git log 查看日志
git log --pretty=oneline 一行看日志
git reset --hard HEAD^ 切回到以前2
git reset --hard <ID号> 强切换
git relog 查看以前的log
git branch 查看分支
git branch <分支名>创建分支
git checkout branch1 切换到branch分支上
git merge 合并分支（需切换到要合并的主分支上）
git remote remove <远程库名>
git remote -v 查看仓库地址
git remote 查看远程仓库
git checkout -b dev 创建分支并，切换到分支
git remote remove <远程库名> 删除的是别名
git remote add <远程库名> <远程地址> 添加远程库别名
git remote rename <旧名称> <新名称>
ssh-keygen -t rsa -C <你的邮箱地址>
ssh -T git@github.com 验证ssh是否通信成功

usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]
git clone 将存储库克隆到新目录中
git init 创建空的Git存储库或重新初始化现有的Git存储库

处理当前更改:
git add 将文件内容添加到索引
git mv 移动或重命名文件、目录或符号链接
git reset 将当前磁头重置为指定状态
git rm 从工作树和索引中删除文件
git bisect 使用二进制搜索查找引入错误的提交
git grep 打印与图案匹配的线条
git log 显示提交日志
git show 显示各种类型的对象
git status 当前状态
git branch 分支列表、创建或删除分支
git checkout 切换分支或还原工作树文件
git commit 记录对存储库的更改
git diff 显示提交、提交和工作树等之间的更改
git merge 将两个或多个开发历史记录合并在一起
git rebase 在另一个基本提示上重新应用提交

忽略文件：
echo -e "忽略内容" > .gitignore



