---
layout: post
title: How to setup Devilbox
date: 2020-11-04
tag: linux, command line, webdev, lamp
description: On this article we talk about installing and configuring devilbox
author: Marco Monteiro
categories: ["devilbox", "lamp", "docker", "docker-compose"]
---

Installing and configuring your Devilbox stack is quite easy. But first what is devilbox?

Here's the video version:

<iframe width="100%" height="450" src="https://www.youtube.com/embed/PuOoxWxU0IM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The Devilbox is a modern dockerized LAMP and MEAN stack for local development on Linux, MacOS and Windows.

It allows you to have an unlimited number of projects ready without having to install any external software and without having to configure any virtual hosts. As well as providing a very flexible development stack that you can run offline. (Internet is only required to initially pull docker container).

The only thing you will have to do is to create a new directory on the filesystem and your virtual host is ready to be served with your custom domain.


![devilbox.png](https://raw.githubusercontent.com/devilbox/artwork/master/submissions_diagrams/cytopia/01/png/architecture-full.png)



Here's the steps we take on the video to do everything:

```
git clone https://github.com/cytopia/devilbox
cp env-example .env
sudo docker-compose up --build -d
```

Access your http://localhost and then all you need to do is create your project folders.

That's it!

* Blog: [blog.marcomonteiro.net](https://blog.marcomonteiro.net/)
* Website: [marcomonteiro.net](https://marcomonteiro.net/)
* Patreon: [patreon.com/tilthings](https://www.patreon.com/tilthings)
* Youtube: [Youtube Channel](https://www.youtube.com/channel/UC9HQjernJPHN-RoKMwtYQ4w)