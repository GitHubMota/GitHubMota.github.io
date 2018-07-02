# githubmota.github.io
hexo clean
hexo server --debug
hexo deploy

仓库里面hexo分支为源码分支,master分支为渲染后的静态页面内容,从github上拉取代码后,注意要切换到hexo分支，代码提交和hexo deploy都在此分支执行.

每次hexo deploy发布博客时,仓库中master分支的内容都会被完全覆盖掉,[Mota's blog](https://githubmota.github.io/)访问master分支的资源文件.
