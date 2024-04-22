# Text-to-Speech Converter

## Overview

This project is a simple text-to-speech converter built using HTML, CSS, and JavaScript. It enables users to convert text input into speech format, allowing them to listen to the text instead of reading it. Users can listen to text of any length.

## How it Works

1. Textarea: Users input the text they want to convert into speech into the provided textarea.

2. Voice Selection: Users can select a voice from the dropdown menu to customize the speech.

3. Listen Button: Upon clicking the "Listen" button, the text is converted into speech format, and users can listen to it.

## JavaScript Functionality

- The JavaScript code initializes a SpeechSynthesisUtterance object to handle text-to-speech conversion.
- It retrieves available voices from the browser's speech synthesis API and populates the dropdown menu with these voices.
- The selected voice is applied to the SpeechSynthesisUtterance object when the user chooses a voice from the dropdown menu.
- When the user clicks the "Listen" button, the text from the textarea is set as the text to be spoken by the SpeechSynthesisUtterance object.
- Finally, the speech synthesis API's speak method is called to convert the text to speech.

## Files

- `index.html`: Contains the HTML structure of the project.
- `style.css`: Contains the CSS styles for the project.
- `script.js`: Contains the JavaScript code for the functionality of the text-to-speech converter.

