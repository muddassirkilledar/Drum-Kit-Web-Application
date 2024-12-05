# Drum Kit Web Application

This is a simple interactive **Drum Kit** application built using HTML, CSS, and JavaScript. It allows users to play drum sounds either by clicking on drum buttons displayed on the webpage or by pressing specific keys on the keyboard.

## Features

- **Click Interaction**: Click on any drum button to play the corresponding sound.
- **Keyboard Interaction**: Press specific keys on the keyboard to trigger drum sounds.
- **Visual Animation**: Buttons animate when clicked or when their corresponding keys are pressed.

## How It Works

The application uses event listeners to detect user interactions (clicks and keypresses) and plays the appropriate drum sound by dynamically creating `Audio` objects.

### Key Mappings

| Key Pressed | Sound Played         |
|-------------|----------------------|
| `w`         | Tom 1               |
| `a`         | Tom 2               |
| `s`         | Tom 3               |
| `d`         | Tom 4               |
| `j`         | Snare               |
| `k`         | Crash Cymbal        |
| `l`         | Kick Bass           |

### Code Breakdown

1. **Event Listeners**:
   - Adds `click` event listeners to all buttons with the class `.drum`.
   - Adds a `keypress` event listener to the document to handle keyboard input.

2. **makeSound Function**:
   - Plays the corresponding drum sound based on the button pressed or key pressed.

3. **buttonAnimation Function**:
   - Adds a CSS class to animate the button when it is triggered and removes it after a short delay.

## File Structure

