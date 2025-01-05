# Video Summarizer Agent 🎥 

A powerful video analysis tool built with Streamlit and Google's Gemini 2.0 Flash that provides intelligent summaries and insights from both uploaded videos and YouTube content.

## 🌟 Features

- **Dual Input Support**: 
  - Upload local video files (MP4, MOV, AVI)
  - Analyze YouTube videos via URL
  
- **Advanced Analysis Capabilities**:
  - Video content summarization
  - Timestamp-based analysis
  - Custom query responses based on video content
  - Supplementary web research integration

- **Powered by Advanced AI**:
  - Uses Google's Gemini 2.0 Flash model
  - Multimodal analysis capabilities
  - Real-time processing

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **AI Model**: Google Gemini 2.0 Flash
- **Video Processing**: YouTube Tools
- **Language**: Python 3.x
- **Package Management**: pip

## 📋 Prerequisites

- Python 3.x
- Google API Key (for Gemini access)
- Internet connection for YouTube video analysis

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/paritosh-Shukla24/Video_Summarizer_Agentic_AI.git
cd Video_Summarizer_Agentic_AI
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add your Google API key:
```bash
GOOGLE_API_KEY=your_api_key_here
```

## 💻 Usage

1. Start the Streamlit application:
```bash
streamlit run vid.py
```

2. Access the web interface through your browser (typically http://localhost:8501)

3. Choose your analysis method:
   - Upload a video file
   - Or paste a YouTube URL

4. Enter your query or analysis requirements

5. Click "Analyze Video" to process and receive insights

## 📸 Application Screenshots & Process Flow

### 1. Main Interface
![Main Interface](screenshots/220800.png)
*The main application interface with upload and URL input options*

### 2. Video Upload Process
![Video Upload](screenshots/215543.png)
*Video file upload interface with format support display*

### 3. Analysis in Progress
![Analysis Process](screenshots/215531.png)
*Video processing and AI analysis in action*

### 4. Timestamp Analysis
![Timestamp Analysis](screenshots/215355.png)
*Detailed timestamp-based content breakdown*

### 5. YouTube URL Analysis
![YouTube Analysis](screenshots/215304.png)
*YouTube video analysis interface and results*

### 6. Final Summary
![Summary View](screenshots/215245.png)
*Comprehensive video summary and insights display*

### 7. Custom Query Response
![Query Response](screenshots/215155.png)
*AI responding to specific user queries about the video content*

## 🔍 Features In Detail

### Video File Analysis
- Upload videos in MP4, MOV, or AVI format
- Real-time video processing
- Custom query support for specific insights
- Detailed analysis results with timestamps

### YouTube Video Analysis
- Simple URL input
- Automatic video fetching and processing
- Comprehensive summary generation
- Timestamp-based content breakdown

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

Paritosh Shukla

## 🙏 Acknowledgments

- Google Gemini Team for the AI model
- Streamlit team for the amazing web framework
- Phidata for the Agent framework

## 📞 Support

For support, please open an issue in the GitHub repository or contact the maintainers.
