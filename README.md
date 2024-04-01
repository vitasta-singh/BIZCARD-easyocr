PROBLEM:  
We need to develope a Streamlit application that allows users to upload an image of a business card and extract relevant information from it using
easyOCR.  
The extracted information should include the company name, card holder
name, designation, mobile number, email address, website URL, area, city, state,
and pin code.  
The application should allow users to save the extracted information into
a database along with the uploaded business card image. And Allow the user to Read the data, also Update the data and Allow the user to delete the data through the streamlit UI.  

PROCEDURE:  
Create a simple and intuitive user interface using Streamlit that guides users through the process of uploading the business card image and extracting its information. You can use widgets like file
uploader, buttons, and text boxes to make the interface more interactive.  
Now a function is created to handle the saving of the uploaded business card image and provide a preview of the image with detected text regions outlined by bounding boxes and labeled text.  
Reads the saved image using OpenCV's imread function.
reader.readtext Uses the reader (presumably an EasyOCR reader object) to extract text from the saved image. And finally displays the processed image with the extracted text highlighted.   
One can use widgets like tables, text boxes, and labels to present the information.  
Use a database management system like
SQLite or MySQL to store the extracted information along with the uploaded
business card image. You can use SQL queries to create tables, insert data,
and retrieve data from the database, Update the data and Allow the user to
delete the data through the streamlit UI.  
Now the modify option presents a user interface for altering or deleting data related to business cards stored in the database.
