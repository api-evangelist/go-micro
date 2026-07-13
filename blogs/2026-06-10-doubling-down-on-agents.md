---
title: "Doubling Down on Agents"
url: "https://go-micro.dev/blog/20"
date: "2026-06-10"
author: ""
feed_url: "https://go-micro.dev/blog/"
---
Go Micro made microservices easy by having an opinion. You called micro.New, and it composed the pieces a service needs — service discovery, RPC, pub/sub, config, storage — behind one interface, with defaults that worked out of the box. You could test an endpoint in minutes, and when you needed to, you swapped any piece: mDNS for etcd, HTTP for gRPC, in-memory for Postgres. Opinionated, batteries-included, and pluggable. That combination is why people used it.
