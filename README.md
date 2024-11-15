# serverless-database-paper-list

## 搜索关键词

* serverless
* Faas

serverless-database-paper-list

https://github.com/penghuima/awesome-serverless-papers

https://github.com/Jeffwan/serverless-research

https://github.com/RuifMaxx/Paper-List-of-Serverless

https://github.com/RuifMaxx/Paper-List-of-cloud-resource-management


[FaaSTube: Optimizing GPU-oriented Data Transfer for Serverless Computing](https://arxiv.org/pdf/2411.01830)

无服务器计算在机器学习推理应用程序中获得了巨大的吸引力，这些应用程序通常部署为由具有数据依赖性的多个 CPU 和 GPU 函数组成的无服务器工作流。但是，现有的无服务器计算数据传递解决方案主要依靠主机内存进行快速数据传输，这需要大量数据移动并导致显著的 I/O 开销。在本文中，我们介绍了 FaaSTube，这是一种用于无服务器推理的 GPU 高效数据传递系统。FaaSTube 管理 GPU 内存池中的中间数据，以促进 GPU 函数之间的直接数据交换。它支持通过 PCIe 和 NVLink 进行精细带宽共享，最大限度地减少主机到 GPU 和 GPU 到 GPU 的数据传递延迟，同时在函数之间提供性能隔离。此外，FaaSTube 还实现了一个弹性 GPU 内存池，该池可以动态扩展以适应不同的数据传递需求。对实际应用的评估表明，与最先进的产品相比，FaaSTube 将端到端延迟降低了 90%，吞吐量提高了 12 倍。
