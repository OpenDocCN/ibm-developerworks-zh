<!--
    需要填充的占位符：
    
    README.md
    
        IBM DeveloperWorks：文档中文名
        {nameEn}：文档英文名
        {urlEn}：文档原始链接
        ibmdw：域名前缀
        飞龙：负责人名称
        wizardforcel：负责人 Github 用户名
        562826179：负责人 QQ
        ibm-developerworks-zh：ApacheCN 的 Github 仓库名称
        ibm-developerworks-zh：DockerHub 仓库名称
        ibm-developerworks-zh：PYPI 包名称
        ibm-developerworks-zh：NPM 包名称
    
    CNAME
    
        ibmdw：域名前缀

    index.html
    
        IBM DeveloperWorks：文档中文名
        #333：显示颜色
        ibm-developerworks-zh：ApacheCN 的 Github 仓库名称

    asset/docsify-flygon-footer.js
    
        ibm-developerworks-zh：ApacheCN 的 Github 仓库名称
-->

# IBM DeveloperWorks

> 协议：[CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)
> 
> 真相一旦入眼，你就再也无法视而不见。——《黑客帝国》

* [在线阅读](https://ibmdw.flygon.net)

## 下载

### Docker

```
docker pull apachecn0/ibm-developerworks-zh
docker run -tid -p <port>:80 apachecn0/ibm-developerworks-zh
# 访问 http://localhost:{port} 查看文档
```

### NPM

```
npm install -g ibm-developerworks-zh
ibm-developerworks-zh <port>
# 访问 http://localhost:{port} 查看文档
```
