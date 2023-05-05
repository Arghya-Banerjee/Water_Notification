![Logo](https://cdn-icons-png.flaticon.com/128/3105/3105807.png)

# Water_Notification

A water drinking notification every hour to keep you healthy while coding. 

💧💧 Stay Hydrated Stay Healthy 💧💧


## Authors

- [@Arghya-Banerjee](https://github.com/Arghya-Banerjee)


## About

A small task that is designed to keep you hydrated while you are on your computer. This program will run in background comsuming around 7 MB of ram and negligible amount of CPU usage.

## Must Read

Before running this program in background you must do one change in order for the icon to work properly. Go to the program and open it in any editor. Now change the path of the icon that is given in the program to the path where you pasted the icon (ideally in the folder with with main.py).


## Installation

To use this project write the following in Terminal

```bash
  pip install pyttsx3
  pip install plyer
```
## Running the Project

To run this project in background write the following in Terminal

```bash
  pythonw main.py
```
This will make the python project a background task which will work even after you close the terminal as well as the IDE. You can see and kill the task with the help of Task Manager where its will be listed as python.
## About the Code

This project uses the [time](https://docs.python.org/3/library/time.html) module in python to get the information about the current time and store information about when to again run the code after the timeout.

Also just a notification can sometimes just get bypassed by the user when he is using any application that has a higher priority than the notification for which I also added a speaking line using the [pyttsx3](https://pyttsx3.readthedocs.io/en/latest/engine.html) module. This will tell you when to drink water along with the desktop nootification.

The last thing to mention is the [plyer](https://plyer.readthedocs.io/en/latest/) module used in this project out of which I only imported the notification function. Its is used to display on desktop notification when its time to Drink Water.


## Contributing

Contributions are always welcome!

You may fork or donwload the project and make contributions.

Please adhere to this project's `code of conduct`.


## Feedback

If you have any feedback, please reach out to us at arghya.banerjee.dev@gmail.com


