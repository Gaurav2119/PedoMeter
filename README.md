# PedoMeter
An Arduino mega-based project for counting total number of steps taken by a person using three components of motion i.e., forward, vertical, and side footsteps with help of the axis and threshold value.
The project uses an accelerometer to get values.
The threshold level is used to decide whether a step is taken or not and is calulated using the average value of 3-axis (Max + Min)/2, is called dynamic threshold.
