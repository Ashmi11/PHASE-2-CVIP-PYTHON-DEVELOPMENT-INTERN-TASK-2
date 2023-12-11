Overview
This Python script implements a basic voice recorder application with a graphical user interface (GUI) using the tkinter library. The application allows users to record audio using their device's microphone, save the recordings as WAV files, and manage the recording process.

Functions
1. Start Recording
Click the "Record" button to initiate the recording process.
The "Record" button will be disabled, and the "Stop" and "Save Recording" buttons will be enabled.
The user will be prompted to choose a destination to save the recording in WAV format.
2. Stop Recording
Click the "Stop" button to halt the recording process.
The "Stop" button will be disabled, and the "Record" and "Save Recording" buttons will be enabled.
3. Save Recording
Click the "Save Recording" button to save the recorded audio.
The application will prompt the user to select a destination for saving the recording in WAV format.
After saving, the "Record" button will be enabled, and the "Stop" and "Save Recording" buttons will be disabled.
Dependencies 


The script relies on the following external libraries:

tkinter:

Used for creating the graphical user interface.
Usually comes pre-installed with Python.

pyaudio:

Used for audio input and output.
Install using the command: pip install pyaudio.

Usage


Install Dependencies:

Ensure you have Python installed on your system.
Install the required libraries using the provided commands.

Run the Script:

Execute the script in a Python environment.
A GUI window titled "Voice Recorder" will appear.

Recording:

Click the "Record" button to start recording.
Choose a destination to save the recording in the prompted file dialog.
While recording, the "Stop" button becomes active.
Stop Recording:

Click the "Stop" button to stop the recording.
The recorded audio is now ready for saving.

Save Recording:

Click the "Save Recording" button to save the recorded audio.
Choose a destination to save the WAV file in the prompted file dialog.

Exit the Application:

Close the GUI window to exit the application.

Notes
Ensure that your microphone is properly connected and functioning.
Adjustments to recording parameters such as sampling rate and bit depth can be made within the script based on user preferences.