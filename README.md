# Assignment: Read-a-File-into-Python

Hi there,

I hear you’re the new junior data scientist on the team. Welcome!

Our polling partners just finished collecting survey data on the happiness levels in each country. I’ve attached the file.

Can you load the data into Python and confirm the number of rows in the data and the range of the happiness scores? Then we can walk through next steps together.

Thanks!
Anna

Attachment: happiness_survey_data.csv


Solution: 

1. Read in data from a csv file

   import pandas as pd
   pd.read_csv('happiness_survey_data.csv')

2. Store data in a DataFrame

   df = pd.read_csv('happiness_survey_data.csv') # Save the output as a DataFrame
   df
   
3. Quickly explore the data in the DataFrame

   df.head(3)
   df.shape # number of rows = 2089
   df.count() 
   df.describe() # range of happiness scores = 2.2 - 8.0
   df.info()
   

   
