---
title: "Configuration PWA"
weight: 4
draft: false
description: "Enable the PWA on SearchWind Site"
slug: "configuration-pwa"
tags: ["config", "docs"]
series: ["Documentation"]
series_order: 4
---

intro

## Add Parameters in tom

### Output

add
- WebAppManifest
- ServiceWorker

example:

[outputs]
    home = ["HTML", "JSON", "RSS", "WebAppManifest", "ServiceWorker"]

### App Informations

title = ""

[params]
    shortName = ""
    description = ""

### Params Description

| Name | Default | Description |
| --- | --- | --- |

## Add Images

create `logo-icons` folder
create 2 images files
- logo-icons/android-chrome-192x192.png
- logo-icons/android-chrome-512x512.png