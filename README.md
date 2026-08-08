# 🚀 Building simple, single-purpose Linux tools...

Hi! I am Mario Lohajner (manjo), a developer from Croatia focused on writing minimalist, low-dependency code and utilities that fit naturally into the Linux ecosystem. 

This GitHub profile functions as a practical collection of **architectural templates** for specific classes of applications. Every core repository here solves a concrete problem while serving as a blueprint for clean implementation patterns, minimalist dependencies, and optimal resource management.

---

## 🛠️ The Philosophy: UNIX Thinking & The Bash Glue

My development approach is fundamentally rooted in **UNIX thinking** and the strict **KISS (Keep It Simple, Stupid)** principle. I believe software should consist of simple, specialized tools that do one thing and do it exceptionally well. 

Instead of rewriting complex wheels or building bloated, heavy monoliths, the real engineering challenge lies in efficiency. True innovation comes from **maximizing the utility of existing system tools** and connecting them in novel, highly useful ways. 

For me, **Bash** is not just a command prompt or a simple terminal handler—it is a robust orchestration and automation platform. The shell scripts found in my repositories serve as the ultimate **architectural glue**, proving that you can achieve absolute system control, determinism, and flawless error handling with zero unnecessary overhead.

---

## 📦 Featured Templates & Tools (Samples included...)

The following repositories are original tools designed to function as reference architectures and living templates:

### 📐 [gtk-ruler](https://github.com) | *C / GTK*
* **A lightweight screen ruler utility for pixel-perfect desktop measurements.**
* **Platform:** GTK + C (meson + ninja build system) + Cambalache
* **Template:** A clean reference for minimal GTK application development in C, avoiding heavy modern desktop frameworks while maintaining precise screen coordinate rendering.

### 🖼️ [CSplash](https://github.com) | *Shell / Chafa*
* **An ANSI/ASCII terminal splash screen utility that brings back the retro CRT/BBS welcoming feel whenever you open a terminal.**
* **Template:** A perfect demonstration of using Bash as "glue" - maximizing the utility of an existing specialized tool (`chafa`) to build a high-impact terminal extension with zero framework overhead.

### 📡 [WiFi-spectrum](https://github.com) | *Python 3*
* **A visual WiFi spectrum analyzer that goes far beyond a basic list of network SSIDs.**
* **Platform:** GTK + Pyhton + WebKit (HTML + CSS for UI/UX with absolute customizability) = no Electron, no heavy frameworks...
* **Template:** Demonstrates how to ingest raw system/network metadata and transform it into low-latency, real-time graphical data within Python.

### 📊 [nemo_progress_dialogue](https://github.com) | *C*
* **Enhances the Nemo file manager copy dialogue with an integrated live transfer speed and bandwidth graph.**
* **Platform:** GTK + C (meson+ninja)
* **Template:** Shows how to extend existing Linux desktop environments natively using C while managing asynchronous UI components and active I/O monitoring.

### 📝 [md-view](https://github.com) | *Shell*
* **A local Markdown viewer for Linux with zero Electron, zero servers, and no bloated dependencies - just: Pandoc, Bash, and a browser.**
* **Template:** Ultra-lightweight desktop tooling, utilizing Bash as the structural glue to pipeline native system packages.

### 🖥️ [terminal-idle](https://github.com) | *C*
* **Monitors inactivity across open TTY sessions and spawns visual screensavers like `cmatrix`, `asciiquarium`, `cbonsai` or `chafa`.**
* **Template:** Illustrates process-level terminal state tracking, session monitoring, and system signal handling inside Linux environments.

### 🔄 [AFST (Analytic File Sync Tool)](https://github.com) | *Shell*
* **A dedicated file synchronization/archiver powered by shell automation and analytics.**
* **Template:** A blueprint for robust file system automation, precise error trapping in shell, and deterministic remote/local resource sync.

---

## 🔬 Upstream & Experimental Contributions

*This section includes upstream work, kernel experimentation, or patches rather than standalone template utilities:*

### 💾 [RRALLOC](https://github.com) | *C*
* **Overview:** A repository implementing support for the round-robin allocation policy as a native disk mount option. It focuses on rotating the starting block group for new filesystem allocations to experiment with alternative I/O distribution policies.

---

## ⚡ Core Tech Stack

* **Languages:** C, Python 3, Bash / Shell (POSIX standards)
* **Domains:** Linux Internals, System Automation, Performance Engineering, Lightweight Tooling
* **Target Platforms:** Linux / UNIX-like environments


