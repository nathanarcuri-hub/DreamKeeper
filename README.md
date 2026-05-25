# Dream Keeper

A standalone dream journal app for saving, reviewing, and reflecting on vivid, strange, or weirdly meaningful dreams.

## Preview

### Main GUI

![Dream Keeper main artwork](DreamKeeper.png)

### Icon

![Dream Keeper icon](dream_keeper_icon.png)

## About

Dream Keeper started as a personal tool for keeping track of dreams that felt too vivid, strange, or oddly relevant to forget. Instead of typing them into a random notepad, this project turns dream logging into a simple standalone desktop app.

Users can name a dream, enter the date, describe what happened, save it locally, and review past dream entries later.

## Features

- Add a dream title, date, and description
- Save dream entries as local text files
- Automatically creates a `Dream Log` folder next to `DreamKeeper.exe`
- Stores saved dreams inside the `Dream Log` folder
- Review past dreams
- Add later reflections or assessments
- Simple local storage with no account required

## How It Works

1. Run `DreamKeeper.exe`.
2. Enter a dream title, date, and description.
3. Submit the dream entry.
4. The app creates a `Dream Log` folder next to `DreamKeeper.exe` if it does not already exist.
5. The dream is saved as a `.txt` file inside the `Dream Log` folder.
6. Saved dreams can be reviewed later.

## What I Learned

- Building a standalone desktop app
- Packaging a project into an `.exe`
- Saving and organizing local files
- Validating user input
- Designing a small tool around a personal use case

## Tech Stack

- Node.js
- HTML
- CSS
- JavaScript

## Files

- `DreamKeeper.png` - Main project image
- `dream_keeper_icon.png` - Icon version
- `DreamKeeper.exe` - Standalone app executable
- `Dream Log` - Folder created next to the executable for saved dream entries

## Possible Improvements

- Add optional AI dream analysis
- Add search and filtering for saved dreams
- Add tags or mood categories
- Add export options for saved dream logs
