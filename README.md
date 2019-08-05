# DataGenerators
Two exploration python scripts in anaconda to generate basic retail transaction test data.  Both scripts have similar functionality but one outputs to a dataframe and the other outputs to a file.

<b>Functionality</b>

    Define:
    Start Date
    End Date
    Date Increment Range
  
From a defined master product and price list, random products are selected from list while randomly incrementing the date (within range) from the previously define start date.  Will continue generating entries until the generated date exceeds the previously defined end date
