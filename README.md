# Drum_Kit
This webpage allows users to play drum sounds either by clicking on buttons or pressing specific keys on their keyboard.

How It Works
Drum Buttons:

The page has several buttons, each representing a different drum sound.
When a button is clicked, it changes color to black, and a corresponding drum sound is played.

Keyboard Interaction:

The webpage listens for keypress events.
Pressing the keys w, a, s, d, j, k, or l will play different drum sounds corresponding to each key.

Playing Sounds:

The function makeSound(key) is called to play the correct drum sound based on the button clicked or key pressed.
Each key is mapped to a different sound file (e.g., crash.mp3 for the w key, kick-bass.mp3 for the a key, etc.).

Button Animation:

The function buttonAnimation(currentkey) adds a visual effect to show which button was pressed.
The button gets an additional CSS class pressed, which is removed after 100 milliseconds to create a brief animation effect.
