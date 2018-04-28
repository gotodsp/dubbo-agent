# dubbo-agent

众所周知，Dubbo 的 RPC 通讯和服务治理能力一直局限在 Java 领域，因此增加多语言适配是建设 Dubbo 生态环境的一个重要方向。随着微服务及相关技术实践的落地，Service Mesh 已经成为分布式场景下服务化改造的热门解决方案，并与底层设施及周边环境实现了很好的融合，这些都与 Dubbo 的能力如出一辙，未来 Dubbo 将有可能发展成为 Service Mesh 的一种通用解决方案。

在初步了解了 Dubbo 和 Service Mesh 的情况下，我们来实现一个简化版本的 Agent，用 Service Mesh 的思想对 Dubbo 进行一下改进。

[What Is a Service Mesh?](https://www.nginx.com/blog/what-is-a-service-mesh/)
