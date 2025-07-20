<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>YouTube Video Voice Replacer</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
        Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
      line-height: 1.6;
      color: #24292e;
    }
    h1, h2 {
      color: #0366d6;
    }
    code {
      background-color: #f6f8fa;
      padding: 0.2em 0.4em;
      border-radius: 3px;
      font-family: monospace;
    }
    pre {
      background-color: #f6f8fa;
      padding: 1em;
      overflow-x: auto;
      border-radius: 6px;
    }
    a.button {
      background-color: #28a745;
      color: white;
      padding: 0.6em 1.2em;
      text-decoration: none;
      border-radius: 5px;
      font-weight: 600;
      display: inline-block;
      margin-top: 1em;
    }
    a.button:hover {
      background-color: #218838;
    }
  </style>
</head>
<body>
  <h1>YouTube Video Voice Replacer</h1>

  <p>
    <strong>YouTube Video Voice Replacer</strong> is a Python tool that downloads a YouTube video, automatically transcribes its audio using OpenAI's Whisper speech-to-text model, generates a voice-over from the transcription using Google Text-to-Speech (gTTS), and replaces the original audio track with the generated voice. It’s ideal for voice-over generation, dubbing, or creative audio editing workflows.
  </p>

  <h2>Features</h2>
  <ul>
    <li>Download YouTube videos reliably using <code>yt-dlp</code></li>
    <li>Extract and transcribe audio with OpenAI Whisper speech-to-text model</li>
    <li>Generate spoken audio from transcribed text using Google Text-to-Speech (<code>gTTS</code>)</li>
    <li>Replace original video audio with generated voice-over</li>
    <li>Handles audio/video duration mismatch gracefully to avoid errors</li>
    <li>Automatically cleans up temporary audio files</li>
  </ul>

  <h2>Requirements</h2>
  <ul>
    <li>Python 3.7 or higher</li>
    <li><a href="https://ffmpeg.org/download.html" target="_blank" rel="noopener">FFmpeg</a> installed and available in your system PATH</li>
  </ul>

  <h2>Installation</h2>
  <p>Install the required Python packages with pip:</p>
  <pre><code>pip install yt-dlp moviepy gtts openai-whisper torch</code></pre>

  <h2>Usage</h2>
  <p>Run the Python script. When prompted, enter a YouTube video URL or press Enter to use the default example video:</p>
  <pre><code>python yt_voice_replace.py</code></pre>
  <p>The script will produce a new video file named <code>final_output.mp4</code> in the current folder, containing the generated voice replacing the original audio.</p>

  <h2>Example</h2>
  <p>Here’s a quick run-through of the process:</p>
  <ol>
    <li>Download a YouTube video</li>
    <li>Extract and transcribe its audio using Whisper</li>
    <li>Generate a speech audio file from the transcript</li>
    <li>Replace the original audio track in the video with the generated speech</li>
    <li>Save the final video with replaced audio</li>
  </ol>

  <h2>Google Colab</h2>
  <p>To try this tool easily without local setup, use this Google Colab notebook:</p>
  <a href="https://colab.research.google.com/drive/YOUR_COLAB_NOTEBOOK_ID" target="_blank" rel="noopener" class="button">Open in Google Colab</a>
  <p><small>Replace <code>YOUR_COLAB_NOTEBOOK_ID</code> with your actual Colab notebook URL or ID.</small></p>

  <h2>License</h2>
  <p>This project is open-source and available under the <a href="https://opensource.org/licenses/MIT" target="_blank" rel="noopener">MIT License</a>.</p>

  <hr />
  <p>Created with ❤️ using Python, yt-dlp, OpenAI Whisper, Google TTS, and MoviePy.</p>
</body>
</html>
