---
layout: post
title: "Beggar's Method"
categories: [combinatorics, number-theory]
show_updated: false
updated_on: 2018-04-29 00:00:00 +0530
---

### Problem

Find the number of integer solutions i.e. ordered pairs $$\left(x_1, x_2, \ldots , x_r \right)$$ such that

$$x_1 + x_2 + \ldots + x_r = n, \quad x_i \geq 0, x_i \in \mathbb{Z}$$
<!--end_excerpt-->

### Solution

The number of such solutions is given by

$${^{n+r-1}C_{r-1}} = \frac{\left( n+r-1 \right)!}{ n! \left( r-1 \right)!}$$
