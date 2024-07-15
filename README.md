# Computer Vision
This is a repo showing projects with computer vision Implementation done in Kaggle for free GPU usage, however, they are posted here because of few saving issues

## Insight on the Repo

The dataset given by Kaggle showcases images concerned with the face expression of people 

### Dataset Issues:

The first trial was done by using 6000 random images it shows that there are class imbalances and therefore the second strategy in trial 2 is to pick a good number that will showcase a balance between classes.

## Models Used and their issues

1. ViT: judging from the confusion matrix, some classes weren't identified , ViT requires a high number of data that wasn't represented in this project
2. ResNet50: ResNet50 is one of the most used and widely recognized CNN. It is a pretrained model used for tasks requiring high accuracy. the accuracy achieved is 41%
3. Due to memory errors: NasNet wasn't applied
4. Instead a CNN that was applied similar to NasNet was used but wih little accuracy of 31%

## Solution:
1. Identified a CNN for 62% accuracy 
