# Modern Scientific Calculator

A polished scientific calculator built with **customtkinter** (modern rounded UI).  
Designed in a Windows-style expanded layout with scientific functions and keyboard support.

## Features

- Dark theme, rounded controls (customtkinter)
- Expanded scientific layout (multiple rows)
- Scientific functions: `sin, cos, tan, asin, acos, atan, log (base 10), ln (natural log), sqrt`
- Constants: `pi`, `e`
- Power: `^` or `**`
- Extra: `x^2`, `x^3`, `1/x`, `%`, `mod`
- Angle mode toggle: **Degrees** (default) / Radians
- Keyboard support:
  - `Enter` → Evaluate
  - `Backspace` → Delete
  - `Esc` → Clear
  - Numbers and operators supported via keyboard
- Uses a restricted `eval` environment with whitelisted functions for improved safety

## Install

1. Create (optionally) a virtual environment:
```bash
python -m venv venv
source venv/bin/activate   # on Windows: venv\\Scripts\\activate
