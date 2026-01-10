---
title: "vibe coding的一些碎碎念"
date: 2026-01-10T11:31:32+08:00
draft: false
tags: ["开发"]
categories: ["杂记"]
author: "L.Tang"
ShowToc: true
TocOpen: false
---

新年新气象，拖延症晚期终于开始vibe coding做自己喜欢的app了，cc太厉害了，不能再找借口说我不会Swift不会UI了otz

第一次体验到了claude的好，见到app跑起来可太快乐了，不过也发现并学到了很多以前没有考虑到的问题，简单的记录一下

- google api调用有免费额度，一个人用没问题，用爱发电要哭的（开发者账号都还没搞就想东想西了
- 数据合规问题。osm这类众包的数据源质量比google差太多，自建数据库不现实，google也不允许pre-fetch或者store，只能后续建立temporarily cache的机制，优化api调用
- UI是门大学问，还有的学。尤其是我还不清楚我想要的界面长什么样，但我知道丑丑的界面是什么样的时候

最后感叹一下，第一步果然是最难的，开始之后就觉得也没什么啊，为什么我之前磨磨叽叽的。迈出了建文件夹的第一步，不过一周demo（虽然UI还是丑丑的）已经能用起来了