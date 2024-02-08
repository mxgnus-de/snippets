# Snippets

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Introduction](#introduction)
- [Proxy setup](#proxy-setup)

## Introduction

Common snippets that I use in my projects.

## Proxy setup

Applies proxy automatically to the environment when available.

You can find the script [here](./scripts/proxy_setup.sh).

### Installation

1. Download the script and put it somewhere in your system (e.g. `~/scripts/proxy_setup.sh`) and replace the `PROXY` variable with your proxy.

2. Make the script executable:

```bash
chmod +x <path_to_script>
```

3. Add the following line to your `.bashrc` or `.zshrc`:

```bash
source ~/scripts/proxy_setup.sh
```
