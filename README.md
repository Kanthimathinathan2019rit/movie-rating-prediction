# MOVIE-RATING-PREDICTION
A machine learning model used to predict IMDB movie raing based on score matchbox recommender.
# PROJECT DESCRIPTION
By updating the entire status of each movie database,we can predict the movie decision accordingly.so that one could predict which movie is mosted rated.if the movie's viewer count is increasing then the movie review will increases which will be more useful for a new user.this model not only helps the fresh user,it also helps in reducing the man labour
work.
# AZURE SERVICES USED
Azure machine learning studio is used to create, train and evaluate the machine learning model. In Azure machine learning portal, select or import a dataset for the model. After uploading the dataset as CSV file, then select the blocks for the model and then connect and visualize the blocks. The final output will be visualized in the evaluated model
# MOVIE RATING PREDICTION MACHINE LEARNING MODEL
![module](https://user-images.githubusercontent.com/89577329/152141661-98e0c29c-7367-45b0-90d7-ca41c9f25ce1.PNG)

# MOVIE RATING PREDICTION DATASET
![dataset](https://user-images.githubusercontent.com/89577329/152141894-1e6b08ca-3066-4223-b346-0f6446d36b83.PNG)
# TRAINED MODEL
![trained model](https://user-images.githubusercontent.com/89577329/152142117-ce813981-6826-44f6-a443-77da1d94bea2.PNG)

# SCORE MODEL RATING PREDICTION
![score model rating prediction](https://user-images.githubusercontent.com/89577329/152142289-7106f17d-11d9-45dd-900d-50b0c3b28197.PNG)

# SCORE MODEL FROM RATED PREDICTION
![score model from rated prediction](https://user-images.githubusercontent.com/89577329/152142430-233fb297-ce7e-40dc-9e9a-fe00a393674c.PNG)

# EVALUATED MODEL FOR RATING
![evaluated model rating](https://user-images.githubusercontent.com/89577329/152142637-f4350299-e405-4cc3-b6c9-c2463c3a0a0c.PNG)

# EVALUATED MODEL FROM RATED PREDICTION
![evaluated model from rated prediction](https://user-images.githubusercontent.com/89577329/152142759-eeb99db4-f0dd-4e4a-9a86-475742c7f8ba.PNG)

# DETAILED DESCRIPTION
Create Project/Experiment and import movie rating data set from saved dataset samples. After creating experiment, we need to drag and drop the required modules in canvas.

I have used the below modules for my experiment in the given order:
 # DATA SET:
       Data set required for experiment is added
       
 # IMDB MOVIE TITLES:
       This data set consists of movie id and movie names.
 # Editing Metadata:
       Used to change data type of fields, etc.
 # Join data:
       Used to join the above two dataset.
 # Select column in dataset:
       Select columns to inclue or exclude from a dataset in an operation.formerly known as project columns.
 # Remove duplicate rows:
       Remove the duplicate rows from a dataset.
 # Split data:
       split the rows of a dataset into two distinct areas,here the dataset is splitted into Train and Score matchbox recommender.
 # Train matchbox recommender:
       Train a bayesian recommender using the matchbox algorithm.
 # Score matchbox recommender:
       It scores a dataset using matchbox recommender.
 # Evaluate recommender:
       this is the final dataset it evaluates and gives the accuracy values 
       this evaluate recommender is used to evaluates a recommender model.
       
 After creating, run the model by clicking run button in the bottom side. After running successfully, we can score and evaluate the model.  
 
# Deploying the model:
Deploy the model by Setting up Web Service in ML Studio. For first time select Update Predictive Experiment. after deployment of model, it can be used in webs.

    Web Service Consumption options:

         Excel 2010 or earlier
         Request-Response Web App Template
 
