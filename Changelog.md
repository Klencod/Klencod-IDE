Klencod IDE - Changelog

This file documents the releases, updates, improvements, and testing performed on Klencod IDE.

Version 2.2.91

Build Number: 8

1. Code Editor

- Improved code editor performance and typing experience.
- Support for smoothly editing large source files containing up to 100,000 lines, without freezing or noticeable lag, as verified through testing.
- Fixed issues and errors that occurred during typing and text editing.
- Support for continuing to edit projects without an internet connection.
- Improved the overall editing experience and handling of source files.

2. Project and File Management

- Improved file and folder management within projects.
- Support for creating, renaming, and importing files and folders.
- Support for selecting and managing multiple files.
- Import projects from ZIP archives.
- Improved handling of large projects.
- Export complete projects as ZIP archives to a location selected by the user.
- View images, videos, and audio files, with the option to open unsupported files using external applications.

3. Local and Cloud Builds

- Integration with Klencod Build Engine for local build operations.
- Local Android project build support using Java and Kotlin.
- Cloud builds through GitHub Actions.
- Cloud build support for Flutter, Java, Kotlin, and React Native projects.
- Real-time build stage and progress monitoring.
- Background build monitoring.
- Ability to cancel build operations and monitor ongoing builds.
- Download generated APK files and add them to the built-app library.

4. GitHub and Git Management

- Sign in to GitHub and manage multiple accounts.
- Create repositories and link them to projects.
- Publish projects and trigger cloud builds.
- Manage local Git changes.
- View file status and create commits.
- Push changes to GitHub and pull updates from repositories.
- Git LFS support for large files.

5. Built-App Library

- Keep access to previously built applications.
- Export APK files to a folder selected by the user.
- Access previously built applications without rebuilding them.

6. Build Logs and Logcat

- Improved build log monitoring interface.
- Clear display of build stages, errors, warnings, and results using distinct colors.
- Search and filter build logs.
- Navigate to the relevant source-code location when error details are available.
- Copy logs and export them as text files.
- Monitor application runtime logs using Logcat.
- Filter Logcat messages by errors, warnings, and informational messages.
- Retain complete logs and export them when needed.

7. Signing Key Management

- Import and manage Android signing keys.
- Store multiple signing keys and select a default key.
- Use the same personal signing identity for both Debug and Release builds, allowing application updates without uninstalling the existing version when the signatures match.

8. General Improvements

- Improved interface design and overall user experience.
- Better interaction with the file tree, code editor, and log panel.
- Improved process stability and background monitoring.
- Better handling of large projects and APK files.
- Improved error messages, loading indicators, and progress reporting.

---

Performance and Reliability Testing

A series of practical tests were performed on Klencod IDE, Git operations, and local builds. These tests included:

Git and Large Project Upload Tests

- Successfully tested uploading a project containing up to 5,000 files without failure.
- Successfully tested uploading a project containing a single 150 MB file.
- Successfully tested uploading a project containing multiple files, including 3 files of 110 MB each.

Project and Local Build Testing

- Tested dozens of diverse projects with different sizes and configurations.
- Successfully completed uploads for the projects included in the tests.
- Successfully completed local builds for the projects included in the tests.
- Tested handling multi-file projects and large projects.

These results demonstrate the application's and build engine's ability to handle large and diverse projects within the tested environment, while performance, stability, and compatibility improvements remain ongoing.

---

Supported Architectures

Klencod Build Engine currently supports:

- ARM64 ("arm64-v8a")
- ARM32 ("armeabi-v7a")

Other architectures, including x86 and x86_64, are not currently supported.

Note About Klencod Build Engine

Klencod Build Engine is currently in Beta.

Although the engine has undergone extensive testing and improvements, some build operations may fail or encounter issues during execution.

Further work is ongoing to improve stability, compatibility, and resolve issues in future releases.

---

Platform: Android

Application: Klencod IDE
