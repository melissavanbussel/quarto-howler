# Quarto howler Extension For Quarto

This Quarto extension allows you to add a Howler music player to your Quarto projects (based on the howler.js JavaScript library).

## Installing

```bash
quarto add melissavanbussel/quarto-howler
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

After installing the extension in your project, use it via:

```
---
title: "My Document"
format: html
filters:
  - quarto-howler
---
```

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).

