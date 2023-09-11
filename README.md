# Text Editor Web Application Module 19



## Acceptance Criteria

- **GIVEN** a text editor web application
- **WHEN** I open my application in my editor
- **THEN** I should see a client-server folder structure.

- **WHEN** I run `npm run start` from the root directory
- **THEN** the application should start up the backend and serve the client.

- **WHEN** I run the text editor application from my terminal
- **THEN** the JavaScript files have been bundled using webpack.

- **WHEN** I run my webpack plugins
- **THEN** I have a generated HTML file, service worker, and a manifest file.

- **WHEN** I use next-gen JavaScript in my application
- **THEN** the text editor still functions in the browser without errors.

- **WHEN** I open the text editor
- **THEN** IndexedDB has immediately created a database storage.

- **WHEN** I enter content and subsequently click off of the DOM window
- **THEN** the content in the text editor has been saved with IndexedDB.

- **WHEN** I reopen the text editor after closing it
- **THEN** the content in the text editor has been retrieved from our IndexedDB.

- **WHEN** I click on the Install button
- **THEN** I download my web application as an icon on my desktop.

- **WHEN** I load my web application
- **THEN** I should have a registered service worker using Workbox.

- **WHEN** I register a service worker
- **THEN** my static assets are pre-cached upon loading, along with subsequent pages and static assets.

- **WHEN** I deploy to Heroku
- **THEN** I have proper build scripts for a webpack application.

## Getting Started

1. Clone this repository: `git clone https://github.com/yourusername/text-editor-app.git`
2. Navigate to the project directory: `cd text-editor-app`
3. Install the dependencies: `npm install`

## Running the Application

1. Start the application: `npm run start`
2. Open your web browser and navigate to the provided URL.

## Building the Application

1. Bundle JavaScript files using webpack: `npm run build`
2. Generate HTML, service worker, and manifest files: `npm run webpack-plugins`

## Using Next-gen JavaScript

This application utilizes next-gen JavaScript features while ensuring compatibility with browsers.

## IndexedDB Storage

The application uses IndexedDB to provide immediate database storage for your content in the text editor.

## Install as Desktop App

Clicking on the Install button enables you to download the web application as an icon on your desktop.

## Service Worker and Caching

The application registers a service worker using Workbox, pre-caching static assets and enabling offline access.

## Deployment to Heroku

For deploying to Heroku, proper build scripts for a webpack application are set up.
