---
title: 调试
status: Completed
category: 概念
---

## 是什么

Debugging is the process or activity of finding and resolving bugs (or errors) from computer programs, software, or systems to get the desired result.  
调试是从计算机程序、软件或系统中查找并解决 Bug（或错误） 以获得预期结果的过程或活动。  
A bug is a defect or a problem leading to incorrect or unexpected results.  
Bug 是导致不正确或不符合预期结果的缺陷或问题。 

## 解决的问题

Software development is a complex activity that makes it nearly impossible to write code without introducing bugs.  
软件开发是一项复杂的活动，在不引入错误的情况下编写代码几乎是不可能的。  
Those bugs lead to code that will likely not function as desired (undefined behavior) when executed.
这些错误导致代码在执行时可能无法按预期运行。 
Depending on how critical an application is, bugs can have a significant negative impact — financially or even on human lives.
根据应用程序的重要性，错误可能会产生重大的负面影响 —— 经济上甚至是人类生活。 
Usually, application code has to go through different stages or environments where it gets tested.
通常，应用程序代码必须在不同阶段或环境被测试。 
The more critical an application is, the more accurate the testing has to be.
应用程序越关键，测试就必须越准确。 

## 如何帮助

When bugs appear, engineers have to debug (e.g., finding and fixing) the app to decrease undesired behavior for production systems.
当出现错误时，工程师通过调试（例如，查找和修复）应用程序以减少生产系统中的不良行为。 
Debugging is no easy task as engineers have to track down the source of the undesired behavior.
调试并非易事，因为工程师必须追踪不良行为的根源。 
It requires knowledge about the code itself and the execution context at runtime.
它需要有关代码本身和运行时执行上下文的知识。 
This is where different debugging techniques and tools come in handy.
这是不同的调试技术和工具派上用场的地方。 
Analysis of logs, traces, and metrics, for instance, are used for debugging directly in production.
例如，日志、跟踪和指标的分析用于直接在生产中进行调试。 
Developers can use interactive debugging to step through the code at runtime while analyzing the related execution context.
开发人员可以使用交互式调试在运行时单步执行代码，同时分析相关的执行上下文。 
Once they have identified the source of the failure, they correct the code and create a bug fix or patch.
一旦定位到故障的根源，他们通过发起修复错误的请求或者发布新的补丁来更正代码行为。 