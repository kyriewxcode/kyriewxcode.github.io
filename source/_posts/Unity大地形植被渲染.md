---
title: Unity大地形植被渲染（一）
date: 2022-06-03 17:59:00
tags:
- Unity
- GameEngine
- Terrain
categories:
- GameEngine
---

因为Unity Terrain自带的Detail和Tree绘制性能不好，手机性能吃不消，所以我们准备预研出一套基于Terrain中草和树信息，自己进行绘制的工具。这样的好处是美术仍然能够在原来的Terrain上用笔刷刷草和树，而通过自己管理绘制流程则可以大幅度提升性能。
