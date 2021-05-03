# Kobe Bryant Shot Predictions
Building a classifier to predict Kobe Bryant making a shot when given test data

I wanted to start off strong and created a scatterplot that would visualize this star's career.

![alt text][overview]

[overview]:/visualizations/overview.png

Here you can see every attempted shot Kobe Bryant had made throughout his time in the NBA, obviously in Laker colors. Gold marks are misses, and purple represent successful field goals.

Continuing from the overall view, I had begun EDA in the hopes of receiving a better understanding of the relationships held within the data.

### The following serves as a few examples from the Jupyter Notebook itself:

#### Shot/Action Type 

![alt text][action_type]

[action_type]:/visualizations/actiontype_distribution.png

#### Shot Distance 

![alt text][shot_dist]

[shot_dist]:/visualizations/bivariate_shotdist_scoreflag.png

#### Shot Zone

![alt text][shot_loc]

[shot_loc]:/visualizations/shot_zone_area.png

### I had also created a few features that would better predict shot accuracy

The most significant of these was shot angle, which I had created by calculating the degree Kobe attempted a fieldgoal from based on the hoop and sideline.

#### These should serve as a helpful visual:

Here are all of the attempted shots again, only this time our point of view is from the net's perspective.

![alt_text][ex1]

[ex1]:/visualizations/shot_angle_creation.png

Now we focus on one

![alt text][ex2]

[ex2]:/visualizations/shot_angle_example.png

Once we plot these points, we can calculate the distance between these two vectors and end up with our angle. 

#### Below is a visual demonstrating this principle en masse:

![alt text][angle_vis]

[angle_vis]:/visualizations/shot_angle_visualized.png

### We've run through most of my EDA and feature engineering; next up is the modeling. If interested, please view the Jupyter Notebook itself. 
