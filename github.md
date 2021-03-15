# Github
----------
## common usage
[https://www.runoob.com/w3cnote/git-guide.html](https://www.runoob.com/w3cnote/git-guide.html "https://www.runoob.com/w3cnote/git-guide.html")


## problems_solutions常规push
> git add file
> 
> git commit -m "***"
> 
> git push


## github blog 常见用法
[https://hexo.io/zh-cn/docs/commands.html](https://hexo.io/zh-cn/docs/commands.html "https://hexo.io/zh-cn/docs/commands.html")

hexo new "title"

hexo clean 清除缓存

hexo generate(g) 生成

hexo publish   draft->posts

hexo deploy


## fatal: unable to access 'https://github.com/XYTK0x0/all_kinds_of_notes/': OpenSSL SSL_read: Connection was reset, errno 10054

git push出错

可能是网络不稳定/SSL的

> solution: git config --global http.sslVerify "false"

不是根本的解决办法，有时仍会出错

## 删除文件

手动删除

git status查看状态

git add .

git commit -m " "

git push