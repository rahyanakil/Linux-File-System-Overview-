## 1. Linux File System Overview

The Linux file system is the way Linux organizes and stores files and directories. 
Unlike Windows, Linux does not use different drives such as C: or D:. Everything 
starts from a single root directory, which is represented by `/`.

Inside the root directory, there are different folders that are used for different 
purposes. For example, user files are normally stored in `/home`, system 
configuration files are kept in `/etc`, and log files can be found inside 
`/var/log`.

Linux follows a hierarchical structure, so directories can contain other 
directories and files. Understanding this structure is important because it makes 
it easier to find files, manage the system, check permissions, and work with 
different Linux commands.

Some commonly used Linux directories are:

- `/` - The main root directory of the whole file system.
- `/home` - Contains personal directories and files of normal users.
- `/root` - The home directory of the root user.
- `/etc` - Contains system and application configuration files.
- `/var` - Stores files that change frequently, such as logs and other system data.
- `/tmp` - Used for temporary files.
- `/usr` - Contains many applications, commands, and other user-related files.
- `/bin` - Contains important basic Linux commands.
- `/dev` - Contains files that represent devices connected to the system.
- `/proc` - Provides information about running processes and the Linux system.
