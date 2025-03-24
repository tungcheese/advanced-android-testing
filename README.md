This repository contains sample code for testing an Android application using the MVVM architecture with ViewModel, LiveData, and Repository patterns. The focus is on unit testing and UI testing in the To-Do app.

## Self Introduction

Name: Nguyen Tuan Vu

StudentID: 22110091

## Overview

The project is part of Google's Advanced Android Testing course, demonstrating best practices for writing tests in Android applications. The code includes unit tests, instrumentation tests, and UI tests using JUnit, Mockito, and Espresso.

## TasksViewModelTest.kt

The `TasksViewModelTest.kt` file contains unit tests for the `TasksViewModel` class, ensuring the ViewModel behaves correctly under different scenarios.

### Key Features:
- Uses JUnit and Mockito for unit testing.
- Tests ViewModel logic without requiring an actual UI or database.
- Verifies LiveData updates correctly.
- Mocks repository dependencies to isolate ViewModel behavior.

### Example Test Cases:
- Checking if the ViewModel loads tasks correctly.
- Filtering active or completed tasks.
- Verifying empty states and error handling.

## Technologies Used
- **Kotlin** for programming language.
- **Android ViewModel** for UI-related data management.
- **LiveData** for observable data streams.
- **JUnit** for unit testing.
- **Mockito** for mocking dependencies.
- **Espresso** for UI testing.

## Running the Tests
To execute the tests:
1. Open the project in Android Studio.
2. You need to build this project in JDK version 11 by navigating to **Files -> Settings -> Build, Execution, Deployment -> Build Tools -> Gradle**, then download or use JDK version 11 if you have it.
3. Navigate to `TasksViewModelTest.kt` or `StatisticsUtilsTest.kt`.
4. Select any function you want to test.
