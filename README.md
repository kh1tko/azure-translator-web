# Azure Translator Web Application

## Description
**Azure Translator Web Application** is a web-based text translation tool built using Flask and Azure Translator API. It provides a user-friendly web interface to input text and select the target language for translation.

## Features
- Translate text between multiple languages.
- Intuitive and easy-to-use web interface.
- Powered by Azure Translator API for accurate translations.

## Installation

### 1. Clone the repository
Clone this repository to your local machine:
```bash
git clone https://github.com/<your-username>/azure-translator-web.git
cd azure-translator-web
```

## 2. Install dependencies
Ensure you have Python 3.10 or higher installed. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## 3. Configure environment variables
Create a .env file in the root directory and add the following environment variables:
```bash
KEY=<your_api_key>
ENDPOINT=<your_endpoint>
LOCATION=<your_region>
```

## 4. Run the application
```bash
python app.py
```
The application will be available at http://127.0.0.1:5000.

## How to Use

- Open the application in your web browser.
- Enter the text you want to translate in the text field.
- Select the target language from the dropdown menu.
- Click the "Translate" button. The translated text will be displayed on the result page.


## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions, suggestions, or feedback:

- **Email**: kh11tko@gmail.com
- **GitHub**: kh1tko
