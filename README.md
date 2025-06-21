# unity-auth-system



```markdown
# Unity Authentication System

This Unity project implements a customizable authentication system supporting:

- **Anonymous Sign-In**
- **Username + Password Sign-Up & Sign-In**
- **Error handling for invalid logins and duplicate accounts**
- **Unity Authentication Services integration**
- **UI built using Unity's Canvas system and TextMeshPro**

## Features

- Clean UI prefabs with input fields and buttons
- ErrorMenu panel for displaying validation and server errors
- Modular Panel system for flexible menu transitions
- Password strength validation (must include uppercase, lowercase, digit, special character)


## Requirements

- Unity 6 or newer
- Unity Authentication (set up via Unity Dashboard)
- Unity TextMeshPro

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/irika00/unity-auth-system.git
````

2. Open the project in Unity.

3. Go to `Edit > Project Settings > Services` and ensure Unity Authentication is enabled.

4. In the `AuthenticationMenu` prefab:

   * Add your sign-in/sign-up logic if you're connecting to a backend
   * Connect the `MenuManager` and `PanelManager` scripts

## Known Issues

* GitHub has file size limits. Make sure you exclude `Library/`, `obj/`, and `Temp/` folders via `.gitignore`
* Avoid committing Unity cache files or `.Runtime` binaries (e.g., from Burst package)

## License

This project is licensed under the MIT License. Feel free to use and modify for educational or commercial projects.

---

