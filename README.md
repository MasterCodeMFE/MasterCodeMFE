<!--
══════════════════════════════════════════════════════════════════════
  MASTER CODE MFE
  DevOps · Linux · Observability · Systems Programming
══════════════════════════════════════════════════════════════════════
-->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&duration=2500&pause=700&color=00D9FF&center=true&vCenter=true&width=900&lines=Hi%2C+I'm+Manuel+Fern%C3%A1ndez+%F0%9F%91%8B;DevOps+%7C+Linux+%7C+Observability;Systems+Programming+%7C+C+%7C+Unix;Automate.+Monitor.+Break.+Debug.+Improve.;Welcome+to+my+terminal+%F0%9F%90%A7" alt="Typing SVG" />

<br>

<a href="https://github.com/MasterCodeMFE">
  <img src="https://img.shields.io/github/followers/MasterCodeMFE?label=Followers&style=for-the-badge&logo=github&color=181717">
</a>

<img src="https://komarev.com/ghpvc/?username=MasterCodeMFE&style=for-the-badge&color=00b4d8&label=PROFILE+VIEWS">

</div>

---

```console
manuel@linux:~$ whoami

Manuel Fernández

manuel@linux:~$ cat current_role.txt

DevOps
42 Madrid Student
Linux & Systems enthusiast

manuel@linux:~$ cat interests.txt

Linux Internals
Observability
Automation
Networking
Containers
Systems Programming

manuel@linux:~$ echo $PHILOSOPHY

"Understand the infrastructure I operate,
 not just the tools running on top of it."
```

---

# 🧑‍💻 About Me

```yaml
name: Manuel Fernández
username: MasterCodeMFE

role:
  - DevOps
  - Systems Programming Enthusiast
  - 42 Madrid Student

location: Madrid, Spain

current_focus:
  - Linux
  - Observability
  - Infrastructure
  - Automation
  - Networking
  - Systems Programming

languages:
  - C
  - C++
  - Bash
  - Python

systems:
  - GNU/Linux
  - Debian
  - Ubuntu

learning:
  - Unix Internals
  - POSIX
  - TTY / Termios / Termcaps
  - Containers
  - Monitoring
  - Networking
```

I like knowing **what is happening underneath the abstraction**.

If a tool already exists, there's a good chance I want to rebuild a smaller version of it just to understand how it works.

---

# ⚡ My Stack

<div align="center">

## 🐧 Systems

<img src="https://skillicons.dev/icons?i=linux,debian,ubuntu,bash&theme=dark" />

<br><br>

## ⚙️ DevOps

<img src="https://skillicons.dev/icons?i=docker,git,gitlab,ansible&theme=dark" />

<br><br>

## 💻 Programming

<img src="https://skillicons.dev/icons?i=c,cpp,python,bash&theme=dark" />

<br><br>

## 📊 Observability

<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
<img src="https://img.shields.io/badge/SNMP-111827?style=for-the-badge&logo=linux&logoColor=white">
<img src="https://img.shields.io/badge/Blackbox_Exporter-6C63FF?style=for-the-badge&logo=prometheus&logoColor=white">

</div>

---

# 🧠 `man manuel`

```text
MANUEL(1)                    USER COMMANDS                    MANUEL(1)

NAME
       manuel - devops engineer obsessed with understanding systems

SYNOPSIS
       manuel [--linux] [--devops] [--monitor] [--build-from-scratch]

DESCRIPTION
       Works with Linux systems, infrastructure, automation,
       monitoring and low-level programming.

       Usually found investigating how something works internally
       instead of accepting that "it just works".

OPTIONS

       --linux
              Explore GNU/Linux and Unix internals.

       --devops
              Automate infrastructure and improve deployments.

       --monitor
              Prometheus, Grafana, SNMP and infrastructure monitoring.

       --c
              Build things dangerously close to the operating system.

       --break
              Discover undocumented features.

       --debug
              Turn those undocumented features back into working software.

       --coffee
              Required dependency.

EXIT STATUS
       0      Everything works.

       1      It's probably DNS.

       42     The answer.
```

---

# 🚀 Featured Projects

<div align="center">

## 📂 `ft_ls`

### My own implementation of the Unix `ls` command

<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black">
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
<img src="https://img.shields.io/badge/POSIX-111827?style=for-the-badge">
<img src="https://img.shields.io/badge/Make-064F8C?style=for-the-badge&logo=cmake&logoColor=white">

</div>

```console
$ ./ft_ls -laRt

drwxr-xr-x   systems/
drwxr-xr-x   linux/
drwxr-xr-x   curiosity/
-rwxr-xr-x   build_it_myself
```

A modular recreation of `ls` written in C to dive into **filesystem internals, directory traversal and metadata management**.

### ⚡ Features

- `-l` Long format
- `-a` Hidden files
- `-R` Recursive traversal
- `-t` Modification-time sorting
- `-r` Reverse ordering
- Symbolic links
- Multiple paths
- File metadata
- Unix file types
- Error handling

**Core concepts**

`C` · `GNU/Linux` · `POSIX` · `stat()` · `lstat()` · `dirent` · Filesystems

### 🔗 [Explore ft_ls](https://github.com/MasterCodeMFE/42-ft_ls)

---

<div align="center">

## 🖥️ `ft_select`

### Building an interactive terminal UI from scratch

<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black">
<img src="https://img.shields.io/badge/TTY-Terminal-00D9FF?style=for-the-badge">
<img src="https://img.shields.io/badge/Termios-Termcaps-6C63FF?style=for-the-badge">

</div>

No GUI.

No framework.

Just the terminal.

```text
Keyboard
   │
   ▼
 read()
   │
   ▼
termios
   │
   ▼
Application
   │
   ├── Selection
   ├── Signals
   ├── Resize
   └── Rendering
   ▼
       TTY
```

Working directly with:

`termios` · `termcaps` · `TTY` · `signals` · `ioctl`

`raw input` · `terminal resize` · `dynamic rendering`

---

<div align="center">

## 🎥 `ft_script`

### Exploring pseudo-terminals and Unix I/O

</div>

```text
Terminal
   │
   ▼
  PTY
 ┌─┴─────────────┐
 │               │
 ▼               ▼
Parent          Child
 │               │
Recorder        Shell
 │               │
 └──────┬────────┘
        ▼
      Output
```

Built around:

`PTY` · `TTY` · `fork()` · `wait()` · `read()` · `write()`

`process management` · `file descriptors` · `terminal I/O`

### 🔗 https://github.com/MasterCodeMFE/ft_script

---

<div align="center">

## 🐳 `Inception`

### Infrastructure built with containers

<img src="https://skillicons.dev/icons?i=docker,nginx,mysql,wordpress&theme=dark"/>

</div>

```text
                 Internet
                    │
                    ▼
               ┌─────────┐
               │  NGINX  │
               └────┬────┘
                    │
                    ▼
              ┌───────────┐
              │ WordPress │
              └─────┬─────┘
                    │
                    ▼
               ┌─────────┐
               │ MariaDB │
               └─────────┘
```

Exploring:

- Docker containers
- Container networking
- Persistent volumes
- Reverse proxies
- Service isolation
- Infrastructure configuration

### 🔗 https://github.com/MasterCodeMFE/inception

---

<div align="center">

## 🌐 `Webserv`

### HTTP server built from scratch in C++

<img src="https://skillicons.dev/icons?i=cpp,linux,nginx&theme=dark"/>

</div>

```text
Client
   │
   │ HTTP Request
   ▼
┌─────────────┐
│   Webserv   │
├─────────────┤
│   Parser    │
│   Sockets   │
│   CGI       │
│   Routing   │
└──────┬──────┘
       │
       ▼
 HTTP Response
```

Built to understand:

`HTTP` · `TCP/IP` · `Sockets` · `Non-blocking I/O`

`CGI` · `Configuration parsing` · `Client/Server architecture`

### 🔗 https://github.com/MasterCodeMFE/webserver

---

<div align="center">

## 🐚 `Babuterm`

### Because apparently using Bash wasn't enough.

</div>

```console
manuel@Babuterm$ echo "Hello world" | grep world > output.txt
manuel@Babuterm$ cat output.txt
Hello world
```

My own Unix shell implementation exploring:

- Processes
- Pipes
- Redirections
- Environment variables
- Built-ins
- Signals
- File descriptors

### 🔗 https://github.com/MasterCodeMFE/Babuterm

---

# 🎓 42 Madrid

<div align="center">

### From `Hello World` to "why is this file descriptor still open?"

</div>

```text
                          42 Madrid
                              │
            ┌─────────────────┼─────────────────┐
            │                 │                 │
            ▼                 ▼                 ▼
            C               UNIX              C++
            │                 │                 │
     ┌──────┼──────┐    ┌────┼─────┐      CPP Modules
     │      │      │    │    │     │
   Libft printf   GNL  shell IPC signals
                         │
                         ▼
                  Systems Programming
                         │
            ┌────────────┼─────────────┐
            │            │             │
            ▼            ▼             ▼
          ft_ls       ft_script     ft_select
```

| Area | Projects |
|:---|:---|
| 🧱 C Foundations | Libft · ft_printf · get_next_line |
| 🧠 Algorithms | push_swap |
| 📡 IPC | minitalk |
| 🐚 Unix | Babuterm |
| 🧵 Concurrency | Philosophers |
| 🎨 Graphics | FdF · cub3d |
| ⚙️ C++ | CPP Modules |
| 🌐 Networking | Webserv |
| 🐳 Infrastructure | Inception |
| 🌍 Web | ft_transcendence |
| 🐧 Linux Internals | ft_ls · ft_script · ft_select |

---

# 🔭 DevOps × Systems Programming

This is where things get interesting.

```text
                     ┌───────────────┐
                     │     DEVOPS    │
                     └───────┬───────┘
                             │
           ┌─────────────────┼─────────────────┐
           │                 │                 │
           ▼                 ▼                 ▼
        Linux          Observability       Automation
           │                 │                 │
           │         ┌───────┼───────┐         │
           │         │       │       │         │
           │     Prometheus Grafana SNMP    Scripts
           │                                   │
           └─────────────────┬─────────────────┘
                             │
                             ▼
                 ┌─────────────────────┐
                 │ SYSTEMS PROGRAMMING │
                 └──────────┬──────────┘
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
              C           POSIX          UNIX
              │             │             │
              └─────────────┼─────────────┘
                            │
                            ▼
                    UNDERSTAND IT.
```

---

# 🔬 `/proc/manuel/status`

```text
Name:           Manuel Fernández
Username:       MasterCodeMFE
State:          R (running)
Threads:        probably too many
Shell:          bash
Editor:         vim
Coffee:         enabled
Curiosity:      100%
Linux:          enabled
Monitoring:     enabled
Automation:     enabled
C:              segmentation fault
Debugging:      in progress
Uptime:         learning since boot
```

---

# 💭 Engineering Philosophy

```c
while (alive)
{
    understand();
    build();
    break_things();
    debug();
    automate();
    learn();
}
```

I don't want to know only **which command fixes the problem**.

I want to understand:

```text
Why did it break?
        │
        ▼
What is actually responsible?
        │
        ▼
How does it work internally?
        │
        ▼
Can I reproduce it?
        │
        ▼
Can I monitor it?
        │
        ▼
Can I automate it?
        │
        ▼
Can I make it better?
```

---

# 📊 GitHub Telemetry

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=MasterCodeMFE&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117">

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MasterCodeMFE&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117">

<br>

<img src="https://streak-stats.demolab.com?user=MasterCodeMFE&theme=tokyonight&hide_border=true&background=0D1117">

</div>

---

# 🐍 My Contributions

<div align="center">

<img src="https://raw.githubusercontent.com/MasterCodeMFE/MasterCodeMFE/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />

</div>

---

# 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=MasterCodeMFE&bg_color=0D1117&color=00D9FF&line=6C63FF&point=FFFFFF&area=true&hide_border=true">

</div>

---

# 🧩 Current Quest

```console
manuel@linux:~$ ./current_quest

[+] Master Linux internals
[+] Build monitoring systems
[+] Automate repetitive infrastructure
[+] Understand networking deeply
[+] Keep building things in C
[+] Break fewer production systems
[+] Break more test systems
[+] Never stop learning

Status: RUNNING...
```

---

# 🎯 The Goal

<div align="center">

### DevOps engineer with a systems programmer mindset.

Not only:

> **"I know how to use the tool."**

But:

> **"I understand why the tool works."**

And eventually:

> **"Let me see if I can build it myself."**

</div>

---

# 🌐 Connect

<div align="center">

<a href="https://github.com/MasterCodeMFE">
<img src="https://img.shields.io/badge/GitHub-MasterCodeMFE-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

<br><br>

### 🐧 Linux · ⚙️ DevOps · 📊 Observability · 💻 Systems Programming

<br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=2500&pause=1200&color=00D9FF&center=true&vCenter=true&width=700&lines=Automate+what+you+repeat.;Monitor+what+you+operate.;Understand+what+you+build.;Keep+learning." />

<br>

**`manuel@linux:~$ exit`**

*Process still running...*

</div>
