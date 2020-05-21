git config --global user.name "castello"
git config --global user.email "wuqichao37@gamil.com"
cd git.first
git init
添加文件至暂存区 git add readme.txt （git add .）（git ）
提交文件至仓库 git commit -m "readme commit"
git status 查看修改内容
撤销 git checkout -- readme.txt 文件未提交至暂存区的修改丢弃

不同 git diff readme.txt
日志 git log
回退 上个版本 git reset --hard HEAD^  前100个版本 git reset --hard HEAD~100
版本 git reflog
恢复 git reset --hard 6459ac2

生成ssh  ssh-keygen -t rsa
查看 cat ~/.ssh/id_rsa cat ~/.ssh/id_rsa_pub 文件在user/.ssh/ 目录下

记住密码
touch .git-credentials
https://username:password@github.com
git config --global credential.helper store
git config –global credential.helper cache
git config credential.helper ‘cache –timeout=3600’

清除缓存
git rm -r --cached .

