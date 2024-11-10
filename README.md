# Bakers Hughes

## Selections
- Kmeans, centroid based
- BIRCH, works better on large sets vs kmeans

## Evaluation
plots orginal data set finds the max and minimum distances and the standerad variation of the diffrences between eveypoint in the orginal data set and its clustered paired.

## Process
### V1
Started with multiple models several clustering models such as kmeans, spectural, BIRCH, OPTICS, DBSCAN, FeatureAgglomeration, kmeans_plusplus, and affinity_propagation. As well as clustering using KDE's.
### V2
due to long load times and trouble evaluting centers point and cluster indices the pool of vibal methods was reduced too. kmeans, spectural, OPTICS, BIRCH, DBSCAN, and KDE + kmeans.
### V3
Due too lack of time the pool was reduced kmeans and BIRCH as well as a layered clustering method mixing the two models.

## Finals Notes
- Birch accurracy improves with lowered threshhold hovever it also raise compute time.
- Nothing to found on kmeans random seeds.
- Layered model clustering ratio could see improvements. 