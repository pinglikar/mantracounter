# Mantra Counter
A simple counter for mantra jaap for personal use. It can be used on smartphones as well as on desktops. 
A lightweight, high-performance, and privacy-first web utility designed for tracking mantra repetitions and as jaap counter for spiritual practices. Runs entirely client-side with zero external trackers or database dependencies.

🔗 [View Live Demo](https://pinglikar.github.io/mantracounter/) 
  https://pinglikar.github.io/mantracounter/

## Features

* **Lightning Fast & Lightweight:** Built as a single, highly optimized static file (~16.8 KB), ensuring instantaneous load times even on low-bandwidth networks or mobile devices.

* **100% Client-Side Persistence:** Utilizes browser `localStorage` to securely save your counts and session history locally on your device without transmitting data to any external server.

* **Privacy-First:** No cookies, no third-party analytics, and no user tracking. Your practice remains entirely private.

* **Responsive Design:** Optimized for both desktop browsers and mobile touchscreens for distraction-free use.

## Technical Architecture

This application is engineered as a static Single Page Application (SPA):

* **Core:** Pure Vanilla JavaScript, HTML5, and CSS3.

* **Hosting:** Deployed via GitHub Pages for reliable, fast static asset delivery.

* **State Management:** Local browser storage APIs for state persistence across sessions.

## Getting Started / Local Development

Since this is a static web application, you do not need complex build tools, Node.js runtimes, or database setups to run it locally.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/pinglikar/mantracounter.git
   ```

2. **Navigate to the directory:**
   ```bash
   cd mantracounter
   ```

3. **Run locally:**
   Simply open `index.html` in any modern web browser, or serve it via a local static server (e.g., Python's built-in server):
   ```bash
   python3 -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser.

## License

This project is open-source and available under the terms of the [MIT License](LICENSE).
