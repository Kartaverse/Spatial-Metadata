# Spatial Metadata GUI

GUI by Andrew Hazelden <andrew@andrewhazelden>  
Powered by the [Spatial CLI](https://blog.mikeswanson.com/spatial-video/) tool by Mike Swanson  

## Overview

This program runs a new MV-HEVC spatial video encoding session. To pick a file, click on the "Select Movie" button or drag a video file directly into the window. Then click the "Encode Video" button.

![GUI](Docs/Images/gui.png)

## Download

The Spatial Metadata GUI downloads are provided using the GitHub releases mechanism. To download the program you simply have to click on the "[Releases](https://github.com/Kartaverse/Spatial-Metadata/releases)" sidebar link to access the 10MB zip archive.

When you expand the zip file you will have access to the following toolset:

![GUI](Docs/Images/zip_contents.png)

## Requirements

The Spatial Metadata GUI is compatible with macOS systems that run macOS 14+ (Sonoma).

It relies on the [Spatial CLI](https://blog.mikeswanson.com/spatial-video/) program that can be installed using the macOS based [Homebrew](https://brew.sh/) package manager.

		# Install Homebrew using the macOS terminal:
		/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
		
		# Install the Spatial CLI app using the brew program in the macOS terminal:
		brew install spatial
		
		# The Spatial CLI app now lives on your hard disk at:
		/opt/homebrew/bin/spatial

## DCC Tool Integrations

This same metadata embedding toolset is also available for use inside of BMD's DaVinci Resolve Studio video editing software via the "KartaLink | Spatial Metadata" scripts that can be installed using the [Reactor Package Manager](https://kartaverse.github.io/Reactor-Docs/#/reactor).

![Reactor](Docs/Images/reactor.png)

The DaVinci Resolve version of the Spatial Metadata toolset allows you to work with immersive footage using Resolve Media Pool "bins". The Kartaverse [Media Command](https://kartaverse.github.io/Kartaverse-Docs/#/mediacommand) launched "Spatial Metadata.lua" script is used to batch processes 180VR, 360VR, fisheye, or flat image projection videos into MV-HEVC encoded content in only a few clicks. This multi-view encoded stereoscopic 3D material is ready for playback on devices like Apple Vision Pro HMDs and Meta Quest HMDs.

![DaVinci Resolve](Docs/Images/davinci-resolve.png)

## Source Code

The GUI wrapper source code is open-source licensed. It is available using the LGPL/GPL v3 license terms.

The "Spatial Metadata GUI.app" wrapper program was compiled using the [Xojo](https://xojo.com/) rapid application development tools on macOS. Xojo is a really quick and efficient toolset to use for creating wrapper GUIs for command line tools, or for building GUI based desktop utilities.

![Xojo IDE](Docs/Images/xojo.png)
