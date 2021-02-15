---
layout: single
title:  "My first attempts at Shell scripting – 1"
date:   2021-01-07 10:13:25 +0100
categories: linux
header:
  image: /assets/images/code.jpg
  teaser: /assets/images/script_teaser.png

---

I personally think that today a data scientist (especially a junior one like myself) can get by without the knowledge of shell scripting. But, now that I have a Linux workstation, it is too tempting not to learn a bit about the Bash shell.
{: .text-justify}

---

I will start by examining some basic shell commands and then in a later blog post, see about shell scripts.
{: .text-justify}

Now, about the Bash shell. Generally, a shell is a computer program that lets us users interact, through the keyboard, directly with the operating system. Bash is one of the shells around, and in many Linux operating systems (like Ubuntu for example), it is the default shell program. To be able to interact with the shell, you’ll use a terminal emulator program (you know, the dark screen-white letters-type command line interface). On Ubuntu, you’ll simply look through the programs and start the one called “Terminal” which is the terminal emulator that will let you interact with the bash shell (and through that, the Ubuntu Linux operating system). I hope it makes sense.
{: .text-justify}

For some Terminal basics, I thought I would collect a few things that I personally used. When you turn the terminal on, you will see the prompt with your username and the dollar $ sign, which means that after the dollar, you can type your commands and the shell is ready to receive your input. When you type in a command and press Enter, it gets executed. Afterwards, if you press the Up arrow on your keyboard, the previous command will be displayed and if you press Enter, it will be executed again (or you can modify it as needed). Often, you would need to execute a command in a specific directory. For example, when you want to use Git to issue a git pull command for one of your repositories, you will need to execute it from the directory where your repository is. An easy way to do that is to navigate to the folder where your repo is, using the graphical user interface for file browsing, right clicking on the folder and choose “Open in terminal”. This will open a Terminal with your username, the directory and of course the dollar $ sign. 
{: .text-justify}

Next, I collected a few basic commands that probably everyone should know:
* **pwd**: print working directory, i.e. the current folder you are in
* **cd**: change directory – move to a new folder
*  **ls**: list the contents of a directory
* **cat**: list the contents of a text file
* **cp**: copy files
* **mkdir**: create a new directory
* **rm**: remove, delete files or directories
* **touch**: create a new empty file (that later you could add text to, etc.)
* **grep**: search for text in a given file
* **sudo**: SuperUser DO, lets you complete administrative tasks with elevated privileges
* **head**: view the first few lines of a text file
* **tail**: view the last few lines of a text file
* **echo**: display a line of text
{: .text-justify}

This is obviously not an exhaustive list, and I did not provide here information of how to exactly use these commands. My recommendation is, try these out yourself. Also note that each command has many parameters that can help you have full control over the behavior of the execution. You can use the --help tag after the command to check these. For example, for the cat command, you can issue it like this: 
{: .text-justify}

```console
cat --help
```

Also, you can find a lot of info on [this website](http://www.gnu.org/software/bash/manual/bash.pdf).
{: .text-justify}

Follow my [next blog](/linux/2021/01/15/bash-scripting-2.html) post as well where I will check out the basics about shell scripts.
{: .text-justify}


Sources:
[https://opensource.com/resources/what-bash](https://opensource.com/resources/what-bash)
[https://linuxcommand.org/lc3_lts0010.php](https://linuxcommand.org/lc3_lts0010.php)
[https://searchdatacenter.techtarget.com/definition/shell](https://searchdatacenter.techtarget.com/definition/shell)
[https://www.hostinger.com/tutorials/linux-commands](https://www.hostinger.com/tutorials/linux-commands)

