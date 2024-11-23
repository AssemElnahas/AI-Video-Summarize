# AI Video Summarizer

An interactive web application built with **Streamlit** that allows users to upload video files, extract key frames, and generate a summarized description of the video content using AI.

## Features

- **Video Upload**: Accepts video files in formats like MP4, AVI, MOV, and MKV.
- **Key Frame Extraction**: Analyzes the video and extracts representative key frames.
- **AI-Powered Summarization**: Generates a concise summary of the video content using transformer-based AI models.
- **Interactive Visualization**: Displays extracted key frames and video summary in an easy-to-use interface.

---

## How It Works

1. **Upload Video**: The user uploads a video file to the app.
2. **Frame Extraction**: Key frames are extracted using OpenCV.
3. **Summarization**: The extracted frames are analyzed, and a natural language summary is generated using Hugging Face's `facebook/bart-large-cnn` model.
4. **Results Displayed**: Key frames and the summary are shown in the app.

---

## Tech Stack

- **Python**
- **Streamlit**: Interactive web app framework.
- **OpenCV**: Video processing and frame extraction.
- **Hugging Face Transformers**: AI-based text summarization.
- **Tempfile**: For temporary video file storage.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-video-summarizer.git
   cd ai-video-summarizer
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run video_summarizer.py
   ```

---

## Requirements

- Python 3.8 or higher
- Required Python libraries:
  - Streamlit
  - OpenCV
  - Transformers
- Stable internet connection for model downloads.

---

## Usage

1. Launch the app and open the URL provided by Streamlit.
2. Upload a video file in one of the supported formats.
3. View extracted key frames and read the AI-generated video summary.

---

## Example Output

- **Input**: A sample video of a nature documentary.
- **Output**:
  - Key Frames: Images from representative moments in the video.
  - Summary: "The video captures scenic landscapes, wildlife activity, and serene environments."

---

## Project Structure

```
ai-video-summarizer/
├── video_summarizer.py  # Main Streamlit app script
├── README.md            # Project description
├── requirements.txt     # Required dependencies
```

---

## Contributing

Contributions are welcome! Please create an issue or submit a pull request for any suggestions or enhancements.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Acknowledgments

- [Streamlit](https://streamlit.io/) for building an amazing framework.
- [OpenCV](https://opencv.org/) for video processing.
- [Hugging Face](https://huggingface.co/) for providing pre-trained AI models.
