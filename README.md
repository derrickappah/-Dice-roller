# Dice Roller - 3D Realistic Dice with Three.js

This is a web-based 3D dice roller built using [Three.js](https://threejs.org/) with realistic rounded dice geometry, bump mapping, and smooth rolling animation. The dice rolls with a natural spin and easing effect, displaying the final result on the screen. It includes sound effects for dice rolling and button clicks.

---

## Features

- Realistic 3D rounded dice using `RoundedBoxGeometry`
- Custom dice face textures with bump maps for depth effect
- Smooth rolling animation with initial chaotic spin and easing into final face
- Responsive canvas size and dynamic resizing support
- Dice roll result displayed in the UI
- Button click and dice roll sound effects

---

## How to Use

1. Open the `index.html` file in a modern web browser (Chrome, Firefox, Edge).
2. Click or tap the **Roll** button to roll the dice.
3. Watch the dice spin and come to rest showing a random face.
4. The result will be displayed below the dice.
5. Resize the browser window and the dice canvas will adjust accordingly.

---

## Technologies Used

- [Three.js](https://threejs.org/) (r160)
- Tailwind CSS for styling
- Google Fonts (Space Grotesk and Noto Sans)
- HTML5, CSS3, and JavaScript (ES6 modules)

---

## File Structure

- `index.html` — main web page containing all HTML, CSS, and JS code.
- Audio assets loaded from external URLs for dice roll and button click sounds.

---

## Notes

- Ensure you serve the file via a local server or host it on a web server to avoid CORS issues with ES modules.
- Tested on latest versions of Chrome and Firefox.
- Works best on devices with WebGL support.

---

## Credits

- Dice textures and bump maps dynamically generated via canvas.
- Sounds from [Mixkit](https://mixkit.co/free-sound-effects/).

---

## License

This project is open source and free to use under the MIT License.

---

Enjoy rolling your dice!
