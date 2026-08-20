# DirScope

A lightweight C++ command-line tool for analyzing disk usage and finding large files.

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
[![Language](https://img.shields.io/badge/Language-C%2B%2B17-blue.svg)](https://isocpp.org/)

> **Status:** Early development — v0.1

## Overview

DirScope is a command-line utility designed to help users understand how storage is being used within a directory.

It scans a specified directory, analyzes the files and subdirectories it contains, and presents the largest contributors to disk usage in a simple terminal interface.

The goal is to keep DirScope lightweight, fast, and easy to use without requiring a large graphical application.

## Features

### v0.1

- [ ] Scan a specified directory
- [ ] Calculate file and directory sizes
- [ ] Identify the largest files
- [ ] Identify the largest directories
- [ ] Sort results by size
- [ ] Display results in the terminal
- [ ] Handle filesystem errors safely

## Planned Features

Future versions may include:

- File type filtering
- Configurable result limits
- JSON output
- Duplicate file detection
- File hashing
- Directory exclusion rules
- More detailed storage statistics
- Cross-platform improvements

## Built With

- C++
- C++17
- CMake
- `std::filesystem`

## Building

Build instructions will be added after the initial build system is implemented and tested.

## Usage

Usage instructions and examples will be added once the first working version is available.

## Project Structure

```text
DirScope/
├── CMakeLists.txt
├── LICENSE
├── README.md
├── .gitignore
└── src/
    └── main.cpp
```

## License

DirScope is licensed under the Apache License 2.0.

See [`LICENSE`](LICENSE) for the full license text.

---

**DirScope**  
Copyright © 2026 Rupesh Joshi  
Licensed under the Apache License 2.0.
