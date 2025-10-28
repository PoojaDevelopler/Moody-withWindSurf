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

Built with ❤️ using SwiftUI naaaaa By WindSurf 🤗

---

## 🤖 AI Generation Details

This project was generated using **WindSurf**, an AI-powered development tool for Swift.  
The app concept and structure were created from a single natural language prompt crafted with **ChatGPT**.

**Prompt used to generate this project:**

> “Build a single-screen SwiftUI app called *Mood Weather*.  
> Goal: A minimal yet elegant one-screen app that changes its background color and animation based on the selected mood.  
> Requirements:  
> 1. Use only SwiftUI.  
> 2. The app should have a smooth UI/UX and a calming color palette.  
> 3. The user selects their current mood from 4 options: ☀️ Happy, 🌧️ Sad, 🌩️ Angry, 🌈 Calm.  
> 4. Each mood should:  
> &nbsp;&nbsp;&nbsp;&nbsp;- Change the background gradient color.  
> &nbsp;&nbsp;&nbsp;&nbsp;- Show an animated SF Symbol that fits the vibe.  
> &nbsp;&nbsp;&nbsp;&nbsp;- Animate transitions smoothly.  
> 5. Include a title “Mood Weather” at the top with a subtle fade-in effect.  
> 6. Center the mood icon and name with animation when mood changes.  
> 7. Use rounded buttons and clean font styling.  
> 8. No API or backend logic.  
> 9. Include SwiftUI Canvas previews.  
> 10. Add soft pulsing motion to the mood icon when it changes.”

This demonstrates how **AI-assisted workflows** can accelerate app creation — from concept to working Swift

