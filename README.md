<div align="center">

# Activity Art

> *「If War Can Be Modeled, Everything Can」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Status: WIP](https://img.shields.io/badge/Status-WIP-orange.svg)]()

<br>

**战争是人类最复杂的集体活动之一。**

**但《孙子兵法》证明了一件事：再复杂的活动，底层也有结构。**

**既然战争都能被建模，日常活动自然也能。**

[问题](#问题) · [核心思想](#核心思想) · [它是什么](#它是什么) · [定位与局限](#定位与局限)

</div>

---

## 问题

OpenClaw 这类 agent 框架反复暴露出同一个问题：

长任务执行到一半，agent 的上下文窗口刷新，之前的决策依据就丢了

换一个 agent 接手，新 agent 没有共享的活动状态，对进度和卡点一无所知

任务中断几天或几个月后，连你自己也忘了做到哪了

现有方案要么人肉复述，要么翻对话日志——但日志是碎片，不是活动本身。

因为没有一个通用的模型来描述“活动”。

---

## 核心思想

活动可以被建模。

中国古典著作中已有大量分散的洞察：《史记》《周易》《孙子兵法》《鬼谷子》《管子》《大学》等。

但从未被提炼成一个通用的 JSON Schema。

Activity Art 要做的事，正是填补这个空白。

---

## 它是什么

Activity Art 是一套描述“活动”（比如一个开发项目、一次情报收集、一次文章撰写）的通用 JSON Schema。

它定义一份 activity.json，用于记录一个活动的完整状态。
不依赖任何特定框架或执行引擎。

---

## 定位与局限

### 定位

Activity Art 定义描述“活动”的 JSON Schema。

它不关心如何执行、不规定怎么推进、不绑定任何框架或引擎。

### 局限

这只是作者基于对多部古籍的理解所构建的活动建模，不代表唯一真理，也不覆盖所有文化视角。

---

<div align="center">

**形存则活动可续，式在则后人可循。**

MIT License © SpaceRelax

</div>
