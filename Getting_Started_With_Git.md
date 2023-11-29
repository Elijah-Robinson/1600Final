# Getting Started with Git

## Installing Git

### Windows

1. Download Git for Windows from [Git Official Website](https://git-scm.com/download/win).
2. Run the downloaded installer.
3. Follow the installation steps, leaving the default settings as they are unless you have specific preferences.

### macOS

1. Install Git via Homebrew (recommended):
   - Run `brew install git` in the terminal.
   - If Homebrew isn't installed, you can get it from [Homebrew's Official Website](https://brew.sh/) and then proceed with the Git installation.

2. Alternatively, download and install Git from [Git Official Website](https://git-scm.com/download/mac).

### Linux

1. For Debian/Ubuntu-based systems:
   - Use the command `sudo apt-get update` followed by `sudo apt-get install git`.

2. For Fedora:
   - Run `sudo dnf install git` in the terminal.

3. For other distributions, refer to the respective package manager.

## Configuring Git

Set up your name and email address:

- Use the commands:
  - `git config --global user.name "Your Name"`
  - `git config --global user.email "your_email@example.com"`

Replace `"Your Name"` with your name and `"your_email@example.com"` with your email address.

## Initializing a Git Repository

- To start version controlling a project, use `git init` in the project directory.

## Cloning a Repository

To clone an existing repository:

- Use `git clone <repository_URL>`.
- Replace `<repository_URL>` with the URL of the repository you want to clone.
