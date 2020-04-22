**Deploy Flutter Web App in a SharedHosting using NodeJs**

Put your "flutter build web" command in the public-flutter folder 

Next upload your the node app to your hosting through File Manager

And then proceed with Node app setup on hosting
Once you are inside the control panel,
- Search for “Setup Node.js App” and select that.
- Click on “Create Application”
- “Application Root” should be your Repository Path from the previous step
- “Application URL” should already hold your domain name.
- “Application startup file” must basically point to the js file which creates the server.
If you have server creation in app.js, just enter app.js
- If you created your node server using the Express framework, then it should “./bin/www”
- Click on “Create”. This will start the node app and should reload the page, with a “Detected configuration file” section. This should detect your package.json (packaje.json should be in the root folder of your repo)
- Click on “Run NPM install”. This is basically installing all your npm packages listed in your package.json
- Click on “Restart” and Hurry! your flutter web app should be up and running.