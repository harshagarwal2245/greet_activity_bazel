# Android basic app

Welcome to `android app development` – an Android app demonstrating Bazel build system integration for efficient Android development!

## Overview

This project showcases a simple Android application that displays personalized greeting messages based on user input. The app is built using Bazel, a powerful build tool known for its speed, reliability, and scalability.

### Key Features

- Personalized greeting message based on user input
- Integration with Bazel build system for optimized builds

## Technologies Used

- **Bazel**: Efficient and scalable build tool
- **Android Development**: Standard Android practices including activities, layouts, and resource management
- **Java & XML**: Backend logic implemented in Java, user interface defined in XML

## Getting Started

### Prerequisites

- Android Studio
- Bazel (install instructions [here](https://docs.bazel.build/versions/main/install.html))

### Build and Run

1. Clone the repository:

   ```bash
   git clone https://github.com/harshagarwal2245/greet_activity_bazel.git
   ```
2. Navigate to the project directory:
  ```bash
    cd greet_activity_bazel
  ```
3. Build the Android app using Bazel:
```bash
   bazel build //...
```
4. Run the app using adb
   ```bash
   bazel mobile-install --start_app //src/main:app
   ```
## Download Apk file

Under release tab also you can download apk file on mobile

### Contributing

Contributions are welcome! Feel free to open issues and submit pull requests to contribute improvements, new features, or bug fixes.

### License

This project is licensed under the MIT License - see the LICENSE file for details.
   
