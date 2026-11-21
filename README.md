# AWS EC2 Linux Web Server Deployment

## Project Overview

Deployed a static website on Amazon EC2 using Amazon Linux 2023 and Apache HTTP Server.

## Project Objectives

  Launch an AWS EC2 instance.
  Configure SSH and HTTP access.
  Install Apache Web Server.
  Host a static website.
  Configure Linux file permissions.
  Test website using Public IPv4.

## AWS Services Used

  Amazon EC2
  Amazon VPC
  Security Groups

## Technologies Used

  Amazon Linux 2023
  Apache HTTP Server
  HTML5
  CSS3
  Linux Commands
  SSH

## Architecture

User Browser → Internet Gateway → Security Group → EC2 → Apache → Website

## Implementation Steps

1. Launched Amazon EC2 instance.
2. Created SSH Key Pair.
3. Configured Security Group.
4. Connected to Linux using SSH.
5. Installed Apache HTTP Server.
6. Created HTML and CSS files.
7. Configured Linux permissions.
8. Tested website using Public IPv4.

## Security Configuration

  SSH restricted to My IP.
  HTTP enabled on port 80.
  Website files configured with 644 permissions.
  Directories configured with 755 permissions.
 
## Learning Outcomes

  EC2 deployment
  Linux administration
  Apache configuration
  Security Group management
  Cloud infrastructure basics

## Project Status

Completed – Basic EC2 Web Server Deployment
