---
title: "Beggar's Method"
date: 2018-04-29T13:59:09+05:30
draft: false
aliases: []
description: ''
slug: 'beggars-method'
tags: [combinatorics, number-theory]
type: post
math: true
weight: 0
---

### Problem

Find the number of integer solutions i.e. ordered pairs $\left(x_1, x_2, \ldots , x_r \right)$ such that

$$x_1 + x_2 + \ldots + x_r = n, \quad x_i \geq 0, x_i \in \mathbb{Z}$$

### Solution

The number of such solutions is given by

$${^{n+r-1}C_{r-1}} = \frac{\left( n+r-1 \right)!}{ n! \left( r-1 \right)!}$$