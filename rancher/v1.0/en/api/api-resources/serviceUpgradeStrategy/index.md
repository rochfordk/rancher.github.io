---
title: API
layout: rancher-default-v1.0
version: v1.0
lang: en
---

## serviceUpgradeStrategy





### Resource Fields

Field | Type | Required | Default | Description
---|---|---|---|---
batchSize | int | false | 1 | The batch size to upgrade a service (i.e. how many containers to launch at a time)
intervalMillis | int | false | 2000 | The number of milliseconds between upgrading

