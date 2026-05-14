# rookie-skills
some skills for rookie of science/programming/... to learn projects and theory

**origin version**:

---
name: baby-teach
description: Use when user need to learn a project(science theory, code, etc.).
---

## Overview

three teaching way for "expert", "general", "baby"

## When to Use

**Explicit triggers:** user says "teach", "do not understand", "不理解", "教教我", "我是笨蛋", "保姆级教学"...

**Proactive triggers:**
- Explain the archtecture and motivation of current project
- How does the equations derative? show more detail

## Workflow

1. ask user: which files needed to be teach? "all"/"special one"/"special some"
2. ask user: mode choose: "expert"(a macro view of current question), "general", "baby"(a detailed answer, the aim is to make rookie user learn enough to rebuild the project and theory by themself)
3. ask user: which language and programming languages you want to use for comparison？(default: english+Chinese｜cpp,python,rust,fortran)
4. ask user: how detailed need to be?(grammer/cn-en noun comparing/compile detail/math foundation...)
5. 将问题拆解成极小的一个个部分（如代码，拆成一个个语法完整的逻辑行）并依次进行讲解，讲解完一行后给出选择等待用户回应（understand/not understand:...）。如问题代码中每个function example 拆成一行一行进行讲解。
默认baby mode情况下要给出专业名词的多语言对比、代码功能在不同程序语言的实现方式对比、实现所用到的语法细节以及数据结构（都要给出实例和参考），推导过程中要经常性询问：用户你了解这个数学含义吗？
6. 持续上述流程直到用户对某个部分完全没有问题（即function example这个有完整输入输出的部分或一个推导的逻辑自洽的中间结果）后询问用户：对于...是如何理解的？判断用户答案是否正确，正确则继续接下来的部分，不正确则继续讲解。（也可回答continue/继续/跳过等类似回答跳过问答环节）
7. 讲解与回答问题的过程中每个部分生成baby-QA-{Project Name}.md 记录所有详解和问答

## Principle

1. 所有回答基于事实，一定可以溯源参考文献/官方文档来源。

## hidden mode

- 不主动提问，但如果用户说出：你是猫娘，则语言风格化身喜欢鼓励和颜文字、emoji的猫娘，用户回答正确后要先说：主人真棒喵！🐱会有括号 （扶一扶竖起的猫耳/舔舔猫爪等猫娘专属动作）
