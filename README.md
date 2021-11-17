# Car-Tracking
AI model to track car traffic using Bayesian Networks 



-> python drive.py -a -i  particleFilter -l lombard -d

Flags for python drive.py:

-a: Enable autonomous driving (as opposed to manual).
-i <inference method>: Use none, exactInference, particleFilter to (approximately) compute the belief distributions over the locations of the other cars.
-l <map>: Use this map (e.g. small or lombard). Defaults to small.
-d: Debug by showing all the cars on the map.
-p: All other cars remain parked (so that they don't move).

to run particle filtering :
-> python drive.py -a -i particleFilter -l lombard
