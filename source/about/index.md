---
title: 关于我
date: 2024-11-15 23:53:12
---

## 教育经历

硕士，东北大学，计算机系统结构，2017.9~2020.1

学士，东北大学，计算机科学与技术，2013.9~2017.7

通过了 CET4/6 英语等级考试

CIPM 持证

## 工作经历

- 字节跳动，火山小视频，实习，后端工程师，2019.4~2019.8

- 华为，2012实验室，操作系统研发工程师，2020.1~至今

## 项目经历

### 读书时期

- Cache 替换策略分析：对 Intel 处理器上的 Cache 进行研究，主要分析 Cache 对程序执行性能的影响。
研究生阶段

- 动态远程安全认证：基于 ARM 处理器的 ETM(Embedded Trace Macrocell)机制进行程序的运行时跟踪，确保程序的 CFI(Control flow integrity)。

- 硬件安全架构: 在 RISC-V 指令架构处理器的基础上进行安全部件的研究，基于 PicoRV32 处理器上进行了 EA-MPU(Execution-aware Memory Protection)、Shadow Stack 的实现。

- DIFT(Dynamic Information Flow Tracking): 基于 PicoRV32 处理器，对敏感信息进行跟踪、标记(Tag Memory)和传播(Tag Propagation)，保护安全数据的机密性。

- 开源项目: 开发维护了一个 Intel 处理器上的简单操作系统，它实现了简单的内存管理和调度器，能够在 Bochs 进行仿真运行。 项目地址：https://github.com/zhangshuai-neu/pt_os


### 字节实习时期

- 火山小视频后端风控：风险控制相关后端开发，包括对用户上传的视频、图片、文本进行自动化审核。


### 华为工作时期

#### 内核研发

- KASAN机制：负责实现自研内核的Kernel Address Sanitizer机制开发与维护，能够对内核中的内存访问进行检测，防止内核出现OOB、UAF等问题。同时适配了musl libc，增加覆盖面。

- 随机数发生器：负责自研内核的RNG的重构与维护，能够生成高安全性的随机数。RNG符合NIST SP800、BSI标准，并通过CC认证。类似于Linux的 /dev/random和/dev/urandom。

- 密钥管理服务：负责自研内核的密钥管理服务的实现与维护，能够对内核中的密钥进行管理，类似于Linux key retention service。

- PXN/PAN/UAO硬件机制：负责自研内核的PXN/PAN/UAO的ARM硬件机制适配，能够对内核中的内存拷贝进行保护。

- 文件加密服务：负责自研内核的文件系统加密机制的密钥相关功能，实现终端设备文件保护，类似于Linux的fscrypt机制。

- 访问控制机制：负责自研内核的访问控制机制的部分功能，能够对内核中的敏感数据进行保护，类似于Linux的SELinux，DAC，Posix Capability机制。

#### 渗透测试与安全评估

- 担任自研内核渗透测试团队的第一任队长。针对鸿蒙内核进行渗透测试，发现并修复了多个安全漏洞。

- 投入内部网络安全实验室，负责自研内核的安全评估工作，对自研内核的安全能力、抗攻击能力进行全面、系统的评估。

#### 创新工作

- OS/Security/RAG(Retrieval-Augmented Generation)/AI Agents等相关的创新工作。
  
- 担任项目经理，负责与中国人民大学的多智能体协作校企合作项目

### 论文和专利

#### Paper

Internet-of-Things Security and Vulnerabilities: Taxonomy, Challenges, and Practice[J]. Journal of Hardware & Systems Security, 2018

Toward Private, Trusted, and Fine-Grained Inference Cloud Outsourcing
，ICNP CEC'24，2024

#### 专利

- 一项数据隐私保护专利