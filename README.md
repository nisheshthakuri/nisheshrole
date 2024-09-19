# Ansible Role: nisheshrole

## Overview

This Ansible role, `nisheshrole`, is designed to automate the installation and configuration of essential services, including Docker, Nginx, MySQL, and Java. This document provides an overview of the Nginx setup within this role.

### Role Name

- **Role**: nisheshrole
- **Author**: Nishesh Thakuri
- **Description**: Roles to install and configure Docker, Nginx, MySQL, and Java.

## Features

- Installs Nginx using the package manager.
- Creates and manages Nginx configuration files.
- Serves a customizable HTML page.
- Ensures Nginx is enabled to start on boot.

## Requirements

- Ansible 2.9 or higher
- A compatible Linux distribution (e.g., Debian, Ubuntu)

## Supported Platforms

This role is compatible with the following platforms:

- **Debian**: All versions
- **Ubuntu**: All versions

## Usage

To use this role in your Ansible playbook, include it as follows:

```yaml
- hosts: your_target_hosts
  become: yes
  roles:
    - 
