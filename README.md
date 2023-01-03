# pahse2_rover_project 🛰🏎

## Description 🧾

This project aims to process the incoming images from a rover moving on the surface of Mars and make a decisions based on the output information in this image.

At the end of phase 1 the rover must map at least 40% of the environment at 60% fidelity and locate at least one rock.

At the end of phase 2 the rover must map at least 95% of the environment at 85% fidelity. All while colliding with the least number of obstacles.

## Dependencies 📚

We used Python 3.10.4 for this project and Jupyter Notebook to process incoming images along with some other dependencies such as OpenCV, numpy, SciPy, matplotlib and others.

## Project Setup 🛠⚙

Download the rover simulator, clone this repo and run the command ```python drive_rover.py``` in the directory where ```drive_rover.py``` exists.
The file called ```drive_rover.py``` is what you will use to navigate the environment in autonomous mode. This script calls functions from within ```perception.py``` and ```decision.py```.

## Phase One Output

![MicrosoftTeams-image](https://user-images.githubusercontent.com/83096913/206876465-37bb0edb-1399-4ff8-9a6b-1b536cb9e0a1.png)
