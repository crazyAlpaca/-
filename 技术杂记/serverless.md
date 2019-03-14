# Serverless

## 历史演进

* 通过虚拟化技术将大型物理机虚拟成单个的VM资源。
* 将虚拟化集群搬到云计算平台上，只做简单运维。
* 把每一个VM按照运行空间最小化的原则切分成更细的Docker容器。
* 基于Docker容器构建不用管理任何运行环境、仅需编写核心代码的Serverless架构。

## 是什么

Serverless架构，即无服务器架构。用户不用更多的去考虑服务器的相关内容，可以交给各大厂商提供的serverless架构的成熟产品。

## 两种提供方式

1. 函数即服务，Function as a Service，FaaS
2. 后端即服务，Backend as a Service，BaaS。

## 各大厂商Serverless产品

|厂商|产品|
|---|---|
|亚马逊|AWS Lambda|
|微软|Microsoft Azure|
|谷歌|Google App Engine|
|谷歌|Google Cloud Functions|
|IBM|IBM OpenWhisk|

## 优势

* 降低成本 —— 无论是物理资源的硬成本，还是开发、维护人员的软成本。
* 安全可靠 —— 依赖大型厂商的技术做有效保障

