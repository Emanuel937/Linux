# User management, groups, and permissions

Linux is a secure operating system that allows you to create users. This means that other people can access your machine, but you can decide what they are allowed or not allowed to do (this is called giving permissions).

All user data is usually stored in the `/home` folder. For example, when you create a new user, Linux will automatically create a personal folder for them inside `/home`. We will discuss folders in more detail later.

Another important folder related to users is the `/etc` directory, especially the `/etc/passwd` file. This file works like a "user book" of the system. Every time you create a new user, their information is automatically saved here. In the next chapter, we will go deeper into how this file works.

## Creating a user

The basic command to create a user is:

```bash
useradd username
