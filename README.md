Prediction API

This folder is for the prediction api that will take in an image 
as input and output a anomalies classification for the given image.

There are two main parts of this API:

1. Model Registry  
    Status:
    Currently not implemented other than a class for handiling model upload in the main raptor repo
    
2. Prediction API  
    Status:
    Currently can be deploy to EC2 and be called through port 80 with nginx. However, it is only http and thus can't be called by the react website

The end goal of this module is to have an secure api for making prediction with the models developed from the model development module/folder. (The website may be ran from this service as well for a more secure connection to it)
