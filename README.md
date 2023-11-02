# Real-Time Face Mask Detector 

# Problem Statement

India has been fighting the COVID-19 pandemic since 30 January 2020 when the first case of COVID-19 was reported. With  the  Unlock  4.0  phase  set  to  begin  in September, the need to be proactive is now more than ever. The objective is to create a Real-Time Face Mask Detector which can solve monitoring issues in crowded areas  such  as  Airports,  Metros,  etc.  using CNN  and OpenCV.

# Dataset Description

The dataset is an artificial set of face mask images
•Total Images: 1376
•with_mask images: 
•without_mask images:
The goal is to create a Deep Learning model to detect in real-time whether a person is wearing a face mask or not.

# Tasks to be performed.

As a part of this project, we will be performing the following tasks:•Prepare a detailed Python notebook using CNN for detecting Face Masks in Real-time.

•Import Required Libraries -
   Hint: TensorFlow, NumPy, etc.
  
•Load and Pre-process the dataset -
  o Pre-process the images present in the dataset using the TensorFlow preprocessing module.
  o Encode the categorical data using an encoder of your choice because Machine Learning algorithms can only understand numerical data
  o Split the data into training and testing sets using sklearn’s train_test_splitfunction
     Hint: Use ImageDataGenerator to perform data augmentation
•Visualize the images present in the dataset•Design a Convolutional Neural Network (CNN) Model using AveragePooling2D, Flatten, Dense, and Dropout layers.
     Hint: Use MobileNetv2 as the base model•Compile the Model using Adam optimizer, Binary Crossentropy loss, and accuracy metric functions
• Train the Model for 30 epochs
     Hint: Use EarlyStopping Callback to terminate the training if there is no improvement in the monitor performance measure of your choice at certain epochs in a row
     (Note: If you do not define the number of epochs, the model will only train for 1 epoch)
• Plot the training history using the Tensorflow History object returned by the model.fit
   o Make a plot for the loss function to visualize the change in the loss at every epochoMake a plot for the accuracy metric to visualize the accuracy at every epoch•Evaluate the Model using the model.evaluate method
•Save the Entire Model using model.save
     (Note: To save the entire model including the model’s architecture, weights, and training configuration, you must use the model.save method. If you only want to save the weights of a model, you can use the 
      model.save_weightsmethod)
•Now that you have trained the model, test it using a webcam using OpenCV, and detect the Face Masks in real-time.



