# irun - Interactive GitHub Software Installer

irun is a command-line tool that simplifies the installation of software directly from GitHub repositories. It supports interactive search, release selection, custom installation paths, and flexible argument parsing.

## Features

- Interactive repository search on GitHub
- Direct installation from specified repositories
- Release version management with specific tag selection
- Asset selection from releases
- Custom installation directories
- Clone-only mode (bypass releases)
- Source code download support
- Automatic executable handling (AppImage, tar.gz, zip, deb, rpm)
- Application removal and listing
- Flexible argument parsing (arguments can be in any order)
- Multi-language Desktop detection (Bureau, Desktop, etc.)

## About
This software is developped by AI (github's copilot), but is tested by hand.

## Installation

### Prerequisites

- Bash 4.0 or higher
- curl
- git
- python3 (optional, for better JSON parsing)

### Setup

1. Download the file in the "releases" section
2. Put the file in ~/.local/bin (for linux users).
3. You're good to go, just type "irun" in your favorite terminal and it should be running!
