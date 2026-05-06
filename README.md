# HW05 — Flutter Quiz Platform

HW05 is a professional, cross-platform Flutter quiz application designed to deliver an engaging assessment experience with a clean user interface, scalable structure, and a clear foundation for competitive score tracking. The project is configured to run from a single codebase across Android, iOS, Web, Windows, Linux, and macOS.

## Overview

HW05 is positioned as a modern quiz platform focused on usability, maintainability, and extensibility. It is organized around the full quiz lifecycle:

- **Setup:** configure and initialize a quiz session.
- **Quiz Flow:** present questions and collect responses.
- **Summary:** review performance and outcome metrics.
- **Leaderboard:** track and compare results.

This structure supports both educational and training-oriented quiz use cases while remaining straightforward for contributors to extend.

## Core Value

- **Cross-Platform Reach:** one application architecture, multiple deployment targets.
- **Modular Design:** dedicated screen boundaries for each stage of the quiz journey.
- **Developer-Friendly Foundation:** standard Flutter conventions and linting for consistent quality.
- **Scalable Direction:** architecture that can be expanded with persistence, analytics, richer question types, and enhanced game mechanics.

## Technical Profile

- **Framework:** Flutter with Material Design.
- **Language/SDK:** Dart (SDK constraint `^3.5.3`).
- **Code Quality:** `flutter_lints` via `analysis_options.yaml`.
- **Testing:** widget test setup under `test/`.
- **Project Configuration:** standard Flutter multi-platform layout and build files.

## Project Layout

```text
lib/
  main.dart
  setup_screen.dart
  quiz_screen.dart
  summary_screen.dart
  leaderboard_screen.dart

test/
  widget_test.dart
```

## Getting Started

### Prerequisites

- Flutter SDK installed and available in your `PATH`.
- A configured target runtime (emulator, simulator, browser, or desktop runtime).

### Install dependencies

```bash
flutter pub get
```

### Run the application

```bash
flutter run
```

### Run automated tests

```bash
flutter test
```

### Run static analysis

```bash
flutter analyze
```

## Use Cases

HW05 is well-suited for:

- Classroom knowledge checks.
- Technical interview practice.
- Internal team learning programs.
- Competitive quiz events with score comparison.

## License

No explicit license file is currently included in this repository.
