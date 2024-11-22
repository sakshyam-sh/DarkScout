# Overview

Brief description of the project. Its purpose, and main functionality

# Setup

## Prerequisites

1. Bun (version 1.1.36)
https://bun.sh/docs/installation

2. Git
https://git-scm.com/downloads

## Installation

### Clone the repository

```
git clone [url to repository]
cd DarkScout

```

### Install dependencies

`bun install`

## Development

### Running the Project

`bun run dev`

After running with bun run dev, By default the development server runs on:  http://localhost:4321

### Building the project

```
bun run build

bun ./dist/server/entry.mjs

```

# Project Structure

```
DarkScout                    # Root directory of the project
├── astro.config.mjs         # Astro configuration file for project-specific settings
├── bun.lockb                # Lockfile for Bun package manager (ensures consistent dependencies)
├── package.json             # Project metadata and dependency management
├── public                   # Directory for static assets served directly
│   └── favicon.svg          # Website favicon
├── README.md                # Project documentation and overview
├── src                      # Source code directory
│   ├── assets               # Non-component static assets
│   │   ├── eye.svg          # SVG icon asset
│   │   └── Vector.svg       # Another SVG asset
│   ├── components           # Reusable UI components
│   │   ├── Button.astro     # Reusable button component
│   │   ├── Card.astro       # Card layout component
│   │   ├── Header.astro     # Site header component
│   │   └── Input.astro      # Form input component
│   ├── env.d.ts             # TypeScript declarations for environment variables
│   ├── layouts              # Page layout components
│   │   ├── AuthLayout.astro # Layout for authentication pages
│   │   └── Layout.astro     # Base layout for the site
│   ├── pages                # Astro pages that define routes
│   │   ├── forgot-password.astro # Forgot password page
│   │   ├── index.astro      # Homepage
│   │   └── sign-in.astro    # Sign-in page
│   └── styles               # Global styling
│   └── global.css           # Main CSS file for global styles
└── tsconfig.json            # TypeScript configuration file
```
