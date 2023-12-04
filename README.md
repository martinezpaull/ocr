# Development of a Mobile Application for Individualized Expense Tracking

## A mobile application for Individualized Expense Tracking to help people track their expenses

This project is a mobile application that aims to track and manage expenses that utilize optical character recognition (OCR) that can extract financial information from a receipt for better tracking experiences.

* Develop an application that scans a receipt and extracts the text into JSON format.
* Calculates the total expenses from the JSON file of costs recorded.
* Displays a dashboard containing analytics on user expenses based on weekly and monthly aggregation.
* Test and evaluate the application’s accuracy.

### Link for our Mockup Design Application
 https://www.figma.com/file/XEARoCciW9bdoeLo4nw3DV/Expense-Tracker?type=design&node-id=0-1&mode=design

## Front End
For our front end, we use React Native since it's used as the main framework for the front end. React native allows cross-platform compatibility, which can be advantageous in reducing the time and cost of development. Consequently, react native renders components with native APIs, thus resulting in performance close to native applications.

## Back End
For our backend, we use Firebase and Google Vision API for our mobile application since it provides several key functionalities that are helpful for the app to be fully functional. These include real-time database, easy integration, authentication, analytics, and scalability. Firebase provides a real-time NoSQL database, allowing for real-time data synchronization across multiple clients and devices. 

Google Vision API was used to make scanning receipts functional using the phone's camera. By utilizing this API, the application will extract details and information from receipts captured through the camera. The API's feature can detect texts within an image and predict what type of data is being extracted. With this tool, users will simply take a photo of their receipts and the API will take charge of optimizing the image for data extraction.
