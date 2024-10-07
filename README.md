<h1>Text-to-Voice and Voice-to-Text Project</h1>
<h2>Overview</h2>
<p>The Text-to-Voice and Voice-to-Text Web Application is a JavaScript-based project that allows users to convert typed text into speech and convert spoken input into 
text. This project uses the Web Speech API, enabling real-time speech synthesis and recognition directly within a web browser.</p>

<h2>Features</h2>
<li>Text-to-Voice (Speech Synthesis): Converts user input text into speech using various voice options (male, female, accents, etc.).</li>
<li>Voice-to-Text (Speech Recognition): Allows users to input speech via their microphone and converts it into text.</li>
<li>Multi-language Support: Supports various languages for both text-to-voice and voice-to-text functionality.</li>
<li>User Interface Controls: Simple buttons for starting speech recognition and triggering speech synthesis.</li>
<li>Responsive Design: Works on both desktop and mobile devices.</li>
<h2>Technologies Used</h2>
<li>HTML5: For structuring the web interface.</li>
<li>CSS3: For styling the UI and ensuring responsiveness.</li>
<li>JavaScript (ES6): For handling the logic of text-to-speech and speech-to-text operations.</li>
<li>Web Speech API:</li>
<ul>
  <li>SpeechSynthesis: Used for converting text to voice.</li>
  <li>SpeechRecognition: Used for converting voice to text.</li>
</ul>
<h2>Usage</h2>
<h3>Text-to-Voice (Speech Synthesis):</h3>
<li>Type the text into the text area.</li>
<li>Choose a voice from the dropdown menu (optional).</li>
<li>Click the "Text to Speak" button to hear the speech.</li>
<h3>Voice-to-Text (Speech Recognition):</h3>
<li>Click the "Start Listening" button.</li>
<li>Speak into your microphone, and the application will convert your speech to text in real-time.</li>
<li>Click the "Stop Listening" button to end the recognition session.</li>

<h2>Multi-language Support:</h2>
<li>The app supports different languages for both speech synthesis and recognition.</li>
<li>Ensure you select the appropriate language options before starting either feature.</li>
<h2>Browser Compatibility</h2>
<p>This project heavily relies on the Web Speech API, which may not be supported by all browsers. Here is a breakdown of browser compatibility:</p>
<li>Google Chrome: Full support for SpeechSynthesis and SpeechRecognition.</li>
<li>Firefox: Partial support (SpeechSynthesis only).</li>
<li>Safari: Partial support (SpeechSynthesis only).</li>
<li>Edge: Full support in the latest versions.</li>
<li>Mobile Browsers: Support may vary; Chrome on Android generally works well.</li>

<strong>Note: Ensure that microphone access is enabled in your browser for voice recognition to work properly.</strong>
