﻿## Url_Shortener
 URL Shortener is a simple web application that allows users to shorten URLs and view their shortened URLs history.
## Features
 Shorten a long URL to a unique short URL.
View history of shortened URLs associated with a specific user ID.
## Installation
1.Clone this repository to your local machine:
git clone 

2.Install the required dependencies:
npm install

## Set up the database:
Ensure you have a MySQL database set up.
Update the database connection details in models/dbconnection.js file.
## Start the server:
node app.js


Sure, here's a sample README file for your URL shortener application:

URL Shortener
URL Shortener is a simple web application that allows users to shorten URLs and view their shortened URLs history.

Features
Shorten a long URL to a unique short URL.
View history of shortened URLs associated with a specific user ID.
Installation
Clone this repository to your local machine:
bash
Copy code
git clone <repository_url>
Install the required dependencies:
bash
Copy code
npm install
Set up the database:
Ensure you have a MySQL database set up.
Update the database connection details in models/dbconnection.js file.
Start the server:
bash
Copy code
node app.js
Access the application in your web browser at http://localhost:2000.
## Usage
=>Shorten a URL
Enter a long URL in the input field labeled "Your URL".
Enter your user ID in the input field labeled "Your ID".
Click on the "View the short URL" button.
A shortened URL will be generated and displayed below the input fields.

## View URLs History
1.Enter your user ID in the input field labeled "YOUR ID".
2.Click on the "View Your URLs" button.
3.Your previously shortened URLs will be displayed as clickable links, showing both the short and full URLs.

## Technologies Used
.Node.js
.Express.js
.MySQL
.Bootstrap
.jQuery
.Short-id (for generating short unique identifiers)

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.




 
