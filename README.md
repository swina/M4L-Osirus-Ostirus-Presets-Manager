# M4L Presets Manager for Osirus 2 / Ostirus Emulators

## Description

This Max for Live device serves as a comprehensive Preset Manager for the **Osirus 2** and **Ostirus** DSP emulators (Access Virus emulations). It provides an intuitive interface to browse, filter, and recall presets from the emulator's banks directly within Ableton Live, streamlining your workflow.

![Presets Manager Preview](https://res.cloudinary.com/moodgiver/image/upload/v1767891939/device-preview_kud0am.png)


> [!IMPORTANT]
> **Only the VST2 version is supported and tested.** The VST3 format does not support MIDI Program Change messages, which are essential for this device to function correctly.

## Features

*   **Dual Emulator Support**: Seamlessly works with both Osirus 2 and Ostirus instances.
*   **Bank Browsing**: Navigate through all available preset banks (A-H) stored in JSON format.
*   **Favorites System**: Mark and recall your go-to presets using the integrated Favorites feature.
*   **Preset Management**: View detailed preset information including name, category, and index.

## Installation

1.  **Download or Clone**: Download this repository or clone it to your machine.
2.  **Locate Folder**: Place the `PresetsManager.amxd` device in your Ableton **User Library** or any preferred location.
3.  **Data Files**: The `Osirus-Ostirus` folder containing the JSON banks can be stored anywhere on your computer.

## Usage

1.  Drag and drop `PresetsManager.amxd` onto a MIDI Track in Ableton Live.
2.  Click the **Load** button on the device interface.
3.  Navigate to the `Osirus-Ostirus` folder and select the JSON bank file you wish to load.
4.  The presets from that bank will now be available for browsing.

## Structure

The provided `Osirus-Ostirus` directory contains the factory banks organized by emulator. You can keep this structure for organization or move the files as needed.

## License

This project is licensed under the MIT License - see the LICENSE file for details.