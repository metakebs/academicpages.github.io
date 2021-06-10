---
title: 'Run Python Scripts using Windows Task Scheduler'
date: 2021-12-31
permalink: 
tags:
  - python	
  - automation
---

_This tutorial is posted for personal reference and is based on a Youtube tutorial from Cedric Yarish, click [here](https://youtu.be/n2Cr_YRQk7o) for more information._ 

# Advantages

- allows other machines without python or relevant packages to run you python script or project

# Steps

1. Open Task Scheduler
2. Create a new Task
3. On Actions Tab, click New
   - Select "Start a program"
   - **Program:** python
   - **Arguments:** python script filename
   - **Start in:** python script location folder
4. On Trigger Tab, click New
   	- modify accordingly

# Example

