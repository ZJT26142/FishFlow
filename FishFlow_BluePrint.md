# FishFlow 🐟💨

## Project Overview

This project is a Swift-based application designed to read texts displayed on Apple devices using OpenAI's Text-to-Speech (TTS) API. The app focuses on providing a minimalist yet powerful solution, seamlessly integrated across the Apple ecosystem.

## Key Features

1. **Text Extraction**:
   
   - Online texts: Extract content from webpages (e.g., articles, blogs).
   - Local texts: Read from files like PDFs, Apple Pages documents, and plain text files.
   - OCR for screen text using the Vision framework.

2. **Text-to-Speech**:
   
   - Use OpenAI's API for generating satisfying voice outputs.
   - Native integration with AVSpeechSynthesizer for fallback functionality.

3. **User Interface**:
   
   - Unified interface using SwiftUI for macOS, iOS, and iPadOS.
   - Accessibility-first design for users with ADHD and other needs.

## Use Cases

- Reading long paragraphs from web browsers, PDF viewers, Apple Pages, or Google Docs.
- Accessible reading tool for both online and offline content.
- Seamless usage across Apple devices.

## Feasibility Evaluation

The transition to Swift for a cross-Apple ecosystem app is feasible due to:

### **Advantages**

1. **Seamless Ecosystem Integration**:
   
   - Swift enables deep integration with Apple hardware and software.
   - Frameworks like SwiftUI, AVFoundation, and Vision provide robust tools for this project.

2. **User Experience**:
   
   - Apps built with Swift are optimized for responsiveness and performance.
   - Accessibility features can be seamlessly integrated.

3. **Performance**:
   
   - Swift's optimizations ensure real-time performance.
   - Native support for modern Apple APIs.

4. **Skill Growth**:
   
   - Transitioning to Swift offers valuable experience for future Apple ecosystem projects.

### **Challenges**

1. **Learning Curve**:
   
   - Familiarity with Swift and Apple frameworks requires initial investment.

2. **Cross-Platform Scope**:
   
   - Limited to the Apple ecosystem, with potential expansion challenges if cross-platform support is needed later.

3. **API Integration**:
   
   - Requires managing RESTful calls to OpenAI's API in Swift.

4. **Testing & Deployment**:
   
   - Testing across multiple Apple devices and joining the Apple Developer Program ($99/year).

## Development Goals

1. Build a **Minimal Viable Product (MVP)** with essential functionality:
   
   - Extract and process text from various sources.
   - Use OpenAI's TTS API to convert text to speech.
   - SwiftUI-based interface for cross-device compatibility.

2. Plan future improvements:
   
   - Add advanced OCR for screen-wide text recognition.
   - Optimize performance for real-time text-to-speech conversion.
   - Cloud sync for reading progress across devices.

## Technologies Used

- **Programming Language**: Swift
- **Frameworks**:
  - **SwiftUI**: For building the user interface.
  - **AVFoundation**: For TTS and audio playback.
  - **Vision**: For OCR and text detection.
- **APIs**: OpenAI's Text-to-Speech API

## Why This Project?

Inspired by the functionality of the Speechify Chrome extension, this project aims to provide:

- Independence from web browsers.
- A seamless experience across the Apple ecosystem.
- A clever solution balancing functionality with simplicity, catering to ADHD challenges.

## Developer's Note

I am an intermediate programmer transitioning from Python to Swift for this project. I aim to create a solution that is elegant, intuitive, and deeply integrated with Apple's ecosystem. Suggestions and contributions are welcome!
