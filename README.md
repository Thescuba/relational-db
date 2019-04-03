# Introduction to Relational Databases
I have sped my way though SQL coures and passing all the quiz and I felt that I could understand the logic behind what I was doing with SQLbut found that I would forget the logic just as quickly as I learned it. These notebooks are my note from the class where I try to learn the ins and out of SQL where I experience to see what my query may be actually doing. Feel free to take that class yourself as it is offered free on [Udacity](https://classroom.udacity.com/courses/ud197/)
 
Table of Contents
=================

  * [Installation](#notebooks-installation)
    * [Install Git](#install-git)
    * [Install VirtuaBox](#installing-virtual-machine)
    * [Install Vagrant](#Install-Vagrant)
  * [Getting Started](#getting-started)
    * [Run Notebooks](#run-notebooks))
    * [Starting up Virtual Machine](Starting-up-Virtual-Machine)
  * [Part 1: Introduction](Intro-Relation-DB.ipynb)
      * 1.1 What is a Database
      * 1.2 How do we Structure Application Data? 
      * 1.3 Relational Database Features
      * 1.4 Looking at Tables
      * 1.5 Relating Tables
  * [Part 2: Elements of SQL](Elements-of-SQL.ipynb)
      * 2.1 Types in SQL World
      * 2.2 Comparison Operations in SQL
      * 2.3 Select Clasuses
      * 2.4 Simliar SQL and Python Operations
      * 2.5 Why use Databases? 
  * [Part 3: Connect Python Code to SQL](Python-Database-API.ipynb)
      * 3.1 What is a DB-API?
      * 3.2 Query Example
      * 3.3 Query and Create Tables
      * 3.4 Running a Web Forum
      * 3.5 Hello PSQL
      * 3.6 Give that App a Backend
      * 3.7 Stop Spam
  * [Part 4: Deeper Into SQL](Deeper-Into-SQL.ipynb)
      * 4.1 Nomalized Design
      * 4.2 Create Table and Types
      * 4.3 Declaring Primary Key
      * 4.4 Declaring Relationships
      * 4.5 Self Join
      * 4.6 Subqueries
      * 4.7 Views
      
# Notebooks Installation
This repository contains Jupyter Notebooks to follow along with the lectures. However, there are several
packages and applications that need to be installed. It is recommended to install anaconda at (https://www.anaconda.com/download/). Alternatively you may just want to go with just a python 3 install and use pip to install numpy, matplotlib, pandas alongwith jupyterlab or jupyter notebook.

## Install Git
Follow the instructions at (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## Installing Virtual Machine
1. Download [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  * You do not need the extension pack or the SDK. You do not need to launch VirtualBox after installing it; Vagrant will do that.
## Install Vagrant
1. Download [Vagrant](https://www.vagrantup.com/downloads.html)
  * The Installer may ask you to grant network permissions to Vagrant or make a firewall exception. Be sure to allow this.

# Getting Started
The VM(Virtual Machine) is a Linux server system that runs on top of your own computer. You can share files easily between your computer and the VM; and you'll be running a web service inside the VM which you'll be able to access from your regular browser. Vagrant is the software that configures the VM and lets you share files between your host computer and the VM's filesystem. If you are following along, part 3 and after will require installation of virtualBox and vagrant. 
## Run Notebooks
1. Clone the repository to a desired location (E.g. `git clone https://github.com/Thescuba/data-science.git`)
2. Open up jupyter labs or jupyter notebook either though anaconda navigator or terminal. 
3. Go to the repository directory
## Starting up Virtual Machine
1. Make sure that you are in the relation-db directory in terminal
2. Run the command `vagrant up`
3. When vagrant up is finished running, log into the machine with `vagrant ssh`
4. Run the command `cd /vagrant` to enter the shared directory
5. To log out or exit, type exit (or Ctrl-D)