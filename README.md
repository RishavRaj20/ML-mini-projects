# [Machine Learning Projects](https://github.com/RishavRaj20/ML-mini-projects/tree/main)
Machine Learning mini-projects for students

Machine learning, a field experiencing rapid growth, possesses the potential to revolutionize our lifestyles and professional landscapes. As a computer science engineering (CSE) student, you possess the unique opportunity to delve into this dynamic realm through engaging in mini-projects. Such endeavours not only provide practical experience but also facilitate skill development. Presented below are some of the finest machine learning mini-project ideas tailored for CSE students.

The following are exemplary mini-projects that illuminate diverse facets of machine learning:

# 1. [Image Classification:](https://github.com/RishavRaj20/ML-mini-projects/tree/main/Image%20Classification)
In this project, the goal is to construct a model proficient in categorizing images into distinct classes, such as distinguishing between cats and dogs. This undertaking offers invaluable insights into image processing techniques and the application of various machine learning algorithms.

Get a crash course on convolutional neural networks, and then build your own image classifier to distinguish cat photos from dog photos

## Prerequisites
Machine Learning Crash Course or equivalent experience with ML fundamentals

Proficiency in programming basics, and some experience coding in Python

## How Image Classification Works
Image classification is a supervised learning problem: define a set of target classes (objects to identify in images), and train a model to recognize them using labeled example photos. Early computer vision models relied on raw pixel data as the input to the model. However, as shown in Figure 2, raw pixel data alone doesn't provide a sufficiently stable representation to encompass the myriad variations of an object as captured in an image. The position of the object, background behind the object, ambient lighting, camera angle, and camera focus all can produce fluctuation in raw pixel data; these differences are significant enough that they cannot be corrected for by taking weighted averages of pixel RGB values.

![image](https://github.com/RishavRaj20/ML-mini-projects/assets/81917305/5a2b6bb6-b360-42c2-b04b-b11d3719cd86)


 Figure 2. Left: Cats can be captured in a photo in a variety of poses, with different backdrops and lighting conditions. Right: averaging pixel data to account for this variety does not produce any meaningful information.

To model objects more flexibly, classic computer vision models added new features derived from pixel data, such as color histograms, textures, and shapes. The downside of this approach was that feature engineering became a real burden, as there were so many inputs to tweak. For a cat classifier, which colors were most relevant? How flexible should the shape definitions be? Because features needed to be tuned so precisely, building robust models was quite challenging, and accuracy suffered.

# 2. [Twitter Sentiment Analysis](https://github.com/RishavRaj20/ML-mini-projects/tree/main/Twitter-Sentiment-Analysis)

![image](https://github.com/RishavRaj20/ML-mini-projects/assets/81917305/9750a479-7d70-41db-a8d1-e8f873bfa778)


## What is sentiment analysis? 

Sentiment Analysis is the process of ‘computationally’ determining whether a piece of writing is positive, negative or neutral. It’s also known as opinion mining, deriving the opinion or attitude of a speaker. 

## Why sentiment analysis?

Business: In marketing field companies use it to develop their strategies, to understand customers’ feelings towards products or brand, how people respond to their campaigns or product launches and why consumers don’t buy some products.
Politics: In political field, it is used to keep track of political view, to detect consistency and inconsistency between statements and actions at the government level. It can be used to predict election results as well!
Public Actions: Sentiment analysis also is used to monitor and analyse social phenomena, for the spotting of potentially dangerous situations and determining the general mood of the blogosphere.
