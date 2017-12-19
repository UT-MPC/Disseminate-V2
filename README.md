# Disseminate-V2
Getting Disseminate protocol to work on Raspberry-Pi system to test various theories, etc

The purpose of this research study has been to duplicate and improve the Disseminate protocol that had been developed on Android OS by first
replicating it on the Raspberry-Pi system, and then creating a wrapper/ API in Python so that the commands are easily callable. So far,
after much experimentation, research and reading, the things that have been accomplished are: 
  1) Gaining a solid fundamental understanding of socket-layer programming
  2) Interfacing with RFCOMM ports and the various nitpicky functions that allow bluetooth communications on Raspberry-Pi's
  3) Assembling a working directory of functions and writing functions to allow quick testing of bluetooth communications
  4) Assembling a network of raspberry-pi's which can effectively communicate with each other and transmit data
  
 What is left to accomplish at this point is automating the task of establishing bluetooth connections between raspberry-pi's and having a
 steady stream of data transfer occur. In order to do this, the following need to be accomplished:
  1) Utilize Python multiprocessing in order for raspberry-pi's to automatically communicate with each other on startup
  2) Add a script to root directory of Raspberry-pi to enable search and connection autonomously.
  
 What is provided in this project:
  1) A model for creating client and server connections.
  2) An in-progress file for multiprocessing sending/recieving data using Bluetooth
  
 The code for everything accomplished so far has been added to this repo, and if there are any questions or concerns, please make an issue
 request.
