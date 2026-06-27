# Flutter Learning Log

Working app name: **Termly**

Termly is a student productivity app for tracking courses, tasks, schedules, grades, and study resources while learning Flutter properly along the way.

## Why This Exists

This file is my learning journal. Every time I build a feature, I will also write down the Flutter concept I learned from it.

The goal is not only to finish the app. The goal is to understand how the app works.

## Current Stage

### Lesson 1: Flutter App Entry Point

What I learned:

- `main()` is where the Flutter app starts.
- `runApp()` puts the root widget on the screen.
- `MaterialApp` gives the app Material Design structure, routing, themes, and app-level configuration.
- `title` names the app, but it does not show visible text on the screen.
- `home` decides which screen opens first.
- A `Widget` describes UI.
- `ThemeData` is not a widget. It is a configuration object used by widgets.

Example mental model:

```text
main()
  -> runApp()
    -> MyApp
      -> MaterialApp
        -> home: FirstScreen
```

## Flutter Concepts To Track

- [x] `main()` and `runApp()`
- [x] `MaterialApp`
- [x] `title` vs `home`
- [x] `StatelessWidget`
- [ ] `Scaffold`
- [ ] `Text`
- [ ] `Center`
- [ ] `Column`
- [ ] `Row`
- [ ] `Container`
- [ ] `Padding`
- [ ] `SizedBox`
- [ ] `StatefulWidget`
- [ ] `setState`
- [ ] Forms and validation
- [ ] Navigation
- [ ] Local models
- [ ] Lists and dynamic UI
- [ ] State management
- [ ] Supabase Auth
- [ ] Supabase database CRUD
- [ ] Local-first persistence

## Daily Reflection Template

### Day 1

Date: 27/06/2026

Built: nothing yet!

Flutter concept learned: learnt how the default counter app actually works in flutter

What confused me: widgets vs simple objects

What clicked: related dart to the concepts of OOP i've learnt which ade it easier to start

Next step: build my first screen in Termly

