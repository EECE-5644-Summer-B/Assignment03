# Cleaning Log

# Dropped
'model' -- Dropped due noise it would add
'color', 'location' -- Were both removed to test if they would improve the final model which the removal did
# Modified
To make the data frame usful for the model changes were made to data and columns to make more useful to the model:
'Year' -- Changed to age
'Owner' -- Changed to number of owners
'Transmision' -- Changed to a bulion of if the car was manual or not.
'Fuel Type','Drivetrain','Seller Type','Color','Make','Location' -- All OneHotEcoded for the model to understand
'Kilometer', 'Engine', 'Max Power', 'Max Torque','Length', 'Width', 'Height', 'Seating Capacity', 'Fuel Tank Capacity', 'Age', 'Owners' -- All scaled for better results from training
