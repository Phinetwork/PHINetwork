---
description: >-
  We are working on simplifying the process of setting up a Node on PHI Smart
  Chain .
---

# 📶 Run A Node

## Before You Start

PHI Smart Chain is incredibly light on its hardware requirements, and you don't need a super high-end machine to set up and run your full node. These requirements might change as the network usage increases. So, as a node manager, it's worth to keep yourself updated with the latest requirements.

This tutorial only supports **Ubuntu Linux**. If you are trying to setup your node on **Windows**, we strongly recommend you to use our Node Management Software instead.

* VPS/AWS vCPU x4 or Equivalent
* 8GB DDR RAM
* 500GB HD or SSD
* Windows 7 or Superior
* OS: Ubuntu 18.04+

{% hint style="info" %}
The scripts haven't been tested on MacOS, and that's the reason for it not being listed as officially supported, but - in theory - you should be able to run a node on a compatible machine running MacOS Catalina or newer.
{% endhint %}

### Deployment Environment Considerations

This tutorial assumes you are running a clear and fresh image of **Ubuntu Linux 18.04 or newer**, on a hosted **Virtualized Private Server (VPS)**, and are accessing it via **SSH**.

You will need both ports **30303** and **8545** open for **TPC** and **UDP**.

If you are using a different Operational System or flavor of Linux, the commands might be different and you will have to adjust.

We strongly recommend you to use a fresh instance of Ubuntu, as old files, programs, and folders might affect the environment variables, making this tutorial not applicable or efficient.

## Installing Packages

Before you fire up your node, you will need to make sure you have all the packages below properly installed, and we have links to their websites where you will be able to find further instructions on how to do so. We also recommend you to install them in the order presented below.

* [Golang](https://go.dev/)
* [Geth](https://geth.ethereum.org/) \* Optional, recommended
* [Screen](https://linuxhint.com/screen-linux/) \* Optional, recommended
* [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Please verify that all packages have been installed properly before advancing to the next step.

You Will Find PHI Smart Chain Genesis File Here To Start Up Your Node

[https://github.com/Phinetwork/phi-chain/blob/main/genesis.json](https://github.com/Phinetwork/phi-chain/blob/main/genesis.json)
