# BizCardX: Extracting Business Card Data with OCR

BizCardX is a Streamlit application that extracts business card data using Optical Character Recognition (OCR) and manages it in a MySQL database. This application allows users to upload images containing business cards, extract relevant information, preview, modify, and store the data in a database.

## Features

- Image Upload: Upload an image containing a business card for data extraction.
- Data Extraction: Extracts relevant information such as name, designation, company name, contact, email, website, address, and pin code from the uploaded image.
- Data Preview and Modification: Preview extracted data, make modifications, and update the information before storing it in the database.
- Database Management: Store, view, and delete business card data in the connected MySQL database.
- User Interface: Provides an interactive and user-friendly interface for a seamless experience.

## Screenshots

- ![Image_uploading](Images/Screenshot%20(3).png)

  - User is prompted to select an image from their local machine.
  - The selected image is displayed on the screen for further processing using OCR.

- ![OCR extraction](Images/Screenshot%20(4).png)

   - Text extracted from the image using EASTOCR is displayed in separate columns such as name, email, address, company name, and phone number.
   - Users are given the option to upload the extracted text to the database or delete it.

- ![Data_Base](Images/Screenshot%20(6).png)

  - The extracted data is stored in the database after the OCR extraction process.

## Dependencies

- Streamlit
- easyocr
- PIL (Python Imaging Library)
- pandas
- numpy
- re (regular expression)
- mysql-connector-python
- sqlalchemy

## Installation

1. Clone the repository: `https://github.com/Yagneshsure/BizcardX.git`
2. Install the dependencies: `pip install -r requirements.txt`

## Usage

1. Run the application: `streamlit run app.py`
2. Upload an image containing a business card.
3. Preview the extracted data and make modifications if necessary.
4. Store the data in the connected MySQL database.
5. Manage the data stored in the database, including previewing and deleting entries.
