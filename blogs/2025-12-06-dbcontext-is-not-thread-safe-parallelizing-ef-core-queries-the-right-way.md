---
title: 'DbContext is Not Thread-Safe: Parallelizing EF Core Queries the Right Way'
url: https://www.milanjovanovic.tech/blog/dbcontext-is-not-thread-safe-parallelizing-ef-core-queries-the-right-way
date: '2025-12-06'
author: milan@milanjovanovic.tech (Milan Jovanović)
feed_url: https://www.milanjovanovic.tech/rss/feed.xml
---
Learn how to safely parallelize EF Core queries to improve performance by using IDbContextFactory to create isolated contexts, avoiding the thread-safety exceptions caused by sharing a single DbContext instance.
