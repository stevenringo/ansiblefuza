## Rubyfuza 2015, Cape Town, 7 Feb 2015

# Ansible for fun and profit workshop

A workshop to provide you with an overview of Ansible that will show you how to confidently deploy your ruby apps and servers and have some fun doing it.

## System Requirements

### 1. Ansible

You will install [Ansible](http://www.ansible.com/) on your "control" machine, likely your regular computer.

Ansible can be run from any "Unix"-type machine with Python 2.6 installed. This includes Red Hat, Debian, CentOS, OS X, BSDs etc.

You will need to install Linux on a local VM if on Windows.

Installation instructions at <http://docs.ansible.com/intro_installation.html>

### 2. VirtualBox

We will use [VirtualBox](https://www.virtualbox.org/) to host the "target" machine VM (which will be managed by Vagrant).

Installation instructions at <https://www.virtualbox.org/wiki/Downloads>

### 3. Vagrant

Vagrant lets you create and configuring virtual development environments. Its a wrapper around virtualization software such as VirtualBox and others and lets us easily configure and start machines from plain text files and the command line respectively.

Installation instructions at <https://www.vagrantup.com/downloads.html>

### 4. Ubuntu machine image

We will work from an Ubuntu 12.04 machine image, available at <http://files.vagrantup.com/precise64.box>

If you're familiar with Vagrant/Virtualbox, go ahead and install it. If not, download the file and we will configure it with Vagrant in the workshop.
