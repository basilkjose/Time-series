# Stacked lstm time series forecasting

Industrial motors are typically monitored by a multitude of sensors. In this problem we are given a dataset containing the vibration sensor measurements from 3 bearings of a large industrial motor(sensor1,sensor2,sensor3). The data looks as follows


| Attempt | #1  | #2  |
| :-----: | :-: | :-: |
| Seconds | 301 | 283 |

our task is to predict the readings from three sensors for the next 500 time points assuming that there is no major change in the functioning of the motor.
