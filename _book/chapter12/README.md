Go语言模块管理经历了三个重要的阶段：
1. 使用GOPATH管理所有的第三方库；
2. 使用Vendor将项目依赖库私有化；
3. Go Module；

早期Go语言单纯使用GOPATH进行依赖管理，后来增加了Vendor，再后来引入了go module。演进过程中还有为数众多的第三方管理工具，比如`Glide`、`Govendor`等等。
本章主要按照依赖管理演进路线介绍主流的方案。