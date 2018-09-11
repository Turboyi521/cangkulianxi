##使用github的基础六个操作
1、创建一个本地仓库
    --创建.gitignore文件,指定需要忽略的文件，idea，node_modules（任意目录下,前面有/
    --创建工作区：git init
    --创建索引区:git add *
    --创建版本区:git commit -m "init"
2、创建远程仓库
3、本地仓库推送到远程
    --git remote add origin https://github.com/Turboyi521/cangkulianxi.git
    --git push origin master 本地仓库的版本区推送到远程，在工作区修改，版本区没有
4、本地有修改，推送到远程
    git add *
    git commit -m "init"
    git push origin master
