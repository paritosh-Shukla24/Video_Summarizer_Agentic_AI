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

### 1. Initial Interface
![Summary](Screenshot%202025-01-05%20215155.png)

*The main application interface showing the Phidata Video AI Summarizer Agent powered by Gemini 2.0*

### 2. Video Analysis Setup
![Processing](Screenshot%202025-01-05%20215531.png)

*Interface for uploading videos and entering YouTube URLs*

### 3. Processing Interface
![Analysis Setup](Screenshot%202025-01-05%20215543.png)
*The processing view showing active video analysis*

### 4. Analysis Progress

![Results](Screenshot%202025-01-05%20215245.png)
*Detailed view of the analysis progress with timestamps*

### 5. Content Processing
![Content Processing](Screenshot%202025-01-05%20215304.png)
*Video content being processed with AI analysis*

### 6. Results View
![Analysis Progress](Screenshot%202025-01-05%20215355.png)
*Display of comprehensive video analysis results*

### 7. Final Summary
![Initial Interface](Screenshot%202025-01-05%20220800.png)
*Final summary and insights from the video analysis*

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
