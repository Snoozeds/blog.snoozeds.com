---
title: What now?
date: 2023-11-14 08:06:10
tags: 
- update
- projects
---

It's been 3+ weeks since [my discord account got disabled](https://blog.snoozeds.com/discord/) for me being negative 6 years old, and I have already decided I will not continue development with my bot, DankRPG, and use Javascript not at all, or less. So what now?

# Learning C#:
Learning either C, C++ or C# (or perhaps all) has always been a dream of mine. Coming from JavaScript, it is quite confusing. I could go over the differences if I had infinite time. My favourite way of learning any programming language has always just been playing around with it, and *maybe* reading documentation if necessary, this has been somewhat difficult with C#, for whatever reason. It's also been an interesting experience trying to do anything using the .NET framework on Arch Linux. It *does* support Linux, just... it's not amazing, in my opinion. Is that anyone's fault? I don't know.

My current opinion is that it is "better" than JavaScript. Both have their uses and advantages/disadvantages. Both approaches are fine, but personally I'd **much** rather use C# to make a desktop app than JS + Electron.

## Upcoming project with C# (Yanta):
I figured I might as well make a simple program to start with, open-source of course. So, here I am introducing Yanta/Yet Another Note-Taking App. It's still in its very early stages (*only* ~400 lines of code thus far), so I don't want to make too many promises or anything. Here is some information regardless.

- It is primarily built for Linux. I use Linux 99% of the time and plan to use this application myself. Windows support is very much planned though.
- MacOS, I don't know. I do not like MacOS. I do not use MacOS. I cannot easily virtualise MacOS.
- Currently, it only supports *.txt files. It may support other simple formats such as json, md, etc. in the future.
- Markdown support with previewing has been tried. It did not work under Linux at all with the libraries that barely existed, so if Markdown support is added, preview will not be available due to this.
- It uses [Gtk](https://www.gtk.org/), a great and simple UI library with cross-platform support.
- It has basic support for Gtk CSS themes, meaning you can customise it to your heart's content (provided you know how to do so, of course.)

## Images of Yanta:
A heavily zoomed-in note using a custom Gtk theme.
![](/images/03/01.png)

A more heavily zoomed-in note using a custom Gtk theme with word wrapping enabled.
![](/images/03/02.png)

A heavily zoomed-in note using the system's Gtk theme.
![](/images/03/03.png)

### TL;DR:
- I'm working on a new open-source note-taking app called Yanta, built primarily for Linux, with plans for Windows support. It currently only supports *.txt files but may support other formats in the future.
- Yanta uses Gtk, a simple UI library with cross-platform support, and has basic support for Gtk CSS themes.