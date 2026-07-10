# Scalar Map Layer Composition

A scalar map composition system extracted from a procedural generation project.

This repository contains a sample of my code from a larger procedural landscape generation project.

## Overview

The system provides:

- Layer-based composition
- Multiple blend modes

## Main Components

### ScalarMap

Stores a 2D array of floating-point values.

Features:

- Fast index access
- Cloning
- Copying
- Fill/Clear operations

### Layer

Represents a single composition layer.

Each layer contains:

- Source map
- Optional influence map
- Blend mode
- Weight
- Priority

### BlendModes

Provides common blending operations:

- Blend
- Add
- Max
- Min
