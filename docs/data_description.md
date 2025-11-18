Dataset Description

The dataset used in this project contains environmental sensor readings collected from a laboratory environment. Each row is a timestamped observation containing the following features:
	•	Temperature sensors: S1_Temp, S2_Temp, S3_Temp, S4_Temp
	•	Light sensors: S1_Light, S2_Light, S3_Light, S4_Light
	•	Sound sensors: S1_Sound, S2_Sound, S3_Sound, S4_Sound
	•	CO₂ and CO₂ slope: S5_CO2 and S5_CO2_Slope
	•	Motion sensors: S6_PIR and S7_PIR
	•	Timestamp: Created from merged Date and Time columns
	•	Target variable: Room_Occupancy_Count, an integer representing the number of people in the room
The dataset contains thousands of observations with a mix of continuous and binary data types. The combination of environmental measurements and motion data makes it suitable for exploratory analysis, feature engineering, and predictive modeling using Python.


