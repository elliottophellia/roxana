# 🦋 Roxana Inspired Color Scheme

Warm, soft, rosy-cocoa colors with creamy surfaces and peach accents.

- **Light** and **Dark** variants
- Designed for **UI themes** and **syntax themes**
- Easy to port (single source of truth)

## Table of Contents

- [Ports](#ports)
- [Usage](#usage)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)

## Ports

> Want a port? Open an issue with screenshots and the target app/editor.

| Port | Status | Repository | Notes |
|---|---:|---|---|
| Discord | ✅ | [source]() | - |
| OldTwitter | ✅ | [source]() | - |


## Usage

### Use a port
Each port lives in `ports/<name>/` with its own instructions.

Example:
- `ports/discord/` - Discord theme
- `ports/oldtwitter/` - Old Twitter theme

### Use the raw tokens
If you’re building your own port, use the tokens from:

- `tokens/roxana.light.json`
- `tokens/roxana.dark.json`

Those files are the **source of truth**. Ports should be generated or mapped from them.

## Development

### Repo structure


```
.
├─ tokens/
│ ├─ roxana.light.json
│ └─ roxana.dark.json
├─ ports/
│ ├─ discord/
│ ├─ oldtwitter/
│ └─ ...
├─ README.md
└─ LICENSE
```

### Adding a new port

1. Create a folder: `ports/<app>/`
2. Add:
   - `README.md` (install / usage steps)
   - the theme file(s)
   - screenshots (optional but appreciated)
3. Keep naming consistent:
   - `roxana-light`
   - `roxana-dark`

## Contributing

Contributions are welcome:
- New ports
- Fixes for existing ports
- Better mappings for app-specific tokens

### Guidelines

- Keep ports faithful to the tokens.
- Don’t “freestyle” extra colors unless the target format requires it.
- If you must introduce derived colors (alpha/hover), document how they’re derived.

## License

```
MIT License

Copyright (c) 2025 Reidho Satria

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```