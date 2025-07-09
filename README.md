# unity-auth-system

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/irika00/unity-auth-system)


# Unity Authentication System

A Unity-based authentication interface for Metaverse Cloud Services that provides a complete menu-driven authentication flow with support for multiple authentication methods.  

## Features

- **Multi-modal Authentication**: Anonymous sign-in, username/password sign-up and sign-in 
- **Unity Services Integration**: Direct integration with Unity Authentication and Analytics services 
- **Input System Support**: Full Unity Input System support for keyboard, gamepad, touch, and XR inputs 
- **Error Handling**: Comprehensive error display and recovery mechanisms  
- **URP Compatibility**: Built on Universal Render Pipeline for cross-platform deployment
- **Modular Panel System**: Flexible menu transitions with clean UI prefabs 

## System Architecture

The system follows a modular architecture built around Unity's UI framework and Services platform, using a singleton-based menu management pattern with panel-based UI screens. 

### Core Components

- **MenuManager**: Central management prefab that coordinates the authentication flow 
- **Menu Scene**: Main scene containing Canvas, EventSystem, and UI components 
- **Input Actions**: Comprehensive input mapping for multiple device types 

## Requirements

- Unity 6 or newer 
- Unity Authentication (set up via Unity Dashboard) 
- Unity TextMeshPro  
- Unity Input System  

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/irika00/unity-auth-system.git
   ``` [15](#0-14) 

2. Open the project in Unity 

3. Configure Unity Services:
   - Go to `Edit > Project Settings > Services` and ensure Unity Authentication is enabled 

4. Set up the authentication flow:
   - Connect the `MenuManager` and `PanelManager` scripts in the AuthenticationMenu prefab 

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

## Known Issues

- GitHub has file size limits. Make sure you exclude `Library/`, `obj/`, and `Temp/` folders via `.gitignore` [22](#0-21) 
- Avoid committing Unity cache files or `.Runtime` binaries (e.g., from Burst package) [23](#0-22) 

## License

This project is licensed under the MIT License. Feel free to use and modify for educational or commercial projects. [24](#0-23) 

## Notes

This README is based on the current codebase structure which includes Unity 6 compatibility, Universal Render Pipeline integration, and comprehensive input system support. The project appears to be built from Unity's URP template and extended with authentication functionality. The existing README in the repository provides additional context about password validation requirements and specific setup steps.

Wiki pages you might want to explore:
- [Overview (irika00/unity-auth-system)](/wiki/irika00/unity-auth-system#1)
