---
title: Download
description: Download OpenServerless with ops CLI
weight: 70
draft: false
---
## Download and Install `ops`

🚧 PAGE UNDER CONSTRUCTION  🚧

To use OpenServerless you need to install a tool called `ops` CLI with which you can install the OpenServerless runtime.
While you typically run `ops` CLI on you computer, you can install the OpenServerless on your computer, on a (remote) Virtual Machine, and on a cluster of (remote) Virtual Machines.

### Download links

For `ops` CLI We support 64-bit versions of recent Windows, macOS and major Linux distributions.
It is available for different architectures, and in different formats.

OpenServerless can be installed with its Command Line Interface, `ops`.

To automatically install the latest version of the ops CLI you can open your terminal and type the command below:

```bash
$ curl -sL https://bit.ly/get-ops | bash
```

If instead you prefer installing the `ops` CLI manually, you can download the `ops` CLI from:

    https://github.com/apache/openserverless-cli/releases

then install it on your system, and make it available in the path.

### After the installation of the ops cli

Once installed, in the first run `ops` will tell to update the tasks
executing:

`ops -update`

This command updates the OpenServerless "tasks" (its internal logic) to the
latest version. This command should be also executed frequently, as the
tasks are continuously evolving and expanding.

`ops` will suggest when to update them (at least once a day).

You normally just need to update the tasks, but sometimes you also need
to update `ops` itself. The system will detect when it is the case and
tell you what to do.
