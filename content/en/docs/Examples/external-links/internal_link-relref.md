---
title: "internal link with relref"
linkTitle: "internal link with relref"
externalLinkRelref: "about"
externalLinkTitle: "internal link to about page using relref"
type: docs
date: 2020-11-27T00:00:00+01:00
draft: false
weight: 999
description: >
  Internal link to following page: [about]({{% relref "about" %}} "internal link")
---

[about]({{< relref "about" >}} "internal link")
