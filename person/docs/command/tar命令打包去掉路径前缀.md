1. 所有的文件都在一个文件夹下进行打包：
```shell
    tar -cvf <tar-name> -C <dir> <files>
```
2. 文件在不同的文件夹下，就需要使用`-r`选项来把文件逐个添加到压缩包中（没有压缩包的话会创建）：
```shell
    tar -rf <tar-name> -C <dir-1> <dir-1/file(s)-1>
        ...
    tar -rf <tar-name> -C <dir1-N> <dir-N/file(s)-N>
```