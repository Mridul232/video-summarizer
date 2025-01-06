# Generative AI Video Summarizer

Welcome to the **Generative AI Video Summarizer** project! This application leverages the power of the Gemini API and PhiData tools to generate detailed, user-friendly video summaries. Built using Streamlit, the tool provides an intuitive interface for uploading videos and analyzing their content using state-of-the-art generative AI models.

## Features

- **Video Upload**: Supports video files in formats like `.mp4`, `.mov`, `.avi`, `.mkv`, and `.webm`.
- **Customizable Queries**: Users can specify questions or insights they seek from the video content.
- **Generative Analysis**: Uses Gemini and PhiData's multimodal capabilities to analyze video content and provide actionable summaries.
- **Supplementary Web Research**: Integrates DuckDuckGo for gathering additional context to enhance the video analysis.
- **User-Friendly Interface**: Built with Streamlit for seamless interaction.


## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.8 or above
- Streamlit
- Required libraries (listed in `requirements.txt`)

### Setup Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/video-summarizer.git
   cd video-summarizer
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up the environment variable for your Google API Key:
   - Create a `.env` file in the project root directory.
   - Add your API key in the following format:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```
4. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Open the Streamlit application in your browser.
2. Upload a video file by clicking the **"Upload a video file"** button.
3. Enter a query in the text area to specify what insights you are seeking from the video.
4. Click **"Analyze Video"** to generate a detailed summary.
5. View the analysis results in the application interface.

## Technologies Used
- **Gemini API**: Advanced generative AI model for video analysis.
- **PhiData**: Multimodal agent integration.
- **DuckDuckGo**: Web search integration for additional insights.
- **Streamlit**: Simplified frontend development for AI applications.

## File Structure
```
video-summarizer/
├── app.py                 # Main application file
├── requirements.txt       # Dependencies list
├── .env.example           # Example environment variables
└── README.md              # Project documentation
```

## Example Query
Upload a video and ask questions like:
- "Summarize the main points of the video."
- "What are the key takeaways?"
- "Provide additional context about the events shown."

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- **PhiData Team**: For the robust multimodal capabilities.
- **Google Generative AI**: For powerful video analysis APIs.
- **Streamlit**: For the user-friendly app framework.

## Contact
For queries, suggestions, or feedback, please contact mridulgarg2004@gmail.com
---

Happy Summarizing! 🎥✨

