# Machine Failure Prediction Dataset
## Overview
The Machine Failure Prediction dataset provides metrics from industrial machines to predict potential failures. 
It's an invaluable dataset for predictive maintenance, reducing downtime and extending machinery life through timely interventions. 
This dataset is perfect for binary classification tasks in supervised learning.

## Dataset Description
The dataset comprises various operational parameters from machines, each potentially indicating impending failure. Here's a description of each column:

1. footfall: Number of operational hours or cycles since the last reset or maintenance.
2. tempMode: Categorical representation of the temperature mode observed.
3. AQ: Air quality index within the operational environment.
4. USS: Ultrasonic sensor status (scale of 1-10).
5. CS: Current status of the machine (scale of 1-10).
6. VOC: Volatile organic compounds level around the machine (scale of 1-10).
7. RP: Rotational pressure indicated by sensors.
8. IP: Internal pressure indicated by sensors.
9. Temperature: Temperature reading from the machine's core sensor.
10. fail: Machine failure status (0: No, 1: Yes).

# Learning Outcomes
From this dataset, we know this dataset is supervised learning, Target = fail, Target column is categorical column
