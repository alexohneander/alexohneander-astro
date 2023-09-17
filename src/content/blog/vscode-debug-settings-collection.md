---
author: Alex Wellnitz
pubDatetime: 2023-17-09T12:20:27+02:00
title: VSCode debug settings Collection
postSlug: vscode-debug-settings-collection.md
featured: true
draft: true
tags:
  - vscode
  - debug
  - development
ogImage: ""
description: In this post, we will show you how to create a MySQL server backup using Kubernetes CronJobs.
---

### Go VSCode debugging
**launch.json:**
```json
{
    "version": "0.2.0",
    "configurations": [
        {
            "name": "Debug Package",
            "type": "go",
            "request": "launch",
            "mode": "debug",
            "program": "${workspaceRoot}"
        }
    ]
}
```
