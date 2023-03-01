<!-- 配置： -->

name:
git config --global user.name "zhangchenhao"
email:
git config --global user.email "1939249521@qq.com"

<!-- 使用 git: -->

git status 查看当前仓库的状态
git init 初始化仓库

新添加到项目中的文件处于未跟踪状态
未跟踪 --> 暂存
git add <filename> 将文件切换到暂存状态
git add \* 将所有已修改（未跟踪）的文件暂存
暂存 --> 未修改
git commit -m "xxx" 将暂存的文件存储到仓库
git commit -a -m "xxx" 提交所有已修改的文件（未跟踪的不提交）
未修改 --> 修改
修改代码后变化

<!-- 常用命令 -->

重置文件
git restore <filename> #恢复文件
git restore --staged <filename> #取消暂存状态
删除文件
git rm <filename> #删除文件
git rm <filename> -f #强制删除
移动文件
git mv from to #移动文件、重命名文件

<!-- 分支 -->
