# Jetson direct to simulator

Based on https://github.com/robin-gdwl/UR_Facetracking

Intended to be run on an NVIDIA Jetson, plugged directly into a computer running UR_Sim.

## Setup

### Install dependencies
On the Jetson, create a virtual environment, navigate to this repo, and run `pip3 install -r requirements.txt`

### Networking
Open the UR_Sim vm, and open a terminal by going down to the lower left corner, hitting the start button, and going System Tools > UXTerm. In the terminal, run `ip a`. On the
jetson, in `Face_tracking01`, change the `ROBOT_IP` variable to that address.

You'll need to do something on the computer that the sim is running on, but idk what yet.

## Jetson Credentials
user: jetson
password: jetson1
root password: jetson1
