# Contributing to WeatherNow

Thank you for your interest in contributing to WeatherNow! This guide explains how to get started and contribute improvements.

## Getting Started

1. Fork the repository on GitHub.
2. Clone your fork locally:

```bash
git clone https://github.com/<your-username>/weathernowapp.git
cd weathernowapp
```

3. Create a new branch for your changes:

```bash
git checkout -b feature/your-feature-name
```

## Development Workflow

- Keep changes focused and small.
- Write clear commit messages.
- Update or add documentation for new features.
- Test before submitting a pull request.

## Running the App

Install dependencies and launch the app:

```bash
flutter pub get
flutter run
```

## Code Style

- Follow Dart and Flutter best practices.
- Prefer descriptive variable and class names.
- Keep the UI and business logic separated.

## Submitting Changes

1. Commit your work to your branch.
2. Push to your fork:

```bash
git push origin feature/your-feature-name
```

3. Open a pull request against the main repository.

## Notes

If the project uses environment variables, add a `.env.example` file rather than committing real secrets.
