#Nutritional Value Checker

This project is a web application designed to analyze the nutritional values of food products from their nutritional labels. It uses Optical Character Recognition (OCR) with **Pytesseract** to extract text from images and evaluates the nutritional quality of the product.

## Features

- Upload an image of a nutritional label.
- Extract nutritional information using OCR.
- Calculate a nutritional score based on predefined standards.
- Interactive web interface with a pie chart visualization.

---

## Getting Started

Follow the steps below to set up and run the project locally.

### Prerequisites

Ensure you have the following installed:
1. **Python 3.7+**
2. **Flask** framework
3. **Pytesseract**
4. **Tesseract-OCR** software
5. **Pillow** for image handling
6. A web browser to interact with the application.

---

### Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your_username/nutritional-value-checker.git
   cd nutritional-value-checker
2.Install Dependencies
Use pip to install the required Python packages :  pip install -r requirements.txt
3. Download and Configure Tesseract-OCR

Download Tesseract-OCR from Tesseract GitHub page.
Install it and ensure it is added to your system's PATH.
For example, on Windows:
setx PATH "%PATH%;C:\Program Files\Tesseract-OCR"
4.Start the Application
Run the Flask app:python app.py
5. Access the Web Application
Open a browser and go to: http://127.0.0.1:5000/







File Structure
app.py
The main Flask application containing the OCR logic, nutritional scoring system, and API routes.

index.html
Frontend HTML template for the web interface.

Usage
Launch the application as mentioned above.
Upload an image of the nutritional label.
View the analyzed nutritional score and the OCR-extracted text on the results page.
Built With
Flask - For building the web application.
Pytesseract - OCR library for extracting text from images.
Chart.js - For visualizing results in the frontend.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Tesseract-OCR for the OCR engine.
Flask for the web framework.
perl
Copy code

### Additional Steps for Downloading Pytesseract

```bash
pip install pytesseract
Ensure Tesseract-OCR is installed on your system. Verify installation with:

bash
Copy code
tesseract --version

