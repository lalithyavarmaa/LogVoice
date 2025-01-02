# Log Voice 🎙️  
Log Voice is an Android application designed to simplify managing and transcribing voice notes. Whether you're in a meeting, attending a lecture, or capturing ideas on the go, Log Voice allows you to record, store, and playback your notes effortlessly. With automatic transcription powered by Google's Speech Recognition API, converting audio to text has never been easier!  

Features:  
- Record voice notes with timestamps and custom names.  
- Save recordings securely using Firebase Real-Time Database.  
- Play back your recorded audio files seamlessly.  
- Generate text from your voice recordings with automatic transcription.  
- Intuitive and user-friendly interface.  

Technologies Used:  
- Android Studio (Java, XML) for application development.  
- Firebase Real-Time Database for user authentication and audio file storage.  
- Media Recorder Library for voice recording.  
- Media Player Library for audio playback.  
- Google Speech Recognition API for automatic transcription.  

Installation Steps:  

1. Clone the Repository:  
   ```bash
   git clone https://github.com/praneethakancharla/LogVoice.git
   ```

2. Open in Android Studio:  
   - Launch Android Studio.  
   - Select "Open an existing project."  
   - Navigate to the `LogVoice/` directory and open it.  

3. Set Up Firebase:  
   - Go to the [Firebase Console](https://console.firebase.google.com/).  
   - Create a new project or select an existing one.  
   - Add Firebase to your Android app:  
     - Download the `google-services.json` file from Firebase.  
     - Place the file in the `app/` directory of your project.  

4. Build and Run:  
   - Sync the project with Gradle files.  
   - Connect your Android device or use an emulator.  
   - Build and run the app.  
