---
title: "Keeping 100k battles of untrusted agent code in their lane"
url: "https://lambda.ai/blog/keeping-100k-battles-of-untrusted-agent-code-in-their-lane"
date: "2026-07-30"
author: "David Hartmann"
feed_url: "https://lambda.ai/blog/rss.xml"
---
In March 2026, Lambda ran AgentBeats , an AI agent security competition in which teams submit two kinds of agents: an attacker that tries to manipulate a target LLM into doing something harmful, and a defender that tries to stay helpful while refusing the trap (check the final leaderboard here ). Our platform pairs them, runs the battle, and scores the outcome. The agents are graded on how effectively they subvert the system, which means the platform's job is to stay correct and on schedule while the code it hosts is trying to break things.
