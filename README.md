# objection-tracking
Tracking multiple objects and storing a list of their locations, video output drawn on top

## System Requirements
* Only tested on Ubuntu 20.04

## Installing
* sudo apt-get install python3-opencv

## Running
In the general case, run:
* python3 tracker.py [filename] [model number]

Where model number is a number from 0-7 to specify which tracking algorithm to use. For example:
* python3 tracker.py fish.mp4 1

At the moment this only works with .mp4 files