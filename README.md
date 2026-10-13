# 24012021094_Anubhav_kanthariya_P8_MAD

# MAD Practical 8 – Hello World iOS App Using SwiftUI

## 📱 Project Overview

This project demonstrates how to create a basic iOS application using **SwiftUI and the Swift programming language**. The application displays a simple **"Hello, world!"** message on the screen.

This practical is part of the Mobile Application Development (MAD) coursework and introduces the basic structure of an iOS application using Xcode and SwiftUI.

## 🎯 Aim

To create your first Hello World iOS application using SwiftUI.

## 🛠️ Technologies Used

- **Programming Language:** Swift
- **UI Framework:** SwiftUI
- **IDE:** Xcode
- **Platform:** iOS
- **Testing Environment:** iOS Simulator
- **Version Control:** Git

## ✨ Features

- Displays a "Hello, world!" message.
- Uses SwiftUI to create the user interface.
- Implements a basic SwiftUI view.
- Uses `.padding()` to add spacing around the text.
- Supports live previews in Xcode.
- Runs using an iOS Simulator.

## 📂 Project Structure

```text
hello-world/
├── hello_worldApp.swift
├── ContentView.swift
├── Assets.xcassets/
└── Preview Content/
```

### File Descriptions

**1. `hello_worldApp.swift`**

This file contains the application entry point. The `@main` attribute marks the main application structure, and `WindowGroup` displays the main `ContentView`.

**2. `ContentView.swift`**

This file defines the main user interface using SwiftUI. It displays the text `"Hello, world!"` with padding.

**3. `Assets.xcassets`**

This folder stores app resources such as images and app icons.

**4. `Preview Content`**

This folder can contain resources used for previewing the interface in Xcode.

## 💻 Source Code

### 1. Application Entry Point

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

**Explanation:**

- `import SwiftUI` imports the SwiftUI framework.
- `@main` identifies the application entry point.
- `struct hello_worldApp: App` defines the app structure.
- `WindowGroup` creates the app's main scene.
- `ContentView()` displays the main user interface.

### 2. User Interface

```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        Text("Hello, world!")
            .padding()
    }
}
```

**Explanation:**

- `struct ContentView: View` defines a SwiftUI view.
- `var body: some View` describes the view's interface.
- `Text("Hello, world!")` displays the message on the screen.
- `.padding()` adds space around the text.

## ⚙️ Requirements

- A Mac computer running a compatible version of macOS.
- Xcode installed.
- Swift and SwiftUI support.
- An iOS Simulator or a compatible iPhone for testing.

## 🚀 Steps to Create and Run the Project

1. Open Xcode on your Mac.
2. Select **File → New → Project**.
3. Choose the **App** template under the iOS section.
4. Set the product name to `hello world`.
5. Select **SwiftUI** as the interface.
6. Select **Swift** as the programming language.
7. Leave Core Data and unit testing options unchecked for this basic app.
8. Save the project.
9. Open `hello_worldApp.swift` and review the application entry point.
10. Open `ContentView.swift` and verify the Hello World code.
11. Select an iOS Simulator from the device menu.
12. Click the **Run ▶** button.
13. Verify that the simulator displays **"Hello, world!"**.
14. Use the SwiftUI Preview pane in `ContentView.swift` to preview interface changes.

## 🧪 Expected Output

The application displays a simple screen containing:

**Hello, world!**

The text appears with padding around it, demonstrating a basic SwiftUI layout.

## 📸 Screenshots

Add screenshots of the running application here.

Example:

```markdown
![Hello World iOS App](screenshots/hello-world.png)
```

Create a `screenshots` folder in the repository and add your actual screenshot using the filename `hello-world.png` if you want to use the example above.

## 📚 Learning Outcomes

After completing this practical, students will understand:

- How to create an iOS project in Xcode.
- The basic structure of a SwiftUI application.
- The role of the `@main` application entry point.
- How to create a view using the `View` protocol.
- How to display text using the `Text` view.
- How to apply modifiers such as `.padding()`.
- How to run an application using the iOS Simulator.
- How to preview UI changes directly in Xcode.

## 👨‍💻 Author

- **Name:** Anubhav Kanthariya
- **Enrollment Number:** 24012021094
- **Subject:** Mobile Application Development
- **Practical Number:** 8

## 📝 Conclusion

This practical introduces the fundamentals of iOS application development using SwiftUI. By creating a simple Hello World application, students learn how to configure an Xcode project, understand the application entry point, create a basic user interface, and run the application in the iOS Simulator.
