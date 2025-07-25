---
permalink: /:year-:month-:day/:title
layout: post
title:  "关于路径规划和微分博弈的一些总结"
author: "Lei Lie"
categories: Study
tag: public
---

在这里总结了**路径规划**和**微分博弈**两者各自的共性问题。写在这里，防止自己忘记。

# 路径规划
路径规划共分为三个步骤：

1. 建立研究对象的运动模型；
2. 根据具体问题构造约束模型；
3. 针对此种约束优化问题，选用合适的最优化方法求解。

# 微分博弈
微分博弈共分为四个步骤：

1. 利用微分方程描述研究对象的运动过程；
2. 针对具体问题提出合适的约束条件，让问题更加能够反映现实；
3. 依据极大极小值原理（或其他准则，例如Nash均衡/Stackberg均衡）构造目标函数；
4. 利用数值方法（例如遗传算法）或解析方法（求解HJB方程）求解。