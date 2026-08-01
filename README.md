# Git-GitHub-VScode-setup-on-ArchLinux

# Git, GitHub & VS Code Setup on Arch Linux
2
 
3
A beginner-friendly guide to setting up Git, GitHub, and VS Code on Arch Linux.
4
 
5
---
6


 
7
## Table of Contents

 

- #install-git-using-pacman
- #configure-git

- #generate-ssh-key
12
- #install-vs-code
13
- [Project Structure
14
- [Useful Links](#useful-linksll Git
15
 
16
## Install Git using pacman:
17
 
18
```bash
19
sudo pacman -S git
20
```
21
 
22
Check that Git is installed:
23
 
24
```bash
25
git --version
26
```
27
 
28
Expected output:
29
 
30
```text
31
git version 2.x.x
32
```
33
 
34
---
35
 
36
## Configure Git
37
 
38
Set your Git identity:
39
 
40
```bash
41
git config --global user.name "Your Name"
42
git config --global user.email "your@email.com"
43
```
44
 
45
Verify:
46
 
47
```bash
48
git config --list
49
```
50
 
51
---
52
 
53
## Generate SSH Key
54
 
55
Create a new SSH key:
56
 
57
```bash
58
ssh-keygen -t ed25519 -C "your@email.com"
59
```
60
 
61
View the public key:
62
 
63
```bash
64
cat ~/.ssh/id_ed25519.pub
65
```
66
 
67
Copy the output and add it to GitHub.
68
 
69
> [!TIP]
70
> Never share your private key.
71
 
72
---
73
 
74
## Install VS Code
75
 
76
Install VS Code:
77
 
78
```bash
79
sudo pacman -S code
80
```
81
 
82
Launch:
83
 
84
```bash
85
code
86
```
87
 
88
---
89
 
90
## Project Structure
91
 
92
```text
93
git-github-vscode-arch/
94
 
95
├── README.md
96
├── LICENSE
97
├── .gitignore
98
└── assets/
99
├── ssh-key.png
100
└── vscode.png
101
```
102
 
103
---
104
 
105
## Screenshot Example
106
 
107
assets/vscode.png
108
 
109
---
110
 
111
## Useful Links
112
 
113
- Git Official Website
114
- https://github.com/
115
- [VS Code](httpssualstudio.com/
116
 
117
---
118
 
119
## License
120
 
121
This project is licensed under the MIT License.