# Car-Tracking
AI model to track car traffic using Bayesian Networks 



-> python drive.py -l lombard -i none

You can steer by either using the arrow keys or 'w', 'a', and 'd'.
The up key and 'w' accelerates your car forward, the left key and 'a' turns the steering wheel to the left, 
and the right key and 'd' turns the steering wheel to the right. Note that you cannot reverse the car or turn in place.
Quit by pressing 'q'. Your goal is to drive from the start to finish (the green box) without getting in an accident. 
How well can you do on the windy Lombard street without knowing the location of other cars? Don't worry if you're not very good;
An accident rate of 60% is pretty abysmal, 
which is why we're going to use AI to do this.

Flags for python drive.py:

-a: Enable autonomous driving (as opposed to manual).
-i <inference method>: Use none, exactInference, particleFilter to (approximately) compute the belief distributions over the locations of the other cars.
-l <map>: Use this map (e.g. small or lombard). Defaults to small.
-d: Debug by showing all the cars on the map.
-p: All other cars remain parked (so that they don't move).

to run particle filtering :
-> python drive.py -a -i particleFilter -l lombard
