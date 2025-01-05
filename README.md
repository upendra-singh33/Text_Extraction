Text Extraction from Image

This project provides a web-based application that extracts text from images using Optical Character Recognition (OCR) technology. It allows users to upload an image, process it, and retrieve the extracted text.

Technologies Used

Backend:
	•	Flask: A lightweight Python framework for handling HTTP requests and routing.
	•	SQLAlchemy: An ORM used for easy database interactions.
	•	Tesseract (OCR): Open-source OCR engine used for text extraction from images.
	•	OpenCV (cv2): A computer vision library used for image preprocessing before text extraction.

Frontend:
	•	HTML: For structuring the content and layout of the web page.
	•	CSS: For styling and ensuring the webpage is visually appealing.
	•	JavaScript: Used for interactive behavior like form submission, file handling, dynamic          content updates, and controlling UI states (e.g., enabling/disabling buttons based on process state).

Database:
	•	SQLite: Lightweight database used for storing user data and the extracted text.
	•	SQLAlchemy ORM: Provides an easy-to-use interface for database operations in    Python.

Features
	•	Upload an image to extract text.
	•	Displays the extracted text on the webpage.
	•	Stores the user-submitted image and the extracted text in an SQLite database.
	•	Provides a clean, responsive, and interactive user interface.

Prerequisites
Make sure you have Python installed on your machine.
Install there libraries:
•	•  Flask: For creating the web application.
•	pytesseract: Python wrapper for Tesseract OCR.
•	opencv-python: For image preprocessing before text extraction.
•	gtts: Google Text-to-Speech library (if you want to add text-to-speech features).
•	langdetect: For language detection (optional, if you plan to detect the language of the extracted text).
•	fpdf: For generating PDF files (optional, if you plan to export the extracted text to PDFs).
•	python-docx: For working with Word documents (optional, if you plan to save extracted text in DOCX format).
•	flask_sqlalchemy: For interacting with the SQLite database.
•	werkzeug: A utility library used by Flask for handling various server-side operations.

Install Tesseract OCR
You need to have Tesseract OCR installed on your machine. Follow the installation instructions for your operating system:
•	Windows: Download and install Tesseract from here.
•	Mac: Install using Homebrew:


Set environment variable

Variable name :    TESSDATA_PREFIX
Variable value :     C:\Program Files\Tesseract-OCR        (or where you install the tesseract-OCR)

Process to Run Project

1.	Paste the project folder to desktop
2.	Open folder and run cmd in project directory
3.	Type: python app.py
4.	Copy the URL which shown in terminal and paste it on any browser.
5.	Now you ready to run the project.
o	You must register first.
o	Then you can login by your username and password.
o	After login you can upload the image file and choose the language of the text present in image.
o	And hit covert button 
o	Now your text display in the bottom of image.
o	You can copy the text or download word file as your preference.
