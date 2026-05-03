⌨️ hangul-keyboard-practice

A web-based Hangul (Korean) Typing Trainer designed to help users master the 2-beolsik (standard) keyboard layout through visual muscle memory.
✨ Features

    Dynamic Jamo Disassembly: Uses Hangul.js to handle complex syllable stacking, allowing users to type in Korean without changing their OS language settings.

    10-Finger Guide System: Color-coded virtual keyboard based on standard touch-typing resting positions (Home Row).

    Flying Ghost Fingers: Real-time visual hints where a glowing "ghost orb" flies from the resting position to the target key, helping eyes track movement.

    Predictive Highlighting: The next required key pulses in the color of the finger that should press it.

    Gamified Feedback:

        Combo System: Accuracy increases your score multiplier; a single mistake resets the combo.

        Visual Errors: The input box shakes and keys flash red on incorrect inputs to discourage bad muscle memory.

        Strict Mode: Prevents typing incorrect letters, forcing the user to find the right key.

    Customizable Experience:

        Speed Slider: Adjust the flight time of the "ghost fingers" from a fast 0.2s dart to a slow 3.0s float.

        Guide Toggle: Hide or show the 10-finger coloring and hints for an extra challenge.

🚀 How to Run

    Download or clone this repository.

    Open index.html in any modern web browser.

    Start typing! (The input field focuses automatically).

🛠️ Built With

    HTML5/CSS3: Custom layout with flexbox and CSS variables for dynamic animations.

    Vanilla JavaScript: For all game logic, coordinate math, and DOM manipulation.

    Hangul.js: A lightweight library used for assembling and disassembling Korean characters.

📝 Future Improvements

    [ ] Expanded word bank with difficulty levels.

    [ ] Statistics tracking (WPM and Accuracy %).

    [ ] Sound effects for correct/incorrect keystrokes.

    [ ] Dark mode support.
