# Zen Timer - Meditation App

A simple, client-side meditation timer app vibecoded with HTML, CSS, and JavaScript. Create, customize, and run meditation routines with configurable timers, sounds, and descriptions.

Note: pure vibecode, expect bugs.

## Features

- **Create and Manage Meditations**

  - Build custom meditation routines with multiple timers
  - Name and save multiple meditation sessions
  - Drag and drop to reorder timers
  - Duplicate or delete existing timers

- **Customizable Timers**

  - Set specific durations (hours, minutes, seconds)
  - Add optional titles and descriptions for each timer
  - Configure start, end, and looping sounds for each timer segment
  - Preview sounds before saving

- **Playback**

  - Play meditation sessions with visual progress tracking
  - Circular progress ring shows overall timing with segment markers
  - Pause/resume functionality
  - Automatically plays configured sounds at timer transitions
  - Exit early with optional confirmation

- **Organization**
  - Search through your saved meditations
  - Sort by name, creation date, or last played time
  - Track meditation history with timestamps
  - See when each meditation was last played

## Technology

- **Single-File App**: The entire application is contained in a single HTML file
- **No Server Required**: Runs entirely in your browser
- **Local Storage**: All data is saved locally in your browser
- **Libraries**:
  - [Tailwind CSS](https://tailwindcss.com/) - For styling
  - [SortableJS](https://github.com/SortableJS/Sortable) - For drag-and-drop ordering
  - [Fuse.js](https://fusejs.io/) - For search functionality

## Getting Started

1. Download the `index.html` file
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. No installation or server required!

## Usage Guide

### Creating a Meditation

1. Click the "Create" button on the home screen
2. Enter a name for your meditation at the top
3. Click "Add Timer" to add timer segments
4. For each timer:
   - Set duration (hours, minutes, seconds)
   - Add an optional title and description
   - Choose sounds for the start, end, and during the timer
   - Drag handles to reorder as needed
5. Click "Save" when finished

### Playing a Meditation

1. Click the play button on any meditation from the home screen
2. The app will load the required sounds
3. Press the large play button to begin
4. The circular progress ring shows your overall progress
5. You can pause/resume at any time, or exit early

### History Tracking

1. Click the "History" button on the home screen
2. View a log of your completed meditation sessions
3. See when meditations were completed and their duration

## Sounds

The app includes several built-in CC0 sounds, sourced from [freesound.org](https://freesound.org/)

## Data Storage

All meditation data is stored in your browser's local storage. This means:

- Data persists between sessions on the same device and browser
- Clearing browser data will erase saved meditations
- Data does not sync between devices
