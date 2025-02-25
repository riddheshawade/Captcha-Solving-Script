# Captcha-Solving-Script
This Python-based automation tool simplifies the process of checking trademark application statuses on the IP India eRegister website. It uses Selenium for web automation and EasyOCR to extract CAPTCHA text, enabling a seamless and efficient retrieval of trademark details.

# Trademark Application Status Checker  

This project automates the process of checking trademark application statuses on the [IP India eRegister](https://tmrsearch.ipindia.gov.in/eregister/) website. It utilizes **Selenium** for web automation and **EasyOCR** for CAPTCHA recognition.  

## 🚀 Features  
- Automates navigation on the IP India eRegister website.  
- Extracts and processes CAPTCHA using EasyOCR.  
- Retrieves trademark application details based on the given application number.  

## 🛠 Technologies Used
  Python – Core programming language
  Selenium – Web automation for navigating and interacting with elements
  EasyOCR – Optical Character Recognition (OCR) for CAPTCHA extraction
  Pillow (PIL) – Image processing to handle CAPTCHA screenshots
  Google Chrome & ChromeDriver – Browser automation

## 📌 Prerequisites  
Before running the script, ensure you have:  
- **Google Chrome** installed.  
- **Chromedriver** compatible with your Chrome version.  

## 📥 Installation  

1. **Clone the repository**  
 
   git clone https://github.com/your-username/trademark-status-checker.git
   cd trademark-status-checker

2. Create a virtual environment (optional but recommended)
    python -m venv venv
    venv\Scripts\activate  # On Windows
   
3. Install dependencies
    pip install -r requirements.txt

## 🔧 Configuration
    Update the application number in the script before running.
    If CAPTCHA recognition fails, try improving the OCR settings.

## 🛠 Troubleshooting
    If ChromeDriver is not found, download the correct version from ChromeDriver and add it to your system path.
    Ensure all dependencies are correctly installed.
## 📜 License
    This project is open-source and available under the MIT License.


