# CodeAlpha Music Player

## Overview

CodeAlpha Music Player is a web-based music player that allows users to create playlists, search for and categorize music, and control playback. The player includes features such as play, pause, skip, and volume control.

## Features

1. **Playlist Functionality**: Create and manage multiple playlists.
2. **Music Search and Categorization**: Search for tracks and categorize music by genre.
3. **Playback Controls**: Play, pause, skip tracks, and control volume.
4. **Responsive Design**: User-friendly interface that works on both desktop and mobile devices.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML, CSS, and JavaScript

### Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/davishkar/CodeAlpha_Music_Player.git
    ```

2. Navigate to the project directory:
    ```bash
    cd CodeAlpha_Music_Player
    ```

3. Open `index.html` in your preferred web browser.

## Project Structure

```
CodeAlpha_Music_Player/
│
├── index.html       # The main HTML file
├── styles.css       # The main CSS file for styling
├── main.js          # The main JavaScript file for functionality
├── songs/           # Directory containing song files
└── covers/          # Directory containing album cover images
```

## Usage

1. **Navigation Bar**: Use the navigation bar to access different sections such as Home, Artists, Albums, Songs, Playlists, and Charts.
2. **Search and Filter**: Use the search bar to find tracks and artists. Use the filter dropdown to categorize music by genre.
3. **Playback Controls**: Use the playback controls at the bottom of the screen to play, pause, skip tracks, and adjust the volume.

### Example Songs

The player comes preloaded with some example songs located in the `songs/` directory. Each song has an associated cover image located in the `covers/` directory.

### Adding New Songs

1. Add your song files to the `songs/` directory.
2. Add the cover images to the `covers/` directory.
3. Update the `songs` array in `main.js` with the new song details:
    ```javascript
    let songs = [
        {songName: "New Song", filePath: "songs/new-song.mp3", coverPath: "covers/new-song.jpg"},
        // ... other songs
    ];
    ```

## Contributing

Contributions are welcome! Please create a pull request or submit an issue for any feature requests or bugs.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Contact

For any questions or feedback, please contact [your email] or create an issue on GitHub.

---
