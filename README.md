# Video Trimmer Web Application

The Video Trimmer web application allows you to upload a video, specify a start and end time, and trim the video to create a shorter clip. You can then download the trimmed video for your use. This application is built using Python (Flask) for the backend and JavaScript for the frontend.

## Prerequisites

Before you begin, ensure you have the following requirements met:

1. Python (3.x recommended) installed on your machine.
2. Required Python packages installed. You can install them using `pip`:

pip install flask moviepy


3. [FFmpeg](https://www.ffmpeg.org/download.html) installed on your system. FFmpeg is used for video processing.

## Installation

1. Clone this repository to your local machine:

git clone https://github.com/adarsh-dikhit/video-trim-using-python.git
https://github.com/adarsh-dikhit/video-trim-using-python.git

cd video-trimmer-web-app


3. Run the Flask application:

python app.py


The web application will be accessible at `http://localhost:5000/` in your web browser.

## Usage

1. Access the application by opening a web browser and navigating to `http://localhost:5000/`.

2. Upload a video file by clicking the "Upload Video" button.

3. Specify the start and end times for trimming in seconds.

4. Click the "Trim Video" button to create a trimmed video.

5. Once the trimming is complete, you can download the trimmed video by clicking the "Download Trimmed Video" link.

## Configuration

- To configure the project, replace `'YOUR_API_KEY'` in the code (`app.py`) with your Google Cloud Console API key.

## Troubleshooting

If you encounter any issues or errors while using the application, please check the following:

- Ensure you have FFmpeg installed and available in your system's PATH.
- Verify that the `temp` directory exists in the project directory and has write permissions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Flask](https://flask.palletsprojects.com/): Web framework for Python.
- [moviepy](https://github.com/Zulko/moviepy): Python library for video editing.
- [FFmpeg](https://www.ffmpeg.org/): Multimedia framework for video processing.


