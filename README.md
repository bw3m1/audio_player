# Audio Player Web Application

A modern, responsive audio player built with HTML, CSS, and JavaScript that allows users to play local audio files with metadata support.

## Features

- **Modern UI**: Sleek dark theme with gradient backgrounds and smooth animations
- **Audio Playback**: Play/pause, skip tracks, and seek through audio
- **Metadata Support**: Displays track information (title, artist, album) and album art from audio files
- **Playlist Management**:
  - Add multiple audio files
  - Shuffle playlist
  - Clear playlist
  - Save and load playlists to/from localStorage
- **Playback Controls**:
  - Adjustable playback speed (0.5x to 2.0x)
  - Repeat modes (off, one, all)
  - Shuffle mode
- **Visual Feedback**:
  - Progress bar with seek functionality
  - Album art display with blur effect background
  - Currently playing track highlight
- **Keyboard Shortcuts**:
  - Space: Play/Pause
  - Arrow Left/Right: Seek backward/forward
  - Arrow Up/Down: Volume control
  - M: Mute
  - S: Toggle shuffle
  - R: Toggle repeat mode
  - N: Next track
  - P: Previous track

## Technologies Used

- HTML5 Audio API
- jsmediatags library for reading audio metadata
- CSS Grid and Flexbox for responsive layout
- CSS custom properties for theming
- LocalStorage for saving playlists

## How to Use

1. Open the `audio_player.html` file in a modern web browser
2. Add audio files by:
   - Clicking the album art placeholder
   - Clicking the "Add Music" button in the empty playlist state
   - Using the file input dialog
3. Control playback using the player controls or keyboard shortcuts
4. Manage playlists using the playlist controls (save, load, clear)

## Browser Support

The audio player should work in all modern browsers that support:
- HTML5 Audio
- CSS Grid
- JavaScript ES6+
- File API

## Limitations

- Playlist saving only stores file references, not the actual files
- File paths may not persist between sessions
- Requires user to reselect files when loading saved playlists

## Future Improvements

- Add volume control slider
- Implement drag-and-drop for adding files
- Add support for online streaming
- Implement more robust playlist saving with file persistence
- Add equalizer and audio effects
