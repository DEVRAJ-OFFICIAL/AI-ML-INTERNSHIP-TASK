Here i am making a Task 1 that's a data Cleaning and Preprocessing for a making a Machine Learning Model, So this is for making a raw data that we can Give to our model. 

So, Data Cleaning includes a finding a null columns and fill it wit the help of a pandas we can drop it or fill it with the help of this.

So, preprocesing includes a 3 Encoding Techniques and a 2 Scaling techniques.

Ordinal Encoding is haivng use for a data with str values fill in a feature and in that also our value is a in order or we cansay that our data has more that 2 values counts as per me and one thing keep in mind it is for 2 dim data.

LabelEncoding :- it is a encoding, i am usin g this for a target columns and it is only suitable for a q dim data.

OnehotEncoder :- It is a a technique where only we have a two value count column because for every value count it make a new column that's bad point for it.

For Scaling we have 

MinMaxScaler & StsandardScaler = In that we will use this for making a columns scale downgrade because we don.t want any dominancy of a feature in a model, so we use it for basially a classifivcation problem, because it has a main DIffrences from a standard that makes a diffrence the mean and std for MinMaxScaler not make it a mean 0 and std 1 but the standard-scaler make out data mean 0 and std 1, and for a guassain distribution follows data must want a std 1 and a mean 0. 

Simpleway :-  MinMaxScaler lies between a 0 to 1 and a standardScaler lies between a -1 to 1 .. Big Difference.