git config --global user.name SugarOne
git config --global user.email 659162428@qq.com
ls
mkdir <file name>
git add . 全部添加
git status 状态
git commit 提交
git commit -m "提交内容"
git rm read.txt 删除read.txt文件

国内有git.occhina.net
git remote add <别名> https://...给远程地址取个别名
git push origin master origin是默认的远程别名
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
