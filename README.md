# 📱 MyFirstApp

A beginner iOS app built with **UIKit** and **Storyboard** that demonstrates core Interface Builder concepts including labels, text fields, buttons, switches, and sliders — all connected to a view controller via IBOutlets and IBActions.

---

## ✨ Features

- **Greeting Label** — Displays a personalized "Hello, [name]" message when the button is tapped
- **Text Field Input** — User enters their name; keyboard is dismissed automatically on submit
- **Student Toggle** — A UISwitch updates a label to reflect "student" or "non-student" status
- **Rating Slider** — A UISlider lets the user select a numeric rating displayed in real time

---

## 🗂 Project Structure

```
MyFirstApp/
├── ViewController.swift      # Main view controller with all IBOutlets and IBActions
├── SceneDelegate.swift       # Standard scene lifecycle boilerplate
├── Main.storyboard           # UI layout built with Interface Builder
├── AppDelegate.swift         # App entry point
├── Assets.xcassets/          # App icons and image assets
└── Info.plist                # App configuration
```

---

## 🔌 IBOutlets & IBActions

### Outlets (UI → Code references)

| Outlet | Type | Description |
|--------|------|-------------|
| `myLabel` | `UILabel` | Displays the greeting or default name |
| `myName` | `UITextField` | Accepts the user's name as input |
| `studentStatus` | `UILabel` | Shows "student" or "non-student" |
| `ratingLabel` | `UILabel` | Displays the current slider rating |

### Actions (User interaction handlers)

| Action | Trigger | Description |
|--------|---------|-------------|
| `myButton` | Button tap | Updates `myLabel` with "Hello [name]" and dismisses the keyboard |
| `selectStudent` | Switch toggle | Updates `studentStatus` based on switch state |
| `myRating` | Slider change | Updates `ratingLabel` with the current integer value |

---

## 🏗 Requirements

- **Xcode** 14 or later
- **iOS** 15.0+
- **Swift** 5.7+
- Framework: `UIKit`

---

## 🚀 Getting Started

1. Clone or download this repository
2. Open `MyFirstApp.xcodeproj` in Xcode
3. Select a simulator or connected device running iOS 15+
4. Press **Run** (`⌘R`)

> No third-party dependencies or additional setup required.

---

## 📖 Concepts Demonstrated

This project is a hands-on introduction to several foundational iOS development concepts:

- Connecting Storyboard UI elements to Swift code using `@IBOutlet` and `@IBAction`
- Handling user input with `UITextField` and dismissing the keyboard with `resignFirstResponder()`
- Responding to control events from `UISwitch` and `UISlider`
- Using `viewDidLoad()` to set initial UI state
- Understanding the UIKit scene lifecycle via `SceneDelegate`

---

## 👩‍💻 Author

Natalie M. Leal — created March 2026 for Texas State University
