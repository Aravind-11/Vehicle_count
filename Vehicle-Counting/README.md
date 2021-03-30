# Video-based Vehicle Counting System

## Setup
- Install Python 3 on your machine. 
- Clone this repo 
- Run `pip install -r requirements.txt` to install dependencies.
- Run main.ipynb file(alternate implementations in *0_Vehicle_Counting.py* and *1_Vehicle_Counting.py*).

## Working
The vehicle counting system is made up of 3 components: a detector, tracker and counter. The detector identifies vehicles in a given frame of video and returns a list of bounding boxes around the vehicles. The tracker uses the bounding boxes to obtain regions of interest and uses them to track the vehicles in subsequent frames. The detector is also used to update tracker objects periodically to ensure that they are still tracking the vehicles correctly. The counter draws a counting lines across the road. When a vehicle crosses the line, the vehicle count is incremented.

