---
title: 一篇论文被NeurIPS 2023录用
date: '2023-09-22'
summary: Automatic Grouping for Efficient Cooperative Multi-Agent Reinforcement Learning
---

标题：[Automatic Grouping for Efficient Cooperative Multi-Agent Reinforcement Learning](https://openreview.net/forum?id=CGj72TyGJy)

摘要：Grouping is ubiquitous in natural systems and is essential for promoting efficiency in team coordination. This paper proposes a novel formulation of Group-oriented Multi-Agent Reinforcement Learning (GoMARL), which learns automatic grouping without domain knowledge for efficient cooperation. In contrast to existing approaches that attempt to directly learn the complex relationship between the joint action-values and individual utilities, we empower grouping as a bridge to model the connection between small sets of agents and encourage cooperation among them, thereby improving the learning efficiency of the whole team. In particular, we factorize the joint action-values as a combination of group-wise values, which guide agents to improve their policies in a fine-grained fashion. We present an automatic grouping mechanism to generate dynamic groups and group action-values. We further introduce a hierarchical control for policy learning that drives the agents in the same group to specialize in similar policies and possess diverse strategies for various groups. Experiments on the StarCraft II micromanagement tasks and Google Research Football scenarios verify our method's effectiveness. Extensive component studies show how grouping works and enhances performance.