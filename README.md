## Sheep_activity_Data
This repository contains two csv files: 1. raw_metamotion_grazing_active_inactive, 2.raw_raspberry_grazing_active_inactive

We used two differest devices. 
  1. MetamotionR+ (raw_metamotion_grazing_active_inactive.csv)
  2. Raspberry pi with sensehat (raw_raspberry_grazing_active_inactive.csv)

 Both devices collected only accelerometer measurements (x, y, z) from 9 sheep at 12.5 Hz while on the pasture. 
 The data is labeled with three classes: active, grazing, inactive. Therefore, there are in total 5 variables:
 1. nseq (timeseries in seconds sampled at 12.5Hz)
 2. x (the x-axis of accelerometer)
 3. y (the y-axis of accelerometer)
 4. z (the z-axis of accelerometer)
 5. activity (activities of the animals: active, grazing, inactive)


For any queries please email Natasa Kleanthous at n.k.orphanidou@2015.ljmu.ac.uk
