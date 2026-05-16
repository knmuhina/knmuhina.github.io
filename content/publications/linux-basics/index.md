---
title: 'Linux basics'

authors:
  - me

date: "2026-05-16"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.

abstract: Linux is a family of free-and-open-source Unix-like operating systems based on the Linux kernel, which was first released on 17 September 1991 by Linus Torvalds.

tags:
- Courses
featured: false

hugoblox:
  ids:
    arxiv: 1512.04133v1

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**wikipedia**](https://en.wikipedia.org/wiki/Tux)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

# Getting Started with Linux

Linux is one of the most important operating systems in modern computing. It powers servers, supercomputers, cloud platforms, embedded devices, and even smartphones. For anyone interested in programming, cybersecurity, system administration, or software development, understanding Linux is an essential skill.

## What is Linux?

Linux is an open-source Unix-like operating system kernel created by Linus Torvalds in 1991. Over time, it became the foundation for complete operating systems known as Linux distributions.

A Linux distribution combines the Linux kernel with system utilities, package managers, desktop environments, and additional software. Popular examples include Ubuntu, Debian, Fedora, and Arch Linux.

## Why Linux?

Linux has become widely used for several reasons:

* **Open-source** — anyone can study, modify, and distribute the source code.
* **Security** — Linux is known for its strong permission system and stability.
* **Performance** — it can efficiently run on both powerful servers and older hardware.
* **Flexibility** — users can customize nearly every part of the system.
* **Developer-friendly environment** — Linux provides powerful tools for programming, automation, and system administration.

Today, most web servers, cloud infrastructures, and DevOps environments rely on Linux.

## Linux Basics

The further information was primarly taken from my experience with Stepik course ["Getting Started with Linux"](https://stepik.org/course/73).

When starting with Linux, there are several core concepts every beginner should learn.

### 1. The Terminal

The terminal is a text-based interface that allows users to interact directly with the operating system.

Common commands include:

`pwd` — shows the current directory
`ls` — lists files and folders
`cd` — changes the current directory
`mkdir` — creates a new directory
`cp` — copies files
`mv` — moves or renames files
`rm` — removes files

### 2. File System Structure

Linux organizes files in a hierarchical structure:

`/` — root directory
`/home` — user files
`/etc` — configuration files
`/bin` — essential system programs
`/var` — variable data such as logs
`/usr` — user applications and libraries

### 3. Permissions

Linux uses permissions to control access to files:

* **r** — read
* **w** — write
* **x** — execute

Permissions can be changed using commands like `chmod` and `chown`.

### 4. Package Management

Software in Linux is usually installed through package managers such as:

* APT
* DNF
* Pacman

This makes installing and updating software fast and convenient.

## Final Thoughts

Learning Linux is not just about using another operating system—it is about understanding how computers work at a deeper level. Mastering Linux basics opens the door to software development, cybersecurity, cloud computing, and many other technical fields.