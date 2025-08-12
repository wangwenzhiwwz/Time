# Timer Webpage with Screen Wake Lock

A simple, elegant web-based timer with a modern font style inspired by [time.is](https://time.is/), supporting start/pause/reset by clicks and preventing screen sleep using the Wake Lock API.

---

## Features

- **Large, clear digital timer display** using the Inter font (similar style to time.is)
- **Units displayed under each time segment** (H, M, S) for clarity
- **Single-click anywhere** to start or pause the timer
- **Double-click anywhere** to reset the timer to zero and pause
- **Prevents screen from sleeping** while the timer is running (using Wake Lock API)
- Responsive design optimized for **mobile portrait mode** with smaller font size

---

## Usage

1. Open the `index.html` file in any modern browser (Chrome, Edge, Firefox, Safari on mobile or desktop)
2. Click anywhere on the page to start or pause the timer
3. Double-click anywhere to reset the timer
4. The timer will keep running accurately even if the browser tab loses focus, and will keep the screen awake while running

---

## Requirements

- Modern browser with support for [Wake Lock API](https://developer.mozilla.org/en-US/docs/Web/API/Screen_Wake_Lock_API) (fallback if not supported)
- Internet connection to load the Inter font from Google Fonts (or you can self-host the font if desired)

---

## Customization

- Modify the font size and colors in the CSS to fit your preference
- Add more controls or features like lap time, countdown, etc.
- Replace or self-host the Inter font if needed for offline use

---

## License

This project is open source and free to use under the [MIT License](https://opensource.org/licenses/MIT).

---

Feel free to contribute improvements or report issues!

