# Music Player #


## Project Aim & Overview ##
We need an application that will allow us to play or listen to digital audio files. Music player is the device to play digital audio files. The Music player GUI program application attempts to emulate the physical Music player. This program will allow you to play songs, music, and all audio files on your desktop or laptops.
The main objective of this project is to allow users to play digital audio files. To be engaging for users, the application has to have a simple but beautiful user interface.
You can have an interface for listing the available digital audio files. The users will also expect the Music Player to have an interface that shows information on the file that is playing. Some of the information you can include are the name of the file, its length, the amount played, and the amount not played in minutes and seconds.

### This project mainly contains three file ###


## View ##
All the front-end code is written here.This file contains the UI of our project and the execution begins from here. All the calls to other method will be made from here.

## Model ##
All the code that interacts with the database is written here. We have a database which stores favourites songs. So adding the song or deleting a song to it is done by this file.

## Player ##
This file work as a bridge between View.py and Model.py. So View.py calls the functions of Player.py and Player.py calls the functions of Model.py. This file will manage the actual playing / pausing / rewind of songs.



### This is a minor group project, created in group with (http://www.github.com/Anas74khan "Mohd Anas Khan") ###