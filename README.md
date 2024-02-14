# Territory_correction


## TerIDCorrection
Codes to solve the issue regarding multiple IDs from the territory detection algorithm
The code takes in the CSV output from the territory detection algorithm. 
It then detects the IDs that have been mislabelled and creates a single ID for each territory throughout the video.

## MovementDetection
Input here is the CSV from the correction algorithm
It detects if there has been any sudden movement in the video by comparing the distance between the same ID of the consequent frames.
