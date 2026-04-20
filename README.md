# Linux Mentorship Lab 01.2: Directory Management

This repository contains materials for **Lab 01.2**, focusing on creating, organizing, and managing the directory structure in Linux. Understanding how to efficiently handle folders is key to maintaining a clean and logical system architecture.

## 🎯 Objectives
The goal of this lab is to master directory-specific operations. By the end of this lab, you will be able to:
* Create simple and complex (nested) directory structures.
* Navigate and visualize the directory hierarchy.
* Move, rename, and copy directories with their contents.
* Securely remove empty and non-empty directories.
* Understand the difference between absolute and relative paths in the context of directories.

## 📋 Core Commands & Utilities

### Creating & Viewing
* `mkdir` — Create a new directory.
* `mkdir -p` — Create parent directories as needed (nested structures).
* `ls -d` — List directories themselves, not their contents.
* `tree` — Visualize the directory structure in a tree-like format (if installed).

### Manipulation
* `cp -r` — Recursively copy a directory and all its contents.
* `mv` — Move or rename a directory.
* `rmdir` — Remove an **empty** directory.
* `rm -r` — Recursively remove a directory and all its files/subfolders.

## 🚀 Lab Tasks
1. **Structure Creation**: Build a project hierarchy (e.g., `project/docs`, `project/src`, `project/bin`) using a single `mkdir` command.
2. **Deep Nesting**: Create a 5-level deep directory path and navigate to the bottom using a single `cd` command.
3. **Cloning**: Practice copying an entire directory structure to a `backup/` location using recursive flags.
4. **Renaming**: Use the `mv` command to rename an existing folder and verify the path change.

## 💡 Pro Tip
Use the `-v` (verbose) flag with `mkdir`, `cp`, or `rm` to see exactly what the system is doing. It’s a great way to learn and debug your command strings in real-time.

---
*This lab is part of the Linux Mentorship program. Keep your file system organized!*
