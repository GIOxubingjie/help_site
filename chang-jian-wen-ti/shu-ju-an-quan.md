# 数据安全

GrowingIO 的业务模式是向企业客户收费，我们提供专业的产品和服务，并且坚持第一方数据属于第一方客户，企业版支持把数据回传给客户。

## 如何保证数据的安全性？

### 1.加密传输

数据传输都是在 https 的 SSL 端口进行传输，防止嗅探。同时，在传输过程中会采取加密和混淆的方式，生成一系列无法被识别的代码和字符串，从而达到安全传输的目的。

### 2.隔离保存

传输过来的数据会储存在云服务上，我们采用的是全球最大的云服务商AWS，并集成了 AWS 的安全机制，在 GrowingIO 内部也拥有一套完整的安全机制和权限管理，并且生产和开发环境完全隔离。

### 3.严格控制内部权限

GrowingIO 的客户服务人员无权访问客户数据，除非客户直接授权客服登录。同时，您的管理账户里面都有日志记录，详细记录了谁对您的账户进行了操作，其中客户服务或者任何有权限的人的操作都有日志您可以查询。

GrowingIO 提供的是数据分析的产品，方法论和最佳实践，不做未经客户授权的任何数据交易相关的业务。

