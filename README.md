# Movement-Direction-Detection-from-Spike-Trains-of-Neurons
This code determines the movement direction from spike trains of 36 neurons. 
Training data is provided in the two files: “Angle_Training.txt” and “Training_SpikeTrains.txt”. The first 
file shows the movement angles at each time sample while the second file shows the corresponding spike 
trains of 36 neurons. Rows in the second file correspond to neurons while columns correspond to either a 
spike (1) or no spike (0) at each time point. Direction is classified using  K-Nearest Neighbor (KNN) 
into one of four directions: 0° to 90°, 90° to 180°, 180° to 270° or 270° to 360°.
