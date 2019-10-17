# KS-HA
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

HA
=================

   * [High Availability Architectures](#high-availability-architectures)
      * [<a href="What.md">What Is HA</a>](#what-is-ha)
      * [<a href="Traffic/README.md">流量控制</a>](#流量控制)
         * [<a href="Traffic/Peak-Clipping/README.md">限流</a>](#限流)
         * [<a href="Traffic/Throttling/README.md">削峰</a>](#削峰)
         * [<a href="">流量整型</a>](#流量整型)
      * [服务](#服务)
         * [<a href="Service/Isolated.md">服务隔离</a>](#服务隔离)
         * [<a href="Service/Downgrade.md">服务降级</a>](#服务降级)
         * [<a href="Service/Fusing.md">服务熔断</a>](#服务熔断)
      * [<a href="LoadBalancing/README.md">负载平衡（Load balancing）</a>](#负载平衡load-balancing)
      * [<a href="Monitor/README.md">监控</a>](#监控)
      * [<a href="Multi-DataCenter/README.md">多数据中心</a>](#多数据中心)
      * [<a href="framework/README.md">框架</a>](#框架)
         * [Hystrix](#hystrix)
         * [Sentinel](#sentinel)
      * [Middleware](#middleware)
         * [<a href="https://github.com/SunnnyChan/sc.drill-code/tree/master/infra/apache-zookeeper">Apache ZooKeeper</a>](#apache-zookeeper)
      * [参考](#参考)
         * [<a href="https://github.com/SunnnyChan/SunnnyChan.github.io/blob/master/post/readme/reading/arch/scalable_arch">可伸缩架构 : 面向增长应用的高可用</a>](#可伸缩架构--面向增长应用的高可用)
         * [<a href="https://github.com/SunnnyChan/SunnnyChan.github.io/blob/master/post/readme/reading/arch/DS-Service-Framework">分布式服务框架：原理与实践</a>](#分布式服务框架原理与实践)

