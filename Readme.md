## Run the code
1. Run `npm install @azure/communication-common --save` on the directory of the project to install dependencies
2. Run `npm install @azure/communication-calling@1.7.0-beta.1 --save` 
3. Run `npm install webpack@4.42.0 webpack-cli@3.3.11 webpack-dev-server@3.10.3 --save-dev`
4. Use the webpack-dev-server to build and run your app. Run the following command to bundle application host in on a local webserver:

        npx webpack-dev-server --entry ./client.js --output bundle.js --debug --devtool inline-source-map

Open your browser and navigate to http://localhost:8080/. 
