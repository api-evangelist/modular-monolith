---
title: Scaling SignalR With a Redis Backplane
url: https://www.milanjovanovic.tech/blog/scaling-signalr-with-redis-backplane
date: '2026-03-21'
author: milan@milanjovanovic.tech (Milan Jovanović)
feed_url: https://www.milanjovanovic.tech/rss/feed.xml
---
SignalR connections are server-local. Scale out to multiple instances and messages stop reaching the right clients. Here's how the Redis backplane fixes that - and what you still need to get right.
