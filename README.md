## Audio Recorder
Audio-recorder is a part of our Next Big Project "⚚ Jack The Grabber ⚚" Stay Tunned .
## Prerequisites

Make sure you have the following libraries installed in your Python environment:

- `pyaudio`
- `wave`
- `time`
- `requests`
- `requests_toolbelt`
- `json`
- `datetime`

You can install these libraries using the following pip command:

```bash
pip install pyaudio wave requests requests_toolbelt
```

## How to Use

1. **Capture Audio:**
   The script captures audio for a duration of 7 seconds using the default system microphone.

2. **Save Audio:**
   The captured audio is saved as a WAV file named `audio.wav` in the same directory as the script.

3. **Send to Discord:**
   The script then sends the captured audio as a file to a Discord webhook. Ensure you replace the webhook URL in the `requests.post()` function with your own webhook URL.

4. **Webhook Message:**
   The Discord webhook message includes a title, a description field with the Discord user profile link, and the captured audio file as an attachment.

## Script Explanation

- The script captures audio using the PyAudio library.
- The audio is saved as `audio.wav`.
- A Discord webhook message is created with a custom username, avatar URL, title, and description.
- The audio file and JSON payload are sent to the specified Discord webhook URL.

**Note:** Make sure to keep your webhook URL private and secure. Do not share it with anyone else.

Feel free to customize the script further according to your needs!
