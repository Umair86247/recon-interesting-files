# Web Reconnaissance Tool - Interesting Files Scanner

## Table of Content:
1. [Description](#description)
2. [Features](#features)
3.  [Installation](#installation)
4.  [Basic Usage](#basic-usage)
5.  [Module Selection](#module-selection)

## Description
This Python script is designed to scan web servers for interesting files that may contain sensitive information such as credentials, configuration settings, or backups. It aids in reconnaissance efforts during security assessments or penetration tests, helping identify potential security vulnerabilities.

## Features
- Automated discovery of common files containing sensitive data
- Customizable list of file names to search for
- Simple command-line interface for ease of use

## Installation
To set up Recon-ng on your Kali Linux system, you've got two options: the easy way or the hands-on approach. If you're looking for simplicity, just open up your terminal and type `sudo apt install recon-ng`. This will automatically fetch Recon-ng and everything it needs to run smoothly. If you're feeling a bit more adventurous, you can take the manual route. Start by grabbing the Recon-ng repository from GitHub, then install the necessary bits and pieces using pip. Once that's done, fire up the `recon-ng` script, and you're good to go! Whether you prefer a quick setup or enjoy tinkering under the hood, Recon-ng will be at your service for all your reconnaissance and security testing needs.

## Basic Usage
Recon-ng is like a detective tool for the internet. It helps you gather important information about websites, networks, and people. With its different tools, you can find out things like what software a website is using or what email addresses are associated with a company. It's a must-have for cybersecurity experts and researchers who want to learn more about their targets.

## Module Selection
Module Options:
   - Syntax: `marketplace search`, `marketplace install <option_name> <value>`,
   - Description: Allows users to view and set options specific to the selected module.
   - `recon-ng`
   - ![image](https://github.com/Umair86247/recon-interesting-files/assets/160429176/d2a5b192-9abf-4b5a-8ed1-e40378042ae5)
   - `marketplace search`
   - ![image](https://github.com/Umair86247/recon-interesting-files/assets/160429176/69d99a8b-355b-49db-af4a-9f756543efd7)
   - `marketplace install (file-name)`
   - ![image](https://github.com/Umair86247/recon-interesting-files/assets/160429176/0c7366c6-9f29-4fa3-a262-f3386ef8753d)
   - ![image](https://github.com/Umair86247/recon-interesting-files/assets/160429176/34add66c-5fde-4f49-942e-1159a30cc122)
   - `modules search`
   - ![image](https://github.com/Umair86247/recon-interesting-files/assets/160429176/ea8382a0-423b-4389-b988-8a8d2ce67a5e)
   - `modules load (module name)`
   - ![image](https://github.com/Umair86247/recon-interesting-files/assets/160429176/d147198a-34d8-43a4-b532-0057ef7c4689)
   - `info`
   - ![image](https://github.com/Umair86247/recon-interesting-files/assets/160429176/e7e590d0-c469-4fa7-b1ce-0976b0759111)
   - `options set SOURCE (source)`
   - ![image](https://github.com/Umair86247/recon-interesting-files/assets/160429176/2444ffb0-f069-43ea-b378-c34993a78498)
   - `run`
   - ![image](https://github.com/Umair86247/recon-interesting-files/assets/160429176/cbe589d9-c24e-4230-9a81-31a42673fb0d)
   - The files will be saved in the path you can copy and paste it by entering `cd (path)`
   - `/root/.recon-ng/workspaces/default/`
   - There you will see the files with different names like .txt, .xml and many more.
   - use `cat` to view the content in .xml or .txt files. 


Help and Documentation:
   - Syntax: `help`, `help <module_or_command_name>`
   - Description: Provides comprehensive help and documentation to assist users in understanding module functionalities and command usage.
