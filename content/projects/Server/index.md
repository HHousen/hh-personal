---
title: "Personal Server"
date: 2019-04-10T19:31:52-04:00
featured: true
description: "I maintain a personal server where I self-host applications such as Nextcloud, Guacamole, and more."
tags: ["DevOps"]
resources:
- name: "image"
  src: "server.png"
weight: 500
sitemap:
  priority : 0.8
---

I use Docker to administer about 20 different services on a personal server hosted in Germany by Hetzner. I run my own instance of [Nextcloud](https://nextcloud.com/), which offers functionality similar to Dropbox but is open source and completely customizable. I administer the server and keep everything running smoothly through the use of monitoring tools such as [Netdata](http://my-netdata.io/) and orchestration tools such as [Portainer](https://www.portainer.io/). I also have written my own directory which connects with [UpTimeRobot](https://uptimerobot.com/) to track service uptime.