# Customer Web Chat Support App

Welcome to the Customer Web Chat Support App repository! This MERN stack application includes a support dashboard and a client widget with an interactive UI/UX, making it a perfect solution for real-time customer support through web chat. This README will guide you through the process of building and running the application.

**Add-on feature:** Interactive UI


For Support Agent
![image](https://github.com/manuj-ss/Customer-Chat-App/assets/96734632/6b5155fd-e737-4546-8d3f-992be87f69d5)



For User



![image](https://github.com/manuj-ss/Customer-Chat-App/assets/96734632/3150ed2b-0b5b-46e2-80df-d0d491560b18)




## Building and Running

To get started with the Customer Web Chat Support App, follow these steps:

1. **Clone the GitHub repository** to your local machine using the following command:

   ```bash
   git clone https://github.com/manuj-ss/Customer-Chat-App/tree/main/web-chat-app
2. **Navigate into the repository directory:**
cd support-agent-dashboard

Inside the repository, you'll find two separate React applications: the Support Agent Dashboard and the Support Client Widget. You'll need to configure and run both to try the demo. Choose the app you want to run by navigating into its directory. For the Support Agent Dashboard, use:
cd support-agent-dashboard

For the Support Client Widget, use:
cd support-client-widget

3. **Open the src/config/pubnub-keys.json file in your chosen app's directory.** Replace YOUR_PUBLISH_KEY_HERE and YOUR_SUBSCRIBE_KEY_HERE with your PubNub keyset from your PubNub Dashboard. It's important to use the same keyset for both the client and dashboard apps.

4. **Install the necessary Node modules by running:**
npm install

5. **Now, you can run the project in your local environment with:**
npm start

This will start the development server and open the application in your default web browser. You can access the app at http://localhost:3000.

**Setting Up the MongoDB Database:**
This application uses MongoDB as the database for storing chat history and other relevant data. To set up the database:

Make sure you have MongoDB installed on your system. You can download it from the official MongoDB website: https://www.mongodb.com/try/download/community

Start the MongoDB server. You can do this by running the mongod command in your terminal.

Create a new MongoDB database for the chat app, or use an existing one. You can create a new database using the MongoDB shell or a graphical interface like MongoDB Compass.

Once you have your database set up, you'll need to configure the connection to MongoDB in your app's server code. Look for a configuration file, typically something like server/config/config.js, and update the MongoDB connection URL to point to your database.

After making the necessary changes, restart your app's server.

Your Customer Web Chat Support App is now ready to run, and the data will be stored in your MongoDB database.
