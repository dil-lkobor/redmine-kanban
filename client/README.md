# Redmine kanban

## Configure

- in the `src/services/Api.js` change the `baseURL` value to the URL of your backend proxy *if you are running the backend proxy locally this should be: http://localhost:3000/api - if you set PORT=3000*

## Start the application

- to install dependencies run: `npm i`
- to start the application: `npm run serve`

## Build the application

- to build the application: `npm run build`
- to run the built version you will need serve, so download it: `npm install -g serve`
- and run: `serve -s dist`
