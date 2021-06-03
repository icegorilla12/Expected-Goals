# Expected-Goals

I have used wyscout data to create a xG model. The expected goal values can be used to draw inferences about the performances of individual players as well as to analyze the performance of teams in matches. 


1. **Preprocess** -  contains a function to extract the information relevant for creating an expected goals model from the dataset.
2. **xG model** - comparing different classification algorithms to find the best fit.
3. **Goalscorers** - Using the predicted xG values to look for the best goalscorers of the 2017-2018 season in the top-5 leagues (open play goals).
4. **xG-Rolling**- Creating rolling xG charts for matches to better understand how the match panned out for different teams.
5. **Shotmaps**- Shot maps of different players as well as for a particular game played. 


## Dataset

The dataset used is taken from the paper, https://www.nature.com/articles/s41597-019-0247-7.  Further documentation for the same can be found here- https://apidocs.wyscout.com/#section/Versioning/Version-Switch
