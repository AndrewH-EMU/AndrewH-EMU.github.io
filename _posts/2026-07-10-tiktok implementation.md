---
layout: post
title: "Week 4: TikTok Implementation"
date: 2026-07-10
---

With access secured to our top three API platforms, I moved into the development phase and started the actual implementation of the TikTok API within Lucidity's GitHub. My goal is to have the TikTok integration finished end to end, from data ingestion in a local Airbyte environment using sandbox API calls to a normalized table in ClickHouse. The time I spent understanding the groundwork paid off, since I now have a solid understanding of how data flows through the system. The biggest challenge I faced was the codebase itself, since I'm building something that inserts right into the middle of an existing pipeline. It's not something I can create in isolation, so fully understanding the flow of data from start to finish, the current schemas and organization in use, and how to test and verify my outputs is the main focus and challenge of working on a task like this.
