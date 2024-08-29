#AI in the Browser

The demos here showcase various applications of AI and machine learning technologies, including real-time audio transcription, object detection, face landmark detection, question-answering, text summarization, image captioning, sentiment analysis, and toxicity analysis. These demos utilize different models and libraries such as the Web Speech API, TensorFlow.js, and Transformers.js to provide interactive and practical examples of AI capabilities completely within the context of a browser.

This document provides an overview of the files in the project folder.

## Files

### [audio1.html](audio1.html)
This file implements real-time audio transcription using the Web Speech API. It includes a button to start and stop transcription and displays the transcribed text in a `div`.

### [audio2.html](audio2.html)
This file provides a web interface for recording audio and transcribing it to text using the Whisper model from Hugging Face. It includes buttons to start and stop recording, displays the transcription, and shows the status of the process.

### [cam1.html](cam1.html)
This file implements real-time object detection using TensorFlow.js and the COCO-SSD model. It captures video from the webcam, detects objects in the video stream, and displays the results along with bounding boxes around detected objects on a canvas.

### [cam2.html](cam2.html)
This file implements face landmark detection and overlays images on detected facial features. It uses the `drawImage` method to place googly eyes and wax lips on the detected face.

### [genai1.html](genai1.html)
This file implements a question-answering interface using BERT. It includes text areas for context and questions, a button to get the answer, and a `div` to display the output.

### [genai2.html](genai2.html)
This file implements text summarization using BART. It includes a text area for input text, a button to summarize the text, and a `div` to display the output.

### [image1.html](image1.html)
This file implements object detection using the COCO-SSD model. It includes functions to display detection results and draw bounding boxes around detected objects on a canvas.

### [image2.html](image2.html)
This file implements image captioning using Transformers.js. It includes an image upload input, a canvas to display the image, and a `div` to display the generated captions or errors.

### [sentiment1.html](sentiment1.html)
This file implements sentiment analysis using Transformers.js. It includes a text area for input text, a button to analyze sentiment, and a `div` to display the output.

### [sentiment2.html](sentiment2.html)
This file implements toxicity analysis using the TensorFlow.js Toxicity model. It includes a text area for input text, a button to analyze sentiment, and a `div` to display the output.