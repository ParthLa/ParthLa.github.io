---
layout: page
title: Playing Notakto with Reinforcement Learning
description: How to train AlphaGo Zero using Reinforcement Learning to win Notakto?
# img: assets/img/model.webp
importance: 3
category: Research
---

<p align="justify"> Reinforcement learning has achieved great success in learning strategies for games with minimal supervision. Here we consider a specific simple combinatorial game called notakto, in which players cover squares on a tic-tac-toe board until one of them loses by finishing a whole row, column, or diagonal. We introduce optimal strategies for this game played on small boards, but larger boards have proven difficult to analyze mathematically. We set out to use reinforcement learning to help give insight into optimal strategies for larger boards. Surprisingly, we found that, despite the simplicity of the game, AlphaGo Zero struggled to learn an optimal strategy, even though we know that they exist. We developed two ways to accelerate AlphaGo Zero’s learning on this problem: one is a targeted sampling strategy that biases towards states that are likely to appear in competent play, and the other is to set the threshold for updating a model based on statistics in the training data. Both techniques make AlphaGo Zero converge faster on notakto, but they are specific to this game and still do not seem to find a near-optimal strategy. We conjecture that this difficulty may show some fundamental limitations of reinforcement learning on combinatorial games that need to be further investigated. </p>

<p align="justify"> The project implementation can be found <a href="https://github.com/ParthLa/Training-Notaktoe-using-Reinforcement-Learning"> here </a>. </p>
