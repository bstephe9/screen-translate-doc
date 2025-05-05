---
sidebar_position: 4
---

# Features and Requirements

## Functional Requirements

### OCR

- Detection of on-screen characters/symbols.
- OCR output must be stored in memory, not in image files.

### Translation

- Translating words from one language to another.
- Continuous detection and translation within regions.
- User language selection.
- Automatic language detection by default.

### Screen Region Selection

- User screen region selection for translation detection.
    - Left mouse click + drag
    - Spacebar + arrow keys
- User may select full screen or selected region.
    - Can not select both at the same time.
- User may create multiple regions (4 max).
- Clearing all regions.
- Regions may not overlap.
- Region size must have a minimum that is not too small.
- The following region selection modes (for existing regions):
    - Resize: When mouse is on region border.
    - Drag: When mouse is within region area.
- Appropriate mouse cursors for region selection modes.
- Maintain a history to undo/redo region selection movements.

### User Interface

- After translation, the translated text must be visible in its same screen
location.
- Widgets:
    - Translate "from" combo box
    - Translate "to" combo box
    - Add new region
    - Clear all regions
    - Undo/redo region movement
    - Save current regions state
    - Load previously saved regions state

## Nonfunctional Requirements

### Performance

- Translation and display should be performed in real-time.

### Usability

- Screen regions should be easily manipulated with mouse and keyboard.
- Widget functionalities should be clearly defined and easy to understand for
new users.
