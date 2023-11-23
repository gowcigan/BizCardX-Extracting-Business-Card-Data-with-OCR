## BizCardX: Extracting Business Card Data with OCR
This Streamlit application aims to extract relevant information from uploaded business card images. It utilizes the EasyOCR library to recognize text elements such as the company name, card holder name, designation, contact details, and address components from the uploaded image.
## FEATURES
## IMAGE UPLOAD: 
Users can upload an image of a business card in common formats (e.g., JPEG, PNG).
## TEXT EXTRACTION: 
The application uses EasyOCR to extract essential information such as company name, card holder name, designation, contact numbers, email address, website URL, and address details (area, city, state, pin code).
## GUI DISPLAY: 
Extracted information is displayed in an easy-to-read graphical user interface within the Streamlit app.
## APPROACH
## INSTALL THE REQUIRED PACKAGES: 
You will need to install Python, Streamlit, easyOCR, and a database management system like SQLite or MySQL.
## DESIGN THE USER INTERFACE: 
Create a simple and intuitive user interface using Streamlit that guides users through the process of uploading the business
card image and extracting its information. You can use widgets like file uploader, buttons, and text boxes to make the interface more interactive.
## IMPLEMENT THE IMAGE PROCESSING AND OCR: 
Use easyOCR to extract the relevant information from the uploaded business card image. You can use
image processing techniques like resizing, cropping, and thresholding to enhance the image quality before passing it to the OCR engine.
## DISPLAY THE EXTRACTED INFORMATION: 
Once the information has been extracted, display it in a clean and organized manner in the Streamlit GUI. You can use
widgets like tables, text boxes, and labels to present the information.
## IMPLEMENT THE DATABASE INTEGRATION: 
Use a database management system like SQLite or MySQL to store the extracted information along with the uploaded
business card image. You can use SQL queries to create tables, insert data, and retrieve data from the database, Update the data and Allow the user to
delete the data through the streamlit UI.
## TEST THE APPLICATION: 
Test the application thoroughly to ensure that it works as
expected. You can run the application on your local machine by running the
command streamlit run app.py in the terminal, where app.py is the name of
your Streamlit application file.
## IMPROVE THE APPLICATION:
Continuously improve the application by adding new
features, optimizing the code, and fixing bugs. You can also add user
authentication and authorization to make the application more secure.
## RESULT
The project delivers a Streamlit app enabling users to upload a business card image for EasyOCR-based data extraction. It captures company details, cardholder info, contact specifics, and address components. Extracted data is displayed intuitively in the GUI. Users can store multiple entries, associating card images with extracted details in a database. This project blends image processing, OCR, GUI development, and database management, emphasizing scalable architecture and code organization. With clear documentation, it offers a user-friendly interface for swift business card data management, benefiting both individuals and businesses.
