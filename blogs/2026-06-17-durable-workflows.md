---
title: "Durable Workflows"
url: "https://go-micro.dev/blog/24"
date: "2026-06-17"
author: ""
feed_url: "https://go-micro.dev/blog/"
---
A workflow that calls real services is rarely instant and rarely side-effect-free. It reserves inventory at step one, charges a card at step two, sends a confirmation at step three. Each of those changes the world. So when the process dies between step two and step three — a deploy, an OOM, a node going away — you can’t just run it again from the top: that reserves twice and charges twice. And if the workflow was triggered by an event with no human watching, nobody noticed it died at all.
