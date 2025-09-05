# 🧠 Brainf**k IDE — LeetCode Style (Tape = Framebuffer)

A **web-based Brainf**k IDE** with a modern LeetCode-inspired interface.  
It features a **tape-as-framebuffer visualizer**, interactive console, and real-time memory/tape view for rapid development of Brainf**k programs that manipulate pixels directly.

**Live Demo:** [https://freeboardtortoise.github.io/brainfuck-game-engine](https://freeboardtortoise.github.io/brainfuck-game-engine)

---

## Features

- **Two-column layout** (Editor + Tabs) for coding and visualization
- **Tape as Framebuffer**  
  Use the Brainf**k tape to draw graphics on a 320×200 canvas
- **Interactive console** for I/O via `.` and `,`
- **Memory/Tape viewer** shows values and highlights the current pointer
- **Toolbar controls**:
  - Run, Step, Pause, Reset
  - Adjust execution speed
  - Save, Load, Export, and Import projects
  - Toggle themes (light/dark)
- **Keypad** for quick insertion of Brainf**k commands
- **Performance-friendly**: throttled rendering, expandable memory

---

## Usage

1. Open the live demo [here](https://freeboardtortoise.github.io/brainfuck-game-engine) **or** open `index.html` locally in a modern browser.
2. Write your Brainf**k code in the editor.
3. Use the **Run**, **Step**, **Pause**, or **Reset** buttons to control execution.
4. Monitor output via:
   - **Framebuffer tab** — graphics output
   - **Console tab** — text output
   - **Tape tab** — full memory visualization
5. Adjust **speed** using the slider to control execution bursts.
6. Save and load code locally or export/import `.bfi` JSON files.

---

## Examples

```bf
+[>+.]  # Gradually paints the screen
+++++[>+++++.<-]  # Paints stripes
