# Puppet DevOps Infrastructure Automation

## Overview
This project demonstrates infrastructure automation using Puppet.

Puppet manifests are used to configure services automatically.
Docker is used to run the Puppet environment.

## Technologies Used
- Puppet
- Docker
- Git
- PowerShell

## Project Structure

puppet-system
Contains main Puppet manifests.

config-modules
Contains reusable Puppet modules.

automation-scripts
Scripts used to execute automation.

documentation
Contains additional documentation.

## How to Run

Run Docker environment:

docker-compose up --build

Or run Puppet manually:

puppet apply puppet-system/main.pp