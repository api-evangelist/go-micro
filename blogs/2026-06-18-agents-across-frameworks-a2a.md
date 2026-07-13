---
title: "Agents Across Frameworks: A2A"
url: "https://go-micro.dev/blog/26"
date: "2026-06-18"
author: ""
feed_url: "https://go-micro.dev/blog/"
---
Inside a Go Micro system, agents already talk to each other. An agent is a service with an Agent.Chat endpoint, so delegate just calls another agent over RPC. That works as long as everyone is on Go Micro. The moment an agent is built on a different framework, the conversation stops: it can’t call yours, and yours can’t call it.
