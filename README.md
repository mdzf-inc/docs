
* 提供多个微服务之间互相依赖调用和样例
* 提供与各种基础设施集成和部署的样例
* 主要为kratos框架使用演示，很多组件的设计做了简化或模拟处理，与实际的电商项目有一定出入，仅供参考

具体架构请参考文档：[Design](design.md)（[设计](design_cn.md)）

**ATTENTION: This project is a Work-in-Progress.**

**注意，目前尚在开发，暂时无法运行，仅供代码参考。**

## Kratos Mono-Repo structure
```
.
├── api  // API&Error Proto files & Generated codes
│   ├── foo
│   │   ├── job
│   │   └── service
│   └── bar
│       └── interface
├── app  // kratos microservices projects
│   ├── foo
│   │   ├── job
│   │   └── service
│   └── bar
│       └── interface
├── pkg  // common used packages
└── docs

```
