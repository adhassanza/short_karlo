# short_karlo

## **Overview**   
The URL Shortener is a web application that allows you to shorten long URLs into easy-to-share, compact links. It's built using Node.js, Express.js, and MongoDB, making it a lightweight and efficient solution.

## **Features**
1. Shorten long URLs to concise links.
2. Track the number of clicks on each shortened URL.
3. View a list of all shortened URLs.   

## Follow these instructions to set up and run the URL Shortener on your local machine.

## **Before you begin, make sure you have the following prerequisites installed:**

**1. Node.js (with npm)** : https://nodejs.org/en   
**2. MongoDB** : https://www.mongodb.com/try/download/community

## **Installation**
1. Clone the repository to your local machine: git clone https://github.com/adhassanza/short_karlo.git
2. Navigate to the project directory: `cd short_karlo`
3. Install the project dependencies: `npm install`
4. Configure the MongoDB connection:  
Open the `server.js` file in a text editor.   
Locate the following line and update the MongoDB connection URL if needed:  
```javascript
mongoose.connect('mongodb://localhost:27017/urlShortener', {
    useNewUrlParser: true,
    useUnifiedTopology: true
});
```
Replace `'mongodb://localhost:27017/urlShortener'` with your MongoDB connection URL.  

5. Start the application: `node server.js`
6. Open your web browser and access the application at `http://localhost:5000`.

## **Usage**
Access the URL Shortener application in your web browser.

Enter a long URL in the provided input field.

Click the "Shrink" button to generate a shortened URL.

Copy and share the shortened URL as needed.

View a list of all shortened URLs and their click counts on the homepage.
