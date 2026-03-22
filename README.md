# VisualQuantumSuite

VisualQuantumSuite is a modular desktop application built in C# (.NET)
designed as a central launcher for quantum and data-oriented simulation tools.

## Overview

The application provides a unified interface to launch and manage multiple
independent simulation modules:

- Matrix exploration tool
- Quantum Data Engine
- Quantum Simulator

Each module is executed as a separate process from a structured folder-based deployment.

## Architecture

- Language: C#
- Framework: .NET (WinForms)
- Modular launcher pattern
- External executable process handling
- Structured deployment approach

## Deployment

The application is distributed as a self-contained Windows (win-x64) build.

Required folder structure:

VisualQuantumSuite/
│
├── VisualQuantumSuite.exe
└── apps/
    ├── Matrix.exe
    ├── QuantumDataEngine.exe
    └── QuantumSimulator.exe

## Purpose

This project demonstrates:
- Modular desktop application architecture
- Multi-process management
- Folder-based deployment strategy
- Structured UI-based launcher design

---

Author: Stjepan Velc
