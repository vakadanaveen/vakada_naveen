---
layout: page
title: LongAudio-RAG
description: Event-Grounded QA over Multi-Hour Audio using Retrieval-Augmented Generation
img: assets/img/1.jpg
importance: 1
category: research
related_publications: true
---

Long-duration audio is increasingly common in industrial and consumer settings, yet reviewing multi-hour recordings is impractical. **LongAudio-RAG (LA-RAG)** is a hybrid framework that grounds Large Language Model outputs in retrieved, timestamped acoustic event detections rather than raw audio.

Multi-hour audio streams are converted into structured event records stored in an SQL database. At inference time, the system:
- Resolves natural-language time references
- Classifies user intent
- Retrieves only the relevant acoustic events
- Generates answers grounded in constrained evidence

This work addresses the gap between long-form audio understanding and practical QA systems, avoiding the context-length limitations of end-to-end audio LLMs.

**Status:** arXiv preprint (arXiv:2602.14612), 2026  
**Authors:** Naveen Vakada, Kartik Hegde, Arvind Krishna Sridhar, Yinyi Guo, Erik Visser
