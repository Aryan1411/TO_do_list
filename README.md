# Simple To‑Do List (Red Background Edition)

A tiny, fast to‑do list web app implemented as a single HTML file with inline CSS/JS. It runs entirely in your browser and saves tasks to localStorage. This version features a bold red page background while keeping the task area readable on a clean white card.

## Overview
- Single-file app: dead simple to host anywhere
- Instant load, no frameworks or build steps
- Add, complete, delete tasks
- Clear all completed tasks
- Tasks persist via localStorage
- Accessible labels, keyboard-friendly, visible focus rings
- Red page background as requested, with high-contrast, readable task UI

License: MIT.

## Setup
Local
- Download index.html
- Double‑click to open in your browser

GitHub Pages
- Create a new public repository
- Add index.html and this README.md to the repository root
- Commit and push
- In your repo, go to Settings → Pages
- Under “Build and deployment”, choose “Deploy from a branch”
- Set Branch to main and Folder to / (root), then Save
- Your site will be available at https://<your-username>.github.io/<repo-name> shortly

Tip: Make sure the main file is named exactly index.html in the repository root.

## Usage
- Add a task:
  - Type your task into the input and press Enter or click Add
- Complete a task:
  - Click the checkbox (or the task text) to toggle completion; completed tasks show strikethrough
- Delete a task:
  - Click the trash icon on the task
- Clear completed:
  - Click “Clear completed” to remove all completed tasks at once
- Persistence:
  - Tasks are saved in your browser’s localStorage. Clearing site data or switching browsers/devices will reset the list.

## Improvements from Previous Version (Round 2)
- Applied a solid red background to the entire page to meet the new brief
- Preserved readability with a white, rounded task card and subtle shadow over the red background
- Clearer, accessible focus styles for inputs and buttons
- Live-updating counters showing remaining and total tasks
- Minor rendering optimizations (event delegation and partial row updates)

## License
MIT License

Copyright (c) 2025 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.