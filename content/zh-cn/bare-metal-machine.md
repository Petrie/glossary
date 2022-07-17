---
title: 裸机
status: Completed
category: 技术
---

## 这是什么

Bare metal refers to a physical computer, more specifically a server, that has one, and only one, operating system. The distinction is important in modern computing because many, if not most, servers are [virtual machines](/virtual-machine/). A physical server is typically a fairly large computer with powerful hardware built-in. Installing an operating system and running applications directly on that physical hardware, without [virtualization](/virtualization/), is referred to as running on “bare metal.”

## Problem it addresses

将一个操作系统与一台物理计算机配对是计算的原始模式。物理计算机的所有资源都可直接用于操作系统，并且不存在虚拟化层，将操作系统指令转换为硬件不会人为延迟。

## How it helps

By dedicating all compute resources of a computer to a single operating system, you potentially provide the best possible performance to the operating system. If you need to run a workload that must have extremely fast access to hardware resources, bare metal may be the right solution.

In the context of [cloud native apps](/cloud-native-apps/), we generally think of performance in terms of [scaling](/scalability/) to a large number of concurrent events, which can be handled by [horizontal scaling](/horizontal-scaling/) (adding more machines to your resource pool). But some workloads may require [vertical scaling](/vertical-scaling/) (adding more power to an existing physical machine) and/or an extremely fast physical hardware response in which case bare metal is better suited. Bare metal also allows you to tune the physical hardware and possibly even hardware drivers to help accomplish your task.
