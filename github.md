1、登录GitHub，创建仓库
2、本地拉取仓库
```
git clone git@github.com:coffeekhoo/hello-world.git
```
这个命令自动做了3件事：

    1、自动执行了 git init —— 在本地目录下创建了 .git；
    2、拉取了远程代码；
    3、自动添加了远程仓库 origin，并设置默认分支（通常是 main）。

3、本地开发

4、提交文件
```
cd hello-world
git add .
git commit -m "修改容"
git push origin main
```
5、本地改仓库
```
git pull origin main
```