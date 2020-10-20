---
layout: post
title: "Linux Fundamentals #1"
categories: Blog
tags:
- linux
status: publish
type: post
published: true
meta: {}
---

## 🗃 Files & Directories

### 🏹 File Permissions

UNIX is a multi-user system. Every file and directory in your account can be protected from or made accessible to other users by changing its access permissions. Every user has responsibility for controlling access to their files. 

There are three type of permissions:
- **r** _for read_,
- **w** _for write_,
- **x** _for execute_. 

These permissions can controlled by:
- **u** _meaning user_ (😎 Yourself),
- **g** _meaning group_ (🧑‍🤝‍🧑 People in the same project),
- **o** _meaning other_ (😋 Everyone on the system).

File permissions also can be displayed in shell by running `ls -l` command.

- **?rwxrwxrwx**

In this line, first bit (_?_) identifies the file type. For example, link files can showed by **l**, directories **d**, etc. 

- First three bits after the question mark, defines the permission for user. (**rwx**)
- Second three bits after first one, defines the permission for group. (**rwx**)
- Last three bits, defines the permission for everyone. (**rwx**)

For example, let's create a directory called **movies** and list files & directories.

`mkdir movies` 
`ls -ltr` 

<img src="/images/linux-commands-image-one.png" align="center">

As seen above, in the left part of our movies folder there is the text **drwxr-xr-x**. _d_ letter shows us it is a directory, first **rwx** permissions of myself, second **r-x** group's permissions and last one is permissions for everyone in the system. 

Command to change permission: **`chmod`**

With **`chmod`** command, we can change permissions for users, groups and system users. 

As you can see, group users are not allowed to write in our movie folder. Let's change this with the **`chmod`** command.

<img src="/images/linux-commands-image-two.png" align="center">

If we want to add permissions, first add the letter of the usergroup (**u, g, o**) and then the letter of the permission (**r, w, x**) we want to add and specify the directory or file. 

In this example, I use `chmod g+w movies/` for add write permissions for group users.
