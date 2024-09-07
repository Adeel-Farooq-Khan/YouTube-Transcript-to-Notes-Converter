# YouTube Transcript to Detailed Notes Converter

A Streamlit app that extracts transcripts from YouTube videos and generates concise, actionable summaries using Google Gemini's generative model.

## Features

- **YouTube Transcript Extraction**: Extracts transcripts from YouTube videos using `YouTubeTranscriptApi`.
- **AI-Powered Summarization**: Generates a summary (within 250 words) of the transcript using Google Gemini Pro.
- **Visual Display**: Shows the YouTube video thumbnail for a more engaging experience.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

2. Enter a YouTube video link in the provided input box.

3. Click "Get Detailed Notes" to extract and summarize the transcript.

## Environment Variables

Ensure you have a `.env` file with your Google API key:
```env
GOOGLE_API_KEY=your_google_api_key
```

## Tech Stack

- **Python**
- **Streamlit**
- **Google Gemini API**
- **YouTube Transcript API**
- **dotenv**

## Contributing

Feel free to submit issues or pull requests. Contributions are welcome!

