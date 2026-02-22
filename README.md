# Virtual Lava Lamp

A customizable, interactive virtual lava lamp built with HTML, CSS, and JavaScript. It features smooth animations, sound reactivity, and various customization options, all contained within a single file.

## Features

*   **Realistic Animation**: CSS-based animations simulate the movement of lava blobs.
*   **Sound Reactivity**: The blobs pulse and scale in real-time based on microphone input.
*   **Customizable Appearance**:
    *   **Speed**: Control how fast the blobs move.
    *   **Particles**: Adjust the number of blobs (1 to 15).
    *   **Colors**: Click the lamp to change colors, or enable "Multicolor" mode for random colors.
    *   **Gradients**: Enable gradient fills for a more dynamic look.
*   **Fullscreen Mode**: Expand the lamp to cover the entire screen.
*   **Collapsible Sidebar**: All controls are tucked away in a sidebar to keep the view clean.

## How to Run

1.  **Download**: Save the `index.html` file to your computer.
2.  **Open**: Double-click the file to open it in your web browser.

### Important Note on Sound Mode
To use the **Sound Mode**, the browser requires access to your microphone. Modern browsers have security restrictions regarding microphone access:

*   **Localhost/Server**: It works best if served via a local server (e.g., VS Code Live Server, Python `http.server`).
*   **File Protocol (`file://`)**: If you open the file directly, some browsers (like Chrome) may block microphone access. Firefox usually allows it with a permission prompt.

## Controls

Click the **☰** button in the top-left corner to open the settings sidebar:

| Control | Description |
| :--- | :--- |
| **Speed** | Adjusts the vertical speed of the blobs. |
| **Particles** | Sets the number of blobs floating in the lamp. |
| **Fullscreen** | Toggles the lamp to fill the browser window. |
| **Sound Mode** | Activates the microphone. Blobs will pulse to the beat of music or voice. |
| **Sound Intensity** | Adjusts how sensitive the blobs are to sound volume. |
| **Multicolor** | Assigns a unique random color to each blob. |
| **Gradients** | (Requires Multicolor) Applies linear gradients to the blobs instead of solid colors. |

## Interaction

*   **Click the Lamp**: If "Multicolor" is **off**, clicking the lamp changes the global color. If "Multicolor" is **on**, it re-randomizes the colors of existing blobs.
*   **Sidebar**: Toggle the sidebar with the hamburger menu icon to access advanced settings.

## Technologies Used

*   **HTML5**
*   **CSS3** (Animations, Variables, Flexbox)
*   **JavaScript** (DOM Manipulation, Web Audio API)
