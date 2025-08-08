Launcher Music Directory
=========================

This directory contains MP3 music files that will be played automatically when the launcher starts.

Instructions:
-------------
1. Place your MP3 music files in this directory
2. Files will be loaded alphabetically and played in sequence
3. Volume can be controlled using the rflMusictrackBar1 slider in the launcher
4. Current track information is saved to NexusPro_Launcher.ini

File Format:
------------
- Supported format: .mp3 only
- File naming: Any valid filename (e.g., "background_music.mp3", "theme_song.mp3")
- Recommended bitrate: 128kbps or higher for good quality
- Maximum file size: No limit, but smaller files load faster

Example files:
--------------
- launcher_theme.mp3
- background_music.mp3
- ambient_music.mp3

The launcher will automatically:
- Scan this directory for MP3 files on startup
- Play the first file found
- Loop through all files continuously
- Save volume settings between sessions
- Update the INI file with current track information