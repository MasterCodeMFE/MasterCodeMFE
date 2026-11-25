<!--
══════════════════════════════════════════════════════════════════════
 MASTER CODE MFE
 DevOps · Linux · Observabilidad · Programación de Sistemas
══════════════════════════════════════════════════════════════════════
-->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&duration=2500&pause=700&color=00D9FF&center=true&vCenter=true&width=900&lines=Hola%2C+soy+Manuel+Fern%C3%A1ndez+%F0%9F%91%8B;DevOps+%7C+Linux+%7C+Observabilidad;Programaci%C3%B3n+de+Sistemas+%7C+C+%7C+Unix;Automatizar.+Monitorizar.+Depurar.+Mejorar.;Bienvenido+a+mi+terminal+%F0%9F%90%A7" alt="Typing SVG" />

<br>

<a href="https://github.com/MasterCodeMFE">
 <img src="https://img.shields.io/github/followers/MasterCodeMFE?label=Seguidores&style=for-the-badge&logo=github&color=181717">
</a>

<img src="https://komarev.com/ghpvc/?username=MasterCodeMFE&style=for-the-badge&color=00b4d8&label=VISITAS+AL+PERFIL">

</div>

---

```console
manuel@linux:~$ whoami

Manuel Fernández

manuel@linux:~$ cat current_role.txt

DevOps
Estudiante en 42 Madrid
Apasionado por Linux y los sistemas

manuel@linux:~$ cat interests.txt

Internals de Linux
Observabilidad
Automatización
Redes
Contenedores
Programación de Sistemas

manuel@linux:~$ echo $PHILOSOPHY

"Entender la infraestructura que opero,
 no solo las herramientas que se ejecutan sobre ella."
```

---

## 🧑‍💻 Sobre mí

```yaml
name: Manuel Fernández
username: MasterCodeMFE

role:
  - DevOps
  - Apasionado por la Programación de Sistemas
  - Estudiante en 42 Madrid

location: Madrid, España

current_focus:
  - Linux
  - Observabilidad
  - Infraestructura
  - Automatización
  - Redes
  - Programación de Sistemas

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
  - Contenedores
  - Monitorización
  - Redes
```

Me interesa comprender **qué ocurre realmente por debajo de las abstracciones**.

Si una herramienta ya existe, probablemente quiera construir una versión más pequeña por mi cuenta para entender cómo funciona internamente.

---

## ⚡ Mi Stack

<div align="center">

### 🐧 Sistemas

<img src="https://skillicons.dev/icons?i=linux,debian,ubuntu,bash&theme=dark" />

<br><br>

### ⚙️ DevOps

<img src="https://skillicons.dev/icons?i=docker,git,gitlab,ansible&theme=dark" />

<br><br>

### 💻 Programación

<img src="https://skillicons.dev/icons?i=c,cpp,bash&theme=dark" />

<br><br>

### 📊 Observabilidad

<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
<img src="https://img.shields.io/badge/SNMP-111827?style=for-the-badge&logo=linux&logoColor=white">
<img src="https://img.shields.io/badge/Blackbox_Exporter-6C63FF?style=for-the-badge&logo=prometheus&logoColor=white">

</div>

---

## 🧠 `man manuel`

```text
MANUEL(1)                  USER COMMANDS                  MANUEL(1)

NAME
    manuel - DevOps orientado a comprender sistemas desde dentro

SYNOPSIS
    manuel [--linux] [--devops] [--monitor] [--build-from-scratch]

DESCRIPTION
    Trabaja con sistemas Linux, infraestructura, automatización,
    monitorización y programación de bajo nivel.

    Habitualmente investigando cómo funciona algo internamente
    en lugar de conformarse con que "simplemente funciona".

OPTIONS

    --linux
        Explorar el funcionamiento interno de GNU/Linux y Unix.

    --devops
        Automatizar infraestructura y mejorar procesos de despliegue.

    --monitor
        Prometheus, Grafana, SNMP y monitorización de infraestructura.

    --c
        Construir software peligrosamente cerca del sistema operativo.

    --break
        Descubrir comportamientos no documentados.

    --debug
        Convertir esos comportamientos en software funcional.

    --coffee
        Dependencia obligatoria.

EXIT STATUS
    0   Todo funciona.

    1   Probablemente sea DNS.

    42  La respuesta.
```

---

# 🚀 Proyectos destacados

<div align="center">

## 📂 `ft_ls`

Mi propia implementación del comando Unix `ls`

<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black">
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
<img src="https://img.shields.io/badge/POSIX-111827?style=for-the-badge">
<img src="https://img.shields.io/badge/Make-064F8C?style=for-the-badge&logo=cmake&logoColor=white">

</div>

```console
$ ./ft_ls -laRt

drwxr-xr-x systems/
drwxr-xr-x linux/
drwxr-xr-x curiosity/
-rwxr-xr-x build_it_myself
```

Una recreación modular de `ls`, escrita en C para profundizar en **sistemas de archivos, recorrido de directorios y gestión de metadatos**.

### ⚡ Funcionalidades

- `-l` Formato largo
- `-a` Archivos ocultos
- `-R` Recorrido recursivo
- `-t` Ordenación por fecha de modificación
- `-r` Orden inverso
- Enlaces simbólicos
- Múltiples rutas
- Metadatos de archivos
- Tipos de archivos Unix
- Gestión de errores

**Conceptos principales**

`C` · `GNU/Linux` · `POSIX` · `stat()` · `lstat()` · `dirent` · Sistemas de archivos

🔗 [Explorar ft_ls](https://github.com/MasterCodeMFE/42-ft_ls)

---

<div align="center">

## 🖥️ `ft_select`

Construyendo una interfaz interactiva de terminal desde cero

<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black">
<img src="https://img.shields.io/badge/TTY-Terminal-00D9FF?style=for-the-badge">
<img src="https://img.shields.io/badge/Termios-Termcaps-6C63FF?style=for-the-badge">

</div>

Sin interfaz gráfica.

Sin frameworks.

Solo la terminal.

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
    ├── Selección
    ├── Señales
    ├── Resize
    └── Renderizado
    │
    ▼
   TTY
```

Trabajando directamente con:

`termios` · `termcaps` · `TTY` · `signals` · `ioctl`

`raw input` · `terminal resize` · `dynamic rendering`

---

<div align="center">

## 🎥 `ft_script`

Explorando pseudo-terminales y E/S en Unix

</div>

```text
              Terminal
                 │
                 ▼
                PTY
          ┌──────┴──────┐
          │             │
          ▼             ▼
        Parent         Child
          │             │
       Recorder        Shell
          │             │
          └──────┬──────┘
                 ▼
               Output
```

Construido alrededor de:

`PTY` · `TTY` · `fork()` · `wait()` · `read()` · `write()`

`process management` · `file descriptors` · `terminal I/O`

🔗 [Explorar ft_script](https://github.com/MasterCodeMFE/ft_script)

---

<div align="center">

## 🐳 `Inception`

Infraestructura construida con contenedores

<img src="https://skillicons.dev/icons?i=docker,nginx,mysql,wordpress&theme=dark"/>

</div>

```text
             Internet
                │
                ▼
          ┌───────────┐
          │   NGINX   │
          └─────┬─────┘
                │
                ▼
         ┌─────────────┐
         │  WordPress  │
         └──────┬──────┘
                │
                ▼
          ┌───────────┐
          │  MariaDB  │
          └───────────┘
```

Profundizando en:

- Contenedores Docker
- Redes entre contenedores
- Volúmenes persistentes
- Reverse proxies
- Aislamiento de servicios
- Configuración de infraestructura

🔗 [Explorar Inception](https://github.com/MasterCodeMFE/inception)

---

<div align="center">

## 🌐 `Webserv`

Servidor HTTP construido desde cero en C++

<img src="https://skillicons.dev/icons?i=cpp,linux,nginx&theme=dark"/>

</div>

```text
Client
  │
  │ HTTP Request
  ▼
┌───────────────┐
│    Webserv    │
├───────────────┤
│ Parser        │
│ Sockets       │
│ CGI           │
│ Routing       │
└───────┬───────┘
        │
        ▼
 HTTP Response
```

Construido para comprender:

`HTTP` · `TCP/IP` · `Sockets` · `Non-blocking I/O`

`CGI` · `Configuration parsing` · `Client/Server architecture`

🔗 [Explorar Webserv](https://github.com/MasterCodeMFE/webserver)

---

<div align="center">

## 🐚 `Babuterm`

Porque, aparentemente, utilizar Bash no era suficiente.

</div>

```console
manuel@Babuterm$ echo "Hello world" | grep world > output.txt
manuel@Babuterm$ cat output.txt
Hello world
```

Mi propia implementación de una shell Unix para profundizar en:

- Procesos
- Pipes
- Redirecciones
- Variables de entorno
- Built-ins
- Señales
- Descriptores de archivo

🔗 [Explorar Babuterm](https://github.com/MasterCodeMFE/Babuterm)

---

# 🎓 42 Madrid

<div align="center">

De `Hello World` a "¿por qué sigue abierto este descriptor de archivo?"

</div>

```text
                         42 Madrid
                             │
             ┌───────────────┼───────────────┐
             │               │               │
             ▼               ▼               ▼
             C              UNIX            C++
             │               │               │
     ┌───────┼───────┐   ┌───┼────┐     CPP Modules
     │       │       │   │        │
   Libft   printf   GNL shell    IPC/signals
             │
             ▼
      Systems Programming
             │
     ┌───────┼─────────┐
     │       │         │
     ▼       ▼         ▼
   ft_ls  ft_script  ft_select
```

| Área | Proyectos |
|:---|:---|
| 🧱 Fundamentos de C | Libft · ft_printf · get_next_line |
| 🧠 Algoritmos | push_swap |
| 📡 IPC | minitalk |
| 🐚 Unix | Babuterm |
| 🧵 Concurrencia | Philosophers |
| 🎨 Gráficos | FdF · cub3d |
| ⚙️ C++ | CPP Modules |
| 🌐 Networking | Webserv |
| 🐳 Infraestructura | Inception |
| 🌍 Web | ft_transcendence |
| 🐧 Linux Internals | ft_ls · ft_script · ft_select |

---

# 🔭 DevOps × Programación de Sistemas

Aquí es donde ambas disciplinas se encuentran.

```text
                 ┌───────────────┐
                 │    DEVOPS     │
                 └───────┬───────┘
                         │
         ┌───────────────┼───────────────┐
         │               │               │
         ▼               ▼               ▼
       Linux       Observabilidad    Automatización
         │               │               │
         │       ┌───────┼───────┐       │
         │       │       │       │       │
         │  Prometheus Grafana  SNMP   Scripts
         │               │
         └───────────────┬───────────────┘
                         │
                         ▼
             ┌─────────────────────┐
             │ SYSTEMS PROGRAMMING │
             └──────────┬──────────┘
                        │
             ┌──────────┼──────────┐
             ▼          ▼          ▼
             C        POSIX       UNIX
             │          │          │
             └──────────┼──────────┘
                        │
                        ▼
                ENTENDER EL SISTEMA
```

---

# 🔬 `/proc/manuel/status`

```text
Name:           Manuel Fernández
Username:       MasterCodeMFE
State:          R (running)
Threads:        probablemente demasiados
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

# 💭 Filosofía de Ingeniería

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

No quiero saber únicamente **qué comando soluciona un problema**.

Quiero entender:

```text
¿Por qué ha fallado?
        │
        ▼
¿Qué componente es realmente responsable?
        │
        ▼
¿Cómo funciona internamente?
        │
        ▼
¿Puedo reproducirlo?
        │
        ▼
¿Puedo monitorizarlo?
        │
        ▼
¿Puedo automatizarlo?
        │
        ▼
¿Puedo mejorarlo?
```

---

# 📊 Telemetría de GitHub

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=MasterCodeMFE&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117">

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MasterCodeMFE&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117">

<br>

<img src="https://streak-stats.demolab.com?user=MasterCodeMFE&theme=tokyonight&hide_border=true&background=0D1117">

</div>

---

# 🐍 Mis contribuciones

<div align="center">

<img src="https://raw.githubusercontent.com/MasterCodeMFE/MasterCodeMFE/output/github-contribution-grid-snake-dark.svg" alt="Animación de contribuciones" />

</div>

---

# 📈 Actividad de contribuciones

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=MasterCodeMFE&bg_color=0D1117&color=00D9FF&line=6C63FF&point=FFFFFF&area=true&hide_border=true">

</div>

---

# 🧩 Objetivos actuales

```console
manuel@linux:~$ ./current_quest

[+] Profundizar en los internals de Linux
[+] Construir sistemas de monitorización
[+] Automatizar tareas repetitivas de infraestructura
[+] Comprender networking en profundidad
[+] Seguir construyendo proyectos en C
[+] Romper menos sistemas en producción
[+] Romper más sistemas de pruebas
[+] No dejar nunca de aprender

Status: RUNNING...
```

---

# 🎯 El objetivo

<div align="center">

### DevOps con mentalidad de programador de sistemas.

No limitarme a:

**"Sé utilizar esta herramienta."**

Sino llegar a:

**"Entiendo por qué funciona esta herramienta."**

Y, eventualmente:

**"Vamos a ver si puedo construirla por mi cuenta."**

</div>

---

# 🌐 Contacto

<div align="center">

<a href="https://github.com/MasterCodeMFE">
<img src="https://img.shields.io/badge/GitHub-MasterCodeMFE-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

<br><br>

🐧 Linux · ⚙️ DevOps · 📊 Observabilidad · 💻 Programación de Sistemas

<br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=2500&pause=1200&color=00D9FF&center=true&vCenter=true&width=700&lines=Automatiza+lo+que+repites.;Monitoriza+lo+que+operas.;Entiende+lo+que+construyes.;Sigue+aprendiendo." />

<br>

**`manuel@linux:~$ exit`**

*El proceso sigue en ejecución...*

</div>
