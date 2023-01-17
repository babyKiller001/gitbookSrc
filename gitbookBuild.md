# 1.gitbook搭建

> * [https://blog.csdn.net](https://blog.csdn.net/weixin_45509085/article/details/122734700?spm=1001.2101.3001.6650.1&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-122734700-blog-110134684.pc_relevant_default&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-122734700-blog-110134684.pc_relevant_default&utm_relevant_index=2)

> * [https://www.cnblogs.com](https://www.cnblogs.com/levywang/p/13569619.html)

> * [https://linxiaoru.github.io](https://linxiaoru.github.io/2019/01/18/%E5%A6%82%E4%BD%95%E7%94%A8gitbook%E6%90%AD%E5%BB%BA%E8%87%AA%E5%B7%B1%E7%9A%84%E6%96%87%E6%A1%A3%E6%95%B4%E5%90%88%E5%B9%B3%E5%8F%B0/)

# 2.gitbook配置 : book.json

* [插件](https://juejin.cn/post/6844903865146441741)

* book.json详解
    > <https://github.com/GitbookIO/gitbook/blob/master/docs/config.md>
    > <https://www.chengweiyang.cn/gitbook/customize/book.json.html>
    > <https://jiangminggithub.github.io/gitbook/4-config.html>

# 3.将gitbook托管到github pages

* [教程](https://yangjh.oschina.io/gitbook/UsingPages.html)
    > 在按照该教程做的时候出了一些问题，最后决定重新建一个文件夹专门用来存放当前项目文件夹
    > _book里的静态网页内容，然后为那个文件夹建仓库，远程推送到github然后直接用pages

* 更新
    > 1. 在项目文件夹 books/blog 下编辑，[gitbook build]生成新的静态网页
    > 2. 在git-bash中进入目录 d:/gitbook/books/blogPage
    > 3. [cp -r ../blog/_book/* ./] 将更新后的静态网页内容复制到当前文件夹
    > 4. 提交推送到远程仓库
