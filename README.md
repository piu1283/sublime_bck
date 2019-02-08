### 备份 sublime test 的插件 

主要备份了:

- Installed Packages
- Packages

这两个文件夹。

### 使用方法:
```shell
cd /Users/alfredchan/Library/Application Support/Sublime Text 3
rm -rf Install\ Packages Packages
git init 
git remote add origin git@github.com:piu1283/sublime_bck.git
git pull origin master
```
