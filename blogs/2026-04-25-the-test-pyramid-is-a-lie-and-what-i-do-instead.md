---
title: The Test Pyramid Is a Lie (and What I Do Instead)
url: https://www.milanjovanovic.tech/blog/the-test-pyramid-is-a-lie-and-what-i-do-instead
date: '2026-04-25'
author: milan@milanjovanovic.tech (Milan Jovanović)
feed_url: https://www.milanjovanovic.tech/rss/feed.xml
---
The test pyramid made sense when integration tests meant a shared database server and a 20-minute build. It doesn't match how I build .NET systems in 2026. Most of my real bugs live at the seams, and unit tests don't catch any of them. Here's the testing shape I actually ship with.
