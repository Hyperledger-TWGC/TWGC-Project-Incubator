# Probe
<!-- 合适的项目名称（非暴力、色情、歧视，符合相关国家法规规定）-->
https://github.com/SamYuan1990/Probe
<!-- 如果项目主要的托管平台不是Github，需要在Github.com建立mirror镜像，并提供链接 -->
<!-- 项目内容的要求
- 开源许可证License：Apache 2.0或兼容协议
- 完整的Readme
- 贡献流程Contribution guideline
- 持续集成（文档类项目除外）
- commit需要有sign-off
-->

## 简介
根据[性能测试白皮书](https://www.hyperledger.org/learn/publications/blockchain-performance-metrics), Probe是一个面向Hyperledger Fabric维护者，用户，研究者的web UI的应用程序，短期而言旨在提供控制被测网络（SUT）并协调压力生成工具于观察工具，来针对性的观察Fabric出块参数对于Fabric网络性能的影响。

- 提供循环测试控制。
- 提供可视化的结果对比图。
- 提供基于test-network的配置案例。

长期而言Probe计划扮演一个协调者的工作

- Probe将允许您设计shell脚本来调度SUT和测试工具。
- Probe将允许您以自定义的方式使用GUI来可视化性能指标和配置之间的关系。

## 目的
<!-- 相比于其他项目，这个项目不同之处在哪？ -->
<!-- 解决了什么痛点？-->
主要在于可以通过UI来进行设置来解决，Fabric出块参数对于Fabric网络性能的影响。
通过UI界面来可调节参数，并调节测试脚本的运行流程，并通过UI来展示Fabric出块参数对于TPS的影响。
<!-- 是否开辟了具有前瞻性和预见性的领域？或者有清晰明确的产出物？ -->
目前明确的产出为Probe该项目并且通过该项目来解决Fabric出块参数对于Fabric网络性能的影响这一问题，如
https://github.com/SamYuan1990/Probe/blob/main/doc/HowToConfigFabricParameters.md

## 路线图和计划
目前有几个方面
0.0.5 | support different sample deploy plan with peers
0.0.6 | support different sample deploy plan with orgs
0.0.7 | support different sample deploy plan with gossip
0.0.8 | support different sample deploy plan with mvcc
0.0.9 | support different sample deploy plan with data size

## 项目的活跃度
### 影响力
<!-- 请尽可能提供项目被引用，参考的链接 -->
高校学校学生邮件询问项目内容和工作方式

### Github指标
<!-- 在评审的过程中，评委会翻阅Github的硬性活跃度指标 -->
<!-- 包括clones，Fork，Stars，Issues，Discussions，维护者maintainers，来自贡献者的commits -->

### 其他社区活力
<!-- Github之外或者自身难以统计的数据，如其他社群（微信，RocketChat，新媒体，视频平台），讨论（微博，Twitter话题）等等 -->
