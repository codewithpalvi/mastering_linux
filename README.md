# mastering_linux
A beginner-friendly guide to learn and explore Linux basics, commands, and usage.

<h2>What is Linux? 👩‍🏫‍ </h2>
Linux is a free and open-source operating source, like Windows or macOS, that helps your computer run and manage tasks. It's widely used in servers, mobile phones and even supercomputers.

<h2>Why Linux? &#x1F914 </h2>
<ul><li>We use Linux because it's free, secure, and reliable.</li>
<li>It doesn't slow down easily, works well on old computers.</li>
<li>It is widely used in programming, servers, and ethical hacking.</li></ul>

<h2>Uses of Linux</h2>
<ol><li><b>Servers: </b>Most websites run on Linux servers because it's stable and secure.</li>
<li><b>Programming & Development: </b>Preferred by coders due to its powerful tools and flexibility.</li>
<li><b>Android OS: </b>Android is based on Linux, so it's used in mobile phones.</li>
<li><b>Supercomputers & Embedded Systems: </b>Powers most supercomputers and smart devices(like TVs, routers).</li></ol>

<h2>Difference between Linux and Windows</h2>

| Feature | Linux | Windows |
| ---- | ---- | ---- |
| License | Free and open-source | Paid and closed-source |
| Customization | Highly customizable | Limited customization |
| Security | More secure, fewer viruses | More prone to viruses |
| Performace | Lightweight, runs well on older hardware | Heavier, needs more system resources |
| Usage | Common in servers, coding, hacking | Common in personal and office use |
| Support | Community support | Official Microsoft support |

<h2>Booting and its types</h2>
<b>BOOTING: </b>Booting is the process of starting a computer when you turn it on. It loads the operating system so you can use the computer.<br></br>
<b>TYPES OF BOOTING: </b>
<ol><li><b>Cold Booting- </b>When you start the computer from a completely off state by pressing the power button.<br>
E.g. You press the power button on your computer in the morning after it was shut down overnight.</li>
<li><b>Warm Booting- </b>When you restart the computer without turning it off, like using the restart option.<br>
E.g. You click the "Restart" option from the Start menu to reboot your computer while it's already on.</li></ol>

<h2>Structure of Linux:</h2>
![image](https://github.com/user-attachments/assets/54561f7c-b63e-4ee4-bfae-900a296668a8)

<h2>Kernal</h2>
The kernal is the core part of the linux operating system. It connects the hardware and software, manages system resources like CPU, memory, and devices, and allows programs to run and communicate with the hardware.<br></br>
<b>Key Functions:</b><br>
<ul><li>Controls hardware (keyboard, disk, etc.) 
<li>File management</li>
<li>Process management</li>
<li>I/O management</li>
<li>Memory management</li>
<li>Device management</li></ul>

<h2>Shell</h2>
Shell is a program that lets you interact with the computer by typing commands. It acts like an interface between user and the operating system.
It takes your commands, sends them to the system, and shows the result.<br></br>
<h4>Types of Shell:</h4>
<ul><li><b>Bash (Bourne Again Shell)- </b>Most common and user-friendly</li>
<li><b>Sh (Bourne Shell)- </b>Older shell, simple and fast</li>
<li><b>Csh (C Shell)- </b>Syntax similar to C programming</li>
<li><b>Ksh (Korn Shell)- </b>Combines features of Bourne and C shell</li></ul><br></br>
<h4>Categories of Shell:</h4>
<ul><li><b>Command Line Shell- </b>You type commands (like in a terminal)</li><br>
![Screenshot 2025-06-28 153230](https://github.com/user-attachments/assets/701f77e3-c72b-4f87-b01f-0553b6930060)</br>
<li><b>Graphical Shell- </b>You click on icons (like desktop environment)</li><br>
![Screenshot 2025-06-28 153327](https://github.com/user-attachments/assets/28e85a60-7745-469f-9fbc-a4f2b3ae9a67)</br></ul>

<h2>Utilities:</h2>
Utilities are small programs or tools in an operating system that helps you perform basic tasks. They make it easier to manage files, folders, system settings, and more.<br>
<b>Examples: </b>copying files, checking disk shape, or setting passwords.

<h2>Linux Commands Overview:</h2>
<h4><b>(1)ls</b></h4>
<ul><li><b>Description: </b>Lists files and directories in the current folder.</li>
<li><b>Syntax: </b>ls</li>
<li><b>Example: </b></li></ul>
```ruby
 ubuntu@ubuntu:~$ ls 
 Desktop    Downloads   Pictures   Templates   snap 
 Documents  Music    Public    Videos
```
<h4><b>(2)cd</b></h4>
<ul><li><b>Description: </b>Changes the current directory</li>
<li><b>Syntax: </b>cd</li>
<li><b>Example: </b></li></ul>
```ruby
ubuntu@ubuntu:~$ cd Documents/
ubuntu@ubuntu:~/Documents$
```
<h4><b>(3)pwd</b></h4>
<ul><li><b>Description: </b>Shows the current working directory</li>
<li><b>Syntax: </b>pwd</li>
<li><b>Example:</b><br></li></ul>
```ruby
 ubuntu@ubuntu:~$ pwd 
/home/user/Documents
```
