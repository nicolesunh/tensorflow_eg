# tensorflow_eg
jupyter notebook的编辑是依托于某个文件夹进行的，默认打开文件夹为安装到的那个目录。在cmd窗口输入jupyter-notebook –generate-config会返回一个文件的路径，打开该文件，找到下面所示的代码

```
1.## The directory to use for notebooks and kernels.
2.#c.NotebookApp.notebook_dir = u''
```
将第二行的“ # ”删去，并将“ u’’ ”修改为自己想要定位的文件夹地址，保存文件，再重新打开jupyter notebook即可。
