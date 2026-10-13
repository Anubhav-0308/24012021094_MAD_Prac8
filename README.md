# Practical 8 – Hello World iOS App (SwiftUI)

## Aim
Create a basic **Hello World iOS application** using SwiftUI in Xcode.

## Overview
This practical demonstrates how to create a new iOS app project, understand its basic SwiftUI structure, and run it using an iOS Simulator. The app displays the text **“Hello, world!”** on the screen.

## Requirements
- A Mac computer
- Xcode
- An available iOS Simulator

## Steps to Create and Run the App

1. Open Xcode and select **File → New → Project**.
2. Select the **App** template under the iOS section.
3. Configure the project:
   - **Product Name:** `hello world`
   - **Interface:** SwiftUI
   - **Language:** Swift
   - Leave **Core Data** and **Unit Tests** unselected for this basic app.
   - Optionally enable **Create Git repository on my Mac**.
4. Open `hello_worldApp.swift` and review the app entry point.
5. Open `ContentView.swift` and confirm that the main view displays `Text("Hello, world!")`.
6. Choose an iOS Simulator from the device menu in Xcode.
7. Click the **Run (▶)** button to build and launch the app.
8. To preview changes without launching the simulator, open `ContentView.swift` and use the SwiftUI Preview pane.

## Example Code

### `hello_worldApp.swift`

```swift
import SwiftUI

@main
struct hello_worldApp: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}
```

### `ContentView.swift`

```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        Text("Hello, world!")
            .padding()
    }
}
```

## Expected Output
The iOS Simulator displays:

**Hello, world!**

## Concepts Covered
- Creating an iOS app project in Xcode
- Swift and SwiftUI basics
- The `App` protocol and `WindowGroup`
- Creating a view with `Text`
- Running an app in the iOS Simulator
- Previewing SwiftUI views

## Author / Submission
- Practical: 8
- Subject: Mobile Application Development
- Enrollment number shown in the practical PDF: `24012021085`

## Notes
- This project is intended as a beginner-level SwiftUI exercise.
- Xcode and the iOS Simulator require macOS.
