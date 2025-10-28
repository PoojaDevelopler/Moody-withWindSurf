# 🚀 Quick Start Guide - Mood Weather App

## Instant Setup (2 minutes)

### Step 1: Create Xcode Project
```bash
# Open Xcode from Applications or use:
open -a Xcode
```

### Step 2: New Project
1. In Xcode: **File → New → Project** (⇧⌘N)
2. Select **iOS** → **App**
3. Click **Next**

### Step 3: Configure Project
- **Product Name**: `MoodWeather`
- **Interface**: `SwiftUI`
- **Language**: `Swift`
- **Storage**: None needed
- **Location**: Choose `/Users/apple/Desktop/Moody`

### Step 4: Add Source Files

The project will create a default structure. Replace/add files:

1. **Delete** the default `ContentView.swift` and `MoodWeatherApp.swift` if they exist
2. **Add** all files from the `MoodWeatherApp` folder:
   - Drag the entire `MoodWeatherApp` folder into the Xcode project navigator
   - Make sure "Copy items if needed" is **checked**
   - Select "Create groups" (not folder references)
   - Target membership: **MoodWeather**

Your project structure should look like:
```
MoodWeather/
├── MoodWeatherApp.swift
├── Models/
│   └── Mood.swift
├── Views/
│   ├── ContentView.swift
│   └── MoodButton.swift
└── ViewModels/
    └── MoodViewModel.swift
```

### Step 5: Run! 🎉
- Press **⌘R** or click the ▶️ Run button
- Choose iOS Simulator (iPhone 15 Pro recommended)
- Watch your Mood Weather app launch!

---

## Alternative: Command Line Setup

If you prefer automation, run:
```bash
cd /Users/apple/Desktop/Moody
chmod +x setup-xcode-project.sh
./setup-xcode-project.sh
```

---

## Troubleshooting

### Issue: "Cannot find 'ContentView' in scope"
**Solution**: Make sure all files are added to the Xcode target (check target membership in File Inspector)

### Issue: Build fails
**Solution**: 
1. Clean Build Folder (**⇧⌘K**)
2. Verify deployment target is iOS 17.0+
3. Check that all files have the correct target membership

### Issue: Black screen on launch
**Solution**: Verify `MoodWeatherApp.swift` has the `@main` attribute and references `ContentView()`

---

## 🎨 Features to Try

1. **Tap each mood** - Watch smooth gradient transitions
2. **Observe the icon** - See the gentle pulsing animation  
3. **Launch the app** - Notice random mood selection with fade-in
4. **Feel the vibe** - Each mood has carefully chosen colors

---

**Need help?** Check README.md for detailed feature documentation.
