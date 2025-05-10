# Text-to-Speech

### 📣 **Text-to-Speech Web App (HTML/CSS/JavaScript)**

This project is a simple yet interactive **Text-to-Speech (TTS) web application** built using **HTML**, **CSS**, and **JavaScript**. It uses the **Web Speech API's `speechSynthesis` interface**, a built-in feature in most modern browsers, to convert user-entered text into spoken words.

---

### 🔧 **Features & UI Interactivity**

* **User Interface**:

  * A clean, responsive input area for typing or pasting text.
  * A dropdown to select from available system voices.
  * Play and stop buttons for controlling speech playback.
  * Optional sliders for adjusting **rate**, **pitch**, and **volume**.
* **Interactivity**:

  * Real-time voice preview and playback using the `speechSynthesis.speak()` method.
  * Dynamic loading of voices from the browser's speech engine.
  * JavaScript event listeners for seamless input and button interactions.

---

### 🧠 **Powered By**:

* **Web Speech API**: Utilizes `window.speechSynthesis` and `SpeechSynthesisUtterance` to trigger voice output.
* **No server required** – runs entirely in the browser.

---

### 📦 **Optional Enhancements**

* **Libraries** (for broader compatibility or features):

  * [`responsivevoice.js`](https://responsivevoice.org/) – for mobile-friendly, cross-browser speech fallback.
  * [`meSpeak.js`](https://www.masswerk.at/mespeak/) – for offline support using client-side voice synthesis.

These can serve as fallbacks if native browser support is unavailable or limited.

---

### 🌐 **Browser Support**

* ✅ **Google Chrome** – Full support
* ✅ **Firefox** – Supported (some voices and events may vary)
* ⚠️ **Safari** – Supported (limitations on iOS and older macOS versions)
* ❌ **Edge/IE Legacy** – Limited or no support (consider polyfills or libraries)

