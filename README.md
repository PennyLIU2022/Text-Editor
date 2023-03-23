# Text Editor

## Description
This application is a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

## Table of Contents
  * [User Story](#user-story)
  * [Installation](#installation)
  * [Heroku Link](#heroku-link)
  * [Application Screenshot](#application-screenshot)
  * [Questions](#questions)  

## User Story
```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Installation
- Install required node pacakges by running:
    ```bash
    npm run install
    ```
- To run the code below, you will find the application start up the backend and serve the client.
    ```
    npm run start
    ```
- When you enter the code below, you will find that the JavaScript files have been bundled using webpack, and a HTML file, service worker, and a manifest file are generated.
    ```
    npm run build
    ```

## Heroku Link
This application is deployed to [Heroku](https://a-good-text-editor.herokuapp.com/)

## Application Screenshot
WHEN I open my application in my editor, THEN I should see a client server folder structure.
![Application Screenshot](public/images/Homepage.png)

When you click the post title, it will bring you to the single post page, it shows the post information and comments. You can make a comment while logged in.
![Application Screenshot 2](public/images/SingleBlog.png)

After you log in or sign up, it will bring you to the dashboard page directly.
![Application Screenshot 3](public/images/login.png)

You can also click navigation link of "dashboard", it will bring you to the page. It shows all your posts, you can click "+ New Post" to add a new post. 
![Application Screenshot 4](public/images/Dashboard.png)


## Questions
If you have any questions, you can find [my Github](https://github.com/PennyLIU2022) and reach me by email at: pennyliu806@gmail.com