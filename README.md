# Freckle Data Engineer Challenge
An open data engineering challenge based on real location data. Each entry in this data set is a "location-event". The idfa is the unique identifier of the user.

The expectation for this exercise is that you use Spark 2.x with Scala, Python, or Java. You can use the RDD or Dataframe APIs as you see fit, but please be ready to explain your choices. You must do your work over the entire dataset.

**Instructions:**

1. Fork this repo with your own id for our review.
2. Answer: What is the max, min, avg, std dev for the location-events per IDFA?
3. Produce geohashes for all coordinates in a new RDD or DataFrame
4. Using the geohashes, determine if there clusters of people at any point in this dataset. If so, how many people and how close are they?
5. Write any findings into a local parquet format file for later use. 
6. *Bonus*: Conduct any additional analysis that might give a hint about the behaviour of the IDFAs in the data set.
