# Fitness_Tracker
-A sample fitness generated dataset is used to generate the dashboards incorporating the latest updates in PowerBI

-4 major KPIs to track:

    1-Heart Rate
    
    2-No. of calories burnt
    
    3-No.of steps/step count
    
    4-No. of exercise sessions

-Aim: To determine the healthiest person among the customer base

-Requirement-All of the KPIs must be considered to determine the above details

-Solution-Generate a new KPI called the "Health Score" incorporating all the KPIs

-No.of dimensions generated:

     1-Measures-60 in total
   
     2-Calculated Tables-13 in total
   
     3-Dashboards-2-One main and the other detailed
   
   4-Tools used-PowerBI desktop-New KPI cards, bookmarks, sync slicers, AI generated images
   
   5-Inclusions in the dashboards:

   -Main Dashboard:

     1-4 KPI cards (in the new format) with the selected personnel score and the comparison score based on the alternate person selection

     2-Personnel/customer selection and the person to be compared with

     3-Customer/personnel AI image/picture

     4-Health Score of the selected Customer/personnel

     5-Line graph representing the health score variation with the option of selecting the timeline (Y/Q/M/D) 
    
    
-Supporting Dashboard:

     1-4 displays/visuals concerning the Health score, time-varation of the selected KPI (for the top N), All KPI comparison for all the 
     line items, one-to-many KPI comparison

     2-In the Health Score visual, a line graph is used to plot the health score of all the participants along with the KPI scores for 
     each data point

     3-In the KPI visual, the Top N participants are identified for the selected KPI slicer and an animated bar chart for the selected 
     time-period wise plot is displayed

     4-In the KPI comparison visual, all the KPIs are plotted for all of the participants to get a one-look understanding of the trends

     5-In the final visual (bottom RHS), a one-to-many comparison table is displayed for the participant selected from the slicer next to 
     the table. The table provides the delta change (in terms of %age) for the selected KPI.
