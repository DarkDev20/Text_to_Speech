### Flask Text-to-Speech Web Application

This Flask web app converts the contents of a text file into speech and provides it as an audio file (.mp3). Using the **gTTS (Google Text-to-Speech)** library, the app processes the text and serves the resulting audio through Flask.

#### Features:
- Reads text from a file (Text.txt).
- Converts the text to speech using the **gTTS** library.
- Provides the generated .mp3 audio file via a Flask route (`/`).
- Option to download or stream the audio directly in the browser.

#### Requirements:
- Python 3.x
- Flask
- gTTS

#### Setup Instructions:

1. **Install the dependencies**:
   ```
   pip install Flask gTTS
   ```

2. **Prepare the Text.txt file**:
   Ensure you have a text file named `Text.txt` in the same directory as `app.py`. The app will use this file's content for conversion into speech.

3. **Running the Application**:
   Launch the Flask application:
   ```
   python app.py
   ```
   The app will be available at `http://localhost:5000`.
