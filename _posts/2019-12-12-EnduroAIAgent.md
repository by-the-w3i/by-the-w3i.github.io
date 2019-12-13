---
layout:     post
title:      "Atari Game -- Enduro AI Agent"
subtitle:   "A Reinforcement Learning (DQN) based AI agent"
author:     "bythew3i"
header-img: "img/post/20191212/bg.png"
tags:
    - AI
    - RL
    - Deep Learning
    - CNN
    - Tensorflow
    - Keras
---

> During the 2019 Thanksgiving break, I trained a DQN based agent which can play Enduro atari game. 

### Game Rule
The number of cars you must pass is posted at the beginning of each day in the lower right corner of your instrument panel (200 on the first day, 300 on subsequent days). Each time you pass a car, this meter counts off by one. When you pass the required number of cars, green flags appear. But keep going. All additional kilometres are added to your total. You'll move on to the next day when the present day ends. If you don't pass the required number of cars by daybreak, the game ends.

### Requirements
tensorflow==1.14.0
numpy==1.16.4
gym==0.15.4
keras-rl
matplotlib



### Results
After 1.5 hours training, I get these results:
<img src="/img/post/20191212/episode_reward_500000.png">
<img src="/img/post/20191212/episode_steps_500000.png">


After 10 hours training, I get these results:
<img src="/img/post/20191212/episode_reward_4000000.png">
<img src="/img/post/20191212/episode_steps_4000000.png">



#### Demo
<iframe src="https://www.youtube.com/embed/qv9AVpAmpJI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
---