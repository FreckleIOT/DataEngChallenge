# Freckle Data Engineer Challenge
An open data engineering challenge based on real location data. Each entry in this data set is a "location-event". The idfa is the unique identifier of the user.

The expectation for this exercise is that you use Spark 2.x with Scala, Python, or Java. You can use the RDD or Dataframe APIs as you see fit, but please be ready to explain your choices. You must do your work over the entire dataset.

**Instructions:**

1. Fork this repo with your own id for our review.
2. Download the dataset here: https://s3.amazonaws.com/freckle-dataeng-challenge/location-data-sample.tar.gz
3. Answer: What is the max, min, avg, std dev for the location-events per IDFA?
4. Produce geohashes for all coordinates in a new RDD or DataFrame
5. Using the geohashes, determine if there clusters of people at any point in this dataset. If so, how many people and how close are they?
6. Write any findings into a local parquet format file for later use. 
7. *Bonus*: Conduct any additional analysis that might give a hint about the behaviour of the IDFAs in the data set.

Please complete as much of the assignment as you have time for. How long you had time to spend on the challenge and your experience will be considered. Have some fun with it!
