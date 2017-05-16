# Kaggle Sea Lion Competition Coordinate and Counts Data
Correct coordinates available for download **[here](https://github.com/LivingProgram/kaggle-sea-lion-data/blob/master/correct_coordinates.csv)**, and correct counts available for download **[here](https://github.com/LivingProgram/kaggle-sea-lion-data/blob/master/correct_train.csv)**. If you are curious about how these are generated I have an IPython Notebook that explains everything and can be run to generate the same results **[here](https://github.com/LivingProgram/kaggle-sea-lion-data/blob/master/Correct%20Coordinates%20%26%20Sea%20Lion%20Counts.ipynb)**. 

## Brief Summary of Method:
 - Use **[Radu's Method](https://www.kaggle.com/radustoicescu/get-coordinates-using-blob-detection)** to extract preliminary coordinates
 - Generate a count for each image based on number of preliminary coordinates for each class
 - Compare that count to the **train.csv** counts
 - Draw coordinates for all the images that have count discrepancies
 - Manually look over the images with discrepancies (over 252 total)
 - Add any missing coordinates, remove any misplaced coordinates
 - Generate correct count based on final number of coordinates
 
 **Questions can be addressed [here](https://www.kaggle.com/c/noaa-fisheries-steller-sea-lion-population-count/discussion/32857)**
