# jupyter文件存储位置更改
jupyter notebook的编辑是依托于某个文件夹进行的，默认打开文件夹为安装到的那个目录。在cmd窗口输入jupyter notebook --generate-config会返回一个文件的路径，打开该文件，找到下面所示的代码

```
1.## The directory to use for notebooks and kernels.
2.#c.NotebookApp.notebook_dir = u''
```
将第二行的“ # ”删去，并将“ u’’ ”修改为自己想要定位的文件夹地址，保存文件
重要：**在菜单栏打开jupyter-notebook的快捷方式的属性 ，将目标中的路径的最后面的 %USERPROFILE% 删掉，并按确认键退出。**

再重新打开jupyter notebook即可。

# 更新项目后推送到github仓库：
 在本地项目目录下打开git输入以下代码
```
（1）git add .

（2）git commit -m "update"

（3）git pull --rebase origri master

（4）git push origin master
```
