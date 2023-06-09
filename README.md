# wordpress-kit (WIP)

A WordPress kit for quickly constructing a website on your server.

This kit can automatically compile, deploy and configure WordPress with a nice method.

---

- [wordpress-kit (WIP)](#wordpress-kit-wip)
  - [Pre-work](#pre-work)
  - [Configuring](#configuring)
  - [Compiling](#compiling)
  - [Deploying](#deploying)
    - [1. To localhost](#1-to-localhost)
    - [2. To docker](#2-to-docker)
  - [Use directly](#use-directly)
  - [Try your website](#try-your-website)

---

## Pre-work

Install basic packages:

```console
sudo apt install bison re2c pkg-config libxml2-dev libssl-dev \ 
 libsqlite3-dev  libcurl4-openssl-dev libpng-dev libwebp-dev libjpeg-dev \
 libfreetype-dev libonig-dev libzip-dev
```

And pull this repo. Use SSH to pull repo is recommended.

```console
git clone --recurse-submodules \
 ssh://git@ssh.github.com:443/Hotakus/wordpress-kit.git
```

If the submodules' folder is empty, you can run:

```console
git submodule update --init --recursive --depth 1
```

---

## Configuring

Opening the file "config.json" in root folder,

---

## Compiling

```console
sudo apt install build-essential cmake 
```

ads

---

## Deploying

This project support localhost and docker(recommended).

```console
sudo apt install python3 python3-pip
```

If you had already installed anaconda, you can ignore command above.

### 1. To localhost

If your host is new and pure, directly deploying project to your localhost is most easy and fast, otherwise not recommended, looking 2.

### 2. To docker

If your localhost is mess, I recommend that you deploy project to docker, otherwise the project maybe don't work or mess up your environment of localhost. even if localhost is pure and new, I still recommend using this method to deploy.

```console
sudo apt install docker.io
```

---

## Use directly

download a release of the project, and use it.

---

## Try your website

kkk

---
