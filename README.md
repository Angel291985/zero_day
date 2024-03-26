# A Guide to running Ubuntu 20.04 on different operating systems
This project is a guide for you to set up the necessary coding environment irrespective
of the operating system that you are using.

# Windows has three options for running Ubuntu on Windows:
. WSL: WSL (Windows Subsystem for Linux) is a feature that allows you to run Linux distributions natively on Windows.
WSL is the easiest option to set up and use, and it provides a good introduction to Ubuntu.
. Vagrant: Vagrant is a tool for creating and managing virtual machines. It is a good option if you need to run Ubuntu
for development or testing purposes, as it allows you to create isolated environments that are easy to replicate and share.
. Docker: Docker is a tool for containerizing applications. It is a good option if you need to run Ubuntu for specific tasks,
such as running a web server or database. But also remember using docker will need an installation of WSL.

# macOS If you have:
. a Mac with an Apple Silicon chip, you can only use Docker to run Ubuntu.
. a Mac with an Intel chip, you can use Vagrant or Docker.

# Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

# General
. What is a virtual machine
. What is Vagrant
. Who wrote Vagrant
. What is Ubuntu
. What does “Ubuntu” mean
. How to use VMs with Vagrant
. What does the command uname do

# Copyright - Plagiarism
. You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
. You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
. You are not allowed to publish any content of this project.
. Any form of plagiarism is strictly forbidden and will result in removal from the program.

# Requirements
## General
. A README.md file at the root of the repo, containing a description of the repository
. A README.md file, at the root of the folder of this project (i.e. 0x00-vagrant), describing what this project is about

# More Info
## Install git
If git is not already installed on your terminal:
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git

## Basic usage
At the end of this project you should be able to reproduce and understand these command lines:
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
