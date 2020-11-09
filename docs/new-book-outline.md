# 《Java 研发自测》大纲

## 一、选题思路
软件测试的种类和分类方法非常多，研发自测的概念来自于微软，微软的交付质量主要由开发者保障。研发自测的主要内容有单元测试、集成测试，以及一些自动化的静态扫描工具。

研发自测并不只是局限于让开发人员编写单元测试，而是围绕着单元测试和集成测试提高质量。例如，一些 QA 的基本知识对于开发人员同样重要，在实践中我们发现代码评审对一个项目成功起到至关重要的作用。

开发人员要写出易于维护和规范的自动化测试脚本，往往受限于框架、基础设施。市面上讲解单元测试的书籍没有结合 Spring 等框架，给出一个在实战环境下的测试策略，这本书的选题描述的是在实战中编写单元测试、集成测试的经验和方法。

## 二、读者对象

1. 开发人员。他们可以在理解软件测试的基本概念基础上，编写出优良的单元测试、API 测试，从而提高软件的质量。将测试行为提前到进入测试周期前，可以提高提测的成功率，减少开发任务在测试阶段的停留时间，提高迭代效率。
2. 研发经理。他们可以为团队设定代码评审规范、架构规范，以及搭建研发自测的必要工具和基础设施。充分的单元测试和集成测试，可以大大减少重构的成本和风险，让重构随时发生，减少代码腐化。

## 三、内容简介

### 第一部分 研发自测基础

- 第一章，测试基础。介绍一些测试的基本概念，以及研发自测的概念和意义。
- 第二章，代码评审。介绍如何进行代码评审（Code Review），代码评审的实践，以及一些自动的代码评审的工具。
- 第三章，单元测试。介绍如何编写单元测试，如何设计测试用例，断言方法。
- 第四章，测试替身。介绍如何编写测试替身（Mock、Stub、Spy），处理单元测试中的依赖关系。
- 第五章，Spring 环境下的测试。介绍如何在 Spring 环境下编写单元测试，以及通过 Spring Boot 注入测试配置，和一些测试工具集合。
- 第六章，API 测试。介绍使用 Mock MVC 的集成测试，通过 Restassure、JsonPath 等工具编写有效的 API 测试。

### 第二部分 研发自测高级

- 第七章，微基准和并发测试。介绍 JMH 测试，验证 java 组件的基准性能，以及测试并发场景下的业务安全。
- 第八章，测试工程化（TestOps）。介绍如何利用 CI/CD 工具自动运行和管理测试，如何搭建 Jenkins 作为 CI 工具和测试环境，以及集成一些自动化检测工具。
- 第九章，测试驱动设计（TDD）。介绍 TDD，使用 TDD 编写测试覆盖率高的代码。 
- 第十章，测试守护重构。介绍如何为重构和遗留系统准备测试保护网，如何通过契约测试快速保护 API，如何验证数据迁移脚本的正确性。

### 第三部分 探秘测试框架

- 第十一章，测试框架源码分析，分析测试框架的原理，帮助解决测试过程中常见的问题。包含 junit、mockito、Hamcrest、jacoco 等库和框架。

## 四、市场分析



## 五、特色分析

## 六、作者简介