# Hello,World! This is PieCloudDB

![logo](https://app.pieclouddb.com/logo_normal.png)

PieCloudDB is OpenPie's next-gen cloud-native virtual data warehouse, which achieved data warehouse virtualization technology through four main technical breakthroughs:

## Cloud-Native Storage-Computing Separation Architecture

PieCloudDB leverages a "metadata-computation-data separation" architecture for separate management of cloud storage and computing resources. Cloud computing resources can be elastically allocated based on computing tasks, with costs calculated based on usages time and scale.

## New Query Optimizer "Dutch"

PieCloudDB intelligently generates statistical information more and efficiently, which supports the “Dutch” query optimizer to optimize query plans. It offers advanced features such as aggregation pushdown, pre-computation, and block skipping to meet complex analytical query demands.

## Cache Architecture and New Storage Engine "JANM"

PieCloudDB employs multi-level cache structures for metadata and user data at the computation layer to reduce network latency and data migration costs, improves computation efficiency, and meet real-time requirements. Additionally, PieCloudDB's "JANM" storage leverages an efficient file format for object storage, enhancing computing efficiency and reducing network requests.

## Patented Technology -- eMPP Distributed System

PieCloudDB utilizes the Elastic Massive Parallel Processing (eMPP) architecture to execute parallelized tasks across multiple virtual warehouses on cloud, allowing computing resources to scale in or out based particular workloads and enabling PieCloudDB to handle massive PB-level data.

---

PieCloudDB 是拓数派旗下的新一代云原生虚拟数仓，主要通过以下技术突破实现数仓虚拟化：

## 云原生存算分离架构

运用元数据-计算-数据分离的三层架构，实现云上存储资源与计算资源的独立管理。云上计算资源可弹性分配，有查询计算任务的时候按需启动，按照使用时间和规模计算成本。

## 全新的优化器「达奇」

PieCloudDB更智能高效的数据统计信息可以帮助达奇优化器生成更高效的查询计划。达奇优化器支持聚集下推，预计算，Block Skipping等高级特性，全面满足各种复杂的分析查询需求。

## 高效数据缓存结构及全新的存储引擎「简墨」

在计算层，虚拟数仓中的各个计算节点针对元数据和用户数据都设计了多层缓存结构，避免网络延迟和数据移动，提高计算效率，保证用户的实时性需求。PieCloudDB针对底层对象存储设计了高效的文件格式，可在节省网络请求的同时提高计算效率。

## eMPP（elastic MPP）分布式专利技术

在云上，PieCloudDB利用eMPP（elastic Massive Parallel Processing）架构，实现多集群并发执行任务。计算资源可根据负载的变化灵活进行扩缩容，轻松应对PB级海量数据。
