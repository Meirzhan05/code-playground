# Code Playground 🎮

A collection of interactive web-based tools for coding, prototyping, and learning — all in your browser, no server required.

## Projects

### 🖥️ Code Playground v2 (`index-v2.html`)
A full-featured live HTML/CSS/JS editor with:
- **Console panel** — see `console.log()` output in real time
- **Syntax highlighting** — CodeMirror-powered editing
- **Project system** — save, load, and switch between projects
- **Snippet library** — reusable code templates
- **Line numbers** — gutter with clickable line numbers
- **Mobile layout** — responsive design for phones
- **Undo/redo** — full history for edits
- **Auto-save** — localStorage persistence
- **Export** — download your project as a single HTML file

### 🖥️ Code Playground v1 (`index.html`, `index-v1.html`)
The original live editor — simpler, lighter, same core functionality:
- Live preview as you type HTML/CSS/JS
- Dark theme
- localStorage auto-save
- Export to file

### 📝 Markdown Previewer (`markdown-previewer.html`)
Live Markdown rendering with:
- Split-pane editor + preview
- GitHub-flavored Markdown support
- Dark theme
- Export rendered HTML

### 🧠 RISC-V VM/OS Simulator (`vm-simulator.html`)
A full RISC-V (RV32IM) virtual machine and operating system simulator in the browser:
- **CPU**: RV32IM instruction set — arithmetic, memory, branches, jumps, CSR
- **Assembler**: custom RISC-V assembler with labels, registers, immediates
- **Kernel**: preemptive round-robin scheduler, syscalls (print, read, exec, exit, yield)
- **5 demo programs**: Hello World, Fibonacci, Prime Sieve, Conway's Game of Life, Mandelbrot
- **Debugger UI**: step through instructions, inspect registers/memory, set breakpoints
- **Terminal**: interactive I/O via a built-in terminal emulator

## Usage

Open any `.html` file directly in your browser. No build tools, no npm, no server needed.

```bash
# Clone the repo
git clone https://github.com/Meirzhan05/code-playground.git

# Open any file
open code-playground/index-v2.html
```

## Tech Stack

- **Vanilla HTML/CSS/JS** — zero dependencies (except CodeMirror for syntax highlighting in v2)
- **localStorage** — persistence without a backend
- **Dark theme** — easy on the eyes

## License

MIT — free to use, modify, and share.
