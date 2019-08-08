# 文件夹说明
## specs 文件夹
技术专题内容。包含各技术专题的中英文md文件；中英文的目录树索引文件：nav.zh.yml,nav.en.yml。
## terms文件夹
GIS术语。包含术语对应的中英文的md文件；中英文的目录树文件：nav.zh.yml,nav.en.yml。
# 如何使用
将 specs、terms两个文件夹，直接拷贝到content文件夹下。content文件夹，需要从对应产品文档仓库获取。例如，要构建iDesktop Java 帮助文档，需要从iDesktop-Java-MainDocs 仓库中下载所有文件，找到content文件夹，将这两个文件拷贝进去即可。
除此之外，还需要从Products-Help-MainFrame 仓库中下载所有文件。

一个完整的产品帮助文档，由以下三个仓库的内容组成：
- Products-Help-MainFrame 
- Products-Help-PublicContents
- 产品文档仓库内容：命名规则：产品名称-MainDocs

在进行三个仓库的文件合并时，需要按照使用说明操作，将文件拷贝到指定的目录下，否则可能会编译失败。

# 如何编译文档
## 需要的环境
### Node.js
Node.js的安装与配置，请参照Node.js的官网https://nodejs.org/en/
### Yarn
Yarn的安装，可参照https://www.yarnpkg.com/zh-Hans/
### 本地编译
文档运行所需要的环境安装完成之后，在源码目录下，打开cmd，先执行yarn，成功后，再执行 yarn dev -p 端口号，执行成功后，在本地浏览器中，输入 localhost:端口号，就能访问在线文档。

# 如何发布文档
使用nginx发布。
