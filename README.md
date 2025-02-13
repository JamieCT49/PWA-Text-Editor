# PWA-Text-Editor
### Live Render Link
https://pwa-text-editor-595.onrender.com/
### Repo link
https://github.com/JamieCT49/PWA-Text-Editor

## Description
Your task is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

![alt text](<Screenshot 2024-07-18 190547.png>)
## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application
```
## Usage
Open the [application](https://pwa-text-editor-595.onrender.com/). Simply type code/text in and it will save automatically. The code/text will be saved to the database which will allow you to revisit it whenever you like. Downloading the web app allows you to use the text editor offline while also saving the data.

## Installation
```
1. Clone repository.
2. Open terminal and run: npm install
3. Run: npm run start
4. Open webpage using port 3000
```

## Technologies Used
1. JavaScript
2. Express
3. Babel
4. idb
5. Webpack
6. Workbox
## Author
- Github: [JamieCT49](https://github.com/JamieCT49)