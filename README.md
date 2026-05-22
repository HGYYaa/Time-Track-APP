# Time Track App

A lightweight task and sprint management web application built with HTML, CSS, and JavaScript. The project is designed to help small teams manage a product backlog, create sprints, track task status, and organise work in a simple browser-based interface.

## Overview

Time Track App is a frontend project for agile task planning and sprint tracking. It provides separate pages for product backlog management, sprint overview, and sprint details. Users can create tasks, assign task metadata, filter backlog items, create sprints, and view sprint information through a Material Design styled interface.

This project was developed as an early web development coursework project and focuses on DOM manipulation, reusable JavaScript classes, local state management, and multi-page frontend interaction without a backend service.

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Material Design Lite
- Bootstrap
- Browser LocalStorage / client-side state handling

## Key Features

- Product backlog page for creating and displaying tasks.
- Task metadata management, including title, description, assignee, type, tag, difficulty, priority, and state.
- Task filtering and card-based task display.
- Sprint overview page for creating and viewing sprints.
- Sprint detail page for organising tasks by status.
- Multi-page navigation between backlog and sprint views.
- Reusable JavaScript classes for tasks, sprints, and application-level data management.
- Responsive UI layout using Material Design Lite and Bootstrap.

## Project Structure

```text
Time-Track-APP/
├── css/
│   ├── main.css
│   ├── product_backlog.css
│   └── sprints.css
├── html/
│   ├── product_backlog.html
│   ├── sprint_detail.html
│   └── sprint_overview.html
├── script/
│   ├── shared.js
│   ├── sprint_detail.js
│   ├── sprint_functions.js
│   └── task_function.js
└── README.md
```

## Main Pages

### Product Backlog

The product backlog page allows users to create, display, search, and filter tasks. Each task can include information such as assignee, task type, tag, difficulty, priority, and current progress state.

### Sprint Overview

The sprint overview page allows users to create and view sprint records, including sprint name, duration, and current status.

### Sprint Detail

The sprint detail page is intended to organise sprint tasks by status, such as pending, in progress, and completed, helping users monitor sprint progress.

## My Role

- Implemented frontend pages using HTML, CSS, and JavaScript.
- Built task creation, display, filtering, and sprint management interactions through DOM manipulation.
- Designed reusable JavaScript data structures for task and sprint records.
- Styled the interface using Material Design Lite, Bootstrap, and custom CSS.

## How to Run

This is a static frontend project and does not require a backend server.

1. Clone the repository:

```bash
git clone https://github.com/your-username/time-track-app.git
```

2. Open the main page in a browser:

```text
html/product_backlog.html
```

Alternatively, use a local static server such as VS Code Live Server for a smoother development experience.

## Notes

- This is an early-stage coursework project focused on frontend fundamentals.
- The project uses browser-side JavaScript and does not include a production backend.
- No sensitive credentials or API keys are required.
