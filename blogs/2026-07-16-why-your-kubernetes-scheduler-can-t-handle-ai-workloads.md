---
title: "Why your Kubernetes scheduler can't handle AI workloads"
url: "https://lambda.ai/blog/why-your-kubernetes-scheduler-cant-handle-ai-workloads"
date: "2026-07-16"
author: "Cody Brownstein"
feed_url: "https://lambda.ai/blog/rss.xml"
---
Imagine this scenario: You have a distributed training job with 16 worker pods, each requesting 1 GPU. 4 GPUs are currently available. The default Kubernetes scheduler ( kube-scheduler ) may schedule those 4 pods while the remaining 12 stay pending.
