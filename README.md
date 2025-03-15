# Video Conversion: Horizontal to Vertical with "Follow the Action" Approach

## Project Overview
This project provides a solution for converting horizontal (16:9) videos into vertical (9:16) formats optimized for social media and OTT platforms targeting mobile devices. The approach focuses on maintaining the subject's prominence in the vertical frame by dynamically cropping and resizing the video.

## Features
- **Dynamic Cropping**: Automatically detects and focuses on the main action or subject in the video, ensuring that it remains in view.
- **Vertical Conversion**: Transforms horizontal videos into vertical format (9:16) suitable for mobile viewing.
- **Audio Preservation**: Extracts and synchronizes the original audio with the transformed video.
- **High-Quality Output**: Uses `ffmpeg` and `moviepy` to ensure high-quality video and audio output.

## Requirements
- **Python 3.x**
- **MoviePy**: Python library for video editing.
- **FFmpeg**: Command-line tool for handling multimedia files.
- **OpenCV**: Library for computer vision tasks (for more advanced action detection).

## Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Bhavan-P/Video-Conversion-Horizontal-to-Vertical-.git
   cd Video-Conversion

2. **Install Dependencies**
   ```bash
   pip install moviepy
   pip install opencv-python  # Optional: if using advanced action detection

## Functionality
**convert_to_vertical(input_video, output_video)**: Main function to convert a horizontal video to vertical format. It handles resizing, cropping, and audio synchronization.
