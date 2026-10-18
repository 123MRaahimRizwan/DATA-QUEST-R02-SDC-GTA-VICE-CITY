## GTA Vice City Self Driving Simulation.

- Hi Everyone, Welcome to the Round 02 of the Data Quest Hackathon.

- In this dataset you guys have to predict the controls of the self driving car in four columns i.e. W, A, S, D which are binary encoded, i.e. 1 represents activation and 0 represents non-activation.

- You guys have to train your models on the images and generate the submission files and a simulation file.

## Dataset Description and Flow

You guys have a csv file named `train.csv` in which there are two things
- Filename
- Labels (W, A, S, D)

You guys have to make a CNN model or any other model which you like which is trained on the training data and evaluated on the testing images. Now in this scenario you also have to do the preprocessing of the training images, in order to obtain a cleaned dataset.

Furthermore, after you have the model ready you have to test this model in making a simulation based on the module `pygame`. The criteria is that whichever model performs the best in the simulation, wins the challenge :)

Happy Hacking :)


## How to Submit?

You have four fields given,
- Model Upload field -> upload the zipped model file.
- Simulation file -> .mp4 video of the simulation (or a simulation.py with video's google drive link)
- Submission csv file -> submission.csv containing the predicted labels.
- Python files -> The whole zipped project of your python files.
