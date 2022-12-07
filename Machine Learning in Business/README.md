# Project description
You work for the OilyGiant mining company. Your task is to find the best place for a new well.
Steps to choose the location:
- Collect the oil well parameters in the selected region: oil quality and volume of reserves;
- Build a model for predicting the volume of reserves in the new wells;
- Pick the oil wells with the highest estimated values;
- Pick the region with the highest total profit for the selected oil wells.
- You have data on oil samples from three regions. Parameters of each oil well in the region are already known. 
- Build a model that will help to pick the region with the highest profit margin. 
- Analyze potential profit and risks using the Bootstrapping technique.

# Data description
Geological exploration data for the three regions are stored in files:
- 'id' — unique oil well identifier
- 'f0', 'f1', 'f2' — three features of points (their specific meaning is unimportant, but the features themselves are significant)
- 'product' — volume of reserves in the oil well (thousand barrels).
