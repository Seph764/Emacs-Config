# Emacs-Config

## Introduction
Featured in this repository is my own personal configuration of the .emacs file for editing in GNU Emacs. The repository exists for editing, portability, and accessibility purposes and makes it far easier for me to get Emacs configured on various systems.

## Current Setup & Bindings

### Quick-Window-Switcher
```
(windmove-default-keybindings)
(setq windmove-wrap-around t)
```

### C-Indentation-Style
```
(setq c-default-style "linux"
      c-basic-offset 4)