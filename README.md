# Module-5-Challenge

To start with I imported my two csv files and then merged them together to create one total df combining the data sets together. 
I then found that there were 249 mice in the data set. There was a mouse that had duplicate rows though and I identified that mouse. The mouse was g989. I then found all the data regarding mouse g989 and removed the duplicates from the data set creating my clean_data dataframe. Once the dulipcate was removed I had 248 total mice. 

I then created a summary statistics table of mean, median, variance, standard deviation, and SEM for the tumor volume for each drug regimen. The table showing these summary statistics is below: 

  <img width="798" alt="Screenshot 2023-04-06 at 4 40 26 PM" src="https://user-images.githubusercontent.com/125215083/230499167-b11b1328-563c-4f31-9dbb-6a6f0d56cff2.png">

I then created the same summary statistics table using the aggregation method. That table showing the summary statistics is below:

  <img width="448" alt="Screenshot 2023-04-06 at 4 43 04 PM" src="https://user-images.githubusercontent.com/125215083/230499544-8d90f4b4-f053-4bff-9877-68b8f38fd9ed.png">

I then created a bar plot showing the total number of timepoints for all mice tested for each drug regimen using Pandas. The chart is below: 

  <img width="597" alt="Screenshot 2023-04-06 at 4 45 12 PM" src="https://user-images.githubusercontent.com/125215083/230499810-1cb3b953-4233-410b-b182-a616a0e6083f.png">

I then created the same bar plot using pyplot. The chart is below: 

  <img width="590" alt="Screenshot 2023-04-06 at 4 47 48 PM" src="https://user-images.githubusercontent.com/125215083/230500157-83637823-1ab4-4174-bab1-134a42b5daf7.png">

I then created a pie plot showing the distribution of female versus male mice using Pandas. The graph is below: 

  <img width="394" alt="Screenshot 2023-04-06 at 4 49 47 PM" src="https://user-images.githubusercontent.com/125215083/230500445-9b5262af-6ce5-46fd-b8bc-51d5b8c43cbc.png">

Then I created the same graph using pyplot. That graph is below as well: 

<img width="395" alt="Screenshot 2023-04-06 at 4 51 11 PM" src="https://user-images.githubusercontent.com/125215083/230500619-4aed19b9-974d-4c4d-9116-53245d7982ea.png">

I then used groupby to create the max_tumor which got me the last (greatest) timepoint for each mouse. I then merged that data with all the data I had to begin with. Then I found the lower quartile, upper quartile, interquartile range, lower bound, and upper bound for the drug regimen of Capomulin, Ramicane, Infubinol, and Ceftamin. The list of is below: 

  <img width="613" alt="Screenshot 2023-04-06 at 4 55 37 PM" src="https://user-images.githubusercontent.com/125215083/230501230-bf68a038-b412-4795-aff7-64a7025328a5.png">

I then created a box plot with all the drug regimens; Capomulin, Ramicane, Infubinol, and Ceftamin on it. The box plot showing all four drug regimens is below: 

  <img width="588" alt="Screenshot 2023-04-06 at 4 57 57 PM" src="https://user-images.githubusercontent.com/125215083/230501495-c49b1f8e-3ff3-4c12-b3a3-443f2d8d00a4.png">

I then took one mouse which was treated with Capomulin and generated a line plot of tumor volume vs. time point. I chose mouse r554 and plotted it. The graph showing the one mouse is below: 

  <img width="583" alt="Screenshot 2023-04-06 at 5 00 29 PM" src="https://user-images.githubusercontent.com/125215083/230501845-4cf94176-f981-449c-8fa5-cc882e09fd79.png">

I then generated a scatter plot of the average tumor volume vs. mouse weight for the Capomulin drug regimen. The scatter plot is below: 

  <img width="630" alt="Screenshot 2023-04-06 at 5 01 52 PM" src="https://user-images.githubusercontent.com/125215083/230502006-f49de066-8c33-4c4e-a5f3-560f7157982a.png">

The correlation coefficient between mouse weight and average tumor volume is 0.84. The r-squared is 0.709 when you round it. I then plotted the liner regression model for mouse weight and average tumor volume for the Capomulin drug regimen. The graph showing the liner regression model is below: 

  <img width="613" alt="Screenshot 2023-04-06 at 5 05 00 PM" src="https://user-images.githubusercontent.com/125215083/230502439-4412e39c-d9bb-4b01-a58f-88cef69b1c36.png">
