# Karabiner Elements Remaps README

## Overview

This README describes a set of custom key remapping configurations for macOS using Karabiner-Elements, a powerful keyboard customization tool. These configurations are designed to enhance productivity and streamline common tasks by redefining key behaviors.

## Configuration Details

### Caps Lock Key

- **Description**: Converts the Caps Lock key to Escape when tapped and Control when held.
- **Modifiers**: Allows optional modifiers to be combined.

### Left Shift with Y

- **Description**: Maps Left Shift + Y to function as Return.
- **Behavior**: Key repeats when held down.

### Left Shift with J/K/L

- **Description**: Customizes deletion functionality with combinations of Left Shift + J/K/L to delete a character, word, or entire line backwards.
- **Modifiers**: Utilizes a combination of control, shift, option, and command keys.

### Left Shift with U/I

- **Description**: Maps Left Shift + U/I to delete a character or word forwards.
- **Modifiers**: Similar to the J/K/L mappings but for forward deletion.

### Left Shift to Hyper Key

- **Description**: Converts Left Shift to a Hyper key (Control + Shift + Option + Command).
- **Modifiers**: This remap does not require additional modifiers.

### Spacebar Functionality

- **Description**: The spacebar functions normally when tapped, but acts as Right Shift when held.
- **Modifiers**: Optional modifiers are allowed.

### Right Command with Number Row

- **Description**: Transforms Right Command + Number Row keys into corresponding Function keys (F1 to F12).
- **Modifiers**: Requires Right Command; optional modifiers are allowed.

### Right Command with H/J/K/L and A/S/D

- **Description**: Implements Vim-like arrow key navigation with Right Command + H/J/K/L. Additionally, remaps Right Command + A/S/D to act as Shift, Option, and Command respectively.
- **Modifiers**: Optional modifiers are allowed. Incorporates a simple Vi mode toggle to enable/disable these mappings.

## Installation Notes

- Ensure Karabiner-Elements is installed on your macOS system.
- Navigate to `~/.config/karabiner/karabiner.json` or use the Karabiner-Elements GUI to import these rules.
- Adjust or extend these mappings as needed for personal preference.
