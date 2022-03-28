# Todo App using JSON-Server & useEffect

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### For JSON-Server

The json file is stored in file structure as /db.json
To initialize the json-server, open the terminal and start the server using command
### json-server db.json --watch --port 3004

--watch will allow you to see the updates in json in realtime and you won't be required to load the server every time on each update.
--port option allows you to set the server port for json-server. For this react-app, json-server has been coded up for Port 3004 which gets initialized at [http://localhost:3004](http://localhost:3004)
