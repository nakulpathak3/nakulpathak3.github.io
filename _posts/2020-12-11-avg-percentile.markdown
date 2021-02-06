---
layout: post
title: "Average or Percentile?"
date: 2020-12-11 17:48:02 -0500
categories: sre
---

![Request Time Example](/assets/request-times.png)

100 Requests - 99 take 1s and 1 takes 100s.

Average = 199 / 100 = ~2s

Does an "average" request take 2s?

Median (or p50) = p75 = p90 = p99 = 1s

Only p100 = 100s :)

This is why watching for "average" time is a bad idea. Prefer percentiles.
