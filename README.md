Auto-admin
==========
Auto-admin is a set of tools for automating common systems management tasks
such as enabling/disabling services, tuning the system, installing software,
etc.

There are two primary goals:

* Provide a compatibility layer to help automate sysadmin tasks across
multiple platforms.
* Act as a knowledgebase for performing sysadmin tasks from the
command-line. 

Core design principals:

* Complete portability: Our aim is to support any POSIX platform for which
someone is willing to maintain the code.
* Zero dependencies: All scripts are written in POSIX Bourne shell and use
only tools included with a minimal install, so auto-admin can be the first
package installed after the OS.
* Speed and Simplicity: Our efforts are focused on basic functionality,
robustness, fast and easy setup and management.

Auto-admin includes well over 100 scripts for performing systems management
tasks as well as a simple menu system for the most common ones, such as
installing software, adding users, etc.

To get started, simple open a terminal and run auto-admin.

https://acadix.biz/auto-admin.php
