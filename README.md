# DisasterReliefProject
Project for STATS 6030

The purpose of this project is to identify a method for locating displaced persons during a national disaster from aerial imagery, such as in the 2010 earthquake in Haiti. To accomplish this, machine learning models were fit to training data from the HaitiPixels.csv file, which was collected from Haiti shortly following the earthquake. The data contains aerial imagery of Haiti which is separated into Red, Green, and Blue values and categorized by what those pixel groups were identified as (either Vegetation, Rooftop, Blue Tarp, Soil, or Various Non-Tarp). It was known that many of the displaced people were using blue tarps to create shelters, and so the goal of fitting each model is to use the image data in order to predict the locations of the blue tarps.

After training the models, holdout data was introduced, which contained additional aerial imagery in various .txt files, as well as several image files themselves. After appropriately cleaning and organizing the data in order to identify which columns mapped to Red, Green, and Blue values and labeling the data according to whether the pixel was classified as containing a blue tarp, each selected model was tested on the holdout data in order to confirm its validity for predicting the locations of the blue tarps.

The PDF in this repo is the final report, detailing conclusions as they would be presented to an advisory board.  

The RMarkdown file includes the code referenced in the PDF. 
