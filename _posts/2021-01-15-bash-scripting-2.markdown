---
layout: single
title:  "My first attempts at Shell scripting – 2"
date:   2021-01-15 10:13:25 +0100
categories: linux
header:
  image: /assets/images/peer_prog.jpg
  teaser: /assets/images/bash_teaser2.png

---

Now that I have a Linux workstation, it is too tempting not to learn a bit about the Bash shell. Here's a continuation of this series.
{: .text-justify}

---

I have looked already at the most basic commands and what a shell is how to open and use it on Ubuntu. Now, let’s go one step further and write some basic scripts. 
{: .text-justify}

I have to admit, I thought this post would be an easier and faster one, but it turned out that there is much more depth to writing bash shell scripts than I originally thought. That’s not a problem though, but it leads me to split this topic into multiple posts. I will start here with only the very basics, that is, a hello world script.
{: .text-justify}

If you are also coming from a Windows-only background, you would understand the key concept of writing shell scripts from the analogies of Windows batch files. The batch files in Windows are basically text files saved with a .bat extension that run a series of commands. The term scripting defines the process of automating certain repetitive tasks by writing commands step by step that will be executed by a program. Shell scripting means writing a series of shell commands that will be executed – you’ve probably guessed – by the shell (in our case, Bash).
{: .text-justify}

You need to write these commands in a text editor and save the file with the .sh extension, or simply without an extension at all. The .sh tag is just helpful so that when you check the contents of your folder and you see a random file with the extension .sh, you would know what it actually is. After the file is created, you can execute it using Terminal.
{: .text-justify}

We will create the classic “Hello World!” solution, which will simply write the text Hello World! onto the terminal window. First, open up the Text Editor and start typing.
{: .text-justify}

All Bash shell scripts you write need to begin with:
{: .text-justify}

```console
#!/bin/bash
```

This is called a “shebang”. It just means that the command will be executed by the Bash shell. Following that, in a new line you can start writing your commands. It is also generally a good practice to comment your scripts, which you can do with the hash (\#) character. We will use the echo command, that displays a line of text. So the whole script would look as follows:
{: .text-justify}

```console
#!/bin/bash 
# This is my first shell script, displaying a line of text
echo “Hello World!”
```

Now, you can save the file. I created a destination folder to save my scripts to: “/home/myusername/Documents/learning/bash\_scripting”. When saving to your destination directory, give the file the name “hello\_world” (or “hello_world.sh”, up to you). 
{: .text-justify}

At this point, you have one additional step. I will let you know what to do, and we will discuss next time why you had to do it. In the Files browser, right click on your file that you just saved, and go to Properties. In the pop-up window, click the Permissions tab and make sure to check and have a tick mark next to the option called “Allow executing file as program”. 
{: .text-justify}

Now, you just have to run the file from Terminal to see if you did a good job. If you open a Terminal from the folder you just saved your script to (by right clicking and selecting Open in Terminal), and type ./hello_world, (which is the command to execute the script), you just need to press Enter and see your first script coming to life and executing. 
{: .text-justify}

You might also ask why did you need the dot and the forward slash character before your script name… We will cover that as well, next time, in my next blog post where we continue this topic.
{: .text-justify}

Sources:
[https://linuxcommand.org/lc3_wss0010.php](https://linuxcommand.org/lc3_wss0010.php)
[https://linuxconfig.org/bash-scripting-tutorial-for-beginners](https://linuxconfig.org/bash-scripting-tutorial-for-beginners)


