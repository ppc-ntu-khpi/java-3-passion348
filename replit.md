# Java Gradle Console Application

## Overview
A Java console application that performs mathematical calculations. Built with Gradle using JUnit 5 for testing.

## Project Structure
- `src/domain/Exercise.java` - Core calculation logic (currently computes circle circumference)
- `src/test/TestResult.java` - Main entry point that runs and displays results
- `build.gradle` - Gradle build configuration with `application` plugin

## How to Run
The project runs via Gradle: `gradle run`

## Technical Details
- **Language**: Java 19 (GraalVM CE 22.3.1)
- **Build Tool**: Gradle 8.x
- **Testing**: JUnit Jupiter 5.6.0
- **Source Layout**: Non-standard `src/domain` and `src/test` directories (configured in `build.gradle` sourceSets)
- **Main Class**: `test.TestResult`
