Spatial Metadata GUI - v1.2 2024-08-15
GUI by Andrew Hazelden <andrew@andrewhazelden.com>
Powered by the Spatial CLI tool by Mike Swanson

This program runs a new MV-HEVC spatial video encoding session. To pick a file, click on the "Select Movie" button or drag a video file directly into the window. Then click the "Encode Video" button.

Spatial Metadata GUI Github Page:
https://github.com/Kartaverse/Spatial-Metadata


Requirements:
The Spatial CLI program can be installed using the macOS based homebrew package manager.

# Install Homebrew using the macOS terminal:
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install the Spatial CLI app using the brew program in the macOS terminal:
brew install spatial

# The Spatial CLI app now lives on your hard disk at:
/opt/homebrew/bin/spatial

# If you want to uninstall the Spatial CLI app using brew in the macOS terminal:
brew uninstall spatial


Video Tutorial:
Learn how to encode next-gen MV-HEVC spatial video for playback on Apple Vision Pro and Meta Quest HMDs. This video covers the Spatial Metadata GUI as a standalone tool, and as a media command/trigger script that works inside of BMD Resolve (Free)/Resolve Studio: 

YouTube | No Code! Free Spatial Video Metadata Injector for Apple Vision Pro | Standalone & DaVinci Resolve
https://www.youtube.com/watch?v=PJWsscXmJiE


Change Log:

Version 1 (2024-07-14)
- Initial Release

Version 1.2 (2024-08-15)
- Clicking on the "movie camera" icon in the GUI  opens the project's GitHub page in your default web browser.
- The program includes localization support for numbers in text fields. This means comma vs period decimal separators are handled automatically based upon your current locale settings. The localized values are then translated into the correct format for the Spatial CLI tool.
- The "Fast Start" checkbox is used to place a QuickTime "Moov" atom at the start of the video file. This helps with network playback of media that is progressively downloaded.
- An "Overwrite an Existing Movie File Export" checkbox allows you to re-export the encoded video file with different parameters. When this checkbox is enabled, the Spatial Metadata GUI program will replace a pre-existing video export that has the same filename.
