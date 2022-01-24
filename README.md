# Jetson direct to simulator

Based on https://github.com/robin-gdwl/UR_Facetracking

Intended to be run on an NVIDIA Jetson, plugged directly into a computer running UR_Sim.

## Setup

### Install dependencies

On the Jetson, create a virtual environment, navigate to this repo, and run `pip3 install -r requirements.txt`

### Networking
Open the UR_Sim vm, and open a terminal by going down to the lower left corner, hitting the start button, and going System Tools > UXTerm. In the terminal, run `ip a`. On the
jetson, in `Face_tracking01`, change the `ROBOT_IP` variable to that address.

#### Current network:

Laptop: 10.30.21.10

Jetson: 10.30.21.20

Mask: 255.255.255.0

No Gatweay

On Jetson: `sudo ifconfig eth0 10.30.21.20 netmask 255.255.255.0`

## Jetson Credentials
user: jetson

password: jetson1

root password: jetson1
