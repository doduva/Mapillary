# Mapillary
Feature Extraction

In some cases, 51% only of the Image Segmentation elements were recognized, 
leaving substantial portions out. 
For example, in this image (b8lnX0wIbI0Sn58c9Qk9ba), 
the Road element was neglected, accounting for 25 % of the whole photo. 
Strangely, asking only the Road feature gave the correct result. 
I suppose the reason is that the system computes 100 features per request, 
even with pagination. This number sometimes included a minor bit of images, 
which brings the count to 100, before completing all the features. 
Using a simple python algorithm I got only 100 feature. Why?


