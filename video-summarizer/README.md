# Phidata Video AI Summarizer Agent 🎥

A multimodal AI agent that analyzes video content and answers questions using Google's Gemini 2.0 Flash model, enhanced with web search capabilities.

## Overview

This application allows users to upload videos and ask questions about their content. The AI agent processes the video, analyzes its content, and provides detailed insights by combining video understanding with supplementary web research when needed.

## Demo

### Testing with 30-Second Weather News

![Application Preview](https://github.com/fenkur/agentic-ai/blob/main/video-summarizer/preview.png)

### AI Analysis Results

![Analysis Results](https://github.com/fenkur/agentic-ai/blob/main/video-summarizer/result.png)

## Tools & Technologies Used

- **Streamlit** - Web application framework for the user interface
- **Phidata** - Agent framework for building AI agents
- **Google Gemini 2.0 Flash Lite** - Multimodal AI model for video analysis
- **Google Generative AI SDK** - For video file processing and API interaction
- **DuckDuckGo** - Web search tool for supplementary research
- **Python-dotenv** - Environment variable management
- **Tempfile** - Temporary file handling for video uploads

## Features

- 📤 Upload videos in multiple formats (MP4, MOV, AVI)
- 🎬 Built-in video player for preview
- 🤖 AI-powered video content analysis
- 🔍 Automatic web search for additional context
- 💬 Natural language question answering
- ⚡ Powered by Gemini 2.0 Flash for fast processing

## What I Learned

### 1. **Working with Multimodal AI Models**
   - Learned how to process and analyze video content using Google's Gemini 2.0 Flash model
   - Understood the workflow of uploading, processing, and querying video files through AI APIs
   - Gained experience handling different media types in AI applications

### 2. **Building AI Agents with Phidata**
   - Discovered how to use the Phidata framework to create specialized AI agents
   - Learned to integrate multiple tools (video analysis + web search) into a single agent
   - Understood agent initialization and caching strategies for performance optimization

### 3. **Video File Processing**
   - Implemented temporary file handling for secure video uploads
   - Learned about video file state management (PROCESSING status monitoring)
   - Gained experience with cleanup operations to prevent memory leaks

### 4. **Streamlit Best Practices**
   - Implemented `@st.cache_resource` for efficient agent initialization
   - Created responsive UI with file uploaders, text areas, and video players
   - Learned custom CSS styling within Streamlit applications
   - Handled loading states and error messages for better UX

### 5. **API Integration & Error Handling**
   - Integrated Google Generative AI SDK with proper API key management
   - Implemented robust error handling with try-except-finally blocks
   - Learned to manage API polling for asynchronous video processing

### 6. **Prompt Engineering**
   - Developed effective prompts for multimodal analysis
   - Learned to combine video insights with web research instructions
   - Understood how to guide AI responses to be detailed and actionable

## Usage

1. Launch the application
2. Upload a video file (MP4, MOV, or AVI)
3. Enter your question or request for analysis
4. Click "🔍 Analyze Video" to get AI-powered insights
5. Review the detailed analysis combining video content and web research