# pisign-instructions
This repository is full of instructions for downloading and installing the application. There may be more specific details for developers within the individual repositories.

# Installation and Usage

## Downloading
The most up-to-date releases for this application can be found in two repositories: [User Interface](https://github.com/pisign/pisign-frontend) and [Server](https://github.com/pisign/pisign-backend). To view the latest release for the User Interface, click on the releases tab then download the dist.tgz file under the "Pisign Frontend Release". The latest release for the server can be found in the releases tab and then you download the corresponding tar file for your operating system.

## Installing and Running the User Interface
After you have downloaded the frontend, you need to untar the file. Afterwards, open up the index.html in the `dist` directory on your computer. This will navigate you to your browser. Note: the widget information will not work if you are not running the server at the same time.

## Installing and Running the Server
After you have downloaded the backend, you need to untar the file. Afterwards, you will have to run the file. For linux machines, run "./pisign-backend run" in the terminal or for Windows machines run "pisign-backend.exe run" on the command prompt. Both of these commands will run the server. 

Note: upon installation of the server currently, you will have to add a folder inside the assets folder called "images". You will also have to add an empty file in the images folder called "images.json". Without this, the slideshow widget will not work.

## Using the Application
When you open the User Interface in your browser, you should be able to add, remove, and edit new widgets. To add a new widget, hit the "plus" button. You can delete the widget by clicking the x button on the specific widget. You can edit the widget by clicking the "gear" button on each widget. In the pop-up box, you can change the type of the widget and change the settings.

### API Keys
Twitter and the weather widgets both require an API key. For the weather application, navigate to the [following website](openweathermap.org) and create an account. Then navigate to the [API page](https://home.openweathermap.org/api_keys) which should have your api key. Copy and paste this key for each of your weather widgets.

For the Twitter widget, navigate to the [following website](https://developer.twitter.com/en) and create an account. Afterwards, navigate to your account and create a new "application", afterwards you should receive a set of access tokens and API keys. Use these values for each of your twitter widgets.

### Managing the Slideshow Application
You can upload new photos for your slideshow application by clicking on the photo button in the bottom left hand part of the screen. You can select multiple photos and then assignment tags to all of them. If you want to put multiple tags for these images, you can type in the different tags in a comma separated manner such as "beach,city,school". Then you can use these tags to select which images you want to view for each of your slideshow applications by going to each respective slideshow widget settings.

### Edit and Presentation Mode
For the most part, you don't want to see all these buttons everywhere when you use this as a signage application. You can change the presentation mode by clicking on the "pencil" button, which toggles edit mode. This will toggle all the editing, deleting, and adding buttons for the widgets and remove borders. If you want to edit, simply toggle the button.

# Feedback
We want your feedback on the application! Are there bugs? Are there cool features you would like to see? Let us know! You can report these by adding a "New Issue" for a repository. If you can, try to put the issue in the correct repository (either the frontend or the backend repository). We will see what we can do, or if you feel up to it, you can try to open up a PR for the fix/enhancement!

# Development Guide

## The Basics
We have two separate repositories: one for the backend and another for the frontend. The frontend uses Vue and the backend uses Go. The repository for the backend is found [here](https://github.com/pisign/pisign-backend) and the repository for the frontend is found [here](https://github.com/pisign/pisign-frontend).

## Issue Boards
Look towards the issue boards to see reported bugs or enhancements to the application. Try to close these or link development branches to the respective issues. 

## Developing
You are free to help with any issues or enhancements you want! Just create a separate branch and create a PR and we will look through, comment, and add it. After a PR is created, the releases is automatically updated, so you can use that updated version afterwards! In the PR, try to be as detailed as possible for what you are adding or changing so that it is easier and faster for us to review it.

