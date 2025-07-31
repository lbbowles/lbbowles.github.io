---
layout: project
type: project
image: img/airplane/airplane-square.png
title: "Airplane Controller"
date: 2023
published: true
labels:
  - C
  - Linux Shell
  - GitHub
summary: "A multithreaded, networked air traffic ground control server project that I coded for CSC 362."
---

<img class="img-fluid" src="../img/airplane/airplane-header.png">

This is the oldest project featured on this webpage, but it's definitely a valuable one to have in my repertoire.   

The project was developed in a Linux environment via a Virtual Machine, allowing students to become comfortable working directly in the shell.  Moreover, It was also the first large-scale project I wrote in C, rather than C++ or Java.  The entire idea of the project was to utilize the C language to create a TCP-based server that handles airplane clients issuing structured protocol commands such as registering flight IDs, requesting taxi clearance, and coordinating takeoff. Each airplane functioned as a client, with its session managed in a separate thread. I used a thread-safe array list to store and manage client data.  Finally, safety measurements such as takeoff delays and queues were implemented.  Altogether, this project was a fun yet challenging introduction to systems-level programming and multithreading, it was definitely an experience that strengthened my foundation as an aspiring Software Engineer.

Below are a few excerpts written by the professor that highlight the objectives and difficulties / nuances of this project:

<hr>

<pre>

Quality reminder: While there's a lot of functionality to implement here, keep in mind that in a 300-level class (and even more so in the work world!), you're expected to write good code, which means good style, good design, and good documentation. Your code should be robust (handling errors gracefully) and should manage memory properly. Remember to check with Valgrind to make sure you don't have any memory leaks, and carefully think through how things can go wrong.

Project difficulty: The project requires you to write a non-trivial amount of code, as compared to the weekly assignments. Get started on each part as soon as you can so you don't run out of time!

  --
  
Of course, lines of code don't tell the entire story. There are thread management issues that come up that need to be carefully thought through, so it's not just a matter of cranking out lines of code.
  
</pre>

<hr>


 
Source: <a href="https://github.com/lbbowles/Airplane-Controller-C-Project">lbbowles/Airplane-Controller-C-Project</a>
