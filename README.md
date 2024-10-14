# YouTubeTranscriber


```markdown
# YouTube Transcript to Detailed Notes Converter

## Overview
This project is a web application built using Streamlit that allows users to convert YouTube video transcripts into summarized notes. By leveraging Google's generative AI capabilities, the application provides concise and informative summaries from the video transcripts, making it easier for users to grasp key points from videos without watching the entire content.

## Features
- Input a YouTube video link to fetch its transcript.
- Summarizes the transcript into detailed notes within 250 words.
- User-friendly interface built with Streamlit.

## Technologies Used
- **Python**: The programming language for the backend.
- **Streamlit**: For creating the web application interface.
- **Google Generative AI (Gemini Pro)**: To generate summaries from the video transcripts.
- **YouTube Transcript API**: To retrieve transcripts from YouTube videos.
- **dotenv**: For managing environment variables.

## Getting Started

### Prerequisites
- Python 3.10 or later
- Google Cloud account with access to Generative AI API
- Required Python libraries (listed in the `requirements.txt`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/VAP2999/YouTubeTranscriber.git
   cd YouTubeTranscriber
   ```

2. Create a virtual environment and activate it:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:
   - Create a `.env` file in the project root and add your Google API key:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```

### Running the Application
To start the Streamlit app, run:
```bash
streamlit run app.py
```
Open your browser and go to `http://localhost:8501` to view the application.

### Usage
1. Enter the URL of the YouTube video in the input box.
2. Click the **Get Detailed Notes** button.
3. The application will display a summary of the video transcript below.

## Example
![YouTube Transcript to Notes Converter](http://img.youtube.com/vi/example_video_id/0.jpg)

## Contributing
Contributions are welcome! If you have suggestions for improvements or want to add new features, please open an issue or submit a pull request.

```
