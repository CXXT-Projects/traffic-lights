# traffic-lights

19级崇新学堂 git 实战仓库

## Intallation

1. 下载并安装 Git https://git-scm.com/downloads ；
2. 安装完成以后，使用 Windows 的同学打开 git bash 命令行工具，使用 macOS 的同学打开终端；
3. 在终端输入 `git --version`，以检查是否成功安装 git。

## Contributing

1. fork 这个项目，并 `clone` (`git clone xxx`)自己的 fork 到本地。
2. 进入自己 `clone` 项目的根目录，使用命令 `git remote -v` 查看是否有 CXXT 的上游地址。
3. 如果只有自己 fork 的远程地址，没有上游项目的地址，那么使用命令 `git remote add upstream https://github.com/CXXT-Projects/traffic-lights` 添加。
4. 再次使用 `git remote -v` 查看是否有上游项目地址存在。
5. 远程地址配置完毕，`git fetch upstream` 下载最新的上游代码。
6. 使用 `git merge upstream/master` 更新自己的 master 分支代码为最新的（前提是切换到 `master` 分支，`git checkout master`）。
7. 这时候就可以开始自己的修改工作了，新建一个分支 `git checkout -b your-branch-name`。
8. 在新的分支上做出你自己的代码修改。
9. 在项目根目录下使用 `git add .` 添加全部修改。
10. 使用 `git commit -m "修改相关的信息"` 提交这个修改。
`git push origin` 或者是 `git push` 讲提交的修改推送到自己的 github fork 项目下。
11. 从 github 自己的项目中对上游项目发起合并请求 (Pull Request)。
PR 被上游仓库开发者审核、测试，最终合并。
