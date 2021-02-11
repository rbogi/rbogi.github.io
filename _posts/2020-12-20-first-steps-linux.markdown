---
layout: single
title:  "My first steps as a Linux user"
date:   2020-12-20 14:23:55 +0100
categories: linux
header:
  image: /assets/images/programmer.png
  teaser: /assets/images/bash_terminal.png

---

I decided to turn my old and unused Windows laptop into a Linux data science sandbox. Here's how it went.
{: .text-justify}

---

Now that I have my shiny new Ubuntu laptop (works pretty fast and smooth for an old device by the way), I started by listing the software I want to start using on it, to build my machine learning development environment. You know, Git, Anaconda, PyCharm... the basics, really.
{: .text-justify}

The [Git documentation](https://github.com/git-guides/install-git) tells you right away, “Fun fact: Git was originally developed to version the Linux operating system! So, it only makes sense that it is easy to configure to run on Linux.” So far, so good. However, the next lines contain somewhat of a confusion. First of all, you install git using the command line, or terminal as it is called on Linux, which is great. But, you use a command called “sudo”, also you have a package manager which might differ based on your flavor of Linux. Confused yet?
{: .text-justify}

So, to understand these things, here is a little bit of explanation:
{: .text-justify}

Whenever you read some installation documentation, you will find instructions based on your Linux distribution. Often, you will just see instructions for “Debian”. Where is Ubuntu, you might wonder? Well, Ubuntu is based on Debian, so that is your short answer. You will also notice that you install things from the Terminal using the apt command. Apt is the package manager software that you can use from your command line interface to manage and install software packages on Debian and it’s derivative Linux distributions (i.e. Ubuntu). So you install, upgrade, remove etc. your software easily from the Terminal with apt. 
{: .text-justify}

The next thing is the sudo command that you can use in Terminal operations. You can remember it as “**S**uper**U**ser **DO**”, and what it does is it lets you – to use a familiar Windows analogy – work as an administrator. For installing software or other operations, you will find that the operating system restricts user access, to prevent any wrong doing. As your own superuser though, you would, from time to time, want to act with these elevated privileges. This is what sudo is for. You will need to supply your credentials also for this to work. By the way, in the Linux world the administrator is called “root” user. It's important to use the rigth terminology now that I am a root user :)
{: .text-justify}

So, here are the first lessons learned as a new Linux user. Go install some things and have fun!
{: .text-justify}

Sources:
[https://ubuntu.com/server/docs/package-management](https://ubuntu.com/server/docs/package-management)
[http://manpages.ubuntu.com/manpages/trusty/man8/sudo_root.8.html](http://manpages.ubuntu.com/manpages/trusty/man8/sudo_root.8.html)

