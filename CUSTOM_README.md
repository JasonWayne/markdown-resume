安装开发环境（要修改template必须安装）
参考http://there4development.com/markdown-resume/

~/composer.phar install

**注：**
原本打算修改templates以后，重新编译，可以用修改后的css，但是由于在电脑上修改任意css文件后重新运行会报奇怪的错，因此放弃。

现在的方案是：
```shell
bin/md2resume pdf --template swissen me/me.md me/
```
即采用默认提供的swissen模版生成pdf以后，再用Acrobat小幅修改pdf。