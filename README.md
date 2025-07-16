# Text-Recognition-in-Unstructured-Environments

Scene Text Recognition in Unstructured Environments
This project demonstrates the implementation of a Scene Text Recognition System using EasyOCR. It detects and recognizes text from images in unstructured environments, and compares OCR performance between original and preprocessed images using various image processing techniques.

📌 Features

Upload and process any image with scene text.

Perform text detection using EasyOCR.

Apply adaptive image preprocessing for enhanced OCR accuracy.

Visualize bounding boxes and recognized text on the original and processed images.

Analyze and compare OCR results:

Number of text regions

Total characters and words

OCR confidence scores

🧰 Technologies Used

Python 3.x

Google Colab (Jupyter Notebook)

EasyOCR

OpenCV

NumPy

Matplotlib

PIL (Pillow)

📦 Installation

Install the required libraries before running the notebook:

bash
Copy
Edit
pip install easyocr opencv-python matplotlib numpy Pillow imutils
🖼️ How It Works
Image Upload: User uploads a scene image containing text.

Text Detection (Original): EasyOCR detects text from the original image.

Image Preprocessing: Applies adaptive thresholding to enhance text visibility.

Text Detection (Processed): EasyOCR detects text from the preprocessed image.

Result Comparison: Compares the number of detected regions, characters, words, and confidence scores.

Visualization: Bounding boxes and recognized text are shown on the images using Matplotlib.

📊 Example Output



<img width="638" height="467" alt="image" src="https://github.com/user-attachments/assets/40a761e7-66b3-4999-9d06-718a66689941" />



<img width="602" height="373" alt="image" src="https://github.com/user-attachments/assets/92e95351-2dbd-488d-bb27-4a5f68e8cac8" />


<img width="646" height="383" alt="image" src="https://github.com/user-attachments/assets/90eebd20-7892-4942-96b3-1272323ebe25" />

<img width="637" height="375" alt="image" src="https://github.com/user-attachments/assets/dd71803e-dbfa-4dee-8e71-8e5d349604ba" />

<img width="565" height="321" alt="image" src="https://github.com/user-attachments/assets/7e6d434a-6f86-4ae6-88bd-9f4fbcd80b14" />


Improvement Summary:

Change in detected regions: +0
Change in characters: -1
Change in words: +0
Average confidence (original): 1.00
Average confidence (preprocessed): 0.86
📂 File Structure
Cv.ipynb – Main notebook containing all steps: setup, detection, preprocessing, analysis, and visualization.

functions.py (optional) – Contains modular functions if refactored for reusability.

requirements.txt – List of all required Python packages (optional).

🔍 Use Cases

Automatic signboard and document digitization.

Assistive tech for visually impaired.

OCR in low-quality or complex background images.

Information extraction from scene photos for smart systems.

📌 Future Enhancements

Support for multi-language text detection.

Integration with real-time camera input.

Export OCR results to JSON or CSV.

GUI-based interface or web deployment.

