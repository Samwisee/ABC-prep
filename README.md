# Android Kotlin Interview Checklist

## Pre-Interview Preparation

### Environment Check
- [ ] Update Android Studio to the latest stable version.
- [ ] Ensure the Kotlin plugin is up-to-date.
- [ ] Test emulator and/or real device for quick deployment.

### Quick Review
- [ ] Refresh key Kotlin language features.
- [ ] Go over Android architecture components and Jetpack libraries.

### Essential Libraries
- [ ] Review usage of essential libraries (Hilt/Dagger, Retrofit, Coroutines, etc.).

---

## After Receiving the Sample Application

### Initial Steps
- [ ] Clone or download the project.
- [ ] Open the project in Android Studio.
- [ ] Perform initial Gradle sync and resolve any dependency issues.

### First Run
- [ ] Build and run the application on an emulator or real device.
- [ ] Note down any immediate issues or bugs.

### Codebase Familiarization
- [ ] Review the project's structure.
- [ ] Examine `build.gradle` files for dependencies and SDK versions.
- [ ] Look for any README or documentation.

---

## Tasks and Code Modification

### Task Prioritization
- [ ] List down tasks to be done and prioritize them.
  
### Feature Implementation/Modification
- [ ] Start coding or modifying as per the tasks.
- [ ] Stick to Kotlin best practices and Android guidelines.
  
### Code Optimization
- [ ] Look for code that can be refactored or optimized.

### Adherence to Architecture
- [ ] Make sure changes align with the existing or improved architecture pattern (MVVM, MVI, etc.).

### Use Kotlin Features
- [ ] Utilize Kotlin's language features effectively (data classes, extension functions, sealed classes, etc.).

---

## Final Steps

### Testing
- [ ] Manually test the changes.
- [ ] Write unit tests if time permits.

### Debugging and Profiling
- [ ] Use Android Studio Profiler to check for performance issues if time allows.

### Documentation and Comments
- [ ] Add necessary comments or documentation for the changes.

### Review
- [ ] Take a final look at the code for anything missed.
- [ ] Prepare to explain your reasoning and decisions during the interview.

# Android Kotlin Code Review Checklist

## Pre-Review Preparation

### Familiarize with Tools
- [ ] Get accustomed to any code review tools that may be used (e.g., Gerrit, Crucible).
- [ ] Prepare a code review template or checklist to jot down your observations.

---

## Initial Codebase Assessment

### High-Level Overview
- [ ] Review the architecture and design patterns used in the project.
- [ ] Look for architectural smells or inconsistencies.
  
### Dependencies and Build
- [ ] Check `build.gradle` files for outdated or unnecessary dependencies.
- [ ] Note if there are custom build configurations or scripts.

### Documentation
- [ ] Examine the presence and quality of documentation (comments, README, Wiki).
  
---

## Deep Dive into Code

### Kotlin Best Practices
- [ ] Check the usage of Kotlin idioms and language features.
- [ ] Look for appropriate null-safety handling.

### Android Specifics
- [ ] Assess the usage of Android components (Activity, Service, etc.).
- [ ] Examine the use of Android Jetpack libraries and AndroidX.

### Code Quality
- [ ] Look for code smells like large methods/classes, tight coupling, etc.
- [ ] Identify any anti-patterns or bad practices.
  
### Error Handling and Logging
- [ ] Check how errors and exceptions are handled.
- [ ] Verify that sensitive information is not logged.

### Asynchronous Code
- [ ] Examine the use of asynchronous mechanisms like Coroutines, RxJava, etc.
- [ ] Look for potential thread-safety issues or race conditions.

---

## Performance and Optimization

### Resource Utilization
- [ ] Check for any leaks (memory, file handles, etc.)
- [ ] Look for inefficient use of resources (CPU, disk, network).

### Algorithmic Efficiency
- [ ] Identify inefficient algorithms or data structures.

---

## Final Review Steps

### Notes and Recommendations
- [ ] Jot down your notes and prepare recommendations.
  
### Prepare for Discussion
- [ ] Be prepared to discuss your findings constructively.
- [ ] Have alternative solutions and explanations for your recommendations.

