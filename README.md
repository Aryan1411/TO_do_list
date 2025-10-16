# Simple To‑Do List (Red Background Edition)

A tiny, fast to‑do list web app implemented as a single HTML file with inline CSS/JS. It runs entirely in your browser and saves tasks to localStorage. This version features a red page background per the new brief, while keeping the task area readable with a clean white card.

## Overview
- Single-file app: dead simple to host anywhere
- Instant load, no frameworks or build steps
- Add, complete, delete tasks
- Clear all completed tasks
- Tasks persist via localStorage
- Accessible labels, keyboard-friendly
- Bold visual style with a red page background

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
  - Click the checkbox to toggle completion; completed tasks show strikethrough
- Delete a task:
  - Click the trash icon on the task
- Clear completed:
  - Click “Clear completed” to remove all completed tasks at once
- Persistence:
  - Tasks are saved in your browser’s localStorage. Clearing site data or switching browsers/devices will reset the list.

## Improvements from Previous Version (Round 2)
- Red background applied to the entire page to match the new brief
- Visual refinement to preserve readability: tasks are displayed on a white, rounded card with subtle shadow over the red background
- Improved accessibility and focus styles for buttons, inputs, and checkboxes
- Slightly clearer toolbar with live-updating task counters

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