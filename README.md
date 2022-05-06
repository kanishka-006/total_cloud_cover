# total_cloud_cover
#We used only the data provided along with this project one csv file provided for train data, and 300 csv files provided for test data.
Link for dataset: https://he-public-data.s3.ap-southeast-1.amazonaws.com/shell_dataset.zip
Missing data handling - 
All those rows where Total Cloud Coverage (%) column had -1 value were removed from the train dataset.
All those rows where Total Cloud Coverage (%) column had -7999 value were accommodated for by taking average of the surrounding values.
‘Precipitation (accumulated) [mm]’ and ‘moisture’ columns were removed as their data was irrelevant.
