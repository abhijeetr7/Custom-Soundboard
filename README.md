# Custom-Soundboard

🎛️ Custom Soundboard Builder
This is an interactive web application that allows users to create a personalized soundboard, assign sounds to keyboard keys, record sequences of sound events, and play them back like a DJ pad. It's perfect for podcasters, gamers, or anyone looking for a fun audio toy.

✨ Features
Sound Assignment:

Upload Sounds: Easily upload your own audio files (e.g., MP3, WAV) to use on the soundboard.

Sound Library: Choose from a built-in library of basic sounds like "Synth Beep," "Kick," "Snare," and "Hi-Hat."

Key Mapping: Assign any uploaded or library sound to one of the 16 available pads, which are mapped to QWERTY keyboard keys (Q, W, E, R, A, S, D, F, Z, X, C, V, T, Y, U, I).

Playback & Performance:

Instant Playback: Play assigned sounds by clicking the pads or pressing the corresponding keyboard keys.

Visual Feedback: Pads provide visual feedback (a blue glow) when a sound is played.

Recording & Sequencing:

Record Sequences: Record a sequence of played sounds, capturing the timing of each event.

Stop Recording: End the recording session.

Play Sequences: Play back your recorded sequences, recreating your performance.

Persistence & Export:

Save Presets: Save your current soundboard configuration (assigned sounds and recorded sequence) to your browser's local storage.

Load Presets: Load previously saved soundboard configurations.

Export Sequence: Export your recorded sequence as a JSON file, allowing you to share or back up your performances.

🚀 How to Use
Launch the Application: Open the index.html file in your web browser.

Start Audio Context: Click anywhere on the page to activate the audio context (required by Tone.js).

Assign Sounds:

Upload: Click the "Upload Sound" button and select an audio file from your computer. Once loaded, click any empty or assigned pad to assign the uploaded sound to it.

Library: Click one of the library sound buttons (e.g., "Synth Beep", "Kick"). Then, click any pad to assign that library sound.

Play Sounds:

Click directly on a soundboard pad.

Press the corresponding keyboard key (Q, W, E, R, A, S, D, F, Z, X, C, V, T, Y, U, I).

Record a Sequence:

Click the "Record" button. The button will pulse red, indicating recording is active.

Play sounds by clicking pads or pressing keys.

Click the "Stop" button to end the recording.

Play a Sequence:

After recording, click the "Play Sequence" button.

Save/Load Presets:

Click "Save Preset" to store your current soundboard setup.

Click "Load Preset" to restore a previously saved setup.

Export Sequence:

Click "Export Sequence" to download your recorded sequence as a JSON file.

🛠️ Technologies Used
HTML5: For the application structure.

Tailwind CSS: For responsive and modern styling.

JavaScript: For all interactive logic.

Tone.js: A powerful web audio framework for creating and playing sounds programmatically.

Web APIs: FileReader for file uploads, localStorage for preset management.

💡 Potential Enhancements
Volume controls (master and individual pad volume).

Ability to delete sounds from pads.

More advanced audio effects (reverb, delay, distortion).

Visual waveform display for uploaded sounds.

Looping functionality for sequences.

More comprehensive sound library.
