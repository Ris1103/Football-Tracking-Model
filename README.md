# Football-Tracking-Model
 A deep learning model trained on YOLOv8 to track football's movement.
 ![Screenshot 2023-07-14 203907](https://github.com/Ris1103/Football-Tracking-Model/assets/82215717/5137ce67-3a2d-43c9-9de3-a8e644c1a941)
 ![Screenshot 2023-07-14 203934](https://github.com/Ris1103/Football-Tracking-Model/assets/82215717/9cc8d473-19be-4102-8cb2-a8db413e3a74)

# Downloading the Dataset
 The dataset can be downloaded by running the commands from the commands.txt file in the terminal while in the root directory and by following the instructions.

# Annotating the data
 To annotate the data, we can either download the annotated image or we can even do it manually using open image annotations platforms like 
 CVAT(https://www.cvat.ai/).

# Training the model
 Once requirements are met, run the train.py file on fewer numbers on epochs(eg: 1 0r 2) to check for any errors. Once resolved, run the file on more than 50 epochs for good accuracy and deep training.

 # Tracking the ball
 Using the trained model, run predict.py on the video of choice.
