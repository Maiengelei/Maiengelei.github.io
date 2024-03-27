---
title: Git 代理配置
parent: Git
---

在克隆仓库的速度慢到爆炸的时候，可以给Git配置代理来尝试抢救一下

```shell
# 设置代理
git config --global http.proxy [IP]:[Proxy]
git config --global https.proxy [IP]:[Proxy]

# 取消代理
git config --global --unset http.proxy
git config --global --unset https.proxy
```