# Termly

Termly is a Flutter-based student productivity app designed to help students manage their semester from one clean mobile dashboard. The MVP focuses on courses, tasks, weekly schedules, grades, and study materials.

This project is also a learning journey. The goal is not only to build a working app, but to build a strong Flutter foundation while making it.

## Project Status

Termly is currently in the early learning and setup phase.

Current focus:

- Understanding the default Flutter counter app
- Learning how `main.dart`, `runApp`, `MaterialApp`, and widgets work
- Building the first visible screen from scratch
- Tracking Flutter concepts in [learning.md](./learning.md)

## MVP Scope

The MVP is based on the Termly Flutter App MVP Screens design and includes:

- Welcome screen
- Login / sign up screen
- First semester setup
- Dashboard / Today overview
- Tasks and deadlines
- Weekly schedule
- Courses list
- Course detail page
- Grades and GPA overview
- Add task form

## Tech Stack

Planned stack:

- **Flutter** for the mobile app
- **Dart** as the programming language
- **Supabase** for authentication, database, and sync
- **Local-first storage** for an offline-friendly student workflow

The app will start local-first so the Flutter fundamentals are clear before backend complexity is added.

## Learning-First Approach

Every feature in Termly is paired with a Flutter concept.

## Planned App Architecture

The project will likely use this structure once the Flutter app is scaffolded:

```text
lib/
  main.dart
  core/
    theme/
    constants/
  features/
    auth/
    dashboard/
    tasks/
    schedule/
    courses/
    grades/
  shared/
    widgets/
    models/
```

This may evolve as the app grows.

## Roadmap

### Phase 1: Flutter Basics

- [ ] Understand the counter app
- [ ] Build the first screen
- [ ] Learn core layout widgets
- [ ] Create reusable UI components

### Phase 2: Local MVP

- [ ] Add course model
- [ ] Add task model
- [ ] Build task list
- [ ] Build add task form
- [ ] Build dashboard summary
- [ ] Build course and schedule screens

### Phase 3: State and Persistence

- [ ] Add state management
- [ ] Store data locally
- [ ] Add filtering and completed tasks
- [ ] Calculate grade and GPA summaries

### Phase 4: Supabase

- [ ] Add authentication
- [ ] Create database schema
- [ ] Add row-level security
- [ ] Sync courses, tasks, and grades

### Phase 5: Polish

- [ ] Match the Figma design closely
- [ ] Add loading, empty, and error states
- [ ] Test main user flows
- [ ] Prepare a demo build


## Author

Built by Areeba as a Flutter learning project and semester productivity MVP.