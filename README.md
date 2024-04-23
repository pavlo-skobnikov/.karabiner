# Karabiner Configuration README

## Overview

This README provides an overview of a custom configuration for Karabiner-Elements, enhancing keyboard functionality on macOS through key remapping.

## Key Remappings

### Double-Key Home Row Modifiers
This configuration enables utilizing double-key combinations for home row modifiers.
- Pressing `a` + `f`: `Left Command` -> `Left Control`
- Pressing `s` + `f`: `Left Command` -> `Left Shift`
- Pressing `d` + `f`: `Left Command` -> `Left Option`
- Pressing `a` + `d`: `Left Command` -> `Left Control` + `Left Option`
- Pressing `a` + `s`: `Left Command` -> `Left Control` + `Left Shift`
- Pressing `s` + `d`: `Left Command` -> `Left Shift` + `Left Option`
- Pressing `semicolon` + `j`: `Right Command` -> `Right Control`
- Pressing `l` + `j`: `Right Command` -> `Right Shift`
- Pressing `k` + `j`: `Right Command` -> `Right Option`
- Pressing `semicolon` + `k`: `Right Command` -> `Right Control` + `Right Option`
- Pressing `semicolon` + `l`: `Right Command` -> `Right Control` + `Right Shift`
- Pressing `l` + `k`: `Right Command` -> `Right Shift` + `Right Option`

### Caps Lock as Escape
- Pressing `Caps Lock`: `Escape`

### Double Option as Hyper
- Pressing `Left Option` + `Right Option`: `Left Control` + `Left Shift` + `Left Option` + `Left Command`

### Double Command for Navigation
- Pressing `Left Command` + `Right Command`: Set `nav_mode` to `1` (Toggle)
  - While `nav_mode` is `1`:
    - Pressing `j`: `Down Arrow`
    - Pressing `k`: `Up Arrow`
    - Pressing `h`: `Left Arrow`
    - Pressing `l`: `Right Arrow`
    - Pressing `a`: `Left Control`
    - Pressing `s`: `Left Shift`
    - Pressing `d`: `Left Option`
    - Pressing `f`: `Left Command`

### Shift w/ Delete for Forward Delete
- Pressing `Shift` + `Delete`: `Forward Delete`

## Installation Instructions

1. Ensure Karabiner-Elements is installed on your macOS system.
2. Access the Karabiner-Elements configuration file, typically located at `~/.config/karabiner/karabiner.json`.
3. Copy the provided JSON rules into the configuration file.
4. Save the changes and restart Karabiner-Elements to apply the new configuration.
