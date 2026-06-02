---
title: What Invariants Are (and Why a Domain Model Is the Best Place to Enforce Them)
url: https://www.milanjovanovic.tech/blog/what-invariants-are-and-why-a-domain-model-is-the-best-place-to-enforce-them
date: '2026-05-02'
author: milan@milanjovanovic.tech (Milan Jovanović)
feed_url: https://www.milanjovanovic.tech/rss/feed.xml
---
Most 'DDD-ish' code I review enforces business rules everywhere except where it should: in the model itself. The same rule ends up duplicated across handlers, validators, and controllers, and each copy drifts a little over time. Here's how I think about invariants, and why an always-valid domain model is the cleanest way to enforce them.
