# Inception

## Summary
This project is part of a system administration exercise focused on the practical implementation of Docker. The goal is to broaden your knowledge of system administration by creating and managing multiple Docker containers within a virtual machine environment.

## Version
2.0

## Contents
- [Preamble](#preamble)
- [Introduction](#introduction)
- [General Guidelines](#general-guidelines)
- [Mandatory Part](#mandatory-part)
- [Bonus Part](#bonus-part)
- [Submission and Peer-evaluation](#submission-and-peer-evaluation)

### Preamble
This document serves as an exercise in system administration related tasks using Docker technology.

### Introduction
In this project, you will virtualize several Docker images, creating them in your new personal virtual machine.

### General Guidelines
- The project must be executed on a Virtual Machine.
- All configuration files should be stored in the `srcs` folder.
- A `Makefile` at the root of your directory should manage the setup of your entire application, including building Docker images via `docker-compose.yml`.
- Extensive documentation reading on Docker and relevant technologies is advised to successfully complete this assignment.

### Mandatory Part
Set up a small infrastructure with different services under specific rules:
- Use docker-compose and virtual machines.
- Create Dockerfiles for each service.
- Setup containers for NGINX, WordPress + php-fpm, and MariaDB.
- Manage data through dedicated volumes and establish network connections between containers without using deprecated features or insecure practices.

### Bonus Part
Enhance your project with optional features:
- Redis cache for WordPress.
- FTP server container for WordPress files.
- A static website (non-PHP).
- Adminer setup.
- Any other service you find useful, which you'll need to justify during your defense.

### Submission and Peer-evaluation
Submit your work via your Git repository. Ensure all filenames and folder structures are correct as only the contents of the repository will be evaluated.
