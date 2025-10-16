# Simple To‑Do List (Static HTML)

A tiny, fast to‑do list web app implemented in a single HTML file (with inline CSS/JS). It runs entirely in the browser and persists tasks using localStorage. Perfect for GitHub Pages.

## Overview
- Single-file app: easy to host anywhere
- Instant load, no build tools or frameworks
- Add, complete, delete tasks
- Clear all completed tasks
- Tasks are saved locally in your browser
- Accessible labels and keyboard-friendly interactions

License: MIT (see below).

## Setup
You can run this locally or deploy to GitHub Pages.

Local:
- Download index.html
- Double-click to open it in your browser

GitHub Pages:
- Create a new public repository on GitHub (for example: todo-sample)
- Add the provided index.html and this README.md to the repository root
- Commit and push
- In your repo, go to Settings → Pages
- Under “Build and deployment”, choose “Deploy from a branch”
- Set Branch to main (or your default) and folder to / (root)
- Save. Your site will be available at https://<your-username>.github.io/<repo-name> within a minute

Tip: Ensure the file is named exactly index.html at the repository root so GitHub Pages serves it as the default page.

## Usage
- Add a task:
  - Type your task into the input and press Enter or click Add
- Complete a task:
  - Click the checkbox to toggle completion; completed tasks show strikethrough
- Delete a task:
  - Click the trash/delete button on the task
- Clear completed:
  - Click “Clear completed” to remove all completed tasks at once
- Persistence:
  - Tasks are saved in your browser’s localStorage. Clearing site data or switching browsers/devices will reset the list.

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