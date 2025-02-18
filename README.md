<!-- Warning! This file will be included in the wheel package.Please do not use relative paths. -->

# TtkText

[简体中文](https://github.com/Jesse205/TtkText/blob/main/README_zh.md) |
**English** |
<small>More translations are welcome!</small>

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](./CODE_OF_CONDUCT.md)

Themed Tkinter Text widget with modern styling support.

## Features

- 🎨 Theme-aware text widget that automatically adapts to ttk themes
- 📜 Built-in ScrolledText component with vertical/horizontal scrollbars
- 🖥️ Native integration with ttk styles and themes
- 🔄 Dynamic theme switching support

## Installation

```bash
pip install ttk-text
```

## Quick Start

```python
from tkinter import Tk
from ttk_text import ThemedText
from ttk_text.scrolled_text import ScrolledText

root = Tk()
themed_text = ThemedText(root)
themed_text.pack(fill="both", expand=True)

scrolled_text = ScrolledText(root)
scrolled_text.pack(fill="both", expand=True)

root.mainloop()
```

## Screenshots

<div>
<img src="./doc/images/screenshots/windows11.webp" alt="Windows 11" width="302">
<img src="./doc/images/screenshots/windows10.webp" alt="Windows 10" width="301">
<img src="./doc/images/screenshots/windows7.webp" alt="Windows 7" width="314">
</div>

Example screenshots of Windows 11, Windows 10, and Windows 7.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for details.
