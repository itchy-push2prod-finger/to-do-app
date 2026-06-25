# To-Do App — AJ & Qwen's First Joint Project (we lit)

## About
A simple to-do app built with vanilla HTML, CSS, and JavaScript. No frameworks, no libraries — just the fundamentals.

## Technologies
- HTML
- CSS
- JavaScript (vanilla)

---

## Requirements

Each requirement below is its own chunk of work. Commit after each one so we build a clean git history together.

### Phase 1 — HTML Structure
- AJ [x] **1.1** Create the page skeleton: `<!DOCTYPE html>`, `<head>`, `<body>`
- Qwen [x] **1.2** Add a heading (e.g. "My To-Do List")
- AJ [ ] **1.3** Add a text input and an "Add" button side by side
- AJ [ ] **1.4** Add an empty `<ul>` or `<ol>` where tasks will appear

### Phase 2 — CSS Styling
- Qwen [ ] **2.1** Center the app on the page and give it a max-width
- AJ [ ] **2.2** Style the heading, input, and button so they look clean
- Qwen [ ] **2.3** Style each task item (padding, border, readable font size)
- AJ [ ] **2.4** Add a style for "completed" tasks (e.g. strikethrough + gray text)

### Phase 3 — JavaScript: Add Tasks
- AJ [ ] **3.1** Select the input, button, and list from the DOM
- Qwen [ ] **3.2** Write a function that reads the input value and creates a new `<li>`
- AJ [ ] **3.3** Append the new `<li>` to the list when the button is clicked
- Qwen [ ] **3.4** Clear the input field after a task is added
- AJ [ ] **3.5** Prevent adding an empty task (show an alert or just do nothing)

### Phase 4 — JavaScript: Complete Tasks
- AJ [ ] **4.1** When a task is clicked, toggle it as "completed" (add/remove the CSS class)

### Phase 5 — JavaScript: Delete Tasks
- AJ [ ] **5.1** Add a "Delete" button inside each task `<li>` when it's created
- Qwen [ ] **5.2** When the delete button is clicked, remove that `<li>` from the list

### Phase 6 — Stretch Goals (optional, tackle in any order)
- [ ] **6.1** Save tasks to `localStorage` so they persist after a page refresh
- [ ] **6.2** Load saved tasks from `localStorage` when the page first loads
- [ ] **6.3** Add a "Clear All" button that removes every task at once
- [ ] **6.4** Show a count of how many tasks are remaining (not yet completed)

---

## Git Flow — How We're Working Together

1. Pull the latest `main` before starting any chunk: `git pull origin main`
2. Pick a requirement above, do the work, then commit with a clear message:
   - `git add <file(s)>`
   - `git commit -m "feat: add HTML structure for task list (1.1–1.4)"`
3. Push your branch and open a PR for the other person to review
4. Check off the box in this README when a requirement is done
5. Switch off — one person does a phase, the other reviews/merges, then picks the next chunk

## Commit Message Style
- `feat:` for new functionality
- `style:` for CSS-only changes
- `fix:` for bug fixes
- `chore:` for housekeeping (updating README, etc.)
