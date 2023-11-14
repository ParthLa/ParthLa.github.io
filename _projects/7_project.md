---
layout: page
title: Enhancing XV6 system 
description: Implementing fundamental OS elements through XV6
img:
importance: 7
category: Implementation
---

<p align="justify"> This was the course work of Operating Systems Lab at IIT BOMBAY, in Autumn 2020. Using XV6, I implemented elements like Scheduling, Memory Management, Shell building, File System handling, Forking that are critical to functioning of an operating system. </p>

<p align="justify">
Scheduler in XV6
<ul>
<li> Modified the current scheduler in XV6 to consider user-defined process priorities </li>
<li> Used priorities as weights to implement a weighted round robin scheduler, while taking care of starvation </li>
</ul>
</p>

<p align="justify">
Custom Memory Manager
<ul>
<li> Implemented a memory manager to allocate and deallocate memory dynamically </li>
<li> Extended the allocator to be elastic and map pages only on demand </li>
</ul>
</p>

<p align="justify">
Custom Linux Shell
<ul>
<li> Built own Linux-like shell in C </li>
<li> Added support for background, serial & parallel processes, and kill signal & exit command </li>
</ul>
</p>

<p align="justify">
File System Implementation
<ul>
<li> Emulated a disk over a text file with the superblock, inode and data blocks </li>
<li> Implemented a file system on the emulated disk with basic operations like open/close/read and write </li>
</ul>
</p>

<p align="justify">
Copy-on-write Fork in XV6
<ul>
<li> Implemented the Copy-on-Write Fork in the XV6 OS </li>
<li> It allocates new pages for the memory image only on modification by the child/parent </li>
</ul>
</p>

Various Implementations can be found here: <a href="https://github.com/ParthLa/Enhancing-XV6-System"> Code </a>.