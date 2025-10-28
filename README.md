# 🌦️ Mood Weather

A minimal, elegant single-screen SwiftUI app that changes its background and animation based on your selected mood.

## ✨ Features

- **4 Mood Options**: ☀️ Happy, 🌧️ Sad, 🌩️ Angry, 🌈 Calm
- **Beautiful Gradients**: Each mood has its own calming color palette
- **Smooth Animations**: Pulsing icons and seamless transitions
- **Pure SwiftUI**: No external dependencies
- **Random Start**: App launches with a random mood and gentle fade-in

## 📁 Project Structure

```
MoodWeatherApp/
├── MoodWeatherApp.swift        # App entry point
├── Models/
│   └── Mood.swift              # Mood enum with colors & SF Symbols
├── Views/
│   ├── ContentView.swift       # Main screen UI
│   └── MoodButton.swift        # Reusable mood button
└── ViewModels/
    └── MoodViewModel.swift     # State management
```

## 🚀 How to Use

### Option 1: Create Xcode Project Manually

1. Open Xcode
2. Create a new iOS App project:
   - Product Name: **MoodWeatherApp**
   - Interface: **SwiftUI**
   - Language: **Swift**
3. Replace the default files with the ones from this folder
4. Make sure the folder structure matches the project structure
5. Build and run (⌘R)

### Option 2: Use Command Line

Run the following command from the `/Users/apple/Desktop/Moody` directory:

```bash
cd /Users/apple/Desktop/Moody
# The script will be created to automate Xcode project creation
```

## 🎨 Mood Details

| Mood | Emoji | SF Symbol | Gradient Colors |
|------|-------|-----------|-----------------|
| Happy | ☀️ | sun.max.fill | Warm yellow → Soft orange |
| Sad | 🌧️ | cloud.rain.fill | Muted blue → Deep blue-grey |
| Angry | 🌩️ | cloud.bolt.fill | Soft red → Deep purple-red |
| Calm | 🌈 | cloud.sun.fill | Soft cyan → Mint green |

## 🧪 SwiftUI Previews

Each view includes `#Preview` macros for live canvas preview in Xcode.

## 📱 Requirements

- iOS 17.0+
- Xcode 15.0+
- SwiftUI

## 🎯 Key Animations

- **Fade-in**: Title and content appear smoothly on launch
- **Pulsing Icon**: Selected mood icon gently pulses
- **Gradient Transition**: Background morphs between mood colors
- **Button Scale**: Selected button scales up with spring animation

---

Built with ❤️ using SwiftUI
