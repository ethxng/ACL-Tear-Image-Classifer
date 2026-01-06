# ACL-Tear-Image-Classifer
Using a publicly available dataset [(link)](https://zenodo.org/records/14789903) containing MRI images of the knee, we pre-processed the data and attempted to use Resnet-50 to detect ACL tears from these images. We were able to achieve an accuracy of about 85%. However, the recall rate of <60% suggests there might be some additional fixes to be done such as diversifying our dataset, sources, etc. 

In addition, we implemented U-net to extract Region-of-Interests (ROI) from each MRI volume, achieving a final DICE score of 88.6/100 on the test set. The purpose of this objective is to eliminate the manual annotation that comes with this dataset, which is often time and effort-intensive. 
