---
title: tsci agent
description: Use the tsci agent from your terminal
---

`tsci agent` lets you use the tsci agent from your terminal.

## Usage

```bash
tsci agent [args...]
```

### Arguments

- `args...` *(optional)* - any arguments to forward directly to `tsci-agent`

## What it does

If `tsci-agent` is not installed, `tsci` prompts to install it before starting.

## Examples

Start the agent:

```bash
tsci agent
```

Pass flags or a prompt:

```bash
tsci agent --help
tsci agent --version
tsci agent "review this circuit project"
```
