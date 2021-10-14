# projects_notebook

https://github.com/udacity/sagemaker-deployment

https://github.com/udacity/DSND_Term2/tree/master/lessons/ObjectOrientedProgramming

https://github.com/aws-samples/aws-deepcomposer-samples


> Machine Learning workflow review
The machine learning workflow contains several steps first introduced in Lesson 2. Let's briefly review the different steps and how they relate to the AWS DeepLens project.

1. Define the problem.
Using machine learning, we want to improve how trash is sorted. We're going to identify objects using a video stream, so we identify this as a computer vision–based problem.
We have access to data that already contains the labels, so we classify this as a supervised learning task.
2. Build the dataset.
Data is essential to any machine learning or computer vision–based project. Before going out and collecting lots of data, we investigate what kinds of data already exist and if they can be used for our application.
In this case, we have the data already collected and labeled.
3. Train the model.
Now that we have our data secured for this project, we use Amazon SageMaker to train our model. We cover specifics about this process in the demonstration video.
4. Evaluate the model.
Model training algorithms use loss functions to bring the model closer to its goals. The exact loss function and related details are outside the scope of this class, but the process is the same.
The loss function improves how well the model detects the different class images (compost, recycling, and landfill) while the model is being trained.
5. Use the model.
We deploy our trained model to our AWS DeepLens device, where inference is performed locally.
