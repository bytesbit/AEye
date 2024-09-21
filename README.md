# **AEye**

**AEye** is an AI-powered application that captures images through a webcam and searches for similar faces across "the web". By integrating facial recognition with web search, the application helps identify individuals and provides links to related profiles and information from the internet.

---

## **Table of Contents**

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [APIs & Dependencies](#apis--dependencies)
- [Configuration](#configuration)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)

---

## **Overview**

**AEye** leverages powerful AI and facial recognition technologies to:
1. Capture a photo via a webcam.
2. Analyze facial features using AI.
3. Perform a reverse image search on platforms such as **.
4. Retrieve profile links or information from social media platforms like **.
5. Use Generative AI to enhance search queries and provide more contextual information.

This tool is designed for use cases like facial identification, investigative tasks, and quick search through AI-powered facial matching.

---

## **Features**

- **Webcam Image Capture**: Captures real-time images from your webcam.
- **Facial Recognition**: Extracts facial features from the captured image using AI-based algorithms.
- **Web Search Integration**: Searches for similar faces across Google and social media platforms.
- **Generative AI Support**: Enhances search queries with AI-based suggestions and contextual information.
- **Profile Link Retrieval**: Returns links to matched profiles across the web, offering quick access to relevant information.

---

## **Installation**

### **Prerequisites**

Make sure you have Python 3.x installed. You will also need to install several dependencies:

- OpenCV: For capturing images from your webcam.
- face_recognition: For facial feature extraction.
- Requests/Selenium: For web scraping and API interaction.
- OpenAI API: For generative AI integration.

### **Steps**

1. Clone the repository:
   ```bash
   git clone https://github.com/bytesbit/AEye.git
   cd AEye
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate 
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
---

## **Usage**

1. **Capture an Image**: Use the command below to capture a photo from your webcam:
   ```bash
   python capture_image.py
   ```

2. **Search the Web**: Run the script to extract facial features and search the web for matching profiles:
   ```bash
   python search_faces.py
   ```

3. **Configuration**: Ensure you have your API keys set up in the `.env` file as follows:
   ```
   ```

4. **Results**: The application will return links to possible profiles and matches based on facial recognition.

---
