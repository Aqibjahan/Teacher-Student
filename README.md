# Steps:
  
  1_Separate train_val_test (No Resizing).ipynb will split the images into train, validation and test images.
  
  2_Separate train_val_test (Resizing).ipynb will split the images into train, validation and test images with resizing the images.
  
  3_Train Teacher Model.ipynb will train the teacher model from the processed images.
  
  4_Student Model.ipynb will train the student model.
  
  5_Get Logits from Teacher Model.ipynb will extract logits from the teacher model.
  
  6_Distilled Student Model.ipynb is the distilled model where the logits from the Teacher Model have been used in order to get an improved     accuracy.
