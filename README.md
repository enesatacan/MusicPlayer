🚀 Daily JavaScript App - 10

This repository is part of a daily challenge to build a JavaScript application every day. The goal is to enhance my JavaScript skills 🧠 and cultivate the habit of consistent coding. 💻✨

Music Player

This project is a web-based audio player that provides basic functionalities such as playing and pausing an audio file. The playback progress is visualized with a progress bar, allowing the user to seek forward or backward.

Features 🎵

Play and pause audio files ⏯️

Automatically update the progress bar during playback ⏳

Seek to a specific time using the progress bar ⏩⏪

Technologies Used 💻

HTML: Used to structure the webpage.

CSS: Basic styles for visual design.

JavaScript: Handles audio playback, pausing, and progress bar functionality.

Code Explanation 🧩

Key Functions 📜

1. song.onloadedmetadata

Triggered when the audio file is loaded. Sets the maximum value of the progress bar to the total duration of the audio file.

2. playPause()

Manages the play and pause functionality:

If the audio is playing, it pauses and changes the control icon to "play" ⏸️➡️▶️.

If the audio is paused, it starts playing and changes the control icon to "pause" ▶️➡️⏸️.

3. setInterval

Runs every 500 milliseconds to update the progress bar value based on the current playback time of the audio.

4. progress.onchange

Triggered when the user changes the progress bar value. This function:

Updates the playback time to the new value from the progress bar.

Resumes playing the audio.

Changes the control icon to "pause" ▶️➡️⏸️.

1️⃣ Clone the repository:

git clone https://github.com/enesatacan/MusicPlayer


![image](https://github.com/user-attachments/assets/de601eb1-32ca-491f-af1b-34ada9a182f5)


