# brHades

<img src="https://cdn.discordapp.com/attachments/1177272749379567617/1289624475230408704/1727540383711.png?ex=66f97fe2&is=66f82e62&hm=5326b31ccce31df6f41888c6d0379ddee211a2527eeec79d056e89ce51425fdc&" align="right" height="450" />

![clang](https://img.shields.io/github/actions/workflow/status/AoShinRo/brHades/build_servers_clang.yml?label=clang%20build&logo=llvm) ![cmake](https://img.shields.io/github/actions/workflow/status/AoShinRo/brHades/build_servers_cmake.yml?label=cmake%20build&logo=cmake) ![gcc](https://img.shields.io/github/actions/workflow/status/AoShinRo/brHades/build_servers_gcc.yml?label=gcc%20build&logo=gnu) ![ms](https://img.shields.io/github/actions/workflow/status/AoShinRo/brHades/build_servers_msbuild.yml?label=ms%20build&logo=visualstudio) ![GitHub](https://img.shields.io/github/license/AoShinRo/brHades.svg) ![commit activity](https://img.shields.io/github/commit-activity/w/AoShinRo/brHades) ![GitHub repo size](https://img.shields.io/github/repo-size/AoShinRo/brHades.svg)

> brHades is a collaborative software development project revolving around the creation of a robust massively multiplayer online role playing game (MMORPG) server package. Written in C++, the program is very versatile and provides NPCs, warps and modifications. The project is jointly managed by a group of volunteers located around the world as well as a tremendous community providing QA and support. brHades is a continuation of the eAthena project.

[Discord](https://discord.com/invite/DAPWeV677z)|[SharpPatcher](https://github.com/AoShinRO/SharpPatcher)|[AzzyAI-RE](https://github.com/AoShinRO/AzzyAI-RE)|[ServerMonitor](https://github.com/AoShinRO/rAthena-ServMonitor-ByAoShinHo)|[Crowdfunding](https://brHades.org/board/crowdfunding/)|[Fork and Pull Request Q&A](https://brHades.org/board/topic/86913-pull-request-qa/)
--------|--------|--------|--------|--------|--------

### Table of Contents
1. [Prerequisites](#1-prerequisites)
2. [Installation](#2-installation)
3. [Troubleshooting](#3-troubleshooting)
4. [More Documentation](#4-more-documentation)
5. [How to Contribute](#5-how-to-contribute)
6. [License](#6-license)

## 1. Prerequisites
Before installing brHades there are certain tools and applications you will need which
differs between the varying operating systems available.

### Hardware
Hardware Type | Minimum | Recommended
------|------|------
CPU | 1 Core | 2 Cores
RAM | 1 GB | 2 GB
Disk Space | 300 MB | 500 MB

### Operating System & Preferred Compiler
Operating System | Compiler
------|------
Linux  | [gcc-10 or newer](https://www.gnu.org/software/gcc/gcc-6/) / [Make](https://www.gnu.org/software/make/)
Windows | [MS Visual Studio 2020 or newer](https://www.visualstudio.com/downloads/)

### Required Applications
Application | Name
------|------
Database | [MySQL 5 or newer](https://www.mysql.com/downloads/) / [MariaDB 5 or newer](https://downloads.mariadb.org/)
Git | [Windows](https://gitforwindows.org/) / [Linux](https://git-scm.com/download/linux)

### Optional Applications
Application | Name
------|------
Database | [MySQL Workbench 5 or newer](http://www.mysql.com/downloads/workbench/)

## 2. Installation 

### Full Installation Instructions
  * [Windows](https://github.com/brHades/brHades/wiki/Install-on-Windows)
  * [CentOS](https://github.com/brHades/brHades/wiki/Install-on-Centos)
  * [Debian](https://github.com/brHades/brHades/wiki/Install-on-Debian)
  * [FreeBSD](https://github.com/brHades/brHades/wiki/Install-on-FreeBSD)

## 3. Troubleshooting

If you're having problems with starting your server, the first thing you should
do is check what's happening on your consoles. More often that not, all support issues
can be solved simply by looking at the error messages given. Check out the [wiki](https://github.com/brHades/brHades/wiki)
or [forums](https://brHades.org/forum) if you need more support on troubleshooting.

## 4. More Documentation
brHades has a large collection of help files and sample NPC scripts located in the /doc/
directory. These include detailed explanations of NPC script commands, atcommands (@),
group permissions, item bonuses, and packet structures, among many other topics. We
recommend that all users take the time to look over this directory before asking for
assistance elsewhere.

## 5. How to Contribute
Details on how to contribute to brHades can be found in [CONTRIBUTING.md](https://github.com/brHades/brHades/blob/master/.github/CONTRIBUTING.md)!

## 6. License
Copyright (c) brHades Development Team - Licensed under [GNU General Public License v3.0](https://github.com/brHades/brHades/blob/master/LICENSE)
