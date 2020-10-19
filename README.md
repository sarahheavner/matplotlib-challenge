# matplotlib-challenge

    Challenge is to analyze data between Capomulin and other skin cancer drug regimens to compare effectiveness.
    
    -Created two data frames from original csv files
        - Merged data into one DF
          - located a mouse ID that had duplicate timepoint values, g989. There were discrepancies between the tumor volumes at the same                   timpoints so all data relating to ID g989 was removed from merged DF
          - Created summary statistics table including mean, median, variance, standard deviation, SEM of Tumor Volume for each Regimen
          - Used Pandas to create bar chart that shows total number of mice on each regimen
          - Used Pyplot to create same bar chart as above
          - Used Pandas to create pie chart to show breakdown of mouse sex
          - Used Pyplot to create same pie chart as above
          - Quartiles, Outliers, Box Plots
              - Created new DF with only 4 drug regimens - Capomulin, Ramicane, Infubinol, and Ceftamin
              - Created new DF with volume of tumor for last Timepoint per mouse
                  -Merged DFs
              - Created new DF per drug regimen 
                  - Calculated IQR ranges and possible outliers
              - Created box plot for each regimen
         - Chose one mouse ID from Capomulin 
              - Created line chart that shows tumor volume over timepoints
         - Created scatter plot to show weight versus average tumor volume
         - Calculated correlation coefficient
         - Used scatter plot and calculated linear regression
            
           
               
               
                   
                   