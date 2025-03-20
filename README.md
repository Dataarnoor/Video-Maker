# Video Maker Website

## Overview
The **Video Maker Website** is a web-based platform that allows users to create videos by uploading photos and music. The system processes the inputs, synchronizes images with the audio, and exports a final video file. It is built with an **HTML & CSS frontend** and a **JavaScript & Python backend** for video processing.

## Features
- **Upload Images & Music**: Users can upload multiple images and an audio file.
- **Automatic Video Creation**: The system arranges images and syncs them with the uploaded music.
- **User-Friendly Interface**: Simple and intuitive design for seamless user experience.
- **Efficient Video Processing**: Backend powered by **Python (MoviePy)** and **JavaScript (Node.js)** for fast processing.
- **Downloadable Output**: Users can download the generated video file.

## Tech Stack
- **Frontend**: HTML, CSS
- **Backend**: JavaScript (Node.js), Python (MoviePy, OpenCV)
- **Database**: (Optional: Firebase, MongoDB, or Local Storage)

## Installation & Setup
### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/video-maker.git
cd video-maker
```
### 2. Install Dependencies
#### Backend (Node.js & Python)
```sh
cd backend
npm install
pip install moviepy opencv-python flask
```
### 3. Run the Backend Server
```sh
node server.js   # For Node.js backend
python app.py    # For Python-based video processing
```
### 4. Open the Frontend
Simply open `index.html` in a browser.

## Usage
1. **Upload images** (JPG, PNG) and a **music file** (MP3, WAV).
2. Click "Generate Video" to start processing.
3. Download the final video file once it's ready.

## Future Improvements
- Add **customizable transitions** and **effects**.
- Implement **cloud storage** for user projects.
- Enhance **video rendering speed** using GPU acceleration.

## Author
**Dataarnoor Singh**  
GitHub: [github.com/Dataarnoor](https://github.com/Dataarnoor)  
Email: [dataarnoor.oberoi@students.iiit.ac.in](mailto:dataarnoor.oberoi@students.iiit.ac.in)

