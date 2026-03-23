# SRC - Source Code Reference

## Overview

This document provides a comprehensive reference to the **portless** source code structure. It serves as the **Source Recipe** for all engineering and development tasks.

---

## Directory Structure

```
portless/
├── apps/              # Applications
│   ├── docs/         # Documentation app
│   └── portless/    # Main app
├── packages/         # Shared packages
├── skills/          # Agent skills
├── tests/           # Test suites
├── node_modules/    # Dependencies
├── package.json     # Package manifest
├── pnpm-workspace.yaml
└── turbo.json       # Turborepo config
```

---

## Core Packages

### apps/portless

**Purpose:** Main portless application.

### packages/

**Purpose:** Shared packages for the monorepo.

---

## Build & Run

```bash
# Install dependencies
pnpm install

# Build all packages
pnpm build

# Run development
pnpm dev
```

---

*Document version: 1.0*
*Last updated: 2026-03-15*
*Part of GitCore Protocol*
