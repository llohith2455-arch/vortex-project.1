# Vortex Tech — App Dev Week 1

## What I Built
A single static Flutter login screen that follows the Week 1 beginner assignment.

The screen includes the required UI elements:
1. **Icon/logo** — a rocket icon inside a soft indigo circle
2. **Heading text** — “Welcome Back”
3. **Subtitle text** — sign-in message
4. **Email input field**
5. **Password input field**
6. **Login button**
7. **Forgot password** text button
8. **Sign Up** row

## Layout Approach
- The main layout uses a `Column` inside `SingleChildScrollView` and `Center`.
- `Padding`, `SizedBox`, and `Container` are used for spacing and visual structure.
- The screen is designed to fit a standard mobile-sized view without absolute positioning.

## How to Run
1. Install Flutter from https://flutter.dev/docs/get-started/install
2. Confirm the setup:
   ```bash
   flutter doctor
   ```
3. Get dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run -d chrome
   ```

## Project Structure
```text
vortextech-appdev-week1/
├── lib/
│   └── main.dart
├── pubspec.yaml
├── README.md
└── screenshots/
```

## Notes
This project is intentionally static and follows the Week 1 requirement of a polished UI without app logic.
