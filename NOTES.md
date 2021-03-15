1:
npm init -y
npm install @azure/msal-browser - enables client-side applications to authenticate users through Azure AD B2C service. Token eaccess is available
npm install express
npm install morgan - http request logger middleware for node.js
npm install yargs - Helps build interactive command line tools, by parsing arguments and generating an elegant user interface

2: Crete file named server.js - Smalle webserver to serve SPA.

CREATING the SPA UI
3: create file index.html in app folder : file implements a UI built with the boostrap 4 framework and imports script files for configuration, authentication, and api calls

4: create file ui.js, this will access and update DOM elements

5: Rgister the app: https://docs.microsoft.com/en-us/azure/active-directory/develop/scenario-spa-app-registration

Configure your javascript SPA
6: Create a file authConfig.js in the app folder to contain your configuration parameters for authentiction
    - modify the values in the msalConfig in this file