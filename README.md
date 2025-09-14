Voice App
This is a simple and interactive web application that demonstrates how to convert text into spoken audio using the Gemini API. This project is an excellent entry point into AI-powered web applications and a valuable addition to any portfolio.
Core Concepts
Text-to-Speech (TTS): The process of synthesizing human-like speech from written text.
API Integration: Making a POST request to an external service (the Gemini API) to perform the TTS conversion.
Audio Data Processing: Handling the raw audio data returned by the API (16-bit PCM format) and converting it into a standard .wav file that can be played in the browser.
Front-End Development: Creating a user interface with HTML, CSS, and JavaScript to allow users to interact with the application.
Technologies Used
HTML: The foundational structure of the web page.
CSS (Tailwind CSS): For styling the user interface to be modern and responsive.
JavaScript: The logic for handling user input, making the API call, processing the audio data, and playing the sound.
Gemini API: The AI model (gemini-2.5-flash-preview-tts) that performs the speech synthesis.
How to Run the Project
This is a single-file web application, so no complex setup is required.
Download or clone the index.html file.
Open the file directly in your web browser (e.g., Chrome, Firefox, Safari) by double-clicking it.
Type some text into the text area and click the "Speak" button.
The application will send your text to the Gemini API, receive the audio data, and then play the synthesized speech.
Expected Output
You will see a clean, centered interface. After entering text and clicking the button, a loading indicator will appear, and once the process is complete, an audio player will show up with the synthesized speech.
Future Improvements
Add Voice Options: Allow the user to select from different voice names provided by the API to change the speaker's accent and tone.
Language Support: Add a dropdown to select the language for the synthesized speech.
Conversational Interface: Integrate this functionality into a simple chatbot where the responses are spoken aloud.
