# Create a standalone README.md file with the provided content

readme_content = """
# Edge AI Audio Logger  
*A Hybrid Audio Capture, Transcription, and Task Summarization System*

## Overview
The Edge AI Audio Logger is a hybrid hardware and software system designed for capturing audio in real-world environments (classrooms, engineering sites, or space missions). The system transcribes conversations, extracts actionable tasks, and summarizes key points — helping educators, engineers, and astronauts maintain better logs and notes.

## Key Features
- Audio capture using M5Stack Core2 or Atom Echo  
- Wireless BLE/WiFi streaming to an iPhone  
- On-device or cloud-based transcription (Whisper)  
- Summarization & Task Extraction (LLM-powered via Ollama or OpenAI)  
- Outputs to iPhone Notifications, Notes App, or Email  

## Use Cases
- Teachers capturing lesson notes  
- Engineers logging field observations  
- Astronauts recording mission logs integrated into existing systems  
- Meeting minutes automation  

## Repository Structure
/firmware/          --> M5 Stack Audio Capture Code (ESP32)  
/iphone-app/        --> iOS Swift Application  
/cloud/             --> Cloud Infrastructure (Optional)  
/docs/              --> Documentation & Diagrams  
/tests/             --> Testing Scripts & Logs  

## Getting Started
1. Clone this repository:
```bash
git clone https://github.com/your-username/edge-ai-audio-logger.git
