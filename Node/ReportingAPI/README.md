## SocketLabs On-Demand Reporting API Example in Node.js

This is a very basic [Node](https://nodejs.org/) application to call the [SocketLabs Reporting API](http://www.socketlabs.com/api-reference/reporting-api/).  We call the API using the [Request](https://github.com/request/request) node package.

To get started, you must first obtain your API Key in the [SocketLabs On-Demand Control Panel](https://cp.socketlabs.com/security#/).  Once you have your API Key, open up the Node application's app.js file and insert your SocketLabs username, Reporting API key, and ServerID number (we have included the placeholder text where you will insert these values).

Once you have updated the app.js file to include your personal values, you are all set.  You can start the application by running the command `node app.js` console or terminal (please be sure that you are in the directory that contains the app.js file for this application).  If this is your first time running the application, you'll also need to install the dependencies first.  This is done by typing the `npm install` command while in the same directory as the `package.json` file.

### Other notes:
* This demo application will simply query the API, and log all of the data from that query to the console.  In a "real world" use case, you'd want to write these responses to a database such as [MongoDB](https://www.mongodb.org/), or write some other sort of logic for handling and processing the responses.
