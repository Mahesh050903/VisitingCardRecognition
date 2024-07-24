# VisitingCardRecognition

## Project Overview
Visiting Card Recognition is a web-based application designed to extract and organize information from images of visiting cards. The application leverages Optical Character Recognition (OCR) to convert text from images into structured data, using a language model to format and present this data coherently.

## Key Features
- **Image Upload**: Users can upload images of visiting cards through a simple HTML form.
- **OCR Processing**: The application uses LEADTOOLS and Pytesseract for extracting text from the images.
- **Structured Data Generation**: Extracted text is processed using the Llama3 language model to generate structured information, including company name, service type, name, position, phone number, email address, website, and address.
- **Web Interface**: A user-friendly web interface built with HTML, CSS, and JavaScript to facilitate easy interaction.
- **Backend**: Implemented with Python and Flask to handle web requests and process the uploaded images.
- **Model Persistence**: The application uses the Pickle library to save the state of the model.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Flask
- **OCR**: LEADTOOLS, Pytesseract
- **NLP**: LangChain, Llama3
- **Data Serialization**: Pickle

## Future Enhancements
- Improved error handling for unsupported file types and OCR errors.
- Enhanced user interface for a better user experience.
- Additional features for extracting specific fields from the visiting cards.
