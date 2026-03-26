---
layout: post
title: "第一篇笔记"
date: 2026-03-26 12:00:00 +0800
categories: [notes]
---

# 第一篇笔记

这是我的第一篇科研笔记。

今天的想法：

阅读一篇综述《Radio Frequency Switches Based on Emerging Resistive Memory Technologies: A Survey》

1. 为什么需要非易失RF开关？
答：RF开关是实现可重构系统的关键单元。当前系统向着多频段、大规模集成的方向发展，对系统功耗提出了更高的要求。传统RF开关是易失性的，需要维持功耗。
而非易失RF开关不需要维持功耗，因此十分有利。
2. 用什么指标评价？
答：核心指标是截止频率Fco，其他重要的指标是循环寿命、面积、开关能耗、开关速度、功率容量、线性度。
3. 现有三类阻变方案各自优势和短板
答：CBRAM，FOM很高，但可靠性差。ReRAM，CMOS优化，但Ron不够低，FOM不高。PCM，Ron低，工艺成熟，但需要间接加热，存在热串扰风险。
4. 当下最关键的瓶颈是什么？
循环寿命（尤其对CBRAM和ReRAM）.
