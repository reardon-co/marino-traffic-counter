# Northeastern University Gym Traffic Tracker

This project's purpose is to create an easy way for Northeastern students to see how many people are using equipment at Northeastern's gyms. Often, the gyms get extremely crowded during certain hours, which makes it extremely difficult to workout. By easily seeing the traffic before deciding to go to the gym, this widget will hopefully help students alleviate this issue by avoiding peak hours or using less crowded sections of the gym.

# How to use

I developed the widget by writing a script in the app Scriptable. You can download Scriptable for free from the App Store. After it is installed, you need to import the scripts and set up the widget.
1. Import the necessary scripts into Scriptable by creating new script files and copy/pasting the code into each one
2. Install the widget by adding a Scriptable widget to your homescreen or lockscreen and setting it to the appropriate installed script.
3. Enjoy

# The Scripts
There are two types of scripts included: dependencies and widgets. For every widget, the GymAvail script is a requirement. For the dial-style widgets, the ProgressCircle script is a requirement.

### GymAvail
The GymAvail script scrapes the Northeastern gym webpage for data on traffic. It then converts this data into an easy-to-read JSON format. This is used in conjunction with the widget scripts to populate real-time data.

### ProgressCircle
The ProgressCircle script is the base circular shape that is used in most of the widgets I created.

### Gym Capacity Dials
![IMG_7921](https://github.com/reardon-co/marino-traffic-counter/assets/61595397/b931aee4-1d7d-4d3a-a47d-cc482a995c49)
This widget tracks gym traffic in different areas in a compact way, as it can fit in a small widget. Each dial represents a different area of the gym. Top-left is Squashbusters traffic, top-right is Marino 3rd floor traffic, bottom-left is Marino treadmill traffic, and bottom-right is 2nd floor weight traffic. The amount of the dial filled in white represents the percentage of in-use machines in that area. 

### Gym Traffic Bars
![IMG_7922](https://github.com/reardon-co/marino-traffic-counter/assets/61595397/cb9a8b4e-a8e0-4bd0-ba0b-1520f683b766)
This widget shows more detailed information than Gym Capacity Dials, but also requires a large widget. The widget shows a percentage which represents the amount of in-use machines in that area. At the bottom of the widget, it also shows the date and time that the traffic data was fetched.
