# Atlantis-model

<hr>
<p align="center">
    <img alt="Atlantis" src="./img/logo.jpg" height="200" width="200">
</p>
<hr>

This page contains the basic instructions for running an Atlantis model on your
computer. For more detailed explanation you should visit the [Wiki](https://confluence.csiro.au/display/Atlantis/Atlantis+Ecosystem+Model+Home+Page)

----
Warning
----
If you want a copy of the Atlantis main code (which you will need to start using the
model) you will need to go first to this page [Licence](https://confluence.csiro.au/display/Atlantis/CSIRO+licence+and+repository+request) and send an email to the
developers, who will give you access to the code.
<hr>

<hr>

Atlantis model instalation and running
===============
### Index
* [Preparing your machine](#preparing-your-machine)
* [Check out the code](#Check-out-the-code)
* [Create](#create)
* [Local Changes](#local-changes)
* [Search](#search)
* [Commit History](#commit-history)
* [Branches & Tags](#branches--tags)
* [Update & Publish](#update--publish)
* [Merge & Rebase](#merge--rebase)
* [Undo](#undo)
* [Git Flow](#git-flow)


<hr>

# Set Up
---
## Linux

####  Checking libraries and packages

```
$ dpkg -l | grep build-essential	# Essential packages to build Debian
$ dpkg -l | grep autoconf      	# Automatic configure script builder
$ dpkg -l | grep subversion      	# Version Control System (like GITHUB)
$ dpkg -l | grep gawk          	# GNU version de Awk
$ dpkg -l | grep proj           	# Program Proj.4 Cartographic projection
$ dpkg -l | grep libxml2-dev 	# Library for XML lenguaje
$ dpkg -l | grep libnetcdf-dev	# Library of development kit for NetCDF
$ dpkg -l | grep flip              	# convert text file line endings between Unix and DOS
```
<hr>
