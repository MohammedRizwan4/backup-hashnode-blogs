---
title: "Mastering the Linux Terminal✨✍: A Comprehensive Guide to Commands and Concepts"
seoTitle: "Mastering the Linux Terminal✨✍: A Comprehensive Guide to Commands"
seoDescription: "Unix🤔- Linux🤔- Shell 🤔- Bash🤔 - Terminal - 🤔Command Prompt🤔, etc.
Are you also confused??👇"
datePublished: Mon May 01 2023 16:38:39 GMT+0000 (Coordinated Universal Time)
cuid: clh52ens8000809kybk7bdu9w
slug: introduction-to-linux-terminal-and-its-commands
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1682958986669/8bcfa1ec-26fa-46f4-afe6-ec96283e4610.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1682959061117/b9853f04-0199-4520-afce-c87b06a26e78.png
tags: linux, cloud-computing, devops, kunalkushwaha, wemakedevs

---

# Unix🤔- Linux🤔- Shell 🤔- Bash🤔 - Terminal - 🤔Command Prompt🤔, etc.

# Are you also confused?👇

In the world of computer science and technology, many terms and concepts can be confusing or difficult to understand, such as **Unix, Linux, Shell, Bash, Terminal, and Command Prompt.**

So, In this article, we will break down these concepts and explain what they mean in **simple language.**

We will explore what a shell is and how it works, introduce the Bash shell, and explain how a terminal and command prompt can be used to interact with a computer system.

By the end of this article, you will have a clear understanding of these important concepts and other Linux commands.

# Some Important Terms to Understand👇

* ## Unix👇
    

Unix is an **operating system** developed in the 1970s, which provides a command-line interface to interact with the system.

To check this:-

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682954947843/b1934427-4c90-4820-b7c0-83b77d149311.png align="center")

* ## Linux👇
    

Linux is a **Unix-like** operating system that was developed in the 1990s, based on the **Unix architecture**.

To check this:-

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682954912699/8e29635e-9707-4b97-8e41-e8aa5be044f7.png align="left")

* ## Shell - An important topic👇
    

A **shell** is a program that runs in the terminal and interprets the user's commands. It acts as an interface between the user and the operating system.

**For example,** when you enter `mkdir student` as a command and execute them accordingly.

```bash
# To create new directory
mkdir student
```

The shell program does this by looking for executable files with the same name as the command.

For instance, the shell searches for an executable file called `mkdir` in the directories listed in the system's PATH environment variable. When it finds the file, it loads it into memory and executes it.

See how to get the path

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682954157617/a675ae75-35cc-43f2-adcb-c77b69b9d7e9.png align="left")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682954183736/117d598a-944c-4779-98b3-b7a977d7cda4.png align="center")

In this way, the shell acts as an intermediary between the user and the computer's operating system. It allows users to interact with the system using textual commands, without needing to use a graphical user interface.

* ## Bash👇
    

Bash is a popular shell that is widely used on Linux and other Unix-like systems.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682954663488/4c987736-5f7a-4e30-b10d-e1f33965cd96.png align="center")

* ## Terminal Emulator👇
    

A terminal is a program that provides a text-based interface to interact with the system. It allows users to enter commands and receive text-based output. A terminal can be opened on a graphical desktop environment, such as GNOME or KDE, or accessed remotely through SSH.

Ex:- **PowerShell, cmd, and Git Bash** are all examples of terminal emulators.

* ## Command Prompt👇
    

A command prompt is a text-based interface that allows users to enter commands and receive text-based output. It is typically displayed in a terminal window and shows the user's current working directory and a prompt character, such as `$` or `#`.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682954417742/c3ab96c1-1a70-4c23-b379-acbd31002afa.png align="left")

# Basic Linux Commands👇

## 1\. `pwd` 🚀

This command stands for **"print working directory".** It displays the name of the current working directory (i.e., the directory that you are currently in). For example, if you type `pwd` in the terminal, it might display something like:-

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682955335709/a9b1a961-52ac-4af6-8dd9-beedfb85d0ca.png align="left")

## 2\. `who` 🚀

This command displays information about the users who are currently logged in to the system. It can **show the username, terminal device, and login time** for each user.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682955771001/81d84621-2717-4165-9365-0047f3a37cd0.png align="left")

## 3\. `mkdir` 🚀

This command stands for **"make directory"**. It is used to **create a new directory** in the current working directory. For example, if you type `mkdir random` in the terminal, it will create a new directory called *"random"* in the current working directory.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682955835804/bac68716-4892-497e-8a14-c14e738aa5a0.png align="left")

## 4.`rmdir` 🚀

This command stands for **"remove directory"**. It is used to **delete an empty directory** from the file system. For example, if you type `rmdir random` in the terminal, it will delete the *"random"* directory if it is empty.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682955989636/97a82127-89da-4c08-af88-f3112ab19b83.png align="left")

* If the directory contains some files or folders then we have to use `-r` tag.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682956291549/a0fe140a-5197-4c40-9130-541e20d56565.png align="left")

## 5.`cd` 🚀

This command stands for **"change directory".** It is used to change the current working directory to another directory. For example, if you type `cd random` in the terminal, it will change the current working directory to the *"random"* directory.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682956085202/ec0becfa-3dd0-479c-bc66-643fce01804a.png align="left")

* If we want to go back to the previous directory then use `cd ..` command
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682956456797/44623d86-3420-4e47-a674-a76c94d148ef.png align="center")

## 6.`ls` 🚀

This command stands for **"list directory".** It is used to display the contents of a directory. For example, if you type `ls` in the terminal, it will **display a list of all the files and directories in the current working directory.**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682956716191/1dd7c295-4bb2-41d8-835f-289fa8a8ff08.png align="left")

* Here, The `-a` flag represents the display of all files (including hidden files).
    
* `-R` Is the recursive tag that displays all the files which are inside the current directory and its sub-directories.
    

## 7\. `touch` 🚀

This command is used to create a new file in the current working directory. For example, if you type `touch my_file.txt` in the terminal, it will create a new file called *"my\_file.txt"* in the current working directory.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682956989119/acfff538-4377-4336-9d54-2672e764fda0.png align="center")

**There are 3 ways you can create a file:-🔥**

* **1). Using** `cat` **command:-🔥**
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682957245810/7e0df0e7-c48e-4bc0-97ef-26c608ecf5b7.png align="left")

* **2). Using** `vim` **editor:-🔥**
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682957467596/23a7e13e-134d-4f3e-bc1d-1abdf8327a55.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682957480289/e33f3d14-f631-49a3-a919-d6830fe5f184.png align="left")

Now, Add some content and press `esc key` `+` `w key` `+` `q key`. So `w` for write and `q` for quit (means save and exit).

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682957605727/889b6980-bbe8-48c7-9919-85db332635fe.png align="left")

* Now print that file
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682957765670/8afff018-ab2d-4cc2-9bd4-b33e48bab4d4.png align="left")

* **3). Using** `the touch` **command which we had already covered.🔥**
    

## 8\. `rm` 🚀

This command stands for **"remove"**. It is used to delete a file or directory from the file system. For example, if you type `rm my_file.txt` in the terminal, it will delete the "*my\_file.txt*" file from the current working directory.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682958013148/15b5a35c-04ca-44f8-b72c-8dda180cb3e7.png align="left")

* If you want to delete a directory and its contents, you can use the `-r` option, as in `rm -r my_folder`. Be careful when using the `rm` command, as it permanently deletes files and directories and they cannot be recovered once they are deleted.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1682958031461/8296f825-93ef-46e4-9df2-f2abd782deb0.png align="left")

**\--.--.------------------------- To be Continued --------------------------.--.--**

## 💫Note:- 😎

**Thank you** for reading this blog post. I hope you found it informative and useful. Stay tuned for more commands here only, we will delve further into the types of commands. See you next time!🚴‍♀️

Thanks for scrolling.🏃‍♀️

*— Mohammed Rizwan Bhavnagri, May 1, 2023.*