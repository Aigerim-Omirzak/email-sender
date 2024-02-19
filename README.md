# email-sender via Node.js
This is a simple Node.js application that enables users to send emails through a web-based contact form. It utilizes Express.js for routing, nodemailer for sending emails, and express-validator for server-side validation of form inputs.

# Features
Server-side form validation for name, email, subject, and message fields.
Sends emails using nodemailer.
Provides feedback to the user about the success or failure of sending an email.

# Prerequisites
Before running this application, ensure you have the following installed:

Node.js installed on your machine.
A Gmail account for sending emails.


# Configuration
Set up Gmail credentials:

Open app.js file.
Replace your EMAIL_USER and EMAIL_PASS with your Gmail username and password respectively in the transporter object.

# Usage
Start the application:

npm run start
Open your web browser and navigate to http://localhost:4000/send-email.

Fill out the contact form with your email, subject, and message.

Click on the "Send Message" button to send the email.

You will receive feedback indicating whether the email was sent successfully or if there were any validation errors.
