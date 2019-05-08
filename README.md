
# Arbotix Arm Quickstart

Navigate to the directory you want to use to hold all the files and run:
```
curl https://raw.githubusercontent.com/1386161/arbotix-arm-quickstart/master/arbotix-quickstart.sh | bash
```

**This script has only been tested on Ubuntu 16.04**

This script downloads and initialises an arbotix workspace in the current directory, installing everything needed to use the Arbotix PhantomX arm into a local directory.

- **Attempts to install if not found:**
  - ros-kinetic-desktop-full
  - ros-kinetic-arbotix

- **Downloads:**
  - Processing 2.2.1
  - Arduino 1.8.9

- **Initialises Workspaces:**
  - Arduino Workspace (+Intrabotix/Arbotix Repos)
  - Processing Workspace (+controlP5, +dynaManager)
  - Catkin Workspace (+PhantomX and +Turtlebot hardware descriptions by Intrabotix, +Arbotix-Ros by VanadiumLabs)
