# Violence Detection 

A violence detection classification model with Convolutional Neural Network to classify violent images.
It was created for Computer Vision assignment, with the aim of classifying violent images automatically
from social media to **save** human moderators' sanity. 

Many thanks to [Dr Zampoglou](https://scholar.google.gr/citations?user=YNFYlTgAAAAJ&hl=en), [@markzampoglou](https://github.com/markzampoglou) and [Dr Papadopoulos](https://scholar.google.gr/citations?user=GuhyORoAAAAJ&hl=en), [@kleinmind](https://github.com/kleinmind)

Dataset from research paper: [A Web-Based Service for Disturbing Image Detection](https://link.springer.com/chapter/10.1007/978-3-319-51814-5_37)



## Problems with the model
:arrow_right: Overfitting problems

:arrow_right: Inadequate pre-processing for the images

:arrow_right: Model built is not domain specific and not fine tuned for the problem



## Thoughts on project
This was done in my first semester in Taylor's University with no prior knowledge to data science and machine learning.
I had a lot of trouble while doing this project because it was too deep and there was no learning curve that I could follow
as there was a lack of time.

The model is really bad and can not be even used for real life classification. the model was found to always predict non-violence
even though violent images were inserted. 

Many things was wrong since the beginning of the project such as the lack of dataset that was available for the project domain. 
Lack of knowledge of the module overall was also a problem because I was overwhelm with information that I do not know where to start.

In future, I would like to make this better with implementing proper pre-processing techniques and feature extraction and maybe try on different model such as SVM as done by previous researchers who provided the dataset. 
