Key Features:
Upload Files: Allows users to upload images and PDF files via POST requests. Files are stored in the MySQL database using a @Lob byte array.
Download Files: Enables users to download stored files by simply entering the URL with the file ID. The files are served directly from the database as downloadable content.
Database Integration: Utilizes JPA for seamless integration with MySQL, handling the storage and retrieval of file data.
API Access: The application is designed to be interacted with via Postman, making it easy to test and extend.
Technologies Used:
Spring Boot
Spring Data JPA
MySQL
Postman
This project is ideal for learning how to handle file uploads and downloads in a Spring Boot application with MySQL as the underlying storage.

Using this project open postman add post request and then use the url localhost:8080/upload  , using form data and add files.
then the postman gives you a url to download your files whatever you saved via postman to your database....
