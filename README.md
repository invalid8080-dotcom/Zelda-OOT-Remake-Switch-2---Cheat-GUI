# Zelda OOT Remake Switch 2 — Cheat GUI

An independently developed desktop Cheat GUI for Zelda OOT Remake on Switch 2 emulators, created and maintained by **a_cow_says**.

Designed to make gameplay customization, world exploration, debugging, and experimentation accessible through a dedicated graphical interface without requiring users to manually edit memory addresses or cheat files.

The project is actively maintained with new features, community contributions, bug fixes, and emulator compatibility improvements.

**Current version: v1.3.0 — The Wayback Update**

## Downloads & Resources

- **[Download the Latest Release](https://github.com/invalid8080-dotcom/Zelda-OOT-Remake-Switch-2---Cheat-GUI/releases/latest)**
- [Browse All Releases](https://github.com/invalid8080-dotcom/Zelda-OOT-Remake-Switch-2---Cheat-GUI/releases)
- [Themes](https://github.com/invalid8080-dotcom/Zelda-OOT-Remake-Switch2-Cheat-GUI---THEME-LIB)
- [Report Bugs & Request Features](https://github.com/invalid8080-dotcom/Zelda-OOT-Remake-Switch-2---Cheat-GUI/issues)


## 🎥 Video Tutorial & Full Deep Dive

A detailed walkthrough of the Cheat GUI, installation, emulator configuration, gameplay features, and available tools.

Whether you're setting up the GUI for the first time or exploring its more advanced features, this tutorial will help you get started.

[![Zelda OOT Remake Cheat GUI – Full Tutorial & Deep Dive](https://img.youtube.com/vi/QYpkmRhjE3A/maxresdefault.jpg)](https://www.youtube.com/watch?v=QYpkmRhjE3A)

**[▶ Watch the Full Tutorial & Deep Dive on YouTube](https://www.youtube.com/watch?v=QYpkmRhjE3A)**

*Click the thumbnail above to watch the full tutorial.*

*This tutorial was recorded using v1.2.4. The current version includes additional features, interface improvements, and the Wayback version management system.*

## GUI Screenshots

A look at the Cheat GUI and its available features throughout development.

<img width="1308" height="791" alt="Zelda_OOT_Remake_Cheat_GUI_6d5BFevtIn" src="https://github.com/user-attachments/assets/f947ee4e-7d1b-43da-8e6b-bae06355b7fd" />
<img width="1308" height="791" alt="Zelda_OOT_Remake_Cheat_GUI_T1Kdq18suI" src="https://github.com/user-attachments/assets/7daa4ca9-6ebb-4847-8b0f-4502a7024b1a" />
<img width="1308" height="791" alt="Zelda_OOT_Remake_Cheat_GUI_1lCJV32rfb" src="https://github.com/user-attachments/assets/ed0faef2-2c5c-479b-aa6e-e94b8e8b0de1" />
<img width="1308" height="791" alt="Zelda_OOT_Remake_Cheat_GUI_LAWr0CgmIt" src="https://github.com/user-attachments/assets/87076822-b92d-444f-b10b-dcac7c6ae322" />






## Features

### Player & Gameplay

- Infinite health.
- Infinite magic.
- Infinite rupees.
- Infinite supported consumable items.
- Custom item and inventory values.
- Moon Jump.
- Configurable keyboard and controller inputs.
- Individual cheat activation and deactivation.
- Dedicated player, inventory, and equipment controls.

### Inventory & Equipment

Manage supported inventory items and equipment directly through the desktop GUI.

- Rupee management.
- Gold Skulltula token management.
- Consumable item quantities.
- Bottle inventory controls.
- Equipment customization.
- Quest item management.

Feature availability depends on the connected game build and individual implementation status.

### World Exploration

Explore the game beyond its normal gameplay boundaries using dedicated exploration tools.

- Free Camera.
- Boundary Breaker FPV Drone.
- Location warping.
- Save and revisit locations.
- Dedicated World Exploration interface.
- Experimental world-related controls.

Certain exploration features require specific game builds.

### Mini Games

A dedicated section for modifying and experimenting with supported mini-game mechanics.

- Fish Escape Assist.
- Adjustable fish escape thresholds.
- Fish Length customization.
- Fishing record management.
- Young and Adult Link fishing warps.
- Research tiles for additional mini-game mechanics.

Experimental and research-only features are identified separately within the GUI.

### Amiibo Management

- Integrated Amiibo library.
- Amiibo organization and categorization.
- Infinite Amiibo functionality.
- Emulator-specific Amiibo integration.
- Support for user-provided Amiibo files.

Amiibo files are not included with the Cheat GUI.

### Emulator Management

The Cheat GUI is designed to work with compatible emulator forks rather than being restricted to a single emulator.

- Automatic emulator detection.
- Automatic emulator profile population.
- Individual emulator configurations.
- One-click game launching.
- Automatic emulator shutdown and relaunch.
- Connection monitoring.
- Advanced configuration and diagnostic tools through Nerd View.

## The Wayback System — Built-in Version Management

Introduced in v1.3.0, the Wayback system replaces the traditional update-only system with an integrated release browser and version manager.

Users are no longer restricted to running the latest version of the Cheat GUI.

If you prefer an older build, encounter compatibility issues, or simply want to revisit a previous version, you can do so directly through the application.

![The Wayback Update – Historical Version Switching](https://github.com/user-attachments/assets/46350e95-576b-492a-a90b-5faeea54547b)

### Version Management

- Browse available GitHub releases directly from the application.
- Read release notes before installing a version.
- Upgrade to newer releases.
- Revert to previous releases.
- View release screenshots and animated GIFs.
- Open release hyperlinks directly from the updater.
- Verify downloaded archives against published SHA-256 digests when available.
- Automatically restart into the selected version.

### Backward Compatibility

The Wayback system remains available when reverting to supported historical builds, including builds that originally did not have the current updater.

Supported version transitions preserve:

- User settings.
- Emulator profiles.
- Amiibo libraries.
- Existing backups.
- Logs.
- The Wayback release browser.

This allows users to return to a preferred version without permanently losing access to newer releases.

### How to Switch Versions

1. Open **Update GUI**.
2. Select your preferred release.
3. Review its release notes.
4. Select the installation option.
5. Confirm the version change.
6. Allow the updater to install and restart the Cheat GUI.

To change versions again, simply reopen **Update GUI** or use the **Zelda OOT Wayback** shortcut when the application is closed.

## Emulator Compatibility

The Cheat GUI supports compatible Switch 2 emulator forks through its emulator profile system.

### Tested Emulators

- [Lichii nx2 — Build 410](https://github.com/zortos293/Lichii/releases/tag/build-410)
- [Fritchii — v6.5](https://github.com/Frizti/Fritchii/releases/tag/fritchii-v6.5)

Other compatible emulator forks may also work.

Compatibility depends on the emulator's debugging functionality, game version, memory layout, and individual cheat requirements.

The Cheat GUI is not exclusively designed for a single emulator.

Not every feature is guaranteed to work across every emulator or game build.

## Cheat Status Indicators

Not every cheat requires the same game state or memory connection to become available.

Individual status indicators distinguish implemented features from experimental, unsupported, or unimplemented features.

| Status | Description |
| --- | --- |
| Waiting for Memory | Implemented and waiting for the required memory connection. |
| Loading | Checking memory or applying the requested cheat. |
| Available | Ready to use. |
| Active | Currently enabled. |
| Experimental | Uses an experimental implementation. |
| Unsupported | Unavailable for the connected game build. |
| Not Implemented | Currently under research or awaiting implementation. |

An implemented cheat displaying **Waiting for Memory** does not necessarily indicate a problem.

Some cheats require specific gameplay conditions before their associated memory becomes available.

### Emulator Connection Status

| Status | Description |
| --- | --- |
| Waiting | Waiting for a compatible emulator. |
| Detected | An emulator has been detected. |
| Connected | Communication with game memory has been established. |
| Disconnected | The previous connection has been lost. |

Connection indicators are emulator-independent.

## Installation & Setup

1. Download the latest Cheat GUI release.
2. Extract the complete ZIP archive into a folder of your choice.
3. Open **Zelda OOT Remake Cheat GUI.exe**.
4. Open the Settings tab.
5. Select or configure your emulator profile.
6. Click **Launch Zelda**.
7. Wait for the emulator and game memory connection.
8. Enable the features you wish to use.

For supported builds, the bundled in-game menu can be opened by holding **R** and tilting the **right stick down**.

### Important Information

- Extract the complete archive before running the application.
- Do not run the executable directly from inside the ZIP archive.
- Always back up important game saves.
- Some features require specific game versions or gameplay conditions.
- Experimental features may produce unexpected results.

**Pressing Launch Zelda may close and restart an emulator that is already running. Always save your game before restarting the emulator.**

For a complete walkthrough, refer to the [Video Tutorial & Full Deep Dive](https://www.youtube.com/watch?v=QYpkmRhjE3A).

## Active Development

The Cheat GUI is an ongoing independent development project.

Development includes:

- Researching new gameplay mechanics.
- Identifying and validating memory addresses.
- Improving existing cheat implementations.
- Expanding emulator compatibility.
- Improving interface accessibility.
- Preventing unintended memory modifications.
- Maintaining historical version compatibility.
- Improving update and rollback reliability.
- Investigating community-reported issues.
- Expanding gameplay customization and exploration tools.

Some features visible within the application may still be under development. Their implementation status is displayed within the GUI.

For detailed changes between versions, visit the [Releases page](https://github.com/invalid8080-dotcom/Zelda-OOT-Remake-Switch-2---Cheat-GUI/releases).

## Community Contributions

Community research, testing, feedback, and bug reports are welcome.

If you discover a new memory address, gameplay mechanic, compatible emulator build, or potential improvement, feel free to share your findings.

### Reporting Issues

When reporting an issue, please include:

- Cheat GUI version.
- Emulator name and build.
- Game version and Build ID, if available.
- Affected feature.
- Steps to reproduce the issue.
- Relevant screenshots or logs.

**[Submit an Issue or Feature Request](https://github.com/invalid8080-dotcom/Zelda-OOT-Remake-Switch-2---Cheat-GUI/issues)**

Thank you to everyone who has contributed memory research, tested experimental features, reported bugs, and helped improve the project.

## Support the Project

This project is independently developed and maintained by **a_cow_says**.

Researching memory addresses, developing new features, testing emulator compatibility, maintaining historical builds, and resolving bugs requires a significant amount of personal time.

That's time I could otherwise be spending earning money elsewhere.

If you find the Cheat GUI useful and would like to support its continued development, donations are appreciated but never required.

**[Support Cow on PayPal](https://www.paypal.com/paypalme/cowslink)**

You can also support the project by starring the repository, sharing it with others, reporting bugs, and contributing research.

Thank you to everyone supporting the project.

## Legal Disclaimer

**Zelda OOT Remake Cheat GUI** is an independently developed, unofficial third-party utility created by **a_cow_says**.

This project is not affiliated with, endorsed by, sponsored by, or associated with Nintendo.

- This software does not include or distribute copyrighted game files, ROMs, firmware, emulators, or Amiibo dumps.
- Users must obtain their own game and compatible emulator separately.
- The software uses runtime memory modifications for gameplay customization, debugging, research, and experimentation.
- The software does not intentionally make permanent modifications to original game installations.
- The software is not designed to bypass emulator security, encryption, or authentication mechanisms.
- All Nintendo-related names and trademarks remain the property of their respective owners.
- Users are responsible for complying with applicable laws and software licensing terms.

**Use at your own risk.** Runtime memory modifications may cause crashes, unexpected gameplay behavior, save-data corruption, or loss of unsaved progress.

Users are encouraged to maintain backups of important save data.

This software is provided without warranty, to the extent permitted by applicable law.

---

Developed and maintained by **a_cow_says**.

Thank you for supporting independent development.
