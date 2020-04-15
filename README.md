# pisign-instructions
This repository is full of instructions for downloading and installing the application. There may be more specific details for developers within the individual repositories.

# Installation and Usage

## Downloading
The most up-to-date releases for this application can be found in two repositories: [User Interface](https://github.com/pisign/pisign-frontend) and [Server](https://github.com/pisign/pisign-backend). To view the latest release for the User Interface, click on the releases tab then download the dist.tgz file under the "Pisign Frontend Release". The latest release for the server can be found in the releases tab and then you download the corresponding tar file for your operating system.

## Installing and Running the User Interface
After you have downloaded the frontend, you need to untar the file. Afterwards, open up the index.html in the `dist` directory on your computer. This will navigate you to your browser. Note: the widget information will not work if you are not running the server at the same time.

## Installing and Running the Server
AFter you have downloaded the backend, you need to untar the file. Afterwards, you will have to run the file. For linux machines, run "./pisign-backend run" in the terminal or for Windows machines run "pisign-backend.exe run" on the command prompt. Both of these commands will run the server. 

Note: upon installation of the server currently, you will have to add a folder inside the assets folder called "images". You will also have to add an empty file in the images folder called "images.json". Without this, the slideshow widget will not work.

## Development Guide
