# ECS 271 - Group Project
Group Project for ECS 271. Collaborators are Elnaz Akherati, Stephanie Lew and Jared White. The project looks into classifying image emotions based on their facial landmarks. 

For this project we plan to implement a number of machine learning techniques. Some that we have planned are k-Nearest Neighbors, SVD Based Classification and Perceptrons. Additionally, we would like to create a small feedforward neural network trained on the landmark coordinate data. 
- k-Nearest Neighbors: Stephanie Lew
- SVD Based Classification: Jared White
- Perceptrons: Elnaz Akherati

Each model's performance will be evaluated in terms of their accuracy of classification, interpretability of results, and their computational efficiency. We would also like to introduce a measure of overall prediction confidence, where we will convert the predictions of each test result into a probability density function, with which we will measure the entropy. We do this because we would like some measure on the overall confidence in our models predictions in addition to its accuracy. 

The dataset we used for this project can be downloaded from here:  [478-Point Normalized 3D Facial Landmark Dataset](https://www.kaggle.com/datasets/psewmuthu/optimized-video-facial-landmarks)

# Deliverables

- A comparative analysis of classical vs. neural network models on landmark-based emotion recognition. 
- An overall metric of classification prediction confidence, which would be given by the sum of all the entropies divided by the total possible entropy. 
- A verdict on the effectiveness and validity of utilizing facial landmarks as a method to classify human emotions.
- A final report and recorded presentation summarizing the methodology, results, and potential applications of landmark-based facial recognition. 

Using the results from each of our models, we will determine whether or not the models would prove efficient in classifying emotions based on facial landmarks. Additionally, we would like to answer whether or not facial landmarks are an effective strategy to interpret human emotions. 
