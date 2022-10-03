# Surfs Up!

## Overview:  
To help W.Avy make the most informed decision, we are going to take a closer look at the statistics for temperature observations in the months of June and December over the years.  
With statistics in a tabular form and some graphs to visualize the temperature observations for the two months, W.Avy will be much more comfortable with his decision about the Surf and Ice Cream shop in Oahu!

## Analysis:

  1. Import the appropriate dependancies  
  
     ![dependencies](https://github.com/SoumyaAbraham/Surfs_Up/blob/main/Screenshots/dependencies.png)
     
  2. Since we are just looking for temperatures for June and December, we can use the _extract_ tool. 
  
      Here is what the code and results look like:
  
  June  
  
  ![June_Extraction](https://github.com/SoumyaAbraham/Surfs_Up/blob/main/Screenshots/june_extract.png)
  
  December
  
  ![December_Extraction](https://github.com/SoumyaAbraham/Surfs_Up/blob/main/Screenshots/dec_extract.png)
  
  
  3. This temperature information is very busy. Let us create a database for each one. We will also sort each by 'Date'.
  
      Let us take a look at what these DataFrames look like:
  
  June
  
  ![June](https://github.com/SoumyaAbraham/Surfs_Up/blob/main/Screenshots/junee_df.png)
  
  December
  
  ![December](https://github.com/SoumyaAbraham/Surfs_Up/blob/main/Screenshots/decem_df.png)
  
  4. We can check the frequency of observed temperatures for June and December, through the years by plotting it as a histogram. 
  
     It is important to first import the matplotlib dependencies.  
     Here is what the code and histogram look like:  
  
  June
  
  ![June_plot](https://github.com/SoumyaAbraham/Surfs_Up/blob/main/Screenshots/june_plot.png)
  
  December
  
  ![Dec_plot](https://github.com/SoumyaAbraham/Surfs_Up/blob/main/Screenshots/dec_plot.png)
  
  5. Lastly, we will print the statistics using .describe().
  
     This is what they look like:
  
  June
  
  ![June_describe](https://github.com/SoumyaAbraham/Surfs_Up/blob/main/Screenshots/june_describe.png)
  
  December
  
  ![December_describe](https://github.com/SoumyaAbraham/Surfs_Up/blob/main/Screenshots/dec_describe.png)
  
  
  ## Results:
  
  When we look at the histograms, there are some things we can infer: 
  
   * In June, we see temperatures varying between 66&deg;F and 81&deg;F.  
   * For the month of June, the highest frequency is seen at 77&deg;F although it is expected to see temperatures between 72&deg;F and 80&deg;F.  
   * In December, we see much less variations in the temperatures. We see the temperature of 72&deg;F almost twice as much as 67&deg;F or 76&deg;F, which are the second highest occuring temperature.   
   * The temperature has been constant over the years, for the month of December.  
    
 When we look at the statistics of the temperatures observed for the two months:
   * More temperature observations have been collected for June, over the years. 
   * The mean temperature is higher in June (74.9&deg;F) than in December (71&deg;F).
   * The range of temperatures vary from 75&deg;F to 85&deg;F in June. December has seen temperatures as low 56&deg;F.
    
  
  ## Summary:
  
Overall, June is consistently warm with temperatures in the high 70&deg;F. This is great weather for both a swim and ice cream!
    
December can see temperatures drop but it is not very common. Seeing that the highest frequency is at 72&deg;F and the histogram shows the frequency is almost double that of other temperatures observed, it is still great weather for a dip and some ice cream. 
    
  ---
 * The code for the analysis can be found here: [SurfsUp_Challenge](https://github.com/SoumyaAbraham/Surfs_Up/blob/main/SurfsUp_Challenge.ipynb)  
 * The data we used for the analysis can be found here [Hawaii](https://github.com/SoumyaAbraham/Surfs_Up/blob/main/hawaii.sqlite)
 
 
    
   
    
