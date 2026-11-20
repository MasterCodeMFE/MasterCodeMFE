# 👋 Hi, I'm Manuel Fernández

### DevOps · Linux · Observability · Automation · Systems Programming

I'm a **DevOps professional and 42 Madrid student** focused on Linux, infrastructure, monitoring, automation and low-level programming.

I enjoy understanding what happens **under the hood**, from containers and observability stacks to processes, signals, filesystems, networking and terminal interfaces.

> **Understand the infrastructure I operate, not just the tools running on top of it.**

---

## 🚀 Tech Stack

### ⚙️ DevOps & Infrastructure

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### 📊 Observability

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

`SNMP` · `Blackbox Exporter` · `Linux Monitoring` · `Infrastructure Monitoring`

### 💻 Programming

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### 🐧 Systems & Networking

`GNU/Linux` · `POSIX` · `Processes` · `Signals` · `File Descriptors`  
`Sockets` · `TCP/IP` · `DNS` · `SSH` · `TTY` · `Termios` · `Termcaps`

---

# 🔥 Featured Projects

## 📂 ft_ls

### Reimplementation of the Unix `ls` command in C

A modular implementation of `ls` focused on understanding directory traversal, filesystem metadata and Unix file types.

**Features**

- Long format listing (`-l`)
- Hidden files (`-a`)
- Recursive traversal (`-R`)
- Modification-time sorting (`-t`)
- Reverse ordering (`-r`)
- Symbolic links
- Multiple paths
- File metadata
- Unix file types
- Error handling

**Tech**

`C` · `GNU/Linux` · `Make` · `POSIX` · `Filesystem APIs`

👉 [View repository](https://github.com/MasterCodeMFE/42-ft_ls)

---

## 🖥️ ft_select

### Interactive terminal interface written in C

A low-level terminal project focused on understanding how interactive terminal applications work without relying on graphical libraries.

Working directly with:

- `termios`
- `termcaps`
- Raw keyboard input
- Terminal capabilities
- Signals
- Terminal resizing
- Dynamic rendering
- TTY handling

The goal is not only to build an interactive interface, but also to understand what actually happens between an application and the terminal.

---

## 🎥 ft_script

### Reimplementation of the Unix `script` command

A systems programming project built around Unix terminal internals.

Concepts explored:

- Pseudo-terminals
- TTY
- `fork`
- Process management
- Terminal I/O
- File descriptors
- Process synchronization

👉 [View repository](https://github.com/MasterCodeMFE/ft_script)

---

## 🐳 Inception

### Containerized infrastructure with Docker

Infrastructure project focused on building and connecting multiple isolated services using containers.

**Stack**

`Docker` · `Docker Compose` · `Nginx` · `MariaDB` · `WordPress`

Concepts explored:

- Container networking
- Persistent volumes
- Service isolation
- Reverse proxies
- Container orchestration
- Infrastructure configuration

👉 [View repository](https://github.com/MasterCodeMFE/inception)

---

## 🌐 Webserv

### HTTP server built from scratch in C++

A web server implementation designed to understand how HTTP servers work internally.

Concepts explored:

- HTTP
- TCP/IP
- Sockets
- Non-blocking I/O
- CGI
- Configuration parsing
- Client/server architecture
- Multiplexed connections

👉 [View repository](https://github.com/MasterCodeMFE/webserver)

---

## 🐚 Babuterm

### Unix shell implementation

A shell built in C to understand how command interpreters manage processes and interact with Unix.

Concepts explored:

- Pipes
- Redirections
- Environment variables
- Built-ins
- Process creation
- Signals
- File descriptors

**Tech**

`C` · `Unix` · `Processes` · `Signals`

👉 [View repository](https://github.com/MasterCodeMFE/Babuterm)

---

## 🧮 push_swap

### Sorting algorithms with constrained operations

Algorithmic challenge where numbers must be sorted using two stacks and a restricted set of operations.

Focused on:

- Algorithm design
- Complexity
- Stack-based operations
- Optimization
- Minimizing operation count

👉 [View repository](https://github.com/MasterCodeMFE/push_swap)

---

# 🎓 42 Madrid

My journey at **42 Madrid** has taken me from C fundamentals to Unix internals, networking, infrastructure and C++.

| Area | Projects |
|---|---|
| 🧱 C Foundations | Libft · ft_printf · get_next_line |
| 🧠 Algorithms | push_swap |
| 📡 IPC | minitalk |
| 🐚 Unix Processes | Babuterm |
| 🧵 Concurrency | Philosophers |
| 🎨 Graphics | FdF · cub3d |
| ⚙️ C++ | CPP Modules |
| 🌐 Networking | Webserv |
| 🐳 DevOps | Inception |
| 🌍 Web | ft_transcendence |
| 🐧 Linux Internals | ft_ls · ft_script · ft_select |

---

# 🔬 Currently Exploring

My main interest is the point where **DevOps and systems programming meet**.

I'm currently diving deeper into:

- 🐧 Linux internals
- 📊 Prometheus & Grafana
- 📡 SNMP monitoring
- 🔭 Observability
- 🐳 Docker & containers
- ⚙️ Infrastructure automation
- 🌐 Networking
- 💾 Storage systems
- 🖥️ Terminal / TTY internals
- 🔧 Systems programming in C
- 🧠 Unix / POSIX internals

---

# 💡 How I Like to Build Things

I don't like treating technology as a black box.

When possible, I prefer to:

1. Understand the problem
2. Learn how the underlying system works
3. Build a smaller version myself
4. Break it
5. Debug it
6. Improve it
7. Automate it

That's why many of my projects involve recreating tools or systems that already exist.

```text
ls          → Filesystems & metadata
shell       → Processes, pipes & signals
script      → Pseudo-terminals & TTY
ft_select   → Terminal interfaces
webserv     → HTTP, TCP/IP & sockets
Inception   → Containers & infrastructure
```

---

# 🧰 Toolbox

<p align="center">

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

</p>

---

# 📊 GitHub Stats

<p align="center">
  <img
    height="165"
    src="https://github-readme-stats.vercel.app/api?username=MasterCodeMFE&show_icons=true&theme=github_dark&hide_border=true"
  />
  <img
    height="165"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=MasterCodeMFE&layout=compact&theme=github_dark&hide_border=true"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-streak-stats.herokuapp.com/?user=MasterCodeMFE&theme=github-dark-blue&hide_border=true"
  />
</p>

---

# 🤝 Let's Connect

<p align="center">

[![GitHub](https://img.shields.io/badge/GitHub-MasterCodeMFE-181717?style=for-the-badge&logo=github)](https://github.com/MasterCodeMFE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Manuel_Fernández-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manuel-fernández-esteban/)

</p>

<p align="center">
  <b>DevOps · Linux · Observability · Systems Programming</b>
</p>

<p align="center">
  Building things to understand how they really work
