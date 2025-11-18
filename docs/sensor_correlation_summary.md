Sensor Correlation Summary

To understand which environmental sensors are most strongly associated with room occupancy, I computed the correlation between each feature and the target variable, Room_Occupancy_Count. The results show clear patterns in how different sensor types respond when more people enter the room.
The strongest predictors of occupancy are the light sensors, especially S1_Light (0.85), S3_Light (0.79), and S2_Light (0.79). This suggests that lighting conditions change noticeably when the room becomes occupied, likely due to increased movement, changes in reflection, or lights being turned on.
Temperature sensors also have moderate to strong correlations with occupancy, ranging from 0.52 to 0.70 across the four sensors. This is expected, as human presence tends to raise room temperature gradually.
Both PIR motion sensors show strong correlations as well (S7_PIR = 0.70, S6_PIR = 0.63). Even though these sensors only record binary values, they capture movement patterns that closely follow occupancy changes.
The CO₂ sensor and CO₂ slope also correlate highly with occupancy (0.66 and 0.60). CO₂ builds up over time when people are in the room, making this a reliable environmental indicator of human presence.
Lastly, the sound sensors show moderate correlations (0.46–0.57). More occupants generally create more noise, which these sensors capture.
Overall, the strongest signals come from light, temperature, PIR motion, and CO₂, all of which move consistently with occupancy levels. These findings will help guide feature selection and model building in the next phase of the project.
