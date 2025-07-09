# unity-auth-system

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/irika00/unity-auth-system)


# Unity Authentication System

A Unity-based authentication interface for Metaverse Cloud Services that provides a complete menu-driven authentication flow with support for multiple authentication methods. [1](#0-0) 

## Features

- **Multi-modal Authentication**: Anonymous sign-in, username/password sign-up and sign-in [2](#0-1) 
- **Unity Services Integration**: Direct integration with Unity Authentication and Analytics services [3](#0-2) 
- **Input System Support**: Full Unity Input System support for keyboard, gamepad, touch, and XR inputs [4](#0-3) 
- **Error Handling**: Comprehensive error display and recovery mechanisms [5](#0-4) 
- **URP Compatibility**: Built on Universal Render Pipeline for cross-platform deployment [6](#0-5) 
- **Modular Panel System**: Flexible menu transitions with clean UI prefabs [7](#0-6) 

## System Architecture

The system follows a modular architecture built around Unity's UI framework and Services platform, using a singleton-based menu management pattern with panel-based UI screens. 

### Core Components

- **MenuManager**: Central management prefab that coordinates the authentication flow [8](#0-7) 
- **Menu Scene**: Main scene containing Canvas, EventSystem, and UI components [9](#0-8) 
- **Input Actions**: Comprehensive input mapping for multiple device types [10](#0-9) 

## Requirements

- Unity 6 or newer [11](#0-10) 
- Unity Authentication (set up via Unity Dashboard) [12](#0-11) 
- Unity TextMeshPro [13](#0-12) 
- Unity Input System [14](#0-13) 

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/irika00/unity-auth-system.git
   ``` [15](#0-14) 

2. Open the project in Unity [16](#0-15) 

3. Configure Unity Services:
   - Go to `Edit > Project Settings > Services` and ensure Unity Authentication is enabled [17](#0-16) 

4. Set up the authentication flow:
   - Connect the `MenuManager` and `PanelManager` scripts in the AuthenticationMenu prefab [18](#0-17) 

## Project Structure

```
Assets/
├── Prefabs/
│   └── MenuManager.prefab          # Core management component
├── Scenes/
│   └── Menu.unity                  # Main authentication scene
├── InputSystem_Actions.inputactions # Input mappings
└── TutorialInfo/                   # Unity template assets
```

## Input System Integration

The project includes comprehensive input support through Unity's Input System, with mappings for:
- Keyboard and mouse controls [19](#0-18) 
- Gamepad support [20](#0-19) 
- XR controller compatibility [21](#0-20) 

## Known Issues

- GitHub has file size limits. Make sure you exclude `Library/`, `obj/`, and `Temp/` folders via `.gitignore` [22](#0-21) 
- Avoid committing Unity cache files or `.Runtime` binaries (e.g., from Burst package) [23](#0-22) 

## License

This project is licensed under the MIT License. Feel free to use and modify for educational or commercial projects. [24](#0-23) 

## Notes

This README is based on the current codebase structure which includes Unity 6 compatibility, Universal Render Pipeline integration, and comprehensive input system support. The project appears to be built from Unity's URP template and extended with authentication functionality. The existing README in the repository provides additional context about password validation requirements and specific setup steps.

Wiki pages you might want to explore:
- [Overview (irika00/unity-auth-system)](/wiki/irika00/unity-auth-system#1)
