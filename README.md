> <h1>Git-GitHub-CodeOSS-ON-Arch-Linux

<p>This is a repo where I'm going to describe how to install git and Code-OSS and then integrate them with GitHub for maximum workflow.</p>

## Table of contents 
- [Introduction](#introduction)
- [How To Install](#how-to-install)
- [How To Configure](#how-to-configure)
- [Workflow](#workflow)
- [Conclusion](#conclusion)

# Introduction

<h2>Git</h2>

> Git is a distributed version control system. It tracks every change you make to your code (or any files) so you can:

- Go back to any previous version
- Work on different features in parallel (branches)
- Merge changes safely
- See exactly what changed and when

Git runs completely on your computer. You don’t need an internet connection to use it.

<h2>GitHub</h2>


> GitHub is a web-based platform built on top of Git. It gives you:

- Remote storage for your repositories
- Collaboration tools (pull requests, issues, code review)
- Free hosting for open-source projects
- Integration with CI/CD, project boards, and more

Think of Git as the tool that manages your code history, and GitHub as the place where you store, share, and collaborate on that code with others.


<h2>Code-OSS</h2>

> code - OSS is the open-source version of Visual Studio Code. It is the version available in the official Arch repositories.


Key advantages on Arch:

- Fully open-source
- Available directly from the official repos
- Excellent Git integration
- Huge extension ecosystem
- Lightweight, fast, and highly customizable
- Perfect terminal integration

> [!NOTE] 
> The proprietary Microsoft version is available via AUR (visual-studio-code-bin), but this guide focuses on Code - OSS.

# How To Install 

> Open your terminal and type:


```bash
sudo pacman -Syu                   #To update your system 
sudo pacman -S git                 #To Install git 
git --version                      #To verify git installation 
sudo pacman -S code                #To install Code-OSS 
code                               #To launch code 
```

# How To Configure 

> <h3>GitHub</h3>
Open your browser and type [github.com](github.com) There you will see this type of interface : 
