---
layout: single
title:  "Headfirst into the Linux file system"
date:   2020-12-26 10:13:25 +0100
categories: linux
header:
  image: /assets/images/file_sys.png
  teaser: /assets/images/file_sys_teaser.png

---

I created a Linux data science development environment from an old Windows 7 laptop. Here are my first steps and learnings as a Linux user. This time, it’s all about the Linux file system!
{: .text-justify}

---

If you are a Windows user, you will know inadvertently many things about the Windows file system. You know, there is the C:\ drive, there is something called Program Files, folders are separated by the backslash character, and there is the Windows Explorer (or File Explorer) that gives you the graphical user interface to interact with these files easily.
{: .text-justify}

Now, in Linux, the file system is different than what you might be used to, from Windows. Before I get to this, there is maybe a somewhat unrelated thing, but it keeps coming up, so I think I should share. Many times when you read about Linux, you will come across the term Unix. Unix is a very very old operating system. Linux was basically created originally to be a copy of the Unix operating system, so it is often called a “Unix-like” operating system. The Unix OS had a philosophy of how to organize things as an operating system, that has lived on in many other operating systems, for example in Linux. So, next time you hear Unix and Linux in the same sentence, you will know why!
{: .text-justify}

Next, I will discuss the structure and most important directories to start with. There is a LOT MORE, but I will not cover it in this blog post. As usual, there is much depth to this, so let’s go step by step. If you would like a more comprehensive summary, I suggest you read [this article](https://www.tecmint.com/linux-directory-structure-and-important-files-paths-explained/).
{: .text-justify}

The Linux file system is organized into a tree structure. This means, it starts from a root, then spreads on different levels of the hierarchy towards “branches and leaves”, if you get the analogy… 
{: .text-justify}

At the root is the... well... root folder that is indicated by a single forward slash character. At this point I should indicate that the file separator character is different in Linux (forward slash) than in Windows (backslash). 
{: .text-justify}

Other important directories under the / root:
* **/home**: the home directory for users. You would have a folder for your username under this parent directory where you can store your own documents
* **/bin**: the location for the operating system’s binary programs, for example the commonly used programs that you issue from the terminal, like cat, etc. (see my post about Linux commands) live here.
* **/etc**: configuration files and scripts of programs are here
* **/opt**: third party application software like Java etc. are stored here
{: .text-justify}

Following this short list of important folders, let’s talk about naming conventions. When you create folders and files yourself, you might want to consider a few things. Linux is case sensitive, so “folder” and “Folder” are not referring to the same. Within a file name you can use characters like minus, underscore, white space or period. There are no strict convention, but I prefer not to have white spaces in my file names, I’d rather use the underscore or minus sign to separate words. Also, I prefer using all small letters and avoid capital letters whenever I can.
{: .text-justify}

So much for the file system basics. Next time, we’ll talk about [bash shell commands and scripting](/linux/2021/01/07/bash-scripting-1.html).
{: .text-justify}

Sources:
[https://www.softwaretestinghelp.com/unix-vs-linux/](https://www.softwaretestinghelp.com/unix-vs-linux/)
[https://www.computernetworkingnotes.com/basic-linux/linux-file-system-and-naming-convention-explained.html](https://www.computernetworkingnotes.com/basic-linux/linux-file-system-and-naming-convention-explained.html)

