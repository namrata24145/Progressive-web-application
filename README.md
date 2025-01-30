# Progressive-web-application
COMPANY:CODTECH IT SOLUTIONS
NAME:NAMRATA POPAT GUND
INTERN ID:CT08HCM
DOMAIN:WEB DEVELOPEMENT
DURATION : 4 WEEKS
MENTOR:NEELA SANTOSH


This HTML document creates a Text-to-Speech (TTS) Converter, allowing users to input text and convert it into speech using their web browser. The functionality is enhanced with a service worker, which can be useful for caching assets and enabling offline support.

1. Understanding the HTML Structure
The HTML document follows standard web development practices and includes essential components:

Document Declaration & Metadata:

<!DOCTYPE html> ensures that the document follows the HTML5 standard.
<html lang="en"> defines English as the primary language.
The <head> section includes:
<meta charset="UTF-8">: Supports a wide range of characters.
<meta http-equiv="X-UA-Compatible" content="IE=edge">: Ensures compatibility with Microsoft Edge.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Optimizes display for mobile devices.
<title>Text to Speech Converter</title>: Sets the browser tab's title.
<link rel="manifest" href="manifest.json">: Links to a web app manifest file, useful for Progressive Web Apps (PWAs).
<script defer src="app.js"></script>: Loads an external JavaScript file (app.js) in a non-blocking way.
Body Content:

<h1>Text to Speech Converter</h1>: A heading that labels the page.
<textarea>: Provides an input field where users can type the text they want to convert to speech.
<button>: A button (id="convert-btn") to trigger the speech conversion.
2. JavaScript for Text-to-Speech Functionality
The script app.js (not shown here) is expected to contain the logic for converting text into speech using the Web Speech API.

The standard process for implementing text-to-speech is:

Capture Input Text: JavaScript retrieves the value from the <textarea> field.
Use Web Speech API: The speechSynthesis interface of the Web Speech API is used to generate speech.
Play the Speech Output: The selected voice reads the text aloud.
