Face Recognition & Authentication System<br>
Technology Stack: Python, OpenCV, PyQt5, Facenet/InsightFace, SQLite.<br>

Overview: Developed a real-time face recognition system that authenticates users by comparing facial embeddings.<br>

Key Contributions:<br>

  Designed a responsive PyQt5 interface to guide users in positioning their faces within an overlayed elliptical frame.<br>
  
  Implemented image pre-processing functions (brightness enhancement, sharpness detection, face cropping) to ensure high-quality input.<br>
  
  Extracted face embeddings using deep learning models and computed cosine similarity for robust identity verification.<br>
  
  Managed user data storage through an SQLite database, including student ID, facial landmarks, bounding boxes, and encoded face images.<br>
  
  Integrated user dialogs for seamless face registration and confirmation, enhancing user experience and data accuracy.<br>

Install dependencies<br>
```
pip install -r requirements.txt
```
