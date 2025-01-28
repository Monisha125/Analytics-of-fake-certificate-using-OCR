# Analytics-of-fake-certificate-using-OCR

This project uses Optical Character Recognition (OCR) to analyze and detect fake certificates. By extracting and validating text from certificates, it helps ensure their authenticity.

## Features
- Extracts text from images of certificates
- Validates authenticity using pre-defined keywords
- Easy-to-use Python script

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Monisha125/fake-certificate-analytics.git
2.Install dependencies:
bash
Copy code
pip install -r requirements.txt
3.Install Tesseract OCR: Installation Guide
## Usage
Place the certificate image in the project directory.
Update the image_path in main.py.
Run the script:
bash
Copy code
python main.py
## License
This project is licensed under the MIT License.

go
Copy code

### `requirements.txt`
```plaintext
pytesseract
opencv-python
