# Railway Reservation System

## Introduction

This is the report of the “Train Ticket Reservation System” web application, in which front end (client side) is developed using React JS and back end (server side) is developed using Node JS and Express JS. This web application use MongoDB as the database, which is a cross-platform document-oriented database. 
 
In this web application users can provide the start and the destination locations, train, class, time, ticket quantity and the date of booking. Users can pay using credit/debit cards or by mobile phone, in which the amount is added to the mobile bill. If the user chooses card payment, the confirmed booking details will send to the email of the user by using “nodemailer” email service. If user chooses mobile payment the booking details will send to the entered mobile number using “Twilio” mobile service. 
 
In the web application booking page, when user select a start location (which contains all the stations of all routes), the destination locations are filtered according to the route of the selected station.  
 
If the user is a government employee, they can have special discounts in this web application. Once user gave their NIC when registering, that NIC is validated using government web service to ensure that user is eligible to have discounts. 
 
Following are sample text emails and text messages sent using previously mentioned services,
<p></p><br />

<img src="https://i.ibb.co/jWRZsx6/Capture1.png" alt="Capture1" border="0">
Figure_1: Email sent using “nodemailer” 
<p></p><br />

<img src="https://i.ibb.co/Qchs3hZ/Screenshot-20190513-100746.png" alt="Screenshot-20190513-100746" border="0">
Figure_2: Text message sent using “Twilio” 
<p></p><br />

## High Level Architectural Diagrams 
 
Front end of the web application is developed using React.js, backend is developed using Node.js and Express.js, MongoDB database is connected to the back end and the front end and the back end communicates with WSO2 EI, which is a comprehensive integration solution that enables communication among various, disparate applications. 
 
### Component Diagram 
<p></p><br />

<img src="https://i.ibb.co/ZL3rYsR/Capture27.png" alt="Capture27" border="0">
Figure_3: component diagram
<p></p><br />

### Overall System Architecture
<p></p><br />

<img src="https://i.ibb.co/GC5MpcN/Capture28.png" alt="Capture28" border="0">
Figure_4: overall system architecture
<p></p><br />