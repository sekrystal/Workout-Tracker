# Workout Tracker
Privacy-friendly iOS workout tracking application built with SwiftUI that helps users track their fitness journey, manage workouts, and monitor progress.

## Features

- Track different types of workouts (Strength, Cardio, Flexibility)
- Create and manage custom exercise routines
- Log sets, reps, weights, and durations for exercises
- Target specific muscle groups
- Track workout completion and progress
- Clean and intuitive SwiftUI interface

## Requirements

- iOS 14.0+
- Xcode 13.0+
- Swift 5.5+

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/Workout.git
```

2. Open the project in Xcode:
```bash
cd Workout
open Workout.xcodeproj
```

3. Build and run the project in Xcode using ⌘+R or the play button.

## Project Structure

- `Models.swift` - Core data models for exercises, workouts, and routines
- `WorkoutManager.swift` - Manages workout state and data persistence
- `ContentView.swift` - Main UI views and navigation
- `WorkoutApp.swift` - App entry point and configuration

### Data Models

#### Exercise
- Tracks individual exercises with properties for:
  - Name, category, and target muscle groups
  - Default sets, reps, weight, and duration
  - Completion status

#### Workout
- Represents a complete workout session with:
  - Category (Strength/Cardio/Flexibility)
  - List of exercises
  - Date and duration
  - Completion status

#### Routine
- Stores workout templates with:
  - Name and description
  - List of exercises with default values
  - Creation date

## Usage

1. Launch the app
2. Create a new workout or select an existing routine
3. Add exercises to your workout
4. Track your sets, reps, and weights as you complete exercises
5. Mark exercises and workouts as complete
6. Review your workout history and progress

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
