# BizCardX: Business Card Data Extraction using OCR
BizCardX is a Streamlit web application designed to effortlessly extract data from business cards using Optical Character Recognition (OCR) technology. With BizCardX, users can easily upload images of business cards, and the application leverages the powerful easyOCR library to extract pertinent information from the cards. The extracted data is then presented in a user-friendly format and can be stored in a MySQL database for future reference and management.

# Prerequisites
To successfully run and deploy BizCardX, ensure you have the following prerequisites in place:

Python environment (Python 3.x recommended) Necessary libraries installed: Streamlit, Pandas, easyOCR, PIL, cv2, matplotlib, re, sqlite3 A functioning MySQL server setup Features Home The home section of BizCardX provides users with an introduction to the application, outlining the technologies utilized and offering a concise overview of its capabilities.

# Upload & Extract
This pivotal section empowers users to upload images of business cards. Once an image is uploaded, BizCardX undertakes the image processing using the easyOCR library to extract essential details from the card. The extracted information encompasses:

Company name Card holder's name Designation Mobile number Email address Website URL Area City State Pin code Image of the card

# Modify
The modify section of BizCardX allows users to interact with the data extracted from business cards. Through a user-friendly dropdown menu, users can select specific entries from the database. This selection enables them to either update or delete the chosen entry. Any modifications performed are promptly saved in the database.

# How to Run
Follow these steps to initiate and explore BizCardX:

1.Clone this repository or download the Python script. 2.Open your command line interface. 3.Navigate to the repository directory. 4.Execute the following command: streamlit run app.py 5.The application will promptly open in a new tab of your preferred web browser. 6.Within the application interface, you can seamlessly navigate, upload business card images, and effortlessly manage extracted data. Note: Before running the application, ensure that your SQLite3 server is operational and the database details within the script correspond accurately to your SQL setup.
