## 现代操作系统设计及其基本问题

- Conflict: 解决冲突的策略设计
- Coordination: 协调协作活动的关系
- Coherence: 保证数据的一致性
- Access Control: 实现数据存取控制

在以下4方面有待完善：并发（concurrent）、共享（sharing）、虚拟（virtual，具体是  
指存储、网络虚拟化）和异步（asynchronism）。

## 未来操作系统的趋势是函数式、模块化

- Redox: 用Rust写的一款OS
  - [介绍文章Programming for Redox OS](https://dev.to/legolord208/programming-for-redox-os-4124)
  - [开源项目Redox](https://github.com/redox-os/redox)
  - [访谈节目Building a secure Operating System (Redox OS) with Rust](https://changelog.com/podcast/280)

- TockOS: 用Rust写的一款embedded OS  
  - [TockOS](https://www.tockos.org/)