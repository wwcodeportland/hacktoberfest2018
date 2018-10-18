---
title: Getting Started with your Dev Environment
category: "hacktoberfest"
cover: photo-1507915600431-5292809c5ab7.jpg
author: wwcodepdx
---

Before you start to code, you’ll need to familiarize with some core web technologies, and make sure that you have installed all required software tools.

### The Command Line
The command line is a text-based interface used to run commands on your computer. (You’ll also often see it referred to as the terminal. In this tutorial we’ll use both interchangeably). It’s a lot like using the Finder on a Mac, or Explorer on Windows. Finder and Explorer are examples of graphical user interfaces (GUI). The command line is a powerful, text-based way to interact with your computer.

Take a moment to locate and open up the command line interface (CLI) for your computer. (Depending on which operating system you are using, see instructions for Mac, or instructions for Windows).

For a great introduction to using the command line, check out Codecademy’s Command Line tutorial for Mac and Linux users, and this tutorial for Windows users. (Even if you are a Windows user, the first page of the Codecademy tutorial is a valuable read, as it explains what the command line is, not just how to interface with it.)

### Install Node.js
Node.js is an environment that can run JavaScript code. Gatsby is built with Node.js. To get up and running with Gatsby, you’ll need to have a recent version installed on your computer.

#### Download Node.js
Visit the Node.js site and follow the instructions to download and install the recommended version for your operating system. Once you have followed the installation steps, make sure everything was installed properly:

#### Check your Node.js installation
- Open up your terminal.
- Run node --version. (If you’re new to the command line, “run command” means “type node --version in the command prompt, and hit the Enter key”. From here on, this is what we mean by “run command”).
- Run npm --version.

The output of each of those commands should be a version number. If entering those commands doesn’t show you a version number, go back and make sure you have installed Node.js.

#### Overview of NPM
npm is a JavaScript package manager. A package is a module of code that you can choose to include in your projects. If you just downloaded and installed Node.js, npm was installed with it!

Check out npm’s introduction, “What is npm?”.

### Install Git
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. When you install a Gatsby “starter” site, Gatsby uses Git behind the scenes to download and install the required files for your starter.

If your system does not have Git installed, install it from the Git downloads page.

### Install the Gatsby CLI
The Gatsby CLI tool lets you quickly create new Gatsby-powered sites, and run commands for developing Gatsby sites. It is a published npm package. You can install the Gatsby CLI from the npm registry, using the npm CLI.

- Install the Gatsby CLI tool
- Navigate to the terminal.
- Run npm install --global gatsby-cli.

If you are unable to successfully install due to a permissions issue, you may want to check out the npm docs on fixing permissions, or this guide.

A couple of different things are happening here:

We’re using the npm CLI to install the Gatsby CLI. npm install is the command used to install packages.
When installing npm packages, you can install them globally, or in a specific project. (We’ll learn about the latter, later). The --global flag signals that we want the first option, to install globally. This means our package will be available to us on our computer, outside of the context of a specific project.
gatsby-cli is the exact name our desired package is registered with on the npm registry.

### Check your Gatsby CLI installation
- Open up your terminal.
- Run gatsby --version.
- Run gatsby --help.

If successfully installed, running `gatsby --version` should return a version number, and running `gatsby --help` will show different commands available to you using the gatsby-cli tool.