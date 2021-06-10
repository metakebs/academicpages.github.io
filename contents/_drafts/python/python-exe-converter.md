---
title: 'Convert Python Scripts to executable file (exe)'
date: 2021-12-31
permalink: 
tags:
  - python	

---

_This tutorial is posted for personal reference and is based on a Youtube tutorial from Tech with Tim, click [here](https://youtu.be/UZX5kH72Yx4) for more information._ 

# Advantages

- allows other machines without python or relevant packages to run you python script or project

# Steps

1. Open `cmd` with directory on 
2. `pyinstaller --onefile -w script-name.py`
   - `--onefile` compiles a single file
   - `--w`
3. pyinstaller will output the following
   - build folder and *.spec file are not required (can be deleted)
   - executable file will be located on the dist folder, needs to be transferred to root if you have dependencies

**Converting to a single folder:**

1. Download NSIS
2. Compress the project folder
3. Compile the zipped file.

# Example

