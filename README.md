# Gitslave Installation Guide

## Introduction
**Gitslave** is a tool that simplifies working with multiple Git repositories. It allows you to manage a group of related Git repositories as if they were one, making tasks like cloning, pulling, and committing more efficient.

This guide provides instructions for installing and setting up gitslave on your system.

---

## Prerequisites

- **Operating System**: Linux (Ubuntu, Debian, Fedora, etc.), macOS
- **Git Installed**: Ensure Git is installed on your system. If not, install it using:
  ```bash
  sudo apt update && sudo apt install git -y  # For Debian/Ubuntu
  sudo dnf install git                       # For Fedora
  brew install git                           # For macOS (Homebrew)
  ```

---

## Installation Steps

### 1. Clone the Gitslave Repository

```bash
git clone https://github.com/kajanan02/gitslave.git
cd gitslave
```

### 2. Install Gitslave

Run the installation script to set up gitslave:

```bash
sudo make install
```

### 3. Verify Installation

Check that gitslave is installed correctly by running:

```bash
gits --version
```

You should see the version of gitslave displayed.

---

## Basic Usage

### Initialize a Gitslave Group
To initialize a gitslave group:

```bash
gits init <group-name> <repo1> <repo2> ...
```




---


2. **Permission Denied During Installation**:
   Run the installation command with `sudo`:
   ```bash
   sudo make install
   ```

3. **Dependencies Missing**:
   Ensure Git and `make` are installed:
   ```bash
   sudo apt install git make
   ```

---

## Uninstallation
To uninstall gitslave, remove the installed script:


---

## Resources

- [Gitslave Documentation](https://github.com/kajanan02/gitslave)
- [Git Official Documentation](https://git-scm.com/doc)

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.
