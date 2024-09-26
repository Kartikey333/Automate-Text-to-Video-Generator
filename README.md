# Automate-Text-to-Video-Generator

This project automates the transformation of Press Information Bureau (PIB) press releases into video format using AI and Machine Learning, supporting English and 13 regional languages. The solution retrieves PIB press releases through web scraping, summarizes the content, extracts key points, and generates audio in multiple languages using text-to-speech. It selects relevant images from a predefined pool, combines them with the generated audio, and creates a video using Python video editing libraries. After the video is generated, an automated approval email is sent to PIB officers, and upon approval, the video is uploaded to social media platforms via APIs.

The system uses technologies like OpenAI for content analysis, Google Text-to-Speech for audio generation, and APIs from platforms like YouTube, Instagram, Twitter, and Facebook for automatic uploading. Key tools include Python libraries such as MoviePy and OpenCV for video creation, and MongoDB for storing data. The project focuses on reducing the human effort involved in converting press releases into videos, enabling faster and more engaging dissemination of information.

To run the project, install the necessary libraries (moviepy, opencv-python, gTTS, openai, pymongo, smtplib) and execute the main Python script.
