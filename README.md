# Pre-Essentials Training for Non-Technical Users

## Description

Prepare individuals who have never opened a terminal window who don't know what Chef is to take Chef Essentials.

## Working Agenda

### Macro Infrastructure (the big picture) - view of a web application
* Webserver
* Appserver
* Database
* Database Master/Slave
* Load Balancer
* Network Topology (how do they communicate)

### Micro Infrastructure
* Packages - how to install them (when you use a package resource it's talking to a package repository)
* Application
* Service the application provides
* Configuration

The objective is for the learner to understand that each machine has an operating system and other applications which inform how that machine will function as a whole

Be able demonstrate a basic understanding through Q/A of ______________________

This module should be a very brief overview (concept slides) (story - where are you and where do we want to go) and then a gamified Q/A session

1. Start from their vantage point of being a desktop user
2. Show how desktop applications are found, retrieved, and installed
3. Desktop user is not fully operational unless all applications are installed, configured correctly, and running. The Desktop user/computer is a functioning business unit.
4. Start a comparison between a desktop OS with all the applications to a Server in "Our Infrastructure"
5. Show how packages are found, retrieved and installed (for some Operating Systems)
6. Show where applications are installed and how they are executed
7. Show how applications have configuration that influences their execution
8. Show how applications need to be run in the background as services

#### Learning Objectives
* Answer questions to demonstrate a knowledge of how an operating system works
* Answer questions regarding how applications are installed using packages
* Answer questions regarding the services applications provide
* Answer questions to demonstration understanding of how OS and applications work together
* Answer questions regarding application configuration

### Overview of Chef Components
* Resources
* Recipes
* Cookbooks
* Chef Server
* Nodes
* Nodes converge through pull model
* Workstation
* Run-List

### Communication Protocols
* Http
* SSH
* RDP
* WinRM

### Communication Tools
* Browser
* PuTTY/SSH
* Remote Desktop Client (Windows)

### Understand basic Linux commands
* mv
* ls
* rm
* cat
* cp
* file structure - directories - hidden files - extensions
* tree
* Flags (generically how they work) commands/subcommands
* Sudo

### Understanding Basic Windows Commmands
* dir
* cp (or copy)
* rm
* cat
* move (or mv)
* tree
* flags commands/subcommands
* run as administrator
* powershell

### use editor (nano)
* what is an editor
* launch the editor
* launch an editor with a file
* edit a file (you can't always use your mouse)
* exit
* save
* exit without saving

### Chef in Practice
* creating a recipe
* file resource
* package resource
* applying recipe

### Ruby
* Primatives
* Strings
* Symbols
* Integers
* Floats
* Functions or methods
* Method parameters (arguments)
* Method blocks as a parameter
* Ruby file extension
