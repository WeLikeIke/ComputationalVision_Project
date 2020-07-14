# ComputationalVision_Project
 Arezou Ranjbarpour Maralani, Lorenzo Tibaldi and Momina Sajid submission for the Computatinal Vision exam

 The project is about Exploring Image Embeddings, Transfer Learning, Fine Tuning of the models, 3D Visualization of Intermediate Features and using Silhoutte Score.
 
 The code was developed in Python on Google Collaboratory using mainly the Keras library, an additional Jupyter Notebook was used for the 3D visualization since the Google Collaboratory Visualization cannot be interactive.
 
 The repository provides all the code, the dataset as 2 compressed .zip files that need to be extracted and combined into 1 and the LaTeX files used for the report.

 ## How to use
  The file "Ranjbarpour_Tibaldi_Sajid_Computational_Vision.ipynb" needs to be uploaded to google drive while the file "Post_visualization.ipynb" must be opend with Jupyter Notebook.
  
  During execution of the main code, one cell will ask which file to upload, at this point a .zip file that contains both "CV_train" and CV_test" has to be selected.
  
  To note that the .zip file name MUST start with "CV", We would've provided the exact .zip file we used but GitHub blocks the uploads of files bigger than 100MB.
  
  Just extract both "CV_train.zip" and "CV_test.zip" and then put the 2 extracted folders in a new .zip file, ours was named "CV_Animals.zip".
  
  What each cell does is written on a comment at its beginning, those should guide you in their executions.
  
  Lastly the code will save 3 .npy files that contain the data for the visualization, just download them and place them in the same folder as the "Post_visualization.ipynb" file.
  
  At this point it will be possible to run the code in the Notebook and look at the data interactively.
  
  To note that even with only 2600 points the interactive window lags tremendously.
  
 ## Resources
  Link to the original dataset: https://www.kaggle.com/andrewmvd/animal-faces
  
  All the images used for the report got downloaded directly from the notebooks.
