# 文件夹说明
## topics文件夹
技术专题内容。包含各技术专题的中英文md文件；
## terms文件夹
GIS术语。包含术语对应的中英文的md文件；
## specs文件夹
编写文档时供参考的文档规范。包含各个规范对应的中文md文件。
# 如何使用
将所有文件夹，直接拷贝到content文件夹下对应的zh、en文件夹下。content文件夹，需要从[Products-Help-MainFrame](https://github.com/SuperMap/Products-Help-MainFrame "文档主框架")仓库下载。

一个完整的产品帮助文档，由以下三个仓库的内容组成：
- Products-Help-MainFrame 
- Products-Help-PublicContents
- 产品文档仓库内容：命名规则：产品名称-MainDocs

其中，Products-Help-PublicContents仓库中的所有内容，产品文档仓库中的所有内容，都需要拷贝到Products-Help-MainFrame仓库中的content文件夹下。

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
