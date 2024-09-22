---
layout: page
title: What's New
include_in_header: true
---

# Countries of the World App - Changelog

## Version 1.0.0 (Initial Release)

### Features:

1. **Interactive World Map**
   - Users can view a custom map of the world
   - Map view can be toggled with a list view

2. **Country Guessing Game**
   - Players can input country names to guess
   - Real-time feedback on correct and incorrect guesses
   - Visual indicators for correct and incorrect guesses

3. **Game Mechanics**
   - 15-minute time limit for each game session
   - Pause functionality with a limit of 3 pauses per game
   - Victory screen upon guessing all countries
   - Game over screen when time runs out

4. **User Interface**
   - Top bar displaying guessed country count and remaining time
   - Input bar for entering country names
   - Toggle between map view and continent table view

5. **Sound Effects**
   - Background music during gameplay
   - Special music when 1 minute remains
   - Sound effects for correct guesses, errors, and game end

6. **Accessibility**
   - Custom fonts for better readability
   - High contrast colors for UI elements

7. **Game State Management**
   - Local storage of game progress
   - Ability to resume game after pausing

8. **Developer Mode**
   - Hidden developer settings for testing (only in debug builds)
   - Options to reduce time and add most countries for quick testing

### Technical Details:
- Built with SwiftUI for iOS
- Uses MapKit for map rendering
- Implements custom overlays for various game states (pause, exit confirmation, victory)
- Utilizes Swift's property wrappers for efficient state management

### Known Limitations:
- Currently only available in English
- No online multiplayer functionality
- High scores are not persisted between app launches

We're excited to bring you this first version of Countries of the World! Stay tuned for future updates and enhancements.
