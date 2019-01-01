---
layout: tabs
title: How to Contribute ?
author: Sujith Abdul Rahim
date: 01/Jan/2019
---

Thanks for reaching out our website. Knowledge should be shared across to everyone no matter what, that's how we learn - unlearn and relearn. Your contribution is very essential for us to keep this website with some good quality contents and we are really excited to have you as a contributor. 

Have any questions ? please mail us, we are happy to respond.

## **Table of Contents**

* [Overview](#overview)
* [Contributing](#contributing)
* [Setting up your development environment](#setting-up-your-development-environment)
    * [Prerequisites](#prerequisites)
        * [Docker](#docker)
    * [Build the environment](#build-the-environment)
        * [Fork and clone the repo](#fork-and-clone-the-sudodevops-repo)
        * [Running the Jekyll environment](#running-the-jekyll-environment)
        * [Access the contents](#access-the-contents)

## **Overview**

This is Me , **Sujith Abdul Rahim**. I built this website to mainly focus on exploring DevOps related topics as an educational purpose. I believe the contents in here would be a kick start for anyone who wish to explore DevOps in depth. And if you are satisfied with the materials in here, please do encourage us by providing a `star` icon in [**GitHub**](https://github.com/sujiar37/SudoDevOps).

## **Contributing**

- We encourage more on technical documents related with DevOps such as providing a Basics to Advanced walkthrough of different automation tools, other trends etc.
- Contribution can be done either through by mailing us / a pull request.
- All code submissions are done through pull requests against the `gh-pages` branch.
- We are excited to announce what you are good at, hence it's mandatory to give a introductory about yourself which would further publish in this website authors page with the topics that you own.
- Last but least, keep connected to everyone and help peoples by clearing their doubts related with the topics that you had publish.


## **Setting up your development environment**

### **Prerequisites**

#### **Docker**

For macOS and Windows, we recommend [Docker for Mac](https://www.docker.com/docker-mac) and [Docker for Windows](https://www.docker.com/docker-windows)
respectively.

For Linux platforms, refer to the following from Docker:

**Fedora**

> <https://docs.docker.com/engine/installation/linux/docker-ce/fedora/>

**CentOS**

> <https://docs.docker.com/engine/installation/linux/docker-ce/centos/>

**Ubuntu**

> <https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/>

**Debian**

> <https://docs.docker.com/engine/installation/linux/docker-ce/debian/>

**Arch**

> <https://wiki.archlinux.org/index.php/Docker>


### **Build the environment**

#### **Fork and clone the SudoDevOps repo**

If you have not done so already, you'll need to fork our repo on [**GitHub**](https://github.com/sujiar37/SudoDevOps). For more on how to do this, see [**Fork a Repo**](https://help.github.com/articles/fork-a-repo/).

#### **Running the Jekyll environment**

Once docker has been installed, start the development containers by running the following,

```bash
$ cd <inside your repo>
$ sudo docker container run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000  -it jekyll/jekyll  jekyll serve --watch
```

The output will be more likely this,

```bash
$ sudo docker container run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000  -it jekyll/jekyll  jekyll serve --watch

ruby 2.5.3p105 (2018-10-18 revision 65156) [x86_64-linux-musl]
Configuration file: /srv/jekyll/_config.yml
            Source: /srv/jekyll
       Destination: /srv/jekyll/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
                    done in 0.455 seconds.
 Auto-regeneration: enabled for '/srv/jekyll'
    Server address: http://0.0.0.0:4000/
  Server running... press ctrl-c to stop.

```

#### **Access the contents**

Finally, access your development environment using <http://localhost:4000>





