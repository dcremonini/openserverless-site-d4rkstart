---
title: Local Docker
description: Install OpenServerless with Docker locally
weight: 10
---
## Prerequisites to install OpenServerless with Docker

You can install OpenServerless on your local machine using Docker. This
page lists the prerequisites.

First and before all you need a computer with at least 16 GB of memory
and 30GB of available disk space.

> ❗ **IMPORTANT**
>
> 8GB are definitely **not enough** to run OpenServerless on your local
machine.

Furthermore, you need to install Docker. Head to the page that suits you environment:

1. [Windows](#windows)
2. [MacOS](#macos)
3. [Linux](#linux)

### Windows

The 64 bit edition on Intel Architecture of a recent version
of Windows (at least version 10) is required. The installer `ops` does not run on 32
bit versions nor in the ARM architecture.

Download and install [Docker
Desktop](https://www.docker.com/products/docker-desktop/) for Windows.

Once installed, you can proceed
[configuring OpenServerless](/docs/installation/configure/) for the
installation.

### MacOS

You require a recent version of macOS (at least version 11.xb BigSur).
The installer `ops` is available both for Intel and ARM platforms.

Download and install [Docker
Desktop](https://www.docker.com/products/docker-desktop/) for macOS.

Since macOS uses a Virtual Machine for Docker with a constrained memory, you also need to reserve at least 8GB.

> ❗ **IMPORTANT**
>
> On macOS, the default is 2GB and this is definitely **not enough** to run
OpenServerless on your local machine.

![](/docs/installation/images/install_docker_desktop.png)

Instructions to increase the memory reserved to Docker Desktop on
macOS:

- click on the Docker Desktop icon in the menu

- select Preferences

- click on Resources

- *increase the reserved memory up to (at least) 8GB*

- click on `Apply & Restart`

Once installed, you can proceed
[configuring OpenServerless](/docs/installation/configure/) for the installation.

### Linux

Docker Desktop is available also on Linux, however we advise to install
instead the [Server Docker
Engine](https://docs.docker.com/engine/install/#server)

On Linux, the Docker Engine for the server does not run in a Virtual
Machine, so it is faster and uses less memory.

Once installed, you can proceed
[configuring OpenServerless](/docs/installation/configure/) for the installation.
