# Text to Speech Converter

## Overview
This project is a lightweight, browser-based application that converts written text into spoken audio[cite: 1, 2]. It provides a clean interface where users can input text and listen to it using various system voices[cite: 1, 2].

## Core Features
* **Dynamic Voice Selection:** The application automatically populates a dropdown menu with available voice profiles using the browser's native Web Speech API[cite: 2].
* **Start & Stop Controls:** Users can initiate the speech synthesis or cancel it midway using a dynamic toggle button[cite: 2].
* **Visual State Feedback:** The action button changes its text and background color (green for start, red for stop) to indicate the current conversion state[cite: 2].
* **Input Validation:** The system alerts the user if they attempt to trigger the conversion with an empty text area[cite: 2].
* **Responsive Design:** The user interface includes media queries to gracefully adjust font sizes, padding, and layout for screens narrower than 768px[cite: 3].

## Technical Stack
* **HTML5:** Structures the application with a main container, a text area for input, and control elements[cite: 1].
* **CSS3:** Styles the interface utilizing a flexbox layout, an `antiquewhite` background, and rounded borders for inputs[cite: 3].
* **JavaScript (ES6):** Manages event listeners, handles the `SpeechSynthesisUtterance` object, and controls voice state management[cite: 2].

## Usage
1. Clone the repository to your local machine.
2. Open `index.html` in any modern web browser.
3. Type or paste your desired text into the text area[cite: 1].
4. Select a voice from the dropdown menu[cite: 1, 2].
5. Click **Start Speaking** to hear the audio[cite: 1]. 
6. Click **Stop Converting** to halt the audio playback at any time[cite: 2].
