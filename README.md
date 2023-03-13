# Mouselogger
## Short description
Simple kernel-mode WDF driver based on [moufiltr](https://github.com/microsoft/Windows-driver-samples/tree/main/input/moufiltr) by Microsoft
## Author
Paweł Langowski
## Installation
See [moufiltr's](https://github.com/microsoft/Windows-driver-samples/tree/main/input/moufiltr) page or [kbfiltr's](https://github.com/microsoft/Windows-driver-samples/tree/main/input/kbfiltr) page for more details.
## Full description
This is a driver that intercepts the user's mouse coordinates on click and utilizes system worker threads to save those coordinates to a file. The file is located at `C:/example.txt`. This driver was developed for educational purposes only.
