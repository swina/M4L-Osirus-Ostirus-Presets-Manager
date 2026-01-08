# M4L Presets Manager for Osirus 2 / Ostirus Emulators

> [!NOTE]
> **Status: Alpha Version**
> This device is currently in development (Alpha stage). Feedback from testers is greatly appreciated to help identify bugs and improve functionality. Please feel free to reach out with your findings!

## Description

This Max for Live device serves as a comprehensive Preset Manager for the **Osirus 2** and **Ostirus** DSP emulators (Access Virus emulations). It provides an intuitive interface to browse, filter, and recall presets from the emulator's banks directly within Ableton Live, streamlining your workflow.

![Presets Manager Preview](https://res.cloudinary.com/moodgiver/image/upload/v1767891939/device-preview_kud0am.png)


> [!IMPORTANT]
> **Only the VST2 version is supported and tested.** The VST3 format does not support MIDI Program Change messages, which are essential for this device to function correctly.

## Features

*   **Dual Emulator Support**: Seamlessly works with both Osirus 2 and Ostirus instances.
*   **Bank Browsing**: Navigate through all available preset banks (A-H) stored in JSON format.
*   **Smart Navigation**: Use the on-screen **Up/Down arrows** to scroll through presets. These buttons are fully **mappable** to keyboard keys or MIDI controllers for hands-on control.
*   **Favorites System**:
    *   **Add/Remove**: Click the **Star icon** to add the selected preset to your favorites.
    *   **Import/Export**: Save and share your favorite lists.
    *   *Note*: Favorites lists must match the target plugin (Osirus 2 or Ostirus), just like the factory banks.
*   **Preset Management**: View detailed preset information including name, category, and index.
*   **Customizable Device Name**: Rename the device label as per your needs (e.g., "Bass Synth", "Lead"). This helps in organizing different instances of the device in your project.
*   **Mixer Controls**:
    *   **Volume**: Directly controls the plugin's volume via MIDI CC# 7.
    *   **Pan**: Directly controls the plugin's panning via MIDI CC# 10.

## Installation

1.  **Download or Clone**: Download this repository or clone it to your machine.
2.  **Locate Folder**: Place the `PresetsManager.amxd` device in your Ableton **User Library** or any preferred location.
3.  **Data Files**: The `Osirus-Ostirus` folder containing the JSON banks can be stored anywhere on your computer.

## Usage

1.  **Placement**: Drag and drop `PresetsManager.amxd` onto a MIDI Track in Ableton Live.
    *   **Same Track**: Ideally, place it on the same track as the emulator plugin (before the instrument).
    *   **Different Track**: If you place the device on a different track, you MUST set that track's **MIDI To** output to the track containing the Osirus/Ostirus plugin, and select the specific channel (usually **Track In** or **Channel 1**).
2.  **Load Banks**: Click the **Load** button on the device interface.
3.  **Select Correct Bank**: Navigate to the `Osirus-Ostirus` folder.
    *   **Important**: Ensure you load a bank that corresponds to the emulator you are controlling. Use the `Osirus 2` subfolder for Osirus 2 and the `Ostirus` subfolder for Ostirus.
4.  **Browse**: The presets from the loaded bank will now be available for browsing and selection.

## Structure

The provided `Osirus-Ostirus` directory contains the factory banks organized by emulator. You can keep this structure for organization or move the files as needed.

## License

This project is licensed under the MIT License - see the LICENSE file for details.