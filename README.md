# auto_commit_everyday
作用:每天定时向github仓库提交,从而在贡献图上增加更多的绿色.
利用github action自动化操作.


usage:
1. 创建一个专门的仓库(这是预防将来你不想使用了,将该仓库设为private即可在贡献图上去除相应的内容.)
2. 你的仓库下创建.github/workflows/auto_commit.yml.
3. 将本仓库的.github/workflows/auto_commit.yml复制到你仓库的.github/workflows/auto_commit.yml内容当中.
4. 修改内容:你需要修改.github/workflows/auto_commit.yml当中git提交的信息.其中,user.email建议使用github提供的noreply仓库.
5. 提交.
6. 你可以尝试在github的仓库页的actions找到"Daily Auto Commit"这个任务,并且尝试运行一次.运行如果成功,则配置正确.
