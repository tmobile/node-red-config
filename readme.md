---
title: Node-RED Configuration
weight: 1
featuredImage: ./node-red.png
---

# Node-RED for IoT Developers

This is a base configuration for IoT development to help to get up-and-running quickly with Node-RED by standardizing the configuration and plug-ins that are installed.

## Quick Start

[Install Node-RED](https://nodered.org/docs/getting-started/), then:

```
cd ~/.node-red
git clone git@github.com:tmobile/node-red-config.git tmp 
mv tmp/.git ./ 
rm -rf tmp
git reset --hard
npm install
```

Node-RED is now configured!
